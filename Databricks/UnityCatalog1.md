### Unity Catalog

Unity Catalog provides centralized access control, auditing, lineage, and data discovery capabilities across Azure Databricks workspaces.

``` SQL
USE CATALOG <catalog>;
CREATE { DATABASE | SCHEMA } [ IF NOT EXISTS ] <schema-name>
    [ MANAGED LOCATION '<location-path>' ]
    [ COMMENT <comment> ]
    [ WITH DBPROPERTIES ( <property-key = property_value [ , ... ]> ) ];
```