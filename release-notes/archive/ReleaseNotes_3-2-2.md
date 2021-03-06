Release Notes
xTuple ERP
PostBooks, Standard, and Manufacturing Editions
Version 3.2.2
May 4, 2009
----------------------------------

These are the release notes for version 3.2.2, a bug-fix
release following up on version 3.2.1. Thanks to all in the
community who provided valuable feedback!

----------------------------------

The following bug fixes have been added to the applications
since the release of version 3.2.1. Additional detail for
each item listed below may be found on our community website
(www.xtuple.org). Simply go to the Issue Tracker and select
the Changelog option.

Bug Fixes:

* [Accounting] Fixed issue where Tax was not being calculated
properly on Sales Order Credit Memos
* [Accounting] Fixed issue where currency conversion was not
incorporated into Bank Reconciliation history report
* [Accounting] Fixed Invoice report definition which was
calculating the total due incorrectly when credit automatically
applied at Sales Order entry
* [Accounting] Fixed issue where Check ids were being stored
in the apapply table, creating references in the AP Aging
report that should not have been there
* [CRM] Removed unnecessary warning about duplicate Contacts
* [Inventory] Fixed issue where posted vs standard cost values
were not the same in QOH report
* [Inventory] Fixed issue leading to error when attempting to
recall orders from Shipping
* [Inventory] Fixed issue where availability was not updating
property if stock manually issued to Shipping
* [Products] Fixed issue leading to unexpected results when
switching from Standard Costing to Average Costing
* [Sales] Fixed issue where a credit card refund on a Return
Authorization left an incomplete Credit Memo
* [Sales] Fixed issue where auto-generated Sales Order numbers
were incrementing without the Sales Order header having been
saved
* [Sales] Fixed issue with PO Item not saving Characteristic
Values
* [Sales] Fixed issue leading to incorrect error messaging
when processing credit card transactions using Authorize.net
* [Sales] Fixed issue preventing deletion of lines using
api.salesline
* [Sales] Fixed issue preventing update of Sales Orders using
Sales Order view
* [Schedule] Fixed issue with MRP not creating all required
planned Work Orders in situation where BOMs were created or
modified in an arbitrary sequence
* [System] Fixed crash behavior when trying to connect signals
and slots in the screen designer
* [System] Fixed issue with contents of mapped XTextEdit fields
not being saved to or retrieved from the database
