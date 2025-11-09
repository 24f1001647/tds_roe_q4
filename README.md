# Matrix Build with Artifacts (Challenge 50bdda8)

This repository demonstrates a GitHub Actions **matrix** build that runs in parallel across multiple OS and Node.js versions, and uploads non-empty, per-variant artifacts named with the required prefix `build-50bdda8-<variant>`.

- **Email (required):** your.name@example.com

## Validate
- At least **3** matrix jobs succeed (this workflow runs 9).
- At least **3** artifacts uploaded with prefix `build-50bdda8-`.
- Each artifact contains content (see `dist/build-info.json` and `dist/summary.txt`).
- Workflow includes a step named `matrix-50bdda8`.

## How to Trigger
1. Commit this workflow and README:
   ```bash
   git add .github/workflows/matrix-build.yml README.md
   git commit -m "Add matrix build workflow (50bdda8)"
   git push origin main
