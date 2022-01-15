# Auction page

## Purpose

The purpose of the auction page is to host the bond auction.

## States

- Upcoming
  - Auction has not started
- Active
  - Auction is ongoing
- Ended
  - Auction has ended

## Users

- Investor
  - Potential auction participant
- Issuer
  - Auction creator/manager

## User flows

- [Investor participates in auction](../../user_flows/investor/submit_an_order.md)

## User needs

### Upcoming state

| User     | User Wants                                                           | Product Needs                                         |
| -------- | -------------------------------------------------------------------- | ----------------------------------------------------- |
| Investor | Wants to determine whether they want to participate in this auction  | Needs information regarding the upcoming bond auction |
| Issuer   | Wants to view the auction                                            | Needs auction to be viewable before it has started    |
|          | Wants to cancel the auction if they decide not to go through with it | Needs a management section                            |

### Active state

| User     | User Wants                                                          | Product Needs                                                                 |
| -------- | ------------------------------------------------------------------- | ----------------------------------------------------------------------------- |
| Investor | Wants to determine whether they want to participate in this auction | Needs information regarding the bond auction                                  |
|          | Wants to determine current status of the auction                    | Needs to show current orders, current pricing, etc                            |
|          | Wants to participate in the bond auction                            | Needs to allow orders to be placed and cancelled                              |
|          | Wants to understand if order will be filled or not                  | Needs to display status of user's orders and whether or not it will be filled |
| Issuer   | Wants to view auction status                                        | Needs to see current volume, pricing, bids, etc                               |
|          | Wants to manage the auction                                         | Needs a management section                                                    |

### Ended state

| User     | User Wants                                                   | Product Needs                                             |
| -------- | ------------------------------------------------------------ | --------------------------------------------------------- |
| Investor | Wants to see if their order got filled                       | Needs status of orders to update to filled/not filled     |
|          | Wants to see overview of past auction                        | Needs to show orders, settled pricing, etc                |
|          | Wants to claim bonds purchased or funds from unfilled orders | Needs to allow claiming of assets                         |
|          | Wants to understand what they should do once they have bonds | Needs to display link to management page in "your orders" |
| Issuer   | Wants to view auction results                                | Needs to see volume, clearing pricing, bids, etc          |
|          | Wants to claim auction funds                                 | Needs to be able to claim funds in auction management     |
|          | Wants to manage issued bond                                  | Needs to link to bond management page                     |

## Features

### [Warning](features/warning.md)

### [Auction information](features/auction_information.md)

### [Bond information](features/bond_information.md)

### [Orderbook](features/orderbook_graph.md)

### [Orderbook graph](features/orderbook_graph.md)

### [Order panel](features/order_panel.md)

### [User orders](features/user_orders.md)

### [Auction management](features/auction_management.md)

## Examples

### Copper Launch

![](../../assets/copper/auction_page.png)

### Gnosis Auction

![](../../assets/gnosis/auction_page.png)
