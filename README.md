# ST

I've built and run companies, raised capital and done cross-border acquisitions.
I've worked inside global technology companies, alongside venture funds and
founders, and as a CEO responsible for making the whole thing work.

I still work on fundraising, M&A and advising businesses. I'm also building
software with AI. Mostly things I want to use myself: family finances that are
scattered across accounts, meetings I don't want to lose track of, and years of
documents that should be easier to find and make sense of.

The tools here come out of those problems. I work on what they should do and
keep testing them against what I actually need. AI coding tools write the code.
Some of it works well, some is still being figured out. I'm sharing the useful
parts as they become ready.

## What I'm working on

| Project | Why it exists | What you can get here |
| --- | --- | --- |
| [MoneyMoney](https://github.com/St-Gonne/moneymoney) | Help my family see what we own, where the numbers come from and what's missing. Includes a simpler view being built for my dad. | Current Clarity source, a runnable local demo with invented data, screenshots and specific contribution issues. Real-data self-hosting still needs work. |
| [MeetingIntel](https://github.com/St-Gonne/meeting-intelligence-system) | Turn private recordings into notes, follow-ups and a daily brief. | Application source, a model-free inbox demo, terminal instructions and lessons from use. Real-model setup is still an early contributor path. |
| [Voice ID](https://github.com/St-Gonne/meeting-intelligence-system/blob/main/docs/VOICE_ID.md) | Suggest who spoke, with a person confirming the match and choosing what to retain. | A separate module inside MeetingIntel, a runnable synthetic lifecycle demo and calibration work to help with. |
| [ExtractCheck](https://github.com/St-Gonne/extractcheck) | Find what a document extractor lost before trusting search built on top of it. | An offline, runnable benchmark using generated documents. |
| [AI Chief of Staff](https://github.com/St-Gonne/ai-chief-of-staff) | Keep commitments and context across conversations instead of starting again each time. | Design notes, templates and a small script. |

ExtractCheck and the phone-ingestion toolkit use Apache-2.0. MoneyMoney,
MeetingIntel application code and Voice ID use MIT, including commercial reuse. Older
architecture documents have their own terms. Real financial records, recordings and
personal context stay private.

If you're working on a similar problem, a specific bug, an independent run or a
small improvement is useful. Useful places to start are [MeetingIntel setup and accuracy](https://github.com/St-Gonne/meeting-intelligence-system/issues),
[Voice ID calibration](https://github.com/St-Gonne/meeting-intelligence-system/issues/9),
and [MoneyMoney usability and performance](https://github.com/St-Gonne/moneymoney/issues).
The demos use invented data. You do not need access to my setup to try them.
