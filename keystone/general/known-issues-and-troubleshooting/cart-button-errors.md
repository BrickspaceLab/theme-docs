# Cart Button Not Working (Kindred, Keystone)

If "Add to cart" doesn’t work or gives an error (like `Required parameter missing or invalid: items`), here’s how to tackle it:

## Troubleshooting Steps
- Check if button colors are set so they’re visible (Theme Settings > Colors).
- Try a Shopify default theme to rule out app conflicts and custom code problems.
- Temporarily disable third-party apps that deal with cart or product pages.
- If you changed button URLs, clear the Button URL setting fully (add a link, save, then remove and save again).
- Install a fresh, uncustomized theme version to test if a code customization is responsible.

## Developer tip
- The error is almost always due to missing/invalid data in the Liquid template or custom app JavaScript conflicts. Contact your developer or submit a ticket if you’re not sure.

## More help
- [Kindred theme doc](https://help.brickspacelab.com/keystone/general/cloning-a-demo-theme/kindred)  
- [Known issues - v2.0.0](https://help.brickspacelab.com/space/general/known-issues-and-troubleshooting/v2.0.0)
- [How to hide Add to cart buttons](https://help.shopify.com/en/manual/online-store/themes/customizing-themes/common-customizations/hide-add-to-cart-buttons)

Error still there? Take a screenshot and email support. Provide details about any recent theme edits or new apps.