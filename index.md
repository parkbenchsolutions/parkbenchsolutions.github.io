
# API Current Release <small>([View All](/API.md))</small>
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
# Web Current Release <small>([View All](/Web.md))</small>
## 5.29.2 (2021-5-11)
### Patches 

- Patched is pilot User Id true or false

  