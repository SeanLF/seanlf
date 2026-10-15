# Sean Floyd

**Staff-level product engineer. I ship AI product end to end.**

Design, build, run, carry the pager. LLM pipelines and agents in production,
with evals and guardrails that fail closed. Ten years on Rails platforms with
million-user communities before that; M.Sc. in machine learning and
distributed systems.

Europe-based, remote or hybrid since 2015, async-first, with live overlap across European
hours and into US-East. Looking for a staff, senior or founding seat on a small
remote team shipping AI product.
[seanfloyd.dev](https://seanfloyd.dev) has the record and the
[CV](https://seanfloyd.dev/cv). Reading this through an AI agent? Start at
[llms.txt](https://seanfloyd.dev/llms.txt).

---

## Shipped

**[news-digest](https://github.com/SeanLF/news-digest)** - An AI news desk that
runs itself: 37 feeds from 30 outlets every morning, a bias-labelled briefing,
every headline fact-checked against its sources before send, no human edits any
issue. TypeScript on Temporal (a crashed run resumes where it stopped), Claude
Agent SDK stages with schema-validated output, Postgres. The model never sees a
URL, so nothing it writes can smuggle a link in. In production unattended since
January 2026, with [cost, source health and every failure
public](https://news-digest.seanfloyd.dev/stats).

**[Steer](https://steer.seanfloyd.dev)** - Swift 6 macOS app that turns a game
controller into full desktop input: cursor, typing, scroll, media keys, haptics,
gyro mouse, radial menu. Built alone, from code to website.

**[still_active](https://github.com/SeanLF/still_active)** - Published RubyGem.
`bundle outdated` says a dependency is behind; `bundler-audit` says it is
vulnerable; neither says nobody maintains it. still_active scores maintenance
activity, archived repos, OpenSSF Scorecard, CVEs and libyear, and catches a
dormant package holding a dependency below its own CVE fix. Ruby native; npm,
PyPI, Cargo, Go, Maven and NuGet through a CycloneDX SBOM. SARIF, CI gates, a
GitHub Action.

**[ccpool](https://github.com/SeanLF/ccpool)** - Go binary that turns a Claude
subscription's "percent used" into dollars left and a keep-going-or-stop call,
so an overnight loop does not burn the week by Tuesday.

**Dispatch (private)** - Multi-tenant platform for back-office work in regulated
businesses, under a human gate. Autonomy bands decide what waits for a
signature; code fills every figure and deadline, so a letter cannot invent a
number. Temporal owns every lifecycle; Postgres row-level security isolates
tenants. Rehearsed end to end; not yet in production.

## Upstream fixes

When something breaks, I follow it to the root.
[Fiber-safe hub storage in Sentry's Ruby SDK](https://github.com/getsentry/sentry-ruby/pull/3018),
[a lock held across network I/O in NextDNS's Go resolver](https://github.com/nextdns/nextdns/pull/1111),
[a keyword-argument delegation fix in Rack](https://github.com/rack/rack/pull/2499),
and [up to 670x on long ASCII strings in Rails ActiveSupport](https://github.com/rails/rails/pull/46586).

## Earlier

At Hivebrite I cut €160k a year from the CI bill and took data exports from a
day to minutes for million-user communities. At OmbuLabs I got a CI pipeline
that had been red for years green again.

---

**[CV](https://seanfloyd.dev/cv)** ·
**[Availability](https://seanfloyd.dev/availability)** ·
**[Writing](https://seanfloyd.dev/blog)** ·
**[Email](https://seanfloyd.dev/email)**
