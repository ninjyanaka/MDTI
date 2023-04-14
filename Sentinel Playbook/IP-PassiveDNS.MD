MDTI-Data-PassiveDns-Ip

Prerequisites
1. This playbook inherits API connections created and established within a base playbook. Ensure you have deployed MDTI-Base playbook. If you have trouble accessing your account or your credentials contact your account representative or reach out to discussMDTI[@]microsoft.com.
2. This playbook requires "Microsoft Sentinel Contributor" role to update Incidents.

Deployment

[![Deploy to Azure](https://aka.ms/deploytoazurebutton)](https://portal.azure.com/#create/Microsoft.Template/uri/<URLEncoded ARM Template URL>)

Post-Deployment Instructions
After deploying the playbook, you must authorize the connections leveraged.

1. Visit the playbook resource.
2. Under "Development Tools" (located on the left), click "API Connections".
3. Ensure each connection has been authorized.
