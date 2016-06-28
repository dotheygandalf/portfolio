---
layout: post
title:  "HTML Tag Counter"
date:   2016-06-28 9:37:36 -0800
categories: project
thumbnail: /assets/work/tag-counter-thumbnail.png
caption: "Product Designer & Software Engineer"
type: "Project"
info: {Role: Product Designer & Software Engineer, Type: Personal Project, Date: 2016, Technologies: 'Angular.js, Node.js, LESS, grunt, bower, CodeMirror, js-beautify'}
intro: "Small webapp that counts HTML elements of webpages."
---


<div class="full-bleed-white" markdown="1">
<div class="wrapper" markdown="1">

## Demo

This project is hosted on Amazon's EC2 at the following [link](http://ec2-54-186-30-18.us-west-2.compute.amazonaws.com/){:target="_blank"} and the code can be found on [GitHub](https://github.com/dotheygandalf/htmlTagCounter){:target="_blank"}.

## Goal

1. Create a simple web app, hosted at a URL we can visit.
1. Users can enter a URL of a page to fetch.
1. The web app fetches the HTML of the page and displays the source to the user.
1. A summary of the document is displayed, listing which tags are present in the HTML and how many of each tag.
1. Clicking on the name of each tag in the summary will highlight the tags in the source code view.

</div>
</div>



<div class="full-bleed orange">
<div class="wrapper" markdown="1">
  ![Screenshot](/assets/work/tagCounter/tag-counter.PNG)
</div>
</div>



<div class="full-bleed-white" markdown="1">
<div class="wrapper" markdown="1">

## Features
* Clicking on an element type will highlight the selected elements in the source view and scroll to the first occurrence.
* A search for elements that is useful when the list gets really long.
* URL validation in the HTML form
* Error handling when requests don't match a content-type of text/html.
* Error handling when requests fail.
* HTML source beautification on the server side using the node js-beautify library.
* Syntax highlighting using the CodeMirror library.
* Support for both mobile and desktop experiences

</div>
</div>
