# Auction list

## Purpose

The purpose of the auction list is to allow a user to discover and distinguish between vetted and unvetted auctions.

## Implementation

Lists will be implemented as a table with an explanation of what curated auctions are at the top for vetted and a warning for unvetted. There will also be a link to learn more about the curators and apply to be added to their list. The information and application can be handled off our platform.

### Headers

#### **Issuer**

- Description: This is the creator of the auction and issuer of debt
- Value: image and name of org
  - Ex: 🦄 Uniswap

#### **Offering amount**

- Description: This is the max issuance provided by the issuer
- Value: amount and type of asset
  - Ex: 50,000,000 FEI

#### **Auction status**

- Description: The current status of the auction
- Value: Depends on auction state
  - Examples:
    - Upcoming: Starting in 3.5 days
    - Active: Ending in 1.2 days
    - Ended: Ended 23 days ago

#### **Interest rate**

- Description: Depends on auction state
  - Upcoming: The maximum interest rate set by the issuer
  - Active: The interest rate that would be used if the auction were to end now
  - Ended: The interest rate that was set in the auction
- Value: percent
  - Ex: 12%

#### **Convertible**

- Description: Is the bond convertible or not
- Value: Depends
  - If no, then no.
  - If yes, then image of token convertible into

#### **Term**

- Description: How long until the bond is repaid
- Value: months
  - Ex: 12 months

#### **Collateral %**

- Description: Collateral coverage of the bond offering
- Value: percent and type of asset
  - Ex: 50% UNI

## Examples

### Copper Launch

#### Auction panel

![](../../../assets/copper/auction_discovery.png)

#### Vetted list

![](../../../assets/copper/vetted_auction_list.png)

#### Unvetted list

![](../../../assets/copper/unvetted_auction_list.png)
