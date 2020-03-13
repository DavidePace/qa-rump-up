# Introduction
We will perform Acceptance and Functional test cases on the Assigned Devices list in Profile Entity page.

# Environment
Test enviroment is the xFi staging site. The system supports access from:
* Safari
* Chrome
* Firefox
* Microsoft Edge
* Microsoft Edge Chromium
* iOS
* Android

# Goals
The goal of the test is to verify that the connection status of devices is correclty shown in the
Assigned Devices lit in Profile Entity page. We want to assure that a message under each device is correclty
shown depending on his connection status: if connected, the message has to communicate it, if not the last connected time
has to be shown. We want to check if error situations are rightly reported in this message also.

# Tests
The main purpose of this test is to assure the acceptance of the device list. So, Acceptance test cases are wrote to check
if correct informations are shown in the message related to each device, changing the connection status.
We want to check if:
* connected device message is shown for every connected device.
* a message reporting last connected time is shown for every not connected device.
* an error message is shown if an error occurs
* an error is correctly logged and reported
* the appearence of the Assigend Devices list is correclty shown

We have also run Functional tests to verify the right behaviour of each function encountered.
We want to assure:
* the functionality of links related to Assigend Devices list

# Expected Results
For Acceptance tests we expect that (with respect to the goal list above):
* a message "Connected to Gateway" under a connected device is shown.
* a message with the last connected time is shown under a disconnected device. Messages could be:
  + "Last connected a minute ago"
  + "Last connected [x] minutes ago"
  + "Last connected an hour ago"
  + "Last connected [x] hours ago"
  + "Last connected [MM/DD]"
* a message "Can't determine last seen date" for a device that occurs to an error
* log an error event to Splunk and update our wikipage with error description
* the Assigend Devices list is correctly shown

For Functional tests we expect:
* the correct functionality on devices Card click.

Every test is performed manually.
