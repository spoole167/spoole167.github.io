## R: Reconnaissance

"Understand how others see your work and what they might do with it."

Every system tells a story not just to its users, but to anyone paying close attention. Reconnaissance is about learning to read that story the way an outsider would. It's a shift from creator to critic, from implementer to investigator.
In this phase, developers explore how every part of the lifecycle, from code to cloud, from local builds to production pipelines, can expose unexpected opportunities. Writing secure, stable code is not enough.
Developers need to look at what has been built the way a motivated stranger might, and ask:
What could I learn just by watching?
What could I influence without direct access?
Where are the shortcuts, defaults, and assumptions, and how could those be exploited?
How far down the supply chain does it go?
This phase includes deliberate, guided exposure to the behaviours and manipulations others have used before and might use again. It does not require being a specialist to learn from real-world case studies, reproduce incidents, or simulate how tiny changes in a config file, a dependency, or a script can have massive consequences.
The people probing these systems are not chaotic. They're thoughtful, patient, and often developers themselves, working with all the same tools and knowledge. Reconnaissance teaches respect and understanding for the adversary. The first step in building systems that can hold their ground.
Developers learn about the mechanics and motivations of attackers, which they can apply to their practices, tools, and systems. The aim is to expose them to the realities of cyber attacks through hands-on simulations and an examination of attack vectors and supporting elements, such as social engineering. As new vectors or vulnerabilities are discovered, development teams learn to spend time understanding the details, keeping themselves educated and prepared.

## E: Evaluation
"Look again. Would our system survive a curious mind?"

Now that developers have seen how things can be twisted, bent, or misunderstood, it's time to turn that lens on their own work.
Evaluation is about taking a hard, honest look at what has been built. Not just whether it works, but whether it holds up under pressure, manipulation, or creative misuse. Now that they've seen how people try to break things, can they spot where the design might trust too easily, assume too much, or rely on perfect behavior?
This phase is reflective, but it's not soft. Code, processes, and systems are revisited with sharper eyes. More challenging questions are posed:
What does this depend on, and is that still a good idea?
What happens if someone uses this in an unexpected way?
Is this default safe, or just convenient?
Are there things that were never tested, because no one imagined someone would do that?
Where can we improve, where is improvement needed by others?
Good engineers test their assumptions. Great engineers doubt them.
This phase is about surfacing weak points before someone else finds them and fixing the ones that matter most.

## F: Fortification

"Don't just build it, reinforce it."

After a system has been examined with curious and critical eyes, it's time to act. Fortification means building with the expectation that someone will push the edges, test your patience, and try things that weren't planned for.
It's not about locking everything down. It's about designing with resilience in mind:
Building in fail-safes, not just features.
Adding early warnings, not just error handling.
Ensuring systems notice strange behaviour, not just ignore or crash from it.
Ensuring pipelines, tools, and delivery processes aren't silent blind spots.
The aim is not just to defend code but to strengthen the entire scaffolding on which it lives. From the moment a tool is installed or code gets pulled into a repo, to how it's built, tested, packaged, shipped, and deployed, every step should be as deliberate and transparent as the code itself.
Good fortification is quiet but firm. It's the extra check in the workflow, the graceful fallback, the log that says "something's not right" long before it becomes a problem.

## L: Alert
"Know when something isn't right, before it's too late."

No system is perfect. Even with solid foundations and thoughtful design, things will go wrong. What matters next is how quickly it's noticed and how effectively the issue can be addressed.
Alert is about building systems that pay attention: systems that don't just fail silently but signal when something odd, dangerous, or unexpected is happening. It's not about drowning in logs or false positives; it's about clear, meaningful insight at the right moment.
A strong alert posture means:
Knowing what "normal" looks like makes it possible to spot when something deviates.
Tuning systems to raise their hand when something starts to slip.
Making noise that matters, alerting the right people, with the right urgency.
Keeping the blast radius small so that even if something breaks, it doesn't break everything.
It's also about preparation: rehearsing what will be done when the alerts fire. Good alerts aren't the end; they're the beginning of a fast, focused, and effective response.

## E: Escalate
"When something breaks, move fast but on purpose."

When things go sideways, a system should already know what to do, and so should the team. Escalate is about acting on the signals that Alert surfaces. It's where preparation meets execution. There's no scrambling; instead, activation. The essentials are contained, isolated, and protected while the team moves to understand and resolve the issue.
This isn't about hitting the panic button; it's about precision. Escalation means:
Limiting further impact.
Slowing, halting, or even rolling back automated processes as needed.
Adjusting trust boundaries.
Giving the team the tools and access needed to respond.
Whether it's reverting a config change or spinning up a containment environment, the key is that the system and the people don't freeze; they move.
The best escalation paths are practiced, predictable, and effective. They reduce noise, restore clarity, and keep the incident from becoming a disaster.

## X: Examine

"If it doesn't learn from it, it'll be relived."
Description:
Every incident, near-miss, or strange behavior is a message. This phase is about listening.
Examine is where the team stops, rewinds, and extracts the lessons. Not just "what broke," but why it broke, what helped, what slowed things down, and what will change as a result. The aim is not to assign blame, the aim is to level up.
It's also about revisiting assumptions:
Were the signals seen early enough?
Did systems react as expected?
Was the response smooth or messy?
Were the alerts meaningful, or just noise?
Was the issue contained, or just delayed?
This phase doesn't just apply to major incidents; it can follow a messy rollout, a confusing bug, or a process bottleneck. The goal is to build a culture of incremental hardening, tuning reflexes one lesson at a time.
This learning isn't private. It should be shared. By capturing and spreading what has been learned, a stronger team, a better playbook, and a more resilient system can be built.

**Appendix: Security by Law: What Developers Need to Know**
As part of REFLEX, developers are introduced to the essential legal and compliance landscape behind secure software development. 

Topics include:
- Key regulatory frameworks such as:
- The EU Cyber Resilience Act
- The U.S. Secure by Design initiative (CISA/NSA/ONCD)
- Sector-specific mandates (e.g., healthcare, finance)
- Secure Software Development Frameworks (e.g., NIST SSDF, OWASP SAMM)
- Code and data governance expectations (SBOMs, AI usage policies)
- How legal obligations map to technical practices in code, CI/CD, and infrastructure
- Why security is no longer just best practice; it's an enforceable expectation.
