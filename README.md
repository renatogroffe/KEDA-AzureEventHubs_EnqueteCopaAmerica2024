# KEDA-AzureEventHubs_EnqueteCopaAmerica2024
Objetos para Deployment de um Worker Service (apuração de enquete sobre a Copa América 2024) no Kubernetes utilizando KEDA, Helm, Azure Event Hubs, .NET 8 e SQL Server.

Worker para consumo dos eventos (imagem **renatogroffe/worker-enquete-copa-america-2024:1**):
**https://github.com/renatogroffe/DotNet8-Worker-AzureEventHubs-SqlServer-Dapper-AppInsightsConnString-Processor_EnqueteCopaAmerica**

Aplicação para geração dos eventos (imagem **renatogroffe/site-enquete-copa-america-2024:1**):
**https://github.com/renatogroffe/ASPNETCore8-MVC-AzureEventHubs-AppInsightsConnString_EnqueteCopaAmerica**