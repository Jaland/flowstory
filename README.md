# FlowStory

AI-agent-first animated flow diagram framework. Define architecture flows in JSON — the engine handles canvas rendering, step-by-step animation, and interactive playback.

## What Makes FlowStory Different

- **AI-agent-first**: Designed for Claude, GPT, and other AI tools to generate diagrams programmatically — not drag-and-drop
- **Animated storytelling**: Step-by-step narrative flows that tell a story, not static diagrams
- **Declarative JSON**: Define nodes, flows, tooltips, and inspector mutations in a single JSON file
- **Zero dependencies**: Pure canvas-based rendering, no external libraries

## Quick Start — Generate a Diagram in 2 Minutes

**No install needed.** Open Claude Code, paste one prompt, get an animated diagram.

**[Quick Start Guide](docs/quick-start-prompt.md)** — step-by-step instructions with the prompt to copy-paste.

## Live Examples

**MaaS Flow Diagrams:**
- [MaaS Inference Flow](https://jland-redhat.github.io/flowstory/flows/maas-inference.html) — Auth, rate limiting, and model serving
- [MaaS Key Minting](https://jland-redhat.github.io/flowstory/flows/maas-key-minting.html) — API key generation and storage
- [MaaS Multi-Tenancy](https://jland-redhat.github.io/flowstory/flows/maas-multi-tenancy.html) — Complete multi-tenant architecture
- [MaaS Policy Creation](https://jland-redhat.github.io/flowstory/flows/maas-policy-creation.html) — Kubernetes policy reconciliation

**Other Examples:**
- [AI Inference Gateway](https://jland-redhat.github.io/flowstory/examples/ai-gateway/index.html) — Red Hat AI Gateway architecture

## Viewing Diagrams Locally

HTML files use ES6 modules and require a local server (browsers block `file://` URLs):

```bash
# Clean start (kills any old server first)
npm run start

# Or manually
npm run dev        # Start server on port 9000
npm run stop       # Stop server

# Then open in browser
http://localhost:9000/flows/maas-inference.html
```

**One-liner alternative** (no npm needed):
```bash
python3 -m http.server 9000
```

## For AI Agents

See [CLAUDE.md](CLAUDE.md) for the complete schema reference.

See [docs/agent-prompt.md](docs/agent-prompt.md) for a copy-pasteable prompt for any AI tool.

## Examples

- [AI Inference Gateway](examples/ai-gateway/) — Red Hat AI Gateway architecture flow
- [Hello World](examples/hello-world/) — Minimal 3-node example

## Gallery

Browse examples on [GitHub Pages](https://Jaland.github.io/flowstory/).

## License

Apache 2.0
