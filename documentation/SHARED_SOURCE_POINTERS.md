# Shared Source Pointers

Generated: 2026-05-16 14:18:50 AEST

This paper uses the shared MNCPPC Travel/2 source context rather than carrying duplicate source trees inside the per-paper package.

## Canonical Shared Source

- Shared source ID: `mncppc-travel2-source`
- Shared source root: `../../../_shared_sources/mncppc-travel2-source`
- Shared folders:
  - `../../../_shared_sources/mncppc-travel2-source/mncppc_sourcecode_t2macros`
  - `../../../_shared_sources/mncppc-travel2-source/mncppc_macros_travel2`
  - `../../../_shared_sources/mncppc-travel2-source/mncppc_mtools_ttools_travel2`

## Deduplication Evidence

The previously staged per-paper folders were checked against the shared source before removal:

- `mncppc_macros_travel2`: 94 files; byte-identical to the shared folder by SHA-256 manifest comparison.
- `mncppc_mtools_ttools_travel2`: 15 files; byte-identical to the shared folder by SHA-256 manifest comparison.
- `mncppc_sourcecode_t2macros`: 173 base files matched the shared folder, plus 60 Finder-style duplicate files whose names contain ` 2.`; every such duplicate was SHA-256 identical to its base file.

The duplicate local source trees were removed from this package. Use the shared source once for Travel/2-family papers.
