# STAREX Cross Chain Blockchain Game

Welcome to the STAREX Blockchain Game repository! This project explores the concept of CROSS-CHAIN gaming and aims to provide a unique gaming experience across various blockchain networks.

## Branches Overview

- **master:** This branch serves as the main hub for overall information and project overview.
- **klaytn-hackathon:** Submitted for the Klaytn hackathon, featuring both app and contract development.

> ⚠️ **Important Note:** Each branch may have different implementations and results, even if the hackathon duration is the same. Each Hackathon may have different developments, some focusing exclusively on mobile development or contract development. Please review the README in each branch for specific details about the submission.

**Demo Links:**

- [STAREX Klaytn Hackathon Demo](https://starex-klaytn.vercel.app)

Introducing STAR-EX, (EXPLORE, EXPEDITION) a groundbreaking CROSS-CHAIN web3 game that combines the thrill of exploration with the excitement of an incremental speed challenge.

_Due to the risk associated with the hackathon, detailed information about the space gameplay is limited and will be given detail on upcoming whitepaper. However, we can share a glimpse of what's to come. The gameplay will feature different dimensions utilizing multiple networks, fostering a unique environment for players._

This innovative concept encourages NETWORK COLLABORATION, where minority networks stand to gain exposure through in-game interactions and seasonal events. The dynamic in-game economy will be influenced by factors specific to each network, affecting asset values and drop rates. Stay tuned for more exciting details as we navigate the challenges of the hackathon and bring this cosmic adventure to life.

For Solo Exploration, players take control of a spaceship on an expedition through space, aptly named "ex" for exploration. Much like the classic Temple Run but now in 360 space with more fun abilities, the game dynamically increases in speed, presenting players with ever-growing challenges to survive.

In this interstellar adventure, players must navigate their spaceship through a cosmic obstacle course, avoiding rocks, monsters, and powerful boss encounters. The longer they last, the faster and more challenging the game becomes. Survival is key, but there's a catch—limited supplies of abilities and energy are essential for prolonged gameplay. Players can discover unique items scattered throughout the in-game space. These items, represented as NFTs (Non-Fungible Tokens), not only grant special abilities but can also be traded in a marketplace, allowing players to turn their in-game achievements into real-world profit. Crafting items is crucial for obtaining the energy needed to activate powerful abilities, providing an additional layer of strategy. The scarcity of these resources adds depth to the gameplay, requiring players to make strategic decisions about when to use their items and abilities.

As the game progresses, Star-Ex evolves beyond its action roots. Players can choose to stake their spaceships as playing the MISSION and rewarding stake, transforming the experience into an idle game. This integration of action and idle gaming mechanics, combined with the NFT marketplace, creates a unique and sustainable gaming ecosystem. This game is actually not just action-arcade but my goal to make it into "Action-Idle RPG" as each spaceship has their own abilities, and some dimension location will be some weakness and strength depending for each spaceship, while it also provide stats that will carry within each NFTs.

## Gameplay Highlights

- **360 Space Exploration:** Experience the classic Temple Run concept in 360 space with additional fun abilities.
- **Increasing Speed Challenge:** Survive and thrive as the game dynamically increases in speed.
- **Unique NFT Items:** Discover and collect NFTs representing unique in-game items, granting special abilities and tradable in a marketplace.
- **Crafting and Strategy:** Craft items crucial for obtaining energy to activate powerful abilities, adding depth and strategy to gameplay.
- **Action-Idle Integration:** Stake your spaceships, transforming the experience into an idle game with a rewarding stake.

## Action-Idle RPG Experience

STAR-EX goes beyond its action roots, aiming to become an "Action-Idle RPG." Each spaceship has unique abilities, and dimension locations have strengths and weaknesses for each spaceship. Stats carry within the KIP-7 (LSP-8 standard), creating a rich gaming experience.

## Technical Details

**Technology Stack:**

- Frontend: React
- Graphics: Three.js library with WEBGPU utilization
- Backend: Node.js for score collection and leaderboard
- Future: Game-server for PvP gameplay

**Smart Contracts Used:**

- (2x) KIP-7 (LSP-7)
- (3x) KIP-17 (LSP-8 collection)
- (1x) KIP-37 (LSP-8 with ID)

**Smart Contract Flow:**

1. Players play and obtain items through in-game exploration.
2. Backend records the items and provides an EIP712 signature.
3. Users use the signature to mint their NFTs through the manager contract.
4. Manager contract validates the signature and allows users to mint.

## Game Development Insights

- The game utilizes React and the Three.js library for enhanced graphics using WEBGPU.
- Smart contracts include (2x) KIP-7, (3x) KIP-17 collection, and (1x) KIP-37 with ID.
- Due to a hackathon time limit, contracts are not finalized, but the flow is outlined.

## Gamefi and NFTs

- Spaceships are represented as NFTs.
- Ticket-NFTs enhance gameplay in high-rate drop dimensions.
- Seasonal NFT-pass provides auto-tickets at a lower cost.
- The game is still enjoyable without NFTs, emphasizing a fun and challenging experience.

## Demo Preview

The demo showcases one ability, a single map, and a limited set of features for security reasons. Stay tuned for future updates as the game evolves and becomes ready for a full showdown.

> **Note:** Due to security concerns, the demo showcases limited features, and certain aspects, features, abilities, map, and concept are intentionally kept undisclosed until the full release.

For more information, feedback, or inquiries, please contact our development team.

# Development Milestones

## Past Achievements (November - During Hackathon)

- Lobby interfaces
- Basic movement game
- Abilities visual
- Effects implemented
- In-game interface
- Procedural rocks
- Contracts architecture
- Contracts integration
- Shop + inventory prototype open

## Roadmap Next

### App-System

- UI/UX rework interface lobby
- Backend leaderboard
- Quests rework

### Gameplay System

- Procedural generator update on obstacle and challenge
- Map or radar
- Visual effects
- Interface in-game

### Blockchain Relation

- Contracts refactor + coverages + completion
- Contract integration with backend
- Auction contracts
- Crafting contracts
- Staking NFT contracts

## Beta Phase Preparation

- Minting for 1st iteration spaceships (purchase by native tokens)

## Tokenomic Phase

- GEMS launch
- Staking contract release

## Game Release

- Release game solo

## Next Year Plans

- PvP system

### Future Plans

In the future, an open-source repository named "map-maker" will be introduced to the community. This repository will empower community members to contribute to the game's expansive world by creating maps. Contributors may receive points from the DAO community and potentially be rewarded with royalties or other incentives.

This initiative is inspired by games like Warcraft, where user-generated content significantly enhances the gaming experience.

---

**Happy gaming! 🚀**
