# Workspace Config Guide
Guide on how to apply the example config.

## Installing team.tenant.xml for Provisioning
1. Navigate to your root LiveTiles Hub page
2. Go into site contents
3. Create a new document library called "PnPTemplates"
4. Insert your customized team.tenant.xml (feel free to use the example file in the this repo)

## Implementing Workspace Team Config
1. Go into your example Workspace config or create a new one
2. Insert the code from any example Workspace_Config.json
3. Replace all variables with the correct value
	3.1 Make sure to give each workspace an unique ID (line 2)
	3.2 Enter the root web URL of your team.tenant.xml file at line 11 (If you followed the previous Team.xml installation step, just insert your SharePoint Root URL)
	3.3 Enter the document library name you created earlier in which your team.tenant.xml is located at line 12 (If you followed the previous step, just insert "PnPTemplates")
	3.4 Enter the name of your Team configuration file at line 15 (standard: "team.tenant.xml")
	3.5 Insert your created Term ID for the specific workspace (line 258)
	3.6 Insert your created unique LiveTiles Metadata Inheritance config key at line 265 (refer to Metadata Inheritance)

## Issues
If you have a question regarding the example config you can open an issue.

## Documentation
Visit https://docs.matchpoint365.com/docs/en/metadata/overview/ for documentation about Metadata.
In case you miss something in the documentation, please open an issue.