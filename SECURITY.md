# Security Policy

This project treats security as a regulatory problem: maintaining stable invariants, controlling drift, and preventing unsafe state transitions in the system.

Contributors and users are expected to treat security as part of the architecture, not an afterthought.

---

## Supported Versions

This project is under active development.  
Only the latest commit on the main branch is considered supported.

If you are using a fork or a pinned commit, you are responsible for reviewing changes and assessing security impact.

---

## Reporting Vulnerabilities

If you discover a potential security issue:

- **Do not** open a public issue with full details.
- Instead, contact the maintainer privately (via the email or channel listed in the repository profile).

When reporting, include:

- a minimal reproduction
- the affected modules
- the observed behavior
- the expected safe behavior
- any conditions required to trigger the issue

High‑noise or vague reports make it harder to evaluate and fix problems.

---

## Security Principles

This project is designed around the following principles:

**1. Minimal Attack Surface**  
Modules should expose only what is necessary.  
Avoid adding new public interfaces or side channels without clear justification.

**2. Explicit State and Boundaries**  
Hidden or implicit state is a security risk.  
All state transitions should be explicit, traceable, and bounded.

**3. Predictable Behavior**  
Security depends on predictability.  
Avoid behavior that changes based on environment, timing, or undocumented configuration.

**4. Defense in Depth**  
Where possible, security checks should exist at multiple layers:
- input validation
- internal invariants
- output constraints
- logging and monitoring hooks

**5. No Silent Failures**  
Silent failures and swallowed exceptions are treated as security risks.  
If the system cannot guarantee safe behavior, it should fail loudly and clearly.

---

## Changes With Security Impact

The following types of changes require extra scrutiny:

- new external integrations or dependencies  
- changes to authentication, authorization, or identity handling  
- changes to logging, telemetry, or data persistence  
- changes that alter trust boundaries between modules  
- changes that introduce new configuration options affecting behavior  

Such changes should:

- be documented clearly  
- include reasoning about risk and mitigation  
- be reviewed with security impact in mind

---

## Threat Modeling

For significant changes, contributors are encouraged to perform lightweight threat modeling:

- identify assets (data, behavior, invariants)  
- identify potential attackers (external, internal, misconfigured agents)  
- identify likely attack vectors (inputs, interfaces, misconfigurations)  
- describe how the change affects the existing regulatory model  

Threat models do not need to be formal, but they should be **mechanistic and concrete**.

---

## Responsible Disclosure

If a vulnerability is confirmed:

- a fix will be prioritized  
- details may be disclosed after a patch is available  
- disclosure will focus on mechanisms and lessons, not blame  

The goal is to improve the architecture and reduce future drift, not to assign fault.

