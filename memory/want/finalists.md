# Stage 2 result — 5 finalists (2026-08-25)

Scored ~115 ideas ([[ideas]], [[ideas-round2]], [[ideas-round3]]) on reach /
≤4-weekend MVP / passivity / existing payers / enjoyment + [[advantages]] fit.
Chosen as five different business SHAPES so validation teaches which shape fits.

1. **"ntfy for WhatsApp"** — dev notification API on existing infra. Laziest first dollar; passive; proven analog (Pushover). Risk: CallMeBot free, WA API rules. Validate: landing page + $3/mo + one HN/Reddit post, 2 weeks.
2. **Hostel lead-conversion bot** — warm channel (gringo.co.il owner suggested it); recurring ₪/mo; hostels physically nearby. Risk: least passive, sales unknown. Validate: 3 intro'd hostel-owner conversations, $0, no code.
3. **Israeli broker-exam prep site** — most passive; mandated demand; SEO distribution; fully remote-friendly. Risk: existing Hebrew competitors; low fun. Validate: 1 evening competitor research, then landing page.
4. **Israeli-abroad "explain this letter" tool** — I am the customer; buyers concentrated in known expat groups. Risk: willingness to pay. Validate: post in 2 groups, 10 free then ₪20, watch behavior.
5. **Claude Code harness/template pack** — build-once from already-paid-for expertise; Gumroad; SO/a.team distribution; do soon or not at all. Risk: free alternatives; NDA lines (own generic patterns only).

Near-misses: LatAm appointment bot (Spanish cold sales), personal WhatsApp
helper (Zapia/Luzia), table-PDF API (crowded).

## Revision after Noam's review (same day)
- **#3 exam prep: KILLED** — "just ChatGPT, nothing special about me"; no founder belief.
- **#4 Israeli-abroad letters: KILLED** — Noam doesn't feel the pain; I had inferred it with zero demand evidence.
- **#5 Claude Code pack: conditional** — money model = paid-boilerplate play (curation + credibility vs free OSS, à la ShipFast); lives only if Noam actually wants to evangelize it.
- **#1 WhatsApp-ping-API: KILLED** (Noam's catch) — already exists (CallMeBot free; Green API/Ultramsg sell send-via-HTTP); official WA API restricts business-initiated messages to paid templates, unofficial = ban risk; Telegram bots are the free legal substitute devs already use.
- **Key WhatsApp platform fact:** free-form replies are allowed only within a 24h window after the CUSTOMER messages first. This kills outbound-notification products but BLESSES the hostel bot — replying to incoming leads is exactly the permitted use case.
- **Sole active finalist: #2 hostel bot.** (#5 Claude Code pack still conditional on Noam's appetite.)

Next (stage 3): validate hostel bot — gringo-owner intros to 3 hostel owners,
$0, no code. If it dies, return to the pool for the next batch. 4-week kill
per [[constraints]].

## Re-research of #5, the Claude Code harness pack (2026-09-15)

Re-derived from scratch in `micro_businesses/IDEAS.md` before that repo knew this
file existed; folded back here. New material beyond the original one-liner:

**The category framing.** Modern AI coding tools ship a general agent and leave every
user to build the harness — skills, hooks, prompts, review loops, guardrails, glue —
that turns a general agent into something that reliably does one *specific* job
(review, migrate, audit, onboard, keep-a-repo-clean). Everyone rebuilds it badly in
their own dotfiles.

**Open question 1 — can you charge for text?** No runtime moat, and the audience is
the most DIY-capable alive. Candidate answers: sell the maintenance (it rots every
model release), sell the evals that prove it works, sell distribution/bundling, or
host it so the value is execution not config. Consistent with the original
"paid-boilerplate à la ShipFast" call.

**Open question 2 — platform risk.** A good harness gets shipped as a built-in next
release and the product is gone. Needs a category the platforms won't absorb:
org-specific, compliance-shaped, tied to a private codebase or a non-code system. If
no such category exists, this is nights-and-weekends, not a business.

**Datapoint against charging (2026-09-15).** Noam's own machine runs `ponytail`
(DietrichGebert/ponytail v4.9.0) — a polished harness with intensity levels, five
sub-skills and hooks, given away free. Good harnesses already exist at $0.

**Wedge if built.** Not prompt packs — a harness with an eval suite attached, so the
pitch is a measured success rate on a job, not a text file anyone could write.

**Cheapest next test:** count paid-vs-free in the wild (Gumroad ratings as a sales
proxy, plugin/rules marketplaces). ~free, one sitting. If everyone gives them away,
#5 dies without building a page. Still gated on Noam's appetite to evangelize.

---

**Superseded as a status file (2026-09-17).** The "sole active finalist: hostel
bot" line above is stage-2 history, not current state. What is actually being
worked on now lives in [[active-portfolio]]: second-hand dropshipping (live),
OneBNB monetization (waiting on decisions), hostel bot (untouched), AI patent
arbitrage (untouched). #5 the Claude Code pack is not among them. New ideas are
judged with [[business-as-process]].
