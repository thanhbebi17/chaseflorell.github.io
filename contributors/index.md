---
layout: page
title: "Contributors"
date: 2015-04-22 -0700
comments: false
categories: [personal blog]
sharing: false
---

This blog was originally forked from the [drvy/minimal-block](https://github.com/drvy/minimal-block) theme.

The lovely people listed here have contributed directly to my blog. If you want to see yourself in this list, send me a pull request!

Every post in my blog has an edit link that lets you edit the blog post directly in the browser and automatically sends me a pull request. Or you can simply [visit my repository]({{site.github.repository_url}}) and send me a pull request the old fashioned way.

{% for contributor in site.github.contributors %}
  - ![]({{ contributor.avatar_url }}){:height="25px" width="25px"} [{{ contributor.login }}]({{ contributor.html_url }})
{% endfor %}

<sup>*this page was 'borrowed' from [Phil Haack](http://haacked.com)*</sup>
