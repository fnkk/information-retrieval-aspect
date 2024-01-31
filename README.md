# information-retrieval-aspect
An idea of Artela Hackthon
# Project Background
In today's digital era, membership schemes are often seen as an investment by users for more services and conveniences. However, this model usually exists within centralized platforms, meaning ownership and control remain in the hands of the service providers. Our project is inspired by the transformation of membership schemes into a real asset owned by users. Through blockchain technology, we aim to return the ownership and control of assets back to the users themselves.

## Innovations
Returning Asset Ownership to Users: Beyond membership NFTs, we aim to return the ownership of user assets such as articles, music, photos, and videos back to the users.
Building a Future Web3 Application Ecosystem: In this ecosystem, data belongs to the users. Applications can only access this data with the user's consent, achieving a truly decentralized data management and service experience.
# Technical Implementation
To achieve the above objectives, we have designed the following two main technical components:

1. Personal Data Storage Contract (Contract 1)
Asset Registration: Users can register their assets, including NFTs and contract addresses, through Contract 1, making them queryable by different applications.
Asset Recording: Users can record their digital assets, such as published articles or videos. These assets can be fully on-chain or stored as IPFS hashes, while following specific protocols for access by different applications.
Asset Authorization Management: Users can authorize or revoke authorization of their assets to specific Dapps through Contract 1.
2. Application-Level Dapp Implementation
Creator and Viewer Interaction: Creators authorize their asset information to Contract 1, allowing Dapps to display this information; viewers can access these contents through Dapps.
## Application Examples:
DeFi Platforms: Upon login, if a user's assets include a membership NFT issued by a specific DeFi platform, the user may enjoy additional benefits.
Decentralized Forums: By binding to Contract 1 to retrieve user-authorized articles, forums can publish these articles for other users to read.
Through this approach, we not only enhance the autonomy and security of user assets but also lay the foundation for building a decentralized application ecosystem.