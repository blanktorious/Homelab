### My Homelab
My self-hosted server running Kubernetes with GitOps approach.

## Introduction

This repository contains all the configuration files that is also the reference for the cluster's GitOps system.

In my day job, I have been working with Kubernetes clusters hosted in Azure for a long time, but I still don’t have a full understanding of all the microcomponents and intricacies of a Kubernetes cluster. So, after a ton of research I decided to convert my old laptop into a Ubuntu Server that can host a Kubernetes.

This cluster serves as my playground where I can experiment, break things, fix things, and especially build solutions that could potentially benefit me.

## Hardware & Tools

The machine that I am using is an old Dell Latitude 7290 with the following Specifications.

| Component   | Specification              |
|-------------|----------------------------|
| **CPU**     | Intel Core i5-7200U, 2 Cores, 4 Threads, 2.5 GHz Base Clock |
| **Memory**  | 16 GB DDR4 RAM              |
| **Storage** | 256 GB SSD                 |

Tools

### Tools Used

| Tool       | Purpose                                      | Version/Details          |
|------------|----------------------------------------------|--------------------------|
| **K3s**    | Lightweight Kubernetes distribution for easy deployment | Version: v1.31.6+k3s1 |
| **FluxCD** | GitOps tool for continuous deployment and management | Version: v2.5.1 |
| **Cloudflare** | Used for hosting applications publicly | Managed DNS and SSL |

