
<h1 align="center">
  <br>
  <a href="https://k8s.haxx.ninja"><img src="images/logo.jpg" alt="Kubernetes Security Walkthrough" width="200"></a>
  <br>
  Kubernetes Security Extravanganza
  <br>
</h1>

<h4 align="center">A minimal walkthrough on Kubernetes security features and controls.</h4>


<p align="center">
  <a href="#intro">Introduction</a> •
  <a href="#hand-holding-kubernetes-hardening">Hand Holding Kubernetes Hardening</a> •
  <a href="#simpler-hardening">Simpler Hardening</a> •
  <a href="#tls-certification-rotation">TLS Certification Rotation</a> •
  <a href="#linux-kernel-filtering">Linux Kernel Filtering</a> •
  <a href="#pod-security">Pod Security</a> •
  <a href="#netsec">NetSec</a> •
  <a href="#cluster">Cluster</a> •
  <a href="#admission-controller">Admission Controller</a> •
  <a href="#workload-integrity">Workload Integrity</a> •
  <a href="#backups">Backups</a> •
  <a href="#secrets">Secrets</a> •
  <a href="#isolated-kernel">Isolated Kernel</a> •
  <a href="#image-pulling">Image Pulling</a> 

</p>


## Intro

Hardening an application server that was never intended to be hardened (wrapped by private R&D security tooling not made publicly available) is always a challenge.  Especially in light of everything else one must consider and engineer around;

* Cluster Architecture
* Containers
* Workloads
* Services, Load Balancing, and Networking
* Storage
* Configuration
* Policies
* Scheduling, Preemption and Eviction
* Cluster Administration
* Extending Kubernetes

Which is why it is worthwhile to view my lecture on the project that became Kubernetes.  Design decisions were made of that era's philosophy.  Hence this walkthrough to right the sins that were made.



## Hand Holding Kubernetes Hardening
[Interesting manual techniques to harden kubernetes core](1_HandHolding_HardenedK8s/README.md)

## Simpler Hardening
[Semi-automated techniques to harden kubernetes core](1_SimplerInstall_HardenedK8s/README.md)

## TLS Certification Rotation
[X.509 builds the internal communication assurance and integrity checks between different Kubernete's services](2_X509_Rotation/README.md)

## Linux Kernel Filtering
[SECCOMP goes a long way but is difficult to master](3_LinuxKernel_Filtering/README.md)

## Pod Security
[Pod Security is the new hotness](4_Pod_Security/README.md)

## NetSec
[Service Mesh, DNS, autodiscovery - oh my!](5_Simple_Network_Security/README.md)

## Cluster
[The root of all governance](6_Cluster_Security/README.md)

## Admission Controller
[The Gatekeeper of Xul](7_Admission_Controller/README.md)

## Workload Integrity
[I think, therefore I am because my identity is mathematicaly proven](8_WorkloadIntegrity/README.md)

## Backups
[You are only as available as your last successful restoration](9_Backups/README.md)

## Secrets
[Touching other people's underwear](10_SecretsAreSecret/README.md)

## Isolated Kernel
[I heard you like kernels so I put a kernel in your kernel](11_GVisorKernel/README.md)

## Image Pulling
[Or why DockerHub had to make money](12_PullingImages/README.md)






----


## Credits

 [John Menerick](https://haxx.ninja)

 [Kubernetes](https://kubernetes.io)

 [Hashicorp](https://hashicorp.com)


---

## License

MIT
---

> [k8s.haxx.ninja](https://k8s.haxx.ninja) &nbsp;&middot;&nbsp;
> GitHub [@w8mej](https://github.com/w8mej) &nbsp;&middot;&nbsp;
> Keyoxide [John Menerick](https://keyoxide.org/hkp/sephiroth@haxx.ninja)
