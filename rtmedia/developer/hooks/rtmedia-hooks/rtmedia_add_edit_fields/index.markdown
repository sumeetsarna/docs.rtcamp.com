---
author: joshuaabenazer
comments: false
date: 2013-09-23 15:00:22+00:00
layout: page
slug: rtmedia_add_edit_fields
title: rtmedia_add_edit_fields
wordpress_id: 46620
---

### Description


Add extra editable fields to be associated with the media.


### Example


Adds a field to enter the Camera used to take the photo. ( Check [rtmedia_after_update_media](https://rtcamp.com/rtmedia/docs/developer/rtmedia-hooks/rtmedia_after_update_media/) )


    
    <code>function custom_rtmedia_camera_build($type) {
        if ( $type == 'photo' ) {
            global $rtmedia_media;
            $id = $rtmedia_media->id;
            $camera = get_rtmedia_meta($id,'camera');
            echo '<br /><br /><label for="camera">Camera</label>  ';
            echo '<input class="camera" id="camera" type="text" name="camera" value="'.$camera.'" />';
        }
    }
    
    add_action('rtmedia_add_edit_fields', 'custom_rtmedia_camera_build');</code>
