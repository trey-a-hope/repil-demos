# Replit Demos

A starter blog page built on Replit in late 2023, set up as a teaching demo for a Black Girls Code session. It's a plain HTML and CSS layout that students can fill in: a header with the blog name, a main column with a post card (title, date, image and text) and a sidebar with an About card and Black Girls Code's social links.

## Files

| File | What it holds |
| --- | --- |
| `index.html` | the page layout with placeholder headings, text and empty image slots |
| `style.css` | the two-column card layout, which stacks into one column on narrow screens |
| `script.js` | empty, ready for students to add JavaScript |
| `.replit`, `replit.nix` | Replit config for an HTML project with the HTML language server |

## Running it

Open the repo in Replit and press Run, or open `index.html` in any browser. To serve it locally:

```sh
python3 -m http.server 8000
```

## Ideas for students

- Change "Blog Name" and the post title and date.
- Add image URLs to the empty `src=""` attributes.
- Duplicate the post card to add more posts.
- Use `script.js` to add something interactive, like a like button.
