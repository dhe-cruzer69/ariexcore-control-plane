# ariexcore-control-plane

**ARIEXCORE control plane** — policy engine, autonomy levels 0–3, fleet contract, evidence gates.

Intended home under org `ARIEXCORE-69X` (transfer when admin available).

## Trending topics
`ai-agents` · `policy-engine` · `autonomous-agents` · `multi-agent` · `local-first` · `mcp`

## Autonomy Levels
| Level | Name | Allowed |
|-------|------|---------|
| 0 | Observe | Read → report |
| 1 | Assist | Plan → open PR |
| 2 | Governed | Execute + autofix inside limits |
| 3 | Never | Deletes, secrets, force-push |

## Structure
```
policy/
  levels.yml
  hard_stops.yml
fleet/
  contract.schema.json
evidence/
  gate.md
```

## License
Apache-2.0
