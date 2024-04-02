
# Arbitrum Nitro Node
[Arbitrum how-tos](https://docs.arbitrum.io/node-running/how-tos/running-a-full-node)


If this is your first time starting this Arbitrum One Nitro Node, you'll need to initialize the DB with pre-nitro blocks for ArbitrumOne. 
WHen starting to sync a new install or after wiping the volume of the package it will automatically download the initial database for you before beginning full node sync.

If this is your first time starting Arbitrum One Nitro Node, go to the config tab and add `--init.url={snpashot-database-url}` in the EXTRA_OPTS filed. Once the initial database has been downloaded, you can remove the flag.

To find the `{snpashot-database-url}`, read the  [prerequisites](https://docs.arbitrum.io/node-running/how-tos/running-a-full-node#prerequisites)
