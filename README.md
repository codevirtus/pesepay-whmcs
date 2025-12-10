
![Pesepay logo](https://github.com/gitnyasha/pesepay-whmcs-module/assets/45620987/95f132ef-a4cf-40c6-a347-08498c2eb5b5)

# Pesepay Payment Gateway Module for WHMCS

### Summary

Pesepay is a payment gateway module designed for WHMCS, a popular web hosting billing and automation platform. The module allows customers to make payments through various payment methods, including Ecocash and Zimswitch for local transactions, as well as Mastercard and Visa for international payments. With a focus on security and seamless integration, Pesepay ensures a reliable and user-friendly payment experience for both merchants and customers.

### Installation

To install the Pesepay gateway module for WHMCS, follow these steps:

1. Download the Pesepay module files from the GitHub repository: [GitHub Repository](https://github.com/codevirtus/pesepay-whmcs)
2. Upload the entire contents of the pesepay-whmcs-module directory to the modules/gateways/ directory of your WHMCS installation take **note** that the callback folder will aleady be there so you just have to copy the file inside the pesepay-whmcs-module/modules/gateways/callback directory into your whmcs modules/gateways/callback directory.
3. Your directory structure after the installation should look like this:

```bash
modules/gateways/pesepay
modules/gateways/callback/pesepay.php
modules/gateways/pesepay.php
```

Once the files are in their respective locations, you can proceed with the configuration of the Pesepay payment gateway within the WHMCS admin panel.
