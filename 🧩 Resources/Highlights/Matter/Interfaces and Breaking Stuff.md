## Metadata
* URL: [https://roundup.getdbt.com/p/interfaces-and-breaking-stuff](https://roundup.getdbt.com/p/interfaces-and-breaking-stuff)
* Published Date: 2022-07-17
* Author: [[Tristan Handy]]

## Highlights
* understated—knowing that something is broken when you are writing the code is exactly when you need that information!
* Today, we’re catching far too many error states in production.
* Breakages almost-always happen at the edges between systems—between ingestion and transformation, between transformation and BI/analytics, etc.
* Allow multiple versions of a model to be consumed at the same time so that downstream models can implement an upgrade path. Publishers of an API give consumers of that API a fairly long period for them to upgrade to the next version—sometimes years!