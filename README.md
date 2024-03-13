# Cashfree Payout Node SDK
![GitHub](https://img.shields.io/github/license/cashfree/cashfree-payout-sdk-nodejs) ![Discord](https://img.shields.io/discord/931125665669972018?label=discord) ![GitHub last commit (branch)](https://img.shields.io/github/last-commit/cashfree/cashfree-payout-sdk-nodejs/main) ![GitHub release (with filter)](https://img.shields.io/github/v/release/cashfree/cashfree-payout-sdk-nodejs?label=latest) ![npm](https://img.shields.io/npm/v/cashfree-payout) ![GitHub forks](https://img.shields.io/github/forks/cashfree/cashfree-payout-sdk-nodejs) [![Coverage Status](https://coveralls.io/repos/github/cashfree/cashfree-payout-sdk-nodejs/badge.svg?branch=)](https://coveralls.io/github/cashfree/cashfree-payout-sdk-nodejs?branch=main)

The Cashfree Payout Node SDK offers a convenient solution to access [Cashfree Payout APIs](https://docs.cashfree.com/reference/payouts-version2-apis) from a server-side JavaScript  applications.



## Documentation

Cashfree's Payout API Documentation - https://docs.cashfree.com/reference/payouts-version2-apis

Learn and understand payout workflows at Cashfree Payments [here](https://docs.cashfree.com/docs/payouts)

Try out our interactive guides at [Cashfree Dev Studio](https://www.cashfree.com/devstudio) !

## Getting Started

### Installation
```bash
npm i cashfree-payout
```
### Configuration

```javascript 
import { Cashfree } from "cashfree-payout";

Cashfree.XClientId = "<x-client-id>";
Cashfree.XClientSecret = "<x-client-secret>";
Cashfree.XEnvironment = Cashfree.Environment.SANDBOX;
```

Generate your API keys (x-client-id , x-client-secret) from [Cashfree Merchant Dashboard](https://merchant.cashfree.com/merchants/login)


## Licence

Apache Licensed. See [LICENSE.md](LICENSE.md) for more details
