[alchemy-sdk](../README.md) / [Exports](../modules.md) / Media

# Interface: Media

Represents the URI information for the NFT's media assets.

## Table of contents

### Properties

- [bytes](Media.md#bytes)
- [format](Media.md#format)
- [gateway](Media.md#gateway)
- [raw](Media.md#raw)
- [size](Media.md#size)
- [thumbnail](Media.md#thumbnail)

## Properties

### bytes

• `Optional` **bytes**: `number`

The size of the media asset in bytes.

#### Defined in

[src/types/types.ts:585](https://github.com/alchemyplatform/alchemy-sdk-js/blob/e05babb/src/types/types.ts#L585)

___

### format

• `Optional` **format**: `string`

The media format (ex: jpg, gif, png) of the [gateway](Media.md#gateway) and
[thumbnail](Media.md#thumbnail) assets.

#### Defined in

[src/types/types.ts:574](https://github.com/alchemyplatform/alchemy-sdk-js/blob/e05babb/src/types/types.ts#L574)

___

### gateway

• **gateway**: `string`

Public gateway URI for the raw URI. Generally offers better performance.

#### Defined in

[src/types/types.ts:565](https://github.com/alchemyplatform/alchemy-sdk-js/blob/e05babb/src/types/types.ts#L565)

___

### raw

• **raw**: `string`

URI for the location of the NFT's original metadata blob for media (ex: the
original IPFS link).

#### Defined in

[src/types/types.ts:562](https://github.com/alchemyplatform/alchemy-sdk-js/blob/e05babb/src/types/types.ts#L562)

___

### size

• `Optional` **size**: `number`

DEPRECATED - The size of the media asset in bytes

**`deprecated`** - Please use [bytes](Media.md#bytes) instead. This field will be removed
  in a subsequent release.

#### Defined in

[src/types/types.ts:582](https://github.com/alchemyplatform/alchemy-sdk-js/blob/e05babb/src/types/types.ts#L582)

___

### thumbnail

• `Optional` **thumbnail**: `string`

URL for a resized thumbnail of the NFT media asset.

#### Defined in

[src/types/types.ts:568](https://github.com/alchemyplatform/alchemy-sdk-js/blob/e05babb/src/types/types.ts#L568)
