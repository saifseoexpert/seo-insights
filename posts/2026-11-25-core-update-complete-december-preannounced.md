# SEO News Deep Dive: November 25, 2026

## Google Finishes the November Core Update, Then Preannounces December's for the First Time

**Date:** November 25, 2026  
**Topics:** November 2026 Core Update Completed, December 2026 Core Update Preannounced, New Search Ranking Hub, How AI Overviews Choose Links, Links Moving Down in AI Overviews, Search Profiles Going Global  
**Author:** Saif Ullah, SEO Expert & Digital Marketer

---

## TL;DR

On **Tuesday, November 24**, Google did two big things within about an hour: it marked the **November 2026 core update as complete**, and it **preannounced a December 2026 core update**, the first time Google has ever flagged a core update in advance. That leaves a short window between two broad updates, with Black Friday and Cyber Monday in the middle. Details below, plus a catch-up on the week's other news.

*Note: my last post was dated November 17. This one covers November 18-25, including items I only know from headlines.*

---

## 1. The November 2026 core update is complete

- It started on **November 10** and finished on **November 24**, so it ran about **14 days**, in line with Google's "up to two weeks" estimate and a little longer than the March and May 2026 updates (about 12 days each).
- Several outlets report Google posted the completion note on its Search Status Dashboard on the morning of November 24, just ahead of Black Friday.
- Search Engine Roundtable had noted that chatter about this update was quieter than usual, with some tools and forums rising on Saturday, November 14. That is a second-hand description, so don't treat it as a measure of impact.

**What to do now (Google's own guidance):**
- [ ] **Wait at least one full week after completion** before analysing Search Console, then compare that week with the **week before the rollout began** (before November 10). By my reading, that points to analysis from about **December 1**.
- [ ] Compare **clicks** first. Remember the data problems from earlier this month: the Generative AI report logging error on **November 9-11**, and the odd click spikes some sites saw in the Performance report (Joy Hawkins reported she was still seeing suspicious click data on November 18).
- [ ] Look for patterns by **page type and topic**, not just totals.
- [ ] Note that holiday demand will distort everything. Compare against last year's equivalent days as well.

## 2. Google preannounces the December 2026 core update (first time ever)

From Google's Search Status Dashboard wording, as quoted by Search Engine Journal, and reporting from Search Engine Roundtable, Search Engine Watch and PPC Land:

- Google said the update **"is scheduled to be released in December 2026"** and that it brings improvements to how its systems **understand and rank relevant content, including for longer and more complex questions**, and **better personalised results for people who have personalisation turned on**.
- It applies to **all locations and languages**, and Google says its **general core update guidance applies**.
- There is **no start date**. For a short while the dashboard entry looked as if the update was active, which caused alarm. A Google spokesperson told Barry Schwartz that Google would announce it **on the day it starts**, as usual, and that it is **not imminent**. Search Engine Roundtable said Google confirmed three times that it is not live.
- **Why now:** Google tied the advance notice to the UK **Competition and Markets Authority's fair ranking requirement**. According to PPC Land, the CMA imposed it on **June 17, 2026**, and Google must comply by **December 17**. The rules call for **30 business days' notice for actionable changes** and **15 business days for significant ones**. Google says it will now give notice when updates bring actionable policy requirements or could cause broad ranking shifts that UK users would see.
- **Context:** Google had said for years that core updates could not be flagged ahead of time. In December 2025, John Mueller said so explicitly.
- Search Engine Journal points out that sites still reviewing November's results can expect **another core update within weeks** of the last one ending.
- Marie Haynes read the announcements as a warning that "there are going to be some big ranking changes soon" (her opinion, per PPC Land).

**What to do:**
- [ ] **Record a clean baseline now.** Save Search Console clicks and impressions for the weeks before and after the November update, with notes on holidays and campaigns.
- [ ] **Don't treat November and December as one event.** When the December update starts, annotate it separately.
- [ ] Review your key pages for **longer, multi-part questions**: do they answer what a real customer would ask, in plain language, with specifics? (My suggestion based on Google's stated focus. Google has not said what will change.)
- [ ] **Avoid big site changes** during the holiday peak and the December rollout, if you can.
- [ ] Check the dashboard and Google's new ranking hub (next section) for the start date.

## 3. A new Search ranking hub, principles and feedback channel

Also on November 24, Google opened a **ranking hub** on Search Central. Per Search Engine Roundtable and PPC Land:

- It collects information on **ranking systems, notice timelines, dashboard updates and structured feedback**, and Google will use it to preannounce updates, starting with December's.
- A **feedback section** lets site owners report problems with a specific update using **hashtags assigned in the dashboard**. Google says this helps engineers spot possible systemic issues, and stresses it is **not a manual appeal route for individual sites**.
- A **principles page** sets out three commitments: users come first, ranking systems are consistent across all result types, and standards are upheld through rigorous testing. It states that Google does **not make manual adjustments to alter rankings except to comply with legal obligations**. PPC Land notes the page does not explain how "usefulness" is measured.
- Google also rewrote its **Google-Extended** documentation. It says **nothing changes in how it honours Google-Extended**, that using it **does not exclude sites from Search results**, and that it is **not a ranking signal**. New Help Center explainers separate **AI training from grounding**. This ties in with the shared AI training control I covered on November 2.

**What to do:**
- [ ] Bookmark the ranking hub and use it to check for notices.
- [ ] If you see a clear problem after a future update, use the feedback channel with the dashboard hashtag, but don't expect a reply.
- [ ] Revisit your **robots.txt AI crawler policy** in light of the Google-Extended clarification.

## 4. How AI Overviews and AI Mode pick their links

Google published "Attribution and factuality in Search generative AI features". According to Search Engine Roundtable's walkthrough:

- The process starts with **ordinary Search**: Google checks top-ranked results from its index for relevance and passes snippets to the model.
- The model may run related searches (**query fan-out**), write a response grounded in what it found, then link to sources that **support** the answer (**corroboration**).
- Links appear as **inline icons, grouped source cards or expandable carousels**, chosen to balance relevance, quality, layout and variety of sources.
- Topics that could affect **health, money or safety** face a higher bar, and Google may **decline to answer** if there is no reliable consensus, for example breaking news.
- Claims are checked against **web results, data feeds and the Knowledge Graph**.
- Google says these AI features are **integrated directly with its core ranking and quality systems**. Barry Schwartz noted the Gemini 4 Hydrogen update and the November core update overlapped, and suggested that with such integration, updates "probably should not overlap" (his opinion).
- **Best practices** named: pages that are **indexable and eligible for snippets**, **clear sourcing**, **author and About pages**, and **avoiding artificial date refreshes**. Site owners are told to watch the **Generative AI report** in Search Console.

**What to do:**
- [ ] Make key pages **indexable, snippet-eligible and clearly sourced**, with named authors and a solid About page.
- [ ] Don't change dates without changing content.
- [ ] For health, finance and legal topics, add **expert review and cited sources**.

## 5. Links are moving down inside AI Overviews (one vendor's data)

Peec AI's David Konitzny tracked where the **first inline link** appears in AI Overviews. His figures:
- **September 21:** 76.8% of AI Overviews had their first inline link in the **first third** of the answer.
- **November 20:** **51.8%**. That is a decline of about **25 percentage points in two months**, with drops around **October 9 and October 30**.

These are **one vendor's own numbers**, Peec AI sells AI tracking, and the article carried **no Google response**. Barry Schwartz called the trend surprising given Google's recent talk about valuing links.

**What this means:** Being cited is not the same as being seen. Measure **clicks and brand searches**, not citations alone.

## 6. Google Search Profiles appear to be rolling out globally

Search Engine Roundtable reports that Google appears to have rolled out **Search Profiles globally**, without an announcement. People outside the **United States, Canada and India** can now reportedly claim a profile **without using a VPN**.

This updates what I wrote on October 26 and November 6, when I said availability might be limited by region.

**What to do:**
- [ ] Check whether you or your brand can now claim a Search profile, and read the **current eligibility rules** (earlier reports mentioned a follower threshold across platforms such as YouTube, Instagram, X and TikTok).
- [ ] Keep your **name, bio and links consistent** across LinkedIn, your website and other profiles.

## 7. Other items from November 18-23 (headline or summary level)

I saw only headlines or short summaries for these (Search Engine Roundtable recaps for November 18, 19, 20 and 23):
- **Google** is rolling out a **collapsible sidebar** on desktop Search to promote AI search.
- **Google tests sign-in protections after the first search** to block scrapers, which fits the AI Mode "continue" prompt I covered on November 7.
- **Bing** confirmed ads in AI Mode and AI Overviews, and both **Bing and ChatGPT are testing web-only link results**.
- An **FBI alert on SEO poisoning** was covered in the November 20 video recap. I did not read the details, so check the original before acting.
- **Search Console's API** gained branded query, multimodal and country/device filters.
- **Google discontinued its Data Feed validation tool** (Merchant Center). If you manage feeds, check Merchant Center diagnostics for alternatives.
- **Google tests hotel booking in Search** via a "Continue on Google" button in AI Mode, and image search results now have a **Lens button** that leads into AI Overview or AI Mode follow-ups.
- **AI Mode** dropped the Gemini model label and rolled **Gemini 4 Carbon** out to Pro subscribers. Google is also testing **more visible AI Overview citation cards**.
- **ChatGPT Business Hub** can now be connected with a **ChatGPT ad account** (November 23).

---

## Key takeaway

The pattern is **more transparency from Google, but also more change on the way**. Use the quiet window to build a clean baseline, make your best pages genuinely helpful for longer, multi-part questions, and avoid reacting to partial data.

## This week's action checklist

- [ ] Save a baseline: Search Console clicks for the week before November 10 and the weeks after November 24
- [ ] Annotate November 8-10 (volatility and start), November 9-11 (AI report logging error) and November 24 (completion)
- [ ] Wait until about December 1 before judging the November update
- [ ] Prepare to annotate the December start date separately
- [ ] Improve key pages for longer, multi-part questions, with clear sourcing and named authors
- [ ] Review robots.txt AI crawler rules after the Google-Extended clarification
- [ ] Check Search Profile availability
- [ ] Check Merchant Center diagnostics after the Data Feed validation tool change
- [ ] Avoid risky site changes during the holiday peak

---

## Sources

- PPC Land, Google preannounces a December core update as AI Overview links slide down (Nov 25, 2026): https://ppc.land/google-preannounces-a-december-core-update-as-ai-overview-links-slide-down/
- Search Engine Journal, Google Announces December 2026 Core Update Ahead Of Rollout: https://www.searchenginejournal.com/google-december-2026-core-update/598760/
- Search Engine Watch, Google preannounces December 2026 core update: https://searchenginewatch.com/oogle-preannounces-december-2026-core-update/
- Search Engine Roundtable, Google December 2026 Core Update Preannounced: https://www.seroundtable.com/google-december-2026-core-update-42615.html
- Search Engine Roundtable, Google Search ranking hub and principles: https://www.seroundtable.com/google-search-ranking-hub-42616.html
- Search Engine Roundtable, How AI Overviews and AI Mode select links: https://www.seroundtable.com/google-ai-overviews-ai-mode-link-selection-42617.html
- Search Engine Roundtable, Google pushing links down in AI Overviews: https://www.seroundtable.com/google-pushing-links-in-ai-overviews-down-42600.html
- Search Engine Roundtable, Google Search Profiles rolling out globally: https://www.seroundtable.com/google-search-profiles-global-42591.html
- Relevant Audience, Google December 2026 core update preannounced: https://www.relevantaudience.com/seo/google-december-2026-core-update-preannounced/
- Search Engine Roundtable, Daily Search Forum Recaps (Nov 18, 19, 20): https://www.seroundtable.com/recap-11-20-2026-42583.html
- Search Engine Roundtable, video recap (Nov 20, 2026): https://www.seroundtable.com/video-11-20-2026-42577.html

*Limitations: Most details come from PPC Land's long summary of Search Engine Roundtable and Google material, plus Search Engine Journal and Search Engine Watch, and I did not open every original or Google's own pages. The November core update completion is reported by multiple outlets, but I did not read Search Engine Roundtable's "what happened" analysis. Peec AI's figures are one vendor's data. Section 7 is headline or summary level. Opinions from named people are theirs. Advice marked as mine is not from Google.*

---

I help businesses grow organically through technical SEO, on-page optimization and data-driven content strategy.

- X: [@saifseoexpert](https://x.com/saifseoexpert)
- Portfolio: [behance.net/saifcreatives](https://behance.net/saifcreatives)
