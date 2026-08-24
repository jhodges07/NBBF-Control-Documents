# NONCANONICAL HISTORICAL EVIDENCE — CWC #42 INVENTORY

**Classification of this file:** NONCANONICAL  
**Not CONTROL authority.**

Captured restore dirty state (`git status --porcelain=v1 -uall`) before copy:

```
MD controls/00C_Property_Rights_and_Pooling_Control.txt
 D controls/00D_Exit_and_Disengagement_Control.txt
MM controls/00_Control.txt
 D controls/03_Constitutional_Authority_Model.txt
 D controls/05_Four_Month_Budget_Cycle.txt
 D controls/07_Audit_and_Performance_Standards.txt
 D controls/08_Exit_and_Clawback_Rules.txt
 D controls/09_Legacy_and_Sealed_Nodes.txt
 D controls/10_Senate_Interface_Rules.txt
 D controls/11_Public_Transparency_and_Publishing.txt
?? .cursor/rules/NBBF_Specification.md
?? controls/03_Republican_Government_Model.txt
?? controls/05_Authority_Review_and_Reauthorization_Cycle.txt
?? controls/07_Signal_Integrity_and_Non-Interference.txt
?? controls/08_Audit_and_Performance_Standards.txt
?? controls/09_Recovery_Exit_and_Clawback_Rules.txt
?? controls/10_Lifecycle_and_Legacy_Node_Management.txt
?? controls/11_Legislative_Decision_Interface.txt
?? controls/12_Public_Transparency_API_and_Digital_Republic.txt
?? controls/NBBF_Design_Philosophy.txt
?? controls/NBBF_Master_Blueprint.txt
?? controls/pdfs/NBBF_Design_Philosophy_v2_Draft.pdf
```

Staged (index) at freeze:

- `M controls/00C_Property_Rights_and_Pooling_Control.txt`
- `M controls/00_Control.txt`

Unstaged at freeze:

- `D` of the deleted committed `.txt` CONTROLs listed above
- `D controls/00C_Property_Rights_and_Pooling_Control.txt` (worktree deleted after staged edit)
- `M controls/00_Control.txt` (additional unstaged edit on top of staged edit)

Equivalent content on `origin/main`: **none** of these historical `.txt` / PDF / `.cursor` paths exist on `origin/main`.

SHA-256 below is of the **preserved copy**, verified equal to the **source** unless noted.

Empty-file SHA-256 `e3b0c44298fc1c149afbf4c8996fb92427ae41e4649b934ca495991b7852b855` is the SHA-256 of a zero-byte file.

---

## A. Copied from current dirty worktree

| Original restore path | Evidence destination | Size | SHA-256 | Git status | On origin/main | In prior reconciliation-evidence | Classification | NONCANONICAL |
|---|---|---|---|---|---|---|---|---|
| `controls/00_Control.txt` | `files/from-dirty-worktree/controls/00_Control.txt` | 8412 | `fb1cb8b9164904bb1e7e1f28c91e90a38f3931226bc0f8681dd36cd4383ead80` | modified (MM; this is the worktree bytes) | no | yes — byte-identical to `NOT_CANONICAL_Root_v2.0.txt` | DUPLICATE HISTORICAL EVIDENCE; SUPERSEDED HISTORICAL CONTROL | YES |
| `controls/03_Republican_Government_Model.txt` | `files/from-dirty-worktree/controls/03_Republican_Government_Model.txt` | 0 | `e3b0c44298fc1c149afbf4c8996fb92427ae41e4649b934ca495991b7852b855` | untracked | no | empty content matches `NOT_CANONICAL_CONTROL_12_placeholder.txt` | SUPERSEDED HISTORICAL CONTROL (empty path freeze; not live CONTROL 03) | YES |
| `controls/05_Authority_Review_and_Reauthorization_Cycle.txt` | `files/from-dirty-worktree/controls/05_Authority_Review_and_Reauthorization_Cycle.txt` | 0 | `e3b0c44298fc1c149afbf4c8996fb92427ae41e4649b934ca495991b7852b855` | untracked | no | empty-content duplicate | SUPERSEDED HISTORICAL CONTROL (empty path freeze; not live CONTROL 05) | YES |
| `controls/07_Signal_Integrity_and_Non-Interference.txt` | `files/from-dirty-worktree/controls/07_Signal_Integrity_and_Non-Interference.txt` | 6105 | `024244c1cb02c000872549e50a3ddec97a2397b1545d0e7c7f089ab7887e036c` | untracked | no | yes — byte-identical to `NOT_CANONICAL_CONTROL_07_v1.0_pre-CWC-13.txt` | UNKNOWN — HUMAN REVIEW REQUIRED (filename claims Signal; content is CONTROL 07 v1.0 evidence) | YES |
| `controls/08_Audit_and_Performance_Standards.txt` | `files/from-dirty-worktree/controls/08_Audit_and_Performance_Standards.txt` | 9410 | `8a4d356d0750f88be41b8a4686ca57a3e6d224fcf0b156dd6d60e0ce6318eeaf` | untracked | no | yes — byte-identical to `NOT_CANONICAL_Signal_v2.1_from_restore_08.txt` | UNKNOWN — HUMAN REVIEW REQUIRED (filename claims Audit; prior evidence labeled this path as Signal v2.1) | YES |
| `controls/09_Recovery_Exit_and_Clawback_Rules.txt` | `files/from-dirty-worktree/controls/09_Recovery_Exit_and_Clawback_Rules.txt` | 0 | `e3b0c44298fc1c149afbf4c8996fb92427ae41e4649b934ca495991b7852b855` | untracked | no | empty-content duplicate | SUPERSEDED HISTORICAL CONTROL (empty path freeze) | YES |
| `controls/10_Lifecycle_and_Legacy_Node_Management.txt` | `files/from-dirty-worktree/controls/10_Lifecycle_and_Legacy_Node_Management.txt` | 0 | `e3b0c44298fc1c149afbf4c8996fb92427ae41e4649b934ca495991b7852b855` | untracked | no | empty-content duplicate | SUPERSEDED HISTORICAL CONTROL (empty path freeze) | YES |
| `controls/11_Legislative_Decision_Interface.txt` | `files/from-dirty-worktree/controls/11_Legislative_Decision_Interface.txt` | 0 | `e3b0c44298fc1c149afbf4c8996fb92427ae41e4649b934ca495991b7852b855` | untracked | no | empty-content duplicate | SUPERSEDED HISTORICAL CONTROL (empty path freeze) | YES |
| `controls/12_Public_Transparency_API_and_Digital_Republic.txt` | `files/from-dirty-worktree/controls/12_Public_Transparency_API_and_Digital_Republic.txt` | 0 | `e3b0c44298fc1c149afbf4c8996fb92427ae41e4649b934ca495991b7852b855` | untracked | no | empty-content duplicate of CONTROL 12 placeholder | SUPERSEDED HISTORICAL CONTROL — **NOT** canonical CONTROL 12 | YES |
| `controls/NBBF_Design_Philosophy.txt` | `files/from-dirty-worktree/controls/NBBF_Design_Philosophy.txt` | 10125 | `f3e36ce843d9b1e32f1d33598a9d52acc85d839e51819027d50fec58235f2d81` | untracked | no | no | UNIQUE HISTORICAL EVIDENCE; SUPPORTING DESIGN MATERIAL | YES |
| `controls/NBBF_Master_Blueprint.txt` | `files/from-dirty-worktree/controls/NBBF_Master_Blueprint.txt` | 38929 | `8e82809e392f43e0f33cec6d3d56dd744087fe06c2ffa71fe6d73c4921b2b665` | untracked | no | no | UNIQUE HISTORICAL EVIDENCE; SUPPORTING DESIGN MATERIAL | YES |
| `controls/pdfs/NBBF_Design_Philosophy_v2_Draft.pdf` | `files/from-dirty-worktree/controls/pdfs/NBBF_Design_Philosophy_v2_Draft.pdf` | 23960 | `45f40754f4064a1ef037d80a042a3c2ca37cfcedc78420986035374a0dfec930` | untracked | no | no | UNIQUE HISTORICAL EVIDENCE; SUPPORTING DESIGN MATERIAL (PDF preserved byte-for-byte, not converted) | YES |
| `.cursor/rules/NBBF_Specification.md` | `files/from-dirty-worktree/dot-cursor/rules/NBBF_Specification.md` | 1230 | `93405e3ac7eb4965a893030b01c4bc73313bc105cb2999bad760ff61b0858359` | untracked | no | no | UNIQUE HISTORICAL EVIDENCE; SUPPORTING DESIGN MATERIAL (path remapped so it is not live Cursor rules) | YES |

`controls/00C_Property_Rights_and_Pooling_Control.txt` was **not** present in the dirty worktree (`MD`: staged modify, worktree delete). See index and HEAD sections.

---

## B. Extracted read-only from restore index (staged)

| Original restore path | Evidence destination | Size | SHA-256 | Git blob | On origin/main | In prior reconciliation-evidence | Classification | NONCANONICAL |
|---|---|---|---|---|---|---|---|---|
| `controls/00_Control.txt` (index) | `files/from-restore-index/controls/00_Control.txt` | 4620 | `9420fabe29c64b7f2160c41d69022646b3ad495708f795b9bf5caae4ab1846e0` | `6eb5fa968a7f8b7a8ee4bdc0031953e12f3b2d1a` | no | no matching SHA-256 | UNIQUE HISTORICAL EVIDENCE; SUPERSEDED HISTORICAL CONTROL | YES |
| `controls/00C_Property_Rights_and_Pooling_Control.txt` (index) | `files/from-restore-index/controls/00C_Property_Rights_and_Pooling_Control.txt` | 3684 | `d54572d60aa02be134c8bca7b2e5ae255e74a8e7b24f287767b775ce824ba6f2` | `869948e98ecbfa1b0d07e2ab9fe7fd1bb4e30d3a` | no | no matching SHA-256 | UNIQUE HISTORICAL EVIDENCE; SUPERSEDED HISTORICAL CONTROL | YES |

These index versions are distinct from both restore HEAD and the dirty worktree `00_Control.txt`.

---

## C. Extracted read-only from restore HEAD `8829c82`

Deleted in the dirty worktree; **not** restored into that worktree.

| Original restore path | Evidence destination | Size | SHA-256 | Git blob | On origin/main | In prior reconciliation-evidence | Classification | NONCANONICAL |
|---|---|---|---|---|---|---|---|---|
| `controls/00_Control.txt` | `files/from-restore-HEAD/controls/00_Control.txt` | 4882 | `633ca85101e7fc4cfdee77c0cc4daac894f423ae8a262aab52866cd6d24a8931` | `632de592201958b5cd31a9160edb0a481ef2e0a5` | no | yes — byte-identical to `NOT_CANONICAL_Signal_v1.0_from_HEAD_00.txt` | DUPLICATE HISTORICAL EVIDENCE; SUPERSEDED HISTORICAL CONTROL | YES |
| `controls/00C_Property_Rights_and_Pooling_Control.txt` | `files/from-restore-HEAD/controls/00C_Property_Rights_and_Pooling_Control.txt` | 3888 | `a3b8f5f6bc9401f9286a6be4c22e41b9bc0fb2deb27f9e4b989d8eb1cbf6c860` | `32242d877200c2376472f7982b6a20da5822ed18` | no | same git blob recorded in `SOURCE_MAP.txt` as 00C v1.0; SHA-256 **differs** from `NOT_CANONICAL_CONTROL_00C_v1.0_pre-CWC-12.txt` (4041 bytes) | UNIQUE HISTORICAL EVIDENCE as git-native bytes; SUPERSEDED HISTORICAL CONTROL | YES |
| `controls/00D_Exit_and_Disengagement_Control.txt` | `files/from-restore-HEAD/controls/00D_Exit_and_Disengagement_Control.txt` | 4006 | `71ef75f99d63eb5608c8fdf4fd3cbb61b08b831c4196175a6268792e73ed6df3` | `b6539cb297dfca44323bb078397adc9221292b56` | no | same git blob recorded in `SOURCE_MAP.txt` as 00D v1.0; SHA-256 **differs** from `NOT_CANONICAL_CONTROL_00D_v1.0_pre-CWC-12.txt` (4158 bytes) | UNIQUE HISTORICAL EVIDENCE as git-native bytes; SUPERSEDED HISTORICAL CONTROL | YES |
| `controls/03_Constitutional_Authority_Model.txt` | `files/from-restore-HEAD/controls/03_Constitutional_Authority_Model.txt` | 0 | `e3b0c44298fc1c149afbf4c8996fb92427ae41e4649b934ca495991b7852b855` | `e69de29bb2d1d6434b8b29ae775ad8c2e48c5391` | no | empty-content duplicate | SUPERSEDED HISTORICAL CONTROL (empty reserved slot) | YES |
| `controls/05_Four_Month_Budget_Cycle.txt` | `files/from-restore-HEAD/controls/05_Four_Month_Budget_Cycle.txt` | 0 | `e3b0c44298fc1c149afbf4c8996fb92427ae41e4649b934ca495991b7852b855` | `e69de29bb2d1d6434b8b29ae775ad8c2e48c5391` | no | empty-content duplicate | SUPERSEDED HISTORICAL CONTROL (empty reserved slot) | YES |
| `controls/07_Audit_and_Performance_Standards.txt` | `files/from-restore-HEAD/controls/07_Audit_and_Performance_Standards.txt` | 5852 | `05eeaccbbe7f1b7f5d4e44bdc3f1d6b755d57daf25af2618ef4cb3f544193bbb` | `d379a1e0aa13e53d408b68e214217dc32aa3f331` | no | same git blob recorded in `SOURCE_MAP.txt`; SHA-256 **differs** from `NOT_CANONICAL_CONTROL_07_v1.0_pre-CWC-13.txt` (6105 bytes) | UNIQUE HISTORICAL EVIDENCE as git-native bytes; SUPERSEDED HISTORICAL CONTROL | YES |
| `controls/08_Exit_and_Clawback_Rules.txt` | `files/from-restore-HEAD/controls/08_Exit_and_Clawback_Rules.txt` | 0 | `e3b0c44298fc1c149afbf4c8996fb92427ae41e4649b934ca495991b7852b855` | `e69de29bb2d1d6434b8b29ae775ad8c2e48c5391` | no | empty-content duplicate | SUPERSEDED HISTORICAL CONTROL (empty reserved slot) | YES |
| `controls/09_Legacy_and_Sealed_Nodes.txt` | `files/from-restore-HEAD/controls/09_Legacy_and_Sealed_Nodes.txt` | 0 | `e3b0c44298fc1c149afbf4c8996fb92427ae41e4649b934ca495991b7852b855` | `e69de29bb2d1d6434b8b29ae775ad8c2e48c5391` | no | empty-content duplicate | SUPERSEDED HISTORICAL CONTROL (empty reserved slot) | YES |
| `controls/10_Senate_Interface_Rules.txt` | `files/from-restore-HEAD/controls/10_Senate_Interface_Rules.txt` | 0 | `e3b0c44298fc1c149afbf4c8996fb92427ae41e4649b934ca495991b7852b855` | `e69de29bb2d1d6434b8b29ae775ad8c2e48c5391` | no | empty-content duplicate | SUPERSEDED HISTORICAL CONTROL (empty reserved slot) | YES |
| `controls/11_Public_Transparency_and_Publishing.txt` | `files/from-restore-HEAD/controls/11_Public_Transparency_and_Publishing.txt` | 0 | `e3b0c44298fc1c149afbf4c8996fb92427ae41e4649b934ca495991b7852b855` | `e69de29bb2d1d6434b8b29ae775ad8c2e48c5391` | no | empty-content duplicate | SUPERSEDED HISTORICAL CONTROL (empty reserved slot) | YES |

HEAD 00C / 00D / 07 git-object IDs match CWC #3 `SOURCE_MAP.txt`. Their SHA-256 values differ from the previously checked-out evidence `.txt` files, consistent with a line-ending (LF vs CRLF) checkout difference. CWC #42 preserves the git-native blobs without normalizing line endings.

---

## D. Duplicates (content already frozen elsewhere)

- Dirty-worktree `00_Control.txt` = `reconciliation-evidence/NOT_CANONICAL_Root_v2.0.txt`
- Restore HEAD `00_Control.txt` = `reconciliation-evidence/NOT_CANONICAL_Signal_v1.0_from_HEAD_00.txt`
- Dirty-worktree `08_Audit_and_Performance_Standards.txt` = `reconciliation-evidence/NOT_CANONICAL_Signal_v2.1_from_restore_08.txt`
- Dirty-worktree `07_Signal_Integrity_and_Non-Interference.txt` = `reconciliation-evidence/NOT_CANONICAL_CONTROL_07_v1.0_pre-CWC-13.txt`
- All zero-byte files = empty placeholder content already in `NOT_CANONICAL_CONTROL_12_placeholder.txt`

They were still copied so the CWC #42 package is a complete freeze of the dirty restore state, not a content-deduplicated archive.

---

## E. UNIQUE material not previously in reconciliation-evidence (new byte identity)

1. `NBBF_Design_Philosophy.txt`
2. `NBBF_Master_Blueprint.txt`
3. `NBBF_Design_Philosophy_v2_Draft.pdf`
4. `.cursor/rules/NBBF_Specification.md` (stored under `dot-cursor/`)
5. restore **index** `00_Control.txt`
6. restore **index** `00C_Property_Rights_and_Pooling_Control.txt`
7. restore HEAD git-native bytes of `00C`, `00D`, and `07` (SHA-256 distinct from prior evidence checkouts)

---

## F. UNKNOWN — HUMAN REVIEW REQUIRED

1. Dirty-worktree `controls/07_Signal_Integrity_and_Non-Interference.txt`  
   Filename implies Signal; SHA-256 matches historical CONTROL 07 v1.0 audit text.
2. Dirty-worktree `controls/08_Audit_and_Performance_Standards.txt`  
   Filename implies Audit; SHA-256 matches prior evidence labeled Signal v2.1 from restore `08`.

Do not resolve these identity collisions in CWC #42. Do not promote either file.

---

## G. SHA-256 source/copy verification

Every preserved copy listed above was hashed after copy/extraction.  
Source SHA-256 = preserved-copy SHA-256 for all items.  
No mismatch. No silent repair.
