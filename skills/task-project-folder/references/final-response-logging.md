# Session note: final response logging requirement

Context: During a task-project-folder skill tuning session, the user explicitly corrected the workflow: "amit most kiírtál végső válasz az is kerüljön bele mindig" — the assistant's final user-facing answer must also be captured in the project folder every time.

Reusable lesson:
- Treat the final assistant response as a first-class output artifact, not only as chat text.
- Save it in both human-readable and machine-readable forms:
  - `outputs/final_response.md`
  - `outputs/final_response.json`
- The saved content should match the text sent to the user as closely as possible.
- Add both files to `artifacts/manifest.json`.
- This is especially important because the final response often contains the canonical status, file paths, version numbers, and completion summary.

Pitfall found in-session:
- After adding `outputs/final_response.*` to the standard tree, avoid leaving a second duplicate `outputs/` entry later in the tree.
