#MintForUkraine
#MINTFORUKRAINE
I thought some others would do this awhile ago, maybe they did I just didnt hear about it.. I have deep respect for the Ukrainian people, I have had some friends and co-workers there since 2004.

I’m happy to see NFT creators try and raise money to support Ukraine. But even in times like this we need to be vigilant against scammers!!

I’ve created a Smart Contract that lets ANYONE Mint an NFT with ANY artwork they want. The CREATOR of the NFT PAYS 0.01 ETH or 10 MATIC to mint the NFT. + gas.. this fee goes to Ukraine!

The Minting fee goes directly to the Ukrainian government’s verified wallet address. At any time, anyone can call the “Withdraw” method, which transfers the balance to Ukraine.

The addresses cant be changed, the contract has no owner.
YOU GET THE NFT, UKRAINE GETS THE MONEY!
The contracts are VERY SIMPLE, and VERIFIED!
I have RENOUNCED OWNERSHIP of the CONTRACTS!

Mint NFTs for Ukraine, all proceeds go directly to Ukraine, no middleman
How to MINT FOR UKRAINE!
1. Pick the artwork you want to use. A flag, a photo, whatever..
2. Upload your artwork to IPFS.
3. Update the sample metadata file with your Image IPFS hash.
Sample file here: ipfs://QmR8WZDTobS3uTMyt863rPMNCm8pGmi1Jm7JLAFSvmTW8u (Default Metadata file)
4. Upload the metadata file to IPFS.
5. Goto Etherscan, or Polygonscan.
6. Connect your wallet.
7. Invoke the safeMint function (like this)

Payable: 0.01 ETH or 10 MATIC per NFT (or more!)
Number: number of NFTs to mint
URI: ipfs:// hash of your metadata file.
VIDEO: https://vimeo.com/688192627/0fb2eb9171
There is no minting site currently, you can use etherscan to invoke the safemint function directly. (Watch the video!)
All funds go to: https://etherscan.io/.../0x165cd37b4c644c2921454429e7f935...
Withdraw function in the code
function withdraw() public {
uint balance = address(this).balance;
//VERIFIED UKRAINE ADDRESS
payable(0x165CD37b4C644C2921454429E7F9358d18A45e14).transfer(balance);
//https://twitter.com/Ukraine/status/1497594592438497282
}
Live Contracts:
Ethereum: 0x12D6B6B7d5e26fFFB7AEA9906aD8dB22EB7F7481
https://etherscan.io/.../0x12D6B6B7d5e26fFFB7AEA9906aD8dB...
https://rarible.com/.../0x12d6b6b7d5e26fffb7aea9906.../items
https://opensea.io/collection/mint-for-ukraine
Polygon: 0x12D6B6B7d5e26fFFB7AEA9906aD8dB22EB7F7481
https://polygonscan.com/.../0x12D6B6B7d5e26fFFB7AEA9906aD...
https://opensea.io/collection/mint-for-ukraine-polygon
Testnets:
Rinkeby: 0xA00486BFe696319DCBC97F1789b63693eC73df85
https://testnets.opensea.io/collection/mint-for-ukraine
https://rinkeby.rarible.com/mintforukraine/items
https://rinkeby.etherscan.io/.../0xa00486bfe696319dcbc97f...
Mumbai: 0xabFf1C4bD78f2B3ac806afdA51EF02ae3A543f0D
https://mumbai.polygonscan.com/.../0xabFf1C4bD78f2B3ac806...
https://testnets.opensea.io/colle.../mint-for-ukraine-mumbai
