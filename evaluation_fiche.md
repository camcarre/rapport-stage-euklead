<!--
Fiche d'évaluation du contenu du site
Résumé: Check-list des exigences et état (Présent/Manquant) avec notes/actions.
-->

### Fiche d'évaluation du contenu

- **Dépôt**: [camcarre/website.io](https://github.com/camcarre/website.io)
- **Sources analysées**: `rapport-stage-euklead.html`, `contenu-rapport-stage-euklead.txt`, `README.md`

#### Exigences et statut

| Exigence | Statut | Où | Notes / Actions |
|---|---|---|---|
| Page "A propos" avec CV, parcours et profil LinkedIn | Manquant | N/A | Créer une page dédiée `about.html` avec sections: Présentation, Parcours (timeline), CV (PDF + résumé), boutons vers LinkedIn et GitHub. Ajouter lien dans navigation. |
| Page "Contact" | Manquant | N/A (seulement infos dans footer et TXT) | Créer `contact.html` avec formulaire (Nom, Email, Message), liens mailto/tel, mentions de confidentialité. Ajouter lien dans navigation. |
| Présentation de l'entreprise | Présent | `rapport-stage-euklead.html` (Introduction) | Améliorer en séparant une sous-section « À propos d’EUKLEAD » avec mission/activités. |
| Articles sur l'expérience (≥ 5) | Incomplet | `rapport-stage-euklead.html` (3 missions) | Besoin d'au moins 5 articles/pages. Créer 2+ articles supplémentaires et idéalement un index `articles/` avec pages individuelles. |
| Bilan de stage obligatoire | Présent | `rapport-stage-euklead.html` (Conclusion, Apports) et TXT | Consolider en page ou section clairement intitulée « Bilan de stage ». |

#### Détails des manques et propositions rapides

- **A propos**: page dédiée + CV (PDF) + parcours; intégrer bouton LinkedIn (lien existant dans le footer).
- **Contact**: page avec formulaire simple (HTML + action mailto ou service ultérieur), coordonnées complètes.
- **Articles (5 minimum)**: transformer chaque mission en article et ajouter au moins 2 nouveaux articles (ex: Observatoire Power BI – détails DAX; Outil VBA – algorithmes et UX; Méthodo – gestion de projet; Résultats/Impacts). 
- **Navigation**: ajouter un menu minimal (Accueil, A propos, Articles, Contact) en haut de chaque page.

#### Plan d'implémentation suggéré (ordre)
1) Créer `about.html` et `contact.html`.
2) Créer dossier `articles/` avec ≥5 fichiers `YYYY-MM-titre.html` + index `articles/index.html`.
3) Extraire/dupliquer le « Bilan de stage » en section claire ou page `bilan.html` (optionnel).
4) Ajouter un header/nav commun et liens entre pages.

#### Fichiers actuels pertinents
- `rapport-stage-euklead.html`: contenu principal (intro, missions, compétences, résultats, conclusion, footer avec GitHub/LinkedIn).
- `contenu-rapport-stage-euklead.txt`: version texte structurée (inclut CONTACT, Apports, etc.).
- `README.md`: consignes générales.


