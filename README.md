# 🌐 Awesome API Gateways & Ingress Controllers

<div align="center">

<img src="./assets/banner.svg" alt="Awesome API Gateways Banner" width="100%" />

<p align="center">
  <strong>Curated Directory of Enterprise SaaS Solutions & High-Performance Open-Source API Gateways</strong><br>
  <em>Traffic Management • Cloud-Native Ingress • Microservices Routing • API Security & Lifecycle Governance</em>
</p>

<p align="center">
  <a href="https://github.com/ishandutta2007/Awesome-Awesome-Awesome"><img src="https://img.shields.io/badge/Awesome-%E2%9C%94-blueviolet?style=flat-square&logo=github" alt="Awesome"/></a><a href="https://discord.gg/jc4xtF58Ve"><img src="https://img.shields.io/badge/Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white" alt="Discord" /></a>
  <a href="https://github.com/ishandutta2007/Awesome-API-Gateways/stargazers"><img src="https://img.shields.io/github/stars/ishandutta2007/Awesome-API-Gateways?style=flat-square&color=blue" alt="Stars" /></a>
  <a href="https://github.com/ishandutta2007/Awesome-API-Gateways/network/members"><img src="https://img.shields.io/github/forks/ishandutta2007/Awesome-API-Gateways?style=flat-square&color=blue" alt="Forks" /></a>
  <a href="https://github.com/ishandutta2007/Awesome-API-Gateways/issues"><img src="https://img.shields.io/github/issues/ishandutta2007/Awesome-API-Gateways?style=flat-square&color=green" alt="Issues" /></a>
  <a href="https://github.com/ishandutta2007/Awesome-API-Gateways/blob/main/LICENSE"><img src="https://img.shields.io/github/license/ishandutta2007/Awesome-API-Gateways?style=flat-square&color=orange" alt="License" /></a>
  <a href="https://github.com/ishandutta2007"><img alt="GitHub followers" src="https://img.shields.io/github/followers/ishandutta2007?label=Follow" /></a>
</p>

</div>

---

> 🚀 **Explore the definitive awesome list of API Gateways, Ingress Controllers, and Reverse Proxies.** Whether building Kubernetes microservices, orchestrating hybrid cloud integrations, or managing enterprise API lifecycles, this collection covers battle-tested SaaS vendors and top-tier open-source projects.

---

## 📑 Table of Contents

- [📊 Sector Overview & Market Dynamics](#-sector-overview--market-dynamics)
- [☁️ SaaS & Hosted API Management Platforms](#️-saas--hosted-api-management-platforms)
- [🔓 Open-Source GitHub Projects](#-open-source-github-projects)
- [🛠️ Frameworks & Architecture Recommendations](#️-frameworks--architecture-recommendations)
- [🤝 How to Contribute](#-how-to-contribute)
- [💖 Support & Sponsorship](#-support--sponsorship)
- [📈 Star History](#-star-history)
- [⚖️ Disclaimer](#️-disclaimer)

---

## 📊 Sector Overview & Market Dynamics

The global **API Management and Gateway market** is valued at approximately **$7.5B to $10B** in the mid-2020s and is projected to surge past **$35B+ by 2033** at a double-digit CAGR exceeding **20%**, propelled by microservices adoption, Kubernetes ingress proliferation, and AI-driven API consumption. 

Rather than being a winner-take-all monopoly, the sector exhibits **moderate fragmentation**: massive cloud hyperscalers (Google Cloud Apigee, AWS, Microsoft) and integration giants (IBM, MuleSoft/Salesforce) dominate heavy enterprise compliance and legacy transformation, while agile SaaS innovators and hyper-popular open-source gateways (Kong, Traefik, Apache APISIX, Envoy Gateway) capture platform engineering teams, cloud-native deployments, and edge routing.

---

## ☁️ SaaS & Hosted API Management Platforms

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

---

## 🔓 Open-Source GitHub Projects

Curated open-source API gateways and cloud-native proxies, sorted by GitHub_Stars_Count (descending):

1. **[Caddy](https://github.com/caddyserver/caddy)** [![GitHub_Stars](https://img.shields.io/github/stars/caddyserver/caddy?style=social&color=white)](https://github.com/caddyserver/caddy/stargazers)  
   **Fast, multi-platform, extensible HTTP/1-2-3 web server & reverse proxy with automatic HTTPS** (Apache-2.0). Written in Go with zero runtime dependencies. Dynamically configurable via JSON REST API or Caddyfile. Ideal as an ultra-fast modern reverse proxy, ingress point, and TLS terminating gateway.

2. **[Traefik](https://github.com/traefik/traefik)** [![GitHub_Stars](https://img.shields.io/github/stars/traefik/traefik?style=social&color=white)](https://github.com/traefik/traefik/stargazers)  
   **The Cloud Native Application Proxy** (MIT). Listens to orchestrator APIs (Docker, Swarm, Kubernetes, ECS, Consul, Etcd) and auto-discovers routes dynamically without restarts. Features automatic Let's Encrypt HTTPS, circuit breakers, retries, and native gRPC/WebSocket routing.

3. **[Kong Gateway](https://github.com/Kong/kong)** [![GitHub_Stars](https://img.shields.io/github/stars/Kong/kong?style=social&color=white)](https://github.com/Kong/kong/stargazers)  
   **The most widely adopted open-source cloud-native API gateway** (Apache-2.0). Built on NGINX/OpenResty (Lua) supporting both PostgreSQL-backed and lightweight DB-less / declarative GitOps (decK) configurations. Offers 100+ community and enterprise plugins for authentication, rate limiting, logging, and transformations.

4. **[Envoy Proxy](https://github.com/envoyproxy/envoy)** [![GitHub_Stars](https://img.shields.io/github/stars/envoyproxy/envoy?style=social&color=white)](https://github.com/envoyproxy/envoy/stargazers)  
   **CNCF Graduated high-performance L4/L7 edge and service proxy** (Apache-2.0). Written in C++ for maximum throughput and low latency. Features dynamic configuration via xDS gRPC APIs, advanced load balancing, distributed tracing, and serves as the data-plane engine powering modern gateways.

5. **[Apache APISIX](https://github.com/apache/apisix)** [![GitHub_Stars](https://img.shields.io/github/stars/apache/apisix?style=social&color=white)](https://github.com/apache/apisix/stargazers)  
   **Dynamic, real-time, high-performance cloud-native API gateway** (Apache-2.0). Built on Nginx and etcd with hitless dynamic reloads. Provides multi-protocol routing (HTTP, gRPC, WebSocket, MQTT, Dubbo), canary rollouts, active health checks, and a rich multilingual plugin ecosystem (Lua, Go, Python, Wasm).

6. **[Netflix Zuul](https://github.com/Netflix/zuul)** [![GitHub_Stars](https://img.shields.io/github/stars/Netflix/zuul?style=social&color=white)](https://github.com/Netflix/zuul/stargazers)  
   **L7 application gateway and edge service** (Apache-2.0). Powers Netflix's global streaming edge with asynchronous, non-blocking Netty core. Provides dynamic filter routing, security inspection, load shedding, and canary testing across complex JVM topologies.

7. **[Tyk Gateway](https://github.com/TykTechnologies/tyk)** [![GitHub_Stars](https://img.shields.io/github/stars/TykTechnologies/tyk?style=social&color=white)](https://github.com/TykTechnologies/tyk/stargazers)  
   **Batteries-included open-source enterprise API gateway** (MPL-2.0). Written in Go with Redis as its only dependency. No feature gating across runtimes; provides OpenAPI 3.0-first routing, mutual TLS, HMAC authorization, hitless reloads, and custom middleware in Go, JavaScript, Python, or gRPC.

8. **[Alibaba Higress](https://github.com/alibaba/higress)** [![GitHub_Stars](https://img.shields.io/github/stars/alibaba/higress?style=social&color=white)](https://github.com/alibaba/higress/stargazers)  
   **Next-generation cloud-native AI & API gateway** (Apache-2.0). Built on Envoy and Istio core to unify Kubernetes Ingress, microservices gateways, and LLM/AI token rate limiting and prompt management into a single declarative data plane.

9. **[Fabio](https://github.com/fabiolb/fabio)** [![GitHub_Stars](https://img.shields.io/github/stars/fabiolb/fabio?style=social&color=white)](https://github.com/fabiolb/fabio/stargazers)  
   **Zero-configuration, ultra-fast HTTP(S) and TCP router for HashiCorp Consul** (MIT). Automatically inspects Consul service health tags to register and balance routes in real-time without reloads.

10. **[HAProxy](https://github.com/haproxy/haproxy)** [![GitHub_Stars](https://img.shields.io/github/stars/haproxy/haproxy?style=social&color=white)](https://github.com/haproxy/haproxy/stargazers)  
    **The gold standard high-performance TCP/HTTP load balancer and reverse proxy** (GPL-2.0). Renowned for rock-solid reliability, multi-core connection handling, millisecond latency guarantees, and deep observability stats.

11. **[Lura Project (KrakenD Framework)](https://github.com/luraproject/lura)** [![GitHub_Stars](https://img.shields.io/github/stars/luraproject/lura?style=social&color=white)](https://github.com/luraproject/lura/stargazers)  
    **Ultra-high-performance stateless API gateway framework** (Apache-2.0, Linux Foundation). The core engine behind KrakenD. Specializes in backend response aggregation, payload transformation, manipulation, and filtering with zero database dependencies.

12. **[Spring Cloud Gateway](https://github.com/spring-cloud/spring-cloud-gateway)** [![GitHub_Stars](https://img.shields.io/github/stars/spring-cloud/spring-cloud-gateway?style=social&color=white)](https://github.com/spring-cloud/spring-cloud-gateway/stargazers)  
    **Reactive, non-blocking API gateway built for Spring Boot and Java ecosystems** (Apache-2.0). Built on Project Reactor and Netty to provide fine-grained predicate matching, circuit breaking via Resilience4j, and seamless Spring Security integration.

13. **[Emissary-ingress](https://github.com/emissary-ingress/emissary)** [![GitHub_Stars](https://img.shields.io/github/stars/emissary-ingress/emissary?style=social&color=white)](https://github.com/emissary-ingress/emissary/stargazers)  
    **CNCF Incubating Kubernetes-native ingress controller & gateway built on Envoy** (Apache-2.0). Declarative CRD-driven routing (`Mapping`, `Listener`) engineered for developer self-service and GitOps delivery.

14. **[Envoy Gateway](https://github.com/envoyproxy/gateway)** [![GitHub_Stars](https://img.shields.io/github/stars/envoyproxy/gateway?style=social&color=white)](https://github.com/envoyproxy/gateway/stargazers)  
    **Official Kubernetes Gateway API implementation powered by Envoy Proxy** (Apache-2.0). Native CRDs (`GatewayClass`, `HTTPRoute`, `BackendTrafficPolicy`) delivering standardized Kubernetes ingress with per-backend circuit breakers and rate limiting.

15. **[Express Gateway](https://github.com/ExpressGateway/express-gateway)** [![GitHub_Stars](https://img.shields.io/github/stars/ExpressGateway/express-gateway?style=social&color=white)](https://github.com/ExpressGateway/express-gateway/stargazers)  
    **Microservices API Gateway built completely on Express.js and Node.js** (Apache-2.0). Configured via YAML declarations with plug-and-play middleware policies for Key Auth, OAuth2, Rate Limiting, and CORS.

16. **[Kong Kubernetes Ingress Controller](https://github.com/Kong/kubernetes-ingress-controller)** [![GitHub_Stars](https://img.shields.io/github/stars/Kong/kubernetes-ingress-controller?style=social&color=white)](https://github.com/Kong/kubernetes-ingress-controller/stargazers)  
    **Kubernetes Ingress Controller powered by Kong Gateway** (Apache-2.0). Connects Kubernetes native services, Ingress, and Gateway API resources directly with Kong's plugin ecosystem.

17. **[KrakenD CE](https://github.com/krakend/krakend-ce)** [![GitHub_Stars](https://img.shields.io/github/stars/krakend/krakend-ce?style=social&color=white)](https://github.com/krakend/krakend-ce/stargazers)  
    **Community Edition binary distribution of the KrakenD API Gateway** (Apache-2.0). Packaged with standard enterprise-grade middleware, OpenAPI validators, caching, and rate limiters delivering up to 80,000 RPS per node.

18. **[Traefik Mesh](https://github.com/traefik/mesh)** [![GitHub_Stars](https://img.shields.io/github/stars/traefik/mesh?style=social&color=white)](https://github.com/traefik/mesh/stargazers)  
    **Lightweight, straightforward service mesh** (Apache-2.0). Built on Traefik Proxy to control and secure east-west microservice traffic with SMI (Service Mesh Interface) specification compliance.

19. **[Apache APISIX Dashboard](https://github.com/apache/apisix-dashboard)** [![GitHub_Stars](https://img.shields.io/github/stars/apache/apisix-dashboard?style=social&color=white)](https://github.com/apache/apisix-dashboard/stargazers)  
    **Official web UI and visual management dashboard for Apache APISIX** (Apache-2.0). Simplifies configuring routes, upstreams, SSL certificates, consumer credentials, and plugin configurations.

20. **[WSO2 API Manager Core (OSS)](https://github.com/wso2/product-apim)** [![GitHub_Stars](https://img.shields.io/github/stars/wso2/product-apim?style=social&color=white)](https://github.com/wso2/product-apim/stargazers)  
    **Complete open-source enterprise API lifecycle management suite** (Apache-2.0). Provides API Publisher, Developer Portal, Gateway, and Analytics for REST, GraphQL, WebSocket, and streaming events.

---

## 🛠️ Frameworks & Architecture Recommendations

When architecting a modern API gateway layer:
- **Cloud-Native Ingress & Zero-Conf Service Discovery**: Deploy **Traefik** or **Caddy** for instant, automatic route generation from container orchestrator APIs without restart overhead.
- **Plugin Breadth & API Governance**: Choose **Kong** or **Apache APISIX** for extensive plugin ecosystems (OAuth2, rate limiting, Wasm, gRPC transcoding) and declarative GitOps workflows.
- **Standardized Kubernetes Gateway API**: Leverage **Envoy Gateway** or **Emissary-ingress** to configure traffic using upstream CNCF standard CRDs.
- **High-Throughput Aggregation (BFF Pattern)**: Implement **KrakenD** or **Lura** for stateless response merging, filtering, and single-binary low-memory footprints.
- **Raw L4/L7 Performance**: Use **HAProxy** or raw **Envoy Proxy** at the edge for maximum throughput and microsecond latency guarantees.

---

## 🤝 How to Contribute

Contributions are warmly welcomed! Help keep this ecosystem guide comprehensive, fresh, and accurate:

1. 🍴 Fork the repository.
2. 🌿 Create a descriptive feature branch (`git checkout -b feature/add-gateway`).
3. 📝 Add or update entries following the established table or badge list format.
4. 🔗 Ensure all URLs, GitHub_Stars_Badges, and pricing tiers are accurate and verified.
5. 🚀 Submit a Pull Request with a clear explanation of your additions.

⭐ **If this repository helps you make better architecture decisions, please give it a star!**

---

## 💖 Support & Sponsorship

Thank you for visiting and supporting the **Awesome API Gateways** project! 🙏

If this curated list saved you time, helped you evaluate vendors, or inspired your infrastructure architecture:
- ⭐ **Star** this repository to help other developers discover it.
- 🍴 **Fork** and share it with your engineering team or community.
- ☕ **Support continuous maintenance & updates**: Buy me a coffee via the [GitHub Sponsor Dashboard](https://github.com/sponsors/ishandutta2007)!

<p align="center">
  <a href="https://github.com/sponsors/ishandutta2007">
    <img src="https://img.shields.io/badge/Sponsor%20on%20GitHub-%E2%99%A5-ea4aaa?style=for-the-badge&logo=githubsponsors&logoColor=white" alt="Sponsor on GitHub" />
  </a>
</p>

---

## 📈 Star History

[![Star History Chart](https://star-history.dera.page/svg?repos=ishandutta2007/Awesome-API-Gateways&type=date&legend=top-left)](https://star-history.dera.page/#ishandutta2007/Awesome-API-Gateways&type=date&legend=top-left)

---

## ⚖️ Disclaimer

- This is an independent, community-curated list and is neither endorsed by nor affiliated with any of the listed companies.
- **Production Readiness**: Open-source gateways like Traefik, Kong, Envoy, and Apache APISIX are proven at scale and serve as powerful, vendor-independent alternatives to proprietary suites.
- **Operational Costs vs. Licensing**: Managed platforms (e.g., Apigee, Kong Konnect, MuleSoft) include compliance and turnkey operations; self-hosted open-source clusters require engineering hours for maintenance, certificate rotation, and cluster scaling. Evaluate total cost of ownership (TCO) based on your team's operational maturity.
