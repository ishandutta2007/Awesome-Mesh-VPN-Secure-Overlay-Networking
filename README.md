# Awesome-Mesh-VPN-Secure-Overlay-Networking

## Top Mesh VPN & Secure Overlay Networking Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on WireGuard Mesh Overlays, Zero-Trust Network Access (ZTNA), NAT Hole-Punching, Self-Hosted Control Planes & Encrypted Peer-to-Peer Tunnels*  
**Last updated: November 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Mesh VPN & Secure Overlay Networking**. These tools enable DevOps teams, homelabbers, enterprises, and security engineers to interconnect servers, laptops, mobile devices, and Kubernetes clusters across NATs and firewalls using end-to-end encrypted peer-to-peer mesh tunnels without exposing public ports.

**Examples** include Tailscale, ZeroTier, Nebula Cloud, NetBird, Netmaker, WireGuard Cloud, Perimeter 81, Twingate, NordLayer, Cloudflare One, and `tailscale/tailcat` (the category leaders). 

**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosted Tailscale control planes (`Headscale`), full-stack open-source WireGuard mesh platforms (`NetBird`, `Netmaker`, `Innernet`, `Firezone`), cryptographic certificate overlays (`Nebula`, `OpenZiti`), and kernel-grade VPN protocols (`WireGuard`, `AmneziaWG`) — ideal for infrastructure architects, security engineers, homelab operators, and distributed teams.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saashosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

| Platform | Starting Price | Free Tier Limits / Free Trial Duration | Description |
| :--- | :--- | :--- | :--- |
| **[Tailscale](https://tailscale.com)** | **$8/user/month** (Standard plan) | **Free forever plan**: Up to 6 users, unlimited devices, and 3 ACL groups | Zero-config WireGuard mesh VPN service featuring MagicDNS, SSO identity integration, subnet routers, exit nodes, and fine-grained ACLs. |
| **[ZeroTier Central](https://zerotier.com)** | **$18/month** (Essential plan, includes 10 devices; $2/device/mo extra) | **Free forever plan (Personal)**: Up to 10 connected devices, 1 network admin, 1 network (non-commercial use) | Cloud-hosted network controller uniting Layer-2 Ethernet virtualization and Layer-3 mesh routing across cloud, desktop, mobile, and IoT endpoints. |
| **[Defined Networking](https://defined.net)** | **$1/host/month** (Pro plan, unlimited hosts) | **Free forever plan**: Up to 100 hosts, 2 external host routes, 1 managed lighthouse/relay, unlimited admins | Commercial cloud-hosted control plane and certificate authority built by the creators of the open-source Nebula overlay network. |
| **[NetBird Cloud](https://netbird.io)** | **€6/user/month** (~$6.50/user/mo, Team plan) | **Free forever plan**: Up to 5 users and 100 machines with full P2P WireGuard encryption and SSO | Managed cloud edition of the open-source WireGuard zero-trust overlay platform with SSO/IdP integration, posture checks, and automated NAT traversal. |
| **[Netmaker SaaS](https://netmaker.io)** | **$2/active connection/month** (Team plan) | **14-day free trial** (unlimited access to SaaS features) or 30-day Business evaluation | Cloud-orchestrated WireGuard virtual networking platform engineered for high-speed multi-cloud, Kubernetes, and data-center mesh topologies. |
| **[Cloudflare One (Zero Trust)](https://cloudflare.com)** | **$7/user/month** (Pay-as-you-go plan) | **Free forever plan**: Up to 50 users, 24-hour activity log retention, and 2 CASB integrations | Global anycast Zero Trust Network Access (ZTNA) and device mesh platform powered by WireGuard/MASQUE tunnels and Cloudflare's edge network. |
| **[Twingate](https://twingate.com)** | **$5/user/month** (Teams plan, billed annually) | **Free forever plan (Starter)**: Up to 5 users, 50 resources, 2 networks, 1 admin | Modern Zero-Trust Network Access cloud replacing legacy corporate VPNs with identity-verified split tunneling and zero-port-exposure connectors. |
| **[Perimeter 81 (Check Point SASE)](https://perimeter81.com)** | **$8/user/month** (Essentials plan; minimum 10 users) | **30-day free trial** via Check Point Infinity Portal (guided PoC available) | Cloud-native SASE and mesh networking platform combining private wire-speed gateways, device posture checks, and centralized access policies. |
| **[NordLayer](https://nordlayer.com)** | **$8/user/month** (Lite plan, billed annually; 5 user minimum) | **14-day money-back guarantee trial** (full access across all platforms with 100% refund guarantee) | Business adaptive network access platform offering cloud virtual private gateways, Smart Remote Access mesh links, and SSO enforcement. |
| **[Firezone Cloud](https://firezone.dev)** | **$5/user/month** (Team plan) | **Free forever plan (Starter)**: Up to 6 users and 10 service accounts with granular resource access policies | Managed cloud Zero-Trust access platform built on WireGuard and Rust, providing granular resource-level routing and identity provider sync. |


## Open-Source GitHub Projects

- **[tailscale/tailcat](https://github.com)**  
  Open-source Tailscale networking utility (`netcat` over Tailscale) enabling direct, encrypted peer-to-peer stream connections across a Tailnet without manual IP/port plumbing.

- **[Tailscale Open-Source Client & `tsnet`](https://github.com)**  
  Official open-source Tailscale node daemon, CLI, and embeddable Go library (`tsnet`) allowing applications to join a WireGuard mesh directly in userspace.

- **[Headscale](https://github.com)**  
  The premier open-source, self-hosted implementation of the Tailscale control server, giving teams full sovereignty over coordination, MagicDNS, and ACL policies.

- **[NetBird](https://github.com)**  
  All-in-one open-source WireGuard-based overlay network combining peer-to-peer WebRTC/ICE NAT hole-punching, SSO login, DNS management, and an intuitive self-hosted web UI.

- **[Nebula (SlackHQ / Defined Networking)](https://github.com)**  
  Scalable, battle-tested open-source overlay networking tool using Noise Protocol encryption and PKI cryptographic certificates to connect tens of thousands of hosts globally.

- **[ZeroTier One (Open-Source Core)](https://github.com)**  
  Open-source global virtual Ethernet switch and P2P mesh engine supporting custom self-hosted root/moon servers and Layer-2 bridging.

- **[Netmaker](https://github.com)**  
  High-speed open-source WireGuard mesh automation platform utilizing kernel-space WireGuard for near-bare-metal throughput across Linux servers and Kubernetes clusters.

- **[Firezone](https://github.com)**  
  Open-source Zero-Trust Network Access platform written in Rust and Elixir, replacing legacy VPNs with WireGuard-based fine-grained resource access policies.

- **[OpenZiti](https://github.com)**  
  Comprehensive open-source Zero Trust overlay networking platform enabling SDK-embedded application-level zero-trust ("dark services" with zero open firewall ports).

- **[Innernet](https://github.com)**  
  Clean, private-network-first open-source WireGuard mesh coordinator written in Rust using CIDR-based access control and zero third-party cloud dependencies.

- **[WireGuard (`wireguard-linux` & `wireguard-go`)](https://github.com)**  
  The foundational, ultra-fast, auditable open-source cryptographic VPN protocol embedded directly in the Linux kernel and powering modern mesh overlays.

- **[AmneziaWG](https://github.com)**  
  Open-source WireGuard protocol extension introducing packet obfuscation and junk-packet padding to resist Deep Packet Inspection (DPI) blocking while preserving WireGuard speeds.

- **[Tinc VPN](https://github.com)**  
  Veteran, battle-tested open-source peer-to-peer mesh VPN daemon featuring automatic full-mesh routing, compression, and Layer-2/Layer-3 bridging across NATs.

- **[Yggdrasil Network](https://github.com)**  
  Experimental, self-arranging open-source end-to-end encrypted IPv6 mesh routing network implementing compact geometric routing over LAN, internet, and Tor.

- **[Pangolin](https://github.com)**  
  Modern self-hosted open-source tunneled reverse proxy and WireGuard mesh gateway (an open alternative to Cloudflare Tunnels + Zero Trust) with identity-based access control.

- **[Rathole & FRP (Fast Reverse Proxy)](https://github.com)**  
  High-performance open-source reverse proxy and NAT-traversal tunneling engines written in Rust (**[rathole](https://github.com)**) and Go (**[frp](https://github.com)**) for exposing private services securely.

- **[Hyprspace](https://github.com)**  
  Lightweight open-source VPN built on top of `libp2p` creating decentralized, NAT-traversing mesh networks using cryptographic peer identities.

### Additional Strong Open-Source Options

- **[ztncui](https://github.com)** for a clean open-source web user interface managing self-hosted ZeroTier network controllers without relying on ZeroTier Central.
- **[wg-easy](https://github.com)** for the easiest single-container open-source WireGuard server + web admin UI with instant QR code provisioning.
- **[BoringTun (Cloudflare)](https://github.com)** for a high-performance open-source userspace WireGuard implementation written in Rust.
- **[Submariner](https://github.com)** and **[Cilium Cluster Mesh](https://github.com)** for open-source multi-cluster Kubernetes pod-and-service overlay networking.
- Many community **Headscale web admin GUIs (`Headplane`, `Headscale-UI`)**, **STUN/TURN `coturn` relay configs**, and **Docker/OpenWrt subnet-router templates**.

**Frameworks for building custom systems**: Combine **Headscale + Tailscale** or **NetBird** (user & device mesh), **Nebula** (server-to-server PKI mesh), **Pangolin** (tunneled ingress), and **WireGuard** with **tailscale/tailcat** for a sovereign, zero-trust overlay network.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Mesh VPN overlays bridge private internal networks across untrusted public infrastructure; always enforce least-privilege Access Control Lists (ACLs), short-lived node key expirations, Multi-Factor Authentication (OIDC/SSO), and firewall segmentation so a single compromised laptop cannot laterally reach production databases.
- Self-hosted coordination servers (`Headscale`, `NetBird`, `Nebula` Lighthouse) require high-availability uptime, TLS certificates, and regular state/key backups.

---

**Made for DevOps engineers, security architects, homelabbers, and distributed infrastructure builders.**  

