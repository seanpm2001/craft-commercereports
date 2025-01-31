# Commerce Reports

Commerce Reports is a plugin intended to provide better insights and statistics into your sales within Craft Commerce.

## Overview

There are three core pages that provide insights into sales: orders, customers and items sold. From the items sold page, you can navigate to a page that shows.

From each of the pages, you can filter the data in various ways.

### Orders

![Orders](docs/assets/orders.png)

The "Orders" page gives you an overview of all orders made for a given date range, providing an overview of the average value and unique items in an order, along with the total number of orders.

### Customers

![Customers](docs/assets/customers.png)

The "Customers" page gives you an overview of the customers that have made orders for a given date range, including a list of the top locations orders are made from.

### Items Sold

![Items Sold](docs/assets/items-sold.png)

The "Items Sold" page gives you an overview of the items sold in orders for a given date range. It supports filtering by a given product type in addition to custom Verbb Events.

### Products

![Products](docs/assets/products.png)

The "Products" page gives you an overview of the orders made for a given product.

## Setup

### Requirements

This plugin requires Craft 4, Craft Commerce 4 and at least PHP 8 to install.

### Installation

This plugin supports installation from Composer.

#### Installing via Craft Plugin Store

This plugin is not currently available on the Craft plugin store yet.

#### Installing via Composer

You can add the package to your project using Composer and the command line using the below as a reference.

Open your terminal of choice and go to your Craft project:

`cd /path/to/project`

Tell Composer to require the plugin and then Craft to install it:

`composer require fostercommerce/variant-manager && php craft plugin/install variant-manager`

Note that if you would like to install a specific branch you can do the following (note the "dev-" prefix):

`composer require fostercommerce/variant-manager "dev-{branch-name}"`

If you would like to install a specific version you can do the following:

`composer require fostercommerce/variant-manager "1.0.1"`

#### Installing the Beta via Composer

To install the beta specifically using Composer, you would need to set the minimum stability for the package to beta which can be done like so:

`composer require fostercommerce/variant-manager "^1.0.1@beta"`

## Help

### I have an idea for a new feature. Where do I share it?

We're open to new ideas and encourage you to please submit your idea to [GitHub Issues](https://github.com/FosterCommerce/craft-commercereports/issues).

### I found a bug or have a concern. Where do I share it?

Like ideas, please submit the bug/concern to [GitHub Issues](https://github.com/FosterCommerce/craft-commercereports/issues).

We'd ask that you be as detailed as possible and always include the versions of Craft, Craft Commerce and our plugin.

If we don't respond in a reasonable amount of time (72 Hours), please send us an email at support@fostercommerce.com.
