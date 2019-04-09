# Tableau-Dashboards-on-TVs

Putting dashboards around in kiosk mode with a Chrome revolver tab will artificially inflate the number of times that a user consumes server resources.  With this process we are able to centrally control and monitor all dashboard use for embedded purposes displayed on TVs through the organization.  When a dashboard is not put through this centralized process, an unnecessary amount of server resources are consumed by placing the Chrome Revolver to refresh the data content.  With this we use the Tableau Server API function to refresh the data source at an interval that makes sense for the dashboard displayed.

Source files stored in a central repository.

## Directions

Process for rolling out new display

### Create source file

Copy source file and change the following fields:

* line 36 - URL

For URL, only add the dashboard/viewName

### Publish File

Publish in the App Deploy network folder

//NF2/AppDeploy/Tableau/Miscellany/Dashboards/location/viewname.html