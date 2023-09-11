# Sysdig Onprem Install Documentation

The Sysdig Platform is a highly available application for securing and monitoring cloud-native infrastructures.

## Table of Contents
  * [Oversight Services Now Offered for All Installs and Upgrades](#oversight-services-now-offered-for-all-installs-and-upgrades)
  * [Supported Migration Paths](#supported-migration-paths)

## Oversight Services Now Offered for All Installs and Upgrades

> **Note**
>
> As part of our continued focus on our customers, we are now offering oversight services for all on-premise installs and upgrades. Your Technical Account Manager (TAM), in conjunction with our support organization and Professional Services \[where applicable\], will work with you to:

-   Assess your environment to ensure it is configured correctly

-   Review your infrastructure to validate the appropriate storage capacities are available

-   Review and provide recommendations for backing up your Sysdig data

-   Work with you to ensure our teams are ready to assist you during the install and upgrade process

-   Provide the software for the install

-   Be available during the process to ensure a successful deployment

> You can always review the process in the documentation.
>
> If you are a new customer looking to explore Sysdig, please head over [here](https://sysdig.com/company/freetrial/) to sign up for a trial on our SaaS Platform. Alternatively, you can contact us [here](https://sysdig.com/company/contactus/).

## K8s support matrix

Sysdig platform is continuosly being validated at multiple K8s flavors including k0ps, Openshift4, EKS, GKE, AKS, IKS, ROKS or RKE2. You can find below the K8s version support matrix. If you might have a question about a custom flavor or K8s version, please just share it with your TAM.

| Install version | Validated K8s versions |
|---|---|
| 5.0.X | 1.16, 1.17, 1.18, 1.19, 1.20, 1.21 |
| <= 5.1.9 | 1.18, 1.19, 1.20, 1.21, 1.22, 1.23, 1.24 |
| >= 5.1.10 | 1.23, 1.24, 1.25, 1.26, 1.27 |
| 6.0.X, 6.1.X | 1.23, 1.24, 1.25, 1.26 |
| >= 6.2.X | 1.23, 1.24, 1.25, 1.26, 1.27 |

## Supported Migration Paths

In general, Sysdig tests and supports direct upgrade from **two releases** back to the current version.

Beyond info at this repo, take a look to our [Sysdig On-Premises Release Notes](https://docs.sysdig.com/en/docs/release-notes/sysdig-on-premises-release-notes/)


|Install version | Supported Upgrade From | Latest Release |
|---|---|---|
| 6.x (by request) | 5.0.X, 5.1.X 6.X.X | [6.X](6.X) |
| 5.1 (by request) | 4.0.X, 5.0.X, 5.1.X | [5.1](5.1) |
| 5.0 (by request) | 4.0.X, 5.0.X | [5.0](5.0) |
| 4.0 (by request) | 3.6.X, 4.0.X | [4.0](4.0) |
| 3.6 (by request) | 3.2.X, 3.5.X, 3.6.X | [3.6](3.6) |

See [docs.sysdig.com](https://docs.sysdig.com/en/on-premises-upgrades.html#UUID-99ec8b45-9aed-4aff-d86b-ad17bc8ef333_UUID-92d3fce4-1e95-4f25-056c-3cc177380de6) for the rest of the migration table.

## Release history

### Version 6.x

- [6.4.1 Release, August 2023](https://docs.sysdig.com/en/docs/release-notes/sysdig-on-premises-release-notes/#641-release-august-2023)
- [6.4.0 Release, July 2023](https://docs.sysdig.com/en/docs/release-notes/sysdig-on-premises-release-notes/#640-release-july-2023)
- [6.3.0 Release, July 2023](https://docs.sysdig.com/en/docs/release-notes/sysdig-on-premises-release-notes/#630-release-july-2023)
- [6.2.1 Release, June 2023](https://docs.sysdig.com/en/docs/release-notes/sysdig-on-premises-release-notes/#621-release-june-2023)
- [6.1.2 Release, May 2023](https://docs.sysdig.com/en/docs/release-notes/sysdig-on-premises-release-notes/#612-release-may-2023)
- [6.1.1 Release, May 2023](https://docs.sysdig.com/en/docs/release-notes/sysdig-on-premises-release-notes/#611-release-may-2023)
- [6.0.2 Hotfix Release, April 2023](https://docs.sysdig.com/en/docs/release-notes/sysdig-on-premises-release-notes/#602-hotfix-release-april-2023)
- [6.0.0 Release, April 2023](https://docs.sysdig.com/en/docs/release-notes/sysdig-on-premises-release-notes/#600-release-april-2023)

### Version 5.x

- [5.1.10 Hotfix Release, September 2023](https://docs.sysdig.com/en/docs/release-notes/sysdig-on-premises-release-notes/#5110-hotfix-release-september-2023)
- [5.1.9 Hotfix Release, April 2023](https://docs.sysdig.com/en/docs/release-notes/sysdig-on-premises-release-notes/#519-hotfix-release-april-2023)
- [5.1.8 Hotfix Release, February 2023](https://docs.sysdig.com/en/docs/release-notes/sysdig-on-premises-release-notes/#518-hotfix-release-february-2023)
- [5.1.7 Hotfix Release, January 2023](https://docs.sysdig.com/en/docs/release-notes/sysdig-on-premises-release-notes/#517-hotfix-release-january-2023)
- [5.1.6 Hotfix Release, January 2023](https://docs.sysdig.com/en/docs/release-notes/sysdig-on-premises-release-notes/#516-hotfix-release-january-2023)
- [5.1.5 Hotfix Release, December 2022](https://docs.sysdig.com/en/docs/release-notes/sysdig-on-premises-release-notes/#515-hotfix-release-december-2022)
- [5.1.4 Hotfix Release, November 2022](https://docs.sysdig.com/en/docs/release-notes/sysdig-on-premises-release-notes/#514-hotfix-release-november-2022)
- [5.1.3 Hotfix Release, September 2022](https://docs.sysdig.com/en/docs/release-notes/sysdig-on-premises-release-notes/#513-hotfix-release-september-2022)
- [5.1.2-2 Hotfix Release, July 2022](https://docs.sysdig.com/en/docs/release-notes/sysdig-on-premises-release-notes/#512-2-hotfix-release-july-2022)
- [5.1.2 Hotfix Release, May 2022](https://docs.sysdig.com/en/docs/release-notes/sysdig-on-premises-release-notes/#512-hotfix-release-may-2022)
- [5.1.1 Hotfix Release, May 2022](https://docs.sysdig.com/en/docs/release-notes/sysdig-on-premises-release-notes/#511-hotfix-release-may-2022)
- [5.1.0 Release, March 2022](https://docs.sysdig.com/en/docs/release-notes/sysdig-on-premises-release-notes/#510-release-march-2022)
- [5.0.5 Hotfix Release for CVE-2022-22965](https://docs.sysdig.com/en/docs/release-notes/sysdig-on-premises-release-notes/#505-hotfix-release-for-cve-2022-22965)

### Version 4.x (5.0.x)

- [4.0.8 Hotfix Release, July 2022](https://docs.sysdig.com/en/docs/release-notes/sysdig-on-premises-release-notes/#408-hotfix-release-july-2022)
- [4.0.7/5.0.4 Hotfix Release for CVE-2021-44228 in Apache’s log4j (3.6.4, 4.0.7, 5.0.4)](https://docs.sysdig.com/en/docs/release-notes/sysdig-on-premises-release-notes/#407504-hotfix-release--for-cve-2021-44228-in-apaches-log4j-364-407-504)
- [4.0.6/5.0.3 Hotfix Release for CVE-2021-44228 in Apache’s log4j (3.6.3, 4.0.6, 5.0.3)](https://docs.sysdig.com/en/docs/release-notes/sysdig-on-premises-release-notes/#406503-hotfix-release--for-cve-2021-44228-in-apaches-log4j-363-406-503)
