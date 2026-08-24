# NONCANONICAL HISTORICAL EVIDENCE

**NBBF-CWC #42 — restore-worktree unique-evidence freeze**

This directory is **NOT CONTROL AUTHORITY**.

It is a frozen copy of historical material that was at risk in the dirty
`restore-control-documents` worktree. It SHALL NOT be treated as live NBBF
CONTROL doctrine.

## Authority firewall

Canonical NBBF CONTROL authority remains solely:

- `origin/main` at CWC #42 start:
  `51a900a31cb33715218d6377aeaf36df651232c9`
- live Markdown CONTROLs `controls/00` through `controls/12`
- `controls/manifest.txt`

Nothing in this package:

- promotes historical drafts to canonical authority;
- replaces canonical CONTROL 12 (`12_Competitive_Node_Procurement.md`);
- creates CONTROL 13;
- creates NBEF;
- drafts deferred architecture.

## Historical CONTROL 12 warning

The preserved file:

`files/from-dirty-worktree/controls/12_Public_Transparency_API_and_Digital_Republic.txt`

is **HISTORICAL EVIDENCE**.

It is **NOT** current canonical CONTROL 12.

Current canonical CONTROL 12 is:

`controls/12_Competitive_Node_Procurement.md`

## Preservation method

COPY — DO NOT MOVE.

The dirty restore worktree was not modified, cleaned, reset, checked out,
restored, stashed, merged, or committed.

Sources:

- `files/from-dirty-worktree/` — byte-for-byte copies of files then present
  in the dirty restore working tree
- `files/from-restore-index/` — read-only extraction of staged index blobs
  (required because `00C` was deleted in the worktree after being staged)
- `files/from-restore-HEAD/` — read-only extraction of committed restore
  HEAD blobs for paths deleted in the dirty worktree

The untracked restore path `.cursor/rules/NBBF_Specification.md` is preserved
as `files/from-dirty-worktree/dot-cursor/rules/NBBF_Specification.md` so it
cannot be mistaken for live Cursor workspace rules.

## Restore source recorded at freeze

- Worktree: `X:\GitHub\NBBF-Control-Documents\NBBF-Control-Documents`
- Branch: `restore-control-documents`
- HEAD: `8829c82e48d1c5746b0614ee10c5eb2435cfe079`

See `INVENTORY.md` for hashes, classifications, and duplicate notes.
