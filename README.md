# FlowStory

AI-agent-first animated flow diagram framework. Define architecture flows in JSON — the engine handles canvas rendering, step-by-step animation, and interactive playback.

This fork hosts interactive architecture diagrams for AI Gateway and MaaS. Browse them on **[jaland.github.io/flowstory](https://jaland.github.io/flowstory/)**.

## Architecture Flows

| Flow | Link |
|------|------|
| AI Inference Gateway | [Open](https://jaland.github.io/flowstory/flows/ai-gateway/index.html) |
| MaaS Inference | [Open](https://jaland.github.io/flowstory/flows/maas-inference.html) |
| MaaS Key Minting | [Open](https://jaland.github.io/flowstory/flows/maas-key-minting.html) |
| MaaS Multi-Tenancy | [Open](https://jaland.github.io/flowstory/flows/maas-multi-tenancy.html) |
| Multi-Tenancy Deployment | [Open](https://jaland.github.io/flowstory/flows/maas-multi-tenancy-deployment.html) |

## Examples

- [Hello World](https://jaland.github.io/flowstory/examples/hello-world/index.html) — Minimal 3-node example
- [Hello World (source)](examples/hello-world/) — Local path

## Quick Start — Generate a Diagram

**No install needed.** Open Claude Code, paste one prompt, get an animated diagram.

**[Quick Start Guide](docs/quick-start-prompt.md)** — step-by-step instructions with the prompt to copy-paste.

## Viewing Diagrams Locally

HTML files use ES6 modules and require a local server (browsers block `file://` URLs):

```bash
npm run start   # kills any old server, then starts on port 9000

# Or manually
npm run dev

# Then open in browser
http://localhost:9000/
http://localhost:9000/flows/maas-inference.html
```

**One-liner alternative** (no npm needed):

```bash
python3 -m http.server 9000
```

## For AI Agents

- [CLAUDE.md](CLAUDE.md) — complete schema reference
- [docs/agent-prompt.md](docs/agent-prompt.md) — copy-pasteable prompt for any AI tool

## Links

- **This repo**: [github.com/Jaland/flowstory](https://github.com/Jaland/flowstory)
- **Upstream framework**: [flowstory.dev](https://flowstory.dev) by Noy Tzikow · [noyitz/flowstory](https://github.com/noyitz/flowstory)

## License

Apache 2.0
