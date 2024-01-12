[typedoc-vitepress-theme-example](../../index.md) / [billing](../index.md) / BillingHistoryService

# BillingHistoryService

Service for managing billing history.

## Constructors

### new BillingHistoryService()

```ts
new BillingHistoryService(): BillingHistoryService
```

#### Returns

[`BillingHistoryService`](BillingHistoryService.md)

## Properties

### history

```ts
private history: BillingTransaction[] = [];
```

## Methods

### addTransactionToHistory()

```ts
addTransactionToHistory(transaction): void
```

Add a transaction to the billing history.

#### Parameters

• **transaction**: [`BillingTransaction`](../interfaces/BillingTransaction.md)

The billing transaction to be added to the history.

#### Returns

`void`

***

### getBillingHistory()

```ts
getBillingHistory(): BillingTransaction[]
```

Get the entire billing history.

#### Returns

[`BillingTransaction`](../interfaces/BillingTransaction.md)[]

An array of all billing transactions in the history.

***

Generated using [typedoc-plugin-markdown](https://www.npmjs.com/package/typedoc-plugin-markdown) and [TypeDoc](https://typedoc.org/)
