---
# generated by https://github.com/hashicorp/terraform-plugin-docs
page_title: "netbox_cluster_type Resource - terraform-provider-netbox"
subcategory: ""
description: |-
  From the official documentation https://docs.netbox.dev/en/stable/core-functionality/virtualization/#cluster-types:
  A cluster type represents a technology or mechanism by which a cluster is formed. For example, you might create a cluster type named "VMware vSphere" for a locally hosted cluster or "DigitalOcean NYC3" for one hosted by a cloud provider.
---

# netbox_cluster_type (Resource)

From the [official documentation](https://docs.netbox.dev/en/stable/core-functionality/virtualization/#cluster-types):

> A cluster type represents a technology or mechanism by which a cluster is formed. For example, you might create a cluster type named "VMware vSphere" for a locally hosted cluster or "DigitalOcean NYC3" for one hosted by a cloud provider.

## Example Usage

```terraform
resource "netbox_cluster_type" "vmw_vsphere" {
  name = "VMware vSphere 6"
}
```

<!-- schema generated by tfplugindocs -->
## Schema

### Required

- `name` (String)

### Optional

- `slug` (String)

### Read-Only

- `id` (String) The ID of this resource.

