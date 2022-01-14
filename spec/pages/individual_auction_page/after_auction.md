# Individual auction page

## State: Auction Ended

## Users

- Auction participants
- Auction creator/manager

## User needs

### Potential auction participant

| User Wants                                                   | Product Needs                                             |
| ------------------------------------------------------------ | --------------------------------------------------------- |
| Wants to see if their order got filled                       | Needs status of orders to update to filled/not filled     |
| Wants to see overview of past auction                        | Needs to show orders, settled pricing, etc                |
| Wants to claim bonds purchased or funds from unfilled orders | Needs to allow claiming of assets                         |
| Wants to understand what they should do once they have bonds | Needs to display link to management page in "your orders" |

### Auction creator/manager

| Wants                         | Needs                                                 |
| ----------------------------- | ----------------------------------------------------- |
| Wants to view auction results | Needs to see volume, clearing pricing, bids, etc      |
| Wants to claim auction funds  | Needs to be able to claim funds in auction management |
| Wants to manage issued bond   | Needs to link to bond management page                 |

## Inspirations

- [Gnosis Auction](assets/gnosis/auction_page_post.png)
- [Copper Launch](assets/copper/auction_page_post.png)

## Features

### Auction information

- Issuer name
  - Ex: Uniswap
- Auction status
  - Ex: Ended
- Auction duration
  - Ex: 7 days
- Days/time auction ended
  - Ex: 3 days, 3 hours
- Bond offering size
  - Ex: \$50M
- Total bid volume
  - Ex: \$60M
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
- Clearing auction interest rate
  - Ex: 8.5%
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

- Examples
  - [Copper](assets/copper/auction_details_post.png)
  - [Gnosis](assets/gnosis/auction_details_post.png)

### Bid submission

- No longer accessible, post auction state
- Examples
  - [Copper](assets/copper/bidding_post.png)
  - [Gnosis](assets/gnosis/bidding_post.png)

### Orderbook

- This is where bids are displayed
  - Bids should have the following info
    - Wallet address
    - Interest rate
    - Price
    - Volume
  - Should be sortable by Price, interest rate, or volume
- Examples
  - [Copper](assets/copper/order_book.png)
  - [Gnosis](assets/gnosis/order_book.png)

### Your orders

- This is where a users bids are displayed
  - Bids should have the following info
    - Wallet address
    - Interest rate
    - Price
    - Volume
    - Status
      - Ex: Filled/Partially Filled/Unfilled/Cancelled
    - Claim bonds
    - Claim funds
- Examples
  - [Copper](assets/copper/order_book.png)
  - [Gnosis](assets/gnosis/my_orders_empty.png)

### Graph

- This is a visual representation of all bids
- Tells user current state of the auction/pricing at a glance
- Examples
  - [Copper](assets/copper/order_book_graph.png)
  - [Gnosis](assets/gnosis/order_book_graph.png)

### Auction management

- Allows auction creator to manage auction
  - Claim funds raised
- Examples
  - [Copper](assets/copper/auction_management.png)
