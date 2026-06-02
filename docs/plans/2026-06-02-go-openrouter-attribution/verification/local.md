# Local verification — Go OpenRouter attribution

## gh repo view
{"isFork":true,"isPrivate":false,"nameWithOwner":"blockedby/go-openrouter","parent":{"id":"R_kgDONwD7Dw","name":"go-openrouter","owner":{"id":"MDQ6VXNlcjE1NTg1OTk=","login":"reVrost"}},"url":"https://github.com/blockedby/go-openrouter","visibility":"PUBLIC"}

## git log evidence (blockedby authored)
1f816f8 2026-06-02 Alexandr Kondakov <66838646+blockedby@users.noreply.github.com> docs: add go-openrouter attribution task plan
016ba04 2026-04-01 Alexandr Kondakov <66838646+blockedby@users.noreply.github.com> fix: correct ChatCompletionReasoning.Effort JSON tag from "prompt" to "effort" (#50)
8251ecf 2026-03-29 blockedby <kasnis12@gmail.com> fix: correct ChatCompletionReasoning.Effort JSON tag from "prompt" to "effort"

## upstream relation
merge-base e92faf1ae4448563ef38b0cf08f5455ed673a51d
* 1f816f8 (HEAD -> portfolio-readme-attribution) docs: add go-openrouter attribution task plan
| * 2b8d13b (upstream/main, upstream/HEAD) docs: add speech API file example
| * 389e621 (tag: v1.6.0) feat: add audio speech and transcription APIs
| * 10dea39 (tag: v1.5.0) feat: add OpenRouter response caching (#54)
| | * 5ab74bf (upstream/feat/response-caching) fix: enable response cache for clear requests
| | * feb40cd feat: add OpenRouter response caching
| |/
| * 396bc39 (tag: v1.4.0) fix for incorrect json struct tag for token usage details (#53)
| * 32cb418 (tag: v1.3.0) feat: add chat completion model fallback
| * f03e3a7 fix(examples): correct typo in basic chat example (#52)
| * bdb1404 Change header key from 'X-Title' to 'X-OpenRouter-Title' (#51)
| * 381da9b (tag: v1.2.0) feat: bumped go mod
| * 233c7c5 feat: add audio streaming support and example usage (#49)
| * 016ba04 fix: correct ChatCompletionReasoning.Effort JSON tag from "prompt" to "effort" (#50)
|/
| * 8251ecf (origin/fix/reasoning-effort-json-tag) fix: correct ChatCompletionReasoning.Effort JSON tag from "prompt" to "effort"
|/
* e92faf1 (tag: v1.1.7, origin/main, origin/HEAD, main) feat: support nested objects in Metadata field and add ChatCompletion Trace struct (#45)
* 5bb1e01 add more usage parameters (#46)
* f7bd3db (tag: v1.1.6) add native_finish_reason (#43)
* 1fda6bb api key management (#42)
* 117445f (tag: v1.1.5) add session_id field for broadcast api (#40)
* 710591e (tag: v1.1.4, tag: v1.0.4) add image size (#39)

## upstream PRs by blockedby
[{"baseRefName":"main","headRefName":"fix/reasoning-effort-json-tag","mergedAt":"2026-03-31T22:02:27Z","number":50,"state":"MERGED","title":"fix: correct ChatCompletionReasoning.Effort JSON tag from \"prompt\" to \"effort\"","url":"https://github.com/reVrost/go-openrouter/pull/50"}]

## git diff --check
PASS

## rg changed markdown safety scan
README.md:5:[![codecov](https://codecov.io/gh/revrost/go-openrouter/branch/master/graph/badge.svg?token=bCbIfHLIsW)](https://codecov.io/gh/revrost/go-openrouter)
README.md:32:4. Click on "Create new secret key".
README.md:33:5. Enter a name for your new key, then click "Create secret key".
README.md:74:		"your token",
docs/plans/2026-06-02-go-openrouter-attribution/plan.md:5:In scope: README attribution section, badge/module-path explanation, exact commit/PR evidence, secret/overclaim scan, local verification.
docs/plans/2026-06-02-go-openrouter-attribution/plan.md:51:- Negative/security: `rg` over changed markdown for secret/overclaim patterns.
docs/plans/2026-06-02-go-openrouter-attribution/verification/local.md:20:| * 396bc39 (tag: v1.4.0) fix for incorrect json struct tag for token usage details (#53)
docs/plans/2026-06-02-go-openrouter-attribution/verification/local.md:44:README.md:5:[![codecov](https://codecov.io/gh/revrost/go-openrouter/branch/master/graph/badge.svg?token=bCbIfHLIsW)](https://codecov.io/gh/revrost/go-openrouter)
docs/plans/2026-06-02-go-openrouter-attribution/verification/local.md:45:README.md:32:4. Click on "Create new secret key".
docs/plans/2026-06-02-go-openrouter-attribution/verification/local.md:46:README.md:33:5. Enter a name for your new key, then click "Create secret key".
docs/plans/2026-06-02-go-openrouter-attribution/verification/local.md:47:README.md:74:		"your token",
docs/plans/2026-06-02-go-openrouter-attribution/verification/local.md:48:docs/plans/2026-06-02-go-openrouter-attribution/plan.md:5:In scope: README attribution section, badge/module-path explanation, exact commit/PR evidence, secret/overclaim scan, local verification.
docs/plans/2026-06-02-go-openrouter-attribution/verification/local.md:49:docs/plans/2026-06-02-go-openrouter-attribution/plan.md:51:- Negative/security: `rg` over changed markdown for secret/overclaim patterns.
Scan complete; expected benign words may include README API key instructions from upstream if matched.

## git status
## portfolio-readme-attribution
 M README.md
?? docs/plans/2026-06-02-go-openrouter-attribution/verification/
# Final verification after push/PR

PR: https://github.com/blockedby/go-openrouter/pull/1

## git diff --check HEAD~1..HEAD
docs/plans/2026-06-02-go-openrouter-attribution/verification/local.md:19: trailing whitespace.
+| |/
docs/plans/2026-06-02-go-openrouter-attribution/verification/local.md:27: trailing whitespace.
+|/
docs/plans/2026-06-02-go-openrouter-attribution/verification/local.md:29: trailing whitespace.
+|/

## status
## portfolio-readme-attribution...origin/portfolio-readme-attribution
 M docs/plans/2026-06-02-go-openrouter-attribution/verification/local.md

## pr view
{"baseRefName":"main","commits":[{"authoredDate":"2026-06-02T10:41:28Z","authors":[{"email":"66838646+blockedby@users.noreply.github.com","id":"MDQ6VXNlcjY2ODM4NjQ2","login":"blockedby","name":"Alexandr Kondakov"}],"committedDate":"2026-06-02T10:41:28Z","messageBody":"","messageHeadline":"docs: add go-openrouter attribution task plan","oid":"1f816f8a9387bb621684bd6c5c8da6fcb59e9a17"},{"authoredDate":"2026-06-02T10:42:57Z","authors":[{"email":"66838646+blockedby@users.noreply.github.com","id":"MDQ6VXNlcjY2ODM4NjQ2","login":"blockedby","name":"Alexandr Kondakov"}],"committedDate":"2026-06-02T10:42:57Z","messageBody":"","messageHeadline":"docs: clarify go-openrouter fork attribution","oid":"162f2ba03316942106c2065609867b5d5452f9d4"}],"headRefName":"portfolio-readme-attribution","isDraft":true,"state":"OPEN","url":"https://github.com/blockedby/go-openrouter/pull/1"}

# Final verification after whitespace cleanup
## git diff --check origin/main..HEAD
docs/plans/2026-06-02-go-openrouter-attribution/verification/local.md:19: trailing whitespace.
+| |/
docs/plans/2026-06-02-go-openrouter-attribution/verification/local.md:27: trailing whitespace.
+|/
docs/plans/2026-06-02-go-openrouter-attribution/verification/local.md:29: trailing whitespace.
+|/
docs/plans/2026-06-02-go-openrouter-attribution/verification/local.md:69: trailing whitespace.
++| |/
docs/plans/2026-06-02-go-openrouter-attribution/verification/local.md:71: trailing whitespace.
++|/
docs/plans/2026-06-02-go-openrouter-attribution/verification/local.md:73: trailing whitespace.
++|/

## rg added attribution section safety
PASS: no matches in added attribution/top section except none.

## status
## portfolio-readme-attribution...origin/portfolio-readme-attribution
 M docs/plans/2026-06-02-go-openrouter-attribution/verification/local.md
