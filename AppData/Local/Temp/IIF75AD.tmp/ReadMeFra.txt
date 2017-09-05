************************************************************
************************************************************
* Fichier Readme/Lisez-moi pour l'installation de la 
* Technologie de stockage Intel(R) Rapid.
*
* Reportez-vous � la configuration requise pour une liste
* des syst�mes d'exploitation pris en charge par la  
* Technologie de stockage Intel Rapid.
*
* Ce document contient des r�f�rences � des produits
* d�velopp�s par Intel. Certaines restrictions
* d'utilisation de ces produits existent, de m�me que des
* restrictions de divulgation des informations � des tiers. 
* Veuillez lire la section Avis de non-responsabilit� au
* bas de ce document et contactez votre repr�sentant Intel
* si vous souhaitez obtenir des informations suppl�mentaires.
*
************************************************************
************************************************************

************************************************************
* Intel n'�met aucune d�claration de facilit� d'utilisation, 
* d'efficacit� ou de garantie. Le CONTRAT DE LICENCE DU 
* LOGICIEL INTEL contenu dans ce document d�finit, de fa�on 
* compl�te, la licence et l'utilisation de ce logiciel.
************************************************************


************************************************************
* CONTENU DE CE DOCUMENT
************************************************************

Ce document contient les sections suivantes :

1.  Pr�sentation
2.  Configuration requise
3.  Langues prises en charge
4.  D�termination du mode syst�me
5.  Installation du logiciel
6.  V�rification de l'installation du logiciel
7.  Instructions d'installation avanc�es
8.  Identification du num�ro de version du logiciel
9.  D�sinstallation du logiciel
10. Acc�der � l'interface utilisateur pr�-syst�me 
    d'exploitation
11. Gestion des volumes RAID pr�-syst�me d'exploitation
12. Options de r�initialisation du volume RAID dans 
    l'interface utilisateur pr�-syst�me d'exploitation
13. V�rification de la version du logiciel de la ROM 
    Optionnelle et du pilote UEFI pr�-syst�me 
    d'exploitation
Avis juridique
Contrat de license logicielle Intel(R)


************************************************************
* 1.  PR�SENTATION
************************************************************

La Technologie de stockage Intel(R) Rapid est con�ue pour 
fournir une fonctionnalit� aux contr�leurs de stockage 
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

1.  Le syst�me doit contenir un des contr�leurs Intel 
    compris dans la section 1 ci-dessus ainsi qu'un des 
    processeurs suivants** :   
    - Intel(R) vPro
    - Intel(R) Celeron
    - Intel(R) Pentium
    - Intel(R) Core(TM) i3, i5, ou i7
    - Famille de processeurs Intel(R) Xeon(R)

** Remarque : certaines caract�ristiques de la Technologie de 
   stockage Intel(R) Rapid ne sont activ�es qu'en fonction du 
   processeur pr�sent dans le syst�me.


2.  Le syst�me doit poss�der un des syst�mes d'exploitation
    suivants (aucune autre version de syst�mes 
    d'exploitation Windows n'est prise en charge) :

    - Microsoft Windows* 10
    - Microsoft Windows* 10 �dition 64 bits**
    - Microsoft Windows* 8.1
    - Microsoft Windows* 8.1 �dition 64 bits** 
    - Microsoft Windows* 8
    - Microsoft Windows* 8 �dition 64 bits**  
    - Microsoft Windows* 7
    - Microsoft Windows* 7 �dition 64 bits** 
    - Microsoft Windows* Server 2008 R2 �dition 64 bits**
    - Microsoft Windows* Server 2012 �dition 64 bits**	
    - Microsoft Windows* Server 2012 R2 �dition 64 bits**
    - Microsoft Windows* MultiPoint Server 2011 �dition 64 bits**


3.  Les syst�mes d'exploitation suivants ne sont pas pris 
    en charge :

    Toute version des syst�mes d'exploitation suivants :
    - Linux*
    - UNIX*
    - BeOS*
    - MacOS*
    - OS/2*


4.  Le syst�me doit contenir au minimum la m�moire syst�me
    minimale requise par le syst�me d'exploitation.


*   Les autres noms et marques pourraient avoir des 
    propri�taires diff�rents.
**  Si le syst�me poss�de une version Windows 64 bits,
    le pilote de la Technologie de stockage Intel (R)
    Rapid prenant en charge 64 bits doit �tre utilis�.


************************************************************
* 3.  LANGUES PRISES EN CHARGE
************************************************************

Vous trouverez ci-dessous la liste des langues (et leur 
abr�viation) disponibles pour le logiciel Technologie de 
stockage Intel(R) Rapid. Le code de langue est affich� entre 
parenth�ses apr�s chaque langue.

ARA : Arabe (Arabie saoudite)   (0401)
CHS : Chinois (simplifi�)       (0804)
CHT : Chinois (traditionnel)    (0404)
CSY : Tch�que                   (0405)
DAN : Danois                    (0406)
NLD : N�erlandais               (0413)
ENU : Anglais (�tats-Unis)      (0409)
FIN : Finnois                   (040B)
FRA : Fran�ais (international)  (040C)
DEU : Allemand                  (0407)
ELL : Grec                      (0408)
HEB : H�breu                    (040D)
HUN : Hongrois                  (040E)
ITA : Italien                   (0410)
JPN : Japonais                  (0411)
KOR : Cor�en                    (0412)
NOR : Norv�gien                 (0414)
PLK : Polonais                  (0415)
PTB : Portugais (Br�sil)        (0416)
PTG : Portugais (standard)      (0816)
RUS : Russe                     (0419)
ESP : Espagnol                  (040A)
SVE : Su�dois                   (041D)
THA : Tha�                      (041E)
TRK : Turc                      (041F)


************************************************************
* 4.  D�TERMINATION DU MODE SYST�ME
************************************************************

Pour utiliser ce fichier Readme efficacement, vous devez
d�terminer le mode de votre syst�me. Le moyen le plus facile
de d�terminer le mode consiste � identifier la fa�on dont le
contr�leur Intel(R) SATA est pr�sent� dans le Gestionnaire 
de p�riph�riques. La proc�dure suivante vous guidera pas � 
pas afin de d�terminer le mode.

Sous Microsoft Windows* 7 ou plus r�cent :

1.  Dans le menu D�marrer, s�lectionnez le Panneau de 
    configuration.

2.  Double-cliquez sur � Syst�me � (Vous devrez peut-�tre 
    d'abord s�lectionner Petites ic�nes ou Grandes ic�nes 
    dans le menu Afficher par dans le coin sup�rieur droit 
    de la fen�tre.)

3.  S�lectionnez l'option � Gestionnaire de p�riph�riques � 
    dans le menu � gauche.

4.  Dans le Gestionnaire de p�riph�riques, recherchez une 
    entr�e intitul�e � Contr�leurs de stockage �. Si cette 
    entr�e existe, d�veloppez-la et recherchez un des 
    contr�leurs figurant dans la pr�sentation (section 1). 
    Si le contr�leur identifi� est un contr�leur Intel(R) 
    SATA RAID, alors le syst�me est en mode RAID et utilise 
    un contr�leur Intel(R) SATA RAID.

5.  Si aucun des contr�leurs ci-dessus n'est affich�,
    le syst�me n'est pas en mode RAID et vous devez
    passer � l'�tape 6 ci-dessous.

6.  Dans le Gestionnaire de p�riph�riques, recherchez une
    entr�e � Contr�leurs IDE ATA/ATAPI �. Si cette entr�e  
    existe, d�veloppez-la et recherchez un des contr�leurs
    figurant dans la pr�sentation (section 1). Si un
    contr�leur Intel(R) SATA AHCI est identifi�, alors le 
    syst�me est en mode AHCI et utilise un contr�leur 
    Intel(R) AHCI.
    Si aucun des contr�leurs ci-dessus n'est affich�,
    le syst�me n'est pas en mode AHCI. Aucun autre mode
    n'est pris en charge par la Technologie de stockage 
    Intel(R) Rapid et vous devez passer � l'�tape 7 
    ci-dessous.

7.  Votre syst�me ne semble pas fonctionner en mode RAID
    ou AHCI, ou ne poss�de pas de contr�leurs Intel(R) SATA
    pris en charge. Si vous pensez que votre syst�me 
    fonctionne en mode RAID ou AHCI et qu'aucun des 
    contr�leurs ci-dessus n'est pr�sent, contactez le 
    fabricant de votre syst�me ou le lieu d'achat pour 
    obtenir de l'assistance.


************************************************************
* 5.  INSTALLATION DU LOGICIEL
************************************************************

5.1 Notes d'installation

1.  Si vous installez le syst�me d'exploitation sur un 
    syst�me configur� en mode RAID ou AHCI, vous pouvez 
    pr�installer le pilote de la Technologie de stockage 
    Intel(R) Rapid en utilisant la m�thode d'installation
    � Charger un pilote � d�crite dans la section 5.3.

2.  Pour installer la Technologie de stockage Intel Rapid,
    cliquez sur le fichier d'installation auto-extractible 
    et � installation automatique et suivez les invites qui 
    s'affichent.

3.  Par d�faut, tous les fichiers install�s (readme.txt, 
    aide, etc.) sont copi�s � l'emplacement suivant 
    (o� C:\ repr�sente le chemin d�acc�s de d�marrage) : 
    
    32 bits : C:\Program Files\Intel\Intel(R) Rapid Storage 
             Technology

    64 bits : C:\Programmes\Intel\Intel(R) Rapid 
             Storage Technology


4.  L'� Utilitaire d'installation du logiciel pour les jeux de 
    composants Intel(R) � devrait �tre install� sur le syst�me 
    apr�s avoir install� un syst�me d'exploitation Microsoft 
    Windows* pris en charge.


5.2 Installation � Microsoft Windows* Automated Installer � � 
    partir du disque dur ou du CD-ROM
    
REMARQUE : Cette m�thode s'applique aux syst�mes 
           configur�s pour le mode RAID ou AHCI.

1.  T�l�chargez le fichier d'installation de la Technologie 
    de stockage Intel(R) Rapid et double-cliquez sur ce fichier
    pour extraire automatiquement les fichiers et lancer le
    processus d'installation (exemple du nom de fichier : 
    SetupRST.exe).

2.  La fen�tre de bienvenue s'affiche. Cliquez sur 
    � Suivant � pour continuer.

3.  Pour les syst�mes fonctionnant en mode RAID, une fen�tre 
    d'avertissement s'affiche. Vous ne pourrez pas d�sinstaller 
    le pilote dans ce mode. Cliquez sur � Suivant � pour continuer.

4.  La fen�tre de l'Accord de licence du logiciel s'affiche. 
    Si vous acceptez les termes de cet accord, cochez la case 
    puis cliquez sur � Oui � pour continuer.

5.  La fen�tre d'information sur le fichier lisez-moi
    s'affiche. R�visez son contenu puis cliquez sur 
    � Suivant � pour continuer.

6.  La fen�tre de s�lection de destination du dossier 
    s'affiche. Tapez l'emplacement choisi pour les fichiers 
    d'installation ou choisissez l'emplacement par defaut. 
    Cliquez sur � Suivant � pour continuer.

7.  La fen�tre de confirmation s'affiche. � ce stade de 
    l'installation, la copie des fichiers est sur le point 
    de s'�ffectuer. Cliquez sur � Suivant � pour continuer � 
    installer le pilote ainsi que les autres composants du 
    logiciel.

8.  Si la fen�tre indiquant que l'assistant � Microsoft Windows* 
    Automated Installer � est termin� s'affiche sans vous inviter 
    � red�marrer le syst�me, cliquez sur � Terminer � et passez � 
    l'�tape 9. Si une invite vous demande de red�marrer le 
    syst�me, s�lectionnez � Oui, je veux red�marrer mon 
    ordinateur maintenant � (s�lection par d�faut) et cliquez 
    sur � Terminer �. Apr�s le red�marrage du syst�me, passez � 
    l'�tape 9.

9.  Pour v�rifier si le pilote est correctement charg�,
    reportez-vous � la section 6.


5.3 Pr�installation en utilisant la m�thode � Charger un pilote � 

1.  Extrayez tous les fichiers de pilote de l'archive ZIP. 

2.  S�lectionnez un p�riph�rique USB et copiez les fichiers 
    extraits sur celui-ci :

    AHCIC.inf
    AHCIC.cat
    iaStorAC.inf
    iaStorAC.cat 
    iaStorA.sys
    iaStorF.sys

3.  Pour les syst�mes d'exploitation Microsoft Windows* :

    Pendant l'installation du syst�me d'exploitation, apr�s 
    avoir s�lectionn� l'emplacement o� vous souhaitez 
    installer Windows*, cliquez sur � Charger un pilote � afin 
    d'installer un pilote SCSI ou RAID tiers.

4.  � l'invite, ins�rez le p�riph�rique USB et appuyez sur 
    � Entr�e �.

5.  Suivez les invites et naviguez vers l'emplacement des fichiers 
    d'installation. S�lectionnez le fichier .inf appropri� 
    (64 ou 32 bits). Si un contr�leur pris en charge est d�tect�, 
    il n'y aura pas de messages d'erreur. Suivez les invites 
    pour continuer et compl�tez l'installation du syst�me 
    d'exploitation.


************************************************************
* 6.  V�RIFICATION DE L'INSTALLATION DU LOGICIEL
************************************************************

6.1 V�rification des installations Disque fourni, � Charger 
    un pilote � ou Sans assistance. En fonction de la 
    configuration de votre syst�me, reportez-vous � la 
    sous-rubrique appropri�e ci-dessous :


6.1a Syst�mes configur�s pour le mode RAID :

1.  Acc�dez au Gestionnaire de p�riph�riques apr�s avoir 
    ouvert une session Windows.
2.  D�veloppez l'entr�e intitul�e � Contr�leurs de stockage � 
    (pour Microsoft Windows* 7 ou plus r�cent). 
3.  Cliquez avec le bouton droit sur � Intel(R) SATA 
    RAID Controller �.
4.  S�lectionnez � Propri�t�s �.
5.  S�lectionnez l'onglet � Pilote �.
6.  Cliquez sur le bouton � D�tails du pilote �.
7.  Si le fichier � iaStorA.sys � est affich�, l'installation
    est r�ussie.


6.1b Syst�mes configur�s pour le mode AHCI :

Sous Microsoft Windows* 7 ou plus r�cent :

1.  Acc�dez au Gestionnaire de p�riph�riques apr�s avoir 
    ouvert une session Windows.
2.  D�veloppez l'entr�e intitul�e � Contr�leurs IDE ATA/ATAPI �. 
3.  Cliquez avec le bouton droit sur � Intel(R) SATA AHCI 
    Controller �.
4.  S�lectionnez � Propri�t�s �.
5.  S�lectionnez l'onglet � Pilote �.
6.  Cliquez sur � D�tails du pilote �.
7.  Si le fichier � iaStorA.sys � est affich�, l'installation
    est r�ussie.


6.2 V�rification des installations � Microsoft Windows* 
    Automated Installer � ou � Package pour le Web � :

1.  Cliquez sur D�marrer.
2.  S�lectionnez l'entr�e � Technologie de stockage 
    Intel(R) Rapid �.
3.  L'application � Technologie de stockage Intel Rapid � 
    devrait d�marrer.
4.  Si l'application ne d�marre pas, le pilote de la 
    Technologie de stockage Intel(R) Rapid n'est pas install�
    correctement et le programme d'installation doit �tre 
    r�ex�cut�. 


************************************************************
* 7.  INSTRUCTIONS D'INSTALLATION AVANC�ES
************************************************************

7.1 Indicateurs d'installation disponibles :

    -?             Le programme d'installation affiche une
                   bo�te de dialogue contenant tous les 
                   indicateurs d'installation pris en charge 
                   (affich�s ici) ainsi que leur utilisation, 
                   et quitte le programme sans installer 
                   l'application.
    -A             Extrait les fichiers du pilote et le 
                   fichier Readme (n'installe pas le pilote) 
                   sous <chemin> si -P est �galement fourni ; 
                   sinon, les fichiers sont extraits vers 
                   l'emplacement par d�faut. 
    -B             Le programme d'installation red�marre 
                   automatiquement le syst�me sans invite 
                   utilisateur d�s que l'installation est 
                   termin�e. Cette option est uniquement 
                   applicable avec l'indicateur -S.
    -L <LCID>      Force l'installation d'une langue 
                   particuli�re (voir la section 3 pour la 
                   table de correspondance des <LCID> et 
                   des langues).
    -Noicc         N'installe pas le Centre de contr�le 
                   Intel (R).
    -Nodrv         N'installe pas le pilote de la Technologie 
                   de stockage Intel(R) Rapid.
    -NoIRSTGUI     Ne cr�e pas de raccourci pour la console 
                   de l'interface utilisateur dans le menu 
                   D�marrer. Cet indicateur d�sactive 
                   �galement l'installation du Centre de 
                   contr�le Intel(R). Cette application n'est 
                   pas supprim�e si elle est d�j� install�e. 
    -Noservice     N'installe pas le service de moniteur des 
                   �v�nements. Cela signifie que les 
                   composants de l'interface utilisateur ne 
                   sont donc pas install�s non plus.
    -Notray        Bloque le lancement de l'applet du moniteur 
                   � chaque red�marrage.
    -Overwrite     Le programme d'installation ex�cute la 
                   mise � niveau vers une version ant�rieure 
                   sans interaction de l'utilisateur.
    -P <chemin>    Modifie l'emplacement du r�pertoire par 
                   d�faut pour les fichiers de l'application 
                   et fournit le chemin cible lorsque 
                   l'indicateur -A est utilis�.
    -report <chemin> Change le chemin d'acc�s par d�faut du 
                     fichier journal.
    -S             Installation silencieuse (aucune invite 
                   utilisateur ou affichage de l'interface 
                   utilisateur de la Technologie de stockage 
                   Intel Rapid). Si cet indicateur est utilis� 
                   avec l'indicateur �B, le programme 
                   d'installation red�marre automatiquement 
                   le syst�me.
    -ver           Affiche les versions des pilotes.


REMARQUE :  Les indicateurs et leurs param�tres respectent 
            la casse.
            Les indicateurs peuvent �tre entr�s dans n'importe 
            quel ordre, � l'exception de -S et -L qui doivent 
            �tre entr�s en dernier. Si vous utilisez 
            l'indicateur -A, un chemin cible peut �tre 
            sp�cifi� via l'indicateur -P, et les indicateurs 
            -L, -S et -N sont ignor�s. Lorsque vous utilisez 
            l'indicateur -P, un espace est exig� entre 
            l'indicateur et l'argument. 


7.2 Utilisez l'exemple de commande suivant pour extraire 
    les fichiers de pilote du logiciel :

      c:\SetupRST.exe -a -p c:\<chemin>

    L'ex�cution de ces commandes lance l'installation et 
    une invite s'affiche pour confirmer l'extraction des 
    fichiers. Cette op�ration n'installe pas le pilote ; 
    elle ne fait qu'extraire les fichiers du pilote dans 
    le <chemin>. Lorsque l'extraction est termin�e, les 
    fichiers du pilote sont disponibles sous 
    <chemin>\Driver (pilote).


************************************************************
* 8.  IDENTIFICATION DU NUM�RO DE VERSION DU LOGICIEL
************************************************************

8.1 Suivez les �tapes ci-dessous pour identifier le num�ro 
    de version du logiciel � la suite d'une installation 
    Disque fourni, � Charger un pilote � ou Sans 
    assistance.


8.1a Syst�mes configur�s pour le mode RAID :

1.  Acc�dez au � Gestionnaire de p�riph�riques �.
2.  D�veloppez l'entr�e intitul�e � Contr�leurs de stockage �. 
3.  Cliquez avec le bouton droit sur le contr�leur 
    Intel(R) RAID pr�sent.
4.  S�lectionnez � Propri�t�s �.
5.  S�lectionnez l'onglet � Pilote �.
6.  La version du logiciel devrait �tre affich�e apr�s
    � Version du pilote : �.


8.1b Syst�mes configur�s pour le mode AHCI :

1.  Acc�dez au � Gestionnaire de p�riph�riques �.
2.  D�veloppez l'entr�e intitul�e � Contr�leurs IDE ATA/ATAPI �.
5.  Cliquez avec le bouton droit sur le contr�leur Intel(R) 
    AHCI pr�sent.
6.  S�lectionnez � Propri�t�s �.
7.  S�lectionnez l'onglet � Pilote �.
8.  La version du logiciel devrait �tre affich�e apr�s
    � Version du pilote : �.


8.2 Identifiez la version du logiciel pour les installations
    � Microsoft Windows* Automated Installer � ou � Package 
    pour le Web � :

1.  Cliquez sur D�marrer.
2.  Recherchez  et s�lectionnez l'�l�ment � Technologie de 
    stockage Intel(R) Rapid �.
3.  L'application � Technologie de stockage Intel 
    Rapid � devrait d�marrer.
4.  Cliquez sur � Aide �. La fen�tre de l'aide devrait s'ouvrir.
5.  � partir de la fen�tre de l'aide, cliquez sur � � propos de �. 
    La version du logiciel s'affiche.


************************************************************
* 9.  D�SINSTALLATION DU LOGICIEL
************************************************************

9a. D�SINSTALLATION DES COMPOSANTS NON-PILOTE

Si vous supprimez ce logiciel du syst�me, tous les disques 
SATA seront inaccessibles au syst�me d'exploitation. 
Par cons�quent, la d�sinstallation sera seulement pour 
les composants moins essentiels de ce logiciel 
(l'interface utilisateur, liens dans le menu D�marrer, etc.). 
Pour d�sinstaller les composants essentiels, reportez-vous 
� la section 9b. 

Utilisez la proc�dure suivante pour d�sinstaller le logiciel :

1. Dans le menu D�marrer, s�lectionnez le Panneau de 
   configuration.
2. Cliquez sur � D�sinstaller un programme � pour 
   Windows* 7 ou plus r�cent (avec Afficher par : Cat�gorie).
3. Recherchez  et s�lectionnez � Technologie de stockage 
   Intel(R) Rapid �.
4. Cliquez avec le bouton droit sur le nom de l'application 
   et s�lectionnez � D�sinstaller �.
5. Le programme de d�sinstallation d�marrera. Cliquez sur 
   les options appropri�es pour la d�sinstallation.

9b. D�SINSTALLATION DES COMPOSANTS PILOTE

Si vous supprimez ce logiciel du syst�me, tous les disques 
SATA risquent d'�tre inaccessibles au syst�me d'exploitation.
Par cons�quent, il est conseill� de faire une copie de 
sauvegarde de vos donn�es avant d'ex�cuter cette �tape.
 
1. Si le syst�me se trouve en mode RAID, supprimez les 
   volumes RAID � l'aide de l'interface utilisateur 
   pr�-syst�me d'exploitation de la Technologie de stockage 
   Intel(R) Rapid (soit l'interface utilisateur UEFI soit 
   celle de la ROM Optionnelle).
2. Red�marrez le syst�me.
 
REMARQUE : si vous �prouvez des difficult�s � modifier le 
BIOS du syst�me, contactez le fabriquant de votre plateforme 
ou le lieu d'achat de votre syst�me pour obtenir de l'aide.

 
************************************************************
* 10.  ACC�DER � L'INTERFACE UTILISATEUR PR�-SYST�ME 
       D'EXPLOITATION
************************************************************

10a. INTERFACE UTILISATEUR DE LA ROM OPTIONNELLE H�RIT�E

Suivez les �tapes ci-dessous pour ouvrir l'interface 
utilisateur de la ROM Optionnelle h�rit�e de la Technologie 
de stockage Intel(R) Rapid :

1. D�marrez le syst�me.
2. Appuyez sur CTRL+I lorsque l'�cran d'�tat
   � Intel(R) Rapid Storage Technology-option ROM vX.y.w.zzzz �
   s'affiche.


10b. PILOTE UEFI ou BIOS

Suivez les �tapes ci-dessous pour ouvrir l'interface 
utilisateur UEFI-HII conforme. (Remarque : les �tapes 
� suivre ainsi que l'emplacement de l'interface utilisateur 
varient en fonction de la plateforme. Contactez le fabriquant 
de votre plateforme pour obtenir ces �tapes et l'emplacement 
de l'interface utilisateur UEFI de la Technologie de stockage 
Intel(R) Rapid.) 

1. D�marrez le syst�me.
2. Appuyez sur la touche requise pour acc�der au syst�me BIOS 
   de la plateforme (p.ex. F2).
3. Naviguez vers l'interface utilisateur de la Technologie 
   de stockage Intel(R) Rapid. La version est indiqu�e en 
   haut de la page principale de l'interface utilisateur 
   dans le format qui suit : 
   � Intel(R) RST ww.x.y.zzzz SATA Driver �.


************************************************************
* 11.  GESTION DES VOLUMES RAID PR�-SYST�ME D'EXPLOITATION
************************************************************

11a. ROM OPTIONNELLE H�RIT�E

L'interface utilisateur de la ROM Optionnelle de la 
Technologie de stockage Intel(R) Rapid permet de g�rer les 
volumes RAID pr�-syst�me d'exploitation. Elle offre les 
options de gestion des volumes RAID suivantes :

1. � Create RAID Volume � (Cr�er un volume RAID).
   Utilisez cette option pour cr�er un ou deux volumes RAID. 

2. � Delete RAID Volume � (Supprimer un volume RAID).
   Utilisez cette option pour supprimer un volume RAID.

3. � Reset Disks to Non-RAID � (R�initialiser les disques 
   durs sur Non RAID).
   Utilisez cette option pour r�initialiser une
   configuration RAID avec une configuration non RAID.

4. � Recovery Volume Options � (Options du volume de reprise).
   Si le syst�me comporte un volume de reprise, utilisez 
   cette option pour :
     a. � Disable Continuous Update � (D�sactiver la mise 
        � jour continue).
     b. � Enable Only Recovery Disk � (Activer uniquement 
        un disque de reprise).
     c. � Enable Only Master Disk � (Activer uniquement un 
        disque ma�tre).

11b. PILOTE UEFI ou BIOS

L'interface utilisateur UEFI de la Technologie de stockage 
Intel(R) Rapid permet de g�rer les volumes RAID pr�-syst�me 
d'exploitation. Elle offre les options de gestion des 
volumes RAID suivantes :

1. � Create RAID Volume � (Cr�er un volume RAID).
   Utilisez cette option pour cr�er un ou deux volumes RAID. 

2. � Delete � (Supprimer).
   Utilisez cette option pour supprimer un volume RAID.

3. � Reset Disks to Non-RAID � (R�initialiser les disques 
   durs sur Non RAID).
   Cliquez sur un disque faisant partie du volume RAID 
   puis utilisez cette option pour r�initialiser le disque 
   RAID � l'�tat pass-through Non RAID.

4. � Recovery Volume Options � (Options du volume de reprise).
   Si le syst�me comporte un volume de reprise, utilisez 
   cette option pour :
     a. � Disable Continuous Update � (D�sactiver la mise 
        � jour continue).
     b. � Enable Only Recovery Disk � (Activer uniquement 
        un disque de reprise).
     c. � Enable Only Master Disk � (Activer uniquement un 
        disque ma�tre).


***************************************************************
* 12.  OPTIONS DE R�INITIALISATION DU VOLUME RAID DANS 
*      L'INTERFACE UTILISATEUR PR�-SYST�ME D'EXPLOITATION
***************************************************************

L'interface utilisateur pr�-syst�me d'exploitation de la 
Technologie de stockage Intel(R) Rapid propose deux m�thodes 
pour r�initialiser les volumes RAID :

1. � Delete RAID Volume � (Supprimer le volume RAID).
2. � Reset Disks to Non-RAID � (R�initialiser les disques sur 
   Non RAID).
   Les diff�rences entre les options sont not�es ci-dessous. 
   Les utilisateurs sont conseill�s de choisir l'option en
   fonction de la situation.

12.1 Suppression d'un volume RAID

     Quand un volume RAID est supprim�, les m�tadonn�es sur le 
     disque sont effac�es et le secteur z�ro est supprim� ; ce 
     qui signifie que les donn�es de la table de partition et 
     du syst�me de fichiers sont effac�es. L'installateur de 
     Windows ne trouvera aucune donn�e inadmissible pendant 
     l'installation du syst�me d'exploitation. C'est la m�thode 
     recommand�e pour modifier le volume RAID et installer le 
     syst�me d'exploitation.

12.2 R�initialisation du disque sur Non RAID

     Cette option est utilis�e pour r�initialiser les 
     m�tadonn�es sur le disque appartenant � plus d'un 
     volume RAID, ceci en une seule action. Utilisez cette 
     option si � Effacer le volume RAID � �choue pour une 
     raison ou une autre et pour r�initialiser un disque qui 
     a �t� marqu� comme disque de r�serve et hors-ligne.
     Quand un disque d'un volume RAID est r�initialis� 
     comme non-RAID, les m�tadonn�es RAID sont effac�es. 
     Cependant, les donn�es de la table de partition et du 
     syst�me de fichiers existent toujours, ce qui peut �tre 
     inadmissible. L'installateur de Windows pourrait mal 
     interpr�ter l'information disponible sur le � disque 
     de r�installation � au moment de l'installation. 
     Ceci peut avoir comme cons�quence un comportement 
     inattendu durant l'installation du syst�me d'exploitation.


************************************************************
* 13.  V�RIFICATION DE LA VERSION DU LOGICIEL DE LA ROM 
*      OPTIONNELLE ET DU PILOTE UEFI PR�-SYST�ME 
*      D'EXPLOITATION
************************************************************

Suivez les �tapes ci-dessous pour identifier le num�ro de 
version du pilote UEFI ou de la ROM Optionnelle h�rit�e  
de la Technologie de stockage Intel(R) Rapid :

1. Ouvrez l'interface utilisateur UEFI ou celle de la ROM 
   Optionnelle de la Technologie de stockage Intel(R) Rapid 
   en suivant les �tapes d�crites dans la section 10.
2. La version du logiciel sera affich�e dans la banni�re 
   de l'interface utilisateur :
   � Intel(R) Rapid Storage Technology-option ROM X.y.w.zzzz �.

   � X.y.w.zzzz � - correspond au num�ro de version de 
   l'interface utilisateur de la ROM Optionnelle install�e 
   sur votre syst�me :
   � X.y.w � - Num�ro de lancement du produit.
   � X � - Num�ro majeur.
   � y � - Num�ro mineur.
   � w � - Num�ro de correctif logiciel.
   � zzzz � - Num�ro de compilation.


************************************************************
* AVIS JURIDIQUE
************************************************************

LES INFORMATIONS CONTENUES DANS CE DOCUMENT CONCERNENT LES 
PRODUITS INTEL. CE DOCUMENT N'ACCORDE AUCUNE LICENCE, 
EXPRESSE OU IMPLICITE, PAR PR�CLUSION OU AUTRE, � DES DROITS 
DE PROPRI�T� INTELLECTUELLE. � L'EXCEPTION DES AUTORISATIONS
ACCORD�ES SELON LES TERMES ET CONDITIONS D'INTEL POUR DES 
PRODUITS PARTICULIERS, INTEL D�CLINE TOUTE RESPONSABILIT� ET 
GARANTIE EXPRESSE OU IMPLICITE LI�E � LA VENTE ET/OU � 
L'UTILISATION DES PRODUITS INTEL Y COMPRIS LES OBLIGATIONS 
OU LES GARANTIES ASSOCI�ES � L'ADAPTATION � UNE UTILISATION 
PARTICULI�RE, LA COMMERCIALISATION OU LA CONTREFA�ON DE 
BREVET, DE COPYRIGHT OU D'AUTRES DROITS DE PROPRI�T� 
INTELLECTUELLE.

SAUF ACCORD �CRIT D'INTEL, LES PRODUITS INTEL NE SONT PAS
CON�US NI PR�VUS POUR DES APPLICATIONS DANS LESQUELLES UNE 
D�FAILLANCE DU PRODUIT INTEL POURRAIT CR�ER UN SITUATION 
POUVANT ENTRA�NER DES BLESSURES OU LA MORT.

Intel se r�serve le droit de modifier les sp�cifications et 
descriptions de produit � tout moment et sans pr�avis. 
Les concepteurs ne doivent pas s'appuyer sur des 
caract�ristiques de fonctionnalit�s ou leur absence, ou 
sur des instructions marqu�es ��r�serv頻 ou ��non d�fini��. 
Intel les r�serve pour une d�finition � venir et n'assume
aucune responsabilit� pour les conflits ou incompatibilit�s 
survenant apr�s que des modifications leur seront apport�es 
� l'avenir. Les informations contenues dans la pr�sente 
sont sujettes � modifications sans pr�avis. Ne finalisez 
pas un design sans ces informations.

Les produits d�crits dans ce document peuvent contenir des 
d�fauts ou erreurs ; dans ce cas, le produit n'est pas 
conforme aux sp�cifications publi�es. Une description des 
erreurs et d�fauts est disponible sur demande.

Contactez le bureau de vente Intel local ou votre distributeur 
pour obtenir les derni�res sp�cifications et avant de passer 
votre commande de produit.

Des copies des documents qui poss�dent un num�ro de commande 
et sont r�f�renc�s dans ce document, ou d'autres documents 
Intel, peuvent �tre obtenues en contactant votre vendeur ou 
distributeur, ou en visitant�: http://www.intel.com/#/en_us_01

Intel(R) est une marque de commerce d'Intel Corporation aux 
�tats-Unis et dans d'autres pays.

* D'autres noms et marques peuvent �tre revendiqu�es en tant 
que propri�t� de tiers.


Copyright (c) Intel Corporation. Tous droits 
r�serv�s.

***************************************************************
* CONTRAT DE LICENCE LOGICIELLE INTEL(R)
***************************************************************

