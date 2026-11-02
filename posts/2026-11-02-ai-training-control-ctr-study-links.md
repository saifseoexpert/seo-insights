# SEO News Deep Dive: November 2, 2026

**Date:** November 2, 2026  
**Topics:** Google's New AI Training Control (AIPREF), The 0.9% AI Click-Through Rate Opt-Out Study, Mueller on Spammy Links, Ads Inside AI Answers  
**Author:** Saif Ullah, SEO Expert & Digital Marketer

---

## TL;DR

Three stories from the last few days matter for site owners. (1) Google, Microsoft Bing and other AI providers are moving toward **one shared robots.txt signal** for AI training preferences, with Google planning to support it in **early 2027**. (2) A small experiment suggests clicks from **AI Overviews and AI Mode are about 0.9%**, and that **opting out of Google's AI features may also reduce regular organic clicks**. (3) John Mueller repeated that you can **ignore random spammy links**, even if tools like Semrush show them and Search Console does not.

---

## 1. Google adopts a shared AI training control (announced October 30)

Per Search Engine Roundtable (Barry Schwartz) and Google's announcement:

- Google plans to **voluntarily adopt** a proposal being discussed at the **IETF** (the internet standards body), created by its **AIPREF** working group. It would let websites express **AI training preferences across several AI providers in one step**, instead of listing each company's crawler separately.
- The signal goes in **robots.txt** as a shared "policy token". Google's note says it intends to support it, using `user-agent: __usage_ai-training`, in **early 2027**. It is a **work in progress**, not live yet.
- Barry reports that **Bing, OpenAI and Anthropic** have also announced plans to adopt the same idea.
- Per John Mueller: if a site uses the token to **opt out of training** and does not mention `Google-Extended`, Google plans to treat that **as if the publisher had disallowed Google-Extended**.
- **Existing controls keep working** alongside the new one. Sites that **explicitly allow Google-Extended** remain eligible to appear in Gemini Apps responses and receive clicks through grounding.
- Google also has the separate **Search Console opt-out** for Search generative AI features (AI Overviews and AI Mode). The new training control is **not the same thing**.
- Nate Hake, who takes part in the IETF group, noted it is **not finalised at the IETF level** and that significant areas of dispute remain. He is, for example, unhappy that the current draft largely exempts actions a user takes. Treat it as a proposal still being negotiated.

**What to do:**
- [ ] **Don't change anything yet.** Nothing is live until 2027.
- [ ] Decide your policy: do you allow AI training on your content, none of it, or only some sections?
- [ ] Review your current `robots.txt` for AI crawlers and note what you have already blocked (for example `Google-Extended`).
- [ ] Remember the difference: **training controls** (robots.txt, future token), **Search AI features** (Search Console opt-out), and **indexing** (`noindex`) are three separate things.
- [ ] Keep a note of this for 2027 so you can add the shared token when providers support it.

## 2. Small study: AI Overviews and AI Mode click-through rate is about 0.9%

On October 30, Search Engine Roundtable covered a **small case study** by SEO Cyrus Shepard. He used Google's Search generative AI opt-out control on one site to compare performance **with and without** its appearance in AI Overviews and AI Mode. His reported findings:

- The estimated click-through rate on **AI impressions was about 0.9%**.
- AI impressions were about **8% of the site's total impressions**.
- When AI features were switched off, **AI impressions dropped to zero immediately**.
- Unexpectedly, **regular organic clicks also dropped** during the experiment. Shepard suggests a **"SERP halo effect"**: the more places your brand appears on a results page, the more likely a user clicks at least one.
- Site-wide average position actually rose during the test (new posts and brand searches), but individual URLs with the most AI visibility dipped and then recovered when AI visibility was switched back on.
- Greg Sterling of Near Media commented that his team's research suggests AI Overviews can create **brand lift** that leads to later searches and clicks, though not consistently.

**Important caveats (Barry Schwartz notes several):**
- This is **one site and a small sample**, not a general rule.
- AI Overviews still appeared on the results pages during the test. The site just did not appear **in** them. So it is not a comparison of results pages with and without AI Overviews.
- The 0.9% figure was **estimated** by subtracting known AI impressions from overall site CTR and impressions.
- Barry also notes that few people dare to run an opt-out test, so there is little other data to compare.

**What to do:**
- [ ] **Do not opt out of Google's AI features in a panic.** This test suggests it could cost organic clicks too, but one case is not proof.
- [ ] If you are curious, use Search Console's AI performance reporting to look at impressions and clicks for AI features on your own site.
- [ ] Judge AI visibility by **brand searches, direct visits and leads**, not clicks alone.

## 3. John Mueller: you can ignore random spammy links

On October 29, Search Engine Roundtable reported that Google does not show all links in the Search Console **Links report**, including all spammy ones. Google has long said the report shows only a **sample** of links.

A site owner on Reddit asked whether to worry because Semrush showed daily spammy links that Search Console did not. John Mueller replied that he would not base the decision on whether Search Console shows them, and that if they are **random spammy links on the web, ignoring them** is the right move.

Background from the same article:
- Not appearing in Search Console does **not** mean Google doesn't know about them.
- Google has said it **does not notify sites about spammy links**, because it ignores them.
- Since **Penguin 4.0**, Google devalues bad links instead of demoting the pages they point to.
- Google has repeatedly advised against **toxic-link reports** and against **disavowing based on third-party scores**.

**What to do:**
- [ ] Don't pay for "toxic link cleanup" or disavow services just because a tool shows a risk score.
- [ ] Disavow only when you have **clear evidence of paid or manipulative links you built** or a **manual action**.
- [ ] Spend that time on content, internal links and earning genuine mentions instead.
- [ ] Check **Manual Actions** in Search Console occasionally.

## 4. Ads and AI answers: headline-level notes

I could confirm only the headlines (Search Engine Roundtable, October 29-30), not the details:
- **AI Overviews with query refinement bubbles**: a Google test.
- **AI Mode testing a blend of all products with sponsored products.**
- **Bing showing ads within AI Overviews** in Copilot.
- **ChatGPT expanding ads** (wider ads and multi-image ads).
- **Bing's new AI controls** that separate AI training from AI search grounding.

The pattern: **ads are moving into AI answers on every major platform**, so organic visibility inside those answers will be harder to win.

## 5. Status check

The Search Engine Roundtable video recap for October 30 mentions **"Google Volatility X2"** and spam updates among its headlines. I only saw the headline, and **I found no confirmed Google ranking update** in the sources I checked. I could not open the live Search Status Dashboard today, so check it yourself before telling a client an update happened.

---

## Key takeaway

The industry is moving toward **clearer, standardised controls** for AI, while the data on AI clicks is still thin. The sensible response is to **stay in AI results, measure carefully, and avoid reactive switches** like blanket opt-outs or disavow files.

## This week's action checklist

- [ ] Write down your policy on AI training (allow, block, partial)
- [ ] Review `robots.txt` for AI crawler rules
- [ ] Leave Search Console's generative AI setting alone unless you have a clear business reason
- [ ] Stop buying toxic-link audits; keep a manual-actions check instead
- [ ] Track brand searches, direct traffic and leads next to clicks
- [ ] Re-check Google's Search Status Dashboard for confirmed updates
- [ ] Keep WordPress and PHP updated

---

## Sources

- Search Engine Roundtable, Google Adopts New AI Training Control (Oct 30, 2026): https://www.seroundtable.com/google-ai-training-control-42430.html
- Google Search Central blog, AI training control (Oct 2026): https://developers.google.com/search/blog/2026/10/ai-training-control
- Search Engine Roundtable, Bing new AI controls (Oct 30, 2026): https://www.seroundtable.com/microsoft-bing-ai-controls-42429.html
- Search Engine Roundtable, AI Overviews & AI Mode 0.9% click-through rate, opt-out study (Oct 30, 2026): https://www.seroundtable.com/google-ai-overviews-mode-ctr-42421.html
- Search Engine Roundtable, Google does not show all links in Search Console, including spammy links (Oct 29, 2026): https://www.seroundtable.com/google-search-console-does-not-show-all-links-42407.html
- Search Engine Roundtable, ChatGPT ads update (Oct 30, 2026): https://www.seroundtable.com/chatgpt-ads-update-42427.html
- Search Engine Roundtable, video recap (Oct 30, 2026): https://www.seroundtable.com/video-10-30-2026-42418.html

*Limitations: Sections 1-3 are based on articles I read in full. The AI training control is a proposal still under discussion, with Google's implementation planned for 2027. The 0.9% CTR figure comes from one small, self-reported case study with the limits noted above. Section 4 items are headline-level only. Opinions from named SEOs are theirs, not Google's.*

---

I help businesses grow organically through technical SEO, on-page optimization and data-driven content strategy.

- X: [@saifseoexpert](https://x.com/saifseoexpert)
- Portfolio: [behance.net/saifcreatives](https://behance.net/saifcreatives)
