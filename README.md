Note:

If you are utilizing a mobile app, we advise you to explore our mobile SDKs. Please note that API integration is exclusively supported for web apps. By opting for SDK integration, you can enhance the payment experience for your customers, minimizing unnecessary steps in the process.

To avoid transaction blocking in production, please keep a check on the below points:

If you are using a personalized Chrome tab within their Android app, hindering URL retrieval. Please use SDK integration to resolve this issue.
If you are launching PayPage in a new window/tab, resulting in the absence of a referrer, then either redirect or employ an iFrame for PayPage is essential.
If you have implemented a no-referrer-policy then it leads to blank merchant URLs captured at our end. Please refrain from using it on the checkout page.
