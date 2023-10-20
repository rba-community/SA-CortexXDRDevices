# All Configurations

Below is a table that list all configuration for this add-on.

Name | Type | Web Location | CLI Location\* | Description
---- | ---- | ------------ | ------------- | -----------
Cortex XDR Devices - Lookup Gen | Saved Search | Settings > Searches reports, and alerts | savedsearches.conf | Populates the lookup file `xdr_devices`.
xdr_devices | lookup | Settings > Lookups > Lookup definitions | transforms.conf | Lookup definition for the KVStore collection `xdr_devices_collection`.
xdr_devices_collection | KVStore collection | n/a\*\* | collections.conf | KVStore configuration.
sa_cortex_xdr_index | Search macro | Settings > Advanced Search > Search Macros | macros.conf | Index definition for the index that contains the sourcetype `cortex:xdr:endpoints`.
identity_manager://xdr_devices | Asset lookup configuration | Enterprise Security > Configure > Data Enrichment > Asset and Identity Management > Asset Lookups | inputs.conf | Asset configuration lookup to load PA Networks Cortex XDR assets into the asset database.

> \*CLI locations are relative to `../default`. Any update to CLI configuration files should be done in the local directory.

!!!info
**If you have the [Splunk App for Lookup File Editing <small>:icon-link-external:</small>](https://splunkbase.splunk.com/app/263){ target="blank" }, the KVStore collection `xdr_devices_collection` is viewable within the Web interface.
!!!