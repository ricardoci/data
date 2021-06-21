## Table of contents

### Constructors

- [constructor](../wiki/Class-BlockFrostAPI#constructor)

### Properties

- [accounts](../wiki/Class-BlockFrostAPI#accounts)
- [accountsAddresses](../wiki/Class-BlockFrostAPI#accountsaddresses)
- [accountsDelegations](../wiki/Class-BlockFrostAPI#accountsdelegations)
- [accountsHistory](../wiki/Class-BlockFrostAPI#accountshistory)
- [accountsRegistrations](../wiki/Class-BlockFrostAPI#accountsregistrations)
- [accountsRewards](../wiki/Class-BlockFrostAPI#accountsrewards)
- [addresses](../wiki/Class-BlockFrostAPI#addresses)
- [addressesTotal](../wiki/Class-BlockFrostAPI#addressestotal)
- [addressesTransactions](../wiki/Class-BlockFrostAPI#addressestransactions)
- [addressesTransactionsAll](../wiki/Class-BlockFrostAPI#addressestransactionsall)
- [addressesTxs](../wiki/Class-BlockFrostAPI#addressestxs)
- [addressesTxsAll](../wiki/Class-BlockFrostAPI#addressestxsall)
- [addressesUtxos](../wiki/Class-BlockFrostAPI#addressesutxos)
- [addressesUtxosAll](../wiki/Class-BlockFrostAPI#addressesutxosall)
- [apiUrl](../wiki/Class-BlockFrostAPI#apiurl)
- [assets](../wiki/Class-BlockFrostAPI#assets)
- [assetsAddresses](../wiki/Class-BlockFrostAPI#assetsaddresses)
- [assetsById](../wiki/Class-BlockFrostAPI#assetsbyid)
- [assetsHistory](../wiki/Class-BlockFrostAPI#assetshistory)
- [assetsPolicyById](../wiki/Class-BlockFrostAPI#assetspolicybyid)
- [assetsTransactions](../wiki/Class-BlockFrostAPI#assetstransactions)
- [assetsTxs](../wiki/Class-BlockFrostAPI#assetstxs)
- [blocks](../wiki/Class-BlockFrostAPI#blocks)
- [blocksLatest](../wiki/Class-BlockFrostAPI#blockslatest)
- [blocksNext](../wiki/Class-BlockFrostAPI#blocksnext)
- [blocksPrevious](../wiki/Class-BlockFrostAPI#blocksprevious)
- [blocksTxs](../wiki/Class-BlockFrostAPI#blockstxs)
- [blocksTxsAll](../wiki/Class-BlockFrostAPI#blockstxsall)
- [epochs](../wiki/Class-BlockFrostAPI#epochs)
- [epochsBlocks](../wiki/Class-BlockFrostAPI#epochsblocks)
- [epochsBlocksByPoolId](../wiki/Class-BlockFrostAPI#epochsblocksbypoolid)
- [epochsLatest](../wiki/Class-BlockFrostAPI#epochslatest)
- [epochsNext](../wiki/Class-BlockFrostAPI#epochsnext)
- [epochsParameters](../wiki/Class-BlockFrostAPI#epochsparameters)
- [epochsPrevious](../wiki/Class-BlockFrostAPI#epochsprevious)
- [epochsStakes](../wiki/Class-BlockFrostAPI#epochsstakes)
- [epochsStakesByPoolId](../wiki/Class-BlockFrostAPI#epochsstakesbypoolid)
- [health](../wiki/Class-BlockFrostAPI#health)
- [healthClock](../wiki/Class-BlockFrostAPI#healthclock)
- [ledger](../wiki/Class-BlockFrostAPI#ledger)
- [metadataTxsLabel](../wiki/Class-BlockFrostAPI#metadatatxslabel)
- [metadataTxsLabelCbor](../wiki/Class-BlockFrostAPI#metadatatxslabelcbor)
- [metadataTxsLabels](../wiki/Class-BlockFrostAPI#metadatatxslabels)
- [metrics](../wiki/Class-BlockFrostAPI#metrics)
- [metricsEndpoints](../wiki/Class-BlockFrostAPI#metricsendpoints)
- [poolMetadata](../wiki/Class-BlockFrostAPI#poolmetadata)
- [pools](../wiki/Class-BlockFrostAPI#pools)
- [poolsById](../wiki/Class-BlockFrostAPI#poolsbyid)
- [poolsByIdBlocks](../wiki/Class-BlockFrostAPI#poolsbyidblocks)
- [poolsByIdDelegators](../wiki/Class-BlockFrostAPI#poolsbyiddelegators)
- [poolsByIdHistory](../wiki/Class-BlockFrostAPI#poolsbyidhistory)
- [poolsByIdRelays](../wiki/Class-BlockFrostAPI#poolsbyidrelays)
- [poolsByIdUpdates](../wiki/Class-BlockFrostAPI#poolsbyidupdates)
- [poolsRetired](../wiki/Class-BlockFrostAPI#poolsretired)
- [poolsRetiring](../wiki/Class-BlockFrostAPI#poolsretiring)
- [projectId](../wiki/Class-BlockFrostAPI#projectid)
- [root](../wiki/Class-BlockFrostAPI#root)
- [txSubmit](../wiki/Class-BlockFrostAPI#txsubmit)
- [txs](../wiki/Class-BlockFrostAPI#txs)
- [txsDelegations](../wiki/Class-BlockFrostAPI#txsdelegations)
- [txsMetadata](../wiki/Class-BlockFrostAPI#txsmetadata)
- [txsMetadataCbor](../wiki/Class-BlockFrostAPI#txsmetadatacbor)
- [txsPoolRetires](../wiki/Class-BlockFrostAPI#txspoolretires)
- [txsPoolUpdates](../wiki/Class-BlockFrostAPI#txspoolupdates)
- [txsStakes](../wiki/Class-BlockFrostAPI#txsstakes)
- [txsUtxos](../wiki/Class-BlockFrostAPI#txsutxos)
- [txsWithdrawals](../wiki/Class-BlockFrostAPI#txswithdrawals)
- [userAgent](../wiki/Class-BlockFrostAPI#useragent)

## Constructors

### constructor

• **new BlockFrostAPI**(`options?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `options?` | `Options` |

#### Defined in

[index.ts:108](https://github.com/blockfrost/blockfrost-js/blob/74c5e4a/src/index.ts#L108)

## Properties

### accounts

• **accounts**: (`stakeAddress`: `string`) => `Promise`<`components`[``"schemas"``][``"account_content"``]\>

#### Type declaration

▸ (`stakeAddress`): `Promise`<`components`[``"schemas"``][``"account_content"``]\>

accounts - Obtain information about a specific stake account.

##### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `stakeAddress` | `string` | Bech32 stake address |

##### Returns

`Promise`<`components`[``"schemas"``][``"account_content"``]\>

Information about a specific stake account.

#### Defined in

[index.ts:135](https://github.com/blockfrost/blockfrost-js/blob/74c5e4a/src/index.ts#L135)

___

### accountsAddresses

• **accountsAddresses**: (`stakeAddress`: `string`, `page`: `number`, `count`: `number`, `order`: ``"asc"`` \| ``"desc"``) => `Promise`<`components`[``"schemas"``][``"account_addresses_content"``]\>

#### Type declaration

▸ (`stakeAddress`, `page`, `count?`, `order?`): `Promise`<`components`[``"schemas"``][``"account_addresses_content"``]\>

accountsAddresses - Obtain information about the addresses of a specific account.

##### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `stakeAddress` | `string` | Bech32 stake address |
| `page` | `number` | - |
| `count` | `number` | - |
| `order` | ``"asc"`` \| ``"desc"`` | - |

##### Returns

`Promise`<`components`[``"schemas"``][``"account_addresses_content"``]\>

Information about the addresses of a specific account.

#### Defined in

[index.ts:180](https://github.com/blockfrost/blockfrost-js/blob/74c5e4a/src/index.ts#L180)

___

### accountsDelegations

• **accountsDelegations**: (`stakeAddress`: `string`, `page`: `number`, `count`: `number`, `order`: ``"asc"`` \| ``"desc"``) => `Promise`<`components`[``"schemas"``][``"account_delegation_content"``]\>

#### Type declaration

▸ (`stakeAddress`, `page`, `count?`, `order?`): `Promise`<`components`[``"schemas"``][``"account_delegation_content"``]\>

accountsDelegations - Obtain information about the delegation of a specific account.

##### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `stakeAddress` | `string` | Bech32 stake address |
| `page` | `number` | - |
| `count` | `number` | - |
| `order` | ``"asc"`` \| ``"desc"`` | - |

##### Returns

`Promise`<`components`[``"schemas"``][``"account_delegation_content"``]\>

Information about the delegation of a specific account.

#### Defined in

[index.ts:144](https://github.com/blockfrost/blockfrost-js/blob/74c5e4a/src/index.ts#L144)

___

### accountsHistory

• **accountsHistory**: (`stakeAddress`: `string`, `page`: `number`, `count`: `number`, `order`: ``"asc"`` \| ``"desc"``) => `Promise`<`components`[``"schemas"``][``"account_history_content"``]\>

#### Type declaration

▸ (`stakeAddress`, `page`, `count?`, `order?`): `Promise`<`components`[``"schemas"``][``"account_history_content"``]\>

accountsHistory - Obtain information about the history of a specific account.

##### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `stakeAddress` | `string` | Bech32 stake address |
| `page` | `number` | - |
| `count` | `number` | - |
| `order` | ``"asc"`` \| ``"desc"`` | - |

##### Returns

`Promise`<`components`[``"schemas"``][``"account_history_content"``]\>

Information about the history of a specific account.

#### Defined in

[index.ts:171](https://github.com/blockfrost/blockfrost-js/blob/74c5e4a/src/index.ts#L171)

___

### accountsRegistrations

• **accountsRegistrations**: (`stakeAddress`: `string`, `page`: `number`, `count`: `number`, `order`: ``"asc"`` \| ``"desc"``) => `Promise`<`components`[``"schemas"``][``"account_registration_content"``]\>

#### Type declaration

▸ (`stakeAddress`, `page`, `count?`, `order?`): `Promise`<`components`[``"schemas"``][``"account_registration_content"``]\>

accountsRegistrations - Obtain information about the registrations and deregistrations of a specific account.

##### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `stakeAddress` | `string` | Bech32 stake address |
| `page` | `number` | - |
| `count` | `number` | - |
| `order` | ``"asc"`` \| ``"desc"`` | - |

##### Returns

`Promise`<`components`[``"schemas"``][``"account_registration_content"``]\>

Information about the registrations and deregistrations of a specific account.

#### Defined in

[index.ts:153](https://github.com/blockfrost/blockfrost-js/blob/74c5e4a/src/index.ts#L153)

___

### accountsRewards

• **accountsRewards**: (`stakeAddress`: `string`, `page`: `number`, `count`: `number`, `order`: ``"asc"`` \| ``"desc"``) => `Promise`<`components`[``"schemas"``][``"account_reward_content"``]\>

#### Type declaration

▸ (`stakeAddress`, `page`, `count?`, `order?`): `Promise`<`components`[``"schemas"``][``"account_reward_content"``]\>

accountsRewards - Obtain information about the history of a specific account.

##### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `stakeAddress` | `string` | Bech32 stake address |
| `page` | `number` | - |
| `count` | `number` | - |
| `order` | ``"asc"`` \| ``"desc"`` | - |

##### Returns

`Promise`<`components`[``"schemas"``][``"account_reward_content"``]\>

Information about the history of a specific account.

#### Defined in

[index.ts:162](https://github.com/blockfrost/blockfrost-js/blob/74c5e4a/src/index.ts#L162)

___

### addresses

• **addresses**: (`address`: `string`) => `Promise`<`components`[``"schemas"``][``"address_content"``]\>

#### Type declaration

▸ (`address`): `Promise`<`components`[``"schemas"``][``"address_content"``]\>

addresses

##### Parameters

| Name | Type |
| :------ | :------ |
| `address` | `string` |

##### Returns

`Promise`<`components`[``"schemas"``][``"address_content"``]\>

xxx

#### Defined in

[index.ts:251](https://github.com/blockfrost/blockfrost-js/blob/74c5e4a/src/index.ts#L251)

___

### addressesTotal

• **addressesTotal**: (`address`: `string`) => `Promise`<`components`[``"schemas"``][``"address_content_total"``]\>

#### Type declaration

▸ (`address`): `Promise`<`components`[``"schemas"``][``"address_content_total"``]\>

addressesTotal

##### Parameters

| Name | Type |
| :------ | :------ |
| `address` | `string` |

##### Returns

`Promise`<`components`[``"schemas"``][``"address_content_total"``]\>

xxx

#### Defined in

[index.ts:260](https://github.com/blockfrost/blockfrost-js/blob/74c5e4a/src/index.ts#L260)

___

### addressesTransactions

• **addressesTransactions**: (`address`: `string`, `page`: `number`, `count`: `number`, `order`: ``"asc"`` \| ``"desc"``, `from`: ``null``, `to`: ``null``) => `Promise`<`components`[``"schemas"``][``"address_transactions_content"``] \| []\>

#### Type declaration

▸ (`address`, `page`, `count?`, `order?`, `from?`, `to?`): `Promise`<`components`[``"schemas"``][``"address_transactions_content"``] \| []\>

addressesTransactions

##### Parameters

| Name | Type | Default value |
| :------ | :------ | :------ |
| `address` | `string` | `undefined` |
| `page` | `number` | `undefined` |
| `count` | `number` | `undefined` |
| `order` | ``"asc"`` \| ``"desc"`` | `undefined` |
| `from` | ``null`` | `undefined` |
| `to` | ``null`` | null |

##### Returns

`Promise`<`components`[``"schemas"``][``"address_transactions_content"``] \| []\>

xxx

#### Defined in

[index.ts:287](https://github.com/blockfrost/blockfrost-js/blob/74c5e4a/src/index.ts#L287)

___

### addressesTransactionsAll

• **addressesTransactionsAll**: (`address`: `string`, `order`: ``"asc"`` \| ``"desc"``, `batchSize`: `number`) => `Promise`<`components`[``"schemas"``][``"address_transactions_content"``] \| []\>

#### Type declaration

▸ (`address`, `order`, `batchSize?`): `Promise`<`components`[``"schemas"``][``"address_transactions_content"``] \| []\>

addressesTransactionsAll

##### Parameters

| Name | Type |
| :------ | :------ |
| `address` | `string` |
| `order` | ``"asc"`` \| ``"desc"`` |
| `batchSize` | `number` |

##### Returns

`Promise`<`components`[``"schemas"``][``"address_transactions_content"``] \| []\>

xxx

#### Defined in

[index.ts:296](https://github.com/blockfrost/blockfrost-js/blob/74c5e4a/src/index.ts#L296)

___

### addressesTxs

• **addressesTxs**: (`address`: `string`, `page`: `number`, `count`: `number`, `order`: ``"asc"`` \| ``"desc"``) => `Promise`<`components`[``"schemas"``][``"address_txs_content"``] \| []\>

#### Type declaration

▸ (`address`, `page`, `count?`, `order?`): `Promise`<`components`[``"schemas"``][``"address_txs_content"``] \| []\>

addressesTxs

##### Parameters

| Name | Type |
| :------ | :------ |
| `address` | `string` |
| `page` | `number` |
| `count` | `number` |
| `order` | ``"asc"`` \| ``"desc"`` |

##### Returns

`Promise`<`components`[``"schemas"``][``"address_txs_content"``] \| []\>

xxx

#### Defined in

[index.ts:269](https://github.com/blockfrost/blockfrost-js/blob/74c5e4a/src/index.ts#L269)

___

### addressesTxsAll

• **addressesTxsAll**: (`address`: `string`, `order`: ``"asc"`` \| ``"desc"``, `batchSize`: `number`) => `Promise`<`components`[``"schemas"``][``"address_txs_content"``] \| []\>

#### Type declaration

▸ (`address`, `order`, `batchSize?`): `Promise`<`components`[``"schemas"``][``"address_txs_content"``] \| []\>

addressesTxsAll

##### Parameters

| Name | Type |
| :------ | :------ |
| `address` | `string` |
| `order` | ``"asc"`` \| ``"desc"`` |
| `batchSize` | `number` |

##### Returns

`Promise`<`components`[``"schemas"``][``"address_txs_content"``] \| []\>

xxx

#### Defined in

[index.ts:278](https://github.com/blockfrost/blockfrost-js/blob/74c5e4a/src/index.ts#L278)

___

### addressesUtxos

• **addressesUtxos**: (`address`: `string`, `page`: `number`, `count`: `number`, `order`: ``"asc"`` \| ``"desc"``) => `Promise`<`components`[``"schemas"``][``"address_utxo_content"``]\>

#### Type declaration

▸ (`address`, `page`, `count?`, `order?`): `Promise`<`components`[``"schemas"``][``"address_utxo_content"``]\>

addressesUtxos

##### Parameters

| Name | Type |
| :------ | :------ |
| `address` | `string` |
| `page` | `number` |
| `count` | `number` |
| `order` | ``"asc"`` \| ``"desc"`` |

##### Returns

`Promise`<`components`[``"schemas"``][``"address_utxo_content"``]\>

xxx

#### Defined in

[index.ts:305](https://github.com/blockfrost/blockfrost-js/blob/74c5e4a/src/index.ts#L305)

___

### addressesUtxosAll

• **addressesUtxosAll**: (`address`: `string`, `order`: ``"asc"`` \| ``"desc"``, `batchSize`: `number`) => `Promise`<`components`[``"schemas"``][``"address_utxo_content"``]\>

#### Type declaration

▸ (`address`, `order`, `batchSize?`): `Promise`<`components`[``"schemas"``][``"address_utxo_content"``]\>

addressesUtxosAll

##### Parameters

| Name | Type |
| :------ | :------ |
| `address` | `string` |
| `order` | ``"asc"`` \| ``"desc"`` |
| `batchSize` | `number` |

##### Returns

`Promise`<`components`[``"schemas"``][``"address_utxo_content"``]\>

xxx

#### Defined in

[index.ts:314](https://github.com/blockfrost/blockfrost-js/blob/74c5e4a/src/index.ts#L314)

___

### apiUrl

• **apiUrl**: `string`

#### Defined in

[index.ts:106](https://github.com/blockfrost/blockfrost-js/blob/74c5e4a/src/index.ts#L106)

___

### assets

• **assets**: (`page`: `number`, `count`: `number`, `order`: ``"asc"`` \| ``"desc"``) => `Promise`<`components`[``"schemas"``][``"assets"``]\>

#### Type declaration

▸ (`page`, `count?`, `order?`): `Promise`<`components`[``"schemas"``][``"assets"``]\>

assets - List of assets.

##### Parameters

| Name | Type |
| :------ | :------ |
| `page` | `number` |
| `count` | `number` |
| `order` | ``"asc"`` \| ``"desc"`` |

##### Returns

`Promise`<`components`[``"schemas"``][``"assets"``]\>

List of assets.

#### Defined in

[index.ts:188](https://github.com/blockfrost/blockfrost-js/blob/74c5e4a/src/index.ts#L188)

___

### assetsAddresses

• **assetsAddresses**: (`asset`: `string`, `page`: `number`, `count`: `number`, `order`: ``"asc"`` \| ``"desc"``) => `Promise`<`components`[``"schemas"``][``"asset_addresses"``]\>

#### Type declaration

▸ (`asset`, `page`, `count?`, `order?`): `Promise`<`components`[``"schemas"``][``"asset_addresses"``]\>

assetsAddresses - List of a addresses containing a specific asset.

##### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `asset` | `string` | Concatenation of the policy_id and hex-encoded asset_name |
| `page` | `number` | - |
| `count` | `number` | - |
| `order` | ``"asc"`` \| ``"desc"`` | - |

##### Returns

`Promise`<`components`[``"schemas"``][``"asset_addresses"``]\>

List of a addresses containing a specific asset.

#### Defined in

[index.ts:233](https://github.com/blockfrost/blockfrost-js/blob/74c5e4a/src/index.ts#L233)

___

### assetsById

• **assetsById**: (`asset`: `string`) => `Promise`<`components`[``"schemas"``][``"asset"``]\>

#### Type declaration

▸ (`asset`): `Promise`<`components`[``"schemas"``][``"asset"``]\>

assetsById - Information about a specific asset.

##### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `asset` | `string` | Concatenation of the policy_id and hex-encoded asset_name |

##### Returns

`Promise`<`components`[``"schemas"``][``"asset"``]\>

Information about a specific asset.

#### Defined in

[index.ts:197](https://github.com/blockfrost/blockfrost-js/blob/74c5e4a/src/index.ts#L197)

___

### assetsHistory

• **assetsHistory**: (`asset`: `string`, `page`: `number`, `count`: `number`, `order`: ``"asc"`` \| ``"desc"``) => `Promise`<`components`[``"schemas"``][``"asset_history"``]\>

#### Type declaration

▸ (`asset`, `page`, `count?`, `order?`): `Promise`<`components`[``"schemas"``][``"asset_history"``]\>

assetsHistory - History of a specific asset.

##### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `asset` | `string` | Concatenation of the policy_id and hex-encoded asset_name |
| `page` | `number` | - |
| `count` | `number` | - |
| `order` | ``"asc"`` \| ``"desc"`` | - |

##### Returns

`Promise`<`components`[``"schemas"``][``"asset_history"``]\>

History of a specific asset.

#### Defined in

[index.ts:206](https://github.com/blockfrost/blockfrost-js/blob/74c5e4a/src/index.ts#L206)

___

### assetsPolicyById

• **assetsPolicyById**: (`policy`: `string`, `page`: `number`, `count`: `number`, `order`: ``"asc"`` \| ``"desc"``) => `Promise`<`components`[``"schemas"``][``"asset_addresses"``]\>

#### Type declaration

▸ (`policy`, `page`, `count?`, `order?`): `Promise`<`components`[``"schemas"``][``"asset_addresses"``]\>

assetsPolicyById - List of asset minted under a specific policy.

##### Parameters

| Name | Type |
| :------ | :------ |
| `policy` | `string` |
| `page` | `number` |
| `count` | `number` |
| `order` | ``"asc"`` \| ``"desc"`` |

##### Returns

`Promise`<`components`[``"schemas"``][``"asset_addresses"``]\>

List of asset minted under a specific policy.

#### Defined in

[index.ts:242](https://github.com/blockfrost/blockfrost-js/blob/74c5e4a/src/index.ts#L242)

___

### assetsTransactions

• **assetsTransactions**: (`asset`: `string`, `page`: `number`, `count`: `number`, `order`: ``"asc"`` \| ``"desc"``) => `Promise`<`components`[``"schemas"``][``"asset_transactions"``]\>

#### Type declaration

▸ (`asset`, `page`, `count?`, `order?`): `Promise`<`components`[``"schemas"``][``"asset_transactions"``]\>

assetsTransactions - List of a specific asset transactions.

##### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `asset` | `string` | Concatenation of the policy_id and hex-encoded asset_name |
| `page` | `number` | - |
| `count` | `number` | - |
| `order` | ``"asc"`` \| ``"desc"`` | - |

##### Returns

`Promise`<`components`[``"schemas"``][``"asset_transactions"``]\>

List of a specific asset transactions.

#### Defined in

[index.ts:224](https://github.com/blockfrost/blockfrost-js/blob/74c5e4a/src/index.ts#L224)

___

### assetsTxs

• **assetsTxs**: (`asset`: `string`, `page`: `number`, `count`: `number`, `order`: ``"asc"`` \| ``"desc"``) => `Promise`<`components`[``"schemas"``][``"asset_txs"``]\>

#### Type declaration

▸ (`asset`, `page`, `count?`, `order?`): `Promise`<`components`[``"schemas"``][``"asset_txs"``]\>

assetsTxs - List of a specific asset transactions.

##### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `asset` | `string` | Concatenation of the policy_id and hex-encoded asset_name |
| `page` | `number` | - |
| `count` | `number` | - |
| `order` | ``"asc"`` \| ``"desc"`` | - |

##### Returns

`Promise`<`components`[``"schemas"``][``"asset_txs"``]\>

List of a specific asset transactions.

#### Defined in

[index.ts:215](https://github.com/blockfrost/blockfrost-js/blob/74c5e4a/src/index.ts#L215)

___

### blocks

• **blocks**: (`hashOrNumber`: `HashOrNumber`) => `Promise`<`components`[``"schemas"``][``"block_content"``]\>

#### Type declaration

▸ (`hashOrNumber`): `Promise`<`components`[``"schemas"``][``"block_content"``]\>

addressesUtxos

##### Parameters

| Name | Type |
| :------ | :------ |
| `hashOrNumber` | `HashOrNumber` |

##### Returns

`Promise`<`components`[``"schemas"``][``"block_content"``]\>

xxx

#### Defined in

[index.ts:323](https://github.com/blockfrost/blockfrost-js/blob/74c5e4a/src/index.ts#L323)

___

### blocksLatest

• **blocksLatest**: () => `Promise`<`components`[``"schemas"``][``"block_content"``]\>

#### Type declaration

▸ (): `Promise`<`components`[``"schemas"``][``"block_content"``]\>

blocksLatest

##### Returns

`Promise`<`components`[``"schemas"``][``"block_content"``]\>

xxx

#### Defined in

[index.ts:331](https://github.com/blockfrost/blockfrost-js/blob/74c5e4a/src/index.ts#L331)

___

### blocksNext

• **blocksNext**: (`hashOrNumber`: `HashOrNumber`, `page`: `number`, `count`: `number`) => `Promise`<`components`[``"schemas"``][``"block_content_array"``]\>

#### Type declaration

▸ (`hashOrNumber`, `page`, `count?`): `Promise`<`components`[``"schemas"``][``"block_content_array"``]\>

blocksNext

##### Parameters

| Name | Type |
| :------ | :------ |
| `hashOrNumber` | `HashOrNumber` |
| `page` | `number` |
| `count` | `number` |

##### Returns

`Promise`<`components`[``"schemas"``][``"block_content_array"``]\>

xxx

#### Defined in

[index.ts:340](https://github.com/blockfrost/blockfrost-js/blob/74c5e4a/src/index.ts#L340)

___

### blocksPrevious

• **blocksPrevious**: (`hashOrNumber`: `HashOrNumber`, `page`: `number`, `count`: `number`) => `Promise`<`components`[``"schemas"``][``"block_content_array"``]\>

#### Type declaration

▸ (`hashOrNumber`, `page`, `count?`): `Promise`<`components`[``"schemas"``][``"block_content_array"``]\>

blockPrevious

##### Parameters

| Name | Type |
| :------ | :------ |
| `hashOrNumber` | `HashOrNumber` |
| `page` | `number` |
| `count` | `number` |

##### Returns

`Promise`<`components`[``"schemas"``][``"block_content_array"``]\>

xxx

#### Defined in

[index.ts:349](https://github.com/blockfrost/blockfrost-js/blob/74c5e4a/src/index.ts#L349)

___

### blocksTxs

• **blocksTxs**: (`hashOrNumber`: `HashOrNumber`, `page`: `number`, `count`: `number`, `order`: ``"asc"`` \| ``"desc"``) => `Promise`<`components`[``"schemas"``][``"block_content_txs"``]\>

#### Type declaration

▸ (`hashOrNumber`, `page`, `count?`, `order?`): `Promise`<`components`[``"schemas"``][``"block_content_txs"``]\>

addressesUtxos

##### Parameters

| Name | Type |
| :------ | :------ |
| `hashOrNumber` | `HashOrNumber` |
| `page` | `number` |
| `count` | `number` |
| `order` | ``"asc"`` \| ``"desc"`` |

##### Returns

`Promise`<`components`[``"schemas"``][``"block_content_txs"``]\>

xxx

#### Defined in

[index.ts:358](https://github.com/blockfrost/blockfrost-js/blob/74c5e4a/src/index.ts#L358)

___

### blocksTxsAll

• **blocksTxsAll**: (`hashOrNumber`: `string` \| `number`, `order`: ``"asc"`` \| ``"desc"``, `batchSize`: `number`) => `Promise`<`components`[``"schemas"``][``"block_content_txs"``]\>

#### Type declaration

▸ (`hashOrNumber`, `order`, `batchSize?`): `Promise`<`components`[``"schemas"``][``"block_content_txs"``]\>

blocksTxsAll

##### Parameters

| Name | Type |
| :------ | :------ |
| `hashOrNumber` | `string` \| `number` |
| `order` | ``"asc"`` \| ``"desc"`` |
| `batchSize` | `number` |

##### Returns

`Promise`<`components`[``"schemas"``][``"block_content_txs"``]\>

xxx

#### Defined in

[index.ts:367](https://github.com/blockfrost/blockfrost-js/blob/74c5e4a/src/index.ts#L367)

___

### epochs

• **epochs**: (`number`: `number`) => `Promise`<`components`[``"schemas"``][``"epoch_content"``]\>

#### Type declaration

▸ (`number`): `Promise`<`components`[``"schemas"``][``"epoch_content"``]\>

epochs

##### Parameters

| Name | Type |
| :------ | :------ |
| `number` | `number` |

##### Returns

`Promise`<`components`[``"schemas"``][``"epoch_content"``]\>

xxx

#### Defined in

[index.ts:376](https://github.com/blockfrost/blockfrost-js/blob/74c5e4a/src/index.ts#L376)

___

### epochsBlocks

• **epochsBlocks**: (`number`: `number`, `page`: `number`, `count`: `number`, `order`: ``"asc"`` \| ``"desc"``) => `Promise`<`components`[``"schemas"``][``"epoch_block_content"``]\>

#### Type declaration

▸ (`number`, `page`, `count?`, `order?`): `Promise`<`components`[``"schemas"``][``"epoch_block_content"``]\>

epochsBlocks

##### Parameters

| Name | Type |
| :------ | :------ |
| `number` | `number` |
| `page` | `number` |
| `count` | `number` |
| `order` | ``"asc"`` \| ``"desc"`` |

##### Returns

`Promise`<`components`[``"schemas"``][``"epoch_block_content"``]\>

xxx

#### Defined in

[index.ts:385](https://github.com/blockfrost/blockfrost-js/blob/74c5e4a/src/index.ts#L385)

___

### epochsBlocksByPoolId

• **epochsBlocksByPoolId**: (`number`: `number`, `poolId`: `string`, `page`: `number`, `count`: `number`, `order`: ``"asc"`` \| ``"desc"``) => `Promise`<`components`[``"schemas"``][``"epoch_stake_pool_content"``]\>

#### Type declaration

▸ (`number`, `poolId`, `page`, `count?`, `order?`): `Promise`<`components`[``"schemas"``][``"epoch_stake_pool_content"``]\>

epochsBlocksByPoolId

##### Parameters

| Name | Type |
| :------ | :------ |
| `number` | `number` |
| `poolId` | `string` |
| `page` | `number` |
| `count` | `number` |
| `order` | ``"asc"`` \| ``"desc"`` |

##### Returns

`Promise`<`components`[``"schemas"``][``"epoch_stake_pool_content"``]\>

xxx

#### Defined in

[index.ts:394](https://github.com/blockfrost/blockfrost-js/blob/74c5e4a/src/index.ts#L394)

___

### epochsLatest

• **epochsLatest**: () => `Promise`<`components`[``"schemas"``][``"epoch_content"``]\>

#### Type declaration

▸ (): `Promise`<`components`[``"schemas"``][``"epoch_content"``]\>

epochsLatest

##### Returns

`Promise`<`components`[``"schemas"``][``"epoch_content"``]\>

xxx

#### Defined in

[index.ts:402](https://github.com/blockfrost/blockfrost-js/blob/74c5e4a/src/index.ts#L402)

___

### epochsNext

• **epochsNext**: (`number`: `number`, `page`: `number`, `count`: `number`) => `Promise`<`components`[``"schemas"``][``"epoch_content_array"``]\>

#### Type declaration

▸ (`number`, `page`, `count?`): `Promise`<`components`[``"schemas"``][``"epoch_content_array"``]\>

epochsNext

##### Parameters

| Name | Type |
| :------ | :------ |
| `number` | `number` |
| `page` | `number` |
| `count` | `number` |

##### Returns

`Promise`<`components`[``"schemas"``][``"epoch_content_array"``]\>

xxx

#### Defined in

[index.ts:411](https://github.com/blockfrost/blockfrost-js/blob/74c5e4a/src/index.ts#L411)

___

### epochsParameters

• **epochsParameters**: (`number`: `number`) => `Promise`<`components`[``"schemas"``][``"epoch_param_content"``]\>

#### Type declaration

▸ (`number`): `Promise`<`components`[``"schemas"``][``"epoch_param_content"``]\>

epochsParameters

##### Parameters

| Name | Type |
| :------ | :------ |
| `number` | `number` |

##### Returns

`Promise`<`components`[``"schemas"``][``"epoch_param_content"``]\>

xxx

#### Defined in

[index.ts:420](https://github.com/blockfrost/blockfrost-js/blob/74c5e4a/src/index.ts#L420)

___

### epochsPrevious

• **epochsPrevious**: (`number`: `number`, `page`: `number`, `count`: `number`) => `Promise`<`components`[``"schemas"``][``"epoch_content_array"``]\>

#### Type declaration

▸ (`number`, `page`, `count?`): `Promise`<`components`[``"schemas"``][``"epoch_content_array"``]\>

epochsPrevious

##### Parameters

| Name | Type |
| :------ | :------ |
| `number` | `number` |
| `page` | `number` |
| `count` | `number` |

##### Returns

`Promise`<`components`[``"schemas"``][``"epoch_content_array"``]\>

xxx

#### Defined in

[index.ts:429](https://github.com/blockfrost/blockfrost-js/blob/74c5e4a/src/index.ts#L429)

___

### epochsStakes

• **epochsStakes**: (`number`: `number`, `page`: `number`, `count`: `number`) => `Promise`<`components`[``"schemas"``][``"epoch_stake_content"``]\>

#### Type declaration

▸ (`number`, `page`, `count?`): `Promise`<`components`[``"schemas"``][``"epoch_stake_content"``]\>

epochsStakes

##### Parameters

| Name | Type |
| :------ | :------ |
| `number` | `number` |
| `page` | `number` |
| `count` | `number` |

##### Returns

`Promise`<`components`[``"schemas"``][``"epoch_stake_content"``]\>

xxx

#### Defined in

[index.ts:438](https://github.com/blockfrost/blockfrost-js/blob/74c5e4a/src/index.ts#L438)

___

### epochsStakesByPoolId

• **epochsStakesByPoolId**: (`number`: `number`, `poolId`: `string`, `page`: `number`, `count`: `number`) => `Promise`<`components`[``"schemas"``][``"epoch_block_content"``]\>

#### Type declaration

▸ (`number`, `poolId`, `page`, `count?`): `Promise`<`components`[``"schemas"``][``"epoch_block_content"``]\>

epochsStakesByPoolId

##### Parameters

| Name | Type |
| :------ | :------ |
| `number` | `number` |
| `poolId` | `string` |
| `page` | `number` |
| `count` | `number` |

##### Returns

`Promise`<`components`[``"schemas"``][``"epoch_block_content"``]\>

xxx

#### Defined in

[index.ts:447](https://github.com/blockfrost/blockfrost-js/blob/74c5e4a/src/index.ts#L447)

___

### health

• **health**: () => `Promise`<`Object`\>

#### Type declaration

▸ (): `Promise`<`Object`\>

health

##### Returns

`Promise`<`Object`\>

xxx

#### Defined in

[index.ts:455](https://github.com/blockfrost/blockfrost-js/blob/74c5e4a/src/index.ts#L455)

___

### healthClock

• **healthClock**: () => `Promise`<`Object`\>

#### Type declaration

▸ (): `Promise`<`Object`\>

healthClock

##### Returns

`Promise`<`Object`\>

xxx

#### Defined in

[index.ts:463](https://github.com/blockfrost/blockfrost-js/blob/74c5e4a/src/index.ts#L463)

___

### ledger

• **ledger**: () => `Promise`<`components`[``"schemas"``][``"genesis_content"``]\>

#### Type declaration

▸ (): `Promise`<`components`[``"schemas"``][``"genesis_content"``]\>

ledger

##### Returns

`Promise`<`components`[``"schemas"``][``"genesis_content"``]\>

xxx

#### Defined in

[index.ts:471](https://github.com/blockfrost/blockfrost-js/blob/74c5e4a/src/index.ts#L471)

___

### metadataTxsLabel

• **metadataTxsLabel**: (`label`: `string`, `page`: `number`, `count`: `number`, `order`: ``"asc"`` \| ``"desc"``) => `Promise`<`components`[``"schemas"``][``"tx_metadata_labels"``]\>

#### Type declaration

▸ (`label`, `page`, `count?`, `order?`): `Promise`<`components`[``"schemas"``][``"tx_metadata_labels"``]\>

metadataTxsLabel

##### Parameters

| Name | Type |
| :------ | :------ |
| `label` | `string` |
| `page` | `number` |
| `count` | `number` |
| `order` | ``"asc"`` \| ``"desc"`` |

##### Returns

`Promise`<`components`[``"schemas"``][``"tx_metadata_labels"``]\>

xxx

#### Defined in

[index.ts:480](https://github.com/blockfrost/blockfrost-js/blob/74c5e4a/src/index.ts#L480)

___

### metadataTxsLabelCbor

• **metadataTxsLabelCbor**: (`label`: `string`, `page`: `number`, `count`: `number`, `order`: ``"asc"`` \| ``"desc"``) => `Promise`<`components`[``"schemas"``][``"tx_metadata_label_cbor"``]\>

#### Type declaration

▸ (`label`, `page`, `count?`, `order?`): `Promise`<`components`[``"schemas"``][``"tx_metadata_label_cbor"``]\>

metadataTxsLabelCbor

##### Parameters

| Name | Type |
| :------ | :------ |
| `label` | `string` |
| `page` | `number` |
| `count` | `number` |
| `order` | ``"asc"`` \| ``"desc"`` |

##### Returns

`Promise`<`components`[``"schemas"``][``"tx_metadata_label_cbor"``]\>

xxx

#### Defined in

[index.ts:489](https://github.com/blockfrost/blockfrost-js/blob/74c5e4a/src/index.ts#L489)

___

### metadataTxsLabels

• **metadataTxsLabels**: (`page`: `number`, `count`: `number`, `order`: ``"asc"`` \| ``"desc"``) => `Promise`<`components`[``"schemas"``][``"tx_metadata_label_json"``]\>

#### Type declaration

▸ (`page`, `count?`, `order?`): `Promise`<`components`[``"schemas"``][``"tx_metadata_label_json"``]\>

metadataTxsLabels

##### Parameters

| Name | Type |
| :------ | :------ |
| `page` | `number` |
| `count` | `number` |
| `order` | ``"asc"`` \| ``"desc"`` |

##### Returns

`Promise`<`components`[``"schemas"``][``"tx_metadata_label_json"``]\>

xxx

#### Defined in

[index.ts:497](https://github.com/blockfrost/blockfrost-js/blob/74c5e4a/src/index.ts#L497)

___

### metrics

• **metrics**: () => `Promise`<`components`[``"schemas"``][``"metrics"``]\>

#### Type declaration

▸ (): `Promise`<`components`[``"schemas"``][``"metrics"``]\>

metrics

##### Returns

`Promise`<`components`[``"schemas"``][``"metrics"``]\>

xxx

#### Defined in

[index.ts:505](https://github.com/blockfrost/blockfrost-js/blob/74c5e4a/src/index.ts#L505)

___

### metricsEndpoints

• **metricsEndpoints**: () => `Promise`<`components`[``"schemas"``][``"metrics"``]\>

#### Type declaration

▸ (): `Promise`<`components`[``"schemas"``][``"metrics"``]\>

metricsEndpoints

##### Returns

`Promise`<`components`[``"schemas"``][``"metrics"``]\>

xxx

#### Defined in

[index.ts:513](https://github.com/blockfrost/blockfrost-js/blob/74c5e4a/src/index.ts#L513)

___

### poolMetadata

• **poolMetadata**: (`poolId`: `string`) => `Promise`<`components`[``"schemas"``][``"pool_metadata"``]\>

#### Type declaration

▸ (`poolId`): `Promise`<`components`[``"schemas"``][``"pool_metadata"``]\>

poolMetadata

##### Parameters

| Name | Type |
| :------ | :------ |
| `poolId` | `string` |

##### Returns

`Promise`<`components`[``"schemas"``][``"pool_metadata"``]\>

xxx

#### Defined in

[index.ts:530](https://github.com/blockfrost/blockfrost-js/blob/74c5e4a/src/index.ts#L530)

___

### pools

• **pools**: (`page`: `number`, `count`: `number`, `order`: ``"asc"`` \| ``"desc"``) => `Promise`<`components`[``"schemas"``][``"pool_list"``]\>

#### Type declaration

▸ (`page`, `count?`, `order?`): `Promise`<`components`[``"schemas"``][``"pool_list"``]\>

pools

##### Parameters

| Name | Type |
| :------ | :------ |
| `page` | `number` |
| `count` | `number` |
| `order` | ``"asc"`` \| ``"desc"`` |

##### Returns

`Promise`<`components`[``"schemas"``][``"pool_list"``]\>

xxx

#### Defined in

[index.ts:521](https://github.com/blockfrost/blockfrost-js/blob/74c5e4a/src/index.ts#L521)

___

### poolsById

• **poolsById**: (`poolId`: `string`) => `Promise`<`components`[``"schemas"``][``"pool"``]\>

#### Type declaration

▸ (`poolId`): `Promise`<`components`[``"schemas"``][``"pool"``]\>

poolsById

##### Parameters

| Name | Type |
| :------ | :------ |
| `poolId` | `string` |

##### Returns

`Promise`<`components`[``"schemas"``][``"pool"``]\>

xxx

#### Defined in

[index.ts:539](https://github.com/blockfrost/blockfrost-js/blob/74c5e4a/src/index.ts#L539)

___

### poolsByIdBlocks

• **poolsByIdBlocks**: (`poolId`: `string`, `page`: `number`, `count`: `number`, `order`: ``"asc"`` \| ``"desc"``) => `Promise`<`components`[``"schemas"``][``"pool_blocks"``]\>

#### Type declaration

▸ (`poolId`, `page`, `count?`, `order?`): `Promise`<`components`[``"schemas"``][``"pool_blocks"``]\>

poolsByIdBlocks

##### Parameters

| Name | Type |
| :------ | :------ |
| `poolId` | `string` |
| `page` | `number` |
| `count` | `number` |
| `order` | ``"asc"`` \| ``"desc"`` |

##### Returns

`Promise`<`components`[``"schemas"``][``"pool_blocks"``]\>

xxx

#### Defined in

[index.ts:548](https://github.com/blockfrost/blockfrost-js/blob/74c5e4a/src/index.ts#L548)

___

### poolsByIdDelegators

• **poolsByIdDelegators**: (`poolId`: `string`, `page`: `number`, `count`: `number`, `order`: ``"asc"`` \| ``"desc"``) => `Promise`<`components`[``"schemas"``][``"pool_delegators"``]\>

#### Type declaration

▸ (`poolId`, `page`, `count?`, `order?`): `Promise`<`components`[``"schemas"``][``"pool_delegators"``]\>

poolsByIdDelegators

##### Parameters

| Name | Type |
| :------ | :------ |
| `poolId` | `string` |
| `page` | `number` |
| `count` | `number` |
| `order` | ``"asc"`` \| ``"desc"`` |

##### Returns

`Promise`<`components`[``"schemas"``][``"pool_delegators"``]\>

xxx

#### Defined in

[index.ts:557](https://github.com/blockfrost/blockfrost-js/blob/74c5e4a/src/index.ts#L557)

___

### poolsByIdHistory

• **poolsByIdHistory**: (`poolId`: `string`, `page`: `number`, `count`: `number`, `order`: ``"asc"`` \| ``"desc"``) => `Promise`<`components`[``"schemas"``][``"pool_history"``]\>

#### Type declaration

▸ (`poolId`, `page`, `count?`, `order?`): `Promise`<`components`[``"schemas"``][``"pool_history"``]\>

poolsByIdHistory

##### Parameters

| Name | Type |
| :------ | :------ |
| `poolId` | `string` |
| `page` | `number` |
| `count` | `number` |
| `order` | ``"asc"`` \| ``"desc"`` |

##### Returns

`Promise`<`components`[``"schemas"``][``"pool_history"``]\>

xxx

#### Defined in

[index.ts:566](https://github.com/blockfrost/blockfrost-js/blob/74c5e4a/src/index.ts#L566)

___

### poolsByIdRelays

• **poolsByIdRelays**: (`poolId`: `string`) => `Promise`<`components`[``"schemas"``][``"pool_relays"``]\>

#### Type declaration

▸ (`poolId`): `Promise`<`components`[``"schemas"``][``"pool_relays"``]\>

poolsByIdRelays

##### Parameters

| Name | Type |
| :------ | :------ |
| `poolId` | `string` |

##### Returns

`Promise`<`components`[``"schemas"``][``"pool_relays"``]\>

xxx

#### Defined in

[index.ts:575](https://github.com/blockfrost/blockfrost-js/blob/74c5e4a/src/index.ts#L575)

___

### poolsByIdUpdates

• **poolsByIdUpdates**: (`poolId`: `string`, `page`: `number`, `count`: `number`, `order`: ``"asc"`` \| ``"desc"``) => `Promise`<`components`[``"schemas"``][``"pool_updates"``]\>

#### Type declaration

▸ (`poolId`, `page`, `count?`, `order?`): `Promise`<`components`[``"schemas"``][``"pool_updates"``]\>

poolsByIdUpdates

##### Parameters

| Name | Type |
| :------ | :------ |
| `poolId` | `string` |
| `page` | `number` |
| `count` | `number` |
| `order` | ``"asc"`` \| ``"desc"`` |

##### Returns

`Promise`<`components`[``"schemas"``][``"pool_updates"``]\>

xxx

#### Defined in

[index.ts:584](https://github.com/blockfrost/blockfrost-js/blob/74c5e4a/src/index.ts#L584)

___

### poolsRetired

• **poolsRetired**: (`page`: `number`, `count`: `number`, `order`: ``"asc"`` \| ``"desc"``) => `Promise`<`components`[``"schemas"``][``"pool_list_retire"``]\>

#### Type declaration

▸ (`page`, `count?`, `order?`): `Promise`<`components`[``"schemas"``][``"pool_list_retire"``]\>

poolsRetired

##### Parameters

| Name | Type |
| :------ | :------ |
| `page` | `number` |
| `count` | `number` |
| `order` | ``"asc"`` \| ``"desc"`` |

##### Returns

`Promise`<`components`[``"schemas"``][``"pool_list_retire"``]\>

xxx

#### Defined in

[index.ts:592](https://github.com/blockfrost/blockfrost-js/blob/74c5e4a/src/index.ts#L592)

___

### poolsRetiring

• **poolsRetiring**: (`page`: `number`, `count`: `number`, `order`: ``"asc"`` \| ``"desc"``) => `Promise`<`components`[``"schemas"``][``"pool_list_retire"``]\>

#### Type declaration

▸ (`page`, `count?`, `order?`): `Promise`<`components`[``"schemas"``][``"pool_list_retire"``]\>

poolsRetiring

##### Parameters

| Name | Type |
| :------ | :------ |
| `page` | `number` |
| `count` | `number` |
| `order` | ``"asc"`` \| ``"desc"`` |

##### Returns

`Promise`<`components`[``"schemas"``][``"pool_list_retire"``]\>

xxx

#### Defined in

[index.ts:600](https://github.com/blockfrost/blockfrost-js/blob/74c5e4a/src/index.ts#L600)

___

### projectId

• `Optional` **projectId**: `string`

#### Defined in

[index.ts:107](https://github.com/blockfrost/blockfrost-js/blob/74c5e4a/src/index.ts#L107)

___

### root

• **root**: () => `Promise`<`Object`\>

#### Type declaration

▸ (): `Promise`<`Object`\>

root

##### Returns

`Promise`<`Object`\>

xxx

#### Defined in

[index.ts:608](https://github.com/blockfrost/blockfrost-js/blob/74c5e4a/src/index.ts#L608)

___

### txSubmit

• **txSubmit**: (`transaction`: `Uint8Array`) => `Promise`<string\>

#### Type declaration

▸ (`transaction`): `Promise`<string\>

txSubmit

##### Parameters

| Name | Type |
| :------ | :------ |
| `transaction` | `Uint8Array` |

##### Returns

`Promise`<string\>

xxx

#### Defined in

[index.ts:698](https://github.com/blockfrost/blockfrost-js/blob/74c5e4a/src/index.ts#L698)

___

### txs

• **txs**: (`hash`: `string`) => `Promise`<`components`[``"schemas"``][``"tx_content"``]\>

#### Type declaration

▸ (`hash`): `Promise`<`components`[``"schemas"``][``"tx_content"``]\>

txs

##### Parameters

| Name | Type |
| :------ | :------ |
| `hash` | `string` |

##### Returns

`Promise`<`components`[``"schemas"``][``"tx_content"``]\>

xxx

#### Defined in

[index.ts:617](https://github.com/blockfrost/blockfrost-js/blob/74c5e4a/src/index.ts#L617)

___

### txsDelegations

• **txsDelegations**: (`hash`: `string`) => `Promise`<`components`[``"schemas"``][``"tx_content_delegations"``]\>

#### Type declaration

▸ (`hash`): `Promise`<`components`[``"schemas"``][``"tx_content_delegations"``]\>

txsDelegations

##### Parameters

| Name | Type |
| :------ | :------ |
| `hash` | `string` |

##### Returns

`Promise`<`components`[``"schemas"``][``"tx_content_delegations"``]\>

xxx

#### Defined in

[index.ts:635](https://github.com/blockfrost/blockfrost-js/blob/74c5e4a/src/index.ts#L635)

___

### txsMetadata

• **txsMetadata**: (`hash`: `string`) => `Promise`<`components`[``"schemas"``][``"tx_metadata_label_json"``]\>

#### Type declaration

▸ (`hash`): `Promise`<`components`[``"schemas"``][``"tx_metadata_label_json"``]\>

txsMetadata

##### Parameters

| Name | Type |
| :------ | :------ |
| `hash` | `string` |

##### Returns

`Promise`<`components`[``"schemas"``][``"tx_metadata_label_json"``]\>

xxx

#### Defined in

[index.ts:689](https://github.com/blockfrost/blockfrost-js/blob/74c5e4a/src/index.ts#L689)

___

### txsMetadataCbor

• **txsMetadataCbor**: (`hash`: `string`) => `Promise`<`components`[``"schemas"``][``"tx_content_metadata_cbor"``]\>

#### Type declaration

▸ (`hash`): `Promise`<`components`[``"schemas"``][``"tx_content_metadata_cbor"``]\>

txsMetadataCbor

##### Parameters

| Name | Type |
| :------ | :------ |
| `hash` | `string` |

##### Returns

`Promise`<`components`[``"schemas"``][``"tx_content_metadata_cbor"``]\>

xxx

#### Defined in

[index.ts:626](https://github.com/blockfrost/blockfrost-js/blob/74c5e4a/src/index.ts#L626)

___

### txsPoolRetires

• **txsPoolRetires**: (`hash`: `string`) => `Promise`<`components`[``"schemas"``][``"tx_content_pool_retires"``]\>

#### Type declaration

▸ (`hash`): `Promise`<`components`[``"schemas"``][``"tx_content_pool_retires"``]\>

txsPoolRetires

##### Parameters

| Name | Type |
| :------ | :------ |
| `hash` | `string` |

##### Returns

`Promise`<`components`[``"schemas"``][``"tx_content_pool_retires"``]\>

xxx

#### Defined in

[index.ts:644](https://github.com/blockfrost/blockfrost-js/blob/74c5e4a/src/index.ts#L644)

___

### txsPoolUpdates

• **txsPoolUpdates**: (`hash`: `string`) => `Promise`<`components`[``"schemas"``][``"tx_content_pool_certs"``]\>

#### Type declaration

▸ (`hash`): `Promise`<`components`[``"schemas"``][``"tx_content_pool_certs"``]\>

txsPoolUpdates

##### Parameters

| Name | Type |
| :------ | :------ |
| `hash` | `string` |

##### Returns

`Promise`<`components`[``"schemas"``][``"tx_content_pool_certs"``]\>

xxx

#### Defined in

[index.ts:653](https://github.com/blockfrost/blockfrost-js/blob/74c5e4a/src/index.ts#L653)

___

### txsStakes

• **txsStakes**: (`hash`: `string`) => `Promise`<`components`[``"schemas"``][``"tx_content_stake_addr"``]\>

#### Type declaration

▸ (`hash`): `Promise`<`components`[``"schemas"``][``"tx_content_stake_addr"``]\>

txsStakes

##### Parameters

| Name | Type |
| :------ | :------ |
| `hash` | `string` |

##### Returns

`Promise`<`components`[``"schemas"``][``"tx_content_stake_addr"``]\>

xxx

#### Defined in

[index.ts:662](https://github.com/blockfrost/blockfrost-js/blob/74c5e4a/src/index.ts#L662)

___

### txsUtxos

• **txsUtxos**: (`hash`: `string`) => `Promise`<`components`[``"schemas"``][``"tx_content_utxo"``]\>

#### Type declaration

▸ (`hash`): `Promise`<`components`[``"schemas"``][``"tx_content_utxo"``]\>

txsUtxos

##### Parameters

| Name | Type |
| :------ | :------ |
| `hash` | `string` |

##### Returns

`Promise`<`components`[``"schemas"``][``"tx_content_utxo"``]\>

xxx

#### Defined in

[index.ts:671](https://github.com/blockfrost/blockfrost-js/blob/74c5e4a/src/index.ts#L671)

___

### txsWithdrawals

• **txsWithdrawals**: (`hash`: `string`) => `Promise`<`components`[``"schemas"``][``"tx_content_withdrawals"``]\>

#### Type declaration

▸ (`hash`): `Promise`<`components`[``"schemas"``][``"tx_content_withdrawals"``]\>

txsWithdrawals

##### Parameters

| Name | Type |
| :------ | :------ |
| `hash` | `string` |

##### Returns

`Promise`<`components`[``"schemas"``][``"tx_content_withdrawals"``]\>

xxx

#### Defined in

[index.ts:680](https://github.com/blockfrost/blockfrost-js/blob/74c5e4a/src/index.ts#L680)

___

### userAgent

• `Optional` **userAgent**: `string`

#### Defined in

[index.ts:108](https://github.com/blockfrost/blockfrost-js/blob/74c5e4a/src/index.ts#L108)
