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

# Collection template

## Customizing filters for your collection template <a href="#h_c21ffc98e1" id="h_c21ffc98e1"></a>

Collection templates in Paper are compatible with Shopify's official [Search & Discovery](https://apps.shopify.com/search-and-discovery) app. This app can be used to customize and extend the available filters for your store.

{% stepper %}
{% step %}
### Enable collection filters

1. Go to **Online Store** > **Themes** > **Customize**
2. From the dropdown in the center of the top bar select **Collections** > **Default** **collection**
3. On the left hand side, select **Collection grid** in the theme sections
4. Scroll down under **Display** and check **Enable filter**
{% endstep %}

{% step %}
### Enable collection sorting

1. Go to **Online Store** > **Themes** > **Customize**
2. From the dropdown in the center of the top bar select **Collections** > **Default** **collection**
3. On the left hand side, select **Collection grid** in the theme sections
4. Scroll down under **Display** and check **Enable sort**
{% endstep %}

{% step %}
### Customizing filtering options

1. Go to the [Search & Discovery](https://apps.shopify.com/search-and-discovery) app to adjust filters
2. Hit **Save**
{% endstep %}
{% endstepper %}

## Adding tag filtering to a collection page <a href="#h_e872ff64e1" id="h_e872ff64e1"></a>

Using Paper you can update collection template to use tag based filtering. This is an easy way to surface sub-categories within a collection. For example, you may have a collection titled Accessories using nested navigation you could then set up links to Wallets, Phone Cases, and Bags.

In this example clicking "Wallets" would filter the current collection to only show products that contain the tag "wallets".

<figure><img src="../.gitbook/assets/tag filter.png" alt=""><figcaption></figcaption></figure>

{% stepper %}
{% step %}
### Create metafield definitions

1. Click **Collections** then click **Add** **definition**
2. Set **Name** to **Subtags**
3. Set **Namespace** and key to `custom.subtags`
4. Click **Select content type** and select **Single line text**
5. Click **List of values**
6. Hit **Save**
{% endstep %}

{% step %}
### Add data to collection metafield

1. Open the collection you’d like to add a tag filtering too
2. Scroll to the bottom **Metafields** area.
3. Enter a text value for each tag filter
   * There's no need to include "All" as that will be the first link within tag filtering
   * Each entry should match a tag that is present within your collection
4. Hit **Save**
{% endstep %}
{% endstepper %}





## Adding a nested menu to a collection <a href="#h_dd72bae66a" id="h_dd72bae66a"></a>

Each collection can be set up with nested navigation. This is useful if you have a large collection with multiple sub-groupings within. For example, you may have a collection titled Accessories using nested navigation you could then set up links to Wallets, Phone Cases, and Bags.

In this example clicking "Elastic" would navigate to a new page loading the "Elastic" collection page.

[![](https://downloads.intercomcdn.com/i/o/1199099544/63f2e36bdd122a2aea0d5730/CleanShot+2024-09-30+at+16_23_07%402x.png?expires=1744682400\&signature=4c5d9a13368a5b114dd7310776cb855a7ca80a4a98ba248657c6b41a8371ece7\&req=dSEuH8l3lIRbXfMW1HO4zYR%2B7dY%2BmS2mc72vnqCuXaUbqa3VDfdXv7ScrQsX%0AIMvxNPwDzRM7PMdE2jg%3D%0A)](https://downloads.intercomcdn.com/i/o/1199099544/63f2e36bdd122a2aea0d5730/CleanShot+2024-09-30+at+16_23_07%402x.png?expires=1744682400\&signature=4c5d9a13368a5b114dd7310776cb855a7ca80a4a98ba248657c6b41a8371ece7\&req=dSEuH8l3lIRbXfMW1HO4zYR%2B7dY%2BmS2mc72vnqCuXaUbqa3VDfdXv7ScrQsX%0AIMvxNPwDzRM7PMdE2jg%3D%0A)

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

## Adding blocks to a collection grid <a href="#h_a6cd48b9a0" id="h_a6cd48b9a0"></a>

***

The collection template can include optional blocks. These blocks are displayed in-grid alongside your products. This can be used to display a text block or a newsletter. Both of which are great for highlighting ongoing promotions.

[![](https://downloads.intercomcdn.com/i/o/1199108757/6cb6ce302434e1ca891ba854/CleanShot+2024-09-30+at+16_33_14%402x.png?expires=1744682400\&signature=efea5fb5d0b6f603788e3062eeb32b7e847145202a7da7e5685fe175bc2991f0\&req=dSEuH8h%2BlYZaXvMW1HO4zRon81P7VX0Vg0kJsktTLR0yhWVr4xkE4VPpCTJH%0AObPX89DBF4XiYMNOZeY%3D%0A)](https://downloads.intercomcdn.com/i/o/1199108757/6cb6ce302434e1ca891ba854/CleanShot+2024-09-30+at+16_33_14%402x.png?expires=1744682400\&signature=efea5fb5d0b6f603788e3062eeb32b7e847145202a7da7e5685fe175bc2991f0\&req=dSEuH8h%2BlYZaXvMW1HO4zRon81P7VX0Vg0kJsktTLR0yhWVr4xkE4VPpCTJH%0AObPX89DBF4XiYMNOZeY%3D%0A)

1. Open the theme editor by clicking "Customize" next to the theme you're working on.
2. From the dropdown in the center of the top bar select Collections > Default collection.
3. Select Collection grid from the theme sections.
4. Click Add Block then select either Newsletter or Content.
5. Click into the newly created block.
6. For the Index field enter the number position you want to display within the collection grid.
   * Entering 1 will ensure this block is displayed as the first item in your grid.
7. Update the content of your block as needed.
8. Click Save.

\
