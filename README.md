# scholar-tracker
This repository will store the code needed to run a Discord Bot which automatically logs earnings from an arbitrary amount of scholars

The typical flow for this Discord bot will be as follows: (1) A Voxie owner runs `!regOwner` to register themself into the database; (2) the Voxie owner runs `!AddScholar @Scholar1 @Scholar2 @ScholarN` to register each of their scholars to the database; (3) the Scholars then perform daily logs by calling the `!logScholar` command in the Discord, then responding to idnividual forms via DM's; (4) the Voxie owner can then request a print-out of their Statistics over DM's using `!dmLogs` or into the public chat using `!showLogs`. 

## Commands:
Users will be able to interact with the following commands in servers that host the scholar-tracker:

```
!regOwner
```
```
!addScholar @Scholar1 @Scholar2 @ScholarN
```
```
!logScholar
```
```
!dmLogs
```
```
!showLogs
```



### Examples:

```
!add-Scholar @Remista @f0rest @killmongerBR @davidsf @aqeoj @tuka
```
```
!logScholar
```
If the Scholar is registered in the database, they will be DM'ed with a form to fill-out. The form will prompt the Scholar to enter the following information:
Hours played: 
$VOXEL earned in those hours:
Number of Wins: (Optional)
Number of Losses: (Optional)

## GETTING STARTED

Simply run the following command in the desired directory of choice:

```
git clone https://github.com/Oreo-web3/scholar-tracker.git
```

### REQUIRED PACKAGES:

The nft-honor-tracker requires the ethers.js, discord.js, aws-sdk.js, and dotenv API's in order to function properly. Please use the following commands to prepare an initially empty directory for the required dependencies using NPM:

```
npm init -y
npm install --save ethers
npm install discord.js
npm install aws-sdk
npm install dotenv --save
```
