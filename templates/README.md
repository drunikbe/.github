# DRUNIK templates

Reference configurations for individual drunikbe repos. These are **not** auto-applied — copy them in and adapt.

## `dependabot.yml`

Canonical Dependabot config. Copy to `.github/dependabot.yml` in any repo and uncomment the package ecosystems that apply.

```bash
curl -fsSL https://raw.githubusercontent.com/drunikbe/.github/main/templates/dependabot.yml -o .github/dependabot.yml
```

Conventions baked in:
- Weekly schedule, Monday 09:00 Europe/Brussels
- Minor/patch grouped into a single PR per ecosystem
- `dependencies` label + per-ecosystem label
- `chore(deps)` commit prefix
- `open-pull-requests-limit: 10` where applicable

Once committed, ensure Dependabot is enabled in repo Settings → Security → Code security and analysis.

## CodeQL

CodeQL ships as a workflow template (not in this directory). In any drunikbe repo, click **Actions → New workflow** and pick "CodeQL Analysis (DRUNIK)" under the "By drunikbe" section. Adjust the `language` matrix to match what the repo actually contains.
