---
title: "Add products to a quote, order, or invoice (Dynamics 365 for Sales) | MicrosoftDocs"
description: "Include details about the products that your customer is interested in purchasing in your quote, order, or invoice in Dynamics 365 for Sales."
keywords: "product, quote, order, invoice"
ms.date: 05/01/2018
ms.service: crm-online
ms.custom: 
ms.topic: article
applies_to:
  - "Dynamics 365 (online)"
  - "Dynamics 365 Version 9.x"
ms.assetid: c1f6f66e-25fe-4528-a2f3-f2a3a2e3830d
author: shubhadaj
ms.author: shujoshi
manager: sakudes
ms.reviewer: 
ms.suite: 
ms.tgt_pltfrm: 
caps.latest.revision: 58
topic-status: Drafting
---

# Add products to a quote, order, or invoice (Sales Hub)

You can add products or product bundles to a quote, order, or invoice record. The product can be an existing product in the [!INCLUDE[pn-dyn-365-sales](../includes/pn-dyn-365-sales.md)] product catalog, or an ad hoc product that you add as a write-in product. 

If you’ve created a quote from an opportunity, the products added to the opportunity are automatically added to the quote. You can add more products or remove the existing ones.

The process for adding a product to a quote record is the same as adding a product to an order or an invoice. This topic explains how to add products to a quote record.

1. From the list of quotes, open the quote record you want to add the product to. 

2. On the **Summary** tab, in the **Products** section, select the **More Commands** button ![More Commands button](media/more-commands-button.png "More Commands button"), and then select **Add New Quote Product**.

3. In the **Quick Create: Quote Product form**, do the following: 

    1.	In the **Select Product** drop-down list, select whether you want to add an existing product or create a new one:

        - To use an existing product, select **Lookup** to search for and add a product. Also, select a unit of measurement for the product.

        - To create a product, select **Write-In**, and then enter the name of the product.

    2.	Fill in details in the **Pricing** section:

        - **Price Overridden**. If you’re adding an existing product from the product catalog, select whether you want to use the default pricing that is listed in the product catalog or override the price. For a write-in product, this field is set to **Override** Price. 

        - **Price Per Unit**. If you’re adding a write-in product, enter the price to be charged per unit for the product.

        - **Quantity**. Enter the quantity of the product or service that will be included. 

        - **Manual Discount**. If you want to offer a discount to the product price, enter it here. 

        - **Tax**. If required, enter the appropriate tax amount. 

4. Select **Save**.

The **Products** grid shows all the products that are associated with the quote. After you add a product, you can change the unit, price, quantity, and discount of the product inline in the **Products** grid. For a write-in product, you can also change the price of the product in addition to the quantity and discount. 

Here are the actions you can take on the products in the Products grid:

|To                                    |Do This                                                           |
|--------------------------------------|------------------------------------------------------------------|
|Edit properties of a product  |Select a product, and on the command bar, select **Edit Properties**.|
|Delete a product associated with the quote |Select the product, and on the command bar, select **Delete Quote Product**. |
|View products within a bundle | Select the **Chevron** icon ![Chevron icon](media/chevron-icon.png "Chevron icon") for the product bundle. You’ll see all the products that are included in the bundle. |
|See and add related products for cross-selling or upselling, or to select an accessory or substitute product | Select a product, and on the command bar, select **Suggestions**. The **Suggestions** pane shows all the products that are defined as related products for the current product. Select the related products that you want to add, and then select **OK**. |
|See specific records together by moving a record up or down in the grid | Select a record, and on the command bar, use the **Up** or **Down** button. |


### See also  
 [Create or edit a quote](../sales-enterprise/create-edit-quote-sales.md)  
 [Create or edit an order](../sales-enterprise/create-edit-order-sales.md)  
 [Create or edit an invoice](../sales-enterprise/create-edit-invoice-sales.md)  
