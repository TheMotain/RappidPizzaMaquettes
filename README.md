Maquettes de RapidPizza (Projet de GL, 2016)


Visualisation de la maquette : RapidePizza.html


Liste des ecrans:
- index.html : accueil

- Marketing/listePromotions-Tout.html         }--> lien vers :  - creerPromotion.html (bouton creer)
- Marketing/listePromotions-Suspendus.html    }                 - modifierPromotion.html (premier bouton modifier de listePromotions-Tout.html et listePromotions-Actifs.html)
- Marketing/listePromotions-Archives.html     }                 - lien entre chaque liste dans le tableau de bord
- Marketing/listePromotions-Terminés.html     }                 - lien vers listePromotions-Tout (navbar)
- Marketing/listePromotions-Actifs.html       }
- Marketing/creerPromotion.html               }--> lien vers :  - editionPromotionErreurValidation.html (bouton valider)
                                                                - listePromotions-Tout.html (bouton annuler)
                                                                - lien vers listePromotions-Tout (navbar)
- Marketing/modifierPromotion.html            }--> idem creerPromotion.html
- Marketing/editionPromotionErreurValidation.html }--> idem creerPromotion.html

- Agenda/Agenda.html                          }--> lien vers :  - historiqueStatistique.html {navbar}

- Comptabilite/historiqueStatistique.html     }--> lien vers :  - Agenda {navbar}
                                                                - historiqueStatistiqueResultatAnnuel.html {bouton rechercher}
                                                                - exceptionFonctionnelle.html {bouton exporter}
- Comptabilite/historiqueStatistiqueResultatAnnuel.html         }--> lien vers :  - historiqueStatistiqueErreurRecherche.html {bouton rechercher}
- Comptabilite/historiqueStatistiqueErreurRecherche.html        }--> idem historiqueStatistique.html

- Exception/exceptionFonctionnelle.html
- Exception/exceptionTechnique.html


- gestionnaire_stock/accueilGestionnaire.html 					}--> accueil de l'acteur gestionnaire de commande
- gestionnaire_stock/stock/modificationEtatStock.html 			}--> A partir de l'accueil au dessus, cliquer sur 'Modifier l'état des stocks'
- gestionnaire_stock/stock/modificationEtatStockOK.html 		}--> Page de l'état des stock , cliquer sur 'Voir l'état des stocks' ou sur 'valider' après avoir modifier l'état des stocks

- gestionnaire_stock/stock/commandeStock/ajouterProduit.html 	}--> Page pour ajouter un produit à une commande pour approvisionner le stock. Cliquer sur 'Approvisionner le stock' et ensuite sur le bouton 'Ajouter' en haut à droite
- gestionnaire_stock/stock/commandeStock/commandeStock.html 	}--> Page de la commande d'approvisionnement de stock. Cliquer sur 'Approvisionner le stock'
- gestionnaire_stock/stock/commandeStock/commandeStockOK.html 	}--> Page de la commande d'approvisionnement avec produits ajoutées. Cliquer sur 'valider' apres avoir choisit les produits dans la page 'Approvisionner le stock' puis 'ajouter'

- gestionnaire_stock/stock/fournisseur/formFournisseur.html 	}--> Page formulaire pour l'ajout d'un fournisseur. Cliquer sur 'Ajouter un nouveau fournisseur'
- gestionnaire_stock/stock/fournisseur/ajoutFournisseurOK.html	}--> Page de validation du fournisseur. Apres avoir remplit le formulaire d'ajout du fournisseur. Cliquer sur 'valider'

- gestionnaire_stock/stock/produit/accueilProduit.html			}--> Page contenant tous les produits. Cliquer sur 'Voir les produits'
- gestionnaire_stock/stock/produit/formProduit.html 			}--> Formulaire de l'ajout d'un produit. Cliquer sur 'Ajouter un nouveau produit avec fournisseur'
- gestionnaire_stock/stock/produit/formCategorie.html 			}--> Formulaire pour ajouter une categorie. Cliquer sur 'Ajouter un nouveau produit avec fournisseur' puis cliquer sur 'La catégorie n'existe pas dans la liste?'
- gestionnaire_stock/stock/produit/ajoutCategorieOK.html		}--> Page de validation de l'ajout de la nouvelle catégorie. Même chose que la description ci-dessus et cliquer sur 'valider'
- gestionnaire_stock/stock/produit/recapProduit.html			}--> Fiche récapitulative du produit (pour l'ajout de celui-ci).
- gestionnaire_stock/stock/produit/ajoutProduitOK.html 			}--> Page de validation de l'ajout du nouveau produit, vient apres  la confirmation de l'ajout du produit
