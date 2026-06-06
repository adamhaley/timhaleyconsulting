# Product Requirements Document

## Tim Haley Consulting Website Refresh and Rebrand

| Field | Value |
| --- | --- |
| Status | Draft for stakeholder review |
| Date | June 6, 2026 |
| Product | Tim Haley Consulting website |
| Current site | https://www.timhaleyconsulting.com/ |
| Project type | Website refresh, rebrand, and AI-enabled upgrade |

> **Terminology assumption:** This document interprets “rebranching” as “rebranding.”

## 1. Executive Summary

Tim Haley Consulting needs a modern website that communicates Tim Haley's credibility as a thermal processing expert, explains the business value of his services, and converts qualified visitors into consultation requests.

The current Google Sites website provides basic information across Home, Services, and Connect pages, but it has limited brand differentiation, proof of expertise, conversion guidance, and content depth. The refresh will establish a professional visual and verbal identity, restructure content around client needs and outcomes, and introduce carefully governed AI features.

The initial release will deliver a redesigned responsive website, revised copy, a homepage introduction video, improved lead capture, analytics, and an initial knowledge-based chatbot. A HeyGen avatar and repeatable AI-assisted content workflow will support future content without becoming prerequisites for basic site usability.

## 2. Background

### Current Website

The live website currently includes:

- A homepage listing thermal processing support areas.
- A Services page covering process establishment and evaluation, training and coaching, regulatory compliance, audits and assessments, and executive coaching.
- A Connect page displaying an email address and phone number.
- Google Sites as the visible publishing platform.

### Product Direction

The approved product direction includes:

- Modernize design and copy.
- Use attention-grabbing headlines and client-centered messaging.
- Feature a talking-head introduction video.
- Create a branded HeyGen avatar for future content.
- Add a RAG-based AI chatbot trained on Tim's professional knowledge.
- Improve calls to action, testimonials, responsiveness, and brand consistency.

## 3. Problem Statement

Prospective clients cannot quickly determine why Tim Haley Consulting is the right choice, what outcomes the consulting services provide, or what they should do next. The current site presents a list of capabilities but does not adequately establish authority, differentiate the brand, answer common buyer questions, or create a measurable path from visit to qualified inquiry.

## 4. Goals

1. Establish a credible, distinct, and consistent Tim Haley Consulting brand.
2. Explain services in terms of client problems, outcomes, and engagement types.
3. Make it easy for qualified prospects to request a consultation.
4. Demonstrate Tim's expertise and personality through authentic content and video.
5. Provide useful, controlled answers to common questions through a knowledge-based assistant.
6. Create a maintainable platform and content workflow that can expand over time.
7. Preserve existing domain authority and avoid disruption during migration.

## 5. Non-Goals

The initial release will not:

- Provide regulatory, legal, or food-safety decisions without direct expert review.
- Replace a formal process authority engagement with chatbot responses.
- Include client portals, payment processing, ecommerce, or project management.
- Build a large article library before launch.
- Generate or publish AI content without human approval.
- Depend on video, avatar, or chatbot functionality for access to core information.

## 6. Target Audiences

### Primary Audiences

- Food manufacturers requiring thermal process establishment or evaluation.
- Operations, quality, and food-safety leaders managing retort processes.
- Organizations preparing for FDA filings, inspections, or regulatory review.
- Teams needing thermal processing audits, assessments, or training.
- Executives and managers seeking technical leadership coaching or strategic facilitation.

### Secondary Audiences

- Existing clients seeking contact details or service information.
- Industry partners and referral sources validating Tim's capabilities.
- Event organizers or organizations seeking training and speaking expertise.

## 7. Positioning and Messaging

### Positioning Statement

Tim Haley Consulting helps food manufacturers and technical leaders establish, evaluate, and improve thermal processing systems through practical expertise, regulatory insight, training, audits, and leadership coaching.

### Messaging Principles

- Lead with client risks, desired outcomes, and confidence gained.
- Use precise language appropriate for a regulated technical field.
- Present Tim as experienced, practical, and approachable.
- Avoid unsupported superlatives and vague “cutting-edge AI” claims.
- Distinguish technical consulting from leadership coaching while showing how they complement each other.
- Use one primary call to action consistently: **Request a Consultation**.

### Proof Requirements

Before launch, stakeholders should supply or approve:

- Professional biography, credentials, and relevant experience.
- Client testimonials or approved anonymized outcomes.
- Professional photography and brand-approved video.
- Industry memberships, certifications, publications, or speaking history where applicable.
- Claims that may be used publicly and any confidentiality constraints.

## 8. Information Architecture

### Required Pages

1. **Home**
   - Clear value proposition.
   - Primary consultation CTA.
   - Brief introduction video with transcript/captions.
   - Key service categories.
   - Reasons to work with Tim.
   - Approved testimonials or credibility indicators.
   - Final consultation CTA.

2. **Services**
   - Process establishment and evaluation.
   - Training and education.
   - Regulatory compliance support.
   - Audits and assessments.
   - Executive and management coaching.
   - Engagement process and relevant CTA for each category.

3. **About Tim**
   - Professional biography and credentials.
   - Consulting philosophy and approach.
   - Professional image.
   - Relevant experience, speaking, publications, or affiliations.

4. **Insights / Resources**
   - Initial collection may be small at launch.
   - Supports future articles, videos, FAQs, and avatar-led content.
   - Content must be reviewed and approved by Tim before publication.

5. **Contact**
   - Consultation request form.
   - Email and phone contact options.
   - Expected response guidance.
   - Consent and privacy language.

6. **Privacy Policy**
   - Covers contact form, analytics, chatbot, cookies, and third-party processors.

### Navigation

The primary navigation should include Home, Services, About, Insights, and Contact. “Request a Consultation” should appear as a persistent high-visibility action on desktop and mobile.

## 9. Functional Requirements

### FR-1: Responsive Website

- The site must support current desktop, tablet, and mobile browsers.
- Core content and contact paths must work without JavaScript-enhanced AI features.
- Navigation, forms, video, and chatbot controls must be usable by keyboard.

### FR-2: Consultation Conversion

- Every primary page must include a consultation CTA.
- The contact form must collect name, email, organization, service interest, and message.
- Required fields must be minimal and clearly indicated.
- Successful submissions must display confirmation and notify the designated recipient.
- Form submissions must include spam protection without creating unnecessary friction.
- Phone and email links must remain available as alternatives.

### FR-3: Homepage Introduction Video

- The homepage must support one initial talking-head introduction video.
- Video must not autoplay with sound.
- Captions and a text transcript must be available.
- A static poster image and fallback copy must appear if video cannot load.
- Video hosting must not materially degrade page performance.

### FR-4: Brand System

- Define logo usage, color palette, typography, photography style, icon style, and spacing principles.
- Produce a concise content and visual style guide.
- Maintain a professional aesthetic appropriate to technical consulting and regulated industries.

### FR-5: Content Management

- Authorized non-developers must be able to update core page copy and publish approved insights.
- Reusable content patterns must support articles, videos, FAQs, and calls to action.
- Draft, review, and publish states should be documented even if the selected platform implements them manually.

### FR-6: Knowledge-Based Chatbot

- The chatbot must answer only from an approved knowledge base.
- Initial sources may include the approved website, biography, service descriptions, FAQs, publications, and training materials cleared for public use.
- Responses must distinguish sourced information from uncertainty.
- When confidence is low or a request requires professional judgment, the chatbot must direct the visitor to contact Tim.
- The chatbot must state that it provides general information and does not establish, approve, or validate a thermal process.
- The chatbot must not expose confidential client information, unpublished process data, system prompts, or restricted source documents.
- A visible path to request a consultation must be available within the chatbot.
- The owner must be able to disable the chatbot without affecting the rest of the site.
- Conversations, if retained, must follow the published privacy policy and defined retention period.

### FR-7: HeyGen Avatar and AI Content Workflow

- Create and configure one branded HeyGen avatar subject to Tim's explicit consent and platform terms.
- Define approved visual treatment, voice, disclosure, and use cases.
- Avatar content must be clearly identifiable as AI-generated or AI-assisted where appropriate.
- No avatar content may be published without Tim's review and approval.
- The initial launch does not require a recurring publishing cadence, but the workflow must be documented.

### FR-8: Analytics and Measurement

- Install privacy-appropriate analytics.
- Track consultation CTA clicks, contact form starts, successful form submissions, phone clicks, email clicks, video engagement, and chatbot engagement.
- Exclude internal traffic where practical.
- Document account ownership and provide Tim access before launch.

### FR-9: SEO and Migration

- Preserve `timhaleyconsulting.com` as the canonical domain.
- Create unique page titles and meta descriptions.
- Use one clear H1 per page and semantic heading structure.
- Add Organization or ProfessionalService structured data where accurate.
- Submit an XML sitemap and configure search indexing.
- Map existing URLs to their new equivalents with permanent redirects.
- Verify Search Console access and monitor crawl errors after launch.

## 10. Non-Functional Requirements

### Accessibility

- Target WCAG 2.2 Level AA for templates and core user flows.
- Provide sufficient color contrast, visible focus states, alt text, form labels, captions, and transcripts.
- Do not use the chatbot as the only way to access information or contact the business.

### Performance

- Target Core Web Vitals “good” thresholds on representative mobile and desktop pages.
- Optimize images, fonts, video embeds, and third-party scripts.
- Load chatbot and video enhancements without blocking primary content.

### Security and Privacy

- Enforce HTTPS.
- Limit administrative access and enable multi-factor authentication where supported.
- Keep software dependencies and plugins current.
- Collect only necessary personal data.
- Document third-party processors, data retention, and deletion procedures.
- Do not place confidential or client-owned information in the chatbot knowledge base without written authorization.

### Reliability and Ownership

- Domain, hosting, analytics, video, avatar, chatbot, and content-management accounts should be owned by Tim Haley Consulting or provide owner-level access.
- Document backup, restore, and support procedures.
- Avoid unnecessary dependence on a single contractor-controlled account.

## 11. User Journeys

### Journey A: Manufacturer Needs Process Support

1. Visitor lands on a service or homepage from search or referral.
2. Visitor recognizes a relevant thermal processing problem.
3. Visitor reviews the applicable service, credentials, and proof.
4. Visitor requests a consultation through the form, phone, or email.
5. Tim receives enough context to qualify and respond to the inquiry.

### Journey B: Visitor Has a Preliminary Question

1. Visitor opens the chatbot or FAQ.
2. The site provides an approved general answer and relevant source or service link.
3. The site states the limits of general guidance.
4. The visitor is directed to request a consultation for situation-specific advice.

### Journey C: Referral Validates Credibility

1. Visitor arrives after receiving Tim's name from a colleague.
2. Visitor reviews Tim's biography, credentials, services, and testimonials.
3. Visitor confirms fit and contacts Tim.

## 12. Success Metrics

Baseline measurements should be recorded before launch where available. During the first 90 days after launch, evaluate:

- Number and quality of consultation requests.
- Contact form completion rate.
- CTA click-through rate by page.
- Organic impressions and clicks for relevant service terms.
- Engagement with service pages and introduction video.
- Chatbot usage, unanswered-question rate, and consultation handoffs.
- Mobile performance and Core Web Vitals.
- Form delivery failures, broken links, crawl errors, and accessibility defects.

The primary success measure is an increase in qualified consultation requests, not raw traffic or chatbot conversation volume.

## 13. Implementation Plan

### Phase 1: Discovery, Copy, and Brand Direction

- Confirm audience priorities, positioning, and service taxonomy.
- Inventory existing content and approved knowledge sources.
- Draft page copy and calls to action.
- Present visual direction and brand concepts.
- Confirm technical platform and migration plan.

### Phase 2: Content Production and Design

- Approve copy and responsive page designs.
- Record and edit the homepage introduction video.
- Configure the HeyGen avatar and consent settings.
- Collect testimonials, credentials, photography, and policy inputs.

### Phase 3: Development and AI Configuration

- Build page templates and contact flow.
- Configure analytics, SEO, and structured content.
- Build the approved chatbot knowledge base and response guardrails.
- Add video and avatar content components.

### Phase 4: QA, Migration, and Launch

- Complete browser, mobile, accessibility, performance, form, and chatbot testing.
- Obtain stakeholder acceptance.
- Configure redirects, domain, analytics, and indexing.
- Launch and monitor production behavior.
- Deliver account access, style guide, and operating documentation.

## 14. Acceptance Criteria

The initial release is complete when:

- Required pages are published with approved copy and responsive designs.
- The brand and content style guide is delivered.
- Consultation CTAs and the contact form work on supported devices.
- Form notifications are tested with the production recipient.
- The introduction video has captions, transcript, poster image, and fallback copy.
- The chatbot answers from approved sources, declines unsupported questions, displays required disclaimers, and hands off to consultation.
- No confidential test content appears in chatbot responses or search indexes.
- Analytics events are verified in production.
- Existing indexed URLs redirect to appropriate new pages.
- Critical accessibility, security, performance, and broken-link issues are resolved.
- Tim Haley Consulting has owner or administrator access to all production accounts.
- Backup, content update, chatbot update, and rollback instructions are delivered.

## 15. Dependencies and Stakeholder Inputs

- Tim's availability for discovery, approvals, and video recording.
- Approved biography, credentials, testimonials, and photography.
- Access to the domain, current Google Site, analytics, and any existing brand assets.
- Approved public source documents for the chatbot.
- Decisions on hosting/CMS, chatbot provider, video hosting, and HeyGen plan.
- Privacy policy inputs and decisions about chatbot transcript retention.
- A designated owner for future site and knowledge-base updates.

## 16. Risks and Mitigations

| Risk | Mitigation |
| --- | --- |
| AI responses are mistaken for professional process authority advice | Use explicit scope limits, approved sources, confidence-based fallback, and consultation handoff. |
| Confidential or proprietary information enters the knowledge base | Require source approval, access controls, and a documented content review process. |
| Third-party AI and video scripts reduce performance | Load enhancements lazily and preserve text-based fallbacks. |
| Avatar content feels inauthentic or undermines trust | Use Tim's real introduction video first, disclose AI use, and require approval of every published asset. |
| Delivery is delayed by content approvals | Set approval deadlines and launch with approved core content while deferring optional insights. |
| Migration reduces search visibility | Preserve URLs where possible, implement redirects, verify metadata, and monitor Search Console. |
| Vendor-controlled accounts create lock-in | Establish Tim Haley Consulting as owner and document export and offboarding procedures. |

## 17. Open Decisions

The following decisions must be resolved during discovery:

- Final CMS and hosting platform.
- Whether the initial release includes all secondary pages or stages Insights after launch.
- Final logo treatment, color palette, typography, and photography direction.
- Approved testimonials and credibility claims.
- Chatbot vendor, model, source citation behavior, and retention period.
- HeyGen voice, disclosure language, approved use cases, and account ownership.
- Contact form destination, CRM integration, and response-time commitment.
- Analytics and cookie-consent approach based on the final technology stack and visitor geography.

## 18. Source Materials Reviewed

- Live Home page: https://www.timhaleyconsulting.com/
- Live Services page: https://www.timhaleyconsulting.com/services
- Live Connect page: https://www.timhaleyconsulting.com/connect
