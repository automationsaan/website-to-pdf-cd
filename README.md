# GitOps repository

This repository is an integral part of the training project which consists of 3 parts:
1) Infrastructure https://github.com/automationsaan/website-to-pdf-infra
2) CI https://github.com/automationsaan/website-to-pdf-ci
3) CD (this) https://github.com/automationsaan/website-to-pdf-cd

Attention. This is an operational resource, a gitops repository. Here are placed complete Kubernetes manifests for deploying the application after the CI cycle: https://github.com/automationsaan/website-to-pdf-ci/blob/prod/.github/workflows/ci.yml
This resource should not be public. We have made it public for demonstration purposes. Don't make it public in your project.