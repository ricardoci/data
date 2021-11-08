### constructor

• **new BlockFrostAPI**(`options?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `options?` | `Options` |

#### Defined in

[src/BlockFrostAPI.ts:140](https://github.com/blockfrost/blockfrost-js/blob/9b3f200/src/BlockFrostAPI.ts#L140)

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

[src/BlockFrostAPI.ts:167](https://github.com/blockfrost/blockfrost-js/blob/9b3f200/src/BlockFrostAPI.ts#L167)

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

[src/BlockFrostAPI.ts:284](https://github.com/blockfrost/blockfrost-js/blob/9b3f200/src/BlockFrostAPI.ts#L284)

___

### accountsAddressesAll

• **accountsAddressesAll**: (`stakeAddress`: `string`, `allMethodOptions?`: `AllMethodOptions`) => `Promise`<`components`[``"schemas"``][``"account_addresses_content"``]\>

#### Type declaration

▸ (`stakeAddress`, `allMethodOptions?`): `Promise`<`components`[``"schemas"``][``"account_addresses_content"``]\>

accountsAddressesAll - Obtain information about all addresses of a specific account.

##### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `stakeAddress` | `string` | Bech32 stake address |
| `allMethodOptions?` | `AllMethodOptions` | - |

##### Returns

`Promise`<`components`[``"schemas"``][``"account_addresses_content"``]\>

Information about the addresses of a specific account.

#### Defined in

[src/BlockFrostAPI.ts:293](https://github.com/blockfrost/blockfrost-js/blob/9b3f200/src/BlockFrostAPI.ts#L293)

___

### accountsAddressesAssets

• **accountsAddressesAssets**: (`stakeAddress`: `string`, `pagination?`: `PaginationOptions`) => `Promise`<`components`[``"schemas"``][``"account_addresses_assets"``]\>

#### Type declaration

▸ (`stakeAddress`, `pagination?`): `Promise`<`components`[``"schemas"``][``"account_addresses_assets"``]\>

accountsAddressesAssets - Obtain information about assets associated with addresses of a specific account.

##### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `stakeAddress` | `string` | Bech32 stake address |
| `pagination?` | `PaginationOptions` | - |

##### Returns

`Promise`<`components`[``"schemas"``][``"account_addresses_assets"``]\>

Assets associated with the account addresses

#### Defined in

[src/BlockFrostAPI.ts:302](https://github.com/blockfrost/blockfrost-js/blob/9b3f200/src/BlockFrostAPI.ts#L302)

___

### accountsAddressesAssetsAll

• **accountsAddressesAssetsAll**: (`stakeAddress`: `string`, `allMethodOptions?`: `AllMethodOptions`) => `Promise`<`components`[``"schemas"``][``"account_addresses_assets"``]\>

#### Type declaration

▸ (`stakeAddress`, `allMethodOptions?`): `Promise`<`components`[``"schemas"``][``"account_addresses_assets"``]\>

accountsAddressesAssets - Obtain information about assets associated with addresses of a specific account.

##### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `stakeAddress` | `string` | Bech32 stake address |
| `allMethodOptions?` | `AllMethodOptions` | - |

##### Returns

`Promise`<`components`[``"schemas"``][``"account_addresses_assets"``]\>

Assets associated with the account addresses

#### Defined in

[src/BlockFrostAPI.ts:311](https://github.com/blockfrost/blockfrost-js/blob/9b3f200/src/BlockFrostAPI.ts#L311)

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

[src/BlockFrostAPI.ts:176](https://github.com/blockfrost/blockfrost-js/blob/9b3f200/src/BlockFrostAPI.ts#L176)

___

### accountsDelegationsAll

• **accountsDelegationsAll**: (`stakeAddress`: `string`, `allMethodOptions?`: `AllMethodOptions`) => `Promise`<`components`[``"schemas"``][``"account_delegation_content"``]\>

#### Type declaration

▸ (`stakeAddress`, `allMethodOptions?`): `Promise`<`components`[``"schemas"``][``"account_delegation_content"``]\>

accountsDelegationsAll - Obtain information about all delegations of a specific account.

##### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `stakeAddress` | `string` | Bech32 stake address |
| `allMethodOptions?` | `AllMethodOptions` | - |

##### Returns

`Promise`<`components`[``"schemas"``][``"account_delegation_content"``]\>

Information about the delegation of a specific account.

#### Defined in

[src/BlockFrostAPI.ts:185](https://github.com/blockfrost/blockfrost-js/blob/9b3f200/src/BlockFrostAPI.ts#L185)

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

[src/BlockFrostAPI.ts:230](https://github.com/blockfrost/blockfrost-js/blob/9b3f200/src/BlockFrostAPI.ts#L230)

___

### accountsHistoryAll

• **accountsHistoryAll**: (`stakeAddress`: `string`, `allMethodOptions?`: `AllMethodOptions`) => `Promise`<`components`[``"schemas"``][``"account_history_content"``]\>

#### Type declaration

▸ (`stakeAddress`, `allMethodOptions?`): `Promise`<`components`[``"schemas"``][``"account_history_content"``]\>

accountsHistoryAll - Obtain information about whole history of a specific account.

##### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `stakeAddress` | `string` | Bech32 stake address |
| `allMethodOptions?` | `AllMethodOptions` | - |

##### Returns

`Promise`<`components`[``"schemas"``][``"account_history_content"``]\>

Information about the history of a specific account.

#### Defined in

[src/BlockFrostAPI.ts:239](https://github.com/blockfrost/blockfrost-js/blob/9b3f200/src/BlockFrostAPI.ts#L239)

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

[src/BlockFrostAPI.ts:266](https://github.com/blockfrost/blockfrost-js/blob/9b3f200/src/BlockFrostAPI.ts#L266)

___

### accountsMirsAll

• **accountsMirsAll**: (`stakeAddress`: `string`, `allMethodOptions?`: `AllMethodOptions`) => `Promise`<`components`[``"schemas"``][``"account_mir_content"``]\>

#### Type declaration

▸ (`stakeAddress`, `allMethodOptions?`): `Promise`<`components`[``"schemas"``][``"account_mir_content"``]\>

accountsMirsAll - Obtain information about all MIRs of a specific account.

##### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `stakeAddress` | `string` | Bech32 stake address |
| `allMethodOptions?` | `AllMethodOptions` | - |

##### Returns

`Promise`<`components`[``"schemas"``][``"account_mir_content"``]\>

Information about the MIRs of a specific account.

#### Defined in

[src/BlockFrostAPI.ts:275](https://github.com/blockfrost/blockfrost-js/blob/9b3f200/src/BlockFrostAPI.ts#L275)

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

[src/BlockFrostAPI.ts:194](https://github.com/blockfrost/blockfrost-js/blob/9b3f200/src/BlockFrostAPI.ts#L194)

___

### accountsRegistrationsAll

• **accountsRegistrationsAll**: (`stakeAddress`: `string`, `allMethodOptions?`: `AllMethodOptions`) => `Promise`<`components`[``"schemas"``][``"account_registration_content"``]\>

#### Type declaration

▸ (`stakeAddress`, `allMethodOptions?`): `Promise`<`components`[``"schemas"``][``"account_registration_content"``]\>

accountsRegistrationsAll - Obtain information about all registrations and deregistrations of a specific account.

##### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `stakeAddress` | `string` | Bech32 stake address |
| `allMethodOptions?` | `AllMethodOptions` | - |

##### Returns

`Promise`<`components`[``"schemas"``][``"account_registration_content"``]\>

Information about the registrations and deregistrations of a specific account.

#### Defined in

[src/BlockFrostAPI.ts:203](https://github.com/blockfrost/blockfrost-js/blob/9b3f200/src/BlockFrostAPI.ts#L203)

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

[src/BlockFrostAPI.ts:212](https://github.com/blockfrost/blockfrost-js/blob/9b3f200/src/BlockFrostAPI.ts#L212)

___

### accountsRewardsAll

• **accountsRewardsAll**: (`stakeAddress`: `string`, `allMethodOptions?`: `AllMethodOptions`) => `Promise`<`components`[``"schemas"``][``"account_reward_content"``]\>

#### Type declaration

▸ (`stakeAddress`, `allMethodOptions?`): `Promise`<`components`[``"schemas"``][``"account_reward_content"``]\>

accountsRewardsAll - Obtain information about whole history of a specific account.

##### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `stakeAddress` | `string` | Bech32 stake address |
| `allMethodOptions?` | `AllMethodOptions` | - |

##### Returns

`Promise`<`components`[``"schemas"``][``"account_reward_content"``]\>

Information about the history of a specific account.

#### Defined in

[src/BlockFrostAPI.ts:221](https://github.com/blockfrost/blockfrost-js/blob/9b3f200/src/BlockFrostAPI.ts#L221)

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

[src/BlockFrostAPI.ts:248](https://github.com/blockfrost/blockfrost-js/blob/9b3f200/src/BlockFrostAPI.ts#L248)

___

### accountsWithdrawalsAll

• **accountsWithdrawalsAll**: (`stakeAddress`: `string`, `allMethodOptions?`: `AllMethodOptions`) => `Promise`<`components`[``"schemas"``][``"account_withdrawal_content"``]\>

#### Type declaration

▸ (`stakeAddress`, `allMethodOptions?`): `Promise`<`components`[``"schemas"``][``"account_withdrawal_content"``]\>

accountsWithdrawalsAll - Obtain information about all withdrawals of a specific account.

##### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `stakeAddress` | `string` | Bech32 stake address |
| `allMethodOptions?` | `AllMethodOptions` | - |

##### Returns

`Promise`<`components`[``"schemas"``][``"account_withdrawal_content"``]\>

Information about the withdrawals of a specific account.

#### Defined in

[src/BlockFrostAPI.ts:257](https://github.com/blockfrost/blockfrost-js/blob/9b3f200/src/BlockFrostAPI.ts#L257)

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

[src/BlockFrostAPI.ts:391](https://github.com/blockfrost/blockfrost-js/blob/9b3f200/src/BlockFrostAPI.ts#L391)

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

[src/BlockFrostAPI.ts:400](https://github.com/blockfrost/blockfrost-js/blob/9b3f200/src/BlockFrostAPI.ts#L400)

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

[src/BlockFrostAPI.ts:409](https://github.com/blockfrost/blockfrost-js/blob/9b3f200/src/BlockFrostAPI.ts#L409)

___

### addressesTransactionsAll

• **addressesTransactionsAll**: (`address`: `string`, `allMethodOptions?`: `AllMethodOptions`, `additionalOptions?`: `AdditionalEndpointOptions`) => `Promise`<`components`[``"schemas"``][``"address_transactions_content"``]\>

#### Type declaration

▸ (`address`, `allMethodOptions?`, `additionalOptions?`): `Promise`<`components`[``"schemas"``][``"address_transactions_content"``]\>

addressesTransactionsAll

##### Parameters

| Name | Type |
| :------ | :------ |
| `address` | `string` |
| `allMethodOptions?` | `AllMethodOptions` |
| `additionalOptions?` | `AdditionalEndpointOptions` |

##### Returns

`Promise`<`components`[``"schemas"``][``"address_transactions_content"``]\>

xxx

#### Defined in

[src/BlockFrostAPI.ts:418](https://github.com/blockfrost/blockfrost-js/blob/9b3f200/src/BlockFrostAPI.ts#L418)

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

[src/BlockFrostAPI.ts:427](https://github.com/blockfrost/blockfrost-js/blob/9b3f200/src/BlockFrostAPI.ts#L427)

___

### addressesUtxosAll

• **addressesUtxosAll**: (`address`: `string`, `allMethodOptions?`: `AllMethodOptions`) => `Promise`<`components`[``"schemas"``][``"address_utxo_content"``]\>

#### Type declaration

▸ (`address`, `allMethodOptions?`): `Promise`<`components`[``"schemas"``][``"address_utxo_content"``]\>

addressesUtxosAll

##### Parameters

| Name | Type |
| :------ | :------ |
| `address` | `string` |
| `allMethodOptions?` | `AllMethodOptions` |

##### Returns

`Promise`<`components`[``"schemas"``][``"address_utxo_content"``]\>

xxx

#### Defined in

[src/BlockFrostAPI.ts:436](https://github.com/blockfrost/blockfrost-js/blob/9b3f200/src/BlockFrostAPI.ts#L436)

___

### apiUrl

• **apiUrl**: `string`

#### Defined in

[src/BlockFrostAPI.ts:134](https://github.com/blockfrost/blockfrost-js/blob/9b3f200/src/BlockFrostAPI.ts#L134)

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

[src/BlockFrostAPI.ts:319](https://github.com/blockfrost/blockfrost-js/blob/9b3f200/src/BlockFrostAPI.ts#L319)

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

[src/BlockFrostAPI.ts:364](https://github.com/blockfrost/blockfrost-js/blob/9b3f200/src/BlockFrostAPI.ts#L364)

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

[src/BlockFrostAPI.ts:328](https://github.com/blockfrost/blockfrost-js/blob/9b3f200/src/BlockFrostAPI.ts#L328)

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

[src/BlockFrostAPI.ts:337](https://github.com/blockfrost/blockfrost-js/blob/9b3f200/src/BlockFrostAPI.ts#L337)

___

### assetsHistoryAll

• **assetsHistoryAll**: (`asset`: `string`, `allMethodOptions?`: `AllMethodOptions`) => `Promise`<`components`[``"schemas"``][``"asset_history"``]\>

#### Type declaration

▸ (`asset`, `allMethodOptions?`): `Promise`<`components`[``"schemas"``][``"asset_history"``]\>

assetsHistoryAll - Whole history of a specific asset.

##### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `asset` | `string` | Concatenation of the policy_id and hex-encoded asset_name |
| `allMethodOptions?` | `AllMethodOptions` | - |

##### Returns

`Promise`<`components`[``"schemas"``][``"asset_history"``]\>

History of a specific asset.

#### Defined in

[src/BlockFrostAPI.ts:346](https://github.com/blockfrost/blockfrost-js/blob/9b3f200/src/BlockFrostAPI.ts#L346)

___

### assetsPolicyById

• **assetsPolicyById**: (`policy`: `string`, `pagination?`: `PaginationOptions`) => `Promise`<`components`[``"schemas"``][``"asset_policy"``]\>

#### Type declaration

▸ (`policy`, `pagination?`): `Promise`<`components`[``"schemas"``][``"asset_policy"``]\>

assetsPolicyById - List of asset minted under a specific policy.

##### Parameters

| Name | Type |
| :------ | :------ |
| `policy` | `string` |
| `pagination?` | `PaginationOptions` |

##### Returns

`Promise`<`components`[``"schemas"``][``"asset_policy"``]\>

List of asset minted under a specific policy.

#### Defined in

[src/BlockFrostAPI.ts:373](https://github.com/blockfrost/blockfrost-js/blob/9b3f200/src/BlockFrostAPI.ts#L373)

___

### assetsPolicyByIdAll

• **assetsPolicyByIdAll**: (`policy`: `string`, `allMethodOptions?`: `AllMethodOptions`) => `Promise`<`components`[``"schemas"``][``"asset_policy"``]\>

#### Type declaration

▸ (`policy`, `allMethodOptions?`): `Promise`<`components`[``"schemas"``][``"asset_policy"``]\>

assetsPolicyByIdAll - List of all assets minted under a specific policy.

##### Parameters

| Name | Type |
| :------ | :------ |
| `policy` | `string` |
| `allMethodOptions?` | `AllMethodOptions` |

##### Returns

`Promise`<`components`[``"schemas"``][``"asset_policy"``]\>

List of asset minted under a specific policy.

#### Defined in

[src/BlockFrostAPI.ts:382](https://github.com/blockfrost/blockfrost-js/blob/9b3f200/src/BlockFrostAPI.ts#L382)

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

[src/BlockFrostAPI.ts:355](https://github.com/blockfrost/blockfrost-js/blob/9b3f200/src/BlockFrostAPI.ts#L355)

___

### axiosInstance

• **axiosInstance**: `AxiosInstance`

#### Defined in

[src/BlockFrostAPI.ts:138](https://github.com/blockfrost/blockfrost-js/blob/9b3f200/src/BlockFrostAPI.ts#L138)

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

[src/BlockFrostAPI.ts:445](https://github.com/blockfrost/blockfrost-js/blob/9b3f200/src/BlockFrostAPI.ts#L445)

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

[src/BlockFrostAPI.ts:453](https://github.com/blockfrost/blockfrost-js/blob/9b3f200/src/BlockFrostAPI.ts#L453)

___

### blocksLatestTxs

• **blocksLatestTxs**: (`pagination?`: `PaginationOptions`) => `Promise`<`components`[``"schemas"``][``"block_content_txs"``]\>

#### Type declaration

▸ (`pagination?`): `Promise`<`components`[``"schemas"``][``"block_content_txs"``]\>

##### Parameters

| Name | Type |
| :------ | :------ |
| `pagination?` | `PaginationOptions` |

##### Returns

`Promise`<`components`[``"schemas"``][``"block_content_txs"``]\>

#### Defined in

[src/BlockFrostAPI.ts:454](https://github.com/blockfrost/blockfrost-js/blob/9b3f200/src/BlockFrostAPI.ts#L454)

___

### blocksLatestTxsAll

• **blocksLatestTxsAll**: (`allMethodOptions?`: `AllMethodOptions`) => `Promise`<`components`[``"schemas"``][``"block_content_txs"``]\>

#### Type declaration

▸ (`allMethodOptions?`): `Promise`<`components`[``"schemas"``][``"block_content_txs"``]\>

##### Parameters

| Name | Type |
| :------ | :------ |
| `allMethodOptions?` | `AllMethodOptions` |

##### Returns

`Promise`<`components`[``"schemas"``][``"block_content_txs"``]\>

#### Defined in

[src/BlockFrostAPI.ts:455](https://github.com/blockfrost/blockfrost-js/blob/9b3f200/src/BlockFrostAPI.ts#L455)

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

[src/BlockFrostAPI.ts:464](https://github.com/blockfrost/blockfrost-js/blob/9b3f200/src/BlockFrostAPI.ts#L464)

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

[src/BlockFrostAPI.ts:473](https://github.com/blockfrost/blockfrost-js/blob/9b3f200/src/BlockFrostAPI.ts#L473)

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

[src/BlockFrostAPI.ts:482](https://github.com/blockfrost/blockfrost-js/blob/9b3f200/src/BlockFrostAPI.ts#L482)

___

### blocksTxsAll

• **blocksTxsAll**: (`hashOrNumber`: `string` \| `number`, `allMethodOptions?`: `AllMethodOptions`) => `Promise`<`components`[``"schemas"``][``"block_content_txs"``]\>

#### Type declaration

▸ (`hashOrNumber`, `allMethodOptions?`): `Promise`<`components`[``"schemas"``][``"block_content_txs"``]\>

blocksTxsAll

##### Parameters

| Name | Type |
| :------ | :------ |
| `hashOrNumber` | `string` \| `number` |
| `allMethodOptions?` | `AllMethodOptions` |

##### Returns

`Promise`<`components`[``"schemas"``][``"block_content_txs"``]\>

xxx

#### Defined in

[src/BlockFrostAPI.ts:491](https://github.com/blockfrost/blockfrost-js/blob/9b3f200/src/BlockFrostAPI.ts#L491)

___

### deriveAddress

• **deriveAddress**: (`publicKey`: `string`, `addressIndex`: `number`, `type`: ``0`` \| ``1``) => { `address`: `string` ; `path`: `string`  }

#### Type declaration

▸ (`publicKey`, `addressIndex`, `type`): `Object`

deriveAddress

##### Parameters

| Name | Type |
| :------ | :------ |
| `publicKey` | `string` |
| `addressIndex` | `number` |
| `type` | ``0`` \| ``1`` |

##### Returns

`Object`

xxx

| Name | Type |
| :------ | :------ |
| `address` | `string` |
| `path` | `string` |

#### Defined in

[src/BlockFrostAPI.ts:938](https://github.com/blockfrost/blockfrost-js/blob/9b3f200/src/BlockFrostAPI.ts#L938)

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

[src/BlockFrostAPI.ts:500](https://github.com/blockfrost/blockfrost-js/blob/9b3f200/src/BlockFrostAPI.ts#L500)

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

[src/BlockFrostAPI.ts:509](https://github.com/blockfrost/blockfrost-js/blob/9b3f200/src/BlockFrostAPI.ts#L509)

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

[src/BlockFrostAPI.ts:518](https://github.com/blockfrost/blockfrost-js/blob/9b3f200/src/BlockFrostAPI.ts#L518)

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

[src/BlockFrostAPI.ts:526](https://github.com/blockfrost/blockfrost-js/blob/9b3f200/src/BlockFrostAPI.ts#L526)

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

[src/BlockFrostAPI.ts:535](https://github.com/blockfrost/blockfrost-js/blob/9b3f200/src/BlockFrostAPI.ts#L535)

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

[src/BlockFrostAPI.ts:544](https://github.com/blockfrost/blockfrost-js/blob/9b3f200/src/BlockFrostAPI.ts#L544)

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

[src/BlockFrostAPI.ts:553](https://github.com/blockfrost/blockfrost-js/blob/9b3f200/src/BlockFrostAPI.ts#L553)

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

[src/BlockFrostAPI.ts:562](https://github.com/blockfrost/blockfrost-js/blob/9b3f200/src/BlockFrostAPI.ts#L562)

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

[src/BlockFrostAPI.ts:571](https://github.com/blockfrost/blockfrost-js/blob/9b3f200/src/BlockFrostAPI.ts#L571)

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

[src/BlockFrostAPI.ts:595](https://github.com/blockfrost/blockfrost-js/blob/9b3f200/src/BlockFrostAPI.ts#L595)

___

### getAccount

• **getAccount**: (`publicKey`: `string`, `type`: `Account.Type`) => `Promise`<`Account.Result`[]\>

#### Type declaration

▸ (`publicKey`, `type`): `Promise`<`Account.Result`[]\>

txSubmit

##### Parameters

| Name | Type |
| :------ | :------ |
| `publicKey` | `string` |
| `type` | `Account.Type` |

##### Returns

`Promise`<`Account.Result`[]\>

xxx

#### Defined in

[src/BlockFrostAPI.ts:947](https://github.com/blockfrost/blockfrost-js/blob/9b3f200/src/BlockFrostAPI.ts#L947)

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

[src/BlockFrostAPI.ts:579](https://github.com/blockfrost/blockfrost-js/blob/9b3f200/src/BlockFrostAPI.ts#L579)

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

[src/BlockFrostAPI.ts:587](https://github.com/blockfrost/blockfrost-js/blob/9b3f200/src/BlockFrostAPI.ts#L587)

___

### metadataTxsLabel

• **metadataTxsLabel**: (`label`: `string`, `pagination?`: `PaginationOptions`) => `Promise`<`components`[``"schemas"``][``"tx_metadata_label_json"``]\>

#### Type declaration

▸ (`label`, `pagination?`): `Promise`<`components`[``"schemas"``][``"tx_metadata_label_json"``]\>

metadataTxsLabel

##### Parameters

| Name | Type |
| :------ | :------ |
| `label` | `string` |
| `pagination?` | `PaginationOptions` |

##### Returns

`Promise`<`components`[``"schemas"``][``"tx_metadata_label_json"``]\>

xxx

#### Defined in

[src/BlockFrostAPI.ts:604](https://github.com/blockfrost/blockfrost-js/blob/9b3f200/src/BlockFrostAPI.ts#L604)

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

[src/BlockFrostAPI.ts:613](https://github.com/blockfrost/blockfrost-js/blob/9b3f200/src/BlockFrostAPI.ts#L613)

___

### metadataTxsLabels

• **metadataTxsLabels**: (`pagination?`: `PaginationOptions`) => `Promise`<`components`[``"schemas"``][``"tx_metadata_labels"``]\>

#### Type declaration

▸ (`pagination?`): `Promise`<`components`[``"schemas"``][``"tx_metadata_labels"``]\>

metadataTxsLabels

##### Parameters

| Name | Type |
| :------ | :------ |
| `pagination?` | `PaginationOptions` |

##### Returns

`Promise`<`components`[``"schemas"``][``"tx_metadata_labels"``]\>

xxx

#### Defined in

[src/BlockFrostAPI.ts:621](https://github.com/blockfrost/blockfrost-js/blob/9b3f200/src/BlockFrostAPI.ts#L621)

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

[src/BlockFrostAPI.ts:629](https://github.com/blockfrost/blockfrost-js/blob/9b3f200/src/BlockFrostAPI.ts#L629)

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

[src/BlockFrostAPI.ts:637](https://github.com/blockfrost/blockfrost-js/blob/9b3f200/src/BlockFrostAPI.ts#L637)

___

### network

• **network**: () => `Promise`<`components`[``"schemas"``][``"network"``]\>

#### Type declaration

▸ (): `Promise`<`components`[``"schemas"``][``"network"``]\>

network

##### Returns

`Promise`<`components`[``"schemas"``][``"network"``]\>

Detailed network information.

#### Defined in

[src/BlockFrostAPI.ts:955](https://github.com/blockfrost/blockfrost-js/blob/9b3f200/src/BlockFrostAPI.ts#L955)

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

[src/BlockFrostAPI.ts:645](https://github.com/blockfrost/blockfrost-js/blob/9b3f200/src/BlockFrostAPI.ts#L645)

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

[src/BlockFrostAPI.ts:653](https://github.com/blockfrost/blockfrost-js/blob/9b3f200/src/BlockFrostAPI.ts#L653)

___

### nutlinkAddressTickerAll

• **nutlinkAddressTickerAll**: (`address`: `string`, `ticker`: `string`, `allMethodOptions?`: `AllMethodOptions`) => `Promise`<`components`[``"schemas"``][``"nutlink_address_ticker"``]\>

#### Type declaration

▸ (`address`, `ticker`, `allMethodOptions?`): `Promise`<`components`[``"schemas"``][``"nutlink_address_ticker"``]\>

nutlinkAddressTickerAll

##### Parameters

| Name | Type |
| :------ | :------ |
| `address` | `string` |
| `ticker` | `string` |
| `allMethodOptions?` | `AllMethodOptions` |

##### Returns

`Promise`<`components`[``"schemas"``][``"nutlink_address_ticker"``]\>

xxx

#### Defined in

[src/BlockFrostAPI.ts:677](https://github.com/blockfrost/blockfrost-js/blob/9b3f200/src/BlockFrostAPI.ts#L677)

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

[src/BlockFrostAPI.ts:661](https://github.com/blockfrost/blockfrost-js/blob/9b3f200/src/BlockFrostAPI.ts#L661)

___

### nutlinkAddressTickersAll

• **nutlinkAddressTickersAll**: (`address`: `string`, `allMethodOptions?`: `AllMethodOptions`) => `Promise`<`components`[``"schemas"``][``"nutlink_address_tickers"``]\>

#### Type declaration

▸ (`address`, `allMethodOptions?`): `Promise`<`components`[``"schemas"``][``"nutlink_address_tickers"``]\>

nutlinkAddressTickersAll

##### Parameters

| Name | Type |
| :------ | :------ |
| `address` | `string` |
| `allMethodOptions?` | `AllMethodOptions` |

##### Returns

`Promise`<`components`[``"schemas"``][``"nutlink_address_tickers"``]\>

xxx

#### Defined in

[src/BlockFrostAPI.ts:669](https://github.com/blockfrost/blockfrost-js/blob/9b3f200/src/BlockFrostAPI.ts#L669)

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

[src/BlockFrostAPI.ts:685](https://github.com/blockfrost/blockfrost-js/blob/9b3f200/src/BlockFrostAPI.ts#L685)

___

### nutlinkTickersAll

• **nutlinkTickersAll**: (`ticker`: `string`, `allMethodOptions?`: `AllMethodOptions`) => `Promise`<`components`[``"schemas"``][``"nutlink_tickers_ticker"``]\>

#### Type declaration

▸ (`ticker`, `allMethodOptions?`): `Promise`<`components`[``"schemas"``][``"nutlink_tickers_ticker"``]\>

nutlinkTickersAll

##### Parameters

| Name | Type |
| :------ | :------ |
| `ticker` | `string` |
| `allMethodOptions?` | `AllMethodOptions` |

##### Returns

`Promise`<`components`[``"schemas"``][``"nutlink_tickers_ticker"``]\>

xxx

#### Defined in

[src/BlockFrostAPI.ts:693](https://github.com/blockfrost/blockfrost-js/blob/9b3f200/src/BlockFrostAPI.ts#L693)

___

### options

• **options**: `ValidatedOptions`

#### Defined in

[src/BlockFrostAPI.ts:137](https://github.com/blockfrost/blockfrost-js/blob/9b3f200/src/BlockFrostAPI.ts#L137)

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

[src/BlockFrostAPI.ts:710](https://github.com/blockfrost/blockfrost-js/blob/9b3f200/src/BlockFrostAPI.ts#L710)

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

[src/BlockFrostAPI.ts:701](https://github.com/blockfrost/blockfrost-js/blob/9b3f200/src/BlockFrostAPI.ts#L701)

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

[src/BlockFrostAPI.ts:719](https://github.com/blockfrost/blockfrost-js/blob/9b3f200/src/BlockFrostAPI.ts#L719)

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

[src/BlockFrostAPI.ts:728](https://github.com/blockfrost/blockfrost-js/blob/9b3f200/src/BlockFrostAPI.ts#L728)

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

[src/BlockFrostAPI.ts:737](https://github.com/blockfrost/blockfrost-js/blob/9b3f200/src/BlockFrostAPI.ts#L737)

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

[src/BlockFrostAPI.ts:746](https://github.com/blockfrost/blockfrost-js/blob/9b3f200/src/BlockFrostAPI.ts#L746)

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

[src/BlockFrostAPI.ts:755](https://github.com/blockfrost/blockfrost-js/blob/9b3f200/src/BlockFrostAPI.ts#L755)

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

[src/BlockFrostAPI.ts:764](https://github.com/blockfrost/blockfrost-js/blob/9b3f200/src/BlockFrostAPI.ts#L764)

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

[src/BlockFrostAPI.ts:772](https://github.com/blockfrost/blockfrost-js/blob/9b3f200/src/BlockFrostAPI.ts#L772)

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

[src/BlockFrostAPI.ts:780](https://github.com/blockfrost/blockfrost-js/blob/9b3f200/src/BlockFrostAPI.ts#L780)

___

### projectId

• `Optional` **projectId**: `string`

#### Defined in

[src/BlockFrostAPI.ts:135](https://github.com/blockfrost/blockfrost-js/blob/9b3f200/src/BlockFrostAPI.ts#L135)

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

[src/BlockFrostAPI.ts:788](https://github.com/blockfrost/blockfrost-js/blob/9b3f200/src/BlockFrostAPI.ts#L788)

___

### script

• **script**: (`scriptHash`: `string`) => `Promise`<`components`[``"schemas"``][``"script"``]\>

#### Type declaration

▸ (`scriptHash`): `Promise`<`components`[``"schemas"``][``"script"``]\>

Information about a specific script

##### Parameters

| Name | Type |
| :------ | :------ |
| `scriptHash` | `string` |

##### Returns

`Promise`<`components`[``"schemas"``][``"script"``]\>

Information about a specific script

#### Defined in

[src/BlockFrostAPI.ts:804](https://github.com/blockfrost/blockfrost-js/blob/9b3f200/src/BlockFrostAPI.ts#L804)

___

### scriptCbor

• **scriptCbor**: (`scriptHash`: `string`) => `Promise`<`components`[``"schemas"``][``"script_cbor"``]\>

#### Type declaration

▸ (`scriptHash`): `Promise`<`components`[``"schemas"``][``"script_cbor"``]\>

##### Parameters

| Name | Type |
| :------ | :------ |
| `scriptHash` | `string` |

##### Returns

`Promise`<`components`[``"schemas"``][``"script_cbor"``]\>

#### Defined in

[src/BlockFrostAPI.ts:814](https://github.com/blockfrost/blockfrost-js/blob/9b3f200/src/BlockFrostAPI.ts#L814)

___

### scriptDatum

• **scriptDatum**: (`datumHash`: `string`) => `Promise`<`components`[``"schemas"``][``"script_datum"``]\>

#### Type declaration

▸ (`datumHash`): `Promise`<`components`[``"schemas"``][``"script_datum"``]\>

##### Parameters

| Name | Type |
| :------ | :------ |
| `datumHash` | `string` |

##### Returns

`Promise`<`components`[``"schemas"``][``"script_datum"``]\>

#### Defined in

[src/BlockFrostAPI.ts:819](https://github.com/blockfrost/blockfrost-js/blob/9b3f200/src/BlockFrostAPI.ts#L819)

___

### scriptJson

• **scriptJson**: (`scriptHash`: `string`) => `Promise`<`components`[``"schemas"``][``"script_json"``]\>

#### Type declaration

▸ (`scriptHash`): `Promise`<`components`[``"schemas"``][``"script_json"``]\>

##### Parameters

| Name | Type |
| :------ | :------ |
| `scriptHash` | `string` |

##### Returns

`Promise`<`components`[``"schemas"``][``"script_json"``]\>

#### Defined in

[src/BlockFrostAPI.ts:809](https://github.com/blockfrost/blockfrost-js/blob/9b3f200/src/BlockFrostAPI.ts#L809)

___

### scriptRedeemers

• **scriptRedeemers**: (`scriptHash`: `string`) => `Promise`<`components`[``"schemas"``][``"script_redeemers"``]\>

#### Type declaration

▸ (`scriptHash`): `Promise`<`components`[``"schemas"``][``"script_redeemers"``]\>

List of redeemers of a specific script

##### Parameters

| Name | Type |
| :------ | :------ |
| `scriptHash` | `string` |

##### Returns

`Promise`<`components`[``"schemas"``][``"script_redeemers"``]\>

List the information about redeemers of a specific script

#### Defined in

[src/BlockFrostAPI.ts:827](https://github.com/blockfrost/blockfrost-js/blob/9b3f200/src/BlockFrostAPI.ts#L827)

___

### scripts

• **scripts**: (`pagination?`: `PaginationOptions`) => `Promise`<`components`[``"schemas"``][``"scripts"``]\>

#### Type declaration

▸ (`pagination?`): `Promise`<`components`[``"schemas"``][``"scripts"``]\>

List scripts

##### Parameters

| Name | Type |
| :------ | :------ |
| `pagination?` | `PaginationOptions` |

##### Returns

`Promise`<`components`[``"schemas"``][``"scripts"``]\>

List of script hashes

#### Defined in

[src/BlockFrostAPI.ts:796](https://github.com/blockfrost/blockfrost-js/blob/9b3f200/src/BlockFrostAPI.ts#L796)

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

[src/BlockFrostAPI.ts:929](https://github.com/blockfrost/blockfrost-js/blob/9b3f200/src/BlockFrostAPI.ts#L929)

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

[src/BlockFrostAPI.ts:836](https://github.com/blockfrost/blockfrost-js/blob/9b3f200/src/BlockFrostAPI.ts#L836)

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

[src/BlockFrostAPI.ts:854](https://github.com/blockfrost/blockfrost-js/blob/9b3f200/src/BlockFrostAPI.ts#L854)

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

[src/BlockFrostAPI.ts:917](https://github.com/blockfrost/blockfrost-js/blob/9b3f200/src/BlockFrostAPI.ts#L917)

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

[src/BlockFrostAPI.ts:845](https://github.com/blockfrost/blockfrost-js/blob/9b3f200/src/BlockFrostAPI.ts#L845)

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

[src/BlockFrostAPI.ts:908](https://github.com/blockfrost/blockfrost-js/blob/9b3f200/src/BlockFrostAPI.ts#L908)

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

[src/BlockFrostAPI.ts:863](https://github.com/blockfrost/blockfrost-js/blob/9b3f200/src/BlockFrostAPI.ts#L863)

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

[src/BlockFrostAPI.ts:872](https://github.com/blockfrost/blockfrost-js/blob/9b3f200/src/BlockFrostAPI.ts#L872)

___

### txsRedeemers

• **txsRedeemers**: (`hash`: `string`) => `Promise`<`components`[``"schemas"``][``"tx_content_redeemers"``]\>

#### Type declaration

▸ (`hash`): `Promise`<`components`[``"schemas"``][``"tx_content_redeemers"``]\>

##### Parameters

| Name | Type |
| :------ | :------ |
| `hash` | `string` |

##### Returns

`Promise`<`components`[``"schemas"``][``"tx_content_redeemers"``]\>

#### Defined in

[src/BlockFrostAPI.ts:920](https://github.com/blockfrost/blockfrost-js/blob/9b3f200/src/BlockFrostAPI.ts#L920)

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

[src/BlockFrostAPI.ts:881](https://github.com/blockfrost/blockfrost-js/blob/9b3f200/src/BlockFrostAPI.ts#L881)

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

[src/BlockFrostAPI.ts:890](https://github.com/blockfrost/blockfrost-js/blob/9b3f200/src/BlockFrostAPI.ts#L890)

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

[src/BlockFrostAPI.ts:899](https://github.com/blockfrost/blockfrost-js/blob/9b3f200/src/BlockFrostAPI.ts#L899)

___

### userAgent

• `Optional` **userAgent**: `string`

#### Defined in

[src/BlockFrostAPI.ts:136](https://github.com/blockfrost/blockfrost-js/blob/9b3f200/src/BlockFrostAPI.ts#L136)
