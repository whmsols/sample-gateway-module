# sample-gateway-module
Gateway Module allow you to connect WHMSOLS with additional payment and credit card processors for processing and capturing payments
#### Summary
Payment Gateway modules allow you to integrate payment solutions with the WHMSOLS automation platform.

There are two types of gateway module:

* <b>Third Party Gateways</b> - These are payment solutions where checkout occurs on a remote website, usually hosted by the Third Party payment gateway themselves.

* <b>Merchant Gateways</b> - These are payment solutions where credit card details are collected - usually within the WHMSOLS application, though more and more often this will be done remotely, typically via an iframe, with a page hosted remotely by the payment gateway enabling tokenised storage.

The sample files here demonstrate how we suggest a Third Party Payment Gateway module for WHMSOLS be structured and implemented.

For more information, please refer to the documentation at: [Third Party Payment Gateways](https://whmsols.com/developers/guide/268-Gateways-Modules "Third Party Payment Gateways").

#### Recommended Module Content
The recommended structure of a third party gateway module is as follows.

 ``` modules/gateways/yourgatewayname.php ```
 
#### Minimum Requirements
For the latest WHMSOLS minimum system requirements, please refer to [View System Requirement](https://whmsols.com/documentation/document/2-System-Requirements "System Requirement")

We recommend your module follows the same minimum requirements wherever possible.

#### Useful Resources
* [Developer Resources](https://whmsols.com/developers "Developer Resources")
* [Hook Documentation](https://whmsols.com/developers/guide/174-Hooks "Hook Documentation")
* [API Documentation](https://whmsols.com/developers/guide/175-API "API Documentation")
