# An example that shows how a local Maven repo can be shared among multiple jenkins builds

## Prerequisites:

1. Jenkins with [Kubernetes]:https://github.com/jenkinsci/kubernetes-plugin plugin installed
2. Maven configured in Jenkins [(I am using withMaven)]: https://jenkins.io/doc/pipeline/steps/pipeline-maven/
3. Persistent Volumes created in [Kubernetes]: https://kubernetes.io/docs/concepts/storage/persistent-volumes/