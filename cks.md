# Certified Kubernetes Security Specialist (CKS)

## 1. Use Network security policies to restrict cluster level access

### Understand Kubernetes Network Policies
- Network Policy is a Kubernetes resource that uses a set of ingress and egress rules to define which traffic is allowed to or from a group of pods.
- These rules are applied to pod communication, allowing fine-grained control over networking between pods, namespaces, or external endpoints.


### Implementing Network Policies for Different Use Cases
- **Isolate Critical Services:** Use network policies to isolate critical services (e.g., databases, admin services) and allow access only to specific trusted pods.
- **Limit External Access:** Create policies that block all egress traffic except for specific external services such as API gateways or load balancers.
- **Enforce Zero-Trust:** By default, block all communication between pods and allow only necessary communication paths via defined network policies.

## 2. Use CIS benchmark to review the security configuration of Kubernetes components (etcd, kubelet, kubedns, kubeapi)
