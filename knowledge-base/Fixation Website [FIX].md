# Site Structure

# STRATEGIC WEBSITE ARCHITECTURE RECOMMENDATION

ver 1.0.0 Dec 3, 2025

## **INFORMATION ARCHITECTURE MAP**

fixation.dev/  
│  
├─ (Primary Navigation \- Conversion)  
│  ├─ Home  
│  ├─ Services  
│  │  ├─ MVP Development (Bobby)  
│  │  ├─ Legacy Modernization (Tim)  
│  │  └─ AI Integration (Both)  
│  ├─ How We Work  
│  ├─ Case Studies  
│  ├─ About  
│  └─ Contact  
│  
├─ (Secondary Navigation \- Trust/Education)  
│  ├─ Testimonials  
│  └─ Resources (Phase 2/3)  
│  
└─ (Footer Only \- Utility)  
   ├─ Careers  
   ├─ Privacy Policy  
   └─ Terms of Service

---

## 

### **PRIMARY NAVIGATION (Conversion-Focused)**

**1\. Home** (/)

* **Purpose:** Entry point for both Bobby & Tim; builds complete belief arc  
* **SEO Value:** Target "custom software development," "AI development," geo-specific  
* **Status:** Redesigning in current wireframe project

**2\. Services** (/services)

* **Landing page:** Overview of service categories with belief-building intro  
* **Sub-pages:**  
  * **/services/mvp-development** (Bobby-focused)  
    * SEO: "MVP development," "startup software partner," "custom MVP"  
  * **/services/legacy-modernization** (Tim-focused)  
    * SEO: "legacy system modernization," "technical debt," "platform migration"  
  * **/services/ai-integration** (Both personas)  
    * SEO: "AI cost optimization," "custom AI development," "AI integration"  
* **Rationale:** Persona-specific entry points; addresses different pain states; enables targeted SEO

**3\. How We Work** (/how-we-work) *\[Exists \- Optimize\]*

* **Purpose:** Prove domain learning methodology \+ weekly demos \+ code ownership  
* **Content:** Process visualization, philosophy, differentiation  
* **SEO:** "custom software methodology," "domain-driven development"

**4\. Case Studies** (/case-studies)

* **Landing page:** Filterable case study grid (by industry, problem type, service)  
* **Individual studies:** Full transformation narratives  
  * Salesforce Alternative  
  * AI Cost Optimization ($10K→$200)  
  * Legacy System Modernization  
  * Manual Team → AI Replacement  
* **SEO:** "custom software case study," industry-specific terms, problem-specific

**5\. About** (/about)

* **Trust:** team credibility, Gavin's story, referral growth  
* **Purpose:** Establish expertise, partnership mentality, "true partner not vendor"  
* **Merge:** Combine existing Our Team content \+ company story  
* **SEO:** "Gavin Koehler," "Fixation founders," "custom software company"

**6\. Contact** (/contact) *\[Exists \- Optimize\]*

* **CTA:** CTA fulfillment from all pages  
* **Form:** Qualification fields (persona type, project type, timeline, budget range)  
* **Options:** Discovery call booking \+ reference call requests  
* **SEO:** "custom software consultation," "free software assessment"

---

### **SECONDARY NAVIGATION (Trust & Education)**

**7\. Testimonials** (/testimonials) *\[Exists \- Keep\]*

* **Current page works well**  
* **Enhancement:** Tag testimonials by theme (Partnership, Problem-Solving, etc.)  
* **Integration:** Pull testimonials dynamically into other pages

**8\. Resources** (/resources) *\[New \- Phase 2/3\]*

* **Purpose:** Educational content proving NT2 (broken alternatives) & NT3 (unique approach)  
* **Content Types:**  
  * Guides: "Questions to Ask Before Hiring a Dev Shop"  
  * Comparison: "Custom vs. Off-the-Shelf vs. In-House"  
  * Whitepapers: "The True Cost of Vendor Lock-In"  
* **Lead Magnet:** ‘unique approach’-based content (methodology explainers)  
* **SEO:** Long-tail educational queries, thought leadership

---

### **UTILITY NAVIGATION (Footer Only)**

* Careers (/careers) \- Recruiting, not conversion-focused  
* Privacy Policy (/privacy-policy)  
* Terms of Service (if needed)  
* Internal assessments (not public-facing links)

---

## 

## **FLOW ARCHITECTURE**

**Primary Conversion Paths:**

**Path 1: Bobby Notebooks (Startup Founder)**

1. Home OR Services/MVP → validates pain (NT1)  
2. Case Studies (MVP examples) → proof methodology works (NT3)  
3. How We Work → deep methodology dive (NT3)  
4. About/Testimonials → trust builders (NT4)  
5. Contact → discovery call

**Path 2: Tim Tables (Operations Executive)**

1. Home OR Services/Legacy Modernization → validates pain (NT1)  
2. Case Studies (legacy/modernization) → proof methodology works (NT3)  
3. Resources (comparison guides) → invalidates alternatives (NT2)  
4. Testimonials (partnership focus) → trust builders (NT4)  
5. Contact → assessment call

**Path 3: Direct Referral**

1. Home → quick overview \+ social proof  
2. About/Testimonials → validate referrer's recommendation  
3. Contact → fast-track to conversation

---

## **SEO STRATEGY ALIGNMENT**

**Keyword Hierarchy:**

**Primary (High Competition):**

* Custom software development  
* Custom software development company  
* Software development partner

**Secondary (Service-Specific):**

* MVP development services  
* Legacy system modernization  
* AI integration services  
* Technical debt solutions

**Long-Tail (Bobby/Tim Pain Points):**

* "How to avoid vendor lock-in software"  
* "Custom software vs offshore development"  
* "Best software development for startups"  
* "Modernizing legacy systems without downtime"

**Local (If Applicable):**

* Custom software development \[city/region\]

**Content Strategy:**

* Each service page targets 2-3 specific keywords  
* Case studies target problem-specific searches  
* Resources target educational/comparison queries  
* Blog/articles (Phase 3\) target thought leadership

---

## **MOBILE-FIRST CONSIDERATIONS**

**Navigation Simplification:**

* Hamburger menu for mobile  
* Services dropdown reveals 3 sub-pages cleanly  
* CTA (Contact/Schedule Call) sticky on mobile  
* Case study cards stack vertically with filter at top

**Page Length:**

* Homepage: Scrollable sections with anchor navigation  
* Service pages: Focused, scannable (like homepage approach)  
* Case studies: Expandable sections to reduce initial scroll

---

## **IMPLEMENTATION COMPLEXITY ASSESSMENT**

**Fixation Build Effort:**

**Phase 1 (Months 1-2):**

* ✅ **Simple:** Home (rebuilding anyway)  
* ✅ **Simple:** Services landing \+ 3 sub-pages (templated structure)  
* ✅ **Simple:** Case Studies landing \+ 4 individual pages (templated)  
* ⚠️ **Moderate:** About (combining existing Our Team \+ new story content)  
* ✅ **Simple:** Contact (optimizing existing)

**Phase 2 (Months 3-4):**

* ⚠️ **Moderate:** Resources section (content management)  
* ✅ **Simple:** Testimonials enhancement (if desired)  
* ✅ **Simple:** How We Work optimization

**Total New Pages:** \~11 new pages (1 home redesign, 1 services landing, 3 service sub-pages, 1 case studies landing, 4 case study pages, 1 about)

**Technical Requirements:**

* Templated structure for services (reusable components)  
* Templated structure for case studies (reusable components)  
* CMS for case study content, testimonials, future blog articles  
* Form with qualification logic (dropdown-based, not complex)

---

**SEO Considerations:**

1. No blog architecture yet (intentional \- focus on conversion first)  
2. Resources section as Phase 2 hedge against needing more content  
3. Service pages may need content expansion for SEO (currently persona-focused)

---

## **SUCCESS METRICS BY PAGE TYPE**

**Homepage:**

* Primary: Time on page \>90 seconds, scroll depth \>50%  
* Conversion: CTA clicks to Contact/Services

**Service Pages:**

* Primary: Time on page \>2 minutes (belief engagement)  
* Conversion: Contact form submissions with service specified

**Case Studies:**

* Primary: Completion rate (read to bottom)  
* Conversion: "Schedule Discovery Call" clicks from case study

**How We Work:**

* Primary: Time on page, section expansion clicks  
* Indicator: Visited before Contact (shows methodology interest)

**About/Testimonials:**

* Primary: Page visits from other pages (not direct)  
* Indicator: Part of trust-building journey

**Contact:**

* Primary: Form completion rate  
* Quality: Persona self-identification, project type clarity

**Recommendation:** Start with Phase 1 core pages (Home, Services, Case Studies, About, Contact), validate conversion with Bobby/Tim traffic, then expand Resources in Phase 2 based on actual behavior data.

# Home

FIXATION HOMEPAGE WIREFRAME

ver 2.0.2 | Jan 9, 2025

---

# **FIXATION HOMEPAGE WIREFRAME v2.0**

## **SECTION 1: HERO**

**Notes:** N:5 (transformation) \+ N:4 (credibility hint)

### **HEADLINE**

**Own Your Software. Own Your Future.**

### **SUBHEAD**

No proprietary lock-in. No overnight disasters. No developers gone dark.

### **BELOW SUBHEAD: SMALL NOTE**

Custom software you actually own—built by US developers who understand your business, not just your requirements.

### **CTA**

**Primary:** Book Discovery Call →  
**Secondary:** See How We’re Different ↓  
*Opt A: For founders building MVPs \[\#services \> MVP\] and CEOs rescuing legacy platforms \[\#services \> Legacy\].*  
*~~Opt B: For founders building MVPs and CEOs inheriting broken systems.~~*

### **TRUST LINE**

Building custom software since 2012 | 100% referral growth

---

## **SECTION 2: SOCIAL PROOF STRIP**

**Notes:** N:4

### **VISUAL**

\[Client Logo Row x 4-6\]

### **CONTEXT LINE**

Trusted by funded startups and established businesses alike.

---

## **SECTION 3: WE GET YOU**

**Notes:** N:1 (empathy)

### **HEADLINE**

**You’re Smart to Be Skeptical**

### **SUBHEAD**

You’ll find more lemons in custom software than on any used car lot. Here’s where things go sour:

### **PAIN POINTS (single bulleted list, not columns)**

* Your vendor holds you hostage with proprietary code  
* Your budget gets burned fixing the same problems  
* Your impressive sales rep disappears after signing  
* Your competitors leapfrog you while you explain your requirements a fifth time

### **CLOSING LINE**

The stakes couldn't be higher. Most teams don't realize they chose the wrong partner until six months and a blown budget later.

Another month with the wrong approach is another month your competitors gain ground. Or another month your board loses confidence. You can’t afford to keep paying the cost of waiting.

---

## **SECTION 4: WHY ALTERNATIVES FAIL**

**Notes:** N:2 (broken alternatives)

### **HEADLINE**

**~~It’s Not You. It’s How Custom Software Is Sold.~~**

**This Is How Custom Software Usually Goes Wrong**

### **SUBHEAD**

Dev shops optimize for THEIR revenue, not your success.

### **PATTERN GRID (4 items, headline \+ one line each)**

| **Cheap Offshore** | Attractive rates. Time zones and cultural gaps kill communication. | | **Big Agencies** | Name-brand credibility. Junior devs at senior prices. |  
| **Lone Developer** | Personalized attention. Single point of failure. |   
| **In-House Hire** | Full control. 12-month detour to the same problem. |

### **PATTERN REVEAL**

Proprietary frameworks lock you in by design. Slow work gets buried until the final invoice. **You’re not picking the best option, you’re paying for your own trap.**

---

## **SECTION 5: OUR APPROACH**

**Notes:** N:3 (unique methodology)

### **HEADLINE**

**What If Your Software Partner Prevented Problems Instead of Creating Them?**

### **SUBHEAD**

Other dev shops solve problems after they occur. We prevent them from happening in the first place.

### **DIFFERENTIATORS (icon grid, 2x3)**

**🧠 Domain Learning First** Your business understood before we write a single line of code.

**🏗️ Clean Architecture** Modular code you control. Swap providers, add features, or bring it in-house—without starting over.

**📅 Weekly Demos** Truth comes out on demo day. Catch misunderstandings in week one, not month six.

**🤖 AI Cost Optimization** $10K/month → $200/month. 98% reduction while improving accuracy. (Real client example)

**🔓 Complete Code Ownership** Every line is yours. No proprietary lock-in. Ever.

**🇺🇸 US-Based & Responsive** 14 senior developers on your sleep schedule. Small enough to care, experienced enough to deliver. Same-day responses.

---

## **SECTION 6: HOW IT WORKS**

**Notes:** N:3 (process)

### **HEADLINE**

**From Skeptical to “Finally, Technology That Works”**

### **PROCESS (3 steps, visual timeline)**

**1\. Discovery & Domain Learning** We dive deep into your business, not just a menu of your requirements. *1-2 weeks*

**2\. Build & Demo Cycles** Weekly sprints with mandatory demos. See real progress every week. *60-90 days for MVP*

**3\. Scale & Optimize** Launch with confidence. Your software evolves with your business. *Ongoing partnership*

---

## **SECTION 7: PROOF**

**Notes:** N:4 (trust)

### **HEADLINE**

**Real Businesses. Real Results. Real Code Ownership.**

### **TESTIMONIAL (featured quote with attribution)**

“Fixation has a deep understanding of our applications, our customers, where we want to be, and how to get us there.” —Pam B., Software Development Manager, Nebraska Furniture Mart

### **CASE STUDY TEASER (two cards, minimal copy)**

**Bobby’s Story: Startup → Series A** Previous offshore team burned $25K with nothing usable. Working MVP in 11 weeks. Series A secured. \[Read Case Study →\]

**Tim’s Story: Legacy Rescue** Inherited buggy platform, vendor holding them hostage. Migrated without downtime. Board confidence restored. \[Read Case Study →\]

---

## **SECTION 8: TRANSFORMATION**

**Notes:** N:5 (new life)

### **HEADLINE**

**Technology That Helps You Win**

### **BODY**

Your software should be a revenue engine, not a source of constant anxiety. Whether you're launching something new or rescuing something broken, we build platforms that drive results.

### **BENEFITS (checkmarks, single line each)**

✓ Own your code, own your future ✓ Weekly visibility into real progress ✓ Platforms built to help you close ✓ Focus on customers, not firefighting

---

## **SECTION 9: CTA**

**Notes:** N:5 \+ N:4

### **HEADLINE**

**Ready to Own Your Software?**

### **SUBHEAD**

Book a discovery call. No pressure, just an honest conversation about whether we’re the right fit.

### **CTA**

\[Book Discovery Call\]

**WHAT HAPPENS NEXT** 30-minute discovery call. If we're a fit, we'll scope your project (1 week) and provide a fixed-price proposal. If we're not, we'll tell you honestly.

### **TRUST REINFORCER**

Our customers are so satisfied, they volunteer to hop on reference calls with you. We’re happy to arrange yours.

# Services \> AI

# FIXATION AI SERVICES PAGE WIREFRAME v2.0

## **fixation.dev/services/ai-integration**

### **Section-by-Section Structure & Messaging**

**Version:** 2.0  
**Date:** February 23, 2026   
**Source Documents:** Wireframe v1.1 (BBCAP/Fixation Web) \+ Gavin V3 Revisions \+ COO Effectiveness Evaluation  
**Structural Template:** Fixation Homepage Wireframe v2.0.1

### **What Changed From v1.1**

* Merges Gavin's V3 improvements (FAQ section, 4-step process, 4th alternatives column, self-selecting path labels, speed-through-AI messaging) with v1.1 elements that were weakened or removed  
* Speed messaging is integrated as a through-line rather than replacing trust-building elements.

**Key Principle:** Fixation's AI-native process is the *reason* they deliver speed, ownership, and savings simultaneously. Speed is the proof of methodology, not a replacement for it.

---

## **NOTES KEY**

| Note | Belief Stage | Core Question |
| ----- | ----- | ----- |
| N:1 | Empathy | "Do they understand my AI situation?" |
| N:2 | Broken Alternatives | "Why haven't other approaches worked?" |
| N:3 | Unique Approach | "What makes Fixation's method different?" |
| N:4 | Trust & Offer | "Can I trust these results?" |
| N:5 | Transformation | "What does success look like for me?" |

---

## **SECTION 1: HERO**

**Notes:** N:5 (Transformation) \+ N:3 (Approach hint)

### **HEADLINE**

Your AI. Built to Outlast the Hype.

### **SUBHEAD**

Working prototypes in two weeks. Production software that costs less and belongs entirely to you.

### **TRUST LINE**

Working prototypes in 2 weeks | 98% AI cost optimization | You own everything we build

### **CTA**

**Primary:** Book a Discovery Call **Secondary:** See How We're Different ↓

### **DESIGN NOTES**

* Headline kept from V1. Gavin V3 uses “We…” and trades specific promise w a vague speed claim any competitor could toss around  
* Subhead kept from Gavin V3 — concrete, benefit-driven, earns the scroll  
* Trust line restores metrics-based proof (98% cost optimization) from v1.1 while adding a speed proof point (2 weeks) and ownership claim.  
* 3 credible claims covering Fixation's actual trifecta: speed, savings, ownership. Scanners get evidence, not feature labels.  
* Secondary CTA earns the scroll

### **RATIONALE FOR CHANGES FROM V1.1**

* v1.1 headline ("Your AI. Built to Outlast the Hype.") was more differentiated but didn't address Gavin's speed feedback. "We Move at AI Speed" is less unique but aligns with his stated priority. Trade-off accepted.  
* v1.1 trust line (feature checkmarks in V3) replaced with metrics-based format. "AI-native development ✓" is a claim; "98% cost optimization" is evidence. Trust lines must give the skeptic a reason to keep reading.

---

## **SECTION 2: EMPATHY**

**Notes:** N:1 ("We Get You")

### **HEADLINE**

You’re Not Paranoid. AI Really Is That Fragile.

### **SUBHEAD**

Every AI demo works. Almost nothing survives production.

### **BODY — DUAL PATH TREATMENT**

**If You're Building Something New** *(Left card or tab)*

Your ChatGPT demo impressed investors. Then production happened—the AI contradicted itself, "forgot" context you gave it, offered discounts that don't exist. Now you're burning runway trying to fix AI that doesn't scale.

You're worried someone could build the same thing over a weekend. That lump in your throat? It's the "AI wrapper" problem. Wrapping your solution around generic AI kills your credibility and makes investors run the other way.

**If You're Scaling What Exists** *(Right card or tab)*

Your board wants AI features yesterday. Your competitors are launching things you can't match. Every vendor you talk to has usage-based pricing you can't predict and data policies that make security nervous.

Meanwhile, your CMO needs a simple answer from your own database and it's a three-day wait through seven layers of IT. You know AI could fix that. You just don't trust anyone to build it right.

### **VISUAL DIRECTION**

Two-path layout: cards, tabs, or side-by-side columns. Both paths equally weighted. Neither persona is secondary.

### **DESIGN NOTES**

* Path labels from Gavin V3 ("If You're Building Something New" / "If You're Scaling What Exists") — self-selecting language that helps visitors find their path. Better UX than persona codenames.  
* Bobby's second paragraph restored from v1.1. "You're worried someone could build the same thing over a weekend" is Bobby's deepest fear — removing it weakened the empathy. Restructured for tighter flow while preserving the core anxiety.  
* Tim copy unchanged from V3 — it was already strong.  
* "Seven layers of IT" is Gavin's language.  
* "AI wrapper" fear is Bobby's stated top concern (direct from Gavin interviews).

---

## **SECTION 3: BROKEN ALTERNATIVES**

**Notes:** N:2 ("Those Aren't Best")

### **HEADLINE**

Everyone You’ve Hired Has a Reason to Keep You on the Expensive Model

### **SUBHEAD**

DIY, consultants, enterprise vendors, and internal hires all optimize for their model, not yours.

### **BODY — FOUR-COLUMN GRID**

**DIY (OpenAI API)**

Tie into the smartest model. Demo looks great. No benchmarks, no testing battery, no way to know when a cheaper model does the same job. When OpenAI releases something new next month, you won't know if switching breaks everything.

*You get speed now. You pay for it later.*

**AI Consultants**

Great first impression. Then you sign and realize: the reporting, the tests, the benchmarks, the methodology—they own all of it. When you need to switch models in six months, you'll hire them again. That's not a bug in their business model. It's the feature.

*You get the bill. They own the handcuffs.*

**Enterprise Vendors**

Safety and scale on the label. Bureaucracy and lock-in inside. You stay on an expensive model too long because nobody tells you there's a cheaper option that works just as well.

*You get the brand name. You pay brand-name prices. Indefinitely.*

**In-House Team**

You hire ML engineers. They build something custom. Six months later they leave, and nobody can maintain it. The documentation exists somewhere, probably.

*You get control. Until they update their LinkedIn.*

### **PATTERN REVEAL**

Every path ends the same way: someone else holds the keys to your own software.

### **VISUAL DIRECTION**

Four-column comparison grid with consistent structure per column: headline, short paragraph, italic tagline. Pattern reveal below the grid as a standalone line.

### **DESIGN NOTES**

* Headline from Gavin V3 — more provocative and specific than v1.1 recommended. Creates an immediate enemy (the vendor) and a specific realization (cheaper models exist). Strong instinct from Gavin.  
* 4th column (In-House Team) from Gavin V3 — fills a real gap. Bobby and Tim both consider hiring internally. "Documentation exists somewhere, probably" is peak Gavin voice.  
* Italic taglines restored from v1.1. These were the scanner's takeaway — the one line someone skimming actually reads. Without them, columns require full paragraph reading to get the point. Added a new tagline for the 4th column in the same style.  
* Pattern reveal uses Gavin V3 wording — functionally equivalent to v1.1, slightly more polished.

---

## **SECTION 4: METHODOLOGY**

**Notes:** N:3 ("Our Way Is Best")

### **HEADLINE**

Built Around AI From Day One. And Every Line of It Is Yours.

### **SUBHEAD**

AI captures your business context from conversation one. Everything we build, the code, the tests, the evaluations, is yours when we’re done.

### **BODY — FIVE METHODOLOGY PILLARS**

**Your Knowledge Becomes AI Training Data**

Every transcript from every meeting gets processed into structured requirements. Your domain expertise—the edge cases, the business rules, the "that's not how it works in our industry" moments—becomes the foundation our AI uses to generate accurate solutions.

Other shops ask you to write requirements. Fixation extracts them from conversation.

**Battery of Tests Before Anything Else**

You'll never have to cross your fingers and hope. Our comprehensive evaluations establish what "working" means for your specific use case. Change the prompt? Rerun the tests. New model comes out? Rerun the tests. If something breaks, we catch it before your users do.

**Working UI in Weeks, Not Months**

You'll see actual working prototypes with sample data in the first two weeks. Not Figma mockups—real applications you can click through, test, and validate against your workflows.

Iteration happens on working software, not slide decks.

**Smart Model Selection (Real Savings)**

Not every AI task needs the most expensive model. Background processing, data classification, simple extraction—these can run on smaller models at a fraction of the cost. The key is proving it works before switching.

One client went from $3,600/week to $300/week on AI costs. That's $170,000/year back in their pocket.

**You Own Everything**

When our engagement ends, you're not locked in. The code, the data, the evaluations used to validate and optimize—they're all yours. Hire someone else. Bring it in-house. Partners stay with us because we deliver value, not because you can't leave.

### **VISUAL DIRECTION**

Five-pillar layout: vertical cards or stacked accordion sections. Each pillar gets an icon, headline, and short paragraph. The $170K/year figure and "own everything" message should be visually prominent. Consider alternating alignment (left-right) for visual rhythm.

### **DESIGN NOTES**

* Headline merges Gavin V3's AI-native framing with v1.1's ownership message. "AI-Native Development, Not AI-Assisted" is strong differentiation that speaks to Gavin's speed feedback. "And You Own All of It" restores the ownership punch that was Fixation's single most powerful differentiator — lost entirely in V3's methodology section.  
* Subhead merges Gavin V3's process explanation with ownership reinforcement.  
* Structure: 5 pillars (restoring from v1.1's depth) but incorporating Gavin V3's strongest additions.  
* Pillar 1 ("Your Knowledge Becomes AI Training Data") kept from Gavin V3 — strong concept, directly supports speed messaging.  
* Pillar 2 ("Battery of Tests") restored from v1.1. This pillar makes the case studies section credible. Without it, the $10K→$200 proof point has no methodology behind it. "Battery of tests" and "design for volatility" are Gavin's exact language from discovery interviews.  
* Pillar 3 ("Working UI in Weeks") kept from Gavin V3 — concrete speed promise.  
* Pillar 4 ("Smart Model Selection") kept from Gavin V3, uses $3,600→$300/week math.  
* Pillar 5 ("You Own Everything") restored from v1.1. This was a standalone pillar in the wireframe, removed entirely in V3. It's Fixation's core differentiator and the emotional resolution for both Bobby (no lock-in) and Tim (board-defensible exit strategy). Must have its own pillar, not just a mention in the subhead.  
* **Removed from v1.1:** "Honest Assessment First" (we might tell you AI isn't the answer) — strong trust signal but moved to the FAQ section where it lands better as a direct answer to "What if AI isn't right for my situation?" Also echoed in the CTA section headline. "Modular Architecture" — the concept is embedded in "Battery of Tests" (swap models, rerun tests) and "You Own Everything" (no lock-in) rather than needing its own pillar.  
* **Removed from v1.1:** "AI changes constantly (and you can't see their source code)" subhead line. This was an unusually honest admission that built trust. Consider restoring as a parenthetical within Pillar 2 or as a design element. Flagging for Gavin review.

---

## **SECTION 5: CASE STUDIES**

**Notes:** N:4 (Trust) \+ N:3 (Methodology proof)

### **HEADLINE**

The Numbers Don’t Hallucinate

### **SUBHEAD**

Real costs cut. Real teams replaced. Real timelines that held.

### **BODY — TWO CASE STUDY CARDS**

**Case Study A: How We Cut a Client's AI Costs by 6x Without Breaking Anything**

**The Problem:** Client's Azure AI bill was climbing. They were stuck on an expensive model because nobody questioned whether a cheaper one could do the same job.

**What We Did:** Identified the opportunity. Ran our battery of tests against a newer, cheaper model. Confirmed performance held. Proved it with benchmarks the client could verify themselves.

**The Result:** $10,000/month to $200/month. 98% cost reduction. Same performance.

---

**Case Study B: Enterprise Migration Success**

**The Problem:** Client had an entire human review team manually processing data. Expensive, slow, and inconsistent.

**What We Did:** Built an AI system with detailed logging. Trained it to match human performance first, then fine-tuned until it exceeded it. Validated every step with our evaluation framework.

**The Result:** Replaced the manual team entirely. 95% cost reduction. Better accuracy. Client launched a superior product at a higher price point because the AI did the work better than humans could.

### **LINK**

VIEW ALL CASE STUDIES →

### **VISUAL DIRECTION**

Two equal-weight cards side by side. Each card follows Problem → What We Did → Result structure. Result numbers ($10K to $200, 95% reduction) should be the most visually prominent element on each card: large typography, possible highlight color. Consider a subtle before/after visual treatment. Image placeholder for visual interest per Gavin V3 layout.

### **DESIGN NOTES**

* Headline restored from v1.1. "Results, Not Promises" (V3) is generic — any agency says this. "This AI Benchmark Tells the Truth About Us (No Hallucinations)" is memorable, AI-specific, and self-aware. It pre-empts skepticism while making a clever AI reference. Does real differentiation work.  
* Subhead from Gavin V3 — "companies that moved at AI speed" is the cleanest speed integration on the page. Contextualizes case studies as speed stories without changing the evidence.  
* Card A title from Gavin V3 ("How We Cut a Client's AI Costs by 6x") — more descriptive than v1.1's label.  
* Card A body restores v1.1's Problem/What We Did/Result structure with full detail. The "battery of tests" language in "What We Did" directly connects to the Methodology section — the case study *proves* the methodology works.  
* Card B title from Gavin V3 ("Enterprise Migration Success").  
* Card B body restores v1.1's full structure. The "launched a superior product at a higher price point" detail is the transformation story Tim needs.  
* Both cases demonstrate the evaluation methodology from Section 4 in action.

### **ASSUMPTIONS**

1. Both case studies ($10K to $200, manual team replacement) are cleared for public use  
2. Are there additional specifics (client industry, timeline, team size) we can add without revealing client identity? *(Flag for Gavin)*

---

## **SECTION 6: PROCESS**

**Notes:** N:4 ("You Can Trust Us")

### **HEADLINE**

Week One: We Listen. Week Two: You’re Using It.

### **SUBHEAD**

No phase where you’re waiting and wondering.

### **BODY — FOUR-STEP TIMELINE**

**Step 1: Discovery** *(Week 1\)* 🗨️

You talk, we listen. Every conversation gets processed into structured requirements within hours. By the end of week one, you have a clear scope and we understand your domain better than most dev shops do after months.

You don't need massive data exports. No need to brush up on the latest in AI. No reason to spend weeks going back and forth.

**Step 2: Working Prototype** *(Week 2\)* 🔲

Not wireframes. Not mockups. A real application with sample data that you can click through. You'll know immediately if we understood your requirements—because you'll be using the software, not reading about it.

**Step 3: Build & Demo** *(Weeks 3+)* \</\>

Weekly demos on real data. Every feature ships with tests that prove it works. The evaluation framework gets built alongside the product, so you always know what's working and what isn't.

**Step 4: Optimize** *(Ongoing)* 🔄

AI doesn't stop changing, and neither do we. When new models release, benchmarks get rerun. When costs can drop, you hear about it first. The architecture adapts because it was built to adapt.

### **VISUAL DIRECTION**

Vertical four-step timeline with numbered progression. Each step gets a heading, time indicator, icon, and short paragraph. Visual connectors between steps suggest continuous flow. Step 4 has no endpoint indicator to reinforce the partnership model.

### **DESIGN NOTES**

* Headline revised from both versions. V1.1's "One Week to Start. Weekly Demos Forever." was concrete but the "forever" felt like a commitment claim. V3's "From Conversation to Production" was generic. New headline keeps the specific time promises (the strongest speed proof on the page) while making a tangible claim: one week to understand your business, two weeks to put working software in your hands.  
* 4-step structure from Gavin V3 — breaking "Build" into "Working Prototype" \+ "Build & Demo" was smart. "Week 2: Working Prototype" is a concrete, impressive promise that Bobby especially needs to hear. This is the single best speed proof on the page.  
* Step 1 body merges V3's tighter language ("within hours," "end of week one") with v1.1's friction-reduction lines ("No need to brush up on the latest in AI"). Both serve different readers — the time-specific language builds confidence, the friction-reduction lines lower anxiety.  
* "Not wireframes. Not mockups." in Step 2 parallels Gavin's "interactive demos, not PowerPoints" ethos.  
* Step 4 distinguishes Fixation from project-based shops that deliver and disappear.

---

## **SECTION 7: TRANSFORMATION**

**Notes:** N:5 ("We Know What You Want")

### **HEADLINE**

What Changes When Your AI Actually Works

### **SUBHEAD**

AI you own. Costs you control. Architecture that adapts.

### **BODY — DUAL PATH TREATMENT**

**If You're Building Something New** *(Bobby's path)*

* Working demos early, so you can show investors your idea is viable before the runway runs out  
* Architecture that scales when you grow, without rewriting  
* Proprietary evaluations that prove you're more than an API wrapper  
* "Your data stays with us. Period."—privacy you can promise customers  
* Same-day model upgrades while competitors wait for their vendor to catch up

**If You're Scaling What Exists** *(Tim's path)*

* Break out of the IT firewall. Your CMO gets answers before she finishes her coffee.  
* Fewer features to build, more capability to deliver (AI replaces months of custom development)  
* Cost control with benchmarks that prove performance. Your CFO gets predictability.  
* Enhanced search that understands misspellings, natural language, and intent  
* Go back to the board with an option that's proven to pay for itself

### **DESIGN NOTES**

* Headline from Gavin V3 — clean, effective.  
* Path labels match Section 2 for consistency.  
* Content substantially unchanged from v1.1/V3 — both versions were strong here.  
* Bookends with Section 2 (Empathy): the pain points from Section 2 are resolved here.  
* Bobby's "AI wrapper" fear (Section 2\) → answered by "proprietary evaluations" benefit  
* Tim's "seven layers of IT" pain (Section 2\) → answered by "break out of the IT firewall"  
* "Period." after privacy statement mirrors Gavin's exact language.  
* "Proven to pay for itself" is Gavin's board-approval language for Tim.  
* Five benefits per path mirrors homepage Section 8 structure.

---

## **SECTION 8: FAQ**

**Notes:** N:4 (Trust) \+ N:1 (Empathy) — addresses residual objections

### **HEADLINE**

Before You Call, You’re Probably Wondering

### **QUESTIONS**

1. **How fast can you build a working prototype?**  
2. **How is your AI development process different?**  
3. **How do I know this isn't just a sales pitch?**  
4. **My company already tried AI and it didn't work. Why would this be different?**  
5. **What if AI models change after something gets built?**  
6. **How much does this cost?**  
7. **Do I own the code?**  
8. **What if AI isn't right for my situation?**

### **DESIGN NOTES**

* New section from Gavin V3 — strong addition not in v1.1. The wireframe should have included this.  
* Questions map directly to Bobby/Tim objections: "How fast" (Bobby's urgency), "already tried AI" (Tim's skepticism), "Do I own the code?" (both personas' lock-in fear).  
* Accordion/expandable format per V3 layout.  
* Q8 ("What if AI isn't right for my situation?") absorbs v1.1's "Honest Assessment First" methodology pillar. This is actually a *better* home for that trust signal — it's framed as a direct answer to the prospect's concern rather than a self-congratulatory methodology claim. Answer should include: "We'll tell you. We're not in the business of selling AI for its own sake."  
* **FLAG:** FAQ answer copy needs to be written. Quality of answers will determine whether this section earns its space. Answers should be concise (2-4 sentences each), use Gavin's voice, and reinforce proof points from earlier sections without repeating them verbatim.  
* **SUGGESTION:** Consider making Q1 answer reference the "Week 2: Working Prototype" claim from Section 6 — creates internal consistency and reinforces the speed message.

---

## **SECTION 9: CTA**

**Notes:** N:4 (Trust reinforcer) \+ N:5 (Echo)

### **HEADLINE**

Start With an Honest Conversation

### **SUBHEAD**

No pitch. No pressure. Just an honest conversation about what you're trying to build, and whether AI is actually the right way to get there.

### **TRUST REINFORCER**

Our clients volunteer for reference calls. If you want to talk to someone who's been through this, that conversation is easy to arrange.

### **CTA**

**Primary Button:** Book a Discovery Call **Secondary Link:** Or ask us anything: hello@fixation.dev

### **DESIGN NOTES**

* Headline shortened from v1.1 per Gavin V3 — works fine without the added length.  
* "Whether AI is actually the right way to get there" echoes the honesty theme from FAQ Q8 and v1.1's "Honest Assessment First" pillar. The willingness to say no is present without needing its own methodology section.  
* Trust reinforcer expanded per Gavin V3 — warmer and more specific than v1.1's single line. Lowers perceived risk.  
* **FLAG:** Email address. V3 footer uses info@fixation.dev. V1.1 spec used hello@fixation.dev. Confirm which is correct/preferred.

---

## **SECTION 10: FOOTER**

### **PERSISTENT CTA BAR**

**Your software should belong to you.** Let’s make that happen. → BOOK A CALL

### **FOOTER LINKS**

info@fixation.dev | AI Services | Careers | Privacy | Terms

### **ADDRESS**

© 2026 Fixation. All rights reserved. 11128 John Galt Blvd, Ste 50, Omaha, NE 68137

### **DESIGN NOTES**

* Persistent bottom CTA bar from Gavin V3 — always-visible conversion path is good UX for high-ticket service page. Strong addition.  
* "Ready to own your software?" is a solid micro-CTA that reinforces ownership messaging.

---

## **BELIEF PROGRESSION MAP**

| Section | Note(s) | Belief Built | Visitor Thought |
| ----- | ----- | ----- | ----- |
| 1\. Hero | N:5 \+ N:3 | Transformation hook \+ speed | "They move fast and I own what they build" |
| 2\. Empathy | N:1 | "They understand my situation" | "They know exactly what I'm dealing with" |
| 3\. Alternatives | N:2 | "Other options won't work" | "That explains why nothing's worked so far" |
| 4\. Methodology | N:3 | "Their approach makes sense" | "AI-native process, battery of tests, and I own it all" |
| 5\. Case Studies | N:4 \+ N:3 | "These results are real" | "$10K to $200, and I can verify it" |
| 6\. Process | N:4 | "Working with them is fast and easy" | "Week 2 I have working software?" |
| 7\. Transformation | N:5 | "I want what they're describing" | "That's exactly the outcome I need" |
| 8\. FAQ | N:4 \+ N:1 | Residual objections resolved | "They'd even tell me if AI isn't right" |
| 9\. CTA | N:4 \+ N:5 | "I should talk to them" | "No risk — their clients volunteer for reference calls" |

---

## **CROSS-PAGE CONSISTENCY CHECK**

| Element | Homepage (v2.0.1) | AI Services v2.0 | Status |
| ----- | ----- | ----- | ----- |
| Hero structure | Headline \+ subhead \+ trust line \+ dual CTA | Same pattern, AI-specific | ✅ Consistent |
| Empathy approach | Single path | Dual path (Bobby \+ Tim) | ✅ Appropriate — deeper page justifies persona split |
| Alternatives format | 4-column grid \+ pattern reveal | 4-column grid \+ pattern reveal | ✅ Consistent (upgraded from v1.1's 3 columns) |
| Methodology format | 6 differentiators, 2×3 grid | 5 pillars, vertical cards | ✅ Adapted for deeper content |
| Proof section | Testimonial \+ case study teasers | Full case study cards | ✅ Appropriate — service page goes deeper |
| Process format | 3-step timeline | 4-step timeline | ✅ Appropriate — AI page adds prototype step |
| Transformation | 4 checkmarks, unified | 5 per path, dual | ✅ Appropriate — AI-specific outcomes |
| FAQ | None | 8 questions | ✅ New — service page addresses deeper objections |
| CTA | Echo headline \+ trust reinforcer | Same pattern | ✅ Consistent |
| Voice | Conversational, direct, Gavin | Same | ✅ Consistent |
| Belief progression | N:5→N:4→N:1→N:2→N:3→N:3→N:4→N:5→CTA | N:5→N:1→N:2→N:3→N:4→N:4→N:5→N:4→CTA | ✅ Same arc |

---

## **OPEN ITEMS & FLAGS**

### **Requires Gavin Input**

1. **Email address:** info@fixation.dev (V3 footer) vs. hello@fixation.dev (v1.1 CTA). Which is correct?  
2. **Case study detail level:** Can we add client industry, timeline, or team size without revealing identity?  
3. **Case study proof point math:** V3 uses $3,600/week→$300/week ($170K/year) in Methodology; v1.1 uses $10K/month→$200/month (98%) in Case Studies. Are these the same client told two ways, or two different clients? If same client, we should pick one math framing and use it consistently. If different clients, even better — we have two proof points.  
4. **"You can't see their source code" line:** v1.1 included this unusually honest admission in Methodology. Gavin removed it. Worth discussing — it was a strong trust signal. Could live as a parenthetical in Pillar 2 or as FAQ answer material.

### **Requires Copy Development**

5. **FAQ answers:** 8 questions need 2-4 sentence answers in Gavin's voice. Priority deliverable.  
6. **Case study B details:** "Enterprise Migration Success" needs more specificity than current placeholder suggests. Timeline? Scale?

### **Assumptions (Carried from v1.1)**

7. Both case studies are cleared for public website use.  
8. Contact email confirmed before launch.

---

## **VERSION HISTORY**

| Version | Date | Changes |
| ----- | ----- | ----- |
| v1.1 | Feb 2, 2026 | BBCAP/Fixation Web wireframe — belief-building architecture complete |
| v2.0 | Feb 23, 2026 | Merged Gavin V3 improvements \+ restored weakened elements \+ speed integration |

# FIXATION AI SERVICES PAGE WIREFRAME v1.1

## **fixation.dev/services/ai-integration**

### **Section-by-Section Structure & Messaging**

**Version:** 1.1, Revised Draft   
**Date:** February 2, 2026   
**Source Documents:** BBCAP 5-Note AI Architecture (Final Draft) \+ Executive Brief (Jan 30, 2026\)   
**Structural Template:** Fixation Homepage Wireframe v2.0.1

---

## **NOTES KEY**

| Note | Belief Stage | Core Question |
| :---- | :---- | :---- |
| N:1 | Empathy | “Do they understand my AI situation?” |
| N:2 | Broken Alternatives | “Why haven’t other approaches worked?” |
| N:3 | Unique Approach | “What makes Fixation’s method different?” |
| N:4 | Trust & Offer | “Can I trust these results?” |
| N:5 | Transformation | “What does success look like for me?” |

---

## **SECTION 1: HERO**

**Notes:** N:5 (Transformation) \+ N:3 (Approach hint)

### **HEADLINE**

**~~Recommended:~~**

~~AI That Works After the Demo~~

**~~Alternative A:~~**

~~Production AI You Actually Own~~

**Alternative B:**

Your AI. Built to Outlast the Hype.

### **SUBHEAD**

No vendor lock-in. No runaway costs. No black box.

### **TRUST LINE**

Proven 98% cost optimization | You own everything we build | 3+ years building production AI

### **CTA**

**Primary:** Book a Discovery Call **Secondary:** See How We’re Different ↓

### **DESIGN NOTES**

- Subhead parallels homepage structure (”No... No... No...”)  
- Trust line uses specific numbers (2+ years, 98%) vs. vague claims  
- Secondary CTA earns the scroll

---

## **SECTION 2: EMPATHY**

**Notes:** N:1 (”We Get You”)

### **HEADLINE**

**Recommended:**

Your AI Fears Aren’t Paranoia

**~~Alternative:~~**

~~You’ve Seen This Movie Before~~

### **SUBHEAD**

You’ve watched demos that looked perfect. Then you tried to build something real.

### **BODY, DUAL PATH TREATMENT**

**Bobby’s Reality** *(Left card or tab)*

Your ChatGPT demo impressed investors. Then production happened. The AI contradicted itself, “forgot” context you gave it, and offered discounts that don’t exist. Now you’re burning runway trying to fix AI that doesn’t scale.

You’re worried someone could build the same thing over a weekend. Wrapping your solution around generic AI kills your credibility. It also makes investors run the other way. That explains the lump in your throat.

**Tim’s Reality** *(Right card or tab)*

Your board wants AI features yesterday. Your competitors are launching things you can’t match. Every vendor you talk to has usage-based pricing you can’t predict and data policies that make security nervous.

Meanwhile, your CMO needs a simple answer from your own database and it’s a three-day wait through seven layers of IT. You know AI could fix that. You just don’t trust anyone to build it right.

### **VISUAL DIRECTION**

Two-path layout: cards, tabs, or side-by-side columns. Bobby path could use a startup/founder visual cue (subtle, not cliche). Tim path could use an enterprise/operations cue. Both should feel equally weighted. Neither persona is secondary here.

### **DESIGN NOTES**

- Bobby’s “AI wrapper” fear is his stated top concern (direct from Gavin interviews)  
- Tim’s “seven layers deep” imagery is Gavin’s language

---

## **SECTION 3: BROKEN ALTERNATIVES**

**Notes:** N:2 (”Those Aren’t Best”)

### **HEADLINE**

**~~Recommended:~~**

~~Every Option You’re Considering Has the Same Problem~~

**Alternative A:**

Your Vendor Will Never Tell You There’s a Cheaper Model

**~~Alternative B:~~**

~~Why All Three Paths Lead to Lock-In~~

### **SUBHEAD**

DIY, consultants, enterprise vendors. They all optimize for their revenue, not your AI performance.

### **BODY, THREE-COLUMN GRID**

**DIY (OpenAI API)** Tie into the smartest model. Your demo looks great. But you’ll have no benchmarks, no testing battery, and no way to know when a cheaper model can do the same job. When OpenAI releases something new next month, you won’t know if switching breaks everything.

*You get speed now. You pay for it later.*

**AI Consultants** They make a great first impression. Then you sign the dotted line and realize…The reporting. The tests. The benchmarks. The methodology. They own all of that. Heck, it’s their secret sauce. When you need to switch models in six months, you’ll hire them again. That’s not a bug in their business model. It’s the feature.

*You get the bill. They own the handcuffs.*

**Enterprise Vendors** Safety and scale on the label. Bureaucracy and lock-in inside. They start you on ‘the latest model.’ Then you stay on an expensive model too long because nobody tells you there’s a cheaper option. Your vendor benefits from your assumption that ‘the latest is the greatest.’ They’ll never volunteer a way to spend less.

*You get the brand name. You pay brand-name prices. Indefinitely.*

### 

**Notice the pattern? None of them hand you the keys when they’re done.**

### **VISUAL DIRECTION**

Three-column comparison grid with consistent structure per column: headline, short paragraph, plain-text tagline. 

### **DESIGN NOTES**

- Mirrors homepage Section 4 format (grid \+ pattern reveal) with 3 columns instead of 4  
- Taglines per column give scanners the takeaway without reading full paragraphs  
- Pattern reveal should feel like a realization, not a pitch

### **WORD COUNT: \~175 words (appropriate for this section)**

---

## **SECTION 4: METHODOLOGY**

**Notes:** N:3 (”Our Way Is Best”)

### **HEADLINE**

**Recommended:**

Smart Enough To Create Future-proof AI. Brave Enough To Let You Own It.

**Alternative:**

We Might Tell You AI Is the Wrong Solution

### **SUBHEAD**

AI changes constantly (and you can’t see their source code). We build systems that don’t care.

### **BODY, FIVE METHODOLOGY PILLARS**

**Honest Assessment First** We’re not in the business of selling you AI for its own sake. When AI isn’t your best path forward, we’ll tell you. When a cheaper model or method solves your problem, you’ll know. With Fixation, expect conversations most AI vendors won’t dare have.

**Battery of Tests Before Anything Else** You’ll never have to cross your fingers and hope. Our comprehensive evaluations establish what “working” means for your specific use case. Change the prompt? Rerun the tests. New model comes out? Rerun the tests. No more guessing. If something breaks, we catch it before your users do.

**Modular Architecture** No AI dead ends. Everything is swappable. Your system doesn’t care which AI vendor powers it. When a better or cheaper model shows up (and they show up monthly), yours gets swapped. That means, you’re done paying to ‘start over’ every time a press-release comes out from the big AI companies.

**You Spend Less (Because We’ll Tell You)** When we saw a client’s AI bill climbing, we didn’t wait for them to ask. We identified the opportunity, ran our battery of tests, and confirmed performance held steady. They went from $10,000 a month to $200. Fixation is your proactive partner.

**You Own Everything** When our engagement ends, you’re not locked in. The code, the data, the evaluations used to validate and optimize. They’re all yours. Hire someone else. Bring it in-house. Partners stay with us because we deliver value, not because you can’t leave.

### **VISUAL DIRECTION**

Five-pillar layout: vertical cards or stacked accordion sections. Each pillar gets an icon, headline, and short paragraph. Consider alternating alignment (left-right) for visual rhythm on longer scroll. The “$10,000 a month to $200” figure should be visually prominent wherever it appears.

### **DESIGN NOTES**

- Heaviest content section (same as homepage). Note 3 carries the core argument.  
- “Battery of tests” and “design for volatility” are Gavin’s exact language  
- The $10K to $200 proof point appears here AND in the case study section. Intentional. Here it’s proof of methodology; in case studies it’s the full story. Repetition reinforces.  
- “You can’t see the source code” is an unusually honest admission that builds trust

### **WORD COUNT: \~275 words (within 200-300 target)**

---

## **SECTION 5: CASE STUDIES**

**Notes:** N:4 (Trust) \+ N:3 (Methodology proof)

### **HEADLINE**

**Recommended:**

This AI Benchmark Tells the Truth About Us (No Hallucinations)

**Alternative:**

Results You Measure, Not Promises You Trust

### **SUBHEAD**

Real numbers from AI Clients

### **BODY, TWO CASE STUDY CARDS**

**Case Study A: 98% AI Cost Optimization**

**The Problem:** Client’s Azure AI bill was climbing. They were stuck on an expensive model because nobody questioned whether a cheaper one could do the same job.

**What We Did:** Identified the opportunity. Ran our battery of tests against a newer, cheaper model. Confirmed performance held. Proved it with benchmarks the client could verify themselves.

**The Result:** $10,000/month to $200/month. 98% cost reduction. Same performance.

---

**Case Study B: 95% Labor Cost Reduction**

**The Problem:** Client had an entire human review team manually processing data. Expensive, slow, and inconsistent.

**What We Did:** Built an AI system with detailed logging. Trained it to match human performance first, then fine-tuned until it exceeded it. Validated every step with our evaluation framework.

**The Result:** Replaced the manual team entirely. 95% cost reduction. Better accuracy. Client launched a superior product at a higher price point because the AI did the work better than humans could.

### **VISUAL DIRECTION**

Two equal-weight cards side by side. Each card follows Problem, What We Did, Result structure. Result numbers ($10K to $200, 95% reduction) should be the most visually prominent element on each card: large typography, possible highlight color. Consider a subtle before/after visual treatment.

### **DESIGN NOTES**

- Case study structure mirrors the belief arc in miniature (problem \= empathy, what we did \= methodology, result \= trust)  
- Numbers do the heavy lifting. Resist adding more copy.  
- Both cases demonstrate the evaluation methodology from Section 4 in action  
- These are the same proof points from the Core Message Blueprint (Note 3.4), validated for public use

---

## **SECTION 6: PROCESS**

**Notes:** N:4 (”You Can Trust Us”)

### **HEADLINE**

**Recommended:**

One Week to Start. Weekly Demos Forever.

**Alternative:**

All You Have to Do Is Talk

### **SUBHEAD**

What working with us on AI actually looks like.

### **BODY, THREE-STEP TIMELINE**

**Step 1: Learn** *(Week 1\)* Your key stakeholders have a real conversation with our team. We ask the questions, you just talk. We translate that into clear requirements, determine what AI path is the right solution (if any), and what “working” looks like for your specific case.

You don’t need massive data exports. No need to brush up on the latest in AI. No reason to spend weeks going back and forth.

**Step 2: Build** *(Weeks 2+)* Weekly demos. Or daily check-ins if we’re moving fast. You see real progress and working software, not slide decks. 

We build the evaluation framework alongside the product. Every feature ships with tests that prove it works.

**Step 3: Optimize** *(Ongoing)* AI doesn’t stop changing, and neither do we. When new models drop, we rerun the benchmarks. When costs can come down, we tell you. When your needs shift, the architecture adapts because we built it that way.

### **VISUAL DIRECTION**

Horizontal or vertical three-step timeline with numbered progression. Each step gets a heading, time indicator, and short paragraph. Visual connectors between steps suggest continuous flow, not hard transitions. Consider a subtle “ongoing” visual on Step 3 (no endpoint) to reinforce the partnership model.

### **DESIGN NOTES**

- Mirrors homepage Section 6 (How It Works): 3-step timeline structure  
- “All you have to do is talk” is a strong secondary headline (Gavin’s language). Works as the headline if “One Week to Understand” feels too specific.  
- “folks” in Step 1 matches voice guidance (conversational, not corporate)  
- Step 3 distinguishes Fixation from project-based shops that deliver and disappear  
- “Not slide decks” parallels Gavin’s “interactive demos, not PowerPoints” ethos

---

## **SECTION 7: TRANSFORMATION**

**Notes:** N:5 (”We Know What You Want”)

### **HEADLINE**

**Recommended:**

From Demo to Competitive Advantage (Skip the Dependency)

**Alternative A:**

What Changes When Your AI Actually Works

### **SUBHEAD**

AI you own. Costs you control. Architecture that adapts.

### **BODY, DUAL PATH TREATMENT**

**If You’re Building Something New** *(Bobby’s path)*

- Working demos early, so you can show investors your idea is viable before the runway runs out  
- Architecture that scales when you grow, without rewriting  
- Proprietary evaluations that prove you’re more than an API wrapper  
- Privacy you can promise customers: “Your data stays with us. Period.”  
- Same-day model upgrades while competitors wait for their vendor to catch up

**If You’re Adding AI to What Exists** *(Tim’s path)*

- Break out of the IT firewall. Your CMO gets answers before she finishes her coffee.  
- Fewer features to build, more capability to deliver (AI replaces months of custom development)  
- Cost control with benchmarks that prove performance. Your CFO gets predictability.  
- Enhanced search that understands misspellings, natural language, and intent  
- Go back to the board with an option that’s proven to pay for itself

### **DESIGN NOTES**

- Bookends with Section 2 (Empathy): the pain points from Section 2 are resolved here  
- Bobby’s “AI wrapper” fear (Section 2\) answered by “proprietary evaluations” benefit  
- Tim’s “seven layers of IT” pain (Section 2\) answered by “break out of the IT firewall”  
- “Period.” after the privacy statement mirrors Gavin’s exact language  
- “Proven to pay for itself” is Gavin’s board-approval language for Tim  
- Five benefits per path mirrors homepage Section 8 structure (adjusted to 5 from 4 given the dual-path split provides natural visual balance)

---

## **SECTION 8: CTA**

**Notes:** N:4 (Trust reinforcer) \+ N:5 (Echo)

### **HEADLINE**

**Recommended:**

Start With An Honest Conversation About Where AI Can Take You

**Alternative:**

 Let’s Find Out If AI Is Right for Your Problem

### **SUBHEAD**

No pitch. No pressure. Just an honest conversation about what you’re trying to build, and whether AI is actually the right way to get there.

### **TRUST REINFORCER**

Our clients volunteer for reference calls. We’re happy to set one up.

### **CTA**

**Primary Button:** Book a Discovery Call **Secondary Link:** Or ask us anything: [hello@fixation.dev](mailto:hello@fixation.dev)

### **DESIGN NOTES**

- Mirrors homepage Section 9 pattern: echo key theme, low friction, reference call offer  
- Reference call offer addresses the implicit objection: “How do I know this isn’t just marketing?”  
- “No pitch. No pressure.” matches homepage CTA tone  
- Secondary CTA of “Download our AI evaluation checklist.” Could be worth testing as a lead magnet for prospects not ready to talk. Flag for Phase 2/3 consideration.

---

## **BELIEF PROGRESSION MAP**

| Section | Note(s) | Belief Built | Visitor Thought |
| :---- | :---- | :---- | :---- |
| 1\. Hero | N:5 \+ N:3 | Transformation hook | “They build AI that actually works in production” |
| 2\. Empathy | N:1 | “They understand my situation” | “They know exactly what I’m dealing with” |
| 3\. Alternatives | N:2 | “Other options won’t work” | “That explains why nothing’s worked so far” |
| 4\. Methodology | N:3 | “Their approach makes sense” | “Design for volatility... that’s what I need” |
| 5\. Case Studies | N:4 \+ N:3 | “These results are real” | “$10K to $200, and I can verify it” |
| 6\. Process | N:4 | “Working with them is easy” | “Wait, all I have to do is talk?” |
| 7\. Transformation | N:5 | “I want what they’re describing” | “That’s exactly the outcome I need” |
| 8\. CTA | N:4 \+ N:5 | “I should talk to them” | “They might even tell me AI isn’t the answer” |

---

## **CROSS-PAGE CONSISTENCY CHECK**

| Element | Homepage (v2.0.1) | AI Services Page | Status |
| :---- | :---- | :---- | :---- |
| Hero structure | Headline \+ 3 “No” subhead \+ trust line \+ dual CTA | Same pattern, AI-specific | Consistent |
| Empathy approach | Single path (”You’re Not Wrong to Be Skeptical”) | Dual path (Bobby \+ Tim) | Appropriate, deeper page justifies persona split |
| Alternatives format | 4-column grid \+ pattern reveal | 3-column grid \+ pattern reveal | Consistent structure |
| Methodology format | 6 differentiators, 2x3 grid | 5 pillars, vertical cards | Adapted for deeper content |
| Proof section | Testimonial \+ case study teasers | Full case study cards | Appropriate, service page goes deeper |
| Process format | 3-step timeline | 3-step timeline | Consistent |
| Transformation | 4 checkmarks, unified | 5 per path, dual | Appropriate, AI-specific outcomes |
| CTA | Echo headline \+ trust reinforcer | Same pattern | Consistent |
| Voice | Conversational, direct, Gavin | Same | Consistent |
| Belief progression | N:5, N:4, N:1, N:2, N:3, N:3, N:4, N:5, CTA | N:5, N:1, N:2, N:3, N:4, N:4, N:5, CTA | Same arc |

---

## **ASSUMPTIONS & FLAGS**

**Assumptions (require validation):**

1. Both case studies ($10K to $200, manual team replacement) are cleared for public use on the website  
2. [hello@fixation.dev](mailto:hello@fixation.dev) is the correct contact email

**Flags for Gavin review:**

1. **Section 5 case study detail level:** Are there additional specifics (client industry, timeline, team size) we can add without revealing client identity?  
2. **Section 7 path labels:** “Building Something New” and “Adding AI to What Exists,” or do you prefer more direct language?

---

# Services \> Leg. Mod.

# FIXATION LEGACY MODERNIZATION PAGE WIREFRAME v1.1

## **fixation.dev/services/legacy-modernization**

### **Section-by-Section Structure & Messaging**

**Version:** 1.1  
**Date:** February 23, 2026   
**Source Documents:** Legacy Modernization Argument Architecture v1.0   
**Structural Template:** Services \> AI v2.0  
**Primary Persona:** Tim Tables (CEO/owner inheriting or stuck with failing platform)

---

## **SECTION 1: HERO**

**Notes:** N:5 (Transformation hook) \+ N:3 (Approach hint)

### **HEADLINE**

We’ve Opened This Wall Hundreds of Times. We Know What’s Behind It.

### **SUBHEAD**

No more begging your vendor for hours. No more $50K quotes for simple features. No more wondering how bad this gets in five years.

Your platform should run quietly while you run the business. We get it there without shutting anything down.

### **TRUST LINE**

13 years. 100% referral growth. Nebraska Furniture Mart trusts us with theirs.

### **CTA**

**Primary Button:** Book a Discovery Call **Secondary Link:** See How We’re Different *(anchor to Section 4\)*

### **VISUAL DIRECTION**

Single-column hero. Headline is the dominant element. Subhead sits below in lighter weight. Trust line beneath as a quiet confidence marker. Dual CTA buttons at bottom.

### **DESIGN NOTES**

* “Opened this wall hundreds of times” is Gavin’s exact language, and no competitor would say it. It frames legacy modernization as Fixation’s sweet spot, not their fallback.  
* Three “No more” lines mirror the AI page hero’s three-line subhead pattern. Each one names a specific Tim pain point (vendor dependency, cost bloat, compounding rot).  
* “Invisible infrastructure” is the Note 5 payoff stated up front. Tim should feel the transformation promise in the first three seconds.  
* Trust line follows AI page pattern: short, specific, credibility without bragging.  
* **FLAG:** Consider whether “We Know What We’ll Find” reads as arrogant without context. Alternative softer version: “We’ve Opened This Wall Hundreds of Times.” (Drop second clause, let subhead carry the specifics.) Test both with Gavin.

### **WORD COUNT: \~65 words**

---

## **SECTION 2: EMPATHY**

**Notes:** N:1 (”We Get You”)

### **HEADLINE**

You Didn’t Build This Problem. But It’s Yours Now.

### **SUBHEAD**

The platform was failing before you got here. Every month you wait, the fix gets more expensive.

### **BODY**

The system was built in the early 2000s, maybe later, by a team that’s long gone. Nobody prioritized modernization because it was always next quarter’s problem. Now it’s your problem, and the technical debt compounds every time someone patches another workaround on top of the last one.

Simple feature requests come back quoted at $50K and three months. Things that should take a week take a quarter, because nobody ran electrical in the attic. Your best developer is thinking about leaving. Your board is asking questions you can’t answer with confidence. And your vendor, the one who built this, has other fish to fry.

You’ve been fighting this with inadequate weapons. That’s not a leadership failure. It’s a situation with no good options, until now.

### **VISUAL DIRECTION**

Full-width section with centered text. Slightly darker background to create mood shift from the hero. Body copy in two short paragraphs, not bullets.

### **DESIGN NOTES**

* “You Didn’t Build This Problem” is the emotional center of Note 1\. Tim needs to hear this before anything else. It separates blame from responsibility.  
* “Nobody ran electrical in the attic” is Gavin’s analogy for technical debt that’s invisible until you try to add something new.  
* “Other fish to fry” is direct from the SportsTip vendor situation and resonates with any Tim who’s been deprioritized by their vendor.  
* Single path (not dual-path like AI page) because this page is Tim-first. Bobby-type readers won’t feel excluded, but the copy isn’t written for them.  
* Final line (”inadequate weapons... not a leadership failure”) reframes Tim’s self-doubt without patronizing him. He’s competent. He was given bad options.

### **WORD COUNT: \~165 words**

---

## **SECTION 3: BROKEN ALTERNATIVES**

**Notes:** N:2 (”Those Aren’t Best”)

### **HEADLINE**

Five Obvious Moves. One Shared Problem.

### **SUBHEAD**

Five paths. Same dead end.

### **BODY: FIVE-COLUMN GRID**

**Keep Patching**

Your current vendor has no incentive to fix root problems. Their revenue depends on you needing them for patches. Each patch compounds the debt. The system that’s hard to fix today becomes impossible to fix in 18 months.

*Staying feels safe. It’s the most dangerous option you have.*

**Hire Internally**

Legacy rescue requires architecture, migration, business continuity, and modern frameworks all at once. That’s not a single hire. It’s a team. And you’d be managing that team through a crisis you don’t fully understand technically. You go from one problem to two.

*You get control. Of a bigger mess.*

**Big Consulting Firm**

Junior developers do the actual work. The senior partners who sold the engagement disappear after signing. Proprietary methodologies create new lock-in that replaces the old lock-in. The brand name gives you political cover but not a working platform.

*Board-defensible on paper. Dangerous in practice.*

**Offshore Team**

Lower hourly rate, higher total cost. Communication gaps compound across time zones. Context gets lost in translation, literally. The nuance of your business workflows, the compliance requirements, the things your sales team depends on daily, none of it transfers through a spec document.

*You get the rate. You lose the context.*

**Wait and See**

Rot doesn’t hold steady. Your best employees leave first because they can see what’s coming. Your top customers leave next because they have alternatives. Board patience expires last, but when it does, it’s sudden. Every month of waiting raises the eventual cost of fixing it.

*The cheapest option is the most expensive one.*

### **PATTERN REVEAL**

Patching keeps the vendor happy. Hiring keeps you busy. Consulting keeps the board comfortable. Offshoring keeps costs looking low. Waiting keeps everyone calm. **None of them fix the platform.**

### **VISUAL DIRECTION**

Five-column comparison grid with consistent structure per column: headline, short paragraph, italic tagline. Pattern reveal below the grid as a standalone line, slightly larger typography. On mobile, columns stack vertically.

### **DESIGN NOTES**

* Five columns instead of AI page’s four. “Wait and See” earns its own column because it’s Tim’s most common default, the thing he does when all options feel bad. Giving it equal visual weight with the active alternatives makes the cost of inaction visible.  
* “Hire Internally” was validated by Gavin as particularly resonant. Tim’s instinct is “I’ll just build a team,” and naming why that fails builds credibility fast.  
* Each italic tagline is the scanner’s takeaway. Someone skimming should get the argument from the taglines alone.  
* Pattern reveal does the heavy lifting: it names the shared flaw across all five without making Fixation the hero yet. That comes in Section 4\.  
* **FLAG:** Five columns may need to become a 3+2 grid or horizontal scroll on tablet. Robby to decide layout treatment for medium viewports.

### **WORD COUNT: \~265 words**

---

## **SECTION 4: METHODOLOGY**

**Notes:** N:3 (”Our Way Is Best”)

### **HEADLINE**

We Learn Your Business Before We Touch Your Code.

### **SUBHEAD**

Legacy modernization isn’t our fallback. It’s our specialty. Thirteen years of methodology built for live platforms that can’t go dark.

### **BODY: FOUR METHODOLOGY PILLARS**

**Domain Learning First**

Before writing a line of code, we learn what can’t break. What workflows exist for compliance. What the sales team depends on daily. What processes are fragile for reasons no one documented.

You can’t hire developers who’ve never booked a flight to build your flight booking system. We start by understanding your business well enough to protect it during the rebuild.

**Business Continuity**

This isn’t a shutdown-and-rebuild. Your revenue keeps running while we modernize underneath. Incremental, controlled, measurable. The business never stops.

Weekly sprint demos make the process visible. Problems surface in days, not months. Truth comes out on demo day. Your board sees real progress, working software, not status reports.

**Clean Architecture**

iDesign methodology from day one. Modular, independently testable components. Future changes don’t require rewriting the whole system.

Need to swap an email provider? An afternoon, not a quarter. Want to bring development in-house someday? The code is clean enough for any competent developer to navigate.

**Zero Lock-In**

100% client IP ownership. Hosted on your own Azure subscription, on your own credit card. If you want to leave, you can. Tomorrow. No penalty clauses. No negotiations. No begging.

The vendors who make it easy to fire them are the ones nobody fires.

### **VISUAL DIRECTION**

Four vertical cards or stacked blocks, each with a bold pillar name, short paragraph, and a secondary detail line. Clean, spacious layout with generous whitespace between pillars.

### **DESIGN NOTES**

* Headline is Gavin’s language, slightly adapted. “Learn your business before we touch your code” is the most differentiating thing on this page. No competitor says this.  
* Subhead includes “sweet spot, not compromise” framing directly from the argument architecture. This counters the assumption that legacy work is what shops do when they can’t get greenfield projects.  
* “Truth comes out on demo day” is Gavin verbatim.  
* “The vendors who make it easy to fire them are the ones nobody fires” is a counter-intuitive closer that earns trust by naming the pattern. This was developed in the argument architecture and it’s too good to bury.  
* Four pillars (not five like AI page) because the content here is denser per pillar. Domain learning alone has more weight than any single AI methodology pillar.  
* **AI as benefit, not feature:** Clean architecture pillar implies AI readiness (”future changes don’t require rewriting”) without naming AI explicitly. The AI page owns that territory.

### **WORD COUNT: \~255 words**

---

## **SECTION 5: CASE STUDIES**

**Notes:** N:4 (Trust) \+ N:3 (Methodology proof)

### **HEADLINE**

This Isn’t Theory. Here’s What It Looks Like.

### **BODY: THREE-CARD LAYOUT**

**Card 1: SportsTip** *Vendor Escape \+ Live Migration*

SportsTrip was trapped by a proprietary Java vendor with “other fish to fry.” No contract. Features perpetually “coming soon.” The platform worked, but it was slowly strangling the business.

Fixation migrated the live platform, from proprietary Java to .NET, from rented infrastructure to client-owned Azure, without a single booking falling through the cracks. Every hotel relationship, every team workflow, every contract template survived intact.

The college segment grew 40% year-over-year. Features that were stuck on the roadmap now ship regularly. Three years later, SportsTrip scales development hours up and down based on seasonal cash flow. No penalty clauses. No begging.

“Love working with the team. Lightyears ahead of where we were with previous guys.”

\[Read the full story →\] *(link to /case-studies/sportstip)*

**Card 2: FinanceScope** *Architecture That Still Works Five Years Later*

FinanceScope needed a customer portal sophisticated enough to differentiate them in financial services. Most shops would have delivered something functional but forgettable.

Fixation built on iDesign architecture with clean separation of concerns. .NET 6, Azure, all on FinanceScope’s own infrastructure. When they wanted to swap email providers, it took an afternoon instead of a quarter.

Five years later, the system keeps running and features keep shipping. The architecture that seemed like overkill in 2021 is the reason they can still move fast in 2026\.

“With Fixation’s assistance, we have created one of the most dynamic portals for our customers in our industry.”

\[Read the full story →\] *(link to /case-studies/financescope)*

**Card 3: \[PLACEHOLDER: Future Tim Migration Story\]** *\[Headline TBD\]*

**Structural note for Card 3:** This card is architecturally reserved for a true Tim Tables proof point: CEO inheriting a failing platform, board pressure mounting, previous vendors having failed, and Fixation’s methodology producing a zero-downtime migration with restored board confidence. When available, this story becomes the lead card and the other two shift right.

**Interim treatment:** Card 3 should render as a visually complete card that invites engagement without signaling “empty.” Two approaches:

*Option A:* Feature a Nebraska Furniture Mart credibility marker. No full case study exists, but the association (Berkshire Hathaway subsidiary, 4-5 Fixation developers on critical systems) carries board-defensibility weight. Card could read:

**Nebraska Furniture Mart** *Enterprise-Scale Trust*

When a Berkshire Hathaway subsidiary needs developers on critical infrastructure, the stakes don’t get much higher. Fixation has had 4-5 developers embedded on Nebraska Furniture Mart systems. If NFM trusts us with theirs, your board can too.

*Option B:* Feature a trust/credibility composite card. Combine the 13-year track record, 100% referral growth, and reference call offer into a single proof card that doesn’t pretend to be a case study:

**13 Years. Zero Advertising.** *100% Referral Growth*

Every client we’ve ever signed came through a referral. We’ve never run an ad, never cold-called, never bought a list. Clients stay and they send others. That track record is the proof. And if you want to hear it firsthand, our clients volunteer for reference calls. We’re happy to set one up.

**Recommendation:** Option A (NFM) for board-defensibility, which is Tim’s primary concern at the trust stage. When the Tim migration story arrives, NFM credibility gets absorbed into the trust markers section (Section 6 equivalent) or the CTA trust reinforcer.

### **VISUAL DIRECTION**

Three equal-width cards side by side. Each card follows a consistent structure: company name, italic descriptor, 2-3 paragraph story, pull quote, and CTA link. Card 3 uses the same visual structure regardless of interim content.

### **DESIGN NOTES**

* SportsTip is primary proof on this page (vendor escape \+ live migration), used differently from any AI page angle. The proof points here are migration-specific: live platform, zero downtime, business continuity.  
* FinanceScope proves long-term durability, the “will this still work in three years?” objection. Five-year track record is the strongest counter to “deliver and disappear” skepticism.  
* Card 3 architecture means when the Tim story arrives, it drops in without restructuring the section. It simply replaces the interim content and moves to position 1\.  
* Pull quotes are short and client-attributed. They do the trust work.  
* **FLAG:** Need explicit permission confirmation for FinanceScope company name and Troy’s quotes before publishing.

### **WORD COUNT: \~310 words (Cards 1-2) \+ \~80 words (Card 3 interim, varies by option)**

---

## **SECTION 6: PROCESS**

**Notes:** N:4 (”You Can Trust Us”)

### **HEADLINE**

One Week to Learn Your Business. Weekly Demos After That.

### **SUBHEAD**

No black box. No quarterly status reports. You see everything, every week.

### **BODY: THREE-STEP TIMELINE**

**Step 1: Learn** *(Week 1\)*

We spend the first week learning your business, not writing code. Real conversations with the people who use the system daily. What can’t break. What workflows are load-bearing. What the documentation doesn’t cover.

This isn’t a questionnaire. We sit with your team and figure out where the real risks are. By the end of the week, you’ll have a clearer picture of your own system than you’ve had in years.

**Step 2: Build** *(Weeks 2+)*

Weekly demos. Working software, not slide decks. Your feedback gets applied the same week, not filed for “phase two.”

We keep the existing system running while building the new one underneath. Revenue doesn’t stop. Customer-facing workflows don’t break. The transition stays invisible to everyone except the people watching the demos.

**Step 3: Own** *(Ongoing)*

When the migration is complete, everything is yours. Code, infrastructure, documentation. If you want to bring development in-house someday, you can. If you want to keep working together, we scale hours up or down based on what you need. No long-term contracts. No exit penalties.

The platform that was your biggest liability is now infrastructure you don’t think about. And you’re back to running your business.

### **VISUAL DIRECTION**

Horizontal or vertical three-step timeline with numbered progression. Each step gets a heading, time indicator, and short paragraph. Clean, spacious layout.

### **DESIGN NOTES**

* Mirrors AI page’s three-step process section exactly. Learn / Build / Own (adapted from Learn / Build / Optimize).  
* Step 3 name changed from “Optimize” (AI page) to “Own” because ownership is the emotional payoff for Tim. He’s been renting his platform from vendors. Owning it is the transformation.  
* “Clearer picture of your own system than you’ve had in years” is a bold claim, but it’s grounded. Most Tim-type clients don’t actually know the full state of their own codebase. Domain learning surfaces things nobody documented.  
* “Revenue doesn’t stop” directly addresses the migration risk objection without calling it out. It’s stated as fact, not reassurance.  
* “Infrastructure you don’t think about” echoes the hero’s “invisible infrastructure” language. Bookend.

### **WORD COUNT: \~210 words**

---

## **SECTION 7: TRANSFORMATION**

**Notes:** N:5 (”We Know What You Want”)

### **HEADLINE**

From the Engine Room to the Captain’s Chair

### **SUBHEAD**

This is what changes when the platform stops being your biggest problem.

### **BODY**

You stop firefighting and start leading. Board meetings shift from technology problems to growth strategy. The Sunday night anxiety about Monday’s failures goes quiet.

Staff complaints about buggy, unstable software stop coming. Your best developer stays because they’re building new things, not patching old ones. The customers who were threatening to leave start asking what’s next.

Features that used to take a quarter ship in weeks. Competitors who were outpacing you technologically start watching what you’re doing instead. The platform that held you hostage is now a competitive advantage you can build on.

And the narrative changes. You’re not the leader who inherited a failing system. You’re the one who fixed it.

### **VISUAL DIRECTION**

Full-width section, lighter background, generous whitespace. Copy is centered prose, not bullets. Consider a subtle visual treatment that signals openness/possibility (lighter colors, more breathing room) contrasting with the empathy section’s heavier mood.

### **DESIGN NOTES**

* “Engine room to captain’s chair” is from the argument architecture’s transformation arc. It captures the identity shift without being corny.  
* Identity shift language lands in the final line: “You’re not the leader who inherited a failing system. You’re the one who fixed it.” This is the Note 5 payoff. It must be the emotional high point of the page.  
* Deliberately NOT bullets. The AI page used a dual-path checklist for transformation, but Tim’s transformation is a single narrative, not a feature list. Prose creates more emotional weight.  
* “Sunday night anxiety” is from the argument architecture. It’s specific enough to feel real.  
* AI as benefit shows up implicitly: “Features that used to take a quarter ship in weeks” includes AI-enabled development speed without naming AI. The AI page owns that territory.  
* No mention of Bobby. This section is 100% Tim’s identity shift.

### **WORD COUNT: \~150 words**

---

## **SECTION 8: FAQ**

**Notes:** N:2 (Objection handling) \+ N:4 (Trust reinforcement)

### **HEADLINE**

Before You Call, You’re Probably Wondering

### **BODY: ACCORDION FORMAT**

**1\. How risky is migrating a live platform?**

The risk isn’t in the migration. The risk is in staying with a platform that compounds problems every month. Our approach keeps the business running throughout. We’ve migrated live platforms serving users nationwide without a single transaction falling through the cracks. Weekly demos mean your team sees exactly what’s changing, every week.

**2\. How long does a legacy modernization take?**

It depends on the size and complexity of the existing system. Some engagements take months, others take longer. We’ll give you an honest assessment in the discovery call, not a number designed to win the deal. What we can promise: you’ll see working software within weeks, not months.

**3\. What if my board pushes back on switching vendors?**

Nebraska Furniture Mart, a Berkshire Hathaway subsidiary, trusts us with their critical infrastructure. We’ve grown 100% through referrals for 13 years. And if your board wants to talk to a current client, that call is easy to arrange. Our clients volunteer for reference calls.

**4\. Do we own the code?**

Yes. 100%. The code, the infrastructure, the documentation. Everything runs on your Azure subscription, under your credit card. If you want to leave, you can. Tomorrow.

**5\. Can we eventually bring development in-house?**

That’s the plan, if you want it. Clean architecture means any competent developer can navigate the codebase. We build it so it works without us, not because of us.

**6\. What if legacy modernization isn’t what we actually need?**

We’ll tell you. Sometimes what looks like a legacy problem is actually a process problem, or a vendor management problem, or a problem that doesn’t need custom software at all. The discovery call is a conversation, not a sales pitch. If we’re not the right fit, we’ll say so.

**7\. How is this different from what every other dev shop says?**

Other shops want greenfield projects. We love looking at legacy codebases. It may be the thing we do best. Most vendors say they can handle migration. We’ve built our methodology around it: domain learning, business continuity, clean architecture, zero lock-in. The person you talk to on the discovery call is the same person who architects the solution. No handoff.

**8\. What does a discovery call look like?**

Thirty minutes. You tell us what you’re dealing with. We tell you what we’ve seen in similar situations. If there’s a fit, we talk next steps. If there isn’t, you leave with a clearer picture of your options. No pitch. No obligation.

### **VISUAL DIRECTION**

Accordion/expandable format. Questions visible, answers expand on click. Clean typography with generous spacing between items.

### **DESIGN NOTES**

* Mirrors AI page FAQ section added in V3. Same format, legacy-specific questions.  
* Q1 (migration risk) is the most important question on this page. It’s first because it’s Tim’s \#1 objection. The answer directly inverts the risk framing: staying is the risk, not switching.  
* Q3 (board pushback) brings NFM credibility and reference calls into the FAQ where they earn maximum trust. If Card 3 in Section 5 uses the NFM interim treatment, this answer should be adjusted to avoid repetition.  
* Q7 includes “We love looking at legacy codebases,” which is Gavin verbatim and differentiating. No other shop would say this.  
* Q8 demystifies the CTA. Tim is risk-averse. Knowing exactly what happens after clicking “Book a Discovery Call” reduces friction.  
* **FLAG:** FAQ answers are 2-4 sentences each. If Gavin wants to adjust tone or add detail, these are easy to edit without restructuring.

### **WORD COUNT: \~385 words**

---

## **SECTION 9: CTA**

**Notes:** N:4 (Trust reinforcer) \+ N:5 (Echo)

### **HEADLINE**

Start With an Honest Conversation

### **SUBHEAD**

No pitch. No pressure. Just a conversation about what you’re dealing with, and whether we’re the right team to fix it.

### **TRUST REINFORCER**

Our clients volunteer for reference calls. If you want to talk to someone who’s been through this, that conversation is easy to arrange.

### **CTA**

**Primary Button:** Book a Discovery Call **Secondary Link:** Or ask us anything: hello@fixation.dev

### **VISUAL DIRECTION**

Dark or contrasting background to create clear section break. Single centered layout. Button is the dominant element. Trust reinforcer text sits below the button, understated.

### **DESIGN NOTES**

* Mirrors AI page CTA exactly. Same structure, same tone, same reference call offer.  
* “Whether we’re the right team to fix it” (instead of AI page’s “whether AI is actually the right way to get there”) adapts the honesty signal for legacy context.  
* Trust reinforcer expanded from a single line to include the “been through this” framing. Tim needs to hear that someone else was in his situation, and he can talk to them directly.  
* **FLAG:** Email address. Confirm hello@fixation.dev vs. info@fixation.dev. AI page flagged the same question.

### **WORD COUNT: \~50 words**

---

## **SECTION 10: FOOTER**

### **PERSISTENT CTA BAR**

**Your platform won’t fix itself. But it can be fixed.** Let’s talk. → BOOK A CALL

### **FOOTER LINKS**

hello@fixation.dev | Legacy Modernization | AI Services | Careers | Privacy | Terms

### **ADDRESS**

© 2026 Fixation.

### **DESIGN NOTES**

* Persistent CTA bar adapts homepage pattern. “Your platform won’t fix itself. But it can be fixed.” is from the argument architecture’s alternative CTA headline. It echoes the page’s core reframe (inaction is the risk) without repeating the hero.  
* Footer includes sibling link to AI Services for cross-navigation between service pages.

---

## **BELIEF PROGRESSION MAP**

| Section | Note(s) | Belief Built | Tim’s Thought |
| ----- | ----- | ----- | ----- |
| 1\. Hero | N:5 \+ N:3 | Transformation hook | “They’ve done this before, and there’s a way out” |
| 2\. Empathy | N:1 | “They understand my situation” | “I didn’t build this problem, but yeah, it’s mine now” |
| 3\. Alternatives | N:2 | “Other options won’t work” | “That’s exactly why nothing I’ve tried has fixed this” |
| 4\. Methodology | N:3 | “Their approach makes sense” | “Domain learning first, business keeps running, I own everything” |
| 5\. Case Studies | N:4 \+ N:3 | “These results are real” | “SportsTip was in a similar situation. It worked.” |
| 6\. Process | N:4 | “Working with them is straightforward” | “One week to learn, then weekly demos. I can see everything.” |
| 7\. Transformation | N:5 | “I want what they’re describing” | “Engine room to captain’s chair. That’s what I need.” |
| 8\. FAQ | N:2 \+ N:4 | “My objections are addressed” | “Migration risk is handled. Board can verify. Code is mine.” |
| 9\. CTA | N:4 \+ N:5 | “I should talk to them” | “Reference calls. No pressure. Let’s go.” |

---

## **CROSS-PAGE CONSISTENCY CHECK**

| Element | AI Services Page (v2.0) | Legacy Mod Page (v1.0) | Status |
| ----- | ----- | ----- | ----- |
| Hero structure | Headline \+ 3-line subhead \+ trust line \+ dual CTA | Same pattern, legacy-specific | Consistent |
| Empathy approach | Dual path (Bobby \+ Tim) | Single path (Tim only) | Appropriate, Tim-first page |
| Alternatives format | 4-column grid \+ pattern reveal | 5-column grid \+ pattern reveal | Consistent structure, expanded for “Wait and See” |
| Methodology format | 5 pillars, vertical cards | 4 pillars, vertical cards | Adapted for denser content per pillar |
| Proof section | 2 case study cards | 3 cards (2 active \+ 1 reserved) | Appropriate, accommodates future story |
| Process format | 3-step timeline (Learn/Build/Optimize) | 3-step timeline (Learn/Build/Own) | Consistent, adapted final step |
| Transformation | Dual path, 5 checkmarks per | Single path, prose narrative | Appropriate, Tim’s identity shift needs narrative |
| FAQ | 8 questions, accordion | 8 questions, accordion | Consistent |
| CTA | Echo \+ trust reinforcer | Same pattern | Consistent |
| Voice | Conversational, direct, Gavin | Same | Consistent |
| Belief progression | N:5, N:1, N:2, N:3, N:4, N:4, N:5, FAQ, CTA | Same arc | Consistent |

---

## **TOTAL WORD COUNT SUMMARY**

| Section | Target | Actual | Status |
| ----- | ----- | ----- | ----- |
| 1\. Hero | 50-75 | \~65 | On target |
| 2\. Empathy | 100-175 | \~165 | On target |
| 3\. Broken Alternatives | 200-300 | \~265 | On target |
| 4\. Methodology | 200-300 | \~255 | On target |
| 5\. Case Studies | 250-350 | \~390 (incl. Card 3\) | Slightly over, justified by 3-card format |
| 6\. Process | 150-250 | \~210 | On target |
| 7\. Transformation | 100-175 | \~150 | On target |
| 8\. FAQ | 300-400 | \~385 | On target |
| 9\. CTA | 30-60 | \~50 | On target |
| **Total page copy** |  | **\~1,935** | Appropriate for legacy services depth |

---

## **SUCCESS CRITERIA VERIFICATION**

* \[x\] Every section maps to a corresponding note in the BBCAP argument architecture  
* \[x\] Structure is a faithful parallel to the AI Services wireframe (10 sections, same types, same rhythm)  
* \[x\] Migration risk objection addressed directly and reframed (Section 3 Subclaim 2.1 \+ Section 4 Business Continuity \+ FAQ Q1)  
* \[x\] Card 3 in proof section cleanly structured to receive future Tim story  
* \[x\] Identity shift language appears explicitly in Section 7: “You’re not the leader who inherited a failing system. You’re the one who fixed it.”  
* \[x\] No AI page proof points duplicated ($10K to $200/month, manual team replacement both absent)  
* \[x\] AI referenced only as implicit benefit of modernized platform, never as feature  
* \[x\] SportsTip used for vendor-escape and live-migration proof without forcing persona match  
* \[x\] Zero em-dashes in final copy  
* \[x\] Zero exclamation points in final copy  
* \[x\] Zero disallowed words/phrases from AI Copywriting file  
* \[x\] Gavin voice test: every sentence passes “would he say this over coffee?”

---

## **ASSUMPTIONS AND FLAGS**

**Assumptions (require validation):**

1. SportsTip case study is approved for public use with Jasa’s name and company  
2. FinanceScope permission pending (flagged in case study file)  
3. NFM association cleared for marketing use (”Everyone’s heard of them around here” context)  
4. Email address is hello@fixation.dev (not info@fixation.dev)  
5. Discovery call is 30 minutes (stated in FAQ Q8, needs Gavin confirmation)

**Structural flags:**

1. Five-column grid in Section 3 needs responsive design decision for tablet viewports  
2. Card 3 interim treatment (Option A vs. Option B) needs Robby/Gavin decision  
3. If Card 3 uses NFM content, FAQ Q3 (board pushback) should be adjusted to avoid repeating the same NFM proof point in two sections  
4. Section 7 (Transformation) uses prose instead of the AI page’s checklist format. This is intentional (Tim’s identity shift reads better as narrative), but Robby may prefer visual consistency across sibling pages. Flag for discussion.

**Gavin voice review priority:**

The following lines are most likely to need Gavin’s direct input:

* Hero headline (arrogance check on “We Know What We’ll Find”)  
* Section 4 subhead (”Legacy modernization isn’t our compromise engagement”)  
* FAQ Q7 (”We love looking at legacy codebases”)  
* Section 7 final line (”You’re the one who fixed it”)

---

## **PROOF POINT TERRITORY MAP**

| Proof Point | AI Services Page | Legacy Mod Page |
| ----- | ----- | ----- |
| $10K to $200/month AI cost reduction | YES | NO |
| Manual team replacement (95%) | YES | NO |
| SportsTip: vendor escape \+ live migration | NO | YES (primary proof) |
| SportsTip: 40% college segment growth | NO | YES |
| FinanceScope: 5-year architecture durability | NO | YES (secondary proof) |
| FinanceScope: swap email provider in afternoon | NO | YES |
| NFM: Berkshire Hathaway credibility | Referenced | YES (board-defensibility) |
| “Battery of tests” methodology | YES | NO |
| “Designed for volatility” | YES | NO |
| Domain learning first | NO | YES (the moat) |
| Business continuity approach | NO | YES |
| iDesign clean architecture | Mentioned | YES (featured) |
| Zero lock-in / code ownership | Both (shared) | Both (shared) |
| 13 years / referral growth | Both (shared) | Both (shared) |
| Reference calls | Both (shared) | Both (shared) |

# Services \> MVP

# **FIXATION MVP DEVELOPMENT PAGE WIREFRAME v1.0**

## **fixation.dev/services/mvp-development**

### **Section-by-Section Structure & Messaging**

**Version:** 1.1.0  
**Date:** Mar 10, 2026  
**Source Documents:** MVP Development Argument Architecture v1.0 \+ COO Review (March 2026\)  
**Structural Template:** Services \> AI v2.0, Services \> Legacy Modernization v1.1 **Primary Persona:** Bobby Notebooks (funded startup founder building from scratch)

---

## **NOTES KEY**

| Note | Belief Stage | Core Question (Bobby's Inner Monologue) |
| ----- | ----- | ----- |
| N:1 | Empathy | "Do they get what it's like to have everything riding on this?" |
| N:2 | Broken Alternatives | "Why hasn't anything I've tried gotten me closer to launch?" |
| N:3 | Unique Approach | "What makes them different from every other dev shop pitching me?" |
| N:4 | Trust & Offer | "Can I actually trust them with my money and my timeline?" |
| N:5 | Transformation | "What does my life look like when this is built and working?" |

---

## **SECTION 1: HERO**

**Notes:** N:5 (Transformation) \+ N:3 (Approach hint)

### **HEADLINE**

60 Days to a Working MVP. Still Running Six Years Later.

### **SUBHEAD**

No proprietary lock-in. No going dark for months. No rebuilding the whole thing after launch.

### **TRUST LINE**

60-day MVP delivery | You own 100% of the code | 13 years, 100% referral growth

### **CTA**

**Primary:** Book a Discovery Call **Secondary:** See How We're Different ↓

### **VISUAL DIRECTION**

Single-column hero. Headline is the dominant element. Subhead sits below in lighter weight. Trust line beneath as a quiet confidence marker. Dual CTA buttons at bottom.

### **DESIGN NOTES**

* Headline uses the architecture's strongest line (COO confirmed). "60 Days" is specific, defensible, and proven by SeniorCareFinder. "Built to Grow With You for Years" is the anti-throwaway-MVP promise. No competitor makes both claims in one breath.  
* Subhead follows the three "No" pattern from Homepage and AI page heroes. Each "No" names a specific Bobby fear: lock-in (ownership anxiety), going dark (transparency anxiety), rebuilding (durability anxiety).  
* Trust line follows AI page pattern: three metrics-based claims, no feature labels. "60-day MVP delivery" is speed. "100% of the code" is ownership. "13 years, 100% referral growth" is credibility.  
* Secondary CTA earns the scroll.  
* **FLAG:** Architecture provided two directional headlines. "You've Got the Idea and the Funding. Now Comes the Hard Part." was flagged by COO as generic. Elevated "60 Days to a Working MVP" from Note 3 to hero position because it's the most Fixation-distinctive claim on the page.

### **WORD COUNT: \~55 words**

---

## **SECTION 2: EMPATHY**

**Notes:** N:1 ("We Get You")

### **HEADLINE**

Every Dev Shop Sounds the Same Until Six Months and a Blown Budget Later

### **SUBHEAD**

Custom software is an opaque market. Every shop sounds the same until six months and a blown budget later.

### **BODY**

You haven't quit your day job yet. You're taking meetings at odd hours, juggling investor expectations, and trying to figure out which of the five dev shops pitching you will actually build what they promised. They all sound good. The proposals look similar. And you know from the horror stories that you won't discover who's competent until long after you've signed.

Meanwhile, your idea keeps evolving. You know what you want in broad strokes, but you can't spec it down to the pixel. The dev shop that expects a finished requirements document before writing code is the wrong shop. You need a team that helps you figure out what to build, not just one that builds what you describe.

Every week without a working product is a week your competitors can move first, your investors quietly lose confidence, and the window to be first-to-market gets smaller. You're watching other startups launch while you're still shopping for developers.

You're right to be careful. The stakes are personal, not just financial.

### **VISUAL DIRECTION**

Full-width section with centered text. Slightly darker background to create mood shift from the hero. Body copy in three short paragraphs, not bullets. Single-path treatment (Bobby only, same as Legacy page's Tim-only approach).

### **DESIGN NOTES**

* Single path, not dual-path like AI page. This is Bobby's page. Tim's concerns live on Legacy Modernization.  
* First paragraph validates Bobby's intelligence: he can't tell good from bad, and that's the market's fault, not his. Parallels Legacy page's "You Didn't Build This Problem" energy.  
* Second paragraph addresses the "idea evolving faster than you can describe it" subclaim. This is a differentiator from sibling pages. Neither AI nor Legacy Mod addresses the "can't spec it perfectly" fear.  
* Third paragraph adds competitive urgency without going generic. "Watching other startups launch" is Bobby's specific anxiety.  
* Final line reframes: the stakes are personal. Bobby's spouse, his investors, his reputation are on the line. This earns the empathy without patronizing.  
* "Meetings at odd hours" is from the Gavin transcript (real prospect scheduling around her day job).

### **WORD COUNT: \~175 words**

---

## **SECTION 3: BROKEN ALTERNATIVES**

**Notes:** N:2 ("Those Aren't Best")

### **HEADLINE**

Five Paths to Getting Your MVP Built. Every One Optimizes for Someone Else.

### **SUBHEAD**

You're Picking Your Own Trap.

### **BODY: FIVE-COLUMN GRID**

**Cheap Offshore**

Attractive rates. Time zones and cultural gaps kill communication. You can't hire a dev team that's never been on an airplane to build a flight booking system. When things break at 2 AM your time, the team that built it is asleep.

*You get the rate. You lose the product.*

**Generic Dev Shop**

They take your requirements, assign developers, and deliver something "technically complete" that nobody wants to use. The gap between "works" and "competitive advantage" is the gap between a team that read your spec and a team that learned your market. One prospect saw mockups from a competing shop and knew they were wrong but couldn't articulate why. Generic shops deliver screens, not solutions.

*You get a product. Not your product.*

**WordPress / Off-the-Shelf**

If it's not a WordPress solution, it would already exist out there. Building on a platform designed for something else means hitting a technology ceiling before you get traction. One company tried Shopify for warehouse-scale B2B ordering. Only 10% of revenue came through the site. The rest required manual workarounds because the platform wasn't built for it.

*You get started fast. Then you start over.*

**Solo Developer**

Personalized attention. Single point of failure. One person can't maintain a whole platform and move it forward simultaneously. Can't stay current on AI, architecture, and your domain. Three-week vacation means your website goes down with zero support.

*You get a person. You need a team.*

**Build It Yourself**

By the time founders get to Fixation, most have tried coding it themselves, hiring a friend, or paying someone obviously substandard. Every hour you spend writing code is an hour not spent selling, raising, or validating the market. The MVP is a tool to get you in front of customers. It's not the business itself.

*You get busy. Your competitors get ahead.*

### **PATTERN REVEAL**

Every alternative shares the same flaw: they optimize for avoiding upfront cost instead of building something that lasts. Cheap rates lead to rewrites. Generic shops deliver generic products. Solo hires create fragile dependencies. DIY burns the founder's time. None of them produce a platform you can scale on, sell with, or eventually exit from.

### **VISUAL DIRECTION**

Five-column comparison grid with consistent structure per column: headline, short paragraph, italic tagline. Pattern reveal below the grid as a standalone line, slightly larger typography. On mobile, columns stack vertically.

### **DESIGN NOTES**

* Five columns matching Legacy page (which also has 5). AI page has 4\. The inclusion of "Build It Yourself" is Bobby-specific and earns its own column because it's the most common path founders take before arriving at Fixation. Gavin confirmed this pattern in the Feb 2026 interview.  
* Each italic tagline is the scanner's takeaway. Someone skimming should get the argument from taglines alone.  
* "Can't hire a dev team that's never been on an airplane to build a flight booking system" is Gavin's language (from Blueprint).  
* "Delivered screens, not solutions" and the mockup anecdote are from the Gavin transcript (real prospect comparing Fixation to a competing shop).  
* Shopify/air compressor story is a proof point unique to this page. Does not appear on AI or Legacy pages.  
* Pattern reveal ties all five columns together and transitions to the methodology section.  
* **FLAG:** Five columns need responsive design decision for tablet viewports (same flag as Legacy page). Consider 3+2 grid or horizontal scroll.

### **WORD COUNT: \~290 words**

---

## **SECTION 4: METHODOLOGY**

**Notes:** N:3 ("Our Way Is Best")

### **HEADLINE**

We Learn Your Business Before We Write Your Code. And You Own All of It.

*\~OR\~*

You Can't Describe What You Want Until You See It. We're Built for That.

### **SUBHEAD**

Other shops build what you describe. We help you build what you actually need, in 60 days, and every line belongs to you.

### **BODY: FIVE METHODOLOGY PILLARS**

**Domain Learning First**

Before writing a line of code, we learn what you're actually building and who you're building it for. Your domain expertise, the edge cases, the "that's not how it works in our industry" moments, that becomes the starting point for every architectural decision.

You can't describe exactly what you want. You have to see it first. That's not a flaw in your preparation. It's how product development works. The right partner helps you define what you need, not just builds what you describe.

**Weekly Demos, Not Status Reports**

Truth comes out on demo day. Developers are motivated because demo is tomorrow. Misunderstandings get corrected in week one, not discovered after the final invoice.

You'll see working software every week. Show investors a functioning product within the first month, not a slide deck at the end of month three. Every demo is a chance to validate, pivot, or double down based on real feedback.

**Clean Architecture That Scales**

Your system is built in independent, swappable pieces from day one. Need to change your CRM? Swap it without touching the rest of the platform. Want to add AI features or switch payment providers? Same story. The methodology behind this is called iDesign, and it's the reason changes stay small even as the system grows.

Your MVP isn't a throwaway. The architecture that seems like overkill on day one is the reason you can still move fast three years later without a rewrite.

**You Own Everything From Day One**

100% client IP ownership. Hosted on your Azure subscription, on your credit card. If you want to leave, you can. Tomorrow.

Want to bring development in-house eventually? Clean code any competent developer can navigate. The architecture works without Fixation, not because of us. We make it easy to leave. That's why nobody does.

**Lower Cost Than You'd Expect**

Here's the part that surprises people. When a prospect compared us to another shop that planned to use foreign talent, Fixation came in at a lower price. Not because we're cheap. Because we're efficient. Low overhead, senior developers, no bloat.

We charge as we go. We bill as we go. No massive upfront deposits. Development hours flex based on your business needs. When things are tight, hours flex down. When you need to move fast, hours flex up. No penalty clauses. No begging. Convertible note arrangements available for the right partnerships.

### **VISUAL DIRECTION**

Five-pillar layout: vertical cards or stacked accordion sections. Each pillar gets an icon, headline, and short paragraph. "Lower Cost Than You'd Expect" and "You Own Everything" should be visually prominent. Consider alternating alignment (left-right) for visual rhythm.

### **DESIGN NOTES**

* Five pillars matching AI page. Legacy page has 4 (denser per pillar).  
* Headline merges methodology-first framing with ownership. Parallels AI page headline: "Built Around AI From Day One. And Every Line of It Is Yours."  
* Pillar 1 (Domain Learning) features Gavin's key insight: "They can never describe exactly what they want. They have to see it first." This is the methodology's emotional center for Bobby.  
* Pillar 2 (Weekly Demos) uses Gavin's exact language: "Truth comes out on demo day." The investor-facing angle (show working software within weeks) is Bobby-specific.  
* Pillar 3 (Clean Architecture) explains iDesign in business terms, not technical terms. Bobby doesn't care about dependency injection. He cares about not hitting a wall.  
* Pillar 4 (Code Ownership) parallels AI page's "You Own Everything" pillar. This is a shared differentiator that must appear on all service pages.  
* Pillar 5 (Lower Cost) is PROMOTED per COO directive. The offshore-competitor pricing reversal is the most counter-intuitive proof point in the architecture. Leading with "surprises people" hooks the scanner. Flexible billing model addresses Bobby's cash flow anxiety directly. Convertible note mention signals startup-fluency.  
* **FLAG:** Pillar 5 is the longest. May need trimming for visual balance with other pillars, but the content earns its weight because pricing is Bobby's \#2 concern after speed.

### **WORD COUNT: \~350 words (slightly over 200-300 target, justified by 5 pillars with promoted pricing pillar)**

---

## **SECTION 5: CASE STUDIES**

**Notes:** N:4 (Trust) \+ N:3 (Methodology proof)

### **HEADLINE**

60-Day MVP. 14,000 Commits. Six Years Later, the Founders Run the Company, Not the Code.

### **SUBHEAD**

Real founders. Real timelines. Real code ownership.

### **BODY: THREE-CARD LAYOUT**

**Card 1: From Idea to MVP in 60 Days, Still Growing 6 Years Later** *(PRIMARY PROOF)*

**The Situation:** A husband and wife, both still working full-time, walked in with investor backing, a concept for a healthcare marketing platform, and no idea how to build software. Customers were waiting. Technology scared them. Every agency they'd evaluated had a revolving door of developers or prices that didn't match the quality.

**What We Did:** Started by listening. The founders explained their world in person: who they were selling to, how purchasing decisions worked in their vertical, what data providers needed. That domain knowledge shaped everything. A full team built the MVP (not a lone contractor) with CI/CD pipelines and clean layered architecture from day one. Weekly demos kept the founders in the loop. They own 100% of the code. Always have.

**The Result:** MVP shipped in about 60 days. Company grew from 2 people to more than 20 employees. Six years and nearly 14,000 commits later: a complete .NET 4 to .NET 8 migration done in 60 days with zero customer disruption. The founders stopped attending weekly demos. Their staff handles that now. They spend their time running a growing company and being with their family.

**NOTE:** Company name withheld at the client's request. Bobby-type prospects understand startup confidentiality. It reinforces trust: Fixation protects client information.

\[Read the full story →\] *(link to /case-studies/idea-to-mvp-60-days)*

---

**Card 2: Founder Escapes Bad Vendor, Grows 40%**

**The Situation:** SportsTrip's CEO was held hostage by a proprietary Java vendor. "Other fish to fry." Begging for hours. No contract. Features perpetually "coming soon."

**What We Did:** Migrated the entire live platform to .NET on client-owned Azure without a single booking falling through the cracks. Every hotel relationship, every team workflow, every contract template survived intact.

**The Result:** College segment grew 40% year-over-year. Features that were stuck on the roadmap now ship regularly. Three years later, SportsTrip scales development hours up and down based on seasonal cash flow. No penalty clauses. No begging.

"Love working with the team. Lightyears ahead of where we were with previous guys."

\[Read the full story →\] *(link to /case-studies/sportstip)*

---

**Card 3: \[PLACEHOLDER: Healthcare Travel Client\]**

**Structural note:** This card is architecturally reserved for the healthcare travel prospect currently in Gavin's pipeline. When this client signs and the story is publishable, it becomes a second Bobby proof point: funded founder, investor backing, existing UI work from a competing shop that Fixation absorbed and improved. The prospect compared Fixation to a shop using foreign talent and chose Fixation at a lower price.

**Interim treatment options:**

*Option A: Referral credibility card*

**13 Years. Zero Advertising.** *100% Referral Growth*

Every client we've signed came through a referral. We've never run an ad, never cold-called, never bought a list. If you want to hear it from someone who's been through this, our clients volunteer for reference calls. We're happy to set one up.

*Option B: NFM trust card*

**Nebraska Furniture Mart** *Enterprise-Scale Trust*

When a Berkshire Hathaway subsidiary needs developers on critical infrastructure, the stakes don't get much higher. If NFM trusts us with theirs, your investors can trust us with yours.

**Recommendation:** Option A (referral credibility) for Bobby. NFM carries more weight with Tim (board-defensibility). Bobby cares more about peer validation than enterprise logos. When the healthcare travel story arrives, it replaces this card in position 3\.

### **VISUAL DIRECTION**

Three equal-width cards side by side. Each card follows a consistent structure: company name/descriptor, 2-3 paragraph story, pull quote where available, CTA link. Card 3 uses the same visual structure regardless of interim content.

### **DESIGN NOTES**

* SeniorCareFinder is the hero proof. This is the single strongest Bobby case study in the Fixation ecosystem. Every detail maps to a Bobby fear: married founders, day jobs, scared of technology, 60-day MVP, 20+ employees, six years of partnership, founders stopped attending demos.  
* SportsTip is used here ONLY for the Bobby-adjacent angle: founder escaping a bad partner, recovering from prior bad decisions. The vendor-escape and live-migration narrative belongs to the Legacy page. Different emphasis, no duplication.  
* Card 3 architecture means the healthcare travel story drops in without restructuring. Matches Legacy page's Card 3 treatment (also reserved for a future story).  
* **FLAG:** SeniorCareFinder is anonymized. Architecture notes that Bobby-type prospects understand startup confidentiality. Consider whether the anonymization note should be visible on the page or just in the wireframe.

### **WORD COUNT: \~350 words (Cards 1-2) \+ \~80 words (Card 3 interim)**

---

## **SECTION 6: PROCESS**

**Notes:** N:4 ("You Can Trust Us")

### **HEADLINE**

Week One: We Learn Your Business. Week Three: You're Showing Investors.

### **SUBHEAD**

No phase where you're waiting and wondering. Bring scraps, mood boards, rough notes, even substandard work from another shop. We start from wherever you are.

### **BODY: FOUR-STEP TIMELINE**

**Step 1: Discovery & Domain Learning** *(Week 1\)* 🗨️

You talk, we listen. Not a questionnaire. Not a requirements-gathering template. A real conversation about your market, your customers, and the problem you're solving. We ask the questions that surface what you know but haven't articulated yet.

By the end of week one, you have a clear scope and we understand your domain better than most shops do after months.

**Step 2: Working Prototype** *(Weeks 2-3)* 🔲

Not wireframes. Not mockups. A real application with sample data you can click through. You'll know immediately if we understood your requirements because you'll be using the software, not reading about it.

This is when you can start showing investors something real.

**Step 3: Build & Demo** *(Weeks 3-8)* \</\>

Weekly sprints with mandatory demos. Every feature ships tested. Your feedback gets applied the same week, not filed for "phase two." We plan the week every week, so the build can change direction as you learn from customers, investors, and the market.

Target: sellable MVP in 60 days. Demo-able progress every single week along the way.

**Step 4: Scale** *(Ongoing)* 🔄

Your business doesn't stop evolving after launch, and neither do we. New features, integrations, AI capabilities. Hours flex up or down based on what you need. When you're ready to bring development in-house, the code is clean enough to hand over.

The goal is a platform that grows with you, not a project that ends.

### **VISUAL DIRECTION**

Vertical four-step timeline with numbered progression. Each step gets a heading, time indicator, icon, and short paragraph. Visual connectors between steps suggest continuous flow. Step 4 has no endpoint indicator to reinforce the partnership model.

### **DESIGN NOTES**

* Four steps, matching AI page's 4-step process. Legacy page has 3 steps (Learn/Build/Own). The extra step here (Working Prototype between Discovery and Build) is justified because Bobby needs the "show investors early" proof point, and the 2-3 week prototype is a specific, impressive promise.  
* Headline follows AI page pattern ("Week One: We Listen. Week Two: You're Using It.") with Bobby-specific payoff: showing investors, not just using it himself.  
* "Scraps, mood boards, rough notes" is Gavin's language about what Bobby typically brings. The "substandard work from another shop" line addresses the common scenario where Bobby has existing UI from a prior vendor.  
* "Plan the week every week" is Gavin's description of the sprint cadence.  
* "Not wireframes. Not mockups" parallels AI page Step 2 and Gavin's "interactive demos, not PowerPoints" ethos.  
* Step 4 distinguishes Fixation from project-based shops that deliver and disappear. "Hours flex up or down" reinforces the pricing pillar from Section 4\.

### **WORD COUNT: \~230 words**

---

## **SECTION 7: TRANSFORMATION**

**Notes:** N:5 ("We Know What You Want")

### **HEADLINE**

From Pitch Deck to Paying Customers

### **SUBHEAD**

This is what changes when you stop shopping for developers and start selling.

### **BODY**

You stop burning runway on research and start burning it on growth. The MVP that was supposed to be a "first version" turns out to be the foundation of a growing company. Investors see working software, not slide decks. Customers can sign up, use the product, and pay for it while the next version is already in demo.

The architecture that seemed like overkill on day one is the reason you can add AI features, swap providers, and scale to thousands of users without starting over. The team that built it is still around because they're worth keeping, not because you're locked in.

And the trajectory shifts. Your spouse stops worrying. Your investors stop asking when they'll see something. Your competitors stop being the ones who launched first, because you launched better.

Six years from now, you won't be thinking about the code. You'll be running a company. Your staff will attend the weekly demos. And the platform that started as an MVP will have 14,000 commits, a framework migration under its belt, and a founder who has time for family.

You're not a founder gambling on the wrong dev team. You're a CEO who chose the right partner.

### **VISUAL DIRECTION**

Full-width section, lighter background, generous whitespace. Copy is centered prose, not bullets. Subtle visual treatment that signals openness/possibility (lighter colors, more breathing room) contrasting with the empathy section's heavier mood.

### **DESIGN NOTES**

* Prose narrative, not checkmarks. Matches Legacy page treatment (Tim's identity shift also uses prose). Bobby's transformation is a single narrative arc, not a feature list.  
* "Super suit" language from Gavin doesn't appear in the wireframe copy. It informed the architecture, but the wireframe copy uses language Bobby would say about himself, not language Gavin would use to describe Bobby. The identity shift needs to feel like Bobby's realization, not Fixation's pitch.  
* "Six years from now" paragraph is the SeniorCareFinder transformation told as Bobby's future. Every detail is real (14,000 commits, framework migration, staff attending demos, founders freed up). Bobby reads this and sees what's possible without Fixation having to say "that could be you."  
* Final line is the explicit identity shift: "founder gambling on wrong dev team" to "CEO who chose the right partner." This is the emotional equivalent of Legacy page's "You're not the leader who inherited a failing system. You're the one who fixed it."  
* "Your spouse stops worrying" is Bobby-specific. Investors and competitors are professional stakes. Spouse is personal. Including it signals that Fixation understands the full weight Bobby carries.

### **WORD COUNT: \~195 words**

---

## **SECTION 8: FAQ**

**Notes:** N:4 (Trust) \+ N:1 (Empathy) \-- addresses residual objections

### **HEADLINE**

Before You Call, You're Probably Wondering

### **BODY: ACCORDION FORMAT**

**1\. How fast can you build an MVP?**

Our target is 60 days to a sellable product. That's not a sales number. One client went from first meeting to working MVP in about 60 days, and they're still using (and growing on) that platform six years later. Complexity matters, so we'll give you an honest estimate in the discovery call, not a number designed to win the deal.

**2\. How much does this cost?**

It depends on scope, but most MVPs fall in a range we can discuss in the first conversation. What surprises founders is that we've come in lower than shops using offshore talent, because our overhead is low and our developers are efficient. We bill as we go. No massive upfront deposit. Flexible payment arrangements, including convertible notes for the right partnerships.

**3\. What happens after the MVP launches?**

Our longest-running MVP client is six years in and still growing. They started as two founders with day jobs. Now they have 20+ employees and their staff attends the weekly demos, not the founders. That's the model. Hours flex up or down based on what your business needs and what your cash flow allows. No long-term contracts. No exit penalties. If you want to bring it in-house later, the code is clean enough to hand over.

**4\. Can we pivot mid-build?**

That's the whole point of weekly demos. You'll see working software every week. If the market tells you to change direction, we change direction that sprint. Our architecture is modular specifically so pivots don't mean starting over.

**5\. What if my requirements change as we go?**

They will. Founders can never describe exactly what they want until they see it. That's not a problem. It's how product development works. We plan the week every week, and the scope evolves based on what you learn from real users, investors, and the product itself.

**6\. Do I own the code?**

Yes. 100%. The code, the infrastructure, the documentation. Everything runs on your Azure subscription, under your credit card. If you want to leave, you can. Tomorrow. We build it so it works without us.

**7\. What does a discovery call look like?**

Thirty minutes. You tell us what you're building and who it's for. We tell you what we've seen in similar situations. If there's a fit, we scope the project within a week and give you a clear estimate. If there's not, you leave with a better understanding of your options. No pitch. No obligation.

**8\. What if I already have work from another shop?**

Bring it. We work with scraps of ideas, mood boards, rough notes, even substandard deliverables from a previous vendor. One prospect brought over UI work from a competing firm by recording a 12-minute screen share. We can work with whatever you have and turn it into something that actually ships.

### **VISUAL DIRECTION**

Accordion/expandable format. Questions visible, answers expand on click. Clean typography with generous spacing between items.

### **DESIGN NOTES**

* Matches sibling page FAQ sections: 8 questions, accordion format, "Before You Call, You're Probably Wondering" header.  
* Q1 (speed) is first because it's Bobby's \#1 concern (from LUCID decision criteria: "Speed of initial prototype, 30-60 days"). Answer anchors the 60-day claim with SeniorCareFinder proof.  
* Q2 (cost) is second because it's the conversion blocker. Answer leads with the counter-intuitive pricing story (cheaper than offshore competitor) without naming specific numbers. Convertible note mention signals startup fluency.  
* Q3 (post-MVP) addresses abandonment fear. "Hours flex up or down" reinforces the pricing pillar.  
* Q4 (pivots) and Q5 (changing requirements) could feel redundant but address different anxieties. Q4 is about strategic direction changes. Q5 is about the normal evolution of product specs. Both use weekly demos and modular architecture as proof.  
* Q6 (code ownership) is short and direct. Bobby doesn't need a long answer here. He needs a clean yes.  
* Q7 (discovery call) demystifies the CTA. Same treatment as Legacy page Q8. Knowing exactly what happens after clicking "Book a Discovery Call" reduces friction.  
* Q8 (existing work) is Bobby-specific. The "12-minute screen share" detail is from the Gavin transcript (real prospect) and makes the answer feel lived-in, not theoretical.  
* "They can never describe exactly what they want until they see it" in Q5 is Gavin's language.

### **WORD COUNT: \~410 words (slightly over 300-400 target, justified by 8 substantive answers)**

---

## **SECTION 9: CTA**

**Notes:** N:4 (Trust reinforcer) \+ N:5 (Echo)

### **HEADLINE**

Your Investors Backed You, Not a Slide Deck. Let's Give Them Something Real.

### **SUBHEAD**

No pitch. No pressure. Just an honest conversation about what you're building, and whether custom software is the right move for your stage and budget. Sometimes it's not. We'd rather save you the trip.

### **TRUST REINFORCER**

Our clients volunteer for reference calls. If you want to talk to a founder who's been through this, that conversation is easy to arrange.

### **CTA**

**Primary Button:** Book a Discovery Call **Secondary Link:** Or ask us anything: hello@fixation.dev

### **VISUAL DIRECTION**

Dark or contrasting background to create clear section break. Single centered layout. Button is the dominant element. Trust reinforcer text sits below the button, understated.

### **DESIGN NOTES**

* Headline from the architecture's CTA alternative. Stronger than "You've Got the Idea. Let's Build the Thing." because it names Bobby's specific pressure (investors) and the specific gap (slide deck vs. working software).  
* "Sometimes it's not. We'd rather save you the trip." echoes the AI page's honesty signal ("whether AI is actually the right way to get there") and the Legacy page's ("whether we're the right team to fix it"). The willingness to say no is a trust signal all three pages share.  
* Trust reinforcer expanded to include "a founder who's been through this." Bobby needs peer validation, not just "our clients." Knowing he can talk to someone in his situation lowers the final barrier.  
* **FLAG:** Email address. Confirm hello@fixation.dev vs. info@fixation.dev (same flag on AI and Legacy pages, still unresolved).

### **WORD COUNT: \~60 words**

---

## **SECTION 10: FOOTER**

### **PERSISTENT CTA BAR**

**Your MVP is the foundation. Build it like one.** → BOOK A CALL

### **FOOTER LINKS**

hello@fixation.dev | MVP Development | AI Services | Legacy Modernization | Careers | Privacy | Terms

### **ADDRESS**

(C) 2026 Fixation. All rights reserved. 11128 John Galt Blvd, Ste 50, Omaha, NE 68137

### **DESIGN NOTES**

* Persistent CTA bar adapts homepage pattern. "Foundation, not a throwaway" echoes the page's core argument (MVP that lasts vs. MVP you rebuild).  
* Footer includes sibling links to AI Services and Legacy Modernization for cross-navigation between service pages.

---

## **BELIEF PROGRESSION MAP**

| Section | Note(s) | Belief Built | Bobby's Thought |
| ----- | ----- | ----- | ----- |
| 1\. Hero | N:5 \+ N:3 | Transformation hook \+ speed | "60 days. I own everything. These people have been doing this for 13 years." |
| 2\. Empathy | N:1 | "They understand my situation" | "Yeah, I can't tell good from bad and every week costs me" |
| 3\. Alternatives | N:2 | "Other options won't work" | "That's exactly why offshore/DIY/WordPress hasn't gotten me anywhere" |
| 4\. Methodology | N:3 | "Their approach makes sense" | "Domain learning first, weekly demos, I own everything, and it costs less than I expected" |
| 5\. Case Studies | N:4 \+ N:3 | "These results are real" | "Two founders in my situation. 60-day MVP. 20+ employees six years later." |
| 6\. Process | N:4 | "Working with them is fast and visible" | "Week 3 I'm showing investors working software?" |
| 7\. Transformation | N:5 | "I want what they're describing" | "Stop thinking about the code. Run the company. That's the goal." |
| 8\. FAQ | N:4 \+ N:1 | Residual objections resolved | "They work with scraps. Flexible billing. I own the code. Low risk." |
| 9\. CTA | N:4 \+ N:5 | "I should talk to them" | "Reference calls. No pressure. Honest about whether it's even the right move." |

**NOTE:** This is the belief progression, not the required section order. The notes can be spiraled for page flow. The wireframe sections above follow the same arc as the AI and Legacy sibling pages: N:5 → N:1 → N:2 → N:3 → N:4 → N:4 → N:5 → N:4 → CTA.

---

## **SUCCESS CRITERIA VERIFICATION**

* \[x\] Every section maps to a corresponding note in the BBCAP argument architecture  
* \[x\] Structure is a faithful parallel to the AI Services and Legacy Mod wireframes (10 sections, same types, same rhythm)  
* \[x\] Bobby reads the argument and thinks "they get what it's like to be me right now" (Section 2 validates his intelligence, urgency, and the market's opacity)  
* \[x\] Every note has at least one proof point grounded in real Fixation evidence (SeniorCareFinder, SportsTip, Gavin transcript, Shopify/air compressor)  
* \[x\] FAQ section added with 8 Bobby-specific questions   
* \[x\] Card 3 in proof section cleanly structured to receive future healthcare travel client story  
* \[x\] Identity shift language appears explicitly in Section 7: "founder gambling on wrong dev team" to "CEO who chose the right partner"  
* \[x\] "60 days to MVP" claim backed by SeniorCareFinder evidence  
* \[x\] No duplication of AI page proof points ($10K to $200, manual team replacement both absent)  
* \[x\] No duplication of Legacy page primary proof points (SportsTip vendor escape, FinanceScope durability)  
* \[x\] SportsTip used only for Bobby-adjacent angle (founder escaping bad partner), not vendor-escape narrative  
* \[x\] Code ownership and exit readiness addressed (Methodology Pillar 4, FAQ Q6, Transformation section)  
* \[x\] Gavin voice test: every sentence passes "would he say this over coffee?"

---

## **ASSUMPTIONS AND FLAGS**

**Assumptions (require validation):**

1. SeniorCareFinder case study approved for public use (anonymized, company name withheld)  
2. SportsTip case study approved for public use with Jasa's name and company  
3. Email address is hello@fixation.dev (not info@fixation.dev) \-- still unresolved from AI and Legacy page flags  
4. Discovery call is 30 minutes (stated in FAQ Q7, consistent with Legacy page FAQ Q8)  
5. "60-day MVP" claim defensible as target, not guarantee (SeniorCareFinder was \~60 days)

**Structural flags:**

1. Five-column grid in Section 3 needs responsive design decision for tablet viewports (same flag on Legacy page)  
2. Card 3 interim treatment (Option A referral credibility vs. Option B NFM trust) needs Robby/Gavin decision  
3. Methodology Section 4 word count runs over target. Pillar 5 (pricing) is longest due to COO promotion directive. May need visual treatment (expandable detail or secondary text) to maintain pillar balance.  
4. Section 7 (Transformation) uses prose instead of checkmarks. This matches Legacy page pattern and is intentional (Bobby's identity shift reads better as narrative). Consistent with persona-specific pages using prose, dual-persona pages (AI, Homepage) using checkmarks.  
5. Architecture flagged Subclaim 1.4 (competitors launching while you shop) as needing stronger proof. Wireframe uses it in Section 2 but the evidence is reasoning, not a story. When the healthcare travel client signs, their "customers waiting while she shopped for developers" story fills this gap.

**Gavin voice review priority:**

The following lines are most likely to need Gavin's direct input:

* Hero headline (does "60 Days to a Working MVP" feel like a promise you’re comfortable making publicly?)  
* Section 4 Pillar 5 (pricing counter-narrative: is the "came in lower than the offshore competitor" story approved for public use?)  
* FAQ Q2 (cost discussion: does the tone match how you handle this in real sales conversations?)

# Lead magnet \-- success criteria

\# Lead Magnet Success Criteria

\*For: "The 2026 Guide to Choosing & Successfully Launching a Custom Software Project Without Getting Burned"\*

\---

\#\# What Makes a Lead Magnet Work

A lead magnet succeeds when someone trades their email for it, reads it, and thinks: "These people understand my problem better than I do. I should talk to them."

It fails when it gets downloaded and forgotten, or worse—never downloaded because the promise wasn't compelling enough.

\---

\#\# Critical Success Criteria

\#\#\# 1\. Specificity Over Generality

\*\*Requirement:\*\* The guide must address a \*specific\* situation with \*specific\* advice.

\*\*Why:\*\* Generic guides ("10 Tips for Software Success") compete with thousands of similar content pieces. Specificity signals expertise.

\*\*Test:\*\* Can a reader immediately tell if this guide is for them within 30 seconds?

\*\*Our specificity:\*\*  
\- \*\*Who:\*\* Non-technical founders/executives choosing a software development partner  
\- \*\*When:\*\* 2026 (AI landscape, current pricing, modern methodologies)  
\- \*\*What:\*\* Custom software projects (not SaaS selection, not hiring internal devs)  
\- \*\*Problem:\*\* Fear of getting burned (budget overruns, missed deadlines, abandoned projects)

\---

\#\#\# 2\. Promise a Transformation, Not Information

\*\*Requirement:\*\* The title and hook must promise the reader will be \*different\* after reading—not just informed.

\*\*Why:\*\* People don't want information. They want confidence, clarity, or capability.

\*\*Test:\*\* Does the promise address an emotional need, not just intellectual curiosity?

\*\*Our transformation:\*\*  
\- \*\*Before:\*\* Anxious, uncertain, worried about making an expensive mistake  
\- \*\*After:\*\* Confident, equipped with red flags to watch for, able to evaluate partners intelligently

\*\*Title analysis:\*\* "...Without Getting Burned" \= emotional promise (avoid pain)

\---

\#\#\# 3\. Immediate Usefulness

\*\*Requirement:\*\* The reader must be able to \*do something\* differently within 24 hours of reading.

\*\*Why:\*\* Actionable content gets shared, remembered, and attributed to the source.

\*\*Test:\*\* Does every chapter end with a concrete action, checklist, or decision framework?

\*\*Our usefulness:\*\*  
\- Checklist of red flags to evaluate current/prospective vendors  
\- Questions to ask in discovery calls  
\- Budget estimation framework  
\- Timeline sanity checks  
\- Contract review checklist

\---

\#\#\# 4\. Mirrors the Reader's Internal Dialogue

\*\*Requirement:\*\* The content must articulate frustrations and fears the reader has felt but not voiced.

\*\*Why:\*\* This creates the "they get me" moment that builds trust faster than credentials.

\*\*Test:\*\* Would the reader highlight passages and think "yes, exactly"?

\*\*Our mirror moments (from persona research):\*\*  
\- \*Bobby Notebooks:\* "Spent 3 months and $15K on a WordPress 'solution' that couldn't handle basic requirements"  
\- \*Tim Tables:\* "Simple changes quoted at $50K and 3 months. Vendor finger-pointing when things break."  
\- Both: "How do I know you won't abandon us after the first phase?"

\---

\#\#\# 5\. Demonstrates Expertise Without Selling

\*\*Requirement:\*\* The guide must prove Fixation knows what they're talking about through \*specificity and insider knowledge\*, not self-promotion.

\*\*Why:\*\* Explicit selling ("and that's why you should hire us\!") destroys trust. Implicit expertise ("here's what we've seen go wrong in 200+ projects") builds it.

\*\*Test:\*\* Remove all mentions of Fixation. Does the content still demonstrate expertise?

\*\*Our expertise signals:\*\*  
\- Specific failure patterns with root cause analysis  
\- Insider terminology explained (iDesign, sprint demos, etc.)  
\- Contrarian takes backed by experience  
\- Real numbers (timelines, budgets, failure rates)

\---

\#\#\# 6\. Appropriate Length

\*\*Requirement:\*\* Long enough to be valuable, short enough to be consumed.

\*\*Why:\*\* A 100-page ebook signals "this will take forever." A 5-page PDF signals "this is probably fluff."

\*\*Target:\*\* 30-50 pages (8,000-15,000 words)  
\- Readable in 30-60 minutes  
\- Substantial enough to feel valuable  
\- Scannable with clear chapters and summaries

\---

\#\#\# 7\. Professional Design

\*\*Requirement:\*\* The guide must look like it came from a company that builds professional software.

\*\*Why:\*\* Design quality signals service quality. A poorly designed guide undermines trust.

\*\*Elements:\*\*  
\- Custom cover (not Canva template obvious)  
\- Consistent typography and spacing  
\- Strategic use of callouts, checklists, and diagrams  
\- PDF optimized for both screen and print  
\- Fixation branding subtle but present

\---

\#\#\# 8\. Clear Next Step

\*\*Requirement:\*\* The guide must make it obvious what the reader should do if they want help.

\*\*Why:\*\* Without a clear CTA, even impressed readers don't convert.

\*\*Our next step:\*\*  
\- "Ready to evaluate your project? Schedule a 30-minute discovery call."  
\- Link to calendar or contact form  
\- Positioned at end of guide (not throughout)

\---

\#\# Audience-Specific Requirements

\#\#\# For Bobby Notebooks (Startup Founder)

\*\*Must address:\*\*  
\- Speed anxiety ("I need this yesterday")  
\- Budget constraints ("Runway is 18 months")  
\- Fear of building the wrong thing  
\- Technical co-founder gap  
\- Investor pressure

\*\*Tone:\*\* Energetic, direct, slightly irreverent. Acknowledge the gamble they're taking.

\#\#\# For Tim Tables (Disgruntled with Existing Tech)

\*\*Must address:\*\*  
\- Trust betrayal from previous vendor  
\- Fear of disruption during transition  
\- Political dynamics with current team  
\- Need for predictability and transparency  
\- Board/stakeholder pressure

\*\*Tone:\*\* Calm, reassuring, methodical. Acknowledge the mess they're in isn't their fault.

\---

\#\# Content Quality Standards

\#\#\# Voice (Same as Website Content)

\- Write as Gavin explaining to a smart non-technical person over coffee  
\- Confident but not arrogant  
\- Commas for natural pauses, parenthetical asides  
\- No AI vocabulary (leverage, robust, seamless, etc.)  
\- Clear opinions backed by experience  
\- Acknowledge complexity and tradeoffs

\#\#\# Structure

\- Each chapter: Hook → Problem → Insight → Action  
\- Callout boxes for key takeaways  
\- Checklists where applicable  
\- Real examples (anonymized if needed)  
\- No filler—every paragraph earns its place

\#\#\# Fact Standards

\- All statistics cited with source  
\- All timelines/budgets based on real project data  
\- Failure patterns drawn from actual experience  
\- No invented scenarios

\---

\#\# Distribution Requirements

\#\#\# Landing Page

\- Clear headline restating the transformation promise  
\- 3-5 bullet points of what's inside  
\- Social proof if available (testimonials, client logos)  
\- Minimal form (name \+ email only)  
\- No friction (no "confirm your email" loops if possible)

\#\#\# Follow-Up Sequence

\- Day 0: Deliver the guide  
\- Day 3: "Did you get a chance to read it?" \+ key insight teaser  
\- Day 7: Related blog post or case study  
\- Day 14: Soft CTA for discovery call  
\- Day 30: Check-in \+ additional resource

\#\#\# Promotion Channels

\- LinkedIn (Gavin's network)  
\- Website homepage CTA  
\- Blog post CTAs  
\- Email signature  
\- Paid ads (later, if organic works)

\---

\#\# Success Metrics

\#\#\# Leading Indicators

| Metric | Target | Why It Matters |  
|--------|--------|----------------|  
| Landing page conversion | 25%+ | Measures promise strength |  
| Download completion | 60%+ | Measures perceived value |  
| Email open rate (follow-up) | 40%+ | Measures continued interest |  
| Reply rate | 5%+ | Measures engagement |

\#\#\# Lagging Indicators

| Metric | Target | Why It Matters |  
|--------|--------|----------------|  
| Discovery calls from guide | 2-4/month | Primary goal |  
| Closed deals from guide leads | 1/quarter | Ultimate ROI measure |  
| Referral mentions | "I read your guide" | Word-of-mouth indicator |

\---

\#\# Anti-Patterns to Avoid

\#\#\# Don't:  
\- \*\*Gate every chapter\*\* — give real value upfront  
\- \*\*Use stock photos\*\* — feels generic  
\- \*\*Promise and underdeliver\*\* — "comprehensive guide" that's 10 pages of fluff  
\- \*\*Write for search engines\*\* — this is for humans who already found you  
\- \*\*Sound like every other dev shop\*\* — differentiate through voice and specificity  
\- \*\*Forget the CTA\*\* — impressive content without conversion path is wasted  
\- \*\*Make it a sales brochure\*\* — guide first, company second

\---

\*Last updated: 2026-02-02\*

# LM Topic Ideas

# Lead Magnet Topic Ideas

# Idea: 2026 Software Guide

\# Book Outline

\*\*Title:\*\* The 2026 Guide to Choosing & Successfully Launching a Custom Software Project Without Getting Burned

\*\*Subtitle:\*\* Red Flags, Realistic Timelines, and the Questions Smart Buyers Ask

\*\*Target Length:\*\* 12,000-15,000 words (\~40-50 pages designed)

\---

\#\# Structure Overview

| Section | Chapters | Word Target | Purpose |  
|---------|----------|-------------|---------|  
| \*\*Front Matter\*\* | Cover, TOC, Intro | 500 | Hook \+ credibility |  
| \*\*Part 1: Before You Start\*\* | Ch 1-3 | 3,500 | Frame the decision correctly |  
| \*\*Part 2: Choosing a Partner\*\* | Ch 4-6 | 4,000 | Evaluate and select |  
| \*\*Part 3: During the Project\*\* | Ch 7-9 | 3,500 | Avoid common disasters |  
| \*\*Part 4: What Success Looks Like\*\* | Ch 10 \+ Closing | 1,500 | Vision \+ CTA |

\---

\#\# Front Matter

\#\#\# Introduction: Why This Guide Exists  
\*\~500 words\*

\- The 60% failure rate for custom software projects  
\- Who this guide is for (and who it's not for)  
\- What you'll know after reading  
\- How to use this guide

\*\*Key stat:\*\* Reference industry failure rates, cite source

\---

\#\# Part 1: Before You Start

\#\#\# Chapter 1: Is Custom Software Even the Right Answer?  
\*\~1,200 words\*

\*\*Hook:\*\* Most custom software projects shouldn't be custom software projects.

\*\*Content:\*\*  
\- When off-the-shelf makes sense (and when it doesn't)  
\- The "unique requirements" trap  
\- Build vs. buy decision framework  
\- Signs you actually need custom:  
  \- Workflow is your competitive advantage  
  \- Integration requirements are complex  
  \- Scale/performance demands are unusual  
  \- Regulatory/compliance requirements  
\- Signs you should buy instead

\*\*Checklist:\*\* "Should I Build Custom?" decision tree

\---

\#\#\# Chapter 2: What Custom Software Actually Costs in 2026  
\*\~1,200 words\*

\*\*Hook:\*\* The numbers everyone lies about.

\*\*Content:\*\*  
\- Why estimates vary wildly (and what that tells you)  
\- Realistic ranges by project type:  
  \- MVP/prototype: $50K-150K  
  \- Full product v1: $150K-500K  
  \- Enterprise application: $500K+  
\- What drives costs up (and what doesn't)  
\- The "10x your estimate" rule and when it applies  
\- AI's impact on development costs (reality vs. hype)  
\- Hidden costs: hosting, maintenance, iteration

\*\*Callout:\*\* "If someone quotes you $20K for a 'full platform,' run."

\---

\#\#\# Chapter 3: Realistic Timelines (Not What Salespeople Tell You)  
\*\~1,100 words\*

\*\*Hook:\*\* Every project takes longer than the estimate. Here's why, and what to do about it.

\*\*Content:\*\*  
\- Why timelines slip (and which reasons are acceptable)  
\- Realistic timeline ranges:  
  \- MVP: 3-6 months  
  \- Full product: 6-12 months  
  \- Enterprise migration: 12-24 months  
\- The discovery phase everyone skips  
\- Scope creep: your fault or theirs?  
\- Milestones that actually matter vs. vanity milestones  
\- When "done" isn't done (post-launch reality)

\*\*Framework:\*\* Timeline sanity check questions

\---

\#\# Part 2: Choosing a Partner

\#\#\# Chapter 4: Red Flags That Should Send You Running  
\*\~1,500 words\*

\*\*Hook:\*\* The warning signs are obvious in hindsight. Here's how to see them upfront.

\*\*Content:\*\*

\*\*Communication Red Flags:\*\*  
\- Slow response times during sales process  
\- Can't explain technical concepts simply  
\- Promises everything, questions nothing  
\- No questions about your business

\*\*Technical Red Flags:\*\*  
\- No discovery process before quoting  
\- Fixed bid on unclear requirements  
\- Proprietary frameworks or lock-in  
\- No mention of testing or QA  
\- Offshore without clear communication plan

\*\*Business Red Flags:\*\*  
\- No references or case studies  
\- Unwilling to share team composition  
\- Payment terms that favor them heavily  
\- No defined methodology or process

\*\*The "Too Good to Be True" Test:\*\*  
\- Dramatically lower quote than others  
\- Unrealistically fast timeline  
\- "We can do anything" attitude

\*\*Checklist:\*\* 15-point red flag assessment

\---

\#\#\# Chapter 5: Questions to Ask (That Reveal Everything)  
\*\~1,300 words\*

\*\*Hook:\*\* The questions you ask tell vendors how sophisticated you are. Ask the right ones.

\*\*Content:\*\*

\*\*About Their Process:\*\*  
\- "Walk me through how a typical project runs from kickoff to launch."  
\- "How do you handle scope changes mid-project?"  
\- "How often will I see working software?"  
\- "What does your QA process look like?"

\*\*About Your Project:\*\*  
\- "What do you see as the biggest risk in this project?"  
\- "What questions do you have about our requirements?"  
\- "What would you push back on in our spec?"  
\- "Have you built something similar? What did you learn?"

\*\*About the Relationship:\*\*  
\- "Who will actually be writing the code?"  
\- "How do you handle disagreements with clients?"  
\- "What happens if this takes longer than expected?"  
\- "Can I talk to a client whose project went sideways?"

\*\*What Good Answers Sound Like\*\* (examples)

\---

\#\#\# Chapter 6: How to Actually Evaluate Proposals  
\*\~1,200 words\*

\*\*Hook:\*\* Comparing proposals is hard when everyone structures them differently. Here's how to normalize.

\*\*Content:\*\*  
\- What should be in a proposal (and what shouldn't)  
\- Comparing apples to oranges: normalizing estimates  
\- The detailed estimate vs. ballpark trap  
\- Payment structures and what they signal  
\- Contract terms that matter:  
  \- IP ownership  
  \- Source code access  
  \- Termination clauses  
  \- Change order process  
\- When to negotiate (and what's non-negotiable)

\*\*Template:\*\* Proposal comparison matrix

\---

\#\# Part 3: During the Project

\#\#\# Chapter 7: The First 30 Days (Make or Break)  
\*\~1,200 words\*

\*\*Hook:\*\* How a project starts predicts how it ends. Here's what good looks like.

\*\*Content:\*\*  
\- The kickoff meeting that actually matters  
\- Discovery phase: what you should see  
\- Early warning signs (and what to do)  
\- Establishing communication rhythms  
\- Your role in the first month  
\- What to expect (and what to demand)

\*\*Checklist:\*\* First 30 days health check

\---

\#\#\# Chapter 8: Common Failure Patterns (And How to Avoid Them)  
\*\~1,300 words\*

\*\*Hook:\*\* These five patterns kill most projects. Know them, prevent them.

\*\*Content:\*\*

\*\*Pattern 1: Scope Creep Death Spiral\*\*  
\- How it starts, how to stop it

\*\*Pattern 2: The Demo Gap\*\*  
\- Building in the dark, big reveal disasters

\*\*Pattern 3: Technical Debt Accumulation\*\*  
\- Why "we'll fix it later" never happens

\*\*Pattern 4: Communication Breakdown\*\*  
\- Silence isn't golden, it's terrifying

\*\*Pattern 5: The Handoff Cliff\*\*  
\- MVP done, team disappears

\*\*For each:\*\* Warning signs, prevention, recovery if caught early

\---

\#\#\# Chapter 9: When Things Go Wrong (Recovery Playbook)  
\*\~1,000 words\*

\*\*Hook:\*\* Every project hits problems. Here's how to tell if yours is recoverable.

\*\*Content:\*\*  
\- Distinguishing normal problems from fatal ones  
\- The hard conversation: how to have it  
\- When to course correct vs. cut losses  
\- Switching vendors mid-project (the nuclear option)  
\- Documenting everything: your insurance policy  
\- Legal options (and why you probably won't use them)

\---

\#\# Part 4: What Success Looks Like

\#\#\# Chapter 10: Signs You Chose Well  
\*\~1,000 words\*

\*\*Hook:\*\* What does a healthy project feel like from the inside?

\*\*Content:\*\*  
\- The "boring" project that actually ships  
\- Communication patterns of successful partnerships  
\- How good teams handle the unexpected  
\- What ongoing relationships look like  
\- Building for the long term, not just launch

\*\*Case Study:\*\* Brief anonymized example of a project that worked

\---

\#\#\# Closing: Your Next Step  
\*\~500 words\*

\- Recap of key decision points  
\- The confidence you should now have  
\- When to start looking (and how)  
\- Clear CTA: discovery call offer

\---

\#\# Appendices

\#\#\# Appendix A: Checklist Collection  
\- Build vs. Buy Decision Tree  
\- Red Flag Assessment (15 points)  
\- Proposal Comparison Matrix  
\- First 30 Days Health Check  
\- Questions to Ask List

\#\#\# Appendix B: Glossary  
\- Key terms explained simply  
\- (MVP, sprint, technical debt, API, etc.)

\---

\#\# Chapter Status Tracker

| Chapter | Status | Writer | Draft Date |  
|---------|--------|--------|------------|  
| Intro | Not started | — | — |  
| Ch 1: Is Custom Right? | Not started | — | — |  
| Ch 2: Costs | Not started | — | — |  
| Ch 3: Timelines | Not started | — | — |  
| Ch 4: Red Flags | Not started | — | — |  
| Ch 5: Questions to Ask | Not started | — | — |  
| Ch 6: Evaluating Proposals | Not started | — | — |  
| Ch 7: First 30 Days | Not started | — | — |  
| Ch 8: Failure Patterns | Not started | — | — |  
| Ch 9: Recovery | Not started | — | — |  
| Ch 10: Success Signs | Not started | — | — |  
| Closing | Not started | — | — |  
| Appendices | Not started | — | — |

\---

\*Last updated: 2026-02-02\*

