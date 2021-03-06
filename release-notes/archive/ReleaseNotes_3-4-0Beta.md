Release Notes
xTuple ERP
PostBooks, Standard, and Manufacturing Editions
Version 3.4.0Beta
October 27, 2009
----------------------------------

This is the Beta release of version 3.4.0--and also the first
release in this shortened release cycle. Implementing the
Manufacturing Edition as a package is the major focus of this
release. And because of that we are especially eager to hear
feedback from beta testers running the Manufacturing Edition.
Here's an overview of new features in this release:

Manufacturing Edition functionality as scripted Package
  * Full spec: http://www.xtuple.org/issuetracker/view.php?id=8333

Script Debugger
  * Full spec: http://www.xtuple.org/issuetracker/view.php?id=8189

CRM
  * Multiple enhancements to Opportunities

NOTE: If you are upgrading your database to version 3.4.0Beta, you
must use the new Updater, version 2.2.0Beta.

----------------------------------

The following features and bug fixes have been added to the
applications since the release of 3.3.1. Additional detail for each
item listed below may be found on our community website
(www.xtuple.org). Simply go to the Issue Tracker and select the
"Changelog" option.


New Features:

* [All] Convert xTuple Manufacturing Edition into a package
* [Architectural] Add a boolean property to the screen widget that
designates document locking
* [CRM] Link Quotes and Sales Orders to Opportunities
* [CRM] Tracking Changes in Opportunities
* [CRM] Need to be able to search Opportunities by Name and CRM
Account
* [CRM] Inactive Opportunities
* [CRM] Additional filters on Opportunities
* [Sales] Add documents widget to Sales Order and Quote
* [System] Script debugger
* [System] Create views for budget and budget entry
* [System] Expose ability to communicate with web services to
scripting
* [System] Add Q_INVOKABLE functions to vendorsgroup widget


Bug Fixes:

* [Accounting] Rescan does not correctly update scripted menu
items
* [Accounting] Misc. Check doesn't clear CM amount
* [Accounting] Deleting a multi-job sales order only deletes
the first job item
* [Accounting] Changing quantities of materials on work orders
does not honor the fractional flag of the materia
* [Accounting] When typing JE on the G/L series screen user
only can jump to next field with tab key
* [Accounting] Item Allocations display uses work order due
date when it should use material requirement due date
* [Accounting] indented BOM list description only shows
item_descrip1 column
* [Accounting] It is possible to change currency on bank
account
* [Accounting] Transaction pairs separated on gl trans printed
report
* [Accounting] Tax not reversed when voiding vouche
* [Accounting] Voiding voucher does not undo misc. tax
distribution
* [Accounting] Incomplete vohead record precludes subsequent
processing of voucher
* [Accounting] Can not load more than one UI into a screen
with scripting
* [Architectural] Scripts can not access the user name in the
username cluster
* [Architectural] Flip Files and Images button on Documents
Widget
* [Architectural] Screens should specify "Grade" instead of
"Order" and use grade logic
* [Architectural] XComboBox updates mapper model after
newID(int) signal
* [CRM] Auto Populate CRM Acct in To-Do created through an
Oppty
* [Inventory] Cannot edit item site when created with utility
* [Inventory] Releasing TO from Line Item closes lin
* [Inventory] Running availability is much slower in version
3.3.0RC2 than 3.2.2
* [Inventory] Year End/Inventory count posting dates
* [Inventory] Site window does not let you set up tax zone;
still uses tax authority
* [Inventory] Receiving TO line items with not enough stock
in transit site gives an error
* [Manufacture] Enter does not save on Work Order screen
* [Manufacture] Comment types on Close Work Order not
filtered
* [Manufacture] Error While querying Production Time Clock
by Work Order report
* [Products] Viewing cost detail fails with error "rev" does
not exist
* [Purchase] Open/close PO line items do not show on "by
vendor" report
* [Purchase] Rescheduling purchase order accepts blank dates
* [Purchase] Item Source screen: Vendor ellipsis pulls up a
list and not a search window
* [Purchase] Print Purchase Orders By Agent screen not
working
* [Reports] Quote Template total calculation omits Misc.
Charges
* [Reports] PO rounding problem
* [Sales] Incorrect data fetched in soheadtrigger
* [Sales] 3.3 Sales analysis report issues
* [Sales] Credit memo line item UOM changes back to default
when editing CM line
* [Sales] Create invoice is much slower than previous version
* [Sales] Voided Check to Customer creates incorrect AR
document
* [Schedule] MRP not creating order for demand because of
existing PRs
* [Schedule] Selecting to release Planned orders generates
db log error
* [System] Privs problem for custom menu items
* [System] XCheckBox memory doesn't work in screen builder
environment
* [System] Vendor Cluster id() function stops script
* [System] Problem importing an invoice with no Order Number
* [System] lupdate gives errors when processing scripts that
use #include
* [System] Work order explosion ignores config option
