# Using account restriction features

Account restriction allows you to hide certain products, pages, or pricing information from visitors who are not logged in or approved. This is particularly useful for wholesale or B2B storefronts, as it protects sensitive information and creates an exclusive experience for approved customers.

#### How to Restrict Your Shopify Theme for Wholesale Ordering

1. Open the **Theme Editor** by clicking **Customize** next to the relevant theme
2. Click **Theme Settings** (gear icon near the top left)
3. Scroll down and click **Account**

#### Setting Which Customers See Restricted Content

You can choose to show restricted content based on customer account tags or B2B customer accounts.

**Show Restricted Content Based on Tags**

1. In **Account Settings**, enter a tag for **Matching tag** (e.g., `approved`)
2. In your Shopify admin, go to **Customers**, find the customer, and add the `approved` tag
3. Approved customers will see restricted content when logged in

**Show Restricted Content for B2B Users**

1. In **Account Settings**, check **Enable B2B customers**
2. B2B customers (Shopify Plus only) will see restricted content when logged in

For more information on B2B accounts, visit: [Shopify B2B Help](https://help.shopify.com/en/manual/b2b)

#### Setting Which Content to Restrict

You can hide products, blog posts, or restrict the entire site to approved customers.

**Hiding Prices with Tags**

1. In **Account Settings**, enter a tag for **Hide prices tag** (e.g., `hide price`)
2. Products with this tag will not display prices or an **Add to Cart** button to unauthorized customers

**Hiding Products with Tags**

1. In **Account Settings**, enter a tag for **Hide products with tag** (e.g., `hide product`)
2. Visitors who are not logged in or approved will not see products with this tag

**Hiding Blog Posts with Tags**

1. In **Account Settings**, enter a tag for **Hide blog posts with tag** (e.g., `hide blog`)
2. Unauthorized visitors will not be able to view blog posts with this tag

**Enable Full Site Restriction**

1. In **Account Settings**, check **Enable full site restriction**
2. Visitors who are not logged in or approved will only see specific sections you choose to display (e.g., a banner linking to your signup form)

> Currently B2B accounts are limited to Shopify Plus stores. Refer to Shopify for more information on B2B accounts: [Shopify B2B Documentation](https://help.shopify.com/en/manual/b2b)

#### Control How Restricted Content Appears

You can choose how restricted content is displayed to customers:

* **Placeholder**: Shows a "Login to view" message
* **Hidden**: Completely hides restricted content

**Steps to Set Restricted Style**

1. In **Account Settings**, set **Restricted Style**
2. Choose **Placeholder** to show a login prompt or **Hidden** to completely hide restricted content
