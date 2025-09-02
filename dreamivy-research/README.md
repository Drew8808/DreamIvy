# DreamIvy Research

This repository acts as a living knowledge base for DreamIvy.  It collects notes about tools, platforms, services and practices that support our mission.  Each tool has its own markdown record in the `radar/` directory with YAML front‑matter describing the category, purpose, maturity, cost and other metadata.  There is also a `sources/` directory for storing raw source links and excerpts, and a `scripts/refresh/` directory for scripts to automate routine research tasks.

## Repository structure

```
dreamivy-research/
├── README.md          # this file
├── radar/             # one file per tool/technology
│   └── RADAR_TEMPLATE.md  # template for new entries
├── sources/           # raw links, quotes and notes
│   └── README.md      # how to organise sources
└── scripts/refresh/   # automation scripts for periodic scans
    └── refresh.py     # placeholder for future automation
```

## Usage guidelines

* When adding a new tool, copy the `radar/RADAR_TEMPLATE.md` into a new file named after the tool (for example, `radar/n8n.md`) and fill in the front‑matter and description.
* For every citation or link used in the radar files, save the URL and relevant notes in a file under `sources/`.  This keeps the radar files focused on analysis while retaining traceability.
* Use `scripts/refresh/` to store any automation or scraping scripts.  For example, you might write a script that checks for updates on your selected tools and opens a pull request with a summary of changes.
