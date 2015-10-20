---
layout: post
title:  "New Poise Author"
date:   2015-10-20 18:49:14
author: joshuavaage
excerpt: Add a new Author to Poise. They'll get their own archive page and a lovely profile.
---


##### Step 1: Create Author Details

Open the `_config.yml` file in your site's root directory. This is where your new author's details will be stored and displayed in various places throughout the site -- Places like post footers and the author archive page.


{% highlight yaml %}
authors:
  joshuavaage:
    handle: joshuavaage
    name: Joshua Vaage
    job_title: Front End Developer
    bio: Spent the 80's supervising the production of action figures on Wall Street. Developed several new methods for promoting Roombas with no outside help.
    thumbImg: images/authors/jvaage.jpg
  sarasmith:
    handle: sarasmith
    name: Sara Smith
    job_title: Co-founder and Product Manager
    bio: Earned praised for my work analyzing squirt guns in Los Angeles, CA. Spent college summers merchandising glucose on the black market. Lead a team buying and selling shaving cream in Atlantic City, NJ.
    thumbImg: images/authors/sara_smith.png
{% endhighlight %}

So that's what two authors looks like in the `_config.yml` file. Copy the formatting of an existing author to create a new author and as time goes on you can update these author details as needed. Be sure to follow the formatting of the existing authors, including indentations.

##### Step 2: Profile Image

Now you'll need to add the new author's profile image to the `/images/author/` directory that you referenced in the `_config` file in the previous step. It is recommended you use an image no less than 150X150 pixels square.

##### Step 3: Create Author Page

Create a file in the `/author/` directory named after your new author. See the following author file's contents?

{% highlight yaml %}
---
layout: author
menu: authors
permalink: /author/joshuavaage/
title: Joshua Vaage
handle: joshuavaage
---
{% endhighlight %}

Fairly simple. That's what your author file should look like. No more, no less. You just created the author's new page. No need to change this file ever again. Author details updates will only need to be done in the `_config.yml` file.

##### Step 4: Managing Author's Posts

Please, now this is very important. See `handle: joshuavaage` in the author file in the previous step? The `handle` you see there needs to match what you use as your `author` in your posts. This is what a post looks like:

{% highlight yaml %}
---
layout: post
title:  "New Poise Author"
date:   2015-10-20 18:49:14
author: joshuavaage
excerpt: This is a short but detailed procedure.
---
{% endhighlight %}

The `author` is `joshuavaage` in this post and the `handle` is `joshuavaage` in `/author/joshuavaage`. These being the same insures you author's posts will show up on their author page and elswhere.
