# SBOM Summary Report

- **Repository:** Sharnlyra/achilles
- **Ref:** main
- **Commit:** f08f03fbcb4c2519a9f0ee9dcf6a9197fd2915af
- **Generated:** 2026-07-15 12:44:38 UTC

---

## Executive Summary
A SCANOSS scan was run against the `Sharnlyra/achilles` repository (ref `main`, commit `f08f03f`), covering 3 files. None of these files matched any known open-source components, snippets, or dependencies in the SCANOSS knowledge base. As a result, there is no license, vulnerability, or component data to report for this scan run — this is a "clean/no-match" result rather than an indication of any problem.

## Risk Highlights
- **Copyleft licenses:** None flagged — `flagged_copyleft_components` is empty.
- **Vulnerable components:** None identified — but see the Vulnerabilities section, as vulnerability data collection was not enabled for this scan.
- **Unknown-risk licenses:** `risk_counts` is empty, so there are no components with unclassified license risk to review.
- Overall, there is nothing in this scan that requires immediate human review, primarily because no components were detected at all.

## Scan Coverage
- Total files scanned: 3
- Matched files: 0
- Unmatched files: 3
- Unique components identified: 0
- Unique dependency components identified: 0
- Snippet matches found: 0

## License Breakdown
No license data available — `license_breakdown` is empty, as no components were matched in this scan.

## Third-Party Components
No components were identified in this scan (`components` is empty). There is no table to display.

## Dependencies
No dependency components were identified in this scan (`dependency_components` is empty). There is no table to display.

## Vulnerabilities
Vulnerability data was **not collected** as part of this scan run (`vulnerability_data_present: false`). This means the absence of vulnerability findings should **not** be interpreted as "no vulnerabilities exist" — it simply reflects that vulnerability scanning was not active for this run. To enable vulnerability detection, integrate a Dependency Track instance or use a premium SCANOSS API tier that supports vulnerability lookups.

## Snippet Matches
No snippet-level matches were found (`snippet_matches` is empty, `snippet_matches_total: 0`). This is consistent with the overall result of 0 matched files.

## Recommendations
1. **Verify scan scope:** Confirm that the 3 scanned files represent the intended/complete codebase for this repository — a very small file count with zero matches may indicate the scan target was limited (e.g., only a subset of the repo, or mostly non-code files such as config/docs).
2. **Re-run with broader coverage:** If the repository contains more source files than the 3 scanned, check the scan configuration (include/exclude patterns, ignored directories) to ensure nothing was inadvertently excluded.
3. **Enable vulnerability scanning:** Integrate Dependency Track or upgrade to a SCANOSS tier with vulnerability data support so future scans can surface known CVEs in any third-party code that is present.
4. **Periodic re-scan:** Since no components/licenses were detected, treat this as a baseline result. Re-scan after any significant code changes or dependency additions to catch newly introduced third-party code.
5. **Manual spot-check:** Given the low file count, consider a manual review of the repository to confirm it does not, in fact, contain vendored or copied open-source code that fell outside SCANOSS's matching capability (e.g., heavily modified snippets).
