# Han's Readme

This is **NOT** a rule book, but rather a "cheat sheet" to help you familiarize yourself with my values, beliefs, and how I operate. I hope this guide helps us accelerate the introductory phase so we can get to the fun part faster.

## General Availability

Some general information to facilitate remote work:

- **Start Time:** I start my work day around 9:00 CET (13:30 IST). Between 8:00 and 9:00 CET, I am driving my daughter to kindergarten. Meetings before 8:00 (12:30 IST) are possible.
- **End Time:** I finish at 17:00 CET (21:30 IST) because I need to cook dinner, though I sometimes continue in the evenings after 21:00.
- **Meetings:** I reserve dedicated slots in my calendar every day specifically for my team—please use them!
- **Teams/Slack:** Notifications are turned off, but I check them regularly. Check out this [medium article](https://medium.com/@hanche2001/the-ux-behind-async-messages-022024348c77) on my thoughts on async messages.
- **1:1s:** at least 30min per week/month with each team member, focusing on personal development, while not talking about operational business.

## My Values

### How I Communicate

- **I ask "Why?" a lot:** Coming from a product/startup background, I am very curious. If I ask "Why did you do it this way?", I am not criticizing or blaming you. I am simply trying to understand.
- **Silence is okay:** If I ask a question and you need time to think, that is fine. You can always get back to me later.
- **Inverted pyramid & "Don't make me think":** Lead with the conclusion, decision, or ask at the top, and put the context and details below. Connect the dots for your reader so they don't have to reconstruct why something matters.
- **Calibrated candour & trust budget:** Every claim spends the trust you have built; evidence and verifiable proof earn it back. State proven facts plainly, and when something is an unverified guess, say *"this is my hypothesis"*. When we disagree on design or architecture, I prefer citing published standards, research, or concrete working proof over arguing personal preference, rank, or volume.

### Focus time
I highly value everyone's focus time and people who show respect for mine.

I usually plan my focus times in my calendar at least one week in advance. However, if you cannot find an open slot and the matter is urgent, **please do not hesitate to call me.**

### Feedback
I am 100% open to feedback — the timelier, the better. I will never admonish you for giving me honest feedback. Why would I? You're helping me grow.

If you feel unable or uncomfortable giving feedback to me personally for **any reason**, please share it with a colleague, my team lead, or even HR. I want to know because I cannot adapt if I don't know what needs to change.

**My promise to you:** You will receive frequent, honest, and constructive feedback from me, with the intent to help you grow. Praise will be public, and criticism will always be private.

Here is my mental model on great feedback:

**Giving Feedback**
1.  **Timely:** As immediate as the situation and setting allow.
2.  **Specific:** Focus on specific behaviors and concrete situations, not hypotheticals.
3.  **Subjective:** Suggest what I could have done differently and why, so I can reflect.

**Receiving Feedback**
1.  **Clarify, don't justify:** Seek to understand instead of letting your ego rule.
2.  **Reflect and filter:** Feedback is a gift, but it’s not always right. Reflect on it, take what is useful for your growth, and discard the rest.

This article matches my mental model quite well:
[The Do’s & Don’ts of Giving and Receiving Effective Feedback](https://crestcom.com/blog/2023/10/06/the-dos-donts-of-giving-and-receiving-effective-feedback/)

### Ownership & Accountability

**My Philosophy**: You drive, I navigate. I believe you do your best work when you have the freedom to drive your own topics. I want you to feel ownership of your code. However, I know that true ownership requires a safe environment.

- **Obsolete by design:** I measure my leadership by how little you need me in the room afterwards. In Kant's words, *Sapere aude* — have the courage to use your own judgment rather than waiting for external direction. As Lao Tzu put it: *"When the best leader's work is done, the people say, 'We did it ourselves.'"*
- **Outcomes over methods:** On a highway we agree on the destination, and nobody drives the wrong way. Which car you take is up to you.

**Safety First**

- **Mistakes happen**: We are building complex software. I will never blame you for an honest mistake, but I will hold you accountable for hiding them. I focus on fixing the process, not blaming the person.
- **Bad News Travels Fast:** If something breaks or a deadline is at risk, tell me **immediately**. I am here to help you put out the fire, not to judge you for the spark.
- **Ask for help:** It is not a weakness to ask for help; it is a strength. If you are stuck for more than 1 hour, please reach out.


**Growing into Accountability**
- **Proactive vs. Reactive:** You are the experts on the code you write. If you see a way to improve our code or process, please tell me. I want to hear your ideas.
- **My Role:** My job is to unblock you, provide context, and handle the politics. Your job is to focus on the technology.

### How I Think About Engineering & AI

Software only exists as a translation layer between human intent and computing power. As natural language becomes the new programming interface, how we engineer software and manage our work shifts fundamentally:

- **People first (socio-technical systems):** AI is an accelerator, not a silver bullet. Plug it into a culture or codebase that isn't ready, and Conway's law guarantees you'll just get the good and the bad parts faster. When AI 10x's coding speed, the bottleneck doesn't vanish—it moves downstream to requirements, architecture, and verification.
- **AI gave you a promotion you never asked for:** Writing code and prose used to be the natural brake that held complexity in check. Now that generation is nearly free, every individual contributor becomes more **manager than maker**. Your leverage comes from how well you **plan, spec, and review**.
- **Treat AI like a brilliant freelancer with amnesia:** It knows every trade, never asks clarifying questions on its own, and forgets everything after each session. Manage it with five moves:
  1. **Break it down** into small vertical slices.
  2. **Requirements first** — state what "done" looks like before execution starts.
  3. **Let AI grill you** — have the agent interview you relentlessly to surface hidden assumptions and edge cases before it writes a line of code.
  4. **One chat, one job** — treat the context window as a finite attention budget; pass explicit handoffs to fresh sessions before context rot sets in.
  5. **Evaluate every step** — never let an agent grade its own homework without a check.
- **The determinism split:** Push work as far left toward deterministic machine checks as possible (*cheap and certain → fuzzy AI middle → expensive human semantic judgment*). Let fast unit tests, type schemas, linters, and automated architecture/document harnesses carry the mechanical rules; use AI for synthesis and exploration; save human attention for architecture, UX taste, and final accountability.
- **Architecture and agent legibility beat delivery:** Deadlines cut scope or polish, never structure. Keep modules deep, domain language exact (`GLOSSARY.md`), and repositories navigable so both a new teammate and an AI agent can reach any authoritative fact in two hops.

## About Me

I have worked across every link of the SaaS value chain — from **Sales Director** in Asia (Infobip, closing 50+ contracts across Kuala Lumpur, Shenzhen, and Beijing), to **Full-Stack Founding Engineer** (Selfbits, building industrial IoT/MES software across 5 European factories), to **Tech Lead & UX/Requirements Lead** (XL2 for Audi, delivering a €7M approval-gate modernization), to **Engineering Manager & Principal AI Enablement Engineer** (RIB Software), alongside 2,000+ hours of coaching and training startups, engineers, and NPOs since 2010.

### Recent Efforts in AI

I spend a lot of my time—both at work and in the evenings—building and teaching practical AI enablement. I believe in **practising what I teach**: anything I claim in a workshop is backed by public research and proven in my own agentic repositories first.

- **[hancrafted.net](https://hancrafted.net) — Visual Knowledge Library & Interactive Explorables:** I build an open, bilingual (EN/DE) library of visual Episodes and interactive [Explorable Explanations](https://hancrafted.net/explorables/) backed by a vetted research wiki:
  - **[Treat AI like a brilliant freelancer with amnesia](https://hancrafted.net/episodes/onboard-ai-every-time/)**, **[Why AI has a weird attention span you must learn to manage](https://hancrafted.net/episodes/ai-attention-span/)**, and **[Why AI gives you more work](https://hancrafted.net/episodes/ai-gives-you-more-work/)**.
  - **[Context Window & Attention Visualizer](https://hancrafted.net/explorables/context-window/):** Interactive simulation of token budgets (200K vs. 1M), attention sinks, the "lost in the middle" effect, and auto-compaction, built on real Claude Code session logs.
  - **[Human-in-the-Loop Agentic Workflows](https://hancrafted.net/explorables/human-in-the-loop/):** A hands-on workflow board where non-technical and technical users alike can practice orchestrating multi-stage AI pipelines (grilling, specs, parallel tasks, verification) in ChatGPT, Gemini, or CLI agents.
  - **[AI Capability Timeline](https://hancrafted.net/explorables/ai-capability/):** Visualizing how Prompting (2022), Agents (2024), Workflows (2024), and the Agentic Factory (2026) each add a layer on top of the same underlying LLM—and why "20x productivity" requires moving up those layers rather than typing better chat prompts.
  - **[Agent CLI & Workshop Starter Guide](https://hancrafted.net/guides/setup-ai-agent-and-starter-folder/):** A step-by-step interactive onboarding guide that takes even terminal-shy users from zero to running their first local agent skills across Claude Code, GitHub Copilot CLI, Codex, and Gemini CLI.
- **Harness Engineering & Deterministic Governance:** To keep multi-agent codebases from decaying into "slop," I build and enforce deterministic harnesses:
  - **Archgate ADRs** for executable TypeScript architecture rules and escalated tech-debt tracking.
  - **`markdown-harness` (`mh`)** — a CLI tool I built to govern markdown repositories: enforcing document schemas, frontmatter provenance (`generated by` vs. `verified by human`), freshness (`stale_after`), and agent writing contracts.
- **Reusable Agent Skills & Visual Decision Specs (`/to-html-spec`):** I author composable agent skills for voice-first `/grilling` (relentless requirement interviews while commuting), `/tdd`, two-axis `/code-review` (Standards vs. Spec), `/writing-for-agents` (context pointers, progressive disclosure, leading words), and `/to-html-spec` — turning complex engineering or design trade-offs into self-contained, interactive HTML decision pages with side-by-side visual options, dictation-friendly feedback rails, and ablation evals so humans can make high-confidence decisions fast.
- **The Agentic Factory:** Building local-first, model-agnostic pipelines (`events.jsonl` tracing, rubric scoring, YouTube post-production automation that learns from my manual edits) that turn repeatable digital and engineering work into measurable Pipelines of Jobs.

Below you'll find quite a long list of personal interests.

### Hobbies

#### Boardgame

I love (complex) euro board games, ideally space themed. What I love even more is to analyze the game's (system) design and discover/exploit unbalanced rules/strategies.

My top 5 favourite board games are 

1. [SETI](https://boardgamegeek.com/boardgame/418059/seti-search-for-extraterrestrial-intelligence)
2. [Anachrony](https://boardgamegeek.com/boardgame/185343/anachrony)
3. [Ark Nova](https://boardgamegeek.com/boardgame/342942/ark-nova)
4. [Andromeda's Edge](https://boardgamegeek.com/boardgame/358661/andromedas-edge)
5. [Galactic Cruise](https://boardgamegeek.com/boardgame/391137/galactic-cruise).

[My BGG Account](https://boardgamegeek.com/profile/Aavelyn)

#### Video Games

I love single player RPGs, because they transport me into another world for a limited time. Apart from that I love indie rougelikes/lites.

My top 10 favourite video games are 

1. Cyberpunk 2077
2. Baldur's Gate 2 + 3
3. Mass Effect Trilogy
4. XCOM 2 Long War
5. Clair Obscur: Expedition 33
6. Slay the Spire 1 + 2
7. Hades 1 + 2
8. Civilization 5, 6
9. Xenoblade Chronicle 1 + 3
10. Fire Emblem: Three Houses


#### Movies/TV/Books

1. Everything Christopher or Jonathan Nolan
2. Evertyhing Star Wars (Before Disney)
3. Everything Brandon Sanderson
    - Stormlight Archive
    - Mistborn
    - Reckoners
4. Harry Potter
   - I actually have a scar on my forehead and I used to do card magic...
6. Sci-fi(Space)/Fantasy(Epic, High)


### YouTube

I watch a lot of (pseudo)-educational videos on YouTube. Here is a list of videos I love and channels I follow.

### AI

- [IBM](https://www.youtube.com/@IBMTechnology)
    - [Five AI Risks That Can Get You Fired](https://www.youtube.com/watch?v=1m55T8xST9s)
- [Google](https://www.youtube.com/@GoogleDevelopers)
    - [Software engineering at the tipping point](https://www.youtube.com/watch?v=2n41YjR5QfU)  
- [AI Engineer](https://www.youtube.com/@aiDotEngineer)
    - [The New Code — Sean Grove, OpenAI](https://www.youtube.com/watch?v=8rABwKRsec4)
    - [No Vibes Allowed: Solving Hard Problems in Complex Codebases – Dex Horthy, HumanLayer](https://www.youtube.com/watch?v=rmvDxxNubIg)
- [Matt Pocock](https://www.youtube.com/@mattpocockuk)
    - [5 Claude Code skills I use every single day](https://www.youtube.com/watch?v=EJyuu6zlQCg) 

### Engineering
- [LearnThatStack](https://www.youtube.com/@LearnThatStack)
- [Modern Software Engineering](https://www.youtube.com/@ModernSoftwareEngineeringYT)
    - [The Secrets to Being an AWESOME Tech Lead](https://www.youtube.com/watch?v=TfBUPu5_G6A)
    - [A Guide To Managing Technical Teams](https://www.youtube.com/watch?v=jMpCF0Z623s)
- [ByteByteGo](https://www.youtube.com/@ByteByteGo)
- [Fireship](https://www.youtube.com/@Fireship)
- [Decoded Frontend (Angular)](https://www.youtube.com/@DecodedFrontend)

### Leadership

- [Simon Sinek](https://www.youtube.com/@SimonSinek)
    - [How Great Leaders Inspire Action | Simon Sinek | TED](https://www.youtube.com/watch?v=qp0HIF3SfI4)
- [The Power of Vulnerability | Brené Brown | TED](https://www.youtube.com/watch?v=iCvmsMzlF7o)

### Nerd Stuff

- [The Friday Checkout](https://www.youtube.com/@TheFridayCheckout)
- [Veritasium](https://www.youtube.com/@veritasium)
- [Numberphile](https://www.youtube.com/@numberphile)
- [The Friday Checkout](https://www.youtube.com/@TheFridayCheckout)
- [Mark Rober](https://www.youtube.com/@MarkRober)
- [Economics Explained](https://www.youtube.com/@EconomicsExplained)

### Documentations

- [Johnny Harris](https://www.youtube.com/@johnnyharris)
- [Howtown](https://www.youtube.com/@Howtown)
- [Elephants in Rooms](https://www.youtube.com/@ElephantsInRooms)

### Fun Stuff

- [Jimmy Kimmel Live](https://www.youtube.com/@JimmyKimmelLive)
- [LastWeekTonight](https://www.youtube.com/@LastWeekTonight)
- [Uncle Roger](https://www.youtube.com/@mrnigelng)
- [The Dice Tower](https://www.youtube.com/@thedicetower)
- [Don McMillan](https://www.youtube.com/@donmcmillancomedy)
