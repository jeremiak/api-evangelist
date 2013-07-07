---
layout: post
title: 'Wrapping URLs for Another Layer of Metrics in Your API'
url: 'http://apievangelist.com2012/05/26/wrapping-content-urls-for-another-layer-of-metrics-in-your-api/'
image: 'http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/blog/turn-long-short.jpg'
---
{% include JB/setup %}

     <img src="http://kinlane-productions.s3.amazonaws.com/api-evangelist/url-wrapping-metrics.png"  width="250" align="right" />
</p>
<p>
     I’m documenting Twitter’s process of wrapping the URLs contained within tweets, using a shorter URL like t.co. I’m interested in understanding the opportunities around URL wrapping (aka URL shortening) as an API business strategy.
</p>
<p>
     From an API business perspective, the reasoning for implementing URL wrapping as part of your API would be:
</p>
<ul >
     <li>
          <strong>Saving Space</strong> - By shortening URLs you are reducing the length of any string that contains URLs, and in cases like Twitters, every character counts
     </li>
     <li>
          <strong>Security</strong> - Twitter is actively combating URLs that carry malicious intent
     </li>
     <li>
          <strong>Analytics</strong> - Each shortened URL provides a mechanism for tracking clicks on URL within content
     </li>
</ul>
<p>
     Shold URL wrapping be something API owners adopt for all content served up via an API? Could every URL within content served up via an API be wrapped, allowing tracking of clicks through that URL--no matter where that content ended up living after it left the API?
</p>
<p>
     Just some initial thoughts, but it seems that a comprehensive linking strategy could be established, bundled with a URL shortening service like <a href="https://bitly.com/">Bit.ly</a>, <a href="http://goo.gl/">Google URL Shortener</a> or a custom service--and provide a new layer of metrics that could be used to tell how your developers and their application users are interacting with the content you serve up via your API.
</p>
