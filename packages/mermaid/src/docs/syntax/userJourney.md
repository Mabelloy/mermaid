graph TD
    subgraph Donors
        A[Signup/Login] --> B{Donor or LCO?}
        B --> |Donor| C[Donor Dashboard]
        B --> |LCO| D[LCO Dashboard]
    end

    subgraph Donor_Dashboard
        C --> E[Inventory Management Tools]
        C --> F[Donation Scheduling]
        C --> G[Real-Time Notifications]
        C --> H[Legal and Regulatory Report]
        C --> I[Feedback and Reporting Mechanism]
        C --> J[Impact or Donation Dashboard]
    end

    subgraph LCO_Dashboard
        D --> K[Request Donation]
        D --> L[Donation Inventory]
        D --> M[Donation Management Tools]
        D --> N[Search and Match]
        D --> O[Pickup Scheduling and Coordination]
        D --> P[Impact Tracking]
        D --> Q[Community Engagement Forum]
    end

    subgraph Inventory_Management_Tools
        E --> E1[Food Categories]
        E --> E2[Add Item/Quantity for Donation]
        E --> E3[Track surplus inventory]
        E --> E4[Track expiration dates]
    end

    subgraph Donation_Scheduling
        F --> F1[Manually choose LCO preference]
        F --> F2[Random donation]
    end

    subgraph Real-Time_Notifications
        G --> G1[Availability of surplus]
        G --> G2[Expiration date notice]
    end

    subgraph Legal_and_Regulatory_Report
        H --> H1[Food safety guidelines]
        H --> H2[Law reports]
        H --> H3[Food donor liability and indemnity laws]
        H --> H4[Tax Incentives]
    end

    subgraph Feedback_and_Reporting_Mechanism
        I --> I1[Donation impact publications]
        I --> I2[Food donor ratings]
        I --> I3[Newsletter]
        I --> I4[Educational materials on food safety]
        I --> I5[Consumer feedback]
    end

    subgraph Impact_or_Donation_Dashboard
        J --> J1[List of past donations]
    end

    subgraph Request_Donation
        K --> K1[Create wishlist]
        K --> K2[Submit donation request]
    end

    subgraph Donation_Inventory
        L --> L1[Inventory by food categories]
    end

    subgraph Donation_Management_Tools
        M --> M1[Donor names]
        M --> M2[Total donations received]
        M --> M3[List of out of stock items]
        M --> M4[Track expiration dates]
    end

    subgraph Search_and_Match
        N --> N1[Search available donations]
        N --> N2[Select and add to cart]
    end

    subgraph Pickup_Scheduling_and_Coordination
        O --> O1[Schedule pickup]
    end

    subgraph Impact_Tracking
        P --> P1[No. of Outreaches]
        P --> P2[No. of Items/Food donated]
        P --> P3[Total Waste Diverted]
    end

    subgraph Community_Engagement_Forum
        Q --> Q1[Testimonials]
        Q --> Q2[Outreach memoirs]
        Q --> Q3[Gallery]
        Q --> Q4[Events]
    end
