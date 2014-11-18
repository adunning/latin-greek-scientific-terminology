# Latin and Greek in Scientific Terminology (CLA 201)

This repository provides the materials for the versions of this course taught by [Andrew Dunning](http://andrewdunning.ca/) at the University of Toronto in Summer and Fall 2014 (CLA201H5S, CLA201H5F). See [Acknowledgements](http://andrewdunning.ca/latin-greek-scientific-terminology/acknowledgements/) for information on sources.

## Technical Information

On creating an alternate version of this course, see [How to Fork a Syllabus on GitHub](http://chronicle.com/blogs/profhacker/how-to-fork-a-syllabus-on-github/39447). (The site design is simply modified from the default Jekyll theme; the original application of it to a course website is from [Lincoln Mullen](https://github.com/lmullen/clio3-syllabus).) To build the site, the following software is required:

- [Pandoc](http://johnmacfarlane.net/pandoc/), used for converting the syllabus, vocabulary list, and lecture notes from Markdown into PDF, RTF, and HTML slides (with [reveal.js](http://lab.hakim.se/reveal-js/)).
- [Jekyll](http://jekyllrb.com), with the [pandoc-ruby](https://github.com/alphabetum/pandoc-ruby) plugin, for assembling the site.
- [Zotero](https://www.zotero.org), with the [Zotxt](https://bitbucket.org/egh/zotxt) add-on, is used for managing the bibliography: these are necessary only if one wishes to add new references.

Unfortunately, GitHub Pages does not support Pandoc, meaning that the site must be built manually. While it could be done automatically using [jekyll-travis](https://github.com/mfenner/jekyll-travis), I have found it simpler for the time being to use the following (rather inelegant) method:

1. Generate any PDFs and lecture slides/notes using Pandoc. To generate new slides, use a command (from the `lectures` directory) such as `pandoc lecture-1.md -o lecture-1.html -t revealjs -s -S`; for RTFs, `pandoc lecture-1.md -o lecture-1.rtf -s -S`. (The `-s` flag is necessary to make the file standalone; otherwise, the file will not display correctly.)
2. Open the GitHub application, commit the changes to the `master` branch, and sync.
3. From the main directory, run `jekyll build`; the files will be copied into a `public` directory one level.
4. In the GitHub application, switch to the `gh-pages` branch (note that this will change the files that appear in the main directory).
5. Copy the generated files from the `public` folder into the main directory, commit, and sync.
6. Switch back to the `master` branch.

Corrections and other improvements are very welcome.

## Licence

This syllabus and all assignments are copyrighted © 2014 Andrew Dunning and licensed under a [Creative Commons Attribution 4.0 International Licence](https://creativecommons.org/licenses/by/4.0/).