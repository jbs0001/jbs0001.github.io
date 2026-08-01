# Portfolio — deploy & finish checklist

## Deploy to GitHub Pages (5 minutes)

1. Create a public repo named `YOUR_GITHUB_USERNAME.github.io` (this exact name gives you the root URL).
2. Drop `index.html` (and your resume PDF, exported from the docx) into the repo root. Commit and push.
3. Repo → Settings → Pages → confirm source is `main` / root. Site goes live at `https://YOUR_GITHUB_USERNAME.github.io` within a minute or two.

## Fill-ins before sharing (search each file for `[` and `YOUR_GITHUB_USERNAME`)

**index.html**
- [ ] Replace `YOUR_GITHUB_USERNAME` in the footer (2 places).
- [ ] Chain The Rainbow stats row: replace `[X]` installs with the real Play Console number (or delete that stat block until you have a number you like).
- [ ] Export the final resume docx to PDF as `Brandon_Stevison_Resume_2026.pdf` and put it in the repo root so the footer link works.

**Resume docx**
- [ ] Header: `github.com/[USERNAME]` and `[USERNAME].github.io`.
- [ ] Chain The Rainbow: start date `[Mon YYYY]` and `[X installs · X.X★ · N reviews]` (Play Console → Statistics, Ratings).

## Judgment calls made for you (change if you disagree)

- **Sensor-Fusion Explorer is framed as a methods demo with synthetic geometry** and explicitly says "no program data." Before linking any code for it, confirm with DICE that a sanitized CI/uncertainty demo is fine to publish. The page as written describes only public math (Julier–Uhlmann CI, Jacobian propagation) and generic capability, which mirrors what's already on your resume.
- **Screenshots added** for ToBeWatched (film page) and Chain The Rainbow (store art) — the `images/` folder must be uploaded to the repo alongside `index.html`. A short gameplay GIF for Chain The Rainbow would still be a worthwhile upgrade over the static store shot. Section 03 remains SVG-only by design (nothing program-adjacent to screenshot).
- **Chain The Rainbow deliberately says "iteratively tuned from player behavior," never "A/B tested"** — matching your own accuracy note. Keep that language in interviews too.
