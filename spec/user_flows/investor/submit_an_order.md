# Submits an order

## Inspiration

- [Copper Launch](https://docs.alchemist.wtf/copper/auction-participation-walkthrough)
- [Gnosis Auction](https://gnosis-auction.eth.link/#/start)
  - Go to docs
  - Click "Participate as a bidder"

## User flow

1. User starts on an auction page with an "Active" status
   ![](../../assets/copper/auction_page.png)
2. User sees warning outlining the dangers of participating in bond auctions
   ![](../../assets/copper/warning.png)
3. User sees auction details
   ![](../../assets/copper/auction_details.png)
   ![](../../assets/gnosis/auction_details.png)
4. User sees chart representing order book
   ![](../../assets/gnosis/order_book_graph.png)
5. User sees bond details
   ![](../../assets/copper/bond_details.png)
6. User sees submit bid panel
   ![](../../assets/gnosis/place_order.png)
7. User submits a bid by entering volume and interest rate (or price)
8. A modal appears which shows bid transactions
9. User confirms a transaction giving Porter authorization to access their funds
10. User confirms a transaction to send funds and submit the bid
11. Loading spinner appears until transactions are complete
    ![](../../assets/gnosis/place_order_loading.png)
12. Happy state is shown once transactions are complete
13. Bid shows up in "your orders" section
    ![](../../assets/gnosis/your_order.png)
