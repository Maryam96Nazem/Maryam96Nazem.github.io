# Personal site

Two files make the site:

| File | What it is | Edit it? |
|---|---|---|
| `index.html` | All the words on the page | Yes — this is the only file you normally touch |
| `style.css` | Fonts, colours, spacing | Only to change colours |

## Editing

The fastest way is in the browser: open `index.html` in this repository,
click the pencil icon, make the change, scroll down, **Commit changes**.
The live site updates within a minute.

Inside `index.html`, every section is marked with a comment like:

```
<!-- ===== EDIT: name and the one-line summary under it ===== -->
```

Change the words *between* the angle brackets, not the brackets themselves.
To add an item to a list, copy a whole `<li>...</li>` block and edit the copy.

## Still to fill in

- PhD start year, advisor and lab name
- Email address
- Links: CV, Google Scholar, ORCID
- Code and data section, once the repository is released
- Writing links, as each piece is published

## Publishing a written piece

Find the title in the Writing section and change this:

```html
<li>Why two models of the same knee produce different results</li>
```

to this:

```html
<li class="published"><a href="https://...">Why two models of the same knee produce different results</a></li>
```

The title turns from grey to black and becomes a link.

## Checking before you commit

Download both files to the same folder and double-click `index.html`.
It opens in your browser exactly as it will appear live.
