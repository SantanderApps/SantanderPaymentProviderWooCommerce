# Install the module
## Before installation
* Make sure that you have an working WooCommerce installation.

## Requirements
The following requirements must be fulfilled for this module to work.
* PHP version 5.3.0 or greater.
* PHP SoapClient ([http://php.net/manual/en/class.soapclient.php](http://php.net/manual/en/class.soapclient.php))
* Openssl
* cURL lib must be enabled for PHP ([http://php.net/manual/en/book.curl.php](http://php.net/manual/en/book.curl.php))
* libxml [http://php.net/manual/en/book.libxml.php](http://php.net/manual/en/book.libxml.php)

## Installation
* Download the module from the WordPress Plugin Directory using the Plugin manager inside your WordPress control panel.

## Configuration parameters
* **Enable/Disable:** whether to enable or disable the payment module.
* **Store ID:** type the store ID that have been provided for you by Santander. This field will be automatically filled out when the module environment is set to "sandbox (test environment)".
* **Username:** type the username that have been provided for you by Santander. This field will be automatically filled out when the module environment is set to "sandbox (test environment)".
* **Password:** type the password that have been provided for you by Santander. This field will be automatically filled out when the module environment is set to "sandbox (test environment)".
* **Merchant ID:** (optional in sandbox/test environment) type the merchant ID that have been provided for you by your payment service provider. See list below for supported payment service providers.
* **Set Module Environment:** select which environment you want to run the module. Sandbox (test environment) is used for evaluating the module.

## Supported payment service providers
Santander supports the following payment service providers:
* Dibs
* DebiTech o Nets
* Payex
* Samport