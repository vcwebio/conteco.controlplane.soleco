[`controlplane.soleco`](../README.md) >> API Auxiliary Methods

-----

# API Auxiliary Methods

## `/conteco/bin`

__`soleco`__  
Entrypoint for the API when called from the CLI.

## `/conteco/bin/controlplane/internal`

__`.soleco`__  
Entrypoint for the API if called as a base API from a derived controlplane.

## `/conteco/bin/controlplane/soleco/internal`

This folder contains auxiliary methods supporting the implementation of the `config` API.

__`config-module`__  
Auxiliary method to configure the module service stacks from the assets imported from the ContEco images.  
This includes renaming the service stack with the module specific names.

-----
[`controlplane.soleco`](../README.md) >> Auxiliary API
