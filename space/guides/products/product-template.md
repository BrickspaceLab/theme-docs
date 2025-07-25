# Product template

## Space: Using the product template

## Summary <a href="#h_917f41281b" id="h_917f41281b"></a>

***

The product template showcases product details.

## Showing selected variant images <a href="#h_58a19ef41e" id="h_58a19ef41e"></a>

***

Enabling “Show selected variant images only” will update your product pages to only show images assigned to each variant. This is useful if you have products that are visually different. Using this will help show customers which variant they have selected. For example if you have a shirt in blue and red - you can show only the red product photos when customers have selected red.

Enable feature

1. Open the theme editor by clicking Customize next to the relevant theme.
2. From the dropdown in the center of the top bar select Products > Default product.
3. Select Product main from the theme sections.
4. Scroll down and toggle on Show selected variant images only.

Order images

Images must be ordered depending on their variants to ensure they are correctly shown when customers change their selection.

1. Upload all images under media in your product settings.
2. Ensure the images are sorted in the same order as your variants.
3. Assign featured images to each variant that match the first image. The below image will help illustrate how to achieve this.

[![](https://downloads.intercomcdn.com/i/o/1200240051/428ab7d74e2b099e88678e51/Poster-2B-C2-B7-2BProducts-2B-C2-B7-2BBig-2BTote-2B-C2-B7-2BShopify-2B2023-09-06-2B17-32-57.png?expires=1744835400\&signature=0f65c7ef4d0df28a9f39454515875fd982427179ea41f71d764bf62ef05e9ed4\&req=dSInFst6nYFaWPMW1HO4zawhmWSYTI7sTp0mPBsvwwE2itfj%2FJeEo2i5bgSx%0An8Z9SDl5xkRjvIgVWRw%3D%0A)](https://downloads.intercomcdn.com/i/o/1200240051/428ab7d74e2b099e88678e51/Poster-2B-C2-B7-2BProducts-2B-C2-B7-2BBig-2BTote-2B-C2-B7-2BShopify-2B2023-09-06-2B17-32-57.png?expires=1744835400\&signature=0f65c7ef4d0df28a9f39454515875fd982427179ea41f71d764bf62ef05e9ed4\&req=dSInFst6nYFaWPMW1HO4zawhmWSYTI7sTp0mPBsvwwE2itfj%2FJeEo2i5bgSx%0An8Z9SDl5xkRjvIgVWRw%3D%0A)

## Using third-party subscription options <a href="#h_d7f119717b" id="h_d7f119717b"></a>

***

Shopify subscriptions can be a bit tricky to setup. This guide will walk you through different options for displaying subscription options on your product page.

Using the built-in subscription options

Our Shopify themes come with built in subscription options. We recommend using this approach as you'll have more control over the experience and can customize this with the help of a developer.

However, this may cause complications with your product templates if you've already installed a third-party subscription widget.

* Ensure the third party subscription widget is disabled
* Ensure the product block Options is included on your product template

Using third-party subscription options\
​Disabling the default subscription options is possible if you'd like to stick to using a third-party widget. There a few more steps here.

1. Create a new product template. In the theme editor click the top dropdown > Products > Create template. Label this template 'subscription' so you can remembe[r later.](http://later.click/)
2. Click into the Product section then check Enable default selling plan widget
3. Click into the Options block and click Remove block
4. Go into your subscription app and follow instructions to install the subscription widget
5. Assign the 'subscription' product template to all products that have a subscription plan

## Adding a quantity picker to your product template <a href="#h_41a9c39821" id="h_41a9c39821"></a>

***

A quantity input field can be enabled or disabled on product pages. If you aren't seeing a quantity field it's likely it has been disabled in your theme settings.

1. Open the theme editor by clicking Customize next to the relevant theme.
2. From the dropdown in the top bar select Products > Default Product.
3. In the Product section click into the Buy buttons block
4. Scroll down to and enable Show quantity input

## Connect products using the “Combined listing” app <a href="#h_9bf4671177" id="h_9bf4671177"></a>

***

Space has been updated to support the Combined listing app. The app can be used to link multiple product together. Visit the Shopify help center to [learn more about this feature](https://www.shopify.com/enterprise/blog/combined-listings?utm_campaign=winter24edition\&utm_channel=W24-editions-website\&utm_content=W24E\&utm_medium=W24E-page\&utm_source=editions).

## Connect products using the “Linked products” block <a href="#h_8f94db96b2" id="h_8f94db96b2"></a>

***

If you have multiple versions of one product split into different product listing it may be hard for customers to find the option they want. Using the “Linked products” block you can display additional products as options on your product page.

[![](https://downloads.intercomcdn.com/i/o/1200242123/92d6b16c704364588eb25008/CleanShot+2024-10-01+at+11_53_41%402x.png?expires=1744835400\&signature=9cc87d5ffa180ac67de27e621044d8e30a776563db71d0711ef35df308ff620a\&req=dSInFst6n4BdWvMW1HO4zYMKNX0%2F2ntXRaDC1v82PG9n1368tLQghXQWuKf6%0AnloVfZvQ94CGEj2Mb3c%3D%0A)](https://downloads.intercomcdn.com/i/o/1200242123/92d6b16c704364588eb25008/CleanShot+2024-10-01+at+11_53_41%402x.png?expires=1744835400\&signature=9cc87d5ffa180ac67de27e621044d8e30a776563db71d0711ef35df308ff620a\&req=dSInFst6n4BdWvMW1HO4zYMKNX0%2F2ntXRaDC1v82PG9n1368tLQghXQWuKf6%0AnloVfZvQ94CGEj2Mb3c%3D%0A)

Enable the product block

1. Open the theme editor by clicking Customize next to the relevant theme.
2. Navigate to the product template then click "Add block" within the "Product" section
   1.
3. Move the block and add a label
   1. It's usually best to display the "Linked products" block above the "Buy buttons"
   2. Try adding a label that describes the additional linked products. If the additional products are variants of different color you could update the label to "Color".

Create metafield definition

1. Navigate to Settings > Custom data > Products.
2. Click Add definition.
3. In the name field type “Linked collection”.
4. Ensure the namespace and key field is `custom.linked_collection`.
5. Set the data type as "Collection".

Update metafield

1. Navigate to the product you’d like to update.
2. Scroll to the bottom and select a collection for the metafield.
3. Click Save.

## Using the content drawer product block <a href="#h_bd722871fd" id="h_bd722871fd"></a>

***

The Content drawer block allows you to display a link that opens a slide-out drawer. Use it to conveniently showcase product details such as sizing charts or ingredient lists.

[![](https://downloads.intercomcdn.com/i/o/1200253261/641bb08629dcd8343c46bb81/CleanShot+2024-10-01+at+12_01_37%402x.png?expires=1744835400\&signature=877885c95c2f1196193c590f4bdaf848ba6fc6d994afbeec176f575d30c59e59\&req=dSInFst7noNZWPMW1HO4zdHJ4xMKgVQmXM%2FGn7Oi7ia4GokNL4bMW5xd%2BH%2Bb%0AtPWc4o6Rm9XXSfSqtmY%3D%0A)](https://downloads.intercomcdn.com/i/o/1200253261/641bb08629dcd8343c46bb81/CleanShot+2024-10-01+at+12_01_37%402x.png?expires=1744835400\&signature=877885c95c2f1196193c590f4bdaf848ba6fc6d994afbeec176f575d30c59e59\&req=dSInFst7noNZWPMW1HO4zdHJ4xMKgVQmXM%2FGn7Oi7ia4GokNL4bMW5xd%2BH%2Bb%0AtPWc4o6Rm9XXSfSqtmY%3D%0A)[![](https://downloads.intercomcdn.com/i/o/1200240060/02b765f172e1396a38e74748/CleanShot%2B2024-09-30%2Bat%2B16_43_02-402x.png?expires=1744835400\&signature=a03e8085edb78161c3a4269b18b5f5b3883aecbcf6266accdfb8c08d142b57b6\&req=dSInFst6nYFZWfMW1HO4zRARIpXjLIp%2B1%2FaEUkcC%2FBUJ89g%2FBuMZ%2FtOXLkvb%0AbF4mvUl1%2F%2BITFu7xMhw%3D%0A)](https://downloads.intercomcdn.com/i/o/1200240060/02b765f172e1396a38e74748/CleanShot%2B2024-09-30%2Bat%2B16_43_02-402x.png?expires=1744835400\&signature=a03e8085edb78161c3a4269b18b5f5b3883aecbcf6266accdfb8c08d142b57b6\&req=dSInFst6nYFZWfMW1HO4zRARIpXjLIp%2B1%2FaEUkcC%2FBUJ89g%2FBuMZ%2FtOXLkvb%0AbF4mvUl1%2F%2BITFu7xMhw%3D%0A)

1. Open the theme editor by clicking Customize next to the relevant theme.
2. From the dropdown in the top bar select Product.
3. On the lefthand side click Add block then select Content drawer.
4. In the Option, field enter the text that matches the product option you want to display this next to.
   * This is an optional field. Leaving this empty will ensure the block is displayed where the block is placed rather than beside the option.
   * E.g. if you want to display this next to Size then enter ‘size’ in the Option field. If no option is specified this block will be shown in the order it appears in the product template.
5. Add a title and select page content
   * Select a page that uses plain text. If you select a page that has custom sections it may not work within the slide-out drawer.
6. Click Save in the top right



#### Clean Size Charts

If you're looking for a more features to showcase size charts on your product page we recommend [Clean Size Charts](https://apps.shopify.com/size-charts-by-clean-canvas).&#x20;

A powerful tool for creating clean, customizable size charts that look great on any product page. Clean Size Charts automates the setup process by generating measurement guides and size conversions, and it also supports more advanced setups like country-specific charts and multiple size systems—perfect for growing or international stores.



## Using the custom field product block <a href="#h_8ff467d33f" id="h_8ff467d33f"></a>

***

The Custom field product block can be used to add additional fields to a product form. This can be used to collect more information. E.g. include a custom engraving field to let customers customize their purchase.

[![](https://downloads.intercomcdn.com/i/o/1200258122/41dfdf176712d92fd568e26c/CleanShot+2024-10-01+at+12_04_14%402x.png?expires=1744835400\&signature=26743c9614904387fe3befbc67dc94bc7310214c0dc866b0968d9193c960db0a\&req=dSInFst7lYBdW%2FMW1HO4zT1wcC7SLPxPTqhrush40LCH4VkKHsaaP6VgYiHC%0AjfTgWAEN%2BVW7rRnPpxA%3D%0A)](https://downloads.intercomcdn.com/i/o/1200258122/41dfdf176712d92fd568e26c/CleanShot+2024-10-01+at+12_04_14%402x.png?expires=1744835400\&signature=26743c9614904387fe3befbc67dc94bc7310214c0dc866b0968d9193c960db0a\&req=dSInFst7lYBdW%2FMW1HO4zT1wcC7SLPxPTqhrush40LCH4VkKHsaaP6VgYiHC%0AjfTgWAEN%2BVW7rRnPpxA%3D%0A)

1. Open the theme editor by clicking Customize next to the relevant theme.
2. From the dropdown in the top bar select Product.
   1. You may want to create a new product template, if you want your custom field to show up on every product page then you can use the default product template. Otherwise you would want to create a new template.
3. On the lefthand side click Add block then select Custom field.
4. Add a label and check Enable required field if you want to make this a mandatory field to use.
5. Reposition the block - it’s best to place this just above the Buy buttons block.
6. Click Save in the top right.

## Using the bundle block <a href="#h_3e575ba075" id="h_3e575ba075"></a>

***

The bundle product template can be used to sell multiple products from a single page. This can be combined with automatic discounts for an added layer of functionality. To set this up you'll need to create a new metafield definition then assign the bundle template to a new product.

[![](https://downloads.intercomcdn.com/i/o/1200255308/6cb391192766f8a940b3e0fc/CleanShot+2024-10-01+at+12_02_55%402x.png?expires=1744835400\&signature=df37e17e9ce15f00708b5ca217cbf55ebc9824f635ddf96ddea5f2510087dab6\&req=dSInFst7mIJfUfMW1HO4zT3wzsTZlMYbnLHBhG8iC9BQ5VuYhCFkO%2Bg1ivna%0ABZJVHFOXG3Kv5RvYnOY%3D%0A)](https://downloads.intercomcdn.com/i/o/1200255308/6cb391192766f8a940b3e0fc/CleanShot+2024-10-01+at+12_02_55%402x.png?expires=1744835400\&signature=df37e17e9ce15f00708b5ca217cbf55ebc9824f635ddf96ddea5f2510087dab6\&req=dSInFst7mIJfUfMW1HO4zT3wzsTZlMYbnLHBhG8iC9BQ5VuYhCFkO%2Bg1ivna%0ABZJVHFOXG3Kv5RvYnOY%3D%0A)

Create metafield definition

1. Navigate to Settings > Custom data > Products.
2. Click Add definition.
3. In the name field type “Product bundle”
4. Ensure the namespace and key field is `custom.product_bundle`
5. Set the data type as "Product" then select List of products

Create a bundle template

1. In the Shopify theme editor select from the top dropdown "Products".
2. Click Add template.
3. Enter a name.
   1. This can be anything. E.g. "Bundle"
4. Click "Add block" inside the product section.
5. Add "Bundled products" block.
6. Make any other changes to your new template as needed.

Create a bundle product

1. Create a new product on Shopify.
2. Add images as needed - you'll likely want to include photos showcasing all the items in your bundle. Even better if you can get photos of all the products together to really highlight the "bundle" part.
3. Set a price for the product - this should be the sum of all the items in the bundle.
4. Uncheck Track quantity. This product won't actually be purchased itself instead it will act as a landing page where the products within the bundle are purchased.
5. Scroll down to Metafields then click Product bundle.
6. Click Select products and add as many products as you'd like to include in this bundle.
7. On the right-hand side under Theme template select bundle (or a different template that you've created using the "Bundled products" block).
