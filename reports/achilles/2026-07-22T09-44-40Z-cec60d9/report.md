# SBOM Summary Report

- **Repository:** Sharnlyra/achilles
- **Ref:** main
- **Commit:** cec60d97191f0ebda74ceb60a2c6fe73b279388b
- **Generated:** 2026-07-22 09:44:38 UTC

---

## Executive Summary
This scan of the `Sharnlyra/achilles` repository (commit `cec60d9`, `main` branch) examined 3 files but found no matches to known open-source components, licenses, or dependencies. As a result, there is nothing to flag from a licensing or component-risk standpoint in this run. Vulnerability scanning was not part of this scan, so no statement can be made about the security status of any code.

## Risk Highlights
- **Copyleft-flagged components:** None found — the flagged_copyleft_components list is empty.
- **Vulnerable components:** None reported, but note this is because vulnerability data was not collected in this scan (see Vulnerabilities section below), not because components were checked and found clean.
- **Unknown-risk licenses:** None — risk_counts is empty, indicating no components were identified at all.

## Scan Coverage
- Total files scanned: 3
- Matched files: 0
- Unmatched files: 3
- Unique components identified: 0
- Unique dependency components identified: 0

## License Breakdown
No license data available — no components were matched in this scan, so there is nothing to report.

## Third-Party Components
No third-party components were identified in this scan. The `components` list is empty and `components_truncated` is false, confirming this is a complete (not capped) result — the repository's scanned files simply did not match any known open-source components.

## Dependencies
No dependency components were identified (`dependency_components` is empty). This section is otherwise omitted per report guidance, but is noted here for completeness given the total absence of data.

## Vulnerabilities
Vulnerability scanning was **not** part of this scan run (`vulnerability_data_present: false`). This means no vulnerability data was collected — it does not mean the codebase is free of vulnerabilities. To enable vulnerability detection in future scans, configure a Dependency Track integration or use a premium SCANOSS API tier that supports vulnerability lookups.

## Snippet Matches
No snippet-level matches were found or recorded (`snippet_matches` is empty, `snippet_matches_total: 0`, not truncated).

## Recommendations
1. **Verify scan scope:** With only 3 files scanned and zero matches, confirm that the scan target actually covers the intended codebase — a very small file count may indicate the scan ran against a limited path, an early-stage/empty repository, or a misconfigured scan root.
2. **Re-run with broader coverage:** If this repository is expected to contain open-source dependencies (e.g., via a package manager manifest), ensure those manifest files are included in the scan input so dependency and license data can be captured.
3. **Enable vulnerability scanning:** Integrate Dependency Track or upgrade to a SCANOSS tier with vulnerability data to get actual CVE/security visibility — this is currently a blind spot.
4. **Re-scan as the project grows:** Since this appears to be an early or minimal codebase, schedule periodic re-scans as source files and dependencies are added, to catch license and security risks as they're introduced.
