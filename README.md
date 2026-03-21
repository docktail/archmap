# archmap

Architecture graph for the [docktail](https://github.com/docktail) GitHub organization.

Generated daily by [abdullahbodur/archmap](https://github.com/abdullahbodur/archmap).

**Live site:** https://docktail.github.io/archmap/

## How it works

A scheduled GitHub Actions workflow runs the ArchMap scanner against the `docktail` org every day at 03:00 UTC. It commits the updated `data/graph.json` and deploys the static React Flow visualization to GitHub Pages.

## Manual trigger

Go to **Actions → Scan & Deploy → Run workflow**.

## Secret required

| Secret | Purpose |
|--------|---------|
| `ARCHMAP_TOKEN` | GitHub PAT with `read:org` + `repo` scopes for the `docktail` org |
