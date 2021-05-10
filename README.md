# cv

It requires `xelatex` or `xelatex` because the underlying document class uses `fontspec` package. Fonts are in the `font` folder in the repo, to improve portability.

## Todos

* dockerise the build and use github actions to create the artifact and make the pdf downloadable from the release tab
* remove dependency from `fontspec` and compile it with `pdflatex` 
* remove dependency from awesome-cv

## Acknowledgement

This cv currently piggybacks on the awesome work done by https://github.com/posquit0/Awesome-CV. 
I've modified the theme to achieve a different layour (i liked the header, but wanted to have bullet list sections) and i would like to remove the dependency on other fonts (or plug the minionpro fonts). 
Eventually, I would like to spend some time designing a bespoke one, but for now awesome-cv has provided a excellent starting point. 


