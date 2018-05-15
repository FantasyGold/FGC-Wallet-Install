# FGC-Wallet-Install
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
addnode=18.218.69.84
addnode=18.222.88.20
addnode=18.188.230.37
addnode=108.61.87.124
addnode=45.63.64.205
addnode=35.194.84.154
addnode=138.68.225.190
addnode=8.9.11.67
addnode=104.236.95.172
addnode=149.28.42.218
addnode=159.65.72.255
addnode=18.216.52.206
addnode=144.202.30.145
addnode=89.47.161.171
addnode=80.209.224.171
addnode=144.76.38.145
addnode=18.191.6.184
addnode=207.246.125.20
addnode=208.167.242.3
addnode=165.227.106.45
addnode=107.172.196.152
addnode=8.12.17.243
addnode=188.166.116.194
addnode=63.209.33.1
addnode=140.82.15.110
addnode=45.77.85.29
addnode=207.148.7.121
addnode=45.56.104.241
addnode=172.104.152.61
addnode=35.230.176.185
addnode=35.199.27.31
addnode=80.211.188.25
addnode=45.76.131.138
addnode=172.245.36.4
addnode=159.89.128.75
addnode=81.169.214.103
addnode=209.250.236.200
addnode=188.187.188.194
addnode=199.247.13.241
addnode=210.211.124.189
addnode=104.238.161.88
addnode=213.52.129.183
addnode=138.197.216.71
addnode=198.58.115.246
addnode=172.105.224.65
addnode=173.230.141.205
addnode=217.69.3.8
addnode=45.79.66.44
addnode=95.96.104.94
addnode=198.13.47.101
addnode=104.207.134.81
addnode=173.199.115.226
addnode=178.62.204.40
addnode=45.32.215.41
addnode=85.217.171.181
addnode=35.186.174.191
```

Save the file, restart the wallet, if you previously had a sync issue, this should fix it.

# Wait for Sync

Wait for the wallet to fully sync.
Goto 'Receive' tab on the wallet.
Enter a label you will use for receiving your coins, no quantity entry is required.
Click 'Request Payment'
You will be displayed your recieving address, send your coins to this address.

# Congrats, you now have FGC in your wallet.
