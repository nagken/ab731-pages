# AB-731 Architectures

> Conceptual architectures relevant to a transformation leader.

## 1. Enterprise AI portfolio map

```mermaid
flowchart TB
    Org[Organization]
    Org --> Roles[Knowledge workers]
    Org --> Spec[Specialists -<br/>sellers, support, finance]
    Org --> Makers[Makers / power users]
    Org --> Devs[Developers]
    Roles --> M365[Microsoft 365 Copilot]
    Spec --> RoleCop[Copilot for Sales /<br/>Service / Finance]
    Makers --> Studio[Copilot Studio]
    Devs --> Foundry[Azure AI Foundry]
    Devs --> GHC[GitHub Copilot]
```

## 2. Microsoft 365 Copilot data flow

```mermaid
flowchart LR
    User[User in Office app]
    User --> M365[Microsoft 365 Copilot]
    M365 --> Graph[Microsoft Graph -<br/>tenant data]
    Graph --> M365
    M365 --> Found[Foundation model -<br/>tenant region]
    Found --> M365
    M365 --> User
    Purview[Microsoft Purview labels + DLP]
    Purview --> M365
    Audit[Audit log]
    M365 --> Audit
```

## 3. Custom AI agent (Copilot Studio)

```mermaid
flowchart LR
    User[Employee or customer]
    User --> Agent[Copilot Studio agent]
    Agent --> Topics[Conversational topics]
    Agent --> KB[Knowledge -<br/>SharePoint, web, custom docs]
    Agent --> Conn[1500+ connectors]
    Conn --> ERP[ERP / CRM / SaaS]
    Agent --> Pub[Publish channels:<br/>M365 Copilot, Teams, web]
```

## 4. Custom AI app (Azure AI Foundry)

```mermaid
flowchart LR
    Dev[Developer]
    Dev --> Foundry[Azure AI Foundry]
    Foundry --> Catalog[Model catalog -<br/>1700+ models]
    Foundry --> Flow[Prompt flow]
    Foundry --> Eval[Eval + safety]
    Foundry --> Deploy[Deploy endpoint]
    App[Custom app] --> Deploy
    App --> Search[Azure AI Search -<br/>RAG]
    Search --> Data[Custom data]
```

## 5. Adoption journey

```mermaid
flowchart LR
    V[Vision] --> R[Readiness]
    R --> P[Pilot]
    P --> S[Scale]
    S --> O[Optimize]
```

## 6. Responsible AI program

```mermaid
flowchart TB
    RAI[Responsible AI program]
    RAI --> Policy[Policy:<br/>RAI Standard v2]
    RAI --> Process[Process:<br/>Impact Assessments]
    RAI --> People[People:<br/>AI Council]
    RAI --> Tech[Technology:<br/>Content Safety,<br/>audit, monitoring]
```

---

[Master Index](00-MASTER-INDEX.md)
