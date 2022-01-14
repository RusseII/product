# Individual auction page

## State: Before Auction Started

## Users

- Potential auction participant
- Auction creator/manager

## User assumptions

### Potential auction participant

- Knows how the auction works
  - User came to this page through landing page which has links to educational content
  - If they don't know how it works, they can learn via the link in the navbar

## User needs

### Potential auction participant

| User Wants                                                          | Product Needs                                         |
| ------------------------------------------------------------------- | ----------------------------------------------------- |
| Wants to determine whether they want to participate in this auction | Needs information regarding the upcoming bond auction |

### Auction creator/manager

| Wants                       | Needs                      |
| --------------------------- | -------------------------- |
| Wants to view the auction   |                            |
| Wants to manage the auction | Needs a management section |

## Inspirations

- [Copper Launch](assets/copper/auction_page_pre.png)

## Features

### Warning

Explains to users the potential risk of participating in the auction.

- [Example](assets/copper/warning.png)

### Auction information

- Issuer name
  - Ex: Uniswap
- Auction status
  - Ex: Upcoming
- Auction duration
  - Ex: 7 days
- Days/time until auction starts
  - Ex: 7 days, 3 hours
- Bond offering size
  - \$50M
- Total bid volume
  - Empty state
  - Ex: -
- Minimum funding threshold
  - Ex: \$30M
- Auction description
  - Abridged version of prospectus to give the reader a brief overview of who the issuer is and why they are issuing a bond
- Link to prospectus
  - Detailed document outlining all aspects of the bond offering
  - Ex: [Prospectus](https://www.sec.gov/Archives/edgar/data/320193/000119312513184506/d527270d424b2.htm)
- Maximum bond interest rate
  - The auction determines interest rate based on supply and demand. This is the maximum interest rate the issuer is willing to pay.
  - Ex: 15%
- Current auction interest rate
  - Empty state
  - Ex: -
- Bond Term length
  - Ex: 12 months
- Bond Collateral stats
  - Type and amount
    - Ex: 500,000 UNI
  - Token contract address
  - Current collateralization ratio
- Convertibility
  - Are the bonds redeemable for a pro-rata portion of the collateral tokens?
  - Yes/No
  - Breakeven token price of convertibility
    - Ex: \$75
  - Current token price
    - Ex: \$25
  - Projected returns graph
    - [Example](assets/convertible_bond_graph.png)
      - This will be replaced by a better example

### Bid submission

- This is where users will submit bids once auction is live
- Examples
  - [Copper](assets/copper/bidding_pre.png)

### Orderbook

- This is where bids will be displayed once auction is live
- Examples
  - [Copper](assets/copper/order_book.png)
  - [Gnosis](assets/gnosis/order_book.png)

### Your orders

- This is where a users bids will be displayed once auction is live and a user has placed a bid
- Examples
  - [Copper](assets/copper/order_book_empty.png)
  - [Gnosis](assets/gnosis/my_orders_empty.png)

### Graph

- This is a visual representation of all bids
- Tells user current state of the auction/pricing at a glance
- Examples
  - [Copper](assets/copper/order_book_graph.png)
  - [Gnosis](assets/gnosis/order_book_graph.png)

### Auction management

- Allows auction creator to manage auction
  - Cancel auction
- Examples
  - [Copper](assets/copper/auction_management.png)
