# Kubernetes Certificate Management Example Spreadsheet
This repository provides an example spreadsheet for managing Kubernetes certificates. It is intended as a reference for future projects, allowing teams to replicate or get inspiration for their own certificate tracking methods.

## kubernetes-certs-checker.xlsx - Spreadsheet Details
The provided spreadsheet, kubernetes-certs-checker.xlsx, is a template that outlines a systematic approach to tracking and managing Kubernetes certificates. It covers the essentials required for a secure Kubernetes setup:

* **Certificate Authorities**: Identifies the CAs used within the cluster.
* **Server and Client Certificates**: Lists the certificates required by Kubernetes servers and clients, including kube-apiserver, etcd, kubelet, and others.
* **File Paths**: Indicates where each certificate and key should reside within the filesystem.
* **Certificate Details**: Includes common names, alternative names, issuing authorities, and expiration dates for each certificate.
* **Usage Descriptions**: Provides a brief explanation of each certificate's role and purpose within the Kubernetes ecosystem.
## Purpose
The spreadsheet serves as an example for:

* System administrators setting up Kubernetes clusters.
* Security professionals auditing Kubernetes certificate management.
* DevOps teams automating certificate rotation and deployment.
* By providing a clear template, this repository assists in maintaining a record of all necessary certificates, their locations, and their expiration dates to ensure the Kubernetes cluster remains secure and functional.

## Repository Overview
Contained within this repository is a single Excel file:

kubernetes-certs-checker.xlsx: An Excel spreadsheet template detailing the certificate structure for a Kubernetes cluster.
