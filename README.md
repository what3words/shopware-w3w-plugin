# What3words Shopware Plugin

[![License: MIT](https://img.shields.io/badge/license-MIT-blue)](./LICENSE.md)

The Shopware 6 plugin adds a what3words address field to your store’s checkout page allowing your customers to easily enter and validate a what3words address when placing an order. what3words addresses can then be converted to GPS coordinates, which can then be passed onto delivery drivers allowing deliveries to arrive at the right place and on time, giving a more reliable delivery experience for your customers.

*Shopware 6 Minimum Supported Version:* 6.0 or higher

*Note:*

This extension has been developed by [Benny Poensgen](https://github.com/vanWittlaer/VanWittlaerWhatThreeWords), if you encounter any problems or have any feedback at all, kindly submit any feedback to our Support team at [support@what3words.com](mailto:support@what3words.com).

## Installation

The Shopware 6 plugin can be installed by downloading the latest plugin zip file from [https://github.com/what3words/shopware-w3w-plugin/releases] (https://github.com/what3words/shopware-w3w-plugin/releases) and uploading this file to your `custom/plugins` folder of your shopware project.

Then go to `Extensions > My extensions`

Click on the `Install` link to install the extension on your storefront.

The next step is to activate the extension by clicking on the toggle next to the extension. It will display the extension at the top of your extensions.

Once activated you will be able to configure the app by adding the what3words API key to your Sales Channels.

Click on the `...` (3 dots) on the right side of the extension and then click on `Configure`.

You will be able to access to the settings page of the extension where you can enter your what3words API key.

Then click the `Save` button.

If you don’t already have a what3words API key, you can `Get your API key` [here](https://accounts.what3words.com/login).

A new field should now be appearing on your checkout under the shipping address. When a what3words address is captured in this field, it will be saved alongside your order details and will be visible on order and costumer billing and shipping addresses as an additional costum field.

**Note:** You can install with composer run `composer require vanwittlaer/what3words --no-scripts`.

## Usage
The plugin is documentated [here](https://developer.what3words.com/tutorial/installing-the-what3words-shopware-plugin).

## License - MIT
Versions 1, Copyright (C)[@vanWittlaer](https://github.com/vanWittlaer/VanWittlaerWhatThreeWords)

## Contributors
This plugin has been developed by [@vanWittlaer](https://github.com/vanWittlaer). You can find the original version on this [Github page](https://github.com/vanWittlaer/VanWittlaerWhatThreeWords) 


