---
subcategory: Cloud Server
page_title: "Bizfly Cloud: bizflycloud_custom_image"
description: |-
    Provides a Bizfly Cloud Custom Image
---

# Data Source: bizflycloud_custom_image

Get information about Bizfly Cloud Custom Image.

## Example Usage

```hcl
# Get information of a custom image
data "bizflycloud_custom_image" "custom_image" {
  id = "d646476d-850c-423e-b02c-6b86aeda3717"
}
```

## Argument Reference

The following arguments are supported:

-   `id` - (Required) The ID of Custom Image

## Attributes Reference

The following attributes are exported:

-   `id` - The ID of Custom Image
-   `name` - The name of Custom Image
-   `size` - The size of Custom Image
-   `disk_format` - The disk format of Custom Image
-   `container_format` - The container format of Custom Image
-   `billing_plan` - The billing plan of Custom Image
