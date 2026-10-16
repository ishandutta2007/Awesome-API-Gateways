# Awesome-API-Gateways

## Top API Gateways Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**

*Focused on Traffic Management, API Lifecycle & Cloud-Native Ingress*

**Last updated: October 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **API Gateways**. These tools enable organizations to secure, route, and observe API traffic—from full-lifecycle API management suites to lightweight cloud-native ingress controllers that discover services automatically.



**Examples** include Apigee, Kong Konnect, MuleSoft Anypoint, Tyk, WSO2 API Manager, Postman, Boomi, Software AG webMethods, IBM API Connect, and Axway (the category leaders).



**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, dynamic configuration, and open API management—ideal for platform engineers, API product teams, and developers seeking transparent, vendor-independent gateways.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



| Platform | Parent Company / Company Size (Revenue / Valuation) | Pricing (Starting Tier) | Free Tier Limits / Free Trial | Description |
| :--- | :--- | :--- | :--- | :--- |
| **[Apigee](https://cloud.google.com/apigee)** | Google / Alphabet (~$4.2T Market Cap / ~$350B+ Rev) | Pay-as-you-go starts at ~$365/mo per active Base environment + $20 per 1M standard API calls | 60-day free evaluation tier with up to $300 Google Cloud credits | Google's enterprise full-lifecycle API management platform. API proxies handle security, authorization, analytics, and monitoring; supports Apigee hybrid and gRPC. |
| **[IBM API Connect](https://www.ibm.com/products/api-connect)** | IBM (~$275B Market Cap / ~$62B Rev) | Reserved/Standard SaaS tiers starting at ~$83/mo ($996/yr) for entry volume bundles | 30-day free trial limited to 1 service instance and 100,000 API calls | Enterprise API management platform covering design, security, and analytics with deep IBM Cloud Pak and AWS Marketplace integration. |
| **[MuleSoft Anypoint Platform](https://www.mulesoft.com/platform/anypoint-platform)** | Salesforce (~$250B Market Cap / ~$35B Rev; acquired for $6.5B) | Subscription packages starting at ~$2,000/mo ($24,000/yr) based on Mule Credits / Flow & Message capacity | 30-day free trial providing sandbox access to Anypoint Platform and core design tools | Unified API management and iPaaS integration suite combining API-led connectivity with prebuilt connectors and Anypoint Exchange. |
| **[Software AG webMethods](https://www.softwareag.com/)** | IBM / Silver Lake (~$2.6B Valuation; ~$1B Rev; acquired by IBM) | Standard enterprise integration & API SaaS tiers starting at ~$2,565/mo | Request-based PoC/eval environment (legacy 30-day / 10k transactions free editions discontinued) | Enterprise integration and API management platform with API Gateway, developer portal, and microservices runtime for legacy and cloud systems. |
| **[Postman](https://www.postman.com/)** | Postman ($5.6B Valuation / ~$313M ARR) | Solo plan starting at $9/mo ($108/yr); Team plan at $19/user/mo ($228/user/yr) | Free forever plan for 1 user: unlimited collection runs & mock servers, 1,000 monitoring requests/mo, and 50 Postbot AI credits/mo | Industry-standard API development, mock server, automated testing, and collaborative documentation platform. |
| **[Boomi](https://boomi.com/)** | Francisco Partners & TPG ($4B Valuation / ~$500M ARR) | Pay-As-You-Go starting at $99/mo base + ~$0.05/message; Pro annual contracts from ~$20,000/yr | 30-day free trial with sandbox access to Boomi Enterprise Platform integration and basic API management | Cloud-native iPaaS and API management platform offering no-code interface, prebuilt connectors, and ELT features. |
| **[Kong Konnect](https://konghq.com/products/kong-konnect)** | Kong Inc. ($2.0B Valuation / ~$146M ARR) | Konnect Plus starting at $25/mo per control plane (includes 1M requests/mo; $200 per extra 1M requests) | 30-day free enterprise trial with unrestricted gateway limits; or open-source self-hosted Kong Gateway (free forever, Apache 2.0) | Managed cloud control plane for Kong Gateway deployments across multi-cloud and hybrid environments with 100+ plugins. |
| **[Axway](https://www.axway.com/)** | Axway Software (~$1.3B Valuation [EURONEXT: AXW] / ~$805M Rev) | Tiered pricing based on usage, with entry runtime tiers starting from 1M transactions/mo | Custom demo and sales-arranged PoC environment upon request (no self-service free tier) | Enterprise API management, developer portal, and Amplify hybrid integration platform focused on heavily regulated industries. |
| **[WSO2 API Manager](https://wso2.com/api-manager/)** | EQT Partners ($600M+ Acquisition Valuation / ~$100M ARR) | SaaS tiers starting at ~$85.80/mo (or ~$150/component/mo on Choreo cloud) | 30-day free trial limited to 5 managed APIs, 1M requests/mo, 1 portal, and 1 hybrid gateway | Open-source-origin API management platform supporting REST, GraphQL, WebSocket, streaming APIs, and Kubernetes ingress. |
| **[Tyk API Management](https://tyk.io/)** | Tyk Technologies (~$150M-$250M Valuation / ~$18M ARR) | Tyk Cloud paid subscriptions quote-based starting at ~$600/mo (varies by gateway units & traffic) | 48-hour free trial of Tyk Cloud (no credit card required); or Tyk OSS Gateway (free forever, MPL 2.0 self-hosted) | Full lifecycle API management platform and gateway with REST, GraphQL, and gRPC support with no feature gating across gateways. |



## Open-Source GitHub Projects



- **[Apache APISIX](https://github.com/apache/apisix)**

  **The Cloud-Native API Gateway** (Apache-2.0) . **14,000+ GitHub stars** . **Dynamic, real-time, high-performance API gateway** built on **Nginx and etcd** with **full dynamic routing** . **Rich plugin ecosystem** with multi-protocol support (HTTP, gRPC, WebSocket, MQTT) . **Kubernetes Ingress Controller** available . **Supports canary releases, circuit breaking, and authentication** . **The most feature-complete open-source gateway** for cloud-native environments .



- **[Kong Gateway](https://github.com/Kong/kong)**

  **The most widely adopted open-source API gateway** (Apache-2.0) . **40,000+ GitHub stars** . Built on **NGINX/OpenResty (Lua)** with **PostgreSQL (traditional) or DB-less mode** . **100+ plugins** for authentication, rate limiting, and transformation . **Full Admin API** and **decK declarative GitOps** . **Trade-offs**: PostgreSQL dependency adds operational overhead; advanced plugins (OpenID Connect) are Enterprise-only . **The default open-source choice** for plugin breadth and API management depth .



- **[Traefik](https://github.com/traefik/traefik)**

  **The Cloud Native Application Proxy** (MIT) . **65,000+ GitHub stars** . **Listens to your orchestrator API and instantly generates routes** without manual configuration . **Supports Docker, Swarm, Kubernetes, ECS, Consul, Etcd, Rancher, and more** . **Automatic Let's Encrypt HTTPS**, circuit breakers, retries, WebSocket/HTTP2/gRPC, and **single binary deployment** . **The most popular open-source cloud-native ingress** for Kubernetes and Docker .



- **[Envoy Gateway](https://github.com/envoyproxy/gateway)**

  **The Kubernetes Gateway API implementation powered by Envoy Proxy** (Apache-2.0) . **Extends the Kubernetes Gateway API** with **BackendTrafficPolicy**, **ClientTrafficPolicy**, and **SecurityPolicy** CRDs . **Per-backend circuit breaker counters**—issues with one backend don't affect others . **The most Kubernetes-native approach** to gateway configuration .



- **[Tyk Gateway](https://github.com/TykTechnologies/tyk)**

  **Open-source Enterprise API Gateway** (MPL-2.0) . **No feature lockout**—same gateway used by Tyk for all applications . **No 3rd-party dependencies** aside from Redis . **Supports REST, SOAP, GraphQL, gRPC, and TCP** . **OpenAPI 3.0 as source of truth**, **hitless reloads**, **API versioning**, and **extensible plugins** . **The most "batteries-included" open-source gateway** .



- **[KrakenD](https://github.com/krakend/krakend-ce)**

  **Stateless API gateway focused on API aggregation** (Apache-2.0) . **Single Go binary, no runtime database** . **Native multi-backend response aggregation**—merge, filter, and reshape multiple backends into one response . **40,000–80,000 RPS per instance** with stateless horizontal scaling . **The same runtime as Enterprise** .



- **[WSO2 API Manager (OSS)](https://github.com/wso2/product-apim)**

  **Open-source API management platform** (Apache-2.0) . **API Publisher, Developer Portal, Gateway, and Analytics** . **Supports REST, GraphQL, WebSocket, and streaming APIs** . **Kubernetes deployment option** . **The foundation for WSO2's commercial offering** .



- **[HAProxy](https://github.com/haproxy/haproxy)**

  **The most widely deployed open-source load balancer** (GPL-2.0) . **High-availability, reliable performance** for TCP and HTTP applications . **Supports round-robin, least connections, URL hash, and random algorithms** . **The performance reference** for load balancing .



- **[Emissary-ingress](https://github.com/emissary-ingress/emissary)**

  **CNCF Incubating project**—the open-source core of Ambassador Edge Stack (Apache-2.0) . **Kubernetes-native API gateway built on Envoy** . **Declarative CRD-based configuration** for GitOps workflows .



- **[APISIX Dashboard](https://github.com/apache/apisix-dashboard)**

  **Open-source dashboard for Apache APISIX** (Apache-2.0) . **Visual management for routes, upstreams, plugins, and certificates** .



### Additional Strong Open-Source Options



- **[Kong Ingress Controller](https://github.com/Kong/kubernetes-ingress-controller)** — Kubernetes Ingress Controller powered by Kong Gateway .

- **[Traefik Mesh](https://github.com/traefik/mesh)** — Open-source service mesh built on Traefik Proxy for east-west traffic .

- **[Fabio](https://github.com/fabiolb/fabio)** — Fast, modern, zero-conf load balancing HTTP(S) router for Consul .

- **[Spring Cloud Gateway](https://github.com/spring-cloud/spring-cloud-gateway)** — API gateway built on Spring ecosystem (Apache-2.0) for Java microservices .

- **[Zuul](https://github.com/Netflix/zuul)** — Netflix's L7 application gateway (Apache-2.0) with filter pipelines .

- Community **n8n** workflows for gateway configuration management and traffic alert automation.



**Frameworks for building custom systems**: Combine **Apache APISIX** or **Kong** for plugin-rich API management with **Traefik** for dynamic service discovery, **Envoy Gateway** for Kubernetes-native configuration, **KrakenD** for stateless aggregation, and **HAProxy** for raw performance—creating a fully self-hosted, enterprise-grade API gateway platform.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- API gateways handling production traffic must follow security best practices and comply with data protection regulations.

- **Open-source API gateways are mature and production-ready.** Apache APISIX (14K+ stars) provides full dynamic routing with rich plugins . Kong (40K+ stars) is the most widely adopted open-source gateway . Traefik (65K+ stars) handles automatic service discovery for Kubernetes and Docker . **These are genuine alternatives to commercial platforms.**

- **Architecture choice matters more than feature lists.** Kong is database-backed (or DB-less) and plugin-rich; KrakenD is stateless and aggregation-focused . Traefik discovers services automatically; NGINX requires explicit configuration . **Choose based on your operational model, not benchmark charts.**

- **The hidden cost of self-hosting is engineering time.** A platform team spending one day per week maintaining a Kong cluster represents a significant fraction of a senior engineer's salary—**this cost rarely appears on an invoice but weighs heavily on the budget** . Even "expensive" managed services can be cheaper than dedicated maintenance.

- **Apigee is 69x more expensive than Kong at scale** —but it provides **full API lifecycle management**, **monetization**, and **hybrid deployment** for regulated industries . **The premium buys governance, not just routing.**

- Self-hosted open-source solutions require proper security hardening, certificate management, and ongoing maintenance. **API gateways are critical infrastructure**—plan for high availability, monitoring, and disaster recovery.



---



**Made for platform engineers, API product teams, and developers building transparent gateway solutions.**

Let's make API Gateways more open, data-driven, and cloud-native.
