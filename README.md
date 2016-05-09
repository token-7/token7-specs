# Token-Based Federation

## Abstract

Token-Based Federation (TBF) is an OAuth 2.0 federated authorization framework.
TBF defines interfaces, flows and constructs for coordinating access to heterogeneous OAuth 2.0
resource servers across multiple administrative domains.

## Introduction

To begin with, there are two different definitions for the term federation:

1. Information sharing between heterogeneous networks (telecommunications networks)  
2. Collective authority (federated identity)

The TBF framework refers to No. 1

##Architectural Principle

The TBF mechanism is handled by the cross-domain autonomic control loop through two authorization servers each in its own administrative domain.

## OSI Model from a federation's perspective

[OSI Model]

## Federated Trust Relationship

Each Federated Trust Relationship between two administrative domains is defined as
an asymmetric one-way trust between Trustor and Trustee paired with the reflexive asymmetric
unidirectional federation between Federator and Federatee.

[Understanding OAuth 2.0 access, trust and federation directions] 

## Low-Level Use Cases

### Authentication and Authorization

* Identity and Attribute Providers
* User-Managed Access

## Medium-Level Use Cases

### Public Key Infrastructure

* Identity-Based Privacy

### Signaling

* VoIP
* WebRTC

### Task Delegation

* Workflow System

### Blockchain

* Federated Ledger

## High-Level Use Cases

### New FTP/email-like services

* File Sharing System
* Persistent Group Chat

[OSI Model]: https://github.com/token-7/token7-specs/wiki/OSI-Model-from-a-federation's-perspective
[Understanding OAuth 2.0 access, trust and federation directions]:  https://github.com/token-7/token7-specs/wiki/Understanding-OAuth-2.0-access,-trust-and-federation-directions
