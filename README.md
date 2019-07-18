Featherbone Docs
========

```text
$ npm install
$ node server
```
From your browser navigate to:
  * <http://localhost:10002/api-client> to view the featherbone Client API definition
  * <http://localhost:10002/api-server> to view the featherbone Server API definition
  * <http://localhost:10002/api-rest> to view the REST Open API definition

By default the API definitions are populated based on the base featherbone installation. However, if a featherbone repository is cloned and installed adjacent to featherbone-docs, the Open API specification will automatically be updated to whatever is installed in the featherbone installation.

You may also update the Client and Server API documentation to match to your current featherbone installation by installing and running `yuidoc` as follows:

```text
$ npm yuidoc -g
$ cd ..\featherbone\client
$ yuidoc .
$ cd ..\server
$ yuidoc .
```