# Azure Sentinel Best Practices Analyzer

Microsoft Azure Sentinel is a scalable, cloud-native, security information event management (SIEM) and security orchestration automated response (SOAR) solution. Azure Sentinel delivers intelligent security analytics and threat intelligence across the enterprise, providing a single solution for alert detection, threat visibility, proactive hunting, and threat response. [[more]](https://docs.microsoft.com/en-us/azure/sentinel/overview)

## Best Practices

-- *"Did we lock down the Log Analytics workspace access rights to only allow the appropriate roles and people to access the data?"*

-- *"Shouldn't we be switching to a different pricing tier? I see that we ingesting quite a bit of data daily."*

-- *"The Azure Activity connector is not connected. Shouldn't we be making use of this free data ingestion to detect Azure-based cybersecurity use cases?"*

These are just a few of the questions we see asked a lot. There are recommendations and preferred settings that could be classified as Best Practices, and from which companies can benefit if applied.

## PowerShell module

This project aims to deliver a PowerShell module to check the current Azure Sentinel settings and configuration against best practices. 

These best practices can be described in an inputfile. Although this project delivers a template inputfile, based on public recommendations by both Microsoft and the community, the file can be edited to adapt to your environment.

## Author

[Wortell Enterprise Security](https://www.wortell.nl)

## Contributors

* Dennis van Doorn
* Dennis van den Akker
* [Jeffrey Appel](https://jeffreyappel.nl)
* Edward de Ruiter
* Frans Oudendorp

## License

This project is licensed under the MIT license. See the [LICENSE](LICENSE) file for details.