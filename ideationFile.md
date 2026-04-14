THIS FILE CONSISTS OF THE ENTIRE ARCHITECTURE: DETAILED Workflow of the Project we're Building.

GITHUB RULES:

1. We merge all branches into dev while working.
2. After We have both reviewed and tested in dev, we shall move it to stg for final checks and verification.
3. Finally once everything is done we raise PR from stg to main and only then merge.

STG is the only branch that gets merged to main
dev only gets merged into stg

any other branch can get merged into dev only..

REASON: to prevent cherry picking and debugging faulty commits or prevent rebasing issues.

[PLEASE DISABLE DIRECT MASTER PUSHES]
