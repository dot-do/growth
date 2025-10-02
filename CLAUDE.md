# growth/ - Growth Strategy & Go-to-Market

## Overview

This repository contains the **growth strategy, go-to-market plans, marketing research, and growth tactics** for the .do platform ecosystem (apps.do, apis.do, studio.do, services.do).

## Purpose

**Primary Goal**: Document and execute growth strategies to reach $200K ARR in 12 months

**Key Objectives**:
1. **Customer Acquisition** - Drive signups and conversions across all .do domains
2. **Revenue Growth** - Scale from $0 → $200K ARR in first year
3. **Market Positioning** - Establish .do as the AI-native platform for developers
4. **Community Building** - Grow engaged developer community (1000+ Discord members)
5. **Content Marketing** - Create 100+ tutorials, guides, and examples
6. **Product-Led Growth** - Optimize onboarding, activation, and retention

## Repository Structure

```
growth/
├── research/
│   ├── competitive-analysis.md    # Competitor research and positioning
│   ├── market-sizing.md            # TAM, SAM, SOM analysis
│   ├── customer-personas.md        # ICP and user personas
│   └── positioning-strategy.md     # Value props and messaging
│
├── gtm/
│   ├── launch-plan.md              # Phase-by-phase launch strategy
│   ├── pricing-strategy.md         # Pricing tiers and packaging
│   ├── sales-playbook.md           # Enterprise sales process
│   └── partner-strategy.md         # Partnerships and integrations
│
├── channels/
│   ├── content-marketing.md        # Blog, tutorials, SEO strategy
│   ├── community.md                # Discord, GitHub, events
│   ├── developer-relations.md      # DevRel, advocacy, champions
│   ├── paid-acquisition.md         # Ads, sponsorships, paid channels
│   └── product-led-growth.md       # In-product growth loops
│
├── campaigns/
│   ├── launch-campaigns/           # Launch campaign plans
│   ├── growth-experiments/         # A/B tests and experiments
│   └── retention-programs/         # Engagement and retention
│
├── metrics/
│   ├── kpis.md                     # Key performance indicators
│   ├── dashboards.md               # Analytics and reporting
│   ├── cohort-analysis.md          # Retention and LTV tracking
│   └── attribution.md              # Channel attribution model
│
├── playbooks/
│   ├── onboarding-optimization.md  # Activation improvements
│   ├── referral-program.md         # Referral mechanics
│   ├── viral-loops.md              # Built-in virality
│   └── retention-tactics.md        # Churn prevention
│
└── assets/
    ├── messaging/                  # Value props, taglines
    ├── creative/                   # Ad creative, visuals
    └── templates/                  # Email, landing pages
```

## Development Commands

```bash
# Research
pnpm research:competitive       # Run competitive analysis
pnpm research:market           # Market sizing research
pnpm research:personas         # Customer persona research

# Analysis
pnpm analyze:metrics           # Analyze growth metrics
pnpm analyze:cohorts           # Cohort retention analysis
pnpm analyze:attribution       # Channel attribution

# Campaigns
pnpm campaign:plan             # Plan new campaign
pnpm campaign:launch           # Launch campaign
pnpm campaign:analyze          # Analyze results

# Reports
pnpm report:weekly             # Weekly growth report
pnpm report:monthly            # Monthly performance
pnpm report:quarterly          # Quarterly business review
```

## Key Metrics (Target: 12 Months)

### Growth Metrics
- **Users**: 0 → 5,000 registered users
- **Apps**: 0 → 1,000 active apps deployed
- **APIs**: 0 → 100 in marketplace
- **Services**: 0 → 600 registered
- **ARR**: $0 → $200K

### Funnel Metrics
- **Visit → Signup**: 5% conversion
- **Signup → Activation**: 40% (create first app)
- **Activation → Paid**: 10% conversion
- **Free → Pro**: $29/mo, 10% conversion
- **Pro → Team**: $99/mo, 5% upgrade rate

### Engagement Metrics
- **DAU/MAU**: 30% (daily/monthly active)
- **Retention**: 70% Month 1 → Month 2
- **NPS**: 50+ (promoter score)
- **Weekly Active**: 50%+ of signups

### Channel Metrics
- **Organic**: 50% of signups (SEO, content)
- **Community**: 20% (Discord, GitHub)
- **Referral**: 15% (word of mouth)
- **Paid**: 10% (ads, sponsorships)
- **Direct**: 5% (brand, PR)

## Go-to-Market Strategy

### Phase 1: Foundation (Months 1-2)
**Focus**: Product-market fit, initial traction

**Tactics**:
- Create foundational content (docs, tutorials, guides)
- Build community infrastructure (Discord, GitHub Discussions)
- Launch beta with 100 hand-picked users
- Gather feedback, iterate quickly
- Establish metrics and tracking

**Target**: 100 signups, 10 paying customers, $1K MRR

### Phase 2: Launch (Months 3-4)
**Focus**: Public launch, content marketing

**Tactics**:
- ProductHunt launch (#1 Product of the Day)
- Hacker News post (top 5 front page)
- Launch blog post (technical deep-dive)
- Video tutorials (YouTube, Twitter)
- Community launch event (Discord AMA)

**Target**: 500 signups, 50 paying, $5K MRR

### Phase 3: Scale (Months 5-6)
**Focus**: Paid acquisition, partnerships

**Tactics**:
- Start paid ads (Twitter, Reddit, Google)
- Launch referral program (give $10, get $10)
- Partner with complementary tools (Cloudflare, Stripe)
- Conference talks and sponsorships
- Developer relations program

**Target**: 2,000 signups, 150 paying, $20K MRR

### Phase 4: Accelerate (Months 7-9)
**Focus**: Enterprise, product-led growth

**Tactics**:
- Enterprise sales outreach
- Advanced PLG loops (viral features)
- API marketplace promotion
- Case studies and success stories
- Ambassador/champion program

**Target**: 5,000 signups, 300+ paying, $50K MRR

### Phase 5: Optimize (Months 10-12)
**Focus**: Retention, LTV optimization

**Tactics**:
- Retention campaigns (email, in-app)
- Upsell/cross-sell automation
- White-label partnerships
- International expansion
- Platform ecosystem growth

**Target**: 5,000+ signups, 500+ paying, $200K ARR

## Marketing Channels

### 1. Content Marketing (50% of signups)
**Strategy**: SEO-optimized technical content

**Tactics**:
- 100+ blog posts (how-to, tutorials, deep-dives)
- Comprehensive documentation
- Video tutorials (YouTube channel)
- Open-source templates and examples
- Guest posts on dev blogs

**Budget**: $2K/mo (writers, SEO tools)
**Expected CAC**: $30

### 2. Community Building (20% of signups)
**Strategy**: Developer-first community

**Tactics**:
- Active Discord server (daily engagement)
- GitHub Discussions (technical support)
- Weekly office hours (live Q&A)
- Monthly hackathons (prizes, recognition)
- User-generated content (showcase)

**Budget**: $1K/mo (tools, prizes, swag)
**Expected CAC**: $20

### 3. Product-Led Growth (15% of signups)
**Strategy**: Built-in viral loops

**Tactics**:
- Referral program (give $10, get $10)
- Social sharing (deploy previews)
- API marketplace discovery
- Template gallery (forkable)
- Public app showcase

**Budget**: $500/mo (referral credits)
**Expected CAC**: $10

### 4. Developer Relations (10% of signups)
**Strategy**: Technical evangelism

**Tactics**:
- Conference talks (5+ per quarter)
- Workshop hosting (hands-on training)
- Live streaming (Twitch, YouTube)
- Twitter engagement (technical threads)
- Partnership co-marketing

**Budget**: $3K/mo (travel, events)
**Expected CAC**: $50

### 5. Paid Acquisition (5% of signups)
**Strategy**: Targeted developer ads

**Tactics**:
- Twitter Ads (developer audience)
- Reddit Ads (r/webdev, r/javascript)
- Google Ads (branded + competitor terms)
- Podcast sponsorships (dev podcasts)
- Newsletter sponsorships (dev newsletters)

**Budget**: $2K/mo (testing phase → $10K/mo at scale)
**Expected CAC**: $80 (improves to $50 with optimization)

## Customer Acquisition Cost (CAC) by Channel

```
Organic (Content):  $30 CAC × 2,500 users = $75K
Community:          $20 CAC × 1,000 users = $20K
Referral (PLG):     $10 CAC × 750 users  = $7.5K
Developer Relations: $50 CAC × 500 users  = $25K
Paid Ads:           $80 CAC × 250 users  = $20K

Total: 5,000 users, $147.5K CAC
Blended CAC: $29.50 per user
```

**LTV**: $522 (Pro), $1,176 (API revenue share), $1,176 (Studio)
**Blended LTV**: ~$625 per user
**LTV/CAC**: 21x (target: 3x+)

## Competitive Positioning

### Direct Competitors

**vs Vercel/Netlify (Hosting)**:
- ✅ Full CMS included (not just hosting)
- ✅ 10x cheaper ($29 vs $300+)
- ✅ Unlimited apps (not per-project)
- ✅ Built-in API marketplace

**vs Contentful/Sanity (Headless CMS)**:
- ✅ AI-native (natural language schemas)
- ✅ Virtual filesystem (portable)
- ✅ 90% bundle reduction (meta-Payload)
- ✅ Zero-latency (DO SQLite)

**vs RapidAPI/Apigee (API Platforms)**:
- ✅ CMS + API (not just API)
- ✅ Auto-generated SDKs
- ✅ Lower fees (10% vs 20-30%)
- ✅ Deploy from gist

**vs Bubble/Webflow (No-Code)**:
- ✅ Real TypeScript code (not visual)
- ✅ AI-powered generation
- ✅ Professional developer tool
- ✅ Portable (not locked in)

### Unique Value Propositions

**For Developers**:
1. **"From MDX to Production in 60 Seconds"** - Fastest deployment
2. **"PayloadCMS to Create Unlimited PayloadCMS"** - Infinite apps
3. **"90% Less Code, 100% Type-Safe"** - Better DX
4. **"AI-Native Development Platform"** - Future-proof

**For Businesses**:
1. **"$29/mo for Unlimited Apps"** - Best economics
2. **"Built-In API Marketplace"** - Revenue opportunities
3. **"Deploy from a Gist"** - Simplest workflow
4. **"Enterprise-Ready from Day One"** - Scalable

## Success Metrics & KPIs

### North Star Metric
**Weekly Active Apps** - Number of apps with activity in past 7 days

### Primary KPIs (Weekly)
- New Signups (target: 100/week by month 6)
- Activation Rate (target: 40%)
- Paid Conversion (target: 10%)
- MRR Growth (target: 20% month-over-month)
- Retention Rate (target: 70% M1→M2)

### Secondary KPIs
- Content Performance (views, conversions)
- Community Growth (Discord members, GitHub stars)
- API Marketplace (listings, revenue)
- Support Metrics (tickets, satisfaction)
- Product Usage (features, engagement)

### Experiment Framework

**Weekly Experiments**:
- 2 growth experiments/week
- 1 retention experiment/week
- 1 monetization experiment/week

**Hypothesis Template**:
```
IF we [change/add/remove X]
THEN we expect [metric Y] to [increase/decrease by Z%]
BECAUSE [reasoning based on user behavior]

Success: [metric moves by ≥Z%]
Learn: [insight regardless of outcome]
```

## Best Practices

### Content Creation
- Focus on SEO from day 1
- Solve real developer problems
- Show, don't tell (code examples)
- Make content shareable (Twitter-friendly)
- Update regularly (freshness signals)

### Community Management
- Respond within 1 hour (Discord)
- Recognize contributors publicly
- Feature community projects
- Weekly spotlight (user showcase)
- Monthly recap (highlights, stats)

### Product-Led Growth
- Time to value <5 minutes
- Aha moment in first session
- Viral by default (social sharing)
- Referral incentives aligned
- Remove friction everywhere

### Developer Relations
- Lead with value (not sales)
- Technical depth (show expertise)
- Open source first (build trust)
- Community over company
- Authentic engagement

## Integration with Other Repos

### apps.do (Product)
- Growth features (referrals, sharing)
- Onboarding optimization
- Conversion funnels
- Retention hooks

### api.services (Backend)
- Analytics events
- A/B testing infrastructure
- User segmentation
- Growth metrics API

### site/ (Marketing Site)
- Landing pages
- Case studies
- Pricing pages
- Blog/content

### sdk/ (Developer Tools)
- Usage analytics
- Developer onboarding
- Integration docs
- Example apps

## Resources

### Tools & Services
- **Analytics**: PostHog (product analytics)
- **Marketing**: HubSpot (email, CRM)
- **Community**: Discord (chat), Circle (discussions)
- **Content**: Webflow (blog), YouTube (video)
- **Experiments**: GrowthBook (A/B testing)
- **Attribution**: Segment (data pipeline)

### Budget (Monthly)
```
Content Marketing:     $2,000
Paid Acquisition:      $2,000
Developer Relations:   $3,000
Community:            $1,000
Tools/Software:       $500
Contingency:          $1,500

Total: $10,000/mo
```

### Team (Eventually)
- **Growth Lead** (hire month 3)
- **Content Marketer** (hire month 4)
- **DevRel Engineer** (hire month 6)
- **Community Manager** (hire month 8)

## Next Steps

### Immediate (This Week)
1. ✅ Set up growth repository structure
2. ✅ Document initial GTM strategy
3. ⏳ Research competitive landscape
4. ⏳ Define customer personas
5. ⏳ Create content calendar (Q1)

### Month 1
- Complete market research
- Build tracking infrastructure
- Create foundational content
- Launch beta community
- Recruit first 100 users

### Month 2
- Refine messaging and positioning
- Optimize onboarding flow
- Prepare launch materials
- Build press/influencer list
- Test referral mechanics

### Month 3
- Public launch (ProductHunt, HN)
- Content blitz (10+ pieces)
- Community launch event
- Start paid experiments
- Monitor metrics closely

## Documentation Standards

### File Structure
- One strategy per file
- Markdown format
- Data-driven insights
- Actionable recommendations
- Regular updates (weekly for active campaigns)

### Metrics Reporting
- Weekly: Key metrics dashboard
- Monthly: Full performance review
- Quarterly: Strategic planning
- Annual: Yearly retrospective

### Experiment Tracking
```yaml
---
experiment: landing-page-v2
hypothesis: New hero copy will increase signups 25%
start_date: 2025-10-15
end_date: 2025-10-29
status: running
result: pending
---
```

---

**Created**: 2025-10-02
**Owner**: Growth Team
**Status**: Active
**Next Review**: Weekly (every Monday)
