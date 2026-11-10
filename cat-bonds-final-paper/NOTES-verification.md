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

- Les tensions de financement autour de Bear Stearns (mars 2008).
- La crise des fonds de pension britanniques (LDI) et l'arrivée de l'ouragan Ian (28 septembre 2022).

Ajoute une source si le professeur l'exige.

## Révisions du 10 novembre 2026 (à partir de `paper_corrige.docx`)

La base est la version corrigée dans Word (révision 6, 30 octobre). Elle faisait 17 pages ; celle-ci en fait 15 (PDF LibreOffice, polices métriquement identiques à Times New Roman), avec environ un tiers de page libre.

### Répartition des pages

| Partie | Pages |
|---|---|
| Page titre | 1 |
| 1. Introduction | 1,3 |
| 2. Revue de littérature (2.1 à 2.7, avec le tableau 1) | 5,1 |
| 3. Analyse (3.1 à 3.6, avec le tableau 2) | 5,3 |
| 4. Conclusion | 0,5 |
| Bibliographie | 1,4 |

### Ce qui a changé

- **Revue de littérature portée à 5,1 pages.** La description complète des résultats de chaque article (régimes de Markov de Carayannopoulos et Perez, mécanismes cités par Drobetz et al., limites rapportées par Haffar et Le Fur eux-mêmes) est revenue en section 2. Une nouvelle section 2.7 dit ce que la littérature établit et ce qu'elle laisse ouvert, ce qui justifie l'analyse.
- **Analyse.** La 3.1 évalue chaque article ; la 3.2 présente la contribution (la décomposition). Ajout en 3.1 : dans les 1 % pires semaines après 2009, les coefficients de Drobetz et al. donnent une corrélation de 0,15, supérieure à celle des semaines normales (0,10).
- **Calculs expliqués en notes de bas de page** (il n'y a pas d'oral) : voir la section suivante.
- **Références ajoutées** : Artemis (2008) pour la dégradation des quatre obligations Lehman ; BIS (2022) et Bank of England (2022) pour la crise LDI ; Bucci et al. (2023) pour l'ouragan Ian ; Artemis (2022) pour la chute de l'indice après Ian ; Engle (2002), Hamilton (1989) et Bollerslev, Engle et Wooldridge (1988) pour les méthodes DCC, Markov et VEC diagonal.
- **Mise en page** : bibliographie en 10 pt, espace de 3 pt après les paragraphes, première colonne des tableaux plus étroite. DOI retirés des articles de revue (liste plus bas) ; URL conservées pour les sources web.

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
- **Nouvelles sources** : titres et dates confirmés par la recherche web (Banque d'Angleterre, 28 septembre 2022 ; BIS Quarterly Review, décembre 2022 ; rapport NHC sur Ian, 3 avril 2023 ; Artemis, 30 septembre 2008). La date exacte de l'article Artemis sur Ian n'a pas été trouvée (« 2022 »). Les pages elles-mêmes n'ont pas pu être ouvertes depuis cette session (domaines bloqués).
- Engle (2002), Hamilton (1989) et Bollerslev, Engle et Wooldridge (1988) sont des références classiques ; leurs détails n'ont pas été revérifiés en ligne.

## DOI retirés de la bibliographie (pour vérification)

- Baur, Dirk G., and Brian M. Lucey (2010) : https://doi.org/10.1111/j.1540-6288.2010.00244.x
- Baur, Dirk G., and Thomas K. McDermott (2010) : https://doi.org/10.1016/j.jbankfin.2009.12.008
- Bollerslev, Tim, Robert F. Engle, and Jeffrey M. Wooldridge (1988) : https://doi.org/10.1086/261527
- Bouri, Elie, Peter Molnár, Georges Azzi, David Roubaud, and Lars Ivar Hagfors (2017) : https://doi.org/10.1016/j.frl.2016.09.025
- Braun, Alexander (2016) : https://doi.org/10.1111/jori.12067
- Brunnermeier, Markus K., and Lasse Heje Pedersen (2009) : https://doi.org/10.1093/rfs/hhn098
- Campbell, John Y., and Tuomo Vuolteenaho (2004) : https://doi.org/10.1257/0002828043052240
- Carayannopoulos, Peter, and M. Fabricio Perez (2015) : https://doi.org/10.1057/gpp.2014.14
- Cummins, J. David (2008) : https://doi.org/10.1111/j.1540-6296.2008.00127.x
- Cummins, J. David, and Mary A. Weiss (2009) : https://doi.org/10.1111/j.1539-6975.2009.01311.x
- Drobetz, Wolfgang, Henning Schröder, and Lars Tegtmeier (2020) : https://doi.org/10.1016/j.frl.2019.05.016
- Duffie, Darrell (2010) : https://doi.org/10.1111/j.1540-6261.2010.01569.x
- Engle, Robert (2002) : https://doi.org/10.1198/073500102288618487
- Feng, Chi, and Xudong Zeng (2025) : https://doi.org/10.21314/JOR.2024.022
- Forbes, Kristin J., and Roberto Rigobon (2002) : https://doi.org/10.1111/0022-1082.00494
- Froot, Kenneth A. (2001) : https://doi.org/10.1016/S0304-405X(01)00052-6
- Getmansky, Mila, Andrew W. Lo, and Igor Makarov (2004) : https://doi.org/10.1016/j.jfineco.2004.04.001
- Gürtler, Marc, Martin Hibbeln, and Christine Winkelvos (2016) : https://doi.org/10.1111/jori.12057
- Haffar, Adlane, and Éric Le Fur (2022) : https://doi.org/10.1057/s41260-022-00271-3
- Hamilton, James D. (1989) : https://doi.org/10.2307/1912559
- Herrmann, Markus, and Martin Hibbeln (2023) : https://doi.org/10.1111/jori.12407
- Roll, Richard (1984) : https://doi.org/10.1111/j.1540-6261.1984.tb03897.x

## Restent à faire

1. Ouvre `paper.docx` dans Word et vérifie qu'il fait 15 pages.
2. Ajoute les pages de Feng et Zeng (2025) depuis le PDF.
3. Corrige la date de la page titre (« December 2026 ») si besoin.
