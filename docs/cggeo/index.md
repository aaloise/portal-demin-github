# 🗺️ Geoinformação (CGGEO)

Diretrizes para produção cartográfica e homologação de plantas na SPU.

## 📐 Fluxo de Homologação

O processo de validação de georreferenciamento segue o fluxo rigoroso abaixo:

```mermaid
graph LR
    A[👷 Engenheiro Externo] -->|Submete DWG/SHP| B(Protocolo SPU)
    B --> C{Análise CGGEO}
    C -->|✅ Aprovado| D[Certificação]
    C -->|❌ Reprovado| E[Devolução com Nota]
    E -->|Correção| A
    D --> F[Base Cartográfica Oficial]
    
    style D fill:#d4edda,stroke:#28a745,stroke-width:2px
    style E fill:#f8d7da,stroke:#dc3545,stroke-width:2px
