# GML Schema Upgrade Policy

---

**GML** is a governed public language. All changes must preserve traceability, compatibility, and stewardship integrity.

### 🎯 Purpose

To ensure the schema can evolve **without breaking trust**, while maintaining interoperability and public oversight.

---

## 📌 Semantic Versioning Rules

- `MAJOR.MINOR.PATCH` format (e.g. `v1.0.0`)
- PATCH: Fixes or documentation changes
- MINOR: Additive, backward-compatible schema changes
- MAJOR: Breaking or structurally incompatible changes

---

## 🧭 Governance Policy

1. **Version Declaration Required**  
   All GML logic must declare a `schema version`.

2. **Backward Compatibility Required for MINOR / PATCH**  
   MINOR and PATCH changes must not break existing logic.

3. **Breaking Changes Require Steward Approval**  
   All MAJOR schema changes must be approved by a supermajority of Covenant Trust stewards.

4. **Deprecation Requires 12-Month Notice**  
   Deprecated schema versions must remain executable for 12 months unless security dictates otherwise.

5. **EOS Must Support 2 Major Versions**  
   The EOS execution engine must maintain support for the current and previous major schema versions.

6. **Changelog Must Remain Public and Signed**  
   All version updates must be documented in `CHANGELOG.md` and optionally published on covenanttrust.org.

---

## 🛡️ Stewardship and Evolution

The Covenant Trust acts as provisional steward of the schema.

Long-term governance may transition to a federated model based on:

- Regional ethics boards
- Open schema consortia
- Multi-jurisdictional governance

This file forms part of the constitutional framework for logic execution infrastructure.
