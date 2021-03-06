Release Notes
xTuple ERP
Version 4.0.0RC
November 26, 2012
----------------------------------

This is the official release candidate for version 4.0.0 of 
xTuple ERP. Thanks to all in the community who have made this 
release possible!

Information about compatibility issues related to this software
version can be found on the xTuple Compatibility Matrix at the
following address: www.xtuple.org/compatibility-matrix.

Here's an overview of notable new features in the 4.0.0 release:

Added tabs to desktop
  * Select Cascade or Tile from the Windows menu to convert the 
    tabbed view to a workspace view with multiple windows that 
    more closely resembles the previous workspace mode.

Enhanced Job Costing functionality
  * Purchase-to-Job
  * Automatic issue of Purchased Items to Work Orders
  * Job Costing for child Work Orders

Log in changes
  * SSL encryption now required for login, client option removed
  * Logins always try enhanced authentication first. If that 
    fails then the client tries to log in without enhanced 
    authentication.

Cost Plus Pricing

Multiple Project updates
  * Ability to copy Projects
  * And more ...

----------------------------------

The following bug fixes have been added to the applications since 
4.0.0Beta3. Additional detail for each item listed below may be 
found on our community website under the Issue Tracker.

Bug Fixes: 

* Net Due on Return Authorization does not match Amount in the Due 
Credit screen [10327]
* Purchase Returns don't record variance [11917]
* Average cost method calculation on Post Misc. Production for 
disassembly inconsistent [15403]
* Qty per on bom does not reflect locale [16696]
* Correct receiving for Control Method None item - no G/L 
transactions [17554]
* Post Misc. Production - affects component itemsite value but 
does not affect assembly itemsite value [17772]
* Correcting Postings [17856]
* Fix problem with Sales Type [18492]
* Incorrect behaviour is observed on selecting to return the 
purchase order [18038]
* Version problem with std400alphato400beta.gz upgrade script 
[18077]
* W/O gets created without saving [18154]
* Postbooks: Selecting to create a Count Slip for a count tag 
generates DB log error [18219]
* Transaction Report from financial report [18224]
* Upgrade std38xto400alpha.gz fails on 3.8.4 database [18292]
* Return Authorizations disappearing [18364]
* Inventory adjustment allowed for Job item via Misc Count tag 
[18449]
* Statement report mishandles currency [18483]
* Work Order Costing error [18489]
* Possible to purchase job items [18581]
* It is not possible to create a Transfer Order [18598]
* Create item sites utility not working [18605]
* Item Source Price screen - nominal and discount options should 
be different [18626]
* Bank reconciliation risk [18631]
* Need to add contract parameter to item source list [18663]
* Cannot issue stock to TO [18666]
* Work order variances not being generated [18681]
* Adjust Inventory Value Utility is not functional [18684]
* Unable to create Purchase orders [18685]
* Dogfood allows users to log in without a password [18739]
* Sales assignment screen is blank [18858]
* "Copy All""from FRE only returns first row [18900]

----------------------------------
Release Notes
xTuple ERP
Version 4.0.0Beta3
November 26, 2012
----------------------------------

The following features and bug fixes have been added to the
applications since 4.0.0Beta2. Additional detail for each item
listed below may be found on our community website under the
Issue Tracker.

PLEASE NOTE: Any testers with 4.0.0Alpha or 4.0.0Beta databases
may experience errors when upgrading to 4.0.0Beta2, due to an 
issue (#18078) with the upgrade scripts. If you encounter this
problem, the solution is to start fresh with a new instance of
your 4.0.0Alpha database--and then migrate that forward to
4.0.0Beta2. You should download a new version of the
pb400alphato400beta.gz or std400alphato400beta.gz upgrade script
before upgrading, as these files have been updated since the
official release date.

ALSO NOTE: If you are starting with a 3.8.2, 3.8.3, or 3.8.4
database, you may hit issue #18077. In this case, change the
"ServerVersion" metric to "3.8.0" in your database and try
upgrading again. If that doesn't work, try using the auxiliary
pre-upgrade package attached to issue #18077. This problem will 
be fixed in the upgrade packages from 3.8.x to 4.0.0RC and 
4.0.0(final). 

New Features:

* Recent button on login screen doesn't handle Enhanced Auth 
[10387]
* Time of Receiving Cost Override (Items Costed at Average) 
[12124]
* Brazilian states [16153]
* List of German states [16156]
* Remove backwards-compatibility views [16598]
* Enhance Operation Buffer Status report [16602]
* Misc. changes for Aurora support [17282]
* Make country force-populate states list in Address when 
available [17842]
* Event for New Customer Created [17981]
* Move issuetoshipping fillList query to MQL [18120]
* SSL encryption should be mandatory on the QT client [18236]
* Cost-Plus Pricing [18313]
* Add transaction created column to GL transactions display 
[18316]
* Purchase tax settings [18357]
* Add a postcomment overload that accepts a cmnttype_name [18372]
* Add Salesrep to filter in Customer List screen [18376]
* Item Source Enhancements [18387]

Bug Fixes: 
  
* RA item warehouse not consistent for disposition ship or credit 
[7639]
* Supplying Site Column in PO Quick Entry should be hidden in 
PostBooks [9287]
* Omnibus: Disallow records with duplicate or blank human readable 
key values [9302]
* Percent Variance not formated in financial report window [10968]
* New Voucher screen: _poitem widget refresh issues [11038]
* User is allowed to add a blank filter even after adding the 
available filters in "Incident workbench" screen [11155]
* Unable to "Export Contents" from Cash Registers screen [11230]
* Contact Widget resize problem on Mac [11667]
* Double-clicking radio button turns all radio buttons off and shows 
credit card xtreewidget [11955]
* Negative hours on Work Order [13471]
* xtree widget use wrong CR+LF [13589]
* Purge Shipping records is not functional [13840]
* Quick Entry PO Item searches don't work [14211]
* Selecting to close List currencies screen from voucher displays 
an irrelevant dialog [14927]
* Cannot void posted check with Multi-Currency [14956]
* Selecting to save an employee attached to an employee group 
displays an error message [15775]
* Incorrect behavior is observed on selecting to Save Quick Entries 
[15940]
* xtuple > preferences actually opens setup window on mac osx when 
using translation file [15945]
* Crash when creating Customer [16057]
* It is possible to create a ToDo item even after revoking 
"MaintainAllToDoItems" and "MaintainPersonalTodoItems" privilege 
[16225]
* Probability field resets to "0" in Opportunity screen [16421]
* Customer defaults are not honored when creating new customer 
[16635]
* Cannot open attached files with spaces in file name [16648]
* Documents are not editable from parent window opened in view mode 
[16732]
* As of Date on Customer Statement does not work [16875]
* Selecting to revoke all privileges of the "System" module 
generates an irrelevant error message [16906]
* Kit will not explode [17074]
* Nightly db backup missing [17220]
* Privilege problem with RA receipts [17236]
* Order Activity by Project - View Sales Order does not give focus 
to Sales Order screen [17291]
* Quantity mismatch in purchase order screen [17364]
* Unable to save Purchase Order Quick Entries [17366]
* Selecting to ship a billed sales order generates db log error 
[17382]
* Cumulative MPS results [17433]
* Correct receiving for Control Method None item - no G/L 
transactions [17554]
* "Close" button is not available in "fixCountries" screen [17595]
* List open return authorization report does not obey unauthorized 
checkbox [17625]
* Print Report of List Employees screen doesn't honor the filter 
selected [17634]
* "Select for Billing" option is checked by default even after 
revoking "SelectBilling" privilege for the user [17673]
* Uninformative dialog is displayed on selecting to create a new 
user with user name starting with numeric digits [17715]
* Observation: Selecting to apply A/P Credit memo with "Interface 
A/P to GL" option unchecked displays a system message [17717]
* Selecting to "Thaw" a Frozen Accounting Period generates db log 
error [17718]
* Sale Order linked Work Orders [17756]
* Postbooks Demo:Selecting to purge invoices generates DB log error 
[17779]
* Modify contact e-mail [17785]
* Start Date Error on Planned Orders [17830]
* View button on Financial Report window opens groups and accounts 
in Edit mode [17854]
* Correcting Postings [17856]
* Unused privilege [17950]
* It is possible to select the parent tax code as the tax 
calculation basis in the "Tax Code" screen [17953]
* SRI - entering credit note line items very slow [17988]
* List TO screen appear when selecting TO from Packing list [17994]
* Operator Precedence issue in C++ code [18015]
* Incorrect behaviour is observed on selecting to return the purchase 
order [18038]
* Create item site utility non functional with multiple sites 
disabled [18048]
* Cumulative and Forecast Reporting forecast do not display/calculate 
on MPS detail [18058]
* Over applying credit notes in A/P [18063]
* Selecting "Save" button does not closes the Production plan screen 
[18070]
* Received quantities not properly converted from PO UOM to SO UOM 
for dropship POs in the unpostedPOReceipts screen [18074]
* Cannot post voucher without maintain PO privilege [18076]
* Error in detail query source on Customer Statement report re: 
debit and credit memos [18079]
* Cannot voucher a PO when all items returned [18084]
* Ad Hoc WO BOO Create [18087]
* Selecting to Synchronize companies generates db log error [18096]
* Cost Cat Transform Clearing list should include expense accounts 
[18100]
* AP Voucher posting error [18101]
* PO not picking up vendor currency [18115]
* Selecting to cancel the Role displays "Save?" dialog irrelevantly 
[18118]
* Can't delete a Characteristic [18135]
* Making a contact inactive sometimes gives an error 
vendaddrinfo_vend_id does not exist [18138]
* Unable to delete a sales order line item [18143]
* W/O gets created without saving [18154]
* DB log error is generated on selecting to query Intended BOM 
screen [18166]
* AP Aging Fx issue [18167]
* Ship Order no longer calcs freight properly for partial shipments 
[18175]
* Selecting to "Modify" owners crashes the application [18179]
* Selecting to Query "Planned Order by Order Types"  generates DB 
log error [18188]
* Translations window cannot be closed on a Mac [18191]
* Db error saving invoice item [18194]
* Translation moves Preferences menu item on Mac OS [18196]
* Item Costs by Class Code screen showing inactive items [18201]
* Rounding Issue when quoting [18204]
* Order cluster do not show TO [18206]
* dspWoEffortByUser and ShopFloorWorkBench do not filter users 
[18209]
* Mac: Selecting to Clock-In a work order operation generates DB log 
error [18212]
* The Access Control utility should fix database object ownership 
[18215]
* Postbooks: Selecting to create a Count Slip for a count tag 
generates DB log error [18219]
* Observation: It is possible to do post production for a Work Order 
even after revoking the "PostProduction" privilege [18220]
* Fix ACL script doesn't fix packages. [18237]
* Postbooks Installer User Reg Email Permissions Flag Spelled Wrong 
[18250]
* ERROR:  more than one row returned by a subquery used as an 
expression CONTEXT [18251]
* itemPricingSchedule metasql does not apply locale to Discounted 
Price column [18252]
* Contact screen is wonky in 4.0.0beta2 [18264]
* XML import fails on alternate_rev_account [18275]
* Project view is not right [18277]
* RA receiving issue [18282]
* Deprecated functions in misc xTuple scripts need to be fixed 
[18284]
* Remove Project from login screen [18285]
* FRE always starts display completely rolled up [18287]
* have user privileges/xtDesktop comment console update immediately 
upon change [18293]
* Irrelevant dialog is displayed on selecting to "Save" a sales 
order line item opened in edit mode [18310]
* Tab order incorrect [18312]
* Shuffling between Misc. Item and regular item generates DB log 
error in "Invoice Item" screen [18317]
* Contacts e-mail adresses are getting deleted and not sticking in 
the application [18331]
* Contact screen is taking too long to load [18340]
* salesOrder.cpp only emits populated() on the quote side & adding 
a signal for when the xtreewidget is filled [18343]
* Db error making contact inactive [18358]
* Shipping order after invoice prepared causes coitem trigger to 
fail [18365]
* Drop ship PO receipt - issue to shipping and shipment transactions 
don't post on received date [18380]
* Cancel Item not working as expected [18383]
* Version upgrade [18438]
* formatabachecks function does not write out amounts over 6 digits 
file spec allows up to 10 digits [18439]
* Backflush materials & operations checkboxes in Post Miscellaneous 
Production not memorized [18567]
* DB log error is generated on selecting to create New Financial 
Report [18570]
* It is not possible to create a new Tax Code [18572]
* Selecting to Ship the sales order generates DB log error [18573]

----------------------------------
Release Notes
xTuple ERP
Version 4.0.0Beta2
August 10, 2012
----------------------------------

The following features and bug fixes have been added to the
applications since 4.0.0Beta. Additional detail for each item
listed below may be found on our community website under the
Issue Tracker

New Features:

* Brazilian states [16153]
* List of German states [16156]
* 380 installer - signal to user that pg install takes time 
[17174]
* 380 installer - deal with legacy postgres installs [17173]
* remove deprecated methods from the script toolbox [16599]
* Move issuetoshipping fillList query to MQL [18120]
* Add Parameter Widget to Employee List [18011]
* 380 installer - move Windows uninstaller warning [17177]
* "Add ability for client to be able to dynamically download 
translation, help, spell check files for languages" [15076]

Bug Fixes:			
				
* Customer defaults are not honored when creating new customer 
[16635]
* Probability field resets to '0' in Opportunity screen [16421]
* Print Packing List Issue [16672]
* Typo in pohead field [17018]
* 380 Installer - Mac Installer only works if run from desktop 
[17169]
* Selecting 'Print Statement by Customer' displays irrelevant 
dialog [17299]
* "Silent error on editing ""sticky"" preferences" [17429]
* Miscellaneous Invoice does not save Ship To [17567]
* Orphan values left in coitem_order_id after associated work 
order deleted [17601]
* Standard Edition: Irrelevant dialog is displayed on selecting 
to create a work order [17609]
* Item Sources selection window is displayed irrelevantly on 
selecting to create a PO for items with inactive item sources 
[17621]
* Observation: 'Issue Work Order Material Item' screen doesn't 
get refreshed on issuing the materials to the selected work order 
[17635]
* Irrelevant dialog is displayed on selecting to edit the 
characteristic value of a sales order item [17650]
* Selecting to print a Credit Memo generates DB log error 
[17667]
* "*Voucher Reject - Correct Receipt, Incorrect Item" [17682]
* Selecting 'Copy P/O' generates DB log error in 'Purchase 
Order History' Screen [17696]
*  Observation: CRM account is not selected by default on 
selecting to create a new Project from the Activities tab [17708]
* Observation: Selecting to post a cash receipt displays a system 
message [17719]
* Changing Manufactured to Tooling Give an Error [17758]
* Postbooks Demo:Selecting to purge invoices generates DB log 
error [17779]
* NULLs in string concatenations degrading searching [17802]
* Comment Types setup does not enforce MaintainCommentTypes 
privilege [17848]
* System calculates customer discount percentage incorrectly 
after selling UOM changed [17928]
* Item type list not sorting consistently [17968]
* Selecting to migrate xTuple 4.0.0 Beta master db to 4.0.0 Beta2 
displays an error message [18071]
* itemcharprice function runs unnecessarily [17956]
* deleting a sale does not ask the user for confirmation [17895]
* Check Formats setup does not enforce MaintainCheckFormats 
privilege [17847]
* Standard Labor Rates are not available for selection in Work 
Center screen [17799]
* Print Journal option missing from Unposted Invoices [17776]
* Sale Order linked Work Orders [17756]
* selecting to 'Thaw' a Frozen Accounting Period generates db log 
error [17718]
*  DB log error is generated on selecting to cancel the sales 
order creation [17704]
* Observation: Unable to close work orders of Job costing item 
[17695]
* DB log error is generated on selecting 'Preview' button in 
Purchase Orders by Vendor screen [17678]
* DB log error is generated on selecting to search for an Item in 
'Search for Item' screen [17658]
* Selecting Edit list in the Unit of Measure screen generates DB 
log error [17647]
* Footer query in Cash Receipts report doubles about because of 
customer groups [17628]
* Item Sources selection window is displayed irrelevantly on 
selecting to create a SO for an item with inactive item sources 
[17620]
* Missing column qualifier in _empbeforetrigger() causes employee 
import to fail [17606]
* It is possible to create a Service type Return Authorization 
for a Non Job-Costing items [17594]
* whseCalendars script in xtmfg uses wrong priv [17561]
* Selecting to save purchase order item generates db log error 
[17376]
* 380 installer - Windows uninstaller should remove desktop 
shortcuts [17180]
* Omnibus: 'Change date' dialog is displayed irrelevantly on 
selecting to open a Work order [16683]
* double-clicking radio button turns all radio buttons off and 
shows credit card xtreewidget [11955]
* page_count:Context Query doesn't return any value [16985]
* Omnibus:Some screens are not opened in tabbed window mode [17344]
* GL/Report/Series bug [17535]
* Itemsite is not displayed in the sales order line item screen 
[17582]
* Extended Commissions not created on line items when a quote is 
converted to a sales order or invoice [17603]
* Vendor History Privilege Issue [17612]
* Selecting to Synchronize companies generates db log error [17622]
* Observation: It is possible to create credit card from cash 
receipt screen opened in view mode [17636]
* Selecting to print a Purchase Order generates DB log error 
[17656]
* 'Select for Billing' option is checked by default even after 
revoking 'SelectBilling' privilege for the user [17673]
* Duplicate item sources [17683]
* POs for Non-Inventory items are not displayed in the Purchase 
Order Delivery Date Variances by Vendor Screen [17697]
* Work Order Operations by Work Center print report displays the 
closed work order operations [17714]
* Incorrect behaviour is observed on selecting to Un-Check 'Use 
Subaccounts' check box in Accounting setup [17721]
* Postbooks Demo: 'Enable EFT check Printing' option is not 
available in the Accounting setup [17760]
* Display GL Series doesn't work [17787]
* Inventory Availability By Sales Order [17803]
* PO number and Order Date are blank on grade 0 PO [17850]
* Expiring BOM items can result in duplicate sequence numbers 
[17935]
* Incorrect behaviour is observed on selecting to return the 
purchase order [18038]
* Observation: Unit Cost and Inventory Values are updated 
relatively on posting an adjustment absolutely for an average cost 
item [17973]
*  Observation: Tax History screen doesn't display the 'Doc#' for 
A/R Misc.Credit Memo [17948]
* View button on Financial Report window opens groups and accounts 
in Edit mode [17854]
* Printing incorrect information [17832]
* Selecting to update Actual Costs by class code displays a system 
message [17788]
* Project summary shows textlabel if no values have been entered 
[17761]
* Irrelevant behavior is observed on selecting to change the 
budget value from Maintain Budget screen opened in view mode 
[17722]
* Observation:Selecting to post/void a voucher with 'Interface 
A/P to GL' option unchecked generates a DB log error [17716]
* Bill of Operations Items screen is displayed blank on selecting 
to create a new Work Order Material Requirement [17698]
* DB log error is generated on selecting to query Intended BOM 
screen [17694]
* deicimal precision in qty per for sequenced Bom [17674]
* Planned Orders screen doesn't honor the 'Order Types' filter 
selected [17657]
* Type error on text [17638]
* Selecting to create a new Bank Adjustment displays a system 
error message [17624]
* Inconsistent work week calendar issue [17618]
* Work Order Schedule from Running availability screen is 
displaying all work orders [17604]
* Selecting to save the Tax Authority crashes the application 
[17584]
* Correct receiving for Control Method None item - no G/L 
transactions [17554]
* Observation: It is possible to add/edit a Bill of materials 
item from the item screen opened in view mode [17367]
* Inventory history default dates when accessed via inventory 
availability [17090]
* Cannot view Expense Category in Inventory History [17122]
* Summary on Customer Workbench [16908]
* SO Pick List prints packing list [15224]
* Posting Voucher With PO Line Freight Amount On Vchr Line: 
Wrong Account [6616]
* Messages sent with Social Desktop are not received immediately 
[18159]

----------------------------------
Release Notes
xTuple ERP
Version 4.0.0Beta
May 17, 2012
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
