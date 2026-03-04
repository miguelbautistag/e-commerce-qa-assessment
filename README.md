# E-commerce Checkout QA Practice Exercise (Anonymized) 🚀

Personal take-home exercise from a recent QA Analyst interview process (e-commerce checkout flow simulation).

**Exercise Details**  
- **Type**: Technical assessment for QA Analyst role  
- **Date**: February 2026  
- **Focus**: Bug hunting, prioritization, A/B test planning, technical debugging  

### 📌Overview

Simulated QA tasks on a typical e-commerce funnel (product page → cart → checkout → upsell):  
- Bug logging & prioritization (functionality + UX/polish issues)  
- A/B test plan for pricing experiment (segmented traffic)  
- Technical checks (meta tags, GTM-served elements)  

All brand-specific details (names, URLs, prices, images, cheat codes, exact text) have been removed or generalized to protect company privacy and confidentiality.

### 🛠️Tools & Techniques Used

- Chrome DevTools (Network, Elements, Console)  
- Google Tag Manager (GTM) debug & preview mode  
- Structured bug reporting (ID, title, steps, expected/actual, severity/priority)  
- Test plan design (questions, mitigation, checklist)  

Core QA focus:  
- Risk-based prioritization  
- End-to-end flow validation  
- Data-driven experiment testing  
- Clear defect handoff to developers  

### 📊Artifacts 

Full anonymized report (bug hunt, A/B plan, technical checks):  
https://docs.google.com/spreadsheets/d/1NR81pERDVb1veMFzK0YGB6WhtoZ7S00v/edit?usp=sharing&ouid=110773353333564353107&rtpof=true&sd=true
https://docs.google.com/document/d/1i6L4062Q1aUYpNIU8M4TYK6x5RBOgAVBkaFs4npFM2c/edit?usp=sharing

**Important note on evidence**:  
In the “Evidence” column of the bug hunt tab:  
“Screenshots / evidence hidden to protect company privacy”

### 🔍Bug Summary (Part 1) 

- Total issues documented: 17  
- Prioritized by business impact (conversion, trust, revenue loss first)  
- Categories: Pricing inconsistencies, UX polish, tracking/debugging issues  

Top priorities included:  
- Timer/countdown failures  
- Shipping charge errors on receipt  
- Price mismatches in checkout/receipt  
- Item/size discrepancies  

### 📈A/B Test Plan Summary (Part 2) 

Goal: Test higher sale prices (with original strikethrough intact) only for segmented traffic (e.g., Facebook), while control traffic sees original prices.  

Key questions asked first: segmentation method, split ratio, tracking events, exclusions, rollback plan.  

Steps: simulate both variants, end-to-end flows, mitigate mismatches in cart/upsell, validate analytics.  

Checklist outline: variant assignment, price display, cart/checkout totals, upsell matching, tracking events, mobile rendering, negative cases.

### 🐛Technical Debugging (Part 3) 

**3A – Meta tag check**  
Used Chrome DevTools → Elements tab → search for tag name → found value (anonymized).

**3B – Missing GTM-served banner**  
Systematic debugging: clear cache, Network tab (gtm.js load), Console errors, GTM preview mode, Elements (hidden CSS?), trigger rules check. Escalate with evidence.

### 🎯Key Learnings & Takeaways

- Importance of variant segmentation in A/B tests  
- Systematic DevTools/GTM debugging for frontend issues  
- Clear, prioritized bug reporting with business impact  
- Proactive questioning before test execution  

### Privacy & Ethics Note 🔒

All identifiable company information has been removed or anonymized. This is a personal learning exercise only — no confidential materials are shared.

Feedback, questions or discussion always welcome! Feel free to open an issue or DM me.

#QA #ManualTesting #ABTesting #EcommerceQA #TestAutomation
