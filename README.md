# Main account

**Reviewer — no clones; reviews and merges.**

This is the **main account**: the personal, canonical account. It is never used to clone
anything — it is opened only in a **browser or the GitHub app**, to review open pull requests,
comment, **approve** (one review), and merge. Changes arrive as pull requests from the paired
**machine account** (a *contributor* that forks each repo and opens PRs); every repo requires a PR
with **1 approving review**, admins enforced — so nothing reaches `main` without review.

Private repositories are managed through **GitHub Codespaces** (no forks, no local clones).

Rules of the road:

- Open this account only when you have the patience to review a **git diff** carefully.
- Review only PRs that **close a linked issue** and have **passing status checks**.
- Approve and merge; never push to a protected branch.

## Repositories

The table is the whole building: public floors above ground, this profile on the ground floor, and
the private repositories underground — titles only; their contents stay private.

<!-- BEGIN status-table -->
| Floor | Repo | Tag | Size | CI |
|------:|------|-----|------|----|
| ☀️ +8 | [database](https://github.com/kapetao/database) | — | 145 KB | — |
| ☀️ +7 | [radar](https://github.com/kapetao/radar) | — | 112 KB | — |
| ☀️ +6 | [journal](https://github.com/kapetao/journal) | — | 613 KB | — |
| ☀️ +5 | [browser-games](https://github.com/kapetao/browser-games) | 2026-10-09T04-16-08Z | 58 KB | — |
| ☀️ +4 | [ai-training](https://github.com/kapetao/ai-training) | 2026-10-09T04-16-11Z | 11 KB | — |
| ☀️ +3 | [browser-extensions](https://github.com/kapetao/browser-extensions) | 2026-10-09T04-10-04Z | 119 KB | — |
| ☀️ +2 | [interviewing](https://github.com/kapetao/interviewing) | 2026-10-09T04-10-05Z | 522 KB | — |
| ☀️ +1 | [cli](https://github.com/kapetao/cli) | v0.3.2 | 55 KB | — |
| 🏢 0 | [profile](https://github.com/kapetao/kapetao) | 2026-10-09T04-16-05Z | 73 KB | — |
| 🌑 -1 | [private-wiki](https://github.com/kapetao/private-wiki) | — | — | — |
| 🌑 -2 | [private-events-log](https://github.com/kapetao/private-events-log) | — | — | — |
| 🌑 -3 | [private-database](https://github.com/kapetao/private-database) | — | — | — |
<!-- END status-table -->

## Repo scorecard

Where each repo stands on the road to a fluid, secure change-flow. The target flow is
**issue → machine-account fork → PR that closes the issue → required checks → one careful review →
up-to-date merge → branch deleted**. Private repositories lean on Codespaces and are out of scope.

**Rule of order.** Get every public repo to **100% of must-have (60)** first, then spend on the
wishlist (40) **highest points first** (easy before hard within a tier).

### Per-repo summary

| Code | Repo | Vis | Tag | Size | Must | Wish | Total | % |
| --- | --- | --- | --- | --: | --: | --: | --: | --: |
| AIT | ai-training | pub | `2026-10-09…` | 11 KB | 30/60 | 0/40 | 30/100 | 30% |
| BEX | browser-extensions | pub | `2026-10-09…` | 119 KB | 30/60 | 0/40 | 30/100 | 30% |
| BGM | browser-games | pub | `2026-10-09…` | 58 KB | 30/60 | 0/40 | 30/100 | 30% |
| CLI | cli | pub | `v0.3.2` | 55 KB | 30/60 | 0/40 | 30/100 | 30% |
| DAT | database | pub | — | 145 KB | 30/60 | 0/40 | 30/100 | 30% |
| INT | interviewing | pub | `2026-10-09…` | 522 KB | 30/60 | 0/40 | 30/100 | 30% |
| JRN | journal | pub | — | 613 KB | 30/60 | 0/40 | 30/100 | 30% |
| KAP | profile (main account) | pub | `2026-10-09…` | 73 KB | 30/60 | 0/40 | 30/100 | 30% |
| RAD | radar | pub | — | 112 KB | 30/60 | 0/40 | 30/100 | 30% |
| — | private-{database,wiki,events-log} | priv | — | — | n/a | n/a | n/a | Codespaces |

### Tier 1 — must-have (bare minimum, target 60)

| Lever | Pts | Effort | AIT | BEX | BGM | CLI | DAT | INT | JRN | KAP | RAD |
| --- | --: | --- | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: |
| Machine-account fork exists | 2 | easy | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ |
| PR required (no direct pushes) | 4 | easy | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ |
| 1 approving review | 6 | easy | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ |
| Dismiss stale approvals on new commits | 4 | easy | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ |
| Require approval of the most recent push | 2 | easy | — | — | — | — | — | — | — | — | — |
| Admins enforced | 2 | easy | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ |
| Secret scanning | 6 | easy | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ |
| Push protection | 6 | easy | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ |
| Required status check (≥1 CI job) | 8 | medium | — | — | — | — | — | — | — | — | — |
| Branch up to date before merge | 6 | easy* | — | — | — | — | — | — | — | — | — |
| PR must close a linked issue | 4 | easy | — | — | — | — | — | — | — | — | — |
| One open PR per repo | 4 | medium | — | — | — | — | — | — | — | — | — |
| Auto-delete branch on merge | 2 | easy | — | — | — | — | — | — | — | — | — |
| Squash-only merge type | 4 | easy | — | — | — | — | — | — | — | — | — |

`*` easy once a check exists. **Every repo: 30 / 60.**

### Tier 2 — wishlist (raise the bar, target 40)

| Lever | Pts | Effort | AIT | BEX | BGM | CLI | DAT | INT | JRN | KAP | RAD |
| --- | --: | --- | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: |
| Per-repo lint/test CI job | 4 | hard | — | — | — | — | — | — | — | — | — |
| Automatic Copilot code review | 3 | easy | — | — | — | — | — | — | — | — | — |
| Require code scanning results (CodeQL) | 3 | medium | — | — | — | — | — | — | — | — | — |
| Require code quality / coverage thresholds | 3 | medium | — | — | — | — | — | — | — | — | — |
| Merge queue | 3 | medium | — | — | — | — | — | — | — | — | — |
| Automated releases | 3 | hard | — | — | — | — | — | — | — | — | — |
| Dependency review on PRs | 2 | easy | — | — | — | — | — | — | — | — | — |
| Dependabot alerts + security updates | 2 | easy | — | — | — | — | — | — | — | — | — |
| Dependabot version updates | 2 | easy | — | — | — | — | — | — | — | — | — |
| CODEOWNERS + code-owner review | 2 | medium | — | — | — | — | — | — | — | — | — |
| Required signed commits | 2 | medium | — | — | — | — | — | — | — | — | — |
| Actions SHA-pinned / restricted | 2 | medium | — | — | — | — | — | — | — | — | — |
| Ruleset: branch/commit name patterns | 2 | easy | — | — | — | — | — | — | — | — | — |
| Require conversation resolution | 1 | easy | — | — | — | — | — | — | — | — | — |
| Auto-merge after checks + review | 1 | easy | — | — | — | — | — | — | — | — | — |
| Required linear history | 1 | easy | — | — | — | — | — | — | — | — | — |
| PR template (what / why / evidence) | 1 | easy | — | — | — | — | — | — | — | — | — |
| Issue templates | 1 | easy | — | — | — | — | — | — | — | — | — |
| Tag ruleset / release discipline | 1 | easy | — | — | — | — | — | — | — | — | — |
| Wiki disabled (docs in-repo) | 1 | easy | — | — | — | — | — | — | — | — | — |

**Every repo: 0 / 40.**

### Notes

- The **main account** is a personal (non-org) account → **no org-level required workflows**; the
  checks / one-open-PR levers must be per-repo workflows (or a hub janitor). Public repos have **no
  workflows** today.
- Levers that need a check first: required status checks, up-to-date-before-merge, merge queue,
  code-scanning / quality gates.
- Changing `main` requires PRs from the **machine account** (protected branch, admins included).
