# Daily Operations Assistant
*Built in Microsoft Copilot Studio*

## The problem
I was starting every day reactively — opening email, getting pulled into whatever was loudest, and losing the first hour to triage. I needed a way to start with a clear picture of what actually mattered that day before anything else landed.

## What it does
Every morning, this agent runs automatically and sends me a structured briefing covering:

- **Priority emails** — flags anything from senior stakeholders or external partners that needs a response that day
- **Outstanding to-dos** — surfaces tasks that are overdue or due today, pulled from my task list
- **Meeting prep** — for any meeting in the next 24 hours, pulls the relevant context: who's attending, what was last discussed, what I need to prepare
- **Open decisions** — flags anything that's been sitting unresolved for more than 48 hours

The output arrives as a Teams message before I open my inbox.

## Why it works
The briefing format is fixed and scannable. It takes under two minutes to read and means I go into every day with a clear set of priorities rather than building them on the fly.

## Tools used
- Microsoft Copilot Studio
- Microsoft Teams (output channel)
- Microsoft To Do + Outlook (data sources)

## What I learned
Getting the output format right took longer than building the agent. The first version gave me too much information. The useful version is ruthlessly brief — one line per item, with a link to the source if I need more context.
