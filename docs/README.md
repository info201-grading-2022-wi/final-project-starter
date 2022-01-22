### Notes 
`/docs`

* Use the `/docs` directory to organize all for your R Markdown files, which have the extension `.Rmd`.
* Your R Markdown files are used to create reports that can be published on the web as HTML files.
* This is the basic workflow 
  - Go to RStudio
  - File > New file > R Markdown
  - Edit the file 
  - Save the file in `/docs`
  - From RStudio Knit the file (this creates an HTML file for publishing)
  - Push your `/docs` directory to your GitHub repository
  - Your `\docs` directory can be viewed in a web browser by using an URL like this: 

`https://info-201a-wi22.github.io/final-project/xxx/index.html`

Where: 
1. `info-201a-wi22`    is the organization 
1. `github.io`         is a webserver that you can use
1. `final-project`     is the repository name 
1. `xxx`               is your GitHub username 
1. `index.htlm`        is the document you would like to view

## IMPORTANT: Setting up your webserver 
1. You must make your repository *public*. To make it public: Go to your GitHub repository > Settings (top-right) > Change visibility (Danger Zone) > Make Public
1. You must set the pages source to /docs. To do so: Got your GitHub repository > Pages (bottom-left) > Select "/docs" from the pulldown menu




