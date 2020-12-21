
# API Current Release <small>([View All](/API.md))</small>
## 5.15.0 (2020-12-21)
### Minor Changes 

- Added cache to the system domains and the software version
- Fixed call forwarding selective import
- Fixed call forwarding selective AIM import
- Fixed service provider dn AIM import
- Fixed call capacity issues AIM import for new group id
- Service Provider Schedules and Event APIs
- Fixed bug with group incoming calling plans import
- Added clone-aim-api for service provider schedules
- Fixed max failed login attempts and password expires days when updating a zero value
- Fixed cfa for users
- Added error checking for user voice messaging AIM
- Added code for submenu to not abort of fail aim
- Fixed dnis issue for aim
- Added controller and routes
- Added api cor call center agent unavailable
- Remove event comments and added xsd document to Enterprise Call Center Request
- Added api route for enterprise call center enhanced reporting
- Fix service provider schedule aim import
- Fixed enterprise schedules AIM and update function
- Fixed voice messaging portal AIM

<br><br>
# Web Current Release <small>([View All](/Web.md))</small>
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

  