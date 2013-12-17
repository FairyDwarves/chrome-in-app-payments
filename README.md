chrome-in-app-payments
======================

Chrome In App Payments is a JavaScript library that supports the use of In-App Payments in Chrome Apps and Extensions.

* [Overview](#overview)
  * [Features](#features)
* [Prerequisites](#prerequisites)
* [API Reference](#api-reference)
* [Examples](#examples)

## Overview

The [In App Payments API](http://developer.chrome.com/apps/google_wallet.html) lets you easily managed and sell digital goods within your *Chrome App* or *Chrome Extension*.  
  

### Features

The In-App Payment Library (`buy.js`) library:

* communicates with the [Google Wallet](https://support.google.com/chrome_webstore/answer/1053354) servers and handles all the required checkout details, so you do not need to process any financial transactions
* communicates with the Chrome Web Store to provide access to your managed digital goods
* manages digital licenses for products purchased by users, making it easy to verify purchases
* provides support for both Closure-based and traditional JavaScript projects

## Prerequisites

Before you use the In-App Payment Library, you should:

* review the [In-App Payment documentation](http://developer.chrome.com/apps/google_wallet.html) for Chrome Apps and Extensions
* set up a [Google Wallet Merchant account](https://wallet.google.com/inapp/merchant/signup.html)
* add the appropriate In-App Products to your Chrome App or Extension's Chrome Web Store listing page


## API Reference

**Namespace**

* [`google.payments.inapp`]() - How you access the APIs. Start here.

**APIs**

* [`google.payments.inapp.getSkuDetails`]() - Returns a list of products available for sale in your App or Extension.
* [`google.payments.inapp.getPurchases`]() - Returns a list of products purchased by the current user.
* [`google.payments.inapp.buy`]() - Kicks off the purchase flow for an item.


## Examples

For an illustration of how to use In App Payments in your Chrome App, see the [example applications]().