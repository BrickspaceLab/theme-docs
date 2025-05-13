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

# Color and option swatches

## Paper: Using color and option swatches

## Summary <a href="#h_57ddc947af" id="h_57ddc947af"></a>

***

Swatches are used to make variant selections easier and more intuitive for customers when they are selecting an option with color. Swatches appear throughout your theme in various places and can be used with custom images or hex code colors.

[![](https://downloads.intercomcdn.com/i/o/1198999216/c5e368298c8cb17a76e8189a/CleanShot+2024-09-30+at+14_49_28%402x.png?expires=1744675200\&signature=dd2ca759d367b204c62a0ee857321f0fe560733a7cdb508f776d05c85caa16c5\&req=dSEuHsB3lINeX%2FMW1HO4zShqNFntBbJ9MucEWHRzj8XmbBYg925uBxDmxlhm%0A8PJdjV9GatuAv%2FxYqTc%3D%0A)](https://downloads.intercomcdn.com/i/o/1198999216/c5e368298c8cb17a76e8189a/CleanShot+2024-09-30+at+14_49_28%402x.png?expires=1744675200\&signature=dd2ca759d367b204c62a0ee857321f0fe560733a7cdb508f776d05c85caa16c5\&req=dSEuHsB3lINeX%2FMW1HO4zShqNFntBbJ9MucEWHRzj8XmbBYg925uBxDmxlhm%0A8PJdjV9GatuAv%2FxYqTc%3D%0A)

## Using swatch options <a href="#h_d144139bc1" id="h_d144139bc1"></a>

***

In order to display swatches on a product page or within a product card we can use metafield connected variant options. This might sound complicated but it's super easy to setup and works great out of the box.

1. Find a product you want to update.
2. Update the "Category" field to match your product.
3. Add a new option like "Color" or "Material".
4. Ensure the option is connected to a metafield.

From here you'll be able to change the hexcode or image of each swatch by clicking into it.

[![](https://downloads.intercomcdn.com/i/o/fnubgeik/1227082230/9e77bf4331d29a5ca3e0f15035dc/CleanShot%2B2024-09-30%2Bat%2B15_59_06.png?expires=1744675200\&signature=eff0bbed04c7e908cfa6405102e5c64415a87e6aecd0f9f58a1c46a2ff0aa856\&req=dSIlEcl2n4NcWfMW1HO4zQu9dHxYCZ%2FWuAeJmgG5F25jawh1PETKDTolIJ7a%0AHsEp2fr14J7%2BSn23G2Y%3D%0A)](https://downloads.intercomcdn.com/i/o/fnubgeik/1227082230/9e77bf4331d29a5ca3e0f15035dc/CleanShot%2B2024-09-30%2Bat%2B15_59_06.png?expires=1744675200\&signature=eff0bbed04c7e908cfa6405102e5c64415a87e6aecd0f9f58a1c46a2ff0aa856\&req=dSIlEcl2n4NcWfMW1HO4zQu9dHxYCZ%2FWuAeJmgG5F25jawh1PETKDTolIJ7a%0AHsEp2fr14J7%2BSn23G2Y%3D%0A)

## Using swatch filtering <a href="#h_e1f22d47f1" id="h_e1f22d47f1"></a>

***

Your collection page filtering can be customized from the [Shopify Search and Discovery app](https://apps.shopify.com/search-and-discovery). Using this app you can add new filters and customize how they appear on your theme.

### Add swatch filter from metafield <a href="#h_4f300afd17" id="h_4f300afd17"></a>

Shopify has recently made a number of improvements to metafields and how they work with swatches. This is great news for us because now swatches are much easier to manage and update.

Create metaobject for your swatch

1. Navigate to your Shopify settings page then click "Custom data".
2. Scroll down to Metaobject definitions then click "Add definition".
3. Add a name and description to your metaobject.
   * You can use any name or description. E.g. "Swatch"
4. Add three fields to your metaobject.
   * Label, color and image.
   * Label should be a required field using "Single line text" - Make sure to select "List of values" after clicking single line text.
   * Color is not required and uses "Color".
   * Image is not required and uses "File" with "Accepts specific file types - Images" selected.

[![](https://downloads.intercomcdn.com/i/o/1199013221/f0bfa88f67338f41026cd4c4/CleanShot+2024-09-30+at+15_02_09.png?expires=1744675200\&signature=4b7b75711b2a983d0254a499d4dff666b0f1292880398c18d14635dd076adeea\&req=dSEuH8l%2FnoNdWPMW1HO4zftfFCQK5NVFz56VIF5nS1Oqm1VdTzN4ONBCSXKL%0Ax6tGlDy%2FPJB7M9hjTfI%3D%0A)](https://downloads.intercomcdn.com/i/o/1199013221/f0bfa88f67338f41026cd4c4/CleanShot+2024-09-30+at+15_02_09.png?expires=1744675200\&signature=4b7b75711b2a983d0254a499d4dff666b0f1292880398c18d14635dd076adeea\&req=dSEuH8l%2FnoNdWPMW1HO4zftfFCQK5NVFz56VIF5nS1Oqm1VdTzN4ONBCSXKL%0Ax6tGlDy%2FPJB7M9hjTfI%3D%0A)

Create metafield to link to metaobject

We now have to assign values so data is populated for our new metafields.

1. Navigate to your Shopify settings page then click "Custom data".
2. Find and click "Product".
3. Click "Add definition".
4. Add a name and description to your new metafield.
   * You can use any name or description. E.g. "Swatch"
5. Click "Select type" then pick "Metaobject". Make sure to select "List of values" after clicking Metaobject.
6. In the reference field enter the Metaobject you have just created.

[![](https://downloads.intercomcdn.com/i/o/1199020156/018a88a62c1d98289f37369c/CleanShot+2024-09-30+at+15_08_08.png?expires=1744675200\&signature=72080f910c82b6ab43b38fad2923b4897320c61efee19442988f89e153e36b5a\&req=dSEuH8l8nYBaX%2FMW1HO4zR4CtisyDIBtBOdQrcpV1nVDseWt00ALMMD3fCB4%0Ahk0qg8vOYkGZ5sQblk8%3D%0A)](https://downloads.intercomcdn.com/i/o/1199020156/018a88a62c1d98289f37369c/CleanShot+2024-09-30+at+15_08_08.png?expires=1744675200\&signature=72080f910c82b6ab43b38fad2923b4897320c61efee19442988f89e153e36b5a\&req=dSEuH8l8nYBaX%2FMW1HO4zR4CtisyDIBtBOdQrcpV1nVDseWt00ALMMD3fCB4%0Ahk0qg8vOYkGZ5sQblk8%3D%0A)

Assign values to each product

From here you can click into each product and make sure the new metafield is updated to correspond to the relevant options.

1. Find a product you want to update.
2. Scroll down to "Product metafields" and add all the colors you'd like to highlight for this product.

[![](https://downloads.intercomcdn.com/i/o/1199023608/66e6467902828c53fba3a6ae/CleanShot+2024-09-30+at+15_11_13.png?expires=1744675200\&signature=79650f0f8a8358465b40db51dd86276048be34f619edd2ae2509735138fff9cd\&req=dSEuH8l8nodfUfMW1HO4zfZgN1rAVj4HnRrXidQxAnU6eAmgnJVASl6HXlTO%0AF80TTKQHqjws%2FBJcQQc%3D%0A)](https://downloads.intercomcdn.com/i/o/1199023608/66e6467902828c53fba3a6ae/CleanShot+2024-09-30+at+15_11_13.png?expires=1744675200\&signature=79650f0f8a8358465b40db51dd86276048be34f619edd2ae2509735138fff9cd\&req=dSEuH8l8nodfUfMW1HO4zfZgN1rAVj4HnRrXidQxAnU6eAmgnJVASl6HXlTO%0AF80TTKQHqjws%2FBJcQQc%3D%0A)

Connect to filter

Once all your data is place the only thing left is to connect this to your filters.

1. Open the Search and discovery app.
2. Navigate to filters and click "Add filter".
3. Click "Select source" then look for the new product metafield you just created
4. Add a label .
   * You can use any name or description. E.g. "Color" or "Material"
5. Click save.

Caveats of metafield filtering

If you use metafield swatch filtering you'll have to ensure you update your metafields for all products that you want to appear on this filter - this will NOT happen automatically even if category metafields and variant options are displaying swatches.

### Add swatch filter from 'color' option <a href="#h_c284ce1b06" id="h_c284ce1b06"></a>

You can add filters using color product options. This is a easy way to add filters but will require swatch files to be uploaded in a specific format. Swatches will only appear using this approach when the product option matches "color" - or a translation of color.

Add filter using Search and discovery

1. Open the Search and discovery app.
2. Navigate to filters and click "Add filter".
3. Click "Select source" then look for the product option "Color".
   * This is the same approach you would take if you wanted to filter by any other product option like size.
4. Add a label.
   * You can use any name or description. E.g. "Color"
5. Click save.

### &#x20;\*A temporary fix for adjusting color swatch sizing <a href="#h_9af1582f1b" id="h_9af1582f1b"></a>

1. Navigate to your theme editor >Theme settings > Custom css
2.  Within your custom css block paste the following code:\
    ​\
    &#x200B;_&#x46;or color swatches/custom swatches_ (adjust the REM within height and width in increments of .1 for the best results) :

    ```
    .btn.btn--plain {
      height: 2.2rem;
      width: 2.2rem;
    }
    ```

Upload missing swatch files

You may notice that not all of your color filters are appearing with swatches. If this is the case you may have to upload custom swatch files.

Swatches will only appear automatically if the color name matches a default [CSS color](https://help.brickspacelab.com/en/articles/9939903-paper-using-color-and-option-swatches).

1. Identify all swatches that are missing
2. Upload a 64x64 jpg file for each swatch you want to replace.
   * Swatches must be named all lowercase and prepended with “swatch-”. For example, if your color variant is “Electric blue” you would name your file “swatch-electric-blue.jpg”

[![](https://downloads.intercomcdn.com/i/o/1199059028/9b81ef79b3eab4e5c7a8a0f1/CleanShot+2024-09-30+at+15_44_05%402x.png?expires=1744675200\&signature=865ef75493c4357adb8745d08b679bc31f09ee2e86d3418347c5f98a7f08f211\&req=dSEuH8l7lIFdUfMW1HO4zZG9a8CpgkG7LgdzPZ2TeSUoAH3PeZJjjdhOr6X%2B%0ASh0ppqqURG%2BQHX2FSfY%3D%0A)](https://downloads.intercomcdn.com/i/o/1199059028/9b81ef79b3eab4e5c7a8a0f1/CleanShot+2024-09-30+at+15_44_05%402x.png?expires=1744675200\&signature=865ef75493c4357adb8745d08b679bc31f09ee2e86d3418347c5f98a7f08f211\&req=dSEuH8l7lIFdUfMW1HO4zZG9a8CpgkG7LgdzPZ2TeSUoAH3PeZJjjdhOr6X%2B%0ASh0ppqqURG%2BQHX2FSfY%3D%0A)
