graph TD
    A[Submit Application] --> B{Resume Screening}
    B -->|Pass| C[Phone Interview]
    B -->|Fail| D[Rejection]
    C --> E[Technical Interview]
    E --> F[Final Interview]
    F --> G[Offer Extended]
    G --> H[Offer Accepted]
    H --> I[Onboarding]
    D --> J[End]
    I --> J[End]
