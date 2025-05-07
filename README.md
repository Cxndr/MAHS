# MAHS Auction House

### A full function all-in-one solution for managing and operating an auction house.

Built to prioritize intuitive user experience in a relatively complex tool, where most of the existing tools don't focus on user experience and become visually bloated and overwhelming due to the nature of the root complexity of the problem being solved.

Designing a solution for auction houses brings many additional complexities when compared to other commerce - having to manage both sides of transactions (buyers and vendors) as well as the unique business structures that auction houses use. Combining this with the relatively niche space auction houses take in the retail market leaves them with not many options for software solutions and those options largely being poorly designed. MAHS aims to address these concerns and provide an intuitive to use all-in-one solution for managing all aspects of an auction house business.

## Features
 - Manage lots for each auction. Inputting items in either a spreadsheet or form format.
 - Automatic spell checker.
 - Easy transfer of lots from one sale to another.
 - Fast search and filtering of lots.
 - Print consignments forms and sale reports for vendors, sale statements, invoices and porters copies for buyers.
 - Track both vendors and buyer information with regular id and bidding numbers.
 - Printable catalogue designed for legibility and use on the rostrum.
 - Export catalogue .csv files in formats for all major bidding platforms.
 - Enter sale results in intuitive interface as the auction is happening.
 - Automatically lot up sales according to pre-defined categories in user-chosen order.
 - Easily manage vendor and buyer payments: see who is still to pay and send batch email reminders.
 - View vendor/buyer history all from the customers main page.
 - Create custom invoices for buyers when changes need to be made.
 - Manage buyers and vendors email preferences in accordance with GDPR.
 - Export and print financial tax data and reports from any range of dates.
 - Fully customizable terms and conditions for buyers and vendors for all printed and emailed documents.
 - Set custom rates for buyers and vendors including percentage rates as well as per lot options.
 - Artist Royalty implementation to calculate and track payments needed.
 - Runs in an offline environment to accomodate remote locations where internet connections may not be stable.

## Requirements
 - Microsoft Access (either through MS Office or seperate license).
 - Windows operating system machines for server computer where data is hosted as well as all employee clients.

## Setup
1. Download this repo.
2. Set up a Windows _Mapped Network Drive_ at Y: called 'MAHS'.
3. Put the `MAHS_be.accdb` file inside the drive.
4. On all client machines create a copy of the `MAHS.accdb` file. _(generate an accde file if preffered)._
5. Run the `MAHS.accdb` on a client machine that has a network connection to the server machine.
6. Visit the `Settings` page to setup the information for your auction house, set the rates you are operating at, and create sale categories for lots.
7. Click `Manage Sales` at the top left to create your first sale.
