# Google SEO Starter Guide (Summary)

## Introduction
- SEO is about making incremental modifications that help search engines crawl, index, and understand content.
- Focus on what benefits **users first**, not just search engines.
- Best practices apply to all sites, regardless of size or content type.
- No “secrets” to rank #1 — it’s about improving visibility and usability.

---

## SEO Basics

### Page Titles
- Use `<title>` inside `<head>`.
- Each page should have a **unique, descriptive title**.
- Titles appear in search results; query words are bolded.
- Keep titles concise; avoid keyword stuffing.

### Meta Descriptions
- Add `<meta name="description">` in `<head>`.
- Summarize the page in **1–2 sentences**.
- Google may use it as the snippet in results.
- Write unique descriptions for each page.

---

## Improving Site Structure

### URLs
- Use **simple, descriptive, human-readable URLs**.
- Avoid long, cryptic, parameter-heavy URLs.
- Provide **one canonical version** (via 301 redirect or `rel="canonical"`).

### Navigation
- Plan a **logical hierarchy** (general → specific).
- Use **breadcrumbs** for clarity.
- Provide:
  - **HTML sitemap** for users.
  - **XML sitemap** for search engines.
- Create **helpful custom 404 pages** with links back to useful sections.

---

## Optimizing Content

### Quality Content
- Create **unique, valuable, compelling content**.
- Anticipate **different search intents** (novices vs experts).
- Write clear, easy-to-read text; organize with headings and paragraphs.
- Update content regularly.
- Avoid:
  - Duplicated or thin content.
  - Keyword stuffing.

### Anchor Text
- Use **descriptive, concise anchor text**.
- Avoid vague links like *“click here”*.
- Use meaningful text for **internal links** too.

### Images
- Use **descriptive filenames** and `alt` attributes.
- Consolidate images in organized directories.
- Prefer **text links** over image links for navigation.
- Provide an **image sitemap**.

### Headings
- Use `<h1>–<h6>` to create a **content hierarchy**.
- Headings help users scan content quickly.
- Avoid misusing headings for styling only.

---

## Dealing with Crawlers

### Robots.txt
- Place in the **root directory**.
- Use to block irrelevant or non-essential pages.
- Do **not** rely on it to protect sensitive content — use authentication.

### rel="nofollow"
- Use `rel="nofollow"` to prevent passing link equity to untrusted pages.
- Common use cases:
  - Blog comments
  - Forums
  - User-generated content
- Can also be applied site-wide with `<meta name="robots" content="nofollow">`.

---

## SEO for Mobile

- Ensure your mobile site is **crawlable** by `Googlebot-Mobile`.
- Use **mobile sitemaps** to notify Google.
- Redirect users to the appropriate mobile/desktop version.
- Or serve adaptive content based on **User-agent**.
- Avoid **cloaking** (showing different content to Googlebot than to users).

---

## Promotions and Analysis

### Promotion
- Promote new content via:
  - Blog posts
  - Social media
  - Newsletters
  - Offline (cards, posters, etc.)
- Add your business to **Google Places** for local visibility.
- Engage with relevant communities; avoid spammy link schemes.

### Webmaster Tools & Analytics
- Use **Google Webmaster Tools (Search Console)** to:
  - Submit sitemaps

