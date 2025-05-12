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

# Collection template

## Keystone: Using the collection template

***

### Summary <a href="#h_d3db8c7a47" id="h_d3db8c7a47"></a>

The collection template is used to display a list of products. It supports grid or list views, customizable filters, and optional blocks for promotions or newsletters.

***

### Tips <a href="#h_6459f466fb" id="h_6459f466fb"></a>

* The collection template can display products in a grid or list view. Customers can switch between these views if enabled.
* Use Shopify’s Search & Discovery app to customize and extend filters for your store.

***

### Customizing Filters for Your Collection Template <a href="#h_112795271e" id="h_112795271e"></a>

### Enable Collection Filters <a href="#h_4ce2072a99" id="h_4ce2072a99"></a>

1. Open the Theme Editor by clicking Customize next to the relevant theme.
2. From the dropdown in the top bar, select Collections > Default Collection.
3. Select Collection Grid from the theme sections.
4. Scroll down under Display and check Enable Filter.

### Enable Collection Sorting <a href="#h_996b2729f7" id="h_996b2729f7"></a>

1. Open the Theme Editor by clicking Customize next to the relevant theme.
2. From the dropdown in the top bar, select Collections > Default Collection.
3. Select Collection Grid from the theme sections.
4. Scroll down under Display and check Enable Sort.

### Customizing Filtering Options <a href="#h_a77dda2981" id="h_a77dda2981"></a>

* Use the Search & Discovery app to adjust and customize filters.

***

### Adding Simple Tag Filtering to a Collection Page <a href="#h_91da1e090e" id="h_91da1e090e"></a>

Tag-based filtering allows you to surface sub-categories within a collection (e.g., filtering "Shirts" to show only products tagged with "shirts").

### Create Metafield Definitions <a href="#h_c08c24e0e9" id="h_c08c24e0e9"></a>

1. Open Settings and click Custom Data.
2. Click Collections, then click Add Definition.
3. Set Name to `Subtags`.
4. Set Namespace and Key to `custom.subtags`.
5. Click Select Content Type and choose Single line text.
6. Select List of values.
7. Click Save.

### Add Data to Collection Metafield <a href="#h_93ef75d6a0" id="h_93ef75d6a0"></a>

1. Open the collection you’d like to add tag filtering to.
2. Scroll to the Metafields area at the bottom.
3. Enter a text value for each tag filter.
   * Note: Do not include "All" as it will be the first link in the tag filtering.
   * Ensure each entry matches a tag present within your collection.
4. Click Save.

***

### Adding a Nested Menu to a Collection <a href="#h_4151a05ae8" id="h_4151a05ae8"></a>

Nested navigation is useful for large collections with multiple sub-groupings (e.g., "Accessories" with links to "Wallets," "Phone Cases," and "Bags").

### Create Metafield Definitions <a href="#h_8713c28b98" id="h_8713c28b98"></a>

1. Open Settings and click Metafields.
2. Click Collections, then click Add Definition.
3. Set Name to `Subcollections`.
4. Set Namespace and Key to `my_fields.subcollections`.
5. Click Select Content Type and choose Single line text.
6. Click Save.

### Add Data to Collection Metafield <a href="#h_6bebd429e6" id="h_6bebd429e6"></a>

1. Open the collection you’d like to add a nested menu to.
2. Scroll to the Metafields area at the bottom.
3. Enter text values formatted as follows:
   * Separate each menu item with `&`.
   * Separate each title and URL with `,`.
   * Example: `Tops,/collections/tops&Bags,/collections/bags&Shorts,/collections/shorts`.
4. Click Save.

***

### Adding Blocks to a Collection Grid <a href="#h_909bdc8144" id="h_909bdc8144"></a>

Optional blocks (e.g., text or newsletter) can be displayed in-grid alongside products to highlight promotions.

1. Open the Theme Editor by clicking Customize next to the theme you’re working on.
2. From the dropdown in the top bar, select Collections > Default Collection.
3. Select Collection Grid from the theme sections.
4. Click Add Block, then select either Newsletter or Content.
5. Click into the newly created block.
6. For the Index field, enter the position number where you want the block to appear in the grid (e.g., `1` for the first item).
7. Update the block content as needed.
8. Click Save.
