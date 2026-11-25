# ScraperAPI Promo Code: Does START10 Still Work, Is 10% the Ceiling, and Which Plan Should You Actually Buy?

Two ScraperAPI discounts hold up to checking. **START10 takes 10% off your first month**, and **annual billing takes 10% off every month with no code at all**. The 50% and 70% codes on coupon pages either expired weeks ago or never worked at checkout.

Below is the full price table with annual math per plan, the difference between the two 10% routes on a real invoice, and the credit costs that decide whether 100,000 credits lasts a month or a week.

> **Quick pick.** Spend the 7-day trial first: 5,000 credits, no credit card, run against the domains you actually need. If the success rate holds and you'll keep scraping, annual billing is the cheaper route — Hobby lands at $44.10/mo, $58.80 less per year than monthly. Use START10 only when you're paying for a single month to finish an evaluation. 👉 [Start the free trial with 5,000 credits](https://www.scraperapi.com/?fp_ref=coupons)

## All ScraperAPI plans and prices

| Plan | Monthly | Annual (10% off) | Credits / threads | Geotargeting | Start |
| --- | --- | --- | --- | --- | --- |
| Free | $0 | $0 | 1,000 / 5 | — | [Get started](https://www.scraperapi.com/?fp_ref=coupons) |
| Hobby | $49 | $44.10 | 100,000 / 20 | US & EU | [Get started](https://www.scraperapi.com/?fp_ref=coupons) |
| Startup | $149 | $134.10 | 1,000,000 / 50 | US & EU | [Get started](https://www.scraperapi.com/?fp_ref=coupons) |
| Business | $299 | $269.10 | 3,000,000 / 100 | Country-level | [Get started](https://www.scraperapi.com/?fp_ref=coupons) |
| Scaling | $475 | $427.50 | 5,000,000 / 200 | Country-level | [Get started](https://www.scraperapi.com/?fp_ref=coupons) |
| Professional | $975 | $877.50 | 10,500,000 / 300 | Country-level | [Get started](https://www.scraperapi.com/?fp_ref=coupons) |
| Advanced | $1,975 | $1,777.50 | 21,500,000 / 500 | Country-level | [Get started](https://www.scraperapi.com/?fp_ref=coupons) |
| Enterprise | Custom | Custom | 22,000,000+ / 500+ | Country-level | [Get started](https://www.scraperapi.com/?fp_ref=coupons) |

Enterprise is quoted per workload. Analytics history splits at Business: Hobby and Startup show the last 30 days, Business and above are unlimited. Prices above come from ScraperAPI's published plan documentation; the checkout page is the final word on what you're charged.

Annual savings by tier: $58.80 on Hobby, $178.80 on Startup, $358.80 on Business, $570 on Scaling, $1,170 on Professional, $2,370 on Advanced.

## Why most "ScraperAPI promo codes" you'll find don't work

The discount ceiling on this product is 10%, and that number comes from tracking rather than guesswork. SimplyCodes, which logs code activity for the store, reports a consistent 10% ceiling on ScraperAPI discounts and a 90-day average discount of 10%. A 50% or 70% code has no support in that record.

Aggregator pages show where the big numbers come from. One page updated in late October listed a 70% "exclusive code," 60% off geo-targeting, 50% off headless rendering, 45% off an e-commerce scraper and a student discount in the same table, none of them with a verification record. Every code on that page that carried an expiry date died between October 24 and October 29. Those dates are three weeks gone.

Community checks are mixed even at the 10% level. SimplyCodes users reported working 10% codes on October 18, 19 and 24, and failures on October 16, 17 and 23, with three separate non-working reports on November 9 alone. What that pattern tells you: 10% codes exist and rotate, and any specific string can be dead by the time you paste it.

START10 is the exception worth typing in. It's the only named code confirmed on ScraperAPI's own domain, on an older promo page that described it as 10% off the first month, and independent write-ups describe it the same way. It applies to a paid plan's first billing period and nothing after that.

## The two 10% routes, priced on a real invoice

START10 and annual billing both move 10%, but they don't move the same money.

On Hobby at $49/mo, the code cuts $4.90 off one invoice. Annual billing cuts $4.90 off every invoice, which is $58.80 across a year. On Startup, the first-month code saves $14.90 once; annual billing saves $178.80 a year. The longer you stay, the less the code matters and the more the billing cycle does.

Don't count on combining them. ScraperAPI's own documentation treats the annual discount as a plan-level setting, and there's no confirmed statement that a first-month promo stacks on top of it. If you want to try, apply the code on the checkout page and read the total before you confirm, since both discounts sit at the same 10% level and the cheaper path isn't always the obvious one.

The practical rule: paying month to month for one or two months while you evaluate? Use START10. Committing to a year? Skip the code hunt and take the annual price.

## What 100,000 credits actually buys

A credit isn't a page. ScraperAPI prices requests by how hard the target is:

| Request type | Credits |
| --- | --- |
| Standard page | 1 |
| Amazon, Walmart, eBay | 5 |
| Google, Bing (incl. subdomains) | 25 |
| LinkedIn | 30 |
| Bot-protection bypass (Cloudflare, DataDome, PerimeterX, Akamai) | +10 |
| JS rendering (`render=true`) | 10 |
| Premium proxies (`premium=true`) | 10 |
| Screenshot | 10 |
| Premium proxies + JS rendering | 25 |
| Ultra premium | 30 |

Geotargeting, sessions, device type, output format and auto-parsing add nothing.

So Hobby's 100,000 credits is 100,000 plain requests, or 20,000 Amazon product pages, or 4,000 Amazon pages that also need rendering and a bot-protection bypass at 25 credits each. That last number is the one that catches people: a Hobby plan that looks like it covers a month of Amazon monitoring can run dry in days if every request is rendered and protected.

Two tools keep this from being a guess. The Domain Cost Estimator in the dashboard quotes the exact credit cost for a URL before you spend anything, and the `max_cost` parameter caps any single scrape so one expensive target can't eat a day's budget. Every response also returns its cost in the `sa-credit-cost` header, which makes it easy to log real spend per domain instead of discovering it at renewal.

Worth knowing before you scale: credits don't roll over. Your balance resets when the subscription renews, so an oversized annual plan doesn't bank unused capacity for a busy quarter.

## Which plan fits which workload

**Hobby ($49, or $44.10 annual)** covers indie projects and one-off data pulls. Its limit isn't credits, it's geotargeting: US and EU only. If your targets serve different pricing or content to users in Japan, Brazil or Germany, Hobby can't request those IPs at all.

**Startup ($149, or $134.10 annual)** is the same feature set with ten times the credits and 50 threads. Same US/EU restriction, same 30-day analytics.

**Business ($299, or $269.10 annual)** is the first tier with country-level geotargeting across the full proxy pool, plus unlimited analytics history and 100 threads. Localized price monitoring or multi-market SERP tracking starts here, because it's the cheapest plan where the geotargeting you need exists.

**Scaling ($475, or $427.50 annual)** is the volume tier, and the first with pay-as-you-go. If your monthly request count swings — client projects, seasonal pulls, a scraper that only runs during sales — PAYG (live since January 2026) lets you keep scraping past your credit limit at a fixed per-credit rate with a monthly cap you set, instead of jumping to a plan sized for your worst month.

**Professional and Advanced** exist for continuous pipelines: 10.5M and 21.5M credits, 300 and 500 threads, priority support. One difference that matters if you rely on automation: auto-upgrade is opt-in on Hobby through Professional but unavailable on Advanced, where you're expected to size the plan correctly or use PAYG.

If you're unsure between two tiers, run the trial on your real targets first and watch the dashboard's success rate and credit burn. 👉 [Test your own domains on the 5,000-credit trial](https://www.scraperapi.com/?fp_ref=coupons)

## What you risk if it doesn't work out

Very little, and that's the reason to test rather than theorize.

The trial is 5,000 credits over 7 days with no credit card, full feature access including proxy rotation, CAPTCHA handling, JS rendering and JSON parsing, capped at 5 concurrent connections. When it ends, the account drops to a permanent free plan with 1,000 credits a month and 5 threads — enough for a small script that runs daily, not enough for production.

Paid plans carry a 7-day no-questions-asked refund, and you can cancel from the dashboard at any time without a cancellation fee. If you exceed your concurrency limit you get a 429 response rather than a surprise charge; the request is refused, not queued and billed.

The catch to plan around: on Hobby, Startup and Business, running out of credits mid-cycle pauses scraping until renewal unless you've opted into auto-upgrade. Only Scaling and above let you keep going on PAYG. 👉 [Start with the no-card trial and cancel from the dashboard](https://www.scraperapi.com/?fp_ref=coupons)

## FAQ

**Is START10 still valid?**
It's the only named code with confirmation from ScraperAPI's own domain and from independent write-ups describing it as the official first-month code. It gives 10% off your first month on a paid plan. Because 10% codes rotate, paste it at checkout and check the total; if it doesn't apply, annual billing gets you the same 10% on every invoice.

**Can I stack START10 with annual billing?**
There's no confirmed statement that the two combine. Both operate at 10%, so test the code on the checkout page and compare the final total against the plain annual price.

**Is the free plan enough to skip paying?**
1,000 credits a month at 5 threads covers a small daily script scraping standard pages. It won't cover rendered pages at 10 credits each, protected targets at 10 extra credits per bypass, or any Google or LinkedIn volume.

**Which plan do most buyers actually need?**
Hobby for US/EU targets at low volume, Business the moment you need country-level geotargeting or unlimited analytics, Scaling if your volume is unpredictable enough that PAYG matters. Professional and Advanced are for pipelines already running millions of requests a month.

**What happens when credits run out?**
Requests stop until renewal. Auto-upgrade is opt-in on Hobby through Professional; PAYG is available on Scaling and above at a fixed per-credit rate with a cap you set. Unused credits don't carry over.

## Before you pay

Match the plan to the constraint that actually binds you. Scraping standard pages from US or EU IPs at modest volume, Hobby at $44.10/mo annual is the whole answer. Needing IPs outside the US and EU pushes you to Business regardless of volume, because no cheaper tier offers it. Volume that spikes unpredictably points at Scaling and PAYG.

Three things to confirm on the checkout page: the total after any code is applied, whether your target domains sit outside the US and EU (which rules out Hobby and Startup), and the credit cost of those domains in the estimator. That last number decides whether your chosen tier lasts a month or a week. 👉 [Pick a plan and see the final price at checkout](https://www.scraperapi.com/?fp_ref=coupons)
