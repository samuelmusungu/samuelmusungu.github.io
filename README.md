# Samuel Musungu, portfolio

Personal portfolio for Samuel Musungu: full-stack developer, AI data specialist and technical recruiter in Nairobi.

Live: https://samuelmusungu.github.io

## Stack

Plain HTML, CSS and JavaScript. No build step, so GitHub Pages serves it as is.

## Structure

```
index.html            the whole site (markup, styles, scripts)
assets/profile.jpg    profile photo
assets/cv.pdf         CV, linked from the hero, nav and footer
assets/projects/      project screenshots (WebP)
.nojekyll             tells GitHub Pages to serve every file as is
```

## Editing content

All copy is in the arrays at the top of the `<script>` block in `index.html`:

| Array | Controls |
| --- | --- |
| `ROLES` | Words rotating in the hero |
| `SKILLS`, `SKILL_CATS` | About section skill bars and tags |
| `ENGAGEMENTS` | Talent sourcing engagement models |
| `MARKETS` | Africa, Europe and Latin America cards |
| `PIPELINE` | Six-step sourcing process |
| `WHY` | Talent section differentiators |
| `SERVICES` | Services grid (the first entry is the featured one) |
| `PROJECTS` | Project cards and case-study modal. Add an `img` path or leave it `null` for a typographic card |
| `TESTIMONIALS` | Client quotes |

GitHub repos are loaded live from the public API for `GH_USER`. If the request fails, a link to the profile is shown instead.

The contact form opens the visitor's email app with the message filled in, so no server is needed.

## Deploying

Push to the `main` branch of `samuelmusungu.github.io`. In repo Settings, Pages should be set to deploy from `main`, root folder. The site updates a few minutes after each push.

## Before going live

- Confirm the email address. The old site used musungusamuel21@gmail.com and the old README used musungusam2000@gmail.com. The site uses the first.
- Replace `assets/cv.pdf` with your latest CV if it has changed.
- Refresh the HighDesign Agency screenshot if the live site has changed since the old capture.
- Check the talent claims (tools, languages and engagement terms) match how you actually work.
