---
title: "WooCommerce"
description: "Wordpress plugin for payments."
category: "Developer Tools"
developer: "WooCommerce"
developerSite: "https://github.com/mobilecoinofficial/mobilecoin-payments-plugin"
icon: "https://raw.githubusercontent.com/mobilecoinofficial/awesome-mobilecoin/main/directory/images/woo.svg"
github: "https://github.com/mobilecoinofficial/mobilecoin-payments-plugin"
---

One of the latest software releases from MobileCoin is a plugin that enables a payments option for MobileCoin during checkout in the popular [WooCommerce store for WordPress](https://woocommerce.com/).  This plugin enables any online shop built on top of WooCommerce to easily be able to accept and process payments using the MobileCoin (MOB) cryptocurrency **worldwide in under 5 seconds with negligible transaction fees**.

Wordpress powers 40% of the world's websites. WooCommerce powers over 28% of all online stores. MobileCoin Payments Plugin enables WooCommerce stores to accept MOB as a Payment Method. Come join our private beta. 

When you use WooCommerce as your website's e-commerce engine, our plugin (MobileCoin Payments) will enable you to add a new MOB Payment Method to use within WooCommerce. When a customer selects the MobileCoin Payment Method, they will be redirected to a MobileCoin Self-Hosted Payments Page where they can pay in MOB. When the payment goes through, the clients will be redirected back to your website's Confirmation Page.

## How to get your MobileCoin API Keys
Would you like to sell your products for MOB? Send us an email at payments@mobilecoin.com to join our private alpha for early access.


#### Show Me the Code
[WooCommerce Plugin](https://github.com/mobilecoinofficial/mobilecoin-payments-plugin)

## How To Enable The MobileCoin Payments Plugin In WooCommerce

Following is a step-by-step guide on how to enable MobileCoin Payments in your WooCommerce shop. This guide assumes that you've already installed [WordPress](https://wordpress.org/) including the [WooCommerce plugin](https://woocommerce.com/), and have configured WooCommerce so that you have a basic shop up and running.

Step-By-Step Guide
------------------

The first thing we need to do is head on over to the [MobileCoin repository](https://github.com/mobilecoinofficial/mobilecoin-payments-plugin) on GitHub to download the latest version of the [MobileCoin Payments plugin for WooCommerce](https://github.com/mobilecoinofficial/mobilecoin-payments-plugin). We can download the source code for the plugin by clicking on the green `Code` button and selecting the `Download ZIP` option from the drop-down menu.

[![](https://blog.kareldonk.com/wp-content/uploads/2021/12/mobsteps1-1440x746.jpg)](https://blog.kareldonk.com/wp-content/uploads/2021/12/mobsteps1.jpg)

Downloading the plugin

After we've downloaded the ZIP file, we can open it and view its contents. You'll find a folder called `mobilecoin-payments-plugin-main` inside the ZIP file. This entire folder needs to be uploaded to the `wp-content\plugins` folder of our WordPress website. There are several ways to do this. We can use the File Manager in the cPanel management software of our website, or we can use FTP software such as FileZilla. Most hosting providers provide access to cPanel for their webhosting products so we'll go with that.

[![](https://blog.kareldonk.com/wp-content/uploads/2021/12/mobsteps1a-1440x746.jpg)](https://blog.kareldonk.com/wp-content/uploads/2021/12/mobsteps1a.jpg)

The File Manager icon in cPanel

Using File Manager in cPanel we can navigate to the `wp-content\plugins` subfolder of our WordPress installation. We can then upload the ZIP file to that folder by using the upload feature.

[![](https://blog.kareldonk.com/wp-content/uploads/2021/12/mobsteps2-1440x746.jpg)](https://blog.kareldonk.com/wp-content/uploads/2021/12/mobsteps2.jpg)

Uploading the MobileCoin Payments plugin ZIP file

We can then select the ZIP file we downloaded from the GitHub repository and upload it.

[![](https://blog.kareldonk.com/wp-content/uploads/2021/12/mobsteps3-1440x746.jpg)](https://blog.kareldonk.com/wp-content/uploads/2021/12/mobsteps3.jpg)

File selection page

After that we need to extract the contents of the ZIP file in the plugins folder. We do that by first selecting the ZIP file and then clicking the `Extract` button.

[![](https://blog.kareldonk.com/wp-content/uploads/2021/12/mobsteps4-1440x746.jpg)](https://blog.kareldonk.com/wp-content/uploads/2021/12/mobsteps4.jpg)

Extracting the MobileCoin Payments plugin ZIP file

We choose to extract the contents of the ZIP file in the same plugins folder; remember that the ZIP file already contained a folder called `mobilecoin-payments-plugin-main`, so that folder will get extracted to the plugins folder.

[![](https://blog.kareldonk.com/wp-content/uploads/2021/12/mobsteps5-1440x746.jpg)](https://blog.kareldonk.com/wp-content/uploads/2021/12/mobsteps5.jpg)

Extraction location

After the ZIP file has been extracted, we can select it and then click on the `Delete` button to delete it.

[![](https://blog.kareldonk.com/wp-content/uploads/2021/12/mobsteps6-1440x746.jpg)](https://blog.kareldonk.com/wp-content/uploads/2021/12/mobsteps6.jpg)

Deleting the MobileCoin Payments plugin ZIP file

The folder structure in FileManager should look like the images below, where we can see the `mobilecoin-payments-plugin-main` subfolder in the plugins folder.

[![](https://blog.kareldonk.com/wp-content/uploads/2021/12/mobsteps7-1440x746.jpg)](https://blog.kareldonk.com/wp-content/uploads/2021/12/mobsteps7.jpg)

The MobileCoin Payments plugin folder

[![](https://blog.kareldonk.com/wp-content/uploads/2021/12/mobsteps8-1440x746.jpg)](https://blog.kareldonk.com/wp-content/uploads/2021/12/mobsteps8.jpg)

Contents of the MobileCoin Payments plugin folder

Now that we have uploaded the MobileCoin Payments plugin to the webserver, it's time to enable it in WordPress. Navigate to the plugins page in WordPress, scroll down and find the "MobileCoin Payments" plugin. Click on the `Activate` link to activate the plugin.

[![](https://blog.kareldonk.com/wp-content/uploads/2021/12/mobsteps9-1440x746.jpg)](https://blog.kareldonk.com/wp-content/uploads/2021/12/mobsteps9.jpg)

Activating the MobileCoin Payments plugin in WordPress

Once the plugin has been activated we can now go to the settings page in WooCommerce and then click on the payments tab. We then need to enable the "MobileCoin Payments" option to be able to use the MobileCoin Payments Gateway during checkout in WooCommerce. After that click on the `Setup` button where we have to specify the unique API keys for our store.

[![](https://blog.kareldonk.com/wp-content/uploads/2021/12/mobsteps10-1440x746.jpg)](https://blog.kareldonk.com/wp-content/uploads/2021/12/mobsteps10.jpg)

Activating the MobileCoin Payments option in WooCommerce

At the moment, API keys can be obtained by sending an email to <payments@mobilecoin.com>. I imagine that this process of obtaining API keys will get automated in the future. Once we've received our API keys we can fill them in and save the changes.

[![](https://blog.kareldonk.com/wp-content/uploads/2021/12/mobsteps11-1440x746.jpg)](https://blog.kareldonk.com/wp-content/uploads/2021/12/mobsteps11.jpg)

Configuring the MobileCoin Payments option in WooCommerce

Now that the MobileCoin Payments plugin has been activated and configured, we can test it using WooCommerce checkout. Add a product to the shopping cart and proceed to the checkout page.

[![](https://blog.kareldonk.com/wp-content/uploads/2021/12/mobsteps12.jpg)](https://blog.kareldonk.com/wp-content/uploads/2021/12/mobsteps12.jpg)

The MobileCoin Payments Gateway option during checkout in WooCommerce

The MobileCoin Payments Gateway should now appear during checkout as a payments option in the shop. Upon clicking the `Place order` button, the user will get directed to the MobileCoin payment processing website where they'll be able to pay for the order using MobileCoin, similar to other options such as PayPal.
