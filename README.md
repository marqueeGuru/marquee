# Marquee

**An open-source emulator for mechanical manufacturability.**

Marquee aims to give mechanical designers the same kind of fast feedback loop that EDA gives chip designers — a way to ask, before you cut metal, *can this be made, and if so, how?*

The first concrete instantiation is **Open Lathe**: a community-driven effort scoped to lathe machining, on two fronts —
- the emulator software, and
- the design of the lathe and its components.

The end goal is back-to-back design between the physical machine and an agentic system that performs manufacturability analysis and supports part design.

## Status

Early research. The project is in the placeholder phase: a geometric kernel (segments, shapes, paths, turning-insert green/red zones, collision and material-removal primitives) exists in MATLAB; the manufacturability verdict, process planner, STEP loader, and the agentic system trained on a synthesized dataset are the first milestone — not yet built.

The website at this repo is the public front door while the work matures.

## Website

Live at: `https://<your-github-username>.github.io/marquee/` (update this once Pages is enabled).

The site is plain HTML + CSS, served from `main` at the repo root. To preview locally:

```sh
python3 -m http.server 8000
# then open http://localhost:8000/
```

## Get involved

The project is early and the most valuable contribution right now is conversation.

- **[GitHub Discussions](../../discussions)** — open-ended questions, ideas, and conversation. No approval needed.
- **[GitHub Issues](../../issues)** — concrete proposals and bug reports. Use the templates.
- **Telegram** — a curated backchannel with join-request approval (joining soon; link will land here).

If you want to contribute code, please open an issue first. The API surface is unstable and coordinating early avoids wasted effort. See [CONTRIBUTING.md](CONTRIBUTING.md).

## License

[MIT](LICENSE).
