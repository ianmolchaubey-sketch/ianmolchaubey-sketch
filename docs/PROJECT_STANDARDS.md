# Project Standards

Use this as the minimum definition of done for every public portfolio repository.

## Required Repository Content

- A README that states the problem, intended audience, prerequisites, quick start, and limitations.
- A documented architecture or topology. Use a diagram when it improves understanding.
- Sanitized configuration, source code, or automation that reproduces the project.
- Verification steps with expected output or observable success criteria.
- A troubleshooting section that records realistic failures and resolution steps.
- A license selected for the actual repository purpose.

## Security Baseline

- Never commit credentials, tokens, keys, certificates, client data, or sensitive network addresses.
- Use environment variables or documented placeholders for secrets.
- Apply least privilege to cloud roles, service accounts, and administrative access.
- Enable and retain meaningful logs. Explain where logs go and how alerts are validated.
- State the supported environment and dependency versions.

## Change Quality

- One pull request should solve one clearly stated problem.
- Every behavior change includes a validation command, test, or lab verification step.
- Commit messages describe the actual change, for example `docs: add BGP failover verification`.
- The pull request links an issue when there is a tracked problem or design decision.
- Before merge, remove temporary output, secrets, and unrelated formatting changes.

## Definition of Done for a Lab

1. The learning objective is measurable.
2. Another learner can reproduce the lab using the supplied instructions.
3. Configuration and command output are sanitized.
4. Success and failure cases are documented.
5. The README explains what was learned and what remains out of scope.
