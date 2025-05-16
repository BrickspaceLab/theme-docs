# Known issues and troubleshooting

A guide to known issues, temporary fixes, and troubleshooting steps for our Shopify themes. We maintain this documentation to help you resolve common problems and provide workarounds while we work on permanent solutions.

<details>

<summary><strong>Known issues - Keystone 1.3.0</strong></summary>

#### Prices Displaying Incorrectly <a href="#h_9b9f33b7e3" id="h_9b9f33b7e3"></a>

***

* Issue: If shipping settings aren’t configured for a given region, products may not display prices and variants correctly.
  * Solution: Navigate to your Market tab within your Shopify admin settings and ensure shipping settings are configured.
* Issue: Prices display incorrectly when “Show trailing zeros” is unchecked.
  * Solution: This setting is not supported in all currencies. Keep it checked to avoid issues.

***

#### Compare-at Price Displaying Incorrectly <a href="#h_ebaf37ad3c" id="h_ebaf37ad3c"></a>

* Issue: The percentage discount badge and strikeout price disappear when switching from the store’s default currency (e.g., GBP) to another currency.
  * Solution: Navigate to your Shopify admin > Settings > Markets > Preferences. Toggle off “Compare-at price hiding”.

***

#### Products Won’t Add to Cart <a href="#h_8b938dd482" id="h_8b938dd482"></a>

* Issue: Products may not add to the cart due to inventory or template settings.
  * Solutions:
    1. Check your inventory and stock settings. Enable “Continue selling when sold out” to allow items to be added.
    2. Ensure the “Options” block is included on your product template, even if your product has only one variant.
    3. Try enabling “Enable default variant”.

***

#### Broken Blog Grid <a href="#h_9f82677923" id="h_9f82677923"></a>

* Issue: The blog grid may break if “Enable summary” is turned on and the blog article contains extra or malformed HTML.
  * Solutions:
    1. Open the Theme Editor by clicking Customize next to the relevant theme.
    2. Go to Theme Settings > Blog Cards.
    3. Uncheck “Enable summary” and click Save.
    4. OR:
       1. Copy the entire contents of your blog article.
       2. Paste it into a Markdown text editor (e.g., Notion).
       3. Copy the content from the Markdown editor and paste it back into your blog article.

***

#### Empty Buttons <a href="#h_93c573a029" id="h_93c573a029"></a>

* Issue: Buttons with placeholder content may remain visible when they should be hidden.
  * Solutions:
    1. Open the Theme Editor by clicking Customize next to the relevant theme.
    2. Select the section you want to edit.
    3. Scroll down to the Button and Button URL settings.
    4. Delete both values so the fields are empty.
    5. Click Save.
    6. If the issue persists:
       1. Add any link to the Button URL setting.
       2. Click Save.
       3. Delete both values again and click Save.

***

#### Missing Login Buttons <a href="#h_5e00a2db9f" id="h_5e00a2db9f"></a>

* Issue: Login and account buttons may not be visible when setting up your Shopify account.
  * Solution:
    1. Navigate to Shopify Settings > Customer Accounts.
    2. Ensure customer accounts are enabled.
    3. Display login and account buttons in the following sections:
       * Announcement
       * Header
       * Mobile Menu
       * Footer

</details>

### Getting Help

#### Support Channels

1. **Documentation**
   * Check our [main documentation](https://help.brickspacelab.com) for detailed guides
   * Review [theme setup guides](https://help.brickspacelab.com/setup)
2. **Community Support**
   * Join our [Discord community](https://discord.gg/brickspacelab)
   * Share experiences and solutions with other theme users
3. **Technical Support**
   * Create a support ticket through our [help center](https://help.brickspacelab.com/support)
   * Include theme version and detailed issue description

### Best Practices

#### Before Reporting Issues

* Clear your browser cache
* Test in an incognito/private window
* Disable third-party apps temporarily
* Check if the issue occurs on multiple devices

#### When reporting issues

* Include your theme version
* Provide steps to reproduce
* Share screenshots or videos
* List any relevant browser/device information

### Version Compatibility

#### Supported Versions

* Current Version: 2.0.0
* Minimum Supported: 1.8.0
* Recommended: Always use the latest version

#### Update Policy

* Critical fixes: Released within 48 hours
* Feature updates: Monthly release cycle
* Security patches: Immediate release

### Contributing

We welcome contributions to improve our documentation and help other users. To contribute:

1. Fork our documentation repository
2. Create a new branch
3. Submit a pull request with your changes
4. Include detailed description of changes

### Contact

For urgent issues or security concerns: [https://brickspacelab.com/pages/contact](https://brickspacelab.com/pages/contact)

* Email: support@brickspacelab.com
* Discord: [Join our server](https://discord.gg/brickspacelab)
* Support Hours: Monday-Friday, 9 AM - 5 PM EST
