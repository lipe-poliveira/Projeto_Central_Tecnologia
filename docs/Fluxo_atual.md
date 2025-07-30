graph TD
    subgraph Unidade Central
        DC[Data Center<br>HC Campus]
        DB[(Banco de Dados Centralizado)]
    end

    subgraph Unidades
        UE[Unidade de Emergência]
        HERP[HERP]
        MATER[Mater]
        SERRANA[HE Serrana]
        AMERICO[HE Américo]
        BAURU[HC Bauru]
        GALILEU[Unidade Galileu]
    end

    DC --> DB

    UE -->|Acesso via Fibra| DB
    HERP -->|Acesso via Fibra| DB
    MATER -->|Acesso via Fibra| DB
    SERRANA -->|Acesso via Fibra| DB
    AMERICO -->|Acesso via Fibra| DB
    BAURU -->|Acesso via Fibra| DB
    GALILEU -->|Acesso via Fibra| DB
