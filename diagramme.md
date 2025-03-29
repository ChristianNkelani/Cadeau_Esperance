# Diagramme des Phases de Recherche

```mermaid
graph TB
    A[Phase 1: Conception] --> B[Phase 2: Échantillonnage]
    B --> C[Phase 3: Préenquête]
    C --> D[Phase 4: Validation Statistique]
    D --> E[Phase 5: Déploiement du VirtLab]
    E --> F[Phase 6: Plan Expérimental]
    F --> G[Phase 7: Analyse et Triangulation]
    G --> H[Phase 8: Limites et Généralisation]

    %% Phase 1: Conception
    A --> A1[Focus Group Pluridisciplinaire]
    A1 --> A1a[Physiciens: Items en mécanique]
    A1 --> A1b[Inspecteur: Validation conceptuelle]
    A1 --> A1c[Psychopédagogue: Tests statistiques]
    A1 --> A1d[Linguiste: Clarté des items]

    %% Phase 2: Échantillonnage
    B --> B1[Population: 480 sujets]
    B1 --> B2[Échantillon: 214 (Table de Morgan)]
    B2 --> B3[Inkisi: 86 apprenants]
    B2 --> B4[Kimpese: 106 apprenants]

    %% Phase 3: Préenquête
    C --> C1[Entretiens structurés]
    C1 --> C2[Test pilote]
    C2 --> C3[Checklist thématique]

    %% Phase 4: Validation Statistique
    D --> D1[Test W de Kendall]
    D --> D2[Alpha de Cronbach ≥ 0.7]
    D --> D3[Analyse factorielle (SPSS)]
    D --> D4[Validation externe]

    %% Phase 5: VirtLab
    E --> E1[Validation multicritères]
    E1 --> E1a[AHP/TOPSIS/CAHP/ELECTRE I]
    E1 --> E1b[Critères: Conformité, Convivialité, Coût]
    E --> E2[Formation enseignants]
    E --> E3[Groupes contrôle: Labo réel]

    %% Phase 6: Plan Expérimental
    F --> F1[Plan de Solomon]
    F1 --> F2[4 groupes (2 exp./2 contrôle)]
    F2 --> F3[Attribution aléatoire]
    F3 --> F4[Formation équilibrée]

    %% Phase 7: Analyse
    G --> G1[Triangulation]
    G1 --> G2[Checklists + Rapports + Feedbacks]
    G --> G3[Éthique: Consentement signé]

    %% Phase 8: Limites
    H --> H1[Taille des groupes]
    H --> H2[Biais de sélection]
    H --> H3[Réplication nationale]