# Extension User Guide

Find installation and configuration instructions here: [www.classyllama.com/documentation/extensions/avatax-magento-2-module](http://www.classyllama.com/documentation/extensions/avatax-magento-2-module).

# About Avalara's AvaTax

Agile, successful companies focus on their core business and outsource complex, administrative functions – such as payroll and sales tax management – to the experts. Avalara can address your sales tax challenges with AvaTax. It’s the fastest, easiest, most accurate and affordable way to calculate sales tax; manage exemption certificates; file returns; and remit payments across multiple tax regions. Our tax decision engine determines rates based on 100,000+ taxability rules in 11,000+ taxing jurisdictions and instantly applies them to each transaction within your Magento shopping cart. 

# Automated Tests

This extension contains integration tests to verify the extension's functionality. These tests should only need to be run by developers maintaining this extension. Instructions for running tests can be found [here](https://github.com/classyllama/ClassyLlama_AvaTax/blob/master/Tests/README.md).

# Magento Version Support

Support for Magento 2.2.x has not yet been officially tested, but is available via the `develop` GitHub branch using:
````
composer require classyllama/module-avatax:dev-develop
````
Please report any issues related to [Magento 2.2.x compatibility](https://github.com/classyllama/ClassyLlama_AvaTax/issues/85) in the corresponding [issue page](https://github.com/classyllama/ClassyLlama_AvaTax/issues/85). 

As of version 0.3.0 of this extension, this extension supported Magento 2.1.x (Community and Enterprise). Support for Magento 2.0.x was dropped as of version 0.3.0. See [this page](https://github.com/classyllama/ClassyLlama_AvaTax/releases) for a list of all releases.

As of version 1.0.0 of this extension, this extension supports [Magento Enterprise's split database mode](http://devdocs.magento.com/guides/v2.1/config-guide/multi-master/multi-master.html). Reference issue [#54](https://github.com/classyllama/ClassyLlama_AvaTax/issues/54) for additional notes and details.

# License

This project is licensed under the Open Software License 3.0 (OSL-3.0). See included LICENSE file for full text of OSL-3.0
