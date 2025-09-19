# Product template

## Keystone: Using the product template

### Summary

The product template showcases product details and supports various features like Request a Quote, Variant Images, Subscription Options, Linked Products, and more to enhance the customer experience.

### Quantity Picker Support on Product Page vs. Product Grid (FAQ)

**Note:** The "Show quantity input" option is available only in product templates. Keystone and Kindred do _not_ support quantity inputs for product cards or grids by default. This is intended to reduce accidental bulk adds and to simplify product grids. If you want to enable quantity pickers on cards, custom code or app integration is needed.

Single-variant and multi-variant products both show this behavior. For most shops, we recommend customers set quantity from the product page.

---

### Using Request a Quote Block

The Request a Quote block allows customers to request a quote or additional information. It can be used alongside or instead of the Buy Buttons.

### Enable Feature

1. Open the Theme Editor by clicking Customize next to the relevant theme.
2. Navigate to the product you want to modify.
3. Within the Product Template, select Add Block > Quote Form.
4. Customize the button text, content, and success message as needed.

---

### Showing Selected Variant Images

Enabling “Show selected variant images only” ensures that only images assigned to the selected variant are displayed.

### Enable Feature

1. Open the Theme Editor by clicking Customize next to the relevant theme.
2. From the dropdown in the top bar, select Products > Default Product.
3. Select Product Main from the theme sections.
4. Scroll down and toggle on Show selected variant images only.

### Order Images

* Upload all images under Media in your product settings.
* Ensure images are sorted in the same order as your variants.
* Assign featured images to each variant that match the first image.

---

### Using Third-Party Subscription Options

Shopify subscriptions can be tricky to set up. Here are two approaches:

### Using Built-In Subscription Options

1. Ensure the third-party subscription widget is disabled.
2. Ensure the Options block is included on your product template.

### Using Third-Party Subscription Widgets

1. Create a new product template:
   * In the Theme Editor, click the top dropdown > Products > Create Template.
   * Label it `subscription`.
2. Enable the default selling plan widget:
   * Click into the Product Section and check Enable default selling plan widget.
3. Remove the Options block.
4. Install the subscription widget via your third-party app.
5. Assign the `subscription` template to all products with a subscription plan.

---

### Adding a Quantity Picker

A quantity input field can be enabled or disabled on product pages.

**Not available on product cards. See above FAQ.**

### Enable Feature

1. Open the Theme Editor by clicking Customize next to the relevant theme.
2. From the dropdown in the top bar, select Products > Default Product.
3. In the Product Section, click into the Buy Buttons block.
4. Scroll down and enable Show quantity input.

---

### Connect Products Using the “Combined Listing” App

Keystone supports the Combined Listing app, which links multiple products together. Visit the [Shopify Help Center](https://help.shopify.com/) for more details.

### Connect Products Using the “Linked Products” Block

Display additional products as options on your product page.

### Enable the Product Block

1. Open the Theme Editor by clicking Customize next to the relevant theme.
2. Navigate to the product template and click Add Block within the Product Section.
3. Add a label (e.g., `Color`) and reposition the block above the Buy Buttons.

### Create Metafield Definition

1. Navigate to Settings > Custom Data > Products.
2. Click Add Definition.
3. Set Name to `Linked Collection`.
4. Set Namespace and Key to `custom.linked_collection`.
5. Set the data type as Collection.

### Update Metafield

1. Navigate to the product you’d like to update.
2. Scroll to the bottom and select a collection for the metafield.
3. Click Save.

---

### Using the Content Drawer Product Block

The Content Drawer block displays a link that opens a slide-out drawer for additional product details (e.g., sizing charts or ingredient lists).

### Enable Feature

1. Open the Theme Editor by clicking Customize next to the relevant theme.
2. From the dropdown in the top bar, select Product.
3. Click Add Block and select Content Drawer.
4. In the Option field, enter the text that matches the product option you want to display this next to (e.g., `size`).
5. Add a title and select a page with plain text content.
6. Click Save.

#### Clean Size Charts

If you're looking for more features to showcase size charts on your product page we recommend [Clean Size Charts](https://apps.shopify.com/size-charts-by-clean-canvas). A powerful tool for creating clean, customizable size charts that look great on any product page. Clean Size Charts automates the setup process by generating measurement guides and size conversions, and it also supports more advanced setups like country-specific charts and multiple size systems—perfect for growing or international stores.

---

### Using the Custom Field Product Block

The Custom Field block adds additional fields to a product form (e.g., custom engraving).

### Enable Feature

1. Open the Theme Editor by clicking Customize next to the relevant theme.
2. From the dropdown in the top bar, select Product.
3. Click Add Block and select Custom Field.
4. Add a label and check Enable Required Field if needed.
5. Reposition the block above the Buy Buttons.
6. Click Save.

---

### Using the Bundle Block

The Bundle template allows you to sell multiple products from a single page.

### Create Metafield Definition

1. Navigate to Settings > Custom Data > Products.
2. Click Add Definition.
3. Set Name to `Product Bundle`.
4. Set Namespace and Key to `custom.product_bundle`.
5. Set the data type as Product and select List of Products.

### Create a Bundle Template

1. In the Theme Editor, select Products > Add Template.
2. Enter a name (e.g., `Bundle`).
3. Add the Bundled Products block.
4. Customize the template as needed.

### Create a Bundle Product

1. Create a new product in Shopify.
2. Add images showcasing all items in the bundle.
3. Set a price for the bundle.
4. Uncheck Track Quantity.
5. Scroll to Metafields and click Product Bundle.
6. Select the products to include in the bundle.
7. Under Theme Template, select the `bundle` template.

---

### How to Use the 'Table' Block

1. Navigate to a product page in the Theme Editor.
2. Click on your Product Template and select Add Block > Table.
3. This block lets customers easily see all options/variants of a product and add multiple quantities at once.
