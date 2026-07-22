# SBOM Summary Report

- **Repository:** Sharnlyra/achilles
- **Ref:** main
- **Commit:** e1930ba2bd8aa7572945129798a5a0c11494287b
- **Generated:** 2026-07-22 08:49:52 UTC

---

## Executive Summary
This scan of the `Sharnlyra/achilles` repository (commit `e1930ba`) examined 3 files but found no matches to any known open-source components, libraries, or snippets. As a result, there is no license, dependency, or vulnerability data to report from this run. This likely means the scanned files contain original code, or the codebase is very small/limited in scope for this scan.

## Risk Highlights
- **Copyleft licenses:** None flagged — `flagged_copyleft_components` is empty.
- **Vulnerable components:** None found — however, see the Vulnerabilities section below, as vulnerability data was not collected in this run.
- **Unknown-risk components:** None — `risk_counts` is empty, indicating no components were identified at all.

Overall, there is nothing actionable to flag from this scan, but this is due to an absence of matched data rather than a confirmed clean bill of health.

## Scan Coverage
- Total files scanned: 3
- Matched files: 0
- Unmatched files: 3
- Unique components identified: 0
- Unique dependency components identified: 0

## License Breakdown
No license data was identified — the `license_breakdown` list is empty. No table is provided since there is nothing to report.

## Third-Party Components
No third-party components were matched in this scan (`components` is empty). Nothing to report in table form.

## Dependencies
No dependency components were identified (`dependency_components` is empty). Nothing to report in table form.

## Vulnerabilities
Vulnerability scanning was **not part of this run** — `vulnerability_data_present` is `false`. This means no conclusion can be drawn about whether vulnerabilities exist in this codebase; it simply was not checked. To enable vulnerability data collection, connect a Dependency Track integration or use a premium SCANOSS API tier that supports vulnerability lookups.

## Snippet Matches
No snippet-level matches were found (`snippet_matches` is empty, `snippet_matches_total` is 0). No table is provided since there is nothing to report.

## Recommendations
1. **Verify scan scope:** With only 3 files scanned and none matched, confirm that the scan target actually covers the full repository (e.g., check for `.gitignore`/scan-path exclusions, submodules, or build artifacts that might not have been included).
2. **Re-run with broader inclusion:** If the repository has more source files (e.g., in subdirectories, vendored code, or a build/dist folder), consider re-scanning with expanded file inclusion rules to ensure nothing is missed.
3. **Enable vulnerability scanning:** Integrate with Dependency Track or upgrade to a premium SCANOSS tier to get vulnerability data on any current or future third-party components.
4. **Re-scan after development progresses:** As the codebase grows and dependencies are added, periodic re-scans will help catch newly introduced third-party code, license obligations, and vulnerabilities early.
5. **Manual spot-check:** Given the very limited scan surface (3 files), consider a quick manual review to confirm there are no unmanaged third-party files that a SCA tool might not have picked up.
