---
title: Billing
tagline: Freely monetize your apps
---

Hello, I am presenting you the extension for **_in-app purchases_**.

> It is based on [Anjlab's library](https://github.com/anjlab/android-inapp-billing-v3) (version 1.0.39)

----------


### INSTRUCTIONS

* Upload your apk to **Google Play** to alpha/beta/prod, and wait for your app to be published.

* You must **create and activate the product ID** in order to make purchases happen.

* For apps uploaded in alpha, use accounts used for testing only and get the link to app from **Opt-in URL** in _Manage Releases_ section of your apps.

* Get **License Key** from your app's _Services & API_ section.

* Get **Merchant ID** from _Payment Settings_ from Developer console.


----------

### ERROR CODES

Learn about the _error codes_ that you may receive using **ErrorOccurred** event block. I've made a list of errors so you know what the does that all mean. Meaning of each error code has been written against that error code.

| Error Code | Meaning |
| :---: | --- |
| 0 | BILLING_RESPONSE_RESULT_OK |
| 1 | BILLING_RESPONSE_RESULT_USER_CANCELED |
| 2 | BILLING_RESPONSE_RESULT_SERVICE_UNAVAILABLE |
| 3 | BILLING_RESPONSE_RESULT_BILLING_UNAVAILABLE |
| 4 | BILLING_RESPONSE_RESULT_ITEM_UNAVAILABLE |
| 5 | BILLING_RESPONSE_RESULT_DEVELOPER_ERROR |
| 6 | BILLING_RESPONSE_RESULT_ERROR |
| 7 | BILLING_RESPONSE_RESULT_ITEM_ALREADY_OWNED |
| 8 | BILLING_RESPONSE_RESULT_ITEM_NOT_OWNED |

Some more error codes:

| Error Code | Meaning |
| :---: | --- |
| 100 | BILLING_ERROR_FAILED_LOAD_PURCHASES |
| 101 | BILLING_ERROR_FAILED_TO_INITIALIZE_PURCHASE |
| 102 | BILLING_ERROR_INVALID_SIGNATURE |
| 103 | BILLING_ERROR_LOST_CONTEXT |
| 104 | BILLING_ERROR_INVALID_MERCHANT_ID |
| 105 | BILLING_ERROR_INVALID_DEVELOPER_PAYLOAD |
| 110 | BILLING_ERROR_OTHER_ERROR |
| 111 | BILLING_ERROR_CONSUME_FAILED |
| 112 | BILLING_ERROR_SKUDETAILS_FAILED |
| 113 | BILLING_ERROR_BIND_PLAY_STORE_FAILED |

_Found at https://goo.gl/q2QnR5_

----------

### Demo

Test this extension using this [app](https://play.google.com/apps/testing/com.thunkable.android.pavitragolchha.Billing).
