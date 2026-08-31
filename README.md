# Guide_circulaire_26G2006_RWA
Guide d'étude — Circulaire BAM n° 26/G/2006


# Guide d'étude — Circulaire BAM n° 26/G/2006
### Exigences en fonds propres — risques de crédit, de marché et opérationnels (approche standard)

> **Texte de base : décembre 2006.** Amendé depuis par plusieurs circulaires (voir section finale). Ce guide couvre le texte original article par article — il faut le compléter avec les modificatifs pour une version à jour à 2026.

---

## 1. Structure générale du texte (66 articles)

| Partie | Articles | Contenu |
|---|---|---|
| I. Dispositions générales | 2–8 | Coefficient de solvabilité (8% minimum), numérateur/dénominateur, périmètre |
| II. Risque de crédit | 9–47 | Pondérations par contrepartie, ARC, règlement livraison |
| III. Risques de marché | 48–55 | Taux, actions, change, produits de base, options, dérivés de crédit |
| IV. Risques opérationnels | 56–62 | 3 approches (indicateur de base / standard / standard alternative) |
| V. Autres dispositions | 63–66 | Consolidation, reporting, pouvoir de révision de BAM |

**règlement livraison** : Logique générale --> si le règlement d'une transaction sur titres/devises/produits de base prend du retard, la banque est exposée à un risque de contrepartie supplémentaire (l'autre partie peut faire défaut avant que l'échange soit complet)

**Formule clé (Art. 2, 5, 6) :**
```
Coefficient de solvabilité = Fonds propres / (RWA crédit + RWA marché + RWA opérationnel) ≥ 8%

RWA crédit      = Σ (actif × pondération)
RWA marché      = Exigence FP marché × 12,5
RWA opérationnel = Exigence FP opérationnel × 12,5
```

---

## 2. RISQUE DE CRÉDIT — Tableau des pondérations (Art. 11)

C'est la partie la plus dense. Voici le tableau récapitulatif par catégorie de contrepartie :

| Catégorie | Notation AAA/AA- | A+/A- | BBB+/BBB- | BB+/B- | <B- | Non noté |
|---|---|---|---|---|---|---|
| **A. États & banques centrales** | 0% | 20% | 50% | 100% | 150% | 100% |
| **B. Organismes publics (hors admin. centrale)** | 20% | 50% | 50%* | 100% | 150% | 50% |
| **C. Banques multilatérales dév. (BMD)** | 20%(0% liste BAM) | 50% | 50% | 100% | 150% | 50% |
| **D. Établissements de crédit** | 20% | 50% | 50% | 100% | 150% | 50% |
| **F. Entreprises / PME** (option notation) | 20% | 50% | 100% | 150% | 150% | 100% |

*Cas particuliers à connaître par cœur (pas de notation à chercher — taux fixes) :*
- **G. TPE et particuliers** : **75%** (100% si crédit particulier >1M MAD hors immo résidentiel)
- **H. Prêts immobiliers résidentiels** (hypothèque 1er rang, LTV ≤80%) : **35%**
- **I. Immobilier commercial** : 100% (crédit direct) / 50% (crédit-bail)
- **J. Créances en souffrance** : 50–150% selon taux de provisionnement
- **K. Autres actifs** : 0% (caisse) à 150% (capital-risque)
- **Créances État marocain/BAM en MAD** : **0%** (cas spécial, Art. 11-A-1)

**Hors-bilan (Art. 13–14)** : converti via FCEC (Facteur de Conversion en Équivalent Crédit) avant application de la même grille : 0% / 20% / 50% / 100% selon la catégorie de risque.

**ARC — Atténuation du Risque de Crédit (Art. 26–44)** : deux approches pour les sûretés financières
- **Approche simple** : la fraction couverte reçoit la pondération de la sûreté (min 20% sauf exceptions)
- **Approche globale** : ajustement par surcote/décote (haircut), seule permise pour le portefeuille de négociation

---

## 3. RISQUES DE MARCHÉ (Art. 48–55)

| Sous-risque | Méthode de calcul de l'exigence FP |
|---|---|
| Taux d'intérêt | Risque spécifique (pondération selon notation) + risque général (méthode échéancier ou duration) |
| Position titres de propriété | 8% position brute (ou 4% si portefeuille liquide/diversifié) + 8% position nette |
| Change | 8% × max(positions courtes, positions longues) + position nette sur or |
| Produits de base | Méthode "tableau d'échéances" (1,5%/0,6%/15%) ou "simplifiée" (15%+3%) |
| Options | Méthode delta-plus (risque gamma + risque vega) |
| Dérivés de crédit | Risque spécifique + risque général |

L'exigence totale est ensuite multipliée par **12,5** pour obtenir le RWA marché (Art. 5).

---

## 4. RISQUES OPÉRATIONNELS (Art. 56–62)

| Approche | Formule |
|---|---|
| **Indicateur de base** | 15% × moyenne PNB sur 3 ans |
| **Standard** | Σ (PNB par ligne de métier × coefficient), moyenne sur 3 ans — 8 lignes de métier, coefficients 12–18% |
| **Standard alternative** | Banque de détail/commerciale : encours crédit × 15% × 0,035 ; autres lignes : PNB × 18% |

**8 lignes de métier et coefficients (Art. 60)** :
Financement entreprises 18% · Marché 18% · Détail 12% · Commerciale 15% · Paiement/règlement 18% · Courtage détail 12% · Agence 15% · Gestion d'actifs 12%

---

## 5. Ce qui a changé depuis 2006 (à vérifier dans les textes modificatifs)

Circulaires modificatives identifiées — **à consulter pour la version consolidée** :
- **Circulaire 13/G/2013** (13 août 2013)
- **Circulaire 3/W/2016** (10 juin 2016)
- **Circulaire 8/W/2018** (27 juillet 2018)
- **Circulaire 1/W/2021** (4 mars 2021)

Ces textes modifient probablement les pondérations, les seuils, et intègrent des évolutions Bâle II/III (le texte de 2006 reste basé sur l'approche standard Bâle II — vérifie si des éléments Bâle III ont été intégrés par ces amendements ou relèvent plutôt de la circulaire 8/G/2010 sur les approches internes et 14/G/2013 sur les fonds propres).

---

