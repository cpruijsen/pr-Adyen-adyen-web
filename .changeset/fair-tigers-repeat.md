---
'@adyen/adyen-web': patch
---

Fixed: Apple Pay and Google Pay no longer call `onPaymentFailed` when `beforeSubmit` is rejected or when handling an already-authorized payment response throws, and `onPaymentFailed` is now always called with a `resultCode`
