<p align="center">
  <a href="https://biga.n10nce.dev/">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="https://biga.n10nce.dev/brand/biga-logo-light.svg">
      <img src="https://biga.n10nce.dev/brand/biga-logo.svg" width="180" alt="biga">
    </picture>
  </a>
</p>

<h1 align="center">Stream your saves, not your screen</h1>

<p align="center">
  Your codebase. A live link. Nothing to install for viewers.
</p>

<p align="center">
  <a href="https://github.com/biga-app/cli/releases/latest"><img src="https://img.shields.io/github/v/release/biga-app/cli?style=flat-square&labelColor=0c0d10&color=63e197&label=cli" alt="Latest CLI release"></a>
  <a href="https://github.com/biga-app/cli/blob/main/LICENSE"><img src="https://img.shields.io/badge/license-MIT-63e197?style=flat-square&labelColor=0c0d10" alt="MIT license"></a>
</p>

<p align="center">
  <a href="https://biga.n10nce.dev/">Website</a> ·
  <a href="https://biga.n10nce.dev/docs">Documentation</a> ·
  <a href="https://biga.n10nce.dev/#how-it-works">How it works</a> ·
  <a href="https://biga.n10nce.dev/docs/self-hosting">Self-hosting</a>
</p>

---

Screen sharing sends pixels. biga sends the files themselves.

Run one command in your project, share the link, and let anyone inspect your source code in their browser as you work. They can navigate files, search, read syntax-highlighted code and step through checkpoints without cloning your repository or creating an account.

## Get started

```bash
curl -fsSL https://raw.githubusercontent.com/biga-app/cli/main/install.sh | sh
biga start
```

That's it. Share the link and keep coding. Windows, Go and other install options are in the [quickstart](https://biga.n10nce.dev/docs/quickstart).

## Made for the moments between commits

| | |
|:---|:---|
| **Pairing across timezones** | Let someone inspect the code while you make changes. |
| **Code reviews** | Share an in-progress implementation without asking someone to clone it. |
| **Teaching and mentoring** | Walk through a real codebase without setup on the viewer's machine. |
| **Building in public** | Give people a live view of your work, not a recording of your screen. |

## Small tool, thoughtful details

- **Only changed files travel.** Content hashes avoid sending unchanged files again.
- **Every checkpoint stays in the session.** Step back through changes and inspect file diffs.
- **Rejoin the same session.** Restart the CLI and keep sharing the same link.
- **Read-only for viewers.** A link lets people watch, nothing more.
- **Privacy-aware file filtering.** Sensitive paths and ignored files stay out of the shared tree.

Curious what happens after `biga start`? **[Explore how biga works →](https://biga.n10nce.dev/#how-it-works)**

## Documentation

- [Quickstart](https://biga.n10nce.dev/docs/quickstart)
- [What gets shared](https://biga.n10nce.dev/docs/what-gets-shared)
- [Architecture](https://biga.n10nce.dev/docs/architecture)
- [Self-hosting](https://biga.n10nce.dev/docs/self-hosting)
- [Brand](https://biga.n10nce.dev/brand)

## Repositories

| Repository | What it is |
| --- | --- |
| [cli](https://github.com/biga-app/cli) | The `biga` command. Watches a folder and streams every save. |
| [server](https://github.com/biga-app/server) | The Go API. Stores sessions and streams updates to viewers. |
| [website](https://github.com/biga-app/website) | The site, the live viewer and the documentation. |
| [docker](https://github.com/biga-app/docker) | Self-hosting: the whole stack with Docker Compose. |

## Contributing

Bug reports, focused fixes and pull requests are welcome. Read the [contributing guide](https://github.com/biga-app/.github/blob/main/CONTRIBUTING.md) before you start, and report vulnerabilities privately as described in the [security policy](https://github.com/biga-app/.github/blob/main/SECURITY.md), not in a public issue.

## License

biga is MIT licensed.

---

<p align="center">
  <sub><a href="https://biga.n10nce.dev/">biga</a> · Made for people who teach, pair and build in public.</sub>
</p>
