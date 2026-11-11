# Academic website of Zainab Khallouf

A static, English-only website: no framework and no dependencies. Upload these files to a GitHub repository and turn on GitHub Pages.

## Publish on GitHub Pages (one time)

1. Create a GitHub account at github.com if you do not have one.
2. Click **New repository** and name it `YOUR-USERNAME.github.io` (replace with your GitHub username). Make it **Public**.
3. Upload everything in this folder to the root of the repository (**Add file > Upload files**, drag the files and folders, then **Commit changes**). Include `.nojekyll`; if your computer hides it, that is fine.
4. In the repository, go to **Settings > Pages**. Under "Build and deployment", set "Source" to **Deploy from a branch**. Under "Branch", choose `main` and `/ (root)`, then **Save**.
5. Wait a few minutes (up to 10), then open `https://YOUR-USERNAME.github.io`.

With the command line instead of step 3:

```bash
git init -b main
git add .
git commit -m "Academic website"
git remote add origin https://github.com/YOUR-USERNAME/YOUR-USERNAME.github.io.git
git push -u origin main
```

## Customise

| To... | Do this |
|---|---|
| Add your photo | Put `photo.jpg` (portrait, about 340x420 px) in `assets/`. Without it, the initials ZK are shown. |
| Edit any text | Edit `index.html`. Each section has a clear `id` (about, research, publications, teaching, career, art, contact). |
| Add Google Scholar, ORCID or LinkedIn | In the commented block under the header buttons, remove the comment markers and paste your links. |
| Link your book | In the Art section, uncomment the button and paste your Amazon URL. |
| Update your CV | Replace `files/CV_Zainab_Khallouf_EN.pdf`, keeping the same name. |
| Change colours | Edit the variables at the top of `assets/style.css` (dark mode follows the visitor's system). |
| Add a publication | Copy one `<li>...</li>` block in the `ol.pubs` list. |

## Before you publish

- A GitHub Pages site is public. It shows your name, position, university email, career, teaching and publications. It contains no phone number or home address.
- Check the author list of SAR'05 against the proceedings.
- Your ongoing work (intent-based networks, GPS spoofing) is marked as unpublished. Remove that sentence if you prefer not to mention it.
- You can later use your own domain name (Settings > Pages > Custom domain).
