# Bootstrap working agreement
Status: Accepted
Scope: Phase 0 repository foundations.
Decision: AI supplies small code increments; Sangam executes and reviews as needed.
S — Spoofing: configure commit signing before the first shipped commit.
T — Tampering: review configuration changes and commit the lockfile.
R — Repudiation: record changes through commits and pull requests.
I — Information disclosure: keep credentials out of tracked files and output.
D/E — Denial of service / elevation: review dependencies; avoid sudo for project commands.
Limit: CI and repository protections are pending, not already enforced.
