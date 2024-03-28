<!DOCTYPE html>
<!-- This site was created in Webflow. https://www.webflow.com -->
<!-- Last Published: Tue Feb 20 2024 22:51:12 GMT+0000 (Coordinated Universal Time) -->
<html data-wf-domain="georgemaxwell.webflow.io" data-wf-page="63b651c3218127b90bfe8bf8" data-wf-site="63b57776402c77650eb13f9f">

<head>
    <meta charset="utf-8" />
    <title>Home - George Maxwell Webflow Ecommerce website template</title>
    <meta content="George Maxwell is a portfolio webflow website template with modern interactions and animations. Perfect for freelacers and creatives" name="description" />
    <meta content="Home - George Maxwell Webflow Ecommerce website template" property="og:title" />
    <meta content="George Maxwell is a portfolio webflow website template with modern interactions and animations. Perfect for freelacers and creatives" property="og:description" />
    <meta content="https://assets-global.website-files.com/63b57776402c77650eb13f9f/63c8a1890bec5cfe57b49a73_thum.png" property="og:image" />
    <meta content="Home - George Maxwell Webflow Ecommerce website template" property="twitter:title" />
    <meta content="George Maxwell is a portfolio webflow website template with modern interactions and animations. Perfect for freelacers and creatives" property="twitter:description" />
    <meta content="https://assets-global.website-files.com/63b57776402c77650eb13f9f/63c8a1890bec5cfe57b49a73_thum.png" property="twitter:image" />
    <meta property="og:type" content="website" />
    <meta content="summary_large_image" name="twitter:card" />
    <meta content="width=device-width, initial-scale=1" name="viewport" />
    <meta content="Webflow" name="generator" />
    <link href="https://assets-global.website-files.com/63b57776402c77650eb13f9f/css/georgemaxwell.webflow.3ec76671e.css" rel="stylesheet" type="text/css" />
    <link href="https://fonts.googleapis.com" rel="preconnect" />
    <link href="https://fonts.gstatic.com" rel="preconnect" crossorigin="anonymous" />
    <script src="https://ajax.googleapis.com/ajax/libs/webfont/1.6.26/webfont.js" type="text/javascript"></script>
    <script type="text/javascript">
        WebFont.load({
            google: {
                families: ["Open Sans:300,300italic,400,400italic,600,600italic,700,700italic,800,800italic", "Gantari:100,200,300,regular,500,600,700,800,900"]
            }
        });
    </script>
    <script type="text/javascript">
        ! function(o, c) {
            var n = c.documentElement,
                t = " w-mod-";
            n.className += t + "js", ("ontouchstart" in o || o.DocumentTouch && c instanceof DocumentTouch) && (n.className += t + "touch")
        }(window, document);
    </script>
    <link href="https://assets-global.website-files.com/63b57776402c77650eb13f9f/63bd72c1040947a72ec6f5db_favicon-32x32.png" rel="shortcut icon" type="image/x-icon" />
    <link href="https://assets-global.website-files.com/63b57776402c77650eb13f9f/63bd73169a78d24054004e71_android-chrome-512x512.png" rel="apple-touch-icon" />
    <script type="text/javascript">
        window.__WEBFLOW_CURRENCY_SETTINGS = {
            "currencyCode": "USD",
            "symbol": "$",
            "decimal": ".",
            "fractionDigits": 2,
            "group": ",",
            "template": "{{wf {\"path\":\"symbol\",\"type\":\"PlainText\"} }} {{wf {\"path\":\"amount\",\"type\":\"CommercePrice\"} }} {{wf {\"path\":\"currencyCode\",\"type\":\"PlainText\"} }}",
            "hideDecimalForWholeNumbers": false
        };
    </script>
</head>

<body class="body">
    <div class="menu">
        <div class="top-menu-wrapper"><a href="#" class="logo-link-block w-inline-block"><img src="https://assets-global.website-files.com/63b57776402c77650eb13f9f/63bd75b5fbe4b90fd47debba_logo%202.jpg" loading="lazy" alt="" class="main-logo"/></a>
            <div class="menu-right-wrapper">
                <div class="cart-main-wrapper">
                    <div data-node-type="commerce-cart-wrapper" data-open-product="" data-wf-cart-type="modal" data-wf-cart-query="query Dynamo2 {
  database {
    id
    commerceOrder {
      comment
      extraItems {
        name
        pluginId
        pluginName
        price {
          value
          unit
          decimalValue
          string
        }
      }
      id
      startedOn
      statusFlags {
        hasDownloads
        hasSubscription
        isFreeOrder
        requiresShipping
      }
      subtotal {
        value
        unit
        decimalValue
        string
      }
      total {
        value
        unit
        decimalValue
        string
      }
      updatedOn
      userItems {
        count
        id
        price {
          value
          unit
          decimalValue
          string
        }
        product {
          id
          cmsLocaleId
          f__draft_0ht
          f__archived_0ht
          f_name_
          f_sku_properties_3dr {
            id
            name
            enum {
              id
              name
              slug
            }
          }
        }
        rowTotal {
          value
          unit
          decimalValue
          string
        }
        sku {
          cmsLocaleId
          f__draft_0ht
          f__archived_0ht
          f_main_image_4dr {
            url
            file {
              size
              origFileName
              createdOn
              updatedOn
              mimeType
              width
              height
              variants {
                origFileName
                quality
                height
                width
                s3Url
                error
                size
              }
            }
            alt
          }
          f_sku_values_3dr {
            property {
              id
            }
            value {
              id
            }
          }
          id
        }
        subscriptionFrequency
        subscriptionInterval
        subscriptionTrial
      }
      userItemsCount
    }
  }
  site {
    id
    commerce {
      businessAddress {
        country
      }
      defaultCountry
      defaultCurrency
      quickCheckoutEnabled
    }
  }
}" data-wf-page-link-href-prefix="" class="w-commerce-commercecartwrapper"><a href="#" data-node-type="commerce-cart-open-link" aria-haspopup="dialog" aria-label="Open cart" role="button" class="w-commerce-commercecartopenlink cart-button w-inline-block"><svg class="w-commerce-commercecartopenlinkicon" width="17px" height="17px" viewBox="0 0 17 17"><g stroke="none" stroke-width="1" fill="none" fill-rule="evenodd"><path d="M2.60592789,2 L0,2 L0,0 L4.39407211,0 L4.84288393,4 L16,4 L16,9.93844589 L3.76940945,12.3694378 L2.60592789,2 Z M15.5,17 C14.6715729,17 14,16.3284271 14,15.5 C14,14.6715729 14.6715729,14 15.5,14 C16.3284271,14 17,14.6715729 17,15.5 C17,16.3284271 16.3284271,17 15.5,17 Z M5.5,17 C4.67157288,17 4,16.3284271 4,15.5 C4,14.6715729 4.67157288,14 5.5,14 C6.32842712,14 7,14.6715729 7,15.5 C7,16.3284271 6.32842712,17 5.5,17 Z" fill="currentColor" fill-rule="nonzero"></path></g></svg><div class="w-inline-block">Cart</div><div data-wf-bindings="%5B%7B%22innerHTML%22%3A%7B%22type%22%3A%22Number%22%2C%22filter%22%3A%7B%22type%22%3A%22numberPrecision%22%2C%22params%22%3A%5B%220%22%2C%22numberPrecision%22%5D%7D%2C%22dataPath%22%3A%22database.commerceOrder.userItemsCount%22%7D%7D%5D" class="w-commerce-commercecartopenlinkcount">0</div></a>
                        <div
                            data-node-type="commerce-cart-container-wrapper" style="display:none" class="w-commerce-commercecartcontainerwrapper w-commerce-commercecartcontainerwrapper--cartType-modal cart-wrapper">
                            <div role="dialog" data-node-type="commerce-cart-container" class="w-commerce-commercecartcontainer cart-container">
                                <div class="w-commerce-commercecartheader">
                                    <h4 class="w-commerce-commercecartheading">Your Cart</h4><a href="#" data-node-type="commerce-cart-close-link" role="button" aria-label="Close cart" class="w-commerce-commercecartcloselink w-inline-block"><svg class="icon-3" width="16px" height="16px" viewBox="0 0 16 16"><g stroke="none" stroke-width="1" fill="none" fill-rule="evenodd"><g fill-rule="nonzero" fill="#333333"><polygon points="6.23223305 8 0.616116524 13.6161165 2.38388348 15.3838835 8 9.76776695 13.6161165 15.3838835 15.3838835 13.6161165 9.76776695 8 15.3838835 2.38388348 13.6161165 0.616116524 8 6.23223305 2.38388348 0.616116524 0.616116524 2.38388348 6.23223305 8"></polygon></g></g></svg></a></div>
                                <div
                                    class="w-commerce-commercecartformwrapper">
                                    <form data-node-type="commerce-cart-form" style="display:none" class="w-commerce-commercecartform">
                                        <script type="text/x-wf-template" id="wf-template-5ebc6c02-4c44-6096-412c-3600ea5b270e">%3Cdiv%20class%3D%22w-commerce-commercecartitem%22%3E%3Cimg%20src%3D%22https%3A%2F%2Fassets-global.website-files.com%2Fplugins%2FBasic%2Fassets%2Fplaceholder.60f9b1840c.svg%22%20data-wf-bindings%3D%22%255B%257B%2522src%2522%253A%257B%2522type%2522%253A%2522ImageRef%2522%252C%2522filter%2522%253A%257B%2522type%2522%253A%2522identity%2522%252C%2522params%2522%253A%255B%255D%257D%252C%2522dataPath%2522%253A%2522database.commerceOrder.userItems%255B%255D.sku.f_main_image_4dr%2522%257D%257D%255D%22%20alt%3D%22%22%20class%3D%22w-commerce-commercecartitemimage%20cart-image%20w-dyn-bind-empty%22%2F%3E%3Cdiv%20class%3D%22w-commerce-commercecartiteminfo%22%3E%3Cdiv%20data-wf-bindings%3D%22%255B%257B%2522innerHTML%2522%253A%257B%2522type%2522%253A%2522PlainText%2522%252C%2522filter%2522%253A%257B%2522type%2522%253A%2522identity%2522%252C%2522params%2522%253A%255B%255D%257D%252C%2522dataPath%2522%253A%2522database.commerceOrder.userItems%255B%255D.product.f_name_%2522%257D%257D%255D%22%20class%3D%22w-commerce-commercecartproductname%20text-block-6%20w-dyn-bind-empty%22%3E%3C%2Fdiv%3E%3Cdiv%20data-wf-bindings%3D%22%255B%257B%2522innerHTML%2522%253A%257B%2522type%2522%253A%2522CommercePrice%2522%252C%2522filter%2522%253A%257B%2522type%2522%253A%2522price%2522%252C%2522params%2522%253A%255B%255D%257D%252C%2522dataPath%2522%253A%2522database.commerceOrder.userItems%255B%255D.price%2522%257D%257D%255D%22%20class%3D%22cart-price%22%3E%24%C2%A00.00%C2%A0USD%3C%2Fdiv%3E%3Cscript%20type%3D%22text%2Fx-wf-template%22%20id%3D%22wf-template-5ebc6c02-4c44-6096-412c-3600ea5b2715%22%3E%253Cli%253E%253Cspan%2520data-wf-bindings%253D%2522%25255B%25257B%252522innerHTML%252522%25253A%25257B%252522type%252522%25253A%252522PlainText%252522%25252C%252522filter%252522%25253A%25257B%252522type%252522%25253A%252522identity%252522%25252C%252522params%252522%25253A%25255B%25255D%25257D%25252C%252522dataPath%252522%25253A%252522database.commerceOrder.userItems%25255B%25255D.product.f_sku_properties_3dr%25255B%25255D.name%252522%25257D%25257D%25255D%2522%253E%253C%252Fspan%253E%253Cspan%253E%253A%2520%253C%252Fspan%253E%253Cspan%2520data-wf-bindings%253D%2522%25255B%25257B%252522innerHTML%252522%25253A%25257B%252522type%252522%25253A%252522CommercePropValues%252522%25252C%252522filter%252522%25253A%25257B%252522type%252522%25253A%252522identity%252522%25252C%252522params%252522%25253A%25255B%25255D%25257D%25252C%252522dataPath%252522%25253A%252522database.commerceOrder.userItems%25255B%25255D.product.f_sku_properties_3dr%25255B%25255D%252522%25257D%25257D%25255D%2522%253E%253C%252Fspan%253E%253C%252Fli%253E%3C%2Fscript%3E%3Cul%20data-wf-bindings%3D%22%255B%257B%2522optionSets%2522%253A%257B%2522type%2522%253A%2522CommercePropTable%2522%252C%2522filter%2522%253A%257B%2522type%2522%253A%2522identity%2522%252C%2522params%2522%253A%255B%255D%257D%252C%2522dataPath%2522%253A%2522database.commerceOrder.userItems%255B%255D.product.f_sku_properties_3dr%5B%5D%2522%257D%257D%252C%257B%2522optionValues%2522%253A%257B%2522type%2522%253A%2522CommercePropValues%2522%252C%2522filter%2522%253A%257B%2522type%2522%253A%2522identity%2522%252C%2522params%2522%253A%255B%255D%257D%252C%2522dataPath%2522%253A%2522database.commerceOrder.userItems%255B%255D.sku.f_sku_values_3dr%2522%257D%257D%255D%22%20class%3D%22w-commerce-commercecartoptionlist%22%20data-wf-collection%3D%22database.commerceOrder.userItems%255B%255D.product.f_sku_properties_3dr%22%20data-wf-template-id%3D%22wf-template-5ebc6c02-4c44-6096-412c-3600ea5b2715%22%3E%3Cli%3E%3Cspan%20data-wf-bindings%3D%22%255B%257B%2522innerHTML%2522%253A%257B%2522type%2522%253A%2522PlainText%2522%252C%2522filter%2522%253A%257B%2522type%2522%253A%2522identity%2522%252C%2522params%2522%253A%255B%255D%257D%252C%2522dataPath%2522%253A%2522database.commerceOrder.userItems%255B%255D.product.f_sku_properties_3dr%255B%255D.name%2522%257D%257D%255D%22%3E%3C%2Fspan%3E%3Cspan%3E%3A%20%3C%2Fspan%3E%3Cspan%20data-wf-bindings%3D%22%255B%257B%2522innerHTML%2522%253A%257B%2522type%2522%253A%2522CommercePropValues%2522%252C%2522filter%2522%253A%257B%2522type%2522%253A%2522identity%2522%252C%2522params%2522%253A%255B%255D%257D%252C%2522dataPath%2522%253A%2522database.commerceOrder.userItems%255B%255D.product.f_sku_properties_3dr%255B%255D%2522%257D%257D%255D%22%3E%3C%2Fspan%3E%3C%2Fli%3E%3C%2Ful%3E%3Ca%20href%3D%22%23%22%20role%3D%22button%22%20aria-label%3D%22Remove%20item%20from%20cart%22%20data-wf-bindings%3D%22%255B%257B%2522data-commerce-sku-id%2522%253A%257B%2522type%2522%253A%2522ItemRef%2522%252C%2522filter%2522%253A%257B%2522type%2522%253A%2522identity%2522%252C%2522params%2522%253A%255B%255D%257D%252C%2522dataPath%2522%253A%2522database.commerceOrder.userItems%255B%255D.sku.id%2522%257D%257D%255D%22%20class%3D%22remove-button%20w-inline-block%22%20data-wf-cart-action%3D%22remove-item%22%20data-commerce-sku-id%3D%22%22%3E%3Cdiv%20class%3D%22text-block-5%22%3ERemove%3C%2Fdiv%3E%3C%2Fa%3E%3C%2Fdiv%3E%3Cinput%20aria-label%3D%22Update%20quantity%22%20data-wf-bindings%3D%22%255B%257B%2522value%2522%253A%257B%2522type%2522%253A%2522Number%2522%252C%2522filter%2522%253A%257B%2522type%2522%253A%2522numberPrecision%2522%252C%2522params%2522%253A%255B%25220%2522%252C%2522numberPrecision%2522%255D%257D%252C%2522dataPath%2522%253A%2522database.commerceOrder.userItems%255B%255D.count%2522%257D%257D%252C%257B%2522data-commerce-sku-id%2522%253A%257B%2522type%2522%253A%2522ItemRef%2522%252C%2522filter%2522%253A%257B%2522type%2522%253A%2522identity%2522%252C%2522params%2522%253A%255B%255D%257D%252C%2522dataPath%2522%253A%2522database.commerceOrder.userItems%255B%255D.sku.id%2522%257D%257D%255D%22%20class%3D%22w-commerce-commercecartquantity%20cart-quantity%22%20required%3D%22%22%20pattern%3D%22%5E%5B0-9%5D%2B%24%22%20inputMode%3D%22numeric%22%20type%3D%22number%22%20name%3D%22quantity%22%20autoComplete%3D%22off%22%20data-wf-cart-action%3D%22update-item-quantity%22%20data-commerce-sku-id%3D%22%22%20value%3D%221%22%2F%3E%3C%2Fdiv%3E</script>
                                        <div
                                            class="w-commerce-commercecartlist" data-wf-collection="database.commerceOrder.userItems" data-wf-template-id="wf-template-5ebc6c02-4c44-6096-412c-3600ea5b270e">
                                            <div class="w-commerce-commercecartitem"><img src="https://assets-global.website-files.com/plugins/Basic/assets/placeholder.60f9b1840c.svg" data-wf-bindings="%5B%7B%22src%22%3A%7B%22type%22%3A%22ImageRef%22%2C%22filter%22%3A%7B%22type%22%3A%22identity%22%2C%22params%22%3A%5B%5D%7D%2C%22dataPath%22%3A%22database.commerceOrder.userItems%5B%5D.sku.f_main_image_4dr%22%7D%7D%5D"
                                                    alt="" class="w-commerce-commercecartitemimage cart-image w-dyn-bind-empty" />
                                                <div class="w-commerce-commercecartiteminfo">
                                                    <div data-wf-bindings="%5B%7B%22innerHTML%22%3A%7B%22type%22%3A%22PlainText%22%2C%22filter%22%3A%7B%22type%22%3A%22identity%22%2C%22params%22%3A%5B%5D%7D%2C%22dataPath%22%3A%22database.commerceOrder.userItems%5B%5D.product.f_name_%22%7D%7D%5D"
                                                        class="w-commerce-commercecartproductname text-block-6 w-dyn-bind-empty"></div>
                                                    <div data-wf-bindings="%5B%7B%22innerHTML%22%3A%7B%22type%22%3A%22CommercePrice%22%2C%22filter%22%3A%7B%22type%22%3A%22price%22%2C%22params%22%3A%5B%5D%7D%2C%22dataPath%22%3A%22database.commerceOrder.userItems%5B%5D.price%22%7D%7D%5D"
                                                        class="cart-price">$ 0.00 USD</div>
                                                    <script type="text/x-wf-template" id="wf-template-5ebc6c02-4c44-6096-412c-3600ea5b2715">%3Cli%3E%3Cspan%20data-wf-bindings%3D%22%255B%257B%2522innerHTML%2522%253A%257B%2522type%2522%253A%2522PlainText%2522%252C%2522filter%2522%253A%257B%2522type%2522%253A%2522identity%2522%252C%2522params%2522%253A%255B%255D%257D%252C%2522dataPath%2522%253A%2522database.commerceOrder.userItems%255B%255D.product.f_sku_properties_3dr%255B%255D.name%2522%257D%257D%255D%22%3E%3C%2Fspan%3E%3Cspan%3E%3A%20%3C%2Fspan%3E%3Cspan%20data-wf-bindings%3D%22%255B%257B%2522innerHTML%2522%253A%257B%2522type%2522%253A%2522CommercePropValues%2522%252C%2522filter%2522%253A%257B%2522type%2522%253A%2522identity%2522%252C%2522params%2522%253A%255B%255D%257D%252C%2522dataPath%2522%253A%2522database.commerceOrder.userItems%255B%255D.product.f_sku_properties_3dr%255B%255D%2522%257D%257D%255D%22%3E%3C%2Fspan%3E%3C%2Fli%3E</script>
                                                    <ul
                                                        data-wf-bindings="%5B%7B%22optionSets%22%3A%7B%22type%22%3A%22CommercePropTable%22%2C%22filter%22%3A%7B%22type%22%3A%22identity%22%2C%22params%22%3A%5B%5D%7D%2C%22dataPath%22%3A%22database.commerceOrder.userItems%5B%5D.product.f_sku_properties_3dr[]%22%7D%7D%2C%7B%22optionValues%22%3A%7B%22type%22%3A%22CommercePropValues%22%2C%22filter%22%3A%7B%22type%22%3A%22identity%22%2C%22params%22%3A%5B%5D%7D%2C%22dataPath%22%3A%22database.commerceOrder.userItems%5B%5D.sku.f_sku_values_3dr%22%7D%7D%5D"
                                                        class="w-commerce-commercecartoptionlist" data-wf-collection="database.commerceOrder.userItems%5B%5D.product.f_sku_properties_3dr" data-wf-template-id="wf-template-5ebc6c02-4c44-6096-412c-3600ea5b2715">
                                                        <li><span data-wf-bindings="%5B%7B%22innerHTML%22%3A%7B%22type%22%3A%22PlainText%22%2C%22filter%22%3A%7B%22type%22%3A%22identity%22%2C%22params%22%3A%5B%5D%7D%2C%22dataPath%22%3A%22database.commerceOrder.userItems%5B%5D.product.f_sku_properties_3dr%5B%5D.name%22%7D%7D%5D"></span><span>: </span>
                                                            <span
                                                                data-wf-bindings="%5B%7B%22innerHTML%22%3A%7B%22type%22%3A%22CommercePropValues%22%2C%22filter%22%3A%7B%22type%22%3A%22identity%22%2C%22params%22%3A%5B%5D%7D%2C%22dataPath%22%3A%22database.commerceOrder.userItems%5B%5D.product.f_sku_properties_3dr%5B%5D%22%7D%7D%5D"></span>
                                                        </li>
                                                        </ul>
                                                        <a href="#" role="button" aria-label="Remove item from cart" data-wf-bindings="%5B%7B%22data-commerce-sku-id%22%3A%7B%22type%22%3A%22ItemRef%22%2C%22filter%22%3A%7B%22type%22%3A%22identity%22%2C%22params%22%3A%5B%5D%7D%2C%22dataPath%22%3A%22database.commerceOrder.userItems%5B%5D.sku.id%22%7D%7D%5D"
                                                            class="remove-button w-inline-block" data-wf-cart-action="remove-item" data-commerce-sku-id="">
                                                            <div class="text-block-5">Remove</div>
                                                        </a>
                                                </div><input aria-label="Update quantity" data-wf-bindings="%5B%7B%22value%22%3A%7B%22type%22%3A%22Number%22%2C%22filter%22%3A%7B%22type%22%3A%22numberPrecision%22%2C%22params%22%3A%5B%220%22%2C%22numberPrecision%22%5D%7D%2C%22dataPath%22%3A%22database.commerceOrder.userItems%5B%5D.count%22%7D%7D%2C%7B%22data-commerce-sku-id%22%3A%7B%22type%22%3A%22ItemRef%22%2C%22filter%22%3A%7B%22type%22%3A%22identity%22%2C%22params%22%3A%5B%5D%7D%2C%22dataPath%22%3A%22database.commerceOrder.userItems%5B%5D.sku.id%22%7D%7D%5D"
                                                    class="w-commerce-commercecartquantity cart-quantity" required="" pattern="^[0-9]+$" inputMode="numeric" type="number" name="quantity" autoComplete="off" data-wf-cart-action="update-item-quantity" data-commerce-sku-id=""
                                                    value="1" /></div>
                            </div>
                            <div class="w-commerce-commercecartfooter">
                                <div aria-atomic="true" aria-live="polite" class="w-commerce-commercecartlineitem">
                                    <div class="text-block-6">Subtotal</div>
                                    <div data-wf-bindings="%5B%7B%22innerHTML%22%3A%7B%22type%22%3A%22CommercePrice%22%2C%22filter%22%3A%7B%22type%22%3A%22price%22%2C%22params%22%3A%5B%5D%7D%2C%22dataPath%22%3A%22database.commerceOrder.subtotal%22%7D%7D%5D"
                                        class="w-commerce-commercecartordervalue text-block-6"></div>
                                </div>
                                <div>
                                    <div data-node-type="commerce-cart-quick-checkout-actions" style="display:none">
                                        <a role="button" tabindex="0" aria-label="Apple Pay" aria-haspopup="dialog" data-node-type="commerce-cart-apple-pay-button" style="background-image:-webkit-named-image(apple-pay-logo-white);background-size:100% 50%;background-position:50% 50%;background-repeat:no-repeat"
                                            class="w-commerce-commercecartapplepaybutton" tabindex="0">
                                            <div></div>
                                        </a><a role="button" tabindex="0" aria-haspopup="dialog" data-node-type="commerce-cart-quick-checkout-button" style="display:none" class="w-commerce-commercecartquickcheckoutbutton"><svg class="w-commerce-commercequickcheckoutgoogleicon" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" width="16" height="16" viewBox="0 0 16 16"><defs><polygon id="google-mark-a" points="0 .329 3.494 .329 3.494 7.649 0 7.649"></polygon><polygon id="google-mark-c" points=".894 0 13.169 0 13.169 6.443 .894 6.443"></polygon></defs><g fill="none" fill-rule="evenodd"><path fill="#4285F4" d="M10.5967,12.0469 L10.5967,14.0649 L13.1167,14.0649 C14.6047,12.6759 15.4577,10.6209 15.4577,8.1779 C15.4577,7.6339 15.4137,7.0889 15.3257,6.5559 L7.8887,6.5559 L7.8887,9.6329 L12.1507,9.6329 C11.9767,10.6119 11.4147,11.4899 10.5967,12.0469"></path><path fill="#34A853" d="M7.8887,16 C10.0137,16 11.8107,15.289 13.1147,14.067 C13.1147,14.066 13.1157,14.065 13.1167,14.064 L10.5967,12.047 C10.5877,12.053 10.5807,12.061 10.5727,12.067 C9.8607,12.556 8.9507,12.833 7.8887,12.833 C5.8577,12.833 4.1387,11.457 3.4937,9.605 L0.8747,9.605 L0.8747,11.648 C2.2197,14.319 4.9287,16 7.8887,16"></path><g transform="translate(0 4)"><mask id="google-mark-b" fill="#fff"><use xlink:href="#google-mark-a"></use></mask><path fill="#FBBC04" d="M3.4639,5.5337 C3.1369,4.5477 3.1359,3.4727 3.4609,2.4757 L3.4639,2.4777 C3.4679,2.4657 3.4749,2.4547 3.4789,2.4427 L3.4939,0.3287 L0.8939,0.3287 C0.8799,0.3577 0.8599,0.3827 0.8459,0.4117 C-0.2821,2.6667 -0.2821,5.3337 0.8459,7.5887 L0.8459,7.5997 C0.8549,7.6167 0.8659,7.6317 0.8749,7.6487 L3.4939,5.6057 C3.4849,5.5807 3.4729,5.5587 3.4639,5.5337" mask="url(#google-mark-b)"></path></g><mask id="google-mark-d" fill="#fff"><use xlink:href="#google-mark-c"></use></mask><path fill="#EA4335" d="M0.894,4.3291 L3.478,6.4431 C4.113,4.5611 5.843,3.1671 7.889,3.1671 C9.018,3.1451 10.102,3.5781 10.912,4.3671 L13.169,2.0781 C11.733,0.7231 9.85,-0.0219 7.889,0.0001 C4.941,0.0001 2.245,1.6791 0.894,4.3291" mask="url(#google-mark-d)"></path></g></svg><svg class="w-commerce-commercequickcheckoutmicrosofticon" xmlns="http://www.w3.org/2000/svg" width="16" height="16" viewBox="0 0 16 16"><g fill="none" fill-rule="evenodd"><polygon fill="#F05022" points="7 7 1 7 1 1 7 1"></polygon><polygon fill="#7DB902" points="15 7 9 7 9 1 15 1"></polygon><polygon fill="#00A4EE" points="7 15 1 15 1 9 7 9"></polygon><polygon fill="#FFB700" points="15 15 9 15 9 9 15 9"></polygon></g></svg><div>Pay with browser.</div></a></div>
                                    <a
                                        href="/checkout" value="Continue to Checkout" data-node-type="cart-checkout-button" class="w-commerce-commercecartcheckoutbutton checkout-button" data-loading-text="Hang Tight...">Continue to Checkout</a>
                                        <div data-wf-paypal-button="{&quot;layout&quot;:&quot;vertical&quot;,&quot;color&quot;:&quot;black&quot;,&quot;shape&quot;:&quot;rect&quot;,&quot;label&quot;:&quot;checkout&quot;,&quot;tagline&quot;:false,&quot;note&quot;:true}"
                                            class="paypal"></div>
                                </div>
                            </div>
                            </form>
                            <div class="w-commerce-commercecartemptystate">
                                <div aria-live="polite" aria-label="This cart is empty">No items found.</div>
                            </div>
                            <div aria-live="assertive" style="display:none" data-node-type="commerce-cart-error" class="w-commerce-commercecarterrorstate error-state-2">
                                <div class="w-cart-error-msg" data-w-cart-quantity-error="Product is not available in this quantity." data-w-cart-general-error="Something went wrong when adding this item to the cart." data-w-cart-checkout-error="Checkout is disabled on this site."
                                    data-w-cart-cart_order_min-error="The order minimum was not met. Add more items to your cart to continue." data-w-cart-subscription_error-error="Before you purchase, please use your email invite to verify your address so we can send order updates.">Product is not available in this quantity.</div>
                            </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
    <div data-w-id="5ebc6c02-4c44-6096-412c-3600ea5b2736" class="menu-hamburger-wrapper"><img src="https://assets-global.website-files.com/63b57776402c77650eb13f9f/63ba7974cfc084570a6a1bc8_hamburger.webp" loading="lazy" alt="" class="menu-hamburger-icon" /><img src="https://assets-global.website-files.com/63b57776402c77650eb13f9f/63ba7974cfc08438536a1bc6_close.webp"
            loading="lazy" alt="" class="menu-close-icon" /></div>
    </div>
    </div>
    <div class="full-screen-menu">
        <div class="menu-wrapper">
            <div class="left">
                <a href="/" aria-current="page" class="menu-link-block w-inline-block w--current">
                    <div class="white-outline-menu">home</div>
                    <div class="white-outline-menu second">home</div>
                </a>
                <a href="/work" class="menu-link-block w-inline-block">
                    <div class="white-outline-menu">work</div>
                    <div class="white-outline-menu second">work</div>
                </a>
                <a href="/hire-me" class="menu-link-block w-inline-block">
                    <div class="white-outline-menu">hire me</div>
                    <div class="white-outline-menu second">hire me</div>
                </a>
                <a href="/about" class="menu-link-block w-inline-block">
                    <div class="white-outline-menu">about</div>
                    <div class="white-outline-menu second">about</div>
                </a>
                <a href="/contact" class="menu-link-block w-inline-block">
                    <div class="white-outline-menu">contact</div>
                    <div class="white-outline-menu second">contact</div>
                </a>
            </div>
            <div class="right">
                <div class="follow-me-wrapper">
                    <div class="follow-me">Follow Me On</div>
                </div>
                <div class="social-links"><a data-w-id="5ebc6c02-4c44-6096-412c-3600ea5b275a" href="http://www.facebook.com" target="_blank" class="social-icon-link w-inline-block"><img src="https://assets-global.website-files.com/63b57776402c77650eb13f9f/63ba83fe18d4e0282532c3e9_facebook-app-symbol%20(1).png" loading="lazy" width="45" alt=""/></a>
                    <a
                        href="http://www.twitter.com" target="_blank" class="social-icon-link w-inline-block"><img src="https://assets-global.website-files.com/63b57776402c77650eb13f9f/63ba83fa15cbc75d2a8cb7b0_twitter.png" loading="lazy" width="45" alt="" /></a><a href="http://www.instagram.com" target="_blank" class="social-icon-link w-inline-block"><img src="https://assets-global.website-files.com/63b57776402c77650eb13f9f/63ba83f8e6b85e9b517106e3_instagram.png" loading="lazy" width="45" alt=""/></a>
                        <a
                            href="#" target="_blank" class="social-icon-link w-inline-block"><img src="https://assets-global.website-files.com/63b57776402c77650eb13f9f/63ba83f93d3d7a28305b86b1_linkedin.png" loading="lazy" width="45" alt="" /></a><a href="http://www.youtube.com" target="_blank" class="social-icon-link w-inline-block"><img src="https://assets-global.website-files.com/63b57776402c77650eb13f9f/63ba83feae7aab50149c9cbb_youtube.png" loading="lazy" width="45" alt=""/></a></div>
            </div>
        </div>
    </div>
    </div>
    <div class="hero-section"><img class="hero-image" src="https://assets-global.website-files.com/63b57776402c77650eb13f9f/63b57ba207797437b6103fe0_christopher-campbell-Xo4YvBp6IBM-unsplash.jpg" alt="" style="opacity:0" sizes="(max-width: 767px) 100vw, (max-width: 991px) 90vw, 50vw"
            data-w-id="72662cdc-a6f4-d5b0-686c-ffff7f494406" loading="lazy" srcset="https://assets-global.website-files.com/63b57776402c77650eb13f9f/63b57ba207797437b6103fe0_christopher-campbell-Xo4YvBp6IBM-unsplash-p-500.jpg 500w, https://assets-global.website-files.com/63b57776402c77650eb13f9f/63b57ba207797437b6103fe0_christopher-campbell-Xo4YvBp6IBM-unsplash-p-800.jpg 800w, https://assets-global.website-files.com/63b57776402c77650eb13f9f/63b57ba207797437b6103fe0_christopher-campbell-Xo4YvBp6IBM-unsplash-p-1080.jpg 1080w, https://assets-global.website-files.com/63b57776402c77650eb13f9f/63b57ba207797437b6103fe0_christopher-campbell-Xo4YvBp6IBM-unsplash-p-1600.jpg 1600w, https://assets-global.website-files.com/63b57776402c77650eb13f9f/63b57ba207797437b6103fe0_christopher-campbell-Xo4YvBp6IBM-unsplash.jpg 1920w"
        />
        <h1 data-w-id="277ba81f-c73c-24c5-2b56-55473fc36072" style="opacity:0" class="hero-heading-outline">George maxwell</h1>
    </div>
    <div data-w-id="d7a73ded-bdd2-fd59-9160-927ef7d88bbe" class="track">
        <div class="camera">
            <div class="frame">
                <div class="item">
                    <div class="collection-list-wrapper w-dyn-list">
                        <div role="list" class="collection-list first w-dyn-items">
                            <div role="listitem" class="collection-item w-dyn-item">
                                <a data-w-id="6e0ff2d2-2cb8-88fc-4c30-7c59ce5937a6" href="/portfolio/softlife" class="link-block w-inline-block">
                                    <div class="image-wrapper"><img src="https://assets-global.website-files.com/63b5882c1786c11ede9e605b/63b6837a89ebb45b4e3ef358_shubham-dhage-mjl0yIdSi18-unsplash.jpg" loading="lazy" alt="" sizes="(max-width: 479px) 93vw, 99vw" srcset="https://assets-global.website-files.com/63b5882c1786c11ede9e605b/63b6837a89ebb45b4e3ef358_shubham-dhage-mjl0yIdSi18-unsplash-p-500.jpg 500w, https://assets-global.website-files.com/63b5882c1786c11ede9e605b/63b6837a89ebb45b4e3ef358_shubham-dhage-mjl0yIdSi18-unsplash-p-800.jpg 800w, https://assets-global.website-files.com/63b5882c1786c11ede9e605b/63b6837a89ebb45b4e3ef358_shubham-dhage-mjl0yIdSi18-unsplash-p-1080.jpg 1080w, https://assets-global.website-files.com/63b5882c1786c11ede9e605b/63b6837a89ebb45b4e3ef358_shubham-dhage-mjl0yIdSi18-unsplash-p-1600.jpg 1600w, https://assets-global.website-files.com/63b5882c1786c11ede9e605b/63b6837a89ebb45b4e3ef358_shubham-dhage-mjl0yIdSi18-unsplash.jpg 1920w"
                                            class="porftolio-image" />
                                        <div class="portfolio-details">
                                            <h2 class="portfolio-heading">Softlife</h2>
                                        </div>
                                        <div class="hover-wrapper">
                                            <div style="opacity:0" class="icon-wrapper"><img src="https://assets-global.website-files.com/63b57776402c77650eb13f9f/63b62a1f9be4fb40dcc4b567_right-down.png" loading="lazy" width="50" alt="" class="hover-icon" /></div>
                                        </div>
                                    </div>
                                </a>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="item">
                    <div class="collection-list-wrapper w-dyn-list">
                        <div role="list" class="collection-list second w-dyn-items">
                            <div role="listitem" class="collection-item w-dyn-item">
                                <a data-w-id="a7dfeb5b-34fc-aa83-a8ab-265193e6c468" href="/portfolio/punk-hand" class="link-block w-inline-block">
                                    <div class="image-wrapper"><img src="https://assets-global.website-files.com/63b5882c1786c11ede9e605b/63b67d5b8a44f085690edcef_axel-ruffini-iulnjpZyWnc-unsplash.jpg" loading="lazy" alt="" sizes="(max-width: 479px) 93vw, 99vw" srcset="https://assets-global.website-files.com/63b5882c1786c11ede9e605b/63b67d5b8a44f085690edcef_axel-ruffini-iulnjpZyWnc-unsplash-p-500.jpg 500w, https://assets-global.website-files.com/63b5882c1786c11ede9e605b/63b67d5b8a44f085690edcef_axel-ruffini-iulnjpZyWnc-unsplash-p-800.jpg 800w, https://assets-global.website-files.com/63b5882c1786c11ede9e605b/63b67d5b8a44f085690edcef_axel-ruffini-iulnjpZyWnc-unsplash-p-1080.jpg 1080w, https://assets-global.website-files.com/63b5882c1786c11ede9e605b/63b67d5b8a44f085690edcef_axel-ruffini-iulnjpZyWnc-unsplash-p-1600.jpg 1600w, https://assets-global.website-files.com/63b5882c1786c11ede9e605b/63b67d5b8a44f085690edcef_axel-ruffini-iulnjpZyWnc-unsplash.jpg 1920w"
                                            class="porftolio-image" />
                                        <div class="portfolio-details">
                                            <h1 class="portfolio-heading">Punk Hand</h1>
                                        </div>
                                        <div class="hover-wrapper">
                                            <div style="opacity:0" class="icon-wrapper"><img src="https://assets-global.website-files.com/63b57776402c77650eb13f9f/63b62a1f9be4fb40dcc4b567_right-down.png" loading="lazy" width="50" alt="" class="hover-icon" /></div>
                                        </div>
                                    </div>
                                </a>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="item">
                    <div class="collection-list-wrapper w-dyn-list">
                        <div role="list" class="collection-list third w-dyn-items">
                            <div role="listitem" class="collection-item w-dyn-item">
                                <a data-w-id="07ba8e05-b1d1-8a6d-fe04-a2f11de6fd59" href="/portfolio/magnum-ai" class="link-block w-inline-block">
                                    <div class="image-wrapper"><img src="https://assets-global.website-files.com/63b5882c1786c11ede9e605b/63b67e9d150d75ac86896f7c_pexels-pavel-danilyuk-8294624.jpg" loading="lazy" alt="" sizes="(max-width: 479px) 93vw, 99vw" srcset="https://assets-global.website-files.com/63b5882c1786c11ede9e605b/63b67e9d150d75ac86896f7c_pexels-pavel-danilyuk-8294624-p-500.jpg 500w, https://assets-global.website-files.com/63b5882c1786c11ede9e605b/63b67e9d150d75ac86896f7c_pexels-pavel-danilyuk-8294624-p-800.jpg 800w, https://assets-global.website-files.com/63b5882c1786c11ede9e605b/63b67e9d150d75ac86896f7c_pexels-pavel-danilyuk-8294624-p-1080.jpg 1080w, https://assets-global.website-files.com/63b5882c1786c11ede9e605b/63b67e9d150d75ac86896f7c_pexels-pavel-danilyuk-8294624.jpg 1279w"
                                            class="porftolio-image" />
                                        <div class="portfolio-details">
                                            <h1 class="portfolio-heading">Magnum AI</h1>
                                        </div>
                                        <div class="hover-wrapper">
                                            <div style="opacity:0" class="icon-wrapper"><img src="https://assets-global.website-files.com/63b57776402c77650eb13f9f/63b62a1f9be4fb40dcc4b567_right-down.png" loading="lazy" width="50" alt="" class="hover-icon" /></div>
                                        </div>
                                    </div>
                                </a>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="item">
                    <div class="collection-list-wrapper w-dyn-list">
                        <div role="list" class="collection-list fourth w-dyn-items">
                            <div role="listitem" class="collection-item w-dyn-item">
                                <a data-w-id="2a7e196f-4876-b641-266c-6a26977a1317" href="/portfolio/plastic-form" class="link-block w-inline-block">
                                    <div class="image-wrapper"><img src="https://assets-global.website-files.com/63b5882c1786c11ede9e605b/63b67f940236ebf56f9a0897_vinicius-amnx-amano-OHPdgstNFGs-unsplash.jpg" loading="lazy" alt="" sizes="(max-width: 479px) 93vw, 99vw" srcset="https://assets-global.website-files.com/63b5882c1786c11ede9e605b/63b67f940236ebf56f9a0897_vinicius-amnx-amano-OHPdgstNFGs-unsplash-p-500.jpg 500w, https://assets-global.website-files.com/63b5882c1786c11ede9e605b/63b67f940236ebf56f9a0897_vinicius-amnx-amano-OHPdgstNFGs-unsplash-p-800.jpg 800w, https://assets-global.website-files.com/63b5882c1786c11ede9e605b/63b67f940236ebf56f9a0897_vinicius-amnx-amano-OHPdgstNFGs-unsplash-p-1080.jpg 1080w, https://assets-global.website-files.com/63b5882c1786c11ede9e605b/63b67f940236ebf56f9a0897_vinicius-amnx-amano-OHPdgstNFGs-unsplash-p-1600.jpg 1600w, https://assets-global.website-files.com/63b5882c1786c11ede9e605b/63b67f940236ebf56f9a0897_vinicius-amnx-amano-OHPdgstNFGs-unsplash.jpg 1920w"
                                            class="porftolio-image" />
                                        <div class="portfolio-details">
                                            <h1 class="portfolio-heading">Plastic form</h1>
                                        </div>
                                        <div class="hover-wrapper">
                                            <div style="opacity:0" class="icon-wrapper"><img src="https://assets-global.website-files.com/63b57776402c77650eb13f9f/63b62a1f9be4fb40dcc4b567_right-down.png" loading="lazy" width="50" alt="" class="hover-icon" /></div>
                                        </div>
                                    </div>
                                </a>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
    <div class="see-all-work">
        <a data-w-id="1dd223e7-9643-2369-36fd-56f4c73c9f17" href="/work" class="link-button w-inline-block">
            <h2 data-w-id="f134c589-2463-9d62-5258-17a977d2d263" style="opacity:0" class="h1-heading">See all work</h2>
            <div data-w-id="018f066f-1adc-712a-8c66-daf69bccb98b" style="opacity:0" class="icon-wrapper-list _2">
                <div class="icon-wrapper margin"><img src="https://assets-global.website-files.com/63b57776402c77650eb13f9f/63b62a1f9be4fb40dcc4b567_right-down.png" loading="lazy" width="50" alt="" class="hover-icon" /></div>
                <div class="icon-wrapper margin"><img src="https://assets-global.website-files.com/63b57776402c77650eb13f9f/63b62a1f9be4fb40dcc4b567_right-down.png" loading="lazy" width="50" alt="" class="hover-icon" /></div>
            </div>
        </a>
    </div>
    <div class="section">
        <div class="container w-container">
            <div class="w-layout-grid grid">
                <div id="w-node-dd03d857-c752-e4f6-af3a-e29d4fee42aa-0bfe8bf8" class="sticky">
                    <h2 data-w-id="abceeb14-620c-7ea1-e640-a44934c93087" style="opacity:0">my Services</h2>
                </div>
                <div data-w-id="13a2881d-1ac1-aa28-5aeb-452b1007804f" style="opacity:0" class="services">
                    <div id="w-node-_3342c1b7-aaaf-8fbb-d347-cdb4b1a024a2-0bfe8bf8" class="wrap">
                        <h2 class="title-outline">Product Design</h2>
                        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Suspendisse varius enim in eros elementum tristique. Duis cursus, mi quis viverra ornare, eros dolor interdum nulla, ut commodo diam libero vitae erat. Aenean faucibus nibh
                            et justo cursus id rutrum lorem imperdiet. Nunc ut sem vitae risus tristique posuere.</p>
                    </div>
                    <div class="wrap">
                        <h2 class="title-outline">UX/UI Design</h2>
                        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Suspendisse varius enim in eros elementum tristique. Duis cursus, mi quis viverra ornare, eros dolor interdum nulla, ut commodo diam libero vitae erat. Aenean faucibus nibh
                            et justo cursus id rutrum lorem imperdiet. Nunc ut sem vitae risus tristique posuere.</p>
                    </div>
                    <div class="wrap">
                        <h2 class="title-outline">Web Development</h2>
                        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Suspendisse varius enim in eros elementum tristique. Duis cursus, mi quis viverra ornare, eros dolor interdum nulla, ut commodo diam libero vitae erat. Aenean faucibus nibh
                            et justo cursus id rutrum lorem imperdiet. Nunc ut sem vitae risus tristique posuere.</p>
                    </div>
                    <div class="wrap">
                        <h2 class="title-outline">App Development</h2>
                        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Suspendisse varius enim in eros elementum tristique. Duis cursus, mi quis viverra ornare, eros dolor interdum nulla, ut commodo diam libero vitae erat. Aenean faucibus nibh
                            et justo cursus id rutrum lorem imperdiet. Nunc ut sem vitae risus tristique posuere.</p>
                    </div>
                    <div data-w-id="c9937a92-15c1-ad90-2a06-4ba2061a5707" style="opacity:0" class="link-wrapper">
                        <a data-w-id="38defdec-250c-ffca-3658-ad5406518e23" href="/hire-me" class="link-button w-inline-block">
                            <h2 class="h1-heading">Hire me</h2>
                            <div class="icon-wrapper-list _2">
                                <div class="icon-wrapper margin"><img src="https://assets-global.website-files.com/63b57776402c77650eb13f9f/63b62a1f9be4fb40dcc4b567_right-down.png" loading="lazy" width="50" alt="" class="hover-icon" /></div>
                                <div class="icon-wrapper margin"><img src="https://assets-global.website-files.com/63b57776402c77650eb13f9f/63b62a1f9be4fb40dcc4b567_right-down.png" loading="lazy" width="50" alt="" class="hover-icon" /></div>
                            </div>
                        </a>
                    </div>
                </div>
            </div>
        </div>
    </div>
    <div class="section white">
        <div class="container w-container">
            <div class="title-wrapper">
                <h2 data-w-id="47e99f3c-e1f5-ec3e-f844-f4f93be29403" style="opacity:0" class="heading-black">my Clients</h2>
            </div>
            <div data-w-id="8faa5354-a5bf-9313-0e45-fbba2b59c21f" style="opacity:0" class="w-layout-grid logos-grid">
                <div id="w-node-_16bfce4a-a636-9485-a24d-c0c2176022e5-0bfe8bf8" class="logo-wrapper"><img src="https://assets-global.website-files.com/63b57776402c77650eb13f9f/63b6669124e16eb514da8cb9_628df6b234fb2d7627a599d2_Clients%20logo%202.svg" loading="lazy" alt="" class="clients-logo" /></div>
                <div id="w-node-_0ecb26ee-24b0-cae1-bcfb-f7b457cb7f09-0bfe8bf8"
                    class="logo-wrapper"><img src="https://assets-global.website-files.com/63b57776402c77650eb13f9f/63b66690133ca71d8c171f25_628df6c45ed89e2a5b1c48f2_Clients%20logo%204.svg" loading="lazy" alt="" class="clients-logo" /></div>
                <div id="w-node-_5e1cf245-13d0-c3de-848d-faa14771a04a-0bfe8bf8"
                    class="logo-wrapper"><img src="https://assets-global.website-files.com/63b57776402c77650eb13f9f/63b6668fd4a068032d706db5_628df6bc33669d3569512481_Clients%20logo%203.svg" loading="lazy" alt="" class="clients-logo" /></div>
                <div id="w-node-dd0265c1-783d-4403-9c1b-d5db95e3c6e6-0bfe8bf8"
                    class="logo-wrapper"><img src="https://assets-global.website-files.com/63b57776402c77650eb13f9f/63b66751723165454e148241_628df678e6296d1d9c14ef63_Clients%20logo%201.svg" loading="lazy" alt="" class="clients-logo" /></div>
                <div id="w-node-_17d881ae-b157-21bc-a0a3-b489af21e7cf-0bfe8bf8"
                    class="logo-wrapper"><img src="https://assets-global.website-files.com/63b57776402c77650eb13f9f/63b6668fd4a068032d706db5_628df6bc33669d3569512481_Clients%20logo%203.svg" loading="lazy" alt="" class="clients-logo" /></div>
                <div id="w-node-_9b0694e2-4e81-5acb-7dce-5f917ec4489a-0bfe8bf8"
                    class="logo-wrapper"><img src="https://assets-global.website-files.com/63b57776402c77650eb13f9f/63b66751723165454e148241_628df678e6296d1d9c14ef63_Clients%20logo%201.svg" loading="lazy" alt="" class="clients-logo" /></div>
                <div id="w-node-_86912e0f-89d7-9416-2d1a-c84454514bfc-0bfe8bf8"
                    class="logo-wrapper"><img src="https://assets-global.website-files.com/63b57776402c77650eb13f9f/63b6669124e16eb514da8cb9_628df6b234fb2d7627a599d2_Clients%20logo%202.svg" loading="lazy" alt="" class="clients-logo" /></div>
                <div id="w-node-bb49b43c-7212-512f-ab17-4db55a599fbb-0bfe8bf8"
                    class="logo-wrapper"><img src="https://assets-global.website-files.com/63b57776402c77650eb13f9f/63b66690133ca71d8c171f25_628df6c45ed89e2a5b1c48f2_Clients%20logo%204.svg" loading="lazy" alt="" class="clients-logo" /></div>
            </div>
        </div>
    </div>
    <div class="section white">
        <div class="container w-container">
            <div data-w-id="6df12351-c5c3-6eb0-fa06-e045a5a98250" style="opacity:0" class="link-wrapper">
                <a data-w-id="6df12351-c5c3-6eb0-fa06-e045a5a98251" href="/contact" class="link-button contact-me w-inline-block">
                    <h2 class="heading-black contact-me">Contact Me</h2>
                    <div class="icon-wrapper-list">
                        <div class="icon-wrapper margin invert"><img src="https://assets-global.website-files.com/63b57776402c77650eb13f9f/63b62a1f9be4fb40dcc4b567_right-down.png" loading="lazy" width="50" alt="" class="hover-icon" /></div>
                        <div class="icon-wrapper margin invert"><img src="https://assets-global.website-files.com/63b57776402c77650eb13f9f/63b62a1f9be4fb40dcc4b567_right-down.png" loading="lazy" width="50" alt="" class="hover-icon" /></div>
                    </div>
                </a>
            </div>
        </div>
    </div>
    <div class="footer">
        <div class="container-3 w-container">
            <div class="w-layout-grid footer-grid">
                <div id="w-node-_886502b4-2d6e-730b-e2ff-7a0b1975cdc3-1975cdbf" class="footer-wrapper">
                    <div class="footer-links-horizontal"><a href="/template/style-guide" class="link-footer">Style Guide</a><a href="/template/licensing" class="link-footer">Licenses</a><a href="/template/changelog" class="link-footer">Changelog</a></div>
                </div>
                <div id="w-node-_886502b4-2d6e-730b-e2ff-7a0b1975cdcd-1975cdbf" class="footer-wrapper">
                    <div class="footer-links-horizontal justify-right"><a href="/" aria-current="page" class="link-footer w--current">Home</a><a href="/work" class="link-footer">work</a><a href="/hire-me" class="link-footer">hire me</a><a href="/about" class="link-footer">about</a><a href="/contact" class="link-footer">contact</a></div>
                </div>
            </div>
            <div class="footer-text-block-wrapper">
                <div class="footer-text-block">Powered by <a href="http://www.webflow.com">Webflow</a> Designed by Olajide Fakorede</div>
            </div>
        </div>
    </div>
    <a href="https://www.olatemplates.com/" target="_blank" class="more-templates-link w-inline-block">
        <div class="fixed-button-text">More Portfolio Templates</div><img src="https://assets-global.website-files.com/63b57776402c77650eb13f9f/65d52c6fca3bc97032761453_next%20(2).png" loading="lazy" width="20" alt="" class="arrow-icon-button" /></a>
    <script src="https://d3e54v103j8qbb.cloudfront.net/js/jquery-3.5.1.min.dc5e7f18c8.js?site=63b57776402c77650eb13f9f"
        type="text/javascript" integrity="sha256-9/aliU8dGd2tb6OSsuzixeV4y/faTqgFtohetphbbj0=" crossorigin="anonymous"></script>
    <script src="https://assets-global.website-files.com/63b57776402c77650eb13f9f/js/webflow.826f3e7b9.js" type="text/javascript"></script>
</body>

</html>
