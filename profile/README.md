# MAID - Multi Access Incentive Distribution 

## Overview
MAID is a coupon factory that allows protocols to reward users with custom ERC3525 coupons based on custom requirements and conditions. By bringing the nostalgic charm of loyalty stamp cards into the realm of Web3, we provide a friendly and seamless solution for protocol users and developers.

## Product Description

Imagine a world where the concept of paper stamp cards has been transformed into a digital wonder, and protocol users can collect stamps for a variety of Web3 services.

MAID offers an interface for protocol developers to implement verification logic, allowing them to define their own requirements for users to obtain stamps. Once all the requirements are met, users are rewarded with ERC3525 tokens (Semi-Fungible Tokens). Developers are also expected to implement the logic determining how these rewards can be used, such as token allocation or airdrops, in-protocol discounts, and exclusive member benefits.

## Implementation Details

The Factory contract is responsible for managing all the coupons. Developers should implement their requirements logic and add it to the Factory. Users interact with the Factory when they want to claim their rewards. The Factory forwards the verification logic to the appropriate coupon logic, and if successful, rewards users with the ERC3525 token.

## Source code

[Frontend](https://github.com/ETH-TOKYO-2023/refactored-sniffle) | 
[Contracts](https://github.com/ETH-TOKYO-2023/super-octo-robot)


