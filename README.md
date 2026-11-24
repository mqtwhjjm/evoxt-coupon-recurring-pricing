# Evoxt Coupon Code: The 40% Recurring Codes, What VM-1 Costs After Discount, and Which Plan Makes the Code Worth Using (Full Plan Table + Renewal Math)

Three Evoxt coupon codes are circulating right now, and all three do the same thing: **40% off, recurring, on VM-1 and above**. They are `EVOXT595`, `BHW595` and `AFF1129-hostspot`. On the $5.99/mo VM-1, that takes the bill to roughly **$3.59/mo** for 1 vCore, 2 GB RAM, 20 GB NVMe and 1 TB of monthly transfer.

"Recurring" is the part that matters here. Most hosting promo codes knock money off the first invoice and then quietly expire, and that's the assumption a lot of people bring to a page like this one. These codes are described as applying to every billing cycle, so year two costs the same as year one. Whether that holds depends on the code staying active on your account, which is why the first invoice is worth a look — more on that below.

What follows: the full plan table with current list prices, the one plan most readers should buy, where to type the code, the actual twelve-month cost, and the cases where Evoxt is the wrong buy.

> **Quick pick:** take **VM-1** and enter **EVOXT595** at checkout. $5.99 drops to about **$3.59/mo** for 1 vCore at up to 6.0 GHz, 2 GB RAM, 20 GB NVMe and 1 TB transfer, with weekly offsite backups included.
> 👉 [Deploy VM-1 with the discount applied](https://bit.ly/EvoXt)

## All Evoxt plans and prices

These are the list prices shown on Evoxt's own pricing page. The discount is applied separately in the cart, so the numbers in this table are what you pay before the code.

| Plan | vCore / RAM | Storage | Transfer (Standard) | Price/mo | Order |
| --- | --- | --- | --- | --- | --- |
| VM-0.5 | 1 core / 512 MB | 5 GB | 500 GB | $2.99 | [Order VM-0.5](https://bit.ly/EvoXt) |
| VM-0.75 | 1 core / 1 GB | 10 GB | 750 GB | $4.99 | [Order VM-0.75](https://bit.ly/EvoXt) |
| VM-1 | 1 core / 2 GB | 20 GB | 1,000 GB | $5.99 | [Order VM-1](https://bit.ly/EvoXt) |
| VM-1.5 | 2 cores / 2 GB | 20 GB | 1,500 GB | $6.95 | [Order VM-1.5](https://bit.ly/EvoXt) |
| VM-2 | 2 cores / 4 GB | 30 GB | 2,000 GB | $11.99 | [Order VM-2](https://bit.ly/EvoXt) |
| VM-3 | 4 cores / 4 GB | 30 GB | 3,000 GB | $14.99 | [Order VM-3](https://bit.ly/EvoXt) |
| VM-4 | 4 cores / 8 GB | 60 GB | 4,000 GB | $23.99 | [Order VM-4](https://bit.ly/EvoXt) |
| VM-6 | 8 cores / 8 GB | 60 GB | 5,000 GB | $29.99 | [Order VM-6](https://bit.ly/EvoXt) |
| VM-8 | 8 cores / 16 GB | 80 GB | 6,000 GB | $47.99 | [Order VM-8](https://bit.ly/EvoXt) |
| VM-12 | 16 cores / 16 GB | 80 GB | 8,000 GB | $60.95 | [Order VM-12](https://bit.ly/EvoXt) |
| VM-16 | 16 cores / 32 GB | 100 GB | 10 TB | $95.99 | [Order VM-16](https://bit.ly/EvoXt) |

Every plan ships with a 1 Gbps port, IPv4 plus IPv6, weekly offsite backups at no extra cost, and one-click app installs. Billing runs monthly through to three years, and you can top up account credit rather than paying per invoice.

Here is what the 40% code does to the plans it covers:

| Plan | List price | With a 40% recurring code |
| --- | --- | --- |
| VM-1 | $5.99 | ~$3.59 |
| VM-1.5 | $6.95 | ~$4.17 |
| VM-2 | $11.99 | ~$7.19 |
| VM-3 | $14.99 | ~$8.99 |
| VM-4 | $23.99 | ~$14.39 |
| VM-6 | $29.99 | ~$17.99 |
| VM-8 | $47.99 | ~$28.79 |
| VM-12 | $60.95 | ~$36.57 |
| VM-16 | $95.99 | ~$57.59 |

## The 60-cent gap that decides most purchases

VM-0.5 at $2.99 is the cheapest thing Evoxt sells, and every write-up of these codes says the same thing: it doesn't take the percentage discount. That's fine, it's already the floor price. But put it next to VM-1 with the code and the comparison stops being close.

VM-0.5 gives you 512 MB RAM, 5 GB storage and 500 GB of transfer for $2.99. VM-1 with `EVOXT595` gives you 2 GB RAM, 20 GB storage and 1 TB of transfer for about $3.59. The difference is **$0.60 a month**, or $7.20 a year, and it buys four times the memory, four times the disk and twice the bandwidth.

512 MB is enough for a single small bot, a DNS resolver, a WireGuard endpoint or a monitoring agent. It is not enough for a WordPress install with plugins, a Node app with a real dependency tree, or MySQL alongside anything else. If there's any chance the box will end up hosting a site, skip VM-0.5 and take VM-1.

VM-0.75 sits in an awkward spot. The code descriptions name VM-1 and above as eligible and single out VM-0.5 as excluded, without saying anything about VM-0.75 either way, so I won't claim it works or doesn't. The arithmetic makes the question mostly moot: VM-0.75 lists at $4.99 with 1 GB RAM, which is more than VM-1 costs with the code, at $3.59 with double the memory. Order VM-1.

Above VM-1, the choice comes down to how many cores and how much memory your workload actually touches:

- **VM-2, $11.99 or about $7.19 with the code.** 2 cores, 4 GB RAM, 30 GB storage, 2 TB transfer. This is the tier for two or three small sites sharing a box, or a site plus a database that doesn't like being starved of memory.
- **VM-3, $14.99 or about $8.99.** Same 4 GB of RAM as VM-2 but 4 cores and 3 TB of transfer. Worth the extra $1.80 if you're running builds, crawlers, game servers or anything that spawns threads.
- **VM-4 and up.** 8 GB RAM at $23.99 (about $14.39 with the code) is where multi-tenant Docker setups and mid-size databases start to make sense. Below that, you're buying headroom you probably won't use.

## Three codes, one behaviour, and where to paste them

`EVOXT595`, `BHW595` and `AFF1129-hostspot` are interchangeable in practice. All three are described as 40% recurring on VM-1 and higher. The only difference in the documentation is that `BHW595` is also advertised alongside a $5.95/mo entry plan, and that's a plan-level promotion rather than a discount you'd get from the other two codes.

Rules that apply whichever one you use:

1. One code per order. You can't stack `EVOXT595` on top of `BHW595` for 80% off.
2. A code can be applied on top of a plan that already carries promotional pricing, so you're not choosing between the sale price and the code.
3. The discount shows up in the order total immediately after you click Apply. If it doesn't, the code isn't valid for that plan in that session.

The checkout flow, in the order you'll hit it: pick a plan, choose your region and OS, set the billing cycle, then look for the **"Promotional Code"** field on the checkout page. Type the code, click **Apply**, and confirm the total changed before you pay. Several users have noted that the code field is easy to miss on the way through checkout, so slow down on that screen.

Payment methods are card, PayPal, Bitcoin and USDT on Tron. Monthly billing works fine with a recurring code; there's no need to prepay a year to lock the rate.

👉 [Start a VM-1 order and paste EVOXT595 at checkout](https://bit.ly/EvoXt)

## What twelve months actually costs

VM-1 at list price runs $71.88 a year. With a 40% recurring code it runs about **$43.08**, a saving of roughly $28.80 in year one. If the discount keeps applying, year two is another $43.08 rather than a jump back to $71.88, which is where the recurring part earns its keep.

The honest caveat: some users have reported billing inconsistencies around renewals, according to a third-party write-up of the offer. That doesn't mean the discount disappears, but it does mean you should check the second invoice rather than assume. Keep the order confirmation email with the code and the discounted total in it; if a renewal comes through at full price, that email is your support ticket.

Evoxt is a Malaysian company founded in 2020, so its track record is shorter than Hostinger's or IONOS's. For a side project or a small production site that's a manageable risk. For something you'd be paged about at 3 a.m., factor it in.

👉 [Lock in the recurring rate on VM-1](https://bit.ly/EvoXt)

## Adding resources costs more than moving up a plan

Evoxt sells add-ons individually: extra vCore at $3/mo, extra RAM at $2/GB/mo, extra IPv4 at $3/mo, extra transfer at $3/TB on Standard, $12/TB on Premium and $24/TB on Premium Plus. Those unit prices are reasonable on their own. Combined, they're a worse deal than the next plan up, and the gap is easy to calculate.

Say you're on VM-1 at $5.99 and decide you need a second core. Adding one vCore costs $3, taking you to $8.99/mo. VM-1.5, which has 2 cores, 2 GB RAM, 20 GB storage and 1,500 GB transfer, lists at $6.95 and comes to about $4.17 with the code. You pay roughly $4.80 a month more for the add-on than for the upgrade, and the upgrade also brings 500 GB of extra transfer.

Memory works out differently. Adding 2 GB of RAM to VM-1 costs $4, bringing it to $9.99/mo with one core and 2 GB of transfer. VM-2 at $11.99 (about $7.19 with the code) gives you 2 cores, 4 GB RAM, 30 GB storage and 2 TB transfer. So the RAM add-on is cheaper in absolute terms if memory is your only bottleneck and one core genuinely handles your load. The moment you also want a core or more bandwidth, VM-2 wins on both price and specs.

The rule: use add-ons for IP addresses and burst storage, not for cores or memory you'll keep paying for every month.

## Regions, network tiers and the transfer trade-off

Evoxt runs 16 data centers across the US, Canada, the UK (London), Germany, the Netherlands (Amsterdam), Poland, Australia, Malaysia (both a Standard and a Premium location), Hong Kong, Japan (Tokyo and Osaka) and South Korea.

Three network tiers sit behind those locations, and they cost the same as each other. What changes is how much transfer you get and what overage costs. Standard gives you the full allowance listed in the table above and charges $3/TB beyond it. Premium, which covers the Asia-optimised routes including Hong Kong's CN2 path plus Tokyo and Osaka, comes with a smaller allowance and $12/TB overage. Premium Plus, aimed at Malaysian local ISP peering, is smaller again at $24/TB.

If your audience is in mainland China, Hong Kong or Japan, the Premium locations are the reason to pick Evoxt over a generic US-only budget host, and the reduced transfer allowance is the price of that routing. Check your expected monthly egress before you commit to a Premium region on a small plan. A 500 GB allowance on a Premium VM-1 disappears quickly under video or large static assets.

## Who shouldn't buy this

Ticket support runs 4 to 8 hours at busy times. Discord and Telegram tend to move faster, and for a hobby box that's fine, but if you need a 30-minute response on a production outage, this isn't the provider for that.

Dedicated servers exist but are currently limited to Malaysia, starting at $169/mo, so anyone shopping for bare metal elsewhere is out of luck for now.

One third-party review mentions a full refund if you cancel within 24 hours of deployment. I couldn't find that confirmed in an official policy page, so treat it as unconfirmed and ask support before you order if the refund window matters to you.

## How it stacks up against the usual alternatives

Rough positioning, all from published pricing rather than hands-on testing:

|  | Evoxt | Hostinger | RackNerd | IONOS |
| --- | --- | --- | --- | --- |
| Entry price | $2.99/mo | $4.99/mo intro | $2.99/mo promo | $2.00/mo |
| Renewal | No hike | Roughly doubles, ~$9.99/mo on most plans | Locked during promo term | Stable |
| CPU clock | Up to 6.0 GHz | ~3.5 GHz | Varies | Varies |
| Recurring discount | Yes, 40% with code | First term only | Promo-based | No |
| Free backups | Weekly, included | Weekly, daily costs extra | Not standard | Not standard |
| Crypto payment | Yes | No | No | No |
| Locations | 16 | 6 regions | Mainly US | EU and US |

Hostinger's intro price is attractive until the renewal lands. IONOS is cheaper at entry but has no recurring code. RackNerd is a US-centric option with promo-based pricing. Evoxt's edge is the combination of high clock speed, a recurring discount and Asian locations in one place.

Third-party benchmark site VPSBenchmarks placed Evoxt second in its under-$25 category for 2025, with top-three finishes across several price brackets going back to 2022, and its February 2026 test of VM-1 found single-core performance in line with the advertised specs. One developer community comment sums up the reaction: *"I did not know VPS can be so fast at such prices."* Single-core speed is what most small web apps, bots and lightly-loaded databases actually feel.

## Picking in one line

- **Single bot, VPN endpoint, monitoring agent:** VM-0.5 at $2.99, no code needed.
- **WordPress, a small app, a staging box:** VM-1 with `EVOXT595`, about $3.59/mo.
- **Two or three sites, or a site plus a database:** VM-2 with the code, about $7.19/mo.
- **Builds, crawlers, game servers:** VM-3, about $8.99/mo.
- **Need a second core on VM-1?** Move to VM-1.5, don't buy the add-on.

Before you pay, confirm three things on the checkout screen: that the code field shows a reduced total, that the billing cycle is the one you intended, and that the region matches your audience's latency needs. Then check the first renewal invoice against your order confirmation.

👉 [Compare the plans and apply EVOXT595 at checkout](https://bit.ly/EvoXt)
