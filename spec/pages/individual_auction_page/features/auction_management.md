# Auction management

## Purpose

The purpose of auction management is to allow the auctioneer to manage the auction.

## States

- Upcoming
  - Auction has not started
- Active
  - Auction is ongoing
- Ended
  - Auction has ended

## Implementation

Should only be viewable by the creator of the auction.

### Functionality

#### Cancel auction **(Upcoming only)**

- Description: The auction creator can cancel the auction before it has begun.
- Value: button

#### Execute auction and claim funds **(Ended only)**

- Description: The auction creator can execute the auction after it has ended. This action is permissionless but it is the responsibility of the creator. Funds are automatically distributed to the auction creator's wallet.
- Value: button

## Examples

### Copper Launch

![](../../../assets/copper/auction_management.png)
