# Plan — Go OpenRouter README attribution

## Task intake
Goal: clarify `blockedby/go-openrouter` fork/upstream status and blockedby changes in README.
In scope: README attribution section, badge/module-path explanation, exact commit/PR evidence, secret/overclaim scan, local verification.
Out of scope: changing Go module path, code refactors, making any private repo public.
Done state: README clearly attributes upstream `reVrost/go-openrouter`, lists blockedby fork changes with links, avoids misleading authorship, verification recorded, final report written.
Blocking unknowns: exact authorship/PR mapping must be derived from git/GitHub evidence.

## Repo orientation
- Local clone: `/home/kcnc/code/tools/go-openrouter`.
- Active worktree: `/home/kcnc/code/tools/go-openrouter/.worktrees/portfolio-readme-attribution`.
- Branch: `portfolio-readme-attribution` from `main`.
- GitHub evidence: `blockedby/go-openrouter` is PUBLIC fork of `reVrost/go-openrouter`.
- Upstream remote: `https://github.com/reVrost/go-openrouter.git` fetched.
- Likely files: `README.md`; task package docs only.
- Verification commands: `gh repo view ...`, `git log`, `git diff --check`, markdown scan with `rg`, `git status --short --branch`.

## Reuse discovery
- Existing README already uses upstream module path `github.com/revrost/go-openrouter` and upstream badges.
- Existing feature checklist includes chat completion, completion, streaming, embeddings, reasoning, tool calling, structured outputs, prompt caching, web search, multimodal, usage fields.
- Existing PR-style commit subjects on fork include API feature additions and fixes (#22-#46); upstream currently contains later commits after fork main.

## Missing pieces
- Add clear `Fork status / My changes` section near top of README.
- Explain upstream badges/module path remain upstream-oriented because this fork tracks/contributes to the upstream module rather than publishing a renamed module.
- List exact blockedby commits/PRs where available from local history/GitHub links.
- Record verification evidence and final slice report.

## Plan tasks

### Task 1: README fork attribution and evidence links
Goal:
- README states fork status, upstream attribution, and blockedby feature/change areas with exact links.
Boundary:
- System area: public markdown/docs.
- Primary verification: README diff review, git/GitHub evidence, markdown safety scan.
Existing pattern / reuse:
- Existing README feature list and upstream module path/badges.
Missing change:
- Add concise `Fork status / My changes` section without changing module path.
Scope / likely files:
- `README.md`; task package reports/verification.
Acceptance criteria:
- Upstream `reVrost/go-openrouter` is attributed.
- Blockedby changes list exact commit/PR links where available.
- Badge/module path explanation prevents misleading ownership.
- No original-authorship overclaim or forbidden public phrase.
Test plan:
- Positive: `gh repo view`, `git log --oneline --decorate --graph --all`, `git diff --check`.
- Negative/security: `rg` over changed markdown for secret/overclaim patterns.
Dependencies:
- Depends on: none.
- Blocks: final verification/report.
Executor:
- aad-implementer.

## Dependency graph
- Wave 1: Task 1 via aad-implementer.
- Wave 2: slice owner verifies, commits/pushes if safe, writes final report.

## Execution ledger
- Task 1: done. Report: `reports/aad-implementer-readme-attribution.md`. Verification: `verification/local.md`.
