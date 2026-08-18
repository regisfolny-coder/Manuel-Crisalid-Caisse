
# Manuel Crisalid Caisse

> ## Installation CRISALID Caisse
[![Regarder la vidéo](https://img.youtube.com/vi/zt3NII_u29M/hqdefault.jpg)](https://youtu.be/zt3NII_u29M)
### 1. Lancement de l'installateur

1.  Ouvrez le dossier contenant les fichiers d'installation (ex: Téléchargements). L'executable d'installation est disponible sur le site de Crisalid ([www.crisalid.com/download](https://www.crisalid.com/download))  
    ![](https://www.crisalid.com/web/image/87941-91775bb8/image.png?access_token=6720ad13-c0e0-4974-925a-8b77022b31cc)
    
2.  Localisez le fichier d'installation (ex: Neptis-6.6.0.107.28327.exe).
    
3.  Effectuez un **clic droit** sur l'exécutable et sélectionnez **Exécuter en tant qu'administrateur**.
    
4.  Validez l'invite de sécurité Windows si elle apparaît à l'écran.
    

### 2. Assistant de configuration de l'installation

1.  **Choix des composants (Composants à installer) :**
    
    -   Conservez l'option **Installation complète** sélectionnée par défaut (inclut les _Fichiers de l'application Caisse Crisalid_, les _Drivers du matériel spécifique_ et les _Modules d'extension_).
        
    -   Cliquez sur **Suivant**.
        
2.  **Tâches supplémentaires :**
    
    -   Laissez la case **Créer une icône sur le Bureau** cochée.
        
    -   Cliquez sur **Suivant**.
        
3.  **Résumé avant installation (Prêt à installer) :**
    
    -   Vérifiez le dossier de destination par défaut (C:\Program Files (x86)\CrisalidCaisse).
        
    -   Cliquez sur **Installer**.
        

### 3. Configuration requise : Fuseau horaire système

> **Avertissement critique (Fenêtre « Verification du fuseau horaire ») :**
> 
> Pour fonctionner correctement, la machine doit impérativement être à l'heure et sur le bon fuseau horaire.

1.  **Vérification du fuseau horaire :**
    
    -   Assurez-vous que le fuseau sélectionné correspond à votre région (ex: (UTC+01:00) Bruxelles, Copenhague, Madrid, Paris).
        
2.  **Synchronisation :**
    
    -   Vérifiez que l'horloge système est synchronisée avec un serveur de temps Internet (réglages accessibles via le panneau _Date et heure_ de Windows).
        
3.  Cliquez sur **Suivant** pour lancer la copie des fichiers.
    

### 4. Déroulement automatique de l'installation

L'assistant déploie et configure automatiquement les services requis :

-   Installation de la base de données **Firebird**
    
-   Installation de l'agent de maintenance **Butterfly**
    
-   Extraction des fichiers applicatifs, DLL et modules (Ventes, Stats, Loyalty, etc.)
    
-   Configuration du service système Crisalid Caisse Service et ouverture des règles pare-feu.
    

### 5. Finalisation et lancement de la web-configuration

1.  Une fois la barre de progression terminée, la fenêtre **Fin de l'installation de Crisalid Encaissement** s'affiche.
    
2.  Cochez la case **Afficher la page de configuration** (ou décochez-la si vous préférez procéder ultérieurement).
    
3.  Cliquez sur **Terminer**.

> ## Configuration du logiciel CRISALID Caisse
> ### 1. Accès au menu de configuration

1.  Depuis l'écran de caisse principal, connectez-vous avec un compte disposant des droits d'administration (ex: profil Manager / code 1).
    
2.  Cliquez sur la touche **Manager** (icône papillon en bas à droite).
    
3.  Dans le panneau de gestion, sélectionnez le bouton orange **Configuration**.
    
4.  Dans le menu latéral gauche, cliquez sur le tout premier onglet : **Options générales**.
 ### Accès et Paramétrage des Options Générales

![](https://www.crisalid.com/web/image/88274-4aa82ea7/image.png?access_token=3a0ac346-2009-4fa2-a643-013560a6b237)

  

   

### 2. Synthèse des paramètres disponibles

Le menu des options générales regroupe les fonctions fondamentales d'utilisation au quotidien :

-   **Comportement général :**
    
    -   _Ouvrir le tiroir_ à l'encaissement.
        
    -   _Déloger vendeur à l'encaissement_ ou au changement de vendeur.
        
    -   _Import automatique re-travaillé_ et gestion des vendeurs/serveurs.
        
-   **Formules / Menus :**
    
    -   Options pour _Calculer automatiquement quand le ticket change_ et _Valider manuellement_.
        
-   **Paramétrage de la journée :**
    
    -   _Saisie de la valeur du _Fond de caisse par défaut_._  
        
    -   _Calcul du service sur le Hors taxe_
        
    -   _Prix donnés service compris._  
        
-   **Contraintes:**
    
    -   _Sous-total obligatoire_
        
    -   _Ouverture de table obligatoire_
        
    -   _Confirmer les ventes manuellement (en mode Borne uniquement)_
        
    -   _Confirmer les pesés manuellement_  
        
    -   _Pointage obligatoire avant d'utiliser la caisse (touche POINTAGE)_  
        
    -   _Remise en banque obligatoire_
        
    -   _Saisie du montant tend obligatoire (avec calcul du rendu monnaie)_
        
    -   _Désactiver l'option "choisir ce produit plus tard". (dans le cas des menus restaurant non automatiques)_
        
-   **Avoirs, Vouchers et Titres Restaurant :**
    
    -   Réglage du _Nombre de jours de validité pour les avoirs à partir de leur date d'émission_ (ex: 7 jours par défaut).
        
    -   Saisie du _Montant maximum admissible pour un paiement par Titre Restaurant_ (ex: 19,00 €).
        
-   **Doublons**
    
    -   Comportement par défaut de l'import des ticket quand un doublon est constaté ( portable d'inventaire ou tickets externe)
        
-   **Comptes Clients :**
    
    -   Gestion du _Solde maximum client autorisé (solde <= 0)_.
        
    -   _Cacher les mouvements pointés_.
        
    -   Type de facture récapitulative (Cumulée ou détaillée par ticket)
        
    -   Récap. des tickets sur la première page (liste le montant de tous les tickets qui participent à la facture)
        

​  

### 3. Enregistrement des modifications

1.  Après avoir coché ou modifié les paramètres souhaités, cliquez sur le bouton **Valide** dans la barre d'outils supérieure.
    
2.  Si une boîte de dialogue d'avertissement apparaît (_ex: « Attention certaines modifications ne pourront être prises en compte qu'après un prochain redémarrage de la caisse »_), cliquez sur **OK**.
    
3.  Pour quitter l'interface de paramétrage, cliquez sur **Terminé** (en haut à droite), puis retournez à l'écran principal via **Accueil**.
<!--stackedit_data:
eyJoaXN0b3J5IjpbLTU1MTc0NTA3NiwtMTUyNzk5NTk2OCwtMT
MwMzc0MDk4NF19
-->