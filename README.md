# ScraperAPI Free API Key: How to Get 5,000 Free Credits With No Credit Card — Complete Signup Guide, Plan Breakdown, and the Credit Math That Actually Matters

So you've heard about ScraperAPI, typed something like "scraperapi api key free" into Google, and landed here. Good. Let me tell you exactly what you'll get for free, how to get your API key in about two minutes, and — most importantly — the one thing almost every other guide skips: the credit math that decides whether your free credits actually last a week or disappear in a single afternoon.

No fluff. Let's just get into it.

---

## What Is ScraperAPI, Exactly?

ScraperAPI is a web scraping API that sits between your code and the internet. You send it a URL, it sends back the HTML. The unglamorous work — rotating proxies across a pool of **40 million+ IPs in 50+ countries**, solving CAPTCHAs, triggering JavaScript rendering, handling retries — all of that happens on their end. You just get clean data back.

The company launched in 2018, is headquartered in Las Vegas, and at this point processes around **36 billion API requests per month** for clients that include names like Deloitte, Sony, and Alibaba. That's not a startup still figuring out uptime — it's infrastructure that's been stress-tested at serious scale.

The reason most developers end up here is simple: building your own proxy rotation and anti-bot infrastructure is genuinely painful. ScraperAPI sidesteps all of that for a monthly subscription that starts at zero.

---

## The ScraperAPI Free API Key: What You Actually Get

Here's where it gets slightly more nuanced than "free forever."

ScraperAPI's free tier works in two layers:

**Layer 1 — The Permanent Free Plan**
Every account gets **1,000 API credits per month** with up to 5 concurrent connections. No credit card required. This exists as long as your account does — it's not a trial that expires, it's a recurring monthly allocation.

**Layer 2 — The 7-Day Trial Boost**
When you first sign up, your account gets bumped to **5,000 API credits** for the first 7 days. Same no-credit-card rule applies. This is there specifically so you can test the API against your real scraping targets at meaningful volume before deciding whether to pay for anything.

The signup page puts it plainly: "Get started with 5,000 free API credits. No credit card required."

That's the honest summary. 1,000 credits/month is the ongoing free plan; 5,000 credits is a one-time 7-day window to kick the tires properly.

👉 [Claim your free ScraperAPI API key here — no card required](https://www.scraperapi.com/?fp_ref=coupons)

---

## How to Get Your ScraperAPI API Key: Step by Step

Getting the key itself takes about two minutes. Here's the actual process:

1. **Click the signup link** — go to the ScraperAPI registration page
2. **Enter your email and create a password** — standard stuff, no credit card field appears
3. **Confirm your email** — they'll send a verification link
4. **Land on your dashboard** — your API key is displayed right there on the home screen

Once you have it, using it is literally one line. The basic format is:


https://api.scraperapi.com/?api_key=YOUR_API_KEY&url=https://target-site.com


That's it. No SDK installation required. No SDK at all, unless you want one. You can also use their Python, Node.js, Ruby, PHP, or Java libraries if you want something more structured, but the core mechanic is just a URL with your key attached.

To generate a new API key (if yours gets exposed), go to your Dashboard → click your email in the bottom left → **Manage API keys** → **New API key**. Note that you can only generate a new key once every 24 hours.

---

## The Part Most Free-Tier Reviews Don't Tell You: Credit Multipliers

This is where things get real, and where people get surprised by how fast their credits disappear.

ScraperAPI's pricing is not "1 request = 1 credit." It's "1 request = *somewhere between 1 and 75 credits* depending on the site and features you enable." The base rate is 1 credit for a standard HTML page, but that number multiplies based on two things: **the domain you're targeting** and **the features you switch on**.

### Domain-Based Credit Costs (Automatic — You Don't Choose This)

| Target Type | Credits Per Request | Examples |
|---|---|---|
| Normal websites | 1 | Blogs, news sites, plain HTML |
| E-commerce | 5 | Amazon, eBay, Walmart |
| Search engines (SERP) | 25 | Google, Bing |
| Social media | 30 | LinkedIn |

These are automatic. The moment ScraperAPI detects that you're pointing at Amazon, it charges 5 credits — you don't have to opt in, and you can't opt out.

### Feature-Based Credit Costs (Optional — You Enable These)

| Parameter | Extra Credits |
|---|---|
| `render=true` (JavaScript rendering) | +10 |
| `screenshot=true` | +10 |
| `premium=true` (premium proxy) | +10 |
| `ultra_premium=true` | +30 |
| `premium=true` + `render=true` combined | +25 (NOT +20) |
| `ultra_premium=true` + `render=true` combined | +75 (NOT +40) |

The combined pricing for the last two rows is the kicker: combining `premium` and `render` costs **25 extra credits**, not the 20 you'd expect from adding the individual costs. Ultra-premium combined with render hits **75 credits** — nearly double what the sum would suggest. This non-linear stacking is documented but not prominently displayed, and it's the primary reason users report credits evaporating.

On the bright side: **you're only billed for successful requests**. If a scrape fails (anything that returns a non-200 and non-404 response), no credits are consumed. You pay only for data ScraperAPI actually delivers.

### What Your 5,000 Free Credits Actually Cover

| Scraping Scenario | Credits Per Request | Requests Covered |
|---|---|---|
| Plain HTML blog or news site | 1 | 5,000 |
| Amazon product page | 5 | 1,000 |
| Google SERP | 25 | 200 |
| Amazon + JavaScript rendering | 15 | ~333 |
| Any site + ultra-premium + JS rendering | 75 | ~66 |

So if you're building something that scrapes standard pages, 5,000 credits is a genuinely generous test window. If you're going after Amazon with rendering on, you've got about 333 requests to work with. That's still enough to validate whether the API works for your use case before you commit to a paid plan.

---

## All ScraperAPI Plans: Full Comparison (Including Free)

Here's the complete current lineup. All plans include JS rendering, premium proxies, JSON auto-parsing, rotating proxy pools, custom headers, CAPTCHA/anti-bot bypass, custom sessions, automatic retries, unlimited bandwidth, and a 99.9% uptime guarantee. The differences between tiers are volume, concurrency, and geotargeting scope.

| Plan | Monthly Price | Annual Price (per mo) | API Credits/Month | Concurrent Threads | Geotargeting |
|---|---|---|---|---|---|
| **Free** | $0 (permanent) | — | 1,000 | 5 | None |
| **Free Trial** | $0 (first 7 days) | — | 5,000 (one-time) | 5 | None |
| **Hobby** | $49/mo | $44.10/mo | 100,000 | 20 | US & EU only |
| **Startup** | $149/mo | $134.10/mo | 1,000,000 | 50 | US & EU only |
| **Business** | $299/mo | $269.10/mo | 3,000,000 | 100 | Global (50+ countries) |
| **Scaling** ⭐ Most Popular | $475/mo | $427.50/mo | 5,000,000 | 200 | Global |
| **Professional** | $975/mo | $877.50/mo | 10,500,000 | 300 | Global |
| **Advanced** | $1,975/mo | $1,777.50/mo | 21,500,000 | 500 | Global |
| **Enterprise** | Custom | Custom | 22,000,000+ | 500+ | Global |

**What to notice in this table:**

- **Geotargeting is gated.** Hobby and Startup are limited to US & EU proxies. If you need to target specific countries outside of that — say, scraping German Amazon listings from a German IP — you're looking at the Business plan at minimum.
- **Pay-As-You-Go is only available from Scaling upward.** On Hobby, Startup, and Business, running out of credits mid-cycle means you're cut off until the next billing date. The only workaround is manually upgrading to the next tier.
- **Credits don't roll over.** Whatever you don't use in a billing cycle disappears at renewal.
- **Annual billing saves 10% across all plans** — no promo code needed, it's automatically applied at checkout.

### Which Plan Should You Pick?

👉 [Start with the free trial and test against your real targets first](https://www.scraperapi.com/?fp_ref=coupons)

**Hobby ($49/mo)** makes sense if you're running a personal project, testing a business idea, or monitoring a handful of competitor pages. 100,000 credits covers a lot of ground for plain HTML — just remember that number shrinks fast if Amazon or Google are your targets.

**Startup ($149/mo)** is the right step-up for a small SaaS product or a freelancer running scraping jobs for a few clients. One million credits with 50 concurrent threads is meaningful volume, though you're still capped at US/EU geotargeting.

**Business ($299/mo)** is the first tier that unlocks global geotargeting, unlimited analytics history, and 100 concurrent threads. If country-level targeting matters to your project, this is the entry point. It also comes with a better price-per-credit ratio than the tiers below it.

**Scaling and above** is for when the question stops being "which plan" and becomes "how do we keep costs predictable at high volume." Scaling is the first tier that includes Pay-As-You-Go overflow — so you're never hard-capped mid-month, you just pay a fixed rate for any credits past your monthly limit.

For **academic research** specifically: ScraperAPI has a dedicated academic program where universities, NGOs, and public bodies can get 50,000 scraping credits for just $10. Worth checking out if that applies to you.

---

## What ScraperAPI Actually Does Well (And Where It Struggles)

Before committing any credits — even free ones — it's worth knowing how the API actually performs across different site types. Independent benchmarking from Scrapeway gives a fairly clear picture.

### Sites Where ScraperAPI Is Genuinely Strong

- **Zillow** — 100% success rate in independent tests
- **Amazon** — 98% success, with structured data endpoints that return parsed JSON (18+ fields: price, BSR, reviews, images, seller info, variants)
- **Etsy** — 99% success
- **Walmart** — 93% success
- **Google SERPs** — solid performance with dedicated structured data endpoints for organic results, shopping, maps, news, and jobs

For e-commerce and real estate specifically, ScraperAPI's **Structured Data Endpoints** (SDEs) are a standout feature. Instead of raw HTML you have to parse yourself, these endpoints return clean, structured JSON. Available on all plans including Free.

### Sites Where It Falls Short or Fails Completely

- **Instagram** — 0% success rate
- **Twitter/X** — 0% success rate
- **Booking.com** — 0% success rate
- **Realtor.com** — 12% success rate

Social media is effectively a dead zone. If your scraping targets live there, ScraperAPI isn't the right tool regardless of which plan you're on.

**One more gotcha:** ScraperAPI explicitly forbids scraping data behind login walls. Session persistence (keeping the same IP across multiple requests) is supported via the `session_number` parameter, but the platform cannot handle authentication, form filling, or 2FA. Sites that require a login before showing data are off-limits.

---

## Real User Reviews: What People Are Actually Saying

ScraperAPI has collected a meaningful body of reviews across platforms. The current ratings:

| Platform | Rating | Number of Reviews |
|---|---|---|
| Trustpilot | 4.5/5 | 43+ |
| Capterra | 4.6/5 | 62+ |
| G2 | 4.4/5 | 16+ |

Capterra's sub-ratings break it down: **Ease of Use 4.9/5**, **Customer Service 4.6/5**, **Features 4.5/5**, **Value for Money 4.5/5**.

The recurring themes in positive reviews: setup is fast (the docs are described as clean and easy to follow), integration is simple (it works as a drop-in proxy replacement for existing code), and support is responsive. Multiple reviewers note that upgrading or downgrading plans is painless.

On the critical side, the consistent complaints are about the credit math being less intuitive than the headline numbers suggest — particularly once users start combining rendering and premium proxy parameters on harder targets. A few reviewers specifically mentioned surprise at discovering the multiplier system only after credits were already gone.

> *"Super easy to set up. You can start scraping in minutes."* — Latenode Community

> *"Breakdown of credit costs can be confusing."* — John S., Founder, Capterra

Both of those can be true at the same time. The API itself is genuinely easy to integrate; the billing model requires a bit more reading than the homepage suggests.

---

## Practical Tips for Stretching Your Free Credits Further

A few things worth knowing before you burn through your 5,000 trial credits:

**Test on your actual targets.** Use the first few hundred credits on the specific sites you need to scrape — not generic test URLs. You need to know how many credits each request actually costs *for your use case* before you can estimate monthly volume.

**Check the Domain Cost Estimator in your dashboard.** ScraperAPI has a built-in tool that lets you see the credit cost for a specific URL before you scrape it at scale. Use this before running any batch job.

**Only enable features you actually need.** `render=true`, `premium=true`, and `ultra_premium=true` are all optional and all cost extra credits. If a site renders fine without JavaScript, don't turn on JS rendering.

**Monitor your dashboard manually.** ScraperAPI does not send proactive usage alerts — no email when you're at 80% of your credits, no notification when you're about to hit zero. You have to check the dashboard yourself. On the free and trial tier, get into the habit of checking it every couple of days.

**Don't forget the 7-day trial window.** The 5,000-credit trial only lasts 7 days. If you sign up and forget about it, those credits just expire. Schedule time in your first week to actually test the API.

---

## Getting Started: Your First API Call

Once you've claimed your free API key, here's what a basic call looks like in Python:

python
import requests

API_KEY = "your_api_key_here"
TARGET_URL = "https://httpbin.org/ip"

response = requests.get(
    "https://api.scraperapi.com/",
    params={
        "api_key": API_KEY,
        "url": TARGET_URL
    }
)

print(response.text)


That's literally the whole integration for a basic HTML scrape. For JavaScript rendering, just add `"render": "true"` to the params dict. For premium proxies, add `"premium": "true"`. For geotargeting (Business plan and above), add `"country_code": "de"` (or whatever country code you need).

The simplicity is real — this is genuinely one of the easier scraping APIs to get started with, which explains why ease-of-use ratings consistently come in near 5/5 from actual users.

---

## Frequently Asked Questions

**Does the free ScraperAPI API key expire?**
The permanent free plan (1,000 credits/month) doesn't expire as long as your account is active. The 7-day trial boost (5,000 credits) expires after 7 days from signup.

**Do I need a credit card to get a free API key?**
No. Signup requires only an email address and password. No payment information is collected until you decide to upgrade to a paid plan.

**What happens if I run out of free credits?**
On the free plan, your scraping stops until the next monthly reset. If you're on a paid Hobby, Startup, or Business plan and exhaust your credits mid-cycle, you can upgrade to the next tier — but there's no Pay-As-You-Go overflow on those plans. PAYG overflow is only available starting at the Scaling plan ($475/mo).

**Can I get more free credits?**
The documented path for additional testing credits is to contact ScraperAPI support directly. The signup page also mentions that you can "contact us to claim up to 50 million scraping credits" — that appears to be for enterprise-level discussions, not a standard self-serve flow.

**Is there a refund policy?**
Yes. ScraperAPI offers a **7-day no-questions-asked refund policy**. If you sign up for a paid plan and it doesn't work for your use case, contact support within 7 days and you'll get your money back.

**Does annual billing offer a discount?**
Yes — a flat **10% discount** applies automatically when you choose annual billing on any plan. No coupon code required.

---

## The Bottom Line

Getting a ScraperAPI free API key is about as frictionless as it gets: sign up with an email, land in the dashboard, copy the key, start scraping. The 5,000-credit trial gives you a real window to test the service against your actual targets — not a neutered demo.

The one thing to get clear on before you start: credits are not a 1:1 exchange with requests unless you're scraping plain HTML pages. Domain multipliers and feature parameters compound quickly. Run your specific targets through the dashboard's cost estimator during the trial period, and you'll know exactly which plan (if any) makes sense for what you're building.

For developers doing moderate-to-high volume scraping of mainstream sites — Amazon, Google, Zillow, Walmart — ScraperAPI is consistently one of the most recommended starting points in this space, and the free tier makes it genuinely easy to find out whether it works for you before spending anything.

👉 [Grab your free ScraperAPI API key — 5,000 trial credits, no credit card required](https://www.scraperapi.com/?fp_ref=coupons)
