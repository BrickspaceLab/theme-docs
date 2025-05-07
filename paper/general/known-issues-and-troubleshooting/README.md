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
    visible: true
---

# Known issues and troubleshooting

### Prices displaying incorrectly <a href="#h_a46871a2d3" id="h_a46871a2d3"></a>

***

* If your shipping settings aren't configured for a given region the products will not display prices and variants correctly.
* To resolve this: Navigate to your 'Market' tab within your Shopify admin settings > Ensure your shipping settings are configured.
* Prices displaying incorrectly when “Show trailing zeros” is unchecked: This setting is not supported in all currencies. If this is causing issues we recommend keeping it checked.

#### Compare-at price displaying incorrectly <a href="#h_86d0205449" id="h_86d0205449"></a>

***

Why does the % discounted badge and strikeout price disappear when changing from the store default currency (GBP) to another currency?

* This issue is related to your 'Market' settings within your Shopify admin.
* To resolve it: Navigate to your Shopify admin page, click on 'Settings' in the bottom left, then 'Markets', and finally 'Preferences'. Toggle off 'Compare-at price hiding'.\
  ​

#### Products won't add to cart <a href="#h_ab045038a5" id="h_ab045038a5"></a>

***

There are a few reasons your products may not be successfully adding to cart. Here are some common troubleshooting tips:

* Check your inventory and stock settings. You can try using "Continue selling when sold out" to ensure items can be added
* Ensure the "Options" block is included on your product template. This block is required even if your product has only one variant.
* Try checking "Enable default variant"

#### Broken product grid <a href="#h_c43ac95083" id="h_c43ac95083"></a>

***

The collection grid comes with blocks that can be set to expand into multiple rows. This can cause your layout to break if you set the blocks to span across more rows then exist.

To fix this follow the below steps

1. Open the theme editor by clicking Customize next to the relevant theme.
2. Navigate to the collection template using the dropdown in the top bar.
3. Click into the Collection grid section and take note of your row settings.
4. Click into the blocks under your Collection grid and ensure the span is not larger than your row size. (E.g. in the above screenshot the desktop row size is 4, and the mobile row size is 2. This means each block must use a row span of 2 or lower)

#### Broken blog grid <a href="#h_b026b453cc" id="h_b026b453cc"></a>

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

#### Empty buttons <a href="#h_da9acb4de5" id="h_da9acb4de5"></a>

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

#### Missing login buttons <a href="#h_16753f9e17" id="h_16753f9e17"></a>

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

\
