graph TD
    A[UniService <br/>(Kết Tình Food JSC)] --> B(Services);
    A --> C(Client Segments);

    B --> B1[Canteen Management <br/>and Industrial Catering];
    B1 --> B1a[Meal Provision <br/>(Breakfast, Lunch, Dinner)];
    B1 --> B1b[Menu Planning and Customization];
    B1 --> B1c[On-site Staffing and Operations];

    B --> B2[Industrial Supplies];
    B2 --> B2a[Office Supplies];
    B2 --> B2b[Kitchen and Pantry Supplies];

    C --> C1[Schools];
    C --> C2[Hospitals];
    C --> C3[Enterprises];

    subgraph Service Delivery
        direction LR
        S1[Meals and Supplies] --> S2{Delivery and Logistics};
        S2 --> S3[Client Sites <br/>(Canteens, Offices)];
    end

    B1 --> Service Delivery;
    B2 --> Service Delivery;

    C1 --> Service Delivery;
    C2 --> Service Delivery;
    C3 --> Service Delivery;

    style A fill:#f9f,stroke:#333,stroke-width:4px
    style B fill:#bbf,stroke:#333,stroke-width:2px
    style C fill:#bbf,stroke:#333,stroke-width:2px
    style B1 fill:#ccf,stroke:#333
    style B2 fill:#ccf,stroke:#333
    style B1a fill:#eef,stroke:#333
    style B1b fill:#eef,stroke:#333
    style B1c fill:#eef,stroke:#333
    style B2a fill:#eef,stroke:#333
    style B2b fill:#eef,stroke:#333
    style C1 fill:#fcf,stroke:#333
    style C2 fill:#fcf,stroke:#333
    style C3 fill:#fcf,stroke:#333
    style S1 fill:#cff,stroke:#333
    style S2 fill:#cff,stroke:#333
    style S3 fill:#cff,stroke:#333
