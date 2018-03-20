# ocpi-schema
JSON Schema's for OCPI

Each OCPI module has its own directory, with in their schema files for entities, and a definitions file which has re-usable components (typically classes) which the documents use.
For now, we've have only created schema's for mod_locations. You are invited to help create schema's for the other modules.

You are free to use these schema's in your project.
Please feel free to contribute to this project through pull-requests or by opening tickets / issues.

# Schema Version
Since the majority of libraries support Draft 06, all schemas are written in draft 06.
The current version of JSON Schema is Draft 07, the major change being that Draft 06 does _not_ support `"if"`/`"then"`/`"else"` validation.

# mod_locations
Locations contains seperate schemas for verifying:
 - a list of locations (locations.json)
 - a single location (location.json)
 - a single EVSE/charger (charger.json)
 - a single connector (connector.json)
 - a set of definitions (definitions.json)


