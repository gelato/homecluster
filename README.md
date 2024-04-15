# 🏡 🧪 Home Lab

## 📖 Overview

This mono repository houses the infrastructure for my homelab. I try to adhere to Infrastructure as Code (IaC) and GitOps practices using tools like [Ansible](https://www.ansible.com/), [Terraform](https://www.terraform.io/), [Kubernetes](https://kubernetes.io/), [Flux](https://github.com/fluxcd/flux2), [Renovate](https://github.com/renovatebot/renovate) and [GitHub Actions](https://github.com/features/actions).

## ⛵ How to get started

There is a template over at [onedr0p/flux-cluster-template](https://github.com/onedr0p/flux-cluster-template) if you want to try and follow along with some of the practices I use here.

## 🎨 Cluster components

+ [cert-manager](https://cert-manager.io/docs/): Creates SSL certificates for services in my k3s cluster.
+ [cilium](https://cilium.io/get-started/): Internal Kubernetes networking plugin.
+ [external-dns](https://github.com/kubernetes-sigs/external-dns): Automatically manages DNS records from my cluster in a cloud DNS provider.
+ [ingress-nginx](https://github.com/kubernetes/ingress-nginx/): Ingress controller to expose HTTP traffic to pods over DNS.
+ [Longhorn](https://longhorn.io): Distributed block storage for persistent storage.
+ [sops](https://github.com/mozilla/sops): Managed secrets for Kubernetes, Ansible and Terraform which are commited to Git.

... and more!

## 🗄️ Hardware
<details>
  <summary>Click to see the summary!</summary>

| Device             | Count | Specs                                                                                                                                                                                                                                                                                                          | OS                                                  | Purpose                |
| ------------------ | ----- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------- | ---------------------- |
| Desktop PC   | 1     | **CPU** `Intel i3-12100F (4) @ 4.300GHz` <br/> **GPU** `Nvidia GeForce RTX 4070` <br/> **RAM** `128GB` <br/> **M.2 SSD** `2TB` <br/> **HDD SSD** `18TB`                                                                                                                                                       | Ubuntu GNU/Linux  (Pop!OS)                      | Worker node          |
| SeeedStudio Recomputer   | 1     | **CPU** `J4105 CPU @ 2.500GHz` <br/> **GPU** `Intel` <br/> **RAM** `8GB` <br/> **M.2 SSD** `1TB` <br/> **HDD SSD** `0GB`
</details>

## 📜 Changelog

See my _awful_ commit [main history](https://github.com/gelato/homecluster/commits/main) and [legacy history](https://github.com/gelato/homecluster/tree/d75a6360586de8b5b5c4ff6b553b7512cfea5007)

## :handshake:&nbsp; Gratitude and thanks

Thanks all the people of [Home Operations](https://discord.gg/home-operations) Discord community who put a lot of effort and donate their time to the community.

## 🔏 License

See [LICENSE](./LICENSE) v.g WTF License