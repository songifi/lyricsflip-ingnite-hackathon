# 🎵 LyricFlip – The On-chain Lyric Guessing Game

**Hackathon Submission Repository**

This repository serves as the central hub for our LyricFlip hackathon submission. LyricFlip is an on-chain lyric guessing game that challenges players to identify songs based on partial lyrics. Think of it as a music trivia meets blockchain — fast-paced, multiplayer, and decentralized!

We leveraged the power of **Starknet**, **Dojo**, and **Flutter** (via starknet.dart) to rebuild and enhance our originally React Native-based project specifically for this hackathon.


## Project Overview

**LyricFlip** is a lyric-based card game where players guess the song title or artist based on a snippet. The gameplay is fast and engaging:
- A card flips to reveal partial lyrics.
- Players must guess the correct answer before time runs out.
- Each round uses on-chain logic for transparency and fairness.

**Core Features:**
- On-chain gameplay logic using Cairo and Dojo
- Starknet-integrated frontend built in Flutter (starknet.dart)
- Originally developed in React Native but re-implemented in Flutter for the hackathon
- Multiplayer capability (with Kahoot-like energy!)
- Token reward system for winners

## Repository Structure

All source code for LyricFlip is distributed across multiple repositories. This is intentional for modularity and specialization.

### 🚀 Starknet.dart Frontend (Flutter)
- **Repo:** [lyricsflip-flutter](https://github.com/songifi/lyricsflip-flutter)
-  Built with Flutter using [starknet.dart](https://github.com/0xSpaceShard/starknet.dart)
-  Handles player interaction, real-time gameplay, and integration with the Dojo-powered smart contracts.

###  Smart Contract Logic (Dojo on Starknet)
-  **Repo:** [lyricsflip_contract](https://github.com/songifi/lyricsflip_contract)
-  All on-chain logic, game flow, and state management is implemented here using Cairo with the Dojo framework.

###  Original Mobile Version (React Native)
-  **Repo:** [lyricsflip_mobile](https://github.com/songifi/lyricsflip_mobile)
-  This was our original implementation in React Native.
-  We pivoted to starknet.dart (Flutter) to better align with the hackathon requirements and demonstrate deeper ecosystem integration.


## Why We Pivoted

While LyricFlip was originally developed as a React Native app, this hackathon encouraged a deeper dive into **Starknet-native** tooling. We made a deliberate decision to:
- Rebuild the app in **Flutter using starknet.dart** for better blockchain-native integration.
- Implement smart contracts using **Dojo** and **Cairo** for a seamless Starknet experience.
- Focus on **on-chain game state management**, ensuring transparency and immutability.

---

## Contributors

- **Lead Developer & PM:** [@Xaxxoo](https://github.com/xaxxoo)
- **Smart Contract Engineer:**[manlikeHB][ https://github.com/xaxxoo
- **Frontend, Mobile UI & Integration & UX:** [Peteroche](https://github.com/peteroche)


## Submission Note

This repo is a **submission aggregator** and contains no standalone code. Please refer to the linked repositories for complete implementation.

Thank you for reviewing our project. We’re excited about LyricFlip and the potential of on-chain gaming — especially when it brings music and trivia together!



