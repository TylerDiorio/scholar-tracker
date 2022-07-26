# scholar-tracker
This repository will store the code needed to run a Discord Bot which automatically logs earnings from an arbitrary amount of scholars

Users will be able to interact with the following commands in servers that host thescholar-tracker: 


```
!getDegens
```

EXAMPLES:

```
!honor 0x7daa42ac914a515cb6c3b1ac147e5b997abe3495985680fee392c52dfad6d1d7 0x01beda4693c0c5b06576555688193a0332017092adc71a63db298da6254cc388
```
```
!addWallets 0x6C485b8A1b5DE16Bd7De7Da6b90d88446B7aE824 0x1C233950Fb282F107c4710D05F4c0a10F31DcA46 0x8bEd15d3C26159f9512EdC2696B0292C9917ce56 0x8a04Df9205eFDB0C7434aBE33274117E881fd704
```
The AWS database will be used to keep a running tally of total ETH/NFT assets transacted so users can easily understand the reputation of any individual with which they are contemplating transacting with.

GETTING STARTED

Simply run the following command in the desired directory of choice:

```
git clone https://github.com/Oreo-web3/scholar-tracker.git
```

REQUIRED PACKAGES:

The nft-honor-tracker requires the ethers.js, discord.js, aws-sdk.js, and dotenv API's in order to function properly. Please use the following commands to prepare an initially empty directory for the required dependencies using NPM:

```
npm init -y
npm install --save ethers
npm install discord.js
npm install aws-sdk
npm install dotenv --save
```
