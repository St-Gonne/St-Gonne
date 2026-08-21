# Sharan Tulsiani

Building systems, for solving problems or annoyances, many unique, from a personal perspective. 
Family financial management, private meeting intelligence, reliable India-centric personal finance,
persistent memory and evidence-groundeddocument retrieval. I want these systems to be local-first, 
honest about what they know and useful enough to earn a place in my daily life.

I approach the work as an AI systems architect and operator. I turn messy needs into
specifications, constraints, acceptance gates and operating decisions. Codex and
Claude write the implementation under those controls. I test the behaviour, reject
what does not hold up and keep improving the system against real workflows.

I do not write the implementation code, and I do not hide that. The question I am
working on is more useful to me: how do I get systems I can trust from AI builders
when I cannot review every line myself?

These repositories show that work as it develops, including the failures that changed
the rules. Some are runnable open-source tools. Others are sanitized architecture
records because the working systems contain private meetings, finances and personal
context. The data stays private; the method and evidence can be public.

## The systems

| Repo | What it is | Public status |
|---|---|---|
| [extractcheck](https://github.com/sharantulsiani-ui/extractcheck) | An offline benchmark for finding what document extractors miss across PDF, PowerPoint, Excel and Word, with exact source provenance. | Runnable Apache-2.0 benchmark with CI |
| [meetingintel-phone-ingest](https://github.com/sharantulsiani-ui/meetingintel-phone-ingest) | A privacy-safe intake boundary for segmented phone recordings: retrieve, wait for stable uploads, prevent duplicates, review grouping and produce canonical audio. | Runnable Apache-2.0 toolkit with CI and an external contribution |
| [ai-chief-of-staff](https://github.com/sharantulsiani-ui/ai-chief-of-staff) | A permanent local memory vault operated by Claude as a chief of staff, with daily briefings, a commitment ledger and provenance rules for every claim. | Sanitized architecture, templates and one working script; private system in daily use |
| [meeting-intelligence-system](https://github.com/sharantulsiani-ui/meeting-intelligence-system) | A local meeting pipeline that turns consented recordings into speaker-labelled notes and one short daily brief. | Sanitized architecture record; private system in daily use |
| [finance-tracker](https://github.com/sharantulsiani-ui/finance-tracker) | A local-first personal finance system where statements are canonical evidence, supporting sources cannot silently rewrite them, and the maths must close before import. | Public architecture and reusable guard toolkit; private system in daily use |

MeetingIntel + Chief of Staff are connected: CoS provides context for constantly improving Diarization, notes and todos. Email, calendar access etc is part of the design.

More will land here as it passes the privacy screen. Everything real inside these systems is my actual work life, so what gets published is the system design and not my data.

## How I work with AI builders, the short version

1. I only build things I personally need everyday. Success means "I use it daily", not "it runs".
2. Constraints get written down before architecture. Privacy boundaries, my attention limits, what always needs my approval.
3. The AI works under a written contract, a control file with one active milestone at a time, clear pass criteria, and a standing rule that the file beats anything said in chat.
4. Nothing unproven touches the live system. New capability runs in parallel until it passes a gate on real cases, judged by me.
5. Every mistake becomes a written rule, with the incident that caused it attached.

And to be clear about what I do and don't do: the AI writes the code and most first drafts. I write the decisions, the constraints, the gates and the rejections. I keep those two things separate on purpose so I can focus on Architecture and Outcome.

## Contact

sharan.tulsiani@gmail.com



## License

Read it, learn from it, share it with credit. Not open source though: no commercial use and no modified redistribution without permission. Details in [LICENSE.md](LICENSE.md).
