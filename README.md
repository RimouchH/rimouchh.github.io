# Rim H. Chaif, Ph.D. — Academic Website

A multi-page static site (Home, About, Research, Publications, Teaching, News, CV, Contact) styled in a navy-and-gold academic identity. No build step, no dependencies. It works as plain HTML and hosts free on GitHub Pages.

## Before you publish, do these three things

1. **Add your headshot.** Save your photo as `assets/headshot.jpg`, then open `index.html` and replace the placeholder block in the hero (search for `hero-photo`) with:
   ```html
   <div class="hero-photo"><img src="assets/headshot.jpg" alt="Rim H. Chaif"></div>
   ```

2. **Confirm your CV PDF.** A copy of your CV is already at `assets/RimChaif_CV.pdf`, so the CV page download and embed work immediately. Replace that file whenever you update the CV (keep the same filename and it just works).

3. **Fix the social links.** In `index.html` and `contact.html`, replace the `#` placeholders with your real LinkedIn and Google Scholar URLs.

## Publish on GitHub Pages (free)

1. Create a new GitHub repository. If you name it `yourusername.github.io`, the site lives at that address. Any other name works too; the URL is then `yourusername.github.io/repo-name`.
2. Upload every file in this folder to the repository (keep the `assets/` folder intact). You can drag and drop in the GitHub web interface, or use git.
3. In the repository, go to **Settings → Pages**.
4. Under **Build and deployment**, set **Source** to "Deploy from a branch," choose the `main` branch and the `/ (root)` folder, and save.
5. Wait a minute, then reload. Your site is live at the URL shown on that Pages settings screen.

## Custom domain (optional)

If you buy a domain (for example, rimchaif.com), add it under **Settings → Pages → Custom domain**, then create a `CNAME` DNS record with your registrar pointing to `yourusername.github.io`.

## Editing content

Each page is a standalone `.html` file with the same header and footer. Edit text directly. All colors and type live in `style.css` under the `:root` variables at the top, so you can restyle the whole site by changing a few hex values there.

## Files

- `index.html` — Home
- `about.html` — About + education
- `research.html` — Research program
- `publications.html` — Publications
- `teaching.html` — Teaching record
- `news.html` — News and updates
- `cv.html` — CV download, summary, and embedded PDF
- `contact.html` — Contact
- `style.css` — Shared styles
- `assets/` — Your CV PDF and headshot
