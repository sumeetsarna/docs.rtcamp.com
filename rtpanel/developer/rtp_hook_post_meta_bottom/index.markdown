---
author: apekshadeshpande
comments: false
date: 2012-04-25 11:36:17+00:00
layout: page
slug: rtp_hook_post_meta_bottom
title: rtp_hook_post_meta_bottom
wordpress_id: 3138
---

### Description


Adds content after .post-content. This is mainly used for the post meta.


### Example



    
    function custom_hook_post_meta_bottom() { ?>
    <p>This is post meta bottom</p><?php
    }
    add_action( 'rtp_hook_post_meta_bottom', 'custom_hook_post_meta_bottom' );
