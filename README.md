# hello-openshift

A simple hello-world type service to test OpenShift.

## Deployment:

```
oc new-app registry.access.redhat.com/openshift3/nodejs-010-rhel7~https://github.com/scheckley/hello-openshift.git
```

## Notes:
Currently doesn't work because of course nothing works with OpenShift!
