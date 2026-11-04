# Basic HTML Website

Personal portfolio of **Al Aqsa Reto Wijaya**, Full-Stack Developer based
in Jakarta, Indonesia. A simple HTML-only website with multiple pages,
built for the roadmap.sh **Basic HTML Website** project.

Project brief: https://roadmap.sh/projects/basic-html-website

## Goal

Learn how to structure a website using HTML — header, footer, navigation,
main content, sidebars and the other sections of a page. No styling: the
structure is the deliverable, and styles are added in a separate project.

## Pages

| File | Page |
|---|---|
| `index.html` | Homepage |
| `projects.html` | Projects |
| `articles.html` | Articles |
| `contact.html` | Contact |

Four pages, exactly as the roadmap brief specifies. The articles are
inlined on `articles.html` rather than split into separate detail pages.

## Contact form

`contact.html` posts to `/contact` with name, email, phone (optional),
subject, message and a consent checkbox. Fields are grouped in two
`fieldset`/`legend` pairs, every label is bound to its input with `for`,
validation is native (`required`, `type="email"`, `type="tel"`).

## Placeholders to change

- Canonical and Open Graph URLs still use `https://example.com/` — swap in
  the real domain once the site is hosted.
