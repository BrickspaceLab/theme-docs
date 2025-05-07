# Displaying metafield content in product tables

Using metafields, you can display custom data within your product table. This allows for enhanced product comparisons and detailed information display.

#### Setting Up Your Metafields

**Displaying Product and Variant Metafields**

1. Within your **Theme Editor**, navigate to **Theme Settings > Product Cards**
2. Scroll down to **Table Details**
3. Enter the designated metafield you’d like to display within your table

#### Displaying Custom Data Using Metafields

**Using the Metafield Block**

1. Navigate to your **Shopify Admin** and select **Settings > Custom Data**
2. Within the **Metafield Definitions**, click **Products** and select **Add Definition**
3. For this example, use **Weight**. Ensure the **Namespace and Key** are labeled accordingly (e.g., `custom.weight`). Set the type to **Multi-line Text**
4. Within the **Metaobject Definitions**, click **Add Definition**. Set a name according to your metafield definition. For **Type**, select **Multi-line Text** and choose a name (e.g., `weight.custom`)
5. Navigate back to a product page within your **Shopify Admin**, scroll to the bottom, and set the custom data within the **Product Metafields**
6. To display your custom data, go to the **Theme Editor**, select the **Product Comparison** section, click **Add Block**, and select **Metafield**

#### Creating Your Metafield Data

1. Navigate to **Custom Data**
2. Add a **Metafield Definition**
3. Add a **Metaobject Definition**
4. Add text to the **Product Metafields** within your **Shopify Admin**
