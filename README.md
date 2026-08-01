# Sharan Tulsiani
Alright, first time on GitHub. I don't write code, always wanted to learn.. BUT! here I am now.
About me: Entrepreneur, worked in Partnerships, BD and marketing roles at Google, Microsoft. Built my own company, fundraised and just exited. Neurodivergent and building with AI is really scratching that itch

What I have been doing in 2026 is building AI systems anyway. Real ones, for me, in daily use. Followed a rule I took years to learn: Double down on strengths and delegate weaknesses. And the emergence of this type of AI allowed me a shot at doing it myself. 

So,the AI writes every line of the implementation, and I write everything else... the specs, the milestone gates, the operating rules, the reviews when something breaks etc.

These repos are that work, published as it develops. WIPs on purpose, so I can share it with people for feedback. Not aiming for polished code, as I wouldn't know what that is. Since I've been working on these,the AI's code gets better with every model release, and I'm banking on that. What I'm actually working out is a method for getting systems I can trust out of AI builders when I can't check the code myself. 

(Have used AI to help write the notes below, so it's understandable)

## The systems

| Repo | What it is | Status |
|---|---|---|
| [meeting-intelligence-system](https://github.com/sharantulsiani-ui/meeting-intelligence-system) | A PRIVATE meeting pipeline that runs entirely on my Mac locally. Takes meeting recordings from my laptop and phone (recorded with consent), transcribes them, works out who said what (diarization), and produces one short daily brief. Built by OpenAI's Codex working under a written control file. | In daily use since early July 2026 |
| [ai-chief-of-staff](https://github.com/sharantulsiani-ui/ai-chief-of-staff) | A permanent local memory vault operated by Claude as a Chief of Staff. Daily briefings, a commitment ledger, health tracking in the same system as work, and provenance rules so I always know where a claim came from. | In daily use since 5 July 2026 |
| [finance-tracker](https://github.com/sharantulsiani-ui/finance-tracker) | A local-first personal finance system. Bank and card statements become one record I can question, with hard rules: statements are truth, emails are gossip, and the math must close before anything imports. Built by Codex; the AI that wrote it can't even see my statement passwords. | In daily use since 11 July 2026 |

MeetingIntel + Chief of Staff are connected: CoS provides context for constantly improving Diarization, notes and todos. Email, calendar access etc is part of the design.

More will land here as it passes the privacy screen. Everything real inside these systems is my actual work life, so what gets published is the system design and not my data.

## How I work with AI builders, the short version

1. I only build things I personally need everyday. Success means "I use it daily", not "it runs".
2. Constraints get written down before architecture. Privacy boundaries, my attention limits, what always needs my approval.
3. The AI works under a written contract, a control file with one active milestone at a time, clear pass criteria, and a standing rule that the file beats anything said in chat.
4. Nothing unproven touches the live system. New capability runs in parallel until it passes a gate on real cases, judged by me.
5. Every mistake becomes a written rule, with the incident that caused it attached.

And to be clear about what I do and don't do: the AI writes the code and most first drafts. I write the decisions, the constraints, the gates and the rejections. I keep those two things seperate on purpose so I can focus on Architecture and Outcome.

## Contact

sharan.tulsiani@gmail.com



## License

Read it, learn from it, share it with credit. Not open source though: no commercial use and no modified redistribution without permission. Details in [LICENSE.md](LICENSE.md).
