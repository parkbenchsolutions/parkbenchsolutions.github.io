
# API Current Release <small>([View All](/API.md))</small>
## 4.7.0 (2019-8-9)
### Minor Changes 

- Added bulk dn assignment endpoints for service provider and group
- Added user schedule endpoints
- Allow webhooks to run as the user that initiated the change if configured to do so

### Patches 

- Remove cache for system domain and version

<br><br>
# Web Current Release <small>([View All](/Web.md))</small>
## 4.7.0 (2019-8-9)
### Minor Changes 

- Added the ability to bulk assign DNs to Service Providers and Groups
- Added UI for User Schedules
- Add Webhook configuration option to send user auth token

### Patches 

- Bulk user create was missing phoneNumber and extension fields on CSV download when leave blank was selected in the wizard
- Clear local cache on logout

  