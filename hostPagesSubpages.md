# How To Use GitHub Pages to Host Webpages 

## Setting Up Your Repository
Use the instructions here to set up your repository on GitHub: https://pages.github.com/

## Hosting Pages
Your main repository will be yourUsername.github.io. This will be the url for your home page, and the root page for all other pages and project sites. 
The main page url will point to a file called "index.html". GitHub pages will automatically generate this file as a web page available at https://yourUsername.github.io or https://yourUsername.github.io/index.html. 

So far, your repository's directory should look like this: 

_Picture of Repository with only index.html here_

You can create any other pages and store them in this main repository. Pages can be created with HTML (.html) files or GitHub Markdown (.md) files. GitHub Pages will generate the URL to these pages as subpages of the main page.

_Picture of page created via markdown and page created via html in the main repository._

_Link to HTML-generated page_

_Link to MD-generated page_ 

## Hosting Project Sites
Unfortunately, GitHub only allows you to host one website domain via one repository per user account. However, this inital repository can host "project sites". 

Project sites are sub-directories/sub-repositories inside of your GitHub Pages repository. To create a project site, create a folder inside of your Pages repository like so:

_Picture of project site folder inside of the main repository._

Inside of this new sub-directory, you can create a new "index.html" file to serve as the home page to your project. 


Sources:
* https://pages.github.com/
* https://docs.github.com/en/pages
* https://jekyllrb.com/docs/posts/
