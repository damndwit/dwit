# Six portfolio projects: implementation roadmap

All six can begin as free, local demonstrations. Avoid paid APIs, private patient data, and client advertising credentials. Before copying any upstream code, verify the exact repository license and preserve required notices.

## 1. AI Support Copilot — AI / prompt engineering
**Reference:** [Streamlit LLM examples](https://github.com/streamlit/llm-examples) and [Promptfoo](https://github.com/promptfoo/promptfoo) for learning about evaluations.

- Build a Streamlit chat interface with a small set of public or self-written troubleshooting articles.
- Start with a simple document search and rule-based answers; optionally add a locally running model (Ollama) after the baseline works.
- Write 20 example questions, expected answers, and prompt tests; add a comparison table for prompt changes.
- Show retrieval sources, limitations, screenshots, and evaluation results.
- **Resume proof:** Working demo, tests, and measurable evaluation on a clearly defined sample.

## 2. Healthcare Data Explorer — healthcare and Python
**Reference:** [Synthea](https://github.com/synthetichealth/synthea), a synthetic patient generator.

- Generate fictional patients and encounters locally, or use sample generated data.
- Convert selected synthetic records to a CSV for use in a Streamlit dashboard.
- Add patient-demographic distributions, encounter summaries, and simple data-validation checks.
- Document that the records are synthetic and not for clinical decisions.
- **Resume proof:** Reproducible processing pipeline, screenshots, checks.

## 3. Windows IT Diagnostic Toolkit — IT support
**Reference:** [WinUtil](https://github.com/ChrisTitusTech/winutil), to study common Windows support workflows.

- Write an original read-only PowerShell script for OS version, disk, memory, network, and service status.
- Add a console menu and export-to-HTML/CSV option.
- Test on your own Windows machine or VM; save sanitized output.
- Document errors, access requirements, and safety (no destructive changes).
- **Resume proof:** Working script, before/after troubleshooting test, instructions.

## 4. Local Ads Performance Dashboard — business and analytics
**Reference:** [Streamlit](https://github.com/streamlit/streamlit) and Google Ads CSV exports/documentation.

- Create a small synthetic CSV of campaigns, spend, clicks, impressions, conversions, and revenue estimates.
- Calculate CTR, CPC, conversion rate, and cost per conversion; use meaningful zero-denominator handling.
- Add filters by campaign, month, and business, plus downloadable reports.
- Add insights based on transparent rules, not invented client outcomes.
- **Resume proof:** Interactive business dashboard, tests for formulas, sample exports.

## 5. Stock Research Dashboard — finance / data engineering
**Reference:** [yfinance](https://github.com/ranaroussi/yfinance).

- Build a Streamlit app for manually uploaded stock price CSVs first.
- Add price, volume, moving averages, drawdown, and a two-symbol comparison.
- Optionally integrate yfinance with network/data-use disclosures; show data freshness.
- Include errors for missing data, tests, and a non-investment-advice note.
- **Resume proof:** Working visualizations and transparent calculations.

## 6. Full-Stack Project Tracker — software engineering
**Reference:** [Full Stack FastAPI Template](https://github.com/fastapi/full-stack-fastapi-template).

- Begin with an isolated FastAPI backend, a SQLite database, and a few REST endpoints; add a small frontend.
- Implement task create/edit/complete, search, and tests.
- Add authentication and move to a richer template only if needed.
- Write API documentation, a simple architecture diagram, and a demo video.
- **Resume proof:** Tested CRUD application, code structure, CI or basic test automation.

## Publishing standards

Each completed repository should include a descriptive name, project purpose, setup steps, license, screenshots, examples, tests, and an attribution section when based on upstream code. Only pin a project when the code runs and you can explain it.
