---
layout: post
title:  "New Poise Author"
date:   2015-10-20 18:49:14
author: sarasmith
excerpt: This is a short but detailed procedure.
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

So that's what two authors looks like in the `_config.yml` file. Copy the formatting of an existing author to create a new author and as time goes on you can update these author details as needed. Be sure to follow the formatting of the existing authors including indentations.

##### Step 2: Profile Image

Now you'll need to add the new author's profile image to the `/images/author/` directory that you referenced in the `_config` file.

You’ll find this post in your `_posts` directory. Go ahead and edit it and re-build the site to see your changes. You can rebuild the site in many different ways, but the most common way is to run `jekyll serve`, which launches a web server and auto-regenerates your site when a file is updated.

To add new posts, simply add a file in the `_posts` directory that follows the convention `YYYY-MM-DD-name-of-post.ext` and includes the necessary front matter. Take a look at the source for this post to get an idea about how it works.

Jekyll also offers powerful support for code snippets:

{% highlight ruby %}
def print_hi(name)
  puts "Hi, #{name}"
end
print_hi('Tom')
#=> prints 'Hi, Tom' to STDOUT.
{% endhighlight %}

Check out the [Jekyll docs][jekyll] for more info on how to get the most out of Jekyll. File all bugs/feature requests at [Jekyll’s GitHub repo][jekyll-gh]. If you have questions, you can ask them on [Jekyll’s dedicated Help repository][jekyll-help].

[jekyll]:      http://jekyllrb.com
[jekyll-gh]:   https://github.com/jekyll/jekyll
[jekyll-help]: https://github.com/jekyll/jekyll-help
