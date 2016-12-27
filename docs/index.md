# How to use infra-data

[infra-data](https://github.com/Epiconcept-Paris/infra-data) is an
EpiConcept private repos.

It contains structural informations about EpiConcept infrastructure
like lists of networks, IPs, VMs, users, etc.

From this stable yaml list of dict we build specific ansible vars and
inventory files.

The generated ansible files are tagged and push back to `infra-data`.

Here we show how to use such a *tag* to add to a public repos using a
dedicated playbook the private data you need from `infra-data`.
