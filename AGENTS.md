# Research package maintenance

- Read the paper-specific README and source project's instructions before importing code. Confirm the exact manuscript version and the code, inputs, settings, and outputs that correspond to it.
- Preserve source projects. Make changes here or in an isolated audit workspace; never overwrite original inputs, scripts, or historical outputs.
- Keep each paper self-contained. Add dependencies, commands, and shared modules only when supported by the actual implementation. Do not invent results, metadata, authorship, or validation claims.
- Separate structural changes, computational repairs, and scientific specification changes. Establish an unreviewed baseline before refactoring; keep provenance in private local records if it contains private paths or correspondence.
- Use independent small examples and affected result comparisons. Distinguish reproducing an old result from validating the computation. A corrected result need not match an erroneous baseline.
- Write new executions to a unique run directory. Record commit and dirty state, input/config hashes, environment, command, seeds where relevant, and completion status.
- Inspect the staged file list and content before committing or publishing. Exclude credentials, restricted data, personal information, private correspondence, and unrelated source-project files. Inspect notebook outputs and any imported Git history as well.
- Use only reviewed, redistributable examples and reference outputs. Do not add a license until ownership and third-party terms are established.
- Use separate worktrees and output directories for concurrent writers. One integrator owns shared root changes.
- Report actual checks, result changes, and remaining uncertainty. Stop a blocked route after the same cause fails twice or its alternative also fails.
