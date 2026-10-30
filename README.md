# us vps hosting: BandwagonHost Plans From $49.99/Year, With Real CPU Limits and a Plan-Picking Guide

Most people searching for US VPS hosting want three things: a server physically in the United States, full root access, and a price that doesn't balloon at renewal. BandwagonHost (often called BWH or 搬瓦工) covers the first two with its KVM PROMO line, which starts at **$49.99/year** for a 20 GB SSD plan with 1 TB of monthly traffic. The catch worth knowing before you click buy: it's strictly self-managed, and the cheapest plans carry CPU fair-use caps that most review sites never mention.

This article walks through every plan currently listed on BandwagonHost's order pages, the actual yearly cost math, the CPU and I/O limits buried in its terms of service, and where this provider fits compared with alternatives like Bluehost or HostFinch.

> **Quick picks**
> - Light workload (blog, small site, personal proxy): **20G KVM PROMO** at $49.99/year — cheapest entry, annual billing only.
> - Running actual services (databases, app hosting): **80G KVM PROMO** at $199.99/year gets you 4 GB RAM and 3 TB traffic without the tightest CPU cap.
> - Need low latency to China or Southeast Asia: the Singapore CN2 GIA line starts at $49.99/month, fixed at the Equinix SG1 datacenter.
>
> 👉 [Check BandwagonHost's current KVM plan prices](https://bandwagonhost.com/aff.php?aff=74518&gid=1)

## BandwagonHost's full plan lineup right now

BandwagonHost currently splits its public VPS offering into two families: the general KVM PROMO plans (multi-datacenter, migratable) and the Singapore CN2 GIA "SPECIAL PROMO V5" plans (fixed location). All plans run on KVM virtualization with the in-house KiwiVM control panel, include 1 dedicated IPv4 address, a routed /64 IPv6 subnet, free automatic backups, free snapshots, and a 99.95% uptime guarantee.

### KVM PROMO VPS (1 Gbps port, SSD RAID-10)

| Plan | SSD / RAM | CPU | Traffic | Price (USD) | Order |
| --- | --- | --- | --- | --- | --- |
| 20G KVM | 20 GB / 1 GB | 2x Xeon | 1 TB/mo | **$49.99/year** (annual only) | [ Order 20G KVM](https://bandwagonhost.com/aff.php?aff=74518&gid=1) |
| 40G KVM | 40 GB / 2 GB | 3x Xeon | 2 TB/mo | $52.99/semi-yr · $99.99/yr | [ Order 40G KVM](https://bandwagonhost.com/aff.php?aff=74518&gid=1) |
| 80G KVM | 80 GB / 4 GB | 4x Xeon | 3 TB/mo | $19.99/mo · $199.99/yr | [ Order 80G KVM](https://bandwagonhost.com/aff.php?aff=74518&gid=1) |
| 160G KVM | 160 GB / 8 GB | 5x Xeon | 4 TB/mo | $39.99/mo · $399.99/yr | [ Order 160G KVM](https://bandwagonhost.com/aff.php?aff=74518&gid=1) |
| 320G KVM | 320 GB / 16 GB | 6x Xeon | 5 TB/mo | $79.99/mo · $799.99/yr | [ Order 320G KVM](https://bandwagonhost.com/aff.php?aff=74518&gid=1) |
| 480G KVM | 480 GB / 24 GB | 7x Xeon | 6 TB/mo | $119.99/mo · $1,199.99/yr | [ Order 480G KVM](https://bandwagonhost.com/aff.php?aff=74518&gid=1) |

All of these plans (except the 20G, which is annual-only) also offer quarterly and semi-annual billing at intermediate rates. The KVM line lets you choose your datacenter at checkout and migrate between datacenters for free later — a genuine perk if you initially misjudge where your users are.

### Singapore CN2 GIA — SPECIAL PROMO V5 (fixed at Equinix SG1)

| Plan | SSD / RAM | Traffic | Port | Price (USD) | Order |
| --- | --- | --- | --- | --- | --- |
| 40G V5 | 40 GB / 2 GB | 500 GB/mo | 1.5 Gbps | $49.99/mo · $499.99/yr | [ Order 40G V5](https://bit.ly/BandwaGon) |
| 80G V5 | 80 GB / 4 GB | 1 TB/mo | 1.5 Gbps | $86.99/mo · $869.99/yr | [ Order 80G V5](https://bit.ly/BandwaGon) |
| 160G V5 | 160 GB / 8 GB | 2 TB/mo | 2.5 Gbps | $165.99/mo · $1,665.99/yr | [ Order 160G V5](https://bit.ly/BandwaGon) |
| 320G V5 | 320 GB / 16 GB | 4 TB/mo | 2.5 Gbps | $329.99/mo · $3,199.00/yr | [ Order 320G V5](https://bit.ly/BandwaGon) |
| 640G V5 | 640 GB / 32 GB | 6 TB/mo | 5 Gbps | $549.99/mo · $5,549.99/yr | [ Order 640G V5](https://bit.ly/BandwaGon) |
| 1280G V5 | 1280 GB / 64 GB | 8 TB/mo | 5 Gbps | $1,059.99/mo · $10,559.99/yr | [ Order 1280G V5](https://bit.ly/BandwaGon) |

The Singapore plans include a secondary private network interface and can't be migrated to another datacenter. They're priced for a specific audience — if your traffic isn't China/Singapore-bound, the US KVM line is the better value by a wide margin.

## What a year of US VPS hosting actually costs here

Sticker prices hide a simple pattern: annual billing on BandwagonHost saves you roughly 17% versus paying month to month.

Take the 80G plan. Monthly billing runs $19.99 × 12 = $239.88 per year. Annual billing is a flat $199.99 — a $39.89 saving for identical hardware. The gap scales with plan size: the 160G plan costs $479.88 monthly versus $399.99 annually, and the 480G plan $1,439.88 versus $1,199.99. The same math holds on the Singapore line, where the 40G V5 works out to $599.88 monthly or $499.99 on the annual term.

Two practical notes on cost:

1. **The 20G plan is the only one locked to a single billing cycle.** At $49.99/year (about $4.17/month), it undercuts nearly every comparable US VPS offer — but you pay the full year up front, so don't buy it to "try things out."
2. **No permanent new-customer discount exists.** Community-shared promo codes circulate (typically in the 5–7% recurring range), but several long-running codes were retired by the provider in late 2025, and the discount on a $49.99 plan amounts to about $3 a year anyway. Plan choice matters far more than coupon hunting.

If you want to verify the current rates before committing, the order pages list every billing cycle explicitly:

👉 [See annual and monthly pricing for all KVM plans](https://bandwagonhost.com/aff.php?aff=74518&gid=1)

## The CPU fair-use limits most reviews skip

Here's the detail that separates a good purchase from a frustrating one. BandwagonHost's terms of service impose hourly average CPU load caps that vary sharply by plan:

- **20G KVM**: capped at 50% of one core
- **40G KVM**: capped at 75% of one core
- **80G and above**: 100% of one core, scaling up to 100% of 8 cores on the largest plans
- **V5 CN2 GIA series**: 100% of one core, up to 100% of 8 cores

Exceeding the cap doesn't kill your VPS — it keeps running, but the CPU gets throttled to your plan's allowance, with a notice in KiwiVM. Throttling lifts automatically once your load drops back. Sustained storage I/O above 100 MiB/s for over four hours triggers an email warning first; continued overuse can lead to temporary suspension.

What this means in practice: the $49.99/year 20G plan is excellent for a lightweight website, a personal VPN endpoint, or a small bot — and poor for compiling code, running crawlers, or anything with a persistent multi-core load. If your workload idles low but spikes hard, an 80G or larger plan is the safer bet despite the higher price. For nonstop heavy compute, the SLA-tier plans (sold separately, without CPU caps) exist precisely for that, though they're priced accordingly.

One more honest caveat: BandwagonHost's storage is fully redundant, but the terms state the company takes no responsibility for data loss and strongly recommends you back up independently and periodically verify restores. Free automatic backups and snapshots are included on every plan — use them, but treat them as a convenience layer, not a disaster-recovery contract.

## What you can't run on it

BandwagonHost's acceptable-use policy is stricter than many buyers expect. Explicitly banned: cryptocurrency mining (and associated decentralized compute services), BitTorrent in any form (trackers, clients, files, links), Tor relays and exit nodes, open proxies and open DNS resolvers, any mass mailing including double opt-in lists, nested virtualization such as Qemu (Docker is a permitted exception), and unlicensed financial or investment platforms.

If your use case involves torrenting, mining, or running a mail server that sends newsletters, this provider will end your service — look elsewhere from the start. For typical web hosting, application deployment, and development work with Docker, none of this gets in the way.

## Is it really "self-managed"? Yes, and that's the deal

BandwagonHost states plainly that its service is self-managed, and that this is how it keeps prices down. The terms go further: users are expected to demonstrate they can independently administer a Linux system. There's no ticket-based hand-holding for software installs, configuration, or troubleshooting inside your VPS.

What you do get on the infrastructure side is solid for the price: enterprise-grade hardware the company owns outright, its own IP space, 1–10 Gbps uplinks, node monitoring every minute for failures and overload, weekly network security audits, and the KiwiVM panel covering start/stop, OS reloads, an emergency console, rDNS management, datacenter migration, snapshots, and an API. Supported operating systems include AlmaLinux, RockyLinux, CentOS, Debian, Ubuntu, CentOS Stream, and Fedora, plus a large library of bootable ISOs — and the company says it adds ISOs on request.

If you need someone else to patch your server at 2 a.m., a managed VPS from another provider is the right product. If you're comfortable with SSH and a root prompt, the self-managed trade-off is exactly what makes a $49.99/year KVM plan possible.

## How BandwagonHost compares for US VPS hosting

A quick, link-free comparison with competitors that publish their numbers:

| Provider | Entry price | Storage | Notable terms |
| --- | --- | --- | --- |
| BandwagonHost | $49.99/year (20G KVM) | 20 GB SSD RAID-10 | Self-managed; CPU fair-use caps on low plans; no SLA on standard plans |
| Bluehost | $4.69/month (self-managed) | NVMe SSD | "Unmetered" bandwidth capped at 25% of system resources sustained 90 seconds; no cPanel included |
| HostFinch | $7.99/month (US-VPS-1) | 40 GB SSD | 300 Mbps port, unmetered traffic, monthly billing only |
| Amaze Servers | Prices not published | NVMe SSD | Multi-city US locations, 1 Gbps, free DDoS protection claimed |
| Fornex | Prices not published | SSD | Dallas datacenter, 99.99% uptime SLA claimed |

Reading the table honestly: Bluehost and HostFinch are cheaper on a monthly cash-flow basis for tiny workloads, and Bluehost's entry tier suits someone testing the waters month to month. Where BandwagonHost pulls ahead is annual value (the 20G works out to roughly $4.17/month for a dedicated IPv4 and free datacenter migration), the traffic allowances (1–6 TB/month on the KVM line), and the network pedigree — BandwagonHost operates 8×10 Gbe CN2 GIA/CTGNet links across its two Los Angeles datacenters, with direct peering in the region, which is why its plans are a fixture among users serving China-bound traffic. HostFinch's higher tiers (4 vCPU/8 GB at $25.99/month) make more sense if you want guaranteed vCPUs with monthly flexibility instead of an annual commitment.

## Quick answers

**Does the $49.99/year price renew at the same rate?** The order page lists a single annual price with no separate renewal figure shown; verify the renewal terms in your cart before completing payment.

**Can I switch datacenters after purchase?** Yes, on the standard KVM line — migration between datacenters is free and handled from KiwiVM. The Singapore V5 plans are fixed at Equinix SG1.

**Which OS can I install?** AlmaLinux, RockyLinux, CentOS, Debian, Ubuntu, CentOS Stream, and Fedora, plus manual ISO installs from a large bootable library.

**Is there a money-back guarantee?** A refund policy isn't published on the pages reviewed here, so don't assume one — treat an annual purchase as a commitment.

## Which plan should you actually buy

- **Blog, portfolio, personal VPN or small proxy** → 20G KVM at $49.99/year. Just respect the 50%-of-one-core cap.
- **Website plus a database or two, moderate traffic** → 80G KVM at $199.99/year. Full core access and 3 TB of traffic make this the practical sweet spot.
- **Sustained heavy compute** → the standard plans will throttle you; look at the SLA tier instead.
- **Latency-sensitive traffic to China or Southeast Asia** → Singapore CN2 GIA V5, from $49.99/month, fixed at Equinix SG1.
- **Can't manage a Linux server yourself** → skip self-managed VPS entirely; no plan here fixes that.
- **Mining, torrenting, or bulk mailing** → against the acceptable-use policy; choose a provider that permits it.

One last check before you pay: confirm the billing cycle (annual saves ~17% versus monthly), pick the datacenter deliberately rather than accepting the default, and take a snapshot right after your initial setup. When you're ready, the [👉 KVM plan order page](https://bandwagonhost.com/aff.php?aff=74518&gid=1) lists current availability and every billing option in one place.
