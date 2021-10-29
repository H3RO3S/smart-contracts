# smart-contracts

-> Base contract inherited from https://github.com/OpenZeppelin/openzeppelin-contracts/blob/master/contracts/token/ERC20/presets/ERC20PresetMinterPauser.sol

-> Heros token function 
    1. mint Percentages -- which mints the respective amount of tokens to thier wallet addresses
    2. Buy - which transfers an user input amount of tokens for stableCoins(USDC,USDT,DAI)
    3. setWallet type -- which is used by owner of contract to set the wallets which can buy 
                            different types of sales.

                            ->set function with integer 1 to enable seed sale rate
                            -> with integer 2 to enable private sale rate 
                            -> with 3 to enable strategic sale rate
                            -> 4 or 0 to enable public sale
