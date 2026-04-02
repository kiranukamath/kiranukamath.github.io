# Blog Post Template

Copy the frontmatter below when starting a new post.

---

## How to publish a new post

### Publish immediately
1. Copy this template
2. Save as `_posts/YYYY-MM-DD-your-post-title.md` using today's date
3. `git add`, `git commit`, `git push` → GitHub Actions builds and deploys within ~2 minutes

### Schedule for a future date
1. Copy this template
2. Save as `_posts/2026-06-01-your-post-title.md` (use the desired publish date)
3. `git push` → the post is in the repo but invisible on the site
4. On June 1st, the daily GitHub Actions cron (7:30 AM IST) runs, builds the site, and the post goes live automatically

### Work on a draft (not ready to publish)
1. Save as `_drafts/your-post-title.md` (no date needed)
2. Preview locally with `bundle exec jekyll serve --drafts`
3. When ready: move to `_posts/YYYY-MM-DD-your-post-title.md`

---

## Frontmatter template

```
---
layout: post
title: "Your Post Title Here"
date: YYYY-MM-DD
tags: [java, backend, fintech]
excerpt: "2-3 sentences summarising the post. Shown in the blog listing and used as the meta description for SEO."
linkedin_summary: |
  🚀 New post: [Your Post Title]

  [One-line hook — what problem does this solve or what will the reader learn?]

  In this post:
  → [Key insight or takeaway 1]
  → [Key insight or takeaway 2]
  → [Key insight or takeaway 3]

  Full read: https://kiranukamath.github.io/blog/YYYY/MM/DD/your-post-title/

  #Java #Backend #Fintech #SoftwareEngineering
---

Your post content in Markdown starts here.
```

---

## Cross-posting to Substack

1. Copy the Markdown content from your `_posts/` file
2. Paste into Substack's editor (it renders Markdown well)
3. Add the canonical URL in Substack settings: `https://kiranukamath.github.io/blog/YYYY/MM/DD/your-post-title/`
   — This tells search engines your GitHub Pages version is the original, protecting your SEO

## Sharing on LinkedIn

After publishing, open your post on the live site and click **"Copy LinkedIn Post Template"**.
This copies the pre-filled `linkedin_summary` from the post frontmatter — paste it directly into LinkedIn.

---

## Suggested tags

`java` · `spring-boot` · `backend` · `microservices` · `fintech` · `fraud-detection`
`performance` · `distributed-systems` · `kafka` · `redis` · `couchbase` · `career`
