# Progress

## State

The Switzerland source scope and Zurich layout are ready. The prepared
axiom-corpus manifests are not yet published; the CI and toolchain placeholders
therefore remain deliberately non-validating. The official 2022 Zurich tariff
source has been identified and manifested separately from the 2026 table.

## Done

- Created the jurisdiction-scoped repository layout and empty validation ratchets.
- Identified the prepared upstream source manifests.
- Added the Zurich sub-jurisdiction layout root.
- Recorded the federal, canton, and city manifest paths.
- Closed the 2022 tariff-vintage source gap with the official historical StG
  Nachtrag 115, § 47, without relabelling the distinct 2026 indexed table.

## Next

- Publish and ingest the Switzerland manifests, then cut and sign the first `ch`
  corpus release and replace the non-validating toolchain state with its
  three-key binding.
- Pin the shared workflow and dependency commits in that dedicated post-release PR.
- Encode and validate the first modules through `axiom-encode`.
