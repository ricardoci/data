# Class: BlockFrostIPFS

## Table of contents

### Constructors

- [constructor](../wiki/BlockFrostIPFS#constructor)

### Properties

- [add](../wiki/BlockFrostIPFS#add)
- [apiUrl](../wiki/BlockFrostIPFS#apiurl)
- [axiosInstance](../wiki/BlockFrostIPFS#axiosinstance)
- [gateway](../wiki/BlockFrostIPFS#gateway)
- [list](../wiki/BlockFrostIPFS#list)
- [listByPath](../wiki/BlockFrostIPFS#listbypath)
- [options](../wiki/BlockFrostIPFS#options)
- [pin](../wiki/BlockFrostIPFS#pin)
- [pinRemove](../wiki/BlockFrostIPFS#pinremove)
- [projectId](../wiki/BlockFrostIPFS#projectid)
- [userAgent](../wiki/BlockFrostIPFS#useragent)

## Constructors

### constructor

• **new BlockFrostIPFS**(`options?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `options?` | `Options` |

#### Defined in

[BlockFrostIPFS.ts:25](https://github.com/blockfrost/blockfrost-js/blob/ced2dac/src/BlockFrostIPFS.ts#L25)

## Properties

### add

• **add**: (`readStream`: `ReadStream`) => `Promise`<`AddResponse`\>

#### Type declaration

▸ (`readStream`): `Promise`<`AddResponse`\>

add - Add a file or directory to ipfs

##### Parameters

| Name | Type |
| :------ | :------ |
| `readStream` | `ReadStream` |

##### Returns

`Promise`<`AddResponse`\>

information about added ipfs object

#### Defined in

[BlockFrostIPFS.ts:45](https://github.com/blockfrost/blockfrost-js/blob/ced2dac/src/BlockFrostIPFS.ts#L45)

___

### apiUrl

• **apiUrl**: `string`

#### Defined in

[BlockFrostIPFS.ts:19](https://github.com/blockfrost/blockfrost-js/blob/ced2dac/src/BlockFrostIPFS.ts#L19)

___

### axiosInstance

• **axiosInstance**: `AxiosInstance`

#### Defined in

[BlockFrostIPFS.ts:23](https://github.com/blockfrost/blockfrost-js/blob/ced2dac/src/BlockFrostIPFS.ts#L23)

___

### gateway

• **gateway**: (`path`: `string`) => `Promise`<`unknown`\>

#### Type declaration

▸ (`path`): `Promise`<`unknown`\>

gateway - Relay to an ipfs gateway

##### Parameters

| Name | Type |
| :------ | :------ |
| `path` | `string` |

##### Returns

`Promise`<`unknown`\>

the object content

#### Defined in

[BlockFrostIPFS.ts:53](https://github.com/blockfrost/blockfrost-js/blob/ced2dac/src/BlockFrostIPFS.ts#L53)

___

### list

• **list**: (`pagination?`: `PaginationOptions`) => `Promise`<`ListResponse`\>

#### Type declaration

▸ (`pagination?`): `Promise`<`ListResponse`\>

list - List objects pinned to local storage

##### Parameters

| Name | Type |
| :------ | :------ |
| `pagination?` | `PaginationOptions` |

##### Returns

`Promise`<`ListResponse`\>

list of pinned objects

#### Defined in

[BlockFrostIPFS.ts:77](https://github.com/blockfrost/blockfrost-js/blob/ced2dac/src/BlockFrostIPFS.ts#L77)

___

### listByPath

• **listByPath**: (`path`: `string`) => `Promise`<`ListResponse`\>

#### Type declaration

▸ (`path`): `Promise`<`ListResponse`\>

listByPath - List objects pinned to local storage

##### Parameters

| Name | Type |
| :------ | :------ |
| `path` | `string` |

##### Returns

`Promise`<`ListResponse`\>

list of pinned objects

#### Defined in

[BlockFrostIPFS.ts:69](https://github.com/blockfrost/blockfrost-js/blob/ced2dac/src/BlockFrostIPFS.ts#L69)

___

### options

• **options**: `ValidatedOptions`

#### Defined in

[BlockFrostIPFS.ts:22](https://github.com/blockfrost/blockfrost-js/blob/ced2dac/src/BlockFrostIPFS.ts#L22)

___

### pin

• **pin**: (`path`: `string`) => `Promise`<`PinResponse`\>

#### Type declaration

▸ (`path`): `Promise`<`PinResponse`\>

pin - Pin an object

##### Parameters

| Name | Type |
| :------ | :------ |
| `path` | `string` |

##### Returns

`Promise`<`PinResponse`\>

pinned object

#### Defined in

[BlockFrostIPFS.ts:61](https://github.com/blockfrost/blockfrost-js/blob/ced2dac/src/BlockFrostIPFS.ts#L61)

___

### pinRemove

• **pinRemove**: (`path`: `string`) => `Promise`<`string`\>

#### Type declaration

▸ (`path`): `Promise`<`string`\>

pinRemove - Remove pinned objects from local storage

##### Parameters

| Name | Type |
| :------ | :------ |
| `path` | `string` |

##### Returns

`Promise`<`string`\>

removed pinned object

#### Defined in

[BlockFrostIPFS.ts:85](https://github.com/blockfrost/blockfrost-js/blob/ced2dac/src/BlockFrostIPFS.ts#L85)

___

### projectId

• `Optional` **projectId**: `string`

#### Defined in

[BlockFrostIPFS.ts:20](https://github.com/blockfrost/blockfrost-js/blob/ced2dac/src/BlockFrostIPFS.ts#L20)

___

### userAgent

• `Optional` **userAgent**: `string`

#### Defined in

[BlockFrostIPFS.ts:21](https://github.com/blockfrost/blockfrost-js/blob/ced2dac/src/BlockFrostIPFS.ts#L21)
