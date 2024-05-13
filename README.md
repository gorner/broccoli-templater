# broccoli-templater

broccoli plugin that combines lodash's `_.template` and broccoli for fun stuff.

## example:

```js
var templatedTree = new Template(untemplatedTree, pathToTemplate,
  function buildVariables(content, relativePath) {
    return {
      moduleBody: content
    };
});
```
