# <your name> - Applied GenAI & Agentic AI Engineering

CoreSmart.AI, cohort 2026B. One repository for every graded project from Week 1
to Week 16. The Week 17 capstone gets its own separate repository, because that
is the one a hiring manager actually opens.

## How this repository is organised

Each graded project gets its own folder, `project-NN-name/`. You work on a
branch named `week-NN-projectname`, open a pull request into `main`, and paste
the pull request URL into the Submit item in the LMS. Your reviewer merges it;
you do not.

The project folders arrive empty. Each week's starter code and test data live in
the public labs repository, https://github.com/coresmartai/labs, and that week's
brief gives you the exact commands to copy them across.

## Projects

| Week | Project | Folder | Status |
|---|---|---|---|
| 1 | ReleaseBot (guided, not submitted) | `project-01-releasebot/` | not started |
| 1 | MinuteMaker (graded) | `project-02-minutemaker/` | not started |

Add a row as each project opens.

## Setup, once

```
python -m venv .venv
source .venv/bin/activate          # Windows: .venv\Scripts\activate
```

Each project installs its own dependencies from its own `requirements.txt`.

## The one rule

Your API key lives in a `.env` file and nowhere else. `.env` is already listed
in `.gitignore` at the root of this repository.

**This repository is public**, which is deliberate: it is what you point an
employer at when the course ends, and it is how your reviewer reads your work
without anyone granting access by hand. It also means a key that reaches a
commit is scraped by bots within minutes, and deleting it in a later commit
does not help, because it stays in the history.

If you ever think you have pushed a key: **revoke it at the provider first**,
then tell us and we will help you clean the history.
