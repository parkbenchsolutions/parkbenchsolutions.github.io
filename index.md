
# API Current Release <small>([View All](/API.md))</small>
## 5.32.12 (2021-9-14)
### Patches 

- Added System Licensing if user.login is system
- Added task for creating group communication barring authorization codes
- Created SystemLogin queue job to store system licensing report records weekly
- Set dispatch to send to listeners queue
- Report status=running when running
- Additional params in task calls are added to event &#39;after&#39; array
- Add attributes to events for device CRUD
- No need to pass attributes on delete
- Fixed virtualOnNetCallTypeName
- Hostname for primary
- HostnameForPrimary migration + added to event
- Added hostnameForPrimary to Tasks and Reports
- Cleanup
- Merge pull request #282 from parkbenchsolutions/feature/hostname-for-primary
- Audit fix for ServiceProviderDeviceType
- Merge from develop
- Removed wrapping task run with exception handling
- Use config param for queue dispatch delay value
- Return empty devices
- Merge pull request #283 from parkbenchsolutions/bug/aim-service-provider-device-type
- Merge pull request #278 from parkbenchsolutions/bug/queue-stalling
- GroupDeviceCreate passes along attributes through DeviceHelper
- Set queue delay to 3s
- Flow attributes into new event.incoming column
- Merge pull request #285 from parkbenchsolutions/chore/set-queue-delay-3
- Added attributes to other calls
- Switched from incoming to options - complete
- Disable fkconstraints during events column update
- Merge pull request #284 from parkbenchsolutions/bug/phonism-create-device

<br><br>
# Web Current Release <small>([View All](/Web.md))</small>
## 5.32.11 (2021-9-2)
### Patches 

- 860 Assign Number Module Issue . notation changes
- Fixed the default extension for announcements

  