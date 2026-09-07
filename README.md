# Z Route: Weekly VS Guide

A practical, beginner-friendly alliance guide for weekly Alliance Competition / VS.

> **Version:** activity map transcribed from the Z Route client v1.30.07. Remote server configuration can change; verify the live event panel.

## Core rules

1. Hold completed work and rewards for the matching VS day when safe.
2. Check the VS panel before claiming anything.
3. Score as an alliance: follow officer targets and stop spending when the target is secure.
4. Never spend scarce resources just to chase a leaderboard rank.

## Six-day VS rotation

| Day | Scoring activities | Hold beforehand |
|---|---|---|
| 1: Radar/gathering | Radar tasks, stamina, food/metal/energy gathering, hero EXP, drone data/parts | Radar completions, stamina, gathering returns, drone items, hero EXP |
| 2: Construction / Special Ops | Building speedups and power, Special Ops missions, truck activity | Building completions, construction speedups/items, Special Ops/truck claims |
| 3: Research | Research speedups and power, research-info items, radar | Research completions, speedups, research info, radar claims |
| 4: Heroes | Recruitment, hero EXP/fragments, skill books | Recruit tickets, EXP, fragments, skill books |
| 5: Mixed growth/training | Radar, construction/research progress, troop training and speedups | Queues, completions, training speedups, radar claims |
| 6: War/recovery | Kills, battle activity, Special Ops, construction/research/training/healing speedups | Healing queues/speedups, Special Ops/truck claims, combat reserves |

The client contains two six-day configurations with this activity pattern. Live labels/order and caps may differ.

## Stockpile checklist

Radar completions; stamina; construction/research/training/healing speedups; building/research rewards; recruit tickets; hero EXP/fragments/books; drone data/parts; gathering marches and returns; Special Ops/truck rewards; and training queues.

Do not burn troops, healing, stamina, or premium currency solely for a VS ranking.

## Alliance procedure

### Before the cycle

- Publish the calendar, daily target, and stop-spend rule.
- Coordinate push members, trucks, Special Ops, and rallies.

### During each day

- Post reset time, stage, target, and what not to spend.
- Prioritize cheap, efficient actions before scarce items.
- Report caps, delayed credit, changed descriptions, or missing points.
- Fight only under officer orders; avoid unauthorized attacks and hospital overloads.

## Source map

The client tables expose `AllianceCompetitionStage` (days), `ActivityTarget` (daily point-source IDs), `PointSource` (actions, conditions, and point values), and `AllianceCompetitionReward` (score thresholds/rewards). Supporting configuration is in `AllianceCompetitionParameters` and `AllianceCompetitionPack`.

This guide is an interpretation of client v1.30.07, not a guarantee of live-server rules.
