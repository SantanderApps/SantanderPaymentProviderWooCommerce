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
### Install through Wordpress Control Panel
* Download the module from the WordPress Plugin Directory using the Plugin manager inside your WordPress control panel.

### Manual installation
* Download the zip file from the GitHub repo and store it on you local computer.
* Go to WordPress control panel > Plugins > Add new and click on "Upload Plugin".
* Browse for the zip file and select it.
* Upload it and the configure it (see section "Configure the module").

## Configure the module
* Go to WordPress control panel > Plugins.
* Click on "Activate" for the plugin "Santander Consumer Bank - Woocommerce Payment Gateway".
* Click on "Activate" and wait for the page to reload.
* When the page have reloaded, click on "Settings".
* Configure the module to suit your needs (see "Configuration parameters" below).
* Save changes by clicking the button "Save changes".
* Start using the gateway!

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