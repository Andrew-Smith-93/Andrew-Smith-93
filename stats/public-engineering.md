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

## Release cadence

The 90-day release window is August 26 through November 23, 2026 UTC, inclusive. For the public profile, stable release counts by calendar month were September **3**, October **0**, and November **6** through November 23. A month without a release does not imply a month without work.

The [Keep RAM Clean GitHub release endpoint](https://api.github.com/repos/Andrew-Smith-93/keep-ram-clean/releases?per_page=100) shows five stable releases on three publication dates: **1** on November 19 (v2.0.0), **2** on November 21 (v2.1.0, v2.2.0), and **2** on November 23 (v2.2.1, v2.3.0). Chart bars use a common zero and linear scale within each chart.

Release notes: [Keep RAM Clean v2.2.1](https://github.com/Andrew-Smith-93/keep-ram-clean/releases/tag/v2.2.1) (Debian 12 amd64 packaging fix), [v2.3.0](https://github.com/Andrew-Smith-93/keep-ram-clean/releases/tag/v2.3.0) (opt-in workload discovery), and [Tessera v1.0.2](https://github.com/Andrew-Smith-93/Tessera/releases/tag/v1.0.2) (shortcut settings and multi-monitor snapping fixes).

## Tessera pull requests

| Window (UTC calendar dates, inclusive) | Andrew-authored | Dependabot-authored | Total merged |
| --- | ---: | ---: | ---: |
| 30 days, Oct 25–Nov 23, 2026 | 2 | 4 | 6 |
| 90 days, Aug 26–Nov 23, 2026 | 12 | 5 | 17 |

Use the [closed PR endpoint](https://api.github.com/repos/Andrew-Smith-93/Tessera/pulls?state=closed&per_page=100), filter by `merged_at` within each window, and group by `user.login`. The 30-day row includes #19–#24 and is a subset of the 90-day row. It counts merged PRs by PR author, not reviews, commits, or unmerged proposals.

## Package download requests

The [Keep RAM Clean release endpoint](https://api.github.com/repos/Andrew-Smith-93/keep-ram-clean/releases?per_page=100) returned **9** total download requests for published Debian `.deb` assets on November 23, 2026 UTC:

| Release | GitHub `.deb` download requests |
| --- | ---: |
| v2.3.0 | 4 |
| v2.2.1 | 2 |
| v2.2.0 | 3 |

The snapshot sums `assets[].download_count` for amd64 Debian package files on stable releases. Standalone executables, checksums, and provenance files are excluded. GitHub counts requests, not unique people, successful installations, or active usage. These cumulative counts can include repeated and automated downloads.

Separately, the [crates.io crate record](https://crates.io/api/v1/crates/keep-ram-clean) identifies this project's GitHub repository and reported **17** cumulative crate download requests on November 23, 2026 UTC: **7** for v2.3.0 and **10** for v2.2.0. The registry serves Rust crate source packages; GitHub serves the selected Debian binary package files. The counters have different scopes, may include automation, and should not be added or treated as installs or unique users.
