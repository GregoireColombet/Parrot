#General certifications

##ITAR L'ITAR (International Traffic in Arms Regulations) 

Ensemble de réglementations fédérales américaines rigoureuses, gérées par le Département d'État, qui contrôlent l'exportation, l'importation et le transfert de technologies, de données techniques et de services de défense recensés sur la United States Munitions List (USML). Elle vise à protéger la sécurité nationale en restreignant l'accès à ces matériels aux personnes américaines uniquement.

##ANAFI Parrot 

Offers certified training programs for ANAFI USA and ANAFI Ai drones, designed to train pilots in safe and effective operation. The training covers ground school and hands-on flight, specifically tailored to the drone model (USA/Ai). Additionally, ANAFI Ai holds network certifications (Verizon, AT&T, FirstNet) and utilizes FIPS140-2 compliant cybersecurity.

##MIL-SPEC MIL-SPEC (Military Specification) 

Refers to technical standards set by the U.S. Department of Defense to ensure products meet strict performance, reliability, and compatibility requirements. These standards cover materials, design, and testing, commonly used in defense, aerospace, and specialized industrial sectors.

# Interview Q&A — Grégoire Colombet × Parrot HR
**Context:** Parrot considering production in Taiwan · XR & Supply Chain Leadership role  
**Format:** HR questions to candidate + Candidate questions to HR

---

## Part 1 — HR questions to Grégoire (with his answers)

### ODM & Taiwan Supply Chain

**1. How would you approach qualifying and onboarding a new manufacturing partner in Taiwan — what are the first 90 days?**

Day one through thirty is all about listening and mapping. I'd do a full audit of their current production lines, quality systems, and key people — not to judge, but to understand how they think and where their pain points are. The relationship with an ODM is long-term, so trust has to be built before you start pushing on timelines or cost. Days thirty to sixty I'd focus on aligning engineering specs and setting up joint review cadences with both Parrot's R&D and the ODM's NPI team. By day ninety I want a shared dashboard, a clear escalation path, and at least one pilot build completed. With Compal at Lynx, the biggest mistake would have been to arrive with all the answers. I arrived with questions.

> ✅ Strong process thinking, names a real ODM by name

---

**2. You achieved a 3× cost reduction on certain components at Lynx. Walk me through that process.**

That was mostly on optics and camera modules. The initial pricing came from the ODM's preferred supplier network — convenient for them, expensive for us. I mapped the BOM component by component and identified where Lynx was paying a relationship tax rather than a market price. For the camera modules specifically, I ran a parallel sourcing process with three Taiwanese and one Chinese supplier, used the competing quotes to renegotiate with the original vendor, and ultimately switched two components entirely. The leverage is always information — knowing what the component actually costs at volume before you sit across the table. I also linked some deals to longer-term volume commitments, which gave suppliers a reason to sharpen their pencils.

> ✅ Concrete, tactical, names the mechanism — not just the outcome

---

**3. Parrot makes safety-critical drone hardware. How does that differ from consumer XR in your experience?**

Honestly, that's one of the things I find most interesting about Parrot. In XR, a firmware bug causes a bad user experience. In a drone used for inspection or defense, it can have real consequences. That shifts everything — your testing protocols, your supplier qualification criteria, your traceability requirements. I don't pretend I've shipped products under MIL-SPEC — I haven't. But at Lynx I worked with components that had very tight tolerance requirements for optics and IMUs, and I developed test protocols at Acer that improved motion sensor data precision by 60%. The mindset translates. What I'd want is a month of deep immersion in Parrot's current quality framework before I touch anything in the supply chain.

> 🟡 Honest about the gap — good self-awareness, but watch if pressed further

---

### R&D–Production Interface

**4. R&D in France, production in Taiwan. What were the biggest friction points and how did you solve them?**

Time zones and vocabulary. Engineers in France write a spec that makes perfect sense in French engineering culture, and the ODM interprets it through a Taiwanese manufacturing lens — and both sides think they understood each other. I became the translation layer, not just linguistically but conceptually. I'd rewrite ambiguous specs into manufacturability language before they ever reached Compal. I also pushed hard for quarterly face-to-face visits — video calls are fine for status updates but you can't build trust through a screen. The other big thing was building relationships at the right level on both sides. A project manager in France talking to a project manager in Taiwan creates a bottleneck. I worked to connect R&D engineers directly with ODM engineers on specific technical issues, which cut cycle time significantly.

> ✅ Shows cultural fluency, not just logistics management

---

**5. R&D wants a mid-production design change the ODM says will cause delays. How do you handle it?**

I don't side with anyone until I understand the cost of both paths. The ODM saying "delay" is often a negotiating position — I'd push for a concrete timeline impact, in writing. R&D wanting the change usually has a real reason — a field failure, a performance gap, a customer commitment. So I'd get both parties in a room, or a call, and make the tradeoff explicit: here's what changing costs, here's what not changing costs. Nine times out of ten there's a compromise — phased implementation, a delta build for specific markets, or a software workaround that buys time. The one thing I never do is let it become a bilateral negotiation where I'm shuttling messages. That always ends badly.

> ✅ Mature conflict resolution — names the trap and avoids it

---

### Fit & Motivation

**6. You've run four businesses in Taipei in parallel with your career. Would you step back from them?**

That's a fair question and I'd rather address it directly than let it sit in the room. My venues are managed businesses at this point — I have teams running day-to-day operations. The cocktail bar is the most recent and the most hands-on, but it's found its footing. I'm not behind the bar every night. What I'd say is this: the businesses gave me a different kind of intelligence that I bring to corporate roles — how to read a P&L, how to hire and retain people, how to build something from zero. I wouldn't pretend they take zero time, but they don't compete with a demanding full-time role. If Parrot needed exclusivity as a contractual condition, I'd discuss it openly.

> 🟡 Transparent but watch for time commitment ambiguity — probe further

---

### Taiwan Operations

**7. What are the top advantages and risks of setting up production in Taiwan for a French company like Parrot?**

Advantages: Taiwan has the deepest hardware supply chain ecosystem in the world for the components Parrot needs — sensors, cameras, PCBs, precision machining. The talent pool of engineers who've worked in consumer electronics at Foxconn, Compal, or Pegatron is enormous. And there's a culture of getting things done — timelines are taken seriously in a way that's sometimes painful but ultimately productive. Risks: geopolitical exposure is real and any board will ask about it. Supply chain concentration is a strategic vulnerability, and the US-China dynamic creates uncertainty around export regulations that affect Parrot's defense segment directly. There's also a cultural gap that French companies consistently underestimate — the relationship-first dynamic here means that pushing hard on price or timelines without investing in the relationship first will cost you more in the long run than whatever you saved.

> ✅ Nuanced, names the geopolitical risk unprompted — shows strategic maturity

---

## Part 2 — Grégoire's questions to Parrot HR

### Phase 1 — Understanding the role

**1. Who defined this role — was it driven by HR, or did a business leader come to you with a specific need?**

*Why ask:* If HR created this role top-down without a clear business sponsor, it may not survive the next reorganization. I want to know there's a P&L owner in the business who actually needs me — not just a headcount slot that appeared in a planning exercise.
`Probing company readiness`

---

**2. What happened before me? Was there someone in this role previously, or is this genuinely new?**

*Why ask:* If someone left, I want to know why — diplomatically. If it's new, I want to understand what triggered it. A role created because of a failed initiative is very different from one created because of a strategic expansion. HR will often soften this — I'll read between the lines.
`Reading culture & intent`

---

**3. How is success measured in this role at 6 months and at 18 months — and who owns that assessment?**

*Why ask:* Vague answers here are a red flag. If HR can't articulate concrete KPIs, it means the role is poorly defined and I'll spend the first year fighting for clarity. A good answer names specific milestones: first production run, supplier contracts signed, cost targets.
`Probing company readiness`

---

### Phase 2 — Testing company maturity on Taiwan

**4. Has Parrot worked with Taiwanese ODM or EMS partners before — and if yes, what was the experience?**

*Why ask:* This is my most important question to HR. If they've tried and failed, I need to know the real reason before I inherit the problem. If they haven't, I need to size my mandate accordingly — because building the relationship from scratch takes 12 months minimum.
`Deliberate trap question`

---

**5. What's the board's rationale for Taiwan specifically — cost reduction, supply chain proximity, or ODM capability access?**

*Why ask:* In 2026, choosing Taiwan purely for cost is naive — labor advantages have largely eroded and geopolitical risk has increased. If the answer is cost-driven, that's a strategic misread and I'm walking into a project built on wrong assumptions. Proximity to the component ecosystem is the right answer.
`Probing company readiness`

---

**6. Has your legal team assessed the export control and ITAR implications of manufacturing Parrot's defense-adjacent products in Taiwan?**

*Why ask:* HR might not know the answer — and that's informative. If a company is planning Taiwan production without having run this past legal counsel, the initiative is not mature enough to hire for. It tells me I'd be setting up an operation that may need to be unwound.
`Deliberate trap question`

---

### Phase 3 — Culture & ways of working

**7. How does Parrot typically manage its relationship between Paris headquarters and people operating remotely or in Asia — is there a strong HQ-centric culture?**

*Why ask:* French companies can be highly Paris-centric. If every decision needs to go back to HQ for approval, I become a highly paid messenger. I've seen this dynamic kill Taiwan operations before. I want real authority, not a liaison title.
`Reading culture & intent`

---

**8. How does the leadership team view failure during a build phase — is there tolerance for iteration, or does a missed milestone become a political problem?**

*Why ask:* Setting up a new manufacturing operation always involves surprises. A company that treats first-year setbacks as execution failures will make the wrong decisions under pressure — cutting corners, pushing the ODM too hard, burning relationships. I need to know the psychological safety level.
`Reading culture & intent`

---

**9. Who are the two or three people in the company who will most directly shape whether this Taiwan initiative succeeds — and what's their track record with international operations?**

*Why ask:* HR sees the org chart. I want to know if there's a senior champion who has actually built something abroad before, or whether this is being driven by someone who thinks Asian manufacturing is just like ordering from a European supplier but cheaper.
`Probing company readiness`

---

### Phase 4 — The practical realities

**10. What's the compensation philosophy — is this role benchmarked against French market rates, Taiwan expat packages, or international tech company bands?**

*Why ask:* I'm a Taipei permanent resident who brings a network, language fluency, and 15 years of supply chain relationships that would take a Paris-based hire years to build. That's a premium skill set in this city. I want to know if Parrot has priced that.
`Anchoring my position`

---

**11. Is there a relocation expectation, or is this role anchored in Taiwan — and if I need to be in Paris regularly, what's the cadence and who covers it?**

*Why ask:* I live in Taipei, which is my biggest advantage for this role. If Parrot expects me to be Paris-based with frequent Asia trips, the logic inverts — they should be hiring from France, not from Taipei. The answer will tell me if they've really thought through why they're hiring someone already here.
`Anchoring my position`

---

**12. What does the first 30 days look like — is there an onboarding structure, or would I be expected to hit the ground running independently?**

*Why ask:* A company that throws someone into a new market without structured onboarding is telling you something. I don't need hand-holding, but I need access — to internal stakeholders, product roadmaps, supplier history, and legal constraints. If those aren't organized, I'll spend month one reconstructing information that already exists somewhere.
`Probing company readiness`

---

### Phase 5 — The closing move

**13. What's your honest assessment of the biggest internal obstacle to this initiative succeeding — not external, internal?**

*Why ask:* This is the question HR least expects. It signals I'm not naive, and it forces an honest conversation. The best HR people will tell you something real — resistance from a VP, budget uncertainty, a competing internal project. If they say "none, everything is aligned," that's the least credible answer possible.
`Deliberate trap question`

---

**14. If I ask you this question in 18 months, and the Taiwan operation is a success — what does that look like, and how does this role evolve?**

*Why ask:* I'm not looking for a job. I'm looking for a platform. A role that dead-ends after the setup phase doesn't interest me. The answer tells me whether Parrot sees this as a project or as the beginning of a long-term Asia presence — and whether there's a seat at the table for whoever builds it.
`Anchoring my position`

---

*Document prepared April 2026 · Parrot × Grégoire Colombet interview preparation*
