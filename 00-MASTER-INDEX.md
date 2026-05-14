# AB-731 - Microsoft Certified: AI Transformation Leader - Visual Study Guide

> Concept-only study aid. No exam questions reproduced. Source PDF (if any) stays local + gitignored.

**Skills outline:** https://learn.microsoft.com/credentials/certifications/ai-transformation-leader/

## Audience

AB-731 is for **leaders and decision-makers** - not developers, not end users - who need to:
- Identify business problems where generative AI delivers measurable value.
- Understand Microsoft's AI portfolio at a strategic level (what each product does and who uses it).
- Lead enterprise AI adoption: change management, governance, ROI, responsible AI.

This is the strategic complement to AB-730 (which is for the daily user).

## The 4 Exam Domains - Mind Map

```mermaid
mindmap
  root((AB-731))
    AI Strategy and Vision
      Business Value Drivers
        Productivity gains
        Cost reduction
        Revenue growth
        Customer experience
      AI Maturity Model
        Experimentation
        Pilot
        Scaled deployment
        Transformative
      Use Case Prioritization
        Impact vs effort matrix
        Risk assessment
        ROI projection
        Strategic alignment
      Build vs Buy
        Microsoft 365 Copilot
        Custom Copilot Studio
        Foundry custom build
        Vendor solutions
    Microsoft AI Platform Overview
      Microsoft 365 Copilot
        Productivity Copilot
        Business Chat
        Copilot Pages
        Sensitivity labels respect
      Copilot Studio
        Low-code builder
        Topic and plugin authoring
        Channels Teams Web M365
      Azure AI Foundry
        Foundation models
        Custom RAG patterns
        Multi-agent solutions
        Enterprise integration
      GitHub Copilot
        Developer productivity
        Engineering velocity
        Code quality and reviews
    Change Management and Adoption
      Stakeholder Alignment
        Executive sponsorship
        Cross-functional steering
        Champions network
        Communications plan
      User Enablement
        Role-based training
        Persona use case maps
        Center of Excellence
        Office hours support
      Organizational Readiness
        Skills assessment
        Job redesign
        Career impact
        Workforce planning
      Measuring Impact
        Adoption metrics MAU DAU
        Productivity savings
        Quality improvements
        Sentiment tracking
    Responsible AI and Governance
      Microsoft Responsible AI Principles
        Fairness
        Reliability and Safety
        Privacy and Security
        Inclusiveness
        Transparency
        Accountability
      Governance Operating Model
        AI Council
        Use case intake
        Risk review board
        Approval workflow
      Data Protection
        Tenant data isolation
        Commercial Data Protection
        DLP and sensitivity labels
        Customer-managed keys
      Compliance and Regulation
        EU AI Act
        GDPR HIPAA SOC
        Audit and Purview
        Vendor due diligence
      Risk Management
        Bias and fairness audits
        Hallucination mitigation
        Security threat modeling
        Incident response plan
```

## Domain map

```mermaid
flowchart LR
    Master["AB-731 Master Index"]
    D01["Business Value of Generative AI"]
    Master --> D01
    D02["Microsoft AI Apps and Services"]
    Master --> D02
    D03["Implementation and Adoption Strategy"]
    Master --> D03
    D01 --> S1[Identify use cases]
    D01 --> S2[Define ROI / KPIs]
    D02 --> S3[Microsoft Copilot family]
    D02 --> S4[Azure AI Foundry, OpenAI]
    D02 --> S5[Copilot Studio + agents]
    D03 --> S6[Change management]
    D03 --> S7[Responsible AI governance]
    D03 --> S8[Pilot and scale]
```

## Domain weights

```mermaid
pie showData
    title AB-731 domain weights
    "Business Value of Generative AI" : 33
    "Microsoft AI Apps and Services" : 33
    "Implementation and Adoption Strategy" : 34
```

## Recommended study order

```mermaid
gantt
    title Suggested study plan
    dateFormat X
    axisFormat Day %d
    section Plan
    Business Value :t1, 0, 1d
    Microsoft AI Apps and Services :t2, after t1, 2d
    Implementation and Adoption Strategy :t3, after t2, 2d
```

## Top 12 things to know

1. **Generative AI value** comes in three buckets: productivity, customer experience, new revenue.
2. **ROI** is measured by minutes saved per task, deflection rate (support), revenue per AI feature.
3. **Microsoft Copilot family** has 3 tiers: Microsoft Copilot (free, web), Microsoft 365 Copilot (work), and role-specific Copilots (Sales, Service, Finance).
4. **Copilot Studio** lets makers build custom Copilot agents on top of organizational data.
5. **Azure AI Foundry** is the developer + IT pro platform (Azure OpenAI models, prompt flow, evaluations).
6. **GitHub Copilot** is a separate developer-targeted product.
7. **Responsible AI governance** - Microsoft's six principles plus organizational policies (Responsible AI Standard, Impact Assessments).
8. **Change management** is the #1 success factor in adoption. Champions, training, prompt libraries.
9. **Pilot to scale** pattern: pick high-value, low-risk use cases first; measure; expand.
10. **Data readiness** matters: Microsoft Graph quality, sensitivity labels, oversharing remediation.
11. **Privacy** - M365 Copilot does NOT use your tenant data to train base models.
12. **Cost** - M365 Copilot is per-user; Azure AI is consumption-based.

## Common gotchas

- "AI strategy" without measurable KPIs fails - start with one clear KPI per use case.
- Pilot without champions stalls.
- Oversharing in SharePoint can leak data through Copilot - Purview labels and access reviews matter.
- Free Microsoft Copilot is NOT the same as Microsoft 365 Copilot for governance purposes.
- AI investments without responsible AI governance create regulatory and reputational risk.

## Supporting pages

- [05-exam-cheatsheet.md](05-exam-cheatsheet.md)
- [06-references.md](06-references.md)
- [07-extra-ab731-concepts.md](07-extra-ab731-concepts.md)
- [08-learn-summaries.md](08-learn-summaries.md)
- [09-arch-ab731.md](09-arch-ab731.md)
- [11-microsoft-resources.md](11-microsoft-resources.md)
- [12-glossary.md](12-glossary.md)
- [13-flashcards.md](13-flashcards.md)
- [14-pitfalls.md](14-pitfalls.md)
- [15-hands-on-labs.md](15-hands-on-labs.md)
- [16-architecture-center.md](16-architecture-center.md)
- [17-copilot-quiz.md](17-copilot-quiz.md)
- [99-practice-assessment.md](99-practice-assessment.md)
- [99-video-tutorials.md](99-video-tutorials.md)

---

**Next:** open [01-business-value.md](01-business-value.md)
