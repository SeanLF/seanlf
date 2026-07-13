# Sean Floyd

**I make AI systems reliable in production**

A decade of platform engineering rigour - €160k/yr infrastructure savings,
systems serving 1M+ users, open-source contributor across the Ruby web stack
(Rails, Sinatra, Rack, async) - now applied to making LLM
pipelines, agents, and evals dependable in production. I work across Python,
Rust, and Ruby as the problem calls for it. M.Sc. in ML / distributed systems.

At Hivebrite I cut €160k/year in infrastructure costs, took data exports from
days to minutes, and halved build times while the engineering team grew from 15
to 40. Now I bring that same production discipline to flaky LLM systems - I care
about owning systems, not just passing through them.

Grew up across 6 countries (diplomatic family). 4+ years remote across 5
continents; async-first, with live overlap across European hours and into
US-East.

Available for B2B contract or fractional work (open to full-time for the right
role), remote, with genuine ownership over systems that matter.
[seanfloyd.dev](https://seanfloyd.dev) has the full story. Reading this through
an AI agent? Query my [MCP server](https://seanfloyd.dev/mcp) directly - seven
read-only tools over my profile, live GitHub activity, and calendar - or grab
[llms.txt](https://seanfloyd.dev/llms.txt).

---

## Proof of Work

**[claude-rss-news-digest](https://github.com/SeanLF/claude-rss-news-digest)** -
Production AI system, built end-to-end: deterministic Python pipeline, five
Claude curation stages over the Agent SDK, a validated LLM-as-judge eval suite,
schema-validated output, Rust web server, Terraform deploys. [Runs unattended
every morning - watch it live.](https://news-digest.seanfloyd.dev/stats) [How I
made it reliable.](https://seanfloyd.dev/blog/i-stopped-hoping-my-llm-would-cooperate)

**[Ask Assistant + MCP server](https://seanfloyd.dev/ask)** - A second
production AI system, public-facing this time: a grounded, tool-calling agent
that answers visitor questions only from my profile - read-only tools, provider
failover, HMAC-signed integrity, and guardrails that fail closed when a tool or
model misbehaves. The same profile runs as a live
[MCP server](https://seanfloyd.dev/mcp): seven read-only tools over my profile,
GitHub activity, and calendar. An agent reading this can call it right now.

**[Rails & upstream contributions](https://github.com/rails/rails/pull/46586)** -
40+ contributions across 29 upstream projects (7 merged PRs, plus open PRs and
maintainer-resolved bugs). Merged a 20x-670x performance fix to Rails
ActiveSupport and, in
[NextDNS's Go resolver](https://github.com/nextdns/nextdns/pull/1111), root-caused
and fixed a lock held across network I/O that stalled every DNS query. Designed
and proposed
[production-safe Rack 3 streaming for Sinatra 5.0](https://github.com/sinatra/sinatra/pull/2172) -
a long-standing help-wanted feature - and filed the bugs behind it: a
Rack::Deflater crash on streaming bodies (rack#2470) and an HTTP/1
client-disconnect edge case in async-http (#224).
[Browse the full list live.](https://seanfloyd.dev/mcp)

**[still_active](https://github.com/SeanLF/still_active)** - `bundle outdated`
tells you a dependency is behind; `bundler-audit` tells you it's vulnerable.
Neither tells you nobody's maintaining it anymore. still_active scores
maintenance activity, archived repos, OpenSSF Scorecard, CVEs (deps.dev + OSV),
libyear, and runtime EOL - then catches the case that bites: a dormant package
capping a transitive dependency below its own CVE fix. Ruby-first, and
cross-ecosystem (npm, PyPI, Cargo, Go, Maven, NuGet) from a CycloneDX SBOM.
Ships SARIF for Code Scanning, CI gates, and a GitHub Action.

**[Jazzify](https://web.archive.org/web/20241212002426/https://jazzify.ca/)** -
Volunteer platform for Ottawa Jazz Festival. Built and ran it for 9 years.
Production Rails, real users, real ops.

More: [Steer](https://steer.seanfloyd.dev) (Swift 6 macOS app - controller to
desktop input) · [crunchyroll-migrate](https://github.com/SeanLF/crunchyroll-migrate)
(Rust) · [ccpool](https://github.com/SeanLF/ccpool) (Go - Claude usage budget
gauge) · [what I write about](https://seanfloyd.dev/blog)

---

## What I Build

- **Production AI/LLM systems** - Claude Agent SDK pipelines, MCP servers,
  schema-validated output, evals and LLM-as-judge, pipelines that run unattended
- **Reliability & cost** - performance engineering, infrastructure
  optimization, CI/CD, monitoring (Datadog, OpenTelemetry)
- **Platform engineering** - Rails, PostgreSQL, Redis, Sidekiq, API
  architecture (Grape, gRPC, OAuth2), Kubernetes, Terraform

---

## Get in Touch

**[Check availability](https://seanfloyd.dev/availability)** ·
**[Email me](https://seanfloyd.dev/email)** ·
**[Full background](https://seanfloyd.dev/background)**
