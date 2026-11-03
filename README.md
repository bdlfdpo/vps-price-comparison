# vps price comparison: what sticker prices hide, what renewals actually cost, and how RackNerd's lifetime-price deals stack up against Vultr, Contabo and Hetzner

Most VPS price comparisons stop at the number on the pricing page. That number is genuinely the least useful one. Two providers can both advertise "from $2.50," and one of them will bill you $30 next year while the other bills you the same $30 every year for as long you keep the server. Add refund policies that range from "30-day money-back guarantee" to "no refunds, period," and the real ranking looks nothing like the homepage.

This comparison looks at what you actually pay: first invoice, renewal invoice, and the total cost of running a box for three years. The budget anchor here is **RackNerd**, whose annual KVM VPS specials currently start at **$21.99/year** with a written promise that you renew at the same rate forever. Against it: Vultr, Contabo, and Hetzner — three names that dominate every "cheap VPS" shortlist, each good at something RackNerd isn't.

If you want the short version:

> **Most people shopping a budget VPS should get the 2 GB KVM VPS special at $35.99/year** (2 vCPU, 35 GB SSD, 5 TB transfer) — enough headroom for a self-hosted app stack, a couple of small sites, or a VPN endpoint, at roughly $3/month. Just know that RackNerd doesn't offer refunds by default, so if you're unsure, start monthly. 👉 [Grab the 2 GB KVM VPS for $35.99/year](https://my.racknerd.com/aff.php?aff=11397&pid=953)

## RackNerd's full price list, as it stands now

RackNerd sells two distinct VPS lines, and mixing them up is the most common mistake in reviews of this host.

The first line is the **annual specials** — five fixed configurations, billed yearly, priced low enough that people assume there's a catch on renewal. There isn't. This is the exact wording from RackNerd's specials page:

> "These RackNerd VPS specials are lifetime recurring. You can renew at the same rate for as long as you decide to keep the service."

All five plans include full root access, 1 dedicated IPv4, a 1Gbps port, KVM virtualization, and RackNerd's ctrl panel (reboot, reinstall, HTML5 VNC console, one-click apps, firewall rules). Every plan can be deployed in multiple datacenter locations — RackNerd runs 20 across North America, Europe, and Asia.

| Plan | vCPU / RAM | SSD | Monthly transfer | Annual price | Order |
| --- | --- | --- | --- | --- | --- |
| 1 GB KVM VPS (most popular) | 1 / 1 GB | 20 GB | 3 TB | **$21.99/yr** | [ Order the 1 GB special](https://my.racknerd.com/aff.php?aff=11397&pid=952) |
| 2 GB KVM VPS | 2 / 2 GB | 35 GB | 5 TB | **$35.99/yr** | [ Order the 2 GB special](https://my.racknerd.com/aff.php?aff=11397&pid=953) |
| 4 GB KVM VPS | 3 / 4 GB | 60 GB | 7 TB | **$59.99/yr** | [ Order the 4 GB special](https://my.racknerd.com/aff.php?aff=11397&pid=954) |
| 6 GB KVM VPS | 6 / 6 GB | 100 GB | 12 TB | **$89.99/yr** | [ Order the 6 GB special](https://my.racknerd.com/aff.php?aff=11397&pid=955) |
| 8 GB KVM VPS | 7 / 8 GB | 150 GB | 20 TB | **$119.99/yr** | [ Order the 8 GB special](https://my.racknerd.com/aff.php?aff=11397&pid=956) |

The second line is the **Los Angeles monthly KVM line**, sold as an "Asia Optimized Network" (RackNerd routes it through Noction IRP). These plans carry more CPU cores and storage per gigabyte of RAM than the specials, and they're the right tool when you don't want to prepay a year. One oddity worth knowing: the entry plan here is a 512 MB box billed *annually* at $26.99 — everything above it is monthly.

| Plan (RAM) | vCore | SSD | Transfer | Price | Order |
| --- | --- | --- | --- | --- | --- |
| 512 MB | 1 | 30 GB | 500 GB | $26.99/yr | [ Order the 512 MB annual plan](https://my.racknerd.com/aff.php?aff=11397&pid=1) |
| 1 GB | 2 | 50 GB | 1 TB | $17.99/mo | [ Order the 1 GB monthly plan](https://my.racknerd.com/aff.php?aff=11397&pid=20) |
| 2 GB | 3 | 75 GB | 2 TB | $20.59/mo | [ Order the 2 GB monthly plan](https://my.racknerd.com/aff.php?aff=11397&pid=21) |
| 4 GB | 4 | 130 GB | 3 TB | $24.59/mo | [ Order the 4 GB monthly plan](https://my.racknerd.com/aff.php?aff=11397&pid=22) |
| 6 GB | 5 | 170 GB | 4 TB | $27.59/mo | [ Order the 6 GB monthly plan](https://my.racknerd.com/aff.php?aff=11397&pid=23) |
| 8 GB | 6 | 220 GB | 5 TB | $36.59/mo | [ Order the 8 GB monthly plan](https://my.racknerd.com/aff.php?aff=11397&pid=24) |
| 12 GB | 7 | 300 GB | 6 TB | $55.99/mo | [ Order the 12 GB monthly plan](https://my.racknerd.com/aff.php?aff=11397&pid=25) |

Beyond VPS, RackNerd also lists dedicated servers from $139/month on its own site, and runs periodic promos (cPanel shared hosting from around $10–14/year on its promo pages, dual-Xeon dedicated boxes from $39/month). Those matter for a different search; this comparison stays on VPS.

## The renewal math nobody puts in the comparison table

Here's the calculation that separates a real budget host from a teaser rate. Across the industry, promotional VPS prices routinely renew at 1.3 to 3 times the first-year rate. One widely cited example from a 2026 price survey of 106 hosts: a VPS plan advertised at $2.09/month on a two-year term renews at $4.68/month — a 124% jump.

Run the same three-year math on the plans in this comparison:

- **RackNerd 2 GB special:** $35.99 × 3 years = **$107.97 total**, renewal identical every year.
- **RackNerd 1 GB special:** $21.99 × 3 years = **$65.97 total**.
- **Vultr, 1 GB Cloud Compute class:** roughly $6/month = ~$72/year, **~$216 over three years**.
- **That $2.09/mo teaser plan:** $106 over three years — cheap, but it lands you at 2.2× the sticker rate by year two.

A 60-provider comparison updated in October 2026 put the median price for a 1 vCPU / 1 GB plan at **$10.37/month** across the market. RackNerd's 1 GB special works out to about **$1.83/month**. That's the whole reason this host keeps showing up in budget comparisons: the discounted number is also the ongoing number.

One honest caveat on performance, because cheap isn't free: in a three-way stress test of Vultr, Contabo, and RackNerd, RackNerd trailed on every metric — roughly 2,800 single-core CPU score vs. Vultr's 4,100, about 20K disk read IOPS vs. Vultr's 50K, and ~750 Mbps network throughput vs. ~950. For reverse proxies, VPN tunnels, small web apps, and bots, that gap is irrelevant. For a busy database or a production Latency-sensitive workload, it isn't, and that's exactly when Vultr or Hetzner earn their higher price.

## How RackNerd compares on the numbers

| Provider | Entry price | Similar-spec price (1 vCPU / 1 GB class) | Billing model | Known strengths |
| --- | --- | --- | --- | --- |
| RackNerd | $21.99/yr (specials) | ~$1.83/mo equivalent | Annual prepay, lifetime same-price renewal | 20 datacenter locations, one-click self-host/AI apps, port 25 open |
| Vultr | $2.50/mo (512 MB, IPv6-only) | ~$6/mo | Hourly, month-to-month | 30+ locations, hourly billing, strongest raw performance of the three tested |
| Contabo | €3.99/mo | Config-heavy plans | Monthly | Best raw specs per euro in the EU |
| Hetzner | €4.50/mo | ~€4.50/mo | Monthly | EU network quality and price balance |

Where each one actually wins, without the marketing:

- **Vultr** is the pick for bursty workloads. Hourly billing means you can spin up a GPU-free inference node or test box for an hour and delete it — you pay only for what you use. RackNerd's annual model makes no sense for that pattern.
- **Contabo** gives you more RAM and disk per euro if your users are in Europe. The tradeoff historically is provisioning and support experience, which is why it keeps losing "beginner-friendly" categories despite the specs.
- **Hetzner** is the default answer for EU-based production sites: solid network, sane billing, €4.50/month for a usable small plan.
- **RackNerd** wins when the requirement is "keep something running 24/7 for the least money over years" — the exact use case of most self-hosters. A five-star Trustpilot reviewer (the host scores 4.1/5 across 371 reviews there) put it plainly after buying the 2 GB promo: "amazing price for what you get," noting support changed his PTR record within 10 minutes.

## The fine print: refunds, "unmanaged," and one unusual perk

This is the part most comparison posts skip, and it's the part most likely to bite you.

**RackNerd does not offer refunds by default.** Its terms state: *"Refunds are issued on a case-by-case basis since by default no refunds are provided once payment is received."* There is no money-back guarantee, and prepaid account credit is explicitly non-refundable. In practice, refunds are granted for things like a VPS that won't boot minutes after delivery or a dedicated server that misses its 72-hour delivery window — and refused for "I changed my mind" on a used annual plan. One more number worth knowing before disputing a charge: a credit card chargeback triggers a **$125–$250 administrative fee** under its billing policy, which is a very expensive way to recover a $21.99 payment.

The practical workaround is built into the price list above. If you're not sure the network works well from your location, order the **1 GB Los Angeles plan at $17.99/month**, test it for a few weeks, then either cancel or switch to the annual special you actually wanted. Monthly commitment, ~60 cents a day, no year-long bet.

Two more items from the fine print:

1. **It's unmanaged.** Support is available 24/7 and responsive (the PTR-record anecdote above is typical), but they fix platform-level problems — network, host node, panel. Your application is your problem. If you need someone to configure your web server for you, a managed VPS at $20–70/month is a different product category entirely.
2. **Port 25 is not blocked.** This sounds trivial until you try to run a mail server; most mainstream providers block outbound SMTP by default. One RackNerd reviewer specifically called this out as "somewhat rare for providers who are actually legit." If self-hosting email is on your list, this matters more than 500 MB of extra RAM.

Smaller details that come up in practice: custom ISO installs are supported but require a support ticket; Los Angeles and France locations can be assigned up to 100 free IPv6 addresses on request; plan upgrades take effect with about a one-minute reboot; and every special ships with RackNerd's ctrl panel, including an out-of-band HTML5 VNC console for when you lock yourself out over SSH.

## Which plan for which job

RackNerd publishes the RAM requirements for its one-click app catalog, which makes plan selection unusually mechanical:

- **Reverse proxy, WireGuard, a small bot, DNS:** 1 GB special at $21.99/year. One vCPU and 20 GB SSD is plenty; anything more is spending for its own sake.
- **n8n or Coolify, a couple of small websites, a Homebridge instance:** 2 GB special at $35.99/year. This is the sensible default for most self-hosters.
- **AnythingLLM, Ollama, LibreChat, or Hermes Agent:** jump to the 4 GB special at $59.99/year — these apps want at least 4 GB of RAM per the official FAQ.
- **OpenClaw:** needs at least 8 GB, so the 8 GB special at $119.99/year is the entry ticket. If your AI workload is bursty rather than always-on, hourly-billed Vultr may cost you less overall.
- **Not sure yet:** the 1 GB monthly LA plan at $17.99/month exists precisely for this decision. 👉 [Try the 1 GB Los Angeles plan at $17.99/month](https://my.racknerd.com/aff.php?aff=11397&pid=20)

And the honest "who shouldn't buy this": anyone needing managed support, Windows licensing, hourly billing, or top-tier CPU/disk performance. RackNerd's own benchmark numbers are mid-pack; you're trading performance headroom for a price that no hourly provider can match on a multi-year horizon.

## FAQ

**Does RackNerd raise the price at renewal?**
No — for the annual specials, the official wording is that they're "lifetime recurring" and renew at the same rate for as long as you keep the service. This is the single biggest difference from the teaser-rate competitors in this comparison.

**Can I get a refund if I change my mind?**
Not by default. Refunds are case-by-case, granted mainly for genuine technical faults shortly after delivery. If you want an exit ramp, order monthly instead of annual.

**What OS can I run?**
CentOS, Rocky Linux, AlmaLinux, Fedora, Debian, or Ubuntu at order time; custom ISOs via a support ticket. The ctrl panel can reinstall the OS later, with an HTML5 VNC console for unattended installs.

**How fast is setup?**
VPS plans provision automatically right after payment — minutes, not hours. Dedicated servers are manually built and take 24–72 hours.

**Is the cheap 1 GB plan actually usable?**
For its target jobs, yes. A public 2026 Reddit thread on starter VPS recommendations had multiple users describing 1 GB RackNerd boxes running reverse proxies and tunnel setups for around €17/year without issues. It is not a plan for databases or container fleets.

## Picking in ten seconds

Running one always-on service on a tight budget → **1 GB special, $21.99/year**. Self-hosting a real app stack → **2 GB special, $35.99/year**. Local AI tools via Ollama or AnythingLLM → **4 GB special, $59.99/year**. Hourly workloads or need 30+ global locations → that's Vultr territory; European production workloads → Hetzner or Contabo. Everyone else whose use case is "a small Linux box that stays up for years" is who RackNerd built these specials for.

Before ordering, do one thing: use RackNerd's public looking-glass and test files to check latency from your location — with no default refund, a two-minute ping test is the cheapest insurance in this whole comparison. 👉 [Check RackNerd's current specials and locations](https://bit.ly/RacKnerd)
