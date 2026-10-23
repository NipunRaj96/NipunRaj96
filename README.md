# Hi, I'm Nipun 🧗🏻

AI Engineer at **InfoEdge (Naukri)**. Before that, Paytm and Times Internet.

I build AI systems that hold up in production: multi-agent pipelines, LLM orchestration, RAG, evaluation, and the deep learning and NLP underneath. I get to a working version fast, then spend the real time making it reliable.

Open to AI Engineer, Applied AI and Forward-Deployed roles. Based in Noida.

---

## At InfoEdge

### Agentic Config Generator
Putting a company's career page on Naukri starts with a config, and an executive writes about 15 to 20 of them a day by hand.

I built the pipeline that does it instead. An LLM drives headless browsers, reads the page, writes the config and checks its own work. When a page shifts mid-run, validation catches the drift there and then, not at the end.

It took three months to understand every flow and every flaw, and one of those months was only testing.

- ⚡ **~300 to 350 configs for about $2**, at roughly 80 seconds each. That is under a cent per config.
- **~96% less manual setup time**, and 60+ person-days a month handed back to a team of about 20 executives.

[Repo](https://github.com/NipunRaj96/agentic-config-engine)

---

## Built on my own
*The code for these two is private. I'm happy to walk anyone through them.*

### Nudge
A complete product for a shuttle operator in Delhi NCR, built solo: one Android app with three roles (rider, driver, operator), live vehicle tracking, seat booking and UPI payment verification.

The operator uploads the timetable PDFs they already have. The app reads the stops and times, corrects obvious errors and places each stop on the map. It was designed to run at almost no cost.

One focused week from idea to production. The operator trialled it, then bought it. Today it serves about 400 riders on 20 vehicles across 7 routes.

[Read the case study](https://medium.com/@nipunraj2004/nudge-rebuilding-a-local-shuttle-operators-workflow-on-an-almost-zero-budget-7a5923d71fb5)

### Mini.ai 
A chat workspace that runs on your own API keys. Six providers sit behind one screen, and you can switch models mid-conversation.

Ask several models the same question and they critique each other, then a judge writes one verdict. Build agents with their own model, tools, memory and rules. They hand work to each other and run on a schedule or a webhook. Every tool is set to Allow, Ask or Block, so anything risky waits for your approval. Documents come back with page citations.

**TLDR:** Something similar to Grokbot, but more advanced. I first built a rough version at **Paytm** in July 2025, well before Grokbot or anything similar existed. This is the finished version, rebuilt from scratch.

[See it](https://miniai-prod.vercel.app/overview)

---

## Also

- **Orca OS**: natural language to executable Linux. Paper accepted in 2026. Paused after OpenClaw arrived and covered the ground. [Repo](https://github.com/NipunRaj96/Orca-OS)
- **ruview-macos-presence**: senses people in a room using only a MacBook's WiFi card. No sensors, no extra hardware. [Repo](https://github.com/NipunRaj96/ruview-macos-presence)
- **frontier-agent-benchmarking**: evaluations for frontier coding agents. [Repo](https://github.com/NipunRaj96/frontier-agent-benchmarking)
- **Freshdesk to Jira** (Paytm): full migration, ~92% lower support-stack cost. [Repo](https://github.com/NipunRaj96/fd-to-jira)

---

## How I work

Reliability is built, not prompted. I wrap LLMs in state machines, validators and audits, and I treat cost, latency and accuracy as design constraints from day one.

Enterprise pipelines, products people pay for, research that gets accepted. If AI has to do real work on your team and be right about it, let's talk.

---

[Portfolio](https://nipun.framer.website/) · [LinkedIn](https://www.linkedin.com/in/nipunkumar01/) · [Medium](https://medium.com/@nipunraj2004) · nipunraj2004@gmail.com
