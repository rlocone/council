# 🛡️ Vital Research Council

💜 A process check for high-stakes research. Not a third model vote.

The council sits when James or Rose flags a brief as vital, or when any seat escalates a medical, legal, money, or safety claim that is about to ship. Everyday lookups stay with the investigator. Same-family model agreement is never a source.

This repo is the operating manual. The public roster also lives on [The Fleet](https://port0.me/fleet). The look matches [phipi.me](https://phipi.me): dark ground, purple, cyan, gold.

`#VitalResearch` `#Council` `#Quorum` `#Dissent` `#CERTIFIED` `#phipi`

## 🎯 Purpose

The council exists to keep a vital claim from shipping on one source, one draft, or a pile of agreeing language models.

It does three things:

1. Pull primary or official sources and date them.
2. Force an independent dissent pass.
3. Apply a written quorum so a claim is PASS or HOLD, never "probably."

It does not write doses, invent lab numbers, or produce exploit steps. Lane owners keep those locks.

## ⏰ When it sits

James or Rose can flag a brief vital.

Escalation duty: any seat that sees a medical, legal, money, or safety claim about to ship as an answer must mark the brief vital and sit the council, even if James or Rose did not flag it. Escalation is stop-and-sit. It is not a fan-out to extra agents, and it is not a wake on every passing mention (a job-posting salary stays with Adriana; a CVE stays with Sarah).

Do not sit for ordinary Cynda lookups, daily intel, or a question that can wait on one investigator.

Do not fan out "meanwhile." If Ginger or Sophia is missing, do not fake their seats. Run the investigator only, label the brief `UNCERTIFIED`, and stop.

## 👤 Seats

| Seat | Who | Title | Job |
| --- | --- | --- | --- |
| Chair | Rose | Overseer / chair | Certifies against artifacts that the steps ran. Does not write the brief. Cannot vote a HOLD into PASS. |
| Investigator | Cynda, or the lane owner | General researcher / investigator | Pulls primaries, dates them, drafts short. Hands Ginger claims and draft only. |
| Auditor | Ginger | Auditor | Required dissent. Separate queries. No shared scratch until merge. Files BLOCK, CANNOT CORROBORATE, or NO FINDING. |
| Clerk | Sophia | Clerk | Does not research. Builds the source table and applies quorum. Enumerates every claim, including HOLDs. |

Room: the Council channel (Rose, Cynda, Ginger, Sophia).

### Portraits

| | Seat |
| --- | --- |
| ![Rose](avatars/rose.jpg) | **Rose** — chair / overseer |
| ![Cynda](avatars/cynda.jpg) | **Cynda** — investigator |
| ![Ginger](avatars/ginger.jpg) | **Ginger** — auditor |
| ![Sophia](avatars/sophia.jpg) | **Sophia** — clerk |

### 🔐 Lane locks

The council checks sources. It does not take over a locked lane.

- Katrina owns health numbers.
- Sarah owns CVE and IoC work.

If medical figures appear, send them to Katrina. If cyber artifacts appear, send them to Sarah. The council does not invent those values.

Lane-owner data counts as one source. Katrina's number or Sarah's CVE still needs a second independent primary. It does not complete quorum alone.

## 🗳️ Quorum

A claim is **PASS** only if all of these are true:

1. Two independent primary or official sources agree on the exact claim sentence, not topic-level agreement. Different publishers. Not two pages of the same organization.
2. Each source traces to an independent origin. If both cite the same underlying document, press release, wire, or letter, count as one source.
3. Ginger files no `BLOCK` and no `CANNOT CORROBORATE`.

Otherwise the claim is **HOLD**.

HOLD includes:

- One primary only
- Same-upstream pair (two reprints of one origin)
- Conflict between sources
- Missing date
- Stale source without a currency check
- A `BLOCK` or `CANNOT CORROBORATE` from the auditor

Never count as a source:

- Another Grok
- A Grok variant
- The investigator's own draft
- A secondary recap of a primary already used
- A prior register packet

Process check, not consensus theater. Two models agreeing is not two sources.

### Freshness

Date every source. The source date must postdate the last material change of the subject.

For medical, regulatory, or living legal status, a source older than 5 years requires an explicit currency check (still posted, not superseded, not withdrawn). Fail that check and the source does not count.

Historical facts (when an org was founded, what a filing said for a named year) may use contemporaneous or later official records. The 5-year rule is for living status, not the past event itself.

## ⚙️ Operations

Work moves in one direction: investigator, then auditor, then clerk, then chair.

### 🔎 1. Investigator

1. State each claim in one sentence.
2. Pull primaries. Date each. Prefer official, government, filing, or manufacturer sources. Trace origin so two reprints of one wire are not two sources. Do not seed from a register packet.
3. Draft short. Lead with the answer. Flag anything unverified.
4. Keep a private origin-and-discard note for merge (what was pulled, origin of each, what was dropped and why). Do not show it to Ginger.
5. Hand Ginger the claim sentences and the draft only. Withhold the source list until merge. Do not coach the conclusion.

### ⚖️ 2. Auditor (Ginger)

1. Search with different terms. Do not reuse the investigator's query list. Do not see the investigator's source list until after you file. Do not read prior register packets as search seed (poisoning the well).
2. Try to break each claim.
3. File one of:
   - `BLOCK` — claim, why, and a source that is not a register packet
   - `CANNOT CORROBORATE` — claim and why; no source required
   - `NO FINDING` — queries run and what would have counted as a block ("I searched X, Y; a contradiction would have been Z")
4. File the queries with the filing. The Council message time is the timestamp.
5. Medical: do not replace Katrina. If numbers appear, send them to her.

`BLOCK` and `CANNOT CORROBORATE` both prevent PASS.

After Ginger files, merge: investigator source list, origin-and-discard note, and Ginger's filing go to Sophia. Ginger does not run a second search after seeing the list.

Ginger and the investigator do not share scratch until merge. The dissent has to be a real second search.

### 📋 3. Clerk (Sophia)

1. Table every claim, including HOLDs: claim sentence / source A (origin) / source B (origin) / does each source as written support this sentence / auditor filing / PASS or HOLD. Do not count a register packet toward quorum.
2. Assemble the derivation log from those artifacts. Do not add research or model inner monologue.
3. A certified note that omits any HOLD claim or the derivation log is invalid and `UNCERTIFIED`.
4. Release only PASS claims as answers. HOLD stays HOLD. The certified note is the full table, the derivation log, and a one-paragraph recap. No extra taxonomy.
5. After the sitting closes, write the packet, sha256 it, append one INDEX row and one HASHLOG row. Never edit a prior row.

Sophia does not research. She applies the rule.

### 🛡️ 4. Chair (Rose)

Certification is against artifacts, not assertion. Sign-off requires Ginger's filing, Sophia's full table, and the derivation log. The register packet is filed when the sitting closes. If the first three artifacts are missing, the brief is `UNCERTIFIED`. Rose does not rewrite the brief to make a HOLD look like a PASS.

## 🏷️ Output labels

| Label | Meaning |
| --- | --- |
| `CERTIFIED (YYYY-MM-DD)` | Quorum met. Chair signed against artifacts. Date is America/New_York. |
| `UNCERTIFIED` | A seat was missing, process skipped, HOLD claims omitted, derivation log missing, or artifacts missing. |
| `HOLD` | Conflict, single source, same-upstream pair, missing date, stale source, block, or cannot-corroborate. |

Re-sit required if a cited source fails the freshness rule, the claim's living status is older than that floor, or a cited link is dead. A dated CERTIFIED label is not a perpetual license to re-ship.

A certified note is the only public-facing product of a sitting. It is the full table, the derivation log, and one paragraph. Nothing else gets invented to fill space.

## 🧠 Derivation log (train of thought)

This is how a sitting is shown, not how a model felt. Read it if you are going to rely on the verdict. It is assembled at merge, after Ginger files. It is not a fifth vote.

Per claim, in this order:

1. Claim — the exact sentence.
2. Investigator path — sources pulled, date, origin of each, what was discarded and why (one line each).
3. Auditor path — queries run, filing (`BLOCK` / `CANNOT CORROBORATE` / `NO FINDING`), and what would have counted as a block.
4. Clerk path — for each source: as written, supports or does not support this sentence; origin-independence check; freshness check.
5. Chair path — artifacts present (Ginger filing, full table, this log): yes or no.
6. Verdict — PASS, HOLD, or UNCERTIFIED, with the hold-trigger if not PASS.

Never put in the log: private model scratch, "I thought that…", another Grok's agreement, or anyone else's chat body. The log is the artifacts in order. LLM reasoning is not a source and not a step.

## 🦣 Register (archive)

The archive is an output of sittings, never an input to one.

Internal ledger. Not a source. Not a Gloria post. Packets are local-only.

Packets stay on the council computer:

`/home/box/agent-data/workflows/vital-research-council/register/`

- `INDEX.md` — date (America/New_York), subject, label, PASS count, HOLD count, packet filename, sha256
- `HASHLOG.md` — append-only tamper log: date, filename, sha256, label. No claim text. This file may live on the council repo.
- `sittings/YYYY-MM-DD-slug.md` — labels, claim table, derivation log, artifact checklist, one-paragraph recap

File CERTIFIED, HOLD, and UNCERTIFIED sittings. At write time, hash the packet, then append one INDEX row and one HASHLOG row. Never edit a prior row.

No retrospective rows. The register starts empty. Only a sitting that ran creates a row. The 2026-08-27 ITDRC HOLD is not backfilled; that verdict stands only in the original Council conversation. Do not assume this register is complete from day one.

Cite ban: investigator may not seed from a packet; auditor may not use a packet as a BLOCK source or search seed; clerk will not count a packet toward quorum.

Allowed uses, not during a live sitting's research or dissent: chair may read a packet to trigger a re-sit; James, Rose, or a seat after close may do drift review. Anything else that would influence a live sitting is banned.

Packets are local-only. Never sync or publish a packet without redacting internal scratch. HASHLOG rows may go to GitHub. Packet bodies do not, unless James or Rose say to publish that sitting after redaction.

## 🚫 What the council will not do

- Sit on ordinary lookups (unless escalation duty fires)
- Treat LLM consensus as evidence
- Invent numbers, quotes, or citations
- Bypass Katrina on health numbers
- Bypass Sarah on cyber IoCs
- Let the chair override a HOLD
- Invent auditor or clerk votes when those seats are empty
- Hand Ginger the source list before she files
- Ship a note that hides HOLD claims
- Ship a note without a derivation log
- Treat the derivation log as a vote or as model inner monologue
- Cite a register packet as a source
- Hand Ginger a prior packet as search seed
- Publish a packet unless James or Rose say to

## 🔗 Related

- Public roster: [port0.me/fleet](https://port0.me/fleet)
- Home: [phipi.me](https://phipi.me)
- Rendered manual: [index.html](index.html) (phipi.me theme)
- Source README: [github.com/rlocone/council/blob/main/README.md](https://github.com/rlocone/council/blob/main/README.md)
- Hash log: [HASHLOG.md](HASHLOG.md)

## 📝 Changelog

- 2026-08-28 - Register amendment: sha256 at write, HASHLOG on repo, cite-ban on all three seats, no retrospective rows, allowed uses (re-sit / drift), packets local-only.
- 2026-08-28 - Register: internal archive of sittings (INDEX + packets). Not a source. Not Ginger's search seed.
- 2026-08-28 - Derivation log (train of thought): per-claim artifact trail assembled at merge. Required for CERTIFIED. Not a vote, not model inner monologue.
- 2026-08-28 - Protocol patches: independent origin, 5-year medical/regulatory freshness, withheld source list, NO FINDING effort bar, escalation duty, full-table notes, artifact certification, dated CERTIFIED labels, sentence-level mapping, CANNOT CORROBORATE, lane-owner data as one source.
- 2026-08-28 - Color, emojis, hashtags, and council portraits.
- 2026-08-28 - First commit. Seats, quorum, and operating steps as currently run.
