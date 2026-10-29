# SEO News Deep Dive: October 28, 2026

**Date:** October 28, 2026  
**Topics:** Rank Tracker Data Follow-Up (What Vendors Say), AI Recommendations vs Citations, Branded AI Overviews, ChatGPT-User and robots.txt, Alphabet Earnings Today  
**Author:** Saif Ullah, SEO Expert & Digital Marketer

---

## TL;DR

Two useful reads this week. First, rank tracking vendors have now given their side of the "poisoned SERPs" story, and **their numbers differ a lot**, so how you report rankings matters. Second, new AI search data suggests that **being recommended by AI is worth far more than being a small footnote link**. I also flag one event to watch today: Alphabet's quarterly earnings.

---

## 1. Rank tracker data: what the vendors now say

In my October 21 post I covered Nozzle's finding that Google has been serving rank trackers results pages with swapped listings. Since then, Search Engine Roundtable's report has been updated with statements from other vendors, and PPC Land summarised them on October 19. Here is how they compare.

| Source | What it reports |
|---|---|
| **Nozzle** | 8.0% of pages collected since Sept 13 were poisoned (0.17% before). Peak of about 27% around Sept 29. Tracked sites missing from the top 10 on **58.6%** of poisoned pages. |
| **AccuRanker** | Far lower rates in its own sample: **1.4% on Sept 29** (when Nozzle saw 27%), and about **1.47% from Oct 1-9**. It says Google tightened detection again on Oct 15, mostly on mobile (2.55% on Oct 16, falling to 0.47% on Oct 17). |
| **Semrush** | Says it has seen the issue since late summer, added extra checks, and that the effect on users' tracked rankings has been "limited", mostly beyond page one. |
| **SISTRIX** | Says it publishes only results that pass quality checks, recollects failures, has disabled on-demand updates since September, and now concentrates on the **top 10**. |
| **DemandSphere** | Reported spurious results on roughly 11% of its daily checks. |

**Why the numbers differ so much:** According to AccuRanker, the rate depends on how a vendor's requests look to Google, not on which keywords you track. The vendors also use different tests, so **the rates cannot be compared directly** and none has been independently audited.

Other details from the reporting:
- Poisoned pages were usually brief. Nozzle says 80% of spells lasted a single collection, and on most affected pages the usual sites returned within three days.
- Replacement results leaned toward **Reddit, Facebook, LinkedIn, Instagram and Quora** (Reddit's share of top-10 appearances rose from 20.8% to 28.8% on poisoned pages).
- Barry Schwartz's view is that Google is probably targeting AI bots and scrapers, not SEO tools. That is his assumption, and **Google has not commented**.
- Search Engine Watch added a related headline on October 26 saying AccuRanker separates suspect results from the data that reached customer reports. I only saw the headline.

**What to do (agencies and freelancers):**
- [ ] Ask each tool vendor how they detect and filter swapped results, and whether they publish error or sampling rates.
- [ ] Before reporting a ranking drop, **confirm it in Search Console** (impressions, clicks, average position for the same page and dates).
- [ ] Focus client reports on the **top 10** and on trends over weeks, not single-day changes.
- [ ] Report business results (leads, calls, sales) next to rankings.
- [ ] Add a note to reports covering **Sept 13 to mid-October 2026**: "Third-party ranking data may include collection errors."
- [ ] Remember Search Console limits: it only covers sites you own, and the AI report shows impressions without clicks or queries.

## 2. AI search: being recommended beats being cited

Similarweb's October AI search update (October 21) pulls together several data points. Several of its figures come from other vendors' studies, which I could not check, so treat them as **indicative, not proven**.

- **Recommendation vs footnote:** The report says being the **#1 recommended brand** in a transactional ChatGPT answer drives a **10.3%-14.6%** direct click rate, while ordinary footnote-style citations average about **2.3%**. It also says branded follow-up searches in classic search engines outnumbered direct clicks at every position, suggesting people use AI answers to vet brands first.
- **Branded AI Overviews:** The report says AI Overviews on branded queries roughly **tripled** over the past month, and that Position #1 organic clicks fell by over 40% while the traffic that remains converts about **23% higher**. (Consistent with the 80%+ AI Overview figures I covered on October 27, though definitions differ.)
- **Perplexity:** The report cites citation click rates of 18%-22%, from a third-party source.
- **ChatGPT-User and robots.txt:** OpenAI's bot documentation, as summarised by Similarweb, says OAI-SearchBot respects robots.txt for indexing, while **ChatGPT-User** fetches a page live when a user pastes a link into a chat, so it may not follow robots.txt rules. This matches the point from my October 25 draft that robots.txt controls crawling, not every kind of access.
- **GA4 attribution:** Similarweb repeats that ChatGPT traffic can arrive without UTM tags and recommends updating your **channel groupings** to capture untagged AI referrals.

**What this means:** Citations alone will not carry your brand. What helps is being **mentioned and recommended** across the web: reviews, comparison articles, digital PR, credible profiles and clear brand information.

**What to do:**
- [ ] Search your brand and services in Google (AI Overview) and ChatGPT, and note whether you are **recommended**, only cited, or missing.
- [ ] Check that the AI Overview for your **brand name** shows accurate information (services, location, reviews).
- [ ] Strengthen third-party proof: Google Business Profile, reviews, directories, LinkedIn and relevant listicles.
- [ ] Put the **direct answer** in the first sentences under each H2 heading, so AI systems can extract it.
- [ ] Update GA4 channel groupings for AI referrers, and add a "How did you hear about us?" form field.

## 3. Event to watch today: Alphabet Q3 earnings

Alphabet is scheduled to report third-quarter results **today, October 28, after the market closes**. Investors will watch Search growth, Gemini adoption and AI spending. **I do not have the results yet**, so I'm not reporting any numbers. SEOs should watch for any comments on AI Overviews, AI Mode and ads, since those often signal product direction.

---

## Key takeaway

**Measure carefully, and build real reputation.** Ranking data has been noisy for a month, and AI answers reward brands that are recommended across the web. Cross-check numbers, report business results, and invest in proof that other sites and customers vouch for you.

## This week's action checklist

- [ ] Cross-check any ranking drop in Search Console before reporting it
- [ ] Add a data-quality note to client reports covering Sept 13 to mid-October
- [ ] Review your brand's AI Overview and ChatGPT answer for accuracy
- [ ] Build third-party proof (reviews, listings, mentions)
- [ ] Update GA4 channel groupings for AI referrals
- [ ] Re-check the Google Search Status Dashboard for any confirmed update
- [ ] Read Alphabet's earnings commentary on Search and AI tomorrow

---

## Sources

- PPC Land, Google feeds rank trackers swapped results on 8% of pages, Nozzle finds (Oct 19, 2026), which summarises Search Engine Roundtable and vendor statements: https://ppc.land/google-feeds-rank-trackers-swapped-results-on-8-of-pages-nozzle-finds/
- Search Engine Roundtable, third-party Google rank tracking broken (Oct 12, 2026, updated): https://www.seroundtable.com/third-party-google-rank-tracking-broken-42272.html
- Search Engine Watch, Is a Google October 2026 update rolling out? (with Oct 26 AccuRanker headline): https://searchenginewatch.com/google-october-2026-update-rumors/
- Similarweb, AI Search News: October 2026 (Oct 21, 2026): https://www.similarweb.com/blog/insights/ai-news/ai-search-news-update/
- Search Engine Roundtable, Over 80% Of Google Searches Have AI Overviews & Growing (Oct 26, 2026): https://www.seroundtable.com/over-80-of-google-searches-have-ai-overviews-42372.html
- Yahoo Finance, Alphabet Q3 earnings preview: https://finance.yahoo.com/markets/stocks/articles/dear-google-stock-fans-mark-163952649.html

*Limitations: The rank tracker section is a follow-up and mostly draws on reporting from October 12-19. Vendor figures use different methods and are not independently audited. Similarweb's recommendation and CTR figures come from other studies that I did not open, and Similarweb sells AI search tools. Alphabet's results were not available when I wrote this.*

---

I help businesses grow organically through technical SEO, on-page optimization and data-driven content strategy.

- X: [@saifseoexpert](https://x.com/saifseoexpert)
- Portfolio: [behance.net/saifcreatives](https://behance.net/saifcreatives)
