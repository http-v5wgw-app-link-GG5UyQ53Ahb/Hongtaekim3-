# Hongtaekim3-
curl -v -X POST https://api-m.sandbox.paypal.com/v2/checkout/orders \ -H "Content-Type: application/json" \ -H "Authorization: Bearer Access-Token" \ -d '{   "intent": "CAPTURE",   "purchase_units": [     {       "amount": {         "currency_code": "USD",         "value": "100.00"       }     }   ] }'
