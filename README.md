# Eidetic Works — Issues & Feedback

Public tracker for the local-first AI memory layer.

- Bug → New Issue → Bug report
- Feature → Feature request
- Question → Question

Site: [eidetic.works](https://eidetic.works)

---

## What this repo is

This is the **customer-facing issue tracker** for the Eidetic Works product surface:

- **eidetic-mcp** — the MCP server you wire into Claude Code / Claude Desktop / other MCP clients.
- **eidetic-daemon** — the local always-on memory daemon that mirrors your sessions, indexes engrams, and serves the MCP.
- **eidetic-pro** — the paid tier (cloud sync, dashboard, advanced retrieval, priority support).

Product source code lives in private repos. This tracker is public so that bug reports, feature requests, and reproductions are visible and searchable.

## How to file an issue

1. Go to **[New Issue](https://github.com/eidetic-works/eidetic-issues/issues/new/choose)**.
2. Pick the closest template:
   - **Bug report** — something is broken, crashing, or behaving wrong.
   - **Feature request** — propose a capability the product doesn't have.
   - **Question** — usage / how-to that doesn't fit Discord.
3. Fill the template end-to-end. The more context (OS, version, MCP client, repro steps, logs), the faster it lands.

If none of the templates fit, open a blank issue — but expect the maintainers to ask for the same info the templates ask for.

## What goes here vs Discord

Rule of thumb:

| Goes here (GitHub) | Goes to Discord |
|---|---|
| Reproducible bugs (with repro steps) | "How do I…?" usage questions |
| Crashes, panics, stack traces | Brainstorming / pre-spec feature talk |
| Feature requests with clear use case | Real-time help, casual chat |
| Anything code-shaped (PRs land in private repos, but the discussion can live here) | Community / showcase / off-topic |

The short version: **if you can paste a stack trace or a `repro:` block, file it here. If you'd open with "quick question," ask Discord first.**

Discord invite is on [eidetic.works](https://eidetic.works).

## Response SLA

- **Pro customers**: first-touch within **24 business hours** (Mon-Fri, IST timezone). Tag your issue with `pro-customer` and include your Pro account email so we can route faster.
- **Free tier**: **best-effort**. Reproducible bugs with logs usually get a first response within a few days. Feature requests are reviewed in batches.

SLAs cover **first response and triage**, not resolution time. Resolution depends on severity and roadmap fit.

## Security issues

**Do not file security issues as public GitHub issues.** Instead:

1. **Preferred:** Use GitHub's [private security advisory](https://github.com/eidetic-works/eidetic-issues/security/advisories/new) feature so the report stays embargoed until a fix ships.
2. **Or:** Email **security@eidetic.works** with a description, repro, and (optionally) a PGP-encrypted attachment.

We will acknowledge within 72 hours and coordinate a disclosure timeline.

## License & conduct

- Repository content (templates, README) is MIT-licensed — see [LICENSE](LICENSE).
- All participants follow the [Code of Conduct](CODE_OF_CONDUCT.md).
