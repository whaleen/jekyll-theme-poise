---
layout: post
title:  "Using Markdown in Poise"
date:   2015-10-21 18:49:14
author: joshuavaage
excerpt: This is a demonstration.
---

Paragraphs are indented. This is common in print and it looks good in Poise due to the horizontally centered nature of the site's design. Without indentations, a sharp vertical line becomes percievable at the left margin of the page. This begins to make the whole page seem unbalanced -- especially when you have long paragraphs.

### A centered image


{:.center .u-max-full-width}
![alt text](/images/example.png "Logo Title Text")

Classes are added to an image in the way shown in the following code example. It is possible to declare these classes due to the use of Kramdown. The `_config.yml` file in this theme has [Kramdown](https://github.com/gettalong/kramdown) set in the build settings for Markdown.


{% highlight ruby %}
{:.center .u-max-full-width}
![alt text](/images/abstract.png "Title Text")
{% endhighlight %}


Moving on, we will have a new paragraph here and in the hopes that it will be lengthy enough to represent the look and feel of a professional blog post author's, we will continue writing without a real purpose other than to fill space with words more carefully than you might with some filler text from a weird generator. This should be enough.

> Quoted text is indented and lightened slightly. You should probably cite the author of an quotation and I do that here while putting the author name in `<em>` tags. - _Joshua Vaage_

##### Other Basic Things

A link will appear <a href="#">as such</a> and you may ad <em>emphaisis</em> to a word in as <strong>boldly</strong> a manner you like. Ok great. Now what else is indented? Why, lists of course. They sit nicely-in from the left margin.

- most
- wonderfully
- listed
