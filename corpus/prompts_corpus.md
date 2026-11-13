# Prompts utilisés pour le corpus MaintiDoc

Chaque prompt est numéroté ; la colonne `outil_ia` de `inventaire.csv` renvoie ici.

## P01 - Génération du livrable 1 et du corpus synthétique

- **Outil** : Claude (Anthropic), interface claude.ai
- **Date** : 2026-11-13
- **Entrées fournies à l'outil** : consignes du livrable 1 (PDF) et cahier des charges du projet (PDF)
- **Prompt (texte exact de la demande)** : « je veut laivrable 1 », puis : « pour le projet on a trinome : saad amargui , anas icame , rayan sabri »
- **Choix faits par l'outil sans autre consigne** : familles = pompes centrifuges et compresseurs à vis (exemple cité dans les consignes) ; voie 2 uniquement (documents synthétiques) ; 4 équipements POMPE-A-01, POMPE-B-01, COMP-A-01, COMP-B-02 ; 3 groupes d'accès fictifs.
- **Résultat** : 36 documents (32 PDF dont 3 scannés simulés, et 4 photos synthétiques ; voir inventaire.csv), rapport, schémas, README.
- **Sous-étapes réalisées dans la même conversation** (aucun autre prompt saisi) :
  1. définition d'un référentiel commun (identifiants, codes d'alarme, seuils, numéros de page) ;
  2. rédaction du contenu de chaque document à partir de ce référentiel ;
  3. rendu des PDF, simulation de scans (rotation, bruit, flou) pour 3 documents ;
  4. rendu de photos de panneaux de commande synthétiques (image de synthèse, pas de photographie réelle) ;
  5. contrôles automatiques de cohérence (codes d'alarme des historiques, identifiants d'équipement, valeurs mesurées vs seuils).

## Prompts à ajouter par l'équipe

Toute itération ultérieure (correction d'un document, ajout d'un document public vérifié, nouvelle version) doit être ajoutée ici sous la forme P02, P03, etc., avec outil, date, prompt exact et document concerné.

## Vérifications humaines

Aucun document n'a encore été relu par un membre de l'équipe : la colonne `verifie_par` contient `A_COMPLETER` pour chacun des 36 documents. Aucun document public n'a été importé, donc pas de lien ni de licence externe à vérifier à ce stade.
