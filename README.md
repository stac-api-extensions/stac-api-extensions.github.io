# STAC API Extensions

- [STAC API Extensions](#stac-api-extensions)
  - [List of STAC API Extensions](#list-of-stac-api-extensions)
    - [Alphabetical list](#alphabetical-list)
    - [Grouped by maturity](#grouped-by-maturity)
  - [Adding a new extension](#adding-a-new-extension)

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

This is meant to be the definitive list of STAC Extensions, but not all of them may be part of this GitHub organization.

An asterisk (*) indicates a community extension that is hosted externally.
As such is not part of the stac-api-extensions GitHub organization and may not follow the normal procedure or classification for STAC extensions, e.g. regarding the maturity.

### Alphabetical list

### Grouped by maturity

## Adding a new extension

The general idea on how to [extend STAC](https://github.com/radiantearth/stac-spec/blob/master/extensions/README.md#extending-stac)
and [propose new extensions](https://github.com/radiantearth/stac-spec/blob/master/extensions/README.md#proposing-new-extensions) is explained on [the page about extensions in the stac-spec repository](https://github.com/radiantearth/stac-spec/blob/master/extensions/README.md).

You can add external/community extensions to the list above by editing the [config file](https://github.com/stac-api-extensions/stac-api-extensions.github.io/edit/main/python/config.py)
and creating a Pull Request for the change. All extensions hosted in the stac-api-extensions organization will be added automatically each night.
