
#XFIWEB-2096 TEST PLAN

The following test cases refer to ticket XFIWEB-2096

##Units tested 
The main unit to be tested is the Gear icon in the Profile page. Some tests will be applied to the 
Settings page according to the ticket specification. Specifically, UI tests will focus on the 
new Settings page carousel that is going to be shown in the Settings page after the "New Settings Page" modal is removed as specified in the ticket. Some secondary tests will eventually be done on the Settings page.
Acceptance, Functional and UI tests are going to be performed on the Gear icon and on the "New Settings Page"
Carousel. Some Acceptance tests will be done on the Settings page. 

##Goal
Clicking on the Gear icon used to open a modal. This is no longer true, and we want to show the user that a new Settings page has been created. The Gear Icon now has to show a "new" label over it. Since the Settings 
page is a new page, we need to show the User a Carousel which is displayed in full page.

##Environment
As the ticket only concernes the browser version of the website, the Environments in which the tests have to be executed will be Safari, Chrome, Microsoft Edge and Firefox.

##Expected Results
-Acceptance tests: we need to make sure that the new icon is visible on the Gear button, but only until the User's first access on the Settings Page.
-UI tests: we need to make sure that a New Settings Page Carousel is displayed in the settings page. 
-Functional: we need to check that the Gear icon redirects the User to the Settings page. We then need to check the functionality of the buttons on the New Settings Page Carousel.


##Tests

The following tests are prioritary and will be executed in the following order.

- Verify the New badge is shown over the Gear icon
- Verify the Gear button functionality
- Verify the full page Carousel is shown at first Settings Page access  
- Verify the X button is shown on the top right corner of the New Settings Page Carousel 
- Verify the Carousel Indicators are shown at the bottom of the New Settings Page Carousel 
- Verify the Next button is visible in the New Settings Page Carousel 
- Verify the Next button functionality in the New Settings Page Carousel 
- Verify the Carousel Indicators functionality in the New Settings Page Carousel 
- Verify the X button functionality in the New Settings Page Carousel 
- Verify the New badge is not shown after the Settings Page is visited
- Verify the New Settings Page full page Carousel is not shown if Settings Page is accessed twice  
- Verify the New badge is not shown after the Settings Page is visited
- Verify the Settings Moved modal is not shown after an User's first access on the Settings page 
- Verify the New badge is shown over the Gear icon on the French website

The following tests are of secondary importance, If we decide to execute them, they have to be executed in the
following order.

- Verify the Settings Page title is correctly displayed|
- Verify that buttons are correctly displayed under the Activity Settings card 
- Verify that buttons are correctly displayed in the Profile Settings card 
- Verify that buttons are correctly displayed in the Downtime card if Downtime schedules exist 
- Verify the Create a Downtime Schedule button is displayed if the profile has no Downtime Schedule 
- Verify the Active Time Limit button is displayed if Active Time Limits exist 
- Verify the Get Started button link is visible in the Create a Downtime Schedule button  
- Verify the Get Started button link is visible in the Set up an Active Time Limit button  
- Verify the Get Started button link is not visible in Downtime buttons if a Downtime is set  
- Verify the Get Started button link is not visible in Active Time Limit buttons if an Active Time Limit is set  
- Verify the Active Time Limit button height is increased if Active Time Limits exist 
- Verify the Weekdays label is visible if an Active Time Limit is set on Weekdays 
- Verify the Weekends label is visible if an Active Time Limit is set on Weekends
- Verify two Active Time Limit buttons are shown if Active Time Limits exist on both Weekends and Weekdays 
- Verify weekdays labels are shown for the selected days in each Downtime button 
- Verify the Settings Page title is correctly translated to Spanish
- Verify the Settings Page title is correctly translated to French
- Verify that buttons are correctly displayed in the Activity Settings card in the French website

The specifics of all activities are defined on the test-cases-xfiweb-2096.md file.