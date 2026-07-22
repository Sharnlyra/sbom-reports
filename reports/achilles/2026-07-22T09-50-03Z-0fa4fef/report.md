# SBOM Summary Report

- **Repository:** Sharnlyra/achilles
- **Ref:** main
- **Commit:** 0fa4fef27bc894d282a2019e45035a0d1d8d2295
- **Generated:** 2026-07-22 09:50:01 UTC

---

## Executive Summary
This scan of the `Sharnlyra/achilles` repository (ref `main`, commit `0fa4fef`) examined 3 files and found no matches to known open-source components, licenses, or dependencies. In practical terms, the scanner did not identify any third-party code, license obligations, or vulnerability data to report for this run. This may reflect a genuinely small/original codebase, but it could also mean the scan had limited coverage — see Recommendations below.

## Risk Highlights
- **Copyleft licenses:** None flagged — `flagged_copyleft_components` is empty.
- **Vulnerable components:** None identified — but note this is because vulnerability data collection was not part of this scan (see Vulnerabilities section), not because components were checked and found clean.
- **Unknown-risk licenses:** No unknown-risk components recorded (`risk_counts` is empty).
- Overall, there is nothing actionable in this scan's findings, largely because no components were matched at all.

## Scan Coverage
- Total files scanned: 3
- Matched files: 0
- Unmatched files: 3
- Unique components identified: 0
- Unique dependency components identified: 0

## License Breakdown
No license data was returned — the license breakdown list is empty, consistent with zero matched components.

## Third-Party Components
No third-party components were identified in this scan (`components` is empty). There is nothing to tabulate.

## Dependencies
No dependency components were identified (`dependency_components` is empty). This section is otherwise omitted per the empty-data rule.

## Vulnerabilities
Vulnerability scanning was **not** part of this run (`vulnerability_data_present` is `false`). This means no conclusion can be drawn about the presence or absence of vulnerabilities — it simply was not checked. To enable vulnerability detection in future scans, connect a Dependency Track integration or use a premium SCANOSS API tier that supports vulnerability enrichment.

## Snippet Matches
No snippet-level matches were recorded (`snippet_matches` is empty, `snippet_matches_total` is 0). There were no source-code fragments detected as matching known open-source snippets in the 3 scanned files.

## Recommendations
1. **Verify scan coverage:** With only 3 files scanned and 0 matched, confirm that the scan actually traversed the full repository (e.g., check for `.gitignore`/scan-path exclusions or build artifacts that may not have been included). A near-total absence of matches on an active project is worth double-checking.
2. **Enable vulnerability scanning:** Integrate Dependency Track or upgrade to a SCANOSS tier with vulnerability data so future scans can surface CVE exposure in used components.
3. **Re-run after adding manifests:** If the repository uses dependency manifests (e.g., `package.json`, `requirements.txt`, `pom.xml`), ensure they are present and readable at the scanned commit, since dependency component detection depends on them being parsed correctly.
4. **Schedule periodic re-scans:** As the codebase grows and dependencies are added, periodic re-scanning will ensure license and vulnerability risks are caught early.
5. **No immediate license or security action required** based on this scan's output, but treat the "no findings" result as inconclusive rather than a clean bill of health until coverage is confirmed.
