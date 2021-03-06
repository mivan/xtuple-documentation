Release Notes
xTuple ERP
Version 4.0.0Beta
May 17, 2012
----------------------------------

This is the beta release of version 4.0.0. This release includes
several new features and bug fixes. As always, we are looking for
feedback from beta testers. However, if you do test the beta,
please be reminded beta software should not be used in live
production.

Information about compatibility issues related to this software
version can be found on the xTuple Compatibility Matrix at the
following address: www.xtuple.org/compatibility-matrix.

Here's an overview of notable new features in this release:

Added tabs to desktop
  * Converted "inside the desktop" view to use tabs for every
    open screen

Enhanced Job Costing functionality
  * Purchase-to-Job
  * Automatic issue of Purchased Items to Work Orders
  * Job Costing for child Work Orders

Multiple Project updates
  * Ability to copy Projects
  * And more ...

----------------------------------

The following features and bug fixes have been added to the
applications since 4.0.0Alpha. Additional detail for each item
listed below may be found on our community website under the
Issue Tracker.

New Features:

* Item Source UOM [17016]
* Time of Receiving Cost Override (Items Costed at Average)
[12124]
* Planned Orders Screen Enhancement [15057]
* Allow entry of an Alternate Revenue Account for a Sales Order
Line Item [15444]
* Incidents should be enhanced to be filterable on Item and
Lot/Serial numbers [16607]
* Planned Orders screen needs Class Code as filter option
[16841]
* Make posting into closed periods a privilege [16955]
* 380 installer - deal with legacy postgres installs [17173]
* 380 installer - signal to user that pg install takes time
[17174]
* 380 installer - move Windows uninstaller warning [17177]
* Add the ability to "turn off" G/L postings from Accounts
Receivable [17184]
* Add the ability to "turn off" G/L postings from Accounts
Payable [17185]
* Production Plan [17250]
* Remove hardwired cloud features for 4.0 [17426]
* checkbox for inactive on employee list [17531]


Bug Fixes:

* Slow MLC performance with thousands of locations [17405]
* External shipping maintenance screen should require
information [7513]
* user has to enter xml-related import/export config even if
only doing csv imports [11504]
* Saving a sale displays an irrelevant dialog [14133]
* Selecting an Address displays irrelevant dialog [14299]
* Unable to create recurring To-Do items [15786]
* "Credit card" tab is not available on opening a Cash
receipt in View mode [15815]
* cancelling bom creation gives "required total Qty. Per"
error [15827]
* error when processing a live credit card through
cybersource [16314]
* Un-expected behavior is observed on selecting a non-working
day as the schedule date for a sales order line item [16535]
* Loophole in priv apply AP credits [16685]
* DB log error is generated on selecting to print Time-Phased
Bookings screen [16719]
* Inventory Value Adjustment does not create an Inventory
History Record [16721]
* Due dates changes wipe characteristics [16739]
* Able to reserve qty. with no QOH [16770]
* Qty rounding issue [16853]
* WO Value not set properly [16939]
* Item Types filter not working [16990]
* Crm record clusters should only return "personal" results
when "all" privileges not granted [17030]
* Production Plan [17099]
* Ship-to Address Line not Visible in Customer Workbench
[17128]
* Backlog Report sorting [17134]
* 380 Installer - Mac Installer only works if run from desktop
[17169]
* 380 installer - Windows uninstaller should remove desktop
shortcuts [17180]
* two different source files create todoitemTrigger [17186]
* Selecting to save a new item displays irrelevant dialog
[17204]
* Sales Rep not defaulting on new customer [17208]
* Customer on Credit Hold locks new Sales Order [17217]
* QWebView widget not supported in scripting [17218]
* Scale in Costed BOM wrong [17234]
* Able to deactivate site in use... [17244]
* Irrelevant behavior is observed in Bill of Materials screen
[17248]
* Can't turn off companies, profit centers or subaccounts
after upgrading to V 3.8 [17288]
* Double clicking on an invoice in unposted invoices does
not open the item [17295]
* Freight weight is not functional on invoice [17297]
* Commission paid field on aropen window is not functional
[17308]
* Viewing Open Items from AP Aging, when using Distribution
Date, results in items not showing on the Open Payables
screen [17337]
* Selecting to add an Item substitution for an item
generates DB log error [17339]
* Filter By Sales Rep on Quotes screen throws SQL Error
[17373]
* Patch for wooper_detail [17378]
* Irrelevant dialog is displayed on selecting to convert
a quote created for a prospect [17381]
* Unable to edit a purchase order due date [17383]
* Edits needed on RA warning messages [17384]
* Observation:- Drop ship: Selecting to receive the purchase
order quantity doesn't ships the sales order [17387]
* Drop ship POs that result from converted quote in reverse
sequence [17391]
* Selecting to delete a sales order doesn't deletes the
Purchase Request linked to the sales order line item [17396]
* Selecting to print "Inventory Availability by Customer Type"
screen generates DB log error [17397]
* Selecting to Query the "Summarized Sales" screen generates
DB log error [17398]
* Revoking "Item is Sold" from item prevents open sales orders
for the item from appearing in Running Availability [17407]
* Distribution Date Changes [17408]
* Incorrect amount is displayed for un-posted invoices in
Open Receivables print report [17416]
* MaintainLicenseKey privilege missing in 3.8 postbooks to
standard upgrade script [17425]
* Selecting to upgrade Postbooks 380 Demo db to Standard
displays an error message [17460]
* Incorrect Default location is displayed in "Distribute
Stock To/From Site Locations" screen [17482]
* Observation: Inventory is not distributed automatically from
the default Stock location for a MLC enabled item [17483]
* It is possible to edit a cash receipt opened in view mode
[17507]
* postvoucher function needs to round number to 4 decimals
before testing value [17515]
* Work Order Schedule filter by Start Date and End Date [17519]
* Misc voucher - French-Bug [17537]
* DB log error is generated on selecting to create invoices
[17580]
* "Change Characteristic" dialog is displayed irrelevently
on selecting to save the SO line item opened in edit mode [17581]
* It is not possible to save a Sales Account Assignment in
PostBooks edition [17583]
* Linked Work Order is not created on selecting to save a
Return Authorization of type "Service" [17596]


----------------------------------
Release Notes
xTuple ERP
Version 4.0.0Alpha
March 30, 2012
----------------------------------

The following features and bug fixes have been added to the
applications since 3.8.0. Additional detail for each item listed below
may be found on our community website under the Issue Tracker.

New Features:

* Change Workspace mode to used tabbed MDI Area [16319]
* Update Unposted Invoices to use display class [16383]
* Posting Bank Adjustment [16571]
* Enhance Operation Buffer Status report [16602]
* Add Purchase-to-Job and automatic issue capability for purchased items [16604]
* Add Costing over-ride on the Bill of Materials [16605]
* Add job costing capability for child work orders [16606]
* Incidents should be enhanced to be filterable on Item and Lot/Serial numbers [16607]
* CRM Account and Contact should be added as standard associations for Project [16609]
* Add additional filters to Project List [16610]
* The assigned date should automatically populate on a Project or Project Task when the document is assigned [16611]
* The completed date should automatically populate on a Project or Project Task when the document status is changed to completed [16612]
* Project and Project Task should be modified to be able to keep track of date changes by whom and when [16613]
* A/R Credit Memo does not release number [11573]
* schema_path search [13211]
* Config option on license manager [15451]
* Add WEIGHTSCALE to format options [15851]
* Add costs and BOM data on the item master window [16315]
* Add the ability to copy Projects [16615]
* Add support for recursive lot tracing for items posted through Misc. Production Posting [16616]
* Make gltrans and sltrans share the same id sequence [17083]
* Make ship form not mandatory in the application [17085]
* Toggle of bankrecitem to uncleared should delete the bankrecitem [17086]
* Create additional transaction type default locations with automatic distribution [17112]
* Reimplement order sequence numbering to prevent number gaps and collisions [17119]


Bug Fixes:

* X-ing out of the application with new RA screen open creates orphaned entries. [8562]
* Posting authorized credit card does not process transaction [8864]
* Empty trialbal column header options confusing [9280]
* Summarized sales displays and reports skew averages incorrectly if misc credit memos have been posted [9458]
* It is possible to delete a Return leaving orphaned work orders [9866]
* PO#'s being skipped [11711]
* Existing line items not displayed while creating RA if manual numbering [12290]
* Transfer order contact change is not handled correctly when reopening transfer order [15900]
* Print report of Pricing Schedule Assignments displays incorrect details [16163]
* Observation: It is possible to create an invoice with no line items [16207]
* Incorrect behavior is observed on clicking "Yes" button in cancellation of a Role [16210]
* The definition of api.purchaseline is incorrect - duplicate PO Lines are returned because the view includes information from work order [16284]
* Financial report tool accepts bad data [16295]
* Selecting to delete a sales order doesn't delete the Purchase order linked to the Sales order line item sub component [16303]
* Blank tax code is created on cancelling the creation of a Tax code [16321]
* UI on detailed inventory history by Lot/Serial needs clean up [16394]
* Create Item Site Utility not functional with InterfaceToGL metric disabled [16409]
* Empty locale is created on selecting to cancel the creation of a new locale [16420]
* Expired Inventory print report doesn't honor the options selected [16458]
* Cost values are printed irrelevantly in the print report of Work Order history by Class code screen [16472]
* Irrelevant dialog is displayed on selecting to re-open Work Order History by Item screen [16473]
* Cancel button does not work in Production Plan window [16485]
* BOM [16498]
* Incorrect behavior is observed in Print Invoice screen when copies decreased to less than 1 [16500]
* Item Costs by Class Code [16513]
* Selecting to copy a sales order doesn't generate Purchase Request linked to the sales order line item [16533]
* Un-expected behavior is observed on selecting a non-working day as the schedule date for a sales order line item [16535]
* Pending availability [16556]
* Quote with scheduled date that is not a working day allows creation of line items on non-working days without warning [16561]
* itemcomment and itemsitecomment api views aren't accessible [16587]
* Pricing schedule of type "Freight" assigned to a Customer Ship-To is not functional [16681]
* Qty per on bom does not reflect locale [16696]
* "Deactivate" option is not available on right click of an Opportunity [16702]
* It is possible to save a Sales Order with blank Sales Order Number [16704]
* DB log error is generated on selecting to print Time-Phased Bookings screen [16719]
* AP aging report not showing correct amounts on aging columns [16724]
* QDir.homePath() script exposure returns JavaScript undefined [16735]
* Error message is displayed on scheduling 'Run MPS' using xtConnect [16746]
* Summarized BOM [16748]
*  It is possible to edit a Purchase Order even after revoking the necessary privileges [16762]
* Add date range filter to customer workbench, sales tab [16763]
* Able to reserve qty. with no QOH [16770]
* Return not reflected on Item Availability Workbench [16802]
* issueWoMaterialItem screen - unused component description2 field [16811]
* Faulty logic in Invoice Item [16824]
* Item Availability Workbench - Where-Used tab rounds qty-per values for non-fractional items [16840]
* As of Date on Customer Statement does not work [16875]
* Posted invoice entries are displayed under incorrect date in the Invoice Register screen [16882]
* It is possible to create a purchase order for an itemsite with no work week defined [16896]
* Lack of index on xtmfg.booitem results in severely degraded MRP performance [16919]
* Item privileges not implemented [16969]
* Item Types filter not working [16990]
* Count Tag Edit List only shows variance values for posted count slips [16994]
* Opportunities vs Customer [17010]
* Tax Registrations requires chart of accounts privilege [17027]
* When Creating New Contact, Default Owner Should be Creator [17032]
* Duplicate accounts utility shows project accounts when it shouldn't [17105]
* Selecting to create a New item crashes the application [17188]
* It is not possible to create WH1 site in Postbooks empty database [17192]