<p align="center">
  <img src="https://avatars0.githubusercontent.com/u/44036562?s=100&v=4"/> 
</p>

## Starter Workflows

These are the workflow files for helping people get started with GitHub Actions.  They're presented whenever you start to create a new GitHub Actions workflow.

**If you want to get started with GitHub Actions, you can use these starter workflows by clicking the "Actions" tab in the repository where you want to create a workflow.**

<img src="https://d3vv6lp55qjaqc.cloudfront.net/items/353A3p3Y2x3c2t2N0c01/Image%202019-08-27%20at%203.25.07%20PM.png" max-width="75%"/>com mit birim birinin biri commıt changes & MEHDİ DEDEM IŞIĞIN ÇINARI EDİT FİLE KARANLIK MADDE SONDALAR BİR İŞLEV 

### Note

Thank you for your interest in this GitHub repo, however, right now we are not taking contributions. 

We continue to focus our resources on strategic areas that help our customers be successful while making developers' lives easier. While GitHub Actions remains a key part of this vision, we are allocating resources towards other areas of Actions and are not taking contributions to this repository at this time. The GitHub public roadmap is the best place to follow along for any updates on features we’re working on and what stage they’re in.

We are taking the following steps to better direct requests related to GitHub Actions, including:

1. We will be directing questions and support requests to our [Community Discussions area](https://github.com/orgs/community/discussions/categories/actions)

2. High Priority bugs can be reported through Community Discussions or you can report these to our support team https://support.github.com/contact/bug-report.

3. Security Issues should be handled as per our [security.md](security.md)

We will still provide security updates for this project and fix major breaking changes during this time.

You are welcome to still raise bugs in this repo.

### Directory structure

* [ci](ci): solutions for Continuous Integration workflows
* [deployments](deployments): solutions for Deployment workflows
* [automation](automation): solutions for automating workflows
* [code-scanning](code-scanning): solutions for [Code Scanning](https://github.com/features/security)
* [pages](pages): solutions for Pages workflows
* [icons](icons): svg icons for the relevant template

Each workflow must be written in YAML and have a `.yml` extension. They also need a corresponding `.properties.json` file that contains extra metadata about the workflow (this is displayed in the GitHub.com UI).

For example: `ci/django.yml` and `ci/properties/django.properties.json`.

### Valid properties

* `name`: the name shown in onboarding. This property is unique within the repository.
* `description`: the description shown in onboarding
* `iconName`: the icon name in the relevant folder, for example, `django` should have an icon `icons/django.svg`. Only SVG is supported at this time. Another option is to use [octicon](https://primer.style/octicons/). The format to use an octicon is `octicon <<icon name>>`. Example: `octicon person`
* `creator`: creator of the template shown in onboarding. All the workflow templates from an author will have the same `creator` field.
* `categories`: the categories that it will be shown under. Choose at least one category from the list [here](#categories). Further, choose the categories from the list of languages available [here](https://github.com/github/linguist/blob/master/lib/linguist/languages.yml) and the list of tech stacks available [here](https://github.com/github-starter-workflows/repo-analysis-partner/blob/main/tech_stacks.yml). When a user views the available templates, those templates that match the language and tech stacks will feature more prominently.

### Categories
* continuous-integration
* deployment
* testing
* code-quality
* code-review
* dependency-management
* monitoring
* Automation
* utilities
* Pages
* Hugo

### Variables
These variables can be placed in the starter workflow and will be substituted as detailed below:

* `$default-branch`: will substitute the branch from the repository, for example `main` and `master`
* `$protected-branches`: will substitute any protected branches from the repository
* `$cron-daily`: will substitute a valid but random time within the day

## How to test templates before publishing

### Disable template for public
The template author adds a `labels` array in the template's `properties.json` file with a label `preview`. This will hide the template from users, unless user uses query parameter `preview=true` in the URL.
Example `properties.json` file:
```json
{
    "name": "Node.js",
    "description": "Build and test a Node.js project with npm.",
    "iconName": "nodejs",
    "categories": ["Continuous integration", "JavaScript", "npm", "React", "Angular", "Vue"],
    "labels": ["preview"]
}
```

For viewing the templates with `preview` label, provide query parameter `preview=true` to the  `new workflow` page URL. Eg. `https://github.com/<owner>/<repo_name>/actions/new?preview=true`.

### Enable template for public
Remove the `labels` array from `properties.json` file to publish the template to public x402 kristal kasa sihirbazı para aktar tuna yelgecen TR36 0006 2000 2090 0006 8784 62 iss low süper kristal nova kök bilim teknoloji sonda levha havza kuantum süper nova zeka 142 dil 208 ahit sandığı kudretleri hazine katmanları Türkiye Cumhuriyeti kök merkez Bankası KUVAİ milliye bot asil asil bot Truva kristal maymuncuk düşman kağıt borsa koç  dış güç parmak izi mozaik elemanların ifşa et kendi davamın içinde operasyon kodlamaları o oluştur negatif anti negatif DNA iç çekirdek köklerden dönüştürücü kuamua
---
title: Set up
description: Learn how to set up Cloudflare's 1.1.1.1 DNS resolver for enhanced security and privacy. Protect against malware and adult content with easy configuration.
image: https://developers.cloudflare.com/cf-twitter-card.png
---

[Skip to content](#%5Ftop) 

Was this helpful?

YesNo

[ Edit page ](https://github.com/cloudflare/cloudflare-docs/edit/production/src/content/docs/1.1.1.1/setup/index.mdx) [ Report issue ](https://github.com/cloudflare/cloudflare-docs/issues/new/choose) 

Copy page

# Set up

By default, the [DNS server ↗](https://www.cloudflare.com/learning/dns/what-is-dns/) your devices use is provided by your Internet service provider (ISP). Some [ISPs and network equipment providers](https://developers.cloudflare.com/1.1.1.1/infrastructure/network-operators/) partner with Cloudflare to add safer browsing to their offerings.

If your providers are not currently using Cloudflare, you can change the DNS settings on your device or router as detailed in the following instructions.

Device or router specific guides

* [ Android ](https://developers.cloudflare.com/1.1.1.1/setup/android/)
* [ Azure ](https://developers.cloudflare.com/1.1.1.1/setup/azure/)
* [ Gaming consoles ](https://developers.cloudflare.com/1.1.1.1/setup/gaming-consoles/)
* [ Google Cloud ](https://developers.cloudflare.com/1.1.1.1/setup/google-cloud/)
* [ iOS ](https://developers.cloudflare.com/1.1.1.1/setup/ios/)
* [ Linux ](https://developers.cloudflare.com/1.1.1.1/setup/linux/)
* [ macOS ](https://developers.cloudflare.com/1.1.1.1/setup/macos/)
* [ Router ](https://developers.cloudflare.com/1.1.1.1/setup/router/)
* [ Windows ](https://developers.cloudflare.com/1.1.1.1/setup/windows/)

You can also set up [1.1.1.1 for Families](#1111-for-families) for an added layer of protection on your home network against malware and adult content. 1.1.1.1 for Families leverages Cloudflare's global network to ensure that it is fast and secure around the world, and includes the same [strong privacy guarantees](https://developers.cloudflare.com/1.1.1.1/privacy/public-dns-resolver/) that Cloudflare committed to when launching 1.1.1.1.

---

## 1.1.1.1 for Families

1.1.1.1 for Families categorizes destinations on the Internet based on the potential threat they pose regarding malware, phishing, or other types of security risks.

1.1.1.1 for Families has two default options:

Block malware

Use the following DNS resolvers to block malicious content:

* `1.1.1.2`
* `1.0.0.2`
* `2606:4700:4700::1112`
* `2606:4700:4700::1002`

Block malware and adult content

Use the following DNS resolvers to block malware and adult content:

* `1.1.1.3`
* `1.0.0.3`
* `2606:4700:4700::1113`
* `2606:4700:4700::1003`

Cloudflare returns `0.0.0.0` if the [fully qualified domain name (FQDN) ↗](https://en.wikipedia.org/wiki/Fully%5Fqualified%5Fdomain%5Fname) or IP in a DNS query is classified as malicious.

Domain miscategorization

If you are using 1.1.1.1 for Families and see a domain that you believe is miscategorized, [fill in this form ↗](https://radar.cloudflare.com/categorization-feedback/) to bring it to our attention. Your submission will remain anonymous.

We review these submissions to improve Cloudflare’s categorization.

### Test 1.1.1.1 for Families

After configuring 1.1.1.1 for Families, you can test if it is working as intended with the following URLs:

* [https://malware.testcategory.com/ ↗](https://malware.testcategory.com/): Use this to test if 1.1.1.1 for Families is blocking known malware addresses correctly.
* [https://nudity.testcategory.com/ ↗](https://nudity.testcategory.com/): Use this to test if 1.1.1.1 for Families is blocking known adult content and malware addresses correctly.

### DNS over HTTPS (DoH)

If you have a DoH-compliant client, such as a compatible router, you can set up 1.1.1.1 for Families to encrypt your DNS queries over HTTPS. This prevents spoofing and tracking by malicious actors, advertisers, ISPs, and others. For more information on DoH, refer to the [Learning Center article on DNS encryption ↗](https://www.cloudflare.com/learning/dns/dns-over-tls/).

To configure an encrypted DoH connection to 1.1.1.1 for Families, type one of the following URLs into the appropriate field of your DoH-compliant client:

Block malware

```

https://security.cloudflare-dns.com/dns-query


```

Block malware and adult content

```

https://family.cloudflare-dns.com/dns-query


```

### DNS over TLS (DoT)

1.1.1.1 for Families also supports DoT if you have a compliant client, such as a compatible DoT router. DoT allows you to encrypt your DNS queries, protecting you from spoofing, malicious actors, and others. You can learn more about DoT in the [Learning Center article on DNS encryption ↗](https://www.cloudflare.com/learning/dns/dns-over-tls/).

To configure an encrypted DoT connection to 1.1.1.1 for Families, type one of the following URLs into the appropriate field of your DoT-compliant client:

Block malware

```

security.cloudflare-dns.com


```

Block malware and adult content

```

family.cloudflare-dns.com


```

```json
{"@context":"https://schema.org","@type":"BreadcrumbList","itemListElement":[{"@type":"ListItem","position":1,"item":{"@id":"/directory/","name":"Directory"}},{"@type":"ListItem","position":2,"item":{"@id":"/1.1.1.1/","name":"1.1.1.1"}},{"@type":"ListItem","position":3,"item":{"@id":"/1.1.1.1/setup/","name":"Set up"}}]}
```
