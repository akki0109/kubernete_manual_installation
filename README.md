# Kubernetes Installation and Application Deployment with Helm

This repository contains code and instructions for setting up a Kubernetes cluster and deploying applications using Helm charts.

## Installation

1. **Step 1:** Install Kubernetes using the following commands:

   ```bash
   $ curl -LO https://storage.googleapis.com/kubernetes-release/release/$(curl -s https://storage.googleapis.com/kubernetes-release/release/stable.txt)/bin/linux/amd64/kubectl
   $ chmod +x ./kubectl
   $ sudo mv ./kubectl /usr/local/bin/kubectl
