# Episode 4: Agile & Product Development

**Estimated Time:** 25 Minutes

> "Plans are worthless, but planning is everything." — Dwight D. Eisenhower

If your engineering team uses terms like "sprints," "retrospectives," and "story points," they're practicing Agile. Understanding these methodologies helps you set realistic expectations, support your teams, and avoid common frustrations.

## Part 1: Agile vs. Waterfall — What Changed

### The Old Way: Waterfall

In waterfall development, you plan everything upfront, then build, then test, then ship:

```
[Requirements] → [Design] → [Build] → [Test] → [Deploy]
     ↓               ↓          ↓         ↓          ↓
  Months          Months     Months    Months     Launch
```

**The problem:** By the time you ship, the market has changed, and you've built the wrong thing.

### The New Way: Agile

In Agile, you ship small increments continuously, learning as you go:

```
[Plan] → [Build] → [Ship] → [Learn] → [Plan] → [Build] → [Ship] → ...
           2-4 weeks              2-4 weeks
```

**The benefit:** You course-correct continuously instead of betting everything on one big release.

### 📺 Watch This (8 mins)
[Atlassian: Agile Explained](https://www.youtube.com/watch?v=Z9QbYZh1YXY)
*A clear, visual explanation of Agile principles.*

## Part 2: Scrum Basics

Scrum is the most common Agile framework. Here's the vocabulary:

| Term | What It Is | Duration |
| :--- | :--- | :--- |
| **Sprint** | A fixed time period to complete work | 1-4 weeks (usually 2) |
| **Sprint Planning** | Meeting to decide what to build this sprint | 1-2 hours |
| **Daily Standup** | Brief sync on progress and blockers | 15 minutes |
| **Sprint Review** | Demo what was built | 1 hour |
| **Retrospective** | Team reflects on what to improve | 1 hour |
| **Product Backlog** | List of all work to be done | Ongoing |
| **Sprint Backlog** | Work committed for this sprint | 2 weeks |

### The Sprint Cycle

```
Week 1                                Week 2
┌─────────────────────────────────────────────────────────┐
│ Planning → Daily Work → Daily Work → Review → Retro   │
│     ↓          ↓             ↓          ↓        ↓     │
│  Commit    Build/Test    Build/Test   Demo    Improve  │
└─────────────────────────────────────────────────────────┘
                          ↓
                   Start Next Sprint
```

## Part 3: Why Estimates Are Hard

CEOs often get frustrated with engineering estimates. Understanding why estimates are uncertain helps you ask better questions.

### Why Software Estimates Fail

| Reason | Explanation |
| :--- | :--- |
| **Unknown unknowns** | We discover complexity while building |
| **Dependencies** | Waiting on other teams, APIs, decisions |
| **Scope creep** | Requirements change mid-sprint |
| **Optimism bias** | Humans underestimate by 2-3x on average |
| **Context switching** | Interruptions kill productivity |

### How to Think About Estimates

| Don't Say | Do Say |
| :--- | :--- |
| "Why was this late?" | "What did we learn that we didn't know before?" |
| "Give me a firm deadline" | "What's the range? Best case, worst case, most likely?" |
| "This can't take that long" | "Help me understand what makes this complex" |
| "Why can't you estimate better?" | "What could we do to reduce uncertainty for next time?" |

### Story Points: A Brief Explanation

Many teams use "story points" instead of hours. Story points measure relative complexity, not time.

| Task A | Task B | Comparison |
| :--- | :--- | :--- |
| 2 points | 8 points | B is ~4x more complex than A |

**Why this works:** Humans are better at comparing than absolute estimation. Velocity (points completed per sprint) becomes predictable over time.

### 📖 Read This (10 mins)
[Shape Up: Appetite vs. Estimates](https://basecamp.com/shapeup/1.2-chapter-03)
*A different approach to estimation and scope from Basecamp.*

## Part 4: The Value of "Invisible" Work

Some of the most important engineering work doesn't produce visible features:

| Work Type | What It Is | Why It Matters |
| :--- | :--- | :--- |
| **Refactoring** | Restructuring code without changing behavior | Makes future changes faster/safer |
| **Testing** | Writing automated tests | Catches bugs before customers do |
| **Documentation** | Explaining how systems work | Helps new engineers ramp up |
| **Security hardening** | Fixing vulnerabilities | Prevents breaches |
| **Performance optimization** | Making things faster | Improves user experience |
| **Ops/DevOps** | Improving deployment and monitoring | Reduces outages and recovery time |

### The CEO's Role

- **Protect time for invisible work** — Allocate 15-25% of capacity
- **Celebrate it publicly** — "We just reduced page load time by 50%"
- **Ask about it** — "What invisible work are we deferring?"
- **Don't let it be the first thing cut** — When deadlines loom, this work suffers

### 📺 Watch This (10 mins)
[Continuous Delivery: Why Quality Matters](https://www.youtube.com/watch?v=4OI22dOB-7Q)
*Why investing in quality pays off.*

## Part 5: Beyond Scrum

Scrum isn't the only Agile methodology:

| Framework | Best For | Key Difference |
| :--- | :--- | :--- |
| **Scrum** | Most teams | Fixed sprints, defined roles |
| **Kanban** | Ops, support teams | Continuous flow, no sprints |
| **Shape Up** | Product-focused teams | 6-week cycles, more autonomy |
| **SAFe** | Large enterprises | Coordination across many teams |
| **Lean** | Startups | Minimize waste, maximize learning |

**CEO insight:** The methodology matters less than consistent execution. If your team is shipping regularly, learning from customers, and improving over time, the framework is working.

## CEO Action Item: Attend a Sprint Retrospective

Take 15 minutes to set this up, then 1 hour to participate:

1. **Ask your CTO or Engineering Manager** if you can observe the next sprint retrospective
2. **Just listen** — don't drive or make suggestions
3. **Note the themes:** What's working? What's frustrating the team?
4. **After the meeting,** ask yourself:
   - What surprised me?
   - What can I do as CEO to help address the team's concerns?
   - What invisible work is being deferred that I should advocate for?

**The goal:** Understand how your engineering team actually works, not how you assume they work.

---
**[Next Episode: Cybersecurity →](05-cybersecurity.md)**
