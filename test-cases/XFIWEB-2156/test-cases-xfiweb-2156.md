# Add your Test Cases for XFIWEB-2156 here

| 00000 - Verify the correct Connection Status copy shown under a connected device |

|Step number | Step Type | Description|

|1           | Normal    | login to xFi using valid credentials on an account which has at least one Profile with at least one device assigned and connected|

|2           | Normal    | click on People tab to open the People page|

|3           | Normal    | click on a profile card with at least one device connected to open the corresponding Profile Entity page|

|4           | Validate  | is the Connection Status copy under connected devices name in the Assigned Devices list set to "Connected to Gateway"?|




| 00001 - Verify the correct Connection Status copy shown under a disconnected device that last connected time was less than 1 minute|

|Step number | Step Type | Description|

|1           | Normal    | login to xFi using valid credentials on an account which has at least one Profile with at least one device assigned and disconnected for less than a minute|

|2           | Normal    | click on People tab to open the People page|

|3           | Normal    | click on a profile card with at least one device disconnected to open the corresponding Profile Entity page|

|4           | Validate  | is the Connection Status copy under the name of devices, in the Assigned Devices, disconnected for less than a minute set to "Last connected a minute ago"?|



| 00002 - Verify the correct Connection Status copy shown under a disconnected device that last connected time was more than a minute but less than an hour |

|Step number | Step Type | Description|

|1           | Normal    | login to xFi using valid credentials on an account which has at least one Profile with at least one device assigned and disconnected for more than a minute and less than an hour|

|2           | Normal    | click on People tab to open the People page|

|3           | Normal    | click on a profile card with at least one device disconnected to open the corresponding Profile Entity page|

|4           | Validate  | is the Connection Status copy under the name of devices, in the Assigned Devices, disconnected for more than a minute but less then an hour set to "Last connected [x] minutes ago"?|




| 00003 - Verify the correct Connection Status  copy shown under a disconnected device that last connected time was more than an hour but less than 24 hours |

|Step number | Step Type | Description|

|1           | Normal    | login to xFi using valid credentials on an account which has at least one Profile with at least one device assigned and disconnected for more than an hour and less 24 hours|

|2           | Normal    | click on "People" tab to open the "People" page|

|3           | Normal    | click on a profile card with at least one device disconnected to open the corresponding Profile Entity page|

|4           | Validate  | is the Connection Status copy under the name of devices, in the Assigned Devices, disconnected for more than an hour but less then 24 hours set to "Last connected [x] hours ago"?|



| 00004 - Verify the correct Connection Status copy shown under a disconnected device that last connected time was an hour ago |

|Step number | Step Type | Description|

|1           | Normal    | login to xFi using valid credentials on an account which has at least one Profile with at least one device assigned and disconnected an hour ago|

|2           | Normal    | click on People tab to open the People page|

|3           | Normal    | click on a profile card with at least one device disconnected to open the corresponding Profile Entity page|

|4           | Validate  | is the Connection Status copy under the name of devices, in the Assigned Devices, disconnected for 1 hour set to "Last connected an hour ago"?|



| 00005 - Verify the correct Connection Status copy shown under a disconnected device that last connected time was more than 24 hours ago |

|Step number | Step Type | Description|

|1           | Normal    | login to xFi using valid credentials on an account which has at least one Profile with at least one device assigned and disconnected for more than 24 hours|

|2           | Normal    | click on People tab to open the People page|

|3           | Normal    | click on a profile card with at least one device disconnected to open the corresponding Profile Entity page|

|4           | Validate  | is the Connection Status copy under the name of devices, in the Assigned Devices, disconnected for more than 24 hours set to "Last connected [MM/DD]"?|



| 00006 - Verify the correct Connection Status copy shown under a disconnected device that occurs in an error|

|Step number | Step Type | Description|

|1           | Normal    | login to xFi using valid credentials on an account which has at least one Profile with at least one device assigned and disconnected for more than 24 hours and that occurs in an error and ORC returns a undefined/null|

|2           | Normal    | click on People tab to open the People page|

|3           | Normal    | click on a profile card with at least one device disconnected to open the corresponding Profile Entity page|

|4           | Validate  | is the Connection Status copy under the name of devices, in the Assigned Devices, disconnected for more than 24 hours which occurs to an error set to "Can't determine last seen date"?|




| 00007 - Test the functionality of Assign Devices list cards |

|Step number | Step Type | Description|

|1           | Normal    | login to xFi using valid credentials on an account which has at least one Profile with at least one device assigned|

|2           | Normal    | click on "People" tab to open the People page|

|3           | Normal    | click on a profile card to open the corresponding Profile Entity page|

|4           | Validate  | is the Device Entity page opened?|



| 00008 - Verify the correct list sorting on devices |

|Step number | Step Type | Description|

|1           | Normal    | login to xFi using valid credentials on an account which has at least one Profile with at least one device assigned and device sorting is set on "Last seen"|

|2           | Normal    | click on People tab to open the People page|

|3           | Normal    | click on a profile card to open the corresponding Profile Entity page|

|4           | Validate  | are devices with "Can't determine last seen date" Connection Status copy in the last positions of the list?|

| 00009 - Verify the correct Connection Status copy shown under a connected device in IgniteWiFi site|

|Step number | Step Type | Description|

|1           | Normal    | login to IgniteWiFi using valid credentials on an account which has at least one Profile with at least one device assigned and connected|

|2           | Normal    | click on People tab to open the People page|

|3           | Normal    | click on a profile card with at least one device connected to open the corresponding Profile Entity page|

|4           | Validate  | is the Connection Status copy under connected devices name in the Assigned Devices list set to "Connected to Gateway"?|




| 00010 - Verify the correct Connection Status copy shown under a disconnected device that last connected time was less than 1 minute  in IgniteWiFi site|

|Step number | Step Type | Description|

|1           | Normal    | login to IgniteWiFi using valid credentials on an account which has at least one Profile with at least one device assigned and disconnected for less than a minute|

|2           | Normal    | click on People tab to open the People page|

|3           | Normal    | click on a profile card with at least one device disconnected to open the corresponding Profile Entity page|

|4           | Validate  | is the Connection Status copy under the name of devices, in the Assigned Devices, disconnected for less than a minute set to "Last connected a minute ago"?|



| 00011 - Verify the correct Connection Status copy shown under a disconnected device that last connected time was more than a minute but less than an hour  in IgniteWiFi site|

|Step number | Step Type | Description|

|1           | Normal    | login to IgniteWiFi using valid credentials on an account which has at least one Profile with at least one device assigned and disconnected for more than a minute and less than an hour|

|2           | Normal    | click on People tab to open the People page|

|3           | Normal    | click on a profile card with at least one device disconnected to open the corresponding Profile Entity page|

|4           | Validate  | is the Connection Status copy under the name of devices, in the Assigned Devices, disconnected for more than a minute but less then an hour set to "Last connected [x] minutes ago"?|




| 00012 - Verify the correct Connection Status  copy shown under a disconnected device that last connected time was more than an hour but less than 24 hours  in IgniteWiFi site|

|Step number | Step Type | Description|

|1           | Normal    | login to IgniteWiFi using valid credentials on an account which has at least one Profile with at least one device assigned and disconnected for more than an hour and less 24 hours|

|2           | Normal    | click on "People" tab to open the "People" page|

|3           | Normal    | click on a profile card with at least one device disconnected to open the corresponding Profile Entity page|

|4           | Validate  | is the Connection Status copy under the name of devices, in the Assigned Devices, disconnected for more than an hour but less then 24 hours set to "Last connected [x] hours ago"?|



| 00013 - Verify the correct Connection Status copy shown under a disconnected device that last connected time was an hour ago  in IgniteWiFi site|

|Step number | Step Type | Description|

|1           | Normal    | login to IgniteWiFi using valid credentials on an account which has at least one Profile with at least one device assigned and disconnected an hour ago|

|2           | Normal    | click on People tab to open the People page|

|3           | Normal    | click on a profile card with at least one device disconnected to open the corresponding Profile Entity page|

|4           | Validate  | is the Connection Status copy under the name of devices, in the Assigned Devices, disconnected for 1 hour set to "Last connected an hour ago"?|



| 00014 - Verify the correct Connection Status copy shown under a disconnected device that last connected time was more than 24 hours ago in IgniteWiFi site |

|Step number | Step Type | Description|

|1           | Normal    | login to IgniteWiFi using valid credentials on an account which has at least one Profile with at least one device assigned and disconnected for more than 24 hours|

|2           | Normal    | click on People tab to open the People page|

|3           | Normal    | click on a profile card with at least one device disconnected to open the corresponding Profile Entity page|

|4           | Validate  | is the Connection Status copy under the name of devices, in the Assigned Devices, disconnected for more than 24 hours set to "Last connected [MM/DD]"?|



| 00015 - Verify the correct Connection Status copy shown under a disconnected device that occurs in an error  in IgniteWiFi site|

|Step number | Step Type | Description|

|1           | Normal    | login to IgniteWiFi using valid credentials on an account which has at least one Profile with at least one device assigned and disconnected for more than 24 hours and that occurs in an error and ORC returns a undefined/null|

|2           | Normal    | click on People tab to open the People page|

|3           | Normal    | click on a profile card with at least one device disconnected to open the corresponding Profile Entity page|

|4           | Validate  | is the Connection Status copy under the name of devices, in the Assigned Devices, disconnected for more than 24 hours which occurs to an error set to "Can't determine last seen date"?|




| 00016 - Test the functionality of Assign Devices list cards  in IgniteWiFi site|

|Step number | Step Type | Description|

|1           | Normal    | login to IgniteWiFi using valid credentials on an account which has at least one Profile with at least one device assigned|

|2           | Normal    | click on "People" tab to open the People page|

|3           | Normal    | click on a profile card to open the corresponding Profile Entity page|

|4           | Validate  | is the Device Entity page opened?|



| 00017 - Verify the correct list sorting on devices  in IgniteWiFi site|

|Step number | Step Type | Description|

|1           | Normal    | login to IgniteWiFi using valid credentials on an account which has at least one Profile with at least one device assigned and device sorting is set on "Last seen"|

|2           | Normal    | click on People tab to open the People page|

|3           | Normal    | click on a profile card to open the corresponding Profile Entity page|

|4           | Validate  | are devices with "Can't determine last seen date" Connection Status copy in the last positions of the list?|

| 00018 - Verify the correct Connection Status copy shown under a connected device in BlueCurve site|

|Step number | Step Type | Description|

|1           | Normal    | login to BlueCurve using valid credentials on an account which has at least one Profile with at least one device assigned and connected|

|2           | Normal    | click on People tab to open the People page|

|3           | Normal    | click on a profile card with at least one device connected to open the corresponding Profile Entity page|

|4           | Validate  | is the Connection Status copy under connected devices name in the Assigned Devices list set to "Connected to Gateway"?|




| 00019 - Verify the correct Connection Status copy shown under a disconnected device that last connected time was less than 1 minute  in BlueCurve site|

|Step number | Step Type | Description|

|1           | Normal    | login to BlueCurve using valid credentials on an account which has at least one Profile with at least one device assigned and disconnected for less than a minute|

|2           | Normal    | click on People tab to open the People page|

|3           | Normal    | click on a profile card with at least one device disconnected to open the corresponding Profile Entity page|

|4           | Validate  | is the Connection Status copy under the name of devices, in the Assigned Devices, disconnected for less than a minute set to "Last connected a minute ago"?|



| 00020 - Verify the correct Connection Status copy shown under a disconnected device that last connected time was more than a minute but less than an hour  in BlueCurve site|

|Step number | Step Type | Description|

|1           | Normal    | login to BlueCurve using valid credentials on an account which has at least one Profile with at least one device assigned and disconnected for more than a minute and less than an hour|

|2           | Normal    | click on People tab to open the People page|

|3           | Normal    | click on a profile card with at least one device disconnected to open the corresponding Profile Entity page|

|4           | Validate  | is the Connection Status copy under the name of devices, in the Assigned Devices, disconnected for more than a minute but less then an hour set to "Last connected [x] minutes ago"?|




| 00021 - Verify the correct Connection Status  copy shown under a disconnected device that last connected time was more than an hour but less than 24 hours  in BlueCurve site|

|Step number | Step Type | Description|

|1           | Normal    | login to BlueCurve using valid credentials on an account which has at least one Profile with at least one device assigned and disconnected for more than an hour and less 24 hours|

|2           | Normal    | click on "People" tab to open the "People" page|

|3           | Normal    | click on a profile card with at least one device disconnected to open the corresponding Profile Entity page|

|4           | Validate  | is the Connection Status copy under the name of devices, in the Assigned Devices, disconnected for more than an hour but less then 24 hours set to "Last connected [x] hours ago"?|



| 00022 - Verify the correct Connection Status copy shown under a disconnected device that last connected time was an hour ago  in BlueCurve site|

|Step number | Step Type | Description|

|1           | Normal    | login to BlueCurve using valid credentials on an account which has at least one Profile with at least one device assigned and disconnected an hour ago|

|2           | Normal    | click on People tab to open the People page|

|3           | Normal    | click on a profile card with at least one device disconnected to open the corresponding Profile Entity page|

|4           | Validate  | is the Connection Status copy under the name of devices, in the Assigned Devices, disconnected for 1 hour set to "Last connected an hour ago"?|



| 00023 - Verify the correct Connection Status copy shown under a disconnected device that last connected time was more than 24 hours ago in BlueCurve site |

|Step number | Step Type | Description|

|1           | Normal    | login to BlueCurve using valid credentials on an account which has at least one Profile with at least one device assigned and disconnected for more than 24 hours|

|2           | Normal    | click on People tab to open the People page|

|3           | Normal    | click on a profile card with at least one device disconnected to open the corresponding Profile Entity page|

|4           | Validate  | is the Connection Status copy under the name of devices, in the Assigned Devices, disconnected for more than 24 hours set to "Last connected [MM/DD]"?|



| 00024 - Verify the correct Connection Status copy shown under a disconnected device that occurs in an error  in BlueCurve site|

|Step number | Step Type | Description|

|1           | Normal    | login to BlueCurve using valid credentials on an account which has at least one Profile with at least one device assigned and disconnected for more than 24 hours and that occurs in an error and ORC returns a undefined/null|

|2           | Normal    | click on People tab to open the People page|

|3           | Normal    | click on a profile card with at least one device disconnected to open the corresponding Profile Entity page|

|4           | Validate  | is the Connection Status copy under the name of devices, in the Assigned Devices, disconnected for more than 24 hours which occurs to an error set to "Can't determine last seen date"?|




| 00025 - Test the functionality of Assign Devices list cards  in BlueCurve site|

|Step number | Step Type | Description|

|1           | Normal    | login to BlueCurve using valid credentials on an account which has at least one Profile with at least one device assigned|

|2           | Normal    | click on "People" tab to open the People page|

|3           | Normal    | click on a profile card to open the corresponding Profile Entity page|

|4           | Validate  | is the Device Entity page opened?|



| 00026 - Verify the correct list sorting on devices  in BlueCurve site|

|Step number | Step Type | Description|

|1           | Normal    | login to BlueCurve using valid credentials on an account which has at least one Profile with at least one device assigned and device sorting is set on "Last seen"|

|2           | Normal    | click on People tab to open the People page|

|3           | Normal    | click on a profile card to open the corresponding Profile Entity page|

|4           | Validate  | are devices with "Can't determine last seen date" Connection Status copy in the last positions of the list?|


| 00027 - Verify the correct Connection Status copy shown under a connected device in HelixFi site|

|Step number | Step Type | Description|

|1           | Normal    | login to HelixFi using valid credentials on an account which has at least one Profile with at least one device assigned and connected|

|2           | Normal    | click on People tab to open the People page|

|3           | Normal    | click on a profile card with at least one device connected to open the corresponding Profile Entity page|

|4           | Validate  | is the Connection Status copy under connected devices name in the Assigned Devices list set to "Connected to Gateway"?|




| 00028 - Verify the correct Connection Status copy shown under a disconnected device that last connected time was less than 1 minute  in HelixFi site|

|Step number | Step Type | Description|

|1           | Normal    | login to HelixFi using valid credentials on an account which has at least one Profile with at least one device assigned and disconnected for less than a minute|

|2           | Normal    | click on People tab to open the People page|

|3           | Normal    | click on a profile card with at least one device disconnected to open the corresponding Profile Entity page|

|4           | Validate  | is the Connection Status copy under the name of devices, in the Assigned Devices, disconnected for less than a minute set to "Last connected a minute ago"?|



| 00029 - Verify the correct Connection Status copy shown under a disconnected device that last connected time was more than a minute but less than an hour  in HelixFi site|

|Step number | Step Type | Description|

|1           | Normal    | login to HelixFi using valid credentials on an account which has at least one Profile with at least one device assigned and disconnected for more than a minute and less than an hour|

|2           | Normal    | click on People tab to open the People page|

|3           | Normal    | click on a profile card with at least one device disconnected to open the corresponding Profile Entity page|

|4           | Validate  | is the Connection Status copy under the name of devices, in the Assigned Devices, disconnected for more than a minute but less then an hour set to "Last connected [x] minutes ago"?|




| 00030 - Verify the correct Connection Status  copy shown under a disconnected device that last connected time was more than an hour but less than 24 hours  in HelixFi site|

|Step number | Step Type | Description|

|1           | Normal    | login to HelixFi using valid credentials on an account which has at least one Profile with at least one device assigned and disconnected for more than an hour and less 24 hours|

|2           | Normal    | click on "People" tab to open the "People" page|

|3           | Normal    | click on a profile card with at least one device disconnected to open the corresponding Profile Entity page|

|4           | Validate  | is the Connection Status copy under the name of devices, in the Assigned Devices, disconnected for more than an hour but less then 24 hours set to "Last connected [x] hours ago"?|



| 00031 - Verify the correct Connection Status copy shown under a disconnected device that last connected time was an hour ago  in HelixFi site|

|Step number | Step Type | Description|

|1           | Normal    | login to HelixFi using valid credentials on an account which has at least one Profile with at least one device assigned and disconnected an hour ago|

|2           | Normal    | click on People tab to open the People page|

|3           | Normal    | click on a profile card with at least one device disconnected to open the corresponding Profile Entity page|

|4           | Validate  | is the Connection Status copy under the name of devices, in the Assigned Devices, disconnected for 1 hour set to "Last connected an hour ago"?|



| 00032 - Verify the correct Connection Status copy shown under a disconnected device that last connected time was more than 24 hours ago in HelixFi site |

|Step number | Step Type | Description|

|1           | Normal    | login to HelixFi using valid credentials on an account which has at least one Profile with at least one device assigned and disconnected for more than 24 hours|

|2           | Normal    | click on People tab to open the People page|

|3           | Normal    | click on a profile card with at least one device disconnected to open the corresponding Profile Entity page|

|4           | Validate  | is the Connection Status copy under the name of devices, in the Assigned Devices, disconnected for more than 24 hours set to "Last connected [MM/DD]"?|



| 00033 - Verify the correct Connection Status copy shown under a disconnected device that occurs in an error  in HelixFi site|

|Step number | Step Type | Description|

|1           | Normal    | login to HelixFi using valid credentials on an account which has at least one Profile with at least one device assigned and disconnected for more than 24 hours and that occurs in an error and ORC returns a undefined/null|

|2           | Normal    | click on People tab to open the People page|

|3           | Normal    | click on a profile card with at least one device disconnected to open the corresponding Profile Entity page|

|4           | Validate  | is the Connection Status copy under the name of devices, in the Assigned Devices, disconnected for more than 24 hours which occurs to an error set to "Can't determine last seen date"?|




| 00034 - Test the functionality of Assign Devices list cards  in HelixFi site|

|Step number | Step Type | Description|

|1           | Normal    | login to HelixFi using valid credentials on an account which has at least one Profile with at least one device assigned|

|2           | Normal    | click on "People" tab to open the People page|

|3           | Normal    | click on a profile card to open the corresponding Profile Entity page|

|4           | Validate  | is the Device Entity page opened?|



| 00035 - Verify the correct list sorting on devices  in HelixFi site|

|Step number | Step Type | Description|

|1           | Normal    | login to HelixFi using valid credentials on an account which has at least one Profile with at least one device assigned and device sorting is set on "Last seen"|

|2           | Normal    | click on People tab to open the People page|

|3           | Normal    | click on a profile card to open the corresponding Profile Entity page|

|4           | Validate  | are devices with "Can't determine last seen date" Connection Status copy in the last positions of the list?|


| 00036 - Verify the correct Connection Status copy shown under a connected device in CoxWiFi site|

|Step number | Step Type | Description|

|1           | Normal    | login to CoxWiFi using valid credentials on an account which has at least one Profile with at least one device assigned and connected|

|2           | Normal    | click on People tab to open the People page|

|3           | Normal    | click on a profile card with at least one device connected to open the corresponding Profile Entity page|

|4           | Validate  | is the Connection Status copy under connected devices name in the Assigned Devices list set to "Connected to Gateway"?|




| 00037 - Verify the correct Connection Status copy shown under a disconnected device that last connected time was less than 1 minute  in CoxWiFi site|

|Step number | Step Type | Description|

|1           | Normal    | login to CoxWiFi using valid credentials on an account which has at least one Profile with at least one device assigned and disconnected for less than a minute|

|2           | Normal    | click on People tab to open the People page|

|3           | Normal    | click on a profile card with at least one device disconnected to open the corresponding Profile Entity page|

|4           | Validate  | is the Connection Status copy under the name of devices, in the Assigned Devices, disconnected for less than a minute set to "Last connected a minute ago"?|



| 00038 - Verify the correct Connection Status copy shown under a disconnected device that last connected time was more than a minute but less than an hour  in CoxWiFi site|

|Step number | Step Type | Description|

|1           | Normal    | login to CoxWiFi using valid credentials on an account which has at least one Profile with at least one device assigned and disconnected for more than a minute and less than an hour|

|2           | Normal    | click on People tab to open the People page|

|3           | Normal    | click on a profile card with at least one device disconnected to open the corresponding Profile Entity page|

|4           | Validate  | is the Connection Status copy under the name of devices, in the Assigned Devices, disconnected for more than a minute but less then an hour set to "Last connected [x] minutes ago"?|




| 00039 - Verify the correct Connection Status  copy shown under a disconnected device that last connected time was more than an hour but less than 24 hours  in CoxWiFi site|

|Step number | Step Type | Description|

|1           | Normal    | login to CoxWiFi using valid credentials on an account which has at least one Profile with at least one device assigned and disconnected for more than an hour and less 24 hours|

|2           | Normal    | click on "People" tab to open the "People" page|

|3           | Normal    | click on a profile card with at least one device disconnected to open the corresponding Profile Entity page|

|4           | Validate  | is the Connection Status copy under the name of devices, in the Assigned Devices, disconnected for more than an hour but less then 24 hours set to "Last connected [x] hours ago"?|



| 00040 - Verify the correct Connection Status copy shown under a disconnected device that last connected time was an hour ago  in CoxWiFi site|

|Step number | Step Type | Description|

|1           | Normal    | login to CoxWiFi using valid credentials on an account which has at least one Profile with at least one device assigned and disconnected an hour ago|

|2           | Normal    | click on People tab to open the People page|

|3           | Normal    | click on a profile card with at least one device disconnected to open the corresponding Profile Entity page|

|4           | Validate  | is the Connection Status copy under the name of devices, in the Assigned Devices, disconnected for 1 hour set to "Last connected an hour ago"?|



| 00041 - Verify the correct Connection Status copy shown under a disconnected device that last connected time was more than 24 hours ago in CoxWiFi site |

|Step number | Step Type | Description|

|1           | Normal    | login to CoxWiFi using valid credentials on an account which has at least one Profile with at least one device assigned and disconnected for more than 24 hours|

|2           | Normal    | click on People tab to open the People page|

|3           | Normal    | click on a profile card with at least one device disconnected to open the corresponding Profile Entity page|

|4           | Validate  | is the Connection Status copy under the name of devices, in the Assigned Devices, disconnected for more than 24 hours set to "Last connected [MM/DD]"?|



| 00042 - Verify the correct Connection Status copy shown under a disconnected device that occurs in an error  in CoxWiFi site|

|Step number | Step Type | Description|

|1           | Normal    | login to CoxWiFi using valid credentials on an account which has at least one Profile with at least one device assigned and disconnected for more than 24 hours and that occurs in an error and ORC returns a undefined/null|

|2           | Normal    | click on People tab to open the People page|

|3           | Normal    | click on a profile card with at least one device disconnected to open the corresponding Profile Entity page|

|4           | Validate  | is the Connection Status copy under the name of devices, in the Assigned Devices, disconnected for more than 24 hours which occurs to an error set to "Can't determine last seen date"?|




| 00043 - Test the functionality of Assign Devices list cards  in CoxWiFi site|

|Step number | Step Type | Description|

|1           | Normal    | login to CoxWiFi using valid credentials on an account which has at least one Profile with at least one device assigned|

|2           | Normal    | click on "People" tab to open the People page|

|3           | Normal    | click on a profile card to open the corresponding Profile Entity page|

|4           | Validate  | is the Device Entity page opened?|



| 00044 - Verify the correct list sorting on devices  in CoxWiFi site|

|Step number | Step Type | Description|

|1           | Normal    | login to CoxWiFi using valid credentials on an account which has at least one Profile with at least one device assigned and device sorting is set on "Last seen"|

|2           | Normal    | click on People tab to open the People page|

|3           | Normal    | click on a profile card to open the corresponding Profile Entity page|

|4           | Validate  | are devices with "Can't determine last seen date" Connection Status copy in the last positions of the list?|


| 00045 - Verify the correct Connection Status copy shown under a connected device in Sky WiFi site|

|Step number | Step Type | Description|

|1           | Normal    | login to Sky WiFi using valid credentials on an account which has at least one Profile with at least one device assigned and connected|

|2           | Normal    | click on People tab to open the People page|

|3           | Normal    | click on a profile card with at least one device connected to open the corresponding Profile Entity page|

|4           | Validate  | is the Connection Status copy under connected devices name in the Assigned Devices list set to "Connected to Gateway"?|




| 00046 - Verify the correct Connection Status copy shown under a disconnected device that last connected time was less than 1 minute  in Sky WiFi site|

|Step number | Step Type | Description|

|1           | Normal    | login to Sky WiFi using valid credentials on an account which has at least one Profile with at least one device assigned and disconnected for less than a minute|

|2           | Normal    | click on People tab to open the People page|

|3           | Normal    | click on a profile card with at least one device disconnected to open the corresponding Profile Entity page|

|4           | Validate  | is the Connection Status copy under the name of devices, in the Assigned Devices, disconnected for less than a minute set to "Last connected a minute ago"?|



| 00047 - Verify the correct Connection Status copy shown under a disconnected device that last connected time was more than a minute but less than an hour  in Sky WiFi site|

|Step number | Step Type | Description|

|1           | Normal    | login to Sky WiFi using valid credentials on an account which has at least one Profile with at least one device assigned and disconnected for more than a minute and less than an hour|

|2           | Normal    | click on People tab to open the People page|

|3           | Normal    | click on a profile card with at least one device disconnected to open the corresponding Profile Entity page|

|4           | Validate  | is the Connection Status copy under the name of devices, in the Assigned Devices, disconnected for more than a minute but less then an hour set to "Last connected [x] minutes ago"?|




| 00048 - Verify the correct Connection Status  copy shown under a disconnected device that last connected time was more than an hour but less than 24 hours  in Sky WiFi site|

|Step number | Step Type | Description|

|1           | Normal    | login to Sky WiFi using valid credentials on an account which has at least one Profile with at least one device assigned and disconnected for more than an hour and less 24 hours|

|2           | Normal    | click on "People" tab to open the "People" page|

|3           | Normal    | click on a profile card with at least one device disconnected to open the corresponding Profile Entity page|

|4           | Validate  | is the Connection Status copy under the name of devices, in the Assigned Devices, disconnected for more than an hour but less then 24 hours set to "Last connected [x] hours ago"?|



| 00049 - Verify the correct Connection Status copy shown under a disconnected device that last connected time was an hour ago  in Sky WiFi site|

|Step number | Step Type | Description|

|1           | Normal    | login to Sky WiFi using valid credentials on an account which has at least one Profile with at least one device assigned and disconnected an hour ago|

|2           | Normal    | click on People tab to open the People page|

|3           | Normal    | click on a profile card with at least one device disconnected to open the corresponding Profile Entity page|

|4           | Validate  | is the Connection Status copy under the name of devices, in the Assigned Devices, disconnected for 1 hour set to "Last connected an hour ago"?|



| 00050 - Verify the correct Connection Status copy shown under a disconnected device that last connected time was more than 24 hours ago in Sky WiFi site |

|Step number | Step Type | Description|

|1           | Normal    | login to Sky WiFi using valid credentials on an account which has at least one Profile with at least one device assigned and disconnected for more than 24 hours|

|2           | Normal    | click on People tab to open the People page|

|3           | Normal    | click on a profile card with at least one device disconnected to open the corresponding Profile Entity page|

|4           | Validate  | is the Connection Status copy under the name of devices, in the Assigned Devices, disconnected for more than 24 hours set to "Last connected [MM/DD]"?|



| 00051 - Verify the correct Connection Status copy shown under a disconnected device that occurs in an error  in Sky WiFi site|

|Step number | Step Type | Description|

|1           | Normal    | login to Sky WiFi using valid credentials on an account which has at least one Profile with at least one device assigned and disconnected for more than 24 hours and that occurs in an error and ORC returns a undefined/null|

|2           | Normal    | click on People tab to open the People page|

|3           | Normal    | click on a profile card with at least one device disconnected to open the corresponding Profile Entity page|

|4           | Validate  | is the Connection Status copy under the name of devices, in the Assigned Devices, disconnected for more than 24 hours which occurs to an error set to "Can't determine last seen date"?|




| 00052 - Test the functionality of Assign Devices list cards  in Sky WiFi site|

|Step number | Step Type | Description|

|1           | Normal    | login to Sky WiFi using valid credentials on an account which has at least one Profile with at least one device assigned|

|2           | Normal    | click on "People" tab to open the People page|

|3           | Normal    | click on a profile card to open the corresponding Profile Entity page|

|4           | Validate  | is the Device Entity page opened?|



| 00053 - Verify the correct list sorting on devices  in Sky WiFi site|

|Step number | Step Type | Description|

|1           | Normal    | login to Sky WiFi using valid credentials on an account which has at least one Profile with at least one device assigned and device sorting is set on "Last seen"|

|2           | Normal    | click on People tab to open the People page|

|3           | Normal    | click on a profile card to open the corresponding Profile Entity page|

|4           | Validate  | are devices with "Can't determine last seen date" Connection Status copy in the last positions of the list?|

