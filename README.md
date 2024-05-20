# hello-openshift

A simple hello-world type service to test OpenShift based on the [docs](https://access.redhat.com/documentation/en-us/red_hat_container_development_kit/2.1/html/getting_started_guide/deploying_an_application_on_openshift#deploying_a_hello_world_application_using_node_js):


## Deployment:

```
oc new-app registry.access.redhat.com/openshift3/nodejs-010-rhel7~https://github.com/scheckley/hello-openshift.git
```

## Notes:
Currently doesn't work because of course nothing works with OpenShift!
