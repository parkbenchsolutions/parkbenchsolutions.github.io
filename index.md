
# API Current Release <small>([View All](/API.md))</small>
## 4.10.0 (2019-9-23)
### Minor Changes 

- Added additional information into event captures such as the reseller
- Add API to download announcements if customMediaFiles web service is installed on BW

### Patches 

- Adder resellerId to service provider add request
- Fixed hunt group return data on updates
- Fix UC-One Bulk Error when Not assigning a Service Pack
- Add simple health check endpoint /health
- Add pubsub capabilities for queue
- Add check to prevent an Int type conversion on userIds under certain situations, that returned invalid ids. 
- Fix custom device tag modifications where a value of 0 was incorrectly set to null

<br><br>
# Web Current Release <small>([View All](/Web.md))</small>
## 4.10.0 (2019-9-23)
### Minor Changes 

- Added notification when the user password is expiring soon (< 14days)
- Add supported browser message for unsupported browsers
- Added new columns to events view to include more data
- Fixed the navbar dropdown rendering in Microsoft Edge

### Patches 

- Added reseller id to service provider create for service providers under a reseller


  