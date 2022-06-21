# Curated list of SPIFFE and SPIRE resources

## Content

- [Video](#video)
    - [SPIFFE and SPIRE Introduction](#spiffe-and-spire-introduction)
    - [Advanced topics](#advanced-topics)
- [Blog posts](#blogs)
- [Utils](#utils)
- [SDK](#sdk)
- [Examples](#examples)

## Video

### SPIFFE and SPIRE Introduction

_A great place to start. Introduction to different concepts and integrations_

- [10 minites introduciton to SPIFFE and SPIRE](https://www.youtube.com/watch?v=Q2SiGeebRKY)
    - February 2020
    - Evan Gilman

- [Real World SPIFFE Scenarios and Outcomes](https://www.youtube.com/watch?v=YTmkh4UlnNA)
    - Andres Vega & Frederick Kautz
    - May 2022
    - KubeCon EU
    - Introduction
    - From perimeter to identity-based security, how do SPIFE and SPIRE solve these challenges, Who should care about SPIFFE in your organization? SPIFFE and SPIRE 101

- [Mithril: Introducing Robust Identities into Istio by integrating with SPIRE](https://www.youtube.com/watch?v=xhd8MhG4Vvw)
    - March 2022
    - HPE DEV MUNCH and LEARN
    - Introduction, Integrations
    - Challenges to secure hybrid environment, identity-based security, SPIFFE and SPIRE 101, architecture, deployment models, federation, what is service-mesh, what is istio, What is Mithril, Istio + SPIRE Integration, demo
- [SPIFFE: In Theory and in Practice](https://www.youtube.com/watch?v=DXE6CDJjDV4)
    - Evan Gilman & Andrew Harding, VMware
    - October 2021
    - KubeCon NA

- [Introduction to SPIFFE by Kelsey Hightower](https://www.youtube.com/watch?v=6e4snGCTLOk)
    - Kelsey Hightower
    - December 2020

- [SPIFFE and SPIRE: Architecture Deep Dive](https://www.youtube.com/watch?v=ZJxq8hPgYVI)
    - Andrew Harding & Evan Gilman, VMware
    - December 2020


- [Five Things You Didn’t Know You Could Do with SPIFFE and SPIRE](https://www.youtube.com/watch?v=5m6kjzdysBI)
    - Andrew Jessup & Andrés Vega
    - November 2019 KubeCon NA
    - History and Federation

- [TGI Kubernetes 094: SPIFFE and SPIRE](https://youtu.be/cx__8khtih4?t=1019)
    - Joe Beda
    - Ocotber 2019
    - History of SPIFFE, SPIFFE ID, SVID, etc. SPIRE concepts. Demo with k8s

- [Securing Multi-Cloud Cross-Cluster Communication with SPIFFE and SPIRE](https://www.youtube.com/watch?v=sLN11qAFAC4)
    - Evan Gilman, Scytale, Inc.
    - May 2019
    - KubeCon EU
    - Security model, SPIRE Architecture, Node Attestation, Workload attestation, Selectors, Deployment topologies

- [Managing Microservices Identity with SPIFFE](https://www.youtube.com/watch?v=6b76J8bC2Ac)
    - November 2018
    - East Bay Cloud Native Meetup

- [SPIFFE and SPIRE in 6 minutes](https://www.youtube.com/watch?v=C1kwY0N4PUk&t=375s)
    - May 2018
    - KubeCon EU 2018

- [SPIFFE Project Intro](https://www.youtube.com/watch?v=0LSaNrOabH4)
    - Andrew Jessup & Emiliano Berenbaum, Scytale, Inc.
    - May 2018
    - KubeCon EU

- [Introducing SPIFFE: An Open Standard for Identity in Cloud Native Environments](https://www.youtube.com/watch?v=ikmxZdZRTio)
    - Evan Gilman
    - December 2017
    - KubeCon NA

**[⬆ back to top](#content)**

### Advanced topics
_Deep dive topics into different SPIRE and SPIFFE concepts as well as advanced use-cases and deployemnt/operation models_

- [SPIRE: Intro & Deep Dive Into Windows Support](https://www.youtube.com/watch?v=pcyOnX08jHs)
    - Agustín Martínez Fayó & Marcos Yacob
    - May 2022
    - KubeCon EU
    - Deep dive
    - SPIFFE and SPIRe overview, SPIRE on Windows, Windows-specific attestation, Demo

- [Multi-Cloud Workload Identity With SPIFFE](https://www.youtube.com/watch?v=vKRUq56xDiE)
    - Jake Sanders & Charlie Egan, Jetstack
    - May 2022
    - KubeCon EU
    - Integrations
    - Workload identity, challenges of single vs multi-cloud architecture, what is SPIFE, what is cert-manager,  SPIFFE-connector and its architecture, demo

- [Integrating SPIRE with Tekton and Sigstore](https://www.youtube.com/watch?v=feX-7vELRe8)
    - Priya Wadhwa & Parth Patel
    - March 2022
    - SPIFFE and SPIRE March meetup
    - Integrations
    - What is Tekton, Tekton Chains, Tekton Chains workflow,  SALSA Framework, Tekton and SPIRE integration, Architectrure, Demo

- [Keyless signing and verification of artifact metadata with Witness and SPIRE](https://www.youtube.com/watch?v=nwBWPBTCVf8)
    - Cole Kennedy
    - March 2022
    - SPIFFE and SPIRE March meetup
    - Integrations
    - Attestation-based security model,  Whtness and Judge architecture, Integration with SPIRE for keyless signing, Demo

- [Bridging the Great Divide: SPIFFE/SPIRE for Cross-Cluster Authentication](https://www.youtube.com/watch?v=sjKNsnEYmiU)
    - Andrew Harding, VMware
    - October 2021
    - KubeCon NA
    - The problem of multi-cluster authentication, SPIFFE and SPIRE refresher, SPIRE controller architecture, Demo architecture, demo

- [Untangling the Multi-Cloud Identity and Access Problem With SPIFFE Tornjak](https://www.youtube.com/watch?v=Voy_8wifB0E)
    - B Lum & M Sabath
    - October 2021
    - KubeCon NA
    - Workload identity, Multi-cloud access problem, solutions with more problems, solution based on SPIFFE universal identity, Meet Tornjak, architecture, demo

- [Deployment Patterns for Operating SPIRE at Scale](https://www.youtube.com/watch?v=dboEv4HMwp0)
    - Evan Gilman
    - March 2021
    - SPIFFE and SPIRE meetup
    - SPIRE Deployment Models
    - Basic SPIRE architecture, Single SPIRE server, SPIRE Servers in HA, Nested SPIRE, Federated SPIRE, 

- [Securing the software supply chain with in-toto and SPIRE](https://www.youtube.com/watch?v=wDDSx0jwv4I)
    - Cole Kennedy
    - March 2021
    - SPIFFE and SPIRE meetup
    - Integrations
    - ZTA, Evidence-based trust, in-toto, using SPIRE for identity verification, demo

- [Using SPIFFE Identities in PARSEC](https://www.youtube.com/watch?v=ahJnTRTJG0A)
    – Paul Howard, Hugues de Valon
    - March 2021
    - SPIFFE and SPIRE meetup
    - Integrations
    - What is PARSEC, Parsec architecture, Multitenancy in parsec, Integrating PSIRE and Parsec for authentication of clients, demo

- [Sneak Peek Severless support](https://www.youtube.com/watch?v=6Jwe4IIGWvs)
    - Agustín Martínez 
    - February 2021
    - SPIFFE and SPIRE Meetup
    - Advanced architecture
    - Challenges of supporting serverless identities, architecture

- [AWS App Mesh, Mutual TLS and SPIRESPIRE Integration](https://www.youtube.com/watch?v=m38vZrMNLzw)
    - Efe Selcuk
    - February 2021
    - SPIFFE and SPIRE Meetup
    - Integrations
    - Intro to AWS App Mesh, Mutual TLS, SPIRE on AWS: EC2, ECS, Fargate, Challenges with fargate (registration, identity bootstrap). App Mesh and EKS SPIRE integration. AppMesh architecture,  Scaling Parameters and perf, Demo

- [Service Identity at Scale at Netflix](https://www.youtube.com/watch?v=-mmOT9I6JlY)
    - Ian Haken
    - October 2020
    - SPIFFE and SPIRE Meetup
    - Case study
    - Netflix ecosystem, need for identities, attestation, AWS instance metadata, bootstrap of trust, nodes, containers, non-cloud, universal identity, scaling identity platform, Authorization, similarities of Netflix identity system with SPIRE and SPIFFE

- [Attestation and identity provisioning to Intel SGX workloads](https://www.youtube.com/watch?v=8xwO1FgVyCU)
    - Andrey Brito
    - December 2020
    - Production Identity day
    - Integrations
    - SGX concepts 101, Porting apps to SGX, Integrating SPIFFE and SGX, Threat model, Integration flow.

- [Using DevIDs and TPMs for Node Attestation](https://www.youtube.com/watch?v=SSdWeDf02TM)
    - Adriane Cardozo, Marcos Yedro
    - December 2020 
    - Production Identity day
    - Integrations
    - DevID and TPM 101, [802.1AR](https://1.ieee802.org/security/802-1ar/), TPM2 attestation design, Demo

- [Fortifying Microservice Security with SPIRE and OPA](https://www.youtube.com/watch?v=iQ5ctLQswUc)
    - Ash Nakar
    - December 2020
    - Production Identity day
    - Integrations
    - What is OPA, OPA 101, Demo, Propogatin user identity through JWT SVID

- [Using a CRD to better integrate SPIRE and Kubernetes](https://www.youtube.com/watch?v=_6yKKvYQcak)
    - Faisal Memon
    - December 2020
    - Production Identity day
    - Integrations
    - SPIRE and NGINX, SPIRE provides Identities and certificates for Webhooks and API servers certs. CRD for SPIRE and why use CRD. Demo.

- [Leveraging Certificate Transparency to Strengthen Auditability in SPIRE](https://www.youtube.com/watch?v=xgzQEb9hbMI&t=1272s)
    - Ruide Zhang, Bytedance
    - December 2020
    - Production Identity day
    - Integration
    - Certificate Transparency in SPIRE, Showcase of a certificate with SCT, 

- [Establishing Trust Across Regulatory Boundaries in Complex, Heterogeneous Infrastructures With SPIRE](https://www.youtube.com/watch?v=MUFQSD6EmZ8)
    - Jonathan Oddy
    - March 2020
    - SPIFFE and SPIRE Meetup
    - Case study
    - The scale of the company and Infrastructure, Service authentication, challenges, Kafka integration, trust domain federation, benefits using SPIRE, and remaining challenges


- [Operationalizing SPIRE at Square](https://www.youtube.com/watch?v=KP9rME3zw6g)
    - Matthew McPherrin
    - March 2020
    - SPIFFE and SPIRE Meetup
    - Case study, Operations
    - Square hybrid multi-cloud architecture, SPIFFE arch overview,  Architect for reliability: Datastore,  dealing with datastore failures, region failure, spire server failure, spire agent failures, no identity issued, monitoring spire, custom logging with SPIRE, recovering from failures. 


- [Observability in SPIRE at Scale](https://www.youtube.com/watch?v=nIRy_aI0E5k&list=PLAtJVtsZ0KWZSRIsOfK4CQeVKNqNKe0_7&index=9)
    - Andrew Moore
    - March 2020
    - SPIFFE and SPIRE Meetup
    - Advanced topics, Operations
    - Telemetry implementation, Scale at Uber, agent observability, logs vs metrics, server observability, future enhancements 

- [Securing Communication Between Meshes and Beyond with SPIFFE Federation](https://www.youtube.com/watch?v=cx_NnvbsCP4)
    - Evan Gilman & Oliver Liu
    - November 2019
    - KubeCon NA
    - Integraitons
    - What is a ServiceMesh, SPIFFE, Identity and service mesh, Hybrid and multi-mesh examples, Different identity authority architectures, SPIFFE Federation as the exchange of trust, Istio and SPIRE federation, Demo, 

- [Scaling SPIRE for Performance and Availability](https://www.youtube.com/watch?v=uF_fU-ngXxY&list=PLj6h78yzYM2NDs-iu8WU5fMxINxHXlien)
    - Tyler Julian, Uber
    - November 2019
    - KubeCon NA
    - Practical design decisions, Operations
    - The concept of the root of trust,  What is SPIFFE, SPIRE Architecture, short-lived credentials vs revocation, Registration challenges, Scaling registration,  Per-cluster vs per-host workload registration, TTL: security vs Reliability


- [Integrating SPIRE with workload schedulers](https://www.youtube.com/watch?v=H5IlmYmEDKk&t=4745s)
    - Tyler Dixon, Uber
    - May 2019
    - SPIFFE Community Day
    - Design decisions, Integrations
    - Background, Workload registration strategies, workload lifecycle readiness check, liveness check and relation to registration and resilience.

- [Securing Application Telemetry & Tracing with SPIFFE and Envoy](https://www.youtube.com/watch?v=_OzG4PHihSk)
    - Sabree Blackmon, Docker
    - December 2018
    - KubeCon NA
    - Integrations
    - Importance of different data types, What are telemetry, logging, tracing, and audit data. Simple-secrets case study and demo of integrating with envoy and spire.

**[⬆ back to top](#content)**

## Blogs


- [AWS OIDC Authentication with SPIFFE](https://developer.squareup.com/blog/aws-oidc-authentication-with-spiffe/)
    - Easy authentication with automated AWS credentials. Federation with AWS.

- [Providing mTLS Identities to Lambdas](https://developer.squareup.com/blog/providing-mtls-identities-to-lambdas/)
    - Securing severless communication with our data centers.

- [Azure AD workload identity federation with SPIFFE and SPIRE](https://blog.identitydigest.com/azuread-federate-spiffe/)
    - SPIFFE federation with Azure Cloud.

- [Using mTLS with SPIFFE/SPIRE in AWS App Mesh on Amazon EKS](https://aws.amazon.com/blogs/containers/using-mtls-with-spiffe-spire-in-app-mesh-on-eks/)
    - SPIFFE federation with AWS cloud.

- [SPIFFE/SPIRE Federation on Kind clusters](https://techblog.cisco.com/blog/spire-federation-kind)
    - SPIFFE federation.

- [Shepherding your Cloud Native “cattle” with Tornjak](https://medium.com/universal-workload-identity/shepherding-your-cloud-native-cattle-with-tornjak-eb0b9a7c96bc)
    - Introduction to project Tornjak

**[⬆ back to top](#content)**

### SDK

- [go spiffe](https://github.com/spiffe/go-spiffe)
    - This library is a convenient Go library for working with SPIFFE.

- [java spiffe](https://github.com/spiffe/java-spiffe)
    - Java SPIFFE Library.

- [c spiffe](https://github.com/HewlettPackard/c-spiffe)
    - C SPIFFE library.

- [python spiffe](https://github.com/HewlettPackard/py-spiffe)
    - This SPIFFE library provides a Workload API client to fetch X.509 and JWT SVIDs and trust bundles. **Important:** This library currently doesn't provide any functionality to support TLS connections using SPIFFE certificates.

- [rust spire-workload-rs](https://github.com/bytedance/spire-workload-rs)
    - This crate provides a number of useful APIs to help Rust programs use Spire workload API.

- [rust-spiffe](https://github.com/maxlambrecht/rust-spiffe)
    - An utility library to interact with the SPIFFE Workload API to fetch X.509 and JWT SVIDs and Bundles. It also provides types that comply with the SPIFFE standards.

**[⬆ back to top](#content)**

## Utils

- [spire-oidc-discovery-provider](https://github.com/spiffe/spire/tree/main/support/oidc-discovery-provider)
    - The SPIRE OIDC Discovery Provider is a small helper that provides a minimal implementation of a subset of the OIDC discovery document as related to exposing a JSON Web Key Set (JWKS) for JSON Web Token (JWT) validation.

- [k8s-workload-registrar](https://github.com/spiffe/spire/tree/main/support/k8s/k8s-workload-registrar)
    - The SPIRE Kubernetes Workload Registrar implements a Kubernetes ValidatingAdmissionWebhook that facilitates automatic workload registration within Kubernetes.

- [SPIFFE CSI Driver](https://github.com/spiffe/spiffe-csi)
    - A Container Storage Interface driver for Kubernetes that facilitates injection of the SPIFFE Workload API.

- [spiffe-aws-assume-role](https://github.com/square/spiffe-aws-assume-role)
    - This tool allows using a SPIFFE JWT to authenticate to AWS APIs

- [Tornjak](https://github.com/spiffe/tornjak)
    - The project aims to provide a management plane and capabilities for SPIFFE identities managed by SPIRE. The goals are to provide global visibility, auditability, and configuration and policy management for identities.

- [SPIFFE Helper](https://github.com/spiffe/spiffe-helper)
    - The SPIFFE Helper is a simple utility for fetching X.509 SVID certificates from the SPIFFE Workload API, launch a process that makes use of the certificates and continuously get new certificates before they expire. The launched process is signaled to reload the certificates when is needed.

- [cert-manager csi-driver-spiffe](https://github.com/cert-manager/csi-driver-spiffe)
    - csi-driver-spiffe is a Container Storage Interface (CSI) driver plugin for Kubernetes to work along cert-manager. This CSI driver transparently delivers SPIFFE SVIDs in the form of X.509 certificate key pairs to mounting Kubernetes Pods.

- [NGINX with SPIFFE support](https://github.com/MarcosDY/spiffe-nginx)
    - This version of NGINX Open Source interacts with the SPIFFE Workload API to request and use certificates for mTLS.

- [Kafka SPIFFE Principal Builder](https://github.com/traiana/kafka-spiffe-principal)
    - A custom KafkaPrincipalBuilder implementation for Apache Kafka. This class and documentation deals only with SslAuthenticationContext, we do not support any other context at the moment (Kerberos, SASL, Oauth)

- [Emissary](https://github.com/github/emissary)
    - This is a service that communicates with spire-agent to fetch and validate JWT-SVIDs sent to it over HTTP, usually from envoy using ext_authz.

- [SPIFFE Vault](https://github.com/philips-labs/spiffe-vault)
    - Integrates SPIFFE SVID authentication with Hashicorp Vault to retrieve a `VAULT_TOKEN`. Example usecases
        - Read secrets from Hashicorp Vault Hashicorp Vault without providing a secret to authenticate against Hashicorp Vault. Instead we will be using a SPIFFE SVID to authenticate ourself against Hashicorp Vault.
        - Perform secretless/keyless code signing by utilizing the Hashicorp Vault Transit engine as a software defined HSM. This resolves the issue of having signing keys on a local machine as well resolves the issue of managing secrets to access the signing keys. Again we utilize the SPIFFE SVID to authenticate against Hashicorp Vault.

- [Kerberos-Attestor](https://github.com/nks5295/kerberos-attestor)
    - The Kerberos-Attestor is a plugin for the SPIRE server and agent that allows SPIRE to automatically attest nodes that are joined to a domain backed by the Kerberos authentication protocol. 

- [SPIRE TPM Plugin](https://github.com/bloomberg/spire-tpm-plugin)
    - This repository contains agent and server plugins for SPIRE to allow TPM 2-based node attestation.

- [SPIRE Tailscale Plugin](https://github.com/jsiebens/spire-tailscale-plugin)
    - This node attestation plugin relies on a Tailscale OIDC id-token feature, which is marked as Work-in-Progress and may not be available for everyone yet.

**[⬆ back to top](#content)**

### Examples

- [Istio Identities with SPIFFE/SPIRE](https://github.com/IBM/istio-spire)
    - The scripts in this repository demonstrate how to replace the identity-issuing mechanism of Istio with that of Spire.

- [spiffe-user-demo](https://github.com/JackOfMostTrades/spiffe-user-demo)
    - This is a proof of concept project that runs a SPIFFE Workload API service meant to provide user-based SVIDs on developer endpoints, bootstrapped from an SSO login. This demo in particular integrates with OIDC providers to enable user login, but generalizes to any web application SSO.

- [Java SPIFFE examples](https://github.com/maxlambrecht/java-spiffe-examples)
    - A bunch of java-spiffe use examples

- [SPIRE and SGX-SCONE](https://github.com/ufcg-lsd/spire-scone-demo)
    -  Issuing SPIFFE IDs to SGX Confidential Workloads

- [opa-spiffe-oidc](https://github.com/ashutosh-narkar/opa-spiffe-oidc)
    - This repository contains the code for the OPA-SPIFFE OIDC Demo.

- [spire-envoy-kafka](https://github.com/flobuehr/spire-envoy-kafka)
    - Data exchange demo - Kafka integrated with Envoy proxy and SPIRE

**[⬆ back to top](#content)**