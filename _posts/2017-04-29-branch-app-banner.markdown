---
layout: post
title:  "Branch app banner"
date:   2017-04-28 11:58:30 -0600
categories: jekyll update
extra_head: |
    <script>
    branch.banner({
    icon: 'http://icons.iconarchive.com/icons/wineass/ios7-redesign/512/Appstore-icon.png',
    title: 'Branch Demo App',
    description: 'The Branch demo app!',
    rating: 5,                              // Displays a star rating out of 5. Supports half stars through increments of .5
    reviewCount: 1500,                      // Amount of reviews your app has received next to the star rating
    openAppButtonText: 'Open',              // Text to show on button if the user has the app installed
    downloadAppButtonText: 'Download',      // Text to show on button if the user does not have the app installed
    sendLinkText: 'Send Link',              // Text to show on desktop button to allow users to text themselves the app
    phonePreviewText: '+44 9999-9999',      // The default phone placeholder is a US format number, localize the placeholder number with a custom placeholder with this option
    showiOS: true,                          // Should the banner be shown on iOS devices (both iPhones and iPads)?
    showiPad: true,                         // Should the banner be shown on iPads (this overrides showiOS)?
    showAndroid: true,                      // Should the banner be shown on Android devices?
    showBlackberry: true,                   // Should the banner be shown on Blackberry devices?
    showWindowsPhone: true,                 // Should the banner be shown on Windows Phone devices?
    showKindle: true,                       // Should the banner be shown on Kindle devices?
    showDesktop: true,                      // Should the banner be shown on desktop devices?
    iframe: true,                           // Show banner in an iframe, recomended to isolate Branch banner CSS
    disableHide: false,                     // Should the user have the ability to hide the banner? (show's X on left side)
    forgetHide: false,                      // Should we show the banner after the user closes it? Can be set to true, or an integer to show again after X days
    respectDNT: false,                      // Should we skip showing the banner when a user's settings show 'Do Not Track'?
    mobileSticky: false,                    // Determines whether the mobile banner will be set `position: fixed;` (sticky) or `position: absolute;`, defaults to false *this property only applies when the banner position is 'top'
    desktopSticky: true,                    // Determines whether the desktop banner will be set `position: fixed;` (sticky) or `position: absolute;`, defaults to true *this property only applies when the banner position is 'top'
    make_new_link: false,                   // Should the banner create a new link, even if a link already exists?
    open_app: false,                        // Should the banner try to open the app passively (without the user actively clicking) on load?

    }, {
    tags: ['tag1', 'tag2'],
    feature: 'dashboard',
    stage: 'new user',
    data: {
        mydata: 'something',
        foo: 'bar',
        '$deeplink_path': 'open/item/1234'
    }
    });
    </script>
---
To add new posts, simply add a file in the `_posts` directory that follows the convention `YYYY-MM-DD-name-of-post.ext` and includes the necessary front matter. Take a look at the source for this post to get an idea about how it works.

