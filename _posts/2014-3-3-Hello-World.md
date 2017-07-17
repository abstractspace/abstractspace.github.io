---
layout: post
title: You're up and running!
comments: true
---

This is my first post, hopefully more will follow...

Next you can update your site name, avatar and other options using the _config.yml file in the root of your repository (shown below).

![_config.yml]({{ site.baseurl }}/images/config.png)

The easiest way to make your first post is to edit this one. Go into /_posts/ and update the Hello World markdown file. For more instructions head over to the [Jekyll Now repository](https://github.com/barryclark/jekyll-now) on GitHub.

<img src="{{ site.baseurl }}/images/me.jpg" alt="Drawing" style="width: 200px;"/>

[Jekyll guide](https://www.smashingmagazine.com/2014/08/build-blog-jekyll-github-pages/)

[Markdwn cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)

{% if page.comments %}

<div id="disqus_thread"></div>
<script>

var disqus_config = function () {
this.page.url = page.url;  // Replace PAGE_URL with your page's canonical URL variable
this.page.identifier = page.id; // Replace PAGE_IDENTIFIER with your page's unique identifier variable
};

(function() { // DON'T EDIT BELOW THIS LINE
var d = document, s = d.createElement('script');
s.src = 'https://https-abstractspace-github-io.disqus.com/embed.js';
s.setAttribute('data-timestamp', +new Date());
(d.head || d.body).appendChild(s);
})();
</script>
<noscript>Please enable JavaScript to view the <a href="https://disqus.com/?ref_noscript">comments powered by Disqus.</a></noscript>
                            
{% endif %}