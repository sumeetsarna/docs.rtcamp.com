---
author: apekshadeshpande
comments: false
date: 2012-04-25 10:43:41+00:00
layout: page
slug: rtp_header_image_height
title: rtp_header_image_height
wordpress_id: 3087
---

### Description


Modifies the height of the header image under Appearance-> Header. Default is 190.


### Example



    
    function custom_rtp_header_image_height( $height ) {
    return 100;
    }
    add_filter( 'rtp_header_image_height', 'custom_rtp_header_image_height' );
