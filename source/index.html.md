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
 | | | |  3GB | ₦2,000 - 3.5GB (valid for 30 days)
 | | | |  3GB | ₦2,000 - 3.5GB (valid for 30 days)
 | | | |  3GB | ₦2,000 - 3.5GB (valid for 30 days)
 | | | |  3GB | ₦2,000 - 3.5GB (valid for 30 days)
 | | | |  3GB | ₦2,000 - 3.5GB (valid for 30 days)
 | | | |  3GB | ₦2,000 - 3.5GB (valid for 30 days)
 | | | |  3GB | ₦2,000 - 3.5GB (valid for 30 days)
 | | | |  3GB | ₦2,000 - 3.5GB (valid for 30 days)
 | | | |  3GB | ₦2,000 - 3.5GB (valid for 30 days)
 | | | |  3GB | ₦2,000 - 3.5GB (valid for 30 days)

 # Sample payload for airtime 
```json
{ "transactionReference": "12221t8TOO095", 
"amountPaid": 10000, 
"transactionHash": "37a469501fb9376133b95def4f340bea39278baf571797a202042a1e59b921ee15b386a29a67f8752a7acb2aaf069b411b85ffa848f7f83b6eb442d80e6a0a78", 
"customerUserId": "08030075922", 
"transactionDate": "08/02/2018 05:00:09", 
"vendingCode": "M301" }
```


# Authentication



> Make sure to replace `meowmeowmeow` with your API key.

Kittn uses API keys to allow access to the API. You can register a new Kittn API key at our [developer portal](http://example.com/developers).

Kittn expects for the API key to be included in all API requests to the server in a header that looks like the following:

`Authorization: meowmeowmeow`

<aside class="notice">
You must replace <code>meowmeowmeow</code> with your personal API key.
</aside>

# Kittens

## Get All Kittens
```javascript
const kittn = require('kittn');

let api = kittn.authorize('meowmeowmeow');
let kittens = api.kittens.get();
```

> The above command returns JSON structured like this:

```json
[
  {
    "id": 1,
    "name": "Fluffums",
    "breed": "calico",
    "fluffiness": 6,
    "cuteness": 7
  },
  {
    "id": 2,
    "name": "Max",
    "breed": "unknown",
    "fluffiness": 5,
    "cuteness": 10
  }
]
```

This endpoint retrieves all kittens.

### HTTP Request

`GET http://example.com/api/kittens`

### Query Parameters

Parameter | Default | Description
--------- | ------- | -----------
include_cats | false | If set to true, the result will also include cats.
available | true | If set to false, the result will include kittens that have already been adopted.

<aside class="success">
Remember — a happy kitten is an authenticated kitten!
</aside>

## Get a Specific Kitten

```ruby
require 'kittn'

api = Kittn::APIClient.authorize!('meowmeowmeow')
api.kittens.get(2)
```

```python
import kittn

api = kittn.authorize('meowmeowmeow')
api.kittens.get(2)
```

```shell
curl "http://example.com/api/kittens/2"
  -H "Authorization: meowmeowmeow"
```

```javascript
const kittn = require('kittn');

let api = kittn.authorize('meowmeowmeow');
let max = api.kittens.get(2);
```

> The above command returns JSON structured like this:

```json
{
  "id": 2,
  "name": "Max",
  "breed": "unknown",
  "fluffiness": 5,
  "cuteness": 10
}
```

This endpoint retrieves a specific kitten.

<aside class="warning">Inside HTML code blocks like this one, you can't use Markdown, so use <code>&lt;code&gt;</code> blocks to denote code.</aside>

### HTTP Request

`GET http://example.com/kittens/<ID>`

### URL Parameters

Parameter | Description
--------- | -----------
ID | The ID of the kitten to retrieve

## Delete a Specific Kitten

```ruby
require 'kittn'

api = Kittn::APIClient.authorize!('meowmeowmeow')
api.kittens.delete(2)
```

```python
import kittn

api = kittn.authorize('meowmeowmeow')
api.kittens.delete(2)
```

```shell
curl "http://example.com/api/kittens/2"
  -X DELETE
  -H "Authorization: meowmeowmeow"
```

```javascript
const kittn = require('kittn');

let api = kittn.authorize('meowmeowmeow');
let max = api.kittens.delete(2);
```

> The above command returns JSON structured like this:

```json
{
  "id": 2,
  "deleted" : ":("
}
```

This endpoint deletes a specific kitten.

### HTTP Request

`DELETE http://example.com/kittens/<ID>`

### URL Parameters

Parameter | Description
--------- | -----------
ID | The ID of the kitten to delete

