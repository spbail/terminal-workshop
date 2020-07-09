# Terminal workshop

A variation of the Learn to Bash workshop materials, adapted for remote teaching and zsh vs bash.

Workshop first held at the DataUmbrella meetup in July 2020.

permits.csv is a modified sample CSV file based on the Film Permits data provided by [NYC OpenData](https://data.cityofnewyork.us/City-Government/Film-Permits/tg4x-b46p)

# Slide instructions

Use the HTML, or follow these instructions in case you want to compile the markdown yourself/play around with Marp:

## Installing Marp
* Install npm: https://www.npmjs.com/get-npm
* Allow global install of npm modules: `sudo mkdir /usr/local/lib/node_modules; chown -R `whoami` /usr/local/lib/node_modules` 
* Install marp CLI: `npm install -g @marp-team/marp-cli`
* This seems to be the most helpful documentation: https://marpit.marp.app/

## Compiling markdown to HTML
* Compile markdowns: `marp *.md --theme theme.css` then open the HTML output in a browser window. Each change requires re-compiling and refreshing the browser. The `theme` flag is needed to compile with the custom CSS.
* You can also run these in "watch" mode which will keep a compile server running and refresh the browser window for both markdown and CSS changes (pretty cool): `marp *.md --theme theme.css --watch`
