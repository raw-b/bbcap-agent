# How FinanceScope Built a Portal They Can Actually Change

*Draft v5.3 — 2026-02-02*

---

When Troy Vosberg's team at FinanceScope needed to build a customer portal, they didn't just need a login screen and some dashboards. They needed a platform sophisticated enough to differentiate them in a crowded financial services market—one their customers would actually want to use.

Most development shops would have spec'd out the requirements, assigned some offshore developers, and delivered something functional but forgettable. FinanceScope had already seen that movie. They knew the difference between "technically complete" and "competitive advantage."

## **The Problem with Most Financial Portals**

Financial services platforms live or die by their customer experience. Your portal isn't just where clients check their numbers—it's often their primary touchpoint with your company. A clunky interface, slow load times, or confusing navigation doesn't just frustrate users. It makes them wonder if you're as outdated as your technology looks.

FinanceScope was building something from scratch, which meant they had a choice most companies don't get: do it right the first time, or inherit their own technical debt before even launching.

The stakes were high. Get the architecture wrong early, and every future feature becomes a battle against your own codebase. Lock yourself into proprietary frameworks, and you're negotiating from weakness when your vendor raises prices or disappears. Build it on a shaky foundation, and you'll spend years apologizing to customers while your competitors ship features.

## **Building for Independence**

The engagement started in 2021 with domain immersion—understanding not just what FinanceScope wanted to build, but why their customers would care. Financial portals are full of industry-specific workflows that generic developers miss: compliance requirements that vary by state, reporting formats that accountants expect, and integration patterns that match how financial professionals actually work.

The technical architecture used iDesign methodology, which meant clean separation of concerns from day one. Built on .NET 6 with SQL Server, the system integrates Mandrill for transactional email, Twilio for SMS notifications, and Application Insights for monitoring. Each component was built to be independently testable, deployable, and—critically—replaceable. When FinanceScope wanted to swap email providers, it took an afternoon instead of a quarter.

Everything runs on Azure infrastructure that FinanceScope owns directly—App Service and Azure SQL under their own subscription. No mysterious hosting fees that inflate over time. No "we'll need to migrate you to our new platform" conversations. The code, the data, the infrastructure—all theirs.

Weekly demos kept the build transparent. Not status reports that say "on track" while hiding problems. Actual working software, every week, with stakeholders clicking through real functionality. When something wasn't right, everyone knew immediately—before it became expensive to fix.

The platform launched in November 2023\. In the weeks leading up to launch, when scope expanded significantly beyond initial estimates, both teams worked together intensively to hit the deadline. "Those guys are impressive," the client noted. "Curtis, Lloyd—fantastic. Very helpful. Shooting me straight."

## **The Results That Compound**

Troy puts it simply: "With Fixation's assistance, we have created one of the most dynamic portals for our customers in our industry and continue to make adjustments as needed. They have been there and guided us through the entire process."

The platform now handles financing applications from dealers across the country—from Wheeler Auctions to Joel's Tractors—processing requests daily. Five years after the first line of code, the system keeps running, and FinanceScope keeps shipping features. The architecture that seemed like overkill in 2021 is the reason they can still move fast in 2026\.

That flexibility shows up in small ways that add up. Need to change an email provider? An afternoon. Need to add a new dealer workflow? A week, not a quarter. Need to hand the codebase to a different team someday? Everything is documented, tested, and running on infrastructure FinanceScope controls.

## **Where They Are Now**

The portal that started as a competitive differentiator is now the backbone of FinanceScope's customer relationships. Features that would have been "next year's roadmap" with another team ship quarterly. Technical debt that compounds at most companies stays near zero because the architecture was built to prevent it.

"I am confident in recommending Fixation to another business after the years of excellent service we have received," Troy says. He has—several times.

---

**\[VERIFICATION STATUS\]:**

- [x] Initial engagement date: 2021  
- [x] Tech stack: .NET 6, SQL Server, Azure App Service, Azure SQL, Mandrill, Twilio, App Insights  
- [x] Architecture: iDesign methodology  
- [x] Launch date: November 2023  
- [x] Ongoing relationship confirmed (Feb 2026 emails show active support)  
- [ ] Permission to use company name and Troy's full quote (need explicit approval)  
- [ ] Any specific metrics Troy wants highlighted (user count, etc.)

**Target audience:** Tim Tables (established business owner wanting reliability \+ flexibility)  
**Key differentiators:** Code ownership, iDesign architecture, long-term maintainability  
**Word count:** \~780