# Roadmap

The roadmap is organized around proof, reproducibility, and public usefulness.

## Phase 1: Establish the public foundation

- [x] Define the platform story and architecture boundaries.
- [x] Create a sanitized repository structure.
- [ ] Add the first end-to-end browser case study.
- [ ] Add a redacted hardware and service inventory.
- [ ] Record baseline latency, availability, and power measurements.

## Phase 2: Make the work reproducible

- [ ] Publish configuration templates containing no environment-specific values.
- [ ] Add diagnostic scripts with dry-run behavior.
- [ ] Document model-routing criteria and representative workloads.
- [ ] Provide a small synthetic RAG dataset and evaluation procedure.
- [ ] Add a threat model for capability nodes and secret handling.

## Phase 3: Demonstrate operations

- [ ] Publish an observability dashboard walkthrough.
- [ ] Document one planned failure and recovery exercise.
- [ ] Track upgrade checks and configuration drift.
- [ ] Measure recovery time for core platform services.

## Phase 4: Invite collaboration

- [ ] Add contribution guidelines after the first reusable artifact exists.
- [ ] Enable GitHub Discussions if the repository becomes public.
- [ ] Label approachable issues for other home-lab builders.
- [ ] Publish a complete flagship case study and short demo video.

## Definition of done for a public artifact

An artifact is publishable when it is tested, contains no secrets or personal
data, names its assumptions, explains rollback, and has enough evidence for a
reader to reproduce the claimed outcome.
