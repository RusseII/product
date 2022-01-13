# Individual auction page (during auction)

## Inspirations

- [Gnosis Auction individual auction page](https://gnosis-auction.eth.link/#/auction?auctionId=52&chainId=1#topAnchor)
- [Copper Launch individual auction page](https://copperlaunch.com/auctions/0xeedca0c2cba983b718c66094fc8e41f9ed52f82a)

## Functionalities

- Show warning
  - [Example](../../assets/risk_warning.png)
- Show auction information
  - Issuer name
  - Auction duration
  - Day/time auction ended
  - last order cancellation date
  - Bond offering size
  - Minimum funding threshold
  - Funds raised
  - Total bid volume
  - Auction description
  - Link to Prospectus (detailed document outlining bond offering)
  - Maximum bond interest rate
  - Clearing auction interest rate
  - Bond Term length
  - Bond Collateral
    - Amount
    - Type
    - Token contract address
  - Convertibility
    - Yes/No
    - If yes, show breakeven price of conversion
- Allow users to claim bonds
- Allow user to claim unfilled bid funds
- Show order book
  - An order should show the following info
    - Volume
    - interest rate
    - price
    - wallet address
- Show chart representation of order book
  - [Example](../../assets/order_book_chart.png)
- Show users orders
