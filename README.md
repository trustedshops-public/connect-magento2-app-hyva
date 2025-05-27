# Trusted Shops Magento 2 Hyvä App Connector

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](COPYING)
[![Release](https://img.shields.io/github/v/release/trustedshops-public/connect-magento2-app-hyva-off)](https://github.com/trustedshops-public/connect-magento2-app-hyva-off/releases)

This module integrates Trusted Shops functionality into Magento 2 storefronts using the Hyvä theme. It adds custom layout XML and CSS to enhance category and product pages with Trusted Shops content.

## Features

- Additional product view and category view templates customized for Trusted Shops widgets
- Easy integration with Hyvä frontend
- Trusted Shops specific styles and layout XML updates

## Installation

Use Composer to install the module in your Magento 2 project:

```bash
composer require trustedshops/connect-magento2-app-hyva
```

Then enable the module and run setup upgrades:

```bash
bin/magento module:enable TrustedShops_ConnectHyva
bin/magento setup:upgrade
```

## Usage

This module adjusts your Hyvä theme to include Trusted Shops layouts and CSS. Make sure your project uses Hyvä and that you are registered with Trusted Shops.

## License

This project is licensed under the MIT License - see the [COPYING](COPYING) file for details.
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
