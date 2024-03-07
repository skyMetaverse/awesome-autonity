## Description
The Autonity Piccadilly test network is scheduled to be re-genesis on 04-03-2024. Post that all validators need to upgrade their nodes to continue participating in the network and Piccadilly Circus Games Competition.

This `How To` guide contains steps to install and configure an Autonity v0.13.0 client and v0.1.6 oracle server.

## Steps to on-board a full node run as a public RPC endpoint on Piccadilly network

**Step 1**: Ensure your `aut` tool is installed and up to date (0.4.0): https://docs.autonity.org/account-holders/setup-aut/ 

**Step 2**: If you had a previous node running, then stop the full node public RPC endpoint, delete the old chaindata folder, generate a new private key `autonitykeys` file for your node.

**Step 3** : Upgrade your Autonity node. Download the new Autonity release (follow the docs) and deploy the node, join the network. **Docs: Install Autonity Guide**: https://docs.autonity.org/node-operators/install-aut/.

**Step 4** : Register for PCGC if you have not already done so. **PCGC: Registration Form**: https://game.autonity.org/getting-started/register.html.

**Step 5** : If you are operating a public RPC endpoint node, register for the "Open the door" challenge **PCGC: Task Guide**: https://game.autonity.org/round-5/node-open-door/.

## Steps to on-board a Validator on Piccadilly network

**Step 1**: Ensure your `aut` tool is installed and up to date (0.4.0): https://docs.autonity.org/account-holders/setup-aut/ 

**Step 2**: If you had a previous Validator running then stop the Validator node, delete the old chaindata folder, generate a new private key `autonitykeys` file for your node.

**Step 3** : Upgrade your Autonity node. Download the new Autonity release (follow the docs) and deploy the node, join the network. **Docs: Install Autonity Guide**: https://docs.autonity.org/node-operators/install-aut/.

**Step 4** : Install the oracle server per the docs. **Docs: Install Autonity Oracle Server Guide**: https://docs.autonity.org/oracle/install-oracle/.

**Step 5**: Create oracle server account keys. **Docs: Create oracle server account Guide**: https://docs.autonity.org/oracle/run-oracle/#create-oracle-server-account.

**Step 6** : Register for PCGC if you have not already done so. **PCGC: Registration Form**: https://game.autonity.org/getting-started/register.html. You will receive 1 NTN and 1 ATN once successfully registered. If you have already registered from previous rounds, you have been pre-funded with 1 ATN and 1 NTN to your registered participant account. Get additional ATN and NTN for Round 5 from the game's off-chain exchange the Centralized Auton Exchange (CAX). **PCGC: Using the CAX**: https://game.autonity.org/getting-started/exchange-cax.html.

**Step 7**: Pre-fund validator treasury and oracle server accounts. Pre-fund as necessary your validator treasury account (ATN & NTN) and oracle account (ATN). **Docs: Register as a Validator Guide**: https://docs.autonity.org/validators/register-vali/. **Docs: Run Autonity Oracle Server Guide**: https://docs.autonity.org/oracle/run-oracle/. Oracle server requires minimal funding as transaction fee costs are refunded; a minimum amount of `0.1` ATN is sufficient.

**Step 8** : Configure the Autonity client as per the docs. The Autonity Oracle Server requires an accessible ws/wss Autonity client endpoint to connect to, so remember to make the Web Socket port accessible when running the node.  The Autonity Oracle Server will feed data to the client via that port! **Docs: Run Autonity**: https://docs.autonity.org/node-operators/run-aut/.

**Step 9**: Configure the oracle server as per the docs. You will need to configure data sources for FX data feeds. The oracle provides data plugins for connecting to FX sources accessible with free subscription and to a simulator for ATN and NTN data. See the docs for reference **Docs: Running an Oracle Server Guide, Configure data source plugins**: http://docs.autonity.org/oracle/run-oracle/#configure-plugins.

**Step 10**: Start the client node. **Docs: Run Autonity Guide**: https://docs.autonity.org/node-operators/run-aut/.

**Step 11**: Start the oracle server.  **Docs: Run Autonity Oracle Server Guide**: https://docs.autonity.org/oracle/run-oracle/.

**Step 12**: Register Autonity node as the Validator on Piccadilly test network. **Docs: Running a Validator Guide, Register Validator**: https://docs.autonity.org/validators/register-vali/.

**Step 13**: Bond stake to the Validator on Piccadilly test network. **Docs: Staking Guide, Bond and Unbond Stake**: https://docs.autonity.org/delegators/bond-stake/.

**Step 14**: Register the Validator for the "Onboard Validator" challenge. **PCGC: Task Guide**: https://game.autonity.org/round-5/node-onboard-validator/.           

**Note** : Discord channel (https://discord.com/channels/753937111781998605/1067051261993680996) to share your experience or in case you need help.
