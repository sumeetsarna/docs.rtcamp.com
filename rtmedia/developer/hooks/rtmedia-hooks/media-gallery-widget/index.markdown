---
author: admin
comments: false
date: 2014-09-05 06:00:27+00:00
layout: page
slug: media-gallery-widget
title: rtMedia Pro- Media gallery widget hooks
wordpress_id: 67486
---

rtMedia pro add-on has widget to display media in sidebar.

rtMedia Pro has provided hooks:

Before Media

    
    <?php do_action ("rtmedia_gallery_widget_before_media", $rt_media_gallery );?>




After Media

    
    <?php do_action("rtmedia_gallery_widget_after_media",$rt_media_gallery);?>




Apply this hook in current theme's function.php file.

example: To show title of each media in sidebar widget,

    
    add_action("rtmedia_gallery_widget_before_media", "my_widget_rtmedia_title",10,1);
    
    function my_widget_rtmedia_title($rt_media_gallery) {
    echo $rt_media_gallery->media_title;
    }
    
    


That's it. Now you can see the title of uploaded media in sidebar widget.

[![Selection_103](http://docs.rtcamp.com/wp-content/uploads/2014/09/Selection_103.png)](http://docs.rtcamp.com/wp-content/uploads/2014/09/Selection_103.png)






