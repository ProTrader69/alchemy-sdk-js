[exploring-pioneer](../README.md) / [Exports](../modules.md) / OwnedBaseNftsResponse

# Interface: OwnedBaseNftsResponse

The response object for the {@link (getNfts:1)} and
{@link (getNftsPaginated:1)} functions. The object contains the NFTs without
metadata owned by the provided address, along with pagination information and
the total count.

## Table of contents

### Properties

- [ownedNfts](OwnedBaseNftsResponse.md#ownednfts)
- [pageKey](OwnedBaseNftsResponse.md#pagekey)
- [totalCount](OwnedBaseNftsResponse.md#totalcount)

## Properties

### ownedNfts

• `Readonly` **ownedNfts**: [`OwnedBaseNft`](OwnedBaseNft.md)[]

The NFTs owned by the provided address.

#### Defined in

[types/types.ts:261](https://github.com/alchemyplatform/exploring-pioneer/blob/7c86334/src/types/types.ts#L261)

___

### pageKey

• `Optional` `Readonly` **pageKey**: `string`

Pagination token that can be passed into another request to fetch the next
NFTs. If there is no page key, then there are no more NFTs to fetch.

#### Defined in

[types/types.ts:267](https://github.com/alchemyplatform/exploring-pioneer/blob/7c86334/src/types/types.ts#L267)

___

### totalCount

• `Readonly` **totalCount**: `number`

The total count of NFTs owned by the provided address.

#### Defined in

[types/types.ts:270](https://github.com/alchemyplatform/exploring-pioneer/blob/7c86334/src/types/types.ts#L270)