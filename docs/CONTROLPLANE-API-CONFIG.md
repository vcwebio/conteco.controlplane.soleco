[`controlplane.soleco`](../README.md) >> `config` API - Full

-----

# `config` API - Full

`controlplane.soleco` implements the following common methods of the `config` API section:

__`build`__  
Generates the `Dockerfile.static` with the `environment` configuration.  
Should be executed after an update to the variables in the `environment` file.  
The `Dockerfile.static` file allows a direct `docker build` of the image. It is used by the automated Docker Hub build.
Inherited from controlplane.base.

__`increment`__  [version-part]
Increments the specified version part of a `vx.y.z` version tag in `$CONTECO_TAG`.
Requires $CONTECO_TAG_TYPE=incremental, otherwise action is ignored.
Inherited from controlplane.base.

__`remove-crs`__  
This method remove CRs from files without extension or with _.md_ or _.static_ extension.  
Inherited from controlplane.base.

__`set-version`__  
This method sets the value of the `$CONTECO_TAG` variable.  
Inherited from controlplane.base.

-----
[`controlplane.soleco`](../README.md) >> `config` API - Full
