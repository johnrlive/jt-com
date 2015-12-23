---
layout: default
permalink: /use-cloudflare-301-redirect-website/
title: "How to Use Cloudflare to 301 Redirect an Entire Website"
seotitle: "How to Use Cloudflare to 301 Redirect an Entire Website"
description: 
sitemap:
  exclude: 'yes'
---
I recently had two websites, Buy Bitcoin Worldwide and No Third Party, which needed to be merged. No Third Party would have its content moved to the Buy Bitcoin Worldwide domain. I spent some time messing around with the .htaccess file, but knew there had to be an easier way. 

No Third Party was already setup with Cloudflare in order to add an HTTPS certificate. Using Cloudflare page rules, I was able to redirect the entire site to Buy Bitcoin Worldwide via 301 redirects. 