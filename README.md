# sk-app-base
[Shanthosh Krishnakumar](http://www.drmsweb.com/)

Use this base structure (sass & js gulp workflow) to start any website or web application

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
  * bower install
  * npm install -g bower-installer
- Once installed bower and additional dependencies (Example: jquery, bootstrap, etc.) go to the bower_components folder and find the installed component folder and get the needed/important file PATHS (js and/or css files which you would like to add into your web application or website) and add into the sources list in the bower.json file. Now enter below command in the command line.
  * bower-installer
- The below 'gulp' command will update the files in the dist folder. If you don't have the folder it creates and copy the files. Simultaneously a browser window will start to open the index.html file from the dist folder.
  * gulp


*TODO*
- add PUG (Jade templating) support to HTML
  * obviously adding that workflow in the gulp
