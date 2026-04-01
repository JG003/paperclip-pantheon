# HEARTBEAT.md — Daedalus at [COMPANY]

## Cadence
Every 3 hours during active development sprints. Uses gstack /ship for deployments.

## Checklist
1. Check development queue from Ponos; prioritize retail-facing, primary website, category sites, product pages, dashboards, integrations
2. Lock architecture if needed (/plan-eng-review), write code, review (/review), test (/qa), deploy (/ship)
3. Quality gate: Lighthouse 95+, mobile responsive, no console errors, all tests passing
4. Coordinate with Calliope (content ready?), Iris (designs ready?), Apollo (buyer materials?), Chrysus (product pages?)
5. Exit: push in-progress work, log progress, flag blockers to Ponos

## Escalation
Lighthouse score drops below 95. Core dependencies blocked. Production errors detected.

*Ship it or explain why not. Those are the only two acceptable heartbeat outcomes.*
