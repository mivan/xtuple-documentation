Release Notes
xTuple Applications
OpenMFG - PostBooks
Version 2.3.0Alpha1
November 2, 2007
----------------------------------

This is the first Alpha release of version 2.3.0. We are especially
interested in feedback from alpha testers on the following new areas
of functionality:

UOM Enhancements
- Extensive changes to normalize Unit of Measure handling/conversions
- New Selling UOM
- New UOM for Bill of Materials
- See issue #4963 in our xTuple.org issue tracker for a detailed spec

BOM/BOO Revisions
- Encompases Part III of Return Material Authorization (RMA) effort
- New Bill of Materials/Operations revision-tracking
- See issue #5771 for a detailed spec

Return Authorizations (Preview)
- Initial preview of Return Authorizations functionality
- Encompasses Part I of RMA effort
- See issue #4832 for a detailed spec

XML Data Import (Preview)
- Initial preview of XML import utility
- Uses XSLT mapping to transform XML for import into xTuple databases
- See issue #5886 for more information

Added UI configuration memory to
- Grid layouts
- Window Size/Position
- Checkboxes when enabled and where applicable

(NOTE: Checkboxes that remember their state are being temporarily 
indicated by a small '?' symbol when checkbox memory is enabled in 
user preferences. We would like additional feedback on windows where 
this behavior should/shouldn't be included.)
	
----------------------------------

The following features and bug fixes have been added to the applications 
since the release of version 2.2.1:

New Features:

* [System] Memory for checkboxes
* [System] Hide menus that are disabled
* [A/P] GUI Memory
* [A/P] Can A/P (or A/R) 'As-Of' Reports be created?
* [A/R] Need open balance snapshot capability
* [CRM] Characteristics Template 
* [CRM] Add ability to search both List CRM Accounts and List Contacts
* [G/L] Add Journal Entry to api schema 
* [P/D] BOM uses Inventory UOM rather than Capacity UOM 
* [P/O] P/R by Planner Code Default Dates
* [S/O] Copy billing address to credit card
* [W/O] Submit button on dspWoOperationBufrStsByWorkCenter 

Bug Fixes:

* [All] CPU usage higher than expected
* [All] Minimize/Maximize window lost of displayed info
* [Inventory] cannot ship with only ship order privilege
* [Inventory] Qty at Shipping is not correct after recalling orders
* [Inventory] Can't Apply Maximum Desired Cost Over $999.00
* [Inventory] Qty field strangely oversized on Inv. Adjustment window 
on Mac.
* [Inventory] Message popped up on issue stock to shipping screen
* [I/M] TO - Unable to Edit TO Head Comment
* [Manufacture] Cut off date field scrunched up on Mac on Release W/O 
by Planner Code window
* [P/O] Contact w/no name gives error
* [Sales] tax override at sales order item entry does not carry through 
to invoicing
* [Sales] Can not remove work order from sales order
* [Sales] Changed Customer Layout
* [Sales] Provide a way to enable the promise date capability in SO
* [System] setting the neo menus, and show menus/toolbars
* [System] Change SoCommentsChanged Event to SoOrderNotesChanged Event
* [System] Saving in Product Configuration turns on Routings in PostBooks