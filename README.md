# Boardly

A Granular Web3 Exploration and Curation Platform with Targeted Sharing and Universal Following.
Boardly empowers you to navigate the expansive web3 world, across multiple chains. Discover NFTs and hidden gems, then organise them into stunning, shareable boards.

**Problem:** Fragmented exploration, limited content visibility, and a lack of user connection hinder a truly engaging web3 experience.

**Solution:** Boardly bridges these gaps by offering a unified platform for:

- **Chain agnostic exploration**: Discover NFTs and web3 content across multiple blockchains.

- **Granular Curation**: Create public, private or semi-private boards to curate and share your discoveries

- **Universal Following System**: Follow other users and their boards based on Universal Profiles, fostering connection and knowledge sharing.

[Checking MVP Demo](https://alpha.boardly.xyz)

## Key Features

### Privacy by Design
Shield sensitive discoveries with Lit Protocol's decentralized storage. Share selectively with trusted groups using semi-private boards, ensuring your control over valuable insights.

### Beyond Images
Move beyond static images with the power of LSPs (Layer-2 Service Providers). Craft dynamic on-chain content pushing the boundaries of web3 creation.

### Universal Following
Connect with like-minded individuals across the web3 landscape. Leverage Universal Profiles to find relevant content creators and follow their curated gems, fostering a network of shared discovery.

### Infinite Canvas
Ditch the grid and unleash your creativity. Design stunning moodboards with complete freedom on an infinite canvas. Arrange content intuitively, tell a visual story,and break away from the limitations of traditional layouts.

### Curated Feeds
Empower yourself. Boardly's explore tools prioritize user control. Personalize your feed to see exactly what interests you, filtering out noise and focusing on the web3 content that sparks your passion.

## What is a Board?

A board is a LSP8 Collection. Using unlimited metadata, we will store the board arrangements, tokens, metadata and access control conditions for Lit Protocol.

Using the KeyManager, we plan to make boards collaborative. By giving permissions to other people to execute functions on this token to update specific things like arrangement, access control conditions or metadata.

Users can also create there own NFTs and content to put in this board, and they can make it specific to be only visible within this board.

## What is a Universal Follower System?

With the help of LSP1, LSP17 and LSP18, we can update metadata in every user's profile around who are following them and who the user is following. This give the control of followers/following to the user and the data is stored in their Universal Profile.

If not possible/feasible/accepting via LSP1 implementation, we plan to create a custom adapter contract which can enable users to enable the follow system on their profiles.

By configuring extensions, users can start charging their followers a fees and receive the tokens directly in their Profile. The extensions themselves can be upgraded/changed/removed.

## What is a Semi Private Boards

All the access control related details are stored as part of token metadata. This is applicable for any boards that are created by the users or any custom content that is created using this platform.

We plan to build a @erc725/erc725.js general tool for all developers so that they can directly encrypt/decrypt data for a universal profile.

## Wallet Less / Keyless web3 Accounts

There are several tools that are offering key/wallet management tools powered by web2 authentication methods. Lit Protocol also provides this tool to allow users to control their accounts even when using web2 modes of authentication.

We are going to integrate Lit Protocols key management solutions to make onboarding seamless, and yet having a Universal Profile from the moment they sign up for the platform. This is made possible by the power of KeyManager to associate specific permissions to specific keys.

## Custom Explore Page Feeds

Imagine a world where your online experience isn't dictated by algorithms, but crafted by your own passions. Our research into custom explore page feeds is about putting the power of discovery in your hands. By allowing you to configure feeds based on your interests, you'll cut through the noise and find content that truly resonates. This doesn't just benefit you – creators can build targeted audiences around their niche expertise. The ability to monetize these custom feeds fosters a thriving community of content curators, while users gain access to a wealth of diverse and engaging content. It's a win-win for everyone, fostering a dynamic online space built around shared interests.