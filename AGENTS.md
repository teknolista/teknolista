# Project instructions

The GitHub profile repository, including profile content and desktop setup assets.


## Prompt Logging

Before analyzing, responding to, or taking any action on a prompt for this repository, append one entry containing that prompt to `AGENTS.log` at the repository root. The first tool operation may locate the repository, check the log target, and append this entry or verify capture; defer other tool use and delegation until logging succeeds. This applies to every prompt, including prompts sent to subagents. Record each received prompt once, including repeated identical submissions. When the host and project have been checked and no automatic capture is active, append the current prompt once without requiring an event identity. Otherwise verify automatic capture using the current event identity or other reliable capture evidence, not text equality alone. If verification requires log access, inspect only the relevant current entry without exposing prior prompts. If capture cannot be verified, stop and report the uncertainty before risking a duplicate or an omitted entry.

Use RFC 5322 local time with a numeric UTC offset, the provider/model, and the receiving agent and host. Use `unknown` for unavailable attribution; if the host is known but the model is not, use `<host>/unknown`. Keep one blank line between entries:

```text
## <RFC 5322 local date and time with numeric UTC offset> | <provider>/<model> (agent <agent name>, host <host>)
<prompt text, preserving its wording, spacing, and line breaks; use [empty prompt] if empty>
[attachment: <filename, at its position in the prompt>]
```

Include attachment names at their position in the prompt; do not copy binary contents. Preserve the prompt text except that secrets and unnecessary personal data must be replaced with `[REDACTED]` before writing. Never put credentials in prompts. Redact common patterns such as PEM private keys, `sk-`/`rk-`/`pk-` keys, `ghp_`/`github_pat_` tokens, `AKIA` and `AIza` keys, `xox*` tokens, JWTs, `Bearer` values, and values after `password`, `passwd`, `senha`, `token`, `secret`, or `api_key`. Redaction is best-effort; it does not identify every secret or personal-data format. If a secret reaches the log, revoke it; deleting the local copy is not sufficient.

Before appending, check the Git index for `AGENTS.log` and `AGENTS.log.*`; if any are tracked or staged, stop and report the privacy conflict. Ignore patterns alone do not untrack files; preserve local data and existing index selections until authorized remediation. Refuse symlink, hard-linked, or non-regular log targets; stop rather than redirecting prompt text. Create the log only if it does not exist, with owner-only permissions where supported. If it already exists, preserve the file and its contents, including during initialization and reruns; no reinitialization is needed. Append only: add each new entry at the end of the file. Never delete, recreate, overwrite, or truncate an existing log, or rewrite, reorder, or delete existing entries. Concurrent entries may not be in chronological order; do not reorder them. The log has no automatic rotation. Keep it local; never commit or publish it. Do not send a success message just for logging. If appending fails, stop, report the failure, fix the write, and record the pending prompt before continuing. Never proceed as if logging succeeded when it did not. This instruction depends on agent compliance and is not mechanical enforcement.


## PentaPRO factory guidance

Use the applicable project-local skills in `.agents/skills/`; use `software-factory` for explicitly requested factory runs and OpenSpec skills for the repository-root `openspec/` workflow. Follow existing project instructions and actual user authority. Factory role profiles are available for Codex, GitHub Copilot, OpenCode and Antigravity CLI; resolve their host-specific identities before delegation.

When a developer directly invokes a factory role without a narrower task, delegate its defined workflow using the current project and session context. Preserve its configured model and reasoning effort, the developer’s custom settings, applicable permissions and role-specific stop conditions. A direct shipper invocation requests git-ship review, commit and normal push; implementation completion alone does not.

All factory roles use the PDSA protocol in `docs/agents/continuous-improvement.md` and consult relevant lessons in `docs/agents/lessons-learned.md`. The orchestrator alone records lessons, always in English. For substantial factory or multi-agent runs, the orchestrator maintains a durable record under `docs/agents/runs/`; role packets carry the run ID, record path, version and input fingerprint. Follow the installed `software-factory` run-record contract.


## Software Excellence Manifesto — Powered by PentaPRO

Our mission is to build the finest software in the world. Every agent, subagent, and component of our development harness must pursue this ambition with unwavering dedication, exceptional engineering discipline, and relentless attention to detail. We are empowered by PentaPRO, our collection of specialized skills, agents, and engineering practices, and must intelligently leverage its most appropriate capabilities throughout the entire software lifecycle, guided by its five pillars: PRODUCT, PROJECT, PRODUCTION, PROOF, and PROCESS. We strive for excellence in every aspect of our software, from product vision, architecture, user experience, and design to implementation, performance, security, privacy, accessibility, reliability, and maintainability. Every decision must be intentional, every implementation purposeful, and every meaningful result verified through objective evidence. We challenge assumptions, eliminate unnecessary complexity, prevent defects, embrace continuous improvement, and never compromise correctness for superficial speed or appearance. We do not merely write code; we engineer extraordinary software that delivers exceptional value to its users. Our ambition is to create software that sets new standards of quality and innovation, worthy of being recognized among the best ever built. Excellence is our commitment, PentaPRO is our engineering foundation, and outstanding software is our ultimate achievement.
