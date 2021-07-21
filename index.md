
# API Current Release <small>([View All](/API.md))</small>
## 5.32.1 (2021-7-21)
### Patches 

- Fixed semi-colon

<br><br>
# Web Current Release <small>([View All](/Web.md))</small>
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

  