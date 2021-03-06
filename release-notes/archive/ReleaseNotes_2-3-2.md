Release Notes
xTuple ERP
PostBooks-Standard-OpenMFG
Version 2.3.2
April 7, 2008


This is a bug fix release, correcting problems found in 2.3.1. Many 
thanks to everyone in our growing user community who contributed
valuable feedback to make this release possible.

NOTE: A complete list of report definition changes can be found
in the file reports231to232.txt.


----------------------------------

The following bug fixes have been incorporated since the release of 
version 2.3.1:


Bug Fixes:

* [All] Fixed issue where Inventory transactions were not posting to 
the Trial Balance 
* [A/P] Fixed issue where Vouchers weren't being properly reopened after 
voiding Checks
* [A/P] Fixed issue where Voucher Item freight was not being processed 
properly
* [A/P] Moved to hide Credit Card options at Cash Receipt if system is 
not configured to use Credit Cards
* [A/P] Fixed Mac-only issue where when printing Checks the first Check 
printed to the selected printer, but subsequent Checks printed to the
default printer
* [A/P] Improved performance of Check printing on Mac
* [A/R] Fixed issue leading to error message when processing Credit 
Cards at Sales Order entry
* [A/R] Fixed loophole where Deposit Register was capable of showing 
duplicate entries
* [Accounting] Fixed issue where closing the Cash Receipt screen using 
the "X" option behaved differently than CANCEL, creating orphaned AR 
records
* [Accounting] Fixed error received when splitting Vouchers
* [Accounting] Improved performance of AR Aging Report
* [Batch Manager] Fixed issue with Addresses printing improperly when 
sending print jobs through the Batch Manager
* [Inventory] Fixed issue where information was not being saved on Item 
Site tab areas
* [Inventory] Fixed error encountered when receiving Transfer Orders
* [Inventory] Fixed issue where multiple users were being prevented from 
shipping simultaneously due to lot/serial locks in the database
* [Inventory] Fixed issue preventing receipt of partial Transfer Order 
quantities
* [Inventory] Fixed issue where non-netable quantity was not being 
calculated properly when Count Tag/Slip created for an individual 
Location
* [Inventory] Fixed several screens where �Automatically Update� option 
was not working correctly
* [Inventory] Fixed issue with Count Tags not freezing properly
* [Manufacture] Fixed issue where run was not being marked complete 
after all Operations quantity had been posted
* [Manufacture] Fixed issue where notes added when posting production 
for serially-tracked Items led to unbalanced QOH
* [Products] Fixed issue where the Bill of Materials Item screen was 
closing when attempting to save a new BOM Item without entering the 
quantity
* [Products] Fixed "Running" tab in Item Availability Workbench to 
correctly recognize UOM conversions
* [Products] Improved performance of cost updates and cost posting
* [Purchase] Fixed issue leading to error when correcting receiving
* [Reports] Fixed image scaling problems on Mac
* [S/O] Ensured that Sales Order notes are transferred to the 
corresponding Invoice
* [S/O] Fixed loophole where Shipping charges were not being updated 
properly if changed on the original Sales Order
* [Sales] fixed issue where Credit Memos were not posting to the 
cohist table correctly, causing incorrect sales analysis values
* [Sales] Fixed printing on Backlog By Customer report
* [Sales] Fixed issue where incorrect values displaying on Sales Order 
Item Pending Availability display when "Show Pending Availability as 
Indented BOM" option was not checked
* [Sales] Fix Summarized Backlog report to work with Customer Types, 
and faster
* [System] Updated application title bar to show "xTuple ERP"


**NOTE: The help files have not been updated for this release
