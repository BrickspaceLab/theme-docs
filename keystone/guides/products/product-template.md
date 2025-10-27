# Product template

## Keystone: Using the product template

***

### Summary <a href="#h_b71da50146" id="h_b71da50146"></a>

The product template showcases product details and supports various features like Request a Quote, Variant Images, Subscription Options, Linked Products, and more to enhance the customer experience.

***

### Using Request a Quote Block <a href="#h_7990575f3a" id="h_7990575f3a"></a>

The Request a Quote block allows customers to request a quote or additional information. It can be used alongside or instead of the Buy Buttons.

### Enable Feature <a href="#h_0b58de060a" id="h_0b58de060a"></a>

1. Open the Theme Editor by clicking Customize next to the relevant theme.
2. Navigate to the product you want to modify.
3. Within the Product Template, select Add Block > Quote Form.
4. Customize the button text, content, and success message as needed.

***

### Showing Selected Variant Images <a href="#h_9a05d6e01b" id="h_9a05d6e01b"></a>

Enabling “Show selected variant images only” ensures that only images assigned to the selected variant are displayed.

### Enable Feature <a href="#h_bd3747789e" id="h_bd3747789e"></a>

1. Open the Theme Editor by clicking Customize next to the relevant theme.
2. From the dropdown in the top bar, select Products > Default Product.
3. Select Product Main from the theme sections.
4. Scroll down and toggle on Show selected variant images only.

### Order Images <a href="#h_3660d186b1" id="h_3660d186b1"></a>

* Upload all images under Media in your product settings.
* Ensure images are sorted in the same order as your variants.
* Assign featured images to each variant that match the first image.

***

### Using Third-Party Subscription Options <a href="#h_6ca5a0259a" id="h_6ca5a0259a"></a>

Shopify subscriptions can be tricky to set up. Here are two approaches:

### Using Built-In Subscription Options <a href="#h_10340383b3" id="h_10340383b3"></a>

1. Ensure the third-party subscription widget is disabled.
2. Ensure the Options block is included on your product template.

### Using Third-Party Subscription Widgets <a href="#h_0f926d6c18" id="h_0f926d6c18"></a>

1. Create a new product template:
   * In the Theme Editor, click the top dropdown > Products > Create Template.
   * Label it `subscription`.
2. Enable the default selling plan widget:
   * Click into the Product Section and check Enable default selling plan widget.
3. Remove the Options block.
4. Install the subscription widget via your third-party app.
5. Assign the `subscription` template to all products with a subscription plan.

***

### Adding a Quantity Picker <a href="#h_c8f7cbdc9b" id="h_c8f7cbdc9b"></a>

A quantity input field can be enabled or disabled on product pages.

### Enable Feature <a href="#h_0562ecf317" id="h_0562ecf317"></a>

1. Open the Theme Editor by clicking Customize next to the relevant theme.
2. From the dropdown in the top bar, select Products > Default Product.
3. In the Product Section, click into the Buy Buttons block.
4. Scroll down and enable Show quantity input.

***

### Connect Products Using the “Combined Listing” App <a href="#h_782ee35ca9" id="h_782ee35ca9"></a>

Keystone supports the Combined Listing app, which links multiple products together. Visit the [Shopify Help Center](https://help.shopify.com/) for more details.

***

### Connect Products Using the “Linked Products” Block <a href="#h_55732fe810" id="h_55732fe810"></a>

Display additional products as options on your product page.

### Enable the Product Block <a href="#h_85cfff255d" id="h_85cfff255d"></a>

1. Open the Theme Editor by clicking Customize next to the relevant theme.
2. Navigate to the product template and click Add Block within the Product Section.
3. Add a label (e.g., `Color`) and reposition the block above the Buy Buttons.

### Create Metafield Definition <a href="#h_4a7f6a8b39" id="h_4a7f6a8b39"></a>

1. Navigate to Settings > Custom Data > Products.
2. Click Add Definition.
3. Set Name to `Linked Collection`.
4. Set Namespace and Key to `custom.linked_collection`.
5. Set the data type as Collection.

### Update Metafield <a href="#h_dd4b183e2a" id="h_dd4b183e2a"></a>

1. Navigate to the product you’d like to update.
2. Scroll to the bottom and select a collection for the metafield.
3. Click Save.

***

### Using the Content Drawer Product Block <a href="#h_965f789548" id="h_965f789548"></a>

The Content Drawer block displays a link that opens a slide-out drawer for additional product details (e.g., sizing charts or ingredient lists).

### Enable Feature <a href="#h_83e23f3648" id="h_83e23f3648"></a>

1. Open the Theme Editor by clicking Customize next to the relevant theme.
2. From the dropdown in the top bar, select Product.
3. Click Add Block and select Content Drawer.
4. In the Option field, enter the text that matches the product option you want to display this next to (e.g., `size`).
5. Add a title and select a page with plain text content.
6. Click Save.



#### Clean Size Charts

If you're looking for a more features to showcase size charts on your product page we recommend [Clean Size Charts](https://apps.shopify.com/size-charts-by-clean-canvas).&#x20;

A powerful tool for creating clean, customizable size charts that look great on any product page. Clean Size Charts automates the setup process by generating measurement guides and size conversions, and it also supports more advanced setups like country-specific charts and multiple size systems—perfect for growing or international stores.

***

### Using the Custom Field Product Block <a href="#h_c945d0359a" id="h_c945d0359a"></a>

The Custom Field block adds additional fields to a product form (e.g., custom engraving).

### Enable Feature <a href="#h_ca60ff3207" id="h_ca60ff3207"></a>

1. Open the Theme Editor by clicking Customize next to the relevant theme.
2. From the dropdown in the top bar, select Product.
3. Click Add Block and select Custom Field.
4. Add a label and check Enable Required Field if needed.
5. Reposition the block above the Buy Buttons.
6. Click Save.

***

### Using the Bundle Block <a href="#h_3c5b447082" id="h_3c5b447082"></a>

The Bundle template allows you to sell multiple products from a single page.

### Create Metafield Definition <a href="#h_c88d8aca90" id="h_c88d8aca90"></a>

1. Navigate to Settings > Custom Data > Products.
2. Click Add Definition.
3. Set Name to `Product Bundle`.
4. Set Namespace and Key to `custom.product_bundle`.
5. Set the data type as Product and select List of Products.

### Create a Bundle Template <a href="#h_54c57da661" id="h_54c57da661"></a>

1. In the Theme Editor, select Products > Add Template.
2. Enter a name (e.g., `Bundle`).
3. Add the Bundled Products block.
4. Customize the template as needed.

### Create a Bundle Product <a href="#h_cd4411e9a0" id="h_cd4411e9a0"></a>

1. Create a new product in Shopify.
2. Add images showcasing all items in the bundle.
3. Set a price for the bundle.
4. Uncheck Track Quantity.
5. Scroll to Metafields and click Product Bundle.
6. Select the products to include in the bundle.
7. Under Theme Template, select the `bundle` template.

***

### How to Use the 'Table' Block <a href="#h_cc9b058e01" id="h_cc9b058e01"></a>

1. Navigate to a product page in the Theme Editor.
2. Click on your Product Template and select Add Block > Table.
3. This block lets customers easily see all options/variants of a product and add multiple quantities at once.
