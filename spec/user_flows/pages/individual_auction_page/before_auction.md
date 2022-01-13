# Individual auction page before auction

## Users

- Potential auction participant
- Auction creator/manager

## User assumptions

### Potential auction participant

- Knows how the auction works
  - User came to this page through landing page which has links to educational content
  - If they don't know how it works, they can learn via the a link in the navbar

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

- [Gnosis Auction individual auction page](https://gnosis-auction.eth.link/#/auction?auctionId=52&chainId=1#topAnchor)

  - There are only completed auctions available to view

- [Copper Launch individual auction page](https://copperlaunch.com/auctions/0xb8ece82fcfb948b1af937e2819eb2d72bb3d98d2)
  - You may need to find a different auction that hasn't started yet

## Features

### Warning

Explains to users the potential risk of participating in the auction. [Here is an example](../../assets/risk_warning.png)

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
- Bond Term length
  - Ex: 12 months
- Bond Collateral
  - Type and amount
    - Ex: 500,000 UNI
  - Token contract address
- Convertibility
  - Are the bonds redeemable for a pro-rata portion of the collateral tokens?
  - Ex: Yes/No

### Bid submission

- This is where users will submit bids once auction is live
- [Example](../../assets/bidding_pre_auction.png)

### Orderbook

- This is where bids will be displayed once auction is live
- [Example](../../assets/order_book_pre_auction.png)

### Your orders

- This is where a users bids will be displayed once auction is live and a user has placed a bid
- [Example](../../assets/your_orders.png)
  - Adapt for pre-auction state

### Graph

- This is a visual representation of all bids
- Tells user current state of the auction/pricing at a glance
- [Example](../../assets/order_book_chart.png)
  - Adapt for pre-auction state

### Auction management

- Allows auction creator to manage auction
- [Example]
