# Organigramm FreshGuard – Atzler, Abel & Dörnbrak GbR

## Organisationsstruktur

```plantuml
@startuml
skinparam backgroundColor #FEFEFE
skinparam shadowing false
skinparam defaultFontName Arial
skinparam defaultFontSize 12

skinparam rectangle {
    BackgroundColor #E3F2FD
    BorderColor #1976D2
    RoundCorner 15
}

skinparam rectangle<<gf>> {
    BackgroundColor #BBDEFB
    BorderColor #1565C0
}

skinparam rectangle<<dev>> {
    BackgroundColor #C8E6C9
    BorderColor #388E3C
}

skinparam rectangle<<pm>> {
    BackgroundColor #FFF9C4
    BorderColor #FBC02D
}

title FreshGuard – Atzler, Abel & Dörnbrak GbR\nOrganisationsstruktur

rectangle "**Geschäftsführung**" as gf <<gf>> {
    rectangle "**Phillipp Atzler**\n---\nGeschäftsführer & Lead Developer\n---\nAlter: [XX] Jahre\nAnteil: 40%\nAusbildung: Fachinformatiker AE\n---\n• Backend-Entwicklung\n• Datenbank & DevOps\n• Tests & Qualitätssicherung" as pa
}

rectangle "**Entwicklung**" as dev <<dev>> {
    rectangle "**Maike Abel**\n---\nFrontend Lead\n---\nAlter: [XX] Jahre\nAnteil: 30%\nAusbildung: Fachinformatikerin AE\n---\n• UI/UX-Design\n• Frontend-Entwicklung\n• Dokumentation" as ma
}

rectangle "**Organisation**" as org <<pm>> {
    rectangle "**Elisa Dörnbrak**\n---\nProjektmanagement & QA\n---\nAlter: [XX] Jahre\nAnteil: 30%\nAusbildung: Fachinformatikerin AE\n---\n• Projektmanagement\n• Kundenbetreuung\n• Koordination & Mediation" as ed
}

gf -down-> dev
gf -down-> org

@enduml
```

## Alternative Darstellung (Mermaid)

Falls PlantUML nicht verfügbar ist, hier die Alternative mit Mermaid:

```mermaid
flowchart TB
    subgraph GF["🏢 Geschäftsführung"]
        PA["<b>Phillipp Atzler</b><br/>Geschäftsführer & Lead Developer<br/>━━━━━━━━━━━━<br/>Alter: [XX] Jahre<br/>Anteil: 40%<br/>Fachinformatiker AE<br/>━━━━━━━━━━━━<br/>• Backend & Datenbank<br/>• DevOps & Tests"]
    end
    
    subgraph DEV["💻 Entwicklung"]
        MA["<b>Maike Abel</b><br/>Frontend Lead<br/>━━━━━━━━━━━━<br/>Alter: [XX] Jahre<br/>Anteil: 30%<br/>Fachinformatikerin AE<br/>━━━━━━━━━━━━<br/>• UI/UX-Design<br/>• Frontend & Doku"]
    end
    
    subgraph ORG["📋 Organisation"]
        ED["<b>Elisa Dörnbrak</b><br/>Projektmanagement & QA<br/>━━━━━━━━━━━━<br/>Alter: [XX] Jahre<br/>Anteil: 30%<br/>Fachinformatikerin AE<br/>━━━━━━━━━━━━<br/>• PM & Koordination<br/>• Kundenbetreuung"]
    end
    
    GF --> DEV
    GF --> ORG
```

## Tabellarische Übersicht

| Position | Name | Alter | Anteil | Ausbildung | Verantwortlichkeiten |
|----------|------|-------|--------|------------|---------------------|
| **Geschäftsführer & Lead Developer** | Phillipp Atzler | [XX] Jahre | 40% | Fachinformatiker AE | Backend, Datenbank, DevOps, Tests |
| **Frontend Lead** | Maike Abel | [XX] Jahre | 30% | Fachinformatikerin AE | UI/UX-Design, Frontend, Dokumentation |
| **Projektmanagement & QA** | Elisa Dörnbrak | [XX] Jahre | 30% | Fachinformatikerin AE | PM, Kundenbetreuung, Koordination, Mediation |

---

## Hinweise

⚠️ **Bitte ersetzen Sie `[XX]` durch das tatsächliche Alter der Gründer.**

### Vertretungsregelung
Bei Abwesenheit eines Gründers übernehmen die anderen beiden dessen Aufgaben. Kritische Zugangsdaten sind bei allen Gesellschaftern hinterlegt.

### Entscheidungsstruktur
- **Geschäftsführung:** Phillipp Atzler (alleinvertretungsberechtigt)
- **Wichtige Entscheidungen:** Zweidrittel-Mehrheit erforderlich
- **Mediation bei Konflikten:** Elisa Dörnbrak
