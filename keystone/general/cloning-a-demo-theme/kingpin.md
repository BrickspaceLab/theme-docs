# Kingpin

{% hint style="info" %}
💡 Tip: Duplicate your theme before making code changes. This will ensure you have a backup to revert to if needed.
{% endhint %}

If you want to get a head start on your theme design this guide will help you copy the existing layout and settings from our demo stores.

### Kingpin theme files

<details>

<summary><strong>sections/header-group.json</strong></summary>

```json
{
  "type": "header",
  "name": "Header group",
  "sections": {
    "theme_announcement": {
      "type": "theme__announcement",
      "blocks": {
        "announcement_z8GqMR": {
          "type": "announcement",
          "settings": {
            "content": "<p>Same Day Delivery</p>"
          }
        }
      },
      "block_order": [
        "announcement_z8GqMR"
      ],
      "custom_css": [],
      "settings": {
        "announcement_delay": 15,
        "color_scheme": "color__bg-secondary color__secondary",
        "layout_alignment": "center",
        "enable_margin": true,
        "visibility": ""
      }
    },
    "theme_header": {
      "type": "theme__header",
      "blocks": {
        "button_XnBygi": {
          "type": "button",
          "settings": {
            "button_label": "Shop now",
            "button_url": "",
            "color_button": "btn"
          }
        }
      },
      "block_order": [
        "button_XnBygi"
      ],
      "custom_css": [],
      "settings": {
        "dropdown_links": "",
        "logo_default": "shopify://shop_images/keystoneparts.png",
        "logo_desktop_height": 26,
        "logo_mobile_height": 14,
        "enable_logo_on_desktop": false,
        "bar_default_color_scheme": "color__bg-body color__text",
        "bar_default_color_border": "color__border-divider-1",
        "bar_button_search_type": "desktop",
        "bar_button_cart_type": "text",
        "bar_button_login_type": "text",
        "bar_button_menu_type_desktop": "icon",
        "bar_button_menu_type_mobile": "icon",
        "bar_capitilization": "",
        "bar_font": "type__body",
        "bar_link_as_button": true,
        "enable_margin": true,
        "dropdown_color_scheme": "color__bg-body !color__text",
        "dropdown_color_border": "color__border-divider-1",
        "visibility": ""
      }
    }
  },
  "order": [
    "theme_announcement",
    "theme_header"
  ]
}
```

</details>

<details>

<summary><strong>sections/footer-group.json</strong></summary>

```json
{
  "type": "footer",
  "name": "Footer group",
  "sections": {
    "liquid_qhQNCW": {
      "type": "liquid",
      "settings": {
        "liquid": "<script>\n  window.intercomSettings = {\n    api_base: \"https://api-iam.intercom.io\",\n    app_id: \"fnubgeik\",\n  };\n</script>\n\n\n<script>\n  // We pre-filled your app ID in the widget URL: 'https://widget.intercom.io/widget/fnubgeik'\n  (function(){var w=window;var ic=w.Intercom;if(typeof ic===\"function\"){ic('reattach_activator');ic('update',w.intercomSettings);}else{var d=document;var i=function(){i.c(arguments);};i.q=[];i.c=function(args){i.q.push(args);};w.Intercom=i;var l=function(){var s=d.createElement('script');s.type='text/javascript';s.async=true;s.src='https://widget.intercom.io/widget/fnubgeik';var x=d.getElementsByTagName('script')[0];x.parentNode.insertBefore(s,x);};if(document.readyState==='complete'){l();}else if(w.attachEvent){w.attachEvent('onload',l);}else{w.addEventListener('load',l,false);}}})();\n</script>",
        "spacing_top": 0,
        "spacing_bottom": 0,
        "color_scheme": "color__bg-body color__text",
        "color_border": "color__border-divider-1",
        "style_border": "",
        "enable_margin": true,
        "visibility": ""
      }
    },
    "content_grid_R999P7": {
      "type": "content-grid",
      "blocks": {
        "content_B7ePAr": {
          "type": "content",
          "settings": {
            "heading": "Apply For An Account",
            "content": "<p>Become a member and receive wholesale pricing</p>",
            "button_label": "Apply Now",
            "url": "shopify://pages/apply-for-contractor-account",
            "enable_autoplay": true,
            "enable_mute_toggle": true,
            "enable_loop": true,
            "spacing_minimum_height": 100,
            "enable_padding": true,
            "color_scheme": "color__bg-overlay-1 color__text",
            "color_text": "!color__text",
            "color_border": "",
            "color_button": "btn--small btn--outline",
            "enable_gradient": false,
            "layout_y_alignment": "justify-start",
            "layout_x_alignment": "left",
            "text_position": "below",
            "layout_row_span": "row-span-1",
            "layout_col_span": "col-span-1 md:col-span-1"
          }
        },
        "content_LhnGTe": {
          "type": "content",
          "settings": {
            "heading": "Same Day Delivery",
            "content": "<p>Place your order before 11am for same day delivery</p>",
            "button_label": "Lean More",
            "url": "",
            "enable_autoplay": true,
            "enable_mute_toggle": true,
            "enable_loop": true,
            "spacing_minimum_height": 100,
            "enable_padding": true,
            "color_scheme": "color__bg-overlay-1 color__text",
            "color_text": "!color__text",
            "color_border": "",
            "color_button": "btn--small btn--outline",
            "enable_gradient": false,
            "layout_y_alignment": "justify-start",
            "layout_x_alignment": "left",
            "text_position": "below",
            "layout_row_span": "row-span-1",
            "layout_col_span": "col-span-1 md:col-span-1"
          }
        },
        "content_8JEeTW": {
          "type": "content",
          "settings": {
            "heading": "Read Our Guides",
            "content": "<p>Learn more about our products and how to use them</p>",
            "button_label": "Guides",
            "url": "shopify://blogs/news",
            "enable_autoplay": true,
            "enable_mute_toggle": true,
            "enable_loop": true,
            "spacing_minimum_height": 100,
            "enable_padding": true,
            "color_scheme": "color__bg-overlay-1 color__text",
            "color_text": "!color__text",
            "color_border": "",
            "color_button": "btn--small btn--outline",
            "enable_gradient": false,
            "layout_y_alignment": "justify-start",
            "layout_x_alignment": "left",
            "text_position": "below",
            "layout_row_span": "row-span-1",
            "layout_col_span": "col-span-1 md:col-span-1"
          }
        },
        "content_QmyzQ6": {
          "type": "content",
          "settings": {
            "heading": "24/7 Support",
            "content": "<p>Our team is able to help you at anytime</p>",
            "button_label": "Contact Us",
            "url": "shopify://pages/contact",
            "enable_autoplay": true,
            "enable_mute_toggle": true,
            "enable_loop": true,
            "spacing_minimum_height": 100,
            "enable_padding": true,
            "color_scheme": "color__bg-overlay-1 color__text",
            "color_text": "!color__text",
            "color_border": "",
            "color_button": "btn--small btn--outline",
            "enable_gradient": false,
            "layout_y_alignment": "justify-start",
            "layout_x_alignment": "left",
            "text_position": "below",
            "layout_row_span": "row-span-1",
            "layout_col_span": "col-span-1 md:col-span-1"
          }
        }
      },
      "block_order": [
        "content_B7ePAr",
        "content_LhnGTe",
        "content_8JEeTW",
        "content_QmyzQ6"
      ],
      "settings": {
        "heading": "",
        "content": "",
        "button_label": "",
        "button_url": "",
        "spacing_top": 50,
        "spacing_bottom": 50,
        "color_scheme": "color__bg-shade-1 color__text",
        "color_border": "color__border-divider-1",
        "color_button": "btn btn--secondary",
        "style_border": "border--t-width",
        "layout_row_desktop": 4,
        "layout_row_mobile": 1,
        "layout_x_alignment": "justify-between",
        "enable_margin": true,
        "enable_split": false,
        "visibility": ""
      }
    },
    "theme_footer": {
      "type": "theme__footer",
      "custom_css": [],
      "settings": {
        "spacing_top": 0,
        "spacing_bottom": 0,
        "main_color_scheme": "color__bg-shade-1 color__text",
        "main_color_border": "!color__border-transparent",
        "main_color_button": "btn--small btn--secondary",
        "main_layout_x_alignment": "justify-start",
        "sub_color_scheme": "color__bg-shade-1 color__text",
        "sub_color_border": "!color__border-transparent",
        "sub_links": "footer",
        "sub_show_account_link": true,
        "sub_show_localization": true,
        "sub_show_payment_icons": true,
        "sub_enable_follow_on_shop": false,
        "visibility": ""
      }
    }
  },
  "order": [
    "liquid_qhQNCW",
    "content_grid_R999P7",
    "theme_footer"
  ]
}
```

</details>

<details>

<summary><strong>sections/overlay-group.json</strong></summary>

```json
{
  "type": "custom.overlay",
  "name": "Overlay group",
  "sections": {
    "theme_tooltip": {
      "type": "theme__tooltip",
      "blocks": {
        "71c48f59-2e6d-4190-8942-3924132a07ee": {
          "type": "newsletter",
          "settings": {
            "content": "<p>Tell customers why they should subscribe to your newsletter.</p>",
            "button_label": "Subscribe",
            "disclaimer": "",
            "success": "<p>Success! You've been subscribed.</p>"
          }
        }
      },
      "block_order": [
        "71c48f59-2e6d-4190-8942-3924132a07ee"
      ],
      "disabled": true,
      "settings": {
        "button_label": "Sign up",
        "button_icon": "",
        "color_button": "btn btn--secondary",
        "placement": "bottom-0 right-0",
        "visibility": ""
      }
    },
    "theme_scrollup": {
      "type": "theme__scroll-up",
      "settings": {
        "scroll_up_style": "text",
        "button_color": "btn btn--secondary",
        "visibility": "hidden md:block"
      }
    },
    "theme_age-verification": {
      "type": "theme__age-verification",
      "disabled": true,
      "settings": {
        "age_verification_style": "full_date",
        "age_limit": 1,
        "heading": "Verify your age",
        "content": "<p>Please confirm that you are over the age of 18 to proceed.</p>"
      }
    }
  },
  "order": [
    "theme_tooltip",
    "theme_scrollup",
    "theme_age-verification"
  ]
}
```

</details>

<details>

<summary><strong>templates/index.json</strong></summary>

```json
{
  "sections": {
    "collection_grid_tqC96q": {
      "type": "collection-grid",
      "settings": {
        "collection": [
          "nails",
          "screws",
          "washers",
          "nuts",
          "staples",
          "cable-zip-ties",
          "threaded-rods",
          "pins"
        ],
        "heading": "Fasteners",
        "content": "<p>Reliable and Durable Fasteners for Every Project Need</p>",
        "button_label": "View All Fasteners",
        "button_url": "shopify://collections/fasteners",
        "spacing_top": 20,
        "spacing_bottom": 20,
        "color_scheme": "color__bg-body",
        "color_border": "color__border-selected-1",
        "color_button": "btn btn--secondary",
        "style_border": "",
        "layout_row_desktop": 8,
        "layout_row_mobile": 3,
        "layout_x_alignment": "justify-between",
        "enable_margin": true,
        "enable_split": false,
        "visibility": ""
      }
    },
    "collection_grid_Vw9Fbm": {
      "type": "collection-grid",
      "settings": {
        "collection": [
          "circular-saws",
          "drills",
          "jigsaws",
          "sanders",
          "hammers",
          "screwdrivers",
          "wrenches"
        ],
        "heading": "Tools",
        "content": "<p>Explore Top-Quality Tools for Every Type of Project</p>",
        "button_label": "View All Tools",
        "button_url": "shopify://collections/tools",
        "spacing_top": 20,
        "spacing_bottom": 20,
        "color_scheme": "color__bg-body",
        "color_border": "color__border-selected-1",
        "color_button": "btn btn--secondary",
        "style_border": "",
        "layout_row_desktop": 8,
        "layout_row_mobile": 3,
        "layout_x_alignment": "justify-between",
        "enable_margin": true,
        "enable_split": false,
        "visibility": ""
      }
    },
    "collection_grid_n3tE6N": {
      "type": "collection-grid",
      "settings": {
        "collection": [
          "sconces",
          "pendants",
          "chandeliers",
          "lamps"
        ],
        "heading": "Lighting",
        "content": "<p>Illuminate Your Home with Cutting-Edge Lighting Solutions</p>",
        "button_label": "View All Lighting",
        "button_url": "shopify://collections/lighting",
        "spacing_top": 20,
        "spacing_bottom": 20,
        "color_scheme": "color__bg-body",
        "color_border": "color__border-selected-1",
        "color_button": "btn btn--secondary",
        "style_border": "",
        "layout_row_desktop": 8,
        "layout_row_mobile": 3,
        "layout_x_alignment": "justify-between",
        "enable_margin": true,
        "enable_split": false,
        "visibility": ""
      }
    }
  },
  "order": [
    "collection_grid_tqC96q",
    "collection_grid_Vw9Fbm",
    "collection_grid_n3tE6N"
  ]
}
```

</details>

<details>

<summary><strong>templates/collection.json</strong></summary>

```json
{
  "sections": {
    "banner": {
      "type": "collection__banner",
      "settings": {
        "layout_y_spacing": "min-h-[200px] md:min-h-[250px]",
        "color_scheme": "color__bg-shade-3 color__text",
        "color_text": "color__text",
        "color_border": "color__border-divider-1",
        "enable_gradient": false,
        "enable_background_overlay": false,
        "style_border": "",
        "layout_y_alignment": "items-center",
        "layout_x_alignment": "justify-start",
        "enable_margin": true,
        "enable_max_width": true,
        "visibility": "",
        "enable_description": true,
        "enable_image": false
      }
    },
    "grid": {
      "type": "collection__main",
      "settings": {
        "spacing_top": 10,
        "spacing_bottom": 100,
        "color_scheme": "color__bg-body",
        "color_border": "color__border-divider-1",
        "layout_row_desktop": 5,
        "layout_row_mobile": 2,
        "filter_placement": "side",
        "layout_type": "list",
        "enable_expand_filters": true,
        "enable_layout_toggle": true,
        "enable_margin": true,
        "enable_sort": true,
        "enable_filter": true,
        "products_per_page": 10
      }
    }
  },
  "order": [
    "banner",
    "grid"
  ]
}
```

</details>

<details>

<summary><strong>templates/list-collections.json</strong></summary>

```json
{
  "sections": {
    "165583830739141e89": {
      "type": "banner",
      "blocks": {
        "82dc43ff-a8dd-484c-a794-1064d07c5d26": {
          "type": "heading",
          "settings": {
            "content": "Collections"
          }
        }
      },
      "block_order": [
        "82dc43ff-a8dd-484c-a794-1064d07c5d26"
      ],
      "settings": {
        "url": "",
        "show_image": false,
        "show_entire_image": false,
        "show_video_background_mobile": true,
        "layout_y_spacing": "min-h-[100px] md:min-h-[150px]",
        "color_scheme": "color__bg-body color__text",
        "color_text": "",
        "color_border": "color__border-divider-1",
        "enable_gradient": false,
        "enable_background_overlay": false,
        "style_border": "border--b-width",
        "layout_y_alignment": "items-end",
        "layout_x_alignment": "justify-start",
        "enable_margin": true,
        "enable_border_margin": false,
        "enable_max_width": true,
        "visibility": ""
      }
    },
    "main": {
      "type": "list-collections__main",
      "settings": {
        "spacing_top": 30,
        "spacing_bottom": 30,
        "color_scheme": "color__bg-body",
        "layout_row_desktop": 2,
        "layout_row_mobile": 1,
        "enable_margin": true,
        "items_per_page": 12
      }
    }
  },
  "order": [
    "165583830739141e89",
    "main"
  ]
}
```

</details>

<details>

<summary><strong>templates/product.json</strong></summary>

```json
{
  "sections": {
    "1638995507af787164": {
      "type": "product__main",
      "blocks": {
        "853ae7f0-85c9-45dc-8326-6e4044bcf5e5": {
          "type": "title",
          "settings": {
            "content": "<p>✔ 100% satisfaction guarantee</p><p>✔ Made locally in Canada</p>",
            "spacing_top": 20,
            "spacing_bottom": 10,
            "color_scheme": "color__bg-transparent",
            "color_border": "color__border-divider-1",
            "style_border": "",
            "position": "right",
            "savings_badge": "none",
            "enable_badges": true,
            "enable_type": false,
            "enable_vendor": false,
            "enable_sku": false
          }
        },
        "62c29cd6-a0b5-4f8b-86c0-a48660869d22": {
          "type": "price",
          "settings": {
            "spacing_top": 0,
            "spacing_bottom": 10,
            "color_scheme": "color__bg-transparent",
            "color_border": "color__border-divider-1",
            "style_border": "border--b-width",
            "position": "right"
          }
        },
        "options_aR9LwQ": {
          "type": "options",
          "settings": {
            "spacing_top": 20,
            "spacing_bottom": 0,
            "color_scheme": "color__bg-transparent",
            "color_border": "color__border-divider-1",
            "style_border": "",
            "position": "right"
          }
        }
      },
      "block_order": [
        "853ae7f0-85c9-45dc-8326-6e4044bcf5e5",
        "62c29cd6-a0b5-4f8b-86c0-a48660869d22",
        "options_aR9LwQ"
      ],
      "settings": {
        "enable_default_variant": true,
        "enable_default_plans": true,
        "enable_default_selling_plan_widget": true,
        "media_gallery_style": "slider",
        "media_slider_size_desktop": 70,
        "media_slider_size_mobile": 80,
        "media_gallery_position": "left",
        "enable_alt": true,
        "enable_variant_images": false,
        "enable_zoom": false,
        "zoom_level": "scale-[1.5]",
        "media_color_scheme": "color__bg-body color__text",
        "media_border": "outline--width color__outline-divider-1",
        "media_ratio": "aspect-[1/1]",
        "media_object_sizing": "cover",
        "enable_ratio": true,
        "spacing_top": 10,
        "spacing_bottom": 0,
        "color_scheme": "color__bg-body",
        "layout_column_width": 40,
        "enable_margin": true
      }
    }
  },
  "order": [
    "1638995507af787164"
  ]
}
```

</details>

<details>

<summary><strong>templates/page.json</strong></summary>

```json
{
  "sections": {
    "main": {
      "type": "page__main",
      "settings": {
      }
    }
  },
  "order": [
    "main"
  ]
}
```

</details>

<details>

<summary><strong>templates/blog.json</strong></summary>

```json
{
  "sections": {
    "banner_9R7hhk": {
      "type": "banner",
      "blocks": {
        "heading_Bb4XW8": {
          "type": "heading",
          "settings": {
            "content": "{{ blog.title }}"
          }
        },
        "content_kUNtpA": {
          "type": "content",
          "settings": {
            "content": "<p>Learn how to use our products from the experts</p>"
          }
        }
      },
      "block_order": [
        "heading_Bb4XW8",
        "content_kUNtpA"
      ],
      "settings": {
        "url": "",
        "show_image": false,
        "show_entire_image": false,
        "show_video_background_mobile": true,
        "layout_y_spacing": "min-h-[100px] md:min-h-[150px]",
        "color_scheme": "color__bg-secondary color__secondary",
        "color_text": "",
        "color_border": "color__border-divider-1",
        "enable_gradient": false,
        "enable_background_overlay": false,
        "style_border": "border--b-width",
        "layout_y_alignment": "items-end",
        "layout_x_alignment": "justify-start",
        "enable_margin": true,
        "enable_border_margin": false,
        "enable_max_width": true,
        "visibility": ""
      }
    },
    "main": {
      "type": "blog__main",
      "settings": {
        "spacing_top": 100,
        "spacing_bottom": 100,
        "color_scheme": "color__bg-body",
        "color_border": "color__border-divider-1",
        "style_border": "border--b-width",
        "layout_row_desktop": 2,
        "layout_row_mobile": 1,
        "enable_margin": true,
        "items_per_page": 6,
        "visibility": ""
      }
    }
  },
  "order": [
    "banner_9R7hhk",
    "main"
  ]
}
```

</details>

<details>

<summary><strong>templates/article.json</strong></summary>

```json
{
  "sections": {
    "article_banner_48nKa3": {
      "type": "article__banner",
      "settings": {
        "layout_y_spacing": "min-h-[100px] md:min-h-[150px]",
        "color_scheme": "color__bg-body color__text",
        "color_text": "color__text",
        "color_border": "color__border-divider-1",
        "enable_gradient": false,
        "enable_background_overlay": false,
        "style_border": "",
        "layout_y_alignment": "items-end",
        "layout_x_alignment": "justify-start",
        "enable_margin": true,
        "enable_max_width": true,
        "visibility": "",
        "enable_author": false,
        "enable_date": true,
        "enable_tags": false,
        "enable_image": false
      }
    },
    "content_grid_qxE9Ym": {
      "type": "content-grid",
      "blocks": {
        "content_nVDTGP": {
          "type": "content",
          "settings": {
            "heading": "",
            "content": "",
            "button_label": "",
            "url": "",
            "image_background": "{{ article.image }}",
            "enable_autoplay": true,
            "enable_mute_toggle": true,
            "enable_loop": true,
            "spacing_minimum_height": 400,
            "enable_padding": true,
            "color_scheme": "color__bg-overlay-1 color__text",
            "color_border": "",
            "color_button": "btn--small btn--outline",
            "enable_gradient": true,
            "layout_y_alignment": "justify-end",
            "layout_x_alignment": "left",
            "text_position": "below",
            "layout_row_span": "row-span-1",
            "layout_col_span": "col-span-1 md:col-span-1"
          }
        }
      },
      "block_order": [
        "content_nVDTGP"
      ],
      "settings": {
        "heading": "",
        "content": "",
        "button_label": "",
        "button_url": "",
        "spacing_top": 0,
        "spacing_bottom": 0,
        "color_scheme": "color__bg-body",
        "color_border": "color__border-divider-1",
        "color_button": "btn btn--secondary",
        "style_border": "",
        "layout_row_desktop": 1,
        "layout_row_mobile": 1,
        "layout_x_alignment": "justify-between",
        "enable_margin": true,
        "enable_split": false,
        "visibility": ""
      }
    },
    "main": {
      "type": "article__main",
      "blocks": {
        "6d44e560-358d-4232-8708-502806610136": {
          "type": "breadcrumb",
          "settings": {
            "spacing_top": 50,
            "spacing_bottom": 10,
            "color_border": "color__border-divider-1",
            "style_border": "",
            "layout_x_alignment": "text-left"
          }
        },
        "table_pj9eVt": {
          "type": "table",
          "settings": {
            "spacing_top": 50,
            "spacing_bottom": 10,
            "color_border": "color__border-divider-1",
            "style_border": "",
            "position": "right"
          }
        },
        "f7c49961-aaf7-41df-8711-43d3d5753948": {
          "type": "article",
          "settings": {
            "spacing_top": 20,
            "spacing_bottom": 50,
            "color_border": "color__border-divider-1",
            "style_border": "",
            "layout_x_alignment": "justify-start"
          }
        }
      },
      "block_order": [
        "6d44e560-358d-4232-8708-502806610136",
        "table_pj9eVt",
        "f7c49961-aaf7-41df-8711-43d3d5753948"
      ],
      "settings": {
        "spacing_top": 0,
        "spacing_bottom": 0,
        "color_scheme": "color__bg-body color__text",
        "color_border": "color__border-divider-1",
        "style_border": "",
        "enable_margin": true,
        "visibility": ""
      }
    }
  },
  "order": [
    "article_banner_48nKa3",
    "content_grid_qxE9Ym",
    "main"
  ]
}
```

</details>
