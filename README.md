####################################################################
####################### CHECKLIST ##################################
####################################################################

[COMPLETED_12/24] First: Python that creates an account and saves the account info in vars

[COMPLETED_12/25] Second: create smart contract that will be user identity

[COMPLETED_12/26] Third: create scripting that deploys smart contract

[COMPLETED_12/28] Fourth: link SC and newly created user account, new acct is soulbound owner

[COMPLETED_12/30] Fifth: add all V1 variables in SC for information we want to capture

            A. ETH Wallet Addresses
            B. Email
            C. Name
            D. DAOs/Memberships
            E. NFT/Badges
            F. Skills
            G. tasks completed
            H. hours worked
            I. NEAR Wallet Addresses
            J. Tokens
            K. DAO Helper Username
            
[NEED_REQS_FROM_FRONT_END_DEV] Sixth: add application calls that update information in the SC

###################################################################
####################### Kash 12/21 Notes ##########################
###################################################################

Goals:

    1. [5] Wants to get rid of the wallets on site and add them inside of the user profile.

    2. [1,2] When users sign up on the website need to create an algo account  and SC on the backend that represents them.

        a. [5] Add other chain wallet address information.

    3. [1,2] Least we can do on chain is prove that a wallet owns a profile (soulbound SC and owner acct).

    4. Can we incorporate [magic_link]? [YES-But not in this script, need to provide magic link data as input to the scripting or update the SC later using app calls.] They only provide MetaMask, WalletConnect and Coinbase Wallet suppport.

    5. [5] We want to show ownership of DAO Helper profile on chain.

###################################################################