# The skills I use before automating

Companion to Jonathon Perez's video, **I Gave Claude Elon's 5-Step Algorithm**.

[Download the skills ZIP](https://github.com/jonathonperez/elon-ai-skills/releases/latest/download/elon-ai-skills.zip). No GitHub account is needed.

Unzip it and follow the setup instructions below.

## What you get

- `elon-company-building/`: the actual skill from my setup, exported with its supporting chapters. It draws on David Senra's Founders Podcast episodes, How Elon Works and How Elon Thinks. These are study notes and summaries, not an official Elon Musk product or endorsement. Podcast-derived quotations were not independently verified against the books.
- `grill-me/` and `grilling/`: Matt Pocock's skills, copied from his public repository with the MIT licence. Keep both: grill-me calls grilling. His name and licence remain with his work.

## Use it in Claude Code

1. Unzip this pack.
2. Copy the three skill folders into your own project's `.claude/skills/` folder. Each folder must retain its `SKILL.md` file. Keep the Elon skill's chapters and supporting files beside its entrypoint.
3. In Claude Code, open that project. Use the slash-command menu to confirm that the skills are available. Follow any workspace trust or organisation policy your setup already uses.
4. At the interactive prompt, try the example below. Start with a process you understand and can change reversibly.

Claude Code's current skill documentation supports project skills in `.claude/skills/` and stacking skill names at the start of an interactive message. These instructions are for local Claude Code, not an assertion that the same folder automatically loads in every Claude app or ChatGPT.

## First prompt

```text
/elon-company-building /grill-me

I want to improve this process: [describe the process in your own words].
The result I need is: [describe the outcome].

Question my assumptions before proposing anything to build. Use the five
steps in order: question the requirements, delete what is unnecessary,
simplify what remains, make it faster, then consider automation.

Use the questioning skill to clarify decisions with me. Read the relevant
project files for facts where I have already granted access. Explain what
could break before proposing a deletion. Return a simpler plan for review.
Do not implement, delete files, deploy or change live data in this exercise.
```

The two bracketed lines are where you describe your own work. This prompt is a suggested way to begin, not a claim that I spoke these exact words in the video.

## If you use an ordinary chat

You can also paste the five-step method into a conversation and ask the AI to question one process before proposing changes. That is a prompt-based adaptation, not an installed skill. Keep private information out of any service you have not approved for it.

## How I judge the answer

Did it understand the outcome? Which steps earn their place? What can I remove? What is the simplest version worth doing? What evidence would tell me automation is worthwhile?

This is a thinking aid. It does not guarantee faster delivery, correct advice or a better product. Keep responsibility for decisions and preserve the existing approval boundaries in your own tools. My productivity comments in the video describe my personal experience, not a measured benchmark.

## Sources

- Matt Pocock's repository: https://github.com/mattpocock/skills
- Grill-me: https://github.com/mattpocock/skills/tree/main/skills/productivity/grill-me
- Its required grilling skill: https://github.com/mattpocock/skills/tree/main/skills/productivity/grilling
- Claude Code skills documentation: https://code.claude.com/docs/en/skills

This is a download for viewers. It contains no credentials, personal-machine setup, client records, or access to my projects.

Matt Pocock's files are pinned to revision `4ae2317ddb22b046e26455e4f9c9b3aaaf62212d`. Their MIT licence is in [MATT-POCOCK-LICENSE.txt](MATT-POCOCK-LICENSE.txt).
