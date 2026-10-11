# AI conventions

Conventions for any AI assistant working in this repository. This file is canonical; CLAUDE.md only points here.

## About this repository

This is the professional portfolio of Marlie Goodman, a BBA in Finance student at the University of Hawaiʻi at Mānoa, Shidler College of Business (expected Spring 2027). My field is finance, and my goal is a career in financial advising. This repository holds my bio, my resume, and the work I produce across courses, organized by capability and engagement, never by course.

## Where things are

- `README.md`: my bio and engagement index (written by me)
- `RESUME.md`: my resume (written by me)
- `prompt-log.md`: the log of AI sessions that changed a file
- `capabilities/`: one folder per capability, each with `README.md`, `spec.md`, and the model file
- `docs/briefs/`: documents written before work begins
- `docs/decisions/`: recommendations written after the work
- `data/`: source data, with where it came from
- `analysis/figures/`: findings and charts

## Naming

- The directory matters most. A file in the wrong folder is harder to find. If you are not certain which folder a file belongs in, ask me
  before you write it — do not choose for me.
- Graded files use the exact filename the stage brief gives — lowercase,
  hyphens, no spaces. Dated documents are YYYY-MM-DD-slug-type.md (no name — the repo is yours);
  the stage page says so when they do.
- Slugs name the engagement, never the week, the course, or the assignment
  number.
- Never invent a path or a filename. I will give you the exact one.

## How I work

- Explain things to me step by step in plain English, with a worked example when a concept is new.
- I am the reviewer; you are the doer. You may draft, calculate, and propose; I decide what is kept.
- If something is unclear, ask me before guessing. Do not invent scope.
- Never invent facts, numbers, sources, or experience. If data is missing, leave a clearly marked placeholder and tell me.

## What you may and may not draft

- **You may draft:** folder structure, README files for folders, `.gitignore`, formatting and Markdown cleanup, spreadsheet formulas I ask for, and the prompt log entries.
- **You may not write:** my bio, my briefs, my analyses, my memos, or my reflections. I write the first draft of each. You may review them and give feedback, but you do not rewrite them. Make no changes to my bio or resume content unless I ask.

## Documentation

Every folder has a short `README.md` saying what belongs in it. Every number in my work must trace back to a source recorded in `data/`.

## Scope

Do only what I asked in this session. If you notice something else that needs fixing, tell me instead of changing it.

## Commits

Commit messages say what changed, for example "Add portfolio skeleton and gitignore", never "update". Show me every file before I commit.

## Prompt log

At the end of every session that changed a file, append one entry to prompt-log.md: the date, what I asked, what you produced, what was wrong and how it was caught. Never backfill earlier sessions and never edit a past entry.

## Never include

Never paste any of the following into an AI model, and never commit it to this repository:

- **Summer Fun program records** from my job with the City and County of Honolulu: children's names, ages, photos, attendance and sign-in/sign-out sheets, incident reports, and parents' or guardians' names, phone numbers, or emails.
- **Client financial information** from any future advising internship or job: names, account numbers, balances, Social Security numbers, tax documents, or investment holdings.
- **My own private details:** my phone number, home address, student ID, bank or card numbers, and passwords.
- **Other people's information:** classmates' names, grades, or contact information from group projects, and my references' contact details.
- **Passwords, keys, or login credentials** of any kind.

## Mistakes to avoid (append to this list)

- (none yet)
