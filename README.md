marked-mermaid-element
==============
Element wrapper for the [marked](https://github.com/chjj/marked) library with support for [mermaid.js](https://github.com/knsv/mermaid).
`<marked-mermaid-element>`functions in the same way the Polymer's marked attribute functions, except it adds support for mermaid.js. For information on the syntax, visit their [website](http://knsv.github.io/mermaid/). You can declare a mermaid element by specifying language of a code block as 'sequenceDiagram', 'graph', or 'gantt'. For example:

    ```
    sequenceDiagram
        Alice->>John: Hello John, how are you?
        John-->>Alice: Great!
    ```
    
    ```
    graph TB
         subgraph one
         a1-->a2
         end
         subgraph two
         b1-->b2
         end
         subgraph three
         c1-->c2
         end
         c1-->a2
    ```
    
    ```
    gantt
        title A Gantt Diagram
    
        section Section
        A task           :a1, 2014-01-01, 30d
        Another task     :after a1  , 20d
        section Another
        Task in sec      :2014-01-12  , 12d
        anther task      : 24d
    ```

Install from bower: `bower install --save marked-mermaid-element`

