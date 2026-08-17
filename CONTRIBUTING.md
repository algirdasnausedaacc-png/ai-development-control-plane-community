# Contributing

Thank you for helping improve the AI Development Control Plane program.

## Choose the right channel

- Discussion / Idea: early problem or concept.
- Work Proposal issue: concrete outcome that can be triaged.
- Bug Report issue: publicly observable defect with reproducible evidence.
- Research / Evidence issue: benchmark, scientific, standards, interoperability, or market/technical evidence.
- Q&A Discussion: support or questions.
- Security: private vulnerability reporting only.

## Before filing

1. Search existing Discussions and Issues.
2. Describe the problem before prescribing architecture.
3. Keep one primary problem/outcome per issue.
4. Explain affected users/use cases.
5. Include evidence and alternatives when available.
6. Identify known resource/cost implications.
7. Do not include confidential or sensitive information.

## Implementation pull requests

The canonical implementation repositories are currently private. Do not open implementation-code PRs in this community repository.

An issue existing does not mean implementation is invited. Only work explicitly marked `help wanted` or `good first issue` in a public and properly licensed repository is open for external implementation.

Community documentation/proposal PRs are enabled only after the Owner selects contribution licensing. Until then, use Issues and Discussions.

## Architecture

Contributions must respect:

**CENTRALIZED AUTHORITY AND TRUTH; DISTRIBUTED CAPABILITIES AND OBSERVATIONS.**

A proposal must not create a second global Authority, Policy Engine, Registry truth, unrestricted host/network/device mutation path, or silently absorb another provider project's responsibility.

## Economic operation

Prefer the smallest sufficient zero-cost solution. Avoid paid dependencies, unnecessary hosted inference, duplicate services, excessive polling, unnecessary always-on processes, and wasteful CPU/GPU/RAM/storage/network/token use.

Economic optimization must not weaken security, privacy, correctness, truthfulness, evidence, reliability, required capability, provider neutrality, or OS neutrality.

## Conduct

Follow `CODE_OF_CONDUCT.md`. Constructive disagreement is welcome; harassment, spam, threats, personal attacks, or disclosure of private data are not.

## Maintainer decisions

Maintainers may request information, redirect, mark duplicate, close out-of-scope proposals, or defer work. `accepted-for-design` means design evaluation only, not implementation acceptance or priority.
