---
author: manish.songirkar
comments: false
date: 2014-02-07 10:55:13+00:00
layout: page
slug: rtp_image_sibling_count
title: rtp_image_sibling_count
wordpress_id: 10283
---

Modify images sibling count on image attachment page template, default is 10.

    
    function custom_rtp_image_sibling_count() {
        return 20;
    }
    add_filter( 'rtp_image_sibling_count', 'custom_rtp_image_sibling_count' );
