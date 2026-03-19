# Fastware & Easyclaw Website Documentation
## Complete Feature Overview for Partner Review

**Prepared by:** Jack (Digital COO)  
**Date:** March 19, 2026  
**Version:** 1.0

---

## 📋 Executive Summary

We have built **two separate business websites** targeting different market segments:

| | **Proj 3a: Easyclaw** | **Proj 3b: Fastware** |
|---|---|---|
| **Domain** | easyclaw.it.com | fastware.pro |
| **Product** | OpenClaw Auto (20 Workflows) | Custom Software Development |
| **Price Point** | RM50 (one-time) | RM8,000 (~20% of market) |
| **Target** | DIY users, individuals, small operators | SMEs, businesses needing custom systems |
| **Delivery** | Instant download | 10-day custom build |

---

## 🌐 Proj 3a: Easyclaw.it.com

### Overview
A product-focused e-commerce website selling 20 pre-built OpenClaw automation workflows for RM50. Positioned as an affordable entry point for users who want to automate their daily tasks.

### Website Structure

#### 1. Homepage (`/`)
**Purpose:** Sales landing page to convert visitors into buyers

**Sections:**
- **Hero Section**
  - Headline: "20 Ready-Made AI Workflows for Your Business"
  - Sub-headline: "Automate your daily tasks with OpenClaw. One-click install. Works on your Mac."
  - Price Badge: "Only RM50"
  - CTAs: "Buy Now - RM50" + "View All Workflows"

- **Problem Section**
  - Pain points: repetitive tasks, manual WhatsApp, price checking, report writing

- **Solution Section**
  - Benefits: 20 workflows, Mac privacy, no monthly fees

- **Workflow Grid (20 Items)**
  1. 🎬 YouTuber - Daily content pipeline
  2. 🏢 SME Owner - Daily business digest
  3. 📈 Trader - Pre-market briefing
  4. 💼 Freelancer - Weekly invoice run
  5. 📚 Teacher - Weekly lesson prep
  6. 🏠 Realtor - New listing blast
  7. 💼 Consultant - Monthly client reports
  8. ⚖️ Lawyer - Case research assistant
  9. 🩺 Doctor - Patient follow-up system
  10. 👥 HR Manager - Recruitment pipeline
  11. 🧮 Accountant - Monthly tax preparation
  12. 🎉 Event Planner - Event coordinator
  13. 🍽️ Restaurant Owner - Daily ops
  14. 🛒 E-commerce - Daily sync
  15. 💪 Fitness Coach - Client progress tracking
  16. 🎙️ Podcaster - Production pipeline
  17. 👨‍💻 Developer - Code assistant
  18. ✍️ Writer - Content calendar
  19. 📢 Marketer - Social media automation
  20. 🏥 Clinic - Appointment management

- **How It Works (5 Steps)**
  1. Buy - Pay RM50 one-time
  2. Download - Get all 20 workflows
  3. Install - One-command OpenClaw setup
  4. Activate - Choose which workflows to run
  5. Relax - Let AI handle your tasks

- **Pricing Section**
  - RM50 one-time vs RM1,500/month VA comparison

- **FAQ Section**
  - What is OpenClaw?
  - Do I need coding? (No)
  - Windows support? (Mac only for now)
  - Can I modify workflows? (Yes)
  - Data safety? (Runs locally)

- **Sticky Mobile CTA**
  - Bottom bar for mobile users

#### 2. Payment Page (`/payment/`)
**Purpose:** Checkout and payment processing

**Features:**
- Product: OpenClaw Auto - 20 Workflows
- Price: RM50 (one-time)
- **Voucher System:** FREETRY code for free access
- Payment methods: Credit Card, PayPal, Bank Transfer
- Order summary sidebar
- Success modal with next steps

**Voucher Logic:**
- Code: `FREETRY`
- Function: Unlocks all features for free
- Admin Control: Can disable via `VOUCHER_CONFIG.ENABLED`
- User Persistence: Saved in localStorage

#### 3. Workflows Detail Page (`/workflows/`)
**Purpose:** Showcase each workflow in detail

**Features:**
- Filterable by category (Content, Business, Finance, Healthcare, Tech)
- Detailed cards for all 20 workflows
- Feature lists for each
- "Buy All - RM50" CTA

#### 4. Setup Guide (`/setup/`)
**Purpose:** Help users install and configure

**Features:**
- Progress bar navigation (Requirements → Download → Install → Activate → Help)
- System requirements checklist
- Terminal commands with copy buttons
- Step-by-step installation
- Troubleshooting section
- Video tutorial placeholders

#### 5. Industries Page (`/industries/`)
**Purpose:** Link to custom software (cross-sell to Proj 3b)

**Features:**
- Banner: "Looking for custom software development? → Contact us"
- 20-industry accordion with pain points/solutions
- Inquiry form

### Technical Stack
- **Platform:** Static HTML/CSS/JS
- **Hosting:** Netlify (GitHub integration)
- **Form Handling:** Netlify Forms
- **Payment:** To be integrated (Stripe/PayPal)
- **Domain:** easyclaw.it.com (DNS pending)

### Design System
- **Colors:** Dark blue (#1e3a5f) + Teal accent (#00d4aa)
- **Font:** Inter (Google Fonts)
- **Style:** Product-focused e-commerce, mobile-optimized
- **Trust Elements:** Secure checkout badges, money-back guarantee

---

## 🌐 Proj 3b: Fastware.pro

### Overview
A premium custom software development agency website. Positions Fastware as an AI-powered development company that delivers enterprise-grade systems in 10 days at 80% below market price.

### Brand Positioning
**Slogan:** "AI-Powered Software Development in 10 Days"

**Key Value Propositions:**
- Speed: 10-day delivery vs 3-6 months traditional
- Price: RM8,000 vs RM40,000 market rate (80% savings)
- Quality: Custom-built, not templates

### Website Structure

#### 1. Homepage (`/`)
**Purpose:** Generate leads for custom software projects

**Sections:**

- **Navigation**
  - Logo: "Fastware"
  - Links: Why Us, Industries, Process, Pricing
  - CTA: "Get Quote"

- **Hero Section**
  - Badge: "AI-Powered Development"
  - Headline: "Your Custom Software Ready in 10 Days"
  - Sub-headline: "Stop waiting months for software. Fastware combines AI acceleration with expert engineering to deliver enterprise-grade systems at 20% of traditional costs."
  - CTAs: "Get Your Free Quote" + "See How It Works"

- **Stats Bar**
  - 10 Days - Average Delivery Time
  - 80% - Cost Savings vs Market
  - 20+ - Industries Served
  - 100% - Source Code Ownership

- **Why Choose Fastware (3 Cards)**
  1. **Lightning Fast** - AI-accelerated development, 10 days vs 3-6 months
  2. **Unbeatable Pricing** - RM8,000 vs RM40,000 market rate
  3. **Perfect Fit Guarantee** - Custom-built for exact workflow

- **Industry Solutions (4 Categories)**
  1. **Logistics & Supply Chain**
     - Cross-border parcel tracking portals
     - Cold chain temperature monitoring
     - Last-mile delivery management
  
  2. **Property & Real Estate**
     - Condo/JMB management systems
     - Rental property automation
     - Lead CRM with social sync
  
  3. **Medical & Wellness**
     - Clinic & dental practice portals
     - Gym membership & access control
     - TCM herb formula management
  
  4. **Specialized Business Systems**
     - Central kitchen ERP solutions
     - Agriculture yield tracking
     - Manufacturing job shop tracking

- **Process Timeline (10-Day Sprint)**
  1. Consultation (Day 1) - Share pain points and requirements
  2. Architecture (Days 2-3) - Design custom database & workflow
  3. Development (Days 4-8) - AI-accelerated build with expert oversight
  4. Launch (Days 9-10) - Test, refine, go live

- **Pricing Section**
  - RM8,000 one-time
  - Strikethrough: RM40,000
  - Includes: Full source code, custom database, mobile-responsive, WhatsApp/Email integrations, 1-year support, training & documentation

- **CTA Section**
  - "Ready to Transform Your Business?"
  - "Get Your Free Quote"

- **Footer**
  - Logo, email (admin@vimamall.com), links, copyright

### Technical Stack
- **Platform:** Static HTML/CSS/JS
- **Hosting:** Netlify (GitHub integration)
- **Form Handling:** Mailto link (can upgrade to Netlify Forms)
- **Domain:** fastware.pro (DNS pending)

### Design System
- **Colors:** Dark blue (#0a1628, #1a2d4a) + Teal gradient (#00d4aa, #00b894)
- **Font:** Inter (Google Fonts)
- **Style:** Premium SaaS aesthetic, professional, modern
- **Elements:** Animated stats, timeline with progress bar, gradient text

---

## 🔗 Cross-Linking Strategy

### Easyclaw → Fastware (Up-sell)
- Industries page banner: "Looking for custom software development?"
- Target: Users who outgrow pre-built workflows

### Fastware → Easyclaw (Down-sell)
- Potential future addition: "Not ready for custom? Try our RM50 workflows"

---

## 📊 Technical Implementation Details

### GitHub Repositories
| Project | Repository | Branch |
|---------|-----------|--------|
| Easyclaw | michael-sis789/easyclaw-website | main |
| Fastware | michael-sis789/fastware-website | main |

### Netlify Sites
| Site | Netlify URL | Custom Domain |
|------|-------------|---------------|
| Easyclaw | easyclaw-site.netlify.app | easyclaw.it.com (pending) |
| Fastware | boisterous-gumption-698489.netlify.app | fastware.pro (pending) |

### DNS Configuration Required
**For both domains:**
- A Record: @ → 75.2.60.5 (Netlify IP)
- CNAME: www → [netlify-site].netlify.app

### File Structure
```
sites/
├── easyclaw.it.com/
│   ├── index.html          (Sales page)
│   ├── payment/
│   │   └── index.html      (Checkout)
│   ├── workflows/
│   │   └── index.html      (Workflow details)
│   ├── setup/
│   │   └── index.html      (Installation guide)
│   └── industries/
│       └── index.html      (20 industries + form)
│
└── fastware.pro/
    └── index.html          (Complete landing page)
```

---

## ✅ Completed Features

### Easyclaw.it.com
- [x] Sales-focused homepage with 20 workflows
- [x] Payment page with FREETRY voucher system
- [x] Workflow detail page with filtering
- [x] Setup/installation guide
- [x] Industries page with cross-sell banner
- [x] Mobile-responsive design
- [x] GitHub repository
- [x] Netlify deployment
- [ ] DNS configuration (pending)
- [ ] Payment gateway integration (pending)

### Fastware.pro
- [x] Professional landing page
- [x] Hero with animated gradient text
- [x] Stats bar with key metrics
- [x] Industry solutions grid
- [x] 10-day sprint timeline
- [x] Transparent pricing section
- [x] Mobile-responsive design
- [x] GitHub repository
- [x] Netlify deployment
- [x] Custom domain added in Netlify
- [ ] DNS configuration (pending)

---

## 🎯 Marketing Positioning

### Easyclaw Target Audience
- Freelancers and solopreneurs
- Small business owners
- Content creators (YouTubers, podcasters)
- Traders and investors
- Professionals (lawyers, doctors, consultants)

### Fastware Target Audience
- SMEs needing custom systems
- Property management companies
- Logistics and supply chain companies
- Healthcare providers
- Manufacturing businesses

### Key Differentiators
1. **Speed:** 10 days vs industry standard 3-6 months
2. **Price:** 80% below market rate
3. **AI-Powered:** Modern tech stack with automation
4. **Local:** Malaysian company (Vimamall Sdn Bhd)
5. **Full Ownership:** 100% source code ownership

---

## 🔄 Next Steps

### Immediate (This Week)
1. Complete DNS configuration for both domains
2. Test both websites live on custom domains
3. Set up payment gateway for Easyclaw (Stripe/PayPal)

### Short Term (Next 2 Weeks)
1. Add analytics (Google Analytics)
2. SEO optimization
3. Content marketing (blog posts about workflows)
4. Social media integration

### Long Term
1. Customer testimonials and case studies
2. Workflow marketplace expansion
3. Affiliate program for Easyclaw
4. Enterprise tier for Fastware

---

## 📞 Contact & Support

**Company:** Vimamall Sdn Bhd  
**Email:** admin@vimamall.com  
**Technical Lead:** Jack (Digital COO)

---

*End of Documentation*
