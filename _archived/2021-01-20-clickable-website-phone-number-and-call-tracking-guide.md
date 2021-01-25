---
title: How to Create a Click to Call Link Using HTML and in WordPress
date: 2021-01-01
description: A super simple look at creating a click-to-call link on your website.

featured_image:
---
I never knew this was a problem when I had my Android phone as most phone numbers were clickable by default. But when I switched over to an iPhone, I realized a lot of websites didn't have a click to call link! That meant I had to start copying and pasting phone numbers, adjusting the little select area over the phone number just right to get it. That's not a good solution.

## How to Make a Clickable Phone Number With HTML

1\. Start with a standard link tag:

2\. Enter your phone number with no dashes in the quotes:

<a href="5554280940"></a>

3\. Now the important part, add tel: to the beginning of the number:

<a href="tel:5554280940"></a>

4\. Then finish it up with some text for the link

<a href="tel:5554280940">Call us at 555-428-0940</a>

Here's what you should see: [Call us at 555-428-0940](tel:5554280940) Click the link to make sure it works. If the call goes through, you're done.

## Common HTML Phone Number Link Mistakes

*   Using dashes, which is by far the most common mistake. The number won't always work on every device
*   Forgetting to place a colon after "tel"
*   Forgetting quotes in the HTML

## How to Make a Phone Number Clickable in WordPress

![animated gif showing how to link phone numbers in Wordpress so they can be clicked and called from a mobile phone](https://www.gaintap.com/wp-content/uploads/2017/08/linking-phone-numbers-in-wordpress.gif) More comfortable with the visual tab/WYSIWYG/TinyMCE editor? Here's how you add phone links in Wordpress:

1.  Edit your page or post in Wordpress.
2.  Make sure you're on the Visual tab - not the Text tab.
3.  Highlight the phone number or text you want to make clickable on phones.
4.  Click the "Hyperlink" button.
5.  Enter tel: followed by your phone number with no dashes.
6.  Apply the link.
7.  Update/publish your page or post.

That's it. You're done.

## Adding Google Analytics Event Tracking to HTML Phone Number Links

Here's an easy call tracking solution: combine the above steps with Google Analytics to track click events.

### Example Click to Call Link with Google Analytics Event Tracking:

<a href="tel:5558920234" onclick="ga('send', 'event', { eventCategory: 'Contact', eventAction: 'Call', eventLabel: 'Mobile Button'});"><p class="call-button">Click to Call</p></a>

*   Copy and paste that link code.
*   Swap out the phone number and text.
*   Check Google Analytics under Behavior -> Events -> Overview or Top Events.

### Here's what those clicks look like in Google Analytics:

![screenshot of Google Analytics showing succeessful call events logged in the Behavior panel](https://www.gaintap.com/wp-content/uploads/2017/08/google-analytics-call-event-tracking.jpg) If you're on Wordpress, you may run into issues with Google Analytics and event tracking. I recommend using [Google Tag Manager](https://www.google.com/analytics/tag-manager/) for all tags on Wordpress. You'll need to have some HTML skills, but it simplifies everything.