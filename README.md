marked-element
==============
Element wrapper for the [marked](https://github.com/chjj/marked) library with support for [mermaid.js](https://github.com/knsv/mermaid).
`<marked-mermaid-element>`functions in the same way the Polymer's marked attribute functions, except it adds support for mermaid.js. For information on the syntax, visit their [website](http://knsv.github.io/mermaid/). You can declare a mermaid element by specifying language of a code block as 'sequenceDiagram' or 'graph'. For example:

    ```sequenceDiagram
sequenceDiagram
    Alice->>John: Hello John, how are you?
    John-->>Alice: Great!
    ````

Install from bower: `bower install --save marked-mermaid-element`

