---
author: joshuaabenazer
comments: false
date: 2014-01-21 07:34:44+00:00
layout: page
slug: rtp_hook_begin_main_wrapper
title: rtp_hook_begin_main_wrapper
wordpress_id: 10078
---

### Description


Adds content at the beginning of the #main-wrapper.


### Example



    
    function custom_rtp_hook_begin_main_wrapper() { ?>
    <p>This is the beginning of #main-wrapper.</p><?php
    }
    add_action( 'rtp_hook_begin_main_wrapper', 'custom_rtp_hook_begin_main_wrapper' );
