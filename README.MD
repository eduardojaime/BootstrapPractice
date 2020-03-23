# Creating a Web Page Using Bootstrap

## Before you start - Intro to HTML

Let's talk about Web Pages and HTML: [Intro to HTML](https://www.w3schools.com/html/html_intro.asp)

## What is Bootstrap?

It's an open source toolkit for developing web pages with HTML, CSS, and Javascript (JS or JQuery).

## Adding Bootstrap to your Web Page

Follow these instructions to enable Bootstrap on your pages:

1. Follow this link: [Bootstrap.com](https://getbootstrap.com/)
2. Add CSS component via CDN link (Content Delivery Network)
3. Add JQuery component via CDN script reference
4. Add Javascript component via CDN script reference

Once these elements are added on your pages HTML code, you will have access to Bootstrap CSS classes and Javascript effects.

## Bootstrap Grid System

[Documentation - Grid System](https://getbootstrap.com/docs/4.0/layout/grid/)

Bootstrap uses a series of containers or `<divs`> to layout and align content. These containers are assigned a CSS class depending on the expected position:

- **container** - makes a container expand to the total page width
- **row** - makes a container a row in order to contain columns
- **col** - automatically resizes each container at the same level (within a row) to occupy the same space

 You can think of them as boxes, which can contain images, text, or other boxes.

```HTML
<div class="container">
  <div class="row">
    <div class="col-sm">
      One of three columns
    </div>
    <div class="col-sm">
      One of three columns
    </div>
    <div class="col-sm">
      One of three columns
    </div>
  </div>
</div>
```

