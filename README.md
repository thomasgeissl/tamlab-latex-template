# tamlab-latex-template
This repository provides a basic setup for writing LaTeX documents locally on your machine and building them using GitHub CI.
It can render the documents to pdf using pdflatex and/or as a stylable html file using pandoc. It is setup as an npm package to make it easier to run tasks and install dependencies.


## requirements
* you will need an editor/ide, vs code is recommended
* nodejs
  * osx with brew: `brew install node`
  * windows: TODO
  * linux with snap: `sudo snap refresh node --channel=16/stable`
* pdflatex via texlive, basictex or any other latex suite that includes pdflatex
    * osx with brew: `brew install --cask basictex`
    * windows: TODO
    * linus: TODO
* [optional] pandoc - in case you wanna render to html instead of pdf
  * osx with brew: `brew install pandoc`

## usage
* use this repo as a template by clicking on the green use this template button in the title bar
* clone it
* install all the build dependencies: `npm install`
* run in watch mode - it will build every time you save: `npm run dev`
* build a pdf: `npm run build`
* build a html file: `npm run build-html`
* serve directory: `npm run serve-html`
* build an epub: `npm run build-epub`
* you might wanna add your references to the scripts/download_references.sh file, so you make it easier for others to fetch them

## contributing
* feel free to fork and send PRs
* or file an issue via the github issue tracker