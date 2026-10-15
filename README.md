# Hi, I'm Nipun 🧗🏻

AI Engineer at **InfoEdge (Naukri)**. Before that, Paytm and Times Internet.

I go looking for work that someone is doing by hand, with a spreadsheet and a lot of patience. I build the replacement quickly, then spend the real time making it survive actual users.

Open to AI Engineer, Applied AI and Forward-Deployed roles. Based in Noida.

---

## At InfoEdge

### Agentic Config Generator
Putting a company's career page on Naukri starts with a config, and an executive writes about 15 to 20 of them a day by hand.

I built the pipeline that does it instead. An LLM drives headless browsers, reads the page, writes the config and checks its own work. When a page shifts mid-run, validation catches the drift there and then, not at the end.

It took three months to understand every flow and every flaw, and one of those months was only testing.

- ⚡ **~300 to 350 configs for about $2**, at roughly 80 seconds each. That is under a cent per config.
- **~96% less manual setup time**, and 60+ person-days a month handed back to a team of about 20 executives.

[Repo](https://github.com/NipunRaj96/agentic-config-generator)

---

## Built on my own
*The code for these two is private. I'm happy to walk anyone through them.*

### Nudge
A shuttle operator in Delhi NCR was running about 400 riders on a WhatsApp group, PDF timetables and an Excel sheet. I replaced all three with one Android app, with a view each for riders, drivers and the operator.

Riders book a seat, pay by UPI and watch the shuttle on a map. Drivers get a stop-by-stop list and tap each rider as boarded. The operator approves payments and imports routes from the PDFs they already had. It costs almost nothing to run.

One focused week from idea to production. The operator trialled it, then bought it. Today it runs 20 vehicles across 7 routes.

[Read the case study](https://medium.com/@nipunraj2004/nudge-rebuilding-a-local-shuttle-operators-workflow-on-an-almost-zero-budget-7a5923d71fb5)

### mini.ai
A chat workspace that runs on your own API keys. Six providers sit behind one screen, and you can switch models mid-conversation.

Ask several models the same question and they critique each other, then a judge writes one verdict. Build agents with their own model, tools, memory and rules. They hand work to each other and run on a schedule or a webhook. Every tool is set to Allow, Ask or Block, so anything risky waits for your approval. Documents come back with page citations.

I first built a rough version at Paytm. This is the finished one, written again from scratch.

[See it](https://miniai-prod.vercel.app/overview)

---

## Also

- **Orca OS**: natural language to executable Linux. Paper accepted in 2026. Paused after OpenClaw arrived and covered the ground. [Repo](https://github.com/NipunRaj96/Orca-OS)
- **ruview-macos-presence**: senses people in a room using only a MacBook's WiFi card. No sensors, no extra hardware. [Repo](https://github.com/NipunRaj96/ruview-macos-presence)
- **frontier-agent-benchmarking**: evaluations for frontier coding agents. [Repo](https://github.com/NipunRaj96/frontier-agent-benchmarking)
- **Freshdesk to Jira** (Paytm): full migration, ~92% lower support-stack cost. [Repo](https://github.com/NipunRaj96/fd-to-jira)
- **Writing**: [Medium](https://medium.com/@nipunraj2004), including a long one on RAG that actually works

---

## How I work

LLMs get wrapped in state machines, validators and audits, because reliability is built, not prompted. Token spend, infra spend and human hours all go on the same spreadsheet.

If your team runs on a WhatsApp group and an Excel sheet, we should talk.

---

[Portfolio](https://nipun.framer.website/) · [LinkedIn](https://www.linkedin.com/in/nipunkumar01/) · [Medium](https://medium.com/@nipunraj2004) · nipunraj2004@gmail.com
