# creating_azlogin_common_templateADO
Created AZ login template which is common among the organization in the azure DevOps pipeline. This will remove the dependency for the team to call AZ login in reputation. 
1. You need to replace <Service Principal ID>, <Service Principal Key>, <Tenant ID>, and <Azure Subscription ID> with the appropriate values for your environment.
2. After the az login command, the az account set command is used to set the desired Azure subscription context.
3. After the az login command, the az account set command is used to set the desired Azure subscription context.
4. Save the modified azure-pipeline.yml file, and when you run the pipeline, it will execute the az login and az account set commands using PowerShell in Azure DevOps.
