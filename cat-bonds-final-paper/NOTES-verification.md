# Notes de vérification (à lire avant de remettre le travail)

Ces notes accompagnent `paper.docx` / `paper.pdf`. Elles disent ce qui a été vérifié, comment, et ce qu'il te reste à contrôler dans les PDF des articles.

## Ce qui a été vérifié

Le réseau de la session ne donnait pas accès aux PDF complets (Springer, Elsevier, SSRN, RePEc étaient bloqués). Chaque affirmation sur un article a donc été vérifiée à partir de son résumé publié, de sa notice bibliographique ou de citations du texte trouvées par recherche web. Aucun chiffre, aucune date d'échantillon et aucun coefficient n'a été ajouté sans source.

| Affirmation dans le travail | Source vérifiée | Statut |
|---|---|---|
| C&P (2015) : GARCH multivarié, ratios de couverture dynamiques lus comme des bêtas, zéro bêta seulement hors crise, corrélation significative après Lehman, effet plus faible que sur les autres actifs, bêtas revenus au niveau d'avant-crise avec les structures de 2009, faiblesses du compte de fiducie | résumé publié + résumé du document de travail (SSRN 2459974) | vérifié |
| Drobetz et al. (2020) : indice Swiss Re Global Unhedged Cat Bond Performance Index (indications d'offre hebdomadaires), 6 classes d'actifs, DCC puis régression (Bouri et al., 2017), mauvaise couverture, bon diversificateur, valeur refuge forte contre les actions seulement après la crise | résumé ScienceDirect + extraits du texte | vérifié |
| Haffar et Le Fur (2022) : copule-GARCH, dépendance variable dans le temps, portefeuille avec six indices boursiers (CAC 40, DJIA, EURO STOXX 50, FTSE 100, Hang Seng, Nikkei 225), meilleure performance ajustée au risque, l'un des meilleurs diversificateurs, plus faible hausse de la probabilité de co-mouvements extrêmes | résumé publié | vérifié |
| Gürtler et al. (2016) : effet de la crise et de Katrina, lien positif avec les écarts de crédit corporatifs, « ne devraient pas être considérées comme des titres à bêta nul » | résumé publié | vérifié |
| Braun (2016) : écarts des obligations de même notation parmi les déterminants | résumé du document de travail (2012) | probable : à confirmer dans la version publiée |
| Herrmann et Hibbeln (2023) : 9 393 transactions TRACE 2015-2019, prime de liquidité ≈ 1/5 de l'écart | résumé SSRN (révisé en avril 2023) | vérifié sur le document de travail |
| Feng et Zeng (2025) : diversificateur sur tout l'échantillon, valeur refuge contre actions et capital-investissement après l'épidémie, robuste aux rendements « désaplanis », sensibilité aux événements météo extrêmes | résumé Risk.net | vérifié |
| Lehman, swap de rendement total sur 4 obligations (Ajax Re, Carillon, Newton Re, Willow Re) ; Ajax Re n'a pas remboursé tout son principal en mai 2009 | Artemis (2009), presse spécialisée | vérifié |
| Mars 2020 : indice de prix Swiss Re −0,81 % la semaine du 20 mars, listes de ventes en bloc | Insurance Insider ILS (2020) | vérifié |
| Obligations pandémiques de la Banque mondiale : 16,67 % (classe A) et 100 % (classe B) du principal à risque | Government Actuary's Department (2021) | vérifié |
| Ouragan Ike : 13 septembre 2008 | presse ; Lehman : 15 septembre 2008 | vérifié |

DOI : tous les DOI ont été confirmés par recherche, sauf deux qui viennent de références standard non confirmées par la recherche : Baur et Lucey (2010) `10.1111/j.1540-6288.2010.00244.x` et Baur et McDermott (2010) `10.1016/j.jbankfin.2009.12.008`. Clique-les une fois avant l'impression.

## À contrôler dans les PDF (10 minutes)

1. **Période d'échantillon et fréquence de chaque article.** Le travail ne donne pas de dates d'échantillon, parce qu'elles n'étaient pas accessibles. Si tu les ajoutes (une demi-phrase par article dans 2.3, 2.4 et 2.5, et une ligne dans le tableau 1), le résumé des articles sera plus précis. Vérifie en particulier les dates des sous-périodes pré-crise / crise / post-crise de Drobetz et al.
2. **Quel indice CAT utilisent C&P (2015) et Haffar et Le Fur (2022).** Si c'est un indice Swiss Re, la remarque sur le lissage (section 2.5 et 3.4) s'applique directement ; tu peux alors enlever le « if » de la phrase correspondante.
3. **Les quantiles utilisés par Drobetz et al.** (habituellement 10 %, 5 % et 1 %). Une demi-phrase suffit.
4. **Si C&P contrôlent pour l'ouragan Ike** (septembre 2008). Si oui, ajuste la phrase de 2.3 (« Timing adds a further difficulty… ») pour dire qu'ils l'ont fait.
5. **Braun (2016)** : confirme que les écarts des obligations corporatives de notation comparable figurent bien parmi les déterminants dans la version publiée.

## La date sur la page titre

La page titre indique « December 2026 ». Change-la pour la date du dernier cours si elle est différente (fichier `build.py`, variable `COVER`, ou directement dans Word).
