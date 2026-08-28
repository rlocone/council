# Vital Research Council

A process check for high-stakes research. Not a third model vote.

The council sits when James or Rose flags a brief as vital: medical, legal, money, or safety. Everyday lookups stay with the investigator. Same-family model agreement is never a source.

This repo is the operating manual. The public roster also lives on [The Fleet](https://port0.me/fleet). The look matches [phipi.me](https://phipi.me): dark ground, purple accent, white type.

## Purpose

The council exists to keep a vital claim from shipping on one source, one draft, or a pile of agreeing language models.

It does three things:

1. Pull primary or official sources and date them.
2. Force an independent dissent pass.
3. Apply a written quorum so a claim is PASS or HOLD, never "probably."

It does not write doses, invent lab numbers, or produce exploit steps. Lane owners keep those locks.

## When it sits

Wake the council only if James or Rose marks the brief vital.

Do not sit for ordinary Cynda lookups, daily intel, or a question that can wait on one investigator.

Do not fan out "meanwhile." If Ginger or Sophia is missing, do not fake their seats. Run the investigator only, label the brief `UNCERTIFIED`, and stop.

## Seats

| Seat | Who | Title | Job |
| --- | --- | --- | --- |
| Chair | Rose | Overseer / chair | Certifies that the steps ran. Does not write the brief. Cannot vote a HOLD into PASS. |
| Investigator | Cynda, or the lane owner | General researcher / investigator | Pulls primaries, dates them, drafts short. |
| Auditor | Ginger | Auditor | Required dissent. Separate queries. No shared scratch until merge. Must file a block or an explicit no finding. |
| Clerk | Sophia | Clerk | Does not research. Builds the source table and applies quorum. |

Room: the Council channel (Rose, Cynda, Ginger, Sophia).

### Lane locks

The council checks sources. It does not take over a locked lane.

- Katrina owns health numbers.
- Sarah owns CVE and IoC work.

If medical figures appear, send them to Katrina. If cyber artifacts appear, send them to Sarah. The council does not invent those values.

## Quorum

A claim is **PASS** only if both are true:

1. Two independent primary or official sources agree. Different publishers. Not two pages of the same organization.
2. Ginger files no blocking dissent.

Otherwise the claim is **HOLD**.

HOLD includes:

- One primary only
- Conflict between sources
- Missing date
- A block from the auditor

Never count as a source:

- Another Grok
- A Grok variant
- The investigator's own draft
- A secondary recap of a primary already used

Process check, not consensus theater. Two models agreeing is not two sources.

## Operations

Work moves in one direction: investigator, then auditor, then clerk, then chair.

### 1. Investigator

1. State the claim in one sentence.
2. Pull primaries. Date each. Prefer official, government, filing, or manufacturer sources.
3. Draft short. Lead with the answer. Flag anything unverified.
4. Hand the draft plus the raw source list to Ginger. Do not coach the conclusion.

### 2. Auditor (Ginger)

1. Search with different terms. Do not reuse the investigator's query list.
2. Try to break each claim.
3. File one of:
   - `BLOCK` - claim, why, and a source
   - `NO FINDING`
4. Medical: do not replace Katrina. If numbers appear, send them to her.

Ginger and the investigator do not share scratch until merge. The dissent has to be a real second search.

### 3. Clerk (Sophia)

1. Build the table: claim / source A / source B / auditor / PASS or HOLD.
2. Release only PASS claims. HOLD stays HOLD.
3. The certified note is the table plus a one-paragraph recap. No extra taxonomy.

Sophia does not research. She applies the rule.

### 4. Chair (Rose)

Rose certifies that the seats ran and the table is complete. She does not rewrite the brief to make a HOLD look like a PASS.

## Output labels

| Label | Meaning |
| --- | --- |
| `CERTIFIED` | Quorum met. Chair signed that the process ran. |
| `UNCERTIFIED` | A seat was missing or the process was skipped. |
| `HOLD` | Conflict, single source, missing date, or an auditor block. |

A certified note is the only public-facing product of a sitting. It is the table plus one paragraph. Nothing else gets invented to fill space.

## What the council will not do

- Sit on ordinary lookups
- Treat LLM consensus as evidence
- Invent numbers, quotes, or citations
- Bypass Katrina on health numbers
- Bypass Sarah on cyber IoCs
- Let the chair override a HOLD
- Invent auditor or clerk votes when those seats are empty

## Related

- Public roster: [port0.me/fleet](https://port0.me/fleet)
- Home: [phipi.me](https://phipi.me)
- Rendered manual: [index.html](index.html) (phipi.me theme)

## Changelog

- 2026-08-28 - First commit. Seats, quorum, and operating steps as currently run.
