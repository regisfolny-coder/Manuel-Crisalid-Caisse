
# Installation CRISALID Caisse
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



    

<!--stackedit_data:
eyJoaXN0b3J5IjpbLTIwNjI1MDY0OTJdfQ==
-->
