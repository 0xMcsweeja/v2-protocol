wildcat doesnt underwrite risk of default. it provides infra, code transparency, but counterparty risk for checking is on lender

code enabling a credit market - where borrower reputation and market configurations drive


Archcontroller - global registry switchboard. where protocol operators register and authorise legit borrowers. tracks approved hook factories / templates.

borrower greenlight whats next?
-> hookfactory. these store blurprints for diff market behavioiur (hook templates). these are the contracts borrowers use to actually deploy specific market contracts and associated hook instances linked to them



hook template = base code defining a type of rule maybe a timelock on withdrawals or a requirement to hold a specific token to deposit  

hook instance = actually deployed copy of that templates code thats bound to a single specific market

within hook instance the borrower configures role providers.




questions
- reading through all the wc content its evident that the platform self selects for technical natives. credit lines are an unlock but half of the market isnt onchain and theyd have an aneurysm trying to configure a market

- hook templates are the dangerzone - if bug found in template then all deployed markets at risk

sidechannel for custom verification of certain hooks
accesscontrol includes extra raw bytes to include something like a merkle