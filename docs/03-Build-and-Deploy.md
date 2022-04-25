# Build and Deploy

## Building

You can build a PDF, epub, or HTML of the book. By default, we will use the `gitbook` style but there are others such as `tufte`.

An epub can converted to the older Kindle format (MOBI) using tools such as Calibre. For the newer Kindle File Format (.azw, .azw3, .kfx file formats) you can find and use [other](https://www.amazon.com/Kindle-Previewer/b?node=21381691011) [tools](https://epub2kindle.com/).

To build a book locally in RStudio, click `Builds` > `Configure Build Tools...` > Select desired output format.

Cmd+Shift+B builds the PDF, epub, or HTML.

## Deploying

### GitHub pages

0. Setup GitHub pages. See [this blog](https://seankross.com/2016/11/17/How-to-Start-a-Bookdown-Book.html)
1. Run `bookdown::render_book("index.Rmd")` in RStudio
2. git add, commit, push

Now open the GitHub pages link and the book should be there. Open https://rishigoutam.github.io/bookdown-start/index.html

### bookdown.org

Publish to bookdown.org via rsconnect

3. `bookdown::render_book("index.Rmd")`

Open https://bookdown.org/google1/rishi-bookdown-start/
