# API Latest Releases
## 5.34.20 (2022-2-4)
### Patches 

- Allow enforce association limit hours up to 999
- Fix ui-data-table searching on dot notation colnames
- Return a more helpful error on bad userid in task
- Improve error message instruction

<br><br>
## 5.34.19 (2022-2-4)
### Patches 

- Check serviceInstanceProfile for a phone number if mapping
- Expand phone number matching for service instances
- Add featureaccesscode exclusion
- Also exclude featureaccesscode for groupsettingsminimumtemplate

<br><br>
## 5.34.18 (2022-2-4)
sync with web

<br><br>
## 5.34.17 (2022-2-3)
sync with api

<br><br>
## 5.34.16 (2022-2-3)
Sync with web
- fix auto attendant call detail report

<br><br>
## 5.34.15 (2022-2-2)
### Patches 

- Added check for r24 login

<br><br>
## 5.34.14 (2022-2-2)
### Patches 

- Fix Webex API URL setting

<br><br>
## 5.34.13 (2022-2-1)
### Patches 

- Add clustered database param for audit
- Add database param to template call
- Clustered db lookup for imports
- Bulkable events tweak + group device bulkable
- Bulkable group device deletes
- Display any errors in the task
- Pass along attributes to dispatched events

<br><br>
## 5.34.12 (2022-1-28)
### Patches 

- Fix Altnernate User Id issue for Group Admins

<br><br>
## 5.34.11 (2022-1-26)
added group services only audit
adde user only audit

<br><br>
## 5.34.10 (2022-1-21)
sync with web

<br><br>
## 5.34.9 (2022-1-21)
### Patches 

- Removed snake case
- Added client license 4 alias update for assigned service user

<br><br>
## 5.34.8 (2022-1-19)
### Patches 

- Fixed hostname for primary for system licensing reporting

<br><br>
## 5.34.7 (2022-1-19)
### Patches 

- Add hostnameForPrimary to system report json
- Add column via migration
- Use camelcase attribute
- Add service instances to full template
- Reseller added to template
- Fix route for groups/devices/users
- Added broadworks receptionist

<br><br>
## 5.34.6 (2022-1-12)
### Patches 

- Added Charge numbers callback
- Fixed the array_keys_exists for phone number numbers

<br><br>
## 5.34.5 (2022-1-10)
### Patches 

- User cfa bulk
- Bulk get request
- Wip: updated BWClient parse to return an array from bulk OCI calls
- Can remove json conversion
- Multicommand + bulkable iterator
- Refactored Bulkable strategy
- Fix destroy methods
- Convert CloneGroup to mostly running in bulk
- Error handling and example routes
- Rename TraitResponse cleanup TraitBulkable
- BulkUpdate returns before after events
- Make event calls static
- Show-update-show
- GetResponseArray abortOnError flag + bulkableShowUpdateShow
- Add bulkableStoreShow + bulkableShowDestroy
- EVENT_UPDATE
- Refactor eventing for traitbulkable
- Call getResponse class method instead of statically
- Rename some bulkable functions
- Added call recording callback
- Added audit.service.instances to templates
- Aim target callCenterSupervisedAgents
- GroupHuntGroup extends Base
- AIM Add serviceUserId to hunt group 
- Call center serviceUserId targets
- Add dnis targets to all call centers
- Fix: trim throwing error on object
- Include other params for GroupDevice-&gt;index
- Removed UserCreate trait from Task
- Fixed getBladeShow
- Added broadworks receptions enterprise and office
- Added before after events receptionists
- Added abort on error for show

<br><br>
## 5.34.4 (2021-12-28)
### Patches 

- Fixes to AIM for target user services
- Targeted the rest of audit.user.services
- Config for import retries + default to 6
- Fix CustomContactDirectories target
- Added minimum template
- Fix for missing template error + parse run twice
- Fixed import retries config
- Fixed issue with only one alternate user id


<br><br>
## 5.34.3 (2021-12-21)
rebase with web

<br><br>
## 5.34.2 (2021-12-21)
rebase with web

<br><br>
## 5.34.1 (2021-12-21)
### Patches 
- Chatbox Enabled
- Add chatbotBranding to branding template
- Update chatbotEnabled + boolean field
- Aim audit groups bulk task
- Added AimImportAudits bulk task
- Added aim audit enterprise+serviceprovider bulk tasks
- Added Network Class of Service to Comm Barring
- Added default sorting and provide updated_at to aim list requests
- Add to uiTemplateController
- Add group meet me conference port to BRC for audit
- Set default orderby for audits
- Rename dial plan policy
- Fixed feature access code single result set
- Aim set serviceprovider meet me conferencing port on audit/import
- Fixed aim import calling plan digit plan
- Clear the error on re-run of import
- Do not return a warning if service meet-me-conferencing is not authorized


<br><br>
## 5.34.0 (2021-12-9)
### Minor Changes 

- Scaffolding for apply import options
- Added short tags to audit
- New audit procedure
- Apply import options
- Added import options tests + refactored tests to use OdinTestCase
- A bit more testing
- Add audit data enrichment feature
- Handle array of users param for enriching
- Conditionally enrichAuditData
- Refactored BackupRecoveryClasses to use for import/audit mapping
- Wip update
- Update items to the array style
- Templates added + reconfig get items
- Audit now supports more flexible transformation configuration
- Tweaked audit+import listeners
- Audit enrich lists of users
- A bit more cleanup
- Enrich audit data update on audit job
- Updated audit.group.settings.Admins for testing audit run
- Can now use deeper users nesting
- Added audit template feature
- Added audit templates endpoint
- Added templates used on FE
- Added endpoint to run audit via template
- Enable audit enrichment for Basic Template classes
- Pass options along to children
- Remove advanced template
- Variety of features
- Added base to other audit classes
- Move tests to run as test suite
- Remove audit options from all except parent on completion
- UserIdPrefix and userIdSuffix now appear in ShortTags
- Update label in BLF callback template
- Apply template transformations on export instead of import
- Export sets top level params
- Updates
- Bulk delete for import/export/audit
- More updates
- Bug fix
- Fix: login to endpoint causes exception
- Refactoring of transform lists + export options
- Transform all root userIds
- Add audit queue delay
- Refactored audit job state sequence
- Export state changes update + additional audit user list keys
- Refactored import user + import state changes update
- Improvements to import
- Refactored status setting + exception handling for aim
- Add status + remaining for export job
- Refresh the session token for exports
- Clear the options for child export jobs
- Clear options for child import jobs
- Updated full template
- Reworked templates to specify includes for audit
- Fixed: trait response compatible with Base
- User call center
- Fix: audit/import of callcenter agent-like targets
- Feature: rerun audits
- Audit device user settings option + switch logic for user voice messaging
- Other classes to transform
- More transforms
- Add call processing policy transform
- Feature: rerun/delete audit jobs
- All core audits skip if not defined in template
- feature access code change added to backup recovery
- Add feature access code to basic template
- Two templates
- Created Classes\AIM folder and moved templates+helpers
- Resolved scott&#39;s comments
- Templates can be individually run + can specify each type of includes
- Wip
- Finish splitting out the audit items
- Fetches destination userIds for mapping
- Match destination phone number for userId
- Handle tripartite targets like callParkGroup.instances.users
- Add rerun endpoint for export
- Added cluster hostname for OdinTestCase
- Added items to UserServiceInstances Template
- Add dial plan policy classes to audit
- Add excludes option to templates
- Add Clarity Template
- SP trunk group call capacity aim not assigned
- Rename clarity template
- Added group password rules
- Audit/import for group device files
- Added voice messaging greeting to bulk
- Added fusion-cypress to cloud build
- Add support for v22 Service Provider PasswordRules
- Add update alternate entries
- Added group dial plan policy
- Added service is not assigned aim
- Fixed aim ServiceProviderTrunkGroupCallCapacity not authorized
- Fixed use schedule update return
- Added GroupPagingGroupTargetCapacity OCI call
- Add to GroupClone and AIM
- Update controller class call
- Update templates and options
- Add group to basic template
- Link audit/import for groupPagingGroupTargetCapacity to the GroupPagingGroup
- Patch for sca bulk

### Patches 

- Interpolate
- Fixed name for attributes
- Fixed the import method
- Refactored to allow for specifying any userId field to update

<br><br>
## 5.33.21 (2021-12-6)
sync with web

<br><br>
## 5.33.20 (2021-12-6)
### Patches 

- Add update alternate entries to bulk user.update task

<br><br>
## 5.33.19 (2021-12-6)
### Patches 

- Fixed user schedule update return show

<br><br>
## 5.33.18 (2021-12-6)
### Patches 

- Merge group call park options into instance

<br><br>
## 5.33.17 (2021-12-6)
### Patches 

- Fixed aim ServiceProviderTrunkGroupCallCapacity not authorized

<br><br>
## 5.33.16 (2021-12-6)
### Patches 

- Added service is not assigned aim

<br><br>
## 5.33.15 (2021-12-6)
### Patches 

- Added group dial plan policy

<br><br>
## 5.33.14 (2021-12-3)
### Patches 

- SP trunk group call capacity aim not assigned
- Added group password rules
- Audit/import for group device files
- Added voice messaging greeting to bulk
- Add support for v22 Service Provider PasswordRules

<br><br>
## 5.33.13 (2021-12-2)
### Patches 

- Adding feature access code
- Added group dialing plan index
- Group dial policy
- Added alternate user id to modify add
- Added group dial plan policy and access codes
- Removed unused use classes
- Added group dial plan
- Added service provider dial plan
- Added system dial plan and access codes
- Added AIM to Dial Plan Policy
- Deploy to fusion
- Fixed alternate userId blade file
- Added system.license.show event
- Update System Collaborate endpoint
- Added Webhook search history
- Calling Line Identity for Redirected Calls fix for User Call Policy
- Bug fix for Voice Portal Recording
- Fixed aim SCA throwing error
- Clone service provider dial plan policy
- Add dialplan policy to clone group
- Update Voice Messaging Voice Portal get request


<br><br>
## 5.33.10 (2021-11-16)
sync

<br><br>
## 5.33.9 (2021-11-16)
### Patches 

- Update possible versions for FeatureAccessCode
- Set to proper function

<br><br>
## 5.33.8 (2021-11-15)
### Patches 

- Added feature access code to sp aim
- Here is password reset
- Fixed passsword to password
- Removed Helpers::log
- Fixed hostName null
- Added migration for common phone list + enterprise directory
- Added hostName for lookup for email
- Refactoring
- Added webex packages as static array
- Fix save Webex settings
- Update Webex Packages
- Verify people and subscriber
- Add Verify Webex People Email Bulk Task

<br><br>
## 5.33.7 (2021-11-9)
sync with web

<br><br>
## 5.33.6 (2021-11-9)
### Patches 

- Added multi-line SCAP to AIM

<br><br>
## 5.33.5 (2021-11-8)
### Patches 

- Check webex account
- Pseudo code for webex verify
- Fixed curly braces
- Update Webex Subscriber attributes
- Update Webex Templates to use common token
- Updated Webex Bulk Templates Control Hub Settings
- WebexResponseCodes
- Update Webex Error Messages
- Added throwable for call me now audit digit plan
- Added group call me now exception on audit
- Fixed array merge for service provider id
- Add Webex Verify Email Create User Bulk Template
- Added support for v20
- Added group trunk group call for 20sp1
- Update GroupTrunkGroup.php
- Fixed userId array for audit user


<br><br>
## 5.33.4 (2021-11-2)
### Patches 

- Fixed directory path sp feature access code


<br><br>
## 5.33.3 (2021-11-2)
### Patches 

- Added portal passcode migration to branding modules
- Subscribers now returns all pages from webex
- Cleanup and done testing
- Added bulk task for bulk tag modify phonism
- Moved event to bottom
- Removed modify to make more general
- Added service provider feature access codes
- Added service provider feature access code clone
- Added service provider feature access code
- Using traing for service provider feature access code
- Added serviceProviderId to show response
- Fixed non alpha
- Good with that
- Fixed type
- Update GroupAccountAuthorizationCodes.php
- Fixed dangling comma

<br><br>
## 5.33.2 (2021-10-14)
### Patches 

- AIM Group department bug fixed:  edd7f9005fb2fc6bb3265d165a6020eab687b304
- AIM Added all of the shared call appearance to audits

<br><br>
## 5.33.1 (2021-10-12)
### Patches 

- Support Password Reset for clustered BW instances
- Put in check for null value
- Fix send email forgot password domain
- Fix domains with forgot password
- Updated clusters for multiple domains
- Fix looping through domains


<br><br>
## 5.33.0 (2021-10-4)
## Bug Fixes

*   Recent Task loads properly now
*   Webex settings re render
*   Group Assign Number firefox loading issue
*   Flexible seating host permissions updated
*   CLID update fixed for business profile
*   Add trunk group fixed
*   Can unassign numbers for auto attendant
*   Allow null values for group and user device tags
*	Edit trunk group name
*	Group services active column moved to left hand side
*	Conferencing domain existing error fixed
*	Loading spinner added to group services
*	Call center statistics save button fixed
*	Bulk wizard unauthorized request fixed
*	Audit not able to add
*	Quick links icons improperly set
*	Device not found error
*	Clone hostname cancel button fixed
*	

## Feature

*	Charge number - user
*	Group comm barr auth code bulk templates + download

### Minor Changes 

- Upgrade from Laravel 5.7 to 5.8
- Upgrade Laravel from 5.8 to 6.0. Few changes as we were proactive in following Laravel suggestions.: - Initial commit to upgrade Laravel to 7.0.
- Upgrade CORS
- Updated composer.lock file
- Upgrade to 5.8
- Fix code to upgrade to 5.8
- Upgrade to 6.x
- Fix code to upgrade to 6.x
- Fix code to upgrade to 7.x
- Added Mailer Job Mailer and Swift On application load
- Pull email configuration from database
- Added testing for email
- Email template
- Added email template
- Keeping Laravel 7,x up to date with changes to the API
- Updated composer.lock file to work with Laravel 7 and api changes
- Here&#39;s the update composer files. Compoer 2 is required.
- Added base class
- Fixed exception error handling function.
- Token
- Hot fix alternateTrunkIdentity
- Hot fix alternateTrunkIdentity
- Tablename callback templates fixed
- Added settings to e911 pull from db
- Added endpoints for e911
- Added logic for user settings
- Removed commented code
- Removed token generate code
- Acl::added ACL for user
- Added new branding module
- Added departments module
- Department now can remove a parent department
- Fixed PR for Department
- Set pilotUserId to string
- Allow Group Admins to clone Auto Attendants
- Added primery info and public cluster login request
- Allow access device update for SCA
- Added throwable for setings
- Allow device update
- Check this out
- Authorized function with serviceProviderId
- Again
- Update Authorized User and Group Services for Enterprise
- Removed debug code
- Fixed endpoint to include services array_filter replaced with array_map
- Added links for call center to show
- Removed return statement
- Added authorized
- Fixed array_unique for group services
- Array_unique
- 5.30.3
- Added mailer label
- Created alhpa build script
- Added email address
- Welcome message
- Fixed phonism cache
- Initial commit
- Fixed server side task email
- Initial commit 2
- Added user call forwarding always bulk task
- Removed old test blade templates
- Added group admin users password mail bulk
- Unset unused task variable for group admin users
- Task controller was readded
- Removed unused classes
- Fixed userId column header template
- Cleaned up unused code and fixed template
- Early return statement
- Removed logging
- Removed commented code
- Added optional message if we decide to support template
- Added message back
- Removed commen code TestTemplate
- Added token revoke minutes and password reset url
- Get api user from config
- Commented out
- 5.30.4
- Changed message to emailMessage api post
- Branding general settings
- Added ui settings
- Working on bug fixes
- Added password reset url check
- Something changed
- Testing token from webex
- Fixed user access device endpoint sip contact list api
- Hotfix access device endpoint sip contact
- Little bit of cleanup
- A little more cleanup
- Fixed a bug
- Cleanup
- Added subscriber delete
- Passing cookie to webex method
- Passing cookies
- Webext
- Fixed bug
- Calling it
- Make it private
- Stuff and things
- Tag value allow null on add
- Check this in
- Update Webex integration
- Updated WebEx integration with odin security
- Clean up code
- Created 2 Webex product master records and removed debug code out fo a migration
- Clean up code
- Code clean up
- Wrong name
- Fixed semi-colon
- Removed helper logs
- Here
- Webex Task init
- IonCube fix
- 5.31.3
- 5.32.3 - 5.23.4
- Revert &quot;5.32.3 - 5.23.4&quot;
- Add webex access_token
- Test
- Updated routes for voice messaging
- All routes verified in Postman
- Fix: ensure valid bw.xsiUrlbefore processing
- Changed throw message and empty function URL
- User voice messaging update
- Removed unnecessary use statement
- Removed named routes as unnecessary
- Removed test
- Restored GroupCloneServicesHelperTest
- Added support for updating voiceportal to task
- Created user reports
- Update label with correct report id
- Renamed ServiceProviderUserReport + removed string declarations
- Added data_get to User Service Search
- SystemServicePack
- Refactored SystemServicePackController2 to use new OCI class
- Added SystemServicePackReport report
- Created new user service reports
- Cleaned up log message + undefined variable/index notices
- Removed unnecessary imports
- Service provider group department
- Wrapped final json value in array
- Added ServiceProviderGroupDepartmentReport + controller and route
- Added migration for webex setting seed
- Split out the three oci reports
- Created reportengine reports
- Updated client id/secret with default params
- Created migration for renaming webex bulk templates/wizards
- Add product webex users
- Finished migration
- Added service isntance report
- Add test to skip migration if already exists
- Test to ensure key does not already exist
- Added System Licensing if user.login is system
- Updated Webex Token Process and Endpoints
- Fix integration in base class
- Tinkering with queues and minor bug fixes
- Add webex enterprises to product master migration
- Added task for creating group communication barring authorization codes
- Added delete task
- Deactivate webex endpoint by default
- Added try/catch for error handling
- Created SystemLogin queue job to store system licensing report records weekly
- Removed session reference
- Set dispatch to send to listeners queue
- Report status=running when running
- Additional params in task calls are added to event &#39;after&#39; array
- Remove log usages
- Add attributes to events for device CRUD
- No need to pass attributes on delete
- Move expansion logic and always add groupId/serviceProviderId if present
- Pass along attributes for groupcallcenter
- Fixed virtualOnNetCallTypeName
- Hostname for primary
- Add try catch
- Added use statement
- Update configurations to send webex
- HostnameForPrimary migration + added to event
- Webex Modify User Package
- Added hostnameForPrimary to Tasks and Reports
- Cleanup
- Audit fix for ServiceProviderDeviceType
- Removed wrapping task run with exception handling
- Use config param for queue dispatch delay value
- Return empty devices
- GroupDeviceCreate passes along attributes through DeviceHelper
- Set queue delay to 3s
- Flow attributes into new event.incoming column
- Added attributes to other calls
- Switched from incoming to options - complete
- Disable fkconstraints during events column update
- Update Webex settings to use hostname
- Update Webex settings to use hostname
- Data_get on url pair
- Fixing group trunk group rename
- Update UISetting to always send Webex
- Update Webex Settings
- Updated webex subscribers index
- Spelling fix
- Gitignore
- Adding alternateUserId emails
- Added Task error handling
- Webex users bulk delete and update
- Deactivate subscription endpoints for testing
- Fix for zero as a tag value
- Removed commented code
- Update endpoints now sending to webex endpoints
- Debug self service controller
- More tests
- Last try
- Fixed bug
- Fixed again
- Fix front end issue for Webex
- Update Webex Modify User Package
- Fixed hostname bug
- Checking back in
- Check this for recpatcha
- Update Verify Webex email
- Fix to for invalid voice message format XSI
- Finish up Webex Verify BW User Email
- Added user service r22 blacklist
- Ignore this
- Fix aim for services not supported in r24 import from r21
- Leverage Settings functions for Webex
- Remove extra comments
- Refactor Webex to leverage Setting
- Fix Webex refactoring
- Fix bug
- Fix empty webex settings
- Fixed webex pull of data
- Debugging
- Debugging
- Fixed bug
- Fetch webexapiurl out of endpoint
- Cleanup spelling consistency
- Rename webex bulk tasks
- Updating single webex user now sends all fields
- Added calling line id group audit and import
- Changed import priority for group calling line id

<br><br>
## 5.32.12 (2021-9-14)
### Patches 

- Added task for creating group communication barring authorization codes
- Set dispatch to send to listeners queue
- Report status=running when running
- Additional params in task calls are added to event &#39;after&#39; array
- Add attributes to events for device CRUD
- No need to pass attributes on delete
- Fixed virtualOnNetCallTypeName
- Hostname for primary
- HostnameForPrimary migration + added to event
- Added hostnameForPrimary to Tasks and Reports
- Cleanup
- Audit fix for ServiceProviderDeviceType
- Merge from develop
- Removed wrapping task run with exception handling
- Use config param for queue dispatch delay value
- Return empty devices
- GroupDeviceCreate passes along attributes through DeviceHelper
- Set queue delay to 3s
- Flow attributes into new event.incoming column
- Added attributes to other calls
- Switched from incoming to options - complete
- Disable fkconstraints during events column update


<br><br>
## 5.32.11 (2021-9-2)
### Patches 

- 860 Assign Number Module Issue . notation changes
- Fixed the default extension for announcements

<br><br>
## 5.32.10 (2021-9-1)
### Patches 

- Deactivate webex endpoint by default

<br><br>
## 5.32.9 (2021-9-1)
### Patches 

- Created user reports
- Update label with correct report id
- Refactored SystemServicePackController2 to use new OCI class
- Added SystemServicePackReport report
- Created new user service reports
- Wrapped final json value in array
- Added ServiceProviderGroupDepartmentReport + controller and route
- Added migration for webex setting seed
- Split out the three oci reports
- Created reportengine reports
- Updated client id/secret with default params
- Created migration for renaming webex bulk templates/wizards
- Add product webex users
- Finished migration
- Added service isntance report
- Add test to skip migration if already exists
- Test to ensure key does not already exist
- Add webex enterprises to product master migration


<br><br>
## 5.32.8 (2021-8-24)
### Patches 

**Bug Fixes**

- Extended user data only pulls when downloading
- Group and enterprise dashboard panels will dynamically render

<br><br>
## 5.32.7 (2021-8-19)
### Bug Fixes
- Visual voice mail data table unresponsive 
- User device tags not loading on render
- User export giving minimal details

### Patches 

- Removed hard value size for nav bar images
- User report
- Visual voice mail
- UI Table Issue Fixed
- Group user report
- Added voice messaging voice portal to task
- Fixed device tag bug

<br><br>
## 5.32.6 (2021-8-18)
### Patches 

- User voice messaging update
- Added support for updating voice-portal to task engine

<br><br>
## 5.32.5 (2021-8-17)
### Patches 

- Created 2 Webex product master records and removed debug code out fo a migration
- IonCube fix

<br><br>
## 5.32.4 (2021-8-5)
Sync with Front End

<br><br>
## 5.32.3 (2021-7-31)
**August 2nd 2021**

**Bug Fixes**

*   Service pack assignment visible to group admins
*   Unable to assign DID
*   Missing column on group users
*   User password change
*   Group Admin Policy
    *   trunk group
    *   user profile
    *   group profile
*   User Password Update
*   Meet Me Conferencing permissions
*   Emergency Call Notification v22

**Upgrades**

*   Group Assign Number
*   Group Config Call Center Service Assignment
*   Enterprise Dashboard
*   Enterprise Meet Me Conferencing

<br><br>
## 5.32.2 (2021-7-31)
Fix comma error for IonCube

<br><br>
## 5.32.1 (2021-7-21)
### Patches 

- Fixed semi-colon

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

- Upgrade from Laravel 5.7 to 5.8
- Upgrade Laravel from 5.8 to 6.0. Few changes as we were proactive in following Laravel suggestions.
- Initial commit to upgrade Laravel to 7.0.
- Upgrade CORS
- Upgrade CORS take 2... with a lot of testing. Postman. UI, including Service Provider, Group, Department and Users. View, Add, Update, and Delete.
- Updated composer.lock file
- Merge branch &#39;master&#39; into feature/31-upgrade-laravel-5.8
- Merge branch &#39;feature/31-upgrade-laravel-5.8&#39; into feature/32-upgrade-laravel-6.0
- Merge branch &#39;feature/32-upgrade-laravel-6.0&#39; into feature/33-upgrade-laravel-7.0
- Upgrade to 5.8
- Fix code to upgrade to 5.8
- Upgrade to 6.x
- Fix code to upgrade to 6.x
- Fix code to upgrade to 7.x
- Added Mailer Job Mailer and Swift On application load
- Pull email configuration from database
- Added testing for email
- Email template
- Added email template
- Merge branch &#39;master&#39; into feature/146-email-bulk-welcome-letter
- Keeping Laravel 7,x up to date with changes to the API
- Updated composer.lock file to work with Laravel 7 and api changes
- Here&#39;s the update composer files. Compoer 2 is required.
- Merge branch &#39;develop&#39; into feature/31-laravel-7.x
- Merge pull request #195 from parkbenchsolutions/feature/31-laravel-7.x
- Added base class
- Fixed exception error handling function.
- Merge pull request #220 from parkbenchsolutions/bug/219OA-response-error-code-gone
- Token
- Hot fix alternateTrunkIdentity
- Hot fix alternateTrunkIdentity
- Tablename callback templates fixed
- Added settings to e911 pull from db
- Added endpoints for e911
- Added logic for user settings
- Removed commented code
- Removed token generate code
- Acl::adde ACL for user
- Merge pull request #223 from parkbenchsolutions/feature/149-dash-911-portal-integration
- Added new branding module
- Merge pull request #225 from parkbenchsolutions/feature/149-dash-911-portal-integration-branding-module
- Added departments module
- Merge pull request #226 from parkbenchsolutions/feature/1309-add-branding-module-department
- Department now can remove a parent department
- Merge pull request #228 from parkbenchsolutions/bug/598-Group-Level-Department
- Fixed PR for Department
- Set pilotUserId to string
- Merge branch &#39;develop&#39; into bug/598-Group-Level-Department2
- Allow Group Admins to clone Auto Attendants
- Added primery info and public cluster login request
- Merge pull request #231 from parkbenchsolutions/bug/230OA-Group-Auto-Attendant-Clone
- Merge pull request #229 from parkbenchsolutions/bug/598-Group-Level-Department2
- Merge pull request #232 from parkbenchsolutions/feature/PublicClusterFullyQualifiedDomainName
- Allow access device update for SCA
- Merge pull request #233 from parkbenchsolutions/bug/594-sca-device-update
- Merge branch &#39;master&#39; into develop
- Added throwable for setings
- Merge pull request #234 from parkbenchsolutions/bug/e911-settings
- Merge branch &#39;develop&#39; into master
- Allow device update
- Merge pull request #235 from parkbenchsolutions/bug/sca-device
- Merge branch &#39;develop&#39; into master
- Check this out
- Authorized function with serviceProviderId
- Again
- Update Authorized User and Group Services for Enterprise
- Removed debug code
- Merge pull request #237 from parkbenchsolutions/feature/612-service-provider-services-authoried
- Fixed endpoint to include services array_filter replaced with array_map
- Merge pull request #238 from parkbenchsolutions/bug/service-provider-services-authorized-bug
- Added links for call center to show
- Removed return statement
- Merge pull request #239 from parkbenchsolutions/feature/Group-Assigned-Services-Get-List
- Added authorized
- Fixed array_unique for group services
- Array_unique
- 5.30.3
- Merge branch &#39;develop&#39; into feature/146-email-bulk-welcome-letter
- Added mailer label
- Created alhpa build script
- Merge branch &#39;develop&#39; into feature/146-email-bulk-welcome-letter
- Added email address
- Welcome message
- Fixed phonism cache
- Merge branch &#39;develop&#39; into feature/146-email-bulk-welcome-letter
- Initial commit
- Fixed server side task email
- Merge branch &#39;feature/146-email-bulk-welcome-letter&#39; of github.com:parkbenchsolutions/odinapi into feature/146-email-bulk-welcome-letter
- Initial commit 2
- Added user call forwarding always bulk task
- Removed old test blade templates
- Added group admin users password mail bulk
- Unset unused task variable for group admin users
- Task controller was readded
- Removed unused classes
- Fixed userId column header template
- Cleaned up unused code and fixed template
- Early return statement
- Removed logging
- Removed commented code
- Added optional message if we decide to support template
- Added message back
- Removed commen code TestTemplate
- Added token revoke minutes and password reset url
- Merge branch &#39;feature/146-email-bulk-welcome-letter&#39; of github.com:parkbenchsolutions/odinapi into feature/146-email-bulk-welcome-letter
- Get api user from config
- Commented out
- Merge branch &#39;develop&#39; into master
- Merge pull request #246 from parkbenchsolutions/feature/146-email-bulk-welcome-letter
- 5.30.4
- Changed message to emailMessage api post
- Branding general settings
- Merge pull request #247 from parkbenchsolutions/feature/146-email-bulk-welcome-letter
- Added ui settings
- Merge pull request #250 from parkbenchsolutions/feature/ui-general-setting
- Added password reset url check
- Merge pull request #251 from parkbenchsolutions/feature/password-reset-url-blade-update
- Fixed user access device endpoint sip contact list api
- Hotfix access device endpoint sip contact
- Merge branch &#39;master&#39; into develop
- Tag value allow null on add
- Merge pull request #253 from parkbenchsolutions/bug/694-tags-not-functioning
- Merge pull request #252 from parkbenchsolutions/bug/663-sip-contact-fiels

<br><br>
## 5.31.1 (2021-7-1)
### Patches 

- Hotfix access device endpoint sip contact
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

### Minor Changes 

- Fixed phonism cache

### Patches 

- Created alpha build script

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

<br><br>
## 5.30.2 (2021-5-22)
### Patches 

- Allow device update for SCA bulk actions

<br><br>
## 5.30.1 (2021-5-21)
### Patches 

- Added throwable for user settings

<br><br>
## 5.30.0 (2021-5-21)
### Minor Changes 

- Upgrade from Laravel 5.7 to 5.8
- Upgrade Laravel from 5.8 to 6.0. Few changes as we were proactive in following Laravel suggestions.
- Upgrade CORS
- Upgrade CORS take 2... with a lot of testing. Postman. UI, including Service Provider, Group, Department and Users. View, Add, Update, and Delete.
- Upgrade to 5.8
- Upgrade to 6.x
- Fix code to upgrade to 6.x
- Fix code to upgrade to 7.x
- Keeping Laravel 7,x up to date with changes to the API
- Here&#39;s the update composer files. Compoer 2 is required.
- Fixed exception error handling function.
- Added settings to e911 pull from db
- Added endpoints for e911
- Added logic for user settings
- Added departments module
- Department now can remove a parent department
- Fixed PR for Department
- Set pilotUserId to string
- Allow Group Admins to clone Auto Attendants

### Patches 

- Hot fix alternateTrunkIdentity
- Hot fix alternateTrunkIdentity
- Tablename callback templates fixed
- Acl::adde ACL for user
- Added primery info and public cluster login request
- Allow access device update for SCA

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

<br><br>
## 5.29.2 (2021-5-11)
sync with web patch for is pilot user id true or false

<br><br>
## 5.29.1 (2021-5-11)
### Patches 

- Hot fix alternateTrunkIdentity

<br><br>
## 5.29.0 (2021-5-7)
### Minor Changes 

- Password reset userId password expire days bypass
- Token Bypass for password reset
- Added assigned list api endpoint for group dashboard
- Added user modify group id bulk
- Changed blacklist from version 24 to 22 for aim import of group/user level services
- Added blacklist for group service import
- Fix OCI call for Voice Messaging Greetings.
- Added requirement newGroupId for userModifyGroupId Task
- Surgemail base
- Added Start Time and Answer Time UTC to response. Browser will display local time.
- Cleaned up Webex Integration endpoints

### Patches 

- Fixed settings api

<br><br>
## 5.28.2 (2021-4-21)
### Patches 

- Created flexibility and efficiency for odin system settings.

<br><br>
## 5.28.1 (2021-4-14)
### Patches 

- Fixed broken comman parenthesis

<br><br>
## 5.28.0 (2021-4-14)
### Minor Changes 

- Added enterprises for webex
- Added sers and enterprises to webex
- Updated OAuth2 webex connector
- Updated webex odin api
- Changed users to subscribers
- Removed users.php
- Webex OAuth2 integration
- Task engine webex
- Added webex verify
- Created webex endpoints to execute actions into webex from odin
- Add email verify with webex and BW
- Added service provider exists so it doesn&#39;t ovewrite the profile on the serice provider
- Alternative to overwriting service provider
- Switched Arr::get to data_get
- Added Report Interface
- Added cloud build develop
- Added user service settings endpoint

### Patches 

- Webex code
- Moved construct to top of class
- Removed commented code
- Removed unused use statement
- Removed users concat doesn&#39;t apply in description
- Refactored code to be more flexible. Move functionality out of Controller and into a Class.

<br><br>
## 5.27.0 (2021-4-12)
### Minor Changes 

- Added task reporting engine

### Patches 

- Added service provider exists so it doesn&#39;t ovewrite the profile on the serice provider
- Group call center removed depracated code
- Moved construct to top of class
- Switched Arr::get to data_get
- Fixed data_get
- Added Report Interface
- Removed unused use statement
- Removed users concat doesn&#39;t apply in description

<br><br>
## 5.26.8 (2021-4-8)
### Patches 

- Fixed user department inventory
- Added check for allow password reset username

<br><br>
## 5.26.7 (2021-4-6)
### Patches 

- Fixed user inventory query to account for inTrunkGroup and department

<br><br>
## 5.26.6 (2021-4-6)
### Patches 

- Changed retries from 4 to 6 for inventory

<br><br>
## 5.26.5 (2021-4-5)
### Patches 

- Added details to users and groups inventory

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
### Patches 

- Added service provider trunk group call capacity to inventory
- Added group trunk group capacity to inventory

<br><br>
## 5.26.0 (2021-3-23)
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
sync with web

<br><br>
## 5.24.0 (2021-3-17)
sync with api

<br><br>
## 5.23.0 (2021-3-17)
### Minor Changes 

- Return if service provider id is already the same from profile do not try to create

<br><br>
## 5.22.8 (2021-3-16)
sync with web

<br><br>
## 5.22.7 (2021-3-16)
sync with odinweb

<br><br>
## 5.22.6 (2021-3-16)
sync with web

<br><br>
## 5.22.5 (2021-3-11)
### Patches 

- Strpos for faster processing

<br><br>
## 5.22.4 (2021-3-11)
### Patches 

- Fixed the groupTable delete
- Fixed minUpdate function in models
- Fixed integer returns on serviceProviderId and groupId
- Added string conversion to broadworks ids that are coming back is integer
- Added locationDialingCode and zipOrPostalCode to string conversion
- Fixed key lookup special columns

<br><br>
## 5.22.3 (2021-3-11)
### Patches 

- Fixed tblUsers minUpdated delete

<br><br>
## 5.22.2 (2021-3-11)
### Patches 

- Delete by now date group and user inventory

<br><br>
## 5.22.1 (2021-3-11)
### Patches 

- Added min updated as delete for inventory

<br><br>
## 5.22.0 (2021-3-11)
### Minor Changes 

- Reporting/Inventory queue added to api tools

<br><br>
## 5.21.0 (2021-3-9)
sync with odinweb

<br><br>
## 5.20.3 (2021-3-9)
### Patches 

- Added trunk group call capacity to clone

<br><br>
## 5.20.2 (2021-3-4)
### Patches 

- Fixed url https for phonism device management

<br><br>
## 5.20.1 (2021-3-3)
### Patches 

- Fixed is-active for connector

<br><br>
## 5.20.0 (2021-3-3)
### Minor Changes 

- Added branding module phonism disabled by default

<br><br>
## 5.19.9 (2021-3-3)
### sync with odin web 

- #867 service calling plans changes
- Group Calling Plans Menu Fix

<br><br>
## 5.19.8 (2021-3-3)
- sync with odinweb
- Alternate Numbers TN field caused logout on User login

<br><br>
## 5.19.7 (2021-3-3)
### Patches 

- Added base classes for webex

<br><br>
## 5.19.6 (2021-3-2)
sync with odinweb

<br><br>
## 5.19.5 (2021-3-2)
sync with odin web

<br><br>
## 5.19.4 (2021-3-2)
### Patches 

-sync with API server

<br><br>
## 5.19.3 (2021-2-24)
### Patches 

> fixed the json post to phonism where the options are being sent down as a json array of options to phonism client

```php
$res = $this->client->request($method, self::$URL . $url, ['json' => $options]);
```



<br><br>