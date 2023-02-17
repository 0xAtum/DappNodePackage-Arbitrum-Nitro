# Important
I will no longer maintain this. I believe Arbitrum is a widely recognized chain, and DappNode should be responsible for supporting it, similar to other major chains. That being said, I may still provide occasional updates, but I am no longer actively maintaining it. If you submit a pull request, you may need to reach out to me via Twitter as I may not see it otherwise.

# Arbitrum Nitro Full Node for DappNode
| ***I'm no longer verifying the package (unless it is a major update), be sure to use the ones inside releases.json***

This repo allows you to run a Aribtrum full node on [DappNode](https://twitter.com/dappnode). I'll support this repo until DappNode's team decide to support it officially. 

## Installation Prerequisites

You'll need access to synced ETH node.
No need to host it yourself, but if you do, you'll need a full Ethereum Mainnet Stack (Both Execution and Consensus Layer Clients) run locally.
If you don't want to host a full stack Ethereum Node yourself be sure to update the ETH_RPC_URL in the Config Tab. By default it uses `http://geth.dappnode:8545`.

## Running an Arbitrum Nitro Node

If this is your first time starting this Arbitrum One Nitro Node, go to the config tab and add `--init.url=https://snapshot.arbitrum.io/mainnet/nitro.tar` to the EXTRA_OPTS field in the config tab of the package.
This will download the Genesis Database for you.
Once the initial database has been downloaded, you can remove the flag.

### [Install Link](http://my.dappnode/#/installer/arbitrum-nitro.public.dappnode.eth)

## Specs

Average on a period of 24 hours

| Spec | Arbitrum Nitro Full Node | GETH Full Node |
|--|--|--|
| Storage (Sep 3, 2022) | 51 GB | 644 GB|
| CPU Usage | 0.31% | 5% |
| Memory Usage | 893 MB | 6.48 GB |
| Cached Memory Usage | 6.14 GB | 7.36 GB
