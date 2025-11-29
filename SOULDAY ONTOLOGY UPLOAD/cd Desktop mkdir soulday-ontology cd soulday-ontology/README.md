# Soulday.app Public Ontology & Data Model
**v1.0.0 — Noiembrie 2025**  
Prima ontologie deschisă a unei platforme sociale românești bazată 100 % pe personalitate.

https://soulday.app • Exclusiv România • Non-dating • Soul AI

## Ce conține
- `soulday_ontology.jsonld` → ontologie completă  
- `data-model/` → 11 tabele Excel goale  
- `diagrams/` → Mermaid + PNG  
- `CONTRIBUTING.md` + `LICENSE`

## Diagrama
```mermaid
erDiagram
    User ||--o{ PersonalityProfile : has
    User ||--o{ Match : participates
    PersonalityProfile }|--|| PersonalityType : "59 types"
    PersonalityType }|--|{ CompatibilityMatrix : "59×59"

Made with soul in Romania 
