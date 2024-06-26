# HTML (Hyper Text Markup Language)

1. How do websites work?
    - Client-server model
    - http request and http respnonse
    - web design fundamentals: HTLM, CSS, JS

2. What is HTML? Why use it?
3. History of HTML
4. Advantages of HTML
5. Environment setup
    - Editor: VS Code
    - Broswer: Firefox
    - Version control: Git & Github
    - VS Code Extensions: Live server and Prettier Code Formatter 

6. Basic structure of HTML
    - head and body
    - opening and closing tags
    - ```<!DOCTYPE html> <!-- a declaration, not a tag -->
      <html lang="en">
      <head>
        <title></title>
      </head>
      <body><body>
      </html>
      ```

7. Basic tags, styling, debugging
    - Two types of tags: Pair/Container tags and Empty/Single tags
    - Tags may have attributes. Attributes are assigned values using the assignment operator: =
    - debugging can be done with https://validator.w3.org/
    - comments can be added by wrapping text with <!-- COMMENT -->

8. Elements and contents
    - Whatever is inside the tags is called content
    - Tag + content = Element

9. Headings
    - There are six headings starting with ```<h1></h1>, .... , <h6></h6>```
    - ```<h1></h1>``` should be used where most emphasis is needed
    - ```<h6></h6>``` has the least emphasis

10. Paragraphs
    - ```<p> Text </p>```

11. Line breaks
    - ```<br />``` (it is an empty tag)
12. Horizontal rule
    - ```<hr />``` (also an empty tag: creates a horizontal line under the preceeding text/tag)     

13. Semantic vs Non-Semantic HTML

    - Non-semantic tags: div, span etc.
        ```
        <div>
            <!-- divide the page -->
            <h1></h1>
            <p></p>
        </div>
        ```

    - Semantic tags: header, footer, main, form, table etc.
        ```
        <header>
            <h1></h1>
        </header>
        ```
    - Best practice is to use the semantic tags as much as possible

14. Text formatting tags
    - bold text ```<strong>TEXT</strong>```
    - italic text ```<em>TEXT</em>```
    - strike through ```<del>TEXT</del>```
    - highlight ```<mark>TEXT</mark>```
    - superscript ```(a + b)<sup>2</sup>```
    - subscript ```H<sub>TEXT</sub>O```

15. Lists
    - ordered list
    ```

    <ol type>
    
        <li>Item 1</li>
        <li>Item 1</li>

    </ol>

    ```
    - unordered list
    ```

    <ul type="circle">
    
        <li>Item 1</li>
        <li>Item 1</li>

    </ul>

    ```

    - definition list
    ```
    <dl>
    <dt>Title</dt>
    <dd>Description</dd>
    
    </dl>


    ```

16. Links

17. Tables

18. Forms

19. Deployment