##Notes##

###todo###
* need to make this a ror project (5)
* have the ymal files do translation keys for all names and descriptions
* have a route to merge all yaml files and display the output
*  auto build html2 by calling that project code from ruby , see https://github.com/swagger-api/swagger-codegen#generating-libraries-from-your-server
* once html2 docs are built then substitute all description links with markdown rendered html
* except in code blocks then put in just first paragraph as text
* render html2 docs to file or display depending on call
* have this callable from the command line and build for all languages
* have git hook on push to push to swaggerhub the single file using swaggerhub api

###runs###
$ cd build directory (right now spec)
$ http-server --cors

 ~/swagger  http-server swagger-editor

 ###links###
 * https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet
 * http://openapi-specification-visual-documentation.apihandyman.io/


