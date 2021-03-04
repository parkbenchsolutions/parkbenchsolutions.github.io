
# API Current Release <small>([View All](/API.md))</small>
## 5.20.2 (2021-3-4)
### Patches 

- Fixed url https for phonism device management

<br><br>
# Web Current Release <small>([View All](/Web.md))</small>
## 5.20.1 (2021-3-3)
### Patches 

- Created files for the group phonism devices
- Filterd devices by macaddress
- When clicking on a device it now routes to the proper page
- Added a lib react-iframes. decided not to use react-iframes and just use a basic iframe tag. the html is rendered with the iframe and loads fine. now going to go through and refine the code.
- Added an iframe that takes the phonism gui and displays it to the screen
- Added a way to close the gui
- Added margin via a &lt;br/&gt; will need to change this
- Fixed proptypes errors
- Added a string method into this useState update hook so that way any mac address coming into the componenet is a string and not a number
- Added a dynamic title to the gui display changed some of the naming
- Created a loadConnectors method inside of group-dashboard that will load the available connectors -- created a connectors dir that contains connector-service.js that dispatches an action to grab connectors
- Updated axios from 0.19.0 to 0.21.1
- Fixed a conflict with the yarn.lock regarding axios
- Added hasConnector: phonism in dashboard menu and then commented out

  