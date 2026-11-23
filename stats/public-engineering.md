# Public engineering snapshot

Snapshot date: 2026-11-23 (UTC). This file and the [current SVG](../assets/public-engineering-2026-11-23-tokyonight-v1.svg) are a static snapshot, not an automatically updating service.

## Counts

| Metric | Count | Scope |
| --- | ---: | --- |
| Tessera merged pull requests | 17 | All merged PRs in the public repository |
| Andrew-Smith-93-authored Tessera merged PRs | 12 | PR author login, not commit authorship |
| Dependabot-authored Tessera merged PRs | 5 | Automation included separately |
| Tessera published releases | 2 | v1.0.1, v1.0.2 |
| Codeward published releases | 2 | v1.0.0, v2.0.0 |
| Keep RAM Clean published releases | 5 | v2.0.0, v2.1.0, v2.2.0, v2.2.1, v2.3.0 |

## Sources and method

- [Tessera closed pull requests, GitHub REST API](https://api.github.com/repos/Andrew-Smith-93/Tessera/pulls?state=closed&per_page=100): fetched 24 records, retained the 17 with non-null `merged_at`. The complete result fits one page. Grouped retained records by `user.login`.
- [Tessera releases, GitHub REST API](https://api.github.com/repos/Andrew-Smith-93/Tessera/releases?per_page=100): 2 records, both published, non-draft, and non-prerelease.
- [Codeward releases, GitHub REST API](https://api.github.com/repos/Andrew-Smith-93/codeward/releases?per_page=100): 2 records, both published, non-draft, and non-prerelease.
- [Keep RAM Clean releases, GitHub REST API](https://api.github.com/repos/Andrew-Smith-93/keep-ram-clean/releases?per_page=100): 5 published, non-draft, non-prerelease records. Crates.io publishes are not counted separately.
- PR numbers included: #24, #23, #22, #21, #20, #19, #16, #15, #14, #13, #12, #11, #10, #9, #8, #7, #6.

The top bar divides all 17 merged PRs by author category (12/17 and 5/17). Release bars share a zero baseline and the same scale (95.2 SVG units per release).

These are repository totals, not claims of personal authorship of every change. They do not measure customers, downloads, production readiness, revenue, review quality, or current test results. Private repositories are excluded. Refresh the API reads and regenerate the counts, date, SVG labels, and README alt text together when updating.


## Repository stats

The per-repository table uses the same release counts above and each repository's public `stargazers_count` on November 23, 2026 (UTC): [Keep RAM Clean](https://api.github.com/repos/Andrew-Smith-93/keep-ram-clean) 3; [Tessera](https://api.github.com/repos/Andrew-Smith-93/Tessera) 1; [Codeward](https://api.github.com/repos/Andrew-Smith-93/codeward) 1. These are stars received per repository, not unique people or usage metrics.

## Profile-wide stats

Snapshot date: 2026-11-23 (UTC). The [profile stats card](../assets/profile-stats-2026-11-23-tokyonight-v1.svg) uses the [GitHub public owned repositories endpoint](https://api.github.com/users/Andrew-Smith-93/repos?type=owner&per_page=100). Seven public owned repositories fit on one page; one was a fork and was excluded. The profile README repository is included in the six non-forks and has no primary language.

| Metric | Count | Method |
| --- | ---: | --- |
| Public non-fork repositories | 6 | Exclude rows with `fork: true` |
| Stars received | 6 | Sum `stargazers_count` across those six: Keep RAM Clean 3; the profile repo, Codeward, and Tessera 1 each; the other two 0 |
| Distinct primary languages | 4 | Count distinct non-null `language` values: Assembly, HTML, Rust, TypeScript |

These are GitHub repository metadata counts. Stars received are not stars Andrew gave, unique people, usage, or downloads. Primary language is GitHub's repository-level label, not a complete language inventory or a proficiency measure. Private work and work in others' repositories are excluded.

## Modeled rank

GitHub Readme Stats returned **C+ · Top 78.5%** for Andrew-Smith-93 on November 23, 2026 (UTC). The [source card](https://github-readme-stats.vercel.app/api?username=Andrew-Smith-93&theme=tokyonight&rank_icon=percentile&show_icons=true&disable_animations=true) is linked for provenance only and may return a later value. The [open-source rank model](https://github.com/anuraghazra/github-readme-stats/blob/master/src/calculateRank.js) combines weighted activity inputs against its own distributions. Smaller "Top …%" values are stronger in this model. It is not an official GitHub rank, an empirical comparison with all GitHub users, or a measure of engineering quality. The README embeds only a static copy of those two values, not the third-party service.

The illustrations and both data cards use the [TokyoNight Night palette](https://github.com/folke/tokyonight.nvim/blob/main/lua/tokyonight/colors/night.lua); the surrounding README uses GitHub’s native theme.
