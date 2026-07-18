# Your site — the editing guide

GitHub now builds your site for you. You edit simple text files in VS Code,
commit + sync, and a minute later the live site updates. You never touch HTML.

## YOUR files (edit these freely)

| File | What it controls |
|---|---|
| `_config.yml` | Your name, email, social links, contact page text |
| `index.md` | Homepage: headline, about paragraphs, which photos show |
| `_posts/` | Blog posts — one file each |
| `_projects/` | Portfolio works — one file each |
| `_data/other.yml` | The Other page: photo collage, quotes, "currently" list |
| `img/` | Drop photos in here |
| `css/custom.css` | Style tweaks (optional) |

## NOT your files (leave alone unless you know why)

`_layouts/` (the page templates), `blog.html`, `portfolio.html`,
`contact.html`, `other.html` (these build their own content automatically).

## Writing a blog post

1. In `_posts`, make a new file named like: `2026-07-20-my-post-title.md`
   (date first, dashes instead of spaces, ends in .md — the date and name
   BECOME the post's date and web address)
2. Start the file with:

   ```
   ---
   title: My post title
   teaser: One line shown on the blog page.
   ---
   ```

3. Write your post below that in plain text. Blank line = new paragraph,
   `## Heading` for headings, `**bold**`, `*italic*`.
4. Commit + sync. It appears on the blog page automatically, newest first.

Tip: press Ctrl+Shift+V in VS Code to preview a markdown file while writing.

## Adding a portfolio work

Copy any file in `_projects`, rename it, edit the settings at the top
(title, summary, year, tags, image, link, order) and write the description
below. It appears on the portfolio grid automatically.

## Publishing changes

Source Control icon (left sidebar) → type a message → Commit → Sync Changes.
Wait ~1 minute, refresh your live site (Ctrl+Shift+R if stubborn).

## Setup notes (one-time)

- Your Brite bootstrap.min.css goes in the `css` folder
- Because GitHub assembles the pages, double-clicking files no longer
  previews the full site — push and check the live site instead
  (markdown preview in VS Code covers most writing needs)
