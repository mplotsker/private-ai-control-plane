# Demonstration Plan

Every demo should be understandable in under three minutes and supported by a
longer technical note.

## Demo 1: Cross-machine browser control

**Claim:** The remote control plane can operate an isolated Windows browser and
reach a development service bound to Windows localhost.

Evidence checklist:

- Show the dedicated browser node connected under its own identity.
- Start the isolated browser profile.
- Open a temporary page served only on Windows localhost.
- Read a unique marker from the page through the remote control plane.
- Remove the temporary server and file.
- Explain why browser routing is separate from the desktop companion.

Do not show tokens, private addresses, browser history, or personal tabs.

## Demo 2: Private, source-backed recall

**Claim:** The platform can answer a useful project question from local documents
and point to the material supporting its answer.

Evidence checklist:

- Use a synthetic or intentionally public document set.
- Show ingestion and collection selection.
- Ask one question requiring information from multiple documents.
- Display citations and one deliberately unsupported question.
- Explain how durable memory differs from broad retrieval.

## Demo 3: Safe home action

**Claim:** The platform can inspect household state and perform one narrow,
authorized action.

Evidence checklist:

- Use a non-sensitive device or synthetic Home Assistant entity.
- Read current state first.
- Request explicit authorization for the change.
- Target one entity, perform the action, and verify the resulting state.
- Explain which device classes are intentionally unavailable.

## Recording pattern

Use the same structure for each demo:

1. The real problem
2. The architecture slice involved
3. The live result
4. One failure encountered while building it
5. What remains imperfect
