# Jenkins World 2017
Making the best out of Jenkins on Kubernetes on Openshift

## Slides
This is a reveal.js presentation, generated by emacs org-mode using [org-reveal](https://github.com/yjwen/org-reveal).
The generated presentation can be found [here](index.html), while the org-mode file can be found [here](index.org).

The presentation is using a custom [theme](css/themes/jenkinsworld.css) for Jenkins World.

## Docker Images
During the demo two custom images have been used:
- [Custom Jenkins Image](workspace/images/jenkins/Dockerfile)
- [Custom Jenkins Agent Image](workspace/images/agent/Dockerfile)

## Kubernetes Manifests

Configuration for installing Jenkins on Kubernetes: [kubernetes.yml](workspace/kubernetes/kubernetes.yml)

## Editor configration and setup

During the demo [spacemacs](https://github.com/syl20bnr/spacemacs) has been used, to:

- Build Docker Images
- Apply Kubernetes Manifests
- Write groovy scripts
- Run pipelines from within the editor

Here is my custom [spacemacs configuration](workspace/editor/.spacemacs).
This configuration makes uses of a [custom script to ivoke jenkins pipelines remotely](workspace/editor/run-jenkins-pipeline).
All the groovy and yml snippets used in the demo (are based on yas snippet) can be found [here](workspace/editor/snippets).

## Other presentations
### Conferences

- [DevNation 2014: Introduction to Fabric8](https://github.com/iocanel/presentations/tree/2014-devnation-introduction-to-fabric8)
- [DevNation 2014: Fabric8: Depp Dive](https://github.com/iocanel/presentations/tree/2014-devnation-fabric8-deep-dive)
- [JavaSi 2014: Introduction to Fabric8](https://github.com/iocanel/presentations/tree/2014-javasi-introduction-to-fabric8)
- [FOSSCOM 2015: Kubernetes for Java Developers](https://github.com/iocanel/presentations/tree/2015-fosscom-kubernetes-for-java-developers)
- [Voxxed Thessaloniki 2016: Getting started with microservices on Kubernetes](https://github.com/iocanel/presentations/tree/2016-voxxed@thessaloniki-getting-started-with-microservices-on-kubernetes)
- [JBCNConf 2017: Spring Cloud Kubernetes](https://github.com/iocanel/presentations/tree/2017-jbcnconf-spring-cloud-kubernetes)
### Other
- [Fuse Face2Face 2013: What's new in Fuse Fabric 7.3](https://github.com/iocanel/presentations/tree/2013-fusef2f-whats-new-in-fuse-fabric-7-3)
- [Fuse Engineering Meeting May 2017: Syndesis CI/CD](https://github.com/iocanel/presentations/tree/2017-fuseeng-syndesis-ci-cd)
