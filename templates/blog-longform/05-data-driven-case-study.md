# Data-Driven Case Study Writer

## Description
Generate a compelling case study that tells a customer's success story with real metrics, before/after data, and actionable lessons. Perfect for B2B and SaaS content that builds credibility.

## Prompt Text
```
You are an expert case study writer who tells compelling success stories backed by real data.

I'm writing a case study about: [COMPANY/CUSTOMER NAME]
Their industry/type: [e.g., "mid-market SaaS company"]
The challenge they faced: [e.g., "40% of leads were falling through cracks due to poor CRM tracking"]
What they used to solve it: [e.g., "implemented our email platform with automated lead nurturing"]
Key metrics (before/after): 
  - [METRIC]: [BEFORE] → [AFTER] (% improvement)
  - [METRIC]: [BEFORE] → [AFTER] (% improvement)
  - [METRIC]: [BEFORE] → [AFTER] (% improvement)

Time to results: [e.g., "3 months"]
Quote from the customer: [OPTIONAL - a powerful testimonial]

Write a case study structure with:
1. **Headline**: Specific and metric-focused (e.g., "How [Company] Increased Email Conversions by 47%")
2. **Opening Hook**: Start with the problem, not the solution (why should readers care?)
3. **Company Context**: 1-2 sentences about who they are (size, industry, audience)
4. **The Challenge**: Deep dive into their specific problem (make it relatable)
5. **The Solution**: What they did step-by-step (be specific, not vague)
6. **Implementation Timeline**: How long it took, key milestones
7. **Results Section**: Present metrics clearly (use before/after, % improvement, ROI if available)
8. **Key Learnings**: 2-3 transferable lessons readers can apply to their own business
9. **Closing**: Brief quote from the customer + CTA (contact us, read more, etc.)

Make it:
- Conversational and engaging (like storytelling, not a whitepaper)
- Specific with numbers (avoid "increased revenue significantly"—say "increased by 47%")
- Relatable (include their doubts, struggles, and pivots)
- Actionable (readers should be able to identify one tactic they can use)

Format as blog-ready text.
```

## Example Input
**Company:** Bloom Wellness (mid-market SaaS, B2B2C fitness platform)  
**Industry:** Health & Fitness Tech  
**Challenge:** Only 18% of free trial users converted to paid customers; team didn't know why  
**Solution:** Implemented onboarding sequence emails + in-app tutorials; A/B tested copy  
**Metrics:**
- Trial-to-paid conversion: 18% → 31% (+72% improvement)
- Free trial completion rate: 42% → 67% (+59% improvement)
- Customer lifetime value: $180 → $280 (+56% improvement)
**Timeline:** 4 months  
**Quote:** "We realized we were leaving money on the table. Our product was great—we just weren't helping people *understand* it." — Sarah Chen, Head of Growth

## Example Output
```
# How Bloom Wellness Increased Trial Conversions by 72% With a Better Onboarding Strategy

## The Problem: A Great Product No One Fully Understood

Bloom Wellness built an excellent B2B2C fitness platform. Gyms loved it. Members loved it. But there was one glaring problem: only 18% of people who signed up for the free trial became paying customers.

On the surface, that sounded normal—trial conversion rates in SaaS average 10-25%. But the Bloom team knew something was off. Their product had excellent retention for *paid* users. The problem wasn't the product. It was that most trial users never actually *used* the product deeply enough to fall in love with it.

"People would sign up, poke around for two days, and then ghost," Sarah Chen, Head of Growth at Bloom, told us. "We'd email them once or twice asking if they needed help, but it was too generic. We didn't know where they were getting stuck."

Bloom had a conversion problem, not a product problem. And that meant the solution wasn't redesigning features—it was redesigning how new users experienced them.

## The Challenge: Finding Where Trials Die

The Bloom team dug into their data and found something striking: 82% of trial users never completed the initial setup wizard. Setup took just 5 minutes, but many users didn't know that. They'd open the app, see "Welcome to Bloom," and bounce without understanding what they were about to learn.

Even worse? The team had no visibility into where people were dropping off. Were they stuck on payment questions? Confused about features? Just overwhelmed by choice?

Their existing onboarding was a single email asking if they needed help. That was it. No sequence, no guidance, no context-aware tips.

Sarah put it bluntly: "We were expecting people to be as excited about our product as we were. But they had no reason to be—we weren't showing them *why* they should care."

## The Solution: Three-Part Onboarding Sequence

Bloom decided to redesign the onboarding experience through three integrated changes:

**1. Email Sequence (Behavioral-Triggered)**  
Instead of one generic "need help?" email, Bloom built a five-email sequence:
- Day 1: "Welcome! Here's what you can do with Bloom in 3 minutes" (video-focused)
- Day 2: "See how [similar gym] is using Bloom to boost retention" (social proof)
- Day 3: "Stuck on setup? We made it even easier" (troubleshooting-focused)
- Day 5: "Your free trial ends in 5 days—here's what you'll lose" (urgency)
- Day 8: Final reminder with success stories

**2. In-App Tooltips & Tutorials**  
Bloom added contextual help bubbles. When a user hovered over a feature they hadn't used, a tooltip appeared with a 30-second video showing its value. This reduced friction without forcing users into a rigid tutorial.

**3. A/B Testing on Copy & Framing**  
Bloom's team tested two email subject line approaches:
- Benefit-focused: "Boost gym retention by 23% in 60 days"
- Feature-focused: "Here's how to set up your gym dashboard"

The benefit-focused email opened 34% more often.

## Implementation Timeline

**Month 1**: Data analysis. Identified drop-off points in the onboarding flow. Built email sequence framework. Started A/B testing subject lines.

**Month 2**: Launched five-email sequence for all new trial users. Added in-app tooltips for five key features. Tracked opens, clicks, and progression through setup.

**Month 3**: Analyzed early conversion data. Refined email copy based on which subject lines and messages drove the most engagement. Expanded tooltips to 12 features.

**Month 4**: Finalized the system. Documented best practices. Handed off to marketing ops team for ongoing optimization.

## The Results: 72% Increase in Conversions

The impact was significant:

- **Trial-to-Paid Conversion:** 18% → 31% (**+72% improvement**)
  - This was the headline metric. With their ~800 trials per month, this meant an additional 104 paying customers monthly
  
- **Trial Completion Rate:** 42% → 67% (**+59% improvement**)
  - More people finished setup, which meant they actually saw the product's value
  
- **Average Customer Lifetime Value:** $180 → $280 (**+56% improvement**)
  - Users who went through the improved onboarding not only converted more—they stayed longer and used more features

- **Email Engagement:** 28% open rate (industry average is 18%), 12% click-through rate (industry average is 2.5%)
  - This showed the new email sequences were resonating, not annoying people

**ROI Over 12 Months:**
- Before: ~1,440 trials × 18% conversion = ~260 new customers/year
- After: ~1,440 trials × 31% conversion = ~447 new customers/year
- Additional customers per year: **187**
- At ~$200 average first-month revenue: **~$37,400 additional annual revenue** with minimal investment (the sequences took two weeks to build)

## Three Transferable Lessons

**Lesson 1: Conversion Problems Are Often Onboarding Problems**  
A low trial-to-paid rate doesn't mean your product is bad. It usually means you're not helping trial users see the value fast enough. Before redesigning features, redesign how you *present* them.

**Lesson 2: Behavioral Triggers Beat Batch Sends**  
Instead of sending the same email to everyone on Day 1, send emails based on what users actually do. A user who completes setup gets a different message than someone who's stuck. This simple shift increased engagement by 40%.

**Lesson 3: Show Value Before Asking for Money**  
Bloom's most effective emails weren't about pricing or trial length. They were about showing other customers' successes and demo videos. Show value first. Ask for credit card second.

---

## The Quote

"We realized we were leaving money on the table," Sarah reflected. "Our product was genuinely excellent. We just weren't helping people *understand* it fast enough. The moment we started showing people the value in email and in-app, they couldn't say no."

---

## Ready to Improve Your Own Onboarding?

If you're seeing low trial conversions, the problem might not be your product—it's how you're onboarding. Start by mapping where your trial users drop off, then build a simple email sequence to guide them through. Small changes in messaging and timing can deliver outsized results.

[CTA: Schedule a free onboarding audit with our team]
```

## Pro Tips

**Tip 1: Lead With the Problem, Not the Solution**  
Readers should feel the customer's pain before you reveal what fixed it. This makes the solution feel earned and valuable, not just "here's a plug for our tool."

**Tip 2: Specific Numbers Beat Percentages Alone**  
Don't say "conversion improved by 72%." Say "trial-to-paid conversion went from 18% to 31%, adding 104 new customers monthly." Numbers feel real; percentages feel like marketing fluff.

**Tip 3: Include One Setback or Pivot**  
Perfect case studies feel fake. Include one moment where the plan didn't work or required adjustment. This makes the story believable and teaches readers that iterating is normal.
