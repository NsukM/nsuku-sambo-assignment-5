graph TD
    A[Fitness Enthusiast] -->|Uses| B(Track Real-Time Activity)
    A -->|Uses| C(Manage Profile)
    A -->|Uses| D(Receive Personalized Recommendations)
    A -->|Uses| E(Share Achievements)
    A -->|Uses| F(Monitor Vital Statistics)
    G[Healthcare Provider] -->|Uses| H(View Patient Progress)
    I[System Administrator] -->|Manages| J(System Configuration)
    K[Wearable Device Partner] -->|Integrates| L(Sync Device Data)
    M[Data Analyst] -->|Analyzes| N(Generate Fitness Analytics)
    O[Mobile App Developer] -->|Develops| P(Maintain Mobile App)

    B -->|Depends on| L
    F -->|Depends on| L
    D -->|Depends on| N

    style A fill:#f9f,stroke:#333,stroke-width:2px
    style G fill:#bbf,stroke:#333,stroke-width:2px
    style I fill:#f96,stroke:#333,stroke-width:2px
    style K fill:#6f9,stroke:#333,stroke-width:2px
    style M fill:#9cf,stroke:#333,stroke-width:2px
    style O fill:#fc6,stroke:#333,stroke-width:2px
