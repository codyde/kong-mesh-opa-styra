# Kong Mesh and Open Policy Agent (OPA) 

## Demo for 6/9 Webinar with Styra 

This repository contains the demo code for the initial demo webinar for Open Policy Agent and Kong Mesh

The webinar details can be found here - https://konghq.com/webinars/kong-mesh-open-policy-agent

![Kong Mesh and OPA](kong-mesh-opa.png)

## NOTE

The values.yaml file has been omitted as it contains the license file in this demo. You can replicate your own without a license (using the 5 Dataplane demo) using the following code...

```yaml
kuma:
    controlPlane:
      envVars:
        KUMA_RUNTIME_KUBERNETES_INJECTOR_BUILTIN_DNS_ENABLED: "true"
```
