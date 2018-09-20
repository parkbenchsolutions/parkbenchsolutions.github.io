
# API Current Release <small>([View All](/API.md))</small>
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
# Web Current Release <small>([View All](/Web.md))</small>
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


  