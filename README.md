# Awesome-Private-Cloud-Service-Endpoint

## Top Private Cloud Service Endpoint Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Private Connectivity, Service Mesh & Self-Hosted Tunnels*  

**Last updated: October 2026**



This repository tracks notable **commercial private service endpoint platforms** and **open-source projects** that connect services privately across clouds, VPCs, and on-premises environments — without exposing traffic to the public internet.



**Examples** include AWS PrivateLink, Azure Private Link, Google Cloud Private Service Connect, Cloudflare Magic WAN, Zscaler Private Access, HashiCorp Consul, Traefik Hub, Kong Mesh, Tailscale, and Ngrok (the category leaders).



**Open-source emphasis**: Private cloud service endpoints are a strong open-source domain. **Netmaker**, **NetBird**, **Tailscale**, and **Headscale** deliver WireGuard-based overlay networks. **Consul** provides service discovery and mesh connectivity. **Traefik**, **Kong**, **Envoy**, and **Linkerd** power service mesh and ingress. **frp**, **rathole**, **Chisel**, and **sish** enable self-hosted tunnels. **OpenZiti** brings zero-trust networking with embedded SDKs. This section is heavily expanded.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[AWS PrivateLink](https://aws.amazon.com/privatelink/)**  

  **AWS's private connectivity service** — access services over private IP without internet exposure . **VPC endpoint services with Interface and Gateway endpoints** . **Best for AWS-native private connectivity** .



- **[Azure Private Link](https://azure.microsoft.com/en-us/products/private-link/)**  

  **Microsoft's private endpoint service** — access Azure PaaS over private IP . **Private endpoints and Private Link service** . **Best for Azure-native private connectivity** .



- **[Google Cloud Private Service Connect](https://cloud.google.com/vpc/docs/private-service-connect)**  

  **Google's private service access** — connect VPCs to Google services and third-party services privately . **Best for GCP-native private connectivity** .



- **[Cloudflare Magic WAN](https://www.cloudflare.com/)**  

  **Enterprise WAN-as-a-service** — Zero Trust integration connecting branch offices and data centers . **Best for enterprise WAN** .



- **[Zscaler Private Access](https://www.zscaler.com/products/zscaler-private-access)**  

  **The market-leading ZTNA platform** — zero trust access to private apps . **Best for enterprise private access** .



- **[HashiCorp Consul](https://www.consul.io/)**  

  **Service discovery and mesh** — see Open-Source section for the core project.



- **[Traefik Hub](https://traefik.io/)**  

  **Cloud-native networking platform** — API gateway, ingress, and service mesh . **Best for Kubernetes networking** .



- **[Kong Mesh](https://konghq.com/)**  

  **Enterprise service mesh** built on Kuma — multi-cluster, multi-cloud . **Best for Kong ecosystem users** .



- **[Tailscale](https://tailscale.com/)**  

  **The easiest WireGuard-based mesh VPN** — see Open-Source section for the client.



- **[Ngrok](https://ngrok.com/)**  

  **Secure tunnels to localhost** — expose local services to the internet . **Best for development and webhooks** .



## Open-Source GitHub Projects



### Overlay Networking & Private Connectivity



- **[Netmaker](https://github.com/gravitl/netmaker)**  

  **The leading open-source WireGuard-based Zero Trust networking platform**, Apache-2.0 licensed . **Creates flat, encrypted overlay networks** — every node is "next door" . **Kernel WireGuard for superior performance** . **Gateways for traffic relaying and egress routing** . **Best for multi-cloud and hybrid cloud networking** .



- **[NetBird](https://github.com/netbirdio/netbird)**  

  **Open-source Zero Trust networking platform**, Apache-2.0 licensed . **WireGuard-based peer-to-peer overlay networks** . **Identity provider integration for granular access control** . **Self-hosted with admin dashboard** . **Best for teams wanting managed-like experience with full data ownership** .



- **[Tailscale](https://github.com/tailscale/tailscale)**  

  **The easiest WireGuard-based mesh VPN**, BSD-3-Clause licensed (client only; coordination server proprietary) . **Excellent NAT traversal, MagicDNS, ACLs, and SSO** . **Best for easy overlay networking** .



- **[Headscale](https://github.com/juanfont/headscale)**  

  **Self-hosted Tailscale control server**, BSD-3-Clause licensed . **Use Tailscale clients with your own coordination server** . **Best for Tailscale without vendor dependency** .



- **[OpenZiti](https://github.com/openziti/ziti)**  

  **Open-source zero trust networking platform**, Apache-2.0 licensed with **2,900+ GitHub stars** . **Comprehensive ZTNA with embeddable SDKs** . **Best for full control over zero trust infrastructure** .



- **[ZeroTier](https://github.com/zerotier/ZeroTierOne)**  

  **Multi-cloud SDN platform**, BSL 1.1 licensed (client open source; controller source-available) . **Custom protocol with strong NAT traversal** . **Best for legacy SDN deployments** .



### Service Mesh & Ingress



- **[Consul](https://github.com/hashicorp/consul)**  

  **Service discovery and service mesh**, MPL-2.0 licensed with **28,000+ GitHub stars** . **Connect for mTLS** — automatic service-to-service encryption . **Intentions for authorization** . **Best for service discovery with mesh capabilities** .



- **[Traefik](https://github.com/traefik/traefik)**  

  **Cloud-native application proxy**, MIT licensed with **50,000+ GitHub stars** . **Ingress, reverse proxy, and service mesh** . **Automatic service discovery** . **Best for Kubernetes ingress** .



- **[Envoy](https://github.com/envoyproxy/envoy)**  

  **High-performance edge and service proxy**, Apache-2.0 licensed with **25,000+ GitHub stars** . **The foundation for most service meshes** . **Best for service proxy** .



- **[Linkerd](https://github.com/linkerd/linkerd2)**  

  **The most performant service mesh**, Apache-2.0 licensed with **10,000+ GitHub stars** . **Rust-based micro-proxy** . **Best for simple service mesh** .



- **[Istio](https://github.com/istio/istio)**  

  **The most feature-rich service mesh**, Apache-2.0 licensed with **36,000+ GitHub Stars** . **Traffic management, mTLS, and observability** . **Best for enterprise service mesh** .



- **[Kuma](https://github.com/kumahq/kuma)**  

  **Universal service mesh**, Apache-2.0 licensed with **3,500+ GitHub stars** . **Multi-cluster, multi-cloud, and multi-platform** . **Best for universal service mesh** .



### Self-Hosted Tunnels



- **[frp](https://github.com/fatedier/frp)**  

  **Fast reverse proxy for exposing local servers behind NAT**, Apache-2.0 licensed with **109,000+ GitHub stars** . **The most popular tunneling tool for self-hosters** . **Best for exposing local services** .



- **[rathole](https://github.com/rapiz1/rathole)**  

  **Lightweight, high-performance reverse proxy in Rust**, Apache-2.0 licensed . **Alternative to frp and ngrok** . **Best for lightweight tunneling** .



- **[Chisel](https://github.com/jpillora/chisel)**  

  **Fast TCP/UDP tunnel over HTTP with SSH**, MIT licensed . **Secure tunneling with authentication** . **Best for secure tunnels** .



- **[sish](https://github.com/antoniomika/sish)**  

  **Open-source ngrok alternative**, MIT licensed . **HTTP(S)/WS(S)/TCP tunnels to localhost** . **Best for self-hosted ngrok** .



- **[bore](https://github.com/ekzhang/bore)**  

  **Simple CLI tool for making tunnels to localhost**, MIT licensed with **10,000+ GitHub stars** . **Minimal and fast** . **Best for simple tunnels** .



- **[localtunnel](https://github.com/localtunnel/localtunnel)**  

  **Expose localhost to the world**, MIT licensed with **20,000+ GitHub stars** . **Simple tunneling** . **Best for development** .



### Additional Strong Open-Source Options



- **WireGuard** — Modern VPN protocol underlying most overlay networks .

- **OpenVPN** — Veteran open-source VPN .

- **strongSwan** — IPsec VPN .

- **Libreswan** — IPsec VPN .

- **Tinc** — Mesh VPN daemon .

- **Nebula** — Slack's overlay networking .

- **Innernet** — Private network for containers .

- **Pritunl Zero** — BeyondCorp-style access .



**Frameworks for building custom private cloud service endpoint solutions**: Combine **Netmaker** for WireGuard-based overlay networking across clouds . Use **NetBird** for zero trust networking with identity integration . Deploy **Consul** for service discovery and mesh connectivity . Choose **Traefik** or **Envoy** for ingress and service proxy . Integrate **frp** or **sish** for self-hosted tunnels . Use **OpenZiti** for zero trust networking with embeddable SDKs . Note that true managed private endpoints with global infrastructure, managed SLAs, and vendor-supported connectivity (AWS PrivateLink, Azure Private Link) remain primarily commercial territory; open-source stacks provide strong overlay networking, service mesh, and tunneling foundations that require integration for complete private connectivity.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Private cloud service endpoints control access to sensitive services and infrastructure. Self-hosted solutions require proper security hardening, key management, and access policy configuration.

- **Commercial private endpoints (PrivateLink, Private Link) are free for the endpoint itself** — you pay for the resources and data processing. Open-source alternatives require infrastructure and operational expertise.

- **Overlay networking introduces complexity** — NAT traversal, key management, and routing require understanding. Netmaker and NetBird simplify but don't eliminate operational responsibility .

- **License considerations**: Netmaker uses Apache-2.0, Tailscale client uses BSD-3-Clause, ZeroTier uses BSL 1.1, and OpenZiti uses Apache-2.0. Verify licensing against your use case before committing .

- The open-source ecosystem provides strong overlay networking, service mesh, and tunneling foundations, but **global infrastructure, managed SLAs, and vendor-supported connectivity** remain primarily commercial offerings.



---



**Made for network engineers, platform teams, and organizations seeking private connectivity sovereignty.**  

Let's make private cloud service endpoints more open, transparent, and secure.
