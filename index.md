
# API Current Release <small>([View All](/API.md))</small>
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
# Web Current Release <small>([View All](/Web.md))</small>
## 5.8.0 (2020-4-20)
### Minor Changes 

- SIP trunking
- Editable table
- SIP trunking service file
- SIP Trunking users
- SIP Trunking
- Bulk create user tags
- Bulk download task
- Bulk create user address
- Library for sip trunking
- SIP Trunking, Trunk Group Creation
- SIP user services
- SIP auth Password Rules
- User count on group cloning
- Import csv
- SIP Trunking Add Devices
- SIP trunking menu
- Rebuilt and Reset on SIP Authentication
- SIP Trunking, Device upsert
- SIP Trunking rebuild and reset on device,upsert
- Cleaned up never used values in react code base
- Updated audits to support group and service provider changes

### Patches 

- Sip Auth Fixes
- SIP Trunking Pilot User
- Button alignment
- Sip Trunking pilot user
- Button color
- SIP Trunking Upload Task
- Bulk clear local storage
- Table border issue
- Network Classes of Services Default selcetion issue #221
- Rolled back &quot;react-query&quot;: &quot;^0.3.24&quot;
- SIP Trunking authentication issue on the sheet

  