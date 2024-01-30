[typedoc-vitepress-theme-example](../../index.md) / [shipping](../index.md) / ShippingService

# ShippingService

Service for managing shipping records.

## Constructors

### new ShippingService()

```ts
new ShippingService(): ShippingService
```

#### Returns

[`ShippingService`](ShippingService.md)

## Properties

### shipments

```ts
private shipments: ShippingRecord[] = [];
```

## Methods

### getAllShipments()

```ts
getAllShipments(): ShippingRecord[]
```

Get all shipping records.

#### Returns

[`ShippingRecord`](../interfaces/ShippingRecord.md)[]

An array of all shipping records.

***

### shipOrder()

```ts
shipOrder(shipment): ShippingRecord
```

Ship an order.

#### Parameters

• `shipment`: [`ShippingRecord`](../interfaces/ShippingRecord.md)

The shipment record.

#### Returns

[`ShippingRecord`](../interfaces/ShippingRecord.md)

The shipped record.

***

Generated using [TypeDoc](https://typedoc.org) and [typedoc-plugin-markdown](https://typedoc-plugin-markdown.org).
