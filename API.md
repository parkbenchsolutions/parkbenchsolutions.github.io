# API Latest Releases
## 4.1.5 (2019-5-7)
- No changes, sync release version

<br><br>
## 4.1.4 (2019-5-7)
  - Add Bulk Group Registration

<br><br>
## 4.1.3 (2019-5-7)
  - Fix single alias on Fax Messaging
  - Fix system domain list on R22

<br><br>
## 4.1.2 (2019-5-3)
  - Fix Service Provider Admin login with default domain

<br><br>
## 4.1.1 (2019-4-29)
- No changes

<br><br>
## 4.1.0 (2019-4-29)
  - Add ability for group admins to search recent tasks in group
  - Add Token refresh endpoint
  - Fix new password logi

<br><br>
## 4.0.2 (2019-4-29)
No Changes

<br><br>
## 4.0.1 (2019-4-29)
  - Fix user password change with IM&P

<br><br>
## 4.0.0 (2019-4-29)
  - Release of API V2
  - Fully documented and available as a Postman Collection
  - Multi-tenant support
  - Added many User Service Cloning endpoints
  - Add ability to limit API to certain levels (eg: Provisioning, Ent Admin, Group Admin...)
  - Automatic Audio Conversion
  - User Services Reports Upgrade
  - Call Center Queue Live Reports
  - New User Call Reports
  - Project Rooms
  - Download large CSV files of Call Report Raw Data
  - Group Admin Policy support

<br><br>
## 3.17.45 (2019-5-23)
Internal release build changes

<br><br>
## 3.17.44 (2019-5-23)
Internal release build changes

<br><br>
## 3.17.43 (2019-5-23)
Internal release build changes

<br><br>
## 3.17.42 (2019-5-23)
Fix fax messaging alias error with one alias

<br><br>
## 3.17.41 (2019-5-14)
update System Licensing to handle empty hostId fields

<br><br>
## 3.17.40 (2019-4-23)
No changes, sync version with Web

<br><br>
## 3.17.39 (2019-4-23)
No changes, sync version with Web

<br><br>
## 3.17.38 (2019-4-23)
Fix parsing error on BW Events

<br><br>
## 3.17.37 (2019-4-5)
No changes, sync version with Web

<br><br>
## 3.17.36 (2019-4-5)
No changes, sync version with Web

<br><br>
## 3.17.35 (2019-4-5)
Add serviceProviderId and groupId to webhooks dn payload

<br><br>
## 3.17.34 (2019-3-22)
- Attach branding Provisioning to Group Delete UI
- Add group.dn.create, group.dn.delete, group.dn.update, serviceProvider.dn.create, serviceProvider.dn.update event logging / webhooks

<br><br>
## 3.17.32 (2019-2-15)
Query optimization for User Call Record searches

<br><br>
## 3.17.30 (2019-2-4)
- User Simultaneous Ring Bug Fix

<br><br>
## 3.17.28 (2018-12-5)
no changes, sync with web

<br><br>
## 3.17.26 (2018-11-27)
add configurable timeouts and more sane defaults for queue workers

```
QUEUE_WORKERS=6
QUEUE_RETRIES=3
QUEUE_TIMEOUT=300
QUEUE_SLEEP=3
```

<br><br>
## 3.17.25 (2018-11-2)
- no changes, sync with odinweb


<br><br>
## 3.17.24 (2018-11-2)
- don't re-activate phone number on user update if not changed

<br><br>
## 3.17.20 (2018-10-27)
- Support new authentication mechanism in R22

<br><br>
## 3.17.16 (2018-10-11)
- fix in auto attendant service search link
- fix service provider admin update
- fix system level network class of service


<br><br>
## 3.17.13 (2018-10-11)
- sync with web

<br><br>
## 3.17.12 (2018-10-11)
sync with web

<br><br>
## 3.17.10 (2018-10-11)
Fixed a bug introduced in 3.17.5 that effected Schedules 

<br><br>
## 3.17.6 (2018-10-11)
- Fix missing class in Enterprise Admins

<br><br>
## 3.17.4 (2018-9-26)
### Patches 

- Allow slash in auto attendant name
- Add v2 api routes
- Fix error showing user service packs

<br><br>
## 3.17.1 (2018-9-20)
no changes, sync version with web

<br><br>
## 3.17.0 (2018-9-20)
### Minor Changes 

- Added rollback to bulk user create to remove created devices upon user failure
- Add user.login.failure and user.login.expired
- Add user privacy api
- Add userPrivacy to API
- Added group feature access code endpoints
- Added group feature access code database migration
- Update User Privacy API
- Added feature access code reset
- Added restore default codes to all versions of feature access codes
- Added group speed dial 100 api request
- Added Client License Mappings for 3,4,17,18,19
- Return alias on Group Services and Service Pack Services Update Group Call Park API to accept a slash in the Group Name
- Allow Slashes in Group Call Pickup Group Names
- Support Slashes in Department Names

### Patches 

- Postman notes
- Fixed fac update
- Update Group Schedule API to work with slashes in schedule name
- Update Group Event API to accept names with slash
- Accept string FALSE on autoActivate phone number setting

<br><br>
## 3.16.3 (2018-9-7)
### Patches 

- Remove orderBy clause on Group and User Call Records
- Added group routing profile check for clone
- Check for invalid tokens
- Add functionality to webhooks, if a 404 or 410 error is returned, immediately fail
- Added user call summary report
- Fix debug logs on soap error
- Update device tags to match all Business Communicator types.  add related services to devices for convenience
- Update soap client to work with broadworks new payload and response in recent updated soap server
- AA daily Error
- A few fixes in UserCallRecords Summary


<br><br>
## 3.16.2 (2018-8-17)
- edit initial import migration script

<br><br>
## 3.16.0 (2018-8-15)
### Minor Changes 

- Added use index on CdrCallRecords
- Move webhook settings to callback settings
- Added related call id reason
- Added system routing profile api
- Added group routing profile
- Added group routing profile
- Added routing profile migration
- Fixed routing profile endpoint
- Added group routing profile clone
- Added busy lamp field callback to database, allowed fillable for CallbackTemplate model
- Update blf callback
- Clean up references to CdrCallRecords model
- Normalize cache keys
- Added schemas for callback templates
- Update related calls
- Move hunt group auto activate to the phoneNumberChanged event
- Create GroupDN-&gt;autoActivate method to handle explicit auto activation.  Remove PhoneNumberChanged event magic
- Update GroupDN-&gt;autoActivate($userObject)

### Patches 

- Fix common phone list

<br><br>
## 3.15.2 (2018-7-10)
### Patches 

- Fix branding hostname settings

<br><br>
## 3.15.1 (2018-7-10)
### Patches 

- Remove old migrations that break updates

<br><br>
## 3.15.0 (2018-7-10)
### Minor Changes 

- Add sessionTimeout to branding templates
- Added use index
- Added branding settings componenet
- Added index to group queries to improve performance
- Added index to group queries to improve performance
- Added group feature access code endpoints
- Feature access codes controller
- Used index not show for access codes
- Removed feauture access codes from old group endpoint
- Merge branch &#39;master&#39; of github.com:parkbenchsolutions/odinapi
- Add pilot user control to branding

### Patches 

- Fix trunkAddressing return values on user show
- Minor rename of function to keep consistency

<br><br>
## 3.14.4 (2018-7-6)
### Patches 

- Fixes 72

<br><br>
## 3.14.3 (2018-7-5)
### Patches 

- Initial implementation of webhook template and settings with openapi definition

<br><br>
## 3.14.1 (2018-7-4)
no changes - syncing with web release

<br><br>
## 3.14.0 (2018-7-3)
### Minor Changes 

- Add enterprise users report - add ala-cart user services to users report

### Patches 

- Fixed callingLineIdLastName and callingLineIdFirstname defaulting to 1

<br><br>
## 3.13.1 (2018-6-29)
### Patches 

- Fix permissions bug when user requesting GroupMeetMeConferenceBridge

<br><br>
## 3.13.0 (2018-6-28)
### Minor Changes 

- Add userId, serviceProviderId, groupId to all responses for webhooks
- Update webhookService, webhookTemplate and migrations

### Patches 

- Updated migration
- Allow 0 for hunt group call forward seconds
- Remove failed product master insert

<br><br>
## 3.12.0 (2018-6-21)
### Minor Changes 

- Add Group Intercept to branding
- Added virtual on net enterprise
- Added webhook services and templates
- Added webhook services method
- Update call center to use announcements on &gt; 20 rel

### Patches 

- Change Intercept Group from Create to Turn on in Product Master migration
- Added collaborate to product master
- Created insert for collaborate
- Fix call center announcement view
- Update to dockerfile

<br><br>
## 3.11.0 (2018-6-12)
- Added Group Night Forwarding
- Added User Night Forwarding
- Added Group Intercept
- fix user.create in bulk to not ask for selected users

<br><br>
## 3.10.0 (2018-6-11)
### Minor Changes 

- Update for callRecrods to startTime
- Add /ping status check and healthcheck to docker

### Patches 

- Remove debug logging
- Remove healthcheck from dockerfile - add to compose

<br><br>
## 3.9.0 (2018-6-7)
### Minor Changes 

- Webhook logs to database
- Webhook api
- Initial GroupPolicy class
- New groupPolicy class.  added to the group admins
- Login message to templates
- Add bulk to admin policies

### Patches 

- Modify some import of 2.0 to 3.0 migrations.  add mongodb support to docker base
- Remove authentication and login debug logs.  add better error messages within application.  trunk deviceName on access device create
- Updated token

<br><br>
## 3.8.3 (2018-5-30)
Initial release

<br><br>
## 3.8.2 (2018-5-30)
### Patches 

- Added migration to clean auto attendant product master

<br><br>
## 3.8.1 (2018-5-30)
Initial release

<br><br>
## 3.8.0 (2018-5-24)
### Minor Changes 

- Bulk virtualpack

<br><br>
## 3.7.11 (2018-5-21)
Initial release

<br><br>
## 3.7.10 (2018-5-19)
Initial release

<br><br>
## 3.7.9 (2018-5-18)
sync with web

<br><br>
## 3.7.8 (2018-5-16)
Initial release

<br><br>
## 3.7.7 (2018-5-15)
### Patches 

- Added answerIndicator and relatedCallIdReason to Group and User Call Records

<br><br>
## 3.7.5 (2018-5-15)
### Patches 

- Full system dn search
- Remove debug statement

<br><br>
## 3.7.4 (2018-5-14)
### Patches 

- Added isEnterprise lookup for enterprise Calls CLID Policy

<br><br>
## 3.7.3 (2018-5-14)
### Patches 

- Return isEnterprise for all service providers

<br><br>
## 3.7.2 (2018-5-10)
### Patches 

- Add service provider id and group id to group devices

<br><br>
## 3.7.1 (2018-5-10)
Initial release

<br><br>
## 3.7.0 (2018-5-10)
### Minor Changes 

- Added documentation
- Add cors
- Phone number search

<br><br>
## 3.6.1 (2018-5-8)
sync with web

<br><br>
## 3.6.0 (2018-5-8)
### Minor Changes 

- Initial integration configuration for emu sso
- Bulk user outgoing calling plans
- Add VDM Custom Config to product master
- VDM Group Device List

<br><br>
## 3.5.1 (2018-5-4)
### Patches 

- Fixed nill for email address and other fields in user modify request
- Fix userModifyRequest

<br><br>
## 3.5.0 (2018-5-2)
### Minor Changes 

- Added bulk for call recording, hoteling guest and hoteling host
- Added voice messaging

### Patches 

- Fixed numberOfRings not nillable
- Fixed xml CFNA
- Fixed routes on new bulk voice messaging and hoteling hosts

<br><br>
## 3.4.0 (2018-5-1)
### Minor Changes 

- Added cfa bulk endpoint
- Bulk CFA
- Added bulk for user call features
- Update bulk actions for users

### Patches 

- Modified return object for bulk user services
- UserIdShort should be a string

<br><br>
## 3.3.2 (2018-4-28)
Initial release

<br><br>
## 3.3.0 (2018-4-24)
### Patches 

- Added check for isEnterprise for enterprise voice vpn
- Added check for enterprise clid for redirecting identity
- Added if schedule group = group to clone
- Moved group clone services as top priority before all other features in the clone process
- Fix user call records search for virtual users

<br><br>
## 3.2.5 (2018-4-20)
Initial release

<br><br>
## 3.2.4 (2018-4-20)
### Patches 

- Fix branding application routing bug

<br><br>
## 3.2.3 (2018-4-19)
Sync

<br><br>
## 3.2.2 (2018-4-19)
### Patches 

- Change UI routes
- Change user permissions
- Bypass limit for downloading csv data for call records
- Finish group device configurations.  added rebuild/reset to all tabs.  
- Added sso test
- Common phone list oci calls
- Beginning of common phone list
- Configurable url in sso test
- Custom phone list complete
- Service user search
- Add to service search by service type
- Added group call processing policy
- Clone branding
- Added check for call processing and commented out enterprise calls

<br><br>
## 3.2.1 (2018-4-3)
### Patches 

- Call records to releaseTime instead of utc
- Change releasetTime for user call records too

<br><br>
## 3.2.0 (2018-3-30)
### Minor Changes 

- Migration fix for timezone
- Group network class of service
- Service provider network class of service API
- System network class of service
- Added replicate service pack service
- New routes model
- Added Replicate Calling Plan Digit Plan Call me now
- UserCallRecords
- Update CdrCallRecord data to use compression
- Clone Service Provider.  Also renamed all the Replicate classes to CloneX
- Clone group
- Clone services implementation

### Patches 

- Added check for service pack before adding
- Fixed replicate group service
- New CdrCallRecords migration to re-enable partitions
- Fix network class of service ent replicate
- Move call record search to use releaseTimeUtc as JSON is sending it over that way
- Fix bug in clone group in service packs
- Outgoing calling plan error

<br><br>
## 3.1.2 (2018-3-14)
sync with odinweb

<br><br>
## 3.1.1 (2018-3-14)
No changes, released to sync with web release.

<br><br>
## 3.1.0 (2018-3-13)
### Database Migration
This release requires a DB migration to be run.
```
docker-compose exec api php artisan migrate
```



### Minor Changes 

- Update some 5.6 queue settings
- Added meet me conference add endpoints
- Added meet me user delegate
- Added enterprise voice vpn and network class of service
- Added oci calls for Group Call Processing Policy
- Added group call processing
- Added network class of services
- Added GroupNetworkClassOfService oci calls
- Group policy
- Added group feature access codes
- Added oci group feature access code
- Added Call Processing and full Enterprise and group clone object
- Added Group Policy
- Added schedule and event cloning to bulk
- Added example of catching and rethrowing an exception in ReplicateEnterprise
- User search implementation
- Added group search
- Added DeviceSearch.  added search by mac to UserSearch.
- Add user greetings api
- User greetings v20+
- Add module permissions to  voice message advanced and trunk group authentication

### Patches 

- Fix bug in webhook
- Fixed users available and assigned api for meetme
- Notes on search for user by mac
- Fix bug in UserSearch

<br><br>
## 3.0.21 (2018-2-23)
### Patches 

- Auto activate phone number on assignment to user
- Moved activate phone number to event model so we can re-use it on other things
- Added meetme conferencing user oci calls
- Some helpers for call forwarding selective


<br><br>
## 3.0.20 (2018-2-22)
### Patches 

- Added instant room endpoint and bridge
- Add department information group admins
- Removed schedule bug from my room
- Colloboration audio apis added and fixed
- Added regenerate api fix

<br><br>
## 3.0.19 (2018-2-20)
### Patches 

- Bug in ACL check.  8216204018daf95d7a73b51cc5013938a7f25775

<br><br>
## 3.0.18 (2018-2-20)
### Patches 

- Dont send user.login webhook events unless specified in custom events

<br><br>
## 3.0.17 (2018-2-20)
### Patches 

- Added better debug logging for webhook

<br><br>
## 3.0.16 (2018-2-20)
### Patches 

- Alternate numbers user bug fix

<br><br>
## 3.0.15 (2018-2-19)
### Patches 

- Release must be outside path
- Robot
- Keep original www.conf for reference
- Broadworks.request

<br><br>
## 3.0.13 (2018-2-12)
### Patches 

- Change migrations to copy tables instead of renaming - for incremental upgrades
- Updated migration for v2 upgrade path
- Fix select number bug on virtual users.  closes parkbenchsolutions/docs#383
- Fix call center - whisper message only for premium
- Missing endif in overflow xml. 41fb1d442ab24b002f37457ca0846cbc0f0ff218
- Moh virtual user does not have access to upload individual announcements - moved to group upload.  
- UI error in Event creation.  XML Error in Event Add for non-repeating events.  closes 
- Fix permissions issue in Enterprise trunk as a Service Provider.  
- Fix issue with adding trunk groups to enterprise trunks as a groupEnterpriseTrunk.  

<br><br>
## 3.0.10 (2018-2-6)
### Patches 

- Added calling line id delivery blocking bulk
- Initial calling plan for users
- add user services to group dashboard
- Added anonymous call rejection bulk
- Added automatic callback bulk
- Added oci/api for automatic hold and retrieve for group and user
- Added automatic hold retrieve user
- Finish up user outgoing calling plan group view
- Added automatic hold retrieve
- Fixed up outgoing calling plan for group
- Fix up incoming calling plans for group
- Clean up group outgoing digit plan
- Update outgoing pinhole digit plan for group
- Touch up group transfer numbers
- Clean up extra calling plan calls - meetme
- Fix group default on user views for calling plans
- Update routes and redirects
- Auto attendant submenu

<br><br>
## 3.0.9 (2018-1-29)
### Patches 

- Fixed collab oci get request
- Added collaborate angular code needs user assignment
- Outgoigcallingplan for user
- User authorization codes
- Added end point Group Call Forward and Call Forwarding Busy
- Added cfna bulk
- Added forwarding not reachable callingLineIDDelivery
- Added service and component
- Added call fowarding no answer bulk user view
- Fix service pack services in user view.  Closes parkbench/odinapi#365
- Remove loadServices call to avoid multiple service calls overriding the isLoading
- Remove loadServices call to avoid overriding the isLoading
- Bulk cleanup and call forward always add
- Cleanup calling plans for user, finish incoming
- Added call forwding busy bulk
- User outgoing digit plan
- Added call forwarding not reachable bulk
- Pinhole digit plan for user
- Transfer-number for user calling plans
- Added ability to center switch inside parent pbs-input-switch="centered"


<br><br>
## 3.0.8 (2018-1-24)
### Patches 

- List huntgroups updated to components + no-parent-click directive
- Huntgroup pull in v20 calls - update ui
- Finish huntgroup.  add assign services component for virtual users.  modify tabs to allow a tab to be removed and added.

<br><br>
## 3.0.7 (2018-1-23)
IGNORE - testing deploy automated builds.

<br><br>
## 3.0.4 (2018-1-23)
### Patches 

- Added oci calls for sp access devices
- Added CPE rebuild/reset
- Added device endpoint for service provider
- Import csv strip non-unicode chars
- Added system  collab
- System collaborate oci
- Added group collab
- Added end point for collab
- Added collaborate
- Added group collaborate modify request
- Added collaborate add instance request
- Check for servicepack authorization before assigned user services to group dashboard
- Added system level device crud.  also created single componenets to use within app
- Add service provider devices to UI
- Enable updated sp and system devices within app
- Css customization
- Added collaborate at group level
- Added bulk user report for group outgoing calling plan
- Added routes for user bulk get
- Return device level for index calls on devices.  Closes #353
- Fix MOH if moving from external source to custom source.  Closes parkbenchsolutions/docs #352
- Added group outgoing calling plan
- Finish group schedules (update/destroy).  Add full CSV example for bulk user.create


<br><br>
## 3.0.3 (2018-1-8)
### Patches 

- Add support for System level user device for User Reports

<br><br>
## 3.0.2 (2018-1-7)
### Patches 

- Fix typo

<br><br>
## 3.0.1 (2018-1-7)
### Patches 

- Calling Plans and Viewable Service Packs permissions for Group View

<br><br>
## 3.0.0 (2018-1-4)
### Major Changes 

- 3.0 Initial Launch.  Backwards incompatible with 2.x series.

<br><br>