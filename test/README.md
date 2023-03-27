# The first config 
Provider: https://github.com/shekeriev/terraform-provider-virtualbox

## Usage

```
terraform init
terraform plan
terraform apply -parallelism=1
```

## Caveats
- :gear: Check the name of the network adapter in VirtualBox and fix the value of `host_interface`