# LibreAkaunto Fork Compliance Guide

This document defines the operating policy for the LibreAkaunto fork of Akaunting.

## 1) License Baseline (BSL)

The baseline license is `LICENSE.txt` (Business Source License 1.1 with Additional Use Grant).

Key operational implications for this fork:

- Keep license text intact and visible in distributed copies.
- Keep required attribution/copyright notices.
- Do not remove or replace required Akaunting branding in a way that creates a rebranded/white-labeled distribution unless separate commercial rights are obtained from the licensor.
- Respect trademark limits defined by the license.

## 2) Naming and Branding Policy

- Organization/distribution identity: **LibreAkaunto**.
- Product identity in-app (under current BSL constraints): **Akaunting**.
- Recommended public phrasing: **“LibreAkaunto, an EU-compliance-focused distribution of Akaunting.”**

## 3) Fork Distribution Requirements

Before distributing releases from this fork:

- Verify `LICENSE.txt` is present and unmodified in release artifacts.
- Verify attribution and branding references required by license remain present.
- Verify no UI/asset changes remove protected branding in ways prohibited by the Additional Use Grant.

## 4) EU Compliance Positioning

### Built-in controls this codebase can support

- User/role/permission controls (where configured by deployer).
- Data export/reporting capabilities that may assist access and portability workflows.
- Activity/audit-oriented features where enabled via product modules/settings.

### Deployer/operator responsibilities

EU compliance depends on deployment-specific configuration and governance. Operators remain responsible for:

- Privacy notice and legal basis disclosures.
- Data processing agreements and processor/subprocessor governance.
- Retention/deletion policies and execution workflows.
- Cookie/consent implementation where required.
- Data subject request handling procedures.
- Security configuration, access controls, backups, and incident response processes.

## 5) Release Gate

Before public release, perform a legal review covering:

- BSL interpretation for the target use case.
- Trademark and branding usage in product/UI/distribution channels.
- Accuracy of any “EU-compliant” claims and wording.

> This guide is a project policy note, not legal advice.
