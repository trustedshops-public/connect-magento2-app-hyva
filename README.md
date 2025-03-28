# Trustedshop integration for Hyvä

This module adds Trustedshops integration to Hyvä themes.

# Installation

1. Copy the contents of `src/` to `app/code/Trustedshops/HyvaEasyIntegration`. You need to create the path first. Make sure that `app/code/Trustedshops/HyvaEasyIntegration/registration.php` exists.
2. Run `bin/magento module:enable Trustedshops_HyvaEasyIntegration`.
3. Empty your cache: `bin/magento cache:flush`.
4. Run `bin/magento setup:static-content:deploy`.
