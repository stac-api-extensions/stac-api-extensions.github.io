# STAC API Extensions

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
instructions for how to go about [creating new extensions](https://github.com/radiantearth/stac-api-spec/blob/main/extensions.md#creating-new-extensions).

The [stac-api-extensions](https://github.com/stac-api-extensions/) GitHub organization is a home for many of the leading "community extensions",
providing a neutral home for collaboration. Many of these used to be in the
[stac-api-spec repository](https://github.com/radiantearth/stac-api-spec), but were removed so they could evolve at their
own pace, instead of having to follow the core STAC API release cycle.

## List of STAC API Extensions

This is meant to be the definitive list of STAC API Extensions, but not all of them may be part of this GitHub organization.

An asterisk (*) indicates a community extension that is hosted externally.
As such is not part of the stac-api-extensions GitHub organization and may not follow the normal procedure or classification for STAC API extensions, e.g. regarding the maturity.

### Alphabetical

| Title | Scope | [Maturity](https://github.com/radiantearth/stac-api-spec/tree/master/extensions#extension-maturity) | Version | Description |
| ----- | ----- | --------------------------------------------------------------------------------------------------- | ------- | ----------- |
| [Aggregation](https://github.com/stac-api-extensions/aggregation) | STAC API - Core | Proposal | 0.3.0 | Aggregation Extension to provide aggregated data over a search, rather than individual Item results |
| [Browseable](https://github.com/stac-api-extensions/browseable) | STAC API - Core | Proposal | 1.0.0-rc.3 | Browseable advertises all Items in a STAC API Catalog can be reached by traversing child and item links. |
| [Children](https://github.com/stac-api-extensions/children) | STAC API - Core | Proposal | 1.0.0-rc.2 | The purpose of this extension is to add an endpoint that presents a single resource from which clients can retrieve the immediate children of a Catalog. |
| [Collection Search](https://github.com/stac-api-extensions/collection-search) | STAC API - Core | *WIP* | **Unreleased** | WIP - Collection Search for STAC APIs |
| [Context](https://github.com/stac-api-extensions/context) | STAC API - Features, STAC API - Item Search | Deprecated | 1.0.0-rc.2 | Context Extension |
| [Context Collections](https://github.com/cedadev/stac-context-collections)* | STAC - Core | *WIP* | **Unreleased** | This defines a new parameter, collections inside the context response which is a summary of all the collections which are part of the current result context. |
| [Fields](https://github.com/stac-api-extensions/fields) | STAC API - Features, STAC API - Item Search | Candidate | 1.0.0-rc.3 | The Fields Extensions describes a mechanism to include or exclude certain fields from a response. |
| [Filter](https://github.com/stac-api-extensions/filter) | STAC API - Features, STAC API - Item Search | Pilot | 1.0.0-rc.2 | The Filter extension provides an expressive mechanism for searching based on Item attributes. |
| [Free-Text Search](https://github.com/cedadev/stac-freetext-search)* | STAC API - Core | Proposal | 0.1.0 | This defines a new parameter, q that allows the user to perform free-text queries against the item properties. |
| [Language (I18N)](https://github.com/stac-api-extensions/language) | STAC API - Core | Proposal | 1.0.0-rc.2 | Definitions and recommendations around making multi-lingual STAC APIs available |
| [Query](https://github.com/stac-api-extensions/query) | STAC API - Features, STAC API - Item Search | Candidate | 1.0.0-rc.2 | The Query Extension adds a query parameter that allows additional filtering based on the properties of Item objects. |
| [Sort](https://github.com/stac-api-extensions/sort) | STAC API - Features, STAC API - Item Search | Candidate | 1.0.0-rc.2 | The Sort Extension that allows the user to define the fields by which to sort results.  |
| [Transaction](https://github.com/stac-api-extensions/transaction) | STAC API - Features | Candidate | 1.0.0-rc.2 |  The Transaction Extension supports the creation, editing, and deleting of items through POST, PUT, PATCH, and DELETE requests. |
| [Version](https://github.com/stac-api-extensions/version) | STAC API - Features | Deprecated | **Unreleased** | Item and Collection Version Extension |

- **Last updated:** Jul 22 2023, 00:48 
- **Count:** 14

### Grouped by maturity


#### Stable


#### Candidate

- [Fields](https://github.com/stac-api-extensions/fields)

- [Query](https://github.com/stac-api-extensions/query)

- [Sort](https://github.com/stac-api-extensions/sort)

- [Transaction](https://github.com/stac-api-extensions/transaction)


#### Pilot

- [Filter](https://github.com/stac-api-extensions/filter)


#### Proposal

- [Aggregation](https://github.com/stac-api-extensions/aggregation)

- [Browseable](https://github.com/stac-api-extensions/browseable)

- [Children](https://github.com/stac-api-extensions/children)

- [Free-Text Search](https://github.com/cedadev/stac-freetext-search)*

- [Language (I18N)](https://github.com/stac-api-extensions/language)


#### WIP

- [Collection Search](https://github.com/stac-api-extensions/collection-search)

- [Context Collections](https://github.com/cedadev/stac-context-collections)*


#### Deprecated

- [Context](https://github.com/stac-api-extensions/context)

- [Version](https://github.com/stac-api-extensions/version)



You can add external/community extensions to the list above by editing the [config file](https://github.com/stac-api-extensions/stac-api-extensions.github.io/edit/main/python/config.py)
and creating a Pull Request for the change. All extensions hosted in the stac-api-extensions organization will be added automatically each night.