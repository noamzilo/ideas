---
name: validation-tooling
description: Landscape of cheap validation stacks (page+price+payment+list) for meta-strategy stage 3; verdict is use Gumroad/Payhip, don't build a product.
metadata:
  type: project
---

# Validation tooling — stage 3 plumbing, not an idea

Researched 2026-09-01 (moved here from `micro_businesses/IDEAS.md` 2026-09-15).
[[meta-strategy]] stage 3 needs, per test: a landing page, a price on it, a payment
link that charges, a list that keeps the address, and one number back
(visitors → signups → paid). Question was whether to build that.

## Landscape

Nobody sells the whole thing; everybody sells one slice:

| Slice | Tools | Price |
|---|---|---|
| One-page site + hosting | Carrd (free 3 sites, Pro $9–49/**yr**), Framer, GitHub Pages | ~$0–19/yr |
| Waitlist / email capture | Waitlister (free ≤100 subs, then $15–99/mo), LaunchList ($19 one-time per project), Getwaitlist | $0–39/mo |
| Email list proper | Kit free ≤10k subs (1 page, 1 form), Beehiiv free ≤2.5k, MailerLite free cut to 250 subs June 2026 | $0 |
| Payment link | Stripe Payment Links (2.9% + 30¢, no monthly), Gumroad (10% + 50¢ on top) | per-sale only |
| AI "build it for me" | Lovable $25/mo, Bolt $20/mo, v0 $20/mo | $20–25/mo |
| Full validation platforms | Prelaunch.com (~<$100/mo), Leadpages $37–99/mo | enterprise-ish |

## Verdict: use Gumroad or Payhip, build nothing

Each is already page + price + working payment + email list, hosted, **$0 until a
sale** (10%+50¢ / 5% fees). A Gumroad page for a $29 pre-order of a thing that
doesn't exist *is* a smoke test today, for free. Fits [[constraints]] ($50/experiment)
with room to spare. What's missing is only framing and a verdict number — not worth
building before there are tests to run.

## Why it is not a business

"Founders testing ideas" is structurally bad: pre-revenue by definition, churning by
design (the idea dies → stop paying, or it works → graduate to real tooling). Most
people run one test, ever. Survivors here sell to repeat testers with budget —
[Prelaunch](https://prelaunch.com/use-cases/price-optimization.html) at ~$100/mo to
funded DTC/hardware teams, Leadpages at $37–99/mo to marketers. That buyer is an
agency, a DTC operator, or an audience owner — not me. Filed as tooling, not as an
idea in the pool.

Sources: [Gumroad email tools](https://insightraider.com/en/answers/how-to-build-an-email-list-with-gumroad) ·
[Payhip review](https://coldiq.com/tools/payhip) ·
[Beehiiv/Ko-fi/Payhip free plans](https://www.getly.store/blog/ko-fi-vs-payhip) ·
[LaunchList](https://getlaunchlist.com/blog/idea-validation-tools) ·
[Waitlister pricing](https://waitlister.me/pricing) ·
[Carrd pricing](https://www.nocode.mba/articles/carrd-pricing) ·
[Gumroad pricing](https://www.swell.is/content/gumroad-pricing) ·
[Kit/MailerLite free tiers](https://www.emailtooltester.com/en/blog/free-newsletter-platforms/) ·
[Lovable vs Bolt vs v0](https://superframeworks.com/compare/lovable-vs-bolt-vs-v0) ·
[MVP page builders](https://www.buildmvpfast.com/blog/best-landing-page-builders-mvp-2026)
