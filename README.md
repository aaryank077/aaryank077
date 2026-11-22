### Hi, I'm Aaryan

I'm a student at the University of Chicago. I build low-level systems and data pipelines, mostly around questions I actually care about in sports, finance and news.

**What I've built**

- **[matchbook](https://github.com/aaryank077/matchbook)**: a limit order book matching engine in C, the core of a stock exchange. 6.5–8M orders/sec in one thread with a ~250 ns median, a checksummed write-ahead journal for crash recovery, and differential fuzzing against a Python reference model. *C, sanitizers, pandas*
- **[courtside-signals](https://github.com/aaryank077/courtside-signals)**: ask NBA stat questions in plain English and get the answer plus the table behind it. A rule-based parser turns questions into SQL over a SQLite database that fills itself from nba_api on demand. *Python, SQLite*
- **[edgar-lens](https://github.com/aaryank077/edgar-lens)**: a Spring Boot service that turns raw SEC XBRL filings into clean annual financials and a DCF valuation for any US public company. It handles tag changes, restatements and SEC rate limits. 32 tests, CI, Docker. *Java 21, Spring Boot, Postgres*
- **[Corroborator](https://github.com/aaryank077/Corroborator)**: a prototype for a breaking-news desk that counts how many truly independent sources stand behind each claim. It's backed by a claim-by-claim reconstruction of how NHK, CNN and AP covered the 2024 Haneda collision. *Product design, research*

**Now:** building the discourse engine for courtside-signals, which turns what fans argue about into questions the data can answer.

**Interests:** systems programming · data engineering · data journalism

📫 aaryank@uchicago.edu
