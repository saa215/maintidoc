# MaintiDoc - Livrable 1 : cadrage, corpus et architecture

Module IA générative multimodale - EMSI 2026.

## Équipe (AMARGUI-ICAME-SABRI)
- Saad AMARGUI
- Anas ICAME
- Rayan SABRI

## Objectif du projet
MaintiDoc est un assistant documentaire multimodal et agentique pour la maintenance : il répond à une question (texte et photo) avec des références vérifiables (page, figure), consulte l'historique d'un équipement via un outil MCP et prépare un ticket dont la création exige une approbation humaine. Il ne pilote aucune machine et ne garantit aucun diagnostic. Toutes les données sont fictives ou synthétiques.

## Contenu du ZIP
- `L1_MaintiDoc_AMARGUI-ICAME-SABRI_Rapport.pdf` : rapport (cadrage, corpus, architecture, flux, risques, planning)
- `L1_MaintiDoc_AMARGUI-ICAME-SABRI_LienGitHub.txt` : URL du dépôt GitHub
- `README.md` : cette page
- `L1_MaintiDoc_AMARGUI-ICAME-SABRI_Corpus/` : `inventaire.csv` (36 documents), `prompts_corpus.md`, `documents/famille_1` (pompes), `documents/famille_2` (compresseurs), `images/` (photos de panneaux synthétiques)

## Structure du dépôt
```
maintidoc/
├── README.md
├── .gitignore
├── docs/diagrammes/      (architecture.mmd, architecture.png, ticket_flow.png)
└── corpus/
    ├── inventaire.csv
    ├── prompts_corpus.md
    ├── documents/famille_1, famille_2
    └── images/
```

## Avertissement
Les valeurs techniques des documents (seuils, couples, volumes) sont inventées. Ne les utiliser sur aucun équipement réel.
