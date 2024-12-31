---
layout: post
title: "EUC News and Updates - December 2024"
permalink: "/euc-news-and-updates-December-2024/"
description: "Latest News and Updates in EUC."
categories: [DaaS, VDI, EUC, News, Update]
image:
  path: /assets/img/general/news.jpg
sitemap: true
hide_last_modified: false
comments: true
---

<!--excerpt-->

-  Table of Contents
{:toc}

# EUC News and Updates - December 2024

# EUC News and Updates December 2024

Here’s a roundup of News and Updates from December 2024.

## EUC News

The following are some of the key news items in EUC for the month of December 2024:

### Citrix and AWS

**Citrix Announces GA of Citrix DaaS on Amazon WorkSpace Core**

Last month, Citrix, a business unit of Cloud Software Group, Inc., announced the general availability of Citrix DaaS™ for Amazon WorkSpaces Core from Amazon Web Services (AWS). You can see the announcement [here](https://www.citrix.com/news/announcements/nov-2024/citrix-announces-general-availability-of-citrix-daas-for-amazon-workspaces-core.html). It will be interesting to see the uptake by customers.

### Microsoft

**Microsoft extends Azure cloud infrastructure to Western Australia**

![Perth, Western Australia](/assets/img/general/perth.jpg "Perth, Western Australia")

Historically for customers in Western Australia, the nearest Azure resources were either on the other side of the country or in Singapore. This meant that even for people in Perth, the capital of WA which is well connected, latency was typically 50-70ms and even further if you were in regional areas. I’ll detail more on this later once I do some testing, however for EUC workloads, this will mean Azure compute will be available for AVD or partner solutions such as Citrix on Azure, improving the experience of latency sensitive workloads.

The full details as provided by Microsoft can be seen [here](https://news.microsoft.com/en-au/2024/12/11/microsoft-extends-azure-cloud-infrastructure-to-western-australia/?msockid=21acd069abb860c63f63c387aad86119).

## EUC Updates

The following are some of the EUC Updates for the month of December 2024:

### Cloud Software Group

**Citrix Cloud**

- [Citrix DaaS: Image management is now Generally Available](https://docs.citrix.com/en-us/citrix-daas/whats-new#november-2024) – Citrix Docs
- [Eight new features in Citrix Monitor](https://docs.citrix.com/en-us/citrix-daas/whats-new#december-2024) – View the resource location for machines; Session Topology includes new endpoint metrics; Cloud Connector health monitoring – Citrix Docs
- [Citrix DaaS new features](https://docs.citrix.com/en-us/citrix-daas/whats-new.html#december-2024) – Support for creating Citrix Provisioning catalogs in VMware environments using Studio; Delivery of app attach disks as CimFS – Citrix Docs
- [Citrix DaaS 12/2024](https://docs.citrix.com/en-us/citrix-daas/whats-new.html#december-2024) – Storage load balancing with least load method – If you select two or more OS data storage locations during catalog creation, disks can be allocated to the least loaded storage repository – Citrix Docs
- [Demo of upcoming Citrix Cloud navigation changes](https://youtube.com/watch?v=jP3XHNIBm0A) – YouTube video

**Citrix Gateway**

- [Detecting and Mitigating Password Spraying Attacks on NetScaler Gateway](https://community.citrix.com/tech-zone/build/tech-papers/detecting-and-mitigating-password-spraying-attacks-nsg/) – Citrix Tech Zone
- Download [Citrix Secure Access for Windows 24.11.1.17](https://citrix.com/downloads/citrix-gateway/plug-ins/citrix-secure-access-client-for-windows.html)

**Citrix StoreFront**

- Download [Citrix Workspace app 2411 for HTML5](https://citrix.com/downloads/workspace-app/html5/workspace-app-for-html5-latest.html)

**Citrix Virtual Apps and Desktops**

- Download [Citrix Virtual Apps and Desktops 2411](https://citrix.com/downloads/citrix-virtual-apps-and-desktops/product-software/citrix-virtual-apps-and-desktops-alleditions-2411.html) – Starting with 2411, MMC-based Studio is deprecated; independent release of Director for LTSR deployments provides access to the latest Director features; Bulk alert dismissal
- [Citrix License Activation Service (LAS) is alternative to traditional Citrix legacy licensing](https://docs.citrix.com/en-us/licensing/current-release/license-activation-service) – No longer have license files to generate; licenses are activated automatically – Citrix Docs
- Download [Citrix License Server for Windows – Version 11.17.2.0 Build 51000](https://citrix.com/downloads/licensing/license-server/license-server-version-111720-51000-for-windows.html)
- Known Issue - While upgrading from previous Citrix Virtual Apps and Desktops versions to version 2411 or deploying a new site on version 2411, the [site creation fails when using a SQL Server 2016 database](https://docs.citrix.com/en-us/citrix-virtual-apps-desktops/whats-new/known-issues) – Citrix Docs

**Citrix Workspace app**

- Download [Citrix Workspace app 2409 for Windows](https://citrix.com/downloads/workspace-app/windows/workspace-app-for-windows-latest.html)
- Download [Citrix Workspace app for Windows LTSR 2402 Cumulative Update 2](https://citrix.com/downloads/workspace-app/workspace-app-for-windows-long-term-service-release/workspace-app-for-windows-LTSR-Latest.html)
- Download [Citrix Workspace app 2411 for Mac](https://citrix.com/downloads/workspace-app/mac/workspace-app-for-mac-latest.html)
- Download [Citrix Workspace app 2409.1 for Windows](https://citrix.com/downloads/workspace-app/windows/workspace-app-for-windows-latest.ext.html) – Fix for printer mapping

**Citrix XenServer**

- [XenCenter 2024.4.0](https://docs.xenserver.com/en-us/xencenter/current-release/whats-new) – Connect XenCenter to the Citrix Virtual Apps and Desktops environment to see information about Citrix Virtual Apps and Desktops machines and sessions hosted in your XenServer pool – XenServer Docs
- Download [XenServer Conversion Manager 8.4.0](https://xenserver.com/downloads) – Now automatically uninstalls VMware Tools from your VMs and provides the option to install XenServer VM Tools

**NetScaler ADC**

- [Citrix Demo: NetScaler VPX HA failover on Azure without an Azure Load Balancer](https://youtube.com/watch?v=K8B8FxHzim0) – Secondary private IP addresses of the primary node are migrated to the secondary node which is faster on new Azure control plane – YouTube video

**NetScaler Console**

- [NetScaler Console on-prem has the new GUI](https://docs.netscaler.com/en-us/netscaler-application-delivery-management-software/current-release/enhanced-gui) – NetScaler Docs
- Download [Citrix NetScaler Console (ADM) 14.1 Build 38.53](https://citrix.com/downloads/citrix-application-management/product-software/citrix-adm-14-1-build-38-53.html)
- Download [Citrix NetScaler ADC Release (Feature Phase) 14.1 Build 38.53](https://citrix.com/downloads/citrix-adc/firmware/release-14-1-build-38-53.html)

### Microsoft

- [Microsoft Teams VDI: SlimCore features vs WebRTC](https://learn.microsoft.com/en-us/microsoftteams/vdi-2#feature-list-with-the-new-optimization) – Microsoft Docs
- [Teams VDI SlimCore optimization in Citrix is Generally available](https://support.citrix.com/s/article/CTX691425-how-to-enable-teams-optimization-with-microsofts-new-vdi-optimization-engine-slimcore?language=en_US) – Microsoft has started the General Availability rollout for Citrix customers starting December 09, 2024 – Citrix Knowledgebase article

### Nerdio

**Nerdio Manager for Enterprise (NME)**

- [v6.6.0 (Release Date 12 December 2024)](https://nmehelp.getnerdio.com/hc/en-us/articles/19837802929677-Release-Notes#f5e5eb4a) – Health Dashboard, Rolling Drain Mode – Scale-in Agressiveness, Windows 365 Cross Region DR Support, Managed Identity Support (Preview), Auto-Shrink, Customer RBAC Dashboard, Custom Branding, New Reports, Azure Local enhancements, JSON and Rest API changes and Resolved Issues
- [v6.6.1 GA (Release Date 19 December 2024)](https://nmehelp.getnerdio.com/hc/en-us/articles/19837802929677-Release-Notes#f3bc122f) – Image Version Expiry and Removal, API update and Resolved Issues.

### Omnissa

- [Omnissa Access On Premises 24.12 Release Notes](https://docs.omnissa.com/bundle/workspace-one-access-release-notesV24.12/page/workspace-one-access-release-notes.html) – new option: Enable Horizon Client with Omnissa URL – Omnissa Docs
- [Omnissa App Volumes 2412 Release Notes](https://docs.omnissa.com/bundle/AppVolumesReleaseNotesV2412/page/AppVolumes-ReleaseNotes.html) – new visual elements and icons – Omnissa Docs