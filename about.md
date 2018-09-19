---
layout: page
title: About
comments: true
---

We are busy these days investing in properties, gold , funds etc. Have you ever thought of investing on your own health and your body in which you reside a lifetime? Many of us have begun the trend of investing in Life insurances which benefits our families only. And the maximum we do for our health is to take Health Insurance which is to treat a disease condition that has already taken control of our system. Prevention is better than cure. It's high time we start thinking of our precious health and start investing for it. HEALTH is our real WEALTH. Ayurveda (science of life) not only treats existing diseases but also revitalizes the health of our cells.

**License & Download**

"We, at Pratidhi are here to assist you in this"Process of Prevention”.Our aim is to provide treatment with all *purity* to obtain its desired results.

<a href="https://gum.co/affiliates-jekyll-template" target="_blank">Download - Affiliates Jekyll Theme</a>

![jekyll template mediumish]({{site.baseurl}}/assets/images/theme1.jpg)

![jekyll template mediumish]({{site.baseurl}}/assets/images/theme2.jpg)

![jekyll template mediumish]({{site.baseurl}}/assets/images/theme3.jpg)

![jekyll template mediumish]({{site.baseurl}}/assets/images/theme4.jpg)

#### Features

- Built for Jekyll
- Compatible with Github pages
- Featured Posts
- Index Pagination
- Post Categories
- Prev/Next Link
- Category Archives (this is not yet compatible with github pages though)
- Integrations:
    - Disqus Comments
    - Google Analaytics
    - Mailchimp Integration
    - Sharethis Integration
    - Formspree.io Contact
- Design Features:
    - Bootstrap v4.0.0-alpha.6
    - Font Awesome
    - Masonry
- Layouts:
    - Default
    - Post left sidebar
    - Post right sidebar
    - Page
    - Archive
    
#### How to Use

If you aren't familiar with Jekyll yet, you should know that it is a static site generator. It will transform your plain text into static websites and blogs. If you are a beginner we recommend you start with [Jekyll's Docs](https://jekyllrb.com/docs/installation/){:target="_blank"}. Now if you know how to use Jekyll, let's move on to using Affiliates template in Jekyll:

[Download](https://gum.co/affiliates-jekyll-template){:target="_blank"} or Fork *Affiliates for Jekyll*. 
- In your local project, open <code>_config.yml</code>. If your site is in root, for <code>baseurl</code>, make sure this is set to <code>baseurl: /</code>. Also, change your Google Analytics code, Disqus username, Authors, Mailchimp, ShareThis code (https://www.sharethis.com/) etc.
- Affiliates requires 2 plugins: 
    - <code>$ gem install jekyll-paginate</code>
    - <code>$ gem install jekyll-archives</code>.
- Locate the files and customize:
    - header & footer in <code>default.html</code>. 
    - homepage in <code>index.html</code>
    - contact form in <code>contact.html</code> (https://formspree.io/)
    - post sidebar in <code>includes/sidebar.html</code>
    - sign up form in <code>includes/newsletter.html</code>
- Start blogging by adding your .md files in <code>_posts</code>. You will see in examples in the download.
- YAML front matter
    - post featured - <code>featured:true</code>
    - post featured image - <code>image: assets/images/mypic.jpg</code>
    - page comments - <code>comments:true</code>
    - meta description (optional) - <code>description: "this is my meta description"</code>
    
YAML Post Example:
<pre class="highlight">
---
layout: post
title:  "We all wait for summer"
author: john
categories: [ Jekyll, tutorial ]
image: assets/images/5.jpg
featured: true
---
</pre>

YAML Post Sidebar Right Example:
<pre class="highlight">
---
layout: post-sidebar-right
title:  "We all wait for summer"
author: john
categories: [ Jekyll, tutorial ]
image: assets/images/5.jpg
featured: true
---
</pre>

YAML Page Example
<pre class="highlight">
---
layout: page
title: Affiliates Template for Jekyll
comments: true
---
</pre>