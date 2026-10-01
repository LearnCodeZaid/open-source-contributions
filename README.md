# Open Source Contributions — LearnCodeZaid

Tracking real contributions to open-source projects people actually use.
Each contribution lives on its own branch here **and** as a fork + PR upstream.

## Active contributions

| # | Upstream | Fork branch | Upstream PR | Status | Notes |
|---|---|---|---|---|---|
| 1 | [TheAlgorithms/C-Plus-Plus#3234](https://github.com/TheAlgorithms/C-Plus-Plus/issues/3234) — Doxygen JAVADOC_BANNER | [LearnCodeZaid/C-Plus-Plus @ fix/doxygen-banner-3234](https://github.com/LearnCodeZaid/C-Plus-Plus/tree/fix/doxygen-banner-3234) | [PR #3237](https://github.com/TheAlgorithms/C-Plus-Plus/pull/3237) | Open — awaiting review | Converted 8 files from `/****` banners to `/**` Doxygen blocks. Local: `../fork-C-Plus-Plus` |
| 2 | [microsoft/markitdown#2482](https://github.com/microsoft/markitdown/issues/2482) — HTML title leaks into body | [LearnCodeZaid/markitdown @ fix/html-title-body-leak-2482](https://github.com/LearnCodeZaid/markitdown/tree/fix/html-title-body-leak-2482) | [PR #2577](https://github.com/microsoft/markitdown/pull/2577) | Open — CLA signed, awaiting review | Capture title, extract `<head>` before convert; 26 existing + 3 new tests pass. Local: `../fork-markitdown` |
| 3 | [iamkun/dayjs#2951](https://github.com/iamkun/dayjs/issues/2951) — Arabic meridiem wrong at 12 PM | [LearnCodeZaid/dayjs @ fix/arabic-meridiem-12pm-2951](https://github.com/LearnCodeZaid/dayjs/tree/fix/arabic-meridiem-12pm-2951) | [PR #3242](https://github.com/iamkun/dayjs/pull/3242) | Open — awaiting review | `hour > 12` → `hour >= 12` in all 8 Arabic locales. Local: `../fork-dayjs` |

## Workflow per contribution
1. `gh repo fork <upstream> --clone=false` (fork to LearnCodeZaid)
2. Clone fork locally into `../fork-<name>`, add `upstream` remote (auto by gh)
3. Branch: `fix/<short-name>-<issue#>` or `feat/...`
4. Fix, syntax/test check, commit with `Fixes/Part of <upstream>#<n>`
5. `git push -u origin <branch>` + `gh pr create --repo <upstream> ...`
6. Log it in the table above.

## Local folders (this workspace)
- `../fork-C-Plus-Plus` — fork of TheAlgorithms/C-Plus-Plus (branch `fix/doxygen-banner-3234`)
- `../fork-markitdown` — fork of microsoft/markitdown (branch `fix/html-title-body-leak-2482`)
- `../fork-dayjs` — fork of iamkun/dayjs (branch `fix/arabic-meridiem-12pm-2951`)

