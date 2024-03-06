## Description
The Autonity Bakerloo test network is scheduled for re-genesis on 01-03-2024. All validators need to upgrade their nodes to continue participating in the network.

This `How To` guide contains steps to install and configure an Autonity v0.13.0 client and v0.1.6 oracle server.

## Steps to on-board Validator on Bakerloo network

**Step 1**: Stop the Validator node, delete the old chaindata folder, generate a new private key `autonitykeys` file for your node.

**Step 2** : Upgrade your Autonity node. Download the new Autonity release (follow the docs) and deploy the node, join the network. **Docs: Install Autonity Guide**: https://docs.autonity.org/node-operators/install-aut/.

**Step 3** : Install the oracle server per the docs. **Docs: Install Autonity Oracle Server Guide**: https://docs.autonity.org/oracle/install-oracle/.

**Step 4**: Create oracle server account keys. **Docs: Create oracle server account Guide**: https://docs.autonity.org/oracle/run-oracle/#create-oracle-server-account.

**Step 5**: Get testnet funds. You will need ATN and NTN. Get ATN from the Bakerloo faucet at https://faucet.autonity.org/. Get NTN by requesting it in the Discord channel `VALIDATORS / get-ntn-bakerloo`.

**Step 6**: Pre-fund validator treasury and oracle server accounts. Pre-fund as necessary your validator treasury account (ATN & NTN) and oracle account (ATN). **Docs: Register as a Validator Guide**: https://docs.autonity.org/validators/register-vali/. **Docs: Run Autonity Oracle Server Guide**: https://docs.autonity.org/oracle/run-oracle/. Oracle server requires minimal funding as transaction fee costs are refunded; a minimum amount of `0.1` ATN is sufficient.

**Step 7**: Configure the Autonity client as per the docs. The Autonity Oracle Server requires an accessible ws/wss Autonity client endpoint to connect to, so remember to make the Web Socket port accessible when running the node.  The Autonity Oracle Server will feed data to the client via that port! **Docs: Run Autonity**: https://docs.autonity.org/node-operators/run-aut/.

**Step 8**: Configure the oracle server as per the docs. You will need to configure data sources for FX data feeds. The oracle provides data plugins for connecting to FX sources accessible with free subscription and to a simulator for ATN and NTN data. See the docs for reference **Docs: Running an Oracle Server Guide, Configure data source plugins**: http://docs.autonity.org/oracle/run-oracle/#configure-plugins.

**Step 9**: Start the client node. **Docs: Run Autonity Guide**: https://docs.autonity.org/node-operators/run-aut/.

**Step 10**: Start the oracle server.  **Docs: Run Autonity Oracle Server Guide**: https://docs.autonity.org/oracle/run-oracle/.

**Step 11**: Register Autonity node as the Validator on Bakerloo test network. **Docs: Running a Validator Guide, Register Validator**: https://docs.autonity.org/validators/register-vali/.

**Step 12**: Bond stake to the Validator on Bakerloo test network. **Docs: Staking Guide, Bond and Unbond Stake**: https://docs.autonity.org/delegators/bond-stake/.          

**Note** : Discord channel (https://discord.com/channels/753937111781998605/1067051261993680996) to share your experience or in case you need help.
