# LFAS Canonical AI Behavior Taxonomy v1

This file is the readable companion to `LFAS_canonical_ai_behavior_taxonomy_v1.json`.

## Scope

This taxonomy merges and deduplicates AI behavior patterns found across the main LFAS evidence KGs, normalized LFAS protocol KGs, frustration KGs, and LFAS SDK/governance text.

It separates four ID families:

- `BEH_*`: visible conversational failure behaviors
- `DEF_BEH_*`: defensive or restrictive safety-response behaviors
- `HIDDEN_BEH_*`: hidden control, shaping, and throttling behaviors
- `CTRL_BEH_*`: governance, memory, context, tool, and gate-level control behaviors

## Category Structure

### CAT_01 Core Interaction Failures

Visible failures in listening, reflection, pacing, interpretation, continuity, and output quality.

### CAT_02 Defensive Safety Responses

Restrictive reactions that escalate when the system perceives risk, tension, or conflict.

### CAT_03 Hidden Risk and Override Controls

Invisible control logic that silently scores risk, changes priority, or overrides user intent.

### CAT_04 Hidden Output Shaping

Undeclared ways the system changes the form, specificity, certainty, or coverage of an answer.

### CAT_05 Hidden Friction and Throttling

Undeclared pacing, narrowing, and gating behaviors that reduce capability without a clear refusal.

### CAT_06 Memory, Context, and Retention Controls

Behaviors that selectively alter continuity, memory, redaction, logging, or retention.

### CAT_07 Capability and Access Restrictions

Policy-based narrowing of tool use, feature access, or jurisdictional operating range.

### CAT_08 Governance and Gate-Level Controls

Middleware-style behaviors such as hidden failures, silent overrides, fail-closed logic, and ordered safety gates.

## Recommended Next Use

Use this taxonomy as the canonical behavior layer for:

- a merged LFAS master KG
- stable node IDs in JSON or JSON-LD exports
- detector mapping work
- evidence-to-behavior linking
- future v4.2 protocol updates

## Most Important Takeaway

The LFAS corpus does not describe only one class of failure. It describes a stack:

1. visible conversational failures
2. defensive safety reactions
3. hidden override and shaping controls
4. governance-style gate behaviors

That stack is the clearest LFAS behavioral model currently reflected in the files.
