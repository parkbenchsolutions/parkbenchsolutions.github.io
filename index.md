
# API Current Release <small>([View All](/API.md))</small>
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
# Web Current Release <small>([View All](/Web.md))</small>
## 5.9.0 (2020-6-22)
### Minor Changes 

- Group dashboard settings
- Group dashboard
- Group dashboard service
- Ent dashboard
- Group - user services
- Group shedule
- Admin-dashboard changes
- Admin dashboard
- Reset Password
- Password-Reset-Option-at-Login-Screen
- Reset Password
- SIP Trunking wiz UI stuff
- SIP Trunking
- Merge pull request #37 from pankajs1306/SIP-Trunking-Upload-Wiz
- Group.device.tag.modify rebuild and reset #249. code committed on both angular code and reactJs code
- Merge pull request #257 from pankajs1306/Bulk-Task-Device-Tags
- Domain #193
- Domain changes
- System dashboard
- Merge pull request #266 from pankajs1306/shared-call-appearance-report
- Fixes for push-notification-registration
- Push-notification-registration-bulk
- Shared-call-appearance-report
- Push-notification-registration
- Domain delete code
- Added user icons
- Fixes clid multiple users
- Domain api
- Added user resources to the user quick features
- Added Landing pages to branding template section
- Added resources
- Add User Landing Pages setting to Branding Template
- Landing page default
- Forgot password
- Added branding email page
- Added service provider routing profile
- Added hoteling guest quick set
- Domains feature #193
- Grp assign domains #193
- Add Hubspot Support Form to Odin
- User Personal Phone List #351
- Download DID lists #378

### Patches 

- Group dashboard call park service
- Group dashboard reports
- Group Report
- Group dashboard routing fixes
- Group departments
- Group call pickup dashboard
- Group dashboard trunk group
- Group music on hold changes
- Group dashboard changes aa
- Group deshboard schedule
- Group departments
- Group dashboard call park
- Grp dept music on hold
- Calling plan fixes
- Fixes for : shared call appearance report #254
- Fixes for : SIPT Error at group trunk task #278
- Bulk service provider routing fixes
- Added padding to icons
- Auto selection service provider and group
- Update ui-menu.js
- Renamed Export To Migrate
- SIP trunk password (auto-generate) doesnt comply with BW rules. (bulk tool) #313
- Call forwading no number
- Group Call Pickup missing menu plus breadcrumb navigation is wrong #312 And Help icon for Group Services
- Removed N/A from hoteling guest from call handeling
- Fix: group admin schedules #373
- Fixes: Department detail has no left menu #374
- User-Personal-Phone-List : accept string also

  