| 000090 - Verify the Settings Moved modal is not shown after an User's first access on the Settings page |
| Step number | Step Type | Description|
| 1           | Normal    | login to xFi using valid credentials on an account which has at least one Profile with at least one connected device in which the Settings page has not been opened |
| 2           | Normal    | click on the People card to open the People page |
| 3           | Normal    | click on "<#.profile_name>" to open the Profile page |
| 4           | Normal    | click on the Gear button to open the Settings page |
| 5           | Validate  | is the "Settings" page shown without any "Settings moved" modal? |


| 000101 - Verify the New badge is not shown after the Settings Page is visited|
| Step number | Step Type | Description|
| 1           | Normal    | login to xFi using valid credentials on an account which has at least one Profile with at least one connected device|
| 2           | Normal    | click on the People card to open the People page |
| 3           | Normal    | click on "<#.profile_name>" to open the Profile page |
| 4           | Normal    | click on the Gear button to open the Settings page |
| 5           | Normal    | click on the "Back" button link to return to the Profile page |
| 6           | Validate  | is the "New" icon not shown over the Gear button? |


[comment]: <> (UI)

| 000092 - Verify the New badge is shown over the Gear icon|
| Step number | Step Type | Description|
| 1           | Normal    | login to xFi using valid credentials on an account which has at least one Profile with at least one connected device|
| 2           | Normal    | click on the People card to open the People page |
| 3           | Normal    | click on "<#.profile_name>" to open the Profile page |
| 4           | Validate  | is the "New" icon shown over the Gear button? |

| 000093 - Verify the New badge is shown over the Gear icon on the French website|
| Step number | Step Type | Description|
| 1           | Normal    | login to one of the Syndacated partners (Rogers, Cox, Videotron, Shaw) using valid credentials in a device/browser which has the language set to French and on an account which has at least one Profile with at least one connected device|
| 2           | Normal    | click on the Personnes card to open the People page |
| 3           | Normal    | click on "<#.profile_name>" to open the Profile page |
| 4           | Validate  | is the "New" icon shown over the Gear button? |


[comment]: <> (In the following UI test cases I'm trying to guess how the settings page is going to be changed. )

| 000115 - Verify the full page Carousel is shown at first Settings Page access  |
| Step number | Step Type | Description|
| 1           | Normal    | login to xFi using valid credentials on an account which has at least one Profile with at least one connected device |
| 2           | Normal    | click on the People card to open the People page |
| 3           | Normal    | click on "<#.profile_name>" to open the Profile page |
| 4           | Normal    | click on the Gear button to open the Settings page|
| 5           | Validate  | is the "Settings" full page Carousel visible in the Settings Page? |

| 000117 - Verify the X button is shown on the top right corner of the New Settings Page Carousel |
| Step number | Step Type | Description|
| 1           | Normal    | login to xFi using valid credentials on an account which has at least one Profile with at least one connected device |
| 2           | Normal    | click on the People card to open the People page |
| 3           | Normal    | click on "<#.profile_name>" to open the Profile page |
| 4           | Normal    | click on the Gear button to open the Settings page|
| 5           | Validate  | is the "X" button visible in the top right corner of the "New Settings Page" full page Carousel in the Settings page? |

| 000118 - Verify the Carousel Indicators are shown at the bottom of the New Settings Page Carousel |
| Step number | Step Type | Description|
| 1           | Normal    | login to xFi using valid credentials on an account which has at least one Profile with at least one connected device |
| 2           | Normal    | click on the People card to open the People page |
| 3           | Normal    | click on "<#.profile_name>" to open the Profile page |
| 4           | Normal    | click on the Gear button to open the Settings page|
| 5           | Validate  | are the Carousel Indicators visible at the bottom center of the "New Settings Page" full page Carousel in the Settings page? |

| 000119 - Verify the New Settings Page full page Carousel is not shown if Settings Page is accessed twice  |
| Step number | Step Type | Description|
| 1           | Normal    | login to xFi using valid credentials on an account which has at least one Profile with at least one connected device |
| 2           | Normal    | click on the People card to open the People page |
| 3           | Normal    | click on "<#.profile_name>" to open the Profile page |
| 4           | Normal    | click on the Gear button to open the Settings page|
| 6           | Normal    | click on the "X" button to close the "New Settings page" Carousel|
| 7           | Normal    | click on the "Back" button to return to the Profile page|
| 8           | Normal    | click on the Gear button to open the Settings page|
| 9           | Validate  | is the "New Settings Page" full page Carousel not visible in the Settings Page? |

| 000121 - Verify the Next button is visible in the New Settings Page Carousel |
| Step number | Step Type | Description|
| 1           | Normal    | login to xFi using valid credentials on an account which has at least one Profile with at least one connected device |
| 2           | Normal    | click on the People card to open the People page |
| 3           | Normal    | click on "<#.profile_name>" to open the Profile page |
| 4           | Normal    | click on the Gear button to open the Settings page|
| 5           | Validate  | is the "Next" button shown in the "New Settings Page" full page Carousel? |

[comment]: <> (Functional)

| 000091 - Verify the Gear button functionality|
| Step number | Step Type | Description|
| 1           | Normal    | login to xFi using valid credentials on an account which has at least one Profile with at least one connected device |
| 2           | Normal    | click on the People card to open the People page |
| 3           | Normal    | click on "<#.profile_name>" to open the Profile page |
| 4           | Normal    | click on the Gear button to open the Settings page |
| 5           | Validate  | is the Settings page shown? |

[comment]: <> (The following Functional tests are related to the carousel UI tests I wrote )

| 000120 - Verify the X button functionality in the New Settings Page Carousel |
| Step number | Step Type | Description|
| 1           | Normal    | login to xFi using valid credentials on an account which has at least one Profile with at least one connected device in which the Settings page has not been opened|
| 2           | Normal    | click on the People card to open the People page |
| 3           | Normal    | click on "<#.profile_name>" to open the Profile page |
| 4           | Normal    | click on the Gear button to open the Settings page|
| 5           | Normal    | click on the "X" button |
| 6           | Validate  | is the "New Settings Page" Carousel not shown in the Settings page? |

| 000116 - Verify the Next button functionality in the New Settings Page Carousel |
| Step number | Step Type | Description|
| 1           | Normal    | login to xFi using valid credentials on an account which has at least one Profile with at least one connected device |
| 2           | Normal    | click on the People card to open the People page |
| 3           | Normal    | click on "<#.profile_name>" to open the Profile page |
| 4           | Normal    | click on the Gear button to open the Settings page|
| 5           | Normal    | click on the "Next" button |
| 6           | Validate  | is the second picture shown in the "New Settings Page" Carousel? |

| 000122 - Verify the Carousel Indicators functionality in the New Settings Page Carousel |
| Step number | Step Type | Description|
| 1           | Normal    | login to xFi using valid credentials on an account which has at least one Profile with at least one connected device |
| 2           | Normal    | click on the People card to open the People page |
| 3           | Normal    | click on "<#.profile_name>" to open the Profile page |
| 4           | Normal    | click on the Gear button to open the Settings page|
| 5           | Normal    | click on the second Carousel Indicator |
| 6           | Validate  | is the second picture shown in the "New Settings Page" Carousel? |


[comment]: <> (The following tests are tests that I  wrote earlier that are not relevant to the Gear icon
nor to the "New Settings Page" Carousel and are of secondary importance. )

| 000094 - Verify the Settings Page title is correctly displayed|
| Step number | Step Type | Description|
| 1           | Normal    | login to xFi using valid credentials on an account which has at least one Profile with at least one connected device|
| 2           | Normal    | click on the People card to open the People page |
| 3           | Normal    | click on "<#.profile_name>" to open the Profile page |
| 4           | Normal    | click on the Gear button |
| 5           | Validate  | is "<#.profile_name>'s Settings" displayed as the page title? |

| 000095 - Verify the Settings Page title is correctly translated to Spanish|
| Step number | Step Type | Description|
| 1           | Normal    | login to xFi using valid credentials in a device/browser which has the language set to Spanish and on an account which has at least one Profile with at least one connected device|
| 2           | Normal    | click on the Gente card to open the People page |
| 3           | Normal    | click on "<#.profile_name>" to open the Profile page |
| 4           | Normal    | click on the Gear button |
| 5           | Validate  | is "Configuraciones de <#.profile_name>" displayed as the page title? |

| 000096 - Verify the Settings Page title is correctly translated to French|
| Step number | Step Type | Description|
| 1           | Normal    | login to one of the Syndacated partners (Rogers, Cox, Videotron, Shaw) using valid credentials in a device/browser which has the language set to French and on an account which has at least one Profile with at least one connected device|
| 2           | Normal    | click on the Personnes card to open the People page |
| 3           | Normal    | click on "<#.profile_name>" to open the Profile page |
| 4           | Normal    | click on the Gear button |
| 5           | Validate  | is "Paramètres de <#.profile_name>" displayed as the page title? |

| 000097 - Verify that buttons are correctly displayed under the Activity Settings card |
| Step number | Step Type | Description|
| 1           | Normal    | login to xFi using valid credentials on an account which has at least one Profile with at least one connected device and with no Active Time Limit set up|
| 2           | Normal    | click on the People card to open the People page |
| 3           | Normal    | click on "<#.profile_name>" to open the Profile page |
| 4           | Normal    | click on the Gear button |
| 5           | Validate  | Are the "Set up an Active Time Limit", "Activity Reporting" and "Parental Controls" buttons displayed in the "Activity Settings" card? |

| 000098 - Verify that buttons are correctly displayed in the Profile Settings card |
| Step number | Step Type | Description|
| 1           | Normal    | login to xFi using valid credentials on an account which has at least one Profile with at least one connected device|
| 2           | Normal    | click on the People card to open the People page |
| 3           | Normal    | click on "<#.profile_name>" to open the Profile page |
| 4           | Normal    | click on the Gear button to open the Settings page |
| 5           | Validate  | is the "<#.profile_name>" button displayed in the "Profile Settings" card? |

| 000099 - Verify that buttons are correctly displayed in the Downtime card if Downtime schedules exist |
| Step number | Step Type | Description|
| 1           | Normal    | login to xFi using valid credentials on an account which has at least one Profile with at least one connected device and with one or more Downtime Schedules set up |
| 2           | Normal    | click on the People card to open the People page |
| 3           | Normal    | click on "<#.profile_name>" to open the Profile page |
| 4           | Normal    | click on the Gear button to open the Settings page|
| 5           | Validate  | are the "<#.schedule_name>" buttons displayed in the "Downtime" card? |

| 000100 - Verify the Create a Downtime Schedule button is displayed if the profile has no Downtime Schedule |
| Step number | Step Type | Description|
| 1           | Normal    | login to xFi using valid credentials on an account which has at least one Profile with at least one connected device and with no Downtime Schedules set up |
| 2           | Normal    | click on the People card to open the People page |
| 3           | Normal    | click on "<#.profile_name>" to open the Profile page |
| 4           | Normal    | click on the Gear button to open the Settings page|
| 5           | Validate  | is the "Create a Downtime Schedule" button displayed in the "Downtime" card? |

| 000103 - Verify that buttons are correctly displayed in the Activity Settings card in the French website|
| Step number | Step Type | Description|
| 1           | Normal    | login to one of the Syndacated partners (Rogers, Cox, Videotron, Shaw) using valid credentials in a device/browser which has the language set to French and on an account which has at least one Profile with at least one connected device and no Active Time Limit set up|
| 2           | Normal    | click on the People card to open the People page |
| 3           | Normal    | click on "<#.profile_name>" to open the Profile page |
| 4           | Normal    | click on the Gear button |
| 5           | Validate  | Are the "Programmer une limite de durée d’activité" and "Contrôle parental" buttons displayed in the "Activity Settings" card? |

| 000104 - Verify the Active Time Limit button is displayed if Active Time Limits exist |
| Step number | Step Type | Description|
| 1           | Normal    | login to xFi using valid credentials on an account which has at least one Profile with at least one connected device and with an Active Time Limit set up |
| 2           | Normal    | click on the People card to open the People page |
| 3           | Normal    | click on "<#.profile_name>" to open the Profile page |
| 4           | Normal    | click on the Gear button to open the Settings page|
| 5           | Validate  | is the "Active Time Limit" button shown under the "Activity Settings" card? |

| 000111 - Verify the Get Started button link is visible in the Create a Downtime Schedule button  |
| Step number | Step Type | Description|
| 1           | Normal    | login to xFi using valid credentials on an account which has at least one Profile with at least one connected device with no downtime schedule set up |
| 2           | Normal    | click on the People card to open the People page |
| 3           | Normal    | click on "<#.profile_name>" to open the Profile page |
| 4           | Normal    | click on the Gear button to open the Settings page|
| 5           | Validate  | is the "Get Started" button link visible in the "Create a Downtime Schedule" button? |

| 000112 - Verify the Get Started button link is not visible in Downtime buttons if a Downtime is set  |
| Step number | Step Type | Description|
| 1           | Normal    | login to xFi using valid credentials on an account which has at least one Profile with at least one connected device with at least one downtime schedule set up |
| 2           | Normal    | click on the People card to open the People page |
| 3           | Normal    | click on "<#.profile_name>" to open the Profile page |
| 4           | Normal    | click on the Gear button to open the Settings page|
| 5           | Validate  | is the "Get Started" button link not visible in each Downtime button? |

| 000113 - Verify the Get Started button link is visible in the Set up an Active Time Limit button  |
| Step number | Step Type | Description|
| 1           | Normal    | login to xFi using valid credentials on an account which has at least one Profile with at least one connected device with no Active Time Limit set up |
| 2           | Normal    | click on the People card to open the People page |
| 3           | Normal    | click on "<#.profile_name>" to open the Profile page |
| 4           | Normal    | click on the Gear button to open the Settings page|
| 5           | Validate  | is the "Get Started" button link visible in the "Set up an Active Time Limit" button? |

| 000114 - Verify the Get Started button link is not visible in Active Time Limit buttons if an Active Time Limit is set  |
| Step number | Step Type | Description|
| 1           | Normal    | login to xFi using valid credentials on an account which has at least one Profile with at least one connected device with an Active Time Limit set up |
| 2           | Normal    | click on the People card to open the People page |
| 3           | Normal    | click on "<#.profile_name>" to open the Profile page |
| 4           | Normal    | click on the Gear button to open the Settings page|
| 5           | Validate  | is the "Get Started" button link not visible in each "Active Time Limit" button? |

| 000105 - Verify the Active Time Limit button height is increased if Active Time Limits exist |
| Step number | Step Type | Description|
| 1           | Normal    | login to xFi using valid credentials on an account which has at least one Profile with at least one connected device and with an Active Time Limit set up |
| 2           | Normal    | click on the People card to open the People page |
| 3           | Normal    | click on "<#.profile_name>" to open the Profile page |
| 4           | Normal    | click on the Gear button to open the Settings page|
| 5           | Validate  | is the "Active Time Limit" button height set to 124px? |

| 000106 - Verify the Weekdays label is visible if an Active Time Limit is set on Weekdays |
| Step number | Step Type | Description|
| 1           | Normal    | login to xFi using valid credentials on an account which has at least one Profile with at least one connected device and with an Active Time Limit set on Weekdays |
| 2           | Normal    | click on the People card to open the People page |
| 3           | Normal    | click on "<#.profile_name>" to open the Profile page |
| 4           | Normal    | click on the Gear button to open the Settings page|
| 5           | Validate  | is the "Weekdays" label visible inside the Active Time Limit button? |

| 000107 - Verify the Weekends label is visible if an Active Time Limit is set on Weekends |
| Step number | Step Type | Description|
| 1           | Normal    | login to xFi using valid credentials on an account which has at least one Profile with at least one connected device and with an Active Time Limit set on Weekends |
| 2           | Normal    | click on the People card to open the People page |
| 3           | Normal    | click on "<#.profile_name>" to open the Profile page |
| 4           | Normal    | click on the Gear button to open the Settings page|
| 5           | Validate  | is the "Weekends" label visible inside the Active Time Limit button? |

| 000108 - Verify two Active Time Limit buttons are shown if Active Time Limits exist on both Weekends and Weekdays |
| Step number | Step Type | Description|
| 1           | Normal    | login to xFi using valid credentials on an account which has at least one Profile with at least one connected device and with Active Time Limits set up on both Weekends and Weekdays |
| 2           | Normal    | click on the People card to open the People page |
| 3           | Normal    | click on "<#.profile_name>" to open the Profile page |
| 4           | Normal    | click on the Gear button to open the Settings page|
| 5           | Validate  | are two "Active Time Limit" buttons shown in the Activity Settings card? |

| 000109 - Verify weekdays labels are shown for the selected days in each Downtime button |
| Step number | Step Type | Description|
| 1           | Normal    | login to xFi using valid credentials on an account which has at least one Profile with at least one connected device and with a downtime schedule set up |
| 2           | Normal    | click on the People card to open the People page |
| 3           | Normal    | click on "<#.profile_name>" to open the Profile page |
| 4           | Normal    | click on the Gear button to open the Settings page|
| 5           | Validate  | are the weekday labels shown in each Downtime button? |
