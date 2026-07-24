# SBOM Summary Report

- **Repository:** Sharnlyra/achilles
- **Ref:** main
- **Commit:** 86b78616bcf73de0fc56acf810c331af531235ee
- **Generated:** 2026-07-24 07:44:09 UTC

---

## Executive Summary
This scan of the Sharnlyra/achilles repository (main branch, commit 86b7861) found no matches to known open-source components. Of the 3 files scanned, none matched any third-party code, license, or dependency signatures in the SCANOSS database. As a result, there is no license, component, or vulnerability data to report from this run.

## Risk Highlights
- **Copyleft licenses**: None flagged — `flagged_copyleft_components` is empty.
- **Vulnerable components**: None flagged — but see Vulnerabilities section below; this scan did not collect vulnerability data at all, so absence of findings here is not a clean bill of health.
- **Unknown-risk components**: None — `risk_counts` is empty, indicating no components were identified to classify.

## Scan Coverage
- Total files scanned: 3
- Matched files: 0
- Unmatched files: 3
- Unique components identified: 0
- Unique dependency components identified: 0

## License Breakdown
No license data available — no components were matched during this scan.

## Third-Party Components
No third-party components were identified in this scan. The `components` list is empty, and `components_truncated` is false, indicating this is a complete (empty) result rather than a capped list.

## Dependencies
No dependency components were identified (`dependency_components` is empty).

## Vulnerabilities
Vulnerability data was **not collected** as part of this scan (`vulnerability_data_present` is false). This means the absence of vulnerable components in the results should **not** be interpreted as "no vulnerabilities found" — it simply reflects that vulnerability scanning was not enabled for this run. To enable vulnerability detection, integrate SCANOSS with a Dependency Track instance or use a premium API tier that supports vulnerability lookups, then re-run the scan.

## Snippet Matches
No snippet-level matches were found or recorded (`snippet_matches` is empty, `snippet_matches_total` is 0, and the list was not truncated).

## Recommendations
1. **Verify scan scope**: With only 3 files scanned and zero matches, confirm that the scan target correctly covered the full repository (e.g., check for `.scanoss` ignore rules, build artifacts, or vendored directories that may have been excluded).
2. **Re-run with vulnerability scanning enabled**: Connect this scan to a Dependency Track integration or upgrade to a tier with vulnerability data support to get meaningful CVE/severity coverage, since none was collected here.
3. **Investigate zero-match result**: A repository with no matched open-source components is unusual unless the codebase is entirely proprietary/original code with no third-party libraries. Manually spot-check the 3 scanned files to confirm this is expected and not a scanning configuration issue (e.g., binary files, minified code, or unsupported file types).
4. **Re-scan after any dependency additions**: If this repository is expected to grow to include external libraries or SBOM-declared dependencies, re-run the scan once those are added to establish a baseline for license and vulnerability risk.
5. **Treat this as inconclusive, not clean**: Do not communicate this result internally as "no risks found" — clarify that it reflects a lack of matched data rather than a confirmed risk-free codebase.
