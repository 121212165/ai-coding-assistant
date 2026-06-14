# Reconstruction Plan

## Diagnosis

This repo is a junk drawer. 330 files, 4 unrelated projects, 1 cloned external repo, 1 dead artifact, 1 misleading README.

| Component | Files | Verdict |
|-----------|-------|---------|
| `awesome-claude-code-subagents/` | 139 | **DELETE** — cloned external repo (VoltAgent). Zero local references. |
| `ai_completion/` | 2 | **DELETE** — dead artifact: a deviceId JSON + bundled ripgrep binary. No code. |
| `codebuddy/个人教育/` | 1 | **DELETE** — empty duplicate skeleton (same package.json as sibling, no src/). |
| `bio_sim/` | ~60 | KEEP — standalone Python bio-simulation platform. Real project. |
| `claude-code-project-config/` | ~20 | KEEP — Claude Code config collection for 5 projects. Real utility. |
| `codebuddy/20250825181611/` | ~8 | KEEP — PDF-to-Markdown converter. Real project. |
| `explorer-agent/` | ~26 | KEEP — AI exploration agent (FastAPI + Streamlit). Real project. |
| `README.md` | 1 | **REWRITE** — current version is generic boilerplate that lies about the repo. |
| `.github/workflows/ci.yml` | 1 | KEEP — CI config. |
| `.gitignore` | 1 | KEEP. |
| `FIRST-PRINCIPLES-RECONSTRUCTION.md` | 1 | KEEP — the analysis doc that triggered this. |

## Actions

1. **DELETE** `awesome-claude-code-subagents/` — 139 files, the entire cloned VoltAgent repo
2. **DELETE** `ai_completion/` — dead code (config.json + ripgrep binary)
3. **DELETE** `codebuddy/个人教育/` — empty duplicate
4. **REWRITE** `README.md` — honest inventory of what remains
5. **COMMIT** and push

## Expected Result

- ~162 files deleted
- ~80 files remaining (4 real projects + repo infra)
- README accurately describes the repo
