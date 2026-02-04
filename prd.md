# Product Requirements Document: Lemons Landing Page

## Overview

**Product:** Lemons  
**Type:** Landing page for early adopters  
**Audience:** Schedule C small business owners  

Lemons is a bookkeeping app designed specifically for Schedule C small business owners. The landing page will serve as the primary acquisition touchpoint for earliest adopters, informing them about Lemons and the value it delivers.

---

## Design Philosophy: Super Simple, One CTA

The landing page should be **stripped down to essentials**. One clear focus. One action.

| Principle | Application |
|-----------|-------------|
| **Super simple** | No competing sections. Minimal UI. Nothing that distracts from the core message. |
| **Strong, centralized CTA** | One primary CTA, above the fold, impossible to miss. The page funnels to this single action. |
| **Short, persuasive copy** | Few words. Every sentence earns its place. Speaks directly to Schedule C pain. |
| **Leave them wanting more** | Tease value; don’t over-explain. Create curiosity. The CTA is the next step—not a wall of features. |

**Visual metaphor:** Think Apple product reveal. One headline, one subhead, one button. No clutter.

---

## Page Plan: Single-Screen Layout

```
┌─────────────────────────────────────────────────────────────┐
│                                                             │
│                     [Logo: Lemons]                          │
│                                                             │
│              [HEADLINE — one sharp line]                    │
│                                                             │
│         [Subhead — 1–2 sentences max, persuasive]           │
│                                                             │
│                    ┌─────────────────────┐                  │
│                    │   [EMAIL INPUT]     │                  │
│                    │   [  CTA BUTTON  ]  │                  │
│                    └─────────────────────┘                  │
│                                                             │
│              [Optional: one trust line or micro-copy]        │
│                                                             │
└─────────────────────────────────────────────────────────────┘
```

**Above the fold only.** No scrolling required to understand or convert. If we add anything below (e.g., 2–3 micro-benefits), it supports—not competes with—the CTA.

---

## Copy Strategy

**Headline (≈5–10 words):**  
- Name the audience + the promise or outcome.  
- Example direction: *"Bookkeeping that gets Schedule C."*  
- Avoid generic phrases like "The best" or "Revolutionary."

**Subhead (≈15–25 words):**  
- Expand the promise in one sentence.  
- Hint at the benefit (simplicity, tax-ready, built for you) without listing features.  
- Example direction: *"Built for freelancers and sole proprietors. Less admin. Cleaner records. Tax time that doesn’t hurt."*

**CTA label:**  
- Action-oriented and specific.  
- Options: *"Get early access"* | *"Be the first to know"* | *"Join the waitlist"*  
- Avoid vague: "Submit" or "Sign up."

**Supporting micro-copy (optional):**  
- One line under the form: e.g., *"We’ll only email when we launch. No spam."*  
- Builds trust without adding bulk.

---

## Problem Statement

Schedule C small business owners (sole proprietors, freelancers, gig workers, independent contractors) face unique bookkeeping challenges:

- Tax categorization is confusing and time-consuming
- Deductible expenses are easy to miss or misclassify
- Many tools are built for larger businesses, not one-person operations
- Year-end tax prep is chaotic without clean records

They need a solution built for their workflow—and they want to be among the first to use it.

---

## Goals & Objectives

| Goal | Description |
|------|-------------|
| **Build awareness** | Help Schedule C owners discover Lemons and understand what it does |
| **Capture early adopters** | Collect sign-ups from people who want to be first in the know |
| **Communicate value** | Clearly explain benefits and differentiation vs. generic bookkeeping tools |
| **Set expectations** | Position Lemons as built specifically for Schedule C businesses |

---

## Target Audience

**Primary:** Schedule C small business owners, including:

- Freelancers (designers, writers, consultants)
- Gig economy workers
- Independent contractors
- Sole proprietors
- Single-member LLCs reporting on Schedule C

**Early adopter mindset:**

- Willing to try new tools
- Frustrated with current bookkeeping/tax workflows
- Interested in being first to know about launches
- Values tools tailored to their business type

---

## User Stories

1. As a Schedule C business owner, I want to quickly understand what Lemons does so I can decide if it’s relevant to me.
2. As an early adopter, I want to sign up to be notified when Lemons launches so I don’t miss out.
3. As a visitor, I want to see why Lemons is different from generic bookkeeping apps.
4. As a busy entrepreneur, I want the page to load fast and work well on mobile.

---

## Functional Requirements

Aligned with the **super simple** philosophy—every element must justify its presence.

### Must Have

- [ ] **Single hero block** – Headline + subhead only. No competing sections above the fold.
- [ ] **Schedule C positioning** – Audience and benefit clear in the copy (headline or subhead).
- [ ] **Email + CTA form** – Email input + single primary button. Inline or stacked. No secondary CTAs.
- [ ] **One trust line** (optional) – Micro-copy under form to reduce friction (e.g., No spam. We'll only email when we launch.)
- [ ] **Responsive design** – Usable on desktop, tablet, and mobile
- [ ] **Accessible** – Meets basic accessibility standards (contrast, focus states, readable font sizes)

### Deferred (Keep It Simple)

- [ ] **Benefits section** – Omit for v1. Value is in the headline + subhead. Add only if conversion suffers.
- [ ] **FAQ** – Omit for v1. Reduces clutter. Add later if support questions spike.
- [ ] **Footer** – Minimal: logo + optional Privacy link. Skip heavy footer.

### Nice to Have (Post-Launch)

- [ ] **Light animation** – Subtle entrance or hover on CTA only.
- [ ] **Social proof** – Add when available; not required for earliest adopters.


---

## Content Requirements

| Section | Purpose |
|--------|---------|
| **Headline** | ~5–10 words. Audience + promise. See Copy Strategy above. |
| **Subheadline** | ~15–25 words. Expand the promise; tease value. Don't list features. |
| **CTA** | Single primary action: "Get early access" / "Be the first to know" / "Join the waitlist" |
| **Trust line** | One sentence under form (optional): e.g., "No spam. We'll only email when we launch." |

---

## Success Metrics

| Metric | Target |
|--------|--------|
| Conversion rate (visitor → email sign-up) | Define baseline after first 100 visitors |
| Bounce rate | < 60% |
| Time on page | > 30 seconds |
| Mobile vs. desktop conversion parity | Within 20% |

---

## Non-Functional Requirements

- **Performance:** Page load < 3 seconds on 4G
- **Browser support:** Latest versions of Chrome, Safari, Firefox, Edge
- **Analytics:** Basic event tracking (page view, CTA click, form submit)
- **SEO:** Meta title, description, and Open Graph tags for sharing

---

## Out of Scope (This Phase)

- Full product onboarding
- In-app sign-in or account creation
- Payment or billing flows
- Multi-page marketing site
- Localization

---

## Open Questions

1. What is the planned launch timeline? (for “Coming soon” messaging)
2. Will early adopters receive any incentive (e.g., free trial, discount)?
3. Is there a brand style guide or design system to follow?
4. Where will collected emails be stored (Mailchimp, ConvertKit, custom backend)?

---

## Appendix: Schedule C Context

**Schedule C** (Form 1040) is used by sole proprietors and single-member LLCs to report profit or loss from a business. Bookkeeping for Schedule C owners often involves:

- Categorizing income and expenses per IRS guidelines
- Tracking deductible business expenses
- Separating personal and business transactions
- Preparing records for tax filing

Lemons aims to simplify this workflow for this specific segment.
