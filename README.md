# TInterface
+ We will build the v0.01 of Textverse interface.
+ About TInterface definition:[Engine Interface](https://github.com/DAO-SX/ethos/blob/main/docs/product/architechure.md)
+ Product will provide :
+ Landing page, login with metamask.
+ Mint your own vNFT(hero NFT, will belongs to TID, DID of Textverse, named tNFT).
+ Join the game and get the newbie package in the default Metaverse.
  
 ## Landing page
+ Have't intergrated with SIWE, later.
+ Just login with wallet.

## Mint vNFT
+ Can mint your name and view basic JSON file.
+ Will store to NFT.storage.
+ Calculate the CID and store into ON Chain Contract for your Assets.
## Load and Save
+ Join the Game, will load the vNFT of your wallet.
+ load newest CID and the JSON file into game.
+ If you fight with monster or get materials and save game manually, will need some gas and token(LToken) cost.
+ You will store your assets to IPFS and Chain.
+ If you get a **Unique Artifact**, it will be a NFT and will belongs to your Metamask wallet address, **do not need to save manually**.

## Enjoin your journey

## Developer quick start
+ 1> react init
+ create a empty git repo in github:[repo](https://github.com/DAO-SX/textverse-interface)
+ run in your mac terminal:
+ 
```
npx create-react-app tint
cd tint
git init
git commit -m "react init commit"
git branch -M main
git remote add origin git@github.com:DAO-SX/textverse-interface.git
git push -u origin main
```
+ and then hardhat init
```
npx hardhat
init in your prj directory
+ 2> .env

```
ALCHEMY_RINKEBY_API_URL=https://rinkeby.infura.io/v3/d3SSSd7279b43XXXXXXXX
METAMASK_RINKEBY_PRIVATE_KEY=71719XXXa1c9bXXXXXXX08a009XXXXXXXXX
ETHERSCAN_API_KEY=MZXXXXFX482XXXXXXXQ6V6B4XXXXS

REACT_APP_CONTRACT_ADDRESS=0xbfD7c7Cf07DA4114D2cFa477a6A38E335Aa8Fb74
REACT_APP_NFT_STORAGE_API_KEY=iOiXXXXXInR5XXIkXXeyJzdWIiOiJkaWQ6ZXRXXXXX
```
+ How to create or get these keys: [start readme](https://github.com/jhfnetboy/filecoin_nft_starter)


+ 3> hardhat config
```
```


### git cheat snip
…or create a new repository on the command line
echo "# textverse-interface" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin git@github.com:DAO-SX/textverse-interface.git
git push -u origin main
…or push an existing repository from the command line
git remote add origin git@github.com:DAO-SX/textverse-interface.git
git branch -M main
git push -u origin main
…or import code from another repository
You can initialize this repository with code from a Subversion, Mercurial, or TFS project.




