# Public engineering snapshot

Snapshot date: 2026-11-17 (UTC). This file and the SVG are a static snapshot, not an automatically updating service.

## Counts

| Metric | Count | Scope |
| --- | ---: | --- |
| Tessera merged pull requests | 15 | All merged PRs in the public repository |
| Andrew-Smith-93-authored Tessera merged PRs | 10 | PR author login, not commit authorship |
| Dependabot-authored Tessera merged PRs | 5 | Automation included separately |
| Tessera published releases | 2 | v1.0.1, v1.0.2 |
| Codeward published releases | 1 | v1.0.0 |

## Sources and method

- [Tessera closed pull requests, GitHub REST API](https://api.github.com/repos/Andrew-Smith-93/Tessera/pulls?state=closed&per_page=100): fetched 22 records, retained the 15 with non-null `merged_at`. The complete result fits one page. Grouped retained records by `user.login`.
- [Tessera releases, GitHub REST API](https://api.github.com/repos/Andrew-Smith-93/Tessera/releases?per_page=100): 2 records, both published, non-draft, and non-prerelease.
- [Codeward releases, GitHub REST API](https://api.github.com/repos/Andrew-Smith-93/codeward/releases?per_page=100): 1 record, published, non-draft, and non-prerelease.
- PR numbers included: #22, #21, #20, #19, #16, #15, #14, #13, #12, #11, #10, #9, #8, #7, #6.

The top bar divides all 15 merged PRs by author category (10/15 and 5/15). Release bars share a zero baseline and the same scale (160 SVG units per release).

These are repository totals, not claims of personal authorship of every change. They do not measure customers, downloads, production readiness, revenue, review quality, or current test results. Private repositories are excluded. Refresh the API reads and regenerate the counts, date, SVG labels, and README alt text together when updating.
