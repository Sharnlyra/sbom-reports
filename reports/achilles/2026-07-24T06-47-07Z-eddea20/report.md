# SBOM Summary Report

- **Repository:** Sharnlyra/achilles
- **Ref:** main
- **Commit:** eddea20424ae72e726114ebfbe17278de96d4e7a
- **Generated:** 2026-07-24 06:47:05 UTC

---

## Executive Summary
This scan of the Sharnlyra/achilles repository (main branch, commit eddea20) found no matches against known open-source components. Of the 3 files scanned, none matched third-party code, meaning no license, component, or snippet data was identified. No dependency information was detected either. Overall, this scan surfaces no supply-chain findings to review — but this likely reflects the small scope of the scan (only 3 files) rather than a confirmed clean bill of health.

## Risk Highlights
- **Copyleft licenses:** None flagged — `flagged_copyleft_components` is empty.
- **Vulnerabilities:** No vulnerability data was collected in this scan run (see Vulnerabilities section below) — this is not the same as "zero vulnerabilities found."
- **Unknown-risk licenses:** None — `risk_counts` contains no entries at all, indicating no licensed components were identified.

## Scan Coverage
- Total files scanned: 3
- Matched files: 0
- Unmatched files: 3
- Unique components identified: 0
- Unique dependency components identified: 0
- Snippet matches: 0

## License Breakdown
No license data available — no components were matched during this scan, so no licenses were identified.

## Third-Party Components
No third-party components were identified in this scan (`components` is empty). The list was not truncated.

## Dependencies
No dependency components were identified in this scan (`dependency_components` is empty).

## Vulnerabilities
Vulnerability data was **not collected** as part of this scan run. This scan does not include a Dependency Track integration or premium API tier, so no CVE or severity information is available. This should not be interpreted as evidence that the codebase is free of known vulnerabilities — it simply means vulnerability scanning was not performed. To enable vulnerability detection, configure a Dependency Track integration or upgrade to a SCANOSS premium API tier for future scans.

## Snippet Matches
No snippet-level matches were found or recorded in this scan (`snippet_matches` is empty, total count 0).

## Recommendations
1. **Verify scan scope:** Only 3 files were scanned with zero matches — confirm this is the intended scope for the repository (e.g., check if the scan was run against a subdirectory, a stripped-down branch, or an incomplete checkout) rather than the full codebase.
2. **Re-run with broader coverage:** If the intent was to assess the full `achilles` repository, re-trigger the scan against the complete source tree to ensure dependency manifests (e.g., package.json, requirements.txt, go.mod) and source files are included.
3. **Enable vulnerability scanning:** Integrate Dependency Track or upgrade to a premium SCANOSS tier so future scans can surface known CVEs against detected components.
4. **Re-scan after dependency detection:** Once components and dependencies are properly identified, review the License Breakdown and Third-Party Components sections for copyleft or unknown-risk licenses requiring legal/compliance review.
5. **Schedule periodic re-scans:** Establish a recurring scan cadence (e.g., on each release or weekly) once full coverage is confirmed, to catch newly introduced components, licenses, or vulnerabilities over time.
