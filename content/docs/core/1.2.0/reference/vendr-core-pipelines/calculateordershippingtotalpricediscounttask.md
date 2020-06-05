---
title: CalculateOrderShippingTotalPriceDiscountTask
description: API reference for CalculateOrderShippingTotalPriceDiscountTask in Vendr, the eCommerce solution for Umbraco v8+
---
## CalculateOrderShippingTotalPriceDiscountTask

```csharp
public class CalculateOrderShippingTotalPriceDiscountTask : 
    PipelineTaskWithTypedArgsBase<OrderCalculationPipelineArgs, OrderCalculation>
```

**Inheritance**

* class [PipelineTaskWithTypedArgsBase&lt;TArgs,T&gt;](../pipelinetaskwithtypedargsbase-2/)

**Namespace**
* [Vendr.Core.Pipelines.Order.Tasks](../)

### Constructors

#### CalculateOrderShippingTotalPriceDiscountTask

The default constructor.

```csharp
public CalculateOrderShippingTotalPriceDiscountTask()
```


### Methods

#### Execute

```csharp
public override PipelineResult<OrderCalculation> Execute(OrderCalculationPipelineArgs args)
```


<!-- DO NOT EDIT: generated by xmldocmd for Vendr.Core.dll -->