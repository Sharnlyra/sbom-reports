# SBOM Summary Report

- **Repository:** Sharnlyra/achilles
- **Ref:** main
- **Commit:** 4107135b067b2bc32e9f9ceade7ee1603273a2d6
- **Generated:** 2026-07-17 11:36:29 UTC

---

## Executive Summary

A SCANOSS scan was run against the `Sharnlyra/achilles` repository (commit `4107135`) on the `main` branch. The scan examined 3 files but found no matches to known open-source components, licenses, or code snippets. In plain terms: this scan did not identify any third-party code, license obligations, or dependencies to review — either because the repository doesn't contain any recognizable open-source components, or because the scanned files fell outside what SCANOSS could fingerprint.

## Risk Highlights

- **Copyleft licenses:** None flagged — `flagged_copyleft_components` is empty.
- **Vulnerable components:** None flagged — but see note below, vulnerability scanning wasn't part of this run.
- **Unknown-risk licenses:** None recorded (`risk_counts` is empty).
- Overall, there is nothing in this scan requiring immediate human review, largely because no components were matched at all.

## Scan Coverage

- Total files scanned: **3**
- Files matched to known components: **0**
- Files unmatched: **3**
- Unique components identified: **0**
- Unique dependency-manifest components identified: **0**

## License Breakdown

No license data was returned — `license_breakdown` is empty. There are no licenses to report for this scan.

## Third-Party Components

No components were identified in this scan (`components` is empty). There is no table to display, and `components_truncated` is `false`, confirming this is a complete (empty) result rather than a capped list.

## Dependencies

No dependency-manifest components were identified (`dependency_components` is empty). This section is otherwise omitted per the reporting guidance, but is noted here for completeness since no dependency data was found at all.

## Vulnerabilities

`vulnerability_data_present` is **false** for this scan. This means vulnerability scanning was **not part of this run** — the absence of entries in `vulnerable_components` should **not** be read as "zero vulnerabilities found." To enable vulnerability detection in future scans, connect a Dependency Track integration or use a premium SCANOSS API tier that supports CVE matching.

## Snippet Matches

No snippet-level matches were found (`snippet_matches` is empty, `snippet_matches_total` is 0, and `snippet_matches_truncated` is `false`). There is no code-similarity data to review for this scan.

## Recommendations

1. **Verify scan scope:** Confirm that the 3 scanned files represent the full intended codebase for this commit. A result of 0 matched components across only 3 files may indicate the scan targeted a small subset of the repository (e.g., excluded build artifacts, vendored code, or large source directories) rather than the full project.
2. **Re-run with broader coverage:** If the repository contains more source files than the 3 scanned, re-run SCANOSS against the complete file tree to ensure open-source components and license obligations are properly captured.
3. **Enable vulnerability scanning:** Integrate Dependency Track (or upgrade to a SCANOSS tier with CVE support) so future scans can surface known vulnerabilities in any dependencies that are identified.
4. **Re-check after dependency manifests are added:** If this project uses a package manager (npm, pip, Maven, etc.), ensure manifest files (package.json, requirements.txt, pom.xml, etc.) are present and included in the scan path, since `dependency_components` returned empty.
5. **Schedule periodic re-scans:** As code and dependencies are added to the repository, run SCANOSS scans regularly to catch newly introduced open-source components, license risks, and vulnerabilities early.
