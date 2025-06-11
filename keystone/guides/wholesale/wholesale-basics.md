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
    visible: false
---

# Wholesale basics

Keystone offers robust features for creating a wholesale or B2B storefront. These features allow you to restrict access to certain products, pages, and pricing information, ensuring an exclusive experience for approved customers.

Key functionalities include:

* Hiding prices, products, and blog posts using tags
* Setting minimum order amounts
* Displaying different prices to different customers using third-party apps

### Setting Up Account Restriction Feature

{% hint style="info" %}
**Restriction tags are case sensitive!**

Restriction tags like `approved` are case-sensitive and must match exactly between the theme editor and tag system. For example, if the theme uses `Approved`, the tag must also be `Approved`—`approved` or `APPROVED` won't work.
{% endhint %}

#### Hiding Prices with Tags

1. In your Shopify theme’s **Account Settings**, enter a tag for **Hide prices tag** (e.g., `hide price`).
2. Products with this tag will not display prices or an **Add to Cart** button to unauthorized customers.

#### Hiding Products with Tags

1. In **Account Settings**, enter a tag for **Hide products with tag** (e.g., `hide product`).
2. Visitors who are not logged in or approved will not see products with this tag.

#### Hiding Blog Posts with Tags

1. In **Account Settings**, enter a tag for **Hide blog posts with tag** (e.g., `hide blog`).
2. Unauthorized visitors will not be able to view blog posts with this tag.

For more details, visit: Account Restriction Features.

### Restricting Checkout Below a Certain Subtotal

1. In the **Theme Editor**, navigate to **Theme Settings > Cart**.
2. Set a **Minimum Order Amount** (e.g., `10000` for $100.00).
3. Leave blank to allow all orders without a minimum.

### Restricting Your Shopify Theme for Wholesale Ordering

1. Open the **Theme Editor** by clicking **Customize** next to the relevant theme.
2. Click **Theme Settings** (gear icon near the top left).
3. Scroll down and click **Account**.

### Setting Which Customers See Restricted Content

#### Show Restricted Content Based on Tags

1. In **Account Settings**, enter a tag for **Matching tag** (e.g., `approved`).
2. In your Shopify admin, go to **Customers**, find the customer, and add the `approved` tag.
3. Approved customers will see restricted content when logged in.

#### Show Restricted Content for B2B Users

1. In **Account Settings**, check **Enable B2B customers**.
2. B2B customers (Shopify Plus only) will see restricted content when logged in.

For more information on B2B accounts, visit: Shopify B2B Help.

### Displaying Different Prices to Different Customers Using Applications

* Install a wholesale pricing app from the **Shopify App Store** (e.g., [**B2B Wholesale Hub** ](https://apps.shopify.com/wholesale-hub)or [**Wholesale Pricing Discount B2B**](https://apps.shopify.com/wholesale-pricing-discount)).
* In the **Theme Editor**, navigate to **App Embeds** and toggle on your application.

### **Automating Wholesale Workflows**

You can use an application like [**Flow**](https://apps.shopify.com/flow) to automate:

* **Wholesale signups** – Automatically tag customers who register via your wholesale form
* **Pricing tiers** – Apply custom discounts based on order history or customer tags
* **Inventory alerts** – Get notified when wholesale products are low in stock
* **Order approvals** – Require manual approval for large wholesale orders
* **Post-purchase follow-ups** – Send thank you emails or invoices automatically

