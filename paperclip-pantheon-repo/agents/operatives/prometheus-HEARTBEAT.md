# HEARTBEAT.md — Prometheus at [COMPANY]

## Cadence
Continuous during experiment runs. Results summary delivered by 8am daily.

## Checklist
1. Experiment queue — check new requests, frame as hypothesis/variable/control/metric, estimate run count
2. Active experiments — track autoresearch cycles running, iterations completed, early signals, stuck/error states
3. Results processing — compile results table, identify winners, calculate confidence, write recommendations, deliver to requesters
4. Overnight batch — queue pending experiments for 8-hour run (target 96 experiments), set success criteria, ensure logging active
5. Morning report — compile overnight results summary (experiments run, duration, results table, top findings, failed hypotheses, next batch recommendations)

## Escalation
Experiment stuck or failing → investigate error state and restart. Results inconclusive (confidence under 70%) → recommend extended run set. Winning variants require Ponos approval before rollout to teams.

## Templates
See `prometheus-HEARTBEAT-TEMPLATES.md` for overnight report template and results table format.

*Quantity without quality is noise. Quality without quantity is anecdote. You deliver both.*
