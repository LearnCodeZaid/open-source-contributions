# Open Source Contributions — LearnCodeZaid

Tracking real contributions to open-source projects people actually use.
Each contribution lives on its own branch here **and** as a fork + PR upstream.

## Active contributions

| # | Upstream issue | Fork branch | Upstream PR | Status | Notes |
|---|---|---|---|---|---|
| 1 | [TheAlgorithms/C-Plus-Plus#3234](https://github.com/TheAlgorithms/C-Plus-Plus/issues/3234) — Doxygen JAVADOC_BANNER | [LearnCodeZaid/C-Plus-Plus @ fix/doxygen-banner-3234](https://github.com/LearnCodeZaid/C-Plus-Plus/tree/fix/doxygen-banner-3234) | [PR #3237](https://github.com/TheAlgorithms/C-Plus-Plus/pull/3237) | Open — awaiting review | Converted 8 files from `/****` banners to `/**` Doxygen blocks |

## Workflow per contribution
1. `gh repo fork <upstream> --clone=false` (fork to LearnCodeZaid)
2. Clone fork locally into `../fork-<name>`, add `upstream` remote
3. Branch: `fix/<short-name>-<issue#>` or `feat/...`
4. Fix, syntax/test check, commit with `Part of <upstream>#<n>`
5. `git push -u origin <branch>` + `gh pr create --repo <upstream> ...`
6. Log it in the table above.

## Local folders (this workspace)
- `../fork-C-Plus-Plus` — fork of TheAlgorithms/C-Plus-Plus (branch `fix/doxygen-banner-3234`)
