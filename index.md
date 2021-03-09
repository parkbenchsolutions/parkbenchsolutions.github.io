
# API Current Release <small>([View All](/API.md))</small>
## 5.20.3 (2021-3-9)
### Patches 

- Added trunk group call capacity to clone

<br><br>
# Web Current Release <small>([View All](/Web.md))</small>
## 5.21.0 (2021-3-9)
### Minor Changes 

- Executive service permissions
- Active / deactive criteria name from filtering
- Fixes - undefined messageSourceSelection - music on hold files

### Patches 

- Branding assistants
- Disabled button message
- Space between music on hold , fixes for helpModule={&lt;AppHelp module=&quot;Alternate Numbers&quot; /&gt;} instead of helpModule={&lt;AppHelp module=&quot;Speed Dial 100&quot; /&gt;}
- Space between cards - music on hold

1.  More spacing in user Music On Hold into file 'src/components/users/service-settings/user-music-on-hold.js' line number 180, 201, 204, 221. 

2. Change the helpModule  ="Speed Dial 100" 
 instead of  helpModule = "Alternate Numbers"  into file 'src/components/users/service-settings/user-alternate-numbers.js' line number 129.

3. Add line  'export * from ./user-executive/user-executive-index' into root file 'src/components/users/service-settings/index.js'
Line number 30.

4. Add module name line 'UserExecutiveIndex' in file 'src/components/users/user-service-routes.js'
line number 27.
with component details 
{
	component: UserExecutiveIndex,
	module: 'Executive',
	path: 'executive',
	services: ['Executive']
}


  