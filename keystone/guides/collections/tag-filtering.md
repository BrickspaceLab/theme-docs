# Adding Simple Tag Filtering to a Collection Page

## Keystone: Using tag-based filtering

***

### Summary <a href="#h_91da1e090e" id="h_91da1e090e"></a>

Tag-based filtering allows you to surface sub-categories within a collection (e.g., filtering "Shirts" to show only products tagged with "shirts").

***

### Create Metafield Definitions <a href="#h_c08c24e0e9" id="h_c08c24e0e9"></a>

1. Open Settings and click Custom Data.
2. Click Collections, then click Add Definition.
3. Set Name to `Subtags`.
4. Set Namespace and Key to `custom.subtags`.
5. Click Select Content Type and choose Single line text.
6. Select List of values.
7. Click Save.

***

### Add Data to Collection Metafield <a href="#h_93ef75d6a0" id="h_93ef75d6a0"></a>

1. Open the collection you'd like to add tag filtering to.
2. Scroll to the Metafields area at the bottom.
3. Enter a text value for each tag filter.
   * Note: Do not include "All" as it will be the first link in the tag filtering.
   * Ensure each entry matches a tag present within your collection.
4. Click Save.

