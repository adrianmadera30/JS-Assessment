# NFT Minting Application

This application allows users to mint NFTs (Non-Fungible Tokens) with specific metadata attributes and display the total collection of minted NFTs. The NFTs are stored in an array and each NFT's metadata includes name, eye color, shirt type, and bling.

## Table of Contents

- [Getting Started](#getting-started)
- [Functions](#functions)
  - [`mintNFT`](#mintnft)
  - [`listNFTs`](#listnfts)
  - [`getTotalSupply`](#gettotalsupply)
- [Usage](#usage)

## Getting Started

To run this application, you need a JavaScript runtime environment, such as Node.js, or a web browser console.

1. **Clone the repository** (if applicable) or copy the code into your preferred environment.
2. **Run the code** to see the NFT minting and listing in action.

## Functions

### `mintNFT`

This function creates a new NFT object with specified metadata and stores it in the `NFTs` array.

#### Parameters

- `_name` (string): The name of the NFT.
- `_eyeColor` (string): The eye color of the NFT.
- `_shirtType` (string): The type of shirt the NFT is wearing.
- `_bling` (string): The bling the NFT is wearing.

#### Usage

```javascript
mintNFT("Alice", "Green", "T-Shirt", "Diamond Necklace");
```

### `listNFTs`

This function iterates over the `NFTs` array and prints out the metadata of each NFT.

#### Usage

```javascript
listNFTs();
```

### `getTotalSupply`

This function prints the total number of minted NFTs to the console.

#### Usage

```javascript
getTotalSupply();
```

## Usage

Here is an example of how to use the provided functions to mint NFTs, list them, and get the total supply:

```javascript
// Minting NFTs
mintNFT("Bob", "Blue", "Hoodie", "Gold Chain");
mintNFT("Adrian", "Black", "Hoodie", "Silver Bracelet");
mintNFT("Madera", "White", "Hoodie", "Gold Watch");

// Listing all NFTs
listNFTs();

// Getting the total supply of NFTs
getTotalSupply();
```

After running the code, you should see the following output:

```
Minted: Bob
Minted: Adrian
Minted: Madera

ID:         1
Name:       Bob
Eyecolor:   Blue
Shirt Type: Hoodie
Bling:      Gold Chain

ID:         2
Name:       Adrian
Eyecolor:   Black
Shirt Type: Hoodie
Bling:      Silver Bracelet

ID:         3
Name:       Madera
Eyecolor:   White
Shirt Type: Hoodie
Bling:      Gold Watch

3
```

This output shows the details of each NFT and the total number of NFTs minted.

### Author
- Adrian B. Madera
