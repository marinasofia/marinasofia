# Marina Martin

**Data and AI builder in New York.** I build machine learning and LLM systems end to end and trust a number only after I have tried to break it. BBA in Computer Information Systems with a minor in Computer Science, graduating 2027. Data analytics experience at Columbia University Irving Medical Center, an M&A advisory firm and the NYC Tech Talent Pipeline.

Open to data, AI, analytics and product roles starting spring 2027.

**[Portfolio](https://marinasofia.github.io/)** · [Plain text version](https://marinasofia.github.io/lofi.html) · [LinkedIn](https://www.linkedin.com/in/marinasofiaml/)

My portfolio is a New York subway car. Ride it to each project and read the poster on the platform.

<a href="https://marinasofia.github.io/"><img src="assets/portfolio.gif" width="720" height="405" alt="The portfolio, a subway car that rides to a station for each project, where a poster explains how it works"></a>

## Projects

- **[Sourcer](https://github.com/marinasofia/sourcer)**. Reads company job boards every morning, drops what cannot fit with explainable rules and has Claude score the rest against my own evidence, quoting it. One October run read 48,031 postings, set aside 95% before any model call and judged 150. Python, LangGraph, SQLite, 90% coverage gate, mypy.
- **[Knowledge Assistant](https://github.com/marinasofia/knowledge-assistant)**. A team asks questions about its own policies and gets the exact approved passage, both sides when two policies disagree, or a refusal when nothing covers it. 25 of 25 answerable questions answered and 10 of 10 unanswerable ones refused on a labeled set with a held out split. FastAPI, Postgres row level security, pgvector, React, 85 backend tests in CI.
- **[Statement Agent](https://github.com/marinasofia/statement-agent)**. A LangGraph agent that turns PDF bank statements into Excel and trusts a number only when the balances reconcile to the cent. 11 of 11 synthetic statements pass an offline eval that replays recorded model answers in CI, at a median cost of $0.0025 per statement.
- **[Bank Churn Model](https://github.com/marinasofia/bank-churn-model)**. Credit card churn model that turns a month of customer data into a ranked outreach list sized to a retention team's capacity, with reason codes and a fairness audit by gender and income. Test ROC AUC 0.871 with a bootstrap interval, drift gate, scikit-learn.

Also: **[sakura-terminal](https://github.com/marinasofia/sakura-terminal)**, local observability for Claude Code agents. Hooks stream every tool call into a secret masked log that a pixel art pet and a live code pane read.

## Stack

Python, SQL, pandas, scikit-learn, FastAPI, PostgreSQL, pgvector, LangGraph, Claude API, TypeScript, React, Tableau.
