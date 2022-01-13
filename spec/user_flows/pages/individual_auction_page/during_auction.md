# Individual auction page (during auction)

## Inspirations

- [Gnosis Auction individual auction page](https://gnosis-auction.eth.link/#/auction?auctionId=52&chainId=1#topAnchor)
  - There are only completed auctions available to view
- [Copper Launch individual auction page](https://copperlaunch.com/auctions/0xc065798f227b49c150bcdc6cdc43149a12c4d757)

## Functionalities

- Show warning
  - [Example](../../assets/risk_warning.png)
- Show auction information
  - Issuer name
  - Auction duration
  - Days/time until auction ends
  - last order cancellation date
  - Bond offering size
  - Total bid volume
  - Minimum funding threshold
  - Auction description
  - Link to Prospectus (detailed document outlining bond offering)
  - Maximum bond interest rate
  - Current auction interest rate
  - Bond Term length
  - Bond Collateral
    - Amount
    - Type
    - Token contract address
  - Convertibility
    - Yes/No
    - If yes, show breakeven price of conversion
- Allow users to submit bids
  - Bid consists of an interest rate and a volume
  - Interest rate can be swapped out with bond price
- Show order book
  - An order should show the following info
    - Volume
    - interest rate
    - price
    - wallet address
- Show chart representation of order book
  - [Example](../../assets/order_book_chart.png)
- Show users orders
  - allows user to cancel order (up until last order cancellation date)
