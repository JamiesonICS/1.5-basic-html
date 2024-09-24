[![Open in Codespaces](https://classroom.github.com/assets/launch-codespace-2972f46106e565e64193e422d61a12cf1da4916b45550586e14ef0a7c637dd04.svg)](https://classroom.github.com/open-in-codespaces?assignment_repo_id=16022312)
###### ICS3 - Mr. J 🐠

# 1.5 - Basic HTML

Learn the basic tags that allow us to define content on a page.

### 📄 Recall: HTML

HTML uses **_tags_** to define _elements_ or _structure_.

<img alt="Example HTML Tag" src="https://media.geeksforgeeks.org/wp-content/uploads/20210401153033/htmltag.PNG" width="220px">

A blank (empty) **HTML** document should _always_ have this structure:
```HTML
<!DOCTYPE html>

<html>

  <head>
    <title>Some sort of title</title>
  </head>

  <body>

  </body>
  
</html>
```

**Notice the spacing / tabbing!**

## 📖 index.html

All web-servers need a "first page" to show when you visit a site. For example, when you go to [www.ash-ics,.ca](https://www.ash-ics.ca) you are shown the `index.html` file. It is named after the "index" at the back of a book which displays where everything is.

**All** of your HTML projects will need an [`index.html`](index.html) file to load first. In a future lesson, we will look at having more than one `.html` file.

## 📖 Some HTML Basics

- HTML is _not_ a programming language. It is a _markup_ or _design_ language.
- HTML ignores white space. Try putting multiple lines of text inside your `<body>` like this:
  ```HTML
  Hello W     orld!

  I love chocolate.
  ```
  You will notice that the text is all on one line on the actual page.
- The `<br>` tag can be used for a "break-line". It tells the browser to put the next content one line below.
  - The `<br>` tag _does not have a closing tag_. It is an _instruction_.
- Some more of the basic tags are:
  |Tag|Purpose|
  |:---:|---|
  |`<title>`Content`</title>`|This will place the `content` in the tab or top bar of the browser application window. **This tag must be placed inside the `<head>` of the page**|
  |`<h1>`Content`</h1>`|This is a **heading** tag - do not confuse this with the `<title>` tag. Headings can have 6 different sizes where `<h1>` is the largest and `<h6>` is the smallest. Try them out!|
  |`<p>`Content`</p>`|This is the _paragraph_ tag and is useful to separate text into paragraphs. By default it will put an empty line between paragraphs of text|
  |`<div>`Content`</div>`|One of the most-used tags, this is a _divider_ or _section_ or _container_ of content for the page. As you become used to HTML and styling your page you will learn to use these to break-up your content for different looks or areas on the page |
  |`<b>`Content`</b>`|This will **bold** the content|
  |`<strong>`Content`</strong>`|This will also **bold** the content but has a slightly different meaning. This means that the content is very important|
  |`<i>`Content`</i>`|This will _italicize_ the content|
  |`<em>`Content`</em>`|This will also _italicize_ the content but similar to the `<strong>` tag, it has a level of _importance_ to it, describing the content as quite important|
  |`<button>`Text`</button>`|This will place a clickable grey button with the `Text` written on it. For now the button will do nothing but we'll learn to make it react using JavaScript|
  |`<br>`|Insert a _break-line_|
  |`<hr>`|Insert a horizontal line across the page|

🖱️ **[Here is a list](https://www.w3schools.com/tags/default.asp) of all the HTML tags that exist.**

Play around with the tags on your page and insert fake content. Try the different headers, paragraphs, divs, break-lines, etc... Maybe even try inserting a picture, if you can (but don't worry, we'll have a lesson on that next class).
<br>
🐠
