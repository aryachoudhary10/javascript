# NFT Minting Application

## Overview

This simple JavaScript application demonstrates a basic NFT (Non-Fungible Token) minting functionality. It includes functions to mint NFTs with specific metadata, list all minted NFTs, and retrieve the total supply of minted NFTs.

## Functions

### `mintNFT(_name, _eyeColor, _shirtType, _bling)`

This function creates an NFT object with metadata provided as parameters and stores it in the `NFTs` array.

### `listNFTs()`

This function iterates through the array of minted NFTs and prints their metadata, including ID, name, eye color, shirt type, and bling, to the console.

### `getTotalSupply()`

This function prints the total number of minted NFTs to the console.

## Usage

1. Open your JavaScript environment (e.g., a browser console or Node.js environment).

2. Copy and paste the provided JavaScript code into your environment.

3. Call the functions to demonstrate the minting, listing, and total supply functionalities.

## Example Usage

```javascript
// Mint NFTs
mintNFT("Harsh", "Black", "Tshirt", "Gold chain");
mintNFT("Sonu", "Black", "Check shirt", "Silver chain");
mintNFT("Atishi", "Brown", "Hoodie", "Diamond ring");

// List NFTs
listNFTs();

// Get Total Supply
getTotalSupply();
