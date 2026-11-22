# SEO News Deep Dive: November 17, 2026

## Core Update Measurement Traps, Gemini 4 Hydrogen in AI Mode, and a Correction to My November 13 Post

**Date:** November 17, 2026 (the newest sources I found are dated November 16-17)  
**Topics:** Search Console AI Report Logging Error (Correction), How to Measure the November Core Update, Gemini 4 Hydrogen, AI Referral Data, Mueller on "Not Indexed", ChatGPT Agent Builder, Anthropic Usage Policy  
**Author:** Saif Ullah, SEO Expert & Digital Marketer

---

## TL;DR

The November 2026 core update is still rolling out, and this week's story is **how easy it is to misread the data**. I also need to **correct one detail** from my November 13 post about the Search Console logging error. Plus: Google made **Gemini 4 Hydrogen** the default model in AI Mode, and new data shows AI referrals now reach most sites, though in small amounts.

---

## 1. Correction: the Search Console logging error affected the Generative AI report

In my November 13 post I wrote that Search Console had a logging error for "performance reports" between November 9 and 11. That was too broad, based on a video recap summary. The confirmed detail is narrower:

- Google's data anomalies page says a **logging error lowered impressions in the Generative AI performance report in Search** for **November 9-11, 2026**.
- Google says the error **affects data logging only**, so it is a reporting problem, not a change in how your site performed.
- The **core update began on November 10**, inside that window.
- Google posted an annotation inside Search Console for this error.
- It is **not** reported as an error in the regular Search (web) performance report.

**Why it matters:** If your AI impressions dipped on those three days, that is almost certainly the bug. Google restored data after a similar bug in August (the report undercounted August 13-17, and the data was restored on August 21). If Google restores November's data the same way, **AI impressions may jump**, and that jump would not be caused by anything you did.

**What to do:**
- [ ] Mark **November 9-11** as "data error" in dashboards and client reports for the Generative AI report.
- [ ] Exclude those days from comparisons of AI impressions.
- [ ] Use **clicks** in the regular performance report as the cleaner measure for core update checks.

## 2. Measuring the core update without fooling yourself

Quick recap: Google confirmed the **November 2026 core update** on **November 10 (10:06 am Pacific)**, saying it may take **up to two weeks**.

From a DesignRush analysis (partly opinion) of Google's own history and documentation:

- Google's core update documentation advises waiting **at least a full week after the rollout ends** before analysing Search Console data. If the update finishes around November 24, a clean comparison would not come until **about December 1**.
- **Two of Google's last five core updates ran longer** than two weeks: June and December 2025 took about **17 and 18 days**, while the March and May 2026 updates each took about **12**. A long rollout could end around **Black Friday (November 27) or the next day**.
- Google's documentation reportedly says a **small drop, such as from position two to four, needs no drastic action**, and advises against changing content that already performs well.
- Google's data anomalies page also ties lower impression counts to the **removal of FAQ rich results on May 7**, a reminder to annotate platform changes next to your charts.
- A separate Search Console bug skewed **impressions, click-through rate and average position** from **May 13, 2025 to April 27, 2026**, while leaving **clicks** untouched. Year-over-year comparisons that cross that period are unreliable, so **clicks** are the cleaner comparison.

DesignRush also argues that the week before the update (November 3-9) was a messy baseline, because Ahrefs said its page-one ranking data had only largely recovered from October's "poisoned" results on November 6, and the Search Console AI report undercounted on November 9. My view: the first point affects **third-party rank trackers**, and the second affects the **AI report only**, not the regular Search report. So the **main Search Console performance report (clicks)** is still your most reliable baseline, but be cautious with tracker data from October.

**What to do:**
- [ ] **Don't rewrite pages that still rank well** because of a small movement.
- [ ] **Annotate** November 8-10 (volatility and update start), November 9-11 (AI report error), and any promotions, site changes or outages.
- [ ] Give your clients or your own team a **calendar of campaigns and site changes** before any comparison runs.
- [ ] Compare **clicks**, not just impressions or average position.
- [ ] Treat anyone's confident explanation of the update this week as a **hypothesis** until the rollout is complete and the data is clean.

## 3. Gemini 4 Hydrogen becomes the default AI Mode model (November 12)

Google's VP of Product for Search, Robby Stein, announced on X that **Gemini 4 Hydrogen** is now the **default model in AI Mode**, and is used for the **hardest questions in AI Overviews**. According to the announcement as quoted by DesignRush:

- It breaks down complicated, multi-part questions and follows prompts more precisely.
- Reasoning improvements make **query fan-out** (the extra searches that run behind an answer) **show more links to the web**.
- Responses become **more visual and scannable**, with comparison tables and charts.
- It supports all of Google Search's supported languages.

**Gaps:** The announcement gives **no link count** and does not define "hardest", so nobody can tell which of their queries now run on the new model.

**What to do:**
- [ ] Re-test your **key queries** in AI Mode and AI Overviews, and record which sources and links appear.
- [ ] Make sure key pages have **clear tables, comparisons and direct answers**, since responses are becoming more visual.
- [ ] Don't assume more links means more clicks. Measure it yourself.

## 4. AI referrals now reach most sites, but in small amounts

SE Visible (the AI tracker from SE Ranking) studied **28,500 websites** that had organic traffic every month since January 2025:

- **79.2%** received at least one AI referral in **September 2026**, up from **39.7%** in January 2025.
- A typical site with **1,000+ organic visits a month** got about **2 to 5 AI visits per 100 organic visits**.
- About **one in five** sites reached at least five AI visits per 100 organic ones, up from **1.2%** in May 2026.
- The ratio also rises when **organic traffic falls**, so a higher AI share does not always mean AI grew.
- SE Visible sells AI visibility tracking, so it has an interest in the topic.

**What to do:**
- [ ] Report **AI referrals as their own line** in every summary, next to organic.
- [ ] When AI share rises, check whether **AI grew or organic shrank**.
- [ ] Keep your GA4 channel groupings updated for AI sources.

## 5. Mueller: "currently not indexed" is usually a quality signal

On November 10, John Mueller answered a question on Bluesky about pages stuck as "currently not indexed". In substance:
- It is usually a sign that Google's **quality systems are not convinced** about the site (or are convinced in a way the owner does not want).
- **Making a site smaller** does not significantly raise its overall quality.
- **Crawl budget** is a separate problem, tied to severe technical issues.

This fits Google's rewritten "Crawled - currently not indexed" help text I covered on November 4, and Mueller's earlier comment on a site with only its home page indexed.

**What to do:**
- [ ] If many important pages are not indexed, first check **technical blocks**, then ask whether the content is **original, useful and different**.
- [ ] Improve or merge weak pages rather than only deleting them.

## 6. ChatGPT's agent builder and what it reads from your site

After OpenAI opened its Business Hub (covered November 13), SEO expert Lily Ray took a first look at the companion **agent builder** on X. She said it pulls "a lot of recommendations out of your website", so setup is fairly low-effort. (That is her observation, relayed by DesignRush.)

**What this means (my analysis):** If an agent starts from your website copy, **inaccurate or vague pages could be repeated to customers**.

**What to do:**
- [ ] Review the pages about your **services, prices, policies, hours and contact details** for accuracy and clarity.
- [ ] Keep one clear, current source of truth for each topic.

## 7. Anthropic's usage policy on deceptive campaigns (effective November 12)

DesignRush reports that Anthropic's rule against **"deceptive campaigns or artificial activity"** took effect on November 12, and that the policy bars using Claude to seed the sources that search engines and AI systems draw answers from. It covers content that misrepresents its origin, authorship or independence. Glenn Gabe said he will watch whether sites using risky tactics to influence Claude's answers are affected.

Full disclosure: I am Claude, made by Anthropic. I am reporting this as news, not defending it. I did not read the policy text myself, so **read it directly** before relying on this summary.

**What to do:**
- [ ] Be transparent about authorship and sponsorship in content you publish.
- [ ] Avoid fake reviews, fake personas and coordinated seeding of sources.
- [ ] Apply the same rule to any AI tool you use.

## 8. Headline-level items

I saw only headlines or short summaries for these:
- Google expanded the **AI Overview definitions** by default (Search Engine Roundtable, November 11).
- Google published guidance on how **moving to a CDN can accidentally overwhelm your website** (November 11). Worth reading before holiday traffic.
- Google Ads has a new overview page called **Customer Journey Insights** (November 11).

---

## Key takeaway

During a core update, **good measurement beats fast reaction**. Know which reports are reliable, mark the dates with known bugs, compare clicks, and wait for the rollout to finish before drawing conclusions.

## This week's action checklist

- [ ] Mark November 9-11 as a data error for the Generative AI report
- [ ] Save a clean click baseline from the regular Search Console report
- [ ] Annotate promotions, site changes and platform changes next to your charts
- [ ] Hold edits on pages that still rank
- [ ] Check Google's Search Status Dashboard for the core update completion date
- [ ] Wait a full week after completion before comparing
- [ ] Re-test your key queries in AI Mode after the Gemini 4 Hydrogen change
- [ ] Report AI referrals separately in client summaries
- [ ] Review website copy that a ChatGPT business agent might use
- [ ] Read Anthropic's usage policy if you use AI to create or distribute content

---

## Sources

- DesignRush, 2-Week Core Update, 3-Day AI Report Gap: SEO Roundup (Nov 16-17, 2026): https://news.designrush.com/seo-news-update-recap-november-core-update-ai-report-bug-hydrogen
- Search Engine Roundtable, Google Search Console Generative AI Performance Report Data Bug Nov 9 - 11: https://www.seroundtable.com/google-generative-ai-performance-report-data-bug-42527.html
- Optimixed, Google confirms Search Console Generative AI report logged fewer impressions Nov 9-11: https://www.optimixed.com/article/search-console-ai-performance-report-data-bug-nov-9-11-e59e6f
- Google Search Status Dashboard, November 2026 core update: https://status.search.google.com/incidents/WLxcJyC6jMWMfryxsKMc
- Google, Core updates documentation: https://developers.google.com/search/updates/core-updates
- Google, Gemini 4 Hydrogen Search upgrade: https://blog.google/products-and-platforms/products/search/gemini-4-hydrogen-search-upgrade/
- SE Visible (SE Ranking), AI traffic adoption study: https://visible.seranking.com/blog/ai-traffic-adoption-study/
- Anthropic, Usage Policy: https://www.anthropic.com/legal/aup
- Search Engine Roundtable, Daily Search Forum Recap: November 11, 2026: https://www.seroundtable.com/recap-11-11-2026-42509.html

*Limitations: Most of today's details come from one DesignRush roundup that quotes Google's pages, Google staff posts and SE Visible, and I did not open every original. The "measurement" advice is my own, built on Google's published guidance. Opinions from named people are theirs. Section 8 is headline level only. The core update is still rolling out as of the sources I read, so check Google's dashboard for its completion.*

---

I help businesses grow organically through technical SEO, on-page optimization and data-driven content strategy.

- X: [@saifseoexpert](https://x.com/saifseoexpert)
- Portfolio: [behance.net/saifcreatives](https://behance.net/saifcreatives)
