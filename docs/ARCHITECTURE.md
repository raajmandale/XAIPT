# XAIPT Architecture

## Root Model

```text
REQUEST
   ↓
RISK
   ↓
HOLD
   ↓
REVIEW
   ↓
APPROVE / DENY
   ↓
EXECUTION
```

## Architecture Layers

| Layer | Role |
|---|---|
| Request Surface | Captures high-risk digital action intent. |
| Risk Context | Evaluates urgency, anomaly, trust drift, and execution sensitivity. |
| HOLD State | Pauses execution before irreversible consequence. |
| Authority Review | Requires trusted human/device authority before finality. |
| Decision Gate | Routes action toward approve or deny branch. |
| Audit Visibility | Records state transitions for review and accountability. |

## Ecosystem Map

```text
XAIPT
├── XAIPT-GUARD
├── Decision Gate
├── Runtime Authority Flow
└── Governance Experiments
```

## Public Architecture Boundary

The public architecture is intentionally conceptual and demonstrative. It shows the governance surface, not the private enforcement layer.
