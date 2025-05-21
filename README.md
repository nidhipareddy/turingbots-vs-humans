# 🤖 Will TuringBots Replace Human Software Developers?

This project explores the potential for AI-powered coding assistants (TuringBots) to augment or replace human software developers by analyzing trends from over 1.36 TiB of GitHub Archive data.

## 📊 Objective
To assess whether AI coding tools meaningfully impact developer productivity, commit behavior, and the future role of human engineers in open-source software development.

## 🗂️ Dataset Overview
Data was obtained from GitHub Archive (2000–2020) and includes:
- `commits`: Metadata such as commit date, author, message, SHA
- `contents`: Commit file contents
- `files`: Metadata on file mode and blob ID
- `languages`: Bytes of code per language per repo
- `licenses`: License metadata per repo

## 🔍 Key Analyses
- Commit activity timeline and major peaks
- Most popular and fast-growing programming languages
- License usage trends across ecosystems
- Commit message uniqueness and duplication using LSH
- Frequent commit reasons: "fix", "add", "merge", etc.
- Prolific committers and their impact on open-source
- Technologies associated with AI/Data Science ("Big Data", "ML", "GenAI")

## 💡 Insights
- JavaScript leads overall usage; Python rapidly rising for AI-related work
- MIT is the dominant license, especially in JavaScript repos
- Frequent contributors are often tied to Big Tech initiatives
- Most commit messages are unique, making automation challenging
- TuringBots could automate standard commit types but not creative tasks

## 🧠 Conclusion
While TuringBots can aid in tasks like bug fixes and feature additions, the nuanced and creative nature of human commits suggests full replacement is unlikely. Instead, they serve as powerful productivity tools for modern developers.

## 📌 Tools & Libraries
- PySpark, pandas, matplotlib, seaborn
- LSH (Locality Sensitive Hashing) for similarity checks
- GitHub Archive + GCP for Big Data storage

## 📁 Repository Structure
```bash
github-turingbots-analysis/
│
├── final_project_notebook.html # Interactive analysis notebook (Spark)
├── annotated_report.pdf # Annotated final report
├── README.md # This file
