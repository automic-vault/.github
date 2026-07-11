# Automic Vault - Marketing Plan v1

**Prepared by:** Codex
**For:** Automic Vault founder / leadership review
**Date:** 2026-06-02
**Status:** Draft v1 - for team review

## 1. Executive summary

This plan optimizes Automic Vault for a specific first year: make it the canonical local security boundary for developers running AI coding agents on Macs, then decide whether the adoption pattern supports a commercial team plan, support plan, or enterprise motion. The plan does not assume paid acquisition, a SaaS funnel, or known CAC because the available materials do not contain ARR, paid conversion, retention, or customer-count data. It treats those as the highest-impact open decisions.

The growth thesis is simple: Automic Vault should win before the category becomes crowded by being more concrete than everyone else. The product does not sell vague "AI safety." It shows package roots, command lines, secret names, file paths, approval requests, and local hazard states. That is the advantage. The marketing plan should keep that advantage visible across the homepage, docs, package pages, incident writeups, GitHub, launch content, and every activation flow.

**Big bet 1 - Own the local agent-runtime boundary.** The market will produce many generic "secure AI agents" claims. Automic Vault has a better wedge: "Secure the tools you brew install." That line connects founder authority, Homebrew familiarity, local developer risk, and the product's actual control plane. The first 90 days should align every public surface around that frame: homepage, README, `llms.txt`, schema, docs, download, pricing, GitHub release metadata, and high-intent pages like `.env`, GitHub CLI, AWS CLI, MCP secrets, and approval gates.

**Big bet 2 - Turn the package catalog into a discovery engine, not a crawlable appendix.** The package catalog is already large enough to create long-tail search and AI-citation surface. The risk is that it drowns out the core product pages. The plan fixes that by adding topical package hubs and internal links from package pages to the right core guides: cloud CLIs to AWS credential security, source-control tools to GitHub token security, package publishers to approval gates, dotenv-adjacent packages to `.env` protection, and agent tool packs to docs and download.

**Big bet 3 - Instrument activation before scaling distribution.** A developer-security product can get attention without knowing whether attention turns into protected usage. Paid acquisition should wait until the team can answer four questions: who downloaded, who installed, who completed a first protected action, and who came back. The proposed activation event is not "visited the site." It is one of: first scan run, first secret saved, first secret injected, first approval gate completed, or first contained agent session. Until those events are measured, acquisition work should prioritize cheap compounding channels: SEO, GitHub, founder-led content, technical docs, incident analysis, and DevRel.

Plausible 12-month outcome:

- Automic Vault has one coherent public claim repeated across website, README, schema, `llms.txt`, release notes, profiles, and founder narrative.
- GitHub, docs, package pages, and download funnel report weekly adoption and activation data.
- Core high-intent pages are deep enough to serve as AI and search citation targets.
- Package pages become internal-link distributors into topic hubs, not isolated pages.
- A repeatable incident-response content motion exists for npm, PyPI, VS Code, Homebrew, MCP, and CLI credential theft stories.
- The team has made a deliberate revenue decision: remain free OSS for adoption, add paid support, add team policy/approval features, or begin an enterprise local-agent-security motion.

90-day priorities:

1. Align site, README, `llms.txt`, schema, titles, meta descriptions, and release metadata around "Secure the tools you brew install."
2. Define and instrument the activation funnel: visit -> download -> install -> first scan -> first protected action -> repeat use.
3. Expand and internally link the commercial pages: download, pricing, GitHub CLI, AWS CLI, `.env`, secret scanner, MCP secrets, approval gates, and `av trace`.
4. Add package-topic hubs and related links from package pages to guide pages.
5. Publish the canonical founder explainer on `mxcl.dev` and cross-link it to site, GitHub, docs, and download.
6. Establish the operating scoreboard and decide whether Q2 is adoption-only or the first commercial packaging sprint.

## 2. Strategic frame

### What Automic Vault is, in one sentence

Automic Vault is a local macOS package manager, secrets manager, and command approval system for AI coding agents: it keeps developer secrets out of plaintext files and model context, installs agent-used tools under controlled roots, and asks before sensitive tool actions execute.

### The category we're claiming

Automic Vault should claim **local runtime security for AI coding agents**. It is not a cloud vault, a generic endpoint security dashboard, a prompt firewall, or an agent wrapper. It is the local boundary beneath the agent session: packages, secrets, command execution, approval gates, local detectors, and the GUI/CLI surfaces that show what is happening.

The category language should stay concrete:

- "Secure the tools you brew install."
- "The secrets manager for the open source ecosystem."
- "Keep the command. Remove the easy-read secret."
- "Approve the tool action before credentials or infrastructure authority are used."

The phrase "from the creator of Homebrew" is an authority proof, not the product claim. It should support the story after the first frame lands. The first frame should be what the user can do with the product.

### Who we're for

Automic Vault is for developers, founders, and security-conscious teams who run AI coding agents on local Macs and need those agents to use real command-line tools without inheriting every credential and writable package path on the machine.

Distilled ICP:

| Segment | What they say | What they really need | Best first message |
|---|---|---|---|
| AI-heavy solo developers | "I use Codex/Claude Code/Cursor and I don't want it reading everything." | A practical local boundary that does not break their workflow. | "Scan local dev-tool secrets before an agent run." |
| Technical founders | "Agents are in our repo and our terminals now." | Confidence that local machine credentials are not ambient authority. | "Give agents tools without handing them every credential." |
| Security-conscious engineering teams | "We have 1Password/Vault, but laptops still have readable config." | Endpoint-level control around CLIs, package tools, and agent sessions. | "Central vaults manage secrets. Automic Vault controls local agent use." |
| Open-source package maintainers | "A compromised tool or publish command could burn us." | Approval gates around high-risk package-manager actions. | "Gate publish, release, and credential use where the tool runs." |
| Isotope / metadata contributors | "I can describe risky command shapes for a package." | Stable manifest rules, reviewable policy, and contributor pathways. | "Help map package-specific approval boundaries." |

The stated problem is agent secret exposure. The real problem is ambient authority: local files, package roots, shell config, CLI tokens, credential helpers, MCP configs, and package-publish permissions were designed around a trusted human at a keyboard. Agents and compromised tools change that assumption.

### Business-model logic

The current public pricing page says Automic Vault is free open-source software under Apache License 2.0 and does not currently publish paid hosted, team, pro, or enterprise plans. The v1 plan therefore treats adoption and activation as the primary year-one objective until the team explicitly chooses a paid model.

Potential revenue paths, in order of near-term plausibility:

1. **Free OSS adoption first.** Maximize GitHub, downloads, protected events, package catalog authority, and developer trust. Commercialization waits until usage patterns reveal the buyer.
2. **Paid support / implementation.** Sell setup help, package hardening guidance, and team rollout support to security-conscious engineering teams.
3. **Team policy tier.** Add shared policy, audit logs, managed approval profiles, team-level package rules, and reporting.
4. **Enterprise local agent security.** Sell to organizations that need local AI-agent runtime controls alongside existing vault, endpoint, and identity tooling.
5. **Hosted services.** Not recommended for year one unless the product direction changes. The brand promise is local-first trust.

The compounding channel thesis is owned technical authority: docs, package pages, package-risk data, GitHub releases, founder narrative, incident analysis, and AI-readable site files.

### Brand voice non-negotiables

The repo already has strong voice rules. The plan preserves them.

Use:

- Concrete package names: `gh`, `awscli`, `npm`, `uv`, `docker`, `curl`.
- Concrete files: `.env`, `~/.netrc`, `.npmrc`, `~/.aws/credentials`, MCP config.
- Concrete actions: scan, harden, gate, approve, deny, inject, contain, trace.
- Calm technical claims: "This does not make agents safe. It removes ambient privilege."
- Direct CTAs: "Download Automic Vault", "Run the scanner", "Read docs", "View source".

Avoid:

- Generic "AI safety" language.
- Crypto, wallet, token, coin, exchange, or speculative-finance metaphors.
- Enterprise security theater.
- Black-box automation claims.
- Sparkle-copy, vague acceleration language, and "10x" promises.
- Decorative risk language where every state feels equally urgent.

The product should sound like it was built by someone who has operated package managers, credential helpers, and Mac apps in production.

## 3. Current state

**Scoring note:** This section is scored from materials. Private customer, revenue, analytics, and funding data were not available.

### Team composition

| Person / role | Current evidence | Marketing surface area |
|---|---|---|
| Founder / engineering owner | Repo, brand docs, website, native app, CLI, package catalog, release cadence. | Product direction, copy, technical content, GitHub, release notes, developer credibility, website implementation. |
| Dedicated marketing owner | Not visible in materials. | Gap. A first marketing hire is not required before Q1 execution, but a pi-shaped Product Marketing + Content/Growth Lead becomes useful once adoption data shows commercial potential. |
| Contractors / agencies | Not visible in materials. | Optional for content production, technical SEO, video, and design once briefs are narrow. |
| Community / contributor owners | Not formalized in materials. | Gap. Package metadata and isotope contribution pathways can become referral and DevRel surface if structured. |

The current team should not hire a pure paid-media tactician first. If hiring becomes necessary, the first hire should be a Marketing Lead or Marketing Manager with product marketing plus technical content/growth depth. The job is to preserve the concrete voice while turning product facts into distribution.

### Marketing budget

Known from materials:

- Paid acquisition: unknown; no active paid evidence.
- Tooling: GitHub, static site, PostHog telemetry in app code, possible local SEO/GEO tooling from audits.
- Retainers: unknown.
- Headcount: unknown.
- Revenue / ARR: unknown.
- Blended CAC: unknown.
- Spend as percent of ARR: cannot compute.

Current tier assumption: **Tier 1 - bootstrapped / pre-seed operating posture.** This is not a judgment about funding. It is the safest planning assumption until paid budget, revenue model, and CAC are known. Tier 1 means organic channels, founder-led authority, docs, SEO, GitHub, DevRel, and zero broad paid acquisition.

### Phase of growth

Automic Vault appears to be in the **pre-revenue or earliest adoption phase** for a developer tool. The GitHub repository was created on 2026-05-04, latest release checked was `v1.14.1` on 2026-06-01, and public GitHub authority is still early at 21 stars and 1 fork during the metadata check. That is normal for a new open-source developer-security product.

The binding constraint is not ad budget. The binding constraint is proof of protected usage: downloads, installs, first scans, first saved secrets, first approval gates, first contained agent sessions, and repeat use.

### What's already done

| Asset | Status | Marketing leverage |
|---|---|---|
| Product and brand docs | Strong | Clear category, voice, anti-references, design principles, and ICP. |
| GitHub repo | Live and active | Source credibility, release cadence, open-source trust, developer distribution. |
| macOS app and CLI | Shipping | Product is concrete, not vapor. Enables screenshot, demo, and docs-led activation. |
| Download path | Live | Direct CTA exists. Needs measurement and better page depth. |
| Pricing page | Live | Clear free OSS stance. Needs commercial-decision framing and buyer FAQ. |
| SEO audit | Completed 2026-06-01 | Gives immediate acquisition backlog. |
| GEO audit | Completed 2026-05-31 | Gives AI-citation and entity-authority backlog. |
| High-intent pages | Live | Pages exist for `.env`, AWS CLI, GitHub CLI, MCP, approval gates, scanner, HashiCorp comparison. Several need more depth. |
| Package catalog | Large static surface | Major long-tail opportunity. Needs internal link architecture and topic hubs. |
| Blog incident content | Live | Strong category-specific proof pattern: show what Automic Vault would have blocked. |
| `llms.txt` | Live locally | Strong AI-search asset. Needs release-version stamping and copy alignment. |
| PostHog telemetry code | Present in app | Start of measurement layer. Event set is currently too narrow for full funnel. |

### What's in-flight or likely in-flight

| Item | Status | Blocker |
|---|---|---|
| Production alignment with latest local positioning | Partly done locally, audit said production was stale | Deployment and verification across schema, `llms.txt`, sitemap, README, homepage. |
| High-intent page expansion | Pages exist | Need content depth, FAQ schema, examples, and internal links. |
| Package page internal links | Package pages exist | Need generator/template work to add topical links. |
| Search Console / analytics feedback loop | Not visible | Need account/data access and weekly scoreboard. |
| Founder launch essay | Recommended by GEO audit | Needs founder time and canonical link strategy. |
| Commercial packaging | Not defined | Needs adoption and activation data first. |

### What's stuck

| Issue | Cost of inaction | Action |
|---|---|---|
| Missing activation metric | Distribution work cannot be judged. | Define protected-action funnel and instrument it in Q1. |
| Product authority mostly owned-channel | AI systems and search may confuse Automic Vault with unrelated "Automic" or "Atomic Vault" entities. | Build third-party and founder-owned entity anchors. |
| Package catalog isolation | Long-tail pages can outrank or dilute core product pages. | Add topical hubs and internal link bridges. |
| Thin or shallow high-intent pages | Pages exist but may not become best citation targets. | Expand with concrete examples, FAQ, and "what changes after install." |
| Revenue model unknown | CAC/LTV and budget math cannot be defended. | Decide adoption-only vs. paid-support vs. team plan after Q1 activation data. |

### Current-state rubric snapshot

| # | Section | Score | Note |
|---:|---|---:|---|
| 1 | Positioning | 4 | Clear and distinctive. Minor risk: surfaces must stay aligned between Homebrew-founder proof and product claim. |
| 2 | Customer research | 2 | ICP is clear from founder/product intuition. No visible continuous customer research or VoC repository. |
| 3 | Homepage | 3 | Strong local direction and visual assets. Audit found production alignment gaps. |
| 4 | Sales / product pages | 3 | Core pages exist. Pricing and download need stronger buyer/use-case depth. |
| 5 | Conversion pages | 2 | Several use-case pages exist but depth and conversion architecture vary. |
| 6 | Competitor comparison | 2 | HashiCorp comparison exists. Needs adjacent alternatives and "complements vs replaces" framing. |
| 7 | Resources / content | 4 | Docs, package catalog, blog, audits, package pages, and incident posts are a real base. |
| 8 | Onboarding | 2 | CLI examples and app exist. Full first-run activation path is not yet measured. |
| 9 | Email lifecycle | 0 | No lifecycle/newsletter evidence. Fine for current stage, but retention surface is missing. |
| 10 | Sales material | 1 | No B2B sales kit visible. Not required yet, but support/team motions will need it. |
| 11 | Messaging | 4 | Brand and product docs are strong. Execution needs consistency checks. |
| 12 | Pricing | 2 | Free OSS is clear. Commercial path and value metric are undecided. |
| 13 | CRO | 1 | No visible testing cadence or funnel instrumentation beyond initial telemetry. |
| 14 | GTM launches | 2 | Release cadence exists. Structured launch motion not yet visible. |
| 15 | Ads | 0 | No paid acquisition. Appropriate for current stage. |
| 16 | SEO | 3 | Strong technical foundation and large surface; authority and core-page depth are early. |
| 17 | Internationalization | 2 | Locales exist, but audits found thin localized support pages. |

**Total: 35 / 85 (41%).**

The shape is strong product, strong voice, strong owned technical base, weak measurement, weak customer proof, weak commercial funnel, and early external authority. That shape makes Sections 4 and 5 the longest: acquisition must compound through technical authority, but activation has to become measurable before spend scales.

## 4. Acquisition

### Current state

Automic Vault already has more acquisition surface than many early developer tools: a public repo, direct download, static docs, package catalog, SEO landing pages, incident posts, `llms.txt`, schema, screenshots, and founder authority. The problem is not absence of surfaces. The problem is sequencing and authority transfer.

Today the acquisition engine should be organic, technical, and founder-led. Paid media is a future layer, not a Q1 default.

### Move 1 - Alignment as acquisition

Every public surface should repeat the same claim in compatible language: "Secure the tools you brew install." This includes homepage H1, title, meta description, README, GitHub repo description, `llms.txt`, `llms-full.txt`, JSON-LD, release notes, download page, pricing page, and founder profiles.

Why this matters: AI answer engines and search engines resolve entity meaning through repeated, stable descriptions. A new product with a name collision cannot afford mixed category claims. The founder proof should be present, but the repeated product claim should describe the product first.

Skills: `product-marketing`, `copy-editing`, `ai-seo`, `schema`.
Tools: GitHub, static site generator/scripts, Search Console, schema validator, `scripts/generate-llms-full.mjs`.

### Move 2 - Core SEO/GEO pages become citation targets

The existing high-intent pages should each answer five concrete questions:

- What exact local risk does this page address?
- Which files, tools, commands, or credentials are involved?
- What changes after installing Automic Vault?
- What is Automic Vault not replacing?
- What command or workflow can the reader run now?

Priority pages:

1. `/download/`
2. `/pricing/`
3. `/secret-scanner-for-ai-agents/`
4. `/stop-ai-agents-reading-env-files/`
5. `/github-cli-token-security-ai-agents/`
6. `/secure-aws-cli-credentials-ai-agents/`
7. `/mcp-secrets-management/`
8. `/ai-agent-approval-gates/`
9. `/av-trace/`
10. `/hashicorp-vault-for-ai-agents/`

Skills: `seo-audit`, `ai-seo`, `schema`, `content-strategy`, `copywriting`.
Tools: Search Console, Ahrefs/DataForSEO if available, GitHub, browser rendering checks.

### Move 3 - Package catalog as internal-link engine

Package pages should not just say "install this package." They should answer "why secure this package with Automic Vault?" and link to the relevant guide. The package catalog can create topical authority only if package pages distribute users and crawlers toward product education.

Initial hub structure:

| Hub | Package families | Core guide links |
|---|---|---|
| Cloud CLI credential risk | `awscli`, `azure-cli`, `gcloud`, `opentofu`, `kubectl`, `helm` | AWS credentials, approval gates, PAM for agents |
| Source-control token risk | `gh`, `git`, `glab`, package release tools | GitHub CLI token security, approval gates |
| Package-publish risk | `npm`, `uv`, `twine`, `cargo`, release CLIs | approval gates, package compromise posts |
| Dotenv/plaintext risk | `dotenv`, `sops`, `age`, app frameworks | `.env` page, API key management |
| Agentic toolkit | media/build/search/OCR/runtime tools | Agentic Toolkit, download, docs |

Skills: `programmatic-seo`, `schema`, `ai-seo`, `content-strategy`.
Tools: package page generator, `data/pkg-pages`, Search Console coverage reports.

### Move 4 - Incident-response content

The blog pattern is strong: explain a real package or developer-tool compromise, then show the specific local theft phase Automic Vault would have changed. This fits the voice because it is concrete and risk-boundary oriented.

The cadence should be event-driven plus one planned monthly retrospective:

- "What got stolen?"
- "Where did the tool look?"
- "Which local files or credential helpers mattered?"
- "Which Automic Vault boundary would have changed the outcome?"
- "What it would not have prevented."

Skills: `content-strategy`, `copywriting`, `ai-seo`, `social`.
Tools: GitHub, RSS/security feeds, package registry advisories, Search Console, `llms-full.txt` generation.

### Move 5 - Founder-led DevRel

Automic Vault has a rare founder proof: Homebrew is directly relevant to the product's category. The founder-led channel should not be inspirational marketing. It should be technical narrative:

- "Homebrew was built before AI agents existed."
- "Why local package roots matter."
- "Why prompt-only safety does not protect CLI tokens."
- "Why `.env` was fine until agents could read it."
- "How approval gates should happen at meaningful tool boundaries."

Recommended channels:

- Canonical launch/explainer on `mxcl.dev`.
- GitHub release notes with product proof and screenshots.
- Hacker News / Reddit only where discussion is technical and transparent.
- Conference talks and podcast interviews with developer/security audiences.
- X/LinkedIn excerpts, but only if founder bandwidth exists.

Skills: `social`, `launch`, `developer-relations`, `copy-editing`, `podcast tours`.
Tools: GitHub, `mxcl.dev`, Typefully if used, calendar/event tracking.

### Move 6 - Entity authority and third-party anchors

The GEO audit identified early product-level authority. The plan should build a small set of complete profiles and references rather than many abandoned accounts.

Now:

- GitHub organization and repository description aligned.
- `mxcl.dev` canonical explainer.
- Security disclosure and source links visible.
- SameAs links only to maintained profiles.

Q2:

- Product Hunt or alternative launch if activation data is ready.
- Technical podcasts.
- Relevant newsletter swaps or community sponsorships.
- Review/listing sites that are credible for developer tools, not generic SaaS directories.

Skills: `launch`, `directory-submissions`, `social`, `ai-seo`.
Tools: GitHub, site schema, founder site, directory/review platform accounts.

### Paid acquisition stance

Hold broad paid acquisition until:

- Download -> install conversion is measured.
- First protected action conversion is measured.
- A revenue model or commercial intent is chosen.
- CAC target can be bounded.

The first paid test, when ready, should be small and high-intent: Google search around "AI agent secrets manager", "secure AI coding agents", "stop AI agents reading .env", "GitHub CLI token security", and retargeting to site visitors. LinkedIn can be tested only if a B2B support/team offer exists.

### 90-day acquisition moves

| Week | Move | Owner |
|---|---|---|
| 1 | Audit and align all public product descriptions. | Founder / product owner |
| 1 | Verify schema, `llms.txt`, release version, sitemap freshness. | Engineering |
| 2 | Publish canonical founder explainer outline and draft. | Founder |
| 2 | Pick first 5 high-intent pages for expansion. | Founder + content contractor if available |
| 3-4 | Add package-page related links and first two hubs. | Engineering |
| 5-8 | Publish two incident-response posts and two page expansions. | Founder / content |
| 9-12 | Run Search Console review and reprioritize pages by impressions and citation potential. | Marketing owner |

### 12-month acquisition outlook

- Q1: alignment, instrumentation, page depth, package links.
- Q2: founder launch, incident cadence, package hubs, credible directory/profile anchors.
- Q3: DevRel expansion, talk/podcast rhythm, optional Product Hunt or GitHub-focused launch.
- Q4: paid pilot only if commercial path and activation data support it.

## 5. Activation

### Current state

The product has usable activation surfaces: download, install script, CLI examples, docs, native app, scanner, keychain saving, injection, containment, and approval gates. The missing piece is a measured path from first curiosity to first protected action.

For Automic Vault, activation should not be "user opened the app." The product creates value when it exposes or controls a real local boundary.

Proposed activation events:

| Activation level | Event | Why it matters |
|---|---|---|
| A0 | Download completed | Interest reached install point. |
| A1 | App opened or `av --help` run | User has local binary. |
| A2 | First `av scan --path` or scanner one-liner run | User sees local exposure. |
| A3 | First secret saved with `av save` | User moved a secret into the boundary. |
| A4 | First approved `av inject` or approval gate | User experienced controlled credential use. |
| A5 | First `av contain` agent command | User adopted the runtime boundary for agent work. |
| A6 | Repeat protected action within 7 days | Product moved from experiment to habit. |

### Move 1 - Make the first action obvious

The download and docs flow should present two first paths:

1. "Run the scanner" for risk discovery.
2. "Protect one token" for conversion into controlled usage.

The first path is lower-friction and should be the primary activation wedge. Developers are more likely to run a scanner than immediately move their secrets. Once they see a concrete path or token, the product has earned the next action.

Skills: `onboarding`, `signup`, `copywriting`, `cro`.
Tools: PostHog, CLI telemetry if privacy policy permits, docs, download page.

### Move 2 - Add activation instrumentation without violating trust

Telemetry must respect the brand: local-first, minimal, and honest. The app already includes PostHog event code for main window opened. The plan needs event expansion and a public explanation.

Recommended events:

- `download_cta_clicked`
- `installer_started` if measurable server-side
- `app_opened`
- `cli_help_invoked` if telemetry is acceptable
- `scan_completed`
- `hazard_found_count_bucket`
- `secret_saved`
- `secret_injected_after_approval`
- `approval_gate_completed`
- `contain_started`
- `repeat_use_7d`

Do not collect secret values, file contents, commands containing secrets, or sensitive paths in telemetry. Bucket counts and event names are enough.

Skills: `analytics`, `onboarding`, `privacy copy-editing`.
Tools: PostHog, server logs, GitHub release/download stats, Search Console.

### Move 3 - Improve first-run docs

The docs should be organized by boundary, not by exhaustive command list:

- "Find exposed secrets."
- "Save a secret."
- "Inject a secret into one approved command."
- "Run an agent inside containment."
- "Trace a shell installer before running it."
- "Understand approval gates."

Each path should end with a visible result. The user should not have to infer what success looks like.

Skills: `onboarding`, `copywriting`, `technical content`.
Tools: docs site, CLI examples, screenshots, terminal recordings.

### Move 4 - Use the scanner as the activation wedge

The scanner is the cleanest activation moment because it does not require the user to restructure their workflow first. It also gives content and SEO pages a concrete CTA.

Every high-intent page should have one relevant scanner CTA:

- `.env` page: scan the repo.
- GitHub CLI page: scan for readable GH token state.
- AWS CLI page: scan AWS credential files.
- MCP secrets page: scan MCP config.
- Secret scanner page: show command examples.

Skills: `cro`, `copywriting`, `onboarding`.
Tools: scanner script, docs, analytics.

### Move 5 - Concierge setup for high-signal teams

For the first 10 to 20 serious teams, offer founder-led setup calls. This is not scalable support. It is customer research disguised as activation help.

The call should answer:

- Which agents do they run?
- Which credentials are present?
- Which tools do they fear most?
- Which approval prompts are acceptable vs annoying?
- What would make this team-ready?

Skills: `customer-research`, `onboarding`, `sales-enablement`.
Tools: calendar, notes, GitHub issues, lightweight CRM/Notion.

### 90-day activation moves

| Week | Move | Owner |
|---|---|---|
| 1 | Define activation event taxonomy A0-A6. | Founder + engineering |
| 1-2 | Add/verify minimal funnel instrumentation. | Engineering |
| 2 | Rewrite download page around scanner and protected-token first paths. | Founder / marketing |
| 3-4 | Add activation CTAs to top high-intent pages. | Engineering + content |
| 5-8 | Run 10 founder-led setup/user calls. | Founder |
| 9-12 | Review A0-A6 conversion and pick one activation bottleneck to fix. | Founder + engineering |

## 6. Retention

### Current state

Retention is not visible in the materials. For a free open-source developer tool, retention should be measured as repeat protected usage, not subscription renewal. The early retention question is: after a developer runs the scanner or saves one secret, do they keep Automic Vault installed and use it again when agents or tools cross risk boundaries?

### Move 1 - Define developer-tool retention

Proposed retention metrics:

- Repeat app open or CLI use within 7 days.
- Repeat protected action within 30 days.
- Number of distinct protected boundaries used: scan, save, inject, gate, contain, trace.
- Update adoption after a release.
- GitHub watch/star/fork as weak but useful retention/community signals.
- Issue/PR contribution to package metadata or approval gates.

Skills: `analytics`, `retention`, `developer-relations`.
Tools: PostHog, GitHub API, release download stats, issue labels.

### Move 2 - Changelog as retention

Automic Vault should use public changelogs and release notes as retention assets. Developers trust tools that explain what changed and why it matters.

Each release note should include:

- New boundaries or detectors.
- New packages with approval metadata.
- Security behavior changes.
- Breaking/non-breaking status.
- One "what to try after updating" command.

Skills: `content-strategy`, `copy-editing`, `developer-relations`.
Tools: GitHub releases, website changelog, social excerpts.

### Move 3 - Lifecycle without spam

If the team adds email, keep it practical:

- Founder welcome after optional email capture.
- Monthly "new package boundaries and incident notes" newsletter.
- Critical security/update notes only when justified.
- No generic drip sequence until the product has commercial tiers.

Skills: `emails`, `copywriting`, `inbox placement`.
Tools: Resend/Buttondown/Mailchimp/Customer.io, domain authentication.

### Move 4 - Support as marketing

Every serious support issue can become one of:

- Docs improvement.
- Package page improvement.
- Detector addition.
- Approval metadata PR.
- Blog note on a concrete boundary.

The product's trust depends on showing how risk rules evolve. Support should feed the package-intelligence system.

Skills: `support-as-marketing`, `customer-research`, `content-strategy`.
Tools: GitHub issues, discussions, package metadata repo, docs.

### 90-day retention moves

| Week | Move | Owner |
|---|---|---|
| 1-2 | Define repeat-use and protected-action metrics. | Founder + engineering |
| 3-4 | Add release note template. | Founder |
| 5-8 | Create optional email capture for security/package updates. | Engineering + marketing |
| 9-12 | Convert top support/user-call issues into docs/package metadata updates. | Founder + contributors |

## 7. Referral

### Current state

For Automic Vault, referral is not coupon-based growth. It is technical recommendation: GitHub stars, package maintainers, security-minded developers, founder mentions, DevRel talks, issue/PR contributors, and teams telling other teams that the product solved a concrete local-agent risk.

Gimmicky giveaways, lifetime deals, and broad affiliate tactics conflict with the product voice.

### Move 1 - Make sharing technical and useful

The product should give users artifacts worth sharing:

- A local scan result summary with no sensitive data.
- A "package boundary added" changelog.
- A "how to secure `gh` / `awscli` / `npm publish`" guide.
- A founder incident breakdown.
- A package page that is actually useful as an operational reference.

Skills: `referrals`, `social`, `content-strategy`, `copywriting`.
Tools: GitHub, site, optional share-safe scan output.

### Move 2 - Contributor pathway as referral loop

The package metadata and isotope/contributor model can become a referral system. Contributors who add a package rule become advocates because their work is visible and useful.

Recommended pathway:

- "Request a package boundary" issue template.
- "Add approval metadata" guide.
- Package pages that credit policy contributions if appropriate.
- Monthly "new protected tools" roundup.

Skills: `developer-relations`, `community-marketing`, `referrals`.
Tools: GitHub issues/PRs, package metadata schema, website.

### Move 3 - Early adopter proof

Once 10 to 20 serious users or teams are active, collect short technical quotes. Avoid generic testimonials. Ask for quotes that include a path, package, or action.

Good quote shape:

- "Automic Vault found `~/.aws/credentials` before we let an agent run Terraform."
- "We now gate `npm publish` and `gh release` from agent sessions."
- "It made the secret path visible instead of asking us to trust the model."

Skills: `customer-research`, `sales-enablement`, `copy-editing`.
Tools: user interviews, site, docs.

### 90-day referral moves

| Week | Move | Owner |
|---|---|---|
| 3-4 | Add "request package boundary" issue template. | Engineering |
| 5-8 | Add contributor guide for approval metadata. | Engineering |
| 5-12 | Collect first 5 technical user quotes from setup calls. | Founder |
| 9-12 | Publish first "new protected tools" roundup. | Founder / marketing |

## 8. Revenue

### Current state

The pricing page says Automic Vault is free open-source software. That is a clean and trust-preserving position for the current stage. It also means standard SaaS budget math cannot be completed yet.

### Unit economics

| Metric | Value | Note |
|---|---:|---|
| ARPC | Unknown / currently $0 public plan | No paid plan published. |
| Blended CAC | Unknown | No acquisition/customer data visible. |
| Annual retention rate | Unknown | No subscription or repeat-use metric visible. |
| LTV | Unknown | Cannot calculate without monetization and retention. |
| LTV / CAC | Unknown | Blocked by CAC and LTV. |

CAC unknown is the highest-impact open decision if the company chooses a paid model.

### Revenue paths to evaluate

| Path | Fit | What must be true |
|---|---|---|
| Free OSS adoption | Strong now | Product still needs category authority and usage data more than revenue. |
| Paid support / setup | Strong Q2 candidate | Teams ask for help deploying, configuring, or interpreting package/security boundaries. |
| Team policy tier | Strong Q3 candidate | Multiple developers in one org need shared rules, audit, policy, and reporting. |
| Enterprise local-agent security | Possible Q4+ | Security buyers see endpoint agent risk as budget-worthy. |
| Hosted vault replacement | Poor near-term fit | Would dilute local-first positioning and compete with established vaults. |

### Recommended pricing posture

Q1 should not force monetization. It should produce the data needed to choose.

By end of Q1, answer:

- Are users mostly individuals or teams?
- Which protected action creates the most value?
- Are users asking for support, shared policy, audit logs, or hosted services?
- What would they pay for without weakening open-source trust?
- Does "free OSS + paid support/team controls" map to the usage pattern?

If a paid offer is needed in Q2, start with **paid team rollout/support** before adding product paywalls. It respects the local-first product and avoids prematurely restricting the tool that needs developer trust.

Skills: `pricing`, `sales-enablement`, `revops`, `customer-research`.
Tools: Stripe only if paid plans are introduced, GitHub issues, user-call notes, PostHog.

## 9. 90-day roadmap

### Weeks 1-2 - Unblock

| Move | Stage | Owner |
|---|---|---|
| Align all product descriptions around "Secure the tools you brew install." | Acquisition | Founder / engineering |
| Verify release version in schema, `llms.txt`, download, and sitemap. | Acquisition | Engineering |
| Define activation taxonomy A0-A6. | Activation | Founder + engineering |
| Add or confirm minimal event instrumentation. | Activation | Engineering |
| Rewrite download page around "Run the scanner" and "Protect one token." | Activation | Founder / marketing |
| Create weekly AARRR scoreboard template. | Measurement | Founder |

### Weeks 3-4 - Foundation

| Move | Stage | Owner |
|---|---|---|
| Expand two high-intent pages with examples and FAQ schema. | Acquisition | Marketing/content |
| Add first package-page related-link template. | Acquisition | Engineering |
| Create first two package topic hubs. | Acquisition | Engineering + content |
| Add activation CTAs to high-intent pages. | Activation | Engineering |
| Add "request package boundary" issue template. | Referral | Engineering |
| Draft founder canonical explainer. | Acquisition | Founder |

### Weeks 5-8 - Velocity

| Move | Stage | Owner |
|---|---|---|
| Publish founder explainer and cross-link from site/GitHub/docs. | Acquisition | Founder |
| Publish two incident-response posts. | Acquisition | Founder / content |
| Run 10 setup/customer-research calls. | Activation | Founder |
| Create release note/changelog template. | Retention | Founder |
| Add optional security/package update email capture. | Retention | Engineering |
| Write approval-metadata contributor guide. | Referral | Engineering |

### Weeks 9-12 - Compound

| Move | Stage | Owner |
|---|---|---|
| Review Search Console, GitHub, download, and activation data. | Measurement | Founder / marketing |
| Expand next three pages based on impressions and activation data. | Acquisition | Marketing/content |
| Publish "new protected tools" roundup. | Referral | Founder |
| Collect first 5 technical user quotes. | Referral | Founder |
| Decide Q2 posture: adoption-only, paid support, or team-policy exploration. | Revenue | Founder |
| Build Q2 roadmap from measured bottleneck. | Cross-cutting | Founder + engineering |

## 10. 12-month outlook

### Framing

Budget method: standard revenue-based and goal-based budget formulas cannot be used yet because ARR, CAC, ARPC, and annual retention are unknown. This plan uses a milestone-based Tier 1 operating budget until Q1 data exists.

Current suggested budget posture:

- Paid acquisition: $0 in Q1.
- Tools: $500-$2,000/mo if Search Console, analytics, email, and SEO tooling require paid accounts.
- Content/design/video contractors: optional and brief-driven.
- Experimental budget: founder time plus narrowly scoped contractor work, not broad ad spend.

Growth pattern: layered S-curves. The first S-curve is founder/open-source/developer credibility. The second is SEO/GEO and package-intelligence pages. The third, if data supports it, is commercial team/security adoption.

### Q1 - Months 1-3

**Funding state:** Tier 1 / organic.

**Focus:** Align the category claim, instrument activation, and turn existing surfaces into a coherent adoption funnel.

Outcomes:

- Public copy alignment complete.
- A0-A6 activation taxonomy live.
- High-intent page expansion started.
- Package-page internal link template live.
- Founder explainer published.
- Weekly AARRR scoreboard running.
- Q2 revenue posture decided.

KPI targets:

- 100% of priority public surfaces aligned with the current claim.
- 5 high-intent pages expanded or queued with owners.
- 2 package hubs live.
- Activation event dashboard live.
- 10 user/setup calls completed.

### Q2 - Months 4-6

**Funding state:** Tier 1 unless support/team revenue emerges.

**Focus:** Validate repeat adoption and deepen technical authority.

Outcomes:

- Incident-response cadence running.
- Package hubs expanded.
- Optional email/newsletter flow live.
- Contributor pathway live.
- First user quotes or case notes published.
- Paid support/team offer scoped only if customer pull exists.

KPI targets:

- 4 to 6 incident or technical content pieces shipped.
- 5 to 8 package hubs or guide-link clusters live.
- Measurable lift in organic impressions for priority queries.
- Repeat protected action tracked.
- At least 3 high-signal teams/users interviewed after real use.

### Q3 - Months 7-9

**Funding state:** Tier 1 or Tier 2 if commercial path opens.

**Focus:** Launch the strongest validated story and test commercial packaging.

Outcomes:

- Product Hunt / alternative launch only if activation data is credible.
- Developer podcasts/talks begin.
- First commercial package tested if chosen: paid setup/support or team-policy waitlist.
- Package contribution loop becomes public and repeatable.
- Docs and onboarding updated from Q1/Q2 bottlenecks.

KPI targets:

- Protected-action conversion improves from Q1 baseline.
- Repeat-use rate baseline established and improving.
- GitHub stars/forks/issues/PRs increase from early baseline.
- First paid discovery calls if commercial path chosen.
- One credible external review, talk, podcast, or newsletter mention.

### Q4 - Months 10-12

**Funding state:** Tier 1, Tier 2, or seed-style deployment depending on adoption and revenue decision.

**Focus:** Decide whether to scale distribution, hire marketing, or preserve OSS adoption as the strategic priority.

Outcomes:

- Year-one adoption story is measurable.
- Commercial motion either launched, killed, or deferred with rationale.
- Package catalog and incident content are compounding.
- First marketing hire decision made from actual workload.
- Next-year plan has defensible budget math.

KPI targets:

- North-star metric established and reviewed monthly.
- Top acquisition channel by activated users identified.
- Top activation bottleneck identified and improved.
- Commercial path has pricing hypothesis or explicit no-go decision.
- Q2-Q4 learnings compiled into plan v2.

## 11. Marketing operations stack

### Thesis

Automic Vault should run a small, technical, founder-led marketing operation. The stack is not a replacement for strategy. It is a way to turn a narrow strategic frame into repeatable outputs: pages, docs, schema, package links, incident posts, user-call synthesis, launch briefs, release notes, and measurement reviews.

### Skills mapped to AARRR stages

| Stage | Primary skills | Supporting skills |
|---|---|---|
| Acquisition | `seo-audit`, `ai-seo`, `programmatic-seo`, `content-strategy`, `launch`, `social`, `developer-relations` | `schema`, `competitors`, `directory-submissions`, `podcast tours`, `copy-editing` |
| Activation | `onboarding`, `signup`, `cro`, `copywriting`, `analytics` | `ab-testing`, `marketing-psychology`, `paywalls` if paid tier exists |
| Retention | `emails`, `churn-prevention`, `support-as-marketing` | `copy-editing`, `analytics`, `developer-relations` |
| Referral | `referrals`, `community-marketing`, `developer-relations` | `social`, `emails`, `customer-research` |
| Revenue | `pricing`, `sales-enablement`, `revops` | `customer-research`, `ab-testing`, `paywalls` |
| Cross-cutting | `product-marketing`, `marketing-ideas`, `customer-research` | `copywriting`, `copy-editing`, `analytics` |

### Tools and APIs by stage

| Stage | Existing or likely tools | Q1/Q2 additions |
|---|---|---|
| Acquisition | GitHub, static site, package page generator, `llms.txt`, sitemap, SEO/GEO audits | Search Console, Ahrefs/DataForSEO if available, schema checks, Typefully if social cadence exists |
| Activation | Download page, install script, CLI, app, PostHog app event | Expanded privacy-safe event taxonomy, server download stats, docs CTA tracking |
| Retention | GitHub releases, app update flow, docs | Optional email/newsletter provider, release-note template |
| Referral | GitHub issues/PRs, package metadata | Contributor guide, package-boundary request template, quote capture |
| Revenue | Pricing page | Stripe only after paid offer, lightweight CRM/Notion for support/team prospects |
| Cross-cutting | GitHub, Notion/local docs, repo materials | Weekly AARRR scoreboard |

### Concrete operating example

Week one demonstration of the stack:

1. Use `product-marketing` and `copy-editing` to align homepage, README, `llms.txt`, and GitHub descriptions.
2. Use `seo-audit` and `ai-seo` to choose one page, such as GitHub CLI token security.
3. Use package data to link relevant `gh` and source-control package pages to that guide.
4. Use `analytics` to add a CTA event for "Run the scanner."
5. Use `content-strategy` to publish a short release note explaining exactly what changed.

This proves the operating model: one technical owner plus the skills library can ship positioning, SEO, product activation, and measurement changes without assembling a full marketing department.

### Capability unlocks by funding stage

| Stage | Headcount | Tooling | Channels live |
|---|---|---|---|
| Current Tier 1 | Founder/engineering, no dedicated marketing assumed | GitHub, static site, PostHog, Search Console, marketing skills | SEO/GEO, docs, GitHub, package pages, founder-led content, DevRel |
| Tier 2 / seed close | Add Marketing Lead or Manager, pi-shaped product marketing + content/growth | Add SEO tooling, email provider, lightweight CRM, optional paid accounts | Paid search pilot, Product Hunt/launch, newsletter, more structured DevRel |
| Tier 3 / seed deployment | Add fractional designer/content contractor | Add analytics depth, dashboard, contractor workflows | Content cadence, launch cadence, paid tests, podcast/talk cycle |
| Series A | Performance/content/design roles | Dedicated dashboard, paid tooling, agency support | Paid scaling, PR, enterprise enablement, broader events |

### Team and agency model

| Function | Owned by | Executed by |
|---|---|---|
| Strategic frame | Founder | Founder + product marketing support |
| Technical content | Founder / Marketing Lead | Founder, contractor, engineering reviewer |
| SEO/GEO | Marketing Lead | Contractor or founder with skills |
| Package page system | Engineering | Engineering |
| Activation instrumentation | Engineering | Engineering |
| Founder-led narrative | Founder | Founder, copy editor |
| Customer research | Founder | Founder / Marketing Lead |
| Commercial packaging | Founder | Founder + pricing/revops support |

## 12. Tactical idea bank

Status legend:

- **Now (Q1):** in the 90-day plan or executable with current capacity.
- **Q2:** layer in after foundation.
- **Q3+:** expansion after activation data or commercial clarity.
- **Q4+:** long-game or higher-budget.
- **Skip:** off-brand, poor fit, or blocked by business model.

| # | Idea | Stage | Status | Automic Vault note |
|---:|---|---|---|---|
| 1 | Easy Keyword Ranking | Acquisition | Now | Target agent-secret and CLI-risk long tails. |
| 2 | SEO Audit | Acquisition | Now | Already done; convert findings into backlog. |
| 3 | Glossary Marketing | Acquisition | Q2 | Glossary for approval gates, MCP secrets, agent containment. |
| 4 | Programmatic SEO | Acquisition | Q2 | Package hubs and package-risk page templates. |
| 5 | Content Repurposing | Acquisition | Now | Turn incident posts into release notes, threads, docs links. |
| 6 | Proprietary Data Content | Acquisition | Q2 | Use package-risk/catalog data for reports. |
| 7 | Internal Linking | Acquisition | Now | Package pages must link to core guides. |
| 8 | Content Refreshing | Acquisition | Q2 | Refresh pages after Search Console data. |
| 9 | Knowledge Base SEO | Acquisition | Q2 | Docs as onboarding and search surface. |
| 10 | Parasite SEO | Acquisition | Now | Founder posts on `mxcl.dev`, maybe LinkedIn/Substack. |
| 11 | Competitor Comparison Pages | Acquisition | Q2 | Compare/complement 1Password, HashiCorp Vault, Infisical, Doppler. |
| 12 | Marketing Jiu-Jitsu | Acquisition | Now | Position against prompt-only safety and cloud-only vaulting. |
| 13 | Competitive Ad Research | Acquisition | Q3+ | Only once paid/commercial path exists. |
| 14 | Side Projects | Acquisition | Q2 | Scanner and package-risk tools can serve this role. |
| 15 | Engineering as Marketing | Acquisition | Q2 | Package risk hubs and scanner output. |
| 16 | Importers as Marketing | Acquisition | Skip | No competitor data migration need yet. |
| 17 | Quiz Marketing | Acquisition | Skip | Too cute for current security voice. |
| 18 | Calculator Marketing | Acquisition | Q3+ | Credential exposure estimator only if serious. |
| 19 | Chrome Extensions | Acquisition | Skip | Product is local macOS/CLI, not browser-first. |
| 20 | Microsites | Acquisition | Q3+ | Possible incident microsite later. |
| 21 | Scanners | Acquisition | Now | Core scanner is already the activation wedge. |
| 22 | Public APIs | Acquisition | Q4+ | Package-risk data API later if demand exists. |
| 23 | Podcast Advertising | Acquisition | Q4+ | Paid host reads only after commercial model. |
| 24 | Pre-targeting Ads | Acquisition | Q4+ | Needs budget and conversion path. |
| 25 | Facebook Ads | Acquisition | Skip | Poor fit for serious dev-security wedge. |
| 26 | Instagram Ads | Acquisition | Skip | Poor fit unless visual launch asset proves demand. |
| 27 | Twitter Ads | Acquisition | Q4+ | Possible small retargeting after adoption data. |
| 28 | LinkedIn Ads | Acquisition | Q4+ | Only for B2B support/team offer. |
| 29 | Reddit Ads | Acquisition | Q4+ | Test only with transparent technical creative. |
| 30 | Quora Ads | Acquisition | Skip | Low priority. |
| 31 | Google Ads | Acquisition | Q4+ | High-intent keywords only after CAC target. |
| 32 | YouTube Ads | Acquisition | Q4+ | Needs strong demo video and commercial offer. |
| 33 | Cross-Platform Retargeting | Acquisition | Q4+ | Only after paid stack exists. |
| 34 | Click-to-Messenger Ads | Acquisition | Skip | Off-fit for developer tool. |
| 35 | Community Marketing | Acquisition | Q2 | GitHub/contributor community, not generic Discord-first. |
| 36 | Quora Marketing | Acquisition | Q2 | Answer narrow questions about agents and secrets. |
| 37 | Reddit Keyword Research | Acquisition | Now | Mine real developer language. |
| 38 | Reddit Marketing | Acquisition | Q2 | Transparent technical posts only. |
| 39 | LinkedIn Audience | Acquisition | Now | Useful if founder wants B2B/security reach. |
| 40 | Instagram Audience | Acquisition | Skip | Not aligned with current buyer. |
| 41 | X Audience | Acquisition | Now | High leverage if founder bandwidth exists. |
| 42 | Short Form Video | Acquisition | Q3+ | CLI/app demos, not trend content. |
| 43 | Engagement Pods | Acquisition | Skip | Off-brand. |
| 44 | Comment Marketing | Acquisition | Q2 | Technical comments on agent/security threads. |
| 45 | Mistake Email Marketing | Retention | Skip | Opportunistic only, not a tactic. |
| 46 | Reactivation Emails | Retention | Q2 | If optional email capture exists. |
| 47 | Founder Welcome Email | Activation | Q2 | For optional update list or setup calls. |
| 48 | Dynamic Email Capture | Activation | Q2 | Capture on docs/download, no intrusive popups. |
| 49 | Monthly Newsletters | Acquisition | Q2 | "New protected tools and incidents." |
| 50 | Inbox Placement | Retention | Now | Set SPF/DKIM/DMARC before email. |
| 51 | Onboarding Emails | Activation | Q2 | Only after first-run path is defined. |
| 52 | Win-back Emails | Retention | Q2 | For inactive update-list users or paid pilots. |
| 53 | Trial Reactivation | Retention | Skip | No trial model yet. |
| 54 | Affiliate Discovery via Backlinks | Acquisition | Q3+ | Find developer newsletters and security blogs. |
| 55 | Influencer Whitelisting | Acquisition | Skip | Paid creator ads are not a Q1/Q2 fit. |
| 56 | Reseller Programs | Acquisition | Q4+ | Possible security consultant channel later. |
| 57 | Expert Networks | Acquisition | Q4+ | Package-boundary experts later. |
| 58 | Newsletter Swaps | Acquisition | Q2 | Developer/security newsletters. |
| 59 | Article Quotes | Acquisition | Now | Founder as quote source on agent security. |
| 60 | Pixel Sharing | Acquisition | Skip | Requires paid stack and partner fit. |
| 61 | Shared Slack Channels | Acquisition | Q3+ | With security/devtool partners if real. |
| 62 | Affiliate Program | Referral | Q3+ | Only for paid support/team offer. |
| 63 | Integration Marketing | Acquisition | Q3+ | Agent tools, MCP servers, devtool ecosystems. |
| 64 | Community Sponsorship | Acquisition | Q2 | Sponsor narrow developer/security venues. |
| 65 | Live Webinars | Acquisition | Q2 | "Run an agent without ambient secrets." |
| 66 | Virtual Summits | Acquisition | Q3+ | Too much before core loop is proven. |
| 67 | Roadshows | Acquisition | Skip | Not needed at current stage. |
| 68 | Local Meetups | Acquisition | Q2 | Developer/security meetups if founder is present. |
| 69 | Meetup Sponsorship | Acquisition | Q3+ | Small, targeted only. |
| 70 | Conference Speaking | Acquisition | Now | Strong founder/category fit. |
| 71 | Conferences (owned) | Acquisition | Skip | Too early. |
| 72 | Conference Sponsorship | Acquisition | Q4+ | Only after budget unlock. |
| 73 | Media Acquisitions | Acquisition | Skip | Not stage-appropriate. |
| 74 | Press Coverage | Acquisition | Now | Founder/Homebrew/AI-agent risk is newsworthy. |
| 75 | Fundraising PR | Acquisition | Q2 | Only if funding happens. |
| 76 | Documentaries | Acquisition | Skip | Off-scope. |
| 77 | Black Friday Promotions | Acquisition | Skip | Free OSS and security category make this odd. |
| 78 | Product Hunt Launch | Acquisition | Q3+ | Only after activation data and page polish. |
| 79 | Early-Access Referrals | Referral | Q2 | Use for package boundary requests or team beta. |
| 80 | New Year Promotions | Acquisition | Q4+ | Security hygiene campaign, not discount. |
| 81 | Early Access Pricing | Acquisition | Skip | No paid plan yet. |
| 82 | Product Hunt Alternatives | Acquisition | Q3+ | AlternativeTo/BetaList if relevant. |
| 83 | Twitter Giveaways | Acquisition | Skip | Off-brand. |
| 84 | Giveaways | Acquisition | Skip | Off-brand. |
| 85 | Vacation Giveaways | Acquisition | Skip | Strongly off-brand. |
| 86 | Lifetime Deals | Acquisition | Skip | Bad fit for trust and future LTV. |
| 87 | Powered By Marketing | Acquisition | Q4+ | Possible "protected by Automic Vault" package badge later. |
| 88 | Free Migrations | Acquisition | Skip | No migration model. |
| 89 | Contract Buyouts | Acquisition | Skip | Enterprise SaaS tactic, not current fit. |
| 90 | One-Click Registration | Activation | Now | Reduce download/install friction, not account signup. |
| 91 | In-App Upsells | Revenue | Q4+ | Only if paid team/support tier exists. |
| 92 | Newsletter Referrals | Referral | Q3+ | If newsletter has traction. |
| 93 | Viral Loops | Referral | Q4+ | Share-safe scan summaries only if carefully designed. |
| 94 | Offboarding Flows | Retention | Q4+ | Relevant after paid/team product. |
| 95 | Concierge Setup | Activation | Q2 | High-signal teams and customer research. |
| 96 | Onboarding Optimization | Activation | Now | Core Q1 work. |
| 97 | Playlists as Marketing | Acquisition | Skip | Off-fit. |
| 98 | Template Marketing | Acquisition | Q2 | Approval policy templates and secure agent setup guides. |
| 99 | Graphic Novel Marketing | Acquisition | Skip | Off-brand. |
| 100 | Promo Videos | Acquisition | Now | Existing video assets can support download/onboarding. |
| 101 | Industry Interviews | Acquisition | Q2 | Interview security/devtool users about agent risk. |
| 102 | Social Screenshots | Acquisition | Q2 | Share app/package boundary screenshots. |
| 103 | Online Courses | Acquisition | Q4+ | "Secure local AI agent workflows" later. |
| 104 | Book Marketing | Acquisition | Q4+ | Long-game founder category book only if category grows. |
| 105 | Annual Reports | Acquisition | Q4+ | Developer credential exposure report from package data. |
| 106 | End of Year Wraps | Acquisition | Q4+ | "Year in agent supply-chain incidents." |
| 107 | Podcasts (owned) | Acquisition | Q4+ | Guesting beats owning for now. |
| 108 | Changelogs | Acquisition | Now | Make releases retention and acquisition assets. |
| 109 | Public Demos | Acquisition | Now | CLI/app demos with real paths and commands. |
| 110 | Awards as Marketing | Acquisition | Skip | Not stage-appropriate. |
| 111 | Challenges as Marketing | Acquisition | Q3+ | Secure-agent setup challenge if serious. |
| 112 | Reality TV Marketing | Acquisition | Skip | Off-brand. |
| 113 | Controversy as Marketing | Acquisition | Q2 | Directly challenge prompt-only safety, carefully. |
| 114 | Moneyball Marketing | Cross-cutting | Now | Use undervalued package/catalog SEO. |
| 115 | Curation as Marketing | Acquisition | Q2 | Curate agentic toolkit and risky tool families. |
| 116 | Grants as Marketing | Acquisition | Skip | Not current fit. |
| 117 | Product Competitions | Referral | Q3+ | Package-boundary contribution competition if community exists. |
| 118 | Cameo Marketing | Acquisition | Skip | Off-brand. |
| 119 | OOH Advertising | Acquisition | Skip | Wrong stage and channel. |
| 120 | Marketing Stunts | Acquisition | Skip | Too risky for trust. |
| 121 | Guerrilla Marketing | Acquisition | Skip | Off-brand. |
| 122 | Humor Marketing | Acquisition | Skip | Use dry specificity, not humor-led campaigns. |
| 123 | Open Source as Marketing | Acquisition | Now | Core distribution channel. |
| 124 | App Store Optimization | Activation | Q3+ | Only if Mac App Store becomes relevant. |
| 125 | App Marketplaces | Acquisition | Q3+ | Devtool/agent directories, not generic marketplaces. |
| 126 | YouTube Reviews | Acquisition | Q3+ | Technical creator reviews after demo polish. |
| 127 | YouTube Channel | Acquisition | Q3+ | Short demos, not broad channel yet. |
| 128 | Source Platforms | Acquisition | Q4+ | G2/Capterra only if B2B paid offer exists. |
| 129 | Review Sites | Acquisition | Q3+ | AlternativeTo, GitHub topic lists, devtool directories. |
| 130 | Live Audio | Acquisition | Q3+ | Technical spaces only if founder wants it. |
| 131 | International Expansion | Acquisition | Q4+ | Fix thin locales first, then expand intentionally. |
| 132 | Price Localization | Revenue | Skip | No paid plan. |
| 133 | Investor Marketing | Acquisition | Q2 | Useful if raising; founder/category story is strong. |
| 134 | Certifications | Retention | Q4+ | "Automic Vault protected package metadata" later. |
| 135 | Support as Marketing | Retention | Q2 | Convert issues into docs/package rules. |
| 136 | Developer Relations | Acquisition | Now | Core channel for open-source dev tool. |
| 137 | Two-Sided Referrals | Referral | Q4+ | Only after team/commercial offer. |
| 138 | Podcast Tours | Acquisition | Q2 | Founder as technical guest. |
| 139 | Customer Language | Cross-cutting | Now | Capture exact user language from setup calls. |

### Idea-bank summary

- Acquisition dominates because Automic Vault is early and developer trust must be built before paid growth.
- Now/Q1 ideas focus on SEO, internal links, scanner activation, founder narrative, GitHub, DevRel, changelogs, public demos, open source, and customer language.
- Q2 adds customer research, content depth, contributor loops, newsletter, webinars, and selective partnerships.
- Q3/Q4 ideas depend on activation data and commercial posture.
- Skipped ideas are mostly off-brand consumer/gimmick tactics or paid channels that require a revenue model.

## 13. Measurement, RACI, open decisions, appendix

### North star

**Proposed north star:** weekly active protected developers.

Definition: unique local installs that complete at least one protected action in a 7-day period. Protected actions include scan, save, inject, approval gate, contain, or trace. If privacy constraints make this exact metric unacceptable, use a less granular proxy: weekly active installs plus protected-action event counts.

### Leading indicators by AARRR stage

| Stage | Leading indicators |
|---|---|
| Acquisition | Organic visits, priority-query impressions, GitHub stars/forks/releases views, download clicks, package-page entrances, external mentions. |
| Activation | Download -> install, app open, first scan, hazards found, first secret saved, first approval, first containment, docs CTA click. |
| Retention | Repeat protected action within 7/30 days, update adoption, repeat app/CLI use, newsletter engagement, GitHub issue/PR activity. |
| Referral | GitHub stars from activated users, contributor PRs, package-boundary requests, technical quotes, inbound mentions, setup-call referrals. |
| Revenue | Paid discovery calls, support/team waitlist, willingness-to-pay notes, pilot conversions, plan mix if paid exists. |

### Review cadence

Weekly:

- 30-minute AARRR scoreboard review.
- Ship/blocker review.
- One decision per week, if needed.

Monthly:

- Search Console, GitHub, download, activation, and content review.
- Compare page/content work to activated users, not just traffic.
- Reprioritize idea bank.

Quarterly:

- Re-score current-state rubric.
- Decide funding/staffing/commercial posture.
- Update plan version.

### RACI

| Domain | Responsible | Accountable | Consulted | Informed |
|---|---|---|---|---|
| Strategic positioning | Founder | Founder | Marketing Lead / advisor | Team |
| Website copy | Founder / Marketing Lead | Founder | Engineering | Team |
| Package page system | Engineering | Founder | SEO/content | Team |
| Docs/onboarding | Engineering + founder | Founder | User-call participants | Team |
| Analytics | Engineering | Founder | Marketing Lead | Team |
| Incident content | Founder | Founder | Security reviewers | Team |
| DevRel | Founder | Founder | Contributors | Team |
| Customer research | Founder / Marketing Lead | Founder | Early users | Team |
| Pricing | Founder | Founder | Revops/pricing advisor | Team |
| Future marketing hire | Founder | Founder | Advisors | Team |

### Open decisions blocking the plan

1. **Revenue model.** Highest impact. Blocks CAC/LTV math, paid budget, and sales material depth.
2. **Activation telemetry policy.** Need to decide what privacy-safe usage events can be collected.
3. **North-star implementation.** Need exact data source for weekly active protected developers.
4. **Funding and runway.** Blocks hire timing and paid/channel budget.
5. **Founder bandwidth.** Determines whether X/LinkedIn/podcast/talk cadence is realistic.
6. **Customer research access.** Need real users or setup calls to validate ICP and language.
7. **Commercial buyer.** Individual developer, founder, security team, or engineering leader.
8. **Mac App Store strategy.** Determines whether ASO matters.
9. **International strategy.** Current locales exist, but thin pages need expansion or sitemap restraint.
10. **External profile ownership.** SameAs links should only point to maintained profiles.

### Appendix - repo materials

Primary source materials:

- `/Users/mxcl/src/automic-vault/PRODUCT.md`
- `/Users/mxcl/src/automic-vault/BRAND.md`
- `/Users/mxcl/src/automic-vault/README.md`
- `/Users/mxcl/src/automic-vault/SEO-AUDIT-REPORT.md`
- `/Users/mxcl/src/automic-vault/GEO-AUDIT-REPORT.md`
- `/Users/mxcl/src/automic-vault/research/seo/automic-vault-seo-content-gap.md`
- `/Users/mxcl/src/automic-vault/docs/features.md`
- `/Users/mxcl/src/automic-vault/docs/spec-pkg-pages.md`
- `/Users/mxcl/src/automic-vault/www/index.md`
- `/Users/mxcl/src/automic-vault/www/pricing.md`

Operating artifacts:

- `/Users/mxcl/marketing-plans/automic-vault/research.md`
- `/Users/mxcl/marketing-plans/automic-vault/progress.md`
- `/Users/mxcl/marketing-plans/automic-vault/final_plan.md`

*Automic Vault Marketing Plan v1. Prepared 2026-06-02. For team review and discussion.*
