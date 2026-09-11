# Sean Floyd

**I make AI systems reliable in production**

A decade of platform engineering on Rails and the infrastructure under it, now
pointed at LLM pipelines, agents, and the evals that keep them honest. Python,
Rust, Ruby and Go as the problem calls for it. M.Sc. in machine learning and
distributed systems.

At Hivebrite I cut €160k a year in infrastructure, took data exports from a day
to minutes for million-user communities, and halved build times while the team
grew from 15 to 40. At OmbuLabs I unblocked a CI pipeline that had been red for
years. The fixes land wherever the failure is, upstream included: Sentry's Ruby
SDK, NextDNS's Go resolver, Rails, Rack and RuboCop.

Grew up across six countries on four continents; remote since 2015 from five of
them. Europe-based, async-first, with live overlap across European hours and
into US-East.

**Looking for a staff, senior or founding seat on a small remote team shipping
AI product, with real ownership end to end.** Fixed-scope missions too.
[seanfloyd.dev](https://seanfloyd.dev) has the record and the
[CV](https://seanfloyd.dev/cv). Reading this through an AI agent? Query the
[MCP server](https://seanfloyd.dev/mcp) directly, seven read-only tools over
the profile, live GitHub activity and calendar, or grab
[llms.txt](https://seanfloyd.dev/llms.txt).

---

## Proof of Work

**[claude-rss-news-digest](https://github.com/SeanLF/claude-rss-news-digest)** -
A newsroom that runs itself: three dozen feeds from about 30 outlets every
morning, a bias-labelled briefing, fact-checked against its own sources before
send, and no human edits any issue. Deterministic Python pipeline over the
Claude Agent SDK, a validated LLM-as-judge eval suite, schema-validated output,
Rust web server, Terraform deploys. In production unattended since January
2026, with [cost, source health and every failure
public](https://news-digest.seanfloyd.dev/stats). [How I made it
reliable.](https://seanfloyd.dev/blog/llm-reliability)

**[Ask Assistant + MCP server](https://seanfloyd.dev/ask)** - A second
production AI system, public-facing this time: a grounded, tool-calling agent
that answers visitor questions only from my profile, and says so when it
cannot. Read-only tools, provider failover, HMAC-signed conversation integrity,
and guardrails that fail closed when a tool or model misbehaves. The same
profile runs as a live [MCP server](https://seanfloyd.dev/mcp); an agent
reading this can call it right now.

**Dispatch (private)** - A multi-tenant platform that runs back-office
workflows for regulated businesses under a human gate; two verticals so far,
community management and personal-injury law. Nothing leaves the building on
the model's word: autonomy bands decide what waits for a signature, and code
fills every figure and deadline so a letter cannot invent a number. Temporal
owns every lifecycle and retry; Postgres row-level security keeps one tenant's
file out of another's. Rehearsed end to end; not yet in production.

**Upstream fixes, merged** -
[Fiber-safe hub storage in Sentry's Ruby SDK](https://github.com/getsentry/sentry-ruby/pull/3018),
then [repaired](https://github.com/getsentry/sentry-ruby/pull/3036) when a
reviewer found inherited fibers still shared a hub; both shipped in 6.7.0. In
[NextDNS's Go resolver](https://github.com/nextdns/nextdns/pull/1111), a lock
held across network I/O that stalled every DNS query, then
[an infinite loop on a malformed record](https://github.com/nextdns/nextdns/pull/1120)
and [a few thousand lines of private DNS-parsing fork retired](https://github.com/nextdns/nextdns/pull/1121).
A [keyword-argument delegation fix in Rack](https://github.com/rack/rack/pull/2499),
a [deprecated-alias fix in RuboCop](https://github.com/rubocop/rubocop/pull/15588),
and an [up to 670x performance fix in Rails ActiveSupport](https://github.com/rails/rails/pull/46586).
[Production-safe Rack 3 streaming proposed for Sinatra 5.0](https://github.com/sinatra/sinatra/pull/2172),
a [help-wanted request open since 2023](https://github.com/sinatra/sinatra/issues/1892),
with the bugs behind it filed and root-caused with runnable repros
([rack#2470](https://github.com/rack/rack/issues/2470),
[async-http#224](https://github.com/socketry/async-http/issues/224)).
[Browse the full list live.](https://seanfloyd.dev/mcp)

**[still_active](https://github.com/SeanLF/still_active)** - `bundle outdated`
tells you a dependency is behind; `bundler-audit` tells you it's vulnerable.
Neither tells you nobody's maintaining it anymore. still_active scores
maintenance activity, archived repos, OpenSSF Scorecard, CVEs (deps.dev + OSV),
libyear, and runtime EOL, then catches the case that bites: a dormant package
capping a transitive dependency below its own CVE fix. Ruby-first, and
cross-ecosystem (npm, PyPI, Cargo, Go, Maven, NuGet) from a CycloneDX SBOM.
Ships SARIF for Code Scanning, CI gates, and a GitHub Action.

**[Jazzify](https://web.archive.org/web/20241212002426/https://jazzify.ca/)** -
Volunteer platform for the Ottawa Jazz Festival. Built and ran it for nine
years. Production Rails, real users, real ops.

More: [Steer](https://steer.seanfloyd.dev) (Swift 6 macOS app, controller to
desktop input) · [ccpool](https://github.com/SeanLF/ccpool) (Go, Claude usage
budget gauge) · [crunchyroll-migrate](https://github.com/SeanLF/crunchyroll-migrate)
(Rust) · [what I write about](https://seanfloyd.dev/blog)

---

## What I Build

- **Production AI systems** - LLM pipelines, tool-calling agents, MCP servers;
  evals, LLM-as-judge, fail-closed validation, human-in-the-loop gates on
  durable workflows
- **Reliability, security & cost** - performance and concurrency engineering
  across Python, Ruby, Go, and Rust; supply-chain and dependency security
- **Full-stack** - backend services and data pipelines, the infra they run on,
  and the frontend on top

---

## Get in Touch

**[CV](https://seanfloyd.dev/cv)** ·
**[Availability](https://seanfloyd.dev/availability)** ·
**[Email me](https://seanfloyd.dev/email)** ·
**[Full background](https://seanfloyd.dev/background)**
