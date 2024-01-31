# information-retrieval-aspect
An idea of Artela aspect use case.
## Project Background
### 会员资产化与数据去中心化
受到会员模式的启发，我们将会员资格视为用户购买的一种资产，其价值在于能够获取更多服务。在传统APP模式中，会员数据多存储于中心化的服务器，我们的目标是颠覆这一模式，将资产的所有权和数据的控制权交还给用户，确保其自主性和安全性。

### 资产多样化与Web2的局限性
我们追求的不仅是会员NFT，还包括用户的其他资产，如文章、音乐、图片、视频等。这些资产的所有权也将回归用户手中，突破Web2模式中数字资产控制权多在服务提供商手中的局限，从而增强用户的自由和隐私。
![ChangeOfHope]('./img/ChangeOfHope.png')

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