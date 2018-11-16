# WINDOWS: FGC-Wallet-Install
How to Install and Configure the FGC Wallet. (required for both standalone wallet and masternode wallet)

# Download & Install the Wallet
You will find your relevant wallet to download from:

```
https://github.com/FantasyGold/FantasyGold-Core/releases
```

# Configure your Wallet
On occasion the wallet will not sync without addnodes, its recomended to preform the following task regardless of immediate sync or not.

Open your wallet.
On the Menu, goto Tools and then "Open Wallet Configuration File", if prompted to 'openwith' choose notepad or similar.
Enter the following text into the fantasygold.conf file which has now opened.

```
rpcuser=iamarandomfgcuser
rpcpassword=asdaDAA@@SDFPSKF"£FOK£"ffdf232jfpj2[3fj]f2pf9f95g4!! 
rpcallowip=127.0.0.1 
listen=1 
server=1 
daemon=1 
logtimestamps=1
```

Save the file, restart the wallet, if you previously had a sync issue, this should fix it.

# Wait for Sync

Wait for the wallet to fully sync.
Goto 'Receive' tab on the wallet.
Enter a label you will use for receiving your coins, no quantity entry is required.
Click 'Request Payment'
You will be displayed your recieving address, send your coins to this address.
Standard transactions require 6 confirmations before available.

# Congrats, you now have FGC in your wallet.

# MAC: FGC-Wallet-Install

Press Command+Space to open Spotlight, write ~/Library/Application Support/FantasyGold and press Enter.
Open fantasygold.conf
Paste in the same conf text from the windows section above.
Save, restart wallet, sync should work.

# LINUX: FGC-Wallet-Install
Please just add the fantasygold.conf text with addnodes to your local linux .conf.
(if your using linux am sure you know what your doing ;)
