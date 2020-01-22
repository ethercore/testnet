# EtherCore Testnet

![EtherCore Logo](./ethercore.png)

Welcome to EtherCore Testnet!

### Portal: https://testnet.ethercore.org/

## Meta data

- Name: EtherCoreTest
- Machine-readable name: `ethercoretest`
- Stage: _launched_
  - Genesis hash: `0x882bef94a19a1ea0dce9cb602fec35f82164535e641e4898ddc8a0ab6ecbd2f5`
  - Network ID: `468`
  - Chain ID: `468`
  - Homestead: `0`
  - EIP150: `0`
  - EIP155: `0`
  - EIP158: `0`
  - Byzantium: `0`
  - Constantinople: `0`
  - Petersburg: `0`
  - Istanbul: `0`
  - ProgPoW: `0`
  - EtherCore: `0`
- Status Dashboard: http://testnet-stats.ethercore.org
- Block Explorer: https://testnet-explorer.ethercore.org
- Mining Pool: https://testnet-pool.ethercore.org
- Wallet: https://wallet.ethercore.org/?network=ethercore_testnet
- Faucet: https://testnet-faucet.ethercore.org
- Public RPC Endpoint: https://testnet-rpc.ethercore.org
- Telegram Support: https://t.me/ethercore

## Connecting the clients

All clients supporting the go-ethercore protocol are able to sync with EtherCore Testnet.

##### Go-EtherCore

You can connect Geth to EtherCore Testnet by executing `geth --test`. https://github.com/ethercoreorg/go-ethercore/releases/latest

## Receiving Testnet Coins

Create new wallet from https://wallet.ethercore.org/?network=ethercore_testnet and receive some testnet coins from https://testnet-faucet.ethercore.org to play with

## Connecting Metamask

You could connect EtherCore Testnet with your Metamask plugin installed on your browser.

Add the following config value to Custom RPC settings.

- Network Name: `EtherCore`

- New RPC URL: `https://testnet-rpc.ethercore.org`

- ChainID: `468`

- Symbol: `ERE`

- Block Explorer URL: `https://testnet-explorer.ethercore.org`

Now you could use your Metamask plugin to receive testnet coins, deploying contract with https://remix.ethereum.org, and interacting DApps deployed on Testnet EtherCore!

## Mining on EtherCore Testnet

Not only requesting coins from faucet, you could also mine some testnet coins via testnet pool https://testnet-pool.ethercore.org

Like mining on Mainnet, fetch the [EthCoreMiner](https://github.com/ethercoreorg/ethcoreminer/releases/latest) and start your miner with the following configuration.

Here is the example bat file for windows

```
:start
TIMEOUT 10
ethcoreminer.exe -P stratum1+tcp://0xbf0d596191fed3c4ed421a42ee4b9bf21bc1139d.rig1@testnet-pool.ethercore.org:8008
goto start
```
