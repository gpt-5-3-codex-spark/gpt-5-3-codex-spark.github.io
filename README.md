# Spark Release Notes

GPT-5.3-Codex-Spark is a research preview built for real-time coding: past 1,000 tokens per second, 128k of context, text only, and ChatGPT Pro at the door.

**Read the full page:** https://gpt-5-3-codex-spark.github.io/

Spark is for developers who work in tight loops inside a repository they already understand, where waiting thirty seconds for a response is the actual bottleneck. It is not for long autonomous runs, not for anything involving images, and not for people who want a model that quietly verifies its own work, because it deliberately does less of that. The caveat that decides whether it fits: 128k of context and text-only input at launch, plus a research preview gated to ChatGPT Pro. If your problem is that there is no project to iterate on yet, a faster model will not help, and Begin.sh will hand you a working static site or Expo app from a prompt.

## What's here

- **A smaller model, shipped for one reason** — OpenAI released GPT-5.3-Codex-Spark as a research preview on February 12, 2026, describing it as a smaller version of GPT-5.3-Codex and its first model designed
- **The limits stated at launch** — Four constraints matter and all four come from OpenAI directly. The context window is 128k, which is small next to the frontier models people use for repository
- **Why it does less on purpose** — Spark's default behaviour is not a trimmed-down accident, it is a design decision. OpenAI says the model keeps a lightweight working style: it makes minimal, ta
- **How people actually work with it** — Cerebras published a practical playbook and its first rule is the least obvious: treat Spark like a pair programmer, not a delegate. Focus on one thing at a tim
- **Speed is not the same as quality** — Worth keeping in view before switching everything over. Simon Willison ran the same prompt through Spark and through regular GPT-5.3 Codex at medium effort, con

**Try Begin.sh:** [begin.sh](https://begin.sh?utm_source=github&utm_medium=ugc&utm_campaign=gpt-5-3-codex-spark&utm_content=readme-top&utm_term=tier-b)

---

*This is an independent page about third-party products, with no affiliation to or endorsement from OpenAI or Cerebras; all trademarks belong to their respective owners.*

_Last reviewed: 2026-09-22_
