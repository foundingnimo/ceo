# Episode 1: The Tech Landscape

**Estimated Time:** 30 Minutes

> "Any sufficiently advanced technology is indistinguishable from magic." — Arthur C. Clarke

As a CEO, technology can feel like magic—or chaos. This episode demystifies the modern tech stack so you can have informed conversations with your engineering team.

## Part 1: The Modern Tech Stack Explained

Every software product has layers. Understanding these layers helps you ask better questions.

| Layer | What It Does | Examples | CEO Questions to Ask |
| :--- | :--- | :--- | :--- |
| **Frontend** | What users see and interact with | Web app, mobile app, UI | "How does our UX compare to competitors?" |
| **Backend** | Business logic and processing | APIs, servers, services | "Can our backend handle 10x users?" |
| **Database** | Stores and retrieves data | PostgreSQL, MongoDB | "How is our data backed up?" |
| **Infrastructure** | The foundation everything runs on | AWS, Azure, Kubernetes | "What's our uptime last quarter?" |

### The Stack Diagram

```
┌─────────────────────────────────────┐
│         Frontend (User Interface)   │  ← What users see
├─────────────────────────────────────┤
│         Backend (Business Logic)    │  ← Where decisions happen
├─────────────────────────────────────┤
│         Database (Data Storage)     │  ← Where data lives
├─────────────────────────────────────┤
│         Infrastructure (Cloud)      │  ← Where everything runs
└─────────────────────────────────────┘
```

### 📺 Watch This (10 mins)
[Fireship: 100+ Computer Science Concepts Explained](https://www.youtube.com/watch?v=-uleG_Vecis)
*Don't try to memorize everything—just get familiar with the vocabulary.*

## Part 2: Cloud Computing Fundamentals

Almost every modern company runs on cloud infrastructure. Here's what you need to know:

| Term | What It Means | Why CEOs Care |
| :--- | :--- | :--- |
| **IaaS** (Infrastructure as a Service) | Rent raw servers and storage | Maximum flexibility, but you manage everything |
| **PaaS** (Platform as a Service) | Rent a platform to build on | Faster development, less control |
| **SaaS** (Software as a Service) | Rent finished software | No development needed, subscription cost |

### The Big Three Cloud Providers

| Provider | Strengths | When to Consider |
| :--- | :--- | :--- |
| **AWS** (Amazon) | Broadest services, market leader | Default choice for most startups |
| **Azure** (Microsoft) | Enterprise integration, hybrid cloud | If you're a Microsoft shop |
| **GCP** (Google) | Data/ML capabilities, Kubernetes | If data/AI is your core product |

**CEO insight:** The choice between cloud providers is rarely critical. What matters more is having a clear cloud strategy and avoiding unnecessary complexity.

### 📖 Read This (8 mins)
[a16z: Understanding Cloud](https://a16z.com/2020/02/16/the-cloud/)
*Focus on: Why cloud changes the economics of building software.*

## Part 3: Key Terminology You'll Hear

| Term | Plain English | Example |
| :--- | :--- | :--- |
| **API** | A way for systems to talk to each other | "Our app uses Stripe's API for payments" |
| **Microservices** | Breaking an app into small, independent pieces | "Each team owns their microservice" |
| **Monolith** | One big application that does everything | "We started as a monolith but are breaking it up" |
| **Containerization** | Packaging software to run anywhere consistently | "We use Docker containers" |
| **Kubernetes (K8s)** | System for managing lots of containers | "Our K8s cluster runs 50 services" |
| **CI/CD** | Automated testing and deployment | "We deploy to production 10 times a day" |
| **Technical Debt** | Shortcuts that will need fixing later | "We have 6 months of tech debt to address" |

## Part 4: Questions Every CEO Should Ask Their CTO

Use these in your next engineering review:

1. **Architecture**: "Can you sketch our system on a whiteboard? Where are the biggest risks?"
2. **Scalability**: "If we 10x our users tomorrow, what breaks first?"
3. **Dependencies**: "What third-party services are we critically dependent on?"
4. **Technical Debt**: "Where are we accumulating tech debt? What's the payoff plan?"
5. **Security**: "When was our last security audit? What were the findings?"

### 📺 Watch This (12 mins)
[Jeff Lawson: Building Software with Superpowers](https://www.youtube.com/watch?v=6OEmqCJ2wJk)
*A developer's perspective on what non-technical leaders get wrong.*

## CEO Action Item: Map Your Tech Stack

Take 20 minutes to create your company's technology map:

1. **Draw the four layers** (Frontend, Backend, Database, Infrastructure)
2. **Fill in what you know** — what technologies are you using in each layer?
3. **Mark "I don't know"** for anything you're unsure about
4. **Schedule 30 minutes with your CTO** to complete the map together

Keep this map updated quarterly. It's your technical foundation.

---
**[Next Episode: Bridging Business & Tech →](02-bridging-business-tech.md)**
