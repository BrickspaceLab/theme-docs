# Collection nested menu

## Keystone: Adding a nested menu to a collection

***

### Summary <a href="#h_4151a05ae8" id="h_4151a05ae8"></a>

Nested navigation is useful for large collections with multiple sub-groupings (e.g., "Accessories" with links to "Wallets," "Phone Cases," and "Bags").

***

### Create Metafield Definitions <a href="#h_8713c28b98" id="h_8713c28b98"></a>

1. Open Settings and click Metafields.
2. Click Collections, then click Add Definition.
3. Set Name to `Subcollections`.
4. Set Namespace and Key to `my_fields.subcollections`.
5. Click Select Content Type and choose Single line text.
6. Click Save.

### Add Data to Collection Metafield <a href="#h_6bebd429e6" id="h_6bebd429e6"></a>

1. Open the collection you'd like to add a nested menu to.
2. Scroll to the Metafields area at the bottom.
3. Enter text values formatted as follows:
   * Separate each menu item with `&`.
   * Separate each title and URL with `,`.
   * Example: `Tops,/collections/tops&Bags,/collections/bags&Shorts,/collections/shorts`.
4. Click Save.

