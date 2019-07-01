# Web Latest Releases
## 4.1.1 (2019-4-29)
Fix bug in custom CSS feature

<br><br>
## 4.1.0 (2019-4-29)
Merge System and Provisioning Dashboard

<br><br>
## 4.0.1 (2019-4-29)
Fix user password change bug with IM&P

<br><br>
## 4.0.0 (2019-4-25)
  https://www.parkbenchsolutions.com/announcement-odin4
  - Online docs now available for Odin Web at https://webdocs.parkbenchsolutions.com
  - Multi-tenant support
  - User dashboard upgrades
  - Automatic Audio Conversion
  - User Services Reports Upgrade
  - Call Center Queue Live Reports
  - New User Call Reports
  - Project Rooms
  - Download large CSV files of Call Report Raw Data
  - Group Admin Policy support

<br><br>
## 3.17.45 (2019-5-9)
No changes, sync version with API

<br><br>
## 3.17.44 (2019-5-9)
No changes, sync version with API

<br><br>
## 3.17.43 (2019-5-9)
No changes, sync version with API

<br><br>
## 3.17.42 (2019-5-9)
No changes, sync version with API

<br><br>
## 3.17.41 (2019-5-9)
No changes, sync version with API

<br><br>
## 3.17.40 (2019-5-9)
Disable auto-fill on device passwords

<br><br>
## 3.17.39 (2019-5-8)
Fix bug on device updates where other components didn't reflect the changes

<br><br>
## 3.17.38 (2019-4-23)
No changes, sync version with API

<br><br>
## 3.17.37 (2019-4-23)
Don't log out users on lost connections

<br><br>
## 3.17.36 (2019-3-14)
No changes, sync version with API

<br><br>
## 3.17.35 (2019-3-14)
Add Branding Permissions to Delete/Create Groups

<br><br>
## 3.17.34 (2019-3-14)
- Attach branding Provisioning to Group Delete UI

<br><br>
## 3.17.32 (2019-2-4)
No changes.  Syncing with API release #.

<br><br>
## 3.17.30 (2019-2-4)
- User Simultaneous Ring Bug Fix

<br><br>
## 3.17.28 (2018-12-20)
- Call Center Agent Report link should not show on Group Admin dashboard unless Premium Call Records is enabled.


<br><br>
## 3.17.26 (2018-11-9)
- no changes, sync with API

<br><br>
## 3.17.25 (2018-11-9)
- fix error on AA submenu key announcement selection

<br><br>
## 3.17.24 (2018-11-9)
- fix auto attendant submenu personal announcement selection error

<br><br>
## 3.17.20 (2018-10-19)
No changes, sync version number with API. 

<br><br>
## 3.17.16 (2018-10-18)
- fix in auto attendant service search link
- fix service provider admin update
- fix system level network class of service

<br><br>
## 3.17.13 (2018-10-16)
- fixed bug in changing passwords on new users

<br><br>
## 3.17.12 (2018-10-16)
- move webfonts local

<br><br>
## 3.17.10 (2018-10-11)
Fixed a bug introduced in 3.17.5 that broke some schedule updates on UI

<br><br>
## 3.17.6 (2018-10-9)
sync with api

<br><br>
## 3.17.4 (2018-9-26)
### Patches 

- Added {{ phoneNumberDigits }} which is the user phone number with non-numbers stripped (eg: +1-5133334444 =&gt; 15133334444).  added {{ phoneNumberShort }} which is the user phone number with the country code stripped (eg: +1-5133334444 =&gt; 5133334444).
- Fix autoattendant status update

<br><br>
## 3.17.3 (2018-9-26)
no changes sync with API release

<br><br>
## 3.17.2 (2018-9-25)
### Patches 

- Update to department routing
- Update routing on callpark, callpickup, departments, schedules
- Update routes on announcements
- Allow slash in auto attendant
- Migrate some services to v2 routes

<br><br>
## 3.17.1 (2018-9-20)
### Patches 

- Fix compilation error

<br><br>
## 3.17.0 (2018-9-20)
### Minor Changes 

- add User Call Report component for groups
- Add answerIndicator and relatedCallIdReason to csv download of call records
- Add user privacy component
- Minor update on service packs UI
- Added group level feature access codes
- Update user privacy api
- Group schedule updated to accept a slash in name
- Update Group Event to use new API format to allow slashes
- Convert autoActivateNumber to string to make it editable in edit-in-place csv editor within the bulk create section
- Added feature access code reset at group level:
- Added feature access code refresh on reload of page
- Add alias of Client License -&gt; Alias Name for User Services assignment.  eg:  Client License 17 = BroadTouch Business Communicator Mobile - Video
- Added group speed dial 100 prefix to feature access codes
- Fixed verbage on speed dial 100 modal
- Added min and max length for speed dial 100
- Update Call Park service to allow slash in Group name
- Allow slashes in Call Pickup Group Name
- Support slashes in Department Names

### Patches 

- Bug in schedules filter.  closes parkbenchsolutions/support-exponential-e/issues/109
- Fix user call report firstname/lastname


<br><br>
## 3.16.3 (2018-9-7)
### Patches 

- Fixed speed dial 100 speed dial code
- Add Group Night Forwarding to Virtual Users configuration menu
- Update uc one bulk to recognize all Business Communicator device types
- Fix type in group collaborate router
- Add navigation back in collaborate instance

<br><br>
## 3.16.2 (2018-8-17)
sync with api

<br><br>
## 3.16.0 (2018-8-15)
### Minor Changes 

- Datetime parse re-implemented with fix on future date issues as well as a help section.
- PbsFormBuilder initial
- Create callback UI
- Rename webhooks
- Fix no response alerts.  fix footer not loading on refresh
- Add sticky footer
- Fix spacing in forms with columns under a subtitle
- Fix more spacing in forms
- Move service packs to tabs
- Added group routing profile
- Routing profile cleanup
- Change Undefined to Unspecified in Device create/update. 
- Added routing profile clone
- Add outgoing calling plan branding description
- Initial call center report
- Fix this week and last week
- Add outgoing calling plan branding to multi user
- Call center agent report
- UI updates for Call Center Agent Report
- Automatically add missing tags due to old templates on vdm.  sort menu items so the proper top item is opened
- Update current tag
- Add (default) to extension selection in bulk
- Re-validate bulk CSV page on cell edits
- AutoActivate on bulk user create

### Patches 

- Simplify favicons

<br><br>
## 3.15.2 (2018-7-10)
sync with api

<br><br>
## 3.15.1 (2018-7-10)
Initial release

<br><br>
## 3.15.0 (2018-7-10)
### Minor Changes 

- Squashed commit of the following:
- Move sessionTimeout to a Branding Settings component.  Added editCLID in branding settings to allow manual CLID editing
- Add permission checks inside trunk group users page
- Change permissions on Pilot User to Trunk Group - Pilot User -&gt; update

### Patches 

- Fix some minification issues due to last commit
- Run alerts in next event loop so can be called from async methods such as event handlers
- Fix UI display of group directory
- Fix UI on directory listings for service provider and user
- Remove hover in group directory listing

<br><br>
## 3.14.4 (2018-7-6)
### Patches 

- Add some min/max checks on call center forms
- Hide supervisors tab from basic call center apply branding to auto attendant report enforce branding permissions to enterprise trunk

<br><br>
## 3.14.3 (2018-7-5)
### Patches 

- upgrade angular 1.7 
- Update switch css

<br><br>
## 3.14.2 (2018-7-4)
### Patches 

- Revert &quot;add session requirement to pbsRouteProvider&quot;

<br><br>
## 3.14.1 (2018-7-4)
### Patches 

- Add session requirement to pbsRouteProvider
- Added returnTo to navigation breadcrumbs Added groupId to User Report for Enterprise Turned user report into data table Added click to follow user on user report
- Untie password change from prov
- Remove tie to provisioning for user password
- Fix notfound page with back button

<br><br>
## 3.14.0 (2018-7-3)
### Minor Changes 

- Upgrade deps
- Upgrade angular
- Update bounced calls for call center - allow on basic if &gt;= R20
- Enterprise users report
- Update pbsDataTable to work with onClick changes in angular 1.7 update prepare group userServices and groupServices for a branding module add provisioning panel to enterprise admin dashboard  - contains read-only User Services, read-only Group Services, read-only  Numbers  - contains service packs based on Service Packs branding Add Service Pack module permission checking to Ent Service Pack page Hide assign services on Virtual User menu if Provisioning read is disabled

### Patches 

- Added required field for collaborate room

<br><br>
## 3.13.1 (2018-6-29)
### Patches 

- Fix routing on call center to show overflow on basic
- Fixed group intercept
- Add sort and download options to enterprise directory
- Make meetmeconference respect branding settings at user level
- Fix delete alert notification on meetme conf

<br><br>
## 3.13.0 (2018-6-28)
### Minor Changes 

- New checkbox, select, radio, switch directives
- Changed users panel to show first/last name
- Provisioning-&gt;Group-&gt;read required to see aliases and endpoints for a user.  Provisioning-&gt;Group-&gt;update required to modify it
- Switch to sp name and gp name in panels

### Patches 

- Hide routing for basic call centers
- Fix announcements - allow selecting Group Level announcements and attaching to Call Center instance

<br><br>
## 3.12.0 (2018-6-21)
### Minor Changes 

- Added virtual on net
- Added guest association to hoteling host with release option
- Combine password and passcode into single view.
- Fix user announcement page for virtual users.  upgrade call center to use announcements

### Patches 

- Make tooltip not show a &lt;br&gt;, hide No File Selected for some browsers
- Check for service on group intercept
- Passcode directive was being called with Password params (min 6, max 60), should have been passcode params (min1, max 30)
- Notes for new checkbox css helper - suspected that the css helper is causing issue with modals and IE11
- Fix modal window from shrinking on dom element changes fix call centers to use announcements if on rel &gt; 20 update call center UI
- UI update on audio file create
- Check for call me now on digitplan and pinhole digit plan
- IE11 Modal CSS hacks

<br><br>
## 3.11.0 (2018-6-12)
- Added Group Night Forwarding
- Added User Night Forwarding
- Added Group Intercept
- fix user.create in bulk to not ask for selected users

<br><br>
## 3.10.0 (2018-6-11)
### Minor Changes 

- Update AA to use new callTime field
- Update numbers for groups
- Added number selection modal to use in group number assignment/activation

<br><br>
## 3.9.0 (2018-6-7)
### Minor Changes 

- Make group AA report search use new date format
- Initial webhook UI
- Administrators
- Minimal UI for webhook data
- Add login message
- Hero-foot on login page
- Add bulk to admin policies
- Bulk ui
- Changes to bulk select users UI.  also add selectAll to when selecting users
- Add select all for service pack creation.  add bulk to group services
- Add bulk to service provider services

### Patches 

- Fix parse error in aa report
- Extract dayStart and dayEnd into a DateService helper
- Don&#39;t show calling plans if not assigned
- Password2 removed from bulk as its not needed
- Fix bug in phone search.  119903d4b58b7339c006b04b5b39d1a2cceb4c4e

<br><br>
## 3.8.3 (2018-5-30)
### Patches 

- Fix service provider service licensing

<br><br>
## 3.8.2 (2018-5-30)
sync with api

<br><br>
## 3.8.1 (2018-5-30)
### Patches 

- Added x-xss-protection x-content-type-options x-frame-options referrer-policy strict-transport-security content-security-policy to proxy
- Fixed auto attendant permissions when only has - Standard assigned.  closes parkbenchsolutions/docs/issues/417

<br><br>
## 3.8.0 (2018-5-24)
### Minor Changes 

- Make all searches default to contains.  autofocus on search modal input
- Bulk edit group virtual pack
- Added autofocus directive to allow autofocus to work on subsequent modal openings

<br><br>
## 3.7.11 (2018-5-21)
### Patches 

- Remove old password match code that is no longer needed.

<br><br>
## 3.7.10 (2018-5-19)
### Patches 

- Passwords should not be required for editing group admins

<br><br>
## 3.7.9 (2018-5-18)
### Patches 

- Added generate password compoennt
- Move more password fields.  change meetme and paging to modal on create to be consistent with rest of app
- Add passcode component.  finish password replacement

<br><br>
## 3.7.8 (2018-5-16)
### Patches 

- Moved account code and auth code to end of table columns
- Tags to Configuration in VDM
- Fix table for system licensing.  closes parkbenchsolutions/docs/issues/422

<br><br>
## 3.7.7 (2018-5-15)
Initial release

<br><br>
## 3.7.6 (2018-5-15)
### Patches 

- Added answer indicator related call id reason call time and total time
- Hide Redirect Out of Primary Zone to Voicemail

<br><br>
## 3.7.5 (2018-5-15)
### Patches 

- Add options to selectPhoneNumber component (show-all and allow-manual).  Set show-all to Group CLID and User CLID.  Set allow-manual to User CLID.
- Url for bulk tasks with space in group or service provider was creating error on breadcrumb.  
- Push to talk fix
- Global dn search for provisioning and above

<br><br>
## 3.7.4 (2018-5-14)
Initial release

<br><br>
## 3.7.3 (2018-5-14)
### Patches 

- Fixed custom contact directories path
- Add filter to select service provider so we can restrict clone group to same type of enterprise/serviceprovider

<br><br>
## 3.7.2 (2018-5-10)
### Patches 

- Make last name the default field for user search
- Normalize search forms

<br><br>
## 3.7.1 (2018-5-10)
### Patches 

- Fix alternate entries edit modal not opening

<br><br>
## 3.7.0 (2018-5-10)
### Minor Changes 

- Allow service search across all types
- Small UI update on service search
- Search for phone numbers

### Patches 

- Fix data table search
- Fix user services bulk removing service

<br><br>
## 3.6.1 (2018-5-8)
### Minor Changes 

- Initial sso emu integration
- Bug in session loading in navigation component
- Sso
- Bulk outgoing calling plan originating
- Outgoing calling plans bulk edit
- Custom config to vdm
- VDM Group Device list
- Hide sso integration in applications

<br><br>
## 3.5.1 (2018-5-4)
### Patches 

- Fix device type search on group devices page

<br><br>
## 3.5.0 (2018-5-2)
### Minor Changes 

- Expand numbers for adding/removing from group
- Apply same numbers UI to service providers
- Added group user service get for CallRecording, HotelingHost and HotelingGuest
- Site-wide UI update, change all a and span buttons to a button.  lock buttons on update numbers
- Add first and last to pagination
- Make all filter buttons link color instead of primary color
- Contain toggle column in pbs data table
- Add filter inside range to sp numbers
- Voice Messaging user bulk

### Patches 

- Fix linting problems
- Enabled to is active

<br><br>
## 3.4.0 (2018-5-1)
### Minor Changes 

- Added random generate for password and passcode
- Add filtering capability to pbsDataTable.  add nested property support to pbsDataTable.  finish call forward always bulk
- Add group CFA to dashboard
- Change cfa to service
- Update user CLID in bulk

### Patches 

- Minor ui tweak
- Document drobdown button

<br><br>
## 3.3.2 (2018-4-28)
### Patches 

- Bulk UI updates
- Some additional ui updates

<br><br>
## 3.3.0 (2018-4-24)
### Minor Changes 

- Finish vir user
- Clean up all virtual user menu items

### Patches 

- Fix call record changes
- Fix group call record search

<br><br>
## 3.2.5 (2018-4-20)
### Patches 

- Fix css style on table

<br><br>
## 3.2.4 (2018-4-20)
### Patches 

- Fix users routing error

<br><br>
## 3.2.3 (2018-4-19)
### Patches 

- Remove auto attendant report from UI, as its not complete yet

<br><br>
## 3.2.2 (2018-4-19)
### Patches 

- Change UI route
- Update default web
- Default favicons
- Bypass limit downloading group cdr call records
- Switch to lastName as default
- Combine rebuild and reset commands into one for VDM.  
- Remove reference to Template (eg: t41) on customer views in VDM.  
- change Name to Template name in VDM.  Remove Device Template columns in VDM. Change LDAP tab to Directories in VDM.
- Add group device configuration
- Finish group device configurations.  added rebuild/reset to all tabs.  
- Sso implementation
- Beginning of common phone list
- Added csv upload capability to custom phone list e29cb616ba27284e323781fde81196bb429568a6
- Initial service search
- Fix branding on push to talk closes db3bba785a6a556091fc9652ac5feb70dff23af5
- Scrollable css
- Add service type to service search
- Fix NONE in phone number select.  
- Finished user service search
- Added group call processing policy:
- Update menu and tabs ui.  make reloadOnSearch false for all routes
- Move wizard to use pbs-menu
- Clone branding
- Fix typo on templates
- Add VDM to provisioning
- Created PbsRouteProvider to simplify routing - will allow us to do more with virtual users
- Typo in routes
- Updates on menu and tabs directive so you can deep link, even when embedding a menu inside a tab
- Move optional prefix to end of arguments
- Re-arrange auto attendants
- Fix route problem
- Remove logging
- Remove debug
- Fix submenu link
- Added section to pbs-menu.  moved aa to use menu. merge submenus into one screen
- Make call records reports inline
- Fly out!
- Move all module help to flyout
- Fixed call processing policy link
- Description OR url will show help


<br><br>
## 3.2.1 (2018-4-3)
### Patches 

- Add rebuild and reset button to user devices
- Switch to local json strings for call record searches
- Update on call records open - fixed bug

<br><br>
## 3.2.0 (2018-3-30)
### Minor Changes 

- Group network class of service
- Service provider network class of service
- System network class of service
- Added service component to reconcile service packs
- Added clone for groups
- Add premium call records for users.  9bdd9c2d47218c51ca08012aaa9c0863bc9b7fd1
- Clone service provider
- Add clone to sp panel
- Clone group
- Fixed error on group select
- Remove replicateGroupService replace with cloneGroup
- Revert changes to group services, add in filter by authorization status
- New clone services implementation
- Add logic for network class of service on group clone

### Patches 

- Call record search
- Remove sp and gp from group call records table as that is known already and taking up space
- Fix lint
- Fix typo.  
- Fix error in contact on group profile page
- Fixed services/servicepacks/networkclassofservice on service provider clone
- Revert

<br><br>
## 3.1.2 (2018-3-14)
### Patches 

- Add trunk name changes to trunk group - authentication permissions.  availabe in 3.1.2. 

<br><br>
## 3.1.1 (2018-3-14)
### Patches 

- Fix addresses permissions tied to provisioning in branding

<br><br>
## 3.1.0 (2018-3-13)
### Minor Changes 

- Slightly widen modals.  move custom css to end of loading to override anything before it
- Add horizon queue
- Add version to front-end footer. closes parkbenchsolutions/docs/issues/193
- Make auto generated passcodes the default for bulk create users.  
- Meet-me complete
- :added delegates for meet-me and fixed user sort for collaborate
- Template for user search
- Pbs-button-compact-bulk
- Global user search
- Add Group search
- Add service provider to group search list
- Add mac address for user search
- Restrict mac search to provisioning+ for now.  will need to loop through all groups to provider for sp admins.
- Added first name search and spid/gpid to results
- Add greetings to user voice messaging
- User greeting v20+
- Add module permissions to  voice message advanced and trunk group authentication

### Patches 

- Update version in package.json
- Clear service cache when modifying services on a group or sp.  closes parkbenchsolutions/docs/issues/398
- Fixed spelling error hoteling guest and host
- Upgrade font awesome
- Reset type on open for user search
- Only show search for SP admins and up
- Fix user search session persistence between login/logout
- Remove fontawesome svg because its not updating on class changes - move to web fonts

<br><br>
## 3.0.18 (2018-2-20)
In sync w/ api

<br><br>
## 3.0.17 (2018-2-20)


<br><br>
## 3.0.16 (2018-2-20)
### Patches 

- Autotag?
- Rewrite/fix alternate entries.  


<br><br>
## 3.0.15 (2018-2-19)
### Patches 

- Add static assets such as favicon and robots.txt

<br><br>