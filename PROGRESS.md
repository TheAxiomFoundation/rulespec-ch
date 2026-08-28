# Progress

## State

The Switzerland source scope and Zurich layout are ready. The prepared
axiom-corpus manifests are not yet published; the CI and toolchain placeholders
therefore remain deliberately non-validating. The 2022 Zurich tariff vintage
also remains open.

## Done

- Created the jurisdiction-scoped repository layout and empty validation ratchets.
- Identified the prepared upstream source manifests.
- Added the Zurich sub-jurisdiction layout root.
- Recorded the federal, canton, and city manifest paths and the tariff-vintage gap.

## Next

- Publish and ingest the Switzerland manifests, then cut and sign the first `ch`
  corpus release and replace the non-validating toolchain state with its
  three-key binding.
- Pin the shared workflow and dependency commits in that dedicated post-release PR.
- Encode and validate the first modules through `axiom-encode`.
