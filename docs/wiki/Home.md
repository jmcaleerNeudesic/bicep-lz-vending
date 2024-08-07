<!-- markdownlint-disable MD041 -->
Welcome to the Bicep Landing Zone (aka Subscription) vending module documentation.

Please see the [README](https://aka.ms/lz-vending/bicep) for information on module requirements, variables and outputs. This wiki contains longer form documentation.

This module can be used standalone, or combined with the [Azure Landing Zones Bicep modules][alz_bicep_module] to create a landing zone within the [Azure Landing Zones conceptual architecture][alz_conceptual_arch].

<!-- markdownlint-disable MD033 -->
<center><img src="img/journey.png" width="60%" /></center>
<!-- markdownlint-enable -->

In the above diagram, this module provides the capability to deploy landing zones (subscriptions) and the core resources, e.g. networking.

We recommend that you deploy the platform using the [Azure Landing Zones Bicep modules][alz_bicep_module] and then use this module to deploy the landing zones.

Before deployment, please review the [required permissions](https://github.com/azure/bicep-lz-vending/wiki/permissions). Then to get started, look at one of the [examples](https://github.com/azure/bicep-lz-vending/wiki/examples).

[alz_conceptual_arch]: https://aka.ms/alz#azure-landing-zone-conceptual-architecture
[alz_bicep_module]: https://aka.ms/alz/bicep
