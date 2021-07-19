<img src="https://blockfrost.io/images/logo.svg" width="250" align="right" height="200">

![master build ci](https://github.com/blockfrost/blockfrost-js/actions/workflows/build.yml/badge.svg?branch=master) [![npm version](https://badge.fury.io/js/%40blockfrost%2Fblockfrost-js.svg)](https://badge.fury.io/js/%40blockfrost%2Fblockfrost-js) ![downloads](https://img.shields.io/npm/dy/@blockfrost/blockfrost-js) <a href="https://fivebinaries.com/"><img src="https://img.shields.io/badge/made%20by-Five%20Binaries-darkviolet.svg?style=flat-square" /></a>

# blockfrost-js

<p align="center">A JavaScript/Typescript SDK for Blockfrost.io API.</a>
<br>

<p align="center">
  <a href="#getting-started">Getting started</a> •
  <a href="#installation">Installation</a> •
  <a href="#usage">Usage</a>
</p>
<br>

## Getting started

To use this SDK, you first need login into to [blockfrost.io](https://blockfrost.io) create your project to retrive your API token.

<img src="https://i.imgur.com/smY12ro.png">

<br/>

## Installation

The SDK is hosted on [npmjs.com](https://www.npmjs.com/package/@blockfrost/blockfrost-js), so you can directly import it using your favorite package manager.

```console
$ yarn add @blockfrost/blockfrost-js
```

<br/>

## Usage

Using the SDK is pretty straight-forward as you can see from the following examples.

### Cardano

```typescript
import { BlockfrostAPI } from '@blockfrost/blockfrost-js';

const API = new BlockFrostAPI({
  projectId: 'YOUR API KEY HERE', // see: https://blockfrost.io
});

try {
  const latestBlock = await API.blocksLatest();
  const latestEpoch = await API.epochsLatest();
  const health = await API.health();
  const address = await API.addresses(
    'addr1qxqs59lphg8g6qndelq8xwqn60ag3aeyfcp33c2kdp46a09re5df3pzwwmyq946axfcejy5n4x0y99wqpgtp2gd0k09qsgy6pz',
  );

  console.log('address', address);
  console.log('latestEpoch', latestEpoch);
  console.log('latestBlock', latestBlock);
  console.log('health', health);
} catch (err) {
  console.log('error', err);
}
```

### IPFS

```typescript
import { BlockfrostIPFS } from '@blockfrost/blockfrost-js';
import fs from 'fs';

const IPFS = new BlockFrostIPFS({
  projectId: 'YOUR IPFS KEY HERE', // see: https://blockfrost.io
});

try {
  const stream = fs.createReadStream(`${__dirname}/img.svg`);
  const added = await IPFS.add(stream);

  console.log('added', added);

  const pinned = await IPFS.pin(added.ipfs_hash);

  console.log('pinned', pinned);
} catch (err) {
  console.log('error', err);
}
```

For a more detailed list of possibilities, [check out the wiki](https://github.com/blockfrost/blockfrost-js/wiki/Class-BlockFrostAPI).
