# Add your Test Cases for XFIWEB-2156 here

| 00000 - Verify the correct message shown under a connected device |
|Step number | Step Type | Description|
|1           | Normal    | login to xFi using valid credentials on an account which has at least one Profile with at least one device assigned and connected|
|2           | Normal    | click on "People" tab to open the "People" page|
|3           | Normal    | click on a profile card with at least one device connected to open the corresponding "Profile" page|
|4           | Validate  | is the message under connected devices name in the "Assigned Devices" list set to "Connected to Gateway"?|



| 00001 - Verify the correct message shown under a disconnected device that last connected time was less than 1 minute|
|Step number | Step Type | Description|
|1           | Normal    | login to xFi using valid credentials on an account which has at least one Profile with at least one device assigned and disconnected for less than 1 minute|
|2           | Normal    | click on "People" tab to open the "People" page|
|3           | Normal    | click on a profile card with at least one device disconnected to open the corresponding "Profile" page|
|4           | Validate  | is the message under the name of devices, in the "Assigned Devices", disconnected for less than a minute set to "Last connected a minute ago"?|



| 00002 - Verify the correct message shown under a disconnected device that last connected time was more than 1 minute but less than an hour |
|Step number | Step Type | Description|
|1           | Normal    | login to xFi using valid credentials on an account which has at least one Profile with at least one device assigned and disconnected for more than 1 minute and less than an hour|
|2           | Normal    | click on "People" tab to open the "People" page|
|3           | Normal    | click on a profile card with at least one device disconnected to open the corresponding "Profile" page|
|4           | Validate  | is the message under the name of devices, in the "Assigned Devices", disconnected for more than a minute but less then an hour set to "Last connected [x] minutes ago"?|



| 00003 - Verify the correct message shown under a disconnected device that last connected time was more than 1 hour but less than 24 hours |
|Step number | Step Type | Description|
|1           | Normal    | login to xFi using valid credentials on an account which has at least one Profile with at least one device assigned and disconnected for more than 1 hour and less 24 hours|
|2           | Normal    | click on "People" tab to open the "People" page|
|3           | Normal    | click on a profile card with at least one device disconnected to open the corresponding "Profile" page|
|4           | Validate  | is the message under the name of devices, in the "Assigned Devices", disconnected for more than 1 hour but less then 24 hours set to "Last connected [x] hours ago"?|



| 00004 - Verify the correct message shown under a disconnected device that last connected time was 1 hour ago |
|Step number | Step Type | Description|
|1           | Normal    | login to xFi using valid credentials on an account which has at least one Profile with at least one device assigned and disconnected 1 hour ago|
|2           | Normal    | click on "People" tab to open the "People" page|
|3           | Normal    | click on a profile card with at least one device disconnected to open the corresponding "Profile" page|
|4           | Validate  | is the message under the name of devices, in the "Assigned Devices", disconnected for 1 hour set to "Last connected an hour ago"?|



| 00005 - Verify the correct message shown under a disconnected device that last connected time was more than 24 hours ago |
|Step number | Step Type | Description|
|1           | Normal    | login to xFi using valid credentials on an account which has at least one Profile with at least one device assigned and disconnected for more than 24 hours|
|2           | Normal    | click on "People" tab to open the "People" page|
|3           | Normal    | click on a profile card with at least one device disconnected to open the corresponding "Profile" page|
|4           | Validate  | is the message under the name of devices, in the "Assigned Devices", disconnected for more than 24 hours set to "Last connected [MM/DD]"?|



| 00006 - Verify the correct message shown under a disconnected device that occurs in an error|
|Step number | Step Type | Description|
|1           | Normal    | login to xFi using valid credentials on an account which has at least one Profile with at least one device assigned and disconnected for more than 24 hours and that occurs in an error and ORC returns a undefined/null|
|2           | Normal    | click on "People" tab to open the "People" page|
|3           | Normal    | click on a profile card with at least one device disconnected to open the corresponding "Profile" page|
|4           | Validate  | is the message under the name of devices, in the "Assigned Devices", disconnected for more than 24 hours which occurs to an error set to "Can't determine last seen date"?|



| 00007 - Test the functionality of "Assign Devices" list cards |
|Step number | Step Type | Description|
|1           | Normal    | login to xFi using valid credentials on an account which has at least one Profile with at least one device assigned|
|2           | Normal    | click on "People" tab to open the "People" page|
|3           | Normal    | click on a profile card to open the corresponding "Profile" page|
|4           | Validate  | is the Device Entity page opened?|



| 00008 - Verify the correct list sorting on devices |
|Step number | Step Type | Description|
|1           | Normal    | login to xFi using valid credentials on an account which has at least one Profile with at least one device assigned and device sorting sorting is set on "Last seen"|
|2           | Normal    | click on "People" tab to open the "People" page|
|3           | Normal    | click on a profile card to open the corresponding "Profile" page|
|4           | Validate  | are devices with "Can't determine last seen date" message in the last positions of the list?|

