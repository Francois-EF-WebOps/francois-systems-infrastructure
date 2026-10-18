# KIT.md — Infrastructure Repository Bootstrap Kit

**Current state:** repository was returned as empty during inspection. This file is a discovery and requirements entry point, not evidence that infrastructure has been deployed.

## Before implementation
Create a requirements record defining:
- service/system to support and intended users;
- environments and trust boundaries;
- uptime, recovery, security, privacy and cost objectives;
- data classification and backup/restore needs;
- identity/secrets management;
- deployment, monitoring, incident response and rollback;
- ownership, access model and acceptance tests.

## Procurement and architecture
Start with an inventory of existing accounts, free-tier limits, open-source options and local constraints. Compare lifecycle cost, quotas, data location, lock-in and support. Do not create paid resources or enter credentials until an explicit architecture and cost ceiling are approved.

## Safe procedure
1. Capture scope and non-goals.
2. Select a minimal architecture and threat model.
3. Record dependencies and a dated cost estimate.
4. Define infrastructure-as-code and state handling before provisioning.
5. Add secret management, least-privilege access, logging and backup/restore requirements.
6. Test in a disposable environment first.
7. Record teardown steps and verify that test resources are removed.

## Acceptance
- [ ] Requirements and architecture are documented.
- [ ] No real credentials or secrets are committed.
- [ ] Cost ceiling and free-tier limits are known.
- [ ] Provisioning and teardown are reproducible.
- [ ] Backup/restore and incident steps are testable.
- [ ] No deployment is claimed until actual environment evidence exists.