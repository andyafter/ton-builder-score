# Builder Score Tech Spec

## Introduction

### 1.1 Purpose

This documentation is to provide details of the requirements, architecture and implementations for the TON Builder Score and Tbook Incentive Passport.

### 1.2 TON Builder Score

TON Builder Score is an index to measure a user’s impact on The Open Network web3 projects. It can:
Help TON community participants digitalize their impact. Improve community participation.
Help new projects onboard TON, and provide Leaderboard for them to efficiently find the top community users to help them build their business.
TON Builder Score is implemented on Incentive Passport

## Demands description

### 2.1 Incentive Passport Telegram Mini App

Register for a Tbook Incentive Passport account by connecting their TON wallet, in the Incentive Passport TMA.
Enable users to view their Builder Scores and index metrics in telegram

### 2.2 Multi-Chain Attestation Integration

Attest users' activies on multiple blockchains and web2 platforms, and update their Builder Scores. This enables users to translate their impact into a singular index.
Generate TON Builder Score through one click with TON address.

### 2.3 Build TON Builder Score Leaderboard

Users need to be able to earn TON Builder Score points based on their on-chain activities attestations. With TON Builder Score Users will be able to measure and demonstrate their impact on TON.
Leaderboard should be able to show the rank of high impact users. The rank could provide Each user needs to have a public profile showing their TON Builder Score and key stats.
When web3 projects onboard TON, they can find the profiles of high impact crowd on the Leaderboard, and use rewards(airdrops, tokens, NFTs etc.) to attract their participation in promotion campaigns.

## Product Implementation

### 3.1 Product Architecture

1. Incentive passport
   Provides functionalities for identity verification. A user can create an incentive passport by connecting with TON wallet.
   Users can attest their activities and profiles from multiple blockchains and web2 services(X, Meta etc.) through Incentive Passport.
   Users should get access to their incentive passport in the TBook TMA. They can manage and view their TON Builder Scores on the TBook Incentive Passport TMA.
2. TON Builder Score Engine
   TON Builder Score is an indicator of: activeness, holdings and coinage, engagement, multi-chain wealth and social impact.
   Handles the calculation of users’ TON Builder Scores and user ranking.
   Each time a user attests certain data, TON Builder Score Engine will update the TOP users if there's any changes in the leaderboard. The update will be in the manner of a priority queue.
3. Leaderboard
   The user interface that provides the ranking of users' TON Builder Score. Leaderboard provides a UI with the high ranking individuals.
   Users can open TON Builder Score Leaderboard in his own incentive passport TMA.

## Milestones

## Conclusion

The TON Builder Score will be a critical piece of infrastructure to accelerate the growth of the web3 projects built on TON and those who want to onboard TON. The key value of TON Builder Score would be:

1. Creating a standard for user activity and reputation measurement on TON. Enabling users to digitalize their impact.
2. Helping projects to airdrop to a user crowd that has the highest potential of boosting their growth efficiently.
3. Advocate competition among community participants, improve overall performance of web3 projects.
4. Enable users to monetize their impact on TON.

In the initial phase of Tbook, we need to work with the top applications on TON network as the cold start phase. Thus we need help from TON to connect us with these applications.
With the integration of TON Builder Score in Tbook Incentive Passport, we will be able to help projects built on TON to gain their advantages on the market quickly. We will also be able to bring more high quality community builders and web3 projects into the TON ecosystem.
