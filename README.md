This extension integrates a Magento 2 based webstore with the **[PayFort](https://www.payfort.com)** payment service.  
Payfort [is available](https://www.payfort.com/payfort-faqs/#section30) for merchants in the United Arab Emirates, Egypt, Saudi Arabia, Jordan, Lebanon and Qatar.

## How to install
```
composer require mage2pro/payfort-mageplaza:*
bin/magento setup:upgrade
rm -rf pub/static/* && bin/magento setup:static-content:deploy en_US <additional locales, e.g.: ar_AE ar_EG ar_SA ar_JO ar_LB ar_QA>
rm -rf var/di var/generation generated/code && bin/magento setup:di:compile
```
If you have some problems while executing these commands, then check the [detailed instruction](https://mage2.pro/t/263).
