# Important
I will no longer maintain this. I believe Arbitrum is a widely recognized chain, and DappNode should be responsible for supporting it, similar to other major chains. That being said, I may still provide occasional updates, but I am no longer actively maintaining it. If you submit a pull request, you may need to reach me via Twitter as I may not see it otherwise.

# Arbitrum Nitro Full Node for DappNode
| ***I'm no longer verifying the package (unless it is a major update), be sure to use the ones inside releases.json***

This repo allows you to run a Aribtrum full node on [DappNode](https://twitter.com/dappnode). I'll support this repo until DappNode's team decide to support it officially. 

## Installation Prerequisites

You'll need access to synced ETH node.
As of Upstream Version v2.3.0+ Arbitrum Nitro requires not just an execution layer endpoint, but also a beacon chain endpoint.
Futher when syncing got yhe first time or if your node has been offline for 18 days or more, you'll need to provide a full Beacon Chain Checkpoint such as the Dappnode ETH Mainnet CL Checkpoint URL which is an option in the Config Tab and Setup Wizard.  Once you are fully synced please switch to using a local beacon chain connection via the `Global` option in the Setup Wizard or Config Tab.

There's no requirement to host the ETH Mainnet stack yourself locally, but it is strongly reccomended you that you do for full decentralization,
If you don't want to host a full stack Ethereum Node yourself be sure to update the Option in the Config Tab to `Custom` and provide your non-local or 3rd party RPC endpoints.

## Running an Arbitrum Nitro Node

If this is your first time syncing your Arbitrum One Nitro Node, it must be initialized first with a download of a DB.  This will be handled for you automatically, however if your initial sync is is iteruppted in the first step you likely will need to wipe the Arbitrum Nitro Data Dir and restart the package it will then re-download the initial Genesis database for you. Ask for support on our [Discord](https://discord.gg/dappnode) if you need help with determining if you need to do this.

## Specs

[Arbitrum's Doc - minimum-hardware-configuration](https://docs.arbitrum.io/node-running/how-tos/running-a-full-node#minimum-hardware-configuration)