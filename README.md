# PKHosting – Mobile-First Landing Page Template

**Task:** Build a mobile-first landing page template with CTA, domain search link and UTM tracking for outreach traffic  
**Brand:** PKHosting.com

## Features

### 1. Mobile-First Design
- Fully responsive (looks great on phones first, then tablets & desktop)
- Clean, modern UI with fast loading
- Sticky header with quick CTA

### 2. Strong Calls-to-Action (CTA)
- Primary CTA in header
- Hero section CTAs (“Start Hosting” + “Search a Domain”)
- Final conversion CTA at the bottom
- All main CTAs are tracked

### 3. Domain Search
- Domain search box on the page
- Redirects to PKHosting domain search with the entered domain
- Supports popular extensions (.com, .pk, .com.pk, etc.)

### 4. UTM Tracking for Outreach Traffic
- Automatically captures UTM parameters from the URL:
  - `utm_source`
  - `utm_medium`
  - `utm_campaign`
  - `utm_term`
  - `utm_content`
- Stores them in localStorage so they persist
- Appends UTM parameters to all tracked outbound links (`data-track`)
- Domain search also carries the UTM parameters forward

### Example UTM URL for outreach:
```
https://your-landing-page.com/?utm_source=facebook&utm_medium=cpc&utm_campaign=hosting_promo&utm_content=ad1
```

## How to use

1. Upload `index.html` to any web hosting (or open it locally)
2. Share the page with UTM parameters in your ads / outreach messages
3. All clicks on main CTAs will carry the UTM data

## Files

```
pkhosting-landing-page/
├── index.html      ← Complete landing page
└── README.md
```

## Notes

- No external libraries required (pure HTML + CSS + JS)
- Easy to customize colors, text, and links
- Ready for Facebook Ads, Google Ads, email outreach, WhatsApp campaigns, etc.

---

**PKHosting.com** – Reliable web hosting for Pakistani businesses
