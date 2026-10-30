# HasanAshraf.github.io

Personal academic website of Hasan Ashraf, live at https://hasanashraf.github.io/

It's a plain static site with no build step: GitHub Pages serves these files as they are.

## Files

- `index.html`: all page content (about, news, publications, experience, projects, education, skills)
- `assets/css/style.css`: styles; colors and type sizes are set at the top
- `assets/js/main.js`: dark mode toggle, BibTeX show/copy, section highlighting in the nav
- `assets/fonts/`: self-hosted Archivo (SIL Open Font License, see `OFL.txt`)
- `files/Hasan_Ashraf_CV.pdf`: the CV linked from the sidebar
- `.nojekyll`: tells GitHub Pages to serve the files as-is

## Common updates

- **New paper:** copy a `<li class="pub">` block in the Publications section and edit it. For the BibTeX toggle, give the `div.bib` a new `id` and point the button's `aria-controls` at it.
- **News item:** add an `<li>` at the top of the News list.
- **New CV:** replace `files/Hasan_Ashraf_CV.pdf` (keep the file name).
- **Photo:** replace `images/profile.jpg` (portrait, 4:5).

## Credits

The layout is adapted from [al-folio](https://github.com/alshedivat/al-folio) (MIT License) and [Jon Barron's website](https://github.com/jonbarron/jonbarron_website).
