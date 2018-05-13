# CKAD
CNCF Certified Kubernetes Application Developer (CKAD)



Online resources that will help you prepare for taking the Certified Kubernetes Application Developer (CKAD) Certification exam.

**Disclaimer:** *This is not likely a comprehensive list as the exam will be a moving target with the fast pace of k8s development - please make a pull request if there something wrong or that should be added, or updated in here.*

* [CNCF Exam Curriculm repository](https://github.com/cncf/curriculum)
* [CKAD Candidate Handbook](https://www.cncf.io/certification/candidate-handbook)
* [CKAD Exam Tips](https://www2.thelinuxfoundation.org/ckad-tips)
* [FAQs](https://www.cncf.io/certification/expert/cka/faq/)


# CKAD Curriculum V1.0

## Core Concepts - 13%
* [Understand kubernetes API Primitives](https://kubernetes.io/docs/concepts/overview/kubernetes-api/)
* [Create and configure basic Pods]()

## Multi-Container Pods - 10%
* [Understand Multi-Container Pod design patterns (e.g: ambassador, adapter, sidecare)](https://kubernetes.io/blog/2015/06/the-distributed-system-toolkit-patterns/)

## Pod Design - 20%
* Understand how to use Labels, Selectors, and Annotations.
  * [Labels & Selectors](https://kubernetes.io/docs/concepts/overview/working-with-objects/labels/)
    * [Using labels effectively](https://kubernetes.io/docs/concepts/cluster-administration/manage-deployment/#using-labels-effectively)
  * [NodeSelector](https://kubernetes.io/docs/concepts/configuration/assign-pod-node/)
  * [Annotations overview](https://kubernetes.io/docs/concepts/overview/working-with-objects/annotations/)
* Understand Deployments and how to perform rolling updates.
  * [deployments](https://kubernetes.io/docs/concepts/workloads/controllers/deployment/)
  * [rolling updates](https://kubernetes.io/docs/tutorials/kubernetes-basics/update-intro/)
* [Understand Deployments and how to perform rollbacks.]()
* Understand Jobs and CronJobs.
  * CronJobs
    * [Overview](https://kubernetes.io/docs/concepts/workloads/controllers/cron-jobs/)
    * [Running automated tasks with CronJob](https://kubernetes.io/docs/tasks/job/automated-tasks-with-cron-jobs/)
  * Jobs
    * [Overview](https://kubernetes.io/docs/concepts/workloads/controllers/jobs-run-to-completion/#job-patterns)
    * [Parallel processing using Expansions](https://kubernetes.io/docs/tasks/job/parallel-processing-expansion/)
## Configuration - 18%
* [Understand ConfigMaps](https://kubernetes.io/docs/tasks/configure-pod-container/configure-pod-configmap/)
  * [Configure redis using ConfigMap](https://kubernetes.io/docs/tutorials/configuration/configure-redis-using-configmap/)
* [Understand SecurityContexts](https://kubernetes.io/docs/tasks/configure-pod-container/security-context/)
* [Define an application's resources requirements](https://kubernetes.io/docs/concepts/configuration/manage-compute-resources-container/)
* [Create & consume Secrets](https://kubernetes.io/docs/concepts/configuration/secret/)
* [Understand ServiceAccounts](https://kubernetes.io/docs/tasks/configure-pod-container/configure-service-account/)

## Observability - 18%
* Understand LivenessProbes and ReadinessProbes
  * [LivenessProbe](https://kubernetes.io/docs/tasks/configure-pod-container/configure-liveness-readiness-probes/)
  * [ReadinessProbe](https://kubernetes.io/docs/tasks/configure-pod-container/configure-liveness-readiness-probes/#define-readiness-probes)
* Understand container logging
  * [Logging](https://kubernetes.io/docs/concepts/cluster-administration/logging/)
  * [Using StackDrive](https://kubernetes.io/docs/tasks/debug-application-cluster/logging-stackdriver/)
* Understand how to monitor applications in Kubernetes
* Understand debugging in Kubernetes

## Services & Networking - 13%
* Understand Services
* Demonstrate basic understanding of NetworkPolicies.
