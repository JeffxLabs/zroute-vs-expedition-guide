# Z Route: Weekly VS & Expedition Frenzy Guide

A practical alliance guide for weekly Alliance Competition / VS and server-vs-server Expedition Frenzy.

> **Version:** activity map transcribed from the Z Route client v1.30.07. Remote server configuration can change; verify the live event panel.

## Core rules

1. Hold completed work and rewards for the matching VS day when safe.
2. Check VS, Mission Readiness, and Expedition Frenzy before claiming anything.
3. Score as an alliance: follow officer targets and stop spending when the target is secure.
4. Never sacrifice war readiness for marginal points.

## Six-day VS rotation

| Day | Scoring activities | Hold beforehand |
|---|---|---|
| 1: Radar/gathering | Radar tasks, stamina, food/metal/energy gathering, hero EXP, drone data/parts | Radar completions, stamina, gathering returns, drone items, hero EXP |
| 2: Construction/rescue | Building speedups and power, rescue missions, truck activity | Building completions, construction speedups/items, rescue/truck claims |
| 3: Research | Research speedups and power, research-info items, radar | Research completions, speedups, research info, radar claims |
| 4: Heroes | Recruitment, hero EXP/fragments, skill books | Recruit tickets, EXP, fragments, skill books |
| 5: Mixed growth/training | Radar, construction/research progress, troop training and speedups | Queues, completions, training speedups, radar claims |
| 6: War/recovery | Kills, battle activity, rescue, construction/research/training/healing speedups | Healing queues/speedups, rescue/truck claims, combat reserves |

The client contains two six-day configurations with this activity pattern. Live labels/order and caps may differ.

## Mission Readiness double-dip

Mission Readiness is a separate mission/milestone system. Make one action satisfy both systems:

- Radar day: complete stored Radar missions when both objectives are active.
- Construction/research days: finish queues or use speedups only when the matching readiness objective is active.
- Hero day: open recruitment or use fragments/EXP/books when readiness requests the same action.
- Training/war day: align training, healing, rescue, and combat objectives without creating unnecessary casualties.

### Timing procedure

1. Before reset, inspect all three event panels.
2. Leave missions/rewards complete but unclaimed where the UI permits.
3. After reset, confirm the exact source that awards points.
4. Claim/finish the action while both objectives are active.
5. Test an inexpensive action if credit timing is unclear; record the result.
6. Stop at the alliance target or efficiency limit.

Do not assume every reward claim scores twice: the client distinguishes radar, speedup, power, item-use, purchase, and other source IDs.

## Stockpile checklist

Radar completions; stamina; construction/research/training/healing speedups; building/research rewards; recruit tickets; hero EXP/fragments/books; drone data/parts; gathering marches and returns; rescue/truck rewards; training queues; and unclaimed Mission Readiness objectives.

Keep a reserve for Expedition Frenzy. Do not burn troops, healing, stamina, or premium currency solely for a VS ranking.

## Alliance procedure

### Before the cycle

- Publish the calendar, daily target, and stop-spend rule.
- Coordinate push members, war leads, trucks, rescues, rallies, and combat windows.
- Keep enough reserves for Expedition Frenzy.

### During each day

- Post reset time, stage, target, and what not to spend.
- Prioritize cheap, efficient actions before scarce items.
- Report caps, delayed credit, changed descriptions, or missing points.
- Fight only under officer orders; avoid unauthorized attacks and hospital overloads.

## Expedition Frenzy conduct

Treat server-war objectives as higher priority than ordinary VS points. Preserve marches, troops, healing, teleport items, stamina, and speedups for the announced war window. Coordinate rallies and defense, follow target lists, and do not create casualties to manufacture points.

## Source map

The client tables expose `AllianceCompetitionStage` (days), `ActivityTarget` (daily point-source IDs), `PointSource` (actions, conditions, and point values), and `AllianceCompetitionReward` (score thresholds/rewards). Supporting configuration is in `AllianceCompetitionParameters` and `AllianceCompetitionPack`.

This guide is an interpretation of client v1.30.07, not a guarantee of live-server rules.
