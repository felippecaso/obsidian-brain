## Metadata
* URL: [https://roundup.getdbt.com/p/coalesce-data-contracts-the-semantic](https://roundup.getdbt.com/p/coalesce-data-contracts-the-semantic)
* Author: Tristan Handy
* Publisher: The Analytics Engineering Roundup
* Published Date: 2022-08-28
* Tags: #data

## Highlights
* The big unlock for me was that his recommendation is to never sync data directly from a database. Instead, build an API for any data that you want to sync into your data warehouse and extract all data via this API.
* this layer of abstraction provides software engineers building the product with a compatibility layer—a
* Ideally, business should own the definitions. For some reason we don’t think this is likely. Defining metrics is a very precise endeavour. The issue is when we mix technical complexity with business complexity. Semantic layers should allow us to focus on business complexity only and they should enable business people to define their own metrics, their own concepts. (Call me naive, go ahead.)
* The best answer to “who should own X thing?” is typically “the person who is most incentivized to want it to be correct.”
