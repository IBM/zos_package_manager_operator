# z/OS Package Manager Operator collection

The IBM® z/OS® Package Manager collection provides automation for installing z/OS Package Manager on one or more z/OS endpoints and managing its lifecycle in a hybrid cloud environment. IBM z/OS Package Manager is a utility that can install any z/OS software that is packaged as an OCI artifact on z/OS. This collection includes both the Ansible operator playbooks and z/OS Package Manager.

Import this collection into an instance of z/OS Cloud Broker running in Red Hat OpenShift Container Platform to get started quickly. z/OS Cloud Broker generates a Kubernetes operator, making it easy to deploy the z/OS Package Manager to a z/OS endpoint. For information, see the [documentation](https://www.ibm.com/docs/SSV97FN_latest/zpm/overview.html).

# IBM Z and Cloud Modernization Stack

The IBM z/OS Package Manager collection is part of the IBM Z and Cloud Modernization Stack.

IBM Z and Cloud Modernization Stack brings together component capabilities from IBM Z into an integrated platform that is optimized for Red Hat OpenShift Container Platform. Together, these capabilities help to modernize and simplify the use of z/OS software.

For information, see [IBM Z and Cloud Modernization Stack documentation](https://www.ibm.com/docs/z-mod-stack).

# Features

The IBM z/OS Package Manager collection contains the following capabilities:

* Ansible playbooks to install, update, and remove the z/OS Package Manager from a z/OS endpoint.
* Ansible playbook to run a MustGather that collects diagnostics if you need support from IBM.
* z/OS Package Manager in .tar format for easy deployment to z/OS from Red Hat OpenShift Container Platform.

This Ansible collection must be used with z/OS Cloud Broker V2. For all system requirements, see the [documentation](https://www.ibm.com/docs/SSV97FN_latest/zstack/system-requirements.html).

# Copyright

© Copyright IBM Corporation 2022.


# License

This collection is licensed by IBM. See the [license](https://www.ibm.com/software/sla/sladb.nsf/searchlis/?searchview&query=(L-ACRR-C9XLWK)) for details.

