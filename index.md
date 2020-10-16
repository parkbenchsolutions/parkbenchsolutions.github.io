
# API Current Release <small>([View All](/API.md))</small>
## 5.12.0 (2020-10-16)
### Minor Changes 

- Added new oci call v22v2 for call processing policies
- Service instance profile alias for group level services
- Added device tag events
- Added resource to cloning
- Added delete to brandind resources
- Fixed response for visual voicemail where no messages are found
- Fixed voice messaging when one message is returned
- Fixed account authorization codes for groups
- Added forgot password and reset password to template branding
- Added columns to resetPassword and forgotPassword
- Added group call processing policy version 22
- Added system media support
- Media to Media
- Make email case insensitive
- Added serviceProviderId groupId deviceName to tag change event
- Fixed service provider call processing policy bug for enterprise calls
- Added group call processing policy for 21sp1
- Added group call processing policy call 21sp1
- Added user speed dial 100 bulk task
- Fixed call processing version 22 get request
- Fixed authentication bulk to check if service is assigned
- Merge pull request #101 from parkbenchsolutions/branding/account-auth-codes

### Patches 

- Added system media set name api
- Added speed dial 100 trait
- Merge pull request #100 from parkbenchsolutions/feature/speed-dial-100-002
- Added account auth code admin login history and support to branding

<br><br>
# Web Current Release <small>([View All](/Web.md))</small>
## 5.11.5 (2020-10-16)
### Patches 

- Set up empty component for call forwarding history
- Added some content to the history component, hard coded strings  will be removed and replaced with variables
- Added an import for the history component to the ucfa component. set up a react-query call to make a call to the events endpoint filtering by the userId -- right now it is commented out to prevent a lot of calls to the API -- soon will add a more dynamic approach to the axios call by creating a history service file
- Changed the token to be accessing the localstorage token rather, will change this to be more dynamic eventually
- Added a call forwarding history service, in process of setting up api.show on the history side
- Changed the limit query
- Some more updates on history service
- Created a ui-accordion component that takes data and displays a diff of the changesfrom before and after. as of now it only really is reliable for the call forwarding always component but it gets the job done. still need to add a few things to make it fully functional
- Pop out menus now working when clicking the ellipsis
- Full functionality for selecting a previous history with accordion dropdown
- Took out an unneccesary line
- Took out unused variables
- Cleaned up scss file and a bit of the accordion component
- Added consistensy between the history tabs and the cfa card above
- Added useMutation hook but it&#39;s still not refetching on the update of CFA working on it still: - Tried to implement the useMutation hook but to no success
- Took away colons and changed the text of the Forward to Phone Number for better consistensy: - Changed to appropriate proptypes
- Updated react-query dependency, histories now update as a new PUT goes through to change their status of CFA: - Set a fake delay on the save edit that will help with the refetch of the cache. will try to move it off of a fake timeout eventually.: - Testing the invalidatingQueries method
- Added note to change title back to date
- Updated comments
- Trying to set up a way to update the histories
- Added a setTimeout to the useMutation hook to allow the user to update their history on edit
- Changed the title of the accordions to the date stamp, using the full date and time. Made it prettier by spacing it out and making it a bit more readable
- Cleaned up comments
- Added username to the title of the accordions
- Added an informative tooltip to tell the user that their update may not reflect in the history for a few minutes: - Updated spacing: - User-pre-alerting service fixes done expected api issue
- Took out unused style
- Putting the conversion to local time on the back burner to work on decoupling some of the code to make it a more reuseable component
- Moved some of the beefy functions under the component to take up less space
- Pulled the hardcoded method &#39;invalidateQueries&#39; into it&#39;s own function in the history service which allows any component to call the invalidate queries on the history
- Pulled out all of the hard coded queries into the history service located in a generate history queries fn startDate and endDate are not yet dynamic but are in the starting phases of being changed
- Search functionality partially works. I can&#39;t seem to narrow the search down on any other day rather than the current day
- Implemented a drop down calendar to allow the user to select a range of dates to filter histories
- Took out some unused variables
- Removed unused comments and code
- Branding module permissions
- Password rules service
- Group passworld rules services
- Service provider password rules
- Password rules
- Reset password rules
- Breaking functions into smaller peices to make them more reuseable
- Removed unnecessary methods inside of the history service file and created a more reuseable index method that takes a url and a set of parameters
- Created an events api library for the CFA History. Moved all of the API calls out of the history-service.js Now the CFA History component is referencing the api from the events and providing it all of the data that it needs in order to show the correct histories
- Service provider branding groups
- Change group services api path and night forwarding
- Branding data changes
- Event history permissions
- Sp barnding settings changes
- Removed unused comments
- Formatted the code
- Git status
- Moved some of the varibales underneath the state so it has access to it
- Reverted some changes back
- Remove unwanted code
- Group collaborate audio
- Group collaborate audio
- Group collaborate audio
- Pre alerting
- Password rules changes
- Removed cfa-history-service and made it more generic with a /api/common/invalidate-queries that takes a user id and a query cache key that invalidates the queries asked for. change the api call on cfaHistory to eventsApi to make it more clear that we are using the api from the events. also changed the name of cfaApi to just api to make it more consistent between cfa and cfaHistory.
- Reverted the package.json back to its original state - only updated react-query
- Changed a comment to me a bit more informative
91ac2e2594353380f47c6f08cda5fed5492bc4ea
- Collaborate audio
- Collaborate audio
82b1b005cc5978f488958c4c496b240616e9fc5f
- Collaborate audio
- Visual voice messaging, react query fixes
- Collaborate audio
- Removed the configs for useQuery in voice-msg-checks.js so that now Visual Voice Mail is being displayed on the menu
- Collaborate audio
- Collaborate audio
- Revert visual voice messaging
- Group api path changes
- !!!visual voice mail not showing up!!! #576
- Group collaborate
- Group collaborate
- Changes for event history
- Added forgot password and reset password template show/hide
aa17ff922e370e982451cd10890d439ecb3acedc
- Forgot and reset password permission
- Forgot and reset password permission
- Forget password
- Remove unwanted code
- Changes replace permission for ent trunk group
- Fixes
d170ea09d6f11f49d364d0a04d5214993d3b59d7
- Password reset for reseller fixes #551


  