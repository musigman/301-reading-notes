# Reading Day: 09.21.20
## EJS Partials
Partials allow you to define reusable code in multiple locations. Partials are like functions, in that they make large websites easier to maintain. Once the code is defined, the partials can be used in templates on multiple pages. Examples of partials include static elements like **Nav Bars, Footers or Reusable text**.

In EJS, any JavaScript or non-HTML syntax you include in a template is always placed inside of *<% %>* tags. The tags allow us to output the **unescaped** content onto the page.

Once partials are defined, you can use them in a .ejs template.

*<% include partials inside these tags %>*



[<== Back to Table of Contents](index.md)