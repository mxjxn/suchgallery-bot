# SuchGallery Bot

This bot should interact with the farcaster timeline. 
When tagged with an artwork, it should be added to the list of NFTs available for curation on suchgallery.

For example:

`@suchgallery chain://eip155:1/erc721:0xa723a8a69d9b8cf0bc93b92f9cb41532c1a27f8f/11`

Formats that should be supported:

- OpenSea links
- Zora links
- Manifold links
- Etherscan links


The bot should take the NFT and retrieve its tokenURI, and then the metadata from there, and store that in the postgres database.
