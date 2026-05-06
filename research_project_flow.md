# Research Project Preparation — Process Flow

**Module:** NB6015CEM · Research Project Preparation (Level 6)

This diagram maps the end-to-end process students follow from initial topic selection through to formal proposal submission and defense. Each phase builds on the one before it — revisit earlier stages whenever your question evolves.

---

```mermaid
flowchart TD

    subgraph Seeding
        A1["📌 Project seed\nTopic area, problem space"]
        A2["🔍 Research gap\nWhat is unsolved or missing?"]
        A3["🧠 Mental model\nBackground scan, domain map"]
    end

    subgraph ResearchDesign["Research design"]
        B1["❓ Research question\nSpecific, achievable, scoped"]
    end

    subgraph Supervision
        C1["👤 Supervisor selection\nMatch expertise and interest"]
        C2["🤝 Initial discussions\nScope, timeline, agreement"]
        C3["📓 Supervision log\nRecord sessions, decisions"]
    end

    subgraph LitMethods["Literature & methods"]
        D1["📚 Literature review\nState of art, critical eval"]
        D2["⚙️ Methodology\nConceptual and operational"]
    end

    subgraph Ethics
        E1["⚖️ Ethics & approval\nApply, review, sign-off"]
    end

    subgraph Proposal
        F1["✍️ Proposal drafting\nStructure, write, refine"]
        F2["🎓 Submission & defense\nFormal assessed event"]
    end

    A1 --> A2 --> A3 --> B1 --> C1 --> C2 --> C3 --> D1 --> D2 --> E1 --> F1 --> F2

    classDef seeding      fill:#FAEEDA,stroke:#BA7517,color:#633806
    classDef research     fill:#EEEDFE,stroke:#534AB7,color:#3C3489
    classDef supervision  fill:#E1F5EE,stroke:#0F6E56,color:#085041
    classDef ethics       fill:#FAECE7,stroke:#993C1D,color:#712B13
    classDef proposal     fill:#E6F1FB,stroke:#185FA5,color:#0C447C

    class A1,A2,A3 seeding
    class B1,D1,D2 research
    class C1,C2,C3 supervision
    class E1 ethics
    class F1,F2 proposal
```

---

## Phase notes

| Phase | What you are doing | Key output |
|---|---|---|
| **Seeding** | Exploring the domain, identifying a genuine problem, forming a rough mental map | A candidate topic with a clear "so what" |
| **Research design** | Sharpening the problem into a single, testable, properly scoped question | A one-sentence research question |
| **Supervision** | Finding the right supervisor, agreeing working arrangements, keeping a formal log | Signed-off supervision agreement, ongoing log |
| **Literature & methods** | Deep literature review co-developed alongside methodology choices | Literature review draft, methodology outline |
| **Ethics** | Completing the institutional ethics approval process before drafting begins | Signed ethics approval form |
| **Proposal** | Writing, refining, and formally submitting the proposal, followed by defense | Submitted CW1, formal assessed defense |

> **Note on iteration:** the research question (Research design phase) frequently evolves during supervision and literature review. It is expected and normal to revisit earlier phases — document any pivots in your supervision log.
