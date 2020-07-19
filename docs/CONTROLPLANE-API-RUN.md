[`controlplane.soleco`](../README.md) >> `run` API - Full

-----

# `run` API - Full

The run interface splits the service stacks in two categories - core services and others.

_boot_ and _shutdown_ are used to deploy / remove core cluster services that require to be
up and running prior to starting any other services.

_start_ and _stop_ are used to deploy / remove other services.

`controlplane.soleco` implements the following methods for the `run` API section:  

__`boot`__ [stack - optional]  

__`pause`__ [stack - optional]  

__`reboot`__ [stack - optional]  

__`restart`__ [stack - optional]  

__`resume`__ [stack - optional]  

__`shutdown`__ [stack - optional]  

__`start`__ [stack - optional]  

__`stop`__ [stack - optional]  

-----
[`controlplane.soleco`](../README.md) >> `run` API - Full
