# Bakerloo GV Data
This repository contains the Genesis Validator data that will be used to create the validator set for launch of the long running Bakerloo testnet (not data for Mainnet genesis).

# Important notes

- Please do not use existing keys/addresses from previous genesises, instead generate new ones. This is good practice as fresh keys/addresses will be required for Mainnet too. 
- Please submit your data by no later than **Wednesday, 23rd July 2025**.
- For participation in Mainnet genesis, it is *mandatory* to take part in the genesis of the Bakerloo testnet. This is to provide all Genesis Validators with an opportunity to refamiliarise themselves with the genesis steps and ensure that Mainnet can be launched without a hitch.
- Please run your validators on Bakerloo for at least three weeks, after which it is not compulsory to continue running a Bakerloo validator. However, it is highly recommended to do so as Bakerloo will be used for testing future features and upgrades.

# Step-by-step guide
The steps below outline how selected Genesis Validators should submit the required data for a successful launch of the Bakerloo testnet. Please:

1. Clone this repo locally and branch off the ***master*** branch. Name your own branch in the following format ***[UUID]-genesis-validator-data***. Please use the same UUID you were given before (if you don't know what it is please reach out to @spencercoll1ns on Telegram).
2. On your own branch, navigate to the `genesis-validator-data` folder.
3. Inspect the `template.json` file that shows the format in which you should submit your own json file, and contains reference documentation for each field.
4. Create a new json file called `[UUID].json`, containing your validator info as per the `template.json` file.
5. Open a pull request against the ***master*** branch and add ***"[UUID]-genesis-validator-data"*** as the PR title.
6. The team will review your PR, verify your ownership proof and merge it if all checks pass. You have now successfully submitted your genesis validator data for Bakerloo!

⚠️ Please ensure any data you submit here will still be correct for genesis of Bakerloo. Specifically, ensure that any IP address/port number you submit here will still be available to you at genesis. Modifying your supplied information later may introduce delays.

Please continue to monitor Discord/Telegram for instructions on next steps. Thank you for helping launch Bakerloo!
