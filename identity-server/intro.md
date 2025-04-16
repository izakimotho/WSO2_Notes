# WSO2_Notes

# WSO2 Identity Server Apps

End-user apps in WSO2 Identity Server

[![Stackoverflow](https://img.shields.io/badge/Ask%20for%20help%20on-Stackoverflow-orange)](https://stackoverflow.com/questions/tagged/wso2is)
[![Discord](https://img.shields.io/badge/Join%20us%20on-Discord-%23e01563.svg)](https://discord.gg/wso2)
[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://github.com/wso2/product-is/blob/master/LICENSE)
[![Twitter](https://img.shields.io/twitter/follow/wso2.svg?style=social&label=Follow)](https://twitter.com/intent/follow?screen_name=wso2)

---

## Table of Content

<!-- Execute: `node scripts/generate-markdown-toc.js README.md` -->
<!-- TOC:START - Do not remove or modify this section -->

- [Prerequisite](#prerequisite)
  * [Setup Development Environment](#setup-development-environment)
  * [Download WSO2 Identity Server](#download-wso2-identity-server)
  * [Setup WSO2 Identity Server](#setup-wso2-identity-server)
    + [Allow CORS Origins](#allow-cors-origins)
    + [Configure FIDO2 origins](#configure-fido2-origins)
    + [Make Applications Editable](#make-applications-editable)
    + [Configure Callback URLs for System Applications (for WSO2 IS v7.0 and above)](#configure-callback-urls-for-system-applications-for-wso2-is-v70-and-above)
    + [Start the Identity Server](#start-the-identity-server)
    + [Configure Callback URLs for System Applications (for WSO2 IS below v7.0)](#configure-callback-urls-for-system-applications-for-wso2-is-below-v70)
- [Build & Run](#build--run)
  * [Build](#build)
    + [For Console & My Account](#for-console--my-account)
    + [For JSP apps (authentication portal, recovery portal, etc)](#for-jsp-apps-authentication-portal-recovery-portal-etc)
  * [Run](#run)
    + [Console](#console)
    + [My Account](#my-account)
- [Releases](#releases)
- [Configuration](#configuration)
- [Deployment](#deployment)
- [Connectors](#connectors)
- [Troubleshoot](#troubleshoot)
- [Contributing](#contributing)
- [Reporting Issues](#reporting-issues)
- [License](#license)

<!-- TOC:END -->