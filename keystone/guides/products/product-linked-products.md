# Sibling products

Keystone supports two methods to display products as swatch options. This is helpful if you want to split one product into seperate listing but maintain visibility for each option. When this is setup customers will see sibling products as options so they can easily select different options or colors.&#x20;

***

### Using the Combined listing app <a href="#h_2bcf225838" id="h_2bcf225838"></a>

The app can be used to link multiple product together. Visit the Shopify help center to [learn more about this feature](https://www.shopify.com/enterprise/blog/combined-listings?utm_campaign=winter24edition\&utm_channel=W24-editions-website\&utm_content=W24E\&utm_medium=W24E-page\&utm_source=editions).

***

### Using the Linked products block <a href="#h_cca672d346" id="h_cca672d346"></a>

If you have multiple versions of one product split into different product listing it may be hard for customers to find the option they want. Using the "Linked products" block you can display additional products as options on your product page.

***

### Enable the product block <a href="#h_85cfff255d" id="h_85cfff255d"></a>

1. Go ton Online Store > Themes > Customize
2. Navigate to the product template then click "Add block" within the "Product" section
3. Move the block and add a label
   * It's usually best to display the "Linked products" block above the "Buy buttons"
   * Try adding a label that describes the additional linked products. If the additional products are variants of different color you could update the label to "Color".
4. Hit **Save**

***

### Create metafield definition <a href="#h_4a7f6a8b39" id="h_4a7f6a8b39"></a>

1. Navigate to **Settings** > **Custom data** > **Products**
2. Click **Add definition**
3. In the name field type "Linked collection"
4. Ensure the namespace and key field is `custom.linked_collection`
5. Set the data type as "Collection"
6. Hit **Save**

***

### Update metafield <a href="#h_dd4b183e2a" id="h_dd4b183e2a"></a>

1. Navigate to the product you'd like to update
2. Scroll to the bottom and select a collection for the metafield
3. Click **Save**

