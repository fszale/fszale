# Hi, I'm Filip Szalewicz

**I build AI SaaS apps, enterprise and consumer.** I write the code, ship it, and keep it running. I am Head of Engineering for Vizly and TRAVIS, and CTO of Data Reaktor and lookingGLASS. I have been shipping software for 20+ years, starting with my first commercial app in 1993.

[Vizly](https://vizly.ai) · [TRAVIS](https://aggregateintelligence.com/travis) · [Data Reaktor](https://www.datareaktor.ai/) · [lookingGLASS](https://lookingglasslifestyle.com/) · [LinkedIn](https://www.linkedin.com/in/fszalewicz/)

---

## Free Grok Bot templates I run in production

I run engineering in small pods where each engineer runs their own bots. These two templates are what keep that working. Both are free.

| Template | What it does | Add it |
| --- | --- | --- |
| **Fleet Chief of Staff** | Holds a fleet of specialist bots accountable. Daily staff check, shared fleet memory, a weekly self improvement loop with a score per bot, one Slack channel per project where the bots coordinate. Nothing sends, spends or merges without your yes. It briefs you only on done, stuck or needs a yes. | [x.ai/bot/_gosP8ICIeFfcAROg3Ij-](https://x.ai/bot/_gosP8ICIeFfcAROg3Ij-) |
| **Virtual CTO** | Technical leadership on call. Architecture reviews, solution reviews, hiring help, 30/60/90 plans, and a workflow built around PR review. It drafts and recommends, you approve what ships. Skills are open source in [`agent-kernel`](https://github.com/fszale/agent-kernel). | [x.ai/bot/eM_J3tkxeQL0JqlBquhyM](https://x.ai/bot/eM_J3tkxeQL0JqlBquhyM) |

### How the pods run

- The bots talk to each other in a shared agent channel and ask a human there when they need one.
- Sentry errors are the daily work queue. Bots take the clear ones to draft PRs.
- Standups center on PR reviews. Nobody gives a status update.
- Humans approve every merge, deploy and send.
- Every bot reads one shared memory folder before it starts, so it never starts cold.

What it changed: junior engineers working at senior level in weeks. Visible velocity and throughput gains with smaller teams. Less time coordinating, more time building and delivering. An order of magnitude productivity impact on engineering resources.

### How to start

1. Install the template from the link above.
2. Give it your channels and repos. One project channel and one repo is enough to start.
3. Start with drafts only.
4. Add bots one lane at a time. Errors first, then PR review, then planning.
5. Review the weekly scores and keep what improves.

Want this set up in your pods? [Book 30 minutes](https://cal.com/filip-szalewicz-wl6x3a/30min) with me at [Solid Cage](https://www.solidcage.com).

---

## Apps I build

| App | What it does | My role | Stack | Link |
| --- | --- | --- | --- | --- |
| **Vizly** | AI data analyst: upload a file, ask a question in plain language, get charts and Python or R analysis. | Head of Engineering | Not public | [vizly.ai](https://vizly.ai) |
| **TRAVIS** | Business intelligence for travel that combines a company's own data with Aggregate Intelligence market data. | Head of Engineering | Not public | [aggregateintelligence.com/travis](https://aggregateintelligence.com/travis) |
| **Data Reaktor** | Agent-first B2B intelligence: lead scoring, prospect research and outreach, through a REST API for agents and a dashboard for people. | CTO | TypeScript, React, Express, Postgres (Drizzle), Clerk, Stripe, n8n on GCP | [datareaktor.ai](https://www.datareaktor.ai/) |
| **lookingGLASS** | Consumer wardrobe app: scan your closet and get daily outfits from clothes you already own. | CTO | Expo / React Native, React, Python and TypeScript API, AWS, Terraform | [lookingglasslifestyle.com](https://lookingglasslifestyle.com/) |

The source for these apps is private. Since July 2026: 1,800+ commits across the lookingGLASS v2 repos and 140 on the Data Reaktor app.

On the side I consult through [Solid Cage](https://www.solidcage.com) ([details below](#consulting-on-the-side)).

---

## Building in the open

| Repo | What it is |
| --- | --- |
| [`agent-kernel`](https://github.com/fszale/agent-kernel) | The control plane my digital twin and agent factories run on. 28 skills, 21 prompt templates, 18 document templates, 6 GitHub Actions that check and improve it. Installs as a Grok Build plugin. |
| [`agent-factory`](https://github.com/fszale/agent-factory) | Runtime for governed AI employees. FastAPI + Supabase, human approval queue, audit log, React admin dashboard, Cloud Run. |
| [`digital-twin-filip`](https://github.com/fszale/digital-twin-filip) | My reference digital twin, loaded by agent-factory. [Chat with it](https://ai-twin-service-395682521918.us-central1.run.app/). |

---

## Prototyping: Dark Factory (Brickworks)

[`dark-factory`](https://github.com/fszale/dark-factory) is a concept I'm developing in the open. A full factory runs in software first: deliveries, sorting, five parallel lines, final assembly, inspection, dispatch. A physical tabletop build comes next.

TypeScript, Babylon.js, Fastify. 123 tests. [Run the live prototype](https://dark-factory-fszale.replit.app/).

---

## Consulting on the side

I am Principal Consultant at [Solid Cage](https://www.solidcage.com), where I help engineering teams with agentic AI transformation. The work is hands-on: I build agents and workflows with your team on your own systems, not slide decks. The first call is a 30-minute readiness review.

[apps.solidcage.com](https://apps.solidcage.com) has free tools to try first: a digital twin builder, an AI ROI generator and readiness scorecard, a rate-of-improvement tracker, and three short decks on the method. The method itself is open source in [`agentic-playbook`](https://github.com/fszale/agentic-playbook).

[Book 30 minutes](https://cal.com/filip-szalewicz-wl6x3a/30min) · [solidcage.com](https://www.solidcage.com) · [Free tools and decks](https://apps.solidcage.com) · [Chat with my AI twin](https://ai-twin-service-395682521918.us-central1.run.app/) · [Agent-readable profile](https://fszale.github.io/agent-ready-cto/)

---

## Older work

- [`configuration-driven-design`](https://github.com/fszale/configuration-driven-design): the config-driven pattern I have used across many systems.
- [`dos-beep`](https://github.com/fszale/dos-beep): my first commercial app, written from scratch in 1993.
- [`resume`](https://github.com/fszale/resume): full engineering history.

---

<sub>Reach me: [LinkedIn](https://www.linkedin.com/in/fszalewicz/) · [Book 30 minutes](https://cal.com/filip-szalewicz-wl6x3a/30min) · [solidcage.com](https://www.solidcage.com) · [YouTube: Control The Outcome](https://www.youtube.com/@Control-The-Outcome)</sub>
