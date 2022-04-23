## Open5gs 5G Core

This repo contains the code templates that was used in the Opensource 5G core with service mesh blog post.

N.B - Calico CNI should be used due to the static IP that is required to make ueransim deployment easier.

Make sure to change the following parameters in the values.yaml to suit the Calico POD CIDR that you are using:

```
upfIP: "10.240.233.70"    
amfIP: "10.240.233.72"
GnbIP: "10.240.233.71"
```