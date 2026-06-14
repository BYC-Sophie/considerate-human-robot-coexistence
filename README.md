# Considerate Human–Robot Coexistence

Project page for a research program on **considerate human–robot coexistence** in
healthcare, bringing together two strongly related papers that study the same
encounter from two complementary sides:

- **Robot Design** — *Towards Considerate Embodied AI: Co-Designing Situated
  Multi-Site Healthcare Robots from Abstract Concepts to High-Fidelity Prototypes*
  (CHI 2026).
- **Human Perception** — *Towards Considerate Human-Robot Coexistence: A Dual-Space
  Framework of Robot Design and Human Perception in Healthcare* (IEEE RO-MAN 2026).

The two are connected by a **co-evolving loop**: design decisions shape what people
perceive and expect, and human perception feeds back to reframe what we design next.

## Live site

This is a static site hosted with **GitHub Pages**. The `.nojekyll` file disables
Jekyll processing so the `static/` assets are served as-is.

## Structure

```
index.html                     # the whole page (content lives here)
static/css/                    # Bulma + project styles (index.css)
static/js/                     # carousel / slider / FontAwesome + index.js
static/images/                 # figures + favicon
static/pdfs/                   # paper PDFs + interview-guide.html
```

## Editing

All content is in `index.html`; styling for the umbrella concept sections is at the
bottom of `static/css/index.css`. Add a figure by dropping it in `static/images/`
and pointing an `<img>` at it.

## Acknowledgments

This page is built on the
[Academic Project Page Template](https://github.com/eliahuhorwitz/Academic-project-page-template)
by Eliahu Horwitz, adapted from the [Nerfies](https://nerfies.github.io) project page.
The template is licensed under
[CC BY-SA 4.0](http://creativecommons.org/licenses/by-sa/4.0/); per its terms, the
attribution link is kept in the page footer.
