# sk-app-base
[Shanthosh Krishnakumar](http://www.drmsweb.com/)

Use this base structure to start any website or web application

This has following Gulp workflows ready
- lint, concatinate and minify the custom js files
- concatinate and copy the vendor js files
- convert the sass file(s) and minify the css file
- copy the html
- watch the changes in html, sass files and js files and does above tasks

Install
- Just download or clone the repository
- In the copied folder run these commands from command line interface
  * npm install
  * gulp
- The last line will update the files in the dist folder. If you don't have the folder it creates and copy the files. Simultaneously a browser window will start to open the index.html file from the dist folder.


*TODO*
- add PUG (Jade templating) support to HTML
..* obviously adding that workflow in the gulp
