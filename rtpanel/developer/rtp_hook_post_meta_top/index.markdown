---
author: apekshadeshpande
comments: false
date: 2012-04-25 11:35:39+00:00
layout: page
slug: rtp_hook_post_meta_top
title: rtp_hook_post_meta_top
wordpress_id: 3136
---

### Description


Adds content after .post-title. This is mainly used for the post meta.


### Example



    
    function custom_hook_post_meta_top() { ?>
    <p>This is post meta top</p><?php
    }
    add_action( 'rtp_hook_post_meta_top', 'custom_hook_post_meta_top' );
