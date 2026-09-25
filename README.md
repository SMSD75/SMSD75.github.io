# SMSD75.github.io

Personal site: https://smsd75.github.io — the homepage is `index.html`; the blog is built by GitHub Pages (Jekyll) from Markdown.

## Writing a blog post

1. Create `_posts/YYYY-MM-DD-short-title.md` (e.g. `_posts/2026-10-01-why-dense-ssl.md`).
2. Start it with front matter:

   ```yaml
   ---
   title: "Why dense self-supervised learning?"
   description: One-line summary for the blog index and link previews.
   tags: [self-supervised, video]
   math: true   # only if the post has equations
   ---
   ```

3. Write Markdown below it. Math: `$$ ... $$` (inline or display). Code: fenced blocks with a language. Images: put them in `images/blog/` and use `![alt](/images/blog/fig.png)`.
4. Commit and push. The post appears at `/blog/YYYY/MM/short-title/` within ~1 minute.

Unfinished posts go in `_drafts/` (never published). `_drafts/example-post.md` shows every feature.

GitHub's web editor works fine for this: *Add file → Create new file → `_posts/2026-10-01-title.md`*.

RSS feed: `/blog/feed.xml`.
