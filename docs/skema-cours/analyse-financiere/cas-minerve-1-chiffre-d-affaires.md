---
titre: "Cas Librairie Minerve — épisode 1 : chiffre d'affaires (énoncé et corrigé)"
source_fichier: Cas Librairie Minerve 1 CA enoncé 2025.docx + cas Minerve 1 C.A corrigé 2025.xlsx
type: "cas d'étude (énoncé + corrigé tableur)"
langue: fr
fiabilite: support-de-cours
sujets: ["analyse financière", "budget", "chiffre d'affaires", "TVA", "loi Lang", "produits d'exploitation", "cas Minerve"]
---

# Cas Librairie Minerve — épisode 1 : chiffre d'affaires

> Cours « Analyse financière de projets et processus d'investissements » (SKEMA) : cas d'étude de l'enseignant. Budget 2025 d'une librairie. Les épisodes 2 et 3 reprennent les chiffres de celui-ci ([épisode 2](cas-minerve-2-achats-et-charges-externes.md), [épisode 3](cas-minerve-3-resultat.md)).

## Énoncé

**Cas Librairie Minerve**
**Episode 1 : Chiffre d’Affaires**
- *Informations*
1. Vous êtes chargé d’établir le budget 2025 de la Librairie Minerve.

L’entreprise, fondée en 1963, est une librairie établie dans une ville de province, sous la forme d’une S.A.S.

Son exercice comptable coïncide avec l’année civile.

> Minerve vend bien sûr les livres au public dans la librairie, mais aussi des ouvrages scolaires à des collectivités et associations, et a lancé en 2023 une activité de vente à distance via Amazon et son propre site web.

2. Les ventes au public en librairie sont, bien sur, payées par les clients en caisse. Ceux-ci bénéficient de cartes de fidélité leur permettant de bénéficier sur tous leurs achats de la remise maximale autorisée par la loi « Lang » n° 81-766 du 10 août 1981 relative au prix du livre, dès que 200 € TTC d’achats sont effectués.

On estime, par expérience, que 10 % des remises ne seront pas réclamées (clients ponctuels, cartes perdues…) et que le reste des remises dues seront réclamées sur de nouveaux achats, dont 30% avec un an de délai à partir de la première vente.

3. Le prix unitaire moyen ttc d’un ouvrage est de 22 €.
4. On prévoit 550 000 € TTC (prix public) de commandes professionnelles de livres scolaires (associations et collectivités) en 2025, mais compte tenue de difficultés d’approvionnement, on craint que 10 % des commandes ne puissent être livrées.
5. La tva applicable en France sur le livre est de 5.5 %. On suppose par simplification que toutes les ventes même à distance s’effectuent en France. Le taux de tva sur les frais de port suit celui des livres.
6. On estime que le nombre de livres vendus en librairie s’élèvera en 2023 à 200 000, l’objectif 2025 est d’augmenter de 5% ce volume par des actions marketing, et les ventes croissantes des ouvrages des rayons spiritualité, bien-être, et mangas.
7. Par dérogation à la loi Lang, on applique une remise de 9 % aux collectivités sur le prix public, celles-ci règlent Minerve à 60 jours date de livraison. On estime que 45 000 € de ventes TTC 2025 seront réglées en 2026.
8. On espère livrer en 2025 12 000 commandes de ventes à distance, chacune de trois livres en moyenne
9. Le prix unitaire moyen des livres vendu à distance est de 30 € TTC, il n’y a pas de remises.
10. Des paiements d’avances sont réclamés pour la vente de livres scolaires à certaines associations peu solvables pour environ 50 000 € par an. On estime les impayés à 5 000 € par an.
11. 50 % des ventes à distances sont réalisées via Amazon, qui prélève 20 % de commissions, et les autres 50 % sur le site de minerve. Les commissions sont comptabilisées comme des charges d’exploitation
12. Seules 30 % des commandes à distance sont inférieures à 35 €, seuil en dessous duquel l’entreprise facture le minimum légal de 3€ de frais de port par livraison (on suppose qu’il y a une seule livraison par commande). Au-dessus de ce seuil, les frais de port facturés (0.01 €) sont négligeables.
13. Minerve a obtenu l’accord du Centre National du Livre pour une subvention de 50 % des couts de rénovation et mise aux normes d’accueil de la librairie. Les travaux seront de 75 000 €HT en 2025 et 75 000 € HT en 2026. Minerve a reçu un acompte de 30 000 € en 2024, attend un second acompte de 30 000 € en 2024 et le solde en 2026.
14. Les couts de développement de la Version 2 du site de ventes à distance (personnel de Minerve) s’élèveront à 100 000 € en 2025 pour une mise en ligne en 2026.

**Questions**
1. Chiffre d’Affaires 2025 en librairie
2. Chiffre d’Affaires 2025 avec les clients professionnels (collectivités et associations)
3. Chiffre d’Affaires 2025 des commandes à distances (marketplace)
4. Autres produits d’exploitation de l’exercice 2025 ?

## Corrigé (tableur de l'enseignant)

Colonnes : A intitulé · B repère de l'énoncé (lettre) · C montant · D commentaire. Les taux sont en décimal (0,055 = 5,5 %).

Feuille « Feuil1 » :

| Ligne | A | B | C | D |
|---|---|---|---|---|
| 1 | CAS librairie Minerve |  |  |  |
| 2 | Corrigé Chiffre d'Affaires |  |  |  |
| 3 | A/ C.A.  librairie grand public |  |  |  |
| 4 | Intitulé | Réf enoncé | montant | Commentaires |
| 5 | Nombre ouvrages | f | 210 000 `=200000*1.05` | augmentation de 5%:200 000 \*1,05 |
| 6 | prix moyen TTC | c | 22 |  |
| 7 | CA prix public TTC |  | 4 620 000 `=+C6*C5` | Quantité \* prix public |
| 8 | Taux de TVA | e | 0,055 |  |
| 9 | CA Prix public HT |  | 4 379 146,92 `=+C7/(1+C8)` | CA public TTC/(1+5,5%) |
| 10 | taux de remise moyen | b | 0,045 `=5%*0.9` | 5 % Loi Lang sur 90 % des ventes |
| 11 | provisions remises (loi lang) |  | 197 061,61 `=+C10*C9` |  |
| 12 | CA net de remises |  | 4 182 085,31 `=+C9-C11` | CA public HT - remise |
| 14 | B/ C.A. clients professionnels (écoles et associations) |  |  |  |
| 16 | CA TTC commandé | d | 550 000 | CA commandé |
| 17 | CA HT commandé | d | 521 327,01 `=+C16/(1+C8)` | CA TTC / (1+5,5%) |
| 18 | Marchandises non livrées | d | -52 132,70 `=-C17*0.1` | 10 % de commande |
| 19 | CA HT  livré (tarif) |  | 469 194,31 `=+C17+C18` | CA commandé moins non livré |
| 20 | % de remise | g | 0,09 | aux professionnels |
| 21 | remise |  | 42 227,49 `=+C19*C20` | sur CA HT |
| 22 | CA total H.T. |  | 426 966,82 `=+C19-C21` | CA tarif moins remises |
| 25 | C/ C.A. Marketplaces |  |  |  |
| 27 | Nbe de commande | h | 12 000 |  |
| 28 | Nbe ouvrages par commande | h | 3 |  |
| 29 | prix moyen TTC ouvrage | i | 30 |  |
| 30 | CA TTC |  | 1 080 000 `=+C29*C28*C27` | Nbe commande\* prix ttc moyen\* nbe ouvrage / commande |
| 31 | Taux de TVA | e | 0,055 |  |
| 32 | CA ventes HT |  | 1 023 696,68 `=+C30/(1+0.055)` | CA TTC/(1+5,5%) |
| 33 | % de commandes < 35 € | l | 0,3 | % de commande soumises aux frais de port |
| 34 | frais de port à 3€ | l | 10 800 `=(+C33*C27)*3` | 3 €sur 30 % des commandes |
| 35 | frais de port à 3€ HT |  | 10 236,97 `=+C34/1.055` | frais de port / (1+5,5%) |
| 36 | CA HT |  | 1 033 933,65 `=+C35+C32` | Ca vente + port |
| 39 | D/ C.A. total |  | 5 642 985,78 `=+C36+C22+C12` | libraire grand public + professioneel + marketplace |
| 41 | E/ Autres produits d'exploitation |  |  |  |
| 43 | production immobilisée | n | 100 000 | couts de developpement |
| 44 | Subvention | m | 37 500 `=75000/2` | 50% sur travaux effectués en 2024 (75 000 €) |
| 45 | Total autres produits d'exploitation |  | 137 500 `=SUM(C43:C44)` |  |
| 48 | Total produits d'exploitation |  | 5 780 485,78 `=+C45+C39` |  |

## Résultats du corrigé (lecture du tableur)

- CA librairie grand public : 210 000 ouvrages × 22 € TTC = 4 620 000 € TTC, soit **4 379 146,92 € HT** avant remise ; provision de remises (loi Lang) 197 061,61 € ; **CA net de remises 4 182 085,31 €**.
- CA clients professionnels : 550 000 € TTC → 521 327,01 € HT ; non livré (10 %) −52 132,70 € ; livré au tarif 469 194,31 € ; remise de 9 % = 42 227,49 € ; **CA HT 426 966,82 €**.
- CA marketplace : 12 000 commandes × 3 livres × 30 € = 1 080 000 € TTC → 1 023 696,68 € HT ; frais de port 10 800 € TTC (10 236,97 € HT) ; **CA HT 1 033 933,65 €**.
- **CA total : 5 642 985,78 €**.
- Autres produits d'exploitation : production immobilisée 100 000 € + subvention 37 500 € = **137 500 €** ; **total des produits d'exploitation 5 780 485,78 €**.
