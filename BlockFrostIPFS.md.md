
### constructor

• **new BlockFrostIPFS**(`options?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `options?` | `Options` |

#### Defined in

[src/BlockFrostIPFS.ts:25](https://github.com/blockfrost/blockfrost-js/blob/9b3f200/src/BlockFrostIPFS.ts#L25)

## Properties

### add

• **add**: (`path`: `string`) => `Promise`<`AddResponse`\>

#### Type declaration

▸ (`path`): `Promise`<`AddResponse`\>

add - Add a file or directory to ipfs

##### Parameters

| Name | Type |
| :------ | :------ |
| `path` | `string` |

##### Returns

`Promise`<`AddResponse`\>

information about added ipfs object

#### Defined in

[src/BlockFrostIPFS.ts:45](https://github.com/blockfrost/blockfrost-js/blob/9b3f200/src/BlockFrostIPFS.ts#L45)

___

### apiUrl

• **apiUrl**: `string`

#### Defined in

[src/BlockFrostIPFS.ts:19](https://github.com/blockfrost/blockfrost-js/blob/9b3f200/src/BlockFrostIPFS.ts#L19)

___

### axiosInstance

• **axiosInstance**: `AxiosInstance`

#### Defined in

[src/BlockFrostIPFS.ts:23](https://github.com/blockfrost/blockfrost-js/blob/9b3f200/src/BlockFrostIPFS.ts#L23)

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

[src/BlockFrostIPFS.ts:53](https://github.com/blockfrost/blockfrost-js/blob/9b3f200/src/BlockFrostIPFS.ts#L53)

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

[src/BlockFrostIPFS.ts:77](https://github.com/blockfrost/blockfrost-js/blob/9b3f200/src/BlockFrostIPFS.ts#L77)

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

[src/BlockFrostIPFS.ts:69](https://github.com/blockfrost/blockfrost-js/blob/9b3f200/src/BlockFrostIPFS.ts#L69)

___

### options

• **options**: `ValidatedOptions`

#### Defined in

[src/BlockFrostIPFS.ts:22](https://github.com/blockfrost/blockfrost-js/blob/9b3f200/src/BlockFrostIPFS.ts#L22)

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

[src/BlockFrostIPFS.ts:61](https://github.com/blockfrost/blockfrost-js/blob/9b3f200/src/BlockFrostIPFS.ts#L61)

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

[src/BlockFrostIPFS.ts:85](https://github.com/blockfrost/blockfrost-js/blob/9b3f200/src/BlockFrostIPFS.ts#L85)

___

### projectId

• `Optional` **projectId**: `string`

#### Defined in

[src/BlockFrostIPFS.ts:20](https://github.com/blockfrost/blockfrost-js/blob/9b3f200/src/BlockFrostIPFS.ts#L20)

___

### userAgent

• `Optional` **userAgent**: `string`

#### Defined in

[src/BlockFrostIPFS.ts:21](https://github.com/blockfrost/blockfrost-js/blob/9b3f200/src/BlockFrostIPFS.ts#L21)
