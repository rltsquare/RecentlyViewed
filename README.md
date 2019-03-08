# RecentlyViewed-Magento2

# Overview

The Recently Viewed Products for Magento 2 extension has been developed by the product team at RLTSquare. This extension will allows merchants to retain the browsing history of each individual visitor and show them recently viewed items WITHOUT having to create an account. So, why not let your customers take an active part in your online eCommerce business and eventually get benefit from it?

Here are some of the salient features for the extension:

```
1. Allow your customers to capture their recently viewed products.
2. Number of products in the slider can be minimize and maximize from admin extension configuration.
3. Lazyload on slider where all the products display.
4. Visible on Product Page and Category Page.
5. Expired Visitor Id's will be delete through Cron Job by selecting backend extension configuration.
```

## Installation

### Magento® Marketplace

This extension will also be available on the Magento® Marketplace when approved.

### Manually

1. Go to Magento® 2 root folder

2. Require/Download this extension:

   Enter following commands to install extension.

   ```
   composer require rltsquare/recently-viewed
   ```

   Wait while composer is updated.
   
   #### OR
   
   You can also download code from this repo under Magento® 2 following directory:
    
    ```
    app/code/RLTSquare/RecentlyViewed
    ```    

3. Enter following commands to enable the module:

   ```
   php bin/magento module:enable RLTSquare_RecentlyViewed
   php bin/magento setup:upgrade
   php bin/magento cache:clean
   php bin/magento cache:flush
   ```

4. If Magento® is running in production mode, deploy static content: 

   ```
   php bin/magento setup:static-content:deploy
   ```


## Requirements

1. This Magento® extension works on Magento 2.1,2.2 and 2.3 versions. Tested on versions 2.2.5 and above.

2. Tested on different themes specifically Ultimo, Porto and certain custom themes

For details, read our blog:
https://www.rltsquare.com/blog/recently-viewed-magento-2-extension/
