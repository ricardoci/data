# Class: BlockFrostAPI

## Table of contents

### Constructors

- [constructor](../wiki/BlockFrostAPI#constructor)

### Properties

- [accounts](../wiki/BlockFrostAPI#accounts)
- [accountsAddresses](../wiki/BlockFrostAPI#accountsaddresses)
- [accountsAddressesAll](../wiki/BlockFrostAPI#accountsaddressesall)
- [accountsDelegations](../wiki/BlockFrostAPI#accountsdelegations)
- [accountsDelegationsAll](../wiki/BlockFrostAPI#accountsdelegationsall)
- [accountsHistory](../wiki/BlockFrostAPI#accountshistory)
- [accountsHistoryAll](../wiki/BlockFrostAPI#accountshistoryall)
- [accountsMirs](../wiki/BlockFrostAPI#accountsmirs)
- [accountsMirsAll](../wiki/BlockFrostAPI#accountsmirsall)
- [accountsRegistrations](../wiki/BlockFrostAPI#accountsregistrations)
- [accountsRegistrationsAll](../wiki/BlockFrostAPI#accountsregistrationsall)
- [accountsRewards](../wiki/BlockFrostAPI#accountsrewards)
- [accountsRewardsAll](../wiki/BlockFrostAPI#accountsrewardsall)
- [accountsWithdrawals](../wiki/BlockFrostAPI#accountswithdrawals)
- [accountsWithdrawalsAll](../wiki/BlockFrostAPI#accountswithdrawalsall)
- [addresses](../wiki/BlockFrostAPI#addresses)
- [addressesTotal](../wiki/BlockFrostAPI#addressestotal)
- [addressesTransactions](../wiki/BlockFrostAPI#addressestransactions)
- [addressesTransactionsAll](../wiki/BlockFrostAPI#addressestransactionsall)
- [addressesTxs](../wiki/BlockFrostAPI#addressestxs)
- [addressesTxsAll](../wiki/BlockFrostAPI#addressestxsall)
- [addressesUtxos](../wiki/BlockFrostAPI#addressesutxos)
- [addressesUtxosAll](../wiki/BlockFrostAPI#addressesutxosall)
- [apiUrl](../wiki/BlockFrostAPI#apiurl)
- [assets](../wiki/BlockFrostAPI#assets)
- [assetsAddresses](../wiki/BlockFrostAPI#assetsaddresses)
- [assetsById](../wiki/BlockFrostAPI#assetsbyid)
- [assetsHistory](../wiki/BlockFrostAPI#assetshistory)
- [assetsHistoryAll](../wiki/BlockFrostAPI#assetshistoryall)
- [assetsPolicyById](../wiki/BlockFrostAPI#assetspolicybyid)
- [assetsPolicyByIdAll](../wiki/BlockFrostAPI#assetspolicybyidall)
- [assetsTransactions](../wiki/BlockFrostAPI#assetstransactions)
- [assetsTxs](../wiki/BlockFrostAPI#assetstxs)
- [axiosInstance](../wiki/BlockFrostAPI#axiosinstance)
- [blocks](../wiki/BlockFrostAPI#blocks)
- [blocksLatest](../wiki/BlockFrostAPI#blockslatest)
- [blocksNext](../wiki/BlockFrostAPI#blocksnext)
- [blocksPrevious](../wiki/BlockFrostAPI#blocksprevious)
- [blocksTxs](../wiki/BlockFrostAPI#blockstxs)
- [blocksTxsAll](../wiki/BlockFrostAPI#blockstxsall)
- [epochs](../wiki/BlockFrostAPI#epochs)
- [epochsBlocks](../wiki/BlockFrostAPI#epochsblocks)
- [epochsBlocksByPoolId](../wiki/BlockFrostAPI#epochsblocksbypoolid)
- [epochsLatest](../wiki/BlockFrostAPI#epochslatest)
- [epochsNext](../wiki/BlockFrostAPI#epochsnext)
- [epochsParameters](../wiki/BlockFrostAPI#epochsparameters)
- [epochsPrevious](../wiki/BlockFrostAPI#epochsprevious)
- [epochsStakes](../wiki/BlockFrostAPI#epochsstakes)
- [epochsStakesByPoolId](../wiki/BlockFrostAPI#epochsstakesbypoolid)
- [genesis](../wiki/BlockFrostAPI#genesis)
- [health](../wiki/BlockFrostAPI#health)
- [healthClock](../wiki/BlockFrostAPI#healthclock)
- [metadataTxsLabel](../wiki/BlockFrostAPI#metadatatxslabel)
- [metadataTxsLabelCbor](../wiki/BlockFrostAPI#metadatatxslabelcbor)
- [metadataTxsLabels](../wiki/BlockFrostAPI#metadatatxslabels)
- [metrics](../wiki/BlockFrostAPI#metrics)
- [metricsEndpoints](../wiki/BlockFrostAPI#metricsendpoints)
- [nutlinkAddress](../wiki/BlockFrostAPI#nutlinkaddress)
- [nutlinkAddressTicker](../wiki/BlockFrostAPI#nutlinkaddressticker)
- [nutlinkAddressTickerAll](../wiki/BlockFrostAPI#nutlinkaddresstickerall)
- [nutlinkAddressTickers](../wiki/BlockFrostAPI#nutlinkaddresstickers)
- [nutlinkAddressTickersAll](../wiki/BlockFrostAPI#nutlinkaddresstickersall)
- [nutlinkTickers](../wiki/BlockFrostAPI#nutlinktickers)
- [nutlinkTickersAll](../wiki/BlockFrostAPI#nutlinktickersall)
- [options](../wiki/BlockFrostAPI#options)
- [poolMetadata](../wiki/BlockFrostAPI#poolmetadata)
- [pools](../wiki/BlockFrostAPI#pools)
- [poolsById](../wiki/BlockFrostAPI#poolsbyid)
- [poolsByIdBlocks](../wiki/BlockFrostAPI#poolsbyidblocks)
- [poolsByIdDelegators](../wiki/BlockFrostAPI#poolsbyiddelegators)
- [poolsByIdHistory](../wiki/BlockFrostAPI#poolsbyidhistory)
- [poolsByIdRelays](../wiki/BlockFrostAPI#poolsbyidrelays)
- [poolsByIdUpdates](../wiki/BlockFrostAPI#poolsbyidupdates)
- [poolsRetired](../wiki/BlockFrostAPI#poolsretired)
- [poolsRetiring](../wiki/BlockFrostAPI#poolsretiring)
- [projectId](../wiki/BlockFrostAPI#projectid)
- [root](../wiki/BlockFrostAPI#root)
- [txSubmit](../wiki/BlockFrostAPI#txsubmit)
- [txs](../wiki/BlockFrostAPI#txs)
- [txsDelegations](../wiki/BlockFrostAPI#txsdelegations)
- [txsMetadata](../wiki/BlockFrostAPI#txsmetadata)
- [txsMetadataCbor](../wiki/BlockFrostAPI#txsmetadatacbor)
- [txsMirs](../wiki/BlockFrostAPI#txsmirs)
- [txsPoolRetires](../wiki/BlockFrostAPI#txspoolretires)
- [txsPoolUpdates](../wiki/BlockFrostAPI#txspoolupdates)
- [txsStakes](../wiki/BlockFrostAPI#txsstakes)
- [txsUtxos](../wiki/BlockFrostAPI#txsutxos)
- [txsWithdrawals](../wiki/BlockFrostAPI#txswithdrawals)
- [userAgent](../wiki/BlockFrostAPI#useragent)

## Constructors

### constructor

• **new BlockFrostAPI**(`options?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `options?` | `Options` |

#### Defined in

[BlockFrostAPI.ts:126](https://github.com/blockfrost/blockfrost-js/blob/ced2dac/src/BlockFrostAPI.ts#L126)

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

[BlockFrostAPI.ts:153](https://github.com/blockfrost/blockfrost-js/blob/ced2dac/src/BlockFrostAPI.ts#L153)

___

### accountsAddresses

• **accountsAddresses**: (`stakeAddress`: `string`, `pagination?`: `PaginationOptions`) => `Promise`<`components`[``"schemas"``][``"account_addresses_content"``]\>

#### Type declaration

▸ (`stakeAddress`, `pagination?`): `Promise`<`components`[``"schemas"``][``"account_addresses_content"``]\>

accountsAddresses - Obtain information about the addresses of a specific account.

##### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `stakeAddress` | `string` | Bech32 stake address |
| `pagination?` | `PaginationOptions` | - |

##### Returns

`Promise`<`components`[``"schemas"``][``"account_addresses_content"``]\>

Information about the addresses of a specific account.

#### Defined in

[BlockFrostAPI.ts:270](https://github.com/blockfrost/blockfrost-js/blob/ced2dac/src/BlockFrostAPI.ts#L270)

___

### accountsAddressesAll

• **accountsAddressesAll**: (`stakeAddress`: `string`, `order`: ``"asc"`` \| ``"desc"``, `batchSize`: `number`) => `Promise`<`components`[``"schemas"``][``"account_addresses_content"``]\>

#### Type declaration

▸ (`stakeAddress`, `order`, `batchSize?`): `Promise`<`components`[``"schemas"``][``"account_addresses_content"``]\>

accountsAddressesAll - Obtain information about all addresses of a specific account.

##### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `stakeAddress` | `string` | Bech32 stake address |
| `order` | ``"asc"`` \| ``"desc"`` | - |
| `batchSize` | `number` | - |

##### Returns

`Promise`<`components`[``"schemas"``][``"account_addresses_content"``]\>

Information about the addresses of a specific account.

#### Defined in

[BlockFrostAPI.ts:279](https://github.com/blockfrost/blockfrost-js/blob/ced2dac/src/BlockFrostAPI.ts#L279)

___

### accountsDelegations

• **accountsDelegations**: (`stakeAddress`: `string`, `pagination?`: `PaginationOptions`) => `Promise`<`components`[``"schemas"``][``"account_delegation_content"``]\>

#### Type declaration

▸ (`stakeAddress`, `pagination?`): `Promise`<`components`[``"schemas"``][``"account_delegation_content"``]\>

accountsDelegations - Obtain information about the delegation of a specific account.

##### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `stakeAddress` | `string` | Bech32 stake address |
| `pagination?` | `PaginationOptions` | - |

##### Returns

`Promise`<`components`[``"schemas"``][``"account_delegation_content"``]\>

Information about the delegation of a specific account.

#### Defined in

[BlockFrostAPI.ts:162](https://github.com/blockfrost/blockfrost-js/blob/ced2dac/src/BlockFrostAPI.ts#L162)

___

### accountsDelegationsAll

• **accountsDelegationsAll**: (`stakeAddress`: `string`, `order`: ``"asc"`` \| ``"desc"``, `batchSize`: `number`) => `Promise`<`components`[``"schemas"``][``"account_delegation_content"``]\>

#### Type declaration

▸ (`stakeAddress`, `order`, `batchSize?`): `Promise`<`components`[``"schemas"``][``"account_delegation_content"``]\>

accountsDelegationsAll - Obtain information about all delegations of a specific account.

##### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `stakeAddress` | `string` | Bech32 stake address |
| `order` | ``"asc"`` \| ``"desc"`` | - |
| `batchSize` | `number` | - |

##### Returns

`Promise`<`components`[``"schemas"``][``"account_delegation_content"``]\>

Information about the delegation of a specific account.

#### Defined in

[BlockFrostAPI.ts:171](https://github.com/blockfrost/blockfrost-js/blob/ced2dac/src/BlockFrostAPI.ts#L171)

___

### accountsHistory

• **accountsHistory**: (`stakeAddress`: `string`, `pagination?`: `PaginationOptions`) => `Promise`<`components`[``"schemas"``][``"account_history_content"``]\>

#### Type declaration

▸ (`stakeAddress`, `pagination?`): `Promise`<`components`[``"schemas"``][``"account_history_content"``]\>

accountsHistory - Obtain information about the history of a specific account.

##### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `stakeAddress` | `string` | Bech32 stake address |
| `pagination?` | `PaginationOptions` | - |

##### Returns

`Promise`<`components`[``"schemas"``][``"account_history_content"``]\>

Information about the history of a specific account.

#### Defined in

[BlockFrostAPI.ts:216](https://github.com/blockfrost/blockfrost-js/blob/ced2dac/src/BlockFrostAPI.ts#L216)

___

### accountsHistoryAll

• **accountsHistoryAll**: (`stakeAddress`: `string`, `order`: ``"asc"`` \| ``"desc"``, `batchSize`: `number`) => `Promise`<`components`[``"schemas"``][``"account_history_content"``]\>

#### Type declaration

▸ (`stakeAddress`, `order`, `batchSize?`): `Promise`<`components`[``"schemas"``][``"account_history_content"``]\>

accountsHistoryAll - Obtain information about whole history of a specific account.

##### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `stakeAddress` | `string` | Bech32 stake address |
| `order` | ``"asc"`` \| ``"desc"`` | - |
| `batchSize` | `number` | - |

##### Returns

`Promise`<`components`[``"schemas"``][``"account_history_content"``]\>

Information about the history of a specific account.

#### Defined in

[BlockFrostAPI.ts:225](https://github.com/blockfrost/blockfrost-js/blob/ced2dac/src/BlockFrostAPI.ts#L225)

___

### accountsMirs

• **accountsMirs**: (`stakeAddress`: `string`, `pagination?`: `PaginationOptions`) => `Promise`<`components`[``"schemas"``][``"account_mir_content"``]\>

#### Type declaration

▸ (`stakeAddress`, `pagination?`): `Promise`<`components`[``"schemas"``][``"account_mir_content"``]\>

accountsMirs - Obtain information about the MIRs of a specific account.

##### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `stakeAddress` | `string` | Bech32 stake address |
| `pagination?` | `PaginationOptions` | - |

##### Returns

`Promise`<`components`[``"schemas"``][``"account_mir_content"``]\>

Information about the MIRs of a specific account.

#### Defined in

[BlockFrostAPI.ts:252](https://github.com/blockfrost/blockfrost-js/blob/ced2dac/src/BlockFrostAPI.ts#L252)

___

### accountsMirsAll

• **accountsMirsAll**: (`stakeAddress`: `string`, `order`: ``"asc"`` \| ``"desc"``, `batchSize`: `number`) => `Promise`<`components`[``"schemas"``][``"account_mir_content"``]\>

#### Type declaration

▸ (`stakeAddress`, `order`, `batchSize?`): `Promise`<`components`[``"schemas"``][``"account_mir_content"``]\>

accountsMirsAll - Obtain information about all MIRs of a specific account.

##### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `stakeAddress` | `string` | Bech32 stake address |
| `order` | ``"asc"`` \| ``"desc"`` | - |
| `batchSize` | `number` | - |

##### Returns

`Promise`<`components`[``"schemas"``][``"account_mir_content"``]\>

Information about the MIRs of a specific account.

#### Defined in

[BlockFrostAPI.ts:261](https://github.com/blockfrost/blockfrost-js/blob/ced2dac/src/BlockFrostAPI.ts#L261)

___

### accountsRegistrations

• **accountsRegistrations**: (`stakeAddress`: `string`, `pagination?`: `PaginationOptions`) => `Promise`<`components`[``"schemas"``][``"account_registration_content"``]\>

#### Type declaration

▸ (`stakeAddress`, `pagination?`): `Promise`<`components`[``"schemas"``][``"account_registration_content"``]\>

accountsRegistrations - Obtain information about the registrations and deregistrations of a specific account.

##### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `stakeAddress` | `string` | Bech32 stake address |
| `pagination?` | `PaginationOptions` | - |

##### Returns

`Promise`<`components`[``"schemas"``][``"account_registration_content"``]\>

Information about the registrations and deregistrations of a specific account.

#### Defined in

[BlockFrostAPI.ts:180](https://github.com/blockfrost/blockfrost-js/blob/ced2dac/src/BlockFrostAPI.ts#L180)

___

### accountsRegistrationsAll

• **accountsRegistrationsAll**: (`stakeAddress`: `string`, `order`: ``"asc"`` \| ``"desc"``, `batchSize`: `number`) => `Promise`<`components`[``"schemas"``][``"account_registration_content"``]\>

#### Type declaration

▸ (`stakeAddress`, `order`, `batchSize?`): `Promise`<`components`[``"schemas"``][``"account_registration_content"``]\>

accountsRegistrationsAll - Obtain information about all registrations and deregistrations of a specific account.

##### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `stakeAddress` | `string` | Bech32 stake address |
| `order` | ``"asc"`` \| ``"desc"`` | - |
| `batchSize` | `number` | - |

##### Returns

`Promise`<`components`[``"schemas"``][``"account_registration_content"``]\>

Information about the registrations and deregistrations of a specific account.

#### Defined in

[BlockFrostAPI.ts:189](https://github.com/blockfrost/blockfrost-js/blob/ced2dac/src/BlockFrostAPI.ts#L189)

___

### accountsRewards

• **accountsRewards**: (`stakeAddress`: `string`, `pagination?`: `PaginationOptions`) => `Promise`<`components`[``"schemas"``][``"account_reward_content"``]\>

#### Type declaration

▸ (`stakeAddress`, `pagination?`): `Promise`<`components`[``"schemas"``][``"account_reward_content"``]\>

accountsRewards - Obtain information about the history of a specific account.

##### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `stakeAddress` | `string` | Bech32 stake address |
| `pagination?` | `PaginationOptions` | - |

##### Returns

`Promise`<`components`[``"schemas"``][``"account_reward_content"``]\>

Information about the history of a specific account.

#### Defined in

[BlockFrostAPI.ts:198](https://github.com/blockfrost/blockfrost-js/blob/ced2dac/src/BlockFrostAPI.ts#L198)

___

### accountsRewardsAll

• **accountsRewardsAll**: (`stakeAddress`: `string`, `order`: ``"asc"`` \| ``"desc"``, `batchSize`: `number`) => `Promise`<`components`[``"schemas"``][``"account_reward_content"``]\>

#### Type declaration

▸ (`stakeAddress`, `order`, `batchSize?`): `Promise`<`components`[``"schemas"``][``"account_reward_content"``]\>

accountsRewardsAll - Obtain information about whole history of a specific account.

##### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `stakeAddress` | `string` | Bech32 stake address |
| `order` | ``"asc"`` \| ``"desc"`` | - |
| `batchSize` | `number` | - |

##### Returns

`Promise`<`components`[``"schemas"``][``"account_reward_content"``]\>

Information about the history of a specific account.

#### Defined in

[BlockFrostAPI.ts:207](https://github.com/blockfrost/blockfrost-js/blob/ced2dac/src/BlockFrostAPI.ts#L207)

___

### accountsWithdrawals

• **accountsWithdrawals**: (`stakeAddress`: `string`, `pagination?`: `PaginationOptions`) => `Promise`<`components`[``"schemas"``][``"account_withdrawal_content"``]\>

#### Type declaration

▸ (`stakeAddress`, `pagination?`): `Promise`<`components`[``"schemas"``][``"account_withdrawal_content"``]\>

accountsWithdrawals - Obtain information about the withdrawals of a specific account.

##### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `stakeAddress` | `string` | Bech32 stake address |
| `pagination?` | `PaginationOptions` | - |

##### Returns

`Promise`<`components`[``"schemas"``][``"account_withdrawal_content"``]\>

Information about the withdrawals of a specific account.

#### Defined in

[BlockFrostAPI.ts:234](https://github.com/blockfrost/blockfrost-js/blob/ced2dac/src/BlockFrostAPI.ts#L234)

___

### accountsWithdrawalsAll

• **accountsWithdrawalsAll**: (`stakeAddress`: `string`, `order`: ``"asc"`` \| ``"desc"``, `batchSize`: `number`) => `Promise`<`components`[``"schemas"``][``"account_withdrawal_content"``]\>

#### Type declaration

▸ (`stakeAddress`, `order`, `batchSize?`): `Promise`<`components`[``"schemas"``][``"account_withdrawal_content"``]\>

accountsWithdrawalsAll - Obtain information about all withdrawals of a specific account.

##### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `stakeAddress` | `string` | Bech32 stake address |
| `order` | ``"asc"`` \| ``"desc"`` | - |
| `batchSize` | `number` | - |

##### Returns

`Promise`<`components`[``"schemas"``][``"account_withdrawal_content"``]\>

Information about the withdrawals of a specific account.

#### Defined in

[BlockFrostAPI.ts:243](https://github.com/blockfrost/blockfrost-js/blob/ced2dac/src/BlockFrostAPI.ts#L243)

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

[BlockFrostAPI.ts:368](https://github.com/blockfrost/blockfrost-js/blob/ced2dac/src/BlockFrostAPI.ts#L368)

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

[BlockFrostAPI.ts:377](https://github.com/blockfrost/blockfrost-js/blob/ced2dac/src/BlockFrostAPI.ts#L377)

___

### addressesTransactions

• **addressesTransactions**: (`address`: `string`, `pagination?`: `PaginationOptions`, `additionalOptions?`: `AdditionalEndpointOptions`) => `Promise`<`components`[``"schemas"``][``"address_transactions_content"``]\>

#### Type declaration

▸ (`address`, `pagination?`, `additionalOptions?`): `Promise`<`components`[``"schemas"``][``"address_transactions_content"``]\>

addressesTransactions

##### Parameters

| Name | Type |
| :------ | :------ |
| `address` | `string` |
| `pagination?` | `PaginationOptions` |
| `additionalOptions?` | `AdditionalEndpointOptions` |

##### Returns

`Promise`<`components`[``"schemas"``][``"address_transactions_content"``]\>

xxx

#### Defined in

[BlockFrostAPI.ts:404](https://github.com/blockfrost/blockfrost-js/blob/ced2dac/src/BlockFrostAPI.ts#L404)

___

### addressesTransactionsAll

• **addressesTransactionsAll**: (`address`: `string`, `order`: ``"asc"`` \| ``"desc"``, `batchSize`: `number`) => `Promise`<`components`[``"schemas"``][``"address_transactions_content"``]\>

#### Type declaration

▸ (`address`, `order`, `batchSize?`): `Promise`<`components`[``"schemas"``][``"address_transactions_content"``]\>

addressesTransactionsAll

##### Parameters

| Name | Type |
| :------ | :------ |
| `address` | `string` |
| `order` | ``"asc"`` \| ``"desc"`` |
| `batchSize` | `number` |

##### Returns

`Promise`<`components`[``"schemas"``][``"address_transactions_content"``]\>

xxx

#### Defined in

[BlockFrostAPI.ts:413](https://github.com/blockfrost/blockfrost-js/blob/ced2dac/src/BlockFrostAPI.ts#L413)

___

### addressesTxs

• **addressesTxs**: (`address`: `string`, `pagination?`: `PaginationOptions`) => `Promise`<`components`[``"schemas"``][``"address_txs_content"``]\>

#### Type declaration

▸ (`address`, `pagination?`): `Promise`<`components`[``"schemas"``][``"address_txs_content"``]\>

addressesTxs

##### Parameters

| Name | Type |
| :------ | :------ |
| `address` | `string` |
| `pagination?` | `PaginationOptions` |

##### Returns

`Promise`<`components`[``"schemas"``][``"address_txs_content"``]\>

xxx

#### Defined in

[BlockFrostAPI.ts:386](https://github.com/blockfrost/blockfrost-js/blob/ced2dac/src/BlockFrostAPI.ts#L386)

___

### addressesTxsAll

• **addressesTxsAll**: (`address`: `string`, `order`: ``"asc"`` \| ``"desc"``, `batchSize`: `number`) => `Promise`<`components`[``"schemas"``][``"address_txs_content"``]\>

#### Type declaration

▸ (`address`, `order`, `batchSize?`): `Promise`<`components`[``"schemas"``][``"address_txs_content"``]\>

addressesTxsAll

##### Parameters

| Name | Type |
| :------ | :------ |
| `address` | `string` |
| `order` | ``"asc"`` \| ``"desc"`` |
| `batchSize` | `number` |

##### Returns

`Promise`<`components`[``"schemas"``][``"address_txs_content"``]\>

xxx

#### Defined in

[BlockFrostAPI.ts:395](https://github.com/blockfrost/blockfrost-js/blob/ced2dac/src/BlockFrostAPI.ts#L395)

___

### addressesUtxos

• **addressesUtxos**: (`address`: `string`, `pagination?`: `PaginationOptions`) => `Promise`<`components`[``"schemas"``][``"address_utxo_content"``]\>

#### Type declaration

▸ (`address`, `pagination?`): `Promise`<`components`[``"schemas"``][``"address_utxo_content"``]\>

addressesUtxos

##### Parameters

| Name | Type |
| :------ | :------ |
| `address` | `string` |
| `pagination?` | `PaginationOptions` |

##### Returns

`Promise`<`components`[``"schemas"``][``"address_utxo_content"``]\>

xxx

#### Defined in

[BlockFrostAPI.ts:422](https://github.com/blockfrost/blockfrost-js/blob/ced2dac/src/BlockFrostAPI.ts#L422)

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

[BlockFrostAPI.ts:431](https://github.com/blockfrost/blockfrost-js/blob/ced2dac/src/BlockFrostAPI.ts#L431)

___

### apiUrl

• **apiUrl**: `string`

#### Defined in

[BlockFrostAPI.ts:120](https://github.com/blockfrost/blockfrost-js/blob/ced2dac/src/BlockFrostAPI.ts#L120)

___

### assets

• **assets**: (`pagination?`: `PaginationOptions`) => `Promise`<`components`[``"schemas"``][``"assets"``]\>

#### Type declaration

▸ (`pagination?`): `Promise`<`components`[``"schemas"``][``"assets"``]\>

assets - List of assets.

##### Parameters

| Name | Type |
| :------ | :------ |
| `pagination?` | `PaginationOptions` |

##### Returns

`Promise`<`components`[``"schemas"``][``"assets"``]\>

List of assets.

#### Defined in

[BlockFrostAPI.ts:287](https://github.com/blockfrost/blockfrost-js/blob/ced2dac/src/BlockFrostAPI.ts#L287)

___

### assetsAddresses

• **assetsAddresses**: (`asset`: `string`, `pagination?`: `PaginationOptions`) => `Promise`<`components`[``"schemas"``][``"asset_addresses"``]\>

#### Type declaration

▸ (`asset`, `pagination?`): `Promise`<`components`[``"schemas"``][``"asset_addresses"``]\>

assetsAddresses - List of a addresses containing a specific asset.

##### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `asset` | `string` | Concatenation of the policy_id and hex-encoded asset_name |
| `pagination?` | `PaginationOptions` | - |

##### Returns

`Promise`<`components`[``"schemas"``][``"asset_addresses"``]\>

List of a addresses containing a specific asset.

#### Defined in

[BlockFrostAPI.ts:341](https://github.com/blockfrost/blockfrost-js/blob/ced2dac/src/BlockFrostAPI.ts#L341)

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

[BlockFrostAPI.ts:296](https://github.com/blockfrost/blockfrost-js/blob/ced2dac/src/BlockFrostAPI.ts#L296)

___

### assetsHistory

• **assetsHistory**: (`asset`: `string`, `pagination?`: `PaginationOptions`) => `Promise`<`components`[``"schemas"``][``"asset_history"``]\>

#### Type declaration

▸ (`asset`, `pagination?`): `Promise`<`components`[``"schemas"``][``"asset_history"``]\>

assetsHistory - History of a specific asset.

##### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `asset` | `string` | Concatenation of the policy_id and hex-encoded asset_name |
| `pagination?` | `PaginationOptions` | - |

##### Returns

`Promise`<`components`[``"schemas"``][``"asset_history"``]\>

History of a specific asset.

#### Defined in

[BlockFrostAPI.ts:305](https://github.com/blockfrost/blockfrost-js/blob/ced2dac/src/BlockFrostAPI.ts#L305)

___

### assetsHistoryAll

• **assetsHistoryAll**: (`asset`: `string`, `order`: ``"asc"`` \| ``"desc"``, `batchSize`: `number`) => `Promise`<`components`[``"schemas"``][``"asset_history"``]\>

#### Type declaration

▸ (`asset`, `order`, `batchSize?`): `Promise`<`components`[``"schemas"``][``"asset_history"``]\>

assetsHistoryAll - Whole history of a specific asset.

##### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `asset` | `string` | Concatenation of the policy_id and hex-encoded asset_name |
| `order` | ``"asc"`` \| ``"desc"`` | - |
| `batchSize` | `number` | - |

##### Returns

`Promise`<`components`[``"schemas"``][``"asset_history"``]\>

History of a specific asset.

#### Defined in

[BlockFrostAPI.ts:314](https://github.com/blockfrost/blockfrost-js/blob/ced2dac/src/BlockFrostAPI.ts#L314)

___

### assetsPolicyById

• **assetsPolicyById**: (`policy`: `string`, `pagination?`: `PaginationOptions`) => `Promise`<`components`[``"schemas"``][``"asset_addresses"``]\>

#### Type declaration

▸ (`policy`, `pagination?`): `Promise`<`components`[``"schemas"``][``"asset_addresses"``]\>

assetsPolicyById - List of asset minted under a specific policy.

##### Parameters

| Name | Type |
| :------ | :------ |
| `policy` | `string` |
| `pagination?` | `PaginationOptions` |

##### Returns

`Promise`<`components`[``"schemas"``][``"asset_addresses"``]\>

List of asset minted under a specific policy.

#### Defined in

[BlockFrostAPI.ts:350](https://github.com/blockfrost/blockfrost-js/blob/ced2dac/src/BlockFrostAPI.ts#L350)

___

### assetsPolicyByIdAll

• **assetsPolicyByIdAll**: (`policy`: `string`, `order`: ``"asc"`` \| ``"desc"``, `batchSize`: `number`) => `Promise`<`components`[``"schemas"``][``"asset_addresses"``]\>

#### Type declaration

▸ (`policy`, `order`, `batchSize?`): `Promise`<`components`[``"schemas"``][``"asset_addresses"``]\>

assetsPolicyByIdAll - List of all assets minted under a specific policy.

##### Parameters

| Name | Type |
| :------ | :------ |
| `policy` | `string` |
| `order` | ``"asc"`` \| ``"desc"`` |
| `batchSize` | `number` |

##### Returns

`Promise`<`components`[``"schemas"``][``"asset_addresses"``]\>

List of asset minted under a specific policy.

#### Defined in

[BlockFrostAPI.ts:359](https://github.com/blockfrost/blockfrost-js/blob/ced2dac/src/BlockFrostAPI.ts#L359)

___

### assetsTransactions

• **assetsTransactions**: (`asset`: `string`, `pagination?`: `PaginationOptions`) => `Promise`<`components`[``"schemas"``][``"asset_transactions"``]\>

#### Type declaration

▸ (`asset`, `pagination?`): `Promise`<`components`[``"schemas"``][``"asset_transactions"``]\>

assetsTransactions - List of a specific asset transactions.

##### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `asset` | `string` | Concatenation of the policy_id and hex-encoded asset_name |
| `pagination?` | `PaginationOptions` | - |

##### Returns

`Promise`<`components`[``"schemas"``][``"asset_transactions"``]\>

List of a specific asset transactions.

#### Defined in

[BlockFrostAPI.ts:332](https://github.com/blockfrost/blockfrost-js/blob/ced2dac/src/BlockFrostAPI.ts#L332)

___

### assetsTxs

• **assetsTxs**: (`asset`: `string`, `pagination?`: `PaginationOptions`) => `Promise`<`components`[``"schemas"``][``"asset_txs"``]\>

#### Type declaration

▸ (`asset`, `pagination?`): `Promise`<`components`[``"schemas"``][``"asset_txs"``]\>

assetsTxs - List of a specific asset transactions.

##### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `asset` | `string` | Concatenation of the policy_id and hex-encoded asset_name |
| `pagination?` | `PaginationOptions` | - |

##### Returns

`Promise`<`components`[``"schemas"``][``"asset_txs"``]\>

List of a specific asset transactions.

#### Defined in

[BlockFrostAPI.ts:323](https://github.com/blockfrost/blockfrost-js/blob/ced2dac/src/BlockFrostAPI.ts#L323)

___

### axiosInstance

• **axiosInstance**: `AxiosInstance`

#### Defined in

[BlockFrostAPI.ts:124](https://github.com/blockfrost/blockfrost-js/blob/ced2dac/src/BlockFrostAPI.ts#L124)

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

[BlockFrostAPI.ts:440](https://github.com/blockfrost/blockfrost-js/blob/ced2dac/src/BlockFrostAPI.ts#L440)

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

[BlockFrostAPI.ts:448](https://github.com/blockfrost/blockfrost-js/blob/ced2dac/src/BlockFrostAPI.ts#L448)

___

### blocksNext

• **blocksNext**: (`hashOrNumber`: `HashOrNumber`, `pagination?`: `PaginationOptions`) => `Promise`<`components`[``"schemas"``][``"block_content_array"``]\>

#### Type declaration

▸ (`hashOrNumber`, `pagination?`): `Promise`<`components`[``"schemas"``][``"block_content_array"``]\>

blocksNext

##### Parameters

| Name | Type |
| :------ | :------ |
| `hashOrNumber` | `HashOrNumber` |
| `pagination?` | `PaginationOptions` |

##### Returns

`Promise`<`components`[``"schemas"``][``"block_content_array"``]\>

xxx

#### Defined in

[BlockFrostAPI.ts:457](https://github.com/blockfrost/blockfrost-js/blob/ced2dac/src/BlockFrostAPI.ts#L457)

___

### blocksPrevious

• **blocksPrevious**: (`hashOrNumber`: `HashOrNumber`, `pagination?`: `PaginationOptions`) => `Promise`<`components`[``"schemas"``][``"block_content_array"``]\>

#### Type declaration

▸ (`hashOrNumber`, `pagination?`): `Promise`<`components`[``"schemas"``][``"block_content_array"``]\>

blockPrevious

##### Parameters

| Name | Type |
| :------ | :------ |
| `hashOrNumber` | `HashOrNumber` |
| `pagination?` | `PaginationOptions` |

##### Returns

`Promise`<`components`[``"schemas"``][``"block_content_array"``]\>

xxx

#### Defined in

[BlockFrostAPI.ts:466](https://github.com/blockfrost/blockfrost-js/blob/ced2dac/src/BlockFrostAPI.ts#L466)

___

### blocksTxs

• **blocksTxs**: (`hashOrNumber`: `HashOrNumber`, `pagination?`: `PaginationOptions`) => `Promise`<`components`[``"schemas"``][``"block_content_txs"``]\>

#### Type declaration

▸ (`hashOrNumber`, `pagination?`): `Promise`<`components`[``"schemas"``][``"block_content_txs"``]\>

addressesUtxos

##### Parameters

| Name | Type |
| :------ | :------ |
| `hashOrNumber` | `HashOrNumber` |
| `pagination?` | `PaginationOptions` |

##### Returns

`Promise`<`components`[``"schemas"``][``"block_content_txs"``]\>

xxx

#### Defined in

[BlockFrostAPI.ts:475](https://github.com/blockfrost/blockfrost-js/blob/ced2dac/src/BlockFrostAPI.ts#L475)

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

[BlockFrostAPI.ts:484](https://github.com/blockfrost/blockfrost-js/blob/ced2dac/src/BlockFrostAPI.ts#L484)

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

[BlockFrostAPI.ts:493](https://github.com/blockfrost/blockfrost-js/blob/ced2dac/src/BlockFrostAPI.ts#L493)

___

### epochsBlocks

• **epochsBlocks**: (`number`: `number`, `pagination?`: `PaginationOptions`) => `Promise`<`components`[``"schemas"``][``"epoch_block_content"``]\>

#### Type declaration

▸ (`number`, `pagination?`): `Promise`<`components`[``"schemas"``][``"epoch_block_content"``]\>

epochsBlocks

##### Parameters

| Name | Type |
| :------ | :------ |
| `number` | `number` |
| `pagination?` | `PaginationOptions` |

##### Returns

`Promise`<`components`[``"schemas"``][``"epoch_block_content"``]\>

xxx

#### Defined in

[BlockFrostAPI.ts:502](https://github.com/blockfrost/blockfrost-js/blob/ced2dac/src/BlockFrostAPI.ts#L502)

___

### epochsBlocksByPoolId

• **epochsBlocksByPoolId**: (`number`: `number`, `poolId`: `string`, `pagination?`: `PaginationOptions`) => `Promise`<`components`[``"schemas"``][``"epoch_stake_pool_content"``]\>

#### Type declaration

▸ (`number`, `poolId`, `pagination?`): `Promise`<`components`[``"schemas"``][``"epoch_stake_pool_content"``]\>

epochsBlocksByPoolId

##### Parameters

| Name | Type |
| :------ | :------ |
| `number` | `number` |
| `poolId` | `string` |
| `pagination?` | `PaginationOptions` |

##### Returns

`Promise`<`components`[``"schemas"``][``"epoch_stake_pool_content"``]\>

xxx

#### Defined in

[BlockFrostAPI.ts:511](https://github.com/blockfrost/blockfrost-js/blob/ced2dac/src/BlockFrostAPI.ts#L511)

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

[BlockFrostAPI.ts:519](https://github.com/blockfrost/blockfrost-js/blob/ced2dac/src/BlockFrostAPI.ts#L519)

___

### epochsNext

• **epochsNext**: (`number`: `number`, `pagination?`: `PaginationOptions`) => `Promise`<`components`[``"schemas"``][``"epoch_content_array"``]\>

#### Type declaration

▸ (`number`, `pagination?`): `Promise`<`components`[``"schemas"``][``"epoch_content_array"``]\>

epochsNext

##### Parameters

| Name | Type |
| :------ | :------ |
| `number` | `number` |
| `pagination?` | `PaginationOptions` |

##### Returns

`Promise`<`components`[``"schemas"``][``"epoch_content_array"``]\>

xxx

#### Defined in

[BlockFrostAPI.ts:528](https://github.com/blockfrost/blockfrost-js/blob/ced2dac/src/BlockFrostAPI.ts#L528)

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

[BlockFrostAPI.ts:537](https://github.com/blockfrost/blockfrost-js/blob/ced2dac/src/BlockFrostAPI.ts#L537)

___

### epochsPrevious

• **epochsPrevious**: (`number`: `number`, `pagination?`: `PaginationOptions`) => `Promise`<`components`[``"schemas"``][``"epoch_content_array"``]\>

#### Type declaration

▸ (`number`, `pagination?`): `Promise`<`components`[``"schemas"``][``"epoch_content_array"``]\>

epochsPrevious

##### Parameters

| Name | Type |
| :------ | :------ |
| `number` | `number` |
| `pagination?` | `PaginationOptions` |

##### Returns

`Promise`<`components`[``"schemas"``][``"epoch_content_array"``]\>

xxx

#### Defined in

[BlockFrostAPI.ts:546](https://github.com/blockfrost/blockfrost-js/blob/ced2dac/src/BlockFrostAPI.ts#L546)

___

### epochsStakes

• **epochsStakes**: (`number`: `number`, `pagination?`: `PaginationOptions`) => `Promise`<`components`[``"schemas"``][``"epoch_stake_content"``]\>

#### Type declaration

▸ (`number`, `pagination?`): `Promise`<`components`[``"schemas"``][``"epoch_stake_content"``]\>

epochsStakes

##### Parameters

| Name | Type |
| :------ | :------ |
| `number` | `number` |
| `pagination?` | `PaginationOptions` |

##### Returns

`Promise`<`components`[``"schemas"``][``"epoch_stake_content"``]\>

xxx

#### Defined in

[BlockFrostAPI.ts:555](https://github.com/blockfrost/blockfrost-js/blob/ced2dac/src/BlockFrostAPI.ts#L555)

___

### epochsStakesByPoolId

• **epochsStakesByPoolId**: (`number`: `number`, `poolId`: `string`, `pagination?`: `PaginationOptions`) => `Promise`<`components`[``"schemas"``][``"epoch_block_content"``]\>

#### Type declaration

▸ (`number`, `poolId`, `pagination?`): `Promise`<`components`[``"schemas"``][``"epoch_block_content"``]\>

epochsStakesByPoolId

##### Parameters

| Name | Type |
| :------ | :------ |
| `number` | `number` |
| `poolId` | `string` |
| `pagination?` | `PaginationOptions` |

##### Returns

`Promise`<`components`[``"schemas"``][``"epoch_block_content"``]\>

xxx

#### Defined in

[BlockFrostAPI.ts:564](https://github.com/blockfrost/blockfrost-js/blob/ced2dac/src/BlockFrostAPI.ts#L564)

___

### genesis

• **genesis**: () => `Promise`<`components`[``"schemas"``][``"genesis_content"``]\>

#### Type declaration

▸ (): `Promise`<`components`[``"schemas"``][``"genesis_content"``]\>

ledger

##### Returns

`Promise`<`components`[``"schemas"``][``"genesis_content"``]\>

xxx

#### Defined in

[BlockFrostAPI.ts:588](https://github.com/blockfrost/blockfrost-js/blob/ced2dac/src/BlockFrostAPI.ts#L588)

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

[BlockFrostAPI.ts:572](https://github.com/blockfrost/blockfrost-js/blob/ced2dac/src/BlockFrostAPI.ts#L572)

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

[BlockFrostAPI.ts:580](https://github.com/blockfrost/blockfrost-js/blob/ced2dac/src/BlockFrostAPI.ts#L580)

___

### metadataTxsLabel

• **metadataTxsLabel**: (`label`: `string`, `pagination?`: `PaginationOptions`) => `Promise`<`components`[``"schemas"``][``"tx_metadata_labels"``]\>

#### Type declaration

▸ (`label`, `pagination?`): `Promise`<`components`[``"schemas"``][``"tx_metadata_labels"``]\>

metadataTxsLabel

##### Parameters

| Name | Type |
| :------ | :------ |
| `label` | `string` |
| `pagination?` | `PaginationOptions` |

##### Returns

`Promise`<`components`[``"schemas"``][``"tx_metadata_labels"``]\>

xxx

#### Defined in

[BlockFrostAPI.ts:597](https://github.com/blockfrost/blockfrost-js/blob/ced2dac/src/BlockFrostAPI.ts#L597)

___

### metadataTxsLabelCbor

• **metadataTxsLabelCbor**: (`label`: `string`, `pagination?`: `PaginationOptions`) => `Promise`<`components`[``"schemas"``][``"tx_metadata_label_cbor"``]\>

#### Type declaration

▸ (`label`, `pagination?`): `Promise`<`components`[``"schemas"``][``"tx_metadata_label_cbor"``]\>

metadataTxsLabelCbor

##### Parameters

| Name | Type |
| :------ | :------ |
| `label` | `string` |
| `pagination?` | `PaginationOptions` |

##### Returns

`Promise`<`components`[``"schemas"``][``"tx_metadata_label_cbor"``]\>

xxx

#### Defined in

[BlockFrostAPI.ts:606](https://github.com/blockfrost/blockfrost-js/blob/ced2dac/src/BlockFrostAPI.ts#L606)

___

### metadataTxsLabels

• **metadataTxsLabels**: (`pagination?`: `PaginationOptions`) => `Promise`<`components`[``"schemas"``][``"tx_metadata_label_json"``]\>

#### Type declaration

▸ (`pagination?`): `Promise`<`components`[``"schemas"``][``"tx_metadata_label_json"``]\>

metadataTxsLabels

##### Parameters

| Name | Type |
| :------ | :------ |
| `pagination?` | `PaginationOptions` |

##### Returns

`Promise`<`components`[``"schemas"``][``"tx_metadata_label_json"``]\>

xxx

#### Defined in

[BlockFrostAPI.ts:614](https://github.com/blockfrost/blockfrost-js/blob/ced2dac/src/BlockFrostAPI.ts#L614)

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

[BlockFrostAPI.ts:622](https://github.com/blockfrost/blockfrost-js/blob/ced2dac/src/BlockFrostAPI.ts#L622)

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

[BlockFrostAPI.ts:630](https://github.com/blockfrost/blockfrost-js/blob/ced2dac/src/BlockFrostAPI.ts#L630)

___

### nutlinkAddress

• **nutlinkAddress**: (`address`: `string`) => `Promise`<`components`[``"schemas"``][``"nutlink_address"``]\>

#### Type declaration

▸ (`address`): `Promise`<`components`[``"schemas"``][``"nutlink_address"``]\>

nutlinkAddress

##### Parameters

| Name | Type |
| :------ | :------ |
| `address` | `string` |

##### Returns

`Promise`<`components`[``"schemas"``][``"nutlink_address"``]\>

xxx

#### Defined in

[BlockFrostAPI.ts:638](https://github.com/blockfrost/blockfrost-js/blob/ced2dac/src/BlockFrostAPI.ts#L638)

___

### nutlinkAddressTicker

• **nutlinkAddressTicker**: (`address`: `string`, `ticker`: `string`, `pagination?`: `PaginationOptions`) => `Promise`<`components`[``"schemas"``][``"nutlink_address_ticker"``]\>

#### Type declaration

▸ (`address`, `ticker`, `pagination?`): `Promise`<`components`[``"schemas"``][``"nutlink_address_ticker"``]\>

nutlinkAddressTicker

##### Parameters

| Name | Type |
| :------ | :------ |
| `address` | `string` |
| `ticker` | `string` |
| `pagination?` | `PaginationOptions` |

##### Returns

`Promise`<`components`[``"schemas"``][``"nutlink_address_ticker"``]\>

xxx

#### Defined in

[BlockFrostAPI.ts:646](https://github.com/blockfrost/blockfrost-js/blob/ced2dac/src/BlockFrostAPI.ts#L646)

___

### nutlinkAddressTickerAll

• **nutlinkAddressTickerAll**: (`address`: `string`, `ticker`: `string`, `order`: ``"asc"`` \| ``"desc"``, `batchSize`: `number`) => `Promise`<`components`[``"schemas"``][``"nutlink_address_ticker"``]\>

#### Type declaration

▸ (`address`, `ticker`, `order`, `batchSize?`): `Promise`<`components`[``"schemas"``][``"nutlink_address_ticker"``]\>

nutlinkAddressTickerAll

##### Parameters

| Name | Type |
| :------ | :------ |
| `address` | `string` |
| `ticker` | `string` |
| `order` | ``"asc"`` \| ``"desc"`` |
| `batchSize` | `number` |

##### Returns

`Promise`<`components`[``"schemas"``][``"nutlink_address_ticker"``]\>

xxx

#### Defined in

[BlockFrostAPI.ts:670](https://github.com/blockfrost/blockfrost-js/blob/ced2dac/src/BlockFrostAPI.ts#L670)

___

### nutlinkAddressTickers

• **nutlinkAddressTickers**: (`address`: `string`, `pagination?`: `PaginationOptions`) => `Promise`<`components`[``"schemas"``][``"nutlink_address_tickers"``]\>

#### Type declaration

▸ (`address`, `pagination?`): `Promise`<`components`[``"schemas"``][``"nutlink_address_tickers"``]\>

nutlinkAddressTickers

##### Parameters

| Name | Type |
| :------ | :------ |
| `address` | `string` |
| `pagination?` | `PaginationOptions` |

##### Returns

`Promise`<`components`[``"schemas"``][``"nutlink_address_tickers"``]\>

xxx

#### Defined in

[BlockFrostAPI.ts:654](https://github.com/blockfrost/blockfrost-js/blob/ced2dac/src/BlockFrostAPI.ts#L654)

___

### nutlinkAddressTickersAll

• **nutlinkAddressTickersAll**: (`address`: `string`, `order`: ``"asc"`` \| ``"desc"``, `batchSize`: `number`) => `Promise`<`components`[``"schemas"``][``"nutlink_address_tickers"``]\>

#### Type declaration

▸ (`address`, `order`, `batchSize?`): `Promise`<`components`[``"schemas"``][``"nutlink_address_tickers"``]\>

nutlinkAddressTickersAll

##### Parameters

| Name | Type |
| :------ | :------ |
| `address` | `string` |
| `order` | ``"asc"`` \| ``"desc"`` |
| `batchSize` | `number` |

##### Returns

`Promise`<`components`[``"schemas"``][``"nutlink_address_tickers"``]\>

xxx

#### Defined in

[BlockFrostAPI.ts:662](https://github.com/blockfrost/blockfrost-js/blob/ced2dac/src/BlockFrostAPI.ts#L662)

___

### nutlinkTickers

• **nutlinkTickers**: (`ticker`: `string`, `pagination?`: `PaginationOptions`) => `Promise`<`components`[``"schemas"``][``"nutlink_tickers_ticker"``]\>

#### Type declaration

▸ (`ticker`, `pagination?`): `Promise`<`components`[``"schemas"``][``"nutlink_tickers_ticker"``]\>

nutlinkTickers

##### Parameters

| Name | Type |
| :------ | :------ |
| `ticker` | `string` |
| `pagination?` | `PaginationOptions` |

##### Returns

`Promise`<`components`[``"schemas"``][``"nutlink_tickers_ticker"``]\>

xxx

#### Defined in

[BlockFrostAPI.ts:678](https://github.com/blockfrost/blockfrost-js/blob/ced2dac/src/BlockFrostAPI.ts#L678)

___

### nutlinkTickersAll

• **nutlinkTickersAll**: (`ticker`: `string`, `order`: ``"asc"`` \| ``"desc"``, `batchSize`: `number`) => `Promise`<`components`[``"schemas"``][``"nutlink_tickers_ticker"``]\>

#### Type declaration

▸ (`ticker`, `order`, `batchSize?`): `Promise`<`components`[``"schemas"``][``"nutlink_tickers_ticker"``]\>

nutlinkTickersAll

##### Parameters

| Name | Type |
| :------ | :------ |
| `ticker` | `string` |
| `order` | ``"asc"`` \| ``"desc"`` |
| `batchSize` | `number` |

##### Returns

`Promise`<`components`[``"schemas"``][``"nutlink_tickers_ticker"``]\>

xxx

#### Defined in

[BlockFrostAPI.ts:686](https://github.com/blockfrost/blockfrost-js/blob/ced2dac/src/BlockFrostAPI.ts#L686)

___

### options

• **options**: `ValidatedOptions`

#### Defined in

[BlockFrostAPI.ts:123](https://github.com/blockfrost/blockfrost-js/blob/ced2dac/src/BlockFrostAPI.ts#L123)

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

[BlockFrostAPI.ts:703](https://github.com/blockfrost/blockfrost-js/blob/ced2dac/src/BlockFrostAPI.ts#L703)

___

### pools

• **pools**: (`pagination?`: `PaginationOptions`) => `Promise`<`components`[``"schemas"``][``"pool_list"``]\>

#### Type declaration

▸ (`pagination?`): `Promise`<`components`[``"schemas"``][``"pool_list"``]\>

pools

##### Parameters

| Name | Type |
| :------ | :------ |
| `pagination?` | `PaginationOptions` |

##### Returns

`Promise`<`components`[``"schemas"``][``"pool_list"``]\>

xxx

#### Defined in

[BlockFrostAPI.ts:694](https://github.com/blockfrost/blockfrost-js/blob/ced2dac/src/BlockFrostAPI.ts#L694)

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

[BlockFrostAPI.ts:712](https://github.com/blockfrost/blockfrost-js/blob/ced2dac/src/BlockFrostAPI.ts#L712)

___

### poolsByIdBlocks

• **poolsByIdBlocks**: (`poolId`: `string`, `pagination?`: `PaginationOptions`) => `Promise`<`components`[``"schemas"``][``"pool_blocks"``]\>

#### Type declaration

▸ (`poolId`, `pagination?`): `Promise`<`components`[``"schemas"``][``"pool_blocks"``]\>

poolsByIdBlocks

##### Parameters

| Name | Type |
| :------ | :------ |
| `poolId` | `string` |
| `pagination?` | `PaginationOptions` |

##### Returns

`Promise`<`components`[``"schemas"``][``"pool_blocks"``]\>

xxx

#### Defined in

[BlockFrostAPI.ts:721](https://github.com/blockfrost/blockfrost-js/blob/ced2dac/src/BlockFrostAPI.ts#L721)

___

### poolsByIdDelegators

• **poolsByIdDelegators**: (`poolId`: `string`, `pagination?`: `PaginationOptions`) => `Promise`<`components`[``"schemas"``][``"pool_delegators"``]\>

#### Type declaration

▸ (`poolId`, `pagination?`): `Promise`<`components`[``"schemas"``][``"pool_delegators"``]\>

poolsByIdDelegators

##### Parameters

| Name | Type |
| :------ | :------ |
| `poolId` | `string` |
| `pagination?` | `PaginationOptions` |

##### Returns

`Promise`<`components`[``"schemas"``][``"pool_delegators"``]\>

xxx

#### Defined in

[BlockFrostAPI.ts:730](https://github.com/blockfrost/blockfrost-js/blob/ced2dac/src/BlockFrostAPI.ts#L730)

___

### poolsByIdHistory

• **poolsByIdHistory**: (`poolId`: `string`, `pagination?`: `PaginationOptions`) => `Promise`<`components`[``"schemas"``][``"pool_history"``]\>

#### Type declaration

▸ (`poolId`, `pagination?`): `Promise`<`components`[``"schemas"``][``"pool_history"``]\>

poolsByIdHistory

##### Parameters

| Name | Type |
| :------ | :------ |
| `poolId` | `string` |
| `pagination?` | `PaginationOptions` |

##### Returns

`Promise`<`components`[``"schemas"``][``"pool_history"``]\>

xxx

#### Defined in

[BlockFrostAPI.ts:739](https://github.com/blockfrost/blockfrost-js/blob/ced2dac/src/BlockFrostAPI.ts#L739)

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

[BlockFrostAPI.ts:748](https://github.com/blockfrost/blockfrost-js/blob/ced2dac/src/BlockFrostAPI.ts#L748)

___

### poolsByIdUpdates

• **poolsByIdUpdates**: (`poolId`: `string`, `pagination?`: `PaginationOptions`) => `Promise`<`components`[``"schemas"``][``"pool_updates"``]\>

#### Type declaration

▸ (`poolId`, `pagination?`): `Promise`<`components`[``"schemas"``][``"pool_updates"``]\>

poolsByIdUpdates

##### Parameters

| Name | Type |
| :------ | :------ |
| `poolId` | `string` |
| `pagination?` | `PaginationOptions` |

##### Returns

`Promise`<`components`[``"schemas"``][``"pool_updates"``]\>

xxx

#### Defined in

[BlockFrostAPI.ts:757](https://github.com/blockfrost/blockfrost-js/blob/ced2dac/src/BlockFrostAPI.ts#L757)

___

### poolsRetired

• **poolsRetired**: (`pagination?`: `PaginationOptions`) => `Promise`<`components`[``"schemas"``][``"pool_list_retire"``]\>

#### Type declaration

▸ (`pagination?`): `Promise`<`components`[``"schemas"``][``"pool_list_retire"``]\>

poolsRetired

##### Parameters

| Name | Type |
| :------ | :------ |
| `pagination?` | `PaginationOptions` |

##### Returns

`Promise`<`components`[``"schemas"``][``"pool_list_retire"``]\>

xxx

#### Defined in

[BlockFrostAPI.ts:765](https://github.com/blockfrost/blockfrost-js/blob/ced2dac/src/BlockFrostAPI.ts#L765)

___

### poolsRetiring

• **poolsRetiring**: (`pagination?`: `PaginationOptions`) => `Promise`<`components`[``"schemas"``][``"pool_list_retire"``]\>

#### Type declaration

▸ (`pagination?`): `Promise`<`components`[``"schemas"``][``"pool_list_retire"``]\>

poolsRetiring

##### Parameters

| Name | Type |
| :------ | :------ |
| `pagination?` | `PaginationOptions` |

##### Returns

`Promise`<`components`[``"schemas"``][``"pool_list_retire"``]\>

xxx

#### Defined in

[BlockFrostAPI.ts:773](https://github.com/blockfrost/blockfrost-js/blob/ced2dac/src/BlockFrostAPI.ts#L773)

___

### projectId

• `Optional` **projectId**: `string`

#### Defined in

[BlockFrostAPI.ts:121](https://github.com/blockfrost/blockfrost-js/blob/ced2dac/src/BlockFrostAPI.ts#L121)

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

[BlockFrostAPI.ts:781](https://github.com/blockfrost/blockfrost-js/blob/ced2dac/src/BlockFrostAPI.ts#L781)

___

### txSubmit

• **txSubmit**: (`transaction`: `Uint8Array` \| `string`) => `Promise`<`string`\>

#### Type declaration

▸ (`transaction`): `Promise`<`string`\>

txSubmit

##### Parameters

| Name | Type |
| :------ | :------ |
| `transaction` | `Uint8Array` \| `string` |

##### Returns

`Promise`<`string`\>

xxx

#### Defined in

[BlockFrostAPI.ts:880](https://github.com/blockfrost/blockfrost-js/blob/ced2dac/src/BlockFrostAPI.ts#L880)

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

[BlockFrostAPI.ts:790](https://github.com/blockfrost/blockfrost-js/blob/ced2dac/src/BlockFrostAPI.ts#L790)

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

[BlockFrostAPI.ts:808](https://github.com/blockfrost/blockfrost-js/blob/ced2dac/src/BlockFrostAPI.ts#L808)

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

[BlockFrostAPI.ts:871](https://github.com/blockfrost/blockfrost-js/blob/ced2dac/src/BlockFrostAPI.ts#L871)

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

[BlockFrostAPI.ts:799](https://github.com/blockfrost/blockfrost-js/blob/ced2dac/src/BlockFrostAPI.ts#L799)

___

### txsMirs

• **txsMirs**: (`hash`: `string`) => `Promise`<`components`[``"schemas"``][``"tx_content_mirs"``]\>

#### Type declaration

▸ (`hash`): `Promise`<`components`[``"schemas"``][``"tx_content_mirs"``]\>

txsMirs

##### Parameters

| Name | Type |
| :------ | :------ |
| `hash` | `string` |

##### Returns

`Promise`<`components`[``"schemas"``][``"tx_content_mirs"``]\>

xxx

#### Defined in

[BlockFrostAPI.ts:862](https://github.com/blockfrost/blockfrost-js/blob/ced2dac/src/BlockFrostAPI.ts#L862)

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

[BlockFrostAPI.ts:817](https://github.com/blockfrost/blockfrost-js/blob/ced2dac/src/BlockFrostAPI.ts#L817)

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

[BlockFrostAPI.ts:826](https://github.com/blockfrost/blockfrost-js/blob/ced2dac/src/BlockFrostAPI.ts#L826)

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

[BlockFrostAPI.ts:835](https://github.com/blockfrost/blockfrost-js/blob/ced2dac/src/BlockFrostAPI.ts#L835)

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

[BlockFrostAPI.ts:844](https://github.com/blockfrost/blockfrost-js/blob/ced2dac/src/BlockFrostAPI.ts#L844)

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

[BlockFrostAPI.ts:853](https://github.com/blockfrost/blockfrost-js/blob/ced2dac/src/BlockFrostAPI.ts#L853)

___

### userAgent

• `Optional` **userAgent**: `string`

#### Defined in

[BlockFrostAPI.ts:122](https://github.com/blockfrost/blockfrost-js/blob/ced2dac/src/BlockFrostAPI.ts#L122)
