# STAC API Extensions

- [STAC API Extensions](#stac-api-extensions)
  - [List of STAC API Extensions](#list-of-stac-api-extensions)
    - [Alphabetical list](#alphabetical-list)

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

Below you can also find a list of extensions grouped by [maturity](#grouped-by-maturity).

### Alphabetical list

| Title | Field Name Prefix | Scope | [Maturity](https://github.com/radiantearth/stac-api-spec/tree/master/extensions#extension-maturity) | Version | Description |
| ----- | ----------------- | ----- | ----------------------------------------------------------------------------------------------- | ------- | ----------- |
| [aggregation](https://github.com/stac-api-extensions/aggregation) | *Unknown* | *Unknown* | Proposal | 0.2.0 | Aggregation Extension to provide aggregated data over a search, rather than individual Item results |
| [children](https://github.com/stac-api-extensions/children) | *Unknown* | *Unknown* | *Unknown* | 1.0.0-rc.2 | Children Extension |
| [collection-search](https://github.com/stac-api-extensions/collection-search) | *Unknown* | *Unknown* | *WIP* | **Unreleased** | WIP - Collection Search for STAC APIs |
| [context](https://github.com/stac-api-extensions/context) | *Unknown* | *Unknown* | Candidate | 1.0.0-rc.2 | Context Extension |
| [fields](https://github.com/stac-api-extensions/fields) | *Unknown* | *Unknown* | Candidate | 1.0.0-rc.2 | The Fields Extensions describes a mechanism to include or exclude certain fields from a response. |
| [filter](https://github.com/stac-api-extensions/filter) | *Unknown* | *Unknown* | Pilot | 1.0.0-rc.2 | Filter Extension |
| [language](https://github.com/stac-api-extensions/language) | *Unknown* | *Unknown* | *WIP* | **Unreleased** | Definitions and recommendations around making multi-lingual STAC APIs available |
| [query](https://github.com/stac-api-extensions/query) | *Unknown* | *Unknown* | Candidate | 1.0.0-rc.2 | Query Extension |
| [sort](https://github.com/stac-api-extensions/sort) | *Unknown* | *Unknown* | Candidate | 1.0.0-rc.2 | Sort Extension |
| [transaction](https://github.com/stac-api-extensions/transaction) | *Unknown* | *Unknown* | Candidate | 1.0.0-rc.2 | Transaction Extension |
| [version](https://github.com/stac-api-extensions/version) | *Unknown* | *Unknown* | *WIP* | **Unreleased** | Item and Collection Version Extension |

* **Last updated:** Jan 27 2023, 16:47 
* **Count:** 11

### Grouped by maturity


#### Stable


#### Candidate

* [context](https://github.com/stac-api-extensions/context)

* [fields](https://github.com/stac-api-extensions/fields)

* [query](https://github.com/stac-api-extensions/query)

* [sort](https://github.com/stac-api-extensions/sort)

* [transaction](https://github.com/stac-api-extensions/transaction)


#### Pilot

* [filter](https://github.com/stac-api-extensions/filter)


#### Proposal

* [aggregation](https://github.com/stac-api-extensions/aggregation)


#### WIP

* [collection-search](https://github.com/stac-api-extensions/collection-search)

* [language](https://github.com/stac-api-extensions/language)

* [version](https://github.com/stac-api-extensions/version)


#### Deprecated



You can add external/community extensions to the list above by editing the [config file](https://github.com/stac-api-extensions/stac-api-extensions.github.io/edit/main/python/config.py)
and creating a Pull Request for the change. All extensions hosted in the stac-api-extensions organization will be added automatically each night.