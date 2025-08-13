# Hide out of stock variants

## Hide out-of-stock variants

Use Custom CSS to hide variant options that are out of stock. This removes values that appear with a strikethrough and disabled options in dropdowns.

{% stepper %}
{% step %}
Go to **Online Store** > **Themes** > **Customize**
{% endstep %}

{% step %}
Open **Theme settings** > **Custom CSS**
{% endstep %}

{% step %}
Paste the following code:

```css
/* Hide out-of-stock variants with strikethrough */
.strikethrough,
.linethrough {
  display: none !important;
}

/* For dropdown options that are disabled */
select option:disabled {
  display: none !important;
}
```
{% endstep %}

{% step %}
Click **Save**
{% endstep %}
{% endstepper %}
