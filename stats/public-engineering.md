# Public engineering snapshot

Static snapshot, November 23, 2026 (UTC). [Text version](../profile-text.md) · [Card view](../README.md).

## Repository stats

| Project | Latest stable GitHub release as of snapshot | Other activity |
| --- | --- | --- |
| Keep RAM Clean | [v2.3.0](https://github.com/Andrew-Smith-93/keep-ram-clean/releases/tag/v2.3.0) · Nov 23 | 5 stable releases published Nov 19–23 |
| Tessera | [v1.0.2](https://github.com/Andrew-Smith-93/Tessera/releases/tag/v1.0.2) · Sep 28 | 17 merged PRs: 12 authored by Andrew and 5 by Dependabot |

The [Tessera closed PR endpoint](https://api.github.com/repos/Andrew-Smith-93/Tessera/pulls?state=closed&per_page=100) returned 24 closed records. The count retains 17 with non-null `merged_at` through November 23 (all within the 90-day window), grouped by PR author login: `Andrew-Smith-93` (12) and `dependabot[bot]` (5). This attributes the PRs, not every commit. Counted PRs: #24, #23, #22, #21, #20, #19, #16, #15, #14, #13, #12, #11, #10, #9, #8, #7, #6.

## Profile-wide stats

**9 stable GitHub releases across 3 repositories** over 90 UTC calendar days, August 26 through November 23, 2026, inclusive. There were 3 in September and 6 in November. The totals include all qualifying owned public non-forks, not only the featured projects.

The [public owned repository endpoint](https://api.github.com/users/Andrew-Smith-93/repos?type=owner&per_page=100) returned seven public repositories. One fork was excluded. For each of the six remaining repositories, read its releases endpoint and retained entries where `draft` and `prerelease` were false and `published_at` satisfied `>= 2026-08-26T00:00:00Z` and `< 2026-11-24T00:00:00Z`. Dates are publication dates, not Git tag dates. Package registry publishes, private repos, and activity in repositories owned by others are outside this snapshot.

| Releases endpoint | Count | Included versions and publication dates (UTC) |
| --- | ---: | --- |
| [Keep RAM Clean](https://api.github.com/repos/Andrew-Smith-93/keep-ram-clean/releases?per_page=100) | 5 | v2.0.0 Nov 19; v2.1.0 and v2.2.0 Nov 21; v2.2.1 and v2.3.0 Nov 23 |
| [Tessera](https://api.github.com/repos/Andrew-Smith-93/Tessera/releases?per_page=100) | 2 | v1.0.1 Sep 27; v1.0.2 Sep 28 |
| [Codeward](https://api.github.com/repos/Andrew-Smith-93/codeward/releases?per_page=100) | 2 | v1.0.0 Sep 20; v2.0.0 Nov 23 |
| [Profile](https://api.github.com/repos/Andrew-Smith-93/Andrew-Smith-93/releases?per_page=100), [Andrew-Smith-93.github.io](https://api.github.com/repos/Andrew-Smith-93/Andrew-Smith-93.github.io/releases?per_page=100), [bone-lab-assembly](https://api.github.com/repos/Andrew-Smith-93/bone-lab-assembly/releases?per_page=100) | 0 | None |

These counts describe published release and PR activity, not usage or software quality. When refreshing the snapshot, update the cards, alt text, text version, and scope together.
