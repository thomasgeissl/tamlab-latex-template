# tamlab-latex-template

## installation
* use this repo as a template
* clone it

## requirements
* you will need an editor/ide, vs code is recommended
* nodejs
  * osx with brew: `brew install node`
  * windows: TODO
  * linux with snap: `sudo snap refresh node --channel=16/stable`
* pdflatex via texlive, basictex
    * osx with brew: `brew install --cask basictex`
    * windows: TODO
    * linus: TODO
* [optional] pandoc - in case you wanna render to html instead of pdf
  * osx with brew: `brew install pandoc`

## usage
* install all the build dependencies: `npm install`
* run in watch mode - it will build every time you save: `npm run dev`
* build a pdf: `npm run build`
* build a html file: `npm run build-html`
* serve directory: `npm run serve-html`
* you might wanna add your references to the scripts/download_references.sh file, so you make it easier for others to fetch them