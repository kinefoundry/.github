# Kinefoundry product demo v0.1

A working prototype of the data operations workflow: buyer brief → collection → quality review → delivery.

## Three-minute walkthrough

1. **Project overview:** Start with the precision assembly pilot. Explain that all 24 episodes and their diagnostics are illustrative. The product ties acceptance and coverage to the underlying episode records.
2. **Collection brief:** Show how a model requirement becomes a task, capture modality, site and acceptance criteria. Edit the target accepted hours and save.
3. **Collection:** Show the common protocol and four pseudonymous contributors. The sample represents human video, not robot actions or joint states.
4. **Quality review:** Inspect KF-0019. Add a note explaining the occlusion and request recapture. The queue and project metrics update. Inspect KF-0021 to show how a rights hold blocks acceptance. “Simulate rights clearance” is explicitly a demo operation.
5. **Delivery:** Show the accepted, cleared subset. Preview or download the JSON manifest. Rejected, pending and rights-held records are excluded. The manifest retains provenance, review decisions and permitted-use references.

Use **Start walkthrough** for an on-screen tour. Use **Reset demo** before each meeting.

## What works

Editable collection brief; browser-local persistence; searchable and filterable review queue; per-episode notes and decisions; rights-hold gate; live recalculation of totals and task coverage; JSON manifest preview and export; guided tour; reset control; responsive layouts.

## Prototype boundaries

All episodes, contributor identities, durations, quality scores and rights references are synthetic. No videos, hardware integrations, signed permissions, actual customers, shared team backend, or model evaluations are included. Changing the planned capture modality does not relabel the human-video sample. Acceptance is an internal demo decision, not proof of buyer acceptance or model improvement. Browser state is local to each viewer and is not a secure production data store.

## Next production milestone

Connect one real pilot: upload and play sample recordings, store episode metadata and verified permissions in a shared backend, introduce authenticated reviewer roles, and validate the export against a buyer's importer. Add sensor synchronization and robot-action schemas only for capture modalities that actually provide those data.

## Offline backup

Unzip Kinefoundry_Demo_Offline.zip and open index.html in a browser. All assets are bundled. Some browsers restrict persistence or file downloads when opening local files; the hosted demo is preferred.
