# cut.social

The website for Lens, Jamasp and Cut: open tools for running behavioral studies online. Live at [cut.social](https://cut.social).

The tools themselves live elsewhere: [Lens](https://github.com/cutsocial/lens) at [lens.cut.social](https://lens.cut.social), and [Jamasp](https://jamasp.app) (pilot code and data in [jamasp-public](https://github.com/cutsocial/jamasp-public)).

## Pages

| Page | File | What's on it |
|---|---|---|
| Home | `index.md` | Phone screenshots of Lens tasks, a section each for Lens, Jamasp and Cut, case studies, and links to every demo |
| Demos | `demo.md` | Each Lens task embedded and playable, plus how a study file is written |
| About | `about.md` | Why Cut was built, the history of Cut, Lens and Jamasp, people, funding and papers |
| CV | `cv.md` → `/resume/` | Mostafa's CV (`assets/MSR-CV-2026.pdf`), not in the menu |

## How it's built

- Jekyll on GitHub Pages, with the `minima` theme (2.5.1, the version GitHub Pages uses). Merging to `master` publishes the site within a minute or two.
- `_config.yml` sets the site title, description and the menu (`header_pages`).
- `_includes/head.html` and `_includes/custom-head.html` load the stylesheets and the font (Atkinson Hyperlegible Next, the typeface Lens 2 uses, from Google Fonts). Each stylesheet link carries `?v=<build time>`, so browsers load new styles right after each update instead of using a cached copy for up to 10 minutes.
- `assets/css/custom.css`: site-wide styles. `assets/css/home.css`: the home page only (loaded when `page.url == "/"`). `assets/css/demo.css`: the embedded demos.

## Editing

### Home page (`index.md`)

The home page is HTML inside Markdown, styled by `home.css`.

- **Screenshots** are in `assets/img/home/`: three phone screens (`lens-stroop`, `lens-bart`, `lens-ultimatum`), the study builder, the Jamasp dashboard (demo data) and Cut's ultimatum game. They're WebP, about 520 px wide for phones and 1400–1600 px for the others.
- **Case studies** are `<details class="case">` drawers, one per study: a `<summary>` with the title and one line of context, then a short summary, figures if any, and the citation. To add one, copy a drawer and keep the order by year. The section has `id="case-studies"`, so other pages can link to `/#case-studies`.
- **Try it**: one `<li>` per demo, with a link and a line on what the task does.

### Demos page (`demo.md`)

Each task has a short paragraph, an "Open in a new tab" link and an embedded demo:

```html
<div class="demo-container">
  <iframe src="https://lens.cut.social/#/demo-stroop/en" loading="lazy" frameborder="0" allowfullscreen=""></iframe>
</div>
```

Demo studies are the `demo-*.json` files in Lens's `public/experiments/`. A new Lens task gets its demo there first, then a link here and on the home page.

### Photos of people

The site doesn't publish identifiable photos of participants or students. The students in the "Students design a dictator game" case study appear only as an illustration (`assets/img/about/students-illustration.webp`), and their original photo was removed from the site and from this repository's history.

## Previewing locally

```bash
bundle install
bundle exec jekyll serve   # http://localhost:4000
```

## Leftovers

Not linked from any page, kept from earlier versions of the site: `blog.md`, `_members/`, `pdf.html`, `_layouts/post.html`, `_includes/disqus_comments.html`, and the 2018 Cut screenshots in `uploads/2018/10/28/`. One of those screenshots is the source of `assets/img/home/cut-ultimatum.webp`.
