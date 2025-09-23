# Collection template

## Space: Using the collection template

## Summary <a href="#h_8621a10d14" id="h_8621a10d14"></a>

***

The collection template is used to show a list of products.

## Customizing filters for your collection template <a href="#h_33347f13c4" id="h_33347f13c4"></a>

***

Collection templates in Space are compatible with Shopify's official [Search & Discovery](https://apps.shopify.com/search-and-discovery) app. This app can be used to customize and extend the available filters for your store.

Enable collection filters

Collection filters can be enabled and disabled from the theme editor. If you aren't seeing your filters make sure you have this setting enabled.

1. Open the theme editor by clicking Customize next to the relevant theme.
2. From the dropdown in the center of the top bar select Collections > Default collection.
3. Select Collection grid from the theme sections.
4. Scroll down under Display and check Enable filter

Enable collection sorting

Collection sorting can be enabled and disabled from the theme editor. If you aren't seeing your sort options make sure you have this setting enabled.

1. Open the theme editor by clicking Customize next to the relevant theme.
2. From the dropdown in the center of the top bar select Collections > Default collection.
3. Select Collection grid from the theme sections.
4. Scroll down under Display and check Enable sort

Customizing filtering options

Use the [Search & Discovery](https://apps.shopify.com/search-and-discovery) app to adjust filters.

## Adding simple tag filtering to a collection page <a href="#h_c09f4c10ee" id="h_c09f4c10ee"></a>

***

Using Space you can update collection template to use tag based filtering. This is an easy way to surface sub-categories within a collection. For example, you may have a collection titled Accessories using nested navigation you could then set up links to Wallets, Phone Cases, and Bags.

In this example clicking "Shirts" would filter the current collection to only show products that contain the tag "shirts".

[![](https://downloads.intercomcdn.com/i/o/1200219594/adc75869bc7aba6b78b6f53a/CleanShot+2024-10-01+at+11_38_36%402x.png?expires=1744835400\&signature=1e65d517891b7dac07dec069d997b67e6090337d360ff8fded457d40d380e827\&req=dSInFst%2FlIRWXfMW1HO4zWYeriHoyTzt%2BG3pzSmDpF%2FyUhDh2e%2FZBpfVP7nF%0A8YsdRpaQJniaHa0QQ58%3D%0A)](https://downloads.intercomcdn.com/i/o/1200219594/adc75869bc7aba6b78b6f53a/CleanShot+2024-10-01+at+11_38_36%402x.png?expires=1744835400\&signature=1e65d517891b7dac07dec069d997b67e6090337d360ff8fded457d40d380e827\&req=dSInFst%2FlIRWXfMW1HO4zWYeriHoyTzt%2BG3pzSmDpF%2FyUhDh2e%2FZBpfVP7nF%0A8YsdRpaQJniaHa0QQ58%3D%0A)

Create metafield definitions

1. Open up Settings and click Custom data.
2. Click Collections then click Add definition.
3. Set Name to Subtags.
4. Set Namespace and key to `custom.subtags`.
5. Click Select content type and select Single line text.
6. Click List of values.
7. Click Save.

Add data to collection metafield

1. Open the collection you’d like to add a tag filtering too
2. Scroll to the bottom Metafields area.
3. Enter a text value for each tag filter
   * There's no need to include "All" as that will be the first link within tag filtering
   * Each entry should match a tag that is present within your collection
4. Click Save.

## Adding a nested menu to a collection <a href="#h_cc26f88e6d" id="h_cc26f88e6d"></a>

***

Each collection can be set up with nested navigation. This is useful if you have a large collection with multiple sub-groupings within. For example, you may have a collection titled Accessories using nested navigation you could then set up links to Wallets, Phone Cases, and Bags.

Create metafield definitions

1. Open up Settings and click Metafields.
2. Click Collections then click Add definition.
3. Set Name to Subcollections.
4. Set Namespace and key to `my_fields.subcollections`.
5. Click Select content type and select Single line text.
6. Click Save.

Add data to collection metafield

1. Open the collection you’d like to add a nested menu to
2. Scroll to the bottom Metafields area.
3.  Enter a text value.

    * This text must be formatted in a specific way. Please ensure each menu item is separated by “&” then ensure each title and url for each item is separated by a “,”.
    * This should look something like the below

    ```
    Tops,/collections/tops&
    Bags,/collections/bags&
    Shorts,/collections/shorts
    ```
4. Click Save.

### Adding blocks to a collection grid <a href="#h_1146d2e149" id="h_1146d2e149"></a>

***

The collection template can include optional blocks. These blocks are displayed in-grid alongside your products. This can be used to display a text block or a newsletter. Both of which are great for highlighting ongoing promotions.

[![](https://downloads.intercomcdn.com/i/o/1200224444/911a936c6d69c90ae1d4c026/CleanShot+2024-10-01+at+11_42_15%402x.png?expires=1744835400\&signature=463987a337de3144bdc600caacedb67558e26692ebf5f0e555c9a6b247573696\&req=dSInFst8mYVbXfMW1HO4zUkWg%2BPAnZ6OKNZP2IaO3beuMtfpdzXG%2FQi8n65%2B%0AEL9FDulJtK4XgP5GwIE%3D%0A)](https://downloads.intercomcdn.com/i/o/1200224444/911a936c6d69c90ae1d4c026/CleanShot+2024-10-01+at+11_42_15%402x.png?expires=1744835400\&signature=463987a337de3144bdc600caacedb67558e26692ebf5f0e555c9a6b247573696\&req=dSInFst8mYVbXfMW1HO4zUkWg%2BPAnZ6OKNZP2IaO3beuMtfpdzXG%2FQi8n65%2B%0AEL9FDulJtK4XgP5GwIE%3D%0A)

1. Open the theme editor by clicking "Customize" next to the theme you're working on.
2. From the dropdown in the center of the top bar select Collections > Default collection.
3. Select Collection grid from the theme sections.
4. Click Add Block then select either Newsletter or Content.
5. Click into the newly created block.
6. For the Index field enter the number position you want to display within the collection grid.
   * Entering 1 will ensure this block is displayed as the first item in your grid.
7. Update the content of your block as needed.
8. Click Save.
