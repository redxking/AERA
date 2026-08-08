# Autonomous Enterprise Reference Architecture (AERA)

AERA is an independently authored, governance-first reference architecture for autonomous decision systems. It treats delegated decision authority and the decision transaction—not a model, agent, API call, or resource-access event—as the primary units of assurance.

This repository contains the controlled AERA 1.2 Working Draft artifact package.

## Status and boundaries

- **Edition:** AERA 1.2 Working Draft
- **Build:** `AERA-001-1.2WD-20260807.1`
- **Release state:** Developmental-review candidate; formal public review is not open
- **Author:** Angelis Pseftis
- **Normative status:** All 199 requirements remain `PROPOSED`
- **Assessment status:** Author-performed I1 publication-integrity review only; no independent I2/I3 validation, consensus determination, certification, or conformance grant
- **NIST boundary:** AERA is not a NIST publication or submission. No NIST support, approval, endorsement, adoption, certification, or correctness claim is made. The mapping ledger is developmental and is not OLIR submission-ready.

Public repository visibility provides public access to this working-draft snapshot. It does not open a formal review period or establish contribution, redistribution, derivative-work, patent, trademark, or implementation rights. See [LICENSE.md](LICENSE.md), [CONTRIBUTING.md](CONTRIBUTING.md), and [PUBLIC_REVIEW.md](PUBLIC_REVIEW.md).

## Controlled package

The authoritative human-readable representation is:

- [AERA 1.2 WD — Autonomous Enterprise Reference Architecture (PDF)](AERA_1.2_WD_Autonomous_Enterprise_Reference_Architecture.pdf)

The editable DOCX and machine-readable derivatives do not establish alternate normative meaning. A semantic mismatch with the authoritative PDF blocks release.

### Architecture and review documents

- [Architecture — DOCX](AERA_1.2_WD_Autonomous_Enterprise_Reference_Architecture.docx)
- [Architecture Integrity and NIST Readiness Review — PDF](AERA_1.2_WD_Architecture_Integrity_and_NIST_Readiness_Review.pdf) · [DOCX](AERA_1.2_WD_Architecture_Integrity_and_NIST_Readiness_Review.docx)
- [Public Review Brief — PDF](AERA_1.2_WD_Public_Review_Brief.pdf) · [DOCX](AERA_1.2_WD_Public_Review_Brief.docx)
- [Public Review Release Notes — PDF](AERA_1.2_WD_Public_Review_Release_Notes.pdf) · [DOCX](AERA_1.2_WD_Public_Review_Release_Notes.docx)

### Registers, traceability, and review controls

- Requirements: [XLSX](AERA_1.2_WD_Requirement_Register.xlsx) · [CSV](AERA_1.2_WD_Requirement_Register.csv)
- Threat-control-test matrix: [XLSX](AERA_1.2_WD_Threat_Control_Test_Matrix.xlsx) · [CSV](AERA_1.2_WD_Threat_Control_Test_Matrix.csv)
- Source register: [XLSX](AERA_1.2_WD_Source_Register.xlsx) · [CSV](AERA_1.2_WD_Source_Register.csv)
- [Review Comment Matrix — XLSX](AERA_1.2_WD_Review_Comment_Matrix.xlsx)
- [NIST Mapping Development Ledger — XLSX](AERA_1.2_WD_NIST_Mapping_Development_Ledger.xlsx)

### Integrity and validation records

- [Release manifest](AERA_1.2_WD_Release_Manifest.json)
- [SHA-256 checksums](AERA_1.2_WD_SHA256SUMS.txt)
- [QA validation record](AERA_1.2_WD_QA_Validation.json)
- [PDF metadata and accessibility-control record](AERA_1.2_WD_PDF_Metadata_Validation.txt)

The package records 31 automated checks, 199 requirements, 25 threats, 69 controlled sources, and visual inspection of 89 rendered PDF pages. Its result is **PASS WITH RELEASE GATES**, not an unconditional release, conformance, accessibility-certification, or external-validation claim.

## Verify integrity

From the repository root on macOS:

```sh
shasum -a 256 -c AERA_1.2_WD_SHA256SUMS.txt
```

On systems with GNU coreutils:

```sh
sha256sum -c AERA_1.2_WD_SHA256SUMS.txt
```

All 19 listed entries must report `OK`. The checksum file itself is not self-hashed.

## Repository scope

This repository is the controlled publication-artifact package. Obsolete editions, authoring intermediates, render images, audit scratch files, IDE configuration, and the non-portable internal build workspace are intentionally excluded.

## Citation

Use the metadata in [CITATION.cff](CITATION.cff) and cite the authoritative PDF, edition, build identifier, author, and repository URL. Citation does not imply endorsement or grant additional rights.
