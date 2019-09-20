# LSRetailPrintTemplates
Custom Print Templates for Lightspeed Retail POS

## LS Sales Receipt.twig
This custom template was developed as a way to emulate the LightSpeed Onsite receipts and invoices.

This template includes the following features:
* Receipt is formatted for letter size printing in portrait orientation
* A receipt with Sale Lines will have the heading of "Invoice" with "I-" prefix to saleID
* A receipt with only Layaways will have the heading of "Approval"
* A receipt with only Special Orders will have the heading of "Special Order"
* A receipt with Layaways and Special Orders will have the heading of "Approval / Special Order"
* Ship to Address moved to be in-between Customer Billing Address and Contact Information
* Added Custom SKU and Titled it "Product ID"
* Discounts will be found in "Notes" Column
* Cleaned up Sell Price with Discounts
* Item Images printed on receipt (must set {{AccountID}} in code to work)

## LS Item Label.twig
This custom template was developed to provide custom sizes and information for item labels.

The Small 1.25 x 1.00 size label has been resized to 1.00 x 1.00 (although it will still show up as 1.25 x 1.00 in LS Retail)
The Normal 2.25 x 1.25 size label has been resized to 4.00 x 2.50 (although it will still show up as 2.25 x 1.25 in LS Retail)

The small labels have the following settings:
* Custom SKU, Price, and Barcode are the only items displayed
* Custom SKU, and Price are centered

The normal labels have the following settings:
* Custom SKU, Price, Dimensions, Barcode and Name are the only items displayed
* A "Dimensions" custom field has been added (must set {{AccountID}} in code to work)
