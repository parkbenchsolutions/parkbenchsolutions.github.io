
# API Current Release <small>([View All](/API.md))</small>
## 5.34.0 (2021-12-9)
### Minor Changes 

- Scaffolding for apply import options
- Added short tags to audit
- New audit procedure
- Apply import options
- Added import options tests + refactored tests to use OdinTestCase
- A bit more testing
- Add audit data enrichment feature
- Handle array of users param for enriching
- Conditionally enrichAuditData
- Refactored BackupRecoveryClasses to use for import/audit mapping
- Wip update
- Update items to the array style
- Templates added + reconfig get items
- Audit now supports more flexible transformation configuration
- Tweaked audit+import listeners
- Audit enrich lists of users
- A bit more cleanup
- Enrich audit data update on audit job
- Updated audit.group.settings.Admins for testing audit run
- Can now use deeper users nesting
- Added audit template feature
- Added audit templates endpoint
- Added templates used on FE
- Added endpoint to run audit via template
- Enable audit enrichment for Basic Template classes
- Pass options along to children
- Remove advanced template
- Variety of features
- Added base to other audit classes
- Move tests to run as test suite
- Remove audit options from all except parent on completion
- UserIdPrefix and userIdSuffix now appear in ShortTags
- Update label in BLF callback template
- Apply template transformations on export instead of import
- Export sets top level params
- Updates
- Bulk delete for import/export/audit
- More updates
- Bug fix
- Fix: login to endpoint causes exception
- Refactoring of transform lists + export options
- Transform all root userIds
- Add audit queue delay
- Refactored audit job state sequence
- Export state changes update + additional audit user list keys
- Refactored import user + import state changes update
- Improvements to import
- Refactored status setting + exception handling for aim
- Add status + remaining for export job
- Refresh the session token for exports
- Clear the options for child export jobs
- Clear options for child import jobs
- Updated full template
- Reworked templates to specify includes for audit
- Fixed: trait response compatible with Base
- User call center
- Fix: audit/import of callcenter agent-like targets
- Feature: rerun audits
- Audit device user settings option + switch logic for user voice messaging
- Other classes to transform
- More transforms
- Add call processing policy transform
- Feature: rerun/delete audit jobs
- All core audits skip if not defined in template
- feature access code change added to backup recovery
- Add feature access code to basic template
- Two templates
- Created Classes\AIM folder and moved templates+helpers
- Resolved scott&#39;s comments
- Templates can be individually run + can specify each type of includes
- Wip
- Finish splitting out the audit items
- Fetches destination userIds for mapping
- Match destination phone number for userId
- Handle tripartite targets like callParkGroup.instances.users
- Add rerun endpoint for export
- Added cluster hostname for OdinTestCase
- Added items to UserServiceInstances Template
- Add dial plan policy classes to audit
- Add excludes option to templates
- Add Clarity Template
- SP trunk group call capacity aim not assigned
- Rename clarity template
- Added group password rules
- Audit/import for group device files
- Added voice messaging greeting to bulk
- Added fusion-cypress to cloud build
- Add support for v22 Service Provider PasswordRules
- Add update alternate entries
- Added group dial plan policy
- Added service is not assigned aim
- Fixed aim ServiceProviderTrunkGroupCallCapacity not authorized
- Fixed use schedule update return
- Added GroupPagingGroupTargetCapacity OCI call
- Add to GroupClone and AIM
- Update controller class call
- Update templates and options
- Add group to basic template
- Link audit/import for groupPagingGroupTargetCapacity to the GroupPagingGroup
- Patch for sca bulk

### Patches 

- Interpolate
- Fixed name for attributes
- Fixed the import method
- Refactored to allow for specifying any userId field to update

<br><br>
# Web Current Release <small>([View All](/Web.md))</small>
## 5.33.21 (2021-12-6)
### Patches 

- 1581- calling plan group auth code
- 835 Porting Group calling plan - Code management #1578
- #1564 service fixes showing for enterprise level / not sp level
- #1905 ui fixes - user dashboard - group
- CLID for redirected calls section is added
- Fixes and changes for grp calling plan -code management
- Announcement fixes for group and users level
- User dashboard ui changes
- Ui dashboard menu service fixes
- Group Services Branding Alias Not Showing On Department Dashboard - Common Phone List And Enterprise Directory
- Revert code
- Fix group dashboard group service user feature need refresh after assignment
- Remove unnecessary parms
- 743 Group Admin Policy Number Activation
- Bulk wizard  ui is messed of import sheet fix
- Can change agent skill level on Odin Portel #2086
- Adding validation check for Skill Level value

  