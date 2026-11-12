# Academic website of Zainab Khallouf

Static English-only site, no framework. Pages: `index.html` (home), `research.html`, `publications.html`, `teaching.html`, `art.html`, `writing.html`. Style: `assets/style.css`.

## Edit a page on GitHub
1. Open the repository, click the file (for example `teaching.html`).
2. Click the **pencil icon** (Edit this file) at the top right of the file.
3. Change the text between the tags (for example inside `<p>...</p>` or `<li>...</li>`).
4. Click **Commit changes**, then **Commit changes** again. The site updates in 1 to 3 minutes.

## Change the colours
Open `assets/style.css`, click the pencil, and edit the colour codes at the top (`--accent`, `--accent-2`, `--accent-soft`, `--bg`, `--card`). The first block is light mode, the second block is dark mode. Replace the codes with one of these palettes, or search "color picker" to find your own code:

| Palette | --accent | --accent-2 | --accent-soft | --bg | --card |
|---|---|---|---|---|---|
| Teal and terracotta (current) | #0f6b66 | #b4572f | #e3f1ee | #fbfaf6 | #f3f1ea |
| Burgundy and gold | #7a1f3d | #b8860b | #f6e6ec | #fcf9f7 | #f4eeea |
| Deep blue and coral | #1d3f72 | #d9534f | #e6edf8 | #fafbfd | #eff2f8 |
| Forest green and ochre | #2f5d3a | #c0872b | #e5f0e7 | #fbfbf7 | #f1f2ea |
| Plum and rose | #5b2a6e | #c2557a | #efe5f4 | #fcfaff | #f3eef6 |

## Photo and artwork
- Photo: upload `photo.jpg` (portrait) into `assets/`. Without it, your initials appear.
- Art pictures: upload into `assets/art/` using exactly these names: `horizon-terre.jpg`, `liberation.jpg`, `horizon-sable.jpg`. Without the picture, only the caption is shown. To add more works, copy one `<figure class="work">...</figure>` block in `art.html`.
- To upload: open the folder in GitHub, click **Add file > Upload files**, drag the image, **Commit changes**.

## Link your book and your profiles
- Book: in `writing.html`, remove the comment markers around the button and paste the Amazon URL.
- Google Scholar, ORCID, LinkedIn: in `index.html`, remove the comment markers in the header and paste your links.

## Add course resources (Teaching page)
The Teaching page has a "Course resources" section with one block per course. To add a file: upload it to a `resources/` folder in the repository (for example `resources/web-security/lab1.pdf`), then edit `teaching.html`, delete the line `<li class="empty">Resources will be added here.</li>` in that course block, and add `<li><a href="resources/web-security/lab1.pdf">Lab 1 - SQL injection</a> <span class="small">PDF</span></li>`. There is a how-to comment in the file above the blocks.

## The CV
The CV is not on the site for now. To add it back later, upload a PDF to a `files/` folder and add `<a class="btn" href="files/your-cv.pdf">Download CV</a>` next to the contact button in `index.html`.

## Publish
Repository `zainab-khallouf.github.io`, **Settings > Pages**, Source: **Deploy from a branch**, **main**, **/ (root)**, **Save**.
