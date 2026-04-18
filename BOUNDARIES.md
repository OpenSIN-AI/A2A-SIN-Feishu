# A2A-SIN-Feishu Boundaries

## Role
`A2A-SIN-Feishu` owns Feishu messaging integration, enterprise chat workflows, and Feishu-specific contracts.

## This repo should own
- Feishu messaging routing, coordination, and automation flows
- Feishu evidence, recovery, auth, and session-health handling
- Feishu contracts used by downstream automation agents
- runbooks tied to enterprise chat communication and automation

## This repo must not own
- unrelated messaging or platform integration logic
- organization SSOT docs or architecture canon
- downstream business logic unrelated to Feishu ownership

## Hard rules
- Keep changes scoped to Feishu messaging integration and automation.
- Move non-Feishu behavior back to the repos that own it.
- Keep reusable contracts focused on workspace chat coordination and messaging.
