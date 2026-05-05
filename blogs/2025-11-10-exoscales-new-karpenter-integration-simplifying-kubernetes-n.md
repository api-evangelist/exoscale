---
title: "Exoscale’s New Karpenter Integration: Simplifying Kubernetes Node Management"
url: "/blog/sks-karpenter/"
date: "Mon, 10 Nov 2025 10:00:00 +0000"
author: ""
feed_url: "https://www.exoscale.com/blog/rss.xml"
---
<p>Exoscale Scalable Kubernetes Service (SKS) has long time support for
<a href="https://github.com/kubernetes/autoscaler" rel="noopener" target="_blank">cluster-autoscaler</a> to automatically adjust the number
of nodes in a Kubernetes cluster based on the resource requests of the workloads running in the cluster.
This integration has been a key feature for our users, allowing them to optimize their resource
usage and reduce costs. This implementation relies on SKS Nodepool implementation.
With the introduction of Karpenter, a modern open-source framework, we are
excited to enhance our SKS Pro offering even further. Karpenter is a flexible, high-performance
Kubernetes cluster autoscaler that improves upon the existing cluster-autoscaler by providing faster
scaling, better resource utilization, and support for a wider range of workloads (like GPUs).</p>
