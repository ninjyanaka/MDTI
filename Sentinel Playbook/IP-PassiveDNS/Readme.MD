MDTI-Data-PassiveDns-Ip

This play book get an Passive DNS information related to IP entiries on Microsoft Setninel.


Prerequisites
1. This playbook inherits API connections created and established within a base playbook. Ensure you have deployed MDTI-Base playbook. 
 https://github.com/Azure/Azure-Sentinel/tree/master/Solutions/Microsoft%20Defender%20Threat%20Intelligence/Playbooks
2. This playbook requires "Microsoft Sentinel Contributor" role to update Incidents.

Deployment

1. Alert trigger

[![Deploy to Azure](https://aka.ms/deploytoazurebutton)](https://portal.azure.com/#create/Microsoft.Template/uri/https://raw.githubusercontent.com/ninjyanaka/MDTI/main/Sentinel%20Playbook/IP-PassiveDNS/azuredeployjson.json)

2. Incident trigger

[![Deploy to Azure](https://aka.ms/deploytoazurebutton)](https://raw.githubusercontent.com/ninjyanaka/MDTI/main/Sentinel%20Playbook/IP-PassiveDNS/azuredeployjson-incident.jsonn)

Post-Deployment Instructions
After deploying the playbook, you must authorize the connections leveraged.

1. Visit the playbook resource.
2. Under "Development Tools" (located on the left), click "API Connections".
3. Ensure each connection has been authorized.

Note: If you've deployed the MDTI-Base playbook, you will only need to authorize the Microsoft Sentinel connection.
