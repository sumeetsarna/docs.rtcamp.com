---
author: manish.songirkar
comments: false
date: 2014-02-07 10:39:41+00:00
layout: page
slug: rtp_email_placeholder
title: rtp_email_placeholder
wordpress_id: 10289
---

Modify email placeholder text in comment form.

    
    function custom_rtp_email_placeholder() {
        return "Enter Email Here";
    }
    add_filter( 'rtp_email_placeholder', 'custom_rtp_email_placeholder' );
