[typedoc-vitepress-theme-example](../../index.md) / [customer](../index.md) / CustomerAccount

# CustomerAccount

Class representing a customer account.

## Constructors

### new CustomerAccount(customer, contactInfo, billingInfo)

```ts
new CustomerAccount(
   customer, 
   contactInfo, 
   billingInfo): CustomerAccount
```

#### Parameters

• `customer`: [`Customer`](../interfaces/Customer.md)

• `contactInfo`: [`CustomerContact`](../interfaces/CustomerContact.md)

• `billingInfo`: [`CustomerBilling`](../interfaces/CustomerBilling.md)

#### Returns

[`CustomerAccount`](CustomerAccount.md)

## Properties

### billingInfo

```ts
private billingInfo: CustomerBilling;
```

***

### contactInfo

```ts
private contactInfo: CustomerContact;
```

***

### customer

```ts
private customer: Customer;
```

***

### orderHistory

```ts
private orderHistory: CustomerOrderHistory[];
```

## Methods

### addOrderToHistory()

```ts
addOrderToHistory(order): void
```

Add an order to the customer's order history.

#### Parameters

• `order`: [`CustomerOrderHistory`](../interfaces/CustomerOrderHistory.md)

The order to be added to the history.

#### Returns

`void`

***

### getBillingInfo()

```ts
getBillingInfo(): CustomerBilling
```

Get the customer billing information.

#### Returns

[`CustomerBilling`](../interfaces/CustomerBilling.md)

The customer billing information.

***

### getContactInfo()

```ts
getContactInfo(): CustomerContact
```

Get the customer contact information.

#### Returns

[`CustomerContact`](../interfaces/CustomerContact.md)

The customer contact information.

***

### getCustomer()

```ts
getCustomer(): Customer
```

Get the customer information.

#### Returns

[`Customer`](../interfaces/Customer.md)

The customer information.

***

### getOrderHistory()

```ts
getOrderHistory(): CustomerOrderHistory[]
```

Get the customer's order history.

#### Returns

[`CustomerOrderHistory`](../interfaces/CustomerOrderHistory.md)[]

An array of the customer's order history.

***

Generated using [TypeDoc](https://typedoc.org) and [typedoc-plugin-markdown](https://typedoc-plugin-markdown.org).
