************************************************************
************************************************************
* Fichier Readme/Lisez-moi pour l'installation de la 
* Technologie de stockage Intel(R) Rapid.
*
* Reportez-vous à la configuration requise pour une liste
* des systèmes d'exploitation pris en charge par la  
* Technologie de stockage Intel Rapid.
*
* Ce document contient des références à des produits
* développés par Intel. Certaines restrictions
* d'utilisation de ces produits existent, de même que des
* restrictions de divulgation des informations à des tiers. 
* Veuillez lire la section Avis de non-responsabilité au
* bas de ce document et contactez votre représentant Intel
* si vous souhaitez obtenir des informations supplémentaires.
*
************************************************************
************************************************************

************************************************************
* Intel n'émet aucune déclaration de facilité d'utilisation, 
* d'efficacité ou de garantie. Le CONTRAT DE LICENCE DU 
* LOGICIEL INTEL contenu dans ce document définit, de façon 
* complète, la licence et l'utilisation de ce logiciel.
************************************************************


************************************************************
* CONTENU DE CE DOCUMENT
************************************************************

Ce document contient les sections suivantes :

1.  Présentation
2.  Configuration requise
3.  Langues prises en charge
4.  Détermination du mode système
5.  Installation du logiciel
6.  Vérification de l'installation du logiciel
7.  Instructions d'installation avancées
8.  Identification du numéro de version du logiciel
9.  Désinstallation du logiciel
10. Accéder à l'interface utilisateur pré-système 
    d'exploitation
11. Gestion des volumes RAID pré-système d'exploitation
12. Options de réinitialisation du volume RAID dans 
    l'interface utilisateur pré-système d'exploitation
13. Vérification de la version du logiciel de la ROM 
    Optionnelle et du pilote UEFI pré-système 
    d'exploitation
Avis juridique
Contrat de license logicielle Intel(R)


************************************************************
* 1.  PRÉSENTATION
************************************************************

La Technologie de stockage Intel(R) Rapid est conçue pour 
fournir une fonctionnalité aux contrôleurs de stockage 
suivants :

    - Intel(R) 9 Series Chipset Family SATA AHCI/RAID 
      Controller
    - Intel(R) 8 Series/C220 Series Chipset Family SATA
      AHCI/RAID Controller
    - Intel(R) 7 Series/C216 Series Chipset Family SATA 
      AHCI/RAID Controller
    - Intel(R) C600 Series Chipset SATA AHCI Controller


************************************************************
* 2.  CONFIGURATION REQUISE
************************************************************

1.  Le système doit contenir un des contrôleurs Intel 
    compris dans la section 1 ci-dessus ainsi qu'un des 
    processeurs suivants** :   
    - Intel(R) vPro
    - Intel(R) Celeron
    - Intel(R) Pentium
    - Intel(R) Core(TM) i3, i5, ou i7
    - Famille de processeurs Intel(R) Xeon(R)

** Remarque : certaines caractéristiques de la Technologie de 
   stockage Intel(R) Rapid ne sont activées qu'en fonction du 
   processeur présent dans le système.


2.  Le système doit posséder un des systèmes d'exploitation
    suivants (aucune autre version de systèmes 
    d'exploitation Windows n'est prise en charge) :

    - Microsoft Windows* 10
    - Microsoft Windows* 10 Édition 64 bits**
    - Microsoft Windows* 8.1
    - Microsoft Windows* 8.1 Édition 64 bits** 
    - Microsoft Windows* 8
    - Microsoft Windows* 8 Édition 64 bits**  
    - Microsoft Windows* 7
    - Microsoft Windows* 7 Édition 64 bits** 
    - Microsoft Windows* Server 2008 R2 Édition 64 bits**
    - Microsoft Windows* Server 2012 Édition 64 bits**	
    - Microsoft Windows* Server 2012 R2 Édition 64 bits**
    - Microsoft Windows* MultiPoint Server 2011 Édition 64 bits**


3.  Les systèmes d'exploitation suivants ne sont pas pris 
    en charge :

    Toute version des systèmes d'exploitation suivants :
    - Linux*
    - UNIX*
    - BeOS*
    - MacOS*
    - OS/2*


4.  Le système doit contenir au minimum la mémoire système
    minimale requise par le système d'exploitation.


*   Les autres noms et marques pourraient avoir des 
    propriétaires différents.
**  Si le système possède une version Windows 64 bits,
    le pilote de la Technologie de stockage Intel (R)
    Rapid prenant en charge 64 bits doit être utilisé.


************************************************************
* 3.  LANGUES PRISES EN CHARGE
************************************************************

Vous trouverez ci-dessous la liste des langues (et leur 
abréviation) disponibles pour le logiciel Technologie de 
stockage Intel(R) Rapid. Le code de langue est affiché entre 
parenthèses après chaque langue.

ARA : Arabe (Arabie saoudite)   (0401)
CHS : Chinois (simplifié)       (0804)
CHT : Chinois (traditionnel)    (0404)
CSY : Tchèque                   (0405)
DAN : Danois                    (0406)
NLD : Néerlandais               (0413)
ENU : Anglais (États-Unis)      (0409)
FIN : Finnois                   (040B)
FRA : Français (international)  (040C)
DEU : Allemand                  (0407)
ELL : Grec                      (0408)
HEB : Hébreu                    (040D)
HUN : Hongrois                  (040E)
ITA : Italien                   (0410)
JPN : Japonais                  (0411)
KOR : Coréen                    (0412)
NOR : Norvégien                 (0414)
PLK : Polonais                  (0415)
PTB : Portugais (Brésil)        (0416)
PTG : Portugais (standard)      (0816)
RUS : Russe                     (0419)
ESP : Espagnol                  (040A)
SVE : Suédois                   (041D)
THA : Thaï                      (041E)
TRK : Turc                      (041F)


************************************************************
* 4.  DÉTERMINATION DU MODE SYSTÈME
************************************************************

Pour utiliser ce fichier Readme efficacement, vous devez
déterminer le mode de votre système. Le moyen le plus facile
de déterminer le mode consiste à identifier la façon dont le
contrôleur Intel(R) SATA est présenté dans le Gestionnaire 
de périphériques. La procédure suivante vous guidera pas à 
pas afin de déterminer le mode.

Sous Microsoft Windows* 7 ou plus récent :

1.  Dans le menu Démarrer, sélectionnez le Panneau de 
    configuration.

2.  Double-cliquez sur « Système » (Vous devrez peut-être 
    d'abord sélectionner Petites icônes ou Grandes icônes 
    dans le menu Afficher par dans le coin supérieur droit 
    de la fenêtre.)

3.  Sélectionnez l'option « Gestionnaire de périphériques » 
    dans le menu à gauche.

4.  Dans le Gestionnaire de périphériques, recherchez une 
    entrée intitulée « Contrôleurs de stockage ». Si cette 
    entrée existe, développez-la et recherchez un des 
    contrôleurs figurant dans la présentation (section 1). 
    Si le contrôleur identifié est un contrôleur Intel(R) 
    SATA RAID, alors le système est en mode RAID et utilise 
    un contrôleur Intel(R) SATA RAID.

5.  Si aucun des contrôleurs ci-dessus n'est affiché,
    le système n'est pas en mode RAID et vous devez
    passer à l'étape 6 ci-dessous.

6.  Dans le Gestionnaire de périphériques, recherchez une
    entrée « Contrôleurs IDE ATA/ATAPI ». Si cette entrée  
    existe, développez-la et recherchez un des contrôleurs
    figurant dans la présentation (section 1). Si un
    contrôleur Intel(R) SATA AHCI est identifié, alors le 
    système est en mode AHCI et utilise un contrôleur 
    Intel(R) AHCI.
    Si aucun des contrôleurs ci-dessus n'est affiché,
    le système n'est pas en mode AHCI. Aucun autre mode
    n'est pris en charge par la Technologie de stockage 
    Intel(R) Rapid et vous devez passer à l'étape 7 
    ci-dessous.

7.  Votre système ne semble pas fonctionner en mode RAID
    ou AHCI, ou ne possède pas de contrôleurs Intel(R) SATA
    pris en charge. Si vous pensez que votre système 
    fonctionne en mode RAID ou AHCI et qu'aucun des 
    contrôleurs ci-dessus n'est présent, contactez le 
    fabricant de votre système ou le lieu d'achat pour 
    obtenir de l'assistance.


************************************************************
* 5.  INSTALLATION DU LOGICIEL
************************************************************

5.1 Notes d'installation

1.  Si vous installez le système d'exploitation sur un 
    système configuré en mode RAID ou AHCI, vous pouvez 
    préinstaller le pilote de la Technologie de stockage 
    Intel(R) Rapid en utilisant la méthode d'installation
    « Charger un pilote » décrite dans la section 5.3.

2.  Pour installer la Technologie de stockage Intel Rapid,
    cliquez sur le fichier d'installation auto-extractible 
    et à installation automatique et suivez les invites qui 
    s'affichent.

3.  Par défaut, tous les fichiers installés (readme.txt, 
    aide, etc.) sont copiés à l'emplacement suivant 
    (où C:\ représente le chemin d’accès de démarrage) : 
    
    32 bits : C:\Program Files\Intel\Intel(R) Rapid Storage 
             Technology

    64 bits : C:\Programmes\Intel\Intel(R) Rapid 
             Storage Technology


4.  L'« Utilitaire d'installation du logiciel pour les jeux de 
    composants Intel(R) » devrait être installé sur le système 
    après avoir installé un système d'exploitation Microsoft 
    Windows* pris en charge.


5.2 Installation « Microsoft Windows* Automated Installer » à 
    partir du disque dur ou du CD-ROM
    
REMARQUE : Cette méthode s'applique aux systèmes 
           configurés pour le mode RAID ou AHCI.

1.  Téléchargez le fichier d'installation de la Technologie 
    de stockage Intel(R) Rapid et double-cliquez sur ce fichier
    pour extraire automatiquement les fichiers et lancer le
    processus d'installation (exemple du nom de fichier : 
    SetupRST.exe).

2.  La fenêtre de bienvenue s'affiche. Cliquez sur 
    « Suivant » pour continuer.

3.  Pour les systèmes fonctionnant en mode RAID, une fenêtre 
    d'avertissement s'affiche. Vous ne pourrez pas désinstaller 
    le pilote dans ce mode. Cliquez sur « Suivant » pour continuer.

4.  La fenêtre de l'Accord de licence du logiciel s'affiche. 
    Si vous acceptez les termes de cet accord, cochez la case 
    puis cliquez sur « Oui » pour continuer.

5.  La fenêtre d'information sur le fichier lisez-moi
    s'affiche. Révisez son contenu puis cliquez sur 
    « Suivant » pour continuer.

6.  La fenêtre de sélection de destination du dossier 
    s'affiche. Tapez l'emplacement choisi pour les fichiers 
    d'installation ou choisissez l'emplacement par defaut. 
    Cliquez sur « Suivant » pour continuer.

7.  La fenêtre de confirmation s'affiche. À ce stade de 
    l'installation, la copie des fichiers est sur le point 
    de s'éffectuer. Cliquez sur « Suivant » pour continuer à 
    installer le pilote ainsi que les autres composants du 
    logiciel.

8.  Si la fenêtre indiquant que l'assistant « Microsoft Windows* 
    Automated Installer » est terminé s'affiche sans vous inviter 
    à redémarrer le système, cliquez sur « Terminer » et passez à 
    l'étape 9. Si une invite vous demande de redémarrer le 
    système, sélectionnez « Oui, je veux redémarrer mon 
    ordinateur maintenant » (sélection par défaut) et cliquez 
    sur « Terminer ». Après le redémarrage du système, passez à 
    l'étape 9.

9.  Pour vérifier si le pilote est correctement chargé,
    reportez-vous à la section 6.


5.3 Préinstallation en utilisant la méthode « Charger un pilote » 

1.  Extrayez tous les fichiers de pilote de l'archive ZIP. 

2.  Sélectionnez un périphérique USB et copiez les fichiers 
    extraits sur celui-ci :

    AHCIC.inf
    AHCIC.cat
    iaStorAC.inf
    iaStorAC.cat 
    iaStorA.sys
    iaStorF.sys

3.  Pour les systèmes d'exploitation Microsoft Windows* :

    Pendant l'installation du système d'exploitation, après 
    avoir sélectionné l'emplacement où vous souhaitez 
    installer Windows*, cliquez sur « Charger un pilote » afin 
    d'installer un pilote SCSI ou RAID tiers.

4.  À l'invite, insérez le périphérique USB et appuyez sur 
    « Entrée ».

5.  Suivez les invites et naviguez vers l'emplacement des fichiers 
    d'installation. Sélectionnez le fichier .inf approprié 
    (64 ou 32 bits). Si un contrôleur pris en charge est détecté, 
    il n'y aura pas de messages d'erreur. Suivez les invites 
    pour continuer et complétez l'installation du système 
    d'exploitation.


************************************************************
* 6.  VÉRIFICATION DE L'INSTALLATION DU LOGICIEL
************************************************************

6.1 Vérification des installations Disque fourni, « Charger 
    un pilote » ou Sans assistance. En fonction de la 
    configuration de votre système, reportez-vous à la 
    sous-rubrique appropriée ci-dessous :


6.1a Systèmes configurés pour le mode RAID :

1.  Accédez au Gestionnaire de périphériques après avoir 
    ouvert une session Windows.
2.  Développez l'entrée intitulée « Contrôleurs de stockage » 
    (pour Microsoft Windows* 7 ou plus récent). 
3.  Cliquez avec le bouton droit sur « Intel(R) SATA 
    RAID Controller ».
4.  Sélectionnez « Propriétés ».
5.  Sélectionnez l'onglet « Pilote ».
6.  Cliquez sur le bouton « Détails du pilote ».
7.  Si le fichier « iaStorA.sys » est affiché, l'installation
    est réussie.


6.1b Systèmes configurés pour le mode AHCI :

Sous Microsoft Windows* 7 ou plus récent :

1.  Accédez au Gestionnaire de périphériques après avoir 
    ouvert une session Windows.
2.  Développez l'entrée intitulée « Contrôleurs IDE ATA/ATAPI ». 
3.  Cliquez avec le bouton droit sur « Intel(R) SATA AHCI 
    Controller ».
4.  Sélectionnez « Propriétés ».
5.  Sélectionnez l'onglet « Pilote ».
6.  Cliquez sur « Détails du pilote ».
7.  Si le fichier « iaStorA.sys » est affiché, l'installation
    est réussie.


6.2 Vérification des installations « Microsoft Windows* 
    Automated Installer » ou « Package pour le Web » :

1.  Cliquez sur Démarrer.
2.  Sélectionnez l'entrée « Technologie de stockage 
    Intel(R) Rapid ».
3.  L'application « Technologie de stockage Intel Rapid » 
    devrait démarrer.
4.  Si l'application ne démarre pas, le pilote de la 
    Technologie de stockage Intel(R) Rapid n'est pas installé
    correctement et le programme d'installation doit être 
    réexécuté. 


************************************************************
* 7.  INSTRUCTIONS D'INSTALLATION AVANCÉES
************************************************************

7.1 Indicateurs d'installation disponibles :

    -?             Le programme d'installation affiche une
                   boîte de dialogue contenant tous les 
                   indicateurs d'installation pris en charge 
                   (affichés ici) ainsi que leur utilisation, 
                   et quitte le programme sans installer 
                   l'application.
    -A             Extrait les fichiers du pilote et le 
                   fichier Readme (n'installe pas le pilote) 
                   sous <chemin> si -P est également fourni ; 
                   sinon, les fichiers sont extraits vers 
                   l'emplacement par défaut. 
    -B             Le programme d'installation redémarre 
                   automatiquement le système sans invite 
                   utilisateur dès que l'installation est 
                   terminée. Cette option est uniquement 
                   applicable avec l'indicateur -S.
    -L <LCID>      Force l'installation d'une langue 
                   particulière (voir la section 3 pour la 
                   table de correspondance des <LCID> et 
                   des langues).
    -Noicc         N'installe pas le Centre de contrôle 
                   Intel (R).
    -Nodrv         N'installe pas le pilote de la Technologie 
                   de stockage Intel(R) Rapid.
    -NoIRSTGUI     Ne crée pas de raccourci pour la console 
                   de l'interface utilisateur dans le menu 
                   Démarrer. Cet indicateur désactive 
                   également l'installation du Centre de 
                   contrôle Intel(R). Cette application n'est 
                   pas supprimée si elle est déjà installée. 
    -Noservice     N'installe pas le service de moniteur des 
                   événements. Cela signifie que les 
                   composants de l'interface utilisateur ne 
                   sont donc pas installés non plus.
    -Notray        Bloque le lancement de l'applet du moniteur 
                   à chaque redémarrage.
    -Overwrite     Le programme d'installation exécute la 
                   mise à niveau vers une version antérieure 
                   sans interaction de l'utilisateur.
    -P <chemin>    Modifie l'emplacement du répertoire par 
                   défaut pour les fichiers de l'application 
                   et fournit le chemin cible lorsque 
                   l'indicateur -A est utilisé.
    -report <chemin> Change le chemin d'accès par défaut du 
                     fichier journal.
    -S             Installation silencieuse (aucune invite 
                   utilisateur ou affichage de l'interface 
                   utilisateur de la Technologie de stockage 
                   Intel Rapid). Si cet indicateur est utilisé 
                   avec l'indicateur –B, le programme 
                   d'installation redémarre automatiquement 
                   le système.
    -ver           Affiche les versions des pilotes.


REMARQUE :  Les indicateurs et leurs paramètres respectent 
            la casse.
            Les indicateurs peuvent être entrés dans n'importe 
            quel ordre, à l'exception de -S et -L qui doivent 
            être entrés en dernier. Si vous utilisez 
            l'indicateur -A, un chemin cible peut être 
            spécifié via l'indicateur -P, et les indicateurs 
            -L, -S et -N sont ignorés. Lorsque vous utilisez 
            l'indicateur -P, un espace est exigé entre 
            l'indicateur et l'argument. 


7.2 Utilisez l'exemple de commande suivant pour extraire 
    les fichiers de pilote du logiciel :

      c:\SetupRST.exe -a -p c:\<chemin>

    L'exécution de ces commandes lance l'installation et 
    une invite s'affiche pour confirmer l'extraction des 
    fichiers. Cette opération n'installe pas le pilote ; 
    elle ne fait qu'extraire les fichiers du pilote dans 
    le <chemin>. Lorsque l'extraction est terminée, les 
    fichiers du pilote sont disponibles sous 
    <chemin>\Driver (pilote).


************************************************************
* 8.  IDENTIFICATION DU NUMÉRO DE VERSION DU LOGICIEL
************************************************************

8.1 Suivez les étapes ci-dessous pour identifier le numéro 
    de version du logiciel à la suite d'une installation 
    Disque fourni, « Charger un pilote » ou Sans 
    assistance.


8.1a Systèmes configurés pour le mode RAID :

1.  Accédez au « Gestionnaire de périphériques ».
2.  Développez l'entrée intitulée « Contrôleurs de stockage ». 
3.  Cliquez avec le bouton droit sur le contrôleur 
    Intel(R) RAID présent.
4.  Sélectionnez « Propriétés ».
5.  Sélectionnez l'onglet « Pilote ».
6.  La version du logiciel devrait être affichée après
    « Version du pilote : ».


8.1b Systèmes configurés pour le mode AHCI :

1.  Accédez au « Gestionnaire de périphériques ».
2.  Développez l'entrée intitulée « Contrôleurs IDE ATA/ATAPI ».
5.  Cliquez avec le bouton droit sur le contrôleur Intel(R) 
    AHCI présent.
6.  Sélectionnez « Propriétés ».
7.  Sélectionnez l'onglet « Pilote ».
8.  La version du logiciel devrait être affichée après
    « Version du pilote : ».


8.2 Identifiez la version du logiciel pour les installations
    « Microsoft Windows* Automated Installer » ou « Package 
    pour le Web » :

1.  Cliquez sur Démarrer.
2.  Recherchez  et sélectionnez l'élément « Technologie de 
    stockage Intel(R) Rapid ».
3.  L'application « Technologie de stockage Intel 
    Rapid » devrait démarrer.
4.  Cliquez sur « Aide ». La fenêtre de l'aide devrait s'ouvrir.
5.  À partir de la fenêtre de l'aide, cliquez sur « À propos de ». 
    La version du logiciel s'affiche.


************************************************************
* 9.  DÉSINSTALLATION DU LOGICIEL
************************************************************

9a. DÉSINSTALLATION DES COMPOSANTS NON-PILOTE

Si vous supprimez ce logiciel du système, tous les disques 
SATA seront inaccessibles au système d'exploitation. 
Par conséquent, la désinstallation sera seulement pour 
les composants moins essentiels de ce logiciel 
(l'interface utilisateur, liens dans le menu Démarrer, etc.). 
Pour désinstaller les composants essentiels, reportez-vous 
à la section 9b. 

Utilisez la procédure suivante pour désinstaller le logiciel :

1. Dans le menu Démarrer, sélectionnez le Panneau de 
   configuration.
2. Cliquez sur « Désinstaller un programme » pour 
   Windows* 7 ou plus récent (avec Afficher par : Catégorie).
3. Recherchez  et sélectionnez « Technologie de stockage 
   Intel(R) Rapid ».
4. Cliquez avec le bouton droit sur le nom de l'application 
   et sélectionnez « Désinstaller ».
5. Le programme de désinstallation démarrera. Cliquez sur 
   les options appropriées pour la désinstallation.

9b. DÉSINSTALLATION DES COMPOSANTS PILOTE

Si vous supprimez ce logiciel du système, tous les disques 
SATA risquent d'être inaccessibles au système d'exploitation.
Par conséquent, il est conseillé de faire une copie de 
sauvegarde de vos données avant d'exécuter cette étape.
 
1. Si le système se trouve en mode RAID, supprimez les 
   volumes RAID à l'aide de l'interface utilisateur 
   pré-système d'exploitation de la Technologie de stockage 
   Intel(R) Rapid (soit l'interface utilisateur UEFI soit 
   celle de la ROM Optionnelle).
2. Redémarrez le système.
 
REMARQUE : si vous éprouvez des difficultés à modifier le 
BIOS du système, contactez le fabriquant de votre plateforme 
ou le lieu d'achat de votre système pour obtenir de l'aide.

 
************************************************************
* 10.  ACCÉDER À L'INTERFACE UTILISATEUR PRÉ-SYSTÈME 
       D'EXPLOITATION
************************************************************

10a. INTERFACE UTILISATEUR DE LA ROM OPTIONNELLE HÉRITÉE

Suivez les étapes ci-dessous pour ouvrir l'interface 
utilisateur de la ROM Optionnelle héritée de la Technologie 
de stockage Intel(R) Rapid :

1. Démarrez le système.
2. Appuyez sur CTRL+I lorsque l'écran d'état
   « Intel(R) Rapid Storage Technology-option ROM vX.y.w.zzzz »
   s'affiche.


10b. PILOTE UEFI ou BIOS

Suivez les étapes ci-dessous pour ouvrir l'interface 
utilisateur UEFI-HII conforme. (Remarque : les étapes 
à suivre ainsi que l'emplacement de l'interface utilisateur 
varient en fonction de la plateforme. Contactez le fabriquant 
de votre plateforme pour obtenir ces étapes et l'emplacement 
de l'interface utilisateur UEFI de la Technologie de stockage 
Intel(R) Rapid.) 

1. Démarrez le système.
2. Appuyez sur la touche requise pour accéder au système BIOS 
   de la plateforme (p.ex. F2).
3. Naviguez vers l'interface utilisateur de la Technologie 
   de stockage Intel(R) Rapid. La version est indiquée en 
   haut de la page principale de l'interface utilisateur 
   dans le format qui suit : 
   « Intel(R) RST ww.x.y.zzzz SATA Driver ».


************************************************************
* 11.  GESTION DES VOLUMES RAID PRÉ-SYSTÈME D'EXPLOITATION
************************************************************

11a. ROM OPTIONNELLE HÉRITÉE

L'interface utilisateur de la ROM Optionnelle de la 
Technologie de stockage Intel(R) Rapid permet de gérer les 
volumes RAID pré-système d'exploitation. Elle offre les 
options de gestion des volumes RAID suivantes :

1. « Create RAID Volume » (Créer un volume RAID).
   Utilisez cette option pour créer un ou deux volumes RAID. 

2. « Delete RAID Volume » (Supprimer un volume RAID).
   Utilisez cette option pour supprimer un volume RAID.

3. « Reset Disks to Non-RAID » (Réinitialiser les disques 
   durs sur Non RAID).
   Utilisez cette option pour réinitialiser une
   configuration RAID avec une configuration non RAID.

4. « Recovery Volume Options » (Options du volume de reprise).
   Si le système comporte un volume de reprise, utilisez 
   cette option pour :
     a. « Disable Continuous Update » (Désactiver la mise 
        à jour continue).
     b. « Enable Only Recovery Disk » (Activer uniquement 
        un disque de reprise).
     c. « Enable Only Master Disk » (Activer uniquement un 
        disque maître).

11b. PILOTE UEFI ou BIOS

L'interface utilisateur UEFI de la Technologie de stockage 
Intel(R) Rapid permet de gérer les volumes RAID pré-système 
d'exploitation. Elle offre les options de gestion des 
volumes RAID suivantes :

1. « Create RAID Volume » (Créer un volume RAID).
   Utilisez cette option pour créer un ou deux volumes RAID. 

2. « Delete » (Supprimer).
   Utilisez cette option pour supprimer un volume RAID.

3. « Reset Disks to Non-RAID » (Réinitialiser les disques 
   durs sur Non RAID).
   Cliquez sur un disque faisant partie du volume RAID 
   puis utilisez cette option pour réinitialiser le disque 
   RAID à l'état pass-through Non RAID.

4. « Recovery Volume Options » (Options du volume de reprise).
   Si le système comporte un volume de reprise, utilisez 
   cette option pour :
     a. « Disable Continuous Update » (Désactiver la mise 
        à jour continue).
     b. « Enable Only Recovery Disk » (Activer uniquement 
        un disque de reprise).
     c. « Enable Only Master Disk » (Activer uniquement un 
        disque maître).


***************************************************************
* 12.  OPTIONS DE RÉINITIALISATION DU VOLUME RAID DANS 
*      L'INTERFACE UTILISATEUR PRÉ-SYSTÈME D'EXPLOITATION
***************************************************************

L'interface utilisateur pré-système d'exploitation de la 
Technologie de stockage Intel(R) Rapid propose deux méthodes 
pour réinitialiser les volumes RAID :

1. « Delete RAID Volume » (Supprimer le volume RAID).
2. « Reset Disks to Non-RAID » (Réinitialiser les disques sur 
   Non RAID).
   Les différences entre les options sont notées ci-dessous. 
   Les utilisateurs sont conseillés de choisir l'option en
   fonction de la situation.

12.1 Suppression d'un volume RAID

     Quand un volume RAID est supprimé, les métadonnées sur le 
     disque sont effacées et le secteur zéro est supprimé ; ce 
     qui signifie que les données de la table de partition et 
     du système de fichiers sont effacées. L'installateur de 
     Windows ne trouvera aucune donnée inadmissible pendant 
     l'installation du système d'exploitation. C'est la méthode 
     recommandée pour modifier le volume RAID et installer le 
     système d'exploitation.

12.2 Réinitialisation du disque sur Non RAID

     Cette option est utilisée pour réinitialiser les 
     métadonnées sur le disque appartenant à plus d'un 
     volume RAID, ceci en une seule action. Utilisez cette 
     option si « Effacer le volume RAID » échoue pour une 
     raison ou une autre et pour réinitialiser un disque qui 
     a été marqué comme disque de réserve et hors-ligne.
     Quand un disque d'un volume RAID est réinitialisé 
     comme non-RAID, les métadonnées RAID sont effacées. 
     Cependant, les données de la table de partition et du 
     système de fichiers existent toujours, ce qui peut être 
     inadmissible. L'installateur de Windows pourrait mal 
     interpréter l'information disponible sur le « disque 
     de réinstallation » au moment de l'installation. 
     Ceci peut avoir comme conséquence un comportement 
     inattendu durant l'installation du système d'exploitation.


************************************************************
* 13.  VÉRIFICATION DE LA VERSION DU LOGICIEL DE LA ROM 
*      OPTIONNELLE ET DU PILOTE UEFI PRÉ-SYSTÈME 
*      D'EXPLOITATION
************************************************************

Suivez les étapes ci-dessous pour identifier le numéro de 
version du pilote UEFI ou de la ROM Optionnelle héritée  
de la Technologie de stockage Intel(R) Rapid :

1. Ouvrez l'interface utilisateur UEFI ou celle de la ROM 
   Optionnelle de la Technologie de stockage Intel(R) Rapid 
   en suivant les étapes décrites dans la section 10.
2. La version du logiciel sera affichée dans la bannière 
   de l'interface utilisateur :
   « Intel(R) Rapid Storage Technology-option ROM X.y.w.zzzz ».

   « X.y.w.zzzz » - correspond au numéro de version de 
   l'interface utilisateur de la ROM Optionnelle installée 
   sur votre système :
   « X.y.w » - Numéro de lancement du produit.
   « X » - Numéro majeur.
   « y » - Numéro mineur.
   « w » - Numéro de correctif logiciel.
   « zzzz » - Numéro de compilation.


************************************************************
* AVIS JURIDIQUE
************************************************************

LES INFORMATIONS CONTENUES DANS CE DOCUMENT CONCERNENT LES 
PRODUITS INTEL. CE DOCUMENT N'ACCORDE AUCUNE LICENCE, 
EXPRESSE OU IMPLICITE, PAR PRÉCLUSION OU AUTRE, À DES DROITS 
DE PROPRIÉTÉ INTELLECTUELLE. À L'EXCEPTION DES AUTORISATIONS
ACCORDÉES SELON LES TERMES ET CONDITIONS D'INTEL POUR DES 
PRODUITS PARTICULIERS, INTEL DÉCLINE TOUTE RESPONSABILITÉ ET 
GARANTIE EXPRESSE OU IMPLICITE LIÉE À LA VENTE ET/OU À 
L'UTILISATION DES PRODUITS INTEL Y COMPRIS LES OBLIGATIONS 
OU LES GARANTIES ASSOCIÉES À L'ADAPTATION À UNE UTILISATION 
PARTICULIÈRE, LA COMMERCIALISATION OU LA CONTREFAÇON DE 
BREVET, DE COPYRIGHT OU D'AUTRES DROITS DE PROPRIÉTÉ 
INTELLECTUELLE.

SAUF ACCORD ÉCRIT D'INTEL, LES PRODUITS INTEL NE SONT PAS
CONÇUS NI PRÉVUS POUR DES APPLICATIONS DANS LESQUELLES UNE 
DÉFAILLANCE DU PRODUIT INTEL POURRAIT CRÉER UN SITUATION 
POUVANT ENTRAÎNER DES BLESSURES OU LA MORT.

Intel se réserve le droit de modifier les spécifications et 
descriptions de produit à tout moment et sans préavis. 
Les concepteurs ne doivent pas s'appuyer sur des 
caractéristiques de fonctionnalités ou leur absence, ou 
sur des instructions marquées « réservé » ou « non défini ». 
Intel les réserve pour une définition à venir et n'assume
aucune responsabilité pour les conflits ou incompatibilités 
survenant après que des modifications leur seront apportées 
à l'avenir. Les informations contenues dans la présente 
sont sujettes à modifications sans préavis. Ne finalisez 
pas un design sans ces informations.

Les produits décrits dans ce document peuvent contenir des 
défauts ou erreurs ; dans ce cas, le produit n'est pas 
conforme aux spécifications publiées. Une description des 
erreurs et défauts est disponible sur demande.

Contactez le bureau de vente Intel local ou votre distributeur 
pour obtenir les dernières spécifications et avant de passer 
votre commande de produit.

Des copies des documents qui possèdent un numéro de commande 
et sont référencés dans ce document, ou d'autres documents 
Intel, peuvent être obtenues en contactant votre vendeur ou 
distributeur, ou en visitant : http://www.intel.com/#/en_us_01

Intel(R) est une marque de commerce d'Intel Corporation aux 
États-Unis et dans d'autres pays.

* D'autres noms et marques peuvent être revendiquées en tant 
que propriété de tiers.


Copyright (c) Intel Corporation. Tous droits 
réservés.

***************************************************************
* CONTRAT DE LICENCE LOGICIELLE INTEL(R)
***************************************************************

