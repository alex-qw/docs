## Granting Ad Partner Access

To grant an Ad Partner access to your App's data, you need to add them as an `agency` in your Branch account.  Doing so give's said ad partner access to your app; based on the permissions you define.

1. Go to **Account Settings** and click on the **Agencies** tab.
1. On the **Agencies** tab, click the **Add New Agency** button.
1. In the **Add New Agency** modal:
	1. Select the Agency name from the drop-down.
	1. Select the appropriate level of access.
		- **Admin** - Edit access to all settings and export access to all data.
		- **Team Member** - Edit access to channels and links, read-only access to app settings, and access to aggregate data.
		- **Full Read** - Read-only access to all settings and access to aggregate data.
		- **Limited Read**  - Access to aggregate data only.
		- **Custom** - Customize settings and data access.
		- **No Access** - no dashboard access.
	1. Click "Invite".
	1. All Agency Admins on the agency account will receive an invitation email, and any of those Agency Admins can accept the invitation on behalf of their agency.

!!! warning "Granting agencies Sensitive Data & App-Level Settings permissions"
	Agencies with Sensitive Data & App-Level Settings permissions to an Org or App will have access to that Org/App's API keys, which can be used to access Branch's [HTTP](https://docs.branch.io/apps/deep-linking-api/) and [Data Export](https://docs.branch.io/exports/api-v3/#__search) APIs. Agency data filters (e.g. Only Show Agency-tagged Data) will not apply to data accessed via the Daily Export API, so we recommend against granting agencies these permissions and providing them with API keys.

### Defining Permissions

Each access level - as defined above - comes with predefined permissions which you can edit if you choose.

!!! tip "Modifying Permissions"
	If you want to modify a predefined access level, click the pencil icon to (de)select the available options.

- **Link-level Settings** - Settings or features that can impact functionality for single links.
- **Channel-level Settings** - Settings or features that can impact functionality across a marketing channel.
- **App-level Settings** - Settings or features that can impact functionality app-wide.
- **Aggregate Data** - Summary data that contains no granular data.
- **Sensitive Data** - Data that can contain user-identifying, payment-related, or secret information.

### Additional Data Filters

During the process of granting an agency access to your Branch account, you can also impose limitations around what data is available to the agency at any given time.

!!! warning "Filter to Only Show Data from Specific Ad Networks"
  When giving an ad partner access to your Branch account, please make sure you toggle the `Only Show Data from Specific Ad Networks` to on and select the ad partner you are giving access to.

- **Only Show Agency-tagged Data** - When toggled on, agency users can only see events tagged with their Agency ID.
- **Restrict Access to Revenue Data** - When toggled on, agency users cannot view revenue data.
- **Only Show Data from Specific Ad Networks** - When toggled on, agency users can only view events from a specific list of ad networks.
- **Only Show Data from Specific Locations** - When toggled on, agency users can only view events that have taken place in a specific list of countries.

!!! warning "Agency Invitation"
	Once you've defined the appropriate levels of access for your Agency, you must **Invite** them to access the Branch dashboard. Only Organization Admins can invite an Agency to access the Branch dashboard.
