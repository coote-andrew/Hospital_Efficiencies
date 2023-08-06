# Hospital_Efficiencies
using apple shortcuts to record information pertinent to being a junior doctor

# Projects
1. Record automatically when I arrive and leave the hospital - useful for timesheets
2. Quickly record events for my CV

These methods take advantage of google scripts - which allow information to be saved to a google sheets document by API. For the un-initiated, what we are trying to do is find a quick and easy way to send informaiton via URL. The format will be https://script.google.com/macros/s/longcompicatedlettersandnumbershere?name1=information1&name2=information2&name3=information3 etc.

This information is then accepted and "parsed" (understood) by the script and then added to the end of the google sheets document.

All we have to do is set up the information above and set up an apple shortcut that sends the correct information

## Recording arrival/leaving times
1. Set up your google sheets document
   * Create a new Google sheets document
   * name the columns as you'd like: I have datetime AND entering/leaving. (I use 1 for entering, 0 for leaving)
