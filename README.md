# David Dalconzo

**Applied AI Systems & Automation Engineer** building reliable agent systems,
laboratory software, and observable workflows that fail safely.

My work sits where AI meets real operations: persistent memory, retrieval and
tool use, laboratory automation, state machines, recovery paths, evaluations,
and evidence that an unfamiliar reviewer can inspect.

## Featured work

### [MiniLLM](https://github.com/Dalconzo/MiniLLM)

A local-first agent memory and tool runtime with provenance, abstention,
review-gated feedback, typed MCP boundaries, and isolated deployment controls;
the [v0.2.0a1 alpha](https://github.com/Dalconzo/MiniLLM/releases/tag/v0.2.0a1)
records 735 passing tests on each Linux matrix job, 302 passing
security-focused tests, 75.02% branch coverage, and 28/28 governed retrieval
gates, with platform-specific skips stated in the release notes.

### [HSLViewer](https://github.com/Dalconzo/HSLViewer)

A local desktop explorer for turning dense Hamilton trace logs into navigable
event blocks, timing evidence, and channel-level pipetting summaries; the public
release uses only a synthetic fixture and has focused parser regression tests.

### [PyLabRobot contributions](https://github.com/PyLabRobot/pylabrobot/pulls?q=is%3Apr+author%3ADalconzo)

Two merged, tested contributions to a hardware-agnostic laboratory automation
SDK: CoRe-gripper barcode reading and backward-compatible per-tip identity and
serialization.

## Human ownership in an AI-assisted workflow

I own problem framing, architecture, constraints, threat models, evaluations,
and acceptance decisions. AI accelerates implementation variants, test
generation, code review, and regression loops. Model output is a proposal—not
proof, deployment authority, or permission to mutate system truth.

## Selected open-source contributions

- [PyLabRobot PR #748 - CoRe gripper barcode read command](https://github.com/PyLabRobot/pylabrobot/pull/748): merged with firmware-response parsing, tests, and backward-compatible behavior.
- [PyLabRobot PR #759 - per-tip names and serialization](https://github.com/PyLabRobot/pylabrobot/pull/759): merged across tip models and Hamilton/Tecan constructors while preserving type equality.

## Current focus

- persistent, provenance-aware memory for long-running agents;
- evaluation-driven retrieval, abstention, and safe tool use;
- observable laboratory workflows with explicit state and recovery;
- secure separation between AI-assisted builders and production authority.

[LinkedIn](https://www.linkedin.com/in/david-dalconzo)
