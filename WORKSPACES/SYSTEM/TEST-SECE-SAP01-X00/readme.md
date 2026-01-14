**SAP System Deployment**

The SAP Application (**X00**) has been deployed to resource group **TEST-SECE-SAP01-X00** in subscription **a54966c1-f3b1-4206-8c82-11715f10ba5f**.

You can access the resource group directly in the Azure Portal using the following link: [TEST-SECE-SAP01-X00](https://portal.azure.com/#@a9125522-2e79-4e2d-8910-29e8b3fefcbb/resource/subscriptions/a54966c1-f3b1-4206-8c82-11715f10ba5f/resourceGroups/TEST-SECE-SAP01-X00/overview)

**SAP Application Information**


| Setting                    | Value                           |
| :------------------------- | :------------------------------ |
| SID                        | X00                          |
| Database                   | hana                     |
| DB SID                     | XDB                       |
| SCS Server Loadbalancer IP | 10.110.32.8   |
| SCS High Availability      | No        |
| DB High Availability       | No   |


**Server Roles and Names**


| Role                           | Names                           |
| :----------------------------- | :------------------------------ |
| Database                       | x00dxdb01l082                   |
| Central Services               | x00scs01l82b                  |
| Primary Application Server     | x00app01l82b                   |
| Additional Application Servers | x00app01l82b          |
| Web Dispatchers                |               |


**Access credentials**


| Setting                  | Value                                             |
| :----------------------- | :------------------------------------------------ |
| Key Vault Name           | [TESTSECESAP01user6B9](https://portal.azure.com/#@a9125522-2e79-4e2d-8910-29e8b3fefcbb/resource/subscriptions/a54966c1-f3b1-4206-8c82-11715f10ba5f/resourceGroups/TEST-SECE-SAP01-INFRASTRUCTURE/providers/Microsoft.KeyVault/vaults/TESTSECESAP01user6B9/overview)             |
| Secret name for username | [TEST-SECE-SAP01-sid-username](https://portal.azure.com/#@a9125522-2e79-4e2d-8910-29e8b3fefcbb/asset/Microsoft_Azure_KeyVault/Secret/https://TESTSECESAP01user6B9.vault.azure.net/secrets/TEST-SECE-SAP01-sid-username) |
| Secret name for password | [TEST-SECE-SAP01-sid-password](https://portal.azure.com/#@a9125522-2e79-4e2d-8910-29e8b3fefcbb/asset/Microsoft_Azure_KeyVault/Secret/https://TESTSECESAP01user6B9.vault.azure.net/secrets/TEST-SECE-SAP01-sid-password) |
| Secret name for SSH key  | [TEST-SECE-SAP01-sid-sshkey](https://portal.azure.com/#@a9125522-2e79-4e2d-8910-29e8b3fefcbb/asset/Microsoft_Azure_KeyVault/Secret/https://TESTSECESAP01user6B9.vault.azure.net/secrets/TEST-SECE-SAP01-sid-sshkey)           |



