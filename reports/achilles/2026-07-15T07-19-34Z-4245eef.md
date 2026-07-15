# SBOM Summary Report

- **Repository:** Sharnlyra/achilles
- **Ref:** main
- **Commit:** 4245eef6870395f7dd5f5fe9a933b6d1352b29d3
- **Generated:** 2026-07-15 07:19:32 UTC

---

# SBOM Scan Summary Report

**Repository:** Sharnlyra/achilles
**Ref:** `main`
**Commit:** `4245eef6870395f7dd5f5fe9a933b6d1352b29d3`

---

## Executive Summary

This SCANOSS scan of the `achilles` repository returned **no meaningful component matches**. Of the 2 files scanned, both were unmatched against known third-party code or package signatures, and the single component record returned is empty (no PURL, vendor, name, version, or license data). There is currently **no actionable SBOM or license data** to assess for this commit — either the repository contains no detectable third-party code, or the scan scope was too limited to draw conclusions.

**Bottom line:** No license or dependency risk can be confirmed or ruled out at this time due to insufficient scan coverage.

---

## Scan Coverage Stats

| Metric | Value |
|---|---|
| Total files scanned | 2 |
| Matched files | 0 |
| Unmatched files | 2 |
| Unique components identified | 1 (empty/placeholder record) |
| Unique dependency components | 0 |
| Components truncated | No |
| Dependency components truncated | No |

⚠️ **Coverage is extremely low** — only 2 files were scanned in total, and neither produced a match. This suggests the scan may have been run against a very small subset of the repo (e.g., a single directory, changed files only, or a shallow clone) rather than the full codebase.

---

## License Breakdown

No license data was returned — the `license_breakdown` array is empty, and the sole component entry has no associated license.

**No copyleft, unusual, or otherwise notable licenses were detected**, but this should be read as **"none found"** rather than **"none present"**, given the near-total lack of matches.

---

## Key Third-Party Components

| Component | Vendor | Version | PURL | License(s) |
|---|---|---|---|---|
| *(none identified)* | — | — | — | — |

The single component record returned is empty across all fields and is not actionable — it likely represents a placeholder/null result rather than a real detected component. No dependency components were found either.

---

## Recommendations / Follow-Up Items

1. **Re-run the scan with full repository coverage.** Only 2 files were scanned — confirm the scan target included the entire working tree (source, manifests, lockfiles, vendored code) rather than a partial diff or single folder.
2. **Verify manifest/dependency files are present and scannable** (e.g., `package.json`, `requirements.txt`, `go.mod`, `Cargo.toml`, etc.). Zero dependency components suggests either the repo has no declared dependencies or these files weren't picked up.
3. **Investigate the empty component record** in the raw scan output — this may indicate a scanner parsing error or an artifact of an unrecognized file type rather than a true "no match."
4. **Do not treat this scan as a clean bill of health.** Given 0/2 files matched, this result should be treated as **inconclusive**, not as evidence of a dependency-free or license-clean codebase.
5. **Schedule a follow-up scan** once coverage issues are resolved, and re-generate this report with complete data before making any compliance or licensing decisions based on this repository.
