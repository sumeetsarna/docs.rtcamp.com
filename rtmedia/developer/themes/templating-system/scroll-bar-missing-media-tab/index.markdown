---
author: adityakane
comments: false
date: 2014-08-20 07:06:00+00:00
layout: page
slug: scroll-bar-missing-media-tab
title: Scroll bar missing in media tab
wordpress_id: 67434
---

In some of the themes scrollbar is missing in media tab. This issue is encounter with Bootstrap based themes. Add following CSS code in your theme's style.css file to fix this issue.

    
    <code>body.media {
    overflow-y: scroll;
    }</code>
