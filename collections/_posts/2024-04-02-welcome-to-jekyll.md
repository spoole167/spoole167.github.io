---
layout: default
title:  "Welcome to Jekyll!"
date:   2024-04-01 17:00:25 +0100
categories: jekyll update
permalink: a2
pics: singapore2024
---
# March 2025: Software and AI Legislation on the Horizon

AI regulation has gone from drawing-board theory to enforceable reality. As of Q1 2025, the legislative landscape around AI is heating up fast — with Europe sprinting ahead, the US layering executive orders over legislative inertia, and China doubling down on algorithmic control.

Developers, platform owners, and DevOps teams — pay attention. This isn’t just about ethics; it’s about compliance, operational cost, and, increasingly, legal risk.

---

## Europe: The AI Act is Real – and It’s a Big Deal

###  Status: Passed in February 2025

Europe has passed the [AI Act](https://artificialintelligenceact.eu/), and it’s being called the **“GDPR of AI”** — and for good reason.

This law introduces a **risk-based framework** for AI systems, which includes:

-  **Banned uses**: Predictive policing, emotion recognition in schools and workplaces, biometric categorization linked to sensitive attributes.
-  **High-risk systems**: AI for hiring, education, healthcare, critical infrastructure – subject to audits, logging, transparency, and human oversight.
-  **General-purpose AI models**: Must document training data and capabilities (looking at you, GPT-style models).

###  Enforcement Timeline:
- **6 months post-enactment**: All banned practices must cease.
- **12–24 months**: High-risk systems need to comply (based on complexity).
- **Ongoing**: Foundation model providers must register, disclose training data sources, and supply documentation.

#### Further Reading:
- [The EU AI Act FAQ by Future of Life Institute](https://futureoflife.org/eu-ai-act-faq/)
- [CMS Law: AI Act Summary](https://cms.law/en/int/expert-guides/cms-expert-guide-to-the-eu-ai-act)

---

##  United States: Executive Orders and Evolving Bills

The US approach is **fragmented but active**. The Biden Administration’s **Executive Order on Safe, Secure, and Trustworthy AI (Oct 2023)** has created real downstream impact:

-  [NIST is drafting AI risk management standards](https://www.nist.gov/artificial-intelligence)
-  [DHS-led red teaming of frontier models](https://www.dhs.gov/news/2023/10/30/dhs-statement-president-bidens-executive-order-safe-secure-and-trustworthy-ai)
-  Federal contractors must file **AI impact assessments**
-  Cybercrime risk is front-and-center — think deepfake-based fraud and phishing-as-a-service powered by LLMs.

Legislation is moving slower but has bipartisan support:
-  Labeling AI-generated content
-  Transparency of model provenance
-  Guardrails for AI in critical infrastructure

### Key Agencies to Watch:
- [CISA](https://www.cisa.gov/)
- [DOJ Cybercrime Division](https://www.justice.gov/criminal-ccips)

#### Case Study:
- **LLM-assisted phishing**: See [Proofpoint's report](https://www.proofpoint.com/us/resources/threat-reports/chatgpt-phishing-potential) on how attackers are using ChatGPT-style models to craft better phishing emails, faster.

---

## United Kingdom: Light-Touch, Strategic Positioning

The UK continues to play the **"innovation-first, regulate-later"** card. The 2023 white paper emphasized voluntary standards, and 2025 is focused on **AI safety research**, not strict compliance mandates.

What the UK is doing:

-  Funding the [Frontier AI Taskforce](https://www.gov.uk/government/groups/frontier-ai-taskforce)
-  Partnering with [OpenAI](https://openai.com/), [DeepMind](https://deepmind.google/), and [Anthropic](https://www.anthropic.com/) to red-team high-risk systems
-  Watching the EU but not formally aligning (yet)

Still, keep an eye on the UK’s [AI Safety Summit outcomes](https://www.gov.uk/government/topical-events/ai-safety-summit-2023) — they could evolve into de facto global norms.

---

##  China: Algorithm Registration and Tight Control

China’s approach is **centralized and aggressive**. The Cyberspace Administration of China (CAC) mandates:

-  **Model registration and disclosure of training data**
- ️**Legal penalties for AI use deemed “socially destabilizing”
-  **Mandatory watermarking** for AI-generated text and video

#### Further Reading:
- [Stanford DigiChina’s Translation of China’s AI Rules](https://digichina.stanford.edu/work/translation-generative-ai-management-rules-2023/)
- [Brookings: How China Regulates AI](https://www.brookings.edu/articles/how-china-regulates-ai/)

---

##  What’s Coming Next?

Here’s what the next wave of legislation looks like:

### 1.  AI Watermarking Standards
Backed by Adobe, Google, OpenAI – the [Content Authenticity Initiative](https://contentauthenticity.org/) is gaining momentum. Expect industry-wide watermarking norms for both image and text.

### 2.  Cybercrime-Specific AI Laws
Criminal liability for using LLMs in fraud, harassment, or disinformation. Think **LLMs as co-conspirators** in phishing kits and extortion scams.

### 3.  Model Licensing & Registration
Just like pharma — AI in finance, healthcare, and law will require **licensed deployment**, documentation, and audit trails.

### 4.  Supply Chain AI Audits
Enterprises will be expected to:
- Verify training data origin
- Document use of OSS models
- Monitor **model drift** and fine-tuning risks

If you're shipping AI in your product, **expect audits.**

### 5.  International AI Governance
[G7](https://www.consilium.europa.eu/en/meetings/international-summit/2023/05/20-21/) and [UN](https://news.un.org/en/story/2023/10/1142467) working groups are forming to align policy — early signs of a **global AI Geneva Convention**.

---

##  What Developers & DevOps Teams Should Do Now

-  Start mapping your AI usage against the [OECD AI Risk Classification](https://oecd.ai/en/wonk/classification)
-  Build internal model registries and documentation now
-  Watch for OSS library liability shifts — especially in generative AI tooling
-  Join policy shaping orgs like [OpenSSF](https://openssf.org/) and [Partnership on AI](https://partnershiponai.org/)

---

##  Final Thoughts

If GDPR changed how we handle personal data, the AI Act and its international cousins are about to do the same for machine learning. The time to embed **compliance-aware AI design** is *before* enforcement hits.

Think of it not as regulation — but **a spec for responsible systems.**
