K8s OCI

![](https://lh6.googleusercontent.com/B7Zvzs66ur402_syxPVPQBIW11HjfBEedz8TDiGmapNuTaQvGeF6VxWZvZRMDAyhIqTBa09M8Ep7X_fJJr3KTxtGt_Twz9FUnp8auR4Sy1hLDqf6aDZF96RUA_LQIF2XNA=w1280)

Module Cluster

| Args | Values |
|---|---|
| `Name` | Variables |
| `image id` | var.image_id|
| `ssh public key` | var.ssh_public_key|  
| `public subnet id  ` | module.network.public_subnet_id |
| `compartment id ` | module.compartment.compartment_id |
| `vcn private subnet id ` | module.network.vcn_private_subnet_id|
| `shape ` | var.shape |
| `memory in gbs per node ` | var.memory_in_gbs_per_node|
| `ocpus per node ` | var.ocpus_per_node |
| `vcn id ` | module.vcn.vcn_id|
| `cluster name ` | var.cluster_name|
| `k8s version ` | var.k8s_version |
| `node size ` | var.node_size |



