# Homework-and-questions-4
1. The sectioning elements helps organize the structure of html5 documents.
2. Semantic sectioning elements are designed to communicate structure to browsers and other technologies reading and configuring the document on behalf of users.
3. Semantic sectioning elements clarify the larger-scale structures within a document and they also intended to enhance the limited semantics that were used ealrier. Example```css <div main class="Site-content"></div>``` only humans reading this would know the purpose this element.
4. Chrome Developer Tools
5. nav element, article element, section element, aside element.
6. the nav element defines a section that contains navigation links that are on a site and they consists of primary and secondary menus. example```css <a class="menu-link"href="index.html">Home</a>```
7. The artcile element defines a piece of self-contained content it can be used for comments and widgets.```css <article itemscope itemtype="http://schema.org/BlogPosting">```
8. The section element defines a section of a document to indicate a related grouping of semantic meaning it can also use the section element to provide extra context for the parent element. ```css <section> <h1> music </h1> <p> my favorite musical instruments</p> </section>```
9. An outline in HTML5 shows the structure of the content on the page and it's useful for user agents who can use the outline to create.
10. the aside element defines a section thats related to the main element and it does not belong to the main flow it's an explanation/description box or an advertisement. ```css <aside> <h1> music </h1> <p> my favorite musical instruments</p> </aside>```
11. body element, header element, footer element.
12. the body element defines the content of a document and It contains all the content as well as HTML tags.
13. the header element defines a page area that contains a logo, title, and navigation. ```css <header> <h1 class="main-heading">music!</h1> </header>```
14. the header element can also be used inside other semantic elements such as article or section and header also may contain the section's heading and etc.
15. the header element is not necessarily positioned at the beginning of a page.
16. The footer element defines a page footer which contains copyright or legal notices and sometimes some links and a footer may contain the sectioned content's publication date and etc. ```css <footer class="site-credits"> <p>© 2021 Xavier laws</p> </footer>```
17. the article, section, aside, and nav can also have footers.
18. The nav element indicates a navigation block like this ```css <nav class="navbar"> <ul> <li> <a class="menu-link" href="index.html">Home</a> </nav>```
19. the ul element is nested inside a nav element.
20. the user-agent selects a bullet type depending on the nesting level of the li element.
21. the ul element is used for bundling a mass of items that do not have a numerical ordering. ```css <ul> <li> <a class="menu-link" href="index.html">Home</a> </ul>```
22. the li element is used to represent an item in a list and it has to contain a parent element also an unordered lists usually shows them in bullet points.
23. the a elements is usually between the open and closed tags.
24. the a element purpose is used to make links to web pages, email adresses, etc and it has a href attribute.  ```css <nav class="navbar"> <ul> <li> <a class="menu-link" href="index.html">Home</a> </nav>```
25. the content in each a element should be a link's destination.
26. Content-Disposition HTTP header it's purpose is make the content be displayed in-line in the browser.
    URL path it's purpose is to indicate href values of the a elements.
    media type it's the the start of a data: URL, or Blob.type for a blob: URL.
27. to add a external stylesheet you have to make a link element to it like so ```css <link rel="stylesheet" href="main.css">```
