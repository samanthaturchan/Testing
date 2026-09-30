# Sam Turchan | Engage Media: personal site

Static site (plain HTML/CSS, no build step). Owner: Sam Turchan.

Master brief: "Sam Turchan | Engage Media" section of the Client Briefs doc (https://claude.ai/code/artifact/fe52c63f-23b9-453a-bb24-2171af80246e). Update the doc first, then mirror changes here.

## Files
- `.vercelignore`: keeps `CLAUDE.md` and `README.md` off the live site
- `index.html`: the whole page (hero, throughline, approach, about, favourites, work, contact)
- `styles.css`: all styling; colour tokens on `:root`

## Hosting & publishing
- GitHub repo `samanthaturchan/Testing`, default branch **`main`**.
- Vercel deploys **`main`** to production automatically (~30s after push).
- Other branches get Vercel preview URLs only; they are not live.
- Workflow: make changes on a working branch → show Sam the preview → merge to `main` when Sam says publish.
- GitHub Pages was used briefly; it should be turned off (Settings → Pages → None) to avoid a duplicate copy.

## Integrations
- Contact form: Formspree form `xgavrorj` (`https://formspree.io/f/xgavrorj`).
- LinkedIn: https://www.linkedin.com/in/samturchan/ (header icon, contact line, footer).
- Domain: not yet purchased (plan: `samturchan.com`, buying through Vercel).

## Design system
- Fonts: Newsreader (serif display, italic accents), Inter (body). The reference design used the paid font "Aime"; Newsreader is the free stand-in.
- Colours: page `#fbfaf9`, raised `#f4efec`, panel `#e9e1dc`, ink `#251f21`, coral `#ef6f5e`, teal `#7fae9e`, dark `#2a2527`.
- Style: editorial, large tight serif headlines, tiny uppercase letter-spaced labels, coral italic for emphasis.

## Copy rules
- Sam's voice: first person, confident, a little playful. Canadian spelling (Honours, favourite).
- Bio and favourite-things copy is Sam's own; don't rewrite without asking.
- Don't name clients publicly without approval.

## Open items
- Automotive case study still labelled "Work in progress"; Sam deciding whether to finalize.
- SEO basics pending: share image (OG), Person structured data, sitemap.xml, robots.txt, sharper <title>. Need Sam's city/region + headshot.
- Search Console setup after domain is live.
