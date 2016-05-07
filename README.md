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

The TBF mechanism is handled by the cross-domain unidirectional autonomic control loop through two authorization servers each in their own administrative domain.

## OSI Model from a federation's perspective

[OSI Model]: https://github.com/token-7/token7-specs/wiki/OSI-Model-from-a-federation's-perspective

## Federated trust relationship without central OAuth 2.0 authority

Each federated trust relationship between two administrative domains is defined as
an assymetric one-way trust between federator and federatee.

[Understanding trust and federation direction]: https://github.com/token-7/token7-specs/wiki/Uderstanding-OAuth2-trust-and-federation-direction

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
