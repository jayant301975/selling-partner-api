---
name: Request for help
about: For requesting help with SP API usage
title: ''
labels: ''
assignees: ''

---

## Problem description:
I am trying to view address of the Order done but it is retuning Application do not have access to some or all requested resource
## Error:
 Exception when calling OrdersV0Api->getOrderAddress: [400] { "errors": [ { "code": "InvalidInput", "message": "Application do not have access to some or all requested resource", "details": "" } ] }
```
# Your error here. PLEASE make sure to redact secrets from your error log!
```

## Code
$apiInstance = new SellingPartnerApi\Api\OrdersV0Api($config); 
$order_id = '402-3081095-7840333';

try { $result = $apiInstance->getOrderAddress($order_id); print_r($result); } 
catch (Exception $e) { echo 'Exception when calling OrdersV0Api->getOrderAddress: ', $e->getMessage(), PHP_EOL; }
```php
// Your code here...PLEASE make sure to redact secrets from your code!
```

## Seller Central SP API config page screenshot

*your screenshot here*
