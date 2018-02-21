---
layout: post
title:  "How i Implemented comments on my blogposts !"
date:   2018-01-25 03:00:43 -0500
categories: jekyll update

---
I have implemented comments by using Disqus, althought I had a lot of problem implementing it since it do not want to work as it should so in the end 
I solved it in a really ugly way by just putting the HTML code straight into my .md files. 
I have had problem with it not showing up at all and when I get it so that I can see it it shows the code and not de commenting field so I solved the only way I figured out. 
I tried implementing it thorough includes and layout as the tutorials shows at youtube but unfortunately it does not work for me this way.


<div id="disqus_thread"></div>
<script>

(function() { // DON'T EDIT BELOW THIS LINE
var d = document, s = d.createElement('script');
s.src = 'https://http-assignment1-martina261482-codeanyapp-com-4000.disqus.com/embed.js';
s.setAttribute('data-timestamp', +new Date());
(d.head || d.body).appendChild(s);
})();
</script>
<noscript>Please enable JavaScript to view the <a href="https://disqus.com/?ref_noscript">comments powered by Disqus.</a></noscript>
