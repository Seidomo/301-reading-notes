# **EJS**

### *EMBEDDED JAVASCRIPT TEMPLATING*

EJS is a simple templating language that lets you generate HTML markup with plain JavaScript.

How to Install?

```
npm install ejs

```

### Options

- ```views``` An array of paths to use when resolving includes with relative paths.
- ```context```function execution context
- ```client```returns standalone compiled function
- ```debug```outputs generated function body
- ```strict```when set to true generated functions is in strict mode


### Tags

- ```<%``` scriptlet tag, for control flow, no out put
- ```<%_``` white space slurping,strips all white space before it
- ```<%=``` outputs the value into the template
- ```<%-``` outputs the unescaped value in the template
- ```<%#``` comment tag, no output
- ```<%%``` output is litteral
- ```%>```  plain ending tag
- ```-%>``` trim-mode tag
- ```_%>``` removes all whitespace after it
















* [Reference](https://ejs.co/)