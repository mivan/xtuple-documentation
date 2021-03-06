Release Notes
xTuple ERP
PostBooks, Standard, and Manufacturing Editions
Version 3.2.1
February 11, 2009
----------------------------------

This is the final release of version 3.2.1, a follow-up release
to version 3.2.0. This is primarily a bug fix release but does
contain several new features designed to support custom screen
and package development. Thanks to all in the community who
helped make this release possible!

----------------------------------

The following features and bug fixes have been added to the
applications since the release of version 3.2.1Beta. Additional
detail for each item listed below may be found on our community
website (www.xtuple.org). Simply go to the Issue Tracker and
select the Changelog option.

New Features:

* [System] Exposed metrics set function to scripting
* [System] Added menu manipulation capabilities to script
toolbox
* [System] Exposed more control of tab widget to scripting


Bug Fixes:

* [Accounting] Fixed CC Refund for Authorize.net
* [Accounting] Fixed return Shipment to update Item Site
Average Cost correctly
* [Accounting] Removed date range requirement for reprint
Invoice
* [Accounting] Fixed running total on GL transaction to not
reverse sense for certain Account Types
* [Accounting] Fixed duplicate key error when selecting to
create Profit Center
* [Accounting] Removed company segment requirement from
forward update utility
* [Accounting] Improved performance when opening Sales
Order/Sales Order Line screens
* [CRM] Fixed alignment problems on Contact, Incident, and
CRM Account screens
* [Products] Made Element column visible in Item Cost
History Report
* [Sales] Removed Zone requirement on Ship To screen
* [Sales] Included Freight Tax into consideration on Sales
Order Summary Screen
* [System] Fixed issue with xtreeview column view/hide
settings over-writing each other


----------------------------------
Release Notes
xTuple ERP
PostBooks, Standard, and Manufacturing Editions
Version 3.2.1Beta
January 26, 2009
----------------------------------

This is the Beta release of version 3.2.1, a follow-up release
to version 3.2.0. This is primarily a bug fix release; however,
several smaller features have been added to improve user
experience--and also to enhance the work being done by custom
screen developers.

We ask everyone in the community who can to please test this
Beta. The 3.2.1 release cycle will be an abbreviated one, with
the plan being to move right to the final release immediately
following 3.2.1Beta testing. Many thanks in advance to all our
Beta testers!

----------------------------------

The following features and bug fixes have been added to the
applications since the release of version 3.2.0. Additional
detail for each item listed below may be found on our community
website (www.xtuple.org). Simply go to the Issue Tracker and
select the Changelog option.

New Features:

* [All] Added api.itemcost view
* [Accounting] Moved Email Invoice menu item to Accounting
module menu
* [Accounting] Enhanced Voucher voiding to also undo
distributions
* [Accounting] Added ability to print Checks alphabetically by
Vendor Name
* [Accounting] Added ability to Post CMs and Invoices from
embedded tab screens in Customer Workbench
* [Accounting] Added new CM button to Credits tab on
Receivables WB
* [Accounting] Added option to post from Invoices tab in
Customer WB
* [Accounting] Added trigger to close Incident Related to
Invoice
* [CRM] Added ability to add new Opportunities from Account
screen
* [Inventory] Prevented Shipping recall if Invoice posted
* [Inventory] Added description column on PO and receiving
screens
* [Inventory] Added help for users with activate/deactive of
Items
* [Inventory] Allowed selection of a new Location default
from the Relocate Inventory screen
* [Purchase] Added unique constraint for pohead_number
* [Sales] Added "active" column (Y/N) in Customers by...
displays
* [Sales] Included baseline Sales Order acknowledgment form
* [Sales] Added Workbench button to Customer Search screen
* [System] Allowed print to PDF from scripts
* [System] Created package development mode
* [System] Added UPC code cross reference and search to Item
cluste
* [System] Provided method to open screen builder screens
from other screen builder screens
* [System] Added more navigation info to Alarms


Bug Fixes:

* [All] Fixed compiler warning on xcheckbox.cpp
* [All] Required Main Window to remember its size for the next
login
* [Accounting] Fixed issue with List Unposted Invoices total
amount not including tax+freight+other
* [Accounting] Fixed issue with the Accounts widget not
calling the latest window
* [Accounting] Resolved deadlock scenario when two people
distributing to/from the same lot/serial/locations
* [Accounting] Fixed Refund feature for for Authorize.net CC
users
* [Accounting] Fixed issue leading to ERROR: null value in
column "gltrans_amount" violates not-null constraint
* [Accounting] Fixed issue leading to -8 failure when posting
Cash Receipt for Credit Card
* [Accounting] Fixed issue where amending Profit Center
numbers did not apply to all Account Numbers
* [Accounting] Updated privileges to allow posting Voucher
with only accounting privileges
* [Accounting] Made Invoice displays consistent
* [Accounting] For Fiscal Years, prevented entry of the end
date prior to the start date
* [Accounting] Modified Voucher tab sequence to resolve data
dependency issues
* [Accounting] Prevented creation of duplicate Tax Selections
* [Batch Manager] Fixed CANCEL button on Configuration Options
screen
* [Batch Manager] Fixed SalesHistorybyCustomerGroup report to
display data when run through the Batch Manager
* [CRM] Prevented creation of duplicate Titles
* [CRM] Fixed issue leading to error when selecting to delete
an Opportunity related with CRM account
* [CRM] Prevented creation of empty records for Tasks
* [Inventory] Filtered recv rows selected by
recv_trans_usr_name=CURRENT_USER to avoid problems when
multiple users simultaneously receiving the same order
* [Inventory] Fixed issue leading to errors when posting
Lot/Serial Count Tags
* [Inventory] Fixed issue leading to error on Query QOH by
Location in PostBooks
* [Inventory] Fixed issue with Packing List form not being
updated correctly if Ship Via changed after Stock issued
* [Inventory] Fixed issue with List Site locations printing
partial information
* [Inventory] Removed obsolete code in postBillingSelection
* [Inventory] Added Alias information to key forms (e.g., Ship
Confirmation and Packing List)
* [Manufacture] Restored Item description information on
Inventory availability by Work Order screen
* [Manufacture] Fixed issue where Notes and Ref Designators
were not copying from one BOM to another
* [Manufacture] Fixed issue leading to error when querying
Work Order History by Work Order report
* [Products] Fixed incorrect or missing UOM data in Where
Used screen
* [Products] Fixed issue preventing addition of Work Center
Labor rates greater than 1,000
* [Purchase] Allowed changing of Purchase Order qty. with
only "ChangePurchaseOrderQty" privilege
* [Purchase] Prevented entry of non-Inventory information on
Purchase Order Item screen unless �Non-Inventory� radio button
explicitly selected
* [Purchase] Added missing fields to Warehouse info view
* [Products] Fixed issue leading to error when selecting to
post Actual Costs
* [Products] Worked to prevent scenario enabling division by
zero error if Breeder BOM incomplete
* [Products] Prevented reassignment of blank Product Category
patterns
* [Products] Prevented reassignment of blank Class Codes
* [Products] Fixed inconsistent operation of Mass Replace
feature
* [Products] BOO can now be edited without saving the item
first
* [Reports] Added bomitem_id and ecn to Indented BOM function
* [Reports] Added atShipping information to data source of
Packing List
* [Sales] Changed overload functions to call itemCharPrice
(rather than itemPrice)
* [Sales] Updated triggers so that when child line items of a
Kit have their status changed then parent line item is updated
as needed
* [Sales] Improved performance of S/O Line Item List on large
databases
* [Sales] Prevented deletion of Sales Orders having linked,
in-process Job Item Work Orders
* [Sales] Fixed Running Availability to work from Sales Order
Backlog screen
* [Sales] Fixed issue with Backlog by Product Category report
displaying Sales Order Number as Currency
* [Sales] Prevented reassignment of blank Customer Type
patterns
* [Sales] Added "grace days" information to api.customer view
* [Sales] Enforced update of Unit price on UOM conversion
* [Sales] Prevented editing of Return line items in view mode
* [Schedule] Prevented deletion of  Item Sites having active
Production Plans
* [System] Fixed issue leading to error when deleting packages
* [System] Fixed issue leading to error when assigning Employees
as their own Manager
* [System] Enforced rule that decimal precision in Locales
should reflect the actual precision
* [System] Fixed issue leading to error when making changes to
Accounting Configuration
* [System] Fixed error encountered when importing data using
api.bomitem
* [System] Prevented creation of duplicate Shifts
* [System] Prevented creation of duplicate Locales with same
code and details
* [System] Fixed issue leading to error when creating
duplicate Employee records
