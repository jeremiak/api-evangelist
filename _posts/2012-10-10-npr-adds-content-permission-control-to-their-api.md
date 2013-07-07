---
layout: post
title: 'NPR Adds Content Permission Control to their API'
url: 'http://apievangelist.com2012/10/10/npr-adds-content-permissions-control-to-their-api/'
image: 'http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/blog/npr-logo.jpeg'
---
{% include JB/setup %}

     <a title="NPR" href="http://www.npr.org/"><img src="https://s3.amazonaws.com/kinlane-productions/api-evangelist/npr/npr-logo.jpeg"  width="200" align="right" /></a>
</p>
<p>
     NPR is defining new models for content distribution. One that other media providers can follow, when designing their API driven content delivery platforms.
</p>
<p>
     The <a href="http://dev.npr.org/">NPR Story API</a> provides digital access to NPR content and to other station content--allowing both NPR and stations to contribute and consume local and national news stories.
</p>
<p>
     In an effort to provide NPR stations with more control over the content they contribute to the platform for distribution, <a href="http://digitalservices.npr.org/post/npr-api-content-permissions-control">NPR Digital Services has introduced content permissions control via the NPR story API</a>.
</p>
<p>
     Currently content stored on the Story API’s platform can be retrieved by anyone with an API key--allowing content pushed across the network to be consumedd in 3 ways:
</p>
<ul >
     <li>
          <strong>Create Once, Publish Everywhere</strong> - Stations and npr.org push content into the API and then pull the content onto other platforms, such as other station-owned web properties and mobile apps
     </li>
     <li>
          <strong>Station Networks</strong> - Content is shared between multiple stations in a content network, both on web sites and mobile apps
     </li>
     <li>
          <strong>National</strong> - Station content is featured on npr.org and NPR mobile apps with links back to station digital properties
     </li>
</ul>
<p>
     Using the new content permissions, stations can now control who is allowed to pull their content from the API. The permissions work by allowing stations pushing content to specify whether the content should be:
</p>
<ul >
     <li>Public to all
     </li>
     <li>Public to the NPR station network
     </li>
     <li>Public to a group of stations listed in a whitelist
     </li>
     <li>Public to everyone except for stations on a blacklist
     </li>
</ul>
<p>
     The new changes allow stations to set these permissions at the individual story level, as well as create permission groups to add multiple stories to.
</p>
<p>
     NPR's approach is a great model for how APIs can facilitate content exchange across a large network of providers, allowing for the widest distribution possible-while also allowing content owners control over who has access to their valuable content in a very granular way.
</p>
<p>
     <img src="https://s3.amazonaws.com/kinlane-productions/api-evangelist/npr/NPR-Digital-Services.png"  width="450" />
</p>
<p>
     APIs are all about providing access to valuable content and resources, but should also be designed to give the proper amount of access, so your content doesn’t end up being consumed, distributed in ways you don’t find appropriate.
</p>
