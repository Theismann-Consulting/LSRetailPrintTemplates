# LSRetailPrintTemplates
Custom Print Templates for Lightspeed Retail POS

<Strong>LS Sales Receipt.twig</strong><br/>
This update adds the following functionality and changes:
<ul>
<li>Receipt is formatted for letter size printing in portrait orientation</li>
<li>A receipt with Sale Lines will have the heading of "Invoice" with "I-" prefix to saleID</li>
<li>A receipt with only Layaways will have the heading of "Approval"</li>
<li>A receipt with only Special Orders will have the heading of "Special Order"</li>
<li>A receipt with Layaways and Special Orders will have the heading of "Approval / Special Order"</li>
<li>Ship to Address moved to be in-between Customer Billing Address and Contact Information</li>
<li>Added Custom SKU and Titled it "Product ID"</li>
<li>Discounts will be found in "Notes" Column</li>
<li>Cleaned up Sell Price with Discounts</li>
<li>Item Images printed on receipt (must set {accountID} in code to work)</li>
</ul>
