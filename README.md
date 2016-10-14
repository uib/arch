This repository contains the writings of the ITA architecture board.  The
published version of this is available from <http://uib.github.io/arch/>.

This is a [hugo](https://gohugo.io/) site.  Hugo is a static site generator.

Update content by updating the markdown files in the content/ directory.
The other directories can mostly be ignored.

    brew install hugo

View the content locally while editing:

    hugo serve

and then visit the page <http://localhost:1313/arch/>.

Regenerate the published docs with by running:

    hugo
    git commit -m "Regenerated site" docs
    git push
