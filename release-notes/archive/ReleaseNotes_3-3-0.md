Release Notes
xTuple ERP
PostBooks, Standard, and Manufacturing Editions
Version 3.3.0
August 28, 2009
----------------------------------

This is the 3.3.0 Final Release for xTuple ERP. Thanks to all
who have contributed to this release--either through sponsorship,
code contributions, or testing feedback.

----------------------------------

The following features and bug fixes have been added to the
applications since the release of 3.3.0RC2. Additional detail for
each item listed below may be found on our community website
(www.xtuple.org). Simply go to the Issue Tracker and select the
Changelog option.

New Features:

* [All] Create example script for opening a core screen from a script
* [Accounting] have Series GL entry screen show difference between
  Debit and Credit
* [CRM] "Show Complete" checkbox on List Projects screen
* [Sales] Ability to email quotes
* [System] Create API views for project
* [System] Add the ability to purge sales orders
* [System] Added extra support for translation mechanism of
  screen builder extensions
* [System] Reduce overlap on keystroke assignments on main menu and
  screens


Bug Fixes:

* [All] Perform few actions and exit, crashes the application
* [All] application has hard-coded shortcut keys
* [Accounting] Able to apply more than due from Cash Receipt
* [Accounting] Posting M.C. CM and DM Result in Uneeded G/L Posting
* [Accounting] Reschedule PO Item screen Original date not being
  stored
* [Accounting] Printing invoices seems slower after upgrade from
  3.2.2 to 3.3.0Beta3
* [Accounting] Tax calculations confused when manually changing the
  currency on a misc. invoice.
* [Accounting] Changing cost method on itemsite does not update
  itemsite_value
* [Batch Manager] Batch Manager and MRP/MPS enter endless loop
* [CRM] DB error on to-do list
* [CRM] Edits to vendor window do not save when vendor edit is
  launched from CRM account
* [CRM] ToDo Item Alarms do not work
* [Inventory] Transfer Order do not close when have a cancelled line
* [Inventory] Cannot Close TO line
* [Manufacture] WO-Detail Tab: New material right click returns wrong
  order
* [Products] Show Actual Versus Std Cost Filter - Does Not Address
  Currency
* [Purchase] Release PR do not honor Vendor's default currency
* [Purchase] When selecting a price from the price list, the quantity
  changes without warning
* [Purchase] Release P/R to P/O does not result in price on P/O line
* [Sales] Selecting to relocate inventory without selecting the
  Target generates DB log
* [Sales] Long, blank list of Preferred Selling Site on Customer WB
* [Sales] Can not create a sales order when projects turned on and a
  preceding sales order has been canceled
* [Sales] Changelog comments are editable in situations
* [Sales] Sales Order tax override does not pass to billing selection
  or invoice
* [Sales] Resale amount not saving on RA item
* [Schedule] Cancelled lines on TO do not disappear from running
  availability
* [System] When designer screen is opened, all signal/slot
  connections are lost
* [System] Screen Builder Will not allow "Slot Signal Mode" to be
  seleted
* [System] When working on embedded QT screen designer the
  application will sometimes crash when saving.
* [System] Empty attachment sent to email client from batch manager

----------------------------------
Release Notes
xTuple ERP
PostBooks, Standard, and Manufacturing Editions
Version 3.3.0RC2
August 17, 2009
----------------------------------

The RC2 release is a client-side only release, which fixes
a printing problem with the embedded OpenRPT report writer.
This means there are no database changes required for 3.3.0RC2.

----------------------------------

The following features and bug fixes have been added to the
applications since the release of 3.3.0RC:

New Features:

* N/A


Bug Fixes:

* [Batch Manager] Built-in formatted (sub)totals cause crash when
render reports

----------------------------------
Release Notes
xTuple ERP
PostBooks, Standard, and Manufacturing Editions
Version 3.3.0RC
August 12, 2009
----------------------------------

After months of development, testing, and our first ever Bug
Derby, we have arrived at the Release Candidate for xTuple
ERP version 3.3.0. This release primarily fixes several last
minute bugs. However, we have also managed to slip in a few
final features--including several contributed by community
member jstandring.

The RC period will run for the next several weeks, after
which time a final 3.3.0 will be released.

----------------------------------

The following features and bug fixes have been added to the
applications since the release of 3.3.0Beta3. Additional detail for
each item listed below may be found on our community website
(www.xtuple.org). Simply go to the Issue Tracker and select the
Changelog option.

New Features:

* [Accounting] Add Ship-to column in list unposted invoices
display
* [Accounting] Have Series GL entry screen show difference
between Debit and Credit
* [Architectural] Usability improvements to comment cluster
* [Inventory] Add an ability to set Location Default whilst
Posting to Inventory
* [Manufacture] Add filter check box "Item Not In Stock" to
Inventory Availability By Work Order
* [Manufacture] Indented work order screen tab to edit and
issue materials
* [Purchase] Add a list filter and vend item# column to "PO
Items By Vendor" Report
* [Purchase] Add List Search to "Unposted Purchase Order"
screen
* [Sales] Add ship-to column to open sales orders display
* [Sales] Explode Kits on Return Authorizations same as Sales
Orders
* [System] Add the ability to purge sales orders


Bug Fixes:

* [Accounting] All GL Account Types display as Asset
* [Accounting] Production Time Clock by Work Order doesn't
print the Setup and Run Time
* [Accounting] Cost Category: "Copy" allows to duplicate
records
* [Accounting] AR Workbench doesn't show posted invoices
due in the future
* [Accounting] Misc Voucher with Tax distributions not
allowed to post
* [Accounting] Cannot create planned orders for items with
child work orders
* [Accounting] Creating recurring Invoices generates DB log
error
* [Accounting] Beginning balance not reflected in GL Trans
display
* [Accounting] Apply cash receipt to balance references
hard-coded currency id causing failure
* [Accounting] Post M.C. Check in future splits GL trans
across dates
* [Accounting] Trial balances have discrepancies due to G/L
discrepancies account using wrong date to adjust
* [Accounting] When entering Series GL entry, doc number
doesn't clear
* [Accounting] Able to apply more than due
* [Accounting] Voucher is unavailable in the list of
payments
* [Accounting] Debit Memo GL transaction is credit when
should be debit
* [Accounting] Cannot print check run
* [Accounting] Foreign currency vouchers do not save
properly
* [Batch Manager] EDI disappears when some orders selected
for deliver
* [Batch Manager] Non-relevant document types in EDI list
* [Batch Manager] Preview on CRM config should be removed
* [Batch Manager] EDI Form dialog draws with its horizontal
center on the left-hand edge of the display in OS X 10.5
* [Batch Manager] Enabled option on package screen not
working
* [Batch Manager] Incident emails fail in batch manager
* [Batch Manager] Incident profiles not upgraded properly
* [Batch Manager] Expand minimum requirement for sending EDI
* [Batch Manager] Empty email address string not filtered out
* [Batch Manager] Empty attachment sent to email client from
batch manager
* [Batch Manager] EDI: Migration script sets "Review Before
Sending" to false
* [CRM] Can't manually enter info in assigned to field on
incident
* [CRM] Error on creation of address for new contact
* [CRM] Assigning a Task in a new Project displays error
* [Documentation] Inventory availability by customer type
* [Inventory] Unnecessary cartesian join in
distributeToLocation::sDistribute SQL
* [Inventory] Cannot cancel TO line
* [Inventory] Lot-controlled check box visible in PostBooks
version
* [Inventory] Transfer Order Receipts using incorrect
invhist_transtype
* [Inventory] Enter receipt detail for TO misrepresents qty.
returned
* [Inventory] Orders ui called form "Enter Order Receipts"
does not remember size and columns
* [Manufacture] wo_postedvalue grows when correcting
production downward
* [Manufacture] Backflush materials does not correctly
calculate scrap for non-fractional items
* [Manufacture] W/O traveler ignores check box memory
* [Manufacture] Work order qty information doesn't make
sense on correct production posting window
* [Products] Selecting to update/post costs with privilege
displays error
* [Products] Shuffling between two UOMs in an S/O doesn't
refresh the net unit price
* [Products] It is possible to save an empty costing
element after editing
* [Purchase] User is allowed to create duplicate records
for purchase master information codes
* [Purchase] Credit memo for PO Return created with wrong
currency
* [Reports] Purchase Order report print wrong date
* [Sales] Error canceling Sales Order when projects are
auto-created
* [Sales] Cannot add item to sales order
* [Sales] Print engine in sales order screen for "Print on
Save" is not functional
* [Sales] Creating Quote with item types "Job" and "Kit"
displays tax related error
* [Sales] getinvcitemlotserial function is not returning
results for Invoice report
* [Sales] Can't enter Notes in new customer master remarks
tab
* [Sales] Opening new customer window (and saving) from
Sales Order causes crash
* [Sales] Update Prices does not update Characteristic
Prices
* [Sales] Change SO Line quantity does not change P/R
quantity
* [Sales] Creating a quote gives foreign key error on
quhead_shipto_cntct_id = -1
* [Sales] Credit Memo unit price not conforming to Locale
sales price
* [System] EDI Master list report is missing
* [Schedule] MRP does not recognize firm orders in the
past
* [Schedule] Missing priv in Standard Edition prevents
creating planned orders
* [Schedule] No Planned Orders generated for MRP enforce
order parameter off and safety stock set
* [System] Selecting to associate sales rep with employee
generates error
* [System] RA manual number generation displays error
message
* [System] Package can be loaded in an un-enabled state
* [System] Employee record not allowed to save

----------------------------------
Release Notes
xTuple ERP
PostBooks, Standard, and Manufacturing Editions
Version 3.3.0Beta3
July 24, 2009
----------------------------------

Following on the heels of our successful Bug Derby (129 issues
resolved-- and congratulations to jstandring for winning the
Dell Netbook!), we are pleased to announce the release of the
third and presumably final Beta in the 3.3.0 release cycle. Beta
testers are encouraged to please continue testing. Let us know if
you find anything!

This is primarly a bug fix release, as we anticipate the 3.3.0
Release Candidate in August. However, users may be particularly
interested in the performance improvements they will see in this
Beta 3 release. Improved performance has emerged as a major
theme in the 3.3.0 cycle. And in this final beta release, users
can expect to find dramatic performance improvements related to
list sorting and other list-related functions thanks to work done
enhancing load performance in the XTreeWidget.

----------------------------------

The following features and bug fixes have been added to the
applications since the release of 3.3.0Beta2. Additional detail for
each item listed below may be found on our community website
(www.xtuple.org). Simply go to the Issue Tracker and select the
Changelog option.

New Features:

* [System] Add the ability to clear the database error log window


Bug Fixes:

* [All] Sorting performance is slow in large lists
* [All] Xtreewidget copy to clipboard not working with windows
* [All] Button tool tips displaying & character
* [All] Creditmemoeditlist view references Creditmemoitem view
* [All] Migrating from 322 to 330beta displays error
* [All] Slow rendering performance in newer versions with large data
sets
* [Accounting] Printed FRE income statement formats percent columns
incorrectly
* [Accounting] User is unable to create a new Voucher
* [Accounting] CRM Account screen deleting customer/prospect gives
error
* [Accounting] Budget Accounting Periods invert selections not
functional
* [Accounting] Customer Invoice EDI profile - problem in assigning a
new one
* [Accounting] User is able to edit AR open items without privilege
* [Accounting] Cash receipt that resulted in credit does not reverse
correctly
* [Accounting] Odd linkage between posting a CR and CRM Account/
Contact/Incident usage
* [Accounting] Send electronic Purchase Order unavailable from
right-click
* [Accounting] Posting multicurrency CM and DM results in uneeded
G/L posting
* [Accounting] Order cluster xtree sizing isn't right on search
* [Accounting] Orphaned credit card appears on Sales Order
* [Accounting] Can't void a check if it was transmitted
electronically
* [Accounting] Invoice Register: Partial Entries and incorrect
totals displayed in report
* [Accounting] Customer lookup widget in A/R open item calls
wrong workbench
* [Accounting] Selecting to view source Check in A/P applications
displays no details
* [Accounting] Division by zero when posting Invoice
* [Accounting] Exchange Rate error on Misc Voucher
* [Accounting] Selecting to print A/P Accounts Assignments prints
partial report
* [Accounting] Cost Category: 'Copy' allows to duplicate record
* [Accounting] It is possible to create duplicate records for
reason codes
* [Accounting] Cancel SO Line does not delete PR
* [Accounting] User is allowed to duplicate records for Standard
journal and Standard journal group
* [Accounting] Selecting to duplicate tax codes creates an empty
record
* [Accounting] The Summarized G/L transaction display does not
show summary numbers
* [Accounting] Summarized G/L Transactions prints unexpected
results
* [Accounting] Sales Order Credit Memos do not backdate
inventory returns
* Accounting] Date fields not converting properly
* [Accounting] Should be warning when attempting to post
invoices into closed periods
* [Accounting] A/P Misc Voucher may be saved with zero
distribution amount or with incomplete distributions
* [Accounting] Selecting to post a cash receipt with funds type
using Credit Card displays error
* [Accounting] Converted SO/CM results in negative ta
* [Accounting] A/R Workbench allows refunding credit memos not
associated with credit card cash receipts
* [Accounting] Change label on customer history window to indicate
date selection is based on document date
* [Accounting] Printed Invoice does not show tax
* [Accounting] Tax calculation error
* [Accounting] Summarized backlog report not sorting properl
* [Accounting] It is possible to create duplicate Tax Codes
* [Accounting] Cash receipt window's apply line balance button
applies base currency amount to non-base cash receipt
* [Accounting] Selecting to save misc tax distribution generates
DB log
* [Accounting] Posting a credit card refund gives an arapply
trigger error
* [Accounting] Print engine in list unposted invoices is not
functional
* [Accounting] Selecting to view Transfer Order Line in Maintain
Shipping displays blank template
* [Accounting] Cannot print check for ACH vendor
* [Accounting] Post C/M on hold should trap for descriptive
message
* [Accounting] Batch Manager not working on STD Edition
* [Accounting] Voucher head not found on new misc Voucher
* [Accounting] Function FormatPrice results in incorrect result
* [Accounting] Maintain Shipping erro
* [Accounting] Database function formatACHChecks Patch
* [Accounting] Posting checks takes too long
* [Batch Manager] Cannot reload deleted package
* [Community] Update Community menu link information
* [Community] Discussion Forums page not found
* [CRM] Selecting to create a new Address displays wrong screen
position
* [CRM] Inactive users still available in selected combo box on
To Do List
* [CRM] CRM Account add - from Opportunity ? button - fails
* [CRM] User is allowed to save an empty contact
* [CRM] Contacts Screen: when expanding the notes section the
header also expands
* [CRM] Auto-populate CRM account when creating a to do from
an Opportunity
* [CRM] It is possible to edit/delete files documents in view
mode
* [CRM] Data can easily be overwritten when adding a vendor
that is already a customer
* [CRM] Users with access to CRM can see vendors screen
partially
* [CRM] Null state value causes crash
* [Inventory] Prevent adding Kit Items to Transfer Orders
* [Inventory] It is possible to generate negative item site
values for average-costed item sites
* [Inventory] Making an already negative item MLC creates
problems with Location/Lot/Serial Detail
* [Inventory] Shipment report is not available to print
* [Inventory] Forward and backward trace allow no escape
mechanism for infinite loops
* [Inventory] Default distribute > QOH if it is less than
distribution requested
* [Inventory] Site Transfer not calculating average cost
correctly, results in negative inventory value
* [Inventory] View in external shipping list displays
mismatched dialog box
* [Inventory] Selecting to edit an external shipping record
doesn't save the updates
* [Inventory] Distribute quantity should not be populated
with value > QOH in location
* [Inventory] Lot tracked items lose link in invhist
* [Inventory] Selecting to print site types displays 'Report
not found'
* [Inventory] Cannot drive negative inventory where stock is
0
* [Inventory] Inventory history can have unposted counts from
previous bug
* [Inventory] Recall Orders does not delete all data, creates
problems later
* [Inventory] Distribute to location dialog qty will not
 accept a negative when issuing stock
* [Inventory] Issue to Shipping sort is incorrect
* [Inventory] Ui form called form "Enter Order Receipts" does
not remember size and columns
* [Inventory] Transfer Orders do not close when have a
canceled line
* [Inventory] Posting a receipt for Lot controlled Item
displayed error
* [Manufacture] Post operations screen is displayed on clicking
"OK" button in the warning
* [Manufacture] Work order qty information doesn't make sense
on correct production posting window
* [Manufacture] W/O Traveler ignores check box memory
* [Manufacture] Change column names in reports to "Reference"
from "Ref. Designator(s)"
* [Manufacture] Manufacturing scrap by component use wrong cost
* [Manufacture] The label 'Received' is misspelled in Post
Production screen
* [Manufacture] Create WO does not always default to correct
WO cost recognition for average cost items
* [Manufacture] Posting scrap of qty greater than issued does
not record GL transactions
* [Manufacture] Cannot return by batch when disassembly WO
status=R
* [Manufacture] Unable to post production
* [Manufacture] Posting misc. production does not properly
account for scrap
* [Manufacture] Update top level WO qty and due date in the
indented WO list should update widgets above
* [Manufacture] Scrap WO material dialog not filled in when
called from indented WO list
* [Products] Cannot print Item image
* [Products] Revisions don't let you create a new one
* [Products] Selecting to save an empty image record in Item
generates DB log error
* [Products] Selecting to duplicate freight classes generates
DB log error
* [Products] Show actual versus standard cost filter - does
not address currency
* [Products] Require 0 QOH at all sites before inventory UOM
can be changed
* [Purchase] Returning inventory on PO generates negative
values
* [Purchase] Able to enter leading zeros if PO order number
generation is manual
* [Purchase] Review EDI before sending - output file blank -
no preview
* [Purchase] Changing any field in poitem reverts overridden
price to item source price
* [Purchase] Purchase Order entry is effectively single user
* [Purchase] Able to delete received PO via CLOSE PO lin
* [Purchase] Able to delete received PO line via DELETE on
Quick Entry
* [Purchase] Delete quick entry in purchase order is not
functional
* [Purchase] Error on Post Purchase order with only Post
Purchase Order Privilege
* [Purchase] User is allowed to create duplicate records for
purchase master information codes
* [Reports] Form link to reports is fragile
* [Sales] RA return product to inventory at 0 cost
* [Sales] CRM Account master window is scrunched
* [Sales] Quote report displays incorrect characteristics
* [Sales] Selecting to attach an EDI profile to a customer
displays error
* [Sales] Typing in a new contact name on the fly on a sales
order doesn't create the contact record in CRM
* [Sales] Post receipts from the Return Authorization window
does not appear to be working
* [Sales] Invoice tab display does not display amount paid
* [Sales] A/R account assignments list prints partially
* [Sales] Possible to delete SO with Inventory History
* [Sales] Summarized backlog does not display S/Os in the
list
* [Sales] Error when List Open Sales Order window opens
* [Sales] User friendly message should be displayed on
duplicating pricing schedule qty. to break by edit
* [Sales] Sales Account Assignments: User is allowed to
duplicate records
* [Sales] Cannot create new employee - api.employee problem
* [Sales] Return authorization error screen
* [Sales] Selecting to print sales category displays 'Report
not found'
* [Sales] Navigation between types not working as expected
* [Sales] Currency error on Customer information workbench
* [Sales] Sales Account Assignments list, prints partially
* [Sales] Summarized Sales History by shipping zone by item:
prints blank page
* [Sales] Selecting to duplicate customer types displays
error message
* [Sales] Duplicating shipping forms generates error message
* [Sales] It is possible to create duplicate records for
shipping zones,via and charge types
* [Sales] Sales Category: 'Copy' allows duplication of record
* [Sales] Entering new customer data in logical order loses
data entered on previous screen in the same add session
* [Sales] Patch to dspPricesByCustomer.cpp to use a Customer's
Default Discount in calculating the List Price column
* [Sales] Inactive ship-to's can be selected in sales order
entry
* [Sales] Unable to set Uses Blanket P/Os on Customer - settings
- terms screen
* [Sales] Cannot comment a line item on Sales Order until after
SAVE
* [Sales] Cannot Override P/R price in quote and S/O line
* [Sales] Post SO Credit Memo via Print Credit Memo does not
prompt for lot/serial number
* [Sales] Add ability to set resale price and calcualte
difference on Returns
* [Schedule] Selecting to create a new Production Plan displays
irrelevant dialog
* [Schedule] Db error saving production plan item
* [Schedule] Schedule menu on/off because of multi-Site
* [Schedule] The report 'Planned Rough Cut' doesn't display
calendar years
* [Schedule] Selecting to print 'Planned Revenue' generates
DB log error
* [System] Hot Key support for Location/Lot/Serial# detail
screen missing
* [System] Designer screen remembers size when it shouldn't
* [System] Api.customer errors on billing_contact_change
values
* [System] Exchange rate precision problem
* [System] Custom command will not open a document directly
* [System] Packages report def missing
* [System] Duplicating Employee group generates error message
* [System] It is possible to create empty Employee groups
* [System] Creating new PO with manual number generation
creates DB log error
* [System] Double click on comment type doesn't open in edit
mode
* [System] Update TOC links to new Drupal site
* [System] Configuration: Adding line Item in sales displayed
error
* [System] User friendly message should be displayed on
duplicating Department records
* [System] Selecting to associate sales rep with Employee
generates error
* [System] Crash on application exit, possibly related to
embedded designer

----------------------------------
Release Notes
xTuple ERP
PostBooks, Standard, and Manufacturing Editions
Version 3.3.0Beta2
July 07, 2009
----------------------------------

This is the second Beta release of version 3.3.0. Thanks to all
in the community who have contributed feedback on the earlier
releases in this beta cycle. Keep up the good work!

For anyone who has been tracking the EDI Profiles and International
Tax development, the following new features/fixes are available for
testing in this release:

EDI Profiles Revision
  * Beta2 adds support for
	- A/R Statements
	- Sales Order Credit Memos
  * Full spec: http://www.xtuple.org/EDIProfilesRevision

Improved VAT and international tax support
  * Beta2 adds fixes for
      - Multiple rounding problems
  * Full spec: http://www.xtuple.org/EnhancedTaxInternationalization

----------------------------------

The following features and bug fixes have been added to the
applications since the release of 3.3.0Beta. Additional detail for
each item listed below may be found on our community website
(www.xtuple.org). Simply go to the Issue Tracker and select the
Changelog option.

New Features:

* [Accounting] Add Journal number to taxhist tables for
reconciliation
* [Accounting] Allow multiple distributions for Misc. Credit and
Debit Memos
* [Accounting] Improve flexibility of discount for quick payment
on Vouchers
* [Accounting] Change the GL transactions screen to default to a
single account
* [Accounting] Add ability to e-mail Credit Memos and AR Statements
* [Accounting] Bank Reconciliation history report needs improvement
* [Accounting] After initial Bank Reconciliation, automatically fill
in opening balance and starting date
* [Accounting] Opening balance when reconciling Bank Accounts should
be automatically populated
* [Sales] Add the ability to create a new Customer from the Sales
Order window
* [System] Create API views for Projects
* [System] Drop-down selection of database on login screen


Bug Fixes:

* [Accounting] Tax code rate does not support 4 decimal places
* [Accounting] Failed stored procedure when posting Cash Receipt
* [Accounting] The automatic "Select for Billing" option takes effect
for kit items when nothing has shipped
* [Accounting] Posting A/P Debit Memo generates db log error
* [Accounting] Selecting to save a Tax Registration generates db log
* [Accounting] Tax calculations confused when manually changing the
currency on a Misc. Invoice.
* [Accounting] It is possible to enter a duplicate registration for
the Tax Zone and Authority
* [Accounting] Selecting to cancel creating a new Tax Code creates
an empty one
* [Accounting] Voucher head not found on new Misc. Voucher
* [Accounting] Selecting to create recurring Invoices generates db
log
* [Accounting] A/R open records should use fixed exchange rate
instead of floating when calculating gain/loss
* [Accounting] Tax History for a selection displays erro
* [Accounting] Cash receipt that resulted in credit does not reverse
* [Accounting] Attempting to edit unposted Invoice causes crash
* [Accounting] Rounding errors on Tax
* [Accounting] Printed report missing for tax histor
* [Accounting] Selecting to print Bank Reconciliation History
generates db log
* [Accounting] SO Line Entry appears to change header Tax Zone
* [Accounting] Date fields will not take mm/dd/yy like they used to
* [Accounting] Unposted Receipts window takes a long time to query
on large dataset
* [Accounting] The AP Aging report does not show the Vendor's
invoice numbers
* [Accounting] User is unable to create a new Voucher
* [CRM] Search box not functioning correctly
* [Inventory] Stock distribution error message in MLC
* [Inventory] Able to save Expense Category with no PPV account
* [Inventory] Deadlock possible shipping Job Items
* [Inventory] Creating and editing inventory receipt Items takes a
very long time on large datasets
* [Inventory] Receiving raw material inventory - post receipt- takes
too long
* [Inventory] Selecting to print Item location displays error
* [Inventory] Selecting to view item locations displays error
* [Manufacture] Correct production sets Work Order posted and WIP
values incorrectly for average-costed Items
* [Products] Selecting to create a revision displays error
* [Products] Extended cost is rounding incorrectly in the single
level Bill of Materials
* [Products] Many costs being formatted, ignoring Locale
* [Purchase] PO non-inventory line item with Tax not on header
* [Purchase] Selecting to create PO line item generates db log error
* [Sales] Post SO Credit Memo via Print Credit Memo screen does not
prompt for lot/serial number
* [Sales] Selecting to create a Sales Rep displays error
* [Sales] Selecting to print Quote list generates db log erro
* [Sales] Tax calculation rounding to 2 decimals even though
precision is set to 4 digits
* [Sales] Unable to enter freight on unposted Invoice
* [Sales] Erroneous rounding on Tax calculation
* [Sales] Cannot search on RA item or CM item
* [Sales] Post Receipt for RA takes a long time and other operations
are all frozen
* [System] User is allowed to create duplicate records for Label
Forms
* [System] Setting the validator to blank on Characteristics renders
the characteristic uneditable
* [System] Report definition missing for Comment Types
* [System] Set English as the default language in Quickstart and Demo
databases so date formatting is consistent

----------------------------------
Release Notes
xTuple ERP
PostBooks, Standard, and Manufacturing Editions
Version 3.3.0Beta
June 23, 2009
----------------------------------

This is the Beta release of version 3.3.0. Owing to the extent of
new features in this release, we are eager to get feedback from
Beta testers. In particular, the following new areas of
functionality deserve attention:

Distribution Resource Planning (DRP)
  * Full spec: http://www.xtuple.org/DistributionResourcePlanning

Improved VAT and international tax support
  * Full spec: http://www.xtuple.org/EnhancedTaxInternationalization
  * Beta adds the following
	- Support for tax on Return Authorization
	- Support for tax on Credit Memo
	- Support for tax on A/R Misc Credit Memo
	- Support for tax on A/R Misc Debit Memo
	- Support for tax on Purchase Order
	- Support for tax on Voucher
	- Support for tax on A/P Misc Credit Memo
	- Support for tax on A/P Misc Debit Memo
	- New Tax History Report

EDI Profiles Revision
  * Full spec: http://www.xtuple.org/EDIProfilesRevision
  * Beta adds support for
	- Incidents
	- Sales Order Acknowledgements
	- Invoices
	- A/R Statements
	- Purchase Orders
  * Bcc now working
  * EDI Profiles on Customers now working

Multiple Accounting features
  * Re-allocation of AR applications
  * Automated forward-updating
  * Reverse Cash Receipts
  * Printing AR Memos
  * And more....

Translation
  * Support for translating extension packages

----------------------------------

The following features and bug fixes have been added to the applications
since the release of 3.3.0Alpha. Additional detail for each item
listed below may be found on our community website (www.xtuple.org).
Simply go to the Issue Tracker and select the Changelog option.


New Features:

* [Accounting] Add tax code to A/R misc. memos
* [Accounting] Allow multiple tax distributions for Misc Credit and
Debit Memos
* [Accounting] Allow cash receipts to distinguish between distribution
date of receipt, and application date to documents
* [Accounting] Credit Card pre-authorizations create cash receipts as
"Credit Memo" not "Customer Deposit"
* [Accounting] Specify globally whether credit cards should generate
credit memos or customer deposits
* [Accounting] Add text search to Enter Order Receipt window
* [Inventory] The "To" name on the order cluster search should show the
ship to name if one exists
* [Inventory] Add right-click menu Print Receipt Label to PO Receipt
screens
* [Manufacture] Indented Work Order screen tab to edit and issue
materials
* [Manufacture] Add filter check box "Item Not In Stock� to Inventory
Availability By Work Order
* [Purchase] Tax calculation needed on PO
* [Purchase] Add tax calculations to Purchase Orders
* [Purchase] Add List Search to "Unposted Purchase Order� screen
* [Purchase] Add a list filter and vend item# column to "PO Items By
Vendor� Report
* [Purchase] Add Vendor description column to quick order entry tab
* [Sales] Enhance Tax handling - omnibus
* [Sales] Add ability for new/edit Characteristic Assignments to
Customers by Characteristic report
* [System] Global EDI profiles don't allow a way to default e-mail
address
* [System] Add From and BCC address to EDI profiles
* [System] Add Bcc: option to EDI profiles
* [System] Password change utility
* [System] Enforce Characteristics input mask and regex validator
* [System] Add ScriptToolbox::getTempDir() method
* [System] Comment types can be associated with many different items


Bug Fixes:

* [All] Issue Stock to Shipping permission does not work alone
* [Accounting] potential issue with trigger _checkheadbeforetrigger()
* [Accounting] It is not possible to enter Start Date for General Ledger
Series
* [Accounting] Remove column options in AR Applications report
* [Accounting] Number -1 on cash receipt
* [Accounting] Tax - Item Tax Type/Tax Auth - Select Should be Most
Specific
* [Accounting] Not able to save Purchase Order Comments
* [Accounting] Privilege hole in Sales Order
* [CRM] Tab order in ToDo item entry skips "owner� and "assigned to�
* [CRM] Selecting to associate a CRM account with a customer displays
error
* [CRM] Selecting to Edit and Save an Opportunity creates a new one
* [CRM] User is able to edit "Use of Contacts� in Contact's view mode
* [Inventory] External Shipping List: User is unable to create a new
external shipping maintenance
* [Inventory] External Shipping List: Wrong window display in View mode
* [Inventory] User is able to save expense category without name and
description
* [Inventory] Ship order: Selecting "Create and Print Invoice� and
"Print Packing List� displays an error for a Job Item
* [Inventory] Posting PO Receipts requires "MaintainPurchaseOrders�
privilege but is an inventory function
* [Inventory] Slow query performance in larger databases at Shipping
* [Manufacture] Selecting to correct operations posting displays an
error
* [Products] It is possible to add Conversion, new Sites and Sources for
an Item in VIEW mode
* [Products] Selecting to create a Item cost for an Item displays error
* [Purchase] Incorrect message when printing PO
* [Purchase] Incorrect alter quantity message on a non-inventory item
 * [Purchase] Database error selecting postPoReturnCreditMemo
* [Purchase] It is possible to save Terms without specifying any code
* [Sales] Email EDI profiles on customers do not work
* [Sales] Canceling Kit Item closes all SO lines
* [Sales] Ability to comment a line item on Sales Order
* [Sales] Customer info disconnected on Sales lookup report
* [Sales] Sales History by Customer link to Invoice Information does not
work
* [Sales] Lockup/crash when opening sales order
* [Sales] User is able to create duplicate records for Sales
* [Sales] It is possible to save Sales Category without specifying name
* [Sales] Sales Representative: Selecting to associate employee doesn't
save
* [Sales] It is possible to create empty Customer groups
* [Sales] Sales history archived by error cannot be restored
* [Sales] A/R Account Assignments: User is allowed to duplicate records
* [Sales] Packing List Batch: Selecting "X� button to add SO generates DB
log error
* [Sales] Possible to have no SO orderdate on cohead
* [Sales] Error canceling Sales Order when projects are auto-created
* [Sales] User is unable to create new Prospect
* [Sales] Selecting to print a Quote generates DB log error
* [Sales] Sales order print displays blank page and generates DB log error
* [Sales] Update Prices does not update Characteristic prices
* [System] User is allowed to add/revoke privileges to a group in view mode
* [System] Grant access to only selected sites gives an error
* [System] It is not possible to save a new employee record
* [System] Error message when editing users
* [System] Mismatched variable naming in getshiptonumberfrominfo
* [System] Missing sort directive in getshiptonumberfrominfo
* [System] Issues with getshiptonumberfrominfo function

----------------------------------
Release Notes
xTuple ERP
PostBooks, Standard, and Manufacturing Editions
Version 3.3.0Alpha
June 03, 2009
----------------------------------

The following features and bug fixes have been added to the applications
since the release of version 3.2.2. Additional detail for each item
listed below may be found on our community website (www.xtuple.org).
Simply go to the Issue Tracker and select the Changelog option.


New Features:

* [All] Add "Copy to Clip Board" to XTreeWidget default Context Menu
* [All] Application has hard-coded shortcut keys
* [All] Integrate xTuple user and PostgreSQL users
* [All] Need to determine translation mechanism for screen builder
extensions
* [All] Updated menus to be more memory efficient and to address some
issues related to rescanning privileges
* [Accounting] Add ability to filter out trial balances with no balance
or activity.
* [Accounting] Change or Remove the automatic forward account balances
capability in Accounting
* [Accounting] Add option to make forward updating accounts fully
automatic
* [Accounting] Enable reversing of Cash Receipt postings
* [Accounting] Adjustment Types description column show name value
* [Accounting] Enable re-allocation of AR applications
* [Accounting] Need to do a negative cash receipt
* [Accounting] Display Cash Receipt subtotals
* [Accounting] Preserve cash receipt info in arapply, credit memos,
and cash deposits
* [Accounting] Enhance Expense Cat Master List to Show G/L Accounts
* [Accounting] Invoice: Add Due Date and Discount Date
* [Accounting] Cannot control Customer's Check Date
* [Accounting] Reference and Notes for Vouchers
* [Accounting] Printing Debit Memos or Credit Memos
* [Accounting] Voiding vouchers does not undo distributions
* [Accounting] Change Reprint Invoices to allow selection by Balance
Due
* [Batch Manager] "Make "Submit Action to ..." Send Email
* [CRM] Add email to searchable fields on CRM Search for Contact
* [CRM] Improve visibility to prior comments on Incident Workbench
* [CRM] Need ability to edit comments
* [CRM] Create Jump To field for incident number
* [CRM] Comments for To-Do's and Tasks
* [Inventory] In Built Inventory Availablity by...
* [Inventory] ABC Classcode and Cycle Count Frequency added to
dspItemSitesByParameterList.cpp
[Inventory] Add an ability to set Location Default whilst Posting
to Inventory
* [Products] Create Item Site by Class Code Util - Needs First
Group field
* [Purchase] Purchase Order Items Window - Prices Tab
* [Purchase] Enhance PO Report Def - Alt Address Prints as Ship To
* [Schedule] Add Distribution Resource Processing (DRP) capability
to Standard Edition
* [Sales] Reorganize and consolidate customer information
* [Sales] Add button to Return Authorization workbench to create a
NEW RA
* [Sales] Rcv site in RA header doesn't affect sites in RA items
- P/R Column
* [Sales] Add Function getpacklistitemlotserialqty()
* [Sales] Explode Kits on Return Authorizations same as Sales Orders
* [Sales] Allow Kit components to inherit COS from Kit parent
* [System] Change default script extension to .js
* [System] Add support on lists (xtreewidget) for export to CSV, ODF
and HTML file formats
* [System] Expose method to add right click menu on xtreewidget and
xtreeview via scripting
* [System] Provide method to open core xTuple screens from other
screen builder screens
* [System] Rework layouts on windows using parameterGroup and
warehouseGroup to use "natural" layouts
* [System] Additional alert functionality when cost exceeds max cost
* [System] Enable incident emails by category setting
* [System] Add the ability to purge sales orders
* [System] Reason Codes assigned to documents
* [System] Add "sticky" memory to grid sorting on xtreewidget
* [System] Add DB Configuration Option to Disallow All User Logons
* [System] Add command line arguments for specifying Enhanced Auth
and SSL boolean
* [System] add include facility to scripting


Bug Fixes:

*  [All] Date Time Stamp in comment change log displays time as
12:00:00 AM
* [All] Remove Schedule Backup menu option
* [All] Obsolete macro in widgets library
* [All] some tables have user ids but should have user names
* [All] Missing return from Screen::submit()
* [Accounting] Tax liability note on G/L transactions causes G/L
series not to group properly
* [Accounting] Post zero amount invoices to aropen, simplify AR
Open query
* [Accounting] Accounting menus inconsistent
* [Accounting] possible to have a closed aropen item with no
aropen_closedate
* [Accounting] Customer Information Workbench missing previously
available information
* [Accounting] Privilege Hole in Sales Order
* [Accounting] Viewing Unposted Invoices
* [Accounting] Sales Order Lookup - Pattern Matching Not Working
* [Accounting] Inactive Vendors not controlled in miscellaneous
voucher entry
* [Accounting] Rescan privileges ignores initMenu script
* [Accounting] Right click drill down results on A/R aging are
incorrect
* [Accounting] GL Trans Report for Doc Type 'IN' does not display
Customer Name
* [Accounting] CR notes not carried forward
* [Accounting] Need to do a negative cash receipt
* [Accounting] Negative cash receipts
* [Schedule] MRP - Grouping Adds Extra Day
* [Accounting] Possible rounding errors when vouchering/processing
in multiple currencies different from base
* [Accounting] Able to save and 'post' a blank Cash Receip
* [Accounting] Deposit Registry does not total Base Balance
* [Accounting] Cash Receipts missing Base Amount column and
total
* [Accounting] Cannot load CSV credit card information to
custcreditcard view
* [Accounting] Cannot load CSV G/L Accounts from glaccount view
* [Accounting] Financial reports printing zeros by group headers
* [Accounting] Post Check generates "Check does not balance"
error message
* [Accounting] Fix Serial Columns screen Fix button produces
error
* [Accounting] Db error posting misc. check with debit memo
* [Accounting] Menu Item Tool-tips non-translatable
* [Accounting] API view glaccount incorrectly defaults profit_center
and sub_account to '1'
* [Batch Manager] creating an edi profile gives missing
ediprofile_emailhtml error
* [CRM] User is able to edit 'Use of Contacts' in Contact's
view mode
* [CRM] Special characters problem on incident workbench?
* [CRM] Tab order incorrect in Task Window
* [CRM] Can not double click opportunity
* [CRM] Contact not opening on double-click
* [CRM] Text > Integer issue
* [CRM] saveAddr() uses wrong comparison technique
* [CRM] tab order in ToDo item entry skips "owner" and "assigned
to"
* [Inventory] Detail Inv Hist by detail Date range do not
deactivate
* [Inventory] error message on delete site location is misleading
* [Inventory] Inventory UOM vs Vendor UOM on Receiving screen.
* [Inventory] Print Shipping Form screen -- Remove shipping
charges
* [Inventory] Multiple Issue Stock to Shipping cause Packing List
to report incorrect Qty Shipped
* [Inventory] Post Count Tag Difference can create multiple
entries for same location, same item
* [Inventory] Update ABC class generates DB log error
* [Inventory] Able to create blank Site type record
* [Inventory] Deleting Site type record generates DB log error
* [Inventory] Transfer Order does not expand list correctly
* [Manufacture] Return W/O Mat. Batch -- Commit executed
erroneously after error
* [Manufacture] Disassembly Work Orders Should not check Order
Parameters
* [Products] Copy BOO doesn't copy closewo flag
* [Products] Canceling to create a new item group member displays
mismatched message
* [Products] Delete does not refresh list in Class codes
* [Purchase] Purchaseorder api allows import of leading zeros
* [Purchase] Characteristics not printed on PO
* [Purchase] User is allowed to post comments while viewing
Purchase Order details
* [Purchase] Purchase Request by Planner Code does not expand
list correctly
* [Reports] Backlog by Customer mixing information
* [Reports] Financial Report Grade 0 errors
* [Reports] SO Picklist - Wrong Use of Line Function
* [Sales] Can not issue credit on credit card processor from
script
* [Sales] UPC does not show up on Item search scree
* [Sales] Credit Memo Item Search error when Item UPC Code checked
* [Sales] Update ship via on invoice and packing list when SO is
saved
* [Sales] Kits do not delete from SO
* [Sales] Negative customer discount was removed
* [Sales] Error importing to api.salesline
* [Sales] Update Prices does not update Characteristic Prices
* [Sales] Credit memo item lookup (ctrl-L) fails due to lack of
explicit type casts in PostgreSQL 8.3.X
* [Sales] Sales order contact information is missing from
api.salesorder
* [Sales] api.salesorder should allow for manually set number even
when numbering is set to automatic
* [Sales] SO and Invoice not honoring default UOM in pricing
* [Sales] SO Ship To Phone Number does not write to invchead table
* [Sales] RA Workbench: Print RA with selected customer type
generates DB log
* [Sales] Packing List Batch: Selecting "x" button to add SO
generates DB log error
* [Sales] creditCard.cpp compiler warning
* [Sales] Customer Information Workbench does not check for
privilege
* [Sales] Quote for Prospect does not filter contact list to
selected CRM account
* [Sales] Newly created invoices are not displayed in Customer
Workbench
* [Sales] Summarized Sales By Customer By Item - Average Price
Calculation is Wrong
* [Sales] Sales History by Customer link to Invoice Information
does not work
* [Sales] Selecting disposition as "Credit" and credit by as
"None" displays database error
* [System] Free floating windows don"t close when application
closes
* [System] Images list unusuable over slow remote links
* [System] locale - timestamp format issue
* [System] Change parameterGroup and warehouseGroup to layout
and size naturally
* [System] Edit User cancel button does not wor
* [System] Add command line arguments for specifying Enhanced
Auth and SSL boolean
* [System] schedule server backup or server maintenance with
time but no date gives sql error
* [System] empty default credit limit causes an error importing
sales order xml
* [System] replace OpenMFG with Manufacturing
* [System] add include facility to scripting
* [System] User is allowed to add/revoke privileges to a group
in view mode
* [System] Exchange Rates: Overlapping of date ranges generates
DB log error
* [System] api.creditmemo - cust_number Not Defaulting Bill-To
Info
* [System] Qt designer (external) gives driver errors when
opening
