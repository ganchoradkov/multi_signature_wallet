# Implementation of Multi Signature Wallet

This smart contract is an implemenetation of multi signature wallet, meaning, it requires multiple confirmations before confirming/paying out transactions.
The number of required transactions is defined by the deployer at the time of contract deployment.

The workflow of the contract is as follows:
 1. Submit transaction
 2. Each of the owners confirms the said transaction
 3. Transaction can be executed only after reaching the required number of confirmations

Additional functionality is that owners can revoke confirmation & every step of the workflow is logged with events.
