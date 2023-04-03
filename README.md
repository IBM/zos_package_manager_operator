# z/OS Package Manager Operator collection

The IBM® z/OS® Package Manager collection provides automation for installing z/OS Package Manager and the z/OS products on one or more z/OS endpoints and managing their lifecycle in a hybrid cloud environment. IBM z/OS Package Manager is a utility that can install any z/OS software that is packaged as an OCI artifact on z/OS. This collection includes both the Ansible operator playbooks and z/OS Package Manager.

Import z/OS Package Manager collection into instance of z/OS Cloud Broker running in Red Hat OpenShift Container Platform to get started quickly. z/OS Cloud Broker generates a Kubernetes operator, making it easy to deploy the z/OS Package Manager to a z/OS endpoint. For information, see the [documentation](https://www.ibm.com/docs/SSV97FN_latest/zpm/overview.html).


# IBM Z and Cloud Modernization Stack

The IBM z/OS Package Manager collection is part of the IBM Z and Cloud Modernization Stack.

IBM Z and Cloud Modernization Stack brings together component capabilities from IBM Z into an integrated platform that is optimized for Red Hat OpenShift Container Platform. Together, these capabilities help to modernize and simplify the use of z/OS software.

For information, see [IBM Z and Cloud Modernization Stack documentation](https://www.ibm.com/docs/en/cloud-paks/z-modernization-stack).


# Features

The IBM z/OS Package Manager collection contains the following capabilities:

* Ansible playbooks to install, update, and remove the z/OS Package Manager from a z/OS endpoint.
* Ansible playbook to run **Gather diagnostics** that collects diagnostics if you need support from IBM.
* z/OS Package Manager in .tar format for easy deployment to z/OS from Red Hat OpenShift Container Platform.
* Ansible playbooks to install, validate, and uninstall a z/OS product on z/OS endpoint.

Beginning with z/OS Package Manager collection 2.0 and the z/OS Cloud Broker 2.2, individual product collections are no longer required and z/OS product OCI artifacts can be installed directly using z/OS Package Manager suboperator v2.0.

For all system requirements, see the [documentation](https://www.ibm.com/docs/SSV97FN_latest/zstack/system-requirements.html).

# Copyright

© Copyright IBM Corporation 2023.


# License

This collection is licensed by IBM. See the [license](https://www.ibm.com/support/customer/csol/terms/?id=L-YJCB-2HHW29) for details.
