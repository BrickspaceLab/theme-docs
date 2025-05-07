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

# Advanced customizations

{% hint style="warning" %}
**We do not provide support for code customizations**

If you are not comfortable making code changes, we highly recommend [hiring an expert developer](../support/hire-a-shopify-developer.md).
{% endhint %}

Our Shopify themes are built with developers in mind. We use a familiar tools so you can take any of our existing themes and customize them quickly.&#x20;

* **Easily extendable**: We've built our themes with a modular approach, so it's super simple to extend and customize. We use Tailwind to give you an easy approach to styling, and Alpine to add interactivity without weighing you down.
* **Meets all standards**: Our themes meets all the [requirements](https://shopify.dev/docs/themes/store/requirements) for the Shopify theme store.



### FAQs

<details>

<summary>When is the right time to make code customizations?</summary>

If you've tried using all the built-in functionality and still find your theme is missing core functionality that you need then customizations are your best option. Making changes directly to your theme will give you full control to change things how you need.&#x20;

</details>

<details>

<summary>Should I hire someone to make code customizations?</summary>

Yes. If you aren't familiar with coding or have never built a Shopify theme then it's going to be a bit tricky. If you want to do code changes on your own - make sure you save a backup and consult your favourite ai assitant.&#x20;

</details>





### Making code changes to your Shopify theme <a href="#h_36e940604c" id="h_36e940604c"></a>

{% hint style="info" %}
Duplicate your theme before making code changes. This will ensure you have a backup to revert to if needed.
{% endhint %}

#### Development toolkits <a href="#h_9dc9736a42" id="h_9dc9736a42"></a>

For more advanced customizations we recommend using the a theme toolkit. Our toolkits will give you full control over source code. You can compile new CSS and edit the themes core JavaScript. Please refer to the GitHub repos for more information.

<table data-view="cards"><thead><tr><th></th><th data-hidden data-card-target data-type="content-ref"></th></tr></thead><tbody><tr><td>Paper toolkit</td><td><a href="https://github.com/BrickspaceLab/paper-toolkit">https://github.com/BrickspaceLab/paper-toolkit</a></td></tr><tr><td>Space toolkit</td><td><a href="https://github.com/BrickspaceLab/space-toolkit">https://github.com/BrickspaceLab/space-toolkit</a></td></tr><tr><td>Keystone toolkit</td><td><a href="https://github.com/BrickspaceLab/keystone-toolkit">https://github.com/BrickspaceLab/keystone-toolkit</a></td></tr></tbody></table>



#### Adding custom liquid <a href="#h_f5e30552ba" id="h_f5e30552ba"></a>

The Custom liquid section can be used to add any code snippet to a template. This is a great way to add app install scripts if an app requires manual installation. This is a great approach to take - your theme code remains un-edited and you still have access to easily update the theme.

{% stepper %}
{% step %}
**Add Custom liquid section**

* Click **Add section**.
* Click **Custom liquid** to add the section.

{% hint style="info" %}
If you want to install a code snippet across your entire site then you can move your section to the Footer group.
{% endhint %}
{% endstep %}

{% step %}
**Add your code**

* Paste in your code.
* Remove the section padding and borders.
* This section renders liquid so if you plan to add JavaScript or CSS you'll need to include that within a `<script>` or a `style` tag.
{% endstep %}

{% step %}
### Save your changes

Click **Save**
{% endstep %}
{% endstepper %}



#### Adding custom CSS

Custom CSS can be applied to your Shopify theme by using the built-in [custom CSS](https://help.shopify.com/en/manual/online-store/themes/theme-structure/extend/add-css) feature in your theme editor. For advanced users who have more experience with development, you can use our development toolkits. Using Custom CSS through the theme editor will maintain your themes original code - this means you'll still be able to update the theme easily.



#### Popular CSS customizations

Custom CSS can be used in a variety of ways and is the perfect option for minor customizations. Here are a few guides for commonly requested customizations.

<details>

<summary>Change the background color for a section</summary>

1. Navigate to the section you want to edit.
2. In the settings panel scroll to the bottom and open **Custom CSS**.
3. Alternatively, if you want to apply this change across your entire store front navigate to **Theme settings > Custom CSS**
4. Paste the following code in the input field and update the color value to any hex color code.

```css
section { background-color: #000000; }
```

</details>

<details>

<summary>Change the color of section section headings</summary>

1. Navigate to the section you want to edit.
2. In the settings panel scroll to the bottom and open **Custom CSS**.
3. Alternatively, if you want to apply this change across your entire store front navigate to **Theme settings > Custom CSS**
4. Paste the following code in the input field and update the color value to any hex color code. E.g. `#000000` could be changed to `#ffffff`.

```css
h3 { color: #000000; }
```

</details>

<details>

<summary>Change the color of a button</summary>

1. Navigate to the section you want to edit.

1) In the settings panel scroll to the bottom and open **Custom CSS**.
2) Alternatively, if you want to apply this change across your entire store front navigate to **Theme settings > Custom CSS**
3) Paste the following code in the input field and update the color value to any hex color code.
   * In the below example, `#000000` can be replaced to change the background of the button, `#ffffff` can be replaced to change the text color of the bottom

```css
.btn { background: #000000; border: #000000; color: #ffffff; }
```

</details>

<details>

<summary>Adjust the size of a button</summary>

1. Navigate to the section you want to edit.

1) In the settings panel scroll to the bottom and open **Custom CSS**.
2) Alternatively, if you want to apply this change across your entire store front navigate to **Theme settings > Custom CSS**
3) Paste in the following code. Adjust any of the values to change the button as needed

```css
.btn { font-size: 24px; padding: 10px 30px; }
```

</details>



#### Adding custom JavaScript

Since our themes are built using Alpine it's often best to consider adding functionality through Alpine first. We can use Alpine to add functionality by writing code directly inside the liquid markup.

For more advanced customizations we recommend using our development toolkits.



#### **Access theme functions and data**

If you are integrating your Shopify theme with a third-party app you may want to access some of the globally available functions. Since our themes utilize [Alpine.js](https://alpinejs.dev/) this is done a bit differently than normal.

The first step is to access the app object. This object contains all the exposed functions and is stored in the \_x\_dataStack array of the html element. Here is how to access it:

```javascript
var app = document.querySelectorAll('html')[0]._x_dataStack[0];
```

From here you can call any of the functions available in the . For example if you want to call cart.updateCart() you could do the following.

```javascript
app.updateCart(true);
```

