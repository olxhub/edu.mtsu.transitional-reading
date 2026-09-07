# MTSU Transitional Reading (READ 1000)

Two parallel reading modules for READ 1000 at Middle Tennessee State
University, built as a pre/post assessment: every student completes both,
in counterbalanced order. In each, the student joins a simulated small-group
discussion (Professor Booker and three peers) and works across three texts,
practicing vocabulary in context, close reading, grammar analysis, image
analysis, and synthesis, toward a four-or-five-sentence comparison.

## Layout

- `temperance/` — the temperance movement of the 1800s compared with today's
  "sober-curious" movement. Readings from *The American Yawp*, Chapter 10
  ("Religion and Reform"); N. Currier's 1846 lithograph *The Drunkard's
  Progress*. Namespace `temperance`.
- `womens-sphere/` — the 1800s ideal of womanhood (the "cult of domesticity")
  compared with today's "tradwife" trend. Readings from *The American Yawp*,
  Chapter 11 ("The Cotton Revolution"); *The Sphere of Woman*, an 1850
  engraving from *Godey's Lady's Book*. Namespace `womens_sphere`.

Each form is one OLX sequence in its own directory with its own
`manifest.yaml`, cast, readings, and images; the directory name is the asset
URL prefix. Both forms discuss a modern magazine article that is distributed
on paper in class and deliberately not included here. Built with
[lo-blocks](https://github.com/olxhub/lo-blocks).

---

The author catalog reads this README for the repository description (git
conventions first; `lo.yaml` covers only beyond-git fields like discipline).
Licensing and attribution live in `LICENSE.TXT`, `NOTICE.TXT`, and
`CONTRIBUTORS.TXT`. Course content is AGPLv3; the *American Yawp* excerpts
under each form's `readings/american-yawp/` are CC BY-SA 4.0 (see the
LICENSE.TXT there); the lithograph and the engraving are public domain.
