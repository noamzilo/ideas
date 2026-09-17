# Active portfolio (execution state, 2026-09-17)

The four things actually in play, with real state — not pool candidates. The
pool files ([[ideas]], [[ideas-round2]], [[ideas-round3]]) are frozen stage-1
artifacts and [[finalists]] is the stage-2 scoring artifact; **this file is the
current truth about what is being worked on.**

Pasted from the operator's status report, so pronouns are theirs: **"I"** is the
operator running the day-to-day, **"you"** is Noam. Evaluate every entry against
[[business-as-process]].

---

## 1. Second-hand dropshipping, Asunción — MOST DEVELOPED, LIVE

**Model:** I do sourcing, listing, photos, buyer messaging; you do inspection,
meetups, cash. Clasipar is the sell-side, deposit-first from buyers, target
**+$50 spread per unit**, AI-enhanced photos + spec card per listing. FB
Marketplace excluded for now (account ban risk — you do those messages manually
with my paste-ready texts).

**Sales pitch, locked by Noam:** *try-before-you-buy*. Buyer takes the laptop
home for a day, **no money down**, comes back to pay or return it ("fall in love
with the dog"). You're betting people don't steal.

Controls on that bet:
- one unit out at a time
- cheapest stock first
- cedula photo + verified WhatsApp before handover
- meet at your building
- **count thefts over 10 trials** so the bet becomes a number

**Moat: the price engine.** Approved by Noam 2026-09-16, running now:
- every Clasipar listing in the **$200–500 band** stored in sqlite (700+ rows and growing)
- hourly crawls, live USD/PYG rate stamped per row
- specs as columns — one different column = a different price
- unknown specs filled by LLM with search
- per-model price tabs
- **sold-signal validation gate:** a vanished listing is "unavailable" unless
  Clasipar explicitly says sold; reposts get detected and linked — so clearing
  prices can't get poisoned

Milestones coming: 3-day clean-rows report → spec-fill coverage → per-model view
+ underpriced-buy alerts to your WhatsApp.

## 2. OneBNB extension, monetize — PLANS DELIVERED, WAITING ON NOAM

Chrome + Firefox extension for Airbnb: true nightly/total price with fees, saved
shortlists, hide rejected listings. Code at `../../airbnb_filter`; pool entry is
[[ideas]] #37.

**Passive growth is a hard requirement** — no ads, no ongoing promotion, like
JustGPTIt's ~300 visits/mo on zero upkeep. Revenue plan and passive/viral
growth-loop plans are delivered and awaiting Noam's decisions.

Constraints:
- **no telemetry or data collection without Noam's explicit sign-off**
- Noam's only steps should be: merge/publish, store listings, payment account

## 3. Hostel sales bot, LatAm — UNTOUCHED

Simple sales bot for hostels. Field proven elsewhere; needs to be executed well
enough. Untouched so far.

Background in [[finalists]] #2 and [[ideas]] #38: warm channel via the
gringo.co.il owner, recurring ₪/mo, hostels physically nearby. The WhatsApp
24-hour-window rule *blesses* this shape — replying to an incoming lead is the
permitted use case. Stage-3 test on the books: 3 intro'd hostel-owner
conversations, $0, no code.

## 4. AI patent arbitrage — UNTOUCHED

Crawl patent databases for patents, AI-crawl to find buyers, **buy the patent
only after a buyer commits**. "Patent dropshipping based on AI." Untouched so
far. New — not in any pool round.

---

## Note on constraints

[[constraints]] says 10 h/wk, $50/experiment, 4-week kill, and [[meta-strategy]]
says one experiment at a time past stage 3. Entry #1 is past stage 3 and running;
#2 is waiting on decisions, not on work. #3 and #4 are parked by definition
("untouched"), which is what keeps this consistent with the one-at-a-time rule.
