# netuitive.packages.kubernetes

For detailed information on this package, please refer to the [online documentation](https://help.netuitive.com/Content/Integrations/kubernetes.htm).

## Heapster Sink
The following are the collectors that are enabled by default in the Heapster Sink:

 - **Heapster** - collects and interprets various signals like compute resource usage, lifecycle events, etc.

## Usage
This package is under development and not available with our automatic installation process at the moment.  

Using metricly-cli you can install this early release, do the following:
- `metricly package install https://github.com/netuitive-community-packages/netuitive-packages-kubernetes/archive/v0.1.0.zip`

## Release History
## Version 0.3.0
* Remove packaged computed metrics and update policies and dashboards to use client side computed usage.percent metrics

### Version 0.2.2
* Fix aggregation on CPU Usage detail dashboard for Pod Containers
* Add unit to cpu.usage

### Version 0.2.1
* Fix package compatible types

### Version 0.2.0
* Add detailed dashboards and more poicies
* Added Validation via metricly-cli

### Version 0.1.0

* Initial release of the package for monitoring Kubernetes resources.
