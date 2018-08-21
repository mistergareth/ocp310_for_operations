# ocp310_for_operations
This is a Red Hat OpenShift Container Platform workshop designed to provide participants with an infrastructure-centric view of installing and using a container platform. 

This training is designed to give you, gentle reader, an infrastructure-centric experience installing Red Hat OpenShift Container Platform. The target audience for this training is technical. Those with Red Hat Enterprise Linux and open source familiarity will feel right at home.

The OpenShift environment will consist of a master and two nodes, with other virtual machines providing services required for the training. The environment will be created on hosted infrastructure conducive to our training purposes. Professional deployments use virtualization platforms, bare metal, or public clouds.

The target time frame for the training is four hours. Except for you, rock star. You need less time.

**Creating the Environment:**

Your instructor will grant you a hosted environment with virtual hardware. The environment consists of a workstation which serves both as an entry point into the environment and a central place to execute installation and operational steps. Along with the workstation, there will be a three-machine OpenShift cluster with a helper virtual machine hosting administrative functions like DNS and software repositories. 

**Lab Environment:**

Workstation: This machine has a dynamically assigned public IP address that you will SSH to, as well as a virtual desktop environment with a web browser. 
Master: This machine will host the OpenShift master.
Node1: This machine will host one OpenShift node.
Node2: This machine will host one OpenShift node.
Core: This machine will host DNS, software repositories, and other services needed for the training environment. Modifying this machine is unnecessary.