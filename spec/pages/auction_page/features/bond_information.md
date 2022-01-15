# Bond information

## Purpose

The purpose of bond information is to display to the user necessary information regarding the bond offering. Some information displayed will change depending on the current state of the auction while others will always be displayed.

## States

- Upcoming
  - Auction has not started
- Active
  - Auction is ongoing
- Ended
  - Auction has ended

## Implementation

The auction information will be displayed toward the bottom of the page in a grid.

### Information to display

#### Auction description

- Description: Abridged version of prospectus to give the reader a brief overview of who the issuer is and why they are issuing a bond
- Value: paragraph

#### Prospectus

- Description: Link to prospectus
  - Detailed document outlining all aspects of the bond offering
- Value: link
  - Ex: [Prospectus](https://www.sec.gov/Archives/edgar/data/320193/000119312513184506/d527270d424b2.htm)

#### Bond Term length

- Description: Amount of time from the issuance event until the bond matures.
- Value: months
  - Ex: 12 months

#### Bond collateral

- Description: Type and amount of asset being provided as collateral for bond issuance.
- Value: number and type of asset

  - Ex: 500,000 UNI

#### Collateral contract address

- Description: Contract address of collateral asset
- Value: address
  - Ex: 0x...

#### Current collateralization ratio

- Description: Calculated by dividing value of collateral offered by total borrow amount.
- Value: percent
  - Ex: 50%

#### Convertibility

- Description: Whether or not the bonds are redeemable for a pro-rata portion of the collateral tokens
- Value: boolean

#### Breakeven token price of convertibility

- Description: The price a token has to increase to in order for bond redemption to be profitable at maturity
- Value: number and type of asset
  - Ex: 75 FEI

#### Current token price

- Description: The current price of the asset provided as collateral in terms of the borrowed asset
- Value: number and type of asset
  - Ex: 25 FEI

## Example

### Copper Launch

![](../../../assets/copper/bond_details.png)
