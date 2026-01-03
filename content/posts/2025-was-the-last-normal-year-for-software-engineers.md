---
title: "2025 Was the Last Normal Year for Software Engineers"
date: 2026-01-03T10:00:00+05:30
tags: ["software-engineering", "AI", "future-of-work", "technology"]
draft: false
---

If you've been feeling like something "snapped" in late 2024 and 2025—that your work still looks the same on the surface, but under the hood it's suddenly… different—you're not alone. The tickets, the stand‑ups, the sprints are all still here, but what it *means* to be a software engineer is quietly changing in front of us.

I have a strong hunch that when we look back a few years from now, we'll say: 2025 was the last normal year for SWE. Not "the year all the jobs vanished," but the last year where it still made sense to think in terms of big IT headcounts, pyramids of junior devs grinding through mundane work, and "coding" as the primary way individual engineers create value.

Because if AI agents can now take on hours of serious work in one shot—and are on track to handle days or weeks worth of it soon—then a lot of the industry logic we grew up with simply stops making sense.

***

One of the reasons I feel this so strongly is my own experience "vibe coding" since the end of 2024. At first, it's playful: you toss half‑baked ideas at the model, it spits out working code, and you get this slight guilty rush—like you're cheating on an exam and somehow getting away with it. But very quickly, that feeling changes. You realise that for a *huge* chunk of the work that used to occupy junior and mid‑level developers—CRUD boilerplate, glue code, small refactors, tests, migrations—the model isn't just helping you. It's doing the first 70–80% almost completely on its own, and you're mostly editing and steering.

Now, zoom out from one developer to a typical IT services pyramid. For decades, these companies were basically arbitraging human time. Lots of juniors at the bottom, a thinner middle of project managers and tech leads, and a tiny layer at the top that actually understood business value and systems end‑to‑end. The model worked because you needed a ton of human "processing power" to move requirements to production: manual testing, hand‑rolled integrations, low‑risk features churned out sprint after sprint.

AI breaks that pyramid in the most boring, inevitable way possible: it chews through the bottom and middle. Not all at once, and not perfectly, but relentlessly.

Another reason 2025 feels like an inflection point is the quantitative side of this story. Benchmarks have quietly shifted from "can this model answer trivia and write leetcode solutions?" to "how many hours of a competent human's work can this system realistically shoulder on a messy, multi‑step task?" That's a fundamentally different question. And the answer has gone from "minutes" to "several hours" frighteningly fast, with credible people arguing that we're on a curve where those "time horizons" might double every few months.

What that means in plain language is: the kind of task that used to keep a junior dev busy for an afternoon—a small feature, a non‑trivial refactor, a migration with some edge cases—is exactly the kind of task that an agent can now take a serious swing at, end‑to‑end, while you go for a walk and come back to review the pull request. Today that still feels magical; in a couple of years, it's going to feel normal.

Now, I know some of you may be thinking: "Isn't this just hype? We've seen automation waves before. Don't these tools always look great in demos and then crumble on real‑world codebases?"

You're right to be skeptical. Anyone who has actually tried to plug an "AI agent" into a non‑toy repo knows how quickly they can hallucinate, get lost in the file tree, or generate confident nonsense. The key difference this time is that we're not talking about little autocomplete tricks in isolation. We're talking about full workflows where the model can read large swathes of context, plan multi‑step changes, call tools (tests, linters, CI, APIs), and iterate on its own output. The failures are very real—but so is the slope of the curve.

Another objection you might have is: "Won't this just create *more* demand for engineers? Every productivity increase in tech so far led to *more* software, not less."

That's partly true, and it will stay true for the engineers who adapt. There will absolutely be more software, more experiments, more agents, more systems to design and supervise. But the structure of that demand changes.

Think about the classic outsourcing story: a client has a big backlog of mundane work. A services firm promises to do it cheaper by hiring lots of juniors. Margins are thin, quality is variable, but the model "works" because you're trading money for human attention at scale. Now imagine the same client in 2028. Do they really need a hundred juniors doing mundane work if ten strong engineers with good agentic tools can deliver the same output—or better—by orchestrating a small army of AI workers? It's hard to see how the old pyramid survives that math.

So where does that leave you, the individual developer reading this?

One of the most important shifts is identity. If you still think of yourself primarily as "the person who writes code," you're going to feel this decade as a constant threat. Every new capability will feel like it's eating your lunch. On the other hand, if you start to think of yourself as "the person who designs and owns systems of humans *and* AI agents to deliver business outcomes," the same curve suddenly looks like your biggest ally.

Instead of panicking every time an agent can do another slice of your work, you start asking:

- How do I scope work so that an agent can own it for a few hours or days?
- How do I break down a week‑long project into phases that a model can handle, while I only step in at key review checkpoints?
- How do I wire up my tools, repos, tests, and infra so that agents can do real work safely, not just churn out cute demos?

At that point, what you're doing day to day is less "coding" and more "directing". You're specifying problems, setting constraints, deciding what "good" looks like, and then delegating execution to a mix of humans and agents. Your leverage comes from taste, architecture, product sense, and your ability to communicate with these systems—just like a good manager's leverage comes from how they lead people, not how many lines of code they personally write.

Now, I know another fear lurking here is: "Does this mean only the 'top 1%' of engineers have a place in the future? What about everyone else who's just… solid?"

All that being said, I'm not saying "only geniuses survive". What changes is the *shape* of "solid". Being the person who quietly ships tickets on time but never really owns problems is going to be harder and harder to justify, because a well‑configured agent can look a lot like that person on paper. But being the person who can take a fuzzy business goal, turn it into a clear plan, orchestrate agents and tools to execute most of it, and then refine the result into something users actually love—that's going to be extraordinarily valuable, and not just at FAANG‑style companies.

In fact, one of the more optimistic possibilities here is that individuals and very small teams get "agency" (pun intended) that used to be reserved for huge organisations. When a solo engineer with good agentic tooling can do the work of a small team, the barrier to trying new things drops. You don't have to beg for headcount to run an experiment; you spin up some agents, point them at your code and data, and supervise. The constraint shifts from "how many people can I hire?" to "how many good ideas and how much taste can I bring to the table?"

At the end of the day, when I say "2025 was the last normal year for SWE", I'm not saying that 2026 is the year everyone gets fired and the machines take over. I'm saying that 2025 will probably look, in hindsight, like the last year where you could reasonably plan a career around the old assumptions: big pyramids of human time, slow linear progression from junior to senior doing mostly similar work with more responsibility, and a clear boundary between "tools" and "teammates".

What's coming next is messier and more interesting: a world where you're expected to work *through* agents, not just *with* them, where your ability to delegate, specify, and judge becomes as important as your ability to implement. If you lean into that now—if you treat today's "vibe coding" as the training ground for serious AI delegation—you're not just safe, you're early. And in a world where capabilities are compounding this fast, being early is everything.
<!--more-->

