# Comparison Article Framework

## Description
Build a comprehensive comparison article structure and content for comparing 3+ products, services, or approaches. Includes fair analysis, scoring systems, and clear recommendations for different reader personas.

## Prompt Text
```
You are an expert comparison writer who provides fair, thorough, unbiased analyses.

I'm comparing: [ITEM 1], [ITEM 2], [ITEM 3], [and ITEM 4 if applicable]
Context/Category: [e.g., "project management tools for remote teams"]
Target audience: [DESCRIBE - e.g., "small business owners with 5-20 employees, non-technical"]
Key comparison dimensions: [e.g., "price, ease of use, integrations, reporting"]

Create a comprehensive comparison framework that includes:

1. **Comparison Grid**: A simple comparison table of [ITEMS] across these dimensions:
   - Each key dimension (3-5 max)
   - Scoring: Simple 1-5 scale (1=poor, 5=excellent)
   - Mark any stand-out features with 🌟

2. **Detailed Analysis Per Item** (2-3 paragraphs each):
   - What it does best
   - Who it's designed for
   - Major limitations
   - Real-world use case example

3. **Winner by Use Case** (1 sentence each):
   - Best for [specific scenario, e.g., "bootstrapped startups"]
   - Best for [specific scenario, e.g., "enterprise teams"]
   - Best overall value
   - Best for [specific scenario, e.g., "creative agencies"]

4. **Pros/Cons Sidebar** for each item:
   - 3 pros
   - 3 cons

5. **Decision Tree or Recommendation Matrix**:
   - "Choose [ITEM 1] if you need X, Y, and Z"
   - "Choose [ITEM 2] if you prioritize A, B, and C"
   - (Similar for each item)

Format as blog-ready text that feels fair and helpful, not sales-y.
```

## Example Input
**Comparing:** Notion, Asana, Monday.com  
**Category:** Project management for creative teams  
**Target Audience:** Design agencies with 10-30 people  
**Key Dimensions:** Price, ease of onboarding, design collaboration, reporting/analytics, integrations

## Example Output
```
# Notion vs. Asana vs. Monday.com: Which Project Management Tool is Right for Your Creative Team?

## Quick Comparison Grid

| Dimension | Notion | Asana | Monday.com |
|-----------|--------|-------|-----------|
| **Price (per user/month)** | $10-15 | $10.99-24.99 | $12-24 |
| **Ease of Setup** | 3/5 (steep learning) | 4/5 (intuitive) | 4.5/5 (drag-and-drop) |
| **Design Collaboration** | 3.5/5 (limited) | 4/5 (good) | 4.5/5 (excellent) 🌟 |
| **Reporting/Analytics** | 3/5 (basic) | 5/5 (comprehensive) | 4/5 (very good) |
| **Integration Ecosystem** | 4.5/5 🌟 | 4/5 | 4/5 |

## Detailed Analysis

### Notion
Notion is the Swiss Army knife of productivity tools—a flexible, all-in-one workspace. You can use it for projects, wikis, databases, and more. For creative teams, this flexibility is both a blessing and a curse.

What it does best: Custom workflows and unlimited flexibility. If your team has unique processes, Notion can adapt. It's also the most affordable option long-term, especially if you use it for multiple functions (projects + documentation + asset management).

Best for: Creative teams that want a fully customized workspace and don't mind the learning curve. Perfect if you already use Notion for documentation.

Limitation: The onboarding is steep. Expect 2-4 weeks before your team feels productive. Design collaboration features are barebones—files live in databases but reviewing isn't visual or intuitive.

Real-world example: A 15-person design studio uses Notion as their project hub, linking to Figma files in a custom database. Once set up, it works beautifully, but the initial three-week setup was painful.

**Pros:**
- Lowest cost ($10/month vs. $12-25 elsewhere)
- Highly customizable databases and workflows
- Excellent for cross-functional work (projects + wiki + CRM in one place)

**Cons:**
- Steep learning curve; long onboarding
- Design collaboration features are weak
- Performance can lag with large teams or complex databases

---

### Asana
Asana is built for project management with a human-centered interface. It feels like the most "professional" tool in this group—polished, intuitive, and structured around project workflows.

What it does best: Organization and visibility. Asana's timeline (Gantt), board (Kanban), and list views are all excellent. Teams see dependencies, deadlines, and who owns what instantly. Reporting is the strongest here—customizable dashboards show progress in real time.

Best for: Teams that want a structured, proven project management tool with strong reporting. Works well for mixed teams (designers + PMs + developers).

Limitation: Less flexible than Notion. You're working within Asana's opinionated workflow model. Design collaboration is good but not specialized—you're still managing iterations through comments and attachments.

Real-world example: A 20-person creative agency uses Asana for all client projects. The timeline view helps PMs manage handoffs; the reporting dashboard shows billable hours and project profitability instantly.

**Pros:**
- Intuitive interface; teams are productive on day 1
- Strong reporting and project visibility
- Excellent for managing timelines and dependencies

**Cons:**
- Pricier than Notion for long-term (especially scaling)
- Limited integrations compared to some competitors
- Not as customizable if you need unique workflows

---

### Monday.com
Monday.com is the "visually delightful" option. It's built for creative teams who want something that looks good and feels easy.

What it does best: Visual design and ease of use. Monday's interface is genuinely beautiful. Setup is drag-and-drop; your team starts collaborating day one. Design collaboration is also strongest here—file uploads, commenting, and version tracking are baked in.

Best for: Creative teams prioritizing ease of use and design-focused collaboration. If your team's technical comfort is mixed, this is safest.

Limitation: It's the most expensive. Pricing starts at $12/user but scales quickly. Customization is good but not as deep as Notion. Reporting is solid but less powerful than Asana.

Real-world example: A 12-person branding agency switched from Monday.com and loved the onboarding. Designers could upload work, clients could review, and everyone could comment—all within Monday—eliminating email feedback loops.

**Pros:**
- Most beautiful UI; zero learning curve
- Design collaboration features are excellent
- Flexible automation and integration options

**Cons:**
- Most expensive at scale
- Less robust reporting than Asana
- Can feel "too colorful" for serious enterprise work

---

## Winner by Use Case

- **Best for bootstrapped startups:** Notion ($10/month, unlimited customization)
- **Best for design collaboration:** Monday.com (file uploads and version tracking are native)
- **Best for project visibility/reporting:** Asana (dashboards and timeline views are unmatched)
- **Best overall value:** Asana (balance of features, price, and ease of use)

---

## Decision Tree: Which One Should You Pick?

**Choose Notion if:**
- You need project management + documentation in one place
- Your budget is tight (under $500/month for your team)
- You're willing to invest 3-4 weeks in setup and customization
- You're comfortable with a learning curve

**Choose Asana if:**
- You want the most intuitive, out-of-the-box experience
- Project visibility and reporting are critical
- Your team has a mix of disciplines (design, dev, product)
- You want a proven, popular tool (less risk)

**Choose Monday.com if:**
- Design collaboration and file review are your #1 priority
- Your team values beautiful, easy-to-use interfaces
- You don't need extensive customization
- Budget allows for ~$24/user at scale
```

## Pro Tips

**Tip 1: Show Your Scoring Methodology Upfront**  
Before comparing, say: "I tested each tool for X weeks with a Y-person team, evaluating on Z criteria. Here's how I scored..." This builds trust. Readers know you're not just guessing.

**Tip 2: Be Honest About Tradeoffs, Not Clear Winners**  
Avoid saying "Asana is objectively better." Instead: "Asana wins on reporting, Notion on customization." This shows nuance and builds credibility. Readers know different tools fit different needs.

**Tip 3: Include a Real-World Team Size in Your Example**  
Instead of generic examples, anchor to actual team sizes: "For a 15-person team..." or "For a solo creator..." This helps readers see themselves in your analysis.
