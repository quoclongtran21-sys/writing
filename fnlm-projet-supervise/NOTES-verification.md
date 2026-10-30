# Notes de vérification — carnet FNLM

Ces notes accompagnent `FNLM_CODE_nettoye_final.ipynb`. Seules les cellules d'explication (markdown) ont changé : les cellules de code, leurs sorties et les métadonnées sont identiques à la version d'origine, ce que le script de remplacement a vérifié cellule par cellule.

## Méthode

1. Chaque chiffre des interprétations a été comparé aux sorties enregistrées du carnet. Les nombres qui n'apparaissent pas tels quels dans les sorties sont des ratios calculés à partir d'elles (par exemple 643 / 1 132 = 56,8 %).
2. Chaque explication du code a été relue contre le code qu'elle décrit.
3. Le style suit le skill `humanizer-french` (motifs propres au français) et le skill d'écriture académique en français. La liste `avoid-ai-writing` du dépôt Awesome-skills a servi de contrôle, sans en transposer les règles : elles sont calibrées pour l'anglais.
4. Le registre académique est conservé, de même que les blocs « Problème / Solution » et les espaces ordinaires (pas d'espaces insécables, que l'outil `watermark-remover` classe parmi les marques à normaliser).

## Corrections de fond

| Cellule | Avant | Après |
|---|---|---|
| 1.1, listes de colonnes | les champs fixes « doivent rester constants pour un site » | ils doivent être identiques entre les lignes répétées d'un même couple site-exercice ; seuls `class` et `sitestatus` sont contrôlés d'un exercice à l'autre |
| 1.2, base de sites | le choix de la dernière observation « ne fait perdre aucune information » | vrai pour la classe et le statut ; les autres champs (province, organisation, `involvement`, population, coordonnées) sont ceux du dernier exercice |
| 1.2, invariance | — | un statut identique sur trente exercices, même pour un site fermé, indique que le fichier reporte la classe et le statut les plus récents sur tout l'historique |
| 1.3, étape 1 | « qu'elle retire » (ambigu) | elle garde le premier segment et en retire le code de réserve |
| 1.4, étape 6 | — | la propagation pourrait en principe réintégrer une exclusion manuelle ; le bilan montre que les 20 exclusions subsistent |
| 1.5 | « le code vérifie » l'absence de grappe mixte | il la signale par un message, sans arrêter l'exécution |
| 3.2 | « les modèles avec effets fixes sont conservés dans `modeles_finaux` » | les six modèles y sont conservés ; la figure 4.3 utilise ceux à effets fixes |
| 4.13 | la superficie « ne diffère presque pas » | l'écart normalisé est négligeable, mais les moyennes vont presque du simple au double (0,23 et 0,42 ha) |
| 4.12 | les autres codages « renforcent légèrement » les écarts | ils les accentuent (11,2 → 14,4 points pour le statut actif) |
| 4.19 | « le signe des écarts est stable » | vrai pour le statut actif et la haute priorité ; pour la priorité d'action, le signe change avec les effets fixes d'organisation |

## Résultats ajoutés (tous tirés des sorties)

- Modèles 1 à 3 : coefficients sans contrôles ; pour la haute priorité, le coefficient FNLM passe de 10,0 points à 0,4 point avec les effets fixes provinciaux.
- Section 3.5 : effectifs et grappes des modèles sur réserve (2 027 sites et 553 grappes ; 4 503 et 692).
- Section 4.3 : médiane de remédiation nulle dans les trois groupes ; résultats d'évaluation.
- Section 4.11 : tailles des échantillons réduits ; pour la haute priorité, la baisse de l'écart vient surtout du changement d'échantillon. Section 4.19 : sur réserve, elle vient des contrôles.
- Section 4.17 : décompte des 4 318 paramètres absorbés (4 290 sites + 29 exercices − 1).
- Section 4.18 : intervalle de confiance à 95 % du coefficient temporel, de −0,22 à +0,24 étape (0,013 ± 1,96 × 0,117).

## Restent à vérifier

1. Valeur p de 0,543 en Colombie-Britannique (priorité d'action) : la sortie affiche 0,5425, dont l'arrondi à trois décimales peut donner 0,542 ou 0,543. Relancer le carnet pour trancher.
2. Le carnet n'a pas été réexécuté, faute du fichier `.dta` dans le dépôt. Si une cellule de code change, relire les interprétations qui en dépendent.
3. La propagation par numéro de bande (étape 6) ne protège pas explicitement les exclusions manuelles. Ce n'est pas un problème avec les données actuelles, mais une condition `methode_appariement != "exclusion manuelle"` le rendrait impossible.
4. Les tableaux des sections 4.2, 4.8, 4.9 et 4.10 affichent les noms de variables bruts (`priorite_action`) dans la colonne Issue. Un `.map(NOMS_INDICATEURS)` sur la colonne `issue`, dans `montrer_robustesse` et à la section 4.8, afficherait les libellés.
