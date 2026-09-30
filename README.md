# yourcompanyai.digitaloman.ai: launch guide

## 1. Upload
Upload **everything in this folder** to the web root of `yourcompanyai.digitaloman.ai`, keeping the structure:

```
index.html         the page
404.html           "page not found" page (set it as the 404 page in your host)
og-image.jpg       share preview for WhatsApp, LinkedIn, X, Facebook
favicon.svg, favicon-32.png, apple-touch-icon.png, icon-192.png, icon-512.png
site.webmanifest
robots.txt, sitemap.xml
images/            photos in WebP + JPG, 900px and 1600px
```

Hosting checklist:
- Serve over **HTTPS** and redirect `http://` to `https://`.
- Turn on **gzip or Brotli** compression and browser caching for `/images/`.
- Any static host works: Cloudflare Pages, Netlify, Vercel, GitHub Pages, or cPanel.

## 2. Tell Google and Bing (day 1)
1. **Google Search Console:** add `https://yourcompanyai.digitaloman.ai/`, verify it, submit `sitemap.xml`, then use "URL inspection" and "Request indexing".
2. **Bing Webmaster Tools:** import from Google Search Console (this also covers DuckDuckGo and Yahoo).
3. Check the structured data at **search.google.com/test/rich-results** (it should detect Organization, Service and FAQ).
4. Check the share preview at **opengraph.xyz** or LinkedIn's **Post Inspector**. After changing `og-image.jpg`, re-scrape it there.

## 3. Backlinks: the plan
Backlinks are links **from other websites** to this page. They are the biggest ranking factor you control outside the page itself. Start with the easiest wins:

**This week**
- **digitaloman.ai:** add a clear link to `https://yourcompanyai.digitaloman.ai/` from the main site's navigation or homepage, using text like "AI apps for businesses".
- **Google Business Profile:** create or update the DigitalOman.ai profile (Oman, category "Software company") and put this page as the website or a product link.
- **LinkedIn:** a company page for DigitalOman.ai, plus a post from your personal profile linking to the page. The share image is already set up.
- **Social profiles:** Instagram, X, Facebook and YouTube bios all linking to the page.

**This month**
- **Oman business directories:** Oman Chamber of Commerce and Industry (OCCI) member listing, Yellow Pages Oman, and local startup directories.
- **Startup ecosystem:** Oman Technology Fund, Riyada (SME Development Authority) and Sas incubators. Ask to be listed in their portfolios or success stories.
- **Tech and startup listings:** Product Hunt launch, Crunchbase, F6S, Clutch and GoodFirms (for "AI app development Oman").
- **Local media:** a short press release to Times of Oman, Muscat Daily, Oman Observer and Zawya ("Omani startup launches offline AI sales apps for local businesses").

**Ongoing**
- Every client app's App Store and Google Play listing can include "Powered by DigitalOman.ai" with a link to this page.
- Ask clients to link to it from their own websites ("Download our app").
- Write 2 to 4 articles a year on digitaloman.ai (for example, "Why Omani retailers need an offline AI app") that link here.

## 4. Keywords this page targets
AI app for business in Oman, company AI app, AI sales representative, offline AI app, AI chatbot app Oman, business app Muscat, App Store and Google Play business app, DigitalOman.ai.

## 5. Next upgrades that would help ranking
- An **Arabic version** at `/ar/`, linked with `hreflang`. Many searches in Oman are in Arabic, so this is the single biggest content win.
- **Real client case studies** with names, logos and results.
- **Real App Store and Google Play links** on the store buttons once the first client app is live. They currently scroll to the contact section.

## 6. Before going public, confirm these FAQ answers
The FAQ is also sent to Google as structured data, so it must match what you actually offer:
- Offline behaviour, and how updates reach customers.
- One-time payment wording, including Apple and Google developer account fees.
- Data privacy (conversations stay on the device).
- Timeline to go live.
