# Your site — how to use this

## What goes where

```
index.html                 ← your homepage (portfolio + blog list)
posts/first-post.html      ← a sample blog post (copy this for new posts)
css/bootstrap.min.css      ← PUT YOUR BRITE FILE HERE (see below)
css/custom.css             ← your own style tweaks
img/                       ← photos and images go here
```

## One thing you must do

Take the **bootstrap.min.css** file you downloaded from Bootswatch (the Brite
theme) and put it inside the **css** folder, replacing nothing — the folder is
waiting for it. Without it the site will look plain.

## Uploading to GitHub

1. Go to your repo on github.com (not the Codespace)
2. Delete the old files if you're replacing the previous site
3. Click **Add file → Upload files**
4. Drag in: `index.html`, the `css` folder, the `posts` folder, the `img` folder
5. Commit changes, wait a minute, visit yourusername.github.io

## Writing a new blog post

1. In the `posts` folder, copy `first-post.html` and rename it,
   e.g. `my-second-post.html`
2. Edit the title, date, and paragraphs inside it
3. In `index.html`, find the "Latest posts" section, copy the existing
   post link block, and change the link + title + date to match your new post
4. Newest posts go at the top of the list

## Editing anything else

Open the HTML files in any text editor. Everything you should change is
marked with `<!-- EDIT: ... -->` comments.
