# SEO News Deep Dive: October 19, 2026

**Date:** October 19, 2026  
**Topics:** Ranking Volatility, AI Mode & AI Overviews Links, ChatGPT UTM Tracking Bug, Indexing API, Programmatic SEO, Bing AI Reports  
**Author:** Saif Ullah, SEO Expert & Digital Marketer

---

## TL;DR

Three things matter this week. (1) Google rankings got shaky again on October 15-16, with no confirmed update. (2) Google is pushing more links into AI Mode and AI Overviews. (3) Your ChatGPT traffic in analytics may have "dropped" because of a tracking change, not because people stopped clicking. **Check before you panic.**

---

## 1. Ranking volatility and chatter spike (October 15-16)

On October 16, Barry Schwartz of Search Engine Roundtable reported a spike in volatility and in SEO community chatter over the previous 24 hours. Some tracking tools showed movement, and forum members reported traffic and ranking changes.

Context:
- The September 2026 spam update started on **September 24** and finished on **October 8**.
- As of mid-October, Google has **not announced** an October 2026 core update.
- This is **unconfirmed volatility**, not a named update.

A counterpoint: one forum member who checked stats across 100+ Search Console properties on October 18 saw the group down only about 0.5-1% with no major outliers. That is anecdotal, but it shows impact varies by site.

**What to do:** Do not make big changes yet. Annotate October 15-16 in your analytics and compare before/after for 7-14 days.

## 2. Google adds more links to AI Mode and AI Overviews

Announced on **October 15**, Google is changing how links appear in its AI search experiences:

- Inline links will appear **higher in responses, more frequently**, with context on why each link is useful.
- Google is testing a section at the top of AI Mode responses for the "one or two" official websites where a user can complete a task or find exact information.
- The "Dive deeper" section gets image thumbnails and a more clickable design.
- Timely article carousels and Preferred Sources expand to more regions and languages. Google says Preferred Sources usage has grown 7x.
- Google is testing clickable creator and publisher names on videos in AI Mode. These go to Google's own Search profile page first.
- Links from a user's news subscriptions will be labeled.

Barry Schwartz notes that Google still does not give click data for these links in the AI performance reports.

**What to do:** Make your site the clear "official source" for what you do: strong brand pages, clear service pages, an author/creator profile, and a trustworthy About page. Ask your audience to add you as a Preferred Source where relevant.

## 3. ChatGPT traffic "drop": probably a tracking problem

If your ChatGPT referral traffic fell around **October 9**, read this before reacting.

- After the GPT-6 rollout, links in ChatGPT answers appear to arrive **without the `utm_source=chatgpt.com` tag and without a referrer**. Analytics then files those visits under **Direct**.
- Adobe's Cedric Huesler checked about 500 pages where ChatGPT drove 5%+ of visits (Oct 9-13 vs the week before): ChatGPT visits fell about 31,000 per day, while **Direct rose about 26,000 per day**. Search fell 7%, similar to elsewhere. Direct rose on two in three pages that lost ChatGPT traffic.
- Search Engine Journal reports GA4 ChatGPT sessions fell **22% to 57%** in datasets analysed by Graphite, and analysts tie it to the missing tags.
- Evertune reports that ChatGPT told Huesler it was a **bug with a fix coming**. OpenAI has not publicly commented, so treat this as **unconfirmed**.
- Caveat: several of the firms publishing these analyses sell AI-search tools.

**What to do:**
- [ ] Annotate October 8-10 in GA4.
- [ ] Compare Direct vs ChatGPT sessions on your former top ChatGPT landing pages.
- [ ] Add a "How did you hear about us?" field to forms.
- [ ] Do not change your AI visibility strategy based on this one metric.

## 4. Google's Indexing API docs no longer explain how to get approval

Per Search Engine Journal (October 17), Google removed the Indexing API approval form and steps from its documentation. The API has long been officially intended for specific content types such as job postings and livestream pages.

**What to do:** Do not build your indexing strategy around it. Keep clean XML sitemaps, strong internal links and fast, crawlable pages.

## 5. Programmatic SEO: Google can lose trust in the whole site

Search Engine Roundtable's October report highlights Google saying it can lose faith in a site that publishes low-value programmatic pages. This matches the wider spam-update and scaled-content message.

**What to do:** Audit templated pages. Merge, improve or remove pages that add nothing beyond swapping a keyword or city name.

## 6. Bing adds Topics Portfolio to its AI reports

On **October 13**, Bing Webmaster Tools added a Topics Portfolio to its AI reports. If you already use Bing Webmaster Tools, it is worth checking what topics Bing associates with your site.

---

## Key takeaway

The pattern: **measurement is getting harder, while AI answers are showing more links.** Smart SEOs will track more than clicks: brand searches, direct traffic, citations, leads and "how did you hear about us" answers.

## This week's action checklist

- [ ] Annotate Oct 8-10 (ChatGPT tracking change) and Oct 15-16 (volatility) in analytics
- [ ] Compare Direct vs ChatGPT sessions on top AI-referred pages
- [ ] Check rankings and traffic over 7-14 days before changing anything
- [ ] Strengthen brand, About and author pages (be the "official source")
- [ ] Audit programmatic or templated pages
- [ ] Review Search Console Manual Actions
- [ ] Check Bing Webmaster Tools AI reports

---

## Sources

- Search Engine Roundtable, ranking volatility and chatter (Oct 16, 2026): https://seroundtable.com/google-search-ranking-volatility-chatter-42317.html
- Search Engine Roundtable, Google updates links in AI Mode & AI Overviews: https://seroundtable.com/google-updates-links-in-ai-mode-and-ai-overviews-again-42308.html
- Search Engine Land, AI Mode and AI Overview link updates: https://searchengineland.com/google-updates-ai-mode-and-ai-overview-with-more-links-context-carousels-and-information-on-creators-496242
- 9to5Google, AI Mode and AI Overview updates (Oct 15, 2026): https://9to5google.com/2026/10/15/google-ai-mode-overviews-links/
- Search Engine Roundtable, OpenAI drops UTM parameters (Oct 14, 2026): https://seroundtable.com/utm-parameters-missing-chatgpt-42299.html
- Search Engine Journal, ChatGPT traffic drop appears to be a tracking problem: https://www.searchenginejournal.com/chatgpt-traffic-drop-appears-to-be-a-tracking-problem/593157/
- Evertune, The Week Without ChatGPT Attribution: https://www.evertune.ai/resources/insights-on-ai/the-week-without-chatgpt-attribution
- Search Engine Journal, latest SEO articles (Indexing API docs, Oct 17, 2026): https://www.searchenginejournal.com/category/seo/
- Search Engine Roundtable, October 2026 Google Webmaster Report: https://www.seroundtable.com/october-2026-google-webmaster-report-42185.html

*Figures are quoted from the cited reports. Unconfirmed items and anecdotal observations are labelled as such.*

---

I help businesses grow organically through technical SEO, on-page optimization and data-driven content strategy.

- X: [@saifseoexpert](https://x.com/saifseoexpert)
- Portfolio: [behance.net/saifcreatives](https://behance.net/saifcreatives)
