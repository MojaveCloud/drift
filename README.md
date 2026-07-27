# drift

A single page of generative art: a dense field of drifting embers, bright heads
trailing long copper streaks over near-black. One `index.html`, no dependencies,
no build step.

The page was written by [Claude Code](https://claude.com/claude-code) from a
single prompt, which then committed it, pushed it here, and deployed it — no
dashboard, no CI config, no YAML. It is live at
**https://drift.mojavedev.sh**.

## Deploy your own copy

```sh
curl -fsSL https://mojave.sh/install.sh | sh
mojave login
mojave deploy --repo MojaveCloud/drift
```

Or fork it, change the palette in `index.html`, and deploy the fork — a static
page like this one needs no configuration beyond an `index.html` at the repo
root.

## License

MIT
