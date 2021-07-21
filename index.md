
# API Current Release <small>([View All](/API.md))</small>
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
# Web Current Release <small>([View All](/Web.md))</small>
## 5.31.1 (2021-7-1)
- fixed api call for access device endpoint contact list

  