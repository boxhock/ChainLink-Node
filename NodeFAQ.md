# ChainLink Node FAQ

## How much LINK is required to be a node operator?

No LINK is required in order to be a node operator. However, holding LINK on your node (first form of staking) helps with ranking your node against others. Your node will also need some LINK in order to bid on smart contracts with the penalty amount. If the node is not selected to perform the job, or the node successfully completes the job, then it can retrieve that paid penalty amount (second form of staking).

---

## Wouldn’t holding millions of LINK automatically rank you to the top above the other nodes?

No, holding LINK is just one of 6 factors when determining a node’s ranking. Having LINK on a node helps get the node started, but there is a point of diminishing returns for how much LINK to hold.

---

## What are the factors for ranking a node?

* Total number of assigned requests
* Total number of completed requests
* Total number of accepted requests
* Average time to respond
* Amount of penalty payments
* Amount of LINK held

---

## Is running a node going to be like passive income?

Mostly, but there are a few manual tasks that need to be accomplished. As a node operator, you will need to establish connections to different API endpoints which would feed data back to a smart contract. You will also need to ensure that the system is well-maintained and updated with the latest security patches. Also, your “income” for running a node will be paid entirely in LINK, so it will be up to you to convert that to FIAT.

---

## Is there a reward system for running a node?

You'll set your own prices (paid in LINK) for retriving data from 3rd party sources. It is not yet known how the [node operator incentive fund](https://etherscan.io/address/0x98c63b7b319dfbdf3d811530f2ab9dfe4983af9d) will be used. So for now, the prices which you set on your node will be the only known form of income to node operators.

---

## Does the ChainLink node need to be ran on the same machine as my Ethereum node?

No, as long as you are running your Ethereum node with the --rpc flag and a port opened, you can configure the .env file to connect to a remote Ethereum node. Set the ETHEREUM_URL value to your remote Ethereum node and port.

---

## Does Ethereum need to run in --full mode?

No, it's not necessary to download the entire blockchain history in order to run a ChainLink node. You're free to use either --fast or --light options when running geth, just make sure you also use the --rpc flag.
