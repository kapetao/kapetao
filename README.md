# kapetao

**Main account — holds the code, reviews the pull requests.**

`kapetao` owns the canonical public repositories and approves every change. Its paired
**machine account** [`kapetim`](https://github.com/kapetim) forks each public repo and opens pull
requests; every repo requires a PR with **1 approving review**, with admins enforced — so nothing
reaches `main` without review here.

## Repositories

The block below is the whole building: public floors above ground, the hub (`kapetao`) on the
ground floor, and the private repositories underground — titles only; their contents stay private.

<!-- BEGIN status-table -->
```mermaid
flowchart TB
  f9["+9 · ui-assets"]:::pub
  f8["+8 · pkg-manager"]:::pub
  f7["+7 · radar"]:::pub
  f6["+6 · journal"]:::pub
  f5["+5 · browser-games"]:::pub
  f4["+4 · ai-training"]:::pub
  f3["+3 · browser-extensions"]:::pub
  f2["+2 · interviewing"]:::pub
  f1["+1 · cli"]:::pub
  f0["0 · kapetao"]:::ground
  b1["-1 · private-wiki"]:::priv
  b2["-2 · private-events-log"]:::priv
  b3["-3 · private-database"]:::priv
  f9 --- f8
  f8 --- f7
  f7 --- f6
  f6 --- f5
  f5 --- f4
  f4 --- f3
  f3 --- f2
  f2 --- f1
  f1 --- f0
  f0 --- b1
  b1 --- b2
  b2 --- b3
  classDef pub fill:#dafbe1,stroke:#1a7f37,color:#0a3622;
  classDef ground fill:#ddf4ff,stroke:#0969da,color:#0a3069;
  classDef priv fill:#ffeff7,stroke:#bf3989,color:#4c0a2f;
```

| Floor | Repo | Tag | Size | CI |
|------:|------|-----|------|----|
| ☀️ +9 | [ui-assets](https://github.com/kapetao/ui-assets) | — | — | — |
| ☀️ +8 | [pkg-manager](https://github.com/kapetao/pkg-manager) | — | — | — |
| ☀️ +7 | [radar](https://github.com/kapetao/radar) | — | — | — |
| ☀️ +6 | [journal](https://github.com/kapetao/journal) | — | — | — |
| ☀️ +5 | [browser-games](https://github.com/kapetao/browser-games) | — | — | — |
| ☀️ +4 | [ai-training](https://github.com/kapetao/ai-training) | — | — | — |
| ☀️ +3 | [browser-extensions](https://github.com/kapetao/browser-extensions) | — | — | — |
| ☀️ +2 | [interviewing](https://github.com/kapetao/interviewing) | — | — | — |
| ☀️ +1 | [cli](https://github.com/kapetao/cli) | — | — | — |
| 🏢 0 | [kapetao](https://github.com/kapetao/kapetao) | — | — | — |
| 🌑 -1 | [private-wiki](https://github.com/kapetao/private-wiki) | — | — | — |
| 🌑 -2 | [private-events-log](https://github.com/kapetao/private-events-log) | — | — | — |
| 🌑 -3 | [private-database](https://github.com/kapetao/private-database) | — | — | — |
<!-- END status-table -->
