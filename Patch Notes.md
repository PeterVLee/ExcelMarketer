## 1.2.0
* Big CSV importing improvement! No more manually fiddling around with csv copy and pasting!
  * Imports CSV files relative to the current sheet's path
  * Added a button to automatically refresh the SDE, works as long as the user has invTypes.csv in the same folder as the sheet
  * Updated instruction tab to reflect this change
* Fixed skills to allow level 0
* Minor formatting changes

## 1.1.1
* Fixed data validation for Accounting skill dropdown
* Added note to search cell for better hint
* Experimenting with locked sheets to make it harder for the user to break stuff. It's not password locked though so people can experiment if they want
* Temporary section for custom, simulated margin stats box. Math is bad but it gets the job done for now. Might steal UI ideas from other websites that do it better
* Added volume stat. Brightened editable cells to make it more obvious
* Changed standing coloring and number format

## 1.1.0
* UI Overhaul
  * Proper dark mode, borders to imitate evemarketer as much as possible
  * Taking out the scrollbar for now because it's a nightmare to work with

## 1.0.2
* Error handling for empty cells
* Improved look of main tab to more closely match in-game regional market
  * Search cell now has placeholder text to make it more intuitive
  * Replaced text with Roboto, same one used in EVEMarketer
  * Broke the scroll because I had to adjust the offset sizes. Planning on fixing this with the active-x scroll bar which will let me set the max to # of orders

## 1.0.1
* Fixed the region for dodixie in formatting tab
* Expanded size of offset cells to show 15 orders in the view instead of 10
* Notes to named ranges
* Fee + sales tax, margin calculator
