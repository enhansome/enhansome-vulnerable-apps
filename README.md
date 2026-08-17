# Awesome Vulnerable Applications with stars

> A curated list of various vulnerable by design applications

## Contents

* [Online](#Online)
* [Paid](#Paid)
* [Vulnerable VMs](#Vulnerable-VMs)
* [Cloud Security](#Cloud-Security)
* [SSO - Single Sign On](#SSO-Single-Sign-On)
* [Mobile Security](#Mobile-Security)
* [OWASP Top 10](#OWASP-Top-10)
  * [SQL Injection](#SQL-Injection)
  * [XSS Injection](#XSS-Injection)
  * [Server Side Request Forgery](#Server-Side-Request-Forgery)
  * [CORS Misconfiguration](#CORS-Misconfiguration)
  * [XXE Injection](#XXE-Injection)
  * [Request Smuggling](#Request-Smuggling)
* [Technologies](#Technologies)
  * [WordPress](#WordPress)
  * [.NET](#.NET)
  * [Node.js](#Node.js)
  * [Firmware](#Firmware)
* [Uncategorized](#Uncategorized)

***

## Online

Online vulnerable app and CTFs

* [Hacker101 CTF](https://ctf.hacker101.com/)
* [Web Security Academy](https://portswigger.net/web-security)
* [Hack The Box](https://www.hackthebox.eu/)
* [Try Hack Me](https://tryhackme.com/)
* [CTFtime](https://ctftime.org/)
* [PWNABLE.KR](http://pwnable.kr/)
* [XSS game](https://xss-game.appspot.com)
* [Gin & Juice Shop](https://ginandjuice.shop/)
* [Duck Store](https://duck-store.escape.tech/)
* [Pentest-Ground](https://pentest-ground.com/)
* [DVAIB](https://dvaib.com/) - Damn Vulnerable AI Bank
* [OverTheWire: Wargames](https://overthewire.org/wargames/)

## Paid

Paid tranining courses

* [PentesterLab](https://pentesterlab.com/)

## Vulnerable VMs

* [Vulhub](https://github.com/vulhub/vulhub) ⭐ 21,132 | 🐛 50 | 🌐 Dockerfile | 📅 2026-07-22
* [Metasploitable3](https://github.com/rapid7/metasploitable3) ⭐ 5,667 | 🐛 74 | 🌐 HTML | 📅 2025-02-13 - Metasploitable3 is a VM that is built from the ground up with a large amount of security vulnerabilities.
* [Exploit Exercises](https://exploit-exercises.lains.space/)
* [Hackmyvm.eu](https://hackmyvm.eu/)

## Cloud Security

* [Kubernetes Goat](https://github.com/madhuakula/kubernetes-goat) ⭐ 5,746 | 🐛 28 | 🌐 HTML | 📅 2026-04-16 - Kubernetes Goat is "Vulnerable by Design" Kubernetes Cluster. Designed to be an intentionally vulnerable cluster environment to learn and practice Kubernetes security.
* [CloudGoat](https://github.com/RhinoSecurityLabs/cloudgoat) ⭐ 3,697 | 🐛 23 | 🌐 Python | 📅 2026-04-28 - CloudGoat is Rhino Security Labs' "Vulnerable by Design" AWS deployment tool
* [AWSGoat](https://github.com/ine-labs/AWSGoat) ⭐ 2,041 | 🐛 12 | 🌐 PHP | 📅 2025-05-20 - A Damn Vulnerable AWS Infrastructure
* [TerraGoat - Vulnerable Terraform Infra](https://github.com/bridgecrewio/terragoat) ⭐ 1,305 | 🐛 60 | 🌐 HCL | 📅 2025-07-13 - TerraGoat is Bridgecrew's "Vulnerable by Design" Terraform repository.
* [AzureGoat](https://github.com/ine-labs/AzureGoat) ⭐ 958 | 🐛 6 | 🌐 Python | 📅 2024-10-30 - A Damn Vulnerable Azure Infrastructure
* [Sadcloud](https://github.com/nccgroup/sadcloud) ⭐ 786 | 🐛 9 | 🌐 HCL | 📅 2023-10-14 - A tool for standing up (and tearing down!) purposefully insecure cloud infrastructure
* [IAM Vulnerable](https://github.com/BishopFox/iam-vulnerable) ⭐ 586 | 🐛 0 | 🌐 HCL | 📅 2026-03-12 - Use Terraform to create your own vulnerable by design AWS IAM privilege escalation playground.
* [CNAPPgoat](https://github.com/ermetic-research/cnappgoat) ⭐ 296 | 🐛 4 | 🌐 Go | 📅 2024-09-04 - CNAPPgoat is a multi-cloud, vulnerable-by-design environment deployment tool.
* [caponeme - Capital One Breach](https://github.com/avishayil/caponeme) ⭐ 244 | 🐛 0 | 🌐 Python | 📅 2021-02-08 - Repository demonstrating the Capital One breach on your AWS account
* [Cfngoat - Vulnerable Cloudformation Template](https://github.com/bridgecrewio/cfngoat) ⭐ 100 | 🐛 11 | 📅 2024-08-05 - Cfngoat is Bridgecrew's "Vulnerable by Design" Cloudformation repository.
* [Unguard](https://github.com/dynatrace-oss/unguard) ⭐ 73 | 🐛 18 | 🌐 TypeScript | 📅 2026-05-28 - An insecure cloud-native microservices demo application for Kubernetes
* [CdkGoat - Vulnerable AWS CDK Infra](https://github.com/bridgecrewio/cdkgoat) ⭐ 47 | 🐛 0 | 🌐 Python | 📅 2023-05-09 - CdkGoat is Bridgecrew's "Vulnerable by Design" AWS CDK repository.
* [WrongSecrets](https://github.com/commjoen/wrongsecrets) ⭐ 0 | 🐛 0 | 📅 2026-04-18 - WrongSecrets is "Vulnerable by Design" to show how to not handle secrets in Docker, Kubernetes and in the cloud (AWS/GCP/Azure).
* [Vulnerable Cloud Lab](https://github.com/anpa1200/vulnerable-cloud-lab) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2026-06-18 - Intentionally vulnerable GCP and AWS infrastructure deployed with Terraform for authorized cloud security training.

## SSO - Single Sign On

* [vulnerable-sso](https://github.com/dogangcr/vulnerable-sso) ⭐ 152 | 🐛 2 | 🌐 Java | 📅 2024-08-01 - vulnerable single sign on

## Mobile Security

* [InsecureBankv2](https://github.com/dineshshetty/Android-InsecureBankv2) ⭐ 1,466 | 🐛 17 | 🌐 Java | 📅 2024-04-17 - Vulnerable Android application for developers and security enthusiasts to learn about Android insecurities.
* [DIVA Android](https://github.com/payatu/diva-android) ⭐ 1,136 | 🐛 13 | 🌐 Java | 📅 2023-05-19 - Damn Insecure and vulnerable App for Android.
* [InjuredAndroid](https://github.com/B3nac/InjuredAndroid) ⚠️ Archived - A vulnerable Android application that shows simple examples of vulnerabilities in a ctf style.
* [Damn Vulnerable Bank](https://github.com/rewanthtammana/Damn-Vulnerable-Bank) ⭐ 755 | 🐛 4 | 🌐 Java | 📅 2023-12-13 -  Damn Vulnerable Bank is designed to be an intentionally vulnerable android application.
* [OVAA](https://github.com/oversecured/ovaa) ⭐ 754 | 🐛 1 | 🌐 Java | 📅 2024-07-18 - Oversecured Vulnerable Android App.
* [Allsafe](https://github.com/t0thkr1s/allsafe) ⭐ 412 | 🐛 2 | 🌐 Java | 📅 2025-09-20 - Allsafe is an intentionally vulnerable application that contains various vulnerabilities.
* [AndroGoat](https://github.com/satishpatnayak/AndroGoat) ⭐ 388 | 🐛 2 | 🌐 Kotlin | 📅 2025-11-22 - AndroGoat is purposely developed open source vulnerable/insecure app using Kotlin.
* [InsecureShop](https://github.com/optiv/InsecureShop) ⚠️ Archived - An Intentionally designed Vulnerable Android Application built in Kotlin.
* [Vulnerable Kext](https://github.com/ant4g0nist/Vulnerable-Kext) ⚠️ Archived - A WIP "Vulnerable by Design" kext for iOS/macOS to play & learn \*OS kernel exploitation.
* [Android Security Testing](https://github.com/RavikumarRamesh/hpAndro1337) ⭐ 104 | 🐛 6 | 📅 2023-12-26 - hpAndro1337 Application made in Kotlin with multiple vulnerabilities and a CTF.
* [Vuldroid](https://github.com/jaiswalakshansh/Vuldroid) ⭐ 68 | 🐛 1 | 🌐 Java | 📅 2021-09-18 - Android Application covering various static and dynamic vulnerabilities.
* [VulnLab APK](https://github.com/anpa1200/Vulnerable-APK) ⭐ 1 | 🐛 0 | 🌐 Java | 📅 2026-06-18 - Intentionally vulnerable Android app covering OWASP Mobile Top 10 classes with exploit commands and screenshots.

## OWASP Top 10

* [Owasp Juice shop](https://github.com/juice-shop/juice-shop) ⭐ 13,678 | 🐛 6 | 🌐 TypeScript | 📅 2026-08-10 - OWASP Juice Shop: Probably the most modern and sophisticated insecure web application
* [DVWA](https://github.com/ethicalhack3r/DVWA) ⭐ 13,502 | 🐛 7 | 🌐 PHP | 📅 2026-08-07 - Damn Vulnerable Web Application (DVWA)
* [WebGoat](https://github.com/WebGoat/WebGoat) ⭐ 9,280 | 🐛 35 | 🌐 JavaScript | 📅 2026-08-14 - WebGoat is a deliberately insecure application by OWASP for training purpose
* [Xtreme Vulnerable Web Application](https://github.com/s4n7h0/xvwa) ⚠️ Archived - XVWA is a badly coded web application written in PHP/MySQL that helps security enthusiasts to learn application security.
* [crApi](https://github.com/OWASP/crAPI) ⭐ 1,556 | 🐛 31 | 🌐 Java | 📅 2026-05-14 - completely ridiculous API: crAPI will help you to understand the ten most critical API security risks. crAPI is vulnerable by design, but you'll be able to safely run it to educate/train yourself.
* [OWASP Mutillidae II](https://github.com/webpwnized/mutillidae) ⭐ 1,511 | 🐛 1 | 🌐 PHP | 📅 2026-06-22 - OWASP Mutillidae II is a free, open source, deliberately vulnerable web-application providing a target for web-security enthusiast.
* [VAmPI](https://github.com/erev0s/VAmPI) ⭐ 1,307 | 🐛 4 | 🌐 Python | 📅 2026-04-07 - Vulnerable REST API with OWASP top 10 vulnerabilities for security testing
* [DSVW](https://github.com/stamparm/DSVW) ⭐ 880 | 🐛 1 | 🌐 Python | 📅 2026-08-11 - Damn Small Vulnerable Web
* [VulnLab](https://github.com/Yavuzlar/VulnLab) ⭐ 527 | 🐛 5 | 🌐 CSS | 📅 2025-02-02 - A vulnerable web application lab using Docker
* [Owasp VulnerableApp](https://github.com/SasanLabs/VulnerableApp) ⭐ 455 | 🐛 115 | 🌐 Java | 📅 2026-08-17 - A modular deliberately vulnerable application designed primarily for validating and benchmarking security scanners through reproducible test scenarios, while also supporting learning and experimentation.
* [Pentest\_lab](https://github.com/oliverwiegers/pentest_lab) ⭐ 218 | 🐛 0 | 🌐 Shell | 📅 2025-06-17 - Local penetration testing lab using docker-compose.
* [bWAPP](https://github.com/raesene/bWAPP) ⚠️ Archived - This is just an instance of the OWASP bWAPP project as a docker container.
* [lazyweb](https://github.com/RamadhanAmizudin/lazyweb) ⭐ 128 | 🐛 0 | 🌐 PHP | 📅 2025-02-16 - This web application is a demonstration of common server-side application flaws. Each of the vulnerabilities has its own difficulty rating.
* [OSS – OopsSec Store](https://github.com/kOaDT/oss-oopssec-store) ⭐ 35 | 🐛 12 | 🌐 TypeScript | 📅 2026-08-16 - An intentionally vulnerable e-commerce application built with Next.js and React. A self-hosted CTF platform for web security training covering OWASP Top 10 vulnerabilities.

### SQL Injection

* [Yet Another Vulnerability Database](https://github.com/rtfpessoa/yavdb) ⚠️ Archived - Yet Another Vulnerability Database

### XSS Injection

* [xssed](https://github.com/aj00200/xssed) ⭐ 38 | 🐛 0 | 🌐 PHP | 📅 2013-02-10 - A set of XSS vulnerable PHP scripts for testing
* [xssable](https://github.com/kiwicom/xssable) ⭐ 9 | 🐛 0 | 🌐 HTML | 📅 2023-12-15 - A vulnerable blogging platform used to demonstrate XSS vulnerabilities.
* [XSSworm.dev](https://github.com/vavkamil/XSSworm.dev) ⭐ 6 | 🐛 0 | 🌐 CSS | 📅 2020-12-01 - Self-replication contest
* [clicker-service - simulate XSS](https://gitlab.com/r00k/clicker-service) - Docker container that intakes post and then "clicks" the link. Intentionally vulnerable. To be used with vulnerable by design web apps to realistically simulate XSS and XSRF (CSRF).

### Server Side Request Forgery

* [SSRF\_Vulnerable\_Lab](https://github.com/incredibleindishell/SSRF_Vulnerable_Lab) ⭐ 791 | 🐛 3 | 🌐 PHP | 📅 2023-08-21 - This Lab contain the sample codes which are vulnerable to Server-Side Request Forgery attack

### CORS Misconfiguration

* [CORS-vulnerable-Lab](https://github.com/incredibleindishell/CORS-vulnerable-Lab) ⭐ 189 | 🐛 3 | 🌐 PHP | 📅 2021-03-14 - Sample vulnerable code and its exploit code
* [CORS misconfiguration vulnerable Lab](https://github.com/incredibleindishell/CORS_vulnerable_Lab-Without_Database) ⭐ 66 | 🐛 0 | 🌐 PHP | 📅 2021-08-25 - This Repository contains CORS misconfiguration related vulnerable codes.

### XXE Injection

* [XXE Lab](https://github.com/jbarone/xxelab) ⭐ 229 | 🐛 1 | 🌐 HTML | 📅 2021-11-10 - A simple web app with a XXE vulnerability.
* [docker-java-xxe](https://github.com/pimps/docker-java-xxe) ⭐ 5 | 🐛 0 | 🌐 Smarty | 📅 2018-11-10 - Docker image to test XXE attacks in java with tomcat.

### Request Smuggling

* [Varnish HTTP/2 Request Smuggling](https://github.com/detectify/Varnish-H2-Request-Smuggling) ⭐ 56 | 🐛 0 | 🌐 VCL | 📅 2021-08-26 - This repository a docker-compose file to setup a local environment that is vulnerable to CVE-2021-36740 Varnish HTTP/2 request smuggling.

## Technologies

### WordPress

* [DVWP](https://github.com/vavkamil/dvwp) ⭐ 206 | 🐛 0 | 🌐 PHP | 📅 2023-12-23 - Damn Vulnerable WordPress

### .NET

* [The Most Vulnerable .NET App](https://github.com/AlexGoOn/the-most-vulnerable-dotnet-app) ⭐ 492 | 🐛 0 | 🌐 HTML | 📅 2026-03-06 - Interactive educational project that demonstrates common security vulnerabilities in .NET applications

### Node.js

* [DVNA](https://github.com/appsecco/dvna) ⭐ 778 | 🐛 16 | 🌐 SCSS | 📅 2024-03-27 - Damn Vulnerable NodeJS Application
* [dvws-node](https://github.com/snoopysecurity/dvws-node) ⭐ 515 | 🐛 4 | 🌐 JavaScript | 📅 2026-03-29 - Damn Vulnerable Web Service is a vulnerable web service/API/application that can be used to learn webservices/API vulnerabilities.
* [exploit-workshop](https://github.com/snyk/exploit-workshop) ⭐ 156 | 🐛 2 | 📅 2024-03-17 - A step by step workshop to exploit various vulnerabilities in Node.js and Java applications
* [Extreme Vulnerable Node Application](https://github.com/vegabird/xvna) ⭐ 95 | 🐛 4 | 📅 2018-11-12 - Extreme Vulnerable Node Application

### Firmware

* [OWASP IoT Goat](https://github.com/OWASP/IoTGoat) ⭐ 917 | 🐛 2 | 🌐 C | 📅 2025-10-05 - IoTGoat is a deliberately insecure firmware created to educate software developers and security professionals with testing commonly found vulnerabilities in IoT devices.
* [DVRF](https://github.com/praetorian-code/DVRF) ⚠️ Archived - The Damn Vulnerable Router Firmware Project
* [DVID](https://github.com/Vulcainreo/DVID) ⭐ 225 | 🐛 3 | 🌐 C | 📅 2024-02-12 -  Damn Vulnerable IoT Device

## Uncategorized

* [Vulhub](https://github.com/vulhub/vulhub) ⭐ 21,132 | 🐛 50 | 🌐 Dockerfile | 📅 2026-07-22 - Vulhub is an open-source collection of pre-built vulnerable docker environments.
* [CI/CD Goat](https://github.com/cider-security-research/cicd-goat) ⭐ 2,286 | 🐛 0 | 🌐 Python | 📅 2024-07-14 - Deliberately vulnerable CI/CD environment. Hack CI/CD pipelines, catch the flags.
* [Damn-Vulnerable-GraphQL-Application](https://github.com/dolevf/Damn-Vulnerable-GraphQL-Application) ⭐ 1,703 | 🐛 3 | 🌐 JavaScript | 📅 2025-05-24 - Damn Vulnerable GraphQL Application is an intentionally vulnerable implementation of Facebook's GraphQL technology, to learn and practice GraphQL Security.
* [Vulnserver](https://github.com/stephenbradshaw/vulnserver) ⭐ 1,131 | 🐛 1 | 🌐 C | 📅 2020-10-09 - Vulnerable server used for learning software exploitation
* [Damn Vulnerable RESTaurant](https://github.com/theowni/Damn-Vulnerable-RESTaurant-API-Game) ⭐ 932 | 🐛 0 | 🌐 Python | 📅 2026-07-09 - Intentionally vulnerable Web API game for learning and training purposes dedicated to developers, ethical hackers and security engineers.
* [OWASP-VWAD](https://github.com/OWASP/OWASP-VWAD) ⭐ 886 | 🐛 0 | 📅 2026-07-20 - The OWASP Vulnerable Web Applications Directory project (VWAD) is a comprehensive and well maintained registry of all known vulnerable web applications currently available.
* [GitHub Actions Goat](https://github.com/step-security/github-actions-goat) ⭐ 515 | 🐛 21 | 🌐 JavaScript | 📅 2025-06-27 - Deliberately Vulnerable GitHub Actions CI/CD Environment
* [OWASP SKF labs](https://github.com/blabla1337/skf-labs) ⭐ 465 | 🐛 31 | 🌐 Python | 📅 2024-08-02 - Repo for all the OWASP-SKF Docker lab examples
* [dvws - Damn Vulnerable Web Services](https://github.com/snoopysecurity/dvws) ⚠️ Archived - Damn Vulnerable Web Services is an insecure web application with multiple vulnerable web service components that can be used to learn real world web service vulnerabilities.
* [leaky-repo](https://github.com/Plazmaz/leaky-repo) ⭐ 249 | 🐛 1 | 🌐 Python | 📅 2024-08-18 - Benchmarking repo for secrets scanning
* [Vulnerable-nginx](https://github.com/detectify/vulnerable-nginx) ⭐ 245 | 🐛 1 | 🌐 Dockerfile | 📅 2020-11-10 - An intentionally vulnerable NGINX setup
* [wavsep](https://github.com/sectooladdict/wavsep) ⭐ 238 | 🐛 8 | 🌐 Java | 📅 2022-10-05 - The Web Application Vulnerability Scanner Evaluation Project
* [Fuzzgoat](https://github.com/fuzzstati0n/fuzzgoat) ⭐ 207 | 🐛 3 | 🌐 C | 📅 2022-11-10 - A vulnerable C program for testing fuzzers.
* [Damn Vulnerable Thick Client](https://github.com/srini0x00/dvta) ⭐ 182 | 🐛 1 | 🌐 C# | 📅 2023-08-17 - Damn Vulnerable Thick Client App developed in C# .NET
* [Raspwn OS](https://github.com/alphacharlie/raspwn/) ⭐ 69 | 🐛 3 | 🌐 Shell | 📅 2017-04-28 - The intentionally vulnerable image for the Raspberry Pi.
* [VulnerableLightApp](https://github.com/Aif4thah/VulnerableLightApp) ⭐ 61 | 🐛 0 | 🌐 C# | 📅 2026-02-25 - .NET vulnerable REST API
* [python\_security](https://github.com/gbleaney/python_security) ⭐ 36 | 🐛 0 | 🌐 Python | 📅 2021-05-09 - This repository collects lists of security-relavent Python APIs, along with examples of exploits using those APIs
* [LogSnare](https://github.com/sea-erkin/log-snare) ⭐ 34 | 🐛 1 | 🌐 CSS | 📅 2024-03-04 - A playground for testing, preventing, and logging IDOR vulnerabilities.
* [OSTE-Vulnerable-Web-Application](https://github.com/OSTEsayed/OSTE-Vulnerable-Web-Application) ⭐ 19 | 🐛 0 | 🌐 PHP | 📅 2023-12-15 - Vulnerable Web application made with PHP/SQL designed to help new web testers gain some experience and test DAST tools for identifying web vulnerabilities.
* [Vulnerable AI Lab](https://github.com/anpa1200/AI-PT-Lab) ⭐ 10 | 🐛 1 | 🌐 Python | 📅 2026-06-18 - Intentionally vulnerable AI agent lab for practicing RAG injection, tool misuse, memory poisoning, supply-chain compromise, and data exfiltration.
* [VulnDoge](https://github.com/burpOverflow/VulnDoge) - Web app for hunters

## Contribute

Contributions welcome! Read the [contribution guidelines](contributing.md) first.

## License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0)

To the extent possible under law, vavkamil has waived all copyright and
related or neighboring rights to this work.

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-17._
