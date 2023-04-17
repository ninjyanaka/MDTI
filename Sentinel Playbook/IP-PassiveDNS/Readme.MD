MDTI-Data-PassiveDns-Ip

This play book get an Passive DNS information related to IP entiries on Microsoft Setninel.


Prerequisites
1. This playbook inherits API connections created and established within a base playbook. Ensure you have deployed MDTI-Base playbook. 
 https://github.com/Azure/Azure-Sentinel/tree/master/Solutions/Microsoft%20Defender%20Threat%20Intelligence/Playbooks
2. This playbook requires "Microsoft Sentinel Contributor" role to update Incidents.

Deployment

1. Alert trigger

[![Deploy to Azure](https://aka.ms/deploytoazurebutton)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fninjyanaka%2FMDTI%2Fmain%2FSentinel%2520Playbook%2FIP-PassiveDNS%2Fazuredeployjson.json)

2. Incident trigger

[![Deploy to Azure](https://aka.ms/deploytoazurebutton)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fgithub.com%2Fninjyanaka%2FMDTI%2Fblob%2Fmain%2FSentinel%2520Playbook%2FIP-PassiveDNS%2Fazuredeployjson-incident.json)

Post-Deployment Instructions
After deploying the playbook, you must authorize the connections leveraged.

1. Visit the playbook resource.
2. Under "Development Tools" (located on the left), click "API Connections".
3. Ensure each connection has been authorized.

Note: If you've deployed the MDTI-Base playbook, you will only need to authorize the Microsoft Sentinel connection.
