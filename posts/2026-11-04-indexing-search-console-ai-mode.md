# SEO News Deep Dive: November 4, 2026

**Date:** November 4, 2026  
**Topics:** "Crawled - currently not indexed" Documentation Change, Only the Home Page Indexed, Search Console Click Spikes, AI Mode Tests, Click Data for AI Reports  
**Author:** Saif Ullah, SEO Expert & Digital Marketer

---

## TL;DR

The key theme this week is **indexing and data quality**. Google rewrote its help text for "Crawled - currently not indexed", John Mueller said a site with only its home page indexed may have a **general quality issue**, and some sites saw **strange click spikes** in Search Console that may be bot traffic or a bug. Plus, new signs that **click data for AI features is not coming** to Search Console soon.

---

## 1. Google rewrites "Crawled - currently not indexed" (November 3)

Search Engine Roundtable reported that Google updated the **Page indexing report** help page for this status.

**Old text (as quoted in the article):** the page was crawled but not indexed, it may or may not be indexed in future, and you do not need to resubmit it.

**New text (paraphrased):**
- Google crawled the page but did not index it.
- Google **does not index every page on the web**, so this is a **common message** for many sites and does not necessarily point to a problem.
- For **important pages**, use the **URL Inspection tool** and other tools to check for causes, such as having blocked the page from crawlers.
- If you have fully diagnosed your site and suspect a **site-wide indexing bug**, use Google's report-an-indexing-issue form.

Barry Schwartz points out that the new text **does not mention quality**, even though Google has linked this status to quality issues in the past.

**What to do:**
- [ ] Don't panic over a few pages in this status. It is normal for many sites.
- [ ] For **important** pages (services, products, key articles), run **URL Inspection**, then check for `noindex`, robots.txt blocks, canonical problems and thin or duplicate content.
- [ ] If the pages are weak, **improve them** (original information, clearer purpose, internal links) instead of resubmitting them repeatedly.
- [ ] Use the indexing issue form only after you have ruled out your own causes.

## 2. Only the home page indexed? It may be a quality issue (Mueller, November 3)

On Bluesky, an SEO described a client site that was hacked last year and cleaned up, but has been "in limbo" ever since, with **only the home page indexed** and no success getting Search Console to crawl or index internal pages.

John Mueller replied that, without more information, it was **impossible to say**. Off the cuff, he said it sounds like a **general quality issue that may be unrelated to the hack**, unless the hack was in place for many months. He added that the timing can make this hard to notice, for example when a hack and a core update happen together.

Barry Schwartz notes that other causes are possible, such as an incompletely cleaned hack or a technical issue.

**What to do if internal pages disappeared from the index:**
- [ ] Rule out technical causes first: `noindex` tags, robots.txt, canonicals, redirects, server errors and leftover hacked files or injected spam.
- [ ] Check **Manual Actions** and **Security issues** in Search Console.
- [ ] Review overall quality: is the content original, useful and different from competitors?
- [ ] Plan a **site-wide improvement**, not a quick fix, and expect recovery to take time.

## 3. Search Console performance reports show strange click spikes (November 3)

Search Engine Land first reported, and Search Engine Roundtable followed up, that the Search Console **Performance report** has shown **sudden spikes in clicks** for some sites over a couple of days. Key details:

- It is **not affecting all sites**, and it may be a **bug**.
- In one case, three sites showed a big spike through the **Search Console API**, but the **web interface** showed it for only one of them.
- Joy Hawkins saw it on three sites, noted that **impressions were flat** while clicks jumped, and said based on click-through-rate patterns that she is **fairly confident it is bot traffic**.
- Glenn Gabe said he sees it for some properties, not most, and that it very well could be a bug.
- One commenter reported about 5x clicks for the weekend and asked whether **rank trackers resolving Google's `goto` redirect parameters** could be responsible. The commenter said it did not translate into real traffic on the site. This is a **question, not a confirmed explanation**.
- Barry Schwartz said he contacted Google for comment. I found **no Google response** yet.

**What to do:**
- [ ] **Do not report these spikes to clients as growth.** Cross-check with Google Analytics and server logs first.
- [ ] Compare **clicks vs impressions**: a click spike with flat impressions is suspicious.
- [ ] Check your analytics for the **same dates (around October 31 to November 3)** to see whether real visits increased.
- [ ] Compare the Search Console **API vs the web interface** if you use dashboards.
- [ ] Annotate the dates and wait for Google's response before making any decisions.

## 4. AI Mode tests and the missing click data

- **AI Mode button test (November 3):** Google is reportedly testing **removing the AI Mode button from the search bar** for a small number of users. Len Raleigh spotted it in incognito mode in Chrome and noted it was still available in other sessions. Barry Schwartz could not replicate it and said Google often tests changes on small groups to compare performance. The button was added in May 2025.
- **Click data for AI reports:** On November 2, Search Engine Roundtable reported that Google's Gary Illyes implied **click and query data are likely not coming** to the AI performance report in Search Console. He said the team wants to provide "data that makes sense" without naming clicks or queries as that data. (I saw only the summary, not the full article.)
- **Reminder:** This is why independent tests like the one by Cyrus Shepard (my November 2 post), which estimated about 0.9% click-through on AI impressions, are getting attention. Remember that it was a small, single-site case study.
- **AI Mode and Google Flights (headline only):** A November 3 Search Engine Roundtable headline says AI Mode only shows links to Google Flights. I did not read the details.

**What to do:**
- [ ] Treat AI Mode button changes as **tests**, not rollouts.
- [ ] Track AI visibility with **brand searches, direct visits and leads**, since first-party click data may not arrive soon.

## 5. Reddit and Google traffic (headline only)

Search Engine Roundtable reported on November 2 that Reddit's stock dropped about a third after its CEO, Steve Huffman, **confirmed declining Google Search traffic** to the site. Different listings cite different drop sizes (33% to 36%), and I only read headlines and summaries.

I mention it because Reddit is one of the most frequently cited sources in Google's AI answers, so being cited and receiving traffic are **not the same thing**.

## 6. Where things stand

- Search Engine Roundtable's **November 2026 Google Webmaster Report** (November 2) says Google completed its **September 2026 spam update in October**, and that there were **several unconfirmed updates** while the industry waits for the **next core update**.
- SEO sites also list an **unconfirmed ranking update with a volatility and chatter spike**. I did not confirm the date.
- I could not open Google's live Search Status Dashboard today, so check it before telling a client an update has happened.

## 7. Headline-level items

- Google will turn off Google Search for **K-12 schools** and test a learning beta (November 3).
- Google Ads **Performance Max** campaigns may filter out navigational and brand queries (November 3).
- Google Ads strategists reportedly using AI-generated names and profile photos when contacting advertisers (November 2).

---

## Key takeaway

In a month of noisy data, the most reliable approach is to **diagnose before you react**: confirm indexing issues with URL Inspection, confirm traffic spikes with analytics and logs, and confirm updates on Google's dashboard.

## This week's action checklist

- [ ] Review "Crawled - currently not indexed" pages and fix only the important ones
- [ ] Check whether any site section has disappeared from Google's index
- [ ] Cross-check any Search Console click spike with Analytics and server logs
- [ ] Don't report anomalous Search Console numbers to clients until verified
- [ ] Keep annotations for Oct 31 to Nov 3 in analytics
- [ ] Track brand searches, direct traffic and leads alongside clicks
- [ ] Re-check Google's Search Status Dashboard for confirmed updates
- [ ] Keep WordPress and PHP updated

---

## Sources

- Search Engine Roundtable, Google Updates Crawled - Currently Not Indexed Details (Nov 3, 2026): https://www.seroundtable.com/google-updates-crawled-currently-not-indexed-42450.html
- Search Engine Roundtable, Only Home Page Indexed? Might Be A Google Search Quality Issue (Nov 3, 2026): https://www.seroundtable.com/google-quality-issues-home-page-indexed-42439.html
- Search Engine Roundtable, Google Performance Reports Showing Weird Spike In Clicks For Some Sites (Nov 3, 2026): https://www.seroundtable.com/google-performance-reports-spike-clicks-42448.html
- Search Engine Land, Search Console spikes in clicks (Nov 3, 2026): https://searchengineland.com/google-search-console-is-showing-some-huge-spikes-in-clicks-in-the-performance-report-500474
- Search Engine Roundtable, Google Tests Removing AI Mode Button From Search Bar (Nov 3, 2026): https://www.seroundtable.com/google-removing-ai-mode-42436.html
- Search Engine Roundtable, Daily Search Forum Recap: November 3, 2026: https://www.seroundtable.com/recap-11-03-2026-42442.html
- Search Engine Roundtable, Daily Search Forum Recap: November 2, 2026: https://www.seroundtable.com/recap-11-02-2026-42434.html
- Search Engine Roundtable, home page (November 2026 Google Webmaster Report, Reddit and Illyes headlines): https://www.seroundtable.com/

*Limitations: Sections 1-3 and the AI Mode button item are based on articles I read in full. The Illyes comment, Reddit item, Google Flights item and section 7 are headline or summary level only. The click spike has no explanation from Google yet, and the bot-traffic and goto-redirect ideas are community speculation. Statements from named SEOs are their own views.*

---

I help businesses grow organically through technical SEO, on-page optimization and data-driven content strategy.

- X: [@saifseoexpert](https://x.com/saifseoexpert)
- Portfolio: [behance.net/saifcreatives](https://behance.net/saifcreatives)
