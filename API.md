# API Latest Releases
## 5.9.32 (2020-7-8)
### Patches 

- SendResetLink

<br><br>
## 5.9.31 (2020-7-8)
### Patches 

- Passing db to password reset

<br><br>
## 5.9.30 (2020-7-8)
### Patches 

- Added Helpers

<br><br>
## 5.9.29 (2020-7-8)
### Patches 

- Debug statements

<br><br>
## 5.9.28 (2020-7-8)
### Patches 

- Added database api user to Send Email

<br><br>
## 5.9.27 (2020-7-8)
### Patches 

- Email event trigger from database

<br><br>
## 5.9.26 (2020-7-8)
### Patches 

- Added db controller for self service controller

<br><br>
## 5.9.25 (2020-7-8)
5.9.25

<br><br>
## 5.9.24 (2020-7-8)
### Patches 

- Fixed cloud build

<br><br>
## 5.9.23 (2020-7-8)
### Patches 

- Added alternateUserId check to login info request
- Renamed isAlternateUserId
- Setup database for sending email notification token

<br><br>
## 5.9.22 (2020-7-7)
### Patches 

- Added shared call endpoint import support

<br><br>
## 5.9.21 (2020-7-6)
### Patches 

- Added comments to template admin request

<br><br>
## 5.9.20 (2020-7-1)
### Patches 

- Added api files for voice messagaging aliases

<br><br>
## 5.9.19 (2020-6-30)
### Patches 

- Fixed custom contact directories AIM

<br><br>
## 5.9.18 (2020-6-30)
### Patches 

- Added exception handling AIM for devices

<br><br>
## 5.9.17 (2020-6-29)
### Patches 

- Added service provider admin to AIM

<br><br>
## 5.9.16 (2020-6-29)
### Patches 

- Added table branding fixes

<br><br>
## 5.9.15 (2020-6-29)
sync with api

<br><br>
## 5.9.14 (2020-6-26)
### Patches 

- Added Call To Numbers to Priority Alert
- Add Call To Numbers to following Actions

<br><br>
## 5.9.13 (2020-6-26)
### Patches 

- Added credentials to the device import if accessDeviceCredentials is populated

<br><br>
## 5.9.12 (2020-6-26)
sync with web patches for firefox and device edit enhancements

<br><br>
## 5.9.11 (2020-6-26)
### Patches 

- Added mailbox url to user third party voice mail support
- Fixed blade file for mailbox url

<br><br>
## 5.9.10 (2020-6-26)
### Patches 

- Group policy aim added

<br><br>
## 5.9.9 (2020-6-26)
### Patches 

- Added group admin policy to aim
- Added group admin policy to audit

<br><br>
## 5.9.8 (2020-6-26)
### Patches 

- Initial commit for selective call acceptance
- Added Call To Number support for Selective Call Acceptance add and modify actions
- Added common blade file for call to numbers modify
- Fixed group admin import and audit

<br><br>
## 5.9.7 (2020-6-25)
### Patches 

- Fixed user push to talk empty list

<br><br>
## 5.9.6 (2020-6-25)
### Patches 

- Fixed department create helper bulk task

<br><br>
## 5.9.5 (2020-6-25)
### Patches 

- Call to numbers endpoint added
- Changed callToNumbers to array of objects
- Added user portal passcode update api bulk task
- Changed GroupDeviceLine back to GroupAccessDeviceGetUserListRequest GroupAccessDeviceGetUserListRequest21sp1 is not working
- Added user password update bulk

<br><br>
## 5.9.4 (2020-6-23)
### Patches 

- Fixed modify for department user during import
- Added device level group import for user

<br><br>
## 5.9.3 (2020-6-23)
### Patches 

- Fixed moving users on import of audit to a new group

<br><br>
## 5.9.2 (2020-6-22)
sync

<br><br>
## 5.9.1 (2020-6-22)
### Patches 

- Fixed debug statement

<br><br>
## 5.9.0 (2020-6-22)
### Minor Changes 

- Added group device type tag task and reset rebuild
- Added user push notification registration api call and fixed User Privacy import bug
- Shared call appearance report
- Added Audit Import Export Webhooks and Callbacks to product master
- Created 2 endpoints to reset password: 1. to receive email, 2. to update password. Email needs better formatting.
- Added ReCaptcha and fixed bugs
- Added system admin add request blade file
- Added Update Domain function for System, Service Providers and Groups Update System Domain and moved logic to OCI Class
- Branging resources for user quick features
- Added branding template options to chose landing pages for each different user type
- Added cluster api username and password config
- Added service provider routing profile
- Domains at the system level are added, updated and deleted with an array of domains
- Added Tags, File and Lines to Group, ServiceProvider and System Device and Device Types
- Added routing profile audit and import functions
- Added domain index acl for group and group department
- Added pre-alerting announcement to branding

### Patches 

- TrunkGroupIdentity and otgDtgIdentity fixed for Group Trunk Task
- Removed nil from group trunk group add
- Removed nill fro add instance request
- Made Reset Password Multitenant
- Fixed branding email save
- Fixed service provider routing profile update
- Fixed audit and import for departments

<br><br>
## 5.8.1 (2020-4-21)
### Patches 

- Added options merge into the import of each service

<br><br>
## 5.8.0 (2020-4-20)
### Minor Changes 

- Fixed reattempts on AIM
- Added rollback of a minute
- Changed delay for imports to 90 seconds
- Unset alias
- Moved hunt group to a higher priority
- Moved hunt group to import priority 4
- Added bulk integrated IMP
- Removed integrated imp requirement for isActive
- Removed debug integrated IMP
- Cfa bulk 2
- Adding Group change to exporter
- Added Group Device rebuild and reset to &#39;&#39;user.authentication.update&quot; task
- Added events for device reset and device rebuild
- Added new group device upsert bulk task
- Added serviceProvider options to serviceProvider import
- Fix group cloings bugs odinapi #16 &amp; #17 - Network Class of Service and Outgoing Calling Plan
- Added reset and rebuild to bulk device upsert
- Fixes service providers, group and bug with maxConcurrentTerminatingAlertingRequests
- MaxConcurrentTerminatingAlertingRequests checking value

### Patches 

- Lowered number of retries to 5
- Updated fieldname for maxConcurrentTerminatingAlertingRequests
- Cleaned up template
- Fix some data bug going into Export and Import tables

<br><br>
## 5.7.14 (2020-4-10)
### Patches 

- Added new group device upsert bulk task

<br><br>
## 5.7.13 (2020-4-9)
### Patches 

- Added user and group device use class
- Added Group Device rebuild and reset to &#39;&#39;user.authentication.update&quot; task
- Added events for device reset and device rebuild

<br><br>
## 5.7.12 (2020-4-7)
### Patches 

- Added bulk integrated IMP
- Removed integrated imp requirement for isActive
- Removed debug integrated IMP

<br><br>
## 5.7.11 (2020-4-4)
### Patches 

- Moved hunt group to import priority 4

<br><br>
## 5.7.10 (2020-4-4)
### Patches 

- Moved hunt group to a higher priority

<br><br>
## 5.7.9 (2020-4-3)
### Patches 

- Unset alias

<br><br>
## 5.7.8 (2020-4-3)
### Patches 

- Changed delay for imports to 90 seconds

<br><br>
## 5.7.7 (2020-4-3)
### Patches 

- Added rollback of a minute

<br><br>
## 5.7.6 (2020-4-3)
sync with api

<br><br>
## 5.7.5 (2020-4-3)
### Patches 

- Fixed reattempts on AIM

<br><br>
## 5.7.4 (2020-4-3)
### Patches 

- Lowered number of retries to 5

<br><br>
## 5.7.3 (2020-4-1)
### Minor Changes 

- Voice Messaging and Tls

### Patches 

- Fixed inboundSeconds outboundSeconds user call report
- Tls changes
- Added new trunk and group limit to bulk

<br><br>
## 5.7.2 (2020-3-27)
### Patches 

- Added new trunk and group limit to bulk

<br><br>
## 5.7.1 (2020-3-26)
### Patches 

- Removed debug statement
- Added voice password to event

<br><br>
## 5.7.0 (2020-3-23)
### Minor Changes 

- Steam tests for exports
- Export
- Export and import listener upgraded
- Export controller details json added
- Export logs
- Socket stream byte increase
- Added exports migration table
- Fixed bug with firstname add profile to last name
- Fixed collaborate bridge profile modify
- Fixed group trunk group pilotUserCallingLineIdentityForEmergencyCallsPolicy
- Fixed inboundSeconds outboundSeconds user call report

<br><br>
## 5.6.1 (2020-3-6)
### Patches 

- Fixed bug with firstname add profile to last name
- Fixed collaborate bridge profile modify
- Fixed group trunk group pilotUserCallingLineIdentityForEmergencyCallsPolicy

<br><br>
## 5.6.0 (2020-3-4)
### Patches 

- Socket stream byte increase

<br><br>
## 5.5.5 (2020-2-24)
sync with web

<br><br>
## 5.5.4 (2020-2-24)
sync with web

<br><br>
## 5.5.3 (2020-2-18)
sync with web

<br><br>
## 5.5.2 (2020-2-18)
### Patches 

- Stream export data

<br><br>
## 5.5.1 (2020-2-14)
### Patches 

- Fixed access level for system domains

<br><br>
## 5.5.0 (2020-2-14)
### Minor Changes 

- Series completion audit fix multiple instances
- Changed retries from 12 to 9 for audit import export
- Added domain support
- Added service provider domain clone

<br><br>
## 5.4.15 (2020-2-11)
sync with web

<br><br>
## 5.4.14 (2020-2-11)
### Patches 

- SipAliasList fix for  groupVoiceMessagingPortal import
- Fixed user voice messaging password
- Added group emergency zones to audit and import
- Added group emergency zones to audit and import

<br><br>
## 5.4.13 (2020-2-10)
### Patches 

- Fixed device type get
- Added comm pilot login for audio files if needed

<br><br>
## 5.4.12 (2020-2-10)
### Patches 

- Aa audio file fix import
- Fixed call center premium import

<br><br>
## 5.4.11 (2020-2-6)
sync with web

<br><br>
## 5.4.10 (2020-2-4)
### Patches 

- SeriesCompletion fix
- Series completion audit/import fix
- Fixed group services update is Valid
- Added group call processing module
- Fixed trunk group call capacity task json

<br><br>
## 5.4.9 (2020-1-31)
### Patches 

- Removed debug statments and return export id

<br><br>
## 5.4.8 (2020-1-31)
### Patches 

- Added export database cluster support

<br><br>
## 5.4.7 (2020-1-31)
### Patches 

- Export listener cluster db

<br><br>
## 5.4.6 (2020-1-31)
### Patches 

- Patch for cluster event database

<br><br>
## 5.4.5 (2020-1-31)
### Patches 

- Export database cluster fix

<br><br>
## 5.4.4 (2020-1-31)
### Patches 

- Database export cluster debugging

<br><br>
## 5.4.3 (2020-1-31)
patched export cluster db

<br><br>
## 5.4.2 (2020-1-31)
### Patches 

- Adding debug export

<br><br>
## 5.4.1 (2020-1-31)
sync with web

<br><br>
## 5.4.0 (2020-1-31)
### Minor Changes 

- Added export task
- Added create exports table migration

### Patches 

- Fixed completed status for export and query

<br><br>
## 5.3.6 (2020-1-29)
### Patches 

- Added group detail dn search report

<br><br>
## 5.3.5 (2020-1-28)
### Patches 

- Trunk Group Trunk Group Task Bulk
- Added system level default domain for logins
- Added announcementUrl
- Fixed series completion
- Fixed count error in tasks
- Added fix for call center agent skill

<br><br>
## 5.3.4 (2020-1-24)
### Patches 

- Group service update started
- Added r22 login info for alternate user id
- Added group service bulk task
- Task group dn bulk assignment
- Added trunk group call capacity task
- MaxActiveCall check Trunk Group Call Capacity

<br><br>
## 5.3.3 (2020-1-23)
### Patches 

- Added r22 login info for alternate user id

<br><br>
## 5.3.2 (2020-1-23)
### Minor Changes 

- Testing alternate user id
- Added alternate user id token
- Added bulk clone sp and group
- Added group device tag task bulk

<br><br>
## 5.3.1 (2020-1-23)
sync with web

<br><br>
## 5.3.0 (2020-1-23)
### Minor Changes 

- Added bulk bulk grp and sp clone

<br><br>
## 5.2.4 (2020-1-17)
sync with web

<br><br>
## 5.2.3 (2020-1-15)
### Patches 

- Added alias to service provider service pack

<br><br>
## 5.2.2 (2020-1-15)
sync with web

<br><br>
## 5.2.1 (2020-1-14)
sync with web

<br><br>
## 5.2.0 (2020-1-14)
### Minor Changes 

- Added service pack audit
- Service provider service packs and trunk import
- Added api for import data
- Import listener trunk
- Added group department permissions
- Fixed department create
- Added service provider password rules
- Fixed password rules bug
- Added group series completion
- Added user level event search
- Fixed OdinEvent Voice Messaging Greeting
- Added group call center enhanced reporting api for groups in a SP
- Added imports table and retry to import
- Added retry to audit
- Added attempt and next_at to audit
- Added User Enable Voice Mail Recording
- FIxed Group Calloborate default
- Added group call center enhanced reporting audit
- Added user privacy
- Fixed permissions on group password rules
- Added reseller access to System Service Controller
- Group music on hold import complete
- Group call park import added
- Added group night forwarding to import
- Added service provider domain to import
- Added group domain
- Added group paging
- Outgoing calling plans fixed
- Added group voice messaging setting
- Added after column to imports
- Added password change api
- Call center agent and call center events added

<br><br>
## 5.1.7 (2020-1-10)
sync with web

<br><br>
## 5.1.6 (2020-1-10)
### Patches 

- Added User Enable Voice Mail Recording
- Fixed permissions on group password rules
- Added reseller access to System Service Controller

<br><br>
## 5.1.5 (2020-1-7)
### Patches 

- Added group series completion
- Added user level event search
- Fixed OdinEvent Voice Messaging Greeting
- Added group call center enhanced reporting api for groups in a SP

<br><br>
## 5.1.4 (2020-1-3)
sync with api

<br><br>
## 5.1.3 (2020-1-3)
Sync with web

<br><br>
## 5.1.2 (2020-1-2)
### Patches 

- Fixed password rules bug

<br><br>
## 5.1.1 (2020-1-2)
### Patches 

- Added service provider password rules

<br><br>
## 5.1.0 (2020-1-2)
sync with web

<br><br>
## 5.0.14 (2020-1-1)
### Patches 

- Fixed department create

<br><br>
## 5.0.13 (2019-12-31)
Initial release

<br><br>
## 5.0.12 (2019-12-26)
### Patches 

- Groups/viewable-packs
- Added group department permissions

<br><br>
## 5.0.11 (2019-12-19)
### Patches 

- Added service pack audit

<br><br>
## 5.0.10 (2019-12-17)
### Patches 

- Added group department admin to tasks auth
- Added group device access to department admin

<br><br>
## 5.0.9 (2019-12-12)
### Patches 

- Added failed job and retries for audit

<br><br>