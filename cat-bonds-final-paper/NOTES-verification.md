# Notes de vérification

Ces notes accompagnent `paper.docx` / `paper.pdf`. Depuis la dernière révision, chaque affirmation sur les trois articles principaux a été vérifiée dans leur texte complet.

## Ce que la lecture des textes complets a changé

| Point | Avant (d'après les résumés) | Après (texte complet) |
|---|---|---|
| Haffar et Le Fur : série CAT | supposée être un indice Swiss Re | un fonds, GAMSTAR Institutional USD Acc (GAM) ; 100 rendements mensuels, novembre 2011 à février 2020 |
| Haffar et Le Fur : « co-mouvements extrêmes » | attribués à la copule | viennent des bêtas de co-kurtosis (0,015 contre 0,80 à 1,35 pour les indices boursiers) |
| Haffar et Le Fur : limites | non connues | paramètre *a* de la copule nul ; probabilité de performance égale de 98 % ; poids nul du fonds dans le portefeuille le plus diversifié ; échantillon sans 2008 ni mars 2020 |
| Drobetz et al. : sous-périodes | trois | deux : 2002-2008 (inclut l'automne 2008) et 2009-2018 |
| Drobetz et al. : « strong safe haven » | définition à vérifier | coefficient d'indicatrice significativement négatif (éq. 5, p. 5) ; un seul coefficient sur trois (−0,091*, −0,101** après désaplanissement) ; corrélation implicite ≈ 0,01 |
| Drobetz et al. : lissage | supposé biaiser les résultats | résultats « virtually unchanged » après désaplanissement ; autocorrélation d'ordre 1 négative (−0,34) |
| Carayannopoulos et Perez : données | inconnues | indice Swiss Re BB (prix), 614 rendements hebdomadaires, janvier 2002 à octobre 2013 ; crise NBER décembre 2007 à mai 2009 |
| Carayannopoulos et Perez : ouragan Ike | « à séparer » | les auteurs en discutent (p. 14-16) et le traitent comme un catalyseur, sans séparation formelle |
| Collatéral après 2009 | source de presse | liste des actifs permis tirée de Carayannopoulos et Perez (p. 23) |

## Chiffres repris des articles (avec page)

- **Carayannopoulos et Perez (2015)**
  - Corrélations avec le S&P 500 avant, pendant et après la crise : 0,016 / 0,252 / 0,058 ; avec les obligations de sociétés : 0,003 / 0,475 / 0,092 (tableau 2, p. 9).
  - Corrélation MGARCH proche de zéro jusqu’à fin août 2008, 0,24 en mai 2009, retour au niveau d’avant-crise début 2011 (p. 13-14).
  - Bêta maximal de 0,014 en janvier 2010, contre 0,13 pour les obligations de sociétés (p. 24).
  - Écart-type hebdomadaire de 0,37 % puis 0,41 % pour les CAT bonds ; de 1,91 % à 4,49 % pour le S&P 500 (tableau 1, p. 7).
  - Citation « are not zero-beta assets » (p. 21) ; citation sur les pertes « not from natural catastrophic events » (p. 22-23).
- **Drobetz et al. (2020)**
  - Les CAT bonds arrivent généralement à échéance en trois à quatre ans ; encours de 2,2 G$ en 2002 et de 23 G$ en juin 2017 (p. 2).
  - 885 rendements hebdomadaires (tableau 1, p. 4).
  - *m*₀ avec les actions : 0,1118 / 0,2418 / 0,1019 ; *m*₂ avant 2009 : 0,0724* (tableaux 2 et 3, p. 6).
  - Citations (p. 5).
- **Haffar et Le Fur (2022)**
  - Données (p. 298).
  - Ratio de Sharpe modifié : 0,112 contre 0,027 à 0,089 (tableau 3, p. 303).
  - Contribution à la VaR : −0,54 % ; poids optimal nul (tableau 5, p. 304).
  - Bêtas co-moments (tableau 6, p. 305).
  - Paramètre *a* = 0 (tableau 2 et texte, p. 301-302) ; probabilité de performance égale de 98 % (p. 303).

## Calcul des 40 à 80 points de base (section 3.3)

L'équation (1) donne : variation de prix ≈ −durée × variation de prime. Pour une durée de 2 ans, 0,81 % / 2 ≈ 40 pb ; pour une durée d'un an, 0,81 % / 1 ≈ 80 pb. Une durée d'un à deux ans découle d'une échéance habituelle de trois à quatre ans (Drobetz et al., p. 2). Tu dois pouvoir l'expliquer à l'oral.

## Faits non cités (connaissances générales)

Il n'en reste plus. Bear Stearns (mars 2008) et l'épisode LDI/Ian (septembre 2022) ont été retirés du texte.

## Révisions du 10 novembre 2026 (à partir de `paper_corrige.docx`)

La base est la version corrigée dans Word (révision 6, 30 octobre). Elle faisait 17 pages ; celle-ci en fait 14 (PDF LibreOffice, polices métriquement identiques à Times New Roman).

### Répartition des pages

| Partie | Pages |
|---|---|
| Page titre | 1 |
| 1. Introduction | 1,3 |
| 2. Revue de littérature (2.1 à 2.7, avec le tableau 1) | 5,2 |
| 3. Analyse (3.1 à 3.6, avec le tableau 2) | 5,2 |
| 4. Conclusion | 0,5 |
| Bibliographie (16 références) | 0,8 |

### Ce qui a changé

- **Revue de littérature portée à 5,1 pages.** La description complète des résultats de chaque article (régimes de Markov de Carayannopoulos et Perez, mécanismes cités par Drobetz et al., limites rapportées par Haffar et Le Fur eux-mêmes) est revenue en section 2. Une nouvelle section 2.7 dit ce que la littérature établit et ce qu'elle laisse ouvert, ce qui justifie l'analyse.
- **Analyse.** La 3.1 évalue chaque article ; la 3.2 présente la contribution (la décomposition). Ajout en 3.1 : dans les 1 % pires semaines après 2009, les coefficients de Drobetz et al. donnent une corrélation de 0,15, supérieure à celle des semaines normales (0,10).
- **Calculs expliqués en notes de bas de page** (il n'y a pas d'oral) : voir la section suivante.
- **Bibliographie réduite de 31 à 16 références.** Seules restent les sources qui portent l'argument : les 3 articles principaux ; 3 études divergentes ou complémentaires (Gürtler et al., Braun, Feng et Zeng) ; 2 pour les définitions (Baur et Lucey, Baur et McDermott) ; Cummins pour le fonctionnement des CAT bonds ; 2 pour le mécanisme de liquidité (Brunnermeier et Pedersen, Duffie) ; 3 pour la mesure (Forbes et Rigobon, Getmansky et al., Herrmann et Hibbeln) ; 2 articles de presse pour mars 2020. Les DOI sont de nouveau dans la bibliographie.
- **Retirées, avec les phrases qui en dépendaient** : Artemis (2008, 2009, 2011, 2022), Bank of England (2022), BIS (2022), Bucci et al. (2023), Government Actuary's Department (2021), Froot (2001), Cummins et Weiss (2009), Campbell et Vuolteenaho (2004), Roll (1984), Bouri et al. (2017), Engle (2002), Hamilton (1989), Bollerslev et al. (1988). Ont donc disparu du texte : les noms des quatre obligations Lehman et le défaut d'Ajax Re, la part de 60 % des fonds monétaires en 2011, l'épisode LDI/Ian de septembre 2022 et les chiffres des obligations pandémie de la Banque mondiale. Aucune affirmation n'est restée sans source.
- **Ajouts tirés des articles déjà cités** (pour garder la revue au-dessus de 5 pages) : prime de liquidité de 141 pb pour les obligations risquées et marché dominé par des courtiers sans inventaire (Herrmann et Hibbeln, résumé SSRN) ; corrélation asymétrique avec les matières premières pendant la pandémie (Feng et Zeng, résumé risk.net).
- **Mise en page** : bibliographie en 10 pt, espace de 3 pt après les paragraphes, première colonne des tableaux plus étroite.

## Les calculs (notes de bas de page 1 à 6)

1. **Corrélation implicite (3.1, note 1).** Les indicatrices de Drobetz et al. sont emboîtées : une semaine dans les 5 % pires est aussi dans les 10 % pires, mais pas dans le 1 % pire. Corrélation ajustée = *m*₀ + *m*₁ + *m*₂ = 0,10 + 0,04 − 0,09 = 0,05 ; 0,01 si *m*₁ (non significatif) vaut 0. Dans le 1 % pire : 0,10 + 0,04 − 0,09 + 0,10 = 0,15.
2. **Bêta d'une somme (3.2, note 2).** La covariance est linéaire, donc le bêta du rendement total est la somme des bêtas de ses composantes. *D* est constant sur la période ; le spread fixe *s* a un bêta nul.
3. **40 à 80 points de base (3.3, note 3).** Le coupon flottant se réajuste, le spread fixe non. Une hausse Δπ de la prime exigée fait baisser le prix d'environ *D*·Δπ, où *D* ≈ durée de vie restante. Échéance de 3 à 4 ans à l'émission, donc 1,5 à 2 ans restants en moyenne dans un indice ; on prend 1 à 2 ans. L'indice de prix exclut les coupons, donc *r* et *s* disparaissent ; il n'y a ni catastrophe ni perte de collatéral, donc ℓ = *k* = 0. Δπ = 0,81 / *D* : 0,40 % (40 pb) pour *D* = 2, 0,81 % (≈ 80 pb) pour *D* = 1.
4. **Corrélation et bêta (3.4, note 4).** β = ρ·σ_CAT/σ_m = 0,25 × 0,41/4,49 ≈ 0,02. Avec β = 0,014, une baisse de 20 % du S&P 500 donne 0,014 × 20 = 0,28 % ≈ 0,3 %.
5. **Effet de la volatilité seule (3.4, note 5).** Avant la crise, β ≈ 0,016 × 0,37/1,91 ≈ 0,0031 et σ_ε ≈ 0,37. Avec σ_m = 4,49 : ρ = 0,0139/√(0,0139² + 0,37²) ≈ 0,038, loin de 0,252.
6. **Fin 2008 (3.4, note 6).** Environ 15 semaines sur 365. Même avec une corrélation de 1 pendant ces 15 semaines : (15 × 1 + 350 × 0,016)/365 ≈ 0,06, loin de 0,24.

Tous ces chiffres ont été recalculés par script le 10 novembre.

## Vérification des références

- **Haffar et Le Fur (2022)** : confirmé par la recherche web (Springer, RePEc) : *Journal of Asset Management*, vol. 23, n° 4, pp. 297–309, juillet 2022 (en ligne le 3 juin 2022).
- **Feng et Zeng (2025)** : confirmés par risk.net : *Journal of Risk*, vol. 27, n° 4 (avril 2025), DOI 10.21314/JOR.2024.022. **Pages non trouvées** : retirées de la bibliographie. Ajoute-les depuis ton PDF de l'article.
- La phrase « When Lehman Brothers, the swap counterparty of several CAT bonds, failed in September 2008, this structure failed with it » est maintenant rattachée au récit de Carayannopoulos et Perez (2015). Vérifie dans leur article qu'ils mentionnent bien Lehman comme contrepartie des swaps.

## Restent à faire

1. Ouvre `paper.docx` dans Word et vérifie qu'il fait 15 pages.
2. Ajoute les pages de Feng et Zeng (2025) depuis le PDF.
3. Corrige la date de la page titre (« December 2026 ») si besoin.
