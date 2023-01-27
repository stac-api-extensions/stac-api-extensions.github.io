# STAC API Extensions

bump

- [STAC API Extensions](#stac-api-extensions)
  - [List of STAC API Extensions](#list-of-stac-api-extensions)
    - [Alphabetical](#alphabetical)
    - [Grouped by maturity](#grouped-by-maturity)
      - [Stable](#stable)
      - [Candidate](#candidate)
      - [Pilot](#pilot)
      - [Proposal](#proposal)
      - [WIP](#wip)
      - [Deprecated](#deprecated)

The [stac-api-extensions](https://github.com/stac-api-extensions/) GitHub organization is a home for extensions to the
[SpatioTemporal Asset Catalog API foundation specifications](https://github.com/radiantearth/stac-api-spec).

To learn about STAC API and Extensions, start with the [extensions](https://github.com/radiantearth/stac-api-spec/tree/main/extensions.md)
section of the STAC API specifications. It explains how extensions work, lists all the known extensions, and has
instructions for how to go about [creating new extensions](https://github.com/radiantearth/stac-api-spec/blob/main/extensions.md#creating-new-extensions)'.

The [stac-api-extensions](https://github.com/stac-api-extensions/) GitHub organization is a home for many of the leading 'community extensions',
providing a neutral home for collaboration. Many of these used to be in the core
[stac-api-spec repository](https://github.com/radiantearth/stac-api-spec), but were removed for 1.0.0 so they could evolve at their
own pace, instead of having to follow the core STAC release cycle.

## List of STAC API Extensions

This is meant to be the definitive list of STAC API Extensions, but not all of them may be part of this GitHub organization.

An asterisk (*) indicates a community extension that is hosted externally.
As such is not part of the stac-api-extensions GitHub organization and may not follow the normal procedure or classification for STAC extensions, e.g. regarding the maturity.

### Alphabetical

| Title | Scope | [Maturity](https://github.com/radiantearth/stac-api-spec/tree/master/extensions#extension-maturity) | Version | Description |
| ----- | ----------------- | ----- | ----------------------------------------------------------------------------------------------- | ------- | ----------- |
| [Aggregation](https://github.com/stac-api-extensions/aggregation) | STAC API - Core | Proposal | 0.2.0 | Aggregation Extension to provide aggregated data over a search, rather than individual Item results |
| [Children](https://github.com/stac-api-extensions/children) | STAC API - Core | Proposal | 1.0.0-rc.2 | Children Extension |
| [Context](https://github.com/stac-api-extensions/context) | STAC API - Features, STAC API - Item Search | Deprecated | 1.0.0-rc.2 | Context Extension |
| [Items and Collections API Version](https://github.com/stac-api-extensions/version) | STAC API - Features | *WIP* | **Unreleased** | Item and Collection Version Extension |
| [Transaction](https://github.com/stac-api-extensions/transaction) | STAC API - Features | Candidate | 1.0.0-rc.2 | Transaction Extension |
| [collection-search](https://github.com/stac-api-extensions/collection-search) | *Unknown* | *WIP* | **Unreleased** | WIP - Collection Search for STAC APIs |
| [fields](https://github.com/stac-api-extensions/fields) | *Unknown* | *Unknown* | 1.0.0-rc.2 | The Fields Extensions describes a mechanism to include or exclude certain fields from a response. |
| [filter](https://github.com/stac-api-extensions/filter) | *Unknown* | *Unknown* | 1.0.0-rc.2 | Filter Extension |
| [language](https://github.com/stac-api-extensions/language) | *Unknown* | *WIP* | **Unreleased** | Definitions and recommendations around making multi-lingual STAC APIs available |
| [query](https://github.com/stac-api-extensions/query) | *Unknown* | *Unknown* | 1.0.0-rc.2 | Query Extension |
| [sort](https://github.com/stac-api-extensions/sort) | *Unknown* | *Unknown* | 1.0.0-rc.2 | Sort Extension |
| [stac-context-collections](https://github.com/cedadev/stac-context-collections)* | *Unknown* | *WIP* | **Unreleased** | None |
| [stac-freetext-search](https://github.com/cedadev/stac-freetext-search)* | *Unknown* | *Unknown* | 0.1.0 | None |

### Grouped by maturity


#### Stable


#### Candidate

* [Transaction](https://github.com/stac-api-extensions/transaction)


#### Pilot


#### Proposal

* [Aggregation](https://github.com/stac-api-extensions/aggregation)

* [Children](https://github.com/stac-api-extensions/children)


#### WIP

* [Items and Collections API Version](https://github.com/stac-api-extensions/version)

* [collection-search](https://github.com/stac-api-extensions/collection-search)

* [language](https://github.com/stac-api-extensions/language)

* [stac-context-collections](https://github.com/cedadev/stac-context-collections)*


#### Deprecated

* [Context](https://github.com/stac-api-extensions/context)



* **Last updated:** Jan 27 2023, 19:56 
* **Count:** 13

You can add external/community extensions to the list above by editing the [config file](https://github.com/stac-api-extensions/stac-api-extensions.github.io/edit/main/python/config.py)
and creating a Pull Request for the change. All extensions hosted in the stac-api-extensions organization will be added automatically each night.