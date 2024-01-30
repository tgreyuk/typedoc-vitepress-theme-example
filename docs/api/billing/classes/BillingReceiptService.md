[typedoc-vitepress-theme-example](../../index.md) / [billing](../index.md) / BillingReceiptService

# BillingReceiptService

Service for generating billing receipts.

## Constructors

### new BillingReceiptService()

```ts
new BillingReceiptService(): BillingReceiptService
```

#### Returns

[`BillingReceiptService`](BillingReceiptService.md)

## Properties

### receipts

```ts
private receipts: BillingReceipt[] = [];
```

## Methods

### generateReceipt()

```ts
generateReceipt(transaction): BillingReceipt
```

Generate a billing receipt for a transaction.

#### Parameters

• `transaction`: [`BillingTransaction`](../interfaces/BillingTransaction.md)

The billing transaction for which to generate a receipt.

#### Returns

[`BillingReceipt`](../interfaces/BillingReceipt.md)

The generated billing receipt.

***

### getAllReceipts()

```ts
getAllReceipts(): BillingReceipt[]
```

Get all billing receipts.

#### Returns

[`BillingReceipt`](../interfaces/BillingReceipt.md)[]

An array of all billing receipts.

***

Generated using [TypeDoc](https://typedoc.org) and [typedoc-plugin-markdown](https://typedoc-plugin-markdown.org).
