# Industry Solutions Landing Page

A high-conversion landing page for Vimamall's industry-specific software solutions.

## Features

- **Hero Section**: Prominent display of "10-Day Delivery Guarantee" and "80% Market Discount"
- **20-Industry Accordion**: Interactive pull-down menu showing pain points and solutions
- **Sticky Inquiry Form**: Captures leads with Netlify Forms integration
- **Mobile-Responsive**: Optimized for all devices
- **Fast Loading**: Static HTML/CSS/JS with minimal dependencies

## Form Handling

The form uses Netlify Forms with:
- Primary submission to `admin@vimamall.com`
- Email subject includes selected industry
- Auto-reply/confirmation flow
- Honeypot spam protection

## Industries Covered

1. Cross-Border Forwarding
2. Cold Chain Logistics
3. Condo & JMB Management
4. Central Kitchen & F&B
5. Smart Agriculture
6. Legal Case Management
7. Accounting & Tax Helper
8. Insurance Agency CRM
9. Manufacturing Job Shop
10. Construction & Site HQ
11. Vehicle Workshop
12. E-Commerce Fulfillment
13. Clinic Patient Portal
14. Dental Practice Manager
15. TCM (Chinese Medicine)
16. Gym & Fitness Club
17. Tuition & Education
18. HR Claim & Leave
19. B2B Wholesale Portal
20. Non-Profit & Temple

## Deployment

This page is deployed to `https://easyclaw.it.com/industries/`

### Deploy to Netlify

```bash
# Navigate to the industries directory
cd sites/easyclaw.it.com/industries

# Deploy using Netlify CLI
netlify deploy --prod --dir=.
```

Or drag-and-drop the `industries` folder to Netlify's deploy UI.

## File Structure

```
industries/
├── index.html       # Main landing page
├── netlify.toml     # Netlify configuration & form settings
└── README.md        # This file
```

## Form Submissions

Submitted forms will:
1. Be captured by Netlify Forms
2. Send email notification to admin@vimamall.com
3. Store submissions in Netlify dashboard
4. Show success message to user

## Contact

Vimamall Sdn Bhd
Email: admin@vimamall.com
