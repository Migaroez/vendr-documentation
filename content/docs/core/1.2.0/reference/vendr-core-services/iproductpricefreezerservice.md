---
title: IProductPriceFreezerService
description: API reference for IProductPriceFreezerService in Vendr, the eCommerce solution for Umbraco v8+
---
## IProductPriceFreezerService

Defines the Vendr Product Price Freezer service

```csharp
public interface IProductPriceFreezerService
```

**Namespace**
* [Vendr.Core.Services](../)

### Methods

#### GetOrCreateFrozenProductPrice

Get or creates a frozen price for a given product

```csharp
public ProductPrice GetOrCreateFrozenProductPrice(Guid orderId, string productReference, 
    string key, Guid currencyId)
```

**Parameters**

| Parameter | Description |
| --- | --- |
| orderId | The ID of the [`Store`](../../vendr-core-models/store/) the product belongs to |
| productReference | The unique reference of the Product who's price to freeze |
| key | A unique key to assign the frozen price to |
| currencyId | The ID of the [`Currency`](../../vendr-core-models/currency/) of the price to freeze |

**Returns**

A frozen [`ProductPrice`](../../vendr-core-models/productprice/)


---

#### ThawFrozenProductPrice

Thaws a frozen price for a given product

```csharp
public void ThawFrozenProductPrice(Guid orderId, string key, Guid currencyId)
```

**Parameters**

| Parameter | Description |
| --- | --- |
| orderId | The ID of the [`Store`](../../vendr-core-models/store/) the product belongs to |
| key | The unique key of the frozen price |
| currencyId | The ID of the [`Currency`](../../vendr-core-models/currency/) of the frozen price to thaw |


<!-- DO NOT EDIT: generated by xmldocmd for Vendr.Core.dll -->
