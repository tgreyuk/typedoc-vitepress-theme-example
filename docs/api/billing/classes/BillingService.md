[typedoc-vitepress-theme-example](../../index.md) / [billing](../index.md) / BillingService

# BillingService

Service for managing billing transactions.

## Constructors

### new BillingService()

```ts
new BillingService(): BillingService
```

#### Returns

[`BillingService`](BillingService.md)

## Properties

### transactions

```ts
private transactions: BillingTransaction[] = [];
```

## Methods

### getAllTransactions()

```ts
getAllTransactions(): BillingTransaction[]
```

Get all billing transactions.

#### Returns

[`BillingTransaction`](../interfaces/BillingTransaction.md)[]

An array of all billing transactions.

***

### processTransaction()

```ts
processTransaction(transaction): BillingTransaction
```

Process a billing transaction.

#### Parameters

• **transaction**: [`BillingTransaction`](../interfaces/BillingTransaction.md)

The billing transaction to be processed.

#### Returns

[`BillingTransaction`](../interfaces/BillingTransaction.md)

The processed billing transaction.

***

Generated using [typedoc-plugin-markdown](https://www.npmjs.com/package/typedoc-plugin-markdown) and [TypeDoc](https://typedoc.org/)
