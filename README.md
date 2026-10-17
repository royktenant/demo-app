# Demo Application (Organisation B: `royktenant`)

This repository represents the consumer application in **Organisation B (`royktenant`)**.

## Cross-Organisation Workflow Invocation
This project invokes the central reusable workflow maintained by **Organisation A (`royknef`)**:
- Central Workflow: `royknef/central-workflows/.github/workflows/arc-runtime.yml@v1`
- Execution: Self-hosted runner scale set `arc-poc-runners` hosted in local Kubernetes cluster `arc-poc-cluster` (registered to `royktenant/demo-app`).
