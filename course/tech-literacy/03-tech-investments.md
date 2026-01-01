# Episode 3: Technology Investments

**Estimated Time:** 25 Minutes

> "The best time to plant a tree was 20 years ago. The second best time is now. But sometimes you should just buy a tree." — Modified proverb

Every technology decision is an investment. Build the wrong thing, and you waste months. Buy the wrong tool, and you're locked into someone else's roadmap. This episode helps you make these calls wisely.

## Part 1: Build vs. Buy — The Eternal Question

Almost every technology decision involves this trade-off:

| Factor | Build | Buy |
| :--- | :--- | :--- |
| **Upfront Cost** | Engineering time | License/subscription fees |
| **Ongoing Cost** | Maintenance, updates | Vendor fees, integration updates |
| **Time to Value** | Slower (months) | Faster (weeks/days) |
| **Customization** | Total control | Limited to vendor features |
| **Risk** | You own all bugs | Vendor dependency |
| **Core Competency** | Builds internal capability | Frees team to focus on core product |

### The Decision Framework

**Build when:**
- It's core to your differentiation (your "secret sauce")
- No vendor solution fits your needs
- You need complete control over the roadmap
- Long-term economics favor ownership

**Buy when:**
- It's a commodity (auth, payments, email)
- Speed to market matters more than customization
- A vendor has solved this problem well
- Maintaining it would distract from your core product

### 📺 Watch This (10 mins)
[Stripe: How to Think About Build vs. Buy](https://www.youtube.com/watch?v=_9Y7Wm8F62g)
*Focus on: The true cost of building and maintaining software.*

## Part 2: Evaluating Vendor Proposals

When vendors pitch you technology, use this evaluation framework:

| Dimension | Questions to Ask |
| :--- | :--- |
| **Fit** | Does this solve our actual problem? Do we need all these features? |
| **Integration** | How does this connect to our existing systems? What's the integration effort? |
| **Lock-in** | How hard is it to switch if this doesn't work out? Can we export our data? |
| **Pricing** | How does pricing scale with our usage? What's the 2-year cost at 5x growth? |
| **Support** | What SLA do they offer? What's the experience of similar-sized companies? |
| **Roadmap** | Where is this product going? Does the vendor's direction align with ours? |
| **Security** | What's their security posture? SOC2? Penetration testing? |

### Red Flags in Vendor Pitches

| Red Flag | Why It's Concerning |
| :--- | :--- |
| Won't share reference customers | May have poor retention |
| Opaque pricing | Hidden costs will emerge later |
| No data export | You're locked in forever |
| Customizations require professional services | Basic changes will be expensive |
| Startup selling to enterprises without SOC2 | Security may be immature |

### 📖 Read This (8 mins)
[First Round: A Founder's Guide to Enterprise Sales (from the buyer side)](https://review.firstround.com/the-founders-guide-to-selling-to-enterprises)
*Flip the script: understand how vendors are selling to you.*

## Part 3: Technical Debt — The Invisible Tax

Technical debt is one of the most important concepts for CEOs to understand.

### What Is Technical Debt?

| Concept | Financial Metaphor | Software Reality |
| :--- | :--- | :--- |
| **Debt** | Borrowing money | Taking shortcuts to ship faster |
| **Interest** | Monthly payments | Slower development, more bugs |
| **Principal** | Original loan amount | Effort to fix the shortcuts |
| **Bankruptcy** | Can't make payments | System is unmaintainable |

### Why Teams Accumulate Debt

- Tight deadlines ("Just ship it, we'll fix it later")
- Changing requirements (what we built no longer fits)
- Learning (we didn't know better at the time)
- Complexity growth (small hacks that compound)

### Signs Your Tech Debt Is Dangerous

| Warning Sign | What It Means |
| :--- | :--- |
| Simple features take months | Debt is slowing everything down |
| Lots of bugs in production | System is fragile |
| Engineers are frustrated | Good people will leave |
| "It's too risky to change" | System is becoming unmaintainable |
| No one understands the codebase | Knowledge debt compounding |

### How to Manage Tech Debt as CEO

1. **Acknowledge it exists** — Ask your CTO for an honest assessment
2. **Allocate capacity** — 15-20% of engineering time on debt reduction
3. **Make it visible** — Include debt metrics in engineering reviews
4. **Celebrate payoff** — Recognize engineers who reduce debt

## Part 4: Platform vs. Features

A critical strategic decision: When do you invest in platform (infrastructure, tooling, scalability) vs. features (customer-facing capabilities)?

| Invest in Platform When | Invest in Features When |
| :--- | :--- |
| Scaling is becoming painful | You're still finding product-market fit |
| Development is slowing due to tech debt | Customers need specific capabilities |
| You're hiring and onboarding engineers | You need to grow revenue quickly |
| Stability/reliability is becoming critical | Competitor pressure is high |

### The Platform Investment Trap

Early-stage startups sometimes over-invest in platform ("Let's build it right from the start"). This is usually a mistake. Until you have product-market fit, building a scalable platform is building for a future that may never arrive.

**Rule of thumb:** Build for 3-5x your current scale. Not 100x.

### 📺 Watch This (8 mins)
[Krazam: Microservices (Satire)](https://www.youtube.com/watch?v=y8OnoxKotPQ)
*Humor with truth: why premature platform investment is dangerous.*

## CEO Action Item: Review a Build-vs-Buy Decision

Take 20 minutes to analyze a recent or upcoming technology decision:

1. **Pick one technology decision** your team is facing (or recently made)
2. **Apply the Build vs. Buy framework:**
   - Is this core to our differentiation?
   - What's the true cost of building (including maintenance)?
   - What's the true cost of buying (including lock-in risk)?
3. **If buying, run the vendor evaluation framework** — identify any red flags
4. **Schedule a discussion with your CTO** to review this decision together

**Document your thinking.** Building a habit of rigorous technology evaluation pays dividends.

---
**[Next Episode: Agile & Product Development →](04-agile-product-dev.md)**
