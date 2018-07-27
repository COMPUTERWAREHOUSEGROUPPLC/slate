---
title: API Reference

language_tabs: # must be one of https://git.io/vQNgJ
  - shell
  - ruby
  - python
  - javascript

toc_footers:
  - <a href='#'>Sign Up for a Developer Key</a>
  - <a href='https://github.com/lord/slate'>Documentation Powered by Slate</a>

includes:
  - errors

search: true
---

# Introduction

This document contains the Steps to be taken for an Agent to be on-boarded on the Vending Management System.

#Steps 
1. Fill the Agent Registration form providing the required details.
2. Ensure that the API Documentation and Agent Subscription List have been collected.
3. Submit the filled Agent Registration form.
4. An email containing the Client ID and Client Secret will be sent to the Contact email address specified in the Agent Registration form.




#Agent Subscription List
Vend Code | Network Provider | Recharge Type | sub code required    | Sub Codes | Description
-------------- | -------------- | -------------- | --------------   | -------------- | --------------
M301 | MTN | Airtime | No | - | -
M302| MTN| Data | YES| 50MB | ₦100 - 50MB (valid for 24hrs)
 | |  |  | 100MB| ₦200 - 100MB (valid for 24hrs)
 | | | | 150MB| ₦300 - 150MB (valid for 7 days)
 | | |  | 750MB| ₦500 - 750MB (valid for 7 days)
 | | | |  1GB | ₦1,000 - 1GB (valid for 30 days)
 | | | |  1.5GB | ₦1,200 - 1.5GB (valid for 30 days)
 | | | |  3.5GB | ₦2,000 - 3.5GB (valid for 30 days)
 | | | |  5GB | ₦3,500 - 5GB (valid for 30 days)
 | | | |  10GB | ₦5,000 - 10GB (valid for 30 days)
 | | | |  22GB | ₦10,000 - 22GB (valid for 30 days)
 G501| Globacom| Airtime| no| - |-
 G502| Globacom| Data|Yes |  10MB | ₦25 - 10MB (valid for 24hrs)
 | | | |  15MB | ₦50 - 15MB (valid for 24hrs)
 | | | |  35MB| ₦100 - 35MB (valid for 24hrs)
 | | | |  100MB | ₦200 - 100MB (valid for 5 days)
 | | | |  800MB | ₦500 - 800MB (valid for 10 days)
 | | | |  1.6GB | ₦1,000 - 1.6GB (valid for 30 days)
 | | | |  3.75GB | ₦2,000 - 3.75GB (valid for 30 days)
 | | | |  5GB | ₦2,500 - 5GB (valid for 30 days)
 | | | |  6GB | ₦3,000 - 6GB (valid for 30 days)
 | | | |  9.5GB| ₦4,000 - 9.5GB (valid for 30 days)
 | | | |  12GB | ₦5,000 - 12GB (valid for 30 days)
 | | | |  22GB | ₦8,000 - 22GB (valid for 30 days)
 | | | |  50GB | ₦10,000 - 50GB (valid for 30 days)
 | | | |  80GB | ₦15,000 - 80GB (valid for 30 days)
 | | | |  100GB | ₦18,000 - 100GB (valid for 30 days)
 | | | |  120GB | ₦20,000 - 120GB (valid for 30 days)
 A201| Airtel| Airtime| No|  - | -
 A202| Airtel| Data| Yes|  10MB | ₦50 - This Data plan gives 10MB + 10% Bonus for N50 valid for 1 day
 | | | |  50MB | ₦100 - This Data plan gives 50MB + 10% Bonus for N100 valid for 1 day
 | | | |  200MB | ₦200 - This Data plan gives 200MB + 10% Bonus for N200 valid for 3 days
| | | |  350MB | ₦300 - This Data plan gives 350MB + 10% Bonus for N300 valid for 7 days
| | | |  750MB | ₦500 - This Data plan gives 750MB + 10% Bonus for N500 valid for 14 days
| | | |  1.5GB | ₦1000 - This Data plan gives 1.5GB + 10% Bonus for N1,000 and access to Social Networks for FREE valid for 30 days
| | | |  3.5GB | ₦2000 - This Data plan gives 3.5GB + 10% Bonus for N2,000 and access to Social Networks for FREE valid for 30 days
| | | |  5GB | ₦2500 - This Data plan gives 5GB + 10% Bonus for N2,500 and access to Social Networks for FREE valid for 30 days
| | | |  7GB | ₦3500 - This Data plan gives 7GB + 10% Bonus for N3,500 and access to Social Networks for FREE valid for 30 days
| | | |  9GB | ₦4000 - This Data plan gives 9GB + 10% Bonus for N4,000 and access to Social Networks for FREE valid for 30 days
| | | |  10GB | ₦5000- This Data plan gives 10GB + 10% Bonus for N5,000 valid for 30 days
| | | |  16GB | ₦8000 - This Data plan gives you 16GB + 10% Bonus for N8,000 valid for 30 days
| | | |  22GB | ₦10,000 - This Data plan gives 22GB + 10% Bonus for N10,000 valid for 30 days
| | | |  30GB | ₦15,000 - This Data plan gives 30GB + 10% Bonus for N15,000 valid for 60 days
| | | |  50GB | ₦36000 - This Data plan gives you 50GB + 10% Bonus for N36,000 valid for 180 days
| | | |  100GB | ₦70,000 - This Data plan gives 100GB + 10% Bonus for N70,000 valid for 365 days
| | | |  200GB | ₦136,000 - This Data plan gives 200GB + 10% Bonus
N901| 9mobile| Airtime| No|  - | 
N902| 9mobile| Data | Yes|  150MB | ₦200 - 150MB (valid for 7days)
| | | |  1GB | ₦1000 - 1GB (valid for 30days)
| | | |  1.5GB | ₦1200 - 1.5GB (valid for 30days)
| | | |  2.5GB | ₦2000 - 2.5GB (valid for 30days)
| | | |  4GB | ₦3000- 4GB (valid for 30days)
| | | |  5.5GB | ₦4000 - 5.5GB (valid for 30days)
| | | |  11.5GB | ₦8000 - 11.5GB (valid for 30days)
| | | |  15GB | ₦10000 - 15GB (valid for 30days)
| | | |  27.5GB | ₦18,000 - 27.5GB (valid for 30days)
| | | |  30GB | ₦27,500 - 30GB (valid for 90days)
| | | |  60GB | ₦55,000- 60GB (valid for 180days)
| | | |  100GB | ₦84,992 - 100GB (valid for 100days)
| | | |  120GB | ₦110,000 - 120GB (valid for 365days)

 

> Sample payload for airtime 

```json
[
  { "transactionReference": "12221t8TOO095", "amountPaid": 10000, 
  "transactionHash": "37a469501fb9376133b95def4f340bea39278baf571797a202042a1e59b921ee15b386a29a67f8752a7acb2aaf069b411b85ffa848f7f83b6eb442d80e6a0a78", 
  "customerUserId": "08030075922", 
  "transactionDate": "08/02/2018 05:00:09", "vendingCode": "M301" }
]
```

> Sample payload for Data

```json
[
  { "transactionReference": "12221t8TOO096", "amountPaid": 10000, 
  "transactionHash": "37a469501fb9376133b95def4f340bea39278baf571797a202042a1e59b921ee15b386a29a67f8752a7acb2aaf069b411b85ffa848f7f83b6eb442d80e6a0a79", 
  "customerUserId": "08030075922", 
  "transactionDate": "08/02/2018 05:00:19", "vendingCode": "M302" "subCode":"22GB"
  }
]
```
#Oauth2 Token API

Description: This is where authorized agents request for access token to make use of the CWG vending API.

### HTTP Request
Method : POST
Security : Basic Authentication (Client id and client secret will provided)

### URL Parameters 
https://41.78.157.169:8084/api/auth/oauth2/token

### Resource Information

|
-------------- | -------------- 
Response formats | JSON
Request formats | JSON
Requires Authentication? | Yes
Rate Limited? | Yes

### Parameters
Name | Required/optional | Description | Default value | Example
-------------- | -------------- | -------------- | -------------- | --------------
clientId | Required | Username|  | BnpS_FXkc5mTTVoY9Ze4VIoH7b80z57RY78RQ
clientSecret | Required | Password| | BnpK_4bmZIutPzHaJqLbc6pMqJL9Iikl4RoMH

### Sample Request


    POST /api/auth/uaa/api/oauth2/token HTTP/1.1 Host: 192.168.16.190:8084 Content-Type: multipart/form-data; boundary=----WebKitFormBoundary7MA4YWxkTrZu0gW Authorization: Basic Qm5wU19NTENOekpHNks4d0hub0poTlNtZVgxeGZmNXZqeDVudTpCbnBLX1gzVk1uZm8wRkhIV3R6T00xbHFuMmQxdEZFR1p5UWli ------WebKitFormBoundary7MA4YWxkTrZu0gW Content-Disposition: form-data; name="grant_type" grant_type=client_credentials ------WebKitFormBoundary7MA4YWxkTrZu0gW--


> Sample Response

```json
[
  { "transactionReference": "12221t8TOO096", "amountPaid": 10000, 
  "transactionHash": "37a469501fb9376133b95def4f340bea39278baf571797a202042a1e59b921ee15b386a29a67f8752a7acb2aaf069b411b85ffa848f7f83b6eb442d80e6a0a79", 
  "customerUserId": "08030075922", 
  "transactionDate": "08/02/2018 05:00:19", "vendingCode": "M302" "subCode":"22GB"
  }
]
```

# View Agent Subscription List Api
### HTTP Request
Description: This is where authorized agents get all subscribed services.
Method: GET.
Security: Bearer Token.

### URL Parameters
https://41.78.157.169:8084/api/platform/vend/query/subscription

|
-------------- | -------------- 
Response formats | JSON
Request formats | JSON
Requires Authentication? | Yes
Rate Limited? | Yes

### Sample Request
GET /api/router/vend/query/subscription HTTP/1.1 Host: 192.168.16.190:8084 Authorization: Bearer c7a13918-f56c-4b7f-a4c1-4ed28cbc949

> Sample Response

```json
[
  { "statusCode": 200, 
  "requestSuccessful": true, 
  "executionTime": 0, 
  "apiErrors": { 
    "errorCount": 0, 
    "apiErrorList": [] 
    }, 
    "apiWarnings": { 
      "warningCount": 0, 
      "apiWarningList": [] 
      }, "requestedCommand": "/vend/query/subscription", "responseEntity": { 
        "headers": {}, 
        "body": { 
          "serviceCount": 6, 
          "subscribedServices": [ { 
            "name": "Mtn Etop up", 
            "vendCode": "MTN_A", 
            "usesPreset": false, 
            "presetAmountList": [], 
            "presetCount": 0 },

            { "name": null, 
            "vendCode": "MTN_D", 
            "usesPreset": true, 
            "presetAmountList": [ 
              { 
                "subCode": "10GB", 
                "description": "10Gb MTN",
                 "amount": 1000 } ], 
                 "presetCount": 1 }, 
                 { "name": null, 
                 "vendCode": "NIN_A", 
                 "usesPreset": false, "presetAmountList": [], 
                 "presetCount": 0 }, 
                 { 
                   "name": "Glo Edata", 
                   "vendCode": "GLO_D", 
                   "usesPreset": false, "presetAmountList": [], "presetCount": 0 
                   }, 
                   { "name": null, "vendCode": "GLO_A", "usesPreset": false, "presetAmountList": [], "presetCount": 0 }, 
                   { "name": null, 
                   "vendCode": "NIN_D", 
                   "usesPreset": false, "presetAmountList": [], "presetCount": 0 }
                   ] 
                   }, 
                   "statusCode": "OK", "statusCodeValue": 200 
                   } 
                   }

]
