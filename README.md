# Parasut API OpenAPI Specification
[![Build Status](https://travis-ci.org/parasutcom/api-doc.svg?branch=master)](https://travis-ci.org/parasutcom/api-doc)

### Development Usage

1. Run `npm start`
2. Checkout console output to see where local server is started. You can use all [links](#links) (except `preview`) by replacing https://apidocs.parasut.com (https://parasutcom.github.io/api-doc) with url from the message: `Server started <url>`
3. Make changes using your favorite editor or `swagger-editor` (look for URL in console output)
4. All changes are immediately propagated to your local server, moreover all documentation pages will be automagically refreshed in a browser after each change
**TIP:** you can open `swagger-editor`, documentation and `swagger-ui` in parallel
5. Once you finish with the changes you can run tests using: `npm test`
6. Share you changes with the rest of the world by pushing to GitHub :smile:

### How to deploy

1. Make changes in "web" and "spec" folder.
2. Push to master.
3. Travis will deploy to gh-pages branch automatically.
