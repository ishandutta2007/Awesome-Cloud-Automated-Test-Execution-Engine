# Awesome-Cloud-Automated-Test-Execution-Engine

## Top Cloud Automated Test Execution Engine Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Distributed Test Orchestration, Parallel Execution & Cloud Browser/Device Infrastructure*  
**Last updated: March 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Cloud Automated Test Execution Engines**. These tools provide the runtime layer for automated testing—orchestrating parallel test sessions across cloud browsers, real devices, and containerized environments, with built-in reporting, retry logic, and CI/CD integration.

**Examples** include BrowserStack Automate, Sauce Labs Test Runner, LambdaTest HyperExecute, Aerokube Moon, Cypress Cloud Runner, Playwright Test Runner, AWS Device Farm Runner, CircleCI Test Runner, GitHub Actions Runner, and Testim Execution Engine (the category leaders).

**Open-source emphasis**: This section highlights every major active project for self-hosted test execution engines, open-source test runners, and Kubernetes-native browser orchestration—ideal for QA engineers, platform teams, and developers building transparent, vendor-neutral test infrastructure without per-parallel-session cloud billing surprises.

Contributions welcome! Open an PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

| Product | Description | Pricing (Starting) | Free Tier / Trial Limits |
|---------|-------------|-------------------|--------------------------|
| **[BrowserStack Automate](https://www.browserstack.com/)** | Cloud test execution engine supporting Selenium, Cypress, Playwright, and Appium across 3,000+ real browsers and 30,000+ real mobile devices. Parallel test billing with unlimited test minutes on annual plans. Real-device mobile testing available as add-on [citation:1][citation:19]. | Automate Desktop: from $99/month per parallel test (billed annually); Desktop & Mobile: $175/month per parallel [citation:24] | No free tier; free trial available on signup; open-source projects eligible for lifetime free access |
| **[Sauce Labs Test Runner](https://saucelabs.com/)** | Enterprise test execution platform supporting Selenium, Playwright (via CDP), Cypress, and mobile testing. Virtual Device Cloud for emulators/simulators and Real Device Cloud for physical iOS/Android devices. AI Test Authoring and Insights Agents available on Enterprise tier [citation:2]. | Virtual Device Cloud: $149/month (billed annually) for automated + manual testing on emulators/simulators; Real Device Cloud: $199/month [citation:2] | No permanent free tier; free trial available via sales |
| **[LambdaTest HyperExecute](https://www.lambdatest.com/)** | Test orchestration engine with virtually unlimited parallel nodes across multiple clouds. Each parallel test execution consumes a single HyperExecute license; no capping on simultaneous tests. Supports Selenium, Cypress, Playwright, and Puppeteer [citation:3]. | HyperExecute: $103/month per parallel session (Linux, annual); $159/month (Windows/macOS) [citation:25] | Free plan: 300 HyperExecute minutes + 2 concurrent sessions; 100 lifetime automation minutes on 2 parallel sessions [citation:25]; open-source projects get 10 HyperExecute parallel sessions free [citation:13] |
| **[Aerokube Moon (Cloud)](https://aerokube.com/moon/)** | Kubernetes-native browser automation platform supporting Selenium, Playwright, Puppeteer, and Cypress in a single cluster. Deploys via Helm with official Chrome, Firefox, and Edge images. Benchmarks show ~3s startup per session (K8s pod scheduling) [citation:4]. | $5 per parallel session per month (contact sales for license key) [citation:4] | Free evaluation license keys of any size until production (Moon Assistance Program for migration support) [citation:4] |
| **[Cypress Cloud Runner](https://www.cypress.io/)** | Hosted orchestration layer for Cypress test runs with parallelization, load balancing, flake detection, and analytics. Pairs with the open-source Cypress App (MIT licensed). Free for non-commercial open-source public projects [citation:5]. | Team/Business plans: contact sales for quote (usage-based on test results) | Free plan for any organization with limited test results; OSS plan: 100k test results/month, parallelization with load balancing, free for qualifying open-source projects [citation:5] |
| **[Playwright Test Runner (Microsoft)](https://playwright.dev/)** | Open-source test runner from Microsoft with built-in parallelism, sharding, retries, and trace viewer. The runner itself is Apache-2.0 licensed and free; Microsoft Playwright Testing is an optional cloud execution service billed per test minute [citation:6][citation:27]. | Core runner: free (Apache-2.0); Microsoft Playwright Testing cloud: pay-per-test-minute (contact Azure for rates) | Core runner: always free, unlimited; Microsoft Playwright Testing: 30-day trial with first 100 test minutes and 1,000 test results free [citation:16][citation:27] |
| **[AWS Device Farm Runner](https://aws.amazon.com/device-farm/)** | Managed mobile app testing service on real iOS and Android devices. Automated test runs with Appium, Espresso, XCTest, and Calabash. Pay-per-device-minute or unlimited monthly device slots [citation:7]. | $0.17 per device minute (pay-as-you-go); Unlimited plan from $250/month per device slot (automated testing, Android or iOS) [citation:7] | 1,000 free device minutes one-time trial (limited time; standard is 250 minutes) [citation:7] |
| **[CircleCI Test Runner](https://circleci.com/)** | Cloud CI/CD platform with native test execution, dynamic parallelism, test splitting, and auto-rerun of failed tests. Docker, Linux VM, Windows, macOS, and GPU executors available. Test atoms for intelligent test selection [citation:8]. | Performance: $15/month base + credits; Free tier includes 30,000 credits/month [citation:8] | Free plan: 30,000 credits/month (~3,000 Linux medium minutes), 5 active users, 5 self-hosted runners, 1 macOS concurrency; credits expire monthly [citation:8] |
| **[GitHub Actions Runner](https://github.com/features/actions)** | Native CI/CD runner within GitHub with matrix builds, reusable workflows, and self-hosted runner support. Public repositories get unlimited free minutes on standard runners. Hosted runner prices reduced up to 39% in January 2026 [citation:9][citation:23]. | Linux 2-core: $0.006/minute (reduced from $0.008); Windows 2-core: $0.010/minute; macOS 3/4-core: $0.062/minute [citation:23] | Free plan: 2,000 minutes/month for private repos (Linux 1x multiplier); public repos unlimited and free; self-hosted runner usage included in free quota from March 2026 [citation:9] |
| **[Testim Execution Engine](https://www.testim.io/)** | AI-powered test execution platform (Tricentis) with smart locators, parallel execution, and cloud/on-prem execution options. Low-code recorder-based authoring with JavaScript/Apex script support. Community plan available [citation:10]. | Contact sales for quote (custom pricing based on test runs and parallel sessions) | Community Free Plan: 1,000 test runs/month, limited to one user account; 7-day free trial available on request [citation:21][citation:26] |

## Open-Source GitHub Projects

| Project | Star Badge | Description |
|---------|------------|-------------|
| **[Playwright](https://github.com/microsoft/playwright)** | [![Stars](https://img.shields.io/github/stars/microsoft/playwright?style=social&color=white)](https://github.com/microsoft/playwright/stargazers) | Microsoft's cross-browser automation framework (Apache-2.0) with a built-in test runner supporting parallelism, sharding, retries, and trace viewer. Runs Chromium, Firefox, and WebKit from a single API [citation:6]. |
| **[Cypress](https://github.com/cypress-io/cypress)** | [![Stars](https://img.shields.io/github/stars/cypress-io/cypress?style=social&color=white)](https://github.com/cypress-io/cypress/stargazers) | Open-source (MIT) E2E testing framework with time-travel debugging, automatic waiting, and network stubbing. The Cypress Cloud runner adds parallelization and flake detection as a paid service [citation:5]. |
| **[Kubernetes](https://github.com/kubernetes/kubernetes)** | [![Stars](https://img.shields.io/github/stars/kubernetes/kubernetes?style=social&color=white)](https://github.com/kubernetes/kubernetes/stargazers) | Container orchestration platform that serves as the foundation for self-hosted test execution engines (Moon, Selenoid/WebSummoner, KubeGrid). Enables dynamic scaling of browser containers per test session. |
| **[Moon by Aerokube (Self-Hosted)](https://github.com/aerokube/moon)** | [![Stars](https://img.shields.io/github/stars/aerokube/moon?style=social&color=white)](https://github.com/aerokube/moon/stargazers) | Kubernetes-native browser automation platform supporting Selenium, Playwright, Puppeteer, and Cypress. Deploys via Helm with official browser images. Free evaluation keys available; paid license required for production [citation:4]. |
| **[WebSummoner](https://github.com/WebSummoner/websummoner)** | [![Stars](https://img.shields.io/github/stars/WebSummoner/websummoner?style=social&color=white)](https://github.com/WebSummoner/websummoner/stargazers) | Maintained successor to Selenoid (archived Dec 2024). Go-based Selenium hub launching browsers in ephemeral Docker containers per session. Apache-2.0 licensed, ~10MB binary, no Java dependency. Selenoid API compatible. |

### Additional Strong Open-Source Options

| Project | Star Badge | Description |
|---------|------------|-------------|
| **[Selenoid (Archived)](https://github.com/aerokube/selenoid)** | [![Stars](https://img.shields.io/github/stars/aerokube/selenoid?style=social&color=white)](https://github.com/aerokube/selenoid/stargazers) | The original Go-based Docker-container-per-session Selenium hub. Archived December 2024; existing deployments should evaluate WebSummoner or Moon as migration targets. |
| **[Selenium Grid 4](https://github.com/SeleniumHQ/selenium)** | [![Stars](https://img.shields.io/github/stars/SeleniumHQ/selenium?style=social&color=white)](https://github.com/SeleniumHQ/selenium/stargazers) | Reference hub-and-node architecture for distributed WebDriver execution. Grid 4 supports relay for Appium, distributed tracing, and GraphQL-based status queries. |
| **[docker-selenium](https://github.com/SeleniumHQ/docker-selenium)** | [![Stars](https://img.shields.io/github/stars/SeleniumHQ/docker-selenium?style=social&color=white)](https://github.com/SeleniumHQ/docker-selenium/stargazers) | Official Docker images for Grid 4 with Chrome, Firefox, and Edge nodes. Provides ready-to-run hub and node containers for self-hosted test execution. |

**Frameworks for building custom systems**: Combine **Playwright** or **Cypress** for test authoring, **Moon** or **WebSummoner** for Kubernetes/Docker-native browser orchestration, and **Selenium Grid 4** for standards-compliant WebDriver routing—orchestrated via **GitHub Actions** or **CircleCI** with dynamic parallelism.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Cloud test execution engines execute arbitrary browser automation code; enforce proper authentication, network isolation, and session cleanup to prevent resource exhaustion or unauthorized use.
- Self-hosted execution engines require capacity planning, browser image updates, and monitoring; pricing for cloud engines varies significantly by parallel session count and test volume—model total cost before committing.

---

**Made for QA engineers, test automation architects, platform teams, and developers building scalable test execution infrastructure.**  
Let's make cloud test execution more open, parallel, and cost-transparent.
