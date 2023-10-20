---
icon: home
label: Home
---

# Welcome to the Docs!

This supporting add-on comes with prebuilt content for [Palo Alto Networks <small>:icon-link-external:</small>][palo]{ target="blank" } Cortex XDR data to be easily used with Splunk Enterprise Security's Asset database. This documentation will cover the components used in the add-on and advanced configurations. 

!!!danger Important
This Supporting add-on is only intended to work with [Splunk Enterprise Security <small>:icon-link-external:</small>](https://splunkbase.splunk.com/app/263){ target="blank" } deployments.
!!!

> __*Disclaimer*__
> 
> *This Splunk Supporting Add-on is __not__ affiliated with [__Palo Alto Networks__ <small>:icon-link-external:</small>][palo]{ target="blank" } and is not sponsored or sanctioned by the Palo Alto Networks team. Please visit [https://www.paloaltonetworks.com/ <small>:icon-link-external:</small>][palo]{ target="blank" } for more information about Palo Alto Networks.*

## Assumptions

This documentation assumes the following:

1. You have a working Splunk Enterprise Security environment. __This add-on is not intended to work without Splunk ES.__
2. You already have Palo Alto Networks Cortex XDR data ingested using the [Palo Alto Cortex XDR Endpoint Retriever <small>:icon-link-external:</small>](https://splunkbase.splunk.com/app/6396){ target="blank" }.
3. Familiarity with setting up a new Asset source in Enterprise Security.

## About

Info | Description
------|----------
SA-CortexXDRDevices | [Splunkbase <small>:icon-link-external:</small>](https://splunkbase.splunk.com/app/7063){ target="blank" } \| [GitHub <small>:icon-link-external:</small>](https://github.com/rba-community/SA-CortexXDRDevices/releases/){ target="blank" }
Splunk Enterprise Security Version <small>(Required)</small> | [7.x \| 6.x <small>:icon-link-external:</small>](https://splunkbase.splunk.com/app/263){ target="blank" }
Palo Alto Cortex XDR Endpoint Retriever <small>(Required)</small> | [>=1.1.0 <small>:icon-link-external:</small>](https://splunkbase.splunk.com/app/6396){ target="blank" }
Add-on has a web UI | No, this add-on does not contain views.
Author | [Dennis Morton](https://www.linkedin.com/in/dennis-morton-627632/)

[palo]: https://www.paloaltonetworks.com/