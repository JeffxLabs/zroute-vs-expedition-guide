# Z Route: Weekly VS Guide

A practical, beginner-friendly alliance guide for weekly Alliance Competition / VS.

> **Version:** activity map transcribed from the Z Route client v1.30.07. Remote server configuration can change; verify the live event panel.

## Core rules

1. Hold completed work and rewards for the matching VS day when safe.
2. Check VS and Mission Readiness before claiming anything.
3. Score as an alliance: follow officer targets and stop spending when the target is secure.
4. Never spend scarce resources just to chase a leaderboard rank.

## Six-day VS rotation

| Day | Scoring activities | Hold beforehand |
|---|---|---|
| 1: Radar/gathering | Radar tasks, stamina, food/metal/energy gathering, hero EXP, drone data/parts | Radar completions, stamina, gathering returns, drone items, hero EXP |
| 2: Construction/rescue | Building speedups and power, Special Ops missions, truck activity | Building completions, construction speedups/items, Special Ops/truck claims |
| 3: Research | Research speedups and power, research-info items, radar | Research completions, speedups, research info, radar claims |
| 4: Heroes | Recruitment, hero EXP/fragments, skill books | Recruit tickets, EXP, fragments, skill books |
| 5: Mixed growth/training | Radar, construction/research progress, troop training and speedups | Queues, completions, training speedups, radar claims |
| 6: War/recovery | Kills, battle activity, rescue, construction/research/training/healing speedups | Healing queues/speedups, Special Ops/truck claims, combat reserves |

The client contains two six-day configurations with this activity pattern. Live labels/order and caps may differ.

## Mission Readiness double-dip

Mission Readiness is a separate mission/milestone system. Make one action satisfy both systems:

- Radar day: complete stored Radar missions when both objectives are active.
- Construction/research days: finish queues or use speedups only when the matching readiness objective is active.
- Hero day: open recruitment or use fragments/EXP/books when readiness requests the same action.
- Training/war day: align training, healing, rescue, and combat objectives without creating unnecessary casualties.

## Simple weekly routine

Use this routine every day. “Reset” means the daily VS reset shown by your event timer.

- **As soon as a day starts:** open VS and Mission Readiness. Write down the 2–3 matching actions for that day.
- **Gathering:** send all available marches soon after reset. Recall them **after the next reset**, claim the gathering result, and immediately send them again. Before the following reset, recall them so the next day’s points can be claimed after reset. Do not recall early unless you need the troops.
- **Queues:** start long construction, research, or training before reset when possible. Finish or claim them after reset only if the new day scores that action.
- **Missions:** leave completed Radar, Special Ops, truck, and Mission Readiness tasks unclaimed until the matching day.
- **Before sleeping:** start marches and queues that will be ready for the next scoring window.
- **Last hour:** do not panic-spend. Check the target, available points, and whether your action is actually listed.

## Mission Readiness schedule

The client exposes Mission Readiness as a rotating stage system with stage swapping and points chests. It does not provide a single permanent weekday calendar in the published data; the live event can rotate or refresh the tasks. Therefore use this reliable schedule by **task type**, not by an assumed Monday/Tuesday label:

| Mission Readiness task type | Prepare before the task appears | Complete/claim during the task | VS double-dip
|---|---|---|---|
| Gathering | Send marches after the prior reset | Recall and claim after the readiness task and VS gathering day are active | Yes, if both panels list gathering
| Radar / missions | Save completed missions and stamina | Claim/finish after both objectives are active | Yes, on Radar day
| Construction | Start an upgrade; save speedups | Finish/use speedups when both objectives match | Yes, on construction day
| Research | Start research; save research items | Finish/use items when both objectives match | Yes, on research day
| Heroes | Save tickets, EXP, fragments, books | Open/use only when the matching task is active | Yes, on Hero day
| Training/healing | Keep queues and reserves ready | Finish/use after reset; heal only real losses | Yes, on training/recovery day

### Timing procedure

1. Before reset, inspect all three event panels.
2. Leave missions/rewards complete but unclaimed where the UI permits.
3. After reset, confirm the exact source that awards points.
4. Claim/finish the action while both objectives are active.
5. Test an inexpensive action if credit timing is unclear; record the result.
6. Stop at the alliance target or efficiency limit.

Do not assume every reward claim scores twice: the client distinguishes radar, speedup, power, item-use, purchase, and other source IDs.

## Stockpile checklist

Radar completions; stamina; construction/research/training/healing speedups; building/research rewards; recruit tickets; hero EXP/fragments/books; drone data/parts; gathering marches and returns; Special Ops/truck rewards; training queues; and unclaimed Mission Readiness objectives.

Do not burn troops, healing, stamina, or premium currency solely for a VS ranking.

## Alliance procedure

### Before the cycle

- Publish the calendar, daily target, and stop-spend rule.
- Coordinate push members, trucks, rescues, and rallies.

### During each day

- Post reset time, stage, target, and what not to spend.
- Prioritize cheap, efficient actions before scarce items.
- Report caps, delayed credit, changed descriptions, or missing points.
- Fight only under officer orders; avoid unauthorized attacks and hospital overloads.

## Source map

The client tables expose `AllianceCompetitionStage` (days), `ActivityTarget` (daily point-source IDs), `PointSource` (actions, conditions, and point values), and `AllianceCompetitionReward` (score thresholds/rewards). Supporting configuration is in `AllianceCompetitionParameters` and `AllianceCompetitionPack`.

This guide is an interpretation of client v1.30.07, not a guarantee of live-server rules.
