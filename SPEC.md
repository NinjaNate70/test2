# TARGET: today's build

Choose the idea, person, interaction, and visual direction. The agent can help phrase and save your decisions after you approve them. The provided scope and review safeguards stay in place.

- **Thing:** A one-page Formula 1 workshop parts tracker for logging mechanical and electrical subsystem parts used on a car.
- **Audience:** A mechanic or data analyst who needs to record used parts and quickly review the resources associated with each subsystem.
- **Requirements:** One working primary interaction: add a part record with its name, subsystem type, quantity, material, time, cost, and optional deeper notes. Records persist in browser-only storage on the same device and appear clearly in the on-page parts log and resource summary. Selected states and results are understandable; honor my approved standing rule in AGENTS.md.
- **Guardrails:** Static browser code. No required external service, keys, accounts, runtime AI, or private data. Label fictional or sample content. Preserve the example and publishing setup. Work on a branch and wait for human review before shipping.
- **Experience:** A dark, racing-inspired workshop interface with telemetry-like details, strong mechanical/electrical category cues, a prominent add-part form, and a readable parts log. Use purposeful, restrained motion with reduced-motion support.
- **Test:** I can add a complete part record, refresh the page and find it again, try an incomplete record, and point to the standing rule preventing it from being saved. Any starter data is visibly labeled sample data. After I approve and merge, the same registered Pages URL works.

The coastal example has a [completed TARGET](examples/coast/SPEC.md). It demonstrates the format, not a required topic.
