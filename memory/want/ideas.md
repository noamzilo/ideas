# Idea Pool (stage 1 — no judging here, judging happens in stage 2)

Format: **what — who pays**. Grounded in [[who-i-am]] skills and past projects
(RL/evals, RAG + table-aware PDF parsing, data pipelines, CV/sports video,
time-series, ad-tech, SO reputation). Constraints per [[constraints]].

## Paid tools / micro-SaaS (small, self-serve, payment link)
1. **Table-aware PDF → clean CSV/JSON API** — devs/analysts drowning in contracts, invoices, pricing tables; pay per page. (Direct reuse of CeranoAI work.)
2. **RAG retrieval-miss auditor** — upload your corpus + queries, get a recall report and chunking recommendations; AI teams pay because silent misses scare them.
3. **LLM eval-harness starter kit** — hosted or downloadable harness for teams that need reward-hacking-resistant grading of agents; AI startups pay.
4. **PyTorch training-run doctor** — CLI that profiles a training loop and flags the classic throughput killers (dataloader stalls, CPU preprocessing, no caching); ML engineers pay once.
5. **Dataset-stratification tool** — upload labels + metadata, get metadata-stratified train/val splits (the UVeye 50%→95% trick as a product); ML teams pay.
6. **Padel/tennis match auto-highlights** — phone video in, clips of rallies/points out; club players pay per video. (Plai work reused.)
7. **Sports-court calibration API** — homography/bundle-adjustment from phone footage for any court sport; sports-tech startups pay.
8. **Insurance-claim sanity checker for individuals** — upload claim + policy, get flagged discrepancies; consumers pay per check. (CeranoAI inverted: sell to patients, not insurers.)
9. **ECG/time-series labeling helper** — semi-automatic labeling for scarce-data time-series domains; research labs pay.
10. **Cron-job / pipeline babysitter** — dead-simple "did my nightly ETL actually run and produce sane output" monitor; solo data engineers pay $5/mo.
11. **ClearML/W&B cost dashboard** — which experiments burn GPU money for no metric gain; ML team leads pay.
12. **OpenAI/Anthropic API cache proxy** — drop-in cache layer that cut costs 90% at CeranoAI, as a self-hosted paid tool; API-heavy startups pay.

## Digital products (build once, sell forever — most passive)
13. **"RL environment design" ebook/course** — how to build environments and grading that resist reward hacking; extremely few people have done this commercially; AI-lab contractors and aspirants pay. (a.team-adjacent audience.)
14. **"Get hired by AI labs as a contractor" guide** — the a.team/Bespoke/PreferenceModel path, with real numbers; ML engineers pay $30–50.
15. **Eval-task template pack** — 20 ready-made RLVR task/grader templates; teams entering the eval-gig economy pay.
16. **"Data contracts in practice" mini-book** — bronze/silver/gold + contract validation patterns from UVeye; data engineers pay.
17. **PyTorch performance checklist/course** — the 10x-throughput playbook; sell on Gumroad; SO reputation (10M reached) is the distribution.
18. **Table-aware RAG cookbook** — code + patterns for PDFs with tables; every RAG team hits this wall; devs pay.
19. **Interview prep pack: ML systems design** — real cases (1M images/week pipeline, real-time cardiac) as worked examples; job-seekers pay.
20. **Notion/Markdown template: freelance ML proposal system** — my proposal method productized; freelancers pay $19.

## Datasets & benchmarks (build once, license)
21. **Labeled padel/racket-sports clips dataset** — sports-CV startups pay to license; I know exactly how to build it cheaply.
22. **Synthetic pricing-table PDF benchmark** — for testing PDF parsers; parser vendors and RAG teams pay or it drives tool #1.
23. **Reward-hacking examples corpus** — documented agent-gaming patterns + defenses; eval teams pay. (Check NDA boundaries — only public/original content.)

## Content/SEO engines (free traffic → affiliate/ads/product funnel)
24. **"PyTorch errors explained" site** — SEO plays on the exact questions I answer on SO; ad/affiliate revenue + funnel to #17.
25. **Niche benchmark blog: PDF-parsing tools compared** — quarterly re-tests, affiliate links to winners; buyers searching "best pdf table extraction" convert.
26. **Ad-tech SQL patterns site** — from the ad-tech project learnings; niche but zero competition; funnel to a paid pattern pack.

## Browser extensions / small apps (one-time or freemium)
27. **Stack Overflow answer-to-blog-post converter** — turn my 30K-pt answer history into content automatically; sell the tool to other high-rep users.
28. **Upwork/a.team job-alert filter with LLM scoring** — scores gigs against your profile, pings only real fits; freelancers pay $5/mo.
29. **PDF table copy-paster extension** — select a table in any PDF in-browser, get clean rows; office workers pay once.

## APIs on marketplaces (RapidAPI etc. — passive distribution built in)
30. **Image-registration/alignment API** — the IAF 90%-optimized classical CV work as an endpoint; app devs pay per call.
31. **Few-shot re-identification API** — person/object re-id from a handful of examples; small CV teams pay per call.
32. **Time-series anomaly-flagging API** — generic, feature-engineering-driven (works on scarce data, unlike deep-only competitors); IoT hobbyists/startups pay.

## Wildcards
33. **Micro-tool directory for ML engineers** — curated, paid listings once traffic exists; the site itself is the asset.
34. **"Kill deadline" accountability app for side-project builders** — literally this meta-strategy as an app; indie hackers pay.
35. **Hebrew-language ML career content** — underserved market I'm native in; sponsorships/course funnel.

## Half-done assets I already have (currently making $0 or less)
36. **WhatsApp lead miner** (`../whatsapp_miner`) — deployed miner+LLM classifier (Green API, Supabase, AWS, Docker). Idea: harvest group messages, classify leads, sell them fast to local businesses. Open problems: getting/staying in groups, classification quality, getting buyers, **legal/privacy risk of selling personal data**. Planned validation: site shows the message, business pays to unlock the lead.
37. **OneBNB / Airbnb extension** (`../airbnb_filter`) — polished long-stay UX extension (Firefox MV2). Monetization unclear (Airbnb has no affiliate program); site changes constantly → maintenance treadmill, anti-passive. Maybe top-of-funnel. Legal/ToS risk. **Update 2026-09-17:** revenue + passive-growth plans delivered, awaiting decisions — see [[active-portfolio]] #2.
38. **Hostel lead-conversion bot** — from gringo.co.il's owner: hostels lose incoming leads; sell them a WhatsApp bot on a number "they own" (but leads route through me → lock-in). Reuses whatsapp_miner infra. Warm intro available via gringo owner. Unknown: real demand, sales effort.
39. **Selling my skills** — that's a job, not a business. Fallback when the current job ends (likely soonish — employer is building an agent to replace the team).
40. **AI YouTube channel** — slow top-of-funnel. Only counts as "not a job" if it funnels to products (courses/tools), not services. Doesn't fit 4-week kill cycles on its own.

## Next
Stage 2: score all 35 on reach / ≤4-weekend MVP / passivity / existing payers /
enjoyment. Keep 3. See [[meta-strategy]].

## Later additions (2026-09-17, after stage 2)
41. **Second-hand dropshipping, Asunción** — source used laptops locally, resell on Clasipar on a +$50 spread, try-before-you-buy pitch, sqlite price engine as the moat. Now the most developed thing in play: [[active-portfolio]] #1.
42. **AI patent arbitrage** — crawl patent databases, AI-crawl for buyers, buy the patent only after a buyer commits ("patent dropshipping"). Untouched: [[active-portfolio]] #4.
