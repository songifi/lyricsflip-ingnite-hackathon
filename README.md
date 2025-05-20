# 🎵 LyricFlip – Hackathon Submission Repository

This repository serves as the central hub for our LyricFlip hackathon submission. LyricFlip is an on-chain lyric guessing game that challenges players to identify songs based on partial lyrics. Think of it as a music trivia meets blockchain — fast-paced, multiplayer, and decentralized!

We leveraged the power of **Starknet**, **Dojo**, **Flutter** (via starknet.dart), and **Next.js** to bring LyricFlip to life for this hackathon.


##  Project Overview

**LyricFlip** is a lyric-based card game where players guess the song title or artist based on a snippet. The gameplay is fast and engaging:
- A card flips to reveal partial lyrics.
- Players must guess the correct answer before time runs out.
- Each round uses on-chain logic for transparency and fairness.

**Core Features:**
- On-chain gameplay logic using Cairo and Dojo
- Starknet-integrated frontend built with Flutter (`starknet.dart`)
- Web frontend with Next.js for contract interaction and Cartridge integration
- Originally developed in React Native but re-implemented for the hackathon
- Multiplayer capability (with Kahoot-like energy!)
- Token reward system for winners


## Repository Structure

All source code for LyricFlip is distributed across multiple repositories. This is intentional for modularity and specialization.

###  Flutter Frontend (starknet.dart)
-  **Repo:** [lyricsflip-flutter](https://github.com/songifi/lyricsflip-flutter)
-  Built with Flutter using [starknet.dart](https://github.com/0xSpaceShard/starknet.dart)
-  Handles mobile interaction, real-time gameplay, and integrates with Dojo contracts.

###  Web Frontend (Next.js + Cartridge)
-  **Repo:** [lyricsflip_frontend](https://github.com/songifi/lyricsflip_frontend)
-  Built with Next.js and tailored for **Cartridge track** integration.
-  Provides a browser-based interface for users to interact with the smart contracts and manage game sessions.

###  Smart Contract Logic (Dojo on Starknet)
-  **Repo:** [lyricsflip_contract](https://github.com/songifi/lyricsflip_contract)
-  All on-chain logic, game flow, and state management is implemented here using Cairo with the Dojo framework.

###  Original Mobile Version (React Native)
-  **Repo:** [lyricsflip_mobile](https://github.com/songifi/lyricsflip_mobile)
-  Our original React Native implementation before transitioning to Flutter.
-  Rewritten for the hackathon to explore Starknet-native tools.


## Why We Pivoted

LyricFlip was initially built as a React Native mobile app. For this hackathon, we shifted direction to:

- Showcase a **blockchain-native mobile app** using Flutter and starknet.dart.
- Build a **Cartridge-compatible frontend** in Next.js to engage users directly through web.
- Leverage **Dojo and Cairo** for smart contract logic and on-chain state transparency.

This pivot allowed us to align more closely with the goals of the hackathon and contribute to multiple ecosystem tracks.


## 🏁 Hackathon Tracks We’re Contributing To

-  **Cartridge Track** — via [lyricsflip_frontend](https://github.com/songifi/lyricsflip_frontend)
-  **starknet.dart Track** — via [lyricsflip-flutter](https://github.com/songifi/lyricsflip-flutter)
-  **Dojo Track** — via [lyricsflip_contract](https://github.com/songifi/lyricsflip-contract)


##  Submission Note

This repo is a **submission aggregator** and contains no standalone code. Please refer to the linked repositories for the complete implementation.

Thank you for reviewing our project. We’re excited about LyricFlip and the potential of on-chain gaming — especially when it brings music and trivia together!
