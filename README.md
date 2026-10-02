# UNIVERSE · An Interactive Cosmos

[![Watch: Qwen 3.8 27B thought for 82 minutes, then built this from one prompt](https://img.youtube.com/vi/Prww8NdNQIo/maxresdefault.jpg)](https://youtu.be/Prww8NdNQIo)

▶ **[Watch how it was built](https://youtu.be/Prww8NdNQIo)**, including the 82 minutes Qwen 3.8 spent thinking before it wrote a line of code, and the one sentence that fixed it.

An interactive universe website (scale, orbits, a timeline from the Big Bang to the first stars, and a gravity playground with bent spacetime and an n-body attractor that follows your cursor) **written entirely by Qwen 3.8 27B running locally** on a MacBook Pro M5 (32GB). No cloud, no API keys.

**Live demo:** https://vikramjitsarkar.github.io/qwen3.8-universe/

It's a single self-contained `index.html`. Open it in any modern browser.

## How it was made

- **Model:** Qwen 3.8 27B, 4-bit quantized (about 16GB)
- **Machine:** MacBook Pro M5 (base chip), 32GB unified memory
- **Coding agent:** OpenCode, fully local
- **Prompt:** a single prompt asking for a website about the universe with good animation and motion graphics

Known limits: not mobile-responsive yet; desktop browsers only.

### If you try this yourself

Qwen 3.8 27B tends to reason about its own reasoning in a loop until the context fills, and never writes code. On this project it thought for 82 minutes before I stopped it. A bigger context window doesn't fix it. Interrupt it and say:

> You're stuck in a loop reasoning with yourself. Stop thinking and start coding.

It starts writing immediately.

---

Made for the video [Qwen 3.8 27B: "Opus-Level" Local LLM? 3 Days on a 32GB MacBook](https://youtu.be/Prww8NdNQIo) on the [IamVikramjit](https://www.youtube.com/@IamVikramjit) channel. Local AI tested on the hardware most people actually own.
