---
layout:
  title:
    visible: true
  description:
    visible: true
  tableOfContents:
    visible: true
  outline:
    visible: true
  pagination:
    visible: false
---

# Known issues and troubleshooting

### Prices displaying incorrectly <a href="#h_687b49a85e" id="h_687b49a85e"></a>

***

* If your shipping settings aren't configured for a given region the products will not display prices and variants correctly.
* To resolve this: Navigate to your 'Market' tab within your Shopify admin settings > Ensure your shipping settings are configured.
* Prices displaying incorrectly when “Show trailing zeros” is unchecked: This setting is not supported in all currencies. If this is causing issues we recommend keeping it checked.

### &#x20;Compare-at price displaying incorrectly <a href="#h_320a7520ff" id="h_320a7520ff"></a>

***

Why does the % discounted badge and strikeout price disappear when changing from the store default currency (GBP) to another currency?

* This issue is related to your 'Market' settings within your Shopify admin.
* To resolve it: Navigate to your Shopify admin page, click on 'Settings' in the bottom left, then 'Markets', and finally 'Preferences'. Toggle off 'Compare-at price hiding'.

### Products won't add to cart <a href="#h_2408f4102e" id="h_2408f4102e"></a>

***

There are a few reasons your products may not be successfully adding to cart. Here are some common troubleshooting tips:

* Check your inventory and stock settings. You can try using "Continue selling when sold out" to ensure items can be added
* Ensure the "Options" block is included on your product template. This block is required even if your product has only one variant.
* Try checking "Enable default variant".

#### Broken blog grid <a href="#h_e39d864ffa" id="h_e39d864ffa"></a>

***

The blog grid can break when you have "Enable summary" turned on and your blog article has extra HTML. If there's extra content in your blog grid with malformed HTML this can sometimes break the blog grid.

To fix this follow the below steps:

1. Open the theme editor by clicking Customize next to the relevant theme.
2. Go to your blog settings in Theme settings > Blog cards.
3. Uncheck "Enable summary" and click save.

OR if you want to continue to show your summary, you'll have to revise the formatting of your blog article.

1. Open up your blog article and copy the entire contents of your article.
2. Paste your article into a markdown text editor. For something like this you can use Notion
3. Copy the content from your markdown editor and paste it over your blog content.

#### Empty buttons <a href="#h_5cfe7a31c0" id="h_5cfe7a31c0"></a>

***

Shopify theme sections come pre-loaded with placeholder content. This can sometimes get in the way if you’d like to remove something. We’ve noticed this issue where buttons are sticking around when they should be hidden.

To remove a button follow the below steps:

1. Open the theme editor by clicking Customize next to the relevant theme.
2. Select the section you want to edit
3. Scroll down to the Button and Button URL settings
4. Delete both of the values here so the fields are empty
5. Click Save

If the above does not work you may need to add a link and remove it for Shopify to catch that the settings have been changed.

1. Add any link to the Button URL setting
2. Click Save
3. Scroll down to the Button and Button URL settings
4. Delete both of the values here so the fields are empty
5. Click Save

#### Missing login buttons <a href="#h_baf27f4f93" id="h_baf27f4f93"></a>

***

When you just start setting up your Shopify account you may notice login and account buttons are not visible on your site. Thankfully this is usually a very easy fix.

\
To ensure your login buttons are showing correctly you must first enable customer accounts on your Shopify account.

1. Navigate to the main Shopify Settings > Customer accounts.
2. Ensure you have customer accounts enabled.

From here you have a few options to display the login and account buttons throughout your theme. Depending on which theme you're using you should find options to show or hide account buttons from the following sections

* From within the Announcement
* From within the Header
* From within the Mobile menu
* From within the Footer
