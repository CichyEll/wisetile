# Wisetile

NodeJS based web application for mass organization of best practices, knowledge and principles.

##Overview

Wisetile is an app primarily created to deliver flexible tool for manage companies work principles with possibility to expand on bigger picture - main source of knowledge on every case (for example diet recommendations, organization of study, coding principles and trends etc.), sorted by categories and tags in a smart way.

###My points:

* Interface of Wisetile will rely on something like Pocket app design - clean, modern and expandable. But some of planned features may change my current look on that.
* App will be based on NodeJS and maybe solutions like backbone.js framework, react.js. 
* No css framework - styles build from scratch with LESS and [justify grid](http://mrdoobhttp://justifygrid.com/) to break float-based grid trend and try with inline-blocks.

###List of features:

* App based on **tiles** - blocks of editable content, showing main content in tile and detailed after clicked.
* Users with right permissions can add/edit/delete tiles
* Block tile if editing.
* Users can comment on creating process (mini chat next to tile)
* Structure based on **sections** -> **categories** -> **tags** (example: *company* is a **section**, *contact with client* is a **category** and finally *mail* is a **tag** for principle tile *send mail to client with carbon copies to John Doe and Susan Williams*
* Visual features including responsive design, icon fonts and modern things like from [codrops](http://tympanus.net/codrops/)

### Final tools:

 * [nodejs](https://nodejs.org/) for webserver
 * [LESS](http://lesscss.org/) for preprocessing CSS and keep theme clean and customizable