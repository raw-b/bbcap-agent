# How a Sports Travel Platform Broke Free from Vendor Lock-In and Grew 40%

*Draft v5.2 — 2026-02-02*

---

The platform worked. That was the problem.

SportsTrip's travel booking system—the engine that let college athletic departments book hotels, buses, and flights for their teams—did what it was supposed to do. Hotels got RFPs. Teams got quotes. Contracts got signed. The technology wasn't broken. It was just trapped.

Every feature request went to a single vendor who had "other fish to fry." Timelines were promises, not commitments. The codebase sat on proprietary Java frameworks that only one company could touch. And when SportsTrip's CEO Jasa Rhone asked about getting work done faster? "We never know when work will start," he explained. "We have to beg for hours. There's no contract in place."

## **Held Hostage by Your Own Platform**

SportsTrip wasn't a startup struggling to find product-market fit. They had proven their model. College athletic programs across the country used their platform because the RFP workflow actually worked—teams could get competitive hotel bids in hours instead of days.

But growth was creating problems their technology partner couldn't solve. Adding flight booking had been "coming soon" for months, pushed from early summer to late summer to "maybe fall." The electronic signature workflow—critical when you're processing hundreds of contracts per week—was still a mess of Word documents and manual back-and-forth.

The real risk wasn't technical. It was strategic. SportsTrip was building a business on infrastructure they didn't control: proprietary CMS libraries, a hosting arrangement tied to their vendor's AWS account, and a codebase that only one company in the world could modify. If that vendor raised prices, pivoted to other clients, or simply got slower—and they were getting slower—SportsTrip had no leverage and no alternatives.

## **The Rebuild That Didn't Break Anything**

The engagement started in late 2022 with a question: what would it take to rebuild this platform on technology SportsTrip actually owns?

Migrating a live platform serving college athletic programs across the country isn't a weekend project. Every hotel relationship, every team workflow, every contract template had to move from the old Java/Spring system to a new .NET architecture without a single booking falling through the cracks.

The first step wasn't writing code. It was understanding the business deeply enough to know what couldn't break. The RFP workflow—where SportsTrip sends customized requests to hotels and gets structured responses back—isn't just a feature. It's the competitive advantage. Hotels respond faster to SportsTrip because the system makes their jobs easier. That workflow had to survive the migration exactly as it was.

The technical migration moved from proprietary Java frameworks to .NET, from rented infrastructure to Azure services SportsTrip owns directly. But the architecture decisions mattered more than the technology choices. Clean separation between the booking engine, the CRM layer, and the reporting tools means features can evolve independently.

Weekly iterations kept the transition visible. Not quarterly check-ins where problems hide until they're expensive. Every week, working software. Every week, stakeholders could see exactly what was changing and catch issues early.

The platform launched in mid-2023. And the feature requests that had been languishing for months? Electronic signatures went from request to production in weeks, not the "maybe next quarter" timeline Jasa had grown accustomed to.

## **40% Growth on a Platform They Own**

The college segment grew 40% year-over-year. Features that were perpetually "on the roadmap" with their previous vendor now ship regularly. The development pace matches the business pace instead of constraining it.

The feedback from Jasa's team captured the shift: "Love working with the team. Lightyears ahead of where we were with previous guys."

The platform that felt like a constraint now feels like a competitive advantage. When competitors approach athletic departments with generic booking tools, SportsTrip's RFP system—purpose-built for how college sports actually work—wins deals.

## **The Difference Between Renting and Owning**

Three years into the relationship, SportsTrip scales their development hours up and down based on seasonal cash flow. July and August get tight (hotels pay on delay, commissions come later), so hours flex down. When booking season hits and they need to move fast, hours flex up. No lengthy negotiations. No penalty clauses. No begging.

That flexibility only works when you trust your technology partner to optimize for your success instead of their billable hours. When the platform you depend on is truly yours—code, infrastructure, and all—you negotiate from strength instead of weakness.

---

**\[VERIFICATION STATUS\]:**

- [x] CEO: Jasa Rhone  
- [x] Previous vendor: Proteus (proprietary Java/Spring/Hibernate stack)  
- [x] Problem: "other fish to fry", begging for hours, no contract  
- [x] Migration: Late 2022 start → mid-2023 launch  
- [x] New stack: .NET, Azure (client-owned)  
- [x] E-signatures: Delivered (was major pain point)  
- [x] 40% college segment growth (June 2024 notes)  
- [x] Ongoing relationship confirmed (Dec 2025 \- security/MFA help)  
- [x] Flexible hours model confirmed  
- [x] Permission to use Jasa's name and company name publicly  
- [ ] Any specific metrics Jasa wants highlighted or excluded

**Target audience:** Bobby Notebooks (founder escaping vendor lock-in) \+ Tim Tables (owner wanting flexibility)  
**Key differentiators:** Vendor escape, code ownership, flexible engagement, weekly demos  
**Word count:** \~820  