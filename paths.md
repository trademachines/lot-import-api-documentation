## Paths
### POST /auction
#### Parameters
|Type|Name|Description|Required|Schema|Default|
|----|----|----|----|----|----|
|BodyParameter|auction||false|Auction||


#### Responses
|HTTP Code|Description|Schema|
|----|----|----|
|200|Ok|No Content|
|400|Validation Error|No Content|


### POST /lot/auction
#### Parameters
|Type|Name|Description|Required|Schema|Default|
|----|----|----|----|----|----|
|BodyParameter|lot|scraped auction lot|true|AuctionLot||


#### Responses
|HTTP Code|Description|Schema|
|----|----|----|
|200|Ok|No Content|
|400|Validation Error|No Content|


### POST /lot/fixed-price
#### Parameters
|Type|Name|Description|Required|Schema|Default|
|----|----|----|----|----|----|
|BodyParameter|lot|scraped fixed price lot|true|FixedPriceLot||


#### Responses
|HTTP Code|Description|Schema|
|----|----|----|
|200|Ok|No Content|
|400|Validation Error|No Content|


