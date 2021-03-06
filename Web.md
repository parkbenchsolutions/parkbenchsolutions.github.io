# Web Latest Releases
## 5.32.1 (2021-7-21)
sync with api

<br><br>
## 5.32.0 (2021-7-21)
**July 21, 2021**

**Enhancements**

*   Bulk Email Password Reset Wizard
*   Branding Email Templates

**Bug fixes**
*   Fixed user access device endpoint sip contact list api
*   Unable to edit user profile with an admin login
*   Adding department was not available
*   Emergency call notification version changed to 22
*   Tags can now be submitted with no value
*   Add Hunt Groups form would reset if leaving page
*   Passcode tags not resolving on bulk wizards

**Upgrades**
*   Group intercept
*   Group trunk users
*   Group feature access codes
*   Group communication barring
*   Group Devices
*   Group Viewable Service Packs
*   Group Delete Group
*   Group Service Pack services
*   Enterprise Admins
*   Branding Modules


### Minor Changes 

- 83 Porting Department Trunk Stateful Rerouting #1076 474 Porting Group Configuration Services Trunk Group stateful rerouting #1177
- 384 Porting Department Trunk Unreachable #1077 475 Porting Group Configuration Services Trunk Group unreachable #1178
- User dashboard
- Porting/group-trunk-group
- Feature access code
- Merge pull request #346 from anshuporwal01/master
- Merge pull request #1375 from parkbenchsolutions/develop
- Merge pull request #1376 from pankajs1306/porting/group-trunk-group
- Access code
- Porting intercept group
- 351 Porting Department Add Users #1045 with #1371
- Feature access code
- Check with condition
- Email password template
- Menu items for user password email added
- Updated routes.js to accept a new route for email. Changed all naming to include &quot;Email&quot;. Route now renders with the same components as passwords update.
- Added two checkboxes to include reset token and send admin email
- Removed auth username and rebuild/reset device. renamed the card.
- Created a bulk email template service that returns templates in the same format as tags
- Group web policy testing
- User policy for profile
- User profile fixes
- Group web policies for user profile
- Group feture access code porting
- Featute access code policy
- Old changes revert back
- Merge pull request #193 from parkbenchsolutions/develop
- Comm barring
- Password
- Comm barring
- Comm barring porting
- Changes group department fixes
- Call forwarding selective
- Monitored users busy lamp field fixes
- Fax-messaging dept level fixes
- Group feature access code
- Added no answer personal greeting audio ui
- Department user-profile and user access permissions
- Fixes issues department adminstrator
- Changes for view users
- Hunt group department service
- Group services department level fixes branding
- User dashboard clid permission deparment level
- Merge pull request #284 from parkbenchsolutions/develop
- Added code to make it more relevant to the email welcome letter, the form should now update all of the correct data to send a task through
- Merge branch &#39;develop&#39; into feature/146-email-bulk-welcome-letter
- .
- Merge branch &#39;develop&#39; into feature/146-email-bulk-welcome-letter
- Removed unused code
- Reset some changes
- Porting/branding-feature
- Merge pull request #348 from parkbenchsolutions/develop
- Delete-group-service
- Merge pull request #349 from parkbenchsolutions/develop
- Policy changes
- Remove unwanted code
- Changed templates &amp; pulled in templates
- Added a series of useEffects and state setters to help the second useQuery call run only if there is a certain condition
- Branding templates
- Merge pull request #194 from parkbenchsolutions/develop
- Select device changes work fixes
- Merge branch &#39;develop&#39; into feature/146-email-bulk-welcome-letter
- Removed console logs
- Enabled the template for &#39;firstName lastName (userId)&#39; on user select
- Merge pull request #285 from parkbenchsolutions/develop
- Merge branch &#39;group-trunk-group-issue-fixes&#39; into porting/group-trunk-group
- Merge pull request #286 from parkbenchsolutions/porting/group-trunk-group
- Trunk group UI validation
- Merge pull request #350 from parkbenchsolutions/develop
- Merge pull request #1391 from pankajs1306/group-trunk-group-issue-fixes
- Merge pull request #351 from parkbenchsolutions/develop
- Lodash template added to bulk email
- Merge pull request #1394 from anshuporwal01/porting-user-dashboard-user
- Clean up
- Added actions to the form to help with defaulting the radio buttons
- Updated example task, removed unused vars, removed console logs
- Changed message to emailMessage
- Good luck
- Added prepareUsers
- Group user feature call forwarding always service settings
- Group call forwarding busy service
- Group service user bulk - no-answer, not rechable
- Call reocrding service group
- Calling line id blocking service
- Group hoteling guest service
- Hoteling host service group
- Group voice messaging service
- Various changes
- Merge pull request #1377 from parkbenchsolutions/porting/group-trunk-group
- Merge branch &#39;develop&#39; into feature/146-email-bulk-welcome-letter
- Group feature out going calling plan - bulk react migration files
- Group out going bulk feature
- Set up api to pull in templates and select a template based on a dropdown
- Validation
- Merge pull request #196 from parkbenchsolutions/develop
- Merge pull request #197 from Mayurkumar144/master
- Merge pull request #287 from parkbenchsolutions/develop
- Merge pull request #288 from pankajs1306/master
- Error in Trunk Group : For Call Capacity, Call Forward &amp; Settings #1396
- Groups users bulk feature settings
- Trunk group users
- Trunk group users
- Merge pull request #1400 from pankajs1306/porting-trunk-group-users
- Fixed unresolved tag issue
- Branding permissions
- Merge pull request #1401 from parkbenchsolutions/feature/146-email-bulk-welcome-letter
- Added lodash _.isEqual check to determine if useEffect is should run again
- Merge pull request #1402 from parkbenchsolutions/feature/146-email-bulk-welcome-letter
- Network class of service - react porting
- Fixes data - group-user-feature
- Merge branch &#39;group-user-feature&#39; of https://github.com/anshuporwal01/odinweb into group-user-feature
- Routing profile - react porting
- Changes
- Routing profile - react porting
- Merge pull request #1380 from Mayurkumar144:porting/group-intercept
- Merge pull request #352 from anshuporwal01/group-network-class-of-service
- Added small change
- Merge pull request #354 from parkbenchsolutions/develop
- Merge branch &#39;group-user-feature&#39; into master
- Merge branch &#39;porting/417-porting-group-user-bulk-feature&#39; into group-user-feature
- Added checks and console logs
- Changed example emailMessage
- Added a resolve passcode function
- Merge pull request #198 from parkbenchsolutions/develop
- Merge branch &#39;porting/feature-access-codes-group&#39; into 26-6-conflict
- Merge pull request #199 from Mayurkumar144/26-6-conflict
- Merge pull request #200 from Mayurkumar144/master
- Porting group device
- Group device
- Group device
- Group service packs - react migration
- Merge branch &#39;group-user-feature&#39; of https://github.com/anshuporwal01/odinweb into group-user-feature
- Merge pull request #1395 from parkbenchsolutions/porting/411-group-user-service
- Merge pull request #1398 from pankajs1306/group-trunk-group-issue-fixes
- Merge pull request #1403 from parkbenchsolutions/porting/group-trunk-group-users
- Merge pull request #1409 from Mayurkumar144/porting/feature-access-codes-group
- Merge pull request #1410 from Mayurkumar144/431-Porting-Group-Comm-barring-#1127
- Fixed user time zone form
- Merge branch &#39;develop&#39; into bug/653-user-time-zone-update
- Group service user feature -react migration
- Group service packs services
- Merge branch &#39;backup-group-feature-access-code&#39; into group-user-feature
- Revert old code fixes
- Merge branch &#39;group-user-feature&#39; of https://github.com/anshuporwal01/odinweb into group-user-feature
- Merge pull request #1408 from anshuporwal01/group-user-feature
- Merge pull request #201 from parkbenchsolutions/develop
- Merge pull request #202 from Mayurkumar144/master
- Odenweb
- Odinweb compare
- Sync branch
- Merge branch &#39;porting/417-porting-group-user-bulk-feature-service&#39; into porting/417-porting-group-user-bulk-feature
- Group-service-pack-services
- Service type changes
- Delete group service
- Merge branch &#39;delete-group-service&#39; of https://github.com/anshuporwal01/odinweb into delete-group-service
- Remove Unused File
- Added fn that changes the resetUrl tag to just a base string, will need to work further on this
- Removed passwordResetUrl
- Changed the dropdown of template select to default to Please Select
- Removed comments and commented out create passcode radio option
- Merge pull request #1417 from parkbenchsolutions/enhancement/bulk-email-password-template
- Delete group
- Changes for group dashboard menu
- Merge pull request #359 from parkbenchsolutions/develop
- Revert changes
- Merge branch &#39;delete-group-service&#39; into resole-confict-group-delete-service
- Merge pull request #361 from anshuporwal01/resole-confict-group-delete-service
- Delete group
- User profile settings
- Merge pull request #1418 from anshuporwal01:user-profile-settings
- Branding porting into React
- Group viewable service packs-user migration
- Profile routing
- Routing profile sp access issue
- Routing-profile remove link from sp and shw btn in res.
- Merge pull request #1387 from parkbenchsolutions/bug/641-ui-announcement-bug
- Merge pull request #1388 from parkbenchsolutions/bug/658-user-device-tags
- Merge pull request #1411 from parkbenchsolutions/bug/653-user-time-zone-update
- Merge remote-tracking branch &#39;origin/group-network-class-of-service&#39;
- Merge branch &#39;master&#39; of https://github.com/anshuporwal01/odinweb
- Porting/branding-feature
- Porting/branding-feature
- Viewable service packs
- Porting/branding-feature
- Porting/branding-feature
- Merge pull request #292 from parkbenchsolutions/develop
- Merge pull request #293 from pankajs1306/master
- Merge pull request #367 from parkbenchsolutions/develop
- Merge pull request #368 from parkbenchsolutions/develop
- Merge pull request #1424 from anshuporwal01/group-viewable-service-packs
- Merge pull request #1427 from anshuporwal01/delete-group-service
- Merge branch &#39;porting/423-porting-group-service-pack&#39; into group-service-packs-services
- Merge pull request #1429 from anshuporwal01/group-service-packs-services
- Fixes for porting/branding-feature
- Merge branch &#39;porting/branding-feature&#39; of https://github.com/pankajs1306/odinweb into porting/branding-feature
- Porting/branding-feature
- Merge pull request #1432 from pankajs1306/porting/branding-feature
- Merge pull request #1413 from Mayurkumar144/porting-group-device-#1136
- Merge pull request #1425 from parkbenchsolutions/porting/437-viewable-service-packs
- Merge branch &#39;develop&#39; into porting/426-delete-group-service
- Merge pull request #1428 from parkbenchsolutions/porting/426-delete-group-service
- Merge pull request #1433 from parkbenchsolutions/porting/branding-module
- Merge branch &#39;porting/417-porting-group-user-bulk-feature&#39; into resolve-conflicts
- Merge pull request #1435 from parkbenchsolutions/resolve-conflicts
- Merge pull request #374 from parkbenchsolutions/resolve-conflicts
- Fix nocs and routing profile
- Group calling plan feature changes
- Merge branch &#39;group-user-feature&#39; of https://github.com/anshuporwal01/odinweb into group-user-feature
- Remove unwanted variable
- Remove unwanted codes
- Group bulk service changes
- Merge pull request #1436 from anshuporwal01/group-user-feature
- Merge pull request #375 from parkbenchsolutions/develop
- Changes for routing profile
- Fixes for unwanted code enlist error
- Test
- Remove unwanted files
- Merge pull request #1437 from anshuporwal01/eslint-fixes-odin
- Added email templates service and component, so far can render the templates and post a single template.
- Delete functionality is working
- .
- .
- I&#39;ve added a validateName function that will check to see if the name has been used need to implement functionality that stops user from posting in form
- Merge pull request #376 from parkbenchsolutions/develop
- Changed disable save based on if action is edit or add
- Service provider admin service
- Admin services
- Branding alias -sp - admin
- Chages for sp admins
- Form autocomplete issue
- Merge pull request #294 from parkbenchsolutions/develop
- Merge branch &#39;develop&#39; into porting/423-porting-group-service-pack
- Utilities service
- Administrator service changes
- Remove fle
- Merge pull request #1449 from anshuporwal01/service-provider-admin-service
- Put doesn&#39;t fully function, still needs to change based on a unique value
- Merge pull request #1412 from parkbenchsolutions/porting/417-porting-group-user-bulk-feature
- Merge branch &#39;develop&#39; into porting/480-porting-enterprise-administrator
- Merge branch &#39;develop&#39; into porting/423-porting-group-service-pack
- Tag value allow null on add
- Merge pull request #1460 from parkbenchsolutions/bug/694-tags-not-functioning
- Changed ecn requirement from v23 to v22
- Ecn v22 support
- Merge pull request #1461 from parkbenchsolutions/bug/707-ecn-bwksV22
- Merge branch &#39;develop&#39; into porting/480-porting-enterprise-administrator
- Added some useState and imported lodash added a cb fn for editing
- Merge branch &#39;develop&#39; into porting/423-porting-group-service-pack
- Merge pull request #1430 from parkbenchsolutions/porting/423-porting-group-service-pack
- Merge pull request #1450 from parkbenchsolutions/porting/480-porting-enterprise-administrator
- Merge branch &#39;develop&#39; into feature/email-branding-templates
- Fixed bug with department create permissions
- Merge pull request #1462 from parkbenchsolutions/bug/708-department-add-not-showing
- Removed dupes
- Merge pull request #1463 from parkbenchsolutions/bug/dupe-import
- Merge branch &#39;develop&#39; into feature/email-branding-templates
- Added comment
- Merge pull request #295 from parkbenchsolutions/feature/email-branding-templates
- Feature/email-template-branding
- Merge pull request #1465 from pankajs1306/feature/email-template-branding
- Added tag service, exports, comments &amp; bulk template tag component
- Created comp for ui input tag text area
- Removed not used code
- Removed unused code
- Changed name of component, updated UI
- Removed refetch on focus from useQuery
- Merge pull request #1466 from parkbenchsolutions/feature/email-branding-templates
- Merge pull request #1469 from parkbenchsolutions/bug/700-hunt-groups-refetch
- Fixed passcode generate tag
- Merge pull request #1473 from parkbenchsolutions/bug/resolve-email-passcode
- Merge branch &#39;develop&#39; into master

<br><br>
## 5.31.1 (2021-7-1)
- fixed api call for access device endpoint contact list

<br><br>
## 5.31.0 (2021-6-21)
**June 21 2021**

**Enhancements**

*   Adjusted UI for adding a new device to user

**Bug fixes**

*   Department admins were not able to access users
*   Feature access codes - Alternate Code column added 
*   Corrected UI for No Answer and Busy settings on user announcements
*   Registration report displays duplicates
*   User device tags only loading on a window refocus

**Upgrades**

*   Group Configuration Service After Hour Menu 
*   Group Configuration Service Business Hour Menu 
*   Group Configuration Service Holiday Menu
*   Department Enterprise Directory
*   Department trunk group settings
*   Group Configuration Services - After Hours menu, Business Hours menu, Holiday menu
*   Trunk Group Hosted User

### Changes 

- Working AA keys
- Group Auto Attendant Menu Keys module working
- AA Fixes
- Auto Attendant after hours menu fixes
- Group auto attendant keys
- Update aa business and holiday settings
- Object assign fixes
- Fixes for autoattendant after refresh page working , case or save button not work
- Fixes delete
- User devices fixes
- Remove unwanted files
- Department dashboard auto attendant
- Department alias fixes
- Grp dept update
- Alias done
- Department alias fixes
- Fixes for delete button #1355
- Delete holiday menu fixes
f2c437aae4082ff00158a6e41813bfce288b6166
- Fixes for submenu keys
- Added additional form validation
- Bredcrum bug fixed
- Porting trunk group setting
- Porting trunk group setting
- Permisison fixes in department
- Breadcrumb issues fixes
- Fixes for: Trunk Group Settings Changes : Existing Issue #1358
- Group meeet me
- Hunt group
- Department - utilities section done
- Meet me breadcrumb issues
- Group department password rules
- Remove delete button from meet me
- User hosted in trunk group
- Auto attendant dialog
- Remove utilities
0bc48f5285b7d739cb9315dc61602c5b762b2bcf
- Test PR
- Fixes for policy issue
- Schedule blank page fixes
- Fixed package version


<br><br>
## 5.30.3 (2021-5-27)
**May 27, 2021**

**Enhancements**
*   Added better descriptions to "Add Auto Attendant" form for drop downs

**Bug Fixes**
*   Auto attendant white screen 
*   Auto attendant console error when deleting an announcement
*   Feature access codes updated with better code to prevent react warnings

**Upgraded to React**
*   Group auto attendant menu

### Patches 

- Alignment issue fixes
- Removed comments from user e911 component
- Announcements console error fixed auto attendant
- Added initial array in useState to fix proptypes
- Feature access code alternate code added
- Updated UiDataTable to better assign keys to maps
- Removed serviceUserId proptype b/c it&#39;s not a prop
- Added userIdSuffix to bulk-tags
- Added a Please Select option to the drop downs -- no blank options now
2797c51bec8871bd031602918791e7533058bd3b


<br><br>
## 5.30.2 (2021-5-22)
Allow device update for SCA bulk actions:

<br><br>
## 5.30.1 (2021-5-21)
Added throwable for user settings

<br><br>
## 5.30.0 (2021-5-21)
**May 21, 2021**

**Enhancements**

*   Added a classname of panelTitle to the panel header on the dashboards to help override the default text with branding
*   Added e911 component to the user level dashboard that redirects to e911 url

**Bug Fixes**

*   Create group admin would redirect to a blank page
*   Group calling plans individual options were not hiding when deselecting in branding, added a fix to hide the options that are not displayed as 'read'
*   Pilot user id is converted to string
*   CLID address can be set to "none" on the group business profile
*   Edit group business profile link fixed
*   Contact name when changing would cause a white screen for group business profile
*   Address input field would cause a white screen when changing on user profile
*   Enterprise dashboard now reflects what policies are allowed per enterprise admin -- business profile was not responding to these changes
*   Trunk group reroute fixed

**Upgraded to React**
*   Group trunk group
*   Group business profile
*   Group Auto Attendant
*   Group Departments

### Minor Changes 

- Announcement service - react-migration
- Group business directory commit code custom phone list
- 378 Porting Trunk Group Front Page #1071
- 378 Porting Department Trunk Group Front Page #1071
- Group business profile 409
- Porting/group-trunk-group
- Revert group meet me user announcement changes , fixes
- Porting/group-trunk-group
- Changes some to admin part for related to duplicate codes and add policy permission to group profile admin
- Added a .filter() to the previously filtered list of modules to determine which module has read: true
- Added e911 settings
- Group auto attendant
- Department parmissions
- Group auto attendant
- 380 Porting Department Trunk Group Call Capacity #1073
- Created a super basic component for e911 that, when visiting, it will automatically redirect to a new tab with the e911 url provided. The component only contains a button that will open a new tab with the url provided. The component, when opened, will make another call the e911 endpoint and dispatch an action to get a new e911 url.
- Added ambulance icon to the user dashboard menu for e911
- Removed the automatic redirect to e911 url
- Added an external link open button at the top of the e911 card component
- Added user address to the e911 component
- Added logic to take away add button in e911 settings that will show up if there are no endpoints available.
- Removed address line 2 from e911 component
- Added each piece of the address to their own line
- Added the main address
- 381 Porting Department Trunk Group Call Forward #1074
- Updated user e911 to better display address
- Group business profile fixes

### Patches 

- Error handling business directory
- Duplicate keys error resolved
- Remove delete button when add new common phone name
- Group business directory changes for getting data
- Alignment of code
- Added panelTitle class to the UiPanelLogo component for branding purposes
- Patched is pilot User Id true or false
- Group-administrator fixes
- Trunk group dashboard
- Porting/group-trunk-group left menu
- Added user settings endpoint
- Set up reducer, menu item that checks for module read, added the api call to the redux store, not fully working yet just committing in changes
- Switching between users shows that e911 menu tab will render if the user has the api call available. Does not display on user zakmayf but does display on revermans user
- Branding Departments #410
- Changed the function to have string values
- Error message fixes
- Added a button to link off page adjusting ui
- Added more space between button and message
- Fixes for: Issue with User Profile Address Input field, redirect to blank page when clicked #1334 Issue with Enterprise Admin Read Policy for Business Profile #1333
- Group business profile fixes select clid number none
- Auto attendant form validation req fields will disable save if not filled in

<br><br>
## 5.29.2 (2021-5-11)
### Patches 

- Patched is pilot User Id true or false

<br><br>
## 5.29.1 (2021-5-11)
syn with api hot fix alternateTrunkAddress

<br><br>
## 5.29.0 (2021-5-7)
### Minor Changes 

- User basic call logs changes #921
- Basic call logs file added
- User service assignment
- 241 Porting User Premium Call Records #922
- User service assignment porting #930
- 318 Porting System Settings Webhooks #1022
- Trunck group bug fixes
- Department dashboard porting
- Porting System Dashboard Settings
- Added bulk-move-user-to-group task
- User-dashboard quick links
- Department services porting
- Department dashboard flexible seating host porting
- Removing group service call from below dashboards
- User-id or delete service user dashboard - react  migration
- Changed name to service for the menu item Account/Authorization Codes
- 406-porting-group-administrator feature react porting
- 266-Group Services in Branding conflicting with individual Service modules #948

### Patches 

- User service assignment porting
- It looks like groups/services/available is getting called twice on each dashboard page load
- Added trash icon and remove function that doesn&#39;t work just yet
- Put the active column in the first column
- Moved Active to Left Better UX
- Changing array notation to dot notation
- Fixes user-dashbaord resources
- User-dashboard- remove unwanted var
- It looks like groups/services/available is getting called twice on each dashboard page load #1041
- Updated busy settings
- Same changes for No Answer as are for Busy Settigns
- Pretty much the same changes as busy and no answer just another piece of logic is used for a checkbox to display data as well
- Added column/cards show/hide
- Update user-voice-messaging-greetings.js
- Edit policies service
- Service Pack created with / are not visible as soon as created on Enterprise dashboard. #1128
- User id delete service
- User delete redirection
- Fix the removal of Call Center Settings when mored Call Center is removed from branding.

<br><br>
## 5.28.2 (2021-4-21)
### Patches 

- Created flexibility and efficiency for odin system settings.

<br><br>
## 5.28.1 (2021-4-14)
5.28.1

<br><br>
## 5.28.0 (2021-4-14)
### Minor Changes 

- Update UI for webex integration
- Webex OAuth2 integration
- Add color to Webex success icons.

<br><br>
## 5.27.0 (2021-4-12)
## **March 23rd 2021**

**Enhancements**

1.  Form validation added to Sip Trunking features
2.  Added user names to call center agent queue

**Bug Fixes**
1.  Pagination causing a log out to occur
2.  Issue with editing Basic Call Center as admin levels

**Upgrades to React**
1.  User Call Center
2.  User Devices
3.  User Password
    *   Passcode rules to change (text/password) click on eye icon.
    *   On user level fixed generate passcode rules six digits.
4.  User Viewable Service Packs
5.  Voice Messaging User
6.  User Hoteling Host
7.  User Hoteling Guest
8.  User Basic Call Logs
9.  User Phone Numbers
10.  User Announcements

<br><br>
## 5.26.8 (2021-4-8)
### Patches 

- Fixed user department inventory
- Added check for allow password reset username

<br><br>
## 5.26.7 (2021-4-6)
sync with api

<br><br>
## 5.26.6 (2021-4-6)
sync with api

<br><br>
## 5.26.5 (2021-4-5)
Added details to users and groups inventory: 095a72b

<br><br>
## 5.26.4 (2021-4-2)
### Patches 

- Moved to jobs from events to process data
- Added jobs for inventory

<br><br>
## 5.26.3 (2021-4-1)
### Patches 

- Added retry queue

<br><br>
## 5.26.2 (2021-3-31)
### Patches 

- Added agent unavailable code for user access
- Added integrated IMP callback migration
- Refresh session token before token check

<br><br>
## 5.26.1 (2021-3-24)
Added service provider trunk group call capacity to inventory api: 5ed4b60
Added group trunk group capacity to inventory api: 89a778a

<br><br>
## 5.26.0 (2021-3-23)
### Minor Changes 

- Flexible seating host
- User hoteling host service
- Flexible Seating Guest group service porting into react only front page
- Flexible seating host guest association tab porting into react
- Flexible seating host guest association tab porting into react
- Flexible seating host user tab porting into react
- Flexible seating host routing policies
- Flexible seating host guest association tab porting into react
- Flexible seating host port routing policies into react
- Port incomming calling plan into react in flexible seating host service
- In group service flexible seating guest have implement number and device tab, incomming calling plan, routing policies into react
- User profile tab ported into react in user dashboard also add api file and write all api&#39;s
- User calling plan porting into react
- Issue fixed for user login
- Fixes for: bulk sip trunking
- Fixes for sip trunking user
- User calling plan porting into react
- Handle AIM reseller branding and fix blank page issue
- Fixes - emergency call notification settings fixes, system, reseller and service provider level
- Added lastname, firstname to select supervisors
- User calling plan changes are done using pointer cursor when delete authorization code
- 263-user-voice-portal-calling
- Call center fixes more time click on popup populated - #686

### Patches 

- Agent unavailable codes fixes
- Update/delete profile in flexible seating guest (number and device)
- Flexible seating host device and number
- Flexible seating host profile tab and device and number tab porting

### Minor Changes 

- Voice portal calling callback
- Added voice portal calling callback and api v1 support
March 23rd 2021
 

### Enhancements

- Quality of life updates for Sip Trunking small component enhancements and tweaks
- Added a new feature: Voice Portal Calling
- Created a new callback for Voice Portal Calling - can be turned off to set Voice Portal Calling to inactive when assigning it or vice versa
- Agent unavailable codes was added as a service
- Added Emergency Call Notification to SYS/ENT/SP/GRP Dashboards for BroadWorks version 23.
 
### Bug Fixes

- Small typo fixed when searching for any service/user/ect.
- VDM quick link no longer displays on dashboard if it is not active
- Corrected display of select supervisors from assigned agents for call centers to LastName, FirstName to (previously displayed as "FirstName, LastName)
- Emergency call notification service no longer displays blank screen
- Removed AIM from displaying twice in the left hand menu
- Agent Unavailable Codes - fixed form submission error
- Agent Unavailable Codes - UI bug fixed involving the active switch button
 
### Upgrades

- User flexible seating host has been upgraded to React.
- User Calling Plans Auth Codes has been upgraded to React
- UI has been updated to include Required * fields
- UI has been updated to change cursor to "pointer" when hovering over delete code button
- Flexible Seating Guest has been upgraded to React
- User Profile has been upgraded to React.
- CLID names can no longer be updated as a User level login
- Required fields now have a * to indicated which are required

<br><br>
## 5.25.0 (2021-3-17)
### Minor Changes 

- Flexible seating host
- Flexible seating host guest association tab porting into react
- Flexible seating host user tab porting into react
- Flexible seating host guest association tab porting into react
- Looks like groupServiceData is an object rather than an array.

<br><br>
## 5.24.0 (2021-3-17)
### Minor Changes 

- User/group meet me conferencing service enhancement with information
- User meet me conferencing updated and save records with fixes - #872
- Fixes for user meet me conferencing - #872

<br><br>
## 5.23.0 (2021-3-17)
### Minor Changes 

- User fax messaging service
- Disabled condition applied even if no phone number - fax-messaging service

<br><br>
## 5.22.8 (2021-3-16)
### Patches 

- Changed the typo sentence from *Nothing Foundfor* to *No Results Found For: ...*

<br><br>
## 5.22.7 (2021-3-16)
### Patches 

- Fixed Reseller Dashboard menu, it now contains Ent route

<br><br>
## 5.22.6 (2021-3-16)
### Patches 

- Fixes for #906 Previous angular logic was &quot; if module is not exist in the modules array then default permissions are { create: true, read: true, update: true, delete: true } &quot; Changed this logic to &quot;default permissions to { create: false, read: false, update: false, delete: false }&quot;

<br><br>
## 5.22.5 (2021-3-11)
sync with api

<br><br>
## 5.22.4 (2021-3-11)
sync with api

<br><br>
## 5.22.3 (2021-3-11)
sync with api

<br><br>
## 5.22.2 (2021-3-11)
sync with web

<br><br>
## 5.22.1 (2021-3-11)
sync with api

<br><br>
## 5.22.0 (2021-3-11)
sync with api

<br><br>
## 5.21.1 (2021-3-11)
no change

<br><br>
## 5.21.0 (2021-3-9)
### Minor Changes 

- Executive service permissions
- Active / deactive criteria name from filtering
- Fixes - undefined messageSourceSelection - music on hold files

### Patches 

- Branding assistants
- Disabled button message
- Space between music on hold , fixes for helpModule={&lt;AppHelp module=&quot;Alternate Numbers&quot; /&gt;} instead of helpModule={&lt;AppHelp module=&quot;Speed Dial 100&quot; /&gt;}
- Space between cards - music on hold

1.  More spacing in user Music On Hold into file 'src/components/users/service-settings/user-music-on-hold.js' line number 180, 201, 204, 221. 

2. Change the helpModule  ="Speed Dial 100" 
 instead of  helpModule = "Alternate Numbers"  into file 'src/components/users/service-settings/user-alternate-numbers.js' line number 129.

3. Add line  'export * from ./user-executive/user-executive-index' into root file 'src/components/users/service-settings/index.js'
Line number 30.

4. Add module name line 'UserExecutiveIndex' in file 'src/components/users/user-service-routes.js'
line number 27.
with component details 
{
	component: UserExecutiveIndex,
	module: 'Executive',
	path: 'executive',
	services: ['Executive']
}


<br><br>
## 5.20.3 (2021-3-9)
sync with api

<br><br>
## 5.20.2 (2021-3-4)
sync with api

<br><br>
## 5.20.1 (2021-3-3)
### Patches 

- Created files for the group phonism devices
- Filterd devices by macaddress
- When clicking on a device it now routes to the proper page
- Added a lib react-iframes. decided not to use react-iframes and just use a basic iframe tag. the html is rendered with the iframe and loads fine. now going to go through and refine the code.
- Added an iframe that takes the phonism gui and displays it to the screen
- Added a way to close the gui
- Added margin via a &lt;br/&gt; will need to change this
- Fixed proptypes errors
- Added a string method into this useState update hook so that way any mac address coming into the componenet is a string and not a number
- Added a dynamic title to the gui display changed some of the naming
- Created a loadConnectors method inside of group-dashboard that will load the available connectors -- created a connectors dir that contains connector-service.js that dispatches an action to grab connectors
- Updated axios from 0.19.0 to 0.21.1
- Fixed a conflict with the yarn.lock regarding axios
- Added hasConnector: phonism in dashboard menu and then commented out

<br><br>
## 5.20.0 (2021-3-3)
### Minor Changes 

- Virtual on net group service add and listing screens
- Virtual on net service
- On net service delete
- Added * to Type required field
- Frontend form validation

### Patches 

- Blank screen issue fixes validation
- Changed &quot;None&quot; to &quot;Select&quot;

<br><br>
## 5.19.9 (2021-3-3)
### Patches 

- #867 service calling plans changes
- Group Calling Plans Menu Fix

<br><br>
## 5.19.8 (2021-3-3)
### Patches 

- Alternate numbers
- Alternate numbers fixes
- Fixes for user login type phone numbers
- Alternate Numbers TN field caused logout on User login

<br><br>
## 5.19.7 (2021-3-3)
### Patches 

- User profile branding
- User can no longer edit profile if user profile is only set to read in branding

<br><br>
## 5.19.6 (2021-3-2)
### Patches 

- Moh
- Music on hold for group ported from angular to react

<br><br>
## 5.19.5 (2021-3-2)
### Patches 

- User music on hold
- User music on hold: added announcements to music on hold user

<br><br>
## 5.19.4 (2021-3-2)
### Patches 

- Breadcrumb issue fixes #783
- Change path name
- Group Call Park Breadcrumb fixed to insert correct serviceProviderId and groupId

<br><br>
## 5.19.3 (2021-2-24)
### Patches (API SYNC)

> fixed the json post to phonism where the options are being sent down as a json array of options to phonism client

```php
$res = $this->client->request($method, self::$URL . $url, ['json' => $options]);
```



<br><br>
## 5.19.2 (2021-2-24)
# odin-api release notes

## Mac Address Fix (2021-02-24) (5.19.2) 

>fixed the response of *macAddress* integer to string for macAddresses with only numbers.
>
>This impacted all levels of devices **System**, **ServiceProvider** and **Group**  *devices*.
>
>Example: *macAddress*: **556688995566** is now *macAddress*: **"556688995566"**

Before

```json
{
    "serviceProviderId": "ent.odin",
    "groupId": "grp.odin",
    "deviceName": "1000_1_grp.odin",
    "deviceType": "Polycom VVX 500 DM",
    "protocol": "SIP 2.0",
    "macAddress": 556688995566,
}
```

After
```json
{
    "serviceProviderId": "ent.odin",
    "groupId": "grp.odin",
    "deviceName": "1000_1_grp.odin",
    "deviceType": "Polycom VVX 500 DM",
    "protocol": "SIP 2.0",
    "macAddress": "556688995566",
}

```

<br><br>
## 5.19.1 (2021-2-23)
sync with api

<br><br>
## 5.19.0 (2021-2-23)
sync with api

<br><br>
## 5.18.0 (2021-2-23)
### Minor Changes 

- Bump immer from 7.0.9 to 8.0.1
- Meet me setting user
- Meet me announcement
- Sip trunking user
- Comm barrring in meet me conferncing
- Added user executive-assistant service
- Select no new component
- Select phone number
- Call center service search 787
- Call center utilities and call policy service with pre alerting service changes
- User service settings changes
- Added call center monitoring tone
- Set none value
- Fixed incomming calling plan verbage
- Changed password rules to default to unchecked when cloning SP&#39;s and groups
- Paging fixes
- Group numbers changes
- ServiceUserId searching fixes with domain
- Group flexible seating host pre-alerting service fixes
- Fixes first and last name search in table #794
- Sip trunking user creation
- Added user portal passcode task name
- Fixes
- Added the active column to the left hand side
- Commented out a cell style of &quot;nowrap&quot; so that way the text will wrap
- Removed the wrap text -- only Active column is moved
- #836 fixes
- #836 fixes , lastName,FirstName and userId
- Nav search collaborate audio fixes related to #787
- Group numbers collaborate audio list
- Added Emergency Call Notification to Group, Reseller and System
- Added adjustments to the ecn ui that added the checkbox next to the input field, also adjust the styling on our UiInputCheckbox component ethat will align the checkbox with the label
- Added a div to separate the common fields on the SP ECN screen to allow better styling
- Changed save button to be disabled if form is empty on System level
- Group ECN save button disabled if no email provided
- Reseller ECN save disabled if email input is empty
- SP ECN save disabled if email input is empty

<br><br>
## 5.17.1 (2021-1-29)
sync with api

<br><br>
## 5.17.0 (2021-1-28)
### Minor Changes 

- Statitics
- Fixes for: Password in Group Paging Profile : Do we need this?? #636
- Fixes for : UI: Service Provider Call Processing Policies #478
- Group paging issue fixes #779
- Hunt group issue fixes
- Hunt group breadcrumb and service assignment issue fixes
- Searching issue fixed for hunt-group
- Call park fixes creating
- Fixes hunt group agent different page breadcrumb
- Branding delete hunt- group
- Fix for: BreadCrumb Auto Attendant meet me bridge
- Hunt group and other services feature access code
- Call park users load fixes
- Added user.update task
- Changes done call disposition code fixes
- Added password rules to clone
- Call processing policy
- Call processing policy ent
- Meet me conferencing service fixes
- Group meet services
- Group meetme confrencing service
- Group meet me conferencing service
- Changes are done for replace userId to serviceUserId
- Changes for user incomming calling plans

<br><br>
## 5.16.0 (2021-1-19)
### Minor Changes 

- Call centers link
- Call center routing
- Call center announcements list
- Sp enterprise tabs
- Call center announcements list
- Filter enterprise panel
- Enterprise link dashboard
- Dashboard left menu items
- Message for clone
- Service-provider-schedules
- Group Schedule porting on react and Separate Schedules(Enterprise Schedules - Group Schedules) on Group Level Schedules #718
- Separate Schedules(Enterprise Schedules - Group Schedules) on Group Level Schedules #718
- Group level schedules
- Service provider schedule UI Enhancement
- Schedules enhancement
- Bump axios from 0.19.2 to 0.21.1
- Routing call center
- Added voice messaging bulk task
- Fixed verbage on tasks
- Agent unavailable codes #686
- Intercept group active/deactive fixes #749
- Issue when using Service Provider Schedules on Group/User Level #730
- Utilization Report Numbers #750
- Fixes for enhance reporting settings
- Utilization Report Numbers #750
- Not able to change Active Status of Criteria(Sequential Ring &amp; Simultaneous Ring Personal) #764
- Emergency Call Notification #754

<br><br>
## 5.15.1 (2020-12-21)
sync with api

<br><br>
## 5.15.0 (2020-12-21)
### Minor Changes 

- Dnis
- Call center calling plan
- Pre Alerting Virtual Services (Call Center) #695
- Hunt group create issue, removed spaces
- Added isDnAssigned check to user create
- Fixed character
- Removed serviceProviderId and groupId from input password lookup for audit
- Loading issue on hunt group similar as call center 711
- Loading issue for group paging(similar as 711)
- Fixed portal passcode auto generate for aim
- Alternate User ID - User portal #670
- Page Music On Hold User goes blank after some time #619
- Added clone schedules at sp/enterprise level
- Error when assigning Schedule to User Service(Call Forwarding Selective) #716
- Schedule fixes
- Call center premium dnis add issue #728
- Enterprise Admin Login and Policies #733
- Query key for music on hold

### Patches 

- Thresholds
- Calling plan
- Fixed creating a hunt group without department
- Also when the modal for adding the service is pulled up it keeps making calls back to API server to get the same information over and over again. Please fix this as well
- Change array notation to dot notation
- Reverting code for alternate user id

<br><br>
## 5.14.2 (2020-12-3)
### Patches 

- Call center call dnis
- Call center dnis announcement
- Calling plan branding
- Group paging pre-alerting service fixes
- Group paging changes

<br><br>
## 5.14.1 (2020-12-1)
### Patches 

- Group Emergency Zones #477

<br><br>
## 5.14.0 (2020-11-30)
### Minor Changes 

- Bulk password rules bug #642
- Bulk password generation
- Call park group and pickup issue fixes #668
- Space issue fixes call-park and call-pickup
- Space fixes in group and users level
- Call-center line spacing
- Broadwork anywhere fixes
- Call center thresholds
- Hunt group pre-alerting service
- Remove unwanted comment and query chache key purals
- Hunt-group querychache key changes
- Group Call Processing Policies SLOW and ERROR #672
- Fixed spelling in agents and thresholds

### Patches 

- Merge branch &#39;bug-fixes-pankaj&#39; of https://github.com/pankajs1306/odinweb into bug-fixes-pankaj
- Thresholds

<br><br>
## 5.13.6 (2020-11-18)
### Patches 

- Call-center-supervisor fixes#418
- Query cache problem fixes
- Bulk User Wizard Service Pack Limit Bug #665
- Added fix for service instance profile update call center

<br><br>
## 5.13.5 (2020-11-13)
Sync with API

<br><br>
## 5.13.4 (2020-11-11)
sync with api

<br><br>
## 5.13.3 (2020-11-11)
### Patches 

- Call center to react:
- !Password Change Issue! 
- Call center password rule:
- Password and password rules:
- Made My Account default to the right hand side but allow custom css to switch it:
- Password issue fixes for virtual users:
- Passcode rule fixes:
- Password for add user:
- Set up canUpdate to check permissions and link to the user clicked:
- Fixed the loading bug on User Reports:
- Can now load / travel to selected user:
- User registration head was fixed on user portal:
- Enterprise trunk:
- Password generation api implementation:
- Call center utilities:
- Call center call policies:
- Call center call policies:
- Passcode default length for user logged in:
- Panel &#39;Migrate&#39; link is now working as intended:
- Added a new panel that holds all of the AIM links:
- Fixes for #656 showing vdm provisioning left menu items:

<br><br>
## 5.13.2 (2020-10-30)
sync with api

<br><br>
## 5.13.1 (2020-10-30)
### Patches 

- Changed header navbar title to a more neutral color and increased the font-size by a small amount.
- Added a couple of id&#39;s to the reset password and forgot password links so they are targetable in custom css template. Colors are now different from background so they now are viewable
- App navbar fix
- The normal small menu now takes the categories and creates menu items for them. My Account is now the first item in the list of quick links.
- Added a classname to the fat menu to easily target for styling. added a couple of styles in the index.scss to help with padding and margin issues. increased the sise of the fat menu so there is more space in between the quick links
- Added margin on the navbar to put space between the logo and the name of the application. created a more spacious fat menu that has more space between quick links.
- Call park and call pick up
- Routing Profile will be available for Reseller admin
- Added some margin on the logo and the application name to space it out a bit more evenly.
- FirstName and lastName group user registration bug fix
- Added a classname to the end of the small menu so i could target it to add some margin to the right so the dropdown no longer flows off page
- Added gilroy font
- Added font to all a and p tags
- Added a meyers selecttion reset to apply Gilroy-Light to everything on the app
- Added ol and ul to the reset
- Fixes show migrate
- Sp level alias
- Default font to helvetica, with custom css they can change to gilroy
- Service provider export fixes

<br><br>
## 5.13.0 (2020-10-23)
### Minor Changes 

- User call processing policy
- Group voice messaging
- Group collaborate
- Group account auth code #444 enhancement
- User and Group Call Processing Policies #435
- Auth code new #568 fixes
- Changed the menu lables to be default Caps instead of UPPERCASE this can be changed with custom css template -- also changed the footer to have a height of auto instead of 50px
- Account auth code group dashboard showing
- Default tab selection: call processing policy
- Added a ui fat menu and a cbts navbar component
- Created two separate components for the navbar to allow individual styles on each
- Added branding for top menu bar
- Item missing in &quot;Numbers &amp; Devices&quot; section for Group Admin Access(Only on Demo 23) #534
- Blank screens fixes migrate and imports #567
- Fixes 425 show left menu trunk call capacity
- Calling Plans missing Management dashboard. #611
- User can now select large menu style that will apply a fat menu on to their navbar, insdie of the custom css they can add specific colors and boldness to text

### Patches 

- Removing eslint warnings
- User-call-processing-policy : &quot;Call Limits&quot;
- Hunt group redirection
- Added two constants for menu title and menu size
- Tab issue fixes due to changes done on tab common component
- Sys admin audit module fixes
- Trunk group redirect fixes done if login first time
- Add space b/w pannels - administration
- Adding spaces auth codes
- Rename modal title name users
- Change in default selected tab in UiTabs component, tested in for all react tabs, tabs working fine
- BroadWorks Anywhere Criteria should be only visible when at least one phone number

<br><br>
## 5.12.0 (2020-10-16)
sync with api

<br><br>
## 5.11.5 (2020-10-16)
### Patches 

- Set up empty component for call forwarding history
- Added some content to the history component, hard coded strings  will be removed and replaced with variables
- Added an import for the history component to the ucfa component. set up a react-query call to make a call to the events endpoint filtering by the userId -- right now it is commented out to prevent a lot of calls to the API -- soon will add a more dynamic approach to the axios call by creating a history service file
- Changed the token to be accessing the localstorage token rather, will change this to be more dynamic eventually
- Added a call forwarding history service, in process of setting up api.show on the history side
- Changed the limit query
- Some more updates on history service
- Created a ui-accordion component that takes data and displays a diff of the changesfrom before and after. as of now it only really is reliable for the call forwarding always component but it gets the job done. still need to add a few things to make it fully functional
- Pop out menus now working when clicking the ellipsis
- Full functionality for selecting a previous history with accordion dropdown
- Took out an unneccesary line
- Took out unused variables
- Cleaned up scss file and a bit of the accordion component
- Added consistensy between the history tabs and the cfa card above
- Added useMutation hook but it&#39;s still not refetching on the update of CFA working on it still: - Tried to implement the useMutation hook but to no success
- Took away colons and changed the text of the Forward to Phone Number for better consistensy: - Changed to appropriate proptypes
- Updated react-query dependency, histories now update as a new PUT goes through to change their status of CFA: - Set a fake delay on the save edit that will help with the refetch of the cache. will try to move it off of a fake timeout eventually.: - Testing the invalidatingQueries method
- Added note to change title back to date
- Updated comments
- Trying to set up a way to update the histories
- Added a setTimeout to the useMutation hook to allow the user to update their history on edit
- Changed the title of the accordions to the date stamp, using the full date and time. Made it prettier by spacing it out and making it a bit more readable
- Cleaned up comments
- Added username to the title of the accordions
- Added an informative tooltip to tell the user that their update may not reflect in the history for a few minutes: - Updated spacing: - User-pre-alerting service fixes done expected api issue
- Took out unused style
- Putting the conversion to local time on the back burner to work on decoupling some of the code to make it a more reuseable component
- Moved some of the beefy functions under the component to take up less space
- Pulled the hardcoded method &#39;invalidateQueries&#39; into it&#39;s own function in the history service which allows any component to call the invalidate queries on the history
- Pulled out all of the hard coded queries into the history service located in a generate history queries fn startDate and endDate are not yet dynamic but are in the starting phases of being changed
- Search functionality partially works. I can&#39;t seem to narrow the search down on any other day rather than the current day
- Implemented a drop down calendar to allow the user to select a range of dates to filter histories
- Took out some unused variables
- Removed unused comments and code
- Branding module permissions
- Password rules service
- Group passworld rules services
- Service provider password rules
- Password rules
- Reset password rules
- Breaking functions into smaller peices to make them more reuseable
- Removed unnecessary methods inside of the history service file and created a more reuseable index method that takes a url and a set of parameters
- Created an events api library for the CFA History. Moved all of the API calls out of the history-service.js Now the CFA History component is referencing the api from the events and providing it all of the data that it needs in order to show the correct histories
- Service provider branding groups
- Change group services api path and night forwarding
- Branding data changes
- Event history permissions
- Sp barnding settings changes
- Removed unused comments
- Formatted the code
- Git status
- Moved some of the varibales underneath the state so it has access to it
- Reverted some changes back
- Remove unwanted code
- Group collaborate audio
- Group collaborate audio
- Group collaborate audio
- Pre alerting
- Password rules changes
- Removed cfa-history-service and made it more generic with a /api/common/invalidate-queries that takes a user id and a query cache key that invalidates the queries asked for. change the api call on cfaHistory to eventsApi to make it more clear that we are using the api from the events. also changed the name of cfaApi to just api to make it more consistent between cfa and cfaHistory.
- Reverted the package.json back to its original state - only updated react-query
- Changed a comment to me a bit more informative
91ac2e2594353380f47c6f08cda5fed5492bc4ea
- Collaborate audio
- Collaborate audio
82b1b005cc5978f488958c4c496b240616e9fc5f
- Collaborate audio
- Visual voice messaging, react query fixes
- Collaborate audio
- Removed the configs for useQuery in voice-msg-checks.js so that now Visual Voice Mail is being displayed on the menu
- Collaborate audio
- Collaborate audio
- Revert visual voice messaging
- Group api path changes
- !!!visual voice mail not showing up!!! #576
- Group collaborate
- Group collaborate
- Changes for event history
- Added forgot password and reset password template show/hide
aa17ff922e370e982451cd10890d439ecb3acedc
- Forgot and reset password permission
- Forgot and reset password permission
- Forget password
- Remove unwanted code
- Changes replace permission for ent trunk group
- Fixes
d170ea09d6f11f49d364d0a04d5214993d3b59d7
- Password reset for reseller fixes #551


<br><br>
## 5.11.4 (2020-9-30)
syny with api

<br><br>
## 5.11.3 (2020-9-29)
### Patches 

- Çall park api axios
- Call pickup api axios
- Call park group service
- Add Event Type selectable filter for search event history #526
- Night forwarding group api axios
- Event-type-filter
- Added domains to bulk template example for enterprise clone
- Bulk User Service Update from spreadsheet #564

<br><br>
## 5.11.2 (2020-9-25)
### Patches 

- Fixed the download issue where file has no extension

<br><br>
## 5.11.1 (2020-9-25)
### Patches 

- System reset profile password service
- Change password system admin rule
- Adding loader in voice mail

<br><br>
## 5.11.0 (2020-9-25)
### Minor Changes 

- Sp branding menu
- Service provider level branding changes
- Service provider add branding permissions
- Service provider branding apply
- Change acl for provisioning audit, migrate,imports
- Service provider branding apply menu items with policy
- Rename name sp level directory to business directory
- Visual voice mail #496
- Sp level delete branding permissions
- Changes for system level branding permissions
- Changes for delete sp
- User id. or delete option is missing and enabled in branding module #545
- Delete service provider hide if no permission for barnding read
- Visual-voice-mail

### Patches 

- Call pickup
- Group call pickup
- Delete sp level branding checkbox disabed
- Fixes for disabled branding in a method
- Removing lint issue

<br><br>
## 5.10.17 (2020-9-16)
### Patches 

- Sca changes System level device can not be modify by Ent/Group Admin
- Permission for device sca module
- Phone number fixes for users
- CSV Download has JSON Object instead of json String #485
- Branding issue Group Calling Plans #529

<br><br>
## 5.10.16 (2020-9-11)
### Patches 

- Call forwarding selective service
- Switch button fixes
- Call to number add in call forwading salective
- Add group policy permission on group level devices feature


<br><br>
## 5.10.15 (2020-9-9)
sync with api

<br><br>
## 5.10.14 (2020-9-9)
### Patches 

- Service broadworks anywhere porting to react
- Broad works anywhere service
- User announcement branding service
- Meet me confrencing and schedule permission
- Alternate user id
- User profile service
- Account auth code
- User id delete , calling plan
- Viewable packs , shared call appearance
- Shared call appearance
- Number and service packs service
- Device endpoint branding permission
- Persional phone list service
- Service user registration
- User service settings authentication and announymous call rejection
- Broad work mobility service
- User service permission branding
- Voice messaging service changes
- User service dashboard branding
- Collaboarate audio service
- Call forwarding selective
- Permission call center
- Viewable service pack module name
- Digit plan outgoing permission
- Transfer service
- Changes branding permissions
- Fixes branding permissions
- Fixes barge services
- Bug fixes in group services
- Call forwarding selective done
- Branding issue fixes
- Group Dashboard policy issues #482
- Bulk provisioning branding
- User bulk changes
- Call me now fixes
- Comm barring
- Renamed Skip on  no answer to Skip to next agent for hunt group
- Device settings icon
- Sca fixes
- Broad works anywhere
- Group Service Configuration Menu Bug #507
- Basic call logs

<br><br>
## 5.10.13 (2020-9-1)
### Patches 

- Fixes for: Event History #462
- Event history search
- Basic call logs fixes

<br><br>
## 5.10.12 (2020-8-27)
sync with api

<br><br>
## 5.10.11 (2020-8-27)
### Patches 

- Branding permission implementation
- Group admin branding
- Fixes for viewable service pack
- Group devices branding permissions
- Device configuration
- Group access code
- Changes feature access code
- Group-dashboard-permission
- Group schedules hover service changes
- Schedule event fixes
- Fixed the multiple odin support forms
- Fixed appendChild to append
- Fixed password expired days ago

<br><br>
## 5.10.10 (2020-8-26)
### Patches 

- Add service packs and users services to user create wizard #450

<br><br>
## 5.10.9 (2020-8-21)
### Patches 

- Fixes for : When turning off read access at the group level for &#39;User Bulk Features&#39; - the panel still shows up on the Group Dashboard.

<br><br>
## 5.10.8 (2020-8-20)
### Patches 

- Group Series completion loading fixes

<br><br>
## 5.10.7 (2020-8-20)
### Patches 

- Service Provider Admin Policies Error #453
- User authentication auto generate not working #451
- Authentication for user logged in

<br><br>
## 5.10.6 (2020-8-20)
Initial release

<br><br>
## 5.10.5 (2020-8-20)
### Patches 

- Fixed group dashboard services

<br><br>
## 5.10.4 (2020-8-18)
### Patches 

- Porting Selective Call Rejection to React
- Fixes for: always getting error on key duplicate, on console..... added some unique keys
- Simultaneous ring personal service
- Code indentation and formatting
- Simultaneous ring personal service changes
- Sequential ring service
- User guest service tab
- Porting : Call Notify
- Removed odin support from service provider dashboard menu
- Fixed alert danger messages for CFA
- Added lastName firstName user agent to user registration
- Group dashboard, alias fixes
- Changed menu
- Added group dashboard panel logos
- New menu development
- Network Class of service
- Network Class of Service
- Branding fixes
- Added user panel logos and group provisioning and user bulk services
- Added branding template for user dashboard quick links panel
- Header logo fixes
- Adding policy check on Group Dashboard
- Group dashboard license split into two
- Changed password to newPassword in sip auth password change

<br><br>
## 5.10.3 (2020-8-4)
### Patches 

- Add Page to show User registration #432
- Add Page to show User registration #432
- Authentication Service - Password Complexity #436
- Changed to user-call-recording to &#39;user-authentication-service&#39; + userId

<br><br>
## 5.10.2 (2020-8-3)
sync with api

<br><br>
## 5.10.1 (2020-7-29)
sync with api

<br><br>
## 5.10.0 (2020-7-29)
### Minor Changes 

- User service phase 3 setup
- Info details user-service-setting-phase-3
- Busy lamp fields service added
- Collaborate audio
- React porting : Priority Alert, with call to number implementation
- Set Permission to Priority Alert
- Push to talk service
- User privacy service
- Speed dial 100
- Ui New Tabs component
- Add permission push to talk
- Moved password below calling features
- Added group dashboard page
- Enterprise dashboard home page is back
- System dashboard has been re-added
- Added module and acl support to system dashboard

### Patches 

- Fixes for callsToNumber property in API
- Switch button fixes using bulma css
- Blf fixes
- Blf user service changes permission
- Arrow function in user services all
- Reseller Breadcrumb link needs corrected #422
- Speed Dial 100 Help text correction

<br><br>
## 5.9.36 (2020-7-23)
sync with api code release

<br><br>
## 5.9.35 (2020-7-22)
### Patches 

- Add user portal passcode and password reset to home page #424

<br><br>
## 5.9.34 (2020-7-20)
sync with api

<br><br>
## 5.9.33 (2020-7-9)
### Patches 

- Call Center Configuration Issue - Stranded Calls #414

<br><br>
## 5.9.32 (2020-7-8)
sync with api

<br><br>
## 5.9.31 (2020-7-8)
sync with api

<br><br>
## 5.9.30 (2020-7-8)
sync with api

<br><br>