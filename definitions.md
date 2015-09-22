## Definitions
### Auction
|Name|Description|Required|Schema|Default|
|----|----|----|----|----|
|foreignId||true|ForeignId||
|url||true|Url||
|title||true|Text array||
|source||true|Source||
|scrapeId||true|ScrapeId||
|location||false|Location||


### AuctionLot
|Name|Description|Required|Schema|Default|
|----|----|----|----|----|
|auctionId||false|string||
|endDate||true|string (date-time)||
|currentBid||false|Price||
|startBid||false|Price||
|minimumBid||false|Price||
|source||true|Source||
|scrapeId||true|ScrapeId||
|foreignId||true|ForeignId||
|price||false|Price||
|location||false|Location||
|url||true|Url||
|manufacturer||false|Manufacturer||
|yearOfManufacture||false|YearOfManufacture||
|description||true|Text array||
|title||true|Text array||
|model||false|Model||
|imageUrls||false|Url array||
|attributes||false|Attribute array||
|category||false|Category||
|sellerContact||false|SellerContact||


### FixedPriceLot
|Name|Description|Required|Schema|Default|
|----|----|----|----|----|
|source||true|Source||
|scrapeId||true|ScrapeId||
|foreignId||true|ForeignId||
|price||false|Price||
|location||false|Location||
|url||true|Url||
|manufacturer||false|Manufacturer||
|yearOfManufacture||false|YearOfManufacture||
|description||true|Text array||
|title||true|Text array||
|model||false|Model||
|imageUrls||false|Url array||
|attributes||false|Attribute array||
|category||false|Category||
|sellerContact||false|SellerContact||


### ForeignId

TODO

### Source

name of the scraped source. Trademachines provides a source for each scraper.

### ScrapeId

UUID, is unique for each scrape run.

### Manufacturer
### Model

the model of a machine

### YearOfManufacture
### Price
|Name|Description|Required|Schema|Default|
|----|----|----|----|----|
|currency||true|string||
|amount||true|number||


### Location
|Name|Description|Required|Schema|Default|
|----|----|----|----|----|
|raw||true|string||


### Url
### Language

ISO-639-1 language code (alpha-2)

### Attribute
|Name|Description|Required|Schema|Default|
|----|----|----|----|----|
|language||true|Language||
|key||true|string||
|value||true|string||


### Category
|Name|Description|Required|Schema|Default|
|----|----|----|----|----|
|foreignId||false|string||
|label||true|string||


### Text
|Name|Description|Required|Schema|Default|
|----|----|----|----|----|
|language||true|Language||
|value||true|string||


### SellerContact
|Name|Description|Required|Schema|Default|
|----|----|----|----|----|
|foreignId||true|string||
|raw||true|string||
|url||false|Url||


