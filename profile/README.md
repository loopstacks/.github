# LoopStacks

**Every AI invocation is a typed loop.**

LoopStacks is an open specification and reference runtime for agentic AI orchestration. It formalizes the insight that every model call, tool invocation, RAG lookup, and agent handoff is a typed loop — with a first-class lifecycle, schema contract, and tracing surface.

Most agent frameworks today treat orchestration as glue code. LoopStacks treats it as a runtime concern.

---

## Projects

**[lsr](https://github.com/loopstacks/lsr)** — The Loop Stack Runtime. TypeScript reference implementation. Single `docker run` command, web UI, REST + WebSocket API, CLI.

**[spec](https://github.com/loopstacks/spec)** — LSEM (Loop Stack Execution Model) specification. The formalism. Language- and implementation-agnostic.

**[examples](https://github.com/loopstacks/examples)** — Sample loops you can run on LSR: prompt loops, composite loops, tool-calling loops, RAG patterns.

---

## Try it in 60 seconds

```bash
docker run -p 3000:3000 ghcr.io/loopstacks/lsr:latest
# Open http://localhost:3000
```

No API keys required to see the runtime work — LSR ships with a mock backend. Add `OPENAI_API_KEY` or `ANTHROPIC_API_KEY` to use real models.

---

## Learn more

- **Site:** [loopstacks.io](https://loopstacks.io)
- **Spec:** [LSEM v0.1](https://github.com/loopstacks/spec)
- **License:** Apache 2.0

Issues, PRs, and discussions welcome.
