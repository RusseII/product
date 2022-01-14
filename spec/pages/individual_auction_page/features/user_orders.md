# User orders

## Purpose

The purpose of user orders is to display the users orders and allow them to cancel them.

## States

- Upcoming
  - Auction has not started
  - Empty state
- Active
  - Auction is ongoing
- Ended
  - Auction has ended

## Implementation

User orders will be implemented as a table at the bottom of the page with each row representing an order.

### Headers

#### Time

- Description: The time the bid was submitted
- Value: date and time
  - Ex: Jan 14, 2022, 12:00 UTC

#### Price

- Description: The bond price submitted as part of the bid.
- Value: amount and type of asset
  - Ex: 0.875 FEI

#### Interest rate

- Description: The interest rate submitted as part of the bid.
- Value: percent
  - Ex: 13%

#### Amount

- Description: The size of the bid
- Value: amount and type of asset
  - Ex: 750,000 FEI

#### Status

- Description: The status of the order.
- Value: enum
  - Active **(Active only)**
    - If order will not get filled based on current bids, a hoverable warning icon should show up next to "Active"
  - Cancelled
  - Filled **(Ended only)**
  - Partially filled **(Ended only)**
  - Unfilled **(Ended only)**

#### Actions

- Description: Actions user can take to manage orders.
- Value: buttons
  - Cancel order
  - Claim funds
    - Shows if order was previously cancelled

## Examples

### Gnosis Auction

![](../../../assets/gnosis/your_order.png)
