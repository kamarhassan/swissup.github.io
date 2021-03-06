---
layout: default
title: Easy Banners Admin Interfaces
category: Easy Banners
---

# Admin Interfaces

Easy Banners extension provides user friendly interfaces to manage banners and
placeholders.

* TOC
{:toc}

### Banners

In order to edit banner or create new one, go to
_Magento Admin > Swissup > Easy Banner > Manage Banners_.

![Grid with Banners](/images/m2/easybanners/banner-grid.png)

After clicking on any banner from the submitted list, you will be able to edit
the settings of Banner information.

##### General configuration

![General](/images/m2/easybanners/general.png)

 * Identifier - the name of the banner
 * Type - banner appearance. Possible values are Banner, Lightbox, Awesomebar.
 * Hide url - if you select Yes, the Url will be hidden
 * Target - please select target window to open URL destination. Possible values
    are Popup, Blank or Self.
 * Sort order - Use it to sort multiple banners inside one placeholder
 * Store view - please select target store view for current banner
 * Placeholder - select placeholder for current banner. You can leave it empty to
    show the banner [manually](/m2/extensions/easybanners/usage/#show-banner-on-frontend).
 * Status - enables or disables current banner

##### Banner Content

![Content](/images/m2/easybanners/content.png)

 * Url - sets banner URL (the page which will be opened by clicking on the banner)
 * Css Class - unique banner css class name
 * Mode - please select banner content mode. Possible values are Image or HTML.
 * Image - please upload the image
 * Title - banner title
 * Width, Height - banner dimensions resize image
 * Use image resizer - enabled resize image
 * Retina support - add support for retina display
 * Background Color - background color for resized image
 * Content - please enter html, javascript or flash code, that get html content mode

##### Banner Conditions

![Conditions](/images/m2/easybanners/conditions.png)

Using the following settings, you can place your banner on specific page or show it in specific custom group.

 * Category - places your banner to specific category
 * Clicks Count - allows to display banner for specific clicks count condition
 * Customer Group - shows your banner for specific customer group
 * Date - reserves your banner active during specified date range
 * Display Count - allows to display banner for specific displays count condition
 * Page - places your banner on specific page
 * Product - places your banner on specific product
 * Time - reserves your banner active during specified time range
 * Display Count per Customer - allows to display banner for specific displays count per Customer condition
 * Lightbox/Awesomebar: Customer activity time (seconds)
 * Lightbox/Awesomebar: Customer browsing time (seconds)
 * Lightbox/Awesomebar: Customer inactivity time (seconds)
 * Lightbox/Awesomebar: Scroll offset

##### Banner Statistics

This interface provides overview of banners hits and clicks.

![Statistics](/images/m2/easybanners/statistics.png)

Proceed to [Banner's usage](/m2/extensions/easybanners/usage/#show-banner-on-frontend)
section to see how to show banner on the frontend.

### Placeholders

To edit placeholder or create new one, go to
_Magento Admin > Swissup > Easy Banner > Manage Placeholders_.

![Grid with placeholder](/images/m2/easybanners/placeholder-grid.png)

The placeholders specified above in screenshot, were configured to show banners
on most popular places of Magento store.

After clicking any placeholder from the submitted list, you will be able to
edit the settings of Placeholder General information.

##### General configuration

![Placeholder general settings](/images/m2/easybanners/placeholder_general.png)

 * Placeholder Name - please enter the name of placeholder
 * Banners limit per rotate - please set the number of banners, that will be
    displayed each time
 * Status - allows you to enable or disable the current placeholder

Proceed to [Placeholder's usage](/m2/extensions/easybanners/usage/#show-placeholder-on-frontend)
section to see how to show placeholder on the frontend.

#### Next up
{:.no_toc}

* [Back to Home](/m2/extensions/easybanners/)
* [Banners and Placeholders usage](/m2/extensions/easybanners/usage/)
