# Bond config

## Purpose

The purpose of the bond config step is to allow the user to supply all the bond config details.

## Implementation

Bond config is a step in the auction creation page which contains sub-steps.

## Sub steps

### Bond

**inputs**

- Bond asset contract address
- Max interest rate
- Term length
- Maximum issuance size
- Minimum issuance size

**display**

- Bond asset logo
- Bond asset name
- Bond asset ticker
- Bond asset balance

### Collateral

**inputs**

- Collateral (yes/no)
  - if yes
    - Collateral asset contract address
    - Collateral asset amount/ratio (can switch between)

**display**

- Link to docs explaining how collateral works
- if collateral
  - Collateral asset logo
  - Collateral asset name
  - Collateral asset ticker
  - Collateral asset balance
  - Collateral asset price (in terms of bond asset)
  - Current value of collateral (in terms of bond asset)

### Convertibility

If there is no collateral, the bond cannot be convertible. Display a message explaining this and disable inputs if there is no collateral.

**inputs**

- Convertible (yes/no)
  - if yes
    - Convertible asset amount (must be lower than or equal to bond collateral asset amount)

**display**

- Link to docs explaining how convertibility works
- if convertible
  - Breakeven token price of convertibility (in terms of bond asset)
  - Link to docs explaining breakeven token price

### Review

**display**

- Bond
  - Bond asset contract address
  - Bond asset logo
  - Bond asset name
  - Bond asset ticker
  - Max interest rate
  - Term length
  - Maximum issuance size
  - Minimum issuance size
- Collateral
  - if yes
    - Collateral asset contract address
    - Collateral asset logo
    - Collateral asset name
    - Collateral asset ticker
    - Collateral asset amount
    - Collateral asset ratio
    - Collateral asset price (in terms of bond asset)
    - Current value of collateral (in terms of bond asset)
  - if no
    - None
- Convertible
  - if yes
    - Convertible asset amount
    - Breakeven token price of convertibility (in terms of bond asset)
  - if no
    - No

## Examples

### Copper Launch

Contract information
![](../../../assets/copper/token_information.png)
Review
![](../../../assets/copper/auction_summary.png)
