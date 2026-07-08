# Fork Talk

Landing page for [Fork Talk](https://fork-talk.github.io/) — open source
Bitcoin fork research, data-driven analysis, and adoption monitoring.

No opinion without evidence. No claim without a source. Community
maintained, corrections welcome via PR.

## Projects

- **[FAQ](https://fork-talk.github.io/faq/)** — what forks are, how they
  work, historical and current proposals, and data-driven responses to
  common talking points.
- **[BIP-110 Monitor](https://fork-talk.github.io/bip110-monitor/)** —
  live tracking of BIP-110 node signaling and miner block signaling.
- **[BIP-110 Technical Review](https://fork-talk.github.io/bip110/)** —
  deep analysis of BIP-110's filtering heuristics, with code from the
  shipped Knots implementation.

## Development

A static site — plain HTML and CSS, no build steps. Served by GitHub
Pages from the default branch of this repo.

To preview locally:

```sh
python3 -m http.server
```

then open <http://localhost:8000/>. Note that links to the other Fork
Talk projects (`/faq/`, `/bip110-monitor/`, …) resolve only on the
deployed site, where each project is served from its own repo under the
same domain.

## Contributing

If something is wrong, open an issue. If something is missing, submit a
PR. The best contributions are data, not opinion.

## License

[MIT](LICENSE)
