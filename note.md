Users can deposit specified ERC20 token into the vault an ERC4626 vault

Each vault is manage by a vaultGuardian a human. 

The guardian is to manage the vault to maximize the vault value for the users who have deposited money.

 in other words the are like hedge funders they are tasked to manage and make yield with erc20 tokens deposited inot the vault by users 

 to prevent malicious activites the vault are designed to ensure gardians are only allowed to deposit and withdraw the erc20s inot specific protocols 

 Aave Uniswap or just hold (investable universe)

 No restriction to how guardians can move funds in and out of these protocols (investable universe )

 funds can be moved in and out of these protocols but cannot be moved to any other address - Invariant 

 performance fee is charged by the guardian the better their performance with managing ythe funds the higher fee they will command (q: whats in for the user if the guardian mismanage funds on purpose?)

 Anyone who can deposit a certain amount of erc20 token into the vault can become a guardian(q: what token are they depositing). to stop being a guardian, they give out all user deposits and withdraw their guardian stake. (q: when they return users stake where is it left and how do users get it out since they initially deposited to the guardian, is it a push from the guardians to users or is it a push to a destination by the guardian and then a pull by users?)

 The protocol is upgradeable -reasons (incase protocol owners need to remove or add an investable universe)


User flow

User deposits an ERC20 into a guardian's vault

The guardian automatically move the funds based on their strategy

The guardian can update the settings of their strategy at any time and move the funds

To leave the pool, a user just calls redeem or withdraw (q: why redeem or withdraw and not one of them? are they seperate functions or one function?)

Users can earn DAO tokens by becoming guardians. the DAO is responsible for;

Updating pricing parameters (q: What Price Parameters)

Getting a cut of all performance of all guardians (q: are dao tokens geting performance from guardians from the fees they command from being a profitable fund manager or elsewhere?)