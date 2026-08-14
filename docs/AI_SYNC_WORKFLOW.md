# AI Sync Workflow (Kiro + Copilot)

Ziel: Kiro und Copilot arbeiten schnell, ohne Konflikte und mit reproduzierbarer Qualitaet.

## 1) Branching-Regeln

- Nie direkt auf `main` arbeiten.
- Pro Task genau ein Feature-Branch.
- Namensschema:
  - `ai/kiro/<task-kurzname>`
  - `ai/copilot/<task-kurzname>`

## 2) Task-Ownership

- Pro Task genau ein Implementierungs-Owner.
- Nur der Owner schreibt produktiven Code in den betroffenen Dateien.
- Der zweite Agent uebernimmt nur eine dieser Rollen:
  - Review
  - Tests
  - Refactor nach Merge

## 3) Kein Parallel-Edit in denselben Dateien

- Wenn beide an derselben Datei arbeiten muessen:
  - Agent A merged zuerst.
  - Agent B rebased danach und arbeitet weiter.

## 4) Qualitaets-Gates vor Push/PR

- Build/Checks passend zum Repo laufen lassen.
- Bei Problemen zuerst fixen, dann pushen.

## 5) Handoff-Standard (Pflicht in jeder PR)

- Problem/Ziel in 1-2 Saetzen
- Geaenderte Bereiche
- Testnachweis
- Risiken / offene Punkte
- Rollback-Idee
