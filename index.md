
# API Current Release <small>([View All](/API.md))</small>
## 5.30.1 (2021-5-21)
### Patches 

- Added throwable for user settings

<br><br>
# Web Current Release <small>([View All](/Web.md))</small>
## 5.30.0 (2021-5-21)
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

### Minor Changes 

- Announcement service - react-migration
- Group business directory commit code custom phone list
- 378 Porting Trunk Group Front Page #1071
- 378 Porting Department Trunk Group Front Page #1071
- Group business profile 409
- Porting/group-trunk-group
- Revert group meet me user announcement changes , fixes
- Porting/group-trunk-group
- Changes some to admin part for related to duplicate codes and add policy permission to group profile admin
- Added a .filter() to the previously filtered list of modules to determine which module has read: true
- Added e911 settings
- Group auto attendant
- Department parmissions
- Group auto attendant
- 380 Porting Department Trunk Group Call Capacity #1073
- Created a super basic component for e911 that, when visiting, it will automatically redirect to a new tab with the e911 url provided. The component only contains a button that will open a new tab with the url provided. The component, when opened, will make another call the e911 endpoint and dispatch an action to get a new e911 url.
- Added ambulance icon to the user dashboard menu for e911
- Removed the automatic redirect to e911 url
- Added an external link open button at the top of the e911 card component
- Added user address to the e911 component
- Added logic to take away add button in e911 settings that will show up if there are no endpoints available.
- Removed address line 2 from e911 component
- Added each piece of the address to their own line
- Added the main address
- 381 Porting Department Trunk Group Call Forward #1074
- Updated user e911 to better display address
- Group business profile fixes

### Patches 

- Error handling business directory
- Duplicate keys error resolved
- Remove delete button when add new common phone name
- Group business directory changes for getting data
- Alignment of code
- Added panelTitle class to the UiPanelLogo component for branding purposes
- Patched is pilot User Id true or false
- Group-administrator fixes
- Trunk group dashboard
- Porting/group-trunk-group left menu
- Added user settings endpoint
- Set up reducer, menu item that checks for module read, added the api call to the redux store, not fully working yet just committing in changes
- Switching between users shows that e911 menu tab will render if the user has the api call available. Does not display on user zakmayf but does display on revermans user
- Branding Departments #410
- Changed the function to have string values
- Error message fixes
- Added a button to link off page adjusting ui
- Added more space between button and message
- Fixes for: Issue with User Profile Address Input field, redirect to blank page when clicked #1334 Issue with Enterprise Admin Read Policy for Business Profile #1333
- Group business profile fixes select clid number none
- Auto attendant form validation req fields will disable save if not filled in

  