

## Installation

```bash
npm install @jsreport/jsreport-ejs
```

## Basics

jsreport EJS engine uses [EJS](http://www.ejs.co/) library and therefore is fully compatible with it. You can do all the typical EJS data binding, conditions, loops or even use helpers.

```html
<ul>
<% for(var i=0; i<students.length; i++) {%>
   <li><%= foo(students[i]) %></li>
<% } %>
</ul>
```
