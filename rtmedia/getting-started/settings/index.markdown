---
author: adityakane
comments: false
date: 2014-07-03 08:39:02+00:00
layout: page
slug: settings
title: 'Managing Settings (For rtMedia Free Version) '
wordpress_id: 66384
---

*rtMedia* has numerous options that give you absolute control over the way you want to display your media. To make it easy for the admin to tweak the settings,  we have separated them into different categories based on functionality.

**Note**: These are settings for the free version of *rtMedia* plugin. For extended settings with *rtMedia* Pro add-ons refer to the [rtMedia Addons documentation](/rtmedia/addons/).

To access the settings, click **rtMedia** > **Settings** from the admin dashboard of your site.

## Display


[![rtMedia-core-Settings-Display](http://docs.rtcamp.com/wp-content/uploads/2014/07/rtMedia-core-Settings-Display.png)](http://docs.rtcamp.com/wp-content/uploads/2014/07/rtMedia-core-Settings-Display.png)

The **Display** tab allows you to control how media is displayed on your website.

	
  1. Toggle commenting for any single media being viewed by the end-user.

	
  2. Toggle the option to display the media item with a [lightbox effect](http://lokeshdhakar.com/projects/lightbox2/). Further, you can customize the number of media items being displayed. The default value is 10.

	
  3. Toggle the [Masonry Cascading](http://masonry.desandro.com/) grid layout. 


## BuddyPress


[![rtMedia-core-settings-BuddyPress](http://docs.rtcamp.com/wp-content/uploads/2014/07/rtMedia-core-settings-BuddyPress.png)](http://docs.rtcamp.com/wp-content/uploads/2014/07/rtMedia-core-settings-BuddyPress.png)

	
These settings fine tune integration of *rtMedia* with BuddyPress on your WordPress website.

	
  1. Enable or disable media on BuddyPress profiles.

	
  2. Toggle media for BuddyPress groups. This is switched OFF by default.

	
  3. Toggle uploading media from status update box that displays the activity stream with BuddyPress.
  
  4. With bulk uploads, the activity stream can get flooded. To prevent flooding, you can limit the number of media files uploaded per activity. This will not affect the actual number of uploads. The default limit set is "0" which means unlimited.

  5. If **Enable media in profile** (Setting 1) is set to ON, enabling this album setting will add an *Album* tab to your users BuddyPress profiles. Your users can then categorize their media into various albums.


## Types

The three types of media items you can control are Photos, Videos and Audio clips.

[![rtmedia-core-settings-type](http://docs.rtcamp.com/wp-content/uploads/2014/07/rtmedia-core-settings-type.png)](http://docs.rtcamp.com/wp-content/uploads/2014/07/rtmedia-core-settings-type.png)


  1. Toggle uploads of photos, videos and audio clips.

	
  2. Allow or disallow users from setting a featured media file.

## Image Sizes


[![rtMedia-Core-settings-image-sizes](http://docs.rtcamp.com/wp-content/uploads/2014/07/rtMedia-Core-settings-image-sizes.png)](http://docs.rtcamp.com/wp-content/uploads/2014/07/rtMedia-Core-settings-image-sizes.png)

You can easily set the width and height of every type of media being displayed.


  1. Photo files are displayed in three different pre-set sizes, namely Thumbnail, Medium and Large. You can specify the size in pixels for these pre-set sizes. You can also choose to crop the image. These pre-set sizes are used as follows :
  
      * Thumbnail: Used to display the list of photos under the media tab.
      * Medium: Used to display media in activity stream.
      * Large: Used for single media page or for [lightbox display](http://lokeshdhakar.com/projects/lightbox2/).

      **Note**: When you select cropping, the original image is NOT changed. *rtMedia* creates another image of the cropped size to display. If you do not select cropping, *rtMedia* will resize the original image to nearly the specified dimension, preserving the aspect ratio of the image.
	
  2. You can display videos in both the Activity and Single view players. Specify the width and height of the video to be displayed, in pixels.

	
  3. Audio files are also played in both Activity and Single views. You can specify the width of the audio player, to be shown in these views.

	
  4. You can set a custom height and width (in pixels) and enable cropping for featured media files.

	
  5. When a video is uploaded, a few thumbnails are created for it. Specify how many thumbnails should be created for every uploaded video.


## Privacy


[![rtmedia-core-settings-privacy](http://docs.rtcamp.com/wp-content/uploads/2014/07/rtmedia-core-settings-privacy.png)](http://docs.rtcamp.com/wp-content/uploads/2014/07/rtmedia-core-settings-privacy.png)

	
  1. When **Enable Privacy** option is switched ON, you can define access rights for your media items. 

	
  2. Set the default privacy as either *Private*, *Logged in Users* or *Public*.

	
  3. Allow or disallow users from setting access rights for their content.
  
   **Note**: If you bar your users from setting their own access rights for their content, the system wide setting as defined in **Default Privacy** (Setting 2) will be applied to their media items.

## Custom CSS

You can add in [custom CSS](http://www.w3schools.com/css/) code to style *rtMedia*, the way you want. 

[![rtmedia-core-settings-customcss](http://docs.rtcamp.com/wp-content/uploads/2014/07/rtmedia-core-settings-customcss.png)](http://docs.rtcamp.com/wp-content/uploads/2014/07/rtmedia-core-settings-customcss.png)

	
  1. To add your own CSS styling, set **rtMedia default styles** to OFF. Else, your CSS code will not take effect.

	
  2. Enter your custom CSS code.
  
   **Note**: Ensure that your CSS code is valid. *rtMedia* does not validate your code. Entering invalid CSS code can break your site.


## Other Settings


[![rtmedia-core-settings-other](http://docs.rtcamp.com/wp-content/uploads/2014/07/rtmedia-core-settings-other.png)](http://docs.rtcamp.com/wp-content/uploads/2014/07/rtmedia-core-settings-other.png)


  1. Set this to ON to add the *rtMedia* Admin menu to the WordPress Admin bar.

	
  2. Enable this to use [JSON API](/rtmedia/docs/developer/json-api/) to handle API requests sent to *rtMedia* through any mobile application.

	
  3. Keeping this ON helps the *rtMedia* team learn about the theme and plugins you are using. This allows the team to make *rtMedia* more compatible with your websites. 
  
      **Note**: We do not collect, nor does the plugin transmit any private information about your site or infrastructure to us.

	
  4. Setting this to ON will enable *rtMedia* to add a link to the *rtMedia* site in the footer of the theme.

	
  5. If you want to monetize the *rtMedia* footer link, you can add your affiliate-id in the text box. (Check our [rtMedia affiliate program](https://rtcamp.com/affiliates/))


Click **Save Settings** to save the settings.