# Liquidity Pool Math Model Simulation in Rust

## Overview

This project implements a basic liquidity pool simulation in Rust. It covers essential functionalities of a liquidity pool, including adding liquidity, removing liquidity, and swapping tokens. The pool handles fixed-point arithmetic for precision and fee calculations.

## Features

- **Initialization:** Create a new liquidity pool with specified parameters.
- **Add Liquidity:** Add tokens to the pool and mint corresponding LP tokens.
- **Remove Liquidity:** Burn LP tokens from the pool and claim the corresponding amount of tokens and staked tokens.
- **Swap Tokens:** Swap staked tokens for liquidity pool tokens with dynamic fees based on the liquidity target.

## Testing

The project includes unit tests to verify the functionality of the liquidity pool. To run the tests, use the following command:

```sh
cargo test
