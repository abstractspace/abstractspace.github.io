---
layout: post
title: Test
comments: true
usemathjax: true
---
A much easier way to make posts from my phone is to use termux along with git. 

I just found the website called the Theoretical Minumum. It has a lot of really good lectures on 
physics by Leonard Susskind. I have watched Feynman's lectures on QED available on Youtube and they 
left me wanting to know more. I skipped through some of Dr. Susskind's lecture on Quantum Field Theory 
and learned a lot!

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
<noscript>Please enable JavaScript to view the <a href="https://disqus.com/?ref_noscript">comments powered by Disqus.</a></noscript/>
{% endif %}
