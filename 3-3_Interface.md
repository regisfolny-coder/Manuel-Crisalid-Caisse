
---
titre: "Manuel d'utilisation Crisalid Caisse"
sujet: "Configuration et procédures d'encaissement"
auteur: "Regis Folny (Service Support & Qualité)"
créé le: 2026-08-18
mis à jour le: 2026-08-18
version: "1.0"
service: "Qualité"
Type : "Document"
---

## Interfaces

Le menu **Interface** permet de personnaliser l'aspect visuel et le comportement des écrans de vente :

-   **Paramètres généraux:**
    
    -   **Identification de la caisse :** Nom d'affichage du poste (ex: CENTRAL issu du serveur de licence).
        
    -   **Environnement par défaut :** Sélection du mode de fonctionnement (ex: CAISSE ou BORNE).
        
    -   **Tarif par défaut / Tarif par défaut des nouvelles tables :** Choix de la grille tarifaire (ex: RESTAURANT).
        
    -   **Double affiche en devise:** pour afficher devise étrangère
        
    -   **Délai de mise en veille :** Réglage du délai d'inactivité avant mise en veille (ex: 30 s pour mode Borne).
        
-   **Interface de vente :**
    
    -   **Couleur de base :** couleur de fond de l'application.
        
    -   **Couleur du texte du ticket :** couleur des lignes dans la vue du ticket.
        
    -   **Layout par défaut :** Sélection du Layout de l' interface de caisse.(défini dans \config\layout.xml et réservé au service technique) cf Layout  
        Le clavier tactile est composé de plusieurs éléments dont la position est définie dans le fichier layout:  
        ![](https://www.crisalid.com/web/image/87976-a59e9e8d/image.png?access_token=809985f9-cee3-4a90-bb88-cc820b904471)  
          
        
    
      
    
    **Elements du clavier**
    
    Ticket
    
    Numpad
    
    Petit clavier (Pclavier)
    
    Fonctions
    
    Grand Clavier (Gclavier)
    
    Volante
    
    Header
    
    **Description  
    **Affichage du contenu du ticket
    
    Pavé numerique
    
    Elément réservé de base au bouton de familles
    
    Elément réservé de base aux touches de fonctions
    
    Elément reservé de base aux articles
    
    Element réservé aux commentaires
    
    Entête
    
    -     
        
    -     
        
    -   **Grand clavier par défaut:** Choix du grand clavier affiché au lancement de l'application
        
    -   ****Petit clavier par défaut:**** Choix du petit clavier affiché au lancement de l'application  
        
    -   **Clavier de fonctions par défaut:** Choix du clavier de fonctions affiché au lancement de l'application  
        Pour chacun des élément il est possible de sélectionner des claviers dynamiques (entre<>)qui se construiront automatiquement à partir des données saisies dans la programmation des articles, familles et groupes.  
        ![](https://www.crisalid.com/web/image/87978-09edbe4a/image.png?access_token=2ae36bb5-4fc2-45bc-9202-9fd620718c0b)
        
-   **Définition par défaut des clavier :**
    
    -   Permet de définir le nombre de bouton présents dans chaque élément:  
        ![](https://www.crisalid.com/web/image/87979-b98ea15a/image.png?access_token=adf5cccd-d566-4449-b17d-39bb01236cd8)
        
-   **Affichage des Widgets du deuxième écran (écran client):**
    
    -   Paramétrage d'un écran secondaire / affichage client (Images par défaut, URL pour la publicité comme [https://www.crisalid.com]([https://www.crisalid.com](https://www.crisalid.com))) positionnés selon les paramètres définis dans le ficheir Layout.
        
-   **Touches vendeurs :** afficher sur le bouton vendeur le Nom, Prénom ou numéro
    
-   **Saisie des prix dans le pavé numérique:** la saisi peut être faite avec des décimales ou sans décimale. Il est possible de personnalisé le mode de saisie
    
-   **Styles des boutons**
    
    -   **Style des boutons :** Mode d'affichage des touches (ex: Bouton plat, Dégradé).
        
    -   **Polices & Tailles :** Personnalisation de la police (ex: Segoe UI) et de la taille du texte pour les éléments du ticket et des boutons.
        

  

### Validation

1.  Cliquez sur le bouton **Valide** dans la barre supérieure pour enregistrer.
    
2.  Confirmez le message d'avertissement indiquant que certaines modifications seront prises en compte après redémarrage de l'application en cliquant sur **OK**.
    
3.  Cliquez sur **Terminé** (en haut à droite) puis retournez à l'écran de caisse via le bouton **Accueil**.
<!--stackedit_data:
eyJoaXN0b3J5IjpbMTgxNTUxOTQzMSwtMTUyNjU5NTU5N119
-->