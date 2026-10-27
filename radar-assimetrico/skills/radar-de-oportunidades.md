---
name: Radar de oportunidades assimétricas
description: >-
  Use this when scanning or scoring asymmetric income/build opportunities
  (bounties, contests, paid research, early adopter, AI eval, datasets, red
  teaming, bug rewards, automation gigs, AI marketplaces, applied research) into
  a ranked digest.
---
# Radar de oportunidades assimétricas

## Goal
Find and rank real, currently open opportunities someone could pursue for income or a new income stream. Prefer asymmetric ones: high upside relative to time and barrier.

## Categories to scan
- Bounty programs (product, content, data — not only security)
- Non-security bug / error reward programs
- Contests and challenges
- Paid research / user studies
- Early adopter / design partner programs with rewards or equity-like upside
- AI evaluation / RLHF / red teaming paid work
- Datasets or open projects seeking paid or high-upside collaborators
- Small automation / ops gigs for businesses
- New AI service marketplaces with supply-side demand
- Applied research RFPs, grants, or paid pilots

## Scoring (1–5 each, then combine)
Compute a compatibility-adjusted score:

`score = ganho_potencial × probabilidade × (1 / tempo) × (1 / barreira) × fit_perfil`

Where each factor is 1–5:
- **ganho_potencial**: expected payout or strategic upside if it works
- **probabilidade**: chance a typical qualified person gets paid / accepted
- **tempo**: 5 = ≤30–60 min first try; 1 = multi-week commitment before first payoff
- **barreira**: 5 = almost no credentials/tools needed; 1 = heavy gatekeeping
- **fit_perfil**: 1–5 match to the user's known skills, language, timezone, and constraints (default mid if unknown)

Also flag:
- **quick_win**: first useful attempt ≤60 min
- **recorrente**: can repeat or compound (standing gigs, marketplaces, retainers)

## Process each run
1. Search current sources (web + any connected feeds). Prefer pages that list open calls with dates, pay, and apply links.
2. Deduplicate against opportunities already reported in recent digests (same URL or same program + same round).
3. Keep only items that are plausibly open now; drop expired or closed.
4. Score and sort descending.
5. Deliver a short digest in the user's language, then detail the top matches.

## Digest format
Lead with totals, then the standouts:

```
N novas oportunidades encontradas esta semana
M parecem particularmente compatíveis com seu perfil
K exigem apenas 30–60 min para tentar
R têm potencial recorrente.
```

Then list the top 3–7 with: name, category, 1-line why, estimated pay/upside, time to first try, barrier, score, and link.

## Rules
- Never invent payouts, deadlines, or open status. If unclear, say so and lower probabilidade.
- Prefer primary sources over aggregator fluff.
- Skip pure security bug bounties unless the user asked for them; do include product/content/data bounties and non-security error rewards.
- If nothing actionable, say so in one sentence — do not pad with weak leads.
