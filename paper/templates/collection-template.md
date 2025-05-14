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

<figure><img src="../.gitbook/assets/right.png" alt=""><figcaption></figcaption></figure>

{% stepper %}
{% step %}
### Create metafields definitions

1. Go to **Settings** > **Metafields**
2. Click **Collections** then click **Add definition**
3. Set **Name** to **Subcollections**
4. Set **Namespace** and key to `my_fields.subcollections`.
5. Click **Select content type** and choose **Single line text**
6. Click **Save**
{% endstep %}

{% step %}
### Add data to Collection metafield

1. Open the collection you’d like to add a tag filtering too
2. Scroll to the bottom **Metafields** area
3. Enter a text value for each tag filter
   * There's no need to include "All" as that will be the first link within tag filtering
   * Each entry should match a tag that is present within your collection
   * This text must be formatted in a specific way. Please ensure each menu item is separated by “&” then ensure each title and url for each item is separated by a “,”.
   * It should look something like this:
     * <pre><code><strong>Tops,/collections/tops&#x26;Bags,/collections/bags&#x26;Shorts,/collections/short
       </strong></code></pre>
4. Click **Save**
{% endstep %}
{% endstepper %}

## Adding blocks to a collection grid <a href="#h_a6cd48b9a0" id="h_a6cd48b9a0"></a>

The collection template can include optional blocks. These blocks are displayed in-grid alongside your products. This can be used to display a text block or a newsletter. Both of which are great for highlighting ongoing promotions

<figure><img src="../.gitbook/assets/highlights.png" alt=""><figcaption></figcaption></figure>

{% stepper %}
{% step %}
Go to **Online Store** > **Themes** > **Customize**
{% endstep %}

{% step %}
From the dropdown in the center of the top bar select **Collections** > **Default collection**
{% endstep %}

{% step %}
Select **Collection grid** from the theme sections
{% endstep %}

{% step %}
Click **Add Block** then select either **Newsletter** or **Content**.
{% endstep %}

{% step %}
Click into the newly created block
{% endstep %}

{% step %}
For the Index field enter the number position you want to display within the collection grid.

* Entering 1 will ensure this block is displayed as the first item in your grid.
{% endstep %}

{% step %}
Update the content of your block as needed
{% endstep %}

{% step %}
Hit **Save**
{% endstep %}
{% endstepper %}

\
