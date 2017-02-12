---
layout: post
title: 10 CSS Tips that everyone should know
description: IOC Blog Post
image_path: /assets/images/tina-becky-6238.jpg
alt: CSS TIPS
month: DEC
day: 15
excerpt: 'From how to add background images, to how to style text and even how to change the color of a link on hover these are the 10 essential css properties that you should know.'
author-name: Tina May
author-bio: Co Founder of Institute of Code
author-image_path: /assets/images/tina-profile.jpg
intro: CSS (aka cascading stylesheets) is what controls the visual aspects of the web.
first-content: |
    <p> While parts of CSS can be tricky (we're looking at you positioning!), the basics are pretty easy to understand. The basic css structure looks like this:</p>
    <pre><code class="language-css">selector { property: value; }</code></pre>
    <p> Where we select the elements that we want to style and then apply various properties to them. </p>
banner-image_path: /assets/images/bali_2016-5-1024x681.jpg
banner-image-blurb: 'A little CSS will go along way!'
_comments:
  image_path: featured image for the blog page 400px x 270px
  banner-image_path: 'full-width image, 1280px x 512px'
---


## 1. How to change the color of text

First select the text that you want to change, then apply the color property.

For example, let's say we want to make all paragraphs a shade of purple (#8E44AD). The selector to select all elements is 'p' so we use that and change the color to purple.

<pre><code class="language-css"> p { color: #8E44AD; }</code></pre>

To change all the level 1 headings to blue you would write…

<pre><code class="language-css">h1 { color: #8E44AD; }</code></pre>


Colors can be set using color names, hex codes, and rgb values.

## 2. How to change the background color

To change the background color in css, first select the element you want to style first. If you want to apply the background to the whole page this would be the body.

<pre><code class="language-css">body { background-color: #8E44AD; }</code></pre>


## 3. How to add a background image

To add a background image in css, you use the 'background-image' property (see, we told you it was simple!)

<pre><code class="language-css">body { background-image: url('/images/sunset.png'); }</code></pre>

## 4. How to change the font

There are a couple of fonts that come ready-to-use in every browser (like Helvetica, Georgia, Arial & Verdana), but let's be honest these are pretty ugly. &nbsp;Most of the time you will want to add a custom font using a font provider like google fonts. Before you can use it in your css, you'll need to add the google font to your site ([instructions here](https://designshack.net/articles/css/a-beginners-guide-to-using-google-web-fonts/)).

Once you've done that you can style your text using the font's that you have added (in this example we are using Lato on all the level 2 headings)

<pre><code class="language-css">h2 { font-family: 'Lato'; }</code></pre>


## 5. How to change the boldness of text

To change how thick text is with css, or to make it bold, we use the font-weight property. To change all of our links to be bold, we use the 'anchor link' element with the 'a' selector.

<pre><code class="language-css">a { font-weight: bold; }</code></pre>

If you are using a google font, you might have more options than just normal and bold, some fonts have options from 200 weight to 900 weight.

<pre><code class="language-css">p { font-weight: 300; }</code></pre>

## 6. How to add a border in css

To create a border we need to specify the border thickness, style and color.

<pre><code class="language-css">h1 { border: 1px solid grey; }</code></pre>


## 7. How to create a circle in CSS

To create rounded edges in CSS we use the border-radius property. For example, we could apply a 3px border-radius will round the corners to round the corners of every element with a class of button.

<pre><code class="language-css">.button { border-radius: 3px; }</code></pre>

If we wanted to make circular images, we just need the border radius to be at least 50% and we need to start with a square image (otherwise we'll end up with an oval).

<pre><code class="language-css">img { border-radius: 50%; }</code></pre>

## 8. How to make a link change color on hover

To do this we add ':hover' to the end of our 'a' selector, which tells the browser to only apply this style when it's being hovered.

<pre><code class="language-css">a:hover { color: teal; }</code></pre>

## 9. How to center text

There are two main ways to centre content. If you want to align all the content in a section, you would use…

<pre><code class="language-css">section { text-align: right; }</code></pre>

but if you just wanted to center (remember, US spelling for coding!) your headings you would use…

<pre><code class="language-css">h1, h2, h3 { text-align: center; }</code></pre>

## 10. How to remove the default underline from links

All links by default are blue and have an underline. To reset the styles of the links and style them yourself you might use something like this…

<pre><code class="language-css"> a {
    text-decoration: none;
    color: teal;
    font-weight: bold
}
</code></pre>
