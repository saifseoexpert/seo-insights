# SEO News Deep Dive: November 6, 2026

**Date:** November 6, 2026  
**Topics:** Facebook Answers' 6 Million AI Pages, Google Protecting Important URLs That Return 4xx, Search Profiles Adds LinkedIn, Search Console and EEA Policy Updates, AI Mode Home Services Booking  
**Author:** Saif Ullah, SEO Expert & Digital Marketer

---

## TL;DR

The biggest story of the week: **Facebook has about 6 million AI-generated "Answers" pages indexed in Google**, and SEOs are asking whether Google's scaled content rules apply equally to big brands. Also useful: Google's Gary Illyes explained what happens when an **important URL returns a 4xx error**, Google Search Profiles may now show **LinkedIn**, and Search Console got a new **multi-select device filter**.

---

## 1. Facebook Answers: 6 million AI-generated pages in Google (November 5)

Per Search Engine Roundtable's report:

- **Facebook Answers** pages live under `facebook.com/fb-answers/`. Each is an **AI-generated summary of a topic**, built using public Facebook posts and pages as sources, and open to indexing by Google and others.
- Saul Westbrook documented it in a write-up. He says he noticed Meta had quietly indexed millions of these pages **in June 2026**. Glenn Gabe says Facebook **started populating the directory in July 2026**. The two timelines differ slightly.
- Google's index shows roughly **6 million** of these pages, and they are **ranking**.
- Glenn Gabe says the directory ranks for **millions of queries** across regular results, AI Overviews and AI Mode, and called it a clear example of **scaled content abuse**. That is his opinion, not a Google decision.
- Barry Schwartz hears **rumours** that Instagram is doing something similar and suspects these pages **won't stay indexed much longer** now that the practice is public. That is his guess, not a confirmed fact.
- I found **no Google statement** in the article.

**Why it matters:** Google's scaled content abuse policy covers content produced in volume with little added value, however it is produced. Many SEOs now watch to see whether it is **applied equally to large brands**.

**What to do:**
- [ ] **Don't treat this as permission.** A page type ranking today does not mean it is safe. Google can change that quickly.
- [ ] If you run programmatic or AI-assisted pages, make sure each one has **unique, useful information** and a clear reason to exist.
- [ ] Audit templated pages and merge, improve or remove weak ones.
- [ ] If your business publishes public Facebook posts, remember that **public posts can be used as source material** for pages like these. Review what you post publicly. (This is my inference from the report, not a Meta policy statement.)

## 2. Google can temporarily protect important URLs that start returning 4xx (November 5)

Gary Illyes of Google commented on LinkedIn after SEOs noticed the VLC website was missing its favicon in Search. He explained:

- VLC's site had been serving the unusual **418 ("teapot") status code**, which Google treats like most **4xx errors: basically "not found"**.
- Because VLC is so important, Search **temporarily protected the URL from falling out of the index right away**.
- The **side effect**: since Google no longer knew what was on the page, there was **no snippet and no favicon**, just the link and the last good title.
- Once the site returned **200 OK** with content again, he said it should sort itself out soon.

Barry Schwartz added that his own site's favicon disappeared for a few days last week. He suspects it was linked to the PHP exploit situation, but that is his **gut feeling**, not a confirmed cause.

**What to do:**
- [ ] Don't expect this protection for ordinary pages. Illyes described it for a very important URL, and it was **temporary**.
- [ ] Check that your key pages return **200** to Googlebot, not 4xx or 5xx. Use **URL Inspection** and server logs.
- [ ] If a snippet or favicon suddenly disappears, check the **status code** and whether a firewall or CDN rule is blocking Googlebot.
- [ ] After emergency security changes (for example the October PHP patch), re-test your important pages. This tip is mine, not from the article.

## 3. Google Search Profiles may now show LinkedIn (November 4-5)

Damien Andell spotted that Google **Search profiles** now display **LinkedIn** next to other networks. Details:

- Search profiles officially support **YouTube, TikTok, Instagram and X**, and you can also add **Facebook** and your **website**.
- LinkedIn appears to be **added automatically**. There is **no way to add it manually** yet.
- Barry Schwartz did not see LinkedIn on his own profile, so rollout looks **partial**.

**What to do:**
- [ ] Keep your **name, headline and About text consistent** across LinkedIn, your website and other profiles.
- [ ] Link your social profiles from your website so Google can connect them.
- [ ] Check whether you or your brand qualify for a Search profile. As I noted on October 26, the follower threshold and eligible regions apply, and availability may differ in your country.

## 4. Search Console and policy updates

- **Multi-select device filters (November 4):** The Performance report now lets you select **multiple device types** at once. Google previously added multi-select for countries.
- **Site reputation abuse and the EEA (November 4):** Google emailed sites with **site reputation abuse manual actions** to say those actions **no longer affect Search results in the European Economic Area**. The change took effect on **August 30, 2026**, and notifications are only arriving now, two months later.

**What to do:**
- [ ] Use the device multi-select to compare **mobile vs desktop and tablet** in one view.
- [ ] If you publish sponsored or third-party content on your domain, check **Manual Actions** for site reputation messages.

## 5. AI Mode adds home services booking (November 5)

Google added **booking buttons** for home services listings in AI Mode results. Partners include **Angi Home, Thumbtack, Housecall and GetJobber**, with **ServiceTitan** coming soon. Search Engine Land also covered it.

**What to do (local service businesses):**
- [ ] Keep your **Google Business Profile** accurate: services, hours, service area and contact details.
- [ ] Check whether any partner platform you already use offers booking connections.
- [ ] Collect genuine reviews, since AI results often show ratings.

## 6. Headline-level items

I saw only the headlines or short summaries for these:
- **OpenAI** says ChatGPT's search-like query volume is **about one-fifth of Google's**, and grew from 1 billion to 1.2 billion in two months (Search Engine Roundtable, November 4). Search Engine Land asked whether claims of **1 trillion ChatGPT searches a year** hold up. Treat the figures with caution until independent data appears.
- Search Engine Land headlines: **Google organic click share reaches a 15-month high**, **3 in 4 homepages lost organic clicks (110 sites)**, and **negative prompts have 2x impact on ChatGPT brand sentiment**. I did not read these studies.

## 7. Where things stand

Search Engine Roundtable's November report says Google finished the **September 2026 spam update in October**, and that the industry is still **waiting for the next core update** after several unconfirmed updates. I could not open the live Search Status Dashboard today, so check it before telling a client that an update happened.

---

## Key takeaway

Google's rules look different from the outside than they do in the results. The practical response is the same: **build pages that are genuinely useful, keep your technical basics healthy, and verify every number** before you report it.

## This week's action checklist

- [ ] Audit templated or AI-assisted pages: improve, merge or remove thin ones
- [ ] Check that key pages return 200 to Googlebot, especially after security or CDN changes
- [ ] Make your name and profile details consistent across LinkedIn, website and social profiles
- [ ] Try the new device multi-select in Search Console Performance
- [ ] Review Manual Actions for site reputation messages
- [ ] Update your Google Business Profile (services, hours, service area)
- [ ] Cross-check Search Console click spikes against analytics before reporting
- [ ] Re-check Google's Search Status Dashboard for confirmed updates

---

## Sources

- Search Engine Roundtable, Facebook Answers AI-Generated 6 Million Pages Is Google Scaled Content Abuse (Nov 5, 2026): https://www.seroundtable.com/facebook-answers-google-42467.html
- Search Engine Roundtable, Google Can Temporarily Protect Important URLs From Being Deindexed (Nov 5, 2026): https://www.seroundtable.com/google-protected-important-urls-index-42464.html
- Search Engine Roundtable, Google Search Profiles Spotted Adding LinkedIn (Nov 5, 2026): https://www.seroundtable.com/google-search-profiles-adds-linkedin-42458.html
- Search Engine Roundtable, Daily Search Forum Recap: November 5, 2026 (device filters, EEA site reputation emails, AI Mode booking, headlines): https://www.seroundtable.com/recap-11-05-2026-42466.html
- Search Engine Roundtable, Daily Search Forum Recap: November 4, 2026 (OpenAI query volume claim): https://www.seroundtable.com/recap-11-04-2026-42452.html
- Search Engine Roundtable, November 2026 Google Webmaster Report: https://www.seroundtable.com/november-2026-google-webmaster-report-42431.html
- Peripheral Creative, Facebook Answers AI-generated pages (Saul Westbrook), as cited by Search Engine Roundtable: https://www.peripheralcreative.com/news/facebook-answers-ai-generated-pages

*Limitations: Sections 1-3 are based on articles I read in full. Sections 4-5 are based on Search Engine Roundtable's summaries and the daily recap. Section 6 is headline or summary level only. Opinions from named SEOs, and Barry Schwartz's guesses, are labelled as such. Google has not commented in the sources I read.*

---

I help businesses grow organically through technical SEO, on-page optimization and data-driven content strategy.

- X: [@saifseoexpert](https://x.com/saifseoexpert)
- Portfolio: [behance.net/saifcreatives](https://behance.net/saifcreatives)
