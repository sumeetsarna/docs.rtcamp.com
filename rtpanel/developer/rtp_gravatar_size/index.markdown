---
author: manish.songirkar
comments: false
date: 2014-02-07 11:05:44+00:00
layout: page
slug: rtp_gravatar_size
title: rtp_gravatar_size
wordpress_id: 57103
---

Modify author gravatar size on comment list.

    
    function custom_rtp_gravatar_size() {
        return 64;
    }
    add_filter( 'rtp_gravatar_size', 'custom_rtp_gravatar_size' );
