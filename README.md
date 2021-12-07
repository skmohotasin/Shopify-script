# Shopify-script
Shopify Scripts are small pieces of code that let you create personalized experiences for your customers in their cart and at checkout.

When you create or edit a script, you choose whether it will run in your online store only, or in your online store and in the following apps:

Private apps built with the Storefront API, JavaScript Buy SDK, Mobile Buy SDKs (Android and iOS)
Private apps that generate checkouts
Tapcart and Plobal Apps mobile app builders
For scripts to work, they require the website to have built-in shopping cart functionality and so scripts can't be used with the Buy button, Facebook, or Wholesale sales channels.

You can use scripts to create discounts that are applied to a cart based on the items in that cart as well as other cart properties. You can also use scripts to customize the shipping and payment options that are available to your customers.

You write scripts using the Shopify Scripts API, which uses a limited version of the Ruby programming language. You can write, edit, manage, and publish scripts using the Script Editor. The Script Editor provides templates to help you write scripts and a debugger to help you test them.

After you have published a script, you can update your Liquid template files so that your online store responds to the changes that your scripts make.

Script examples
The following list contains examples of the types of discounts and customizations you can make with scripts:

discount products with specific tags to offer percentage (%) or fixed ($) discounts, or a combination of both
run promotions with simple or complex logic (buy one, get one free (BOGO); buy two get 10% off, buy four get 20% off)
offer dynamic pricing with volume-based price breaks
modify, hide, or re-order shipping options and prices
modify, hide, or re-order payment gateway methods
You can create the following types of scripts:

Line item scripts—These scripts affect line items in a cart and can change prices and grant discounts. These scripts run each time that an item is added, removed, or changed in your cart.
Shipping scripts—These scripts interact with shipping, and can change shipping methods and grant discounts on shipping rates. These scripts run each time that your customer accesses the shipping options page at checkout.
Payment scripts—These scripts interact with payments, and can rename, hide and re-order payment gateways. These scripts run each time that your customer accesses the payment method page at checkout. Payment scripts do not interact with payment gateways, such as PayPal Express or Apple Pay, that are shown to your customer before the checkout.
Script templates
The Script Editor includes templates of common scripts. When you create a script, you can choose a template and edit it for the needs of your store. The following list contains examples of the templates that you can customize:

percentage (%) off a product
amount ($) off a product
percentage (%) and amount ($) off a product
bulk discounts
buy one get one free (BOGO)
modify shipping rate price
modify shipping rate name
hide shipping rates
re-order shipping rates
modify payment gateway name
hide payment gateway
re-order payment gateways
