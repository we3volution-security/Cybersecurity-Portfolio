# Active Directory Basics

**Platform:** TryHackMe
**Path:** Cyber Security 101
**Module:** Active Directory Basics
**Status:** ✅ Completed
**Environment:** Windows / Active Directory lab environment
**Lab Type:** Hands-on Windows domain and Active Directory lab

---

## Overview

Active Directory Basics introduced the structure and operation of Microsoft Active Directory within Windows domain environments.

This represented an important progression from individual Windows system administration towards understanding how multiple computers, users and security policies can be centrally managed within an enterprise environment.

TryHackMe describes Active Directory as the directory service used by Windows domain networks and highlights its importance when attacking Windows environments. The room covers domains, forests, users and groups, trusts, policies, Domain Services and authentication.

---

# Practical Environment

The room included a dedicated practical environment for applying the concepts covered during the learning material.

The hands-on work provided experience investigating an Active Directory environment rather than learning the structure solely as theory.

The practical progression can be represented as:

```text
Windows System
      ↓
Windows Domain
      ↓
Domain Controller
      ↓
Users + Groups
      ↓
Policies
      ↓
Authentication
      ↓
Trust Relationships
      ↓
Enterprise Attack Surface
```

---

# What I Learned

## Windows Domains

Developed an understanding of how Windows computers and users can be organised and centrally managed within a domain.

---

## Active Directory

Learned how Active Directory provides a central directory service containing information about users, computers, groups and other resources.

---

## Users & Groups

Explored how identities and group membership influence access within a Windows domain environment.

This introduced the importance of understanding:

* User accounts
* Group membership
* Permissions
* Privileges
* Access relationships

---

## Domain Controllers

Developed an understanding of the role of domain controllers in managing and authenticating users and computers within a Windows domain.

---

## Group Policy

Introduced Group Policy as a mechanism for centrally managing configuration and security settings across domain-connected systems.

---

## Authentication

Developed foundational knowledge of how users authenticate within Windows domain environments.

Understanding authentication is particularly important when progressing towards security testing involving:

* Credentials
* Authentication protocols
* Privilege
* Identity
* Lateral movement

---

## Trees, Forests & Trusts

Learned how Active Directory environments can contain multiple domains organised into trees and forests, and how trust relationships can connect domains.

This introduced the concept that enterprise environments are not simply collections of isolated machines.

---

# Hands-On Experience

The practical work provided experience applying Active Directory concepts within a Windows domain environment.

This included investigating:

* Domain structure
* Users
* Groups
* Computers
* Policies
* Authentication
* Domain relationships
* Active Directory components

The room includes a dedicated hands-on lab following the conceptual sections.

---

# Practical Skills Demonstrated

The module developed practical understanding of:

`Active Directory`

`Windows Domains`

`Domain Controllers`

`Users & Groups`

`Group Policy`

`Authentication`

`Trust Relationships`

`Enterprise Windows`

`Identity & Access`

---

# Cybersecurity Relevance

Active Directory is particularly important to enterprise penetration testing.

A large proportion of corporate Windows environments rely on Active Directory for identity and access management.

From an offensive-security perspective, understanding Active Directory provides the foundation for later studying:

* Domain enumeration
* LDAP
* Kerberos
* Credential attacks
* Privilege escalation
* Account abuse
* Lateral movement
* Domain compromise
* Attack paths
* Enterprise red-team operations

From a defensive perspective, the same knowledge helps explain how attackers may move through an enterprise environment and where identity and access controls need to be protected.

---

# Why This Matters to My Development

Active Directory represents an important transition in my cybersecurity training.

My earlier work focused primarily on individual Linux and Windows systems.

Active Directory introduces a much larger concept:

> **How systems, identities, permissions and policies interact across an organisation.**

This is particularly relevant to my longer-term interest in penetration testing and red-team operations.

At the same time, understanding the defensive side of Active Directory provides useful context for assessing and improving enterprise security.

---

# Evidence

Evidence will be added as screenshots are organised.

**Evidence location:**

`/evidence/screenshots/security-101/active-directory-basics/`

### Planned evidence

* Active Directory lab environment
* Windows domain environment
* Domain structure
* Users and groups
* Computer objects
* Group Policy
* Authentication concepts
* Domain/forest relationships
* Hands-on lab interaction

Screenshots will demonstrate practical interaction without publishing credentials, flags or complete room solutions.

---

# Key Takeaway

Active Directory Basics introduced the fundamentals of enterprise Windows identity and access management.

The most important outcome was understanding that Windows security extends beyond individual machines into relationships between:

```text
Users
  ↕
Groups
  ↕
Permissions
  ↕
Computers
  ↕
Policies
  ↕
Domains
  ↕
Trusts
```

This provides an important foundation for future Active Directory enumeration, Windows privilege escalation, lateral movement and enterprise penetration-testing work.

---

## Further Development

Future Active Directory security development will build towards:

* Active Directory enumeration
* LDAP
* Kerberos
* Windows authentication
* Credential attacks
* Privilege escalation
* Lateral movement
* Domain security
* Attack-path analysis
* Enterprise penetration testing
* Red-team operations
