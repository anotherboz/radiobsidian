Exam1 : https://exam1.r-e-f.org/accueil

[[COURS radioamateur 2024.pdf]]

#flashcards/généralité
## Examen, Classes d'émission, Conditions techniques
Deux épreuves (techniques et réglementaires), 10/20 minimum pour chaque. Pas d'age réglementaire. 1 point par bonne réponse. Organisé par les SRR.

### Réglementation internationale 
L'UIT édite le RR. Tous les 3 ou 4 ans, l’UIT-R organise à son siège de Genève une CMR (WRC) pour mettre à jour le RR.

Le Réglement des Radiocommunications définit le service radioamateur :: S1-56
<!--SR:!2025-02-08,1,211-->
Le RR définit le service d'amateurs par satellite :: S1-57
<!--SR:!2025-02-08,1,211-->

La Résolution 646 préconise une harmonisation des fréquences par région et reconnaît l’utilité de la Convention de Tampere.

L’article S25 précise les conditions d’exploitation du service amateur. La disposition S25-9A du RR résume l’esprit de tous ces textes : "les administrations sont invitées à prendre les mesures nécessaires pour autoriser les stations d'amateurs à se préparer en vue de répondre aux besoins de communication pour les opérations de secours en cas de catastrophes". La Recommandation UIT-RM.1042 demande aux radioamateurs la mise en œuvre rapide de réseaux souples et fiables en cas de catastrophe. 

UIT :: Union Internationale des Télécommunications
<!--SR:!2025-02-21,14,291-->
RR :: Radio Regulation, Réglement des Radiocommunications
<!--SR:!2025-02-10,3,251-->

### Réglementation européenne
 La CEPT regroupe les administrations chargées des postes et des télécommunications des 27 pays de l’Union Européenne et de 21 autres pays européens.

T/R 61-01 :: La recommandation établit la libre circulation des radioamateurs au sein de la CEPT pour des séjours de moins de 3 mois.
<!--SR:!2025-02-09,2,231-->
T/R 61-02 :: La recommandation préconise notamment un programme d’examen détaillé de réglementation et de technique (HAREC).
<!--SR:!2025-02-09,2,231-->

CEPT :: Conférence Européenne des administration des Postes et Télécommunications
<!--SR:!2025-02-09,2,231-->

### Réglementation nationale
Le CPCE définit 5 catégories d'installations. Les installations radioamateurs constituent la 3ème catégorie.
L33-3 :: "L'utilisation des fréquences radioélectrique constitue un mode privatif du domaine publicde l'Etat" & "Les installations radioélectriques n'utilisant pas des fréquences spécifiquement assignées"
<!--SR:!2025-02-08,1,211-->

ARCEP est consulté pour les projets de loi. Elle prend des décisions qui sont homologuées par le ministre et publiées au journal officiel. Elle attribue les fréquences et veille à leur bonne utilisation.
L36-7 :: l’ARCEP assigne aux utilisateurs les fréquences. Elle est notre autorité de tutelle
<!--SR:!2025-02-09,2,231-->
L41 :: le Premier Ministre arrête le partage du spectre radioélectrique
<!--SR:!2025-02-08,1,211-->
L41-1 :: l'utilisation de fréquences radioélectrique est soumise à autorisation administrative
<!--SR:!2025-02-08,1,211-->
L42 :: l’ARCEP fixe les conditions techniques d’utilisation des fréquences
<!--SR:!2025-02-08,1,211-->
L42-4 :: le ministre chargé des communications électroniques fixe les conditions d’obtention du certificat d’opérateur
<!--SR:!2025-02-08,1,211-->
L43 :: l’ANFR assure la gestion et le contrôle d’utilisation des fréquences radioélectriques.
<!--SR:!2025-02-08,1,211-->

L'ANFR a pour but d'assurer la planification, la gestion et le contrôle d'utilisation des fréquences radioélectriques. Elle organise les examens, délivre les certificats et les indicatifs. Les SRR organisent les examens en région.

• D406-7 : définition des installations utilisant des fréquences radioélectriques

CPCE :: Code des Postes et Communications électroniques
<!--SR:!2025-02-14,7,251-->
ARCEP :: Autorité de Régulation des Communications Electronique, des Postes et de la distribution de la Presse (autres usagers dont services amateurs)
<!--SR:!2025-02-09,2,251-->
ARCOM :: Autorité de Régulation des Communication, anciennement CSA, gère les fréquences de la TV, la FM et les services de l'état
<!--SR:!2025-02-18,11,271-->
TNRBF :: Tableau National de Répartition des Bandes de Fréquences
<!--SR:!2025-02-22,15,291-->
ANFR :: Agence Nationale des Fréquences
SRR :: Services Régionaux de Radiocommunication
<!--SR:!2025-02-19,12,271-->


### Classe d'émission

| 1er lettre - Modulation de porteuse            | Chiffre - Signal modulant                          | 2eme lettre - Information transmises |
| ---------------------------------------------- | -------------------------------------------------- | ------------------------------------ |
| **A** Amplitude (double bande latérale)        | **1** Une seule voies sans sous porteuse           | **A** Télégraphie auditive           |
| **B** Amplitude (bande latérale indépendantes) | **2** Une seule voies avec sous porteuse modulante | **B** Télégraphie automatique        |
| **C** Amplitude (bande latérale résiduelle)    | **3** Analogique                                   | **C** Fac-similé (image fixe)        |
| **D** Amplitude et angulaire                   | **7** Numérique (plusieurs voies)                  | **D** Transmission de données        |
| **F** Angulaire - Fréquence                    | **8** Analogique (plusieurs voies)                 | **E** Téléphonie                     |
| **G** Angulaire - Phase                        | **9** Analogique et numérique<br>                  | **F** Télévision                     |
| **H** Amplitude - BLU porteuse complète        | **0** Pas de signal modulant                       | **N** Aucune information             |
| **J** Amplitude - BLU porteuse supprimée       | **X** Autres cas                                   | **W** Combinaison                    |
| **R** Amplitude - BLU porteuse réduite         |                                                    | **X** Autres cas                     |
| **K,L,M,P,Q,V** Train d'impulsions             |                                                    |                                      |
| **W** Combinaison et autre                     |                                                    |                                      |
| **N** Porteuse non modulée                     |                                                    |                                      |

Logique du codage :
On commence par l’amplitude seule (A = AM pure, B et C = AM spécifique) puis 
amplitude et angulaire (D) puis angulaire seule (F = fréquence et G = phase). Viennent ensuite les trois types de BLU (H, J et R = réduite). A la fin, on trouve les trains d’impulsions (K, L, M, P, Q et V)

Moyen mnémotechnique (initiale du code) :
**A**uditif, **B**écane (= machine), **C**opie, **D**onnées, **E**coute, **F**rance Télévision, **N**o info, **W**et suit (= combinaison de plongée en anglais…). 

#flashcards/classes-emission
Exemple de classe : 
A1A :: Télégraphie audive, modulation d'amplitude par tout ou rien sans sous porteuse, CW
<!--SR:!2025-02-23,16,291-->
A1B :: Télégraphie automatique, modulation d'amplitude par tout ou rien sans sous porteuse
<!--SR:!2025-02-21,14,291-->
F2A :: Télégraphie auditive en FM avec une seule voie avec sous porteuse modulante
<!--SR:!2025-02-22,15,291-->
F3E :: Téléphonie en modulation de fréquence
<!--SR:!2025-02-23,16,291-->
G2B :: Télégraphie automatique avec modulation de phase; une seule voie avec sous porteuse modulante (PSK31)
<!--SR:!2025-02-22,15,291-->
J3C :: Fac-simile, BLU porteuse supprimée
<!--SR:!2025-02-18,11,271-->
F7W :: Combinaison de différent type d'information, modulation de fréquence avec plusieur voies numériques (comme le protocole D-Start)
<!--SR:!2025-02-17,10,271-->

### Conditions techniques

#flashcards/conditions-techniques

Le seul **matériel obligatoire** est :: ==l'indicateur de puissance==.
<!--SR:!2025-02-09,2,231-->

#flashcards/conditions-techniques/largeur-de-bande

La **largeur de bande occupée** est ==6kHz== pour les fréquences :::  inférieues à 28MHz
<!--SR:!2025-02-09,2,231!2025-02-15,8,251-->

La **largeur de bande occupée** est==12kHz==  ::: entre 28 et 144MHz
<!--SR:!2025-02-19,12,271!2025-02-14,7,251-->

La **largeur de bande occupée** est==20kHz== ::: entre 144 et 225MH
<!--SR:!2025-02-09,2,231!2025-02-16,9,251-->

La **largeur de bande occupée** n'est ==pas de limite==  ::: au dessus de 225MHz.
<!--SR:!2025-02-09,2,231!2025-02-15,8,251-->

Puissance maximale des **rayonnements non essentiels** :: est ==43dB + 10 log[P]==.
<!--SR:!2025-02-09,2,231-->
Emission hors bande ::  ==5 x bande passante==.
<!--SR:!2025-02-09,2,231-->
Rayonnement non essentiel ::: hors de la zone hors bande.
<!--SR:!2025-02-08,1,211!2025-02-09,2,231-->

## Fréquences et Puissances autorisées

Il y a 27 bandes attribuées aux radio-amateurs. Certaines à **titre primaire** sont attribuées exclusivement aux OM. Celles à titre **primaire partagées** avec égalitée de droits avec d'autres services. Celles à **titre secondaire**, les OM ne sont pas prioritaires et ne doivent pas causer de brouillage.

|     | Bande | Fréquences MHz | Statut     | Puissance | Satellite     |
| --- | ----- | -------------- | ---------- | --------- | ------------- |
| LF  | 2222m | 0,1357-0,1378  | Secondaire | 1 W PIRE  |               |
| MF  | 630m  | 0,472-0,479    | Secondaire | 1 W PIRE  |               |
|     | 160m  | 1,810-1,850    | Primaire   |           |               |
| HF  | 80m   | 3,5-3,8        | Secondaire | < 500W    |               |
|     | 60m   | 5,3515-5,5665  | Partagé    | 15 W PIRE |               |
|     | 40m   | 7-7,2          | Primaire   |           | 7-7,1         |
|     | 30m   | 10,1-10,15     | Secondaire |           |               |
|     | 20m   | 14-14,35       | Primaire   |           | 14-14,25      |
|     | 17m   | 18,068-18,168  | Primaire   |           | 18,068-18,168 |
|     | 15m   | 21-21,45       | Primaire   |           | 21-21,45      |
|     | 12m   | 24,89-24,99    | Primaire   |           | 24,89-24,99   |
|     | 10m   | 28-29,7        | Primaire   | < 250W    | 28-29,7       |
| VHF | 6m    | 50-52          | Secondaire | < 120W    |               |
|     | 2m    | **144-146**    | Primaire   |           | 144-146       |
| UHF | 70cm  | 430-434        | Secondaire |           |               |
|     | 70cm  | 434-440        | Primaire   |           |               |
|     | 23cm  | 1240-1300      | Secondaire |           |               |
|     | 13cm  | 2300-2450      | Secondaire |           | 2400-2450     |
| SHF | 6cm   | 5650-5850      | Secondaire |           |               |
|     | 3cm   | 10 000-10 450  | Secondaire |           |               |
|     | 3cm   | 10 450-10 500  | Primaire   |           |               |
|     | 1,2cm | 24 000-24 050  | Primaire   |           |               |
|     | 1,2cm | 24 050-24 250  | Secondaire |           |               |
| EHF | 6mm   | 47 000-47 200  |            |           |               |
|     | 4mm   | 76 000-77 500  |            |           |               |
|     | 4mm   | 77 500-78 000  |            |           |               |
|     | 2,4mm |                |            |           |               |
|     | 2,2mm |                |            |           |               |
|     | 2,2mm |                |            |           |               |
|     | 1,2mm |                |            |           |               |

PIRE :: Puissance Isotrope Rayonnée Equivalente

#flashcards/conditions-techniques/statut-des-bandes

Statut A ::  Primaire : Les radioamateurs sont prioritaire sur ces bandes
Statut B ::  En partage : Avec églité de droit
Statut C :: A titre secondaire : Les radioamateurs ne doivent pas brouiller les usagers à titre primaire
Statut D :: A titre primaire uniquement en France (pour la bande de 10GHz)

## Alphabet & Code Q
<!--SR:!2025-02-14,7,251!2025-02-15,8,251-->

### Alphabete
#flashcards/alphabet
A :: Alpha
<!--SR:!2025-02-23,16,291-->
B :: Bravo
<!--SR:!2025-02-22,15,291-->
C :: Charlie
<!--SR:!2025-02-21,14,291-->
D :: Delta
<!--SR:!2025-02-21,14,291-->
E :: Echo
<!--SR:!2025-02-23,16,291-->
F :: Foxtrot
<!--SR:!2025-02-21,14,291-->
G :: Golf
<!--SR:!2025-02-22,15,291-->
H :: Hotel
<!--SR:!2025-02-23,16,291-->
I :: India
<!--SR:!2025-02-22,15,291-->
J :: Juliett
<!--SR:!2025-02-22,15,291-->
K :: Kilo
<!--SR:!2025-02-21,14,291-->
L :: Lima
<!--SR:!2025-02-22,15,291-->
M :: Mike
<!--SR:!2025-02-21,14,291-->
N :: November
<!--SR:!2025-02-22,15,291-->
O :: Oscar
<!--SR:!2025-02-21,14,291-->
P :: Papa
<!--SR:!2025-02-22,15,291-->
Q :: Quebec
<!--SR:!2025-02-21,14,291-->
R :: Romeo
<!--SR:!2025-02-22,15,291-->
S :: Sierra
<!--SR:!2025-02-23,16,291-->
T :: Tango
<!--SR:!2025-02-23,16,291-->
U :: Uniform
<!--SR:!2025-02-22,15,291-->
V :: Victor
<!--SR:!2025-02-21,14,291-->
W :: Whiskey
<!--SR:!2025-02-21,14,291-->
X :: X-Ray
<!--SR:!2025-02-23,16,291-->
Y :: Yankee
<!--SR:!2025-02-23,16,291-->
Z :: Zoulou
<!--SR:!2025-02-23,16,291-->

### Code Q

#flashcards/code-q
QRA :: Quel est le nom de votre station ?
<!--SR:!2025-02-15,8,251-->
QRG :: Quelle est *ma* fréquence exacte ?
<!--SR:!2025-02-16,9,251-->
QRH :: Ma fréquence varie-t-elle ?
<!--SR:!2025-02-10,3,251-->
QRK :: Quelle est l'intelligibilité de mes signaux ? de 1 à 5
<!--SR:!2025-02-16,9,251-->
QRL :: Etes vos occupé ?
<!--SR:!2025-02-09,2,231-->
QRM :: Etes vous brouillé ?
<!--SR:!2025-02-14,7,251-->
QRN :: Etes vous troublé par des parasites ?
<!--SR:!2025-02-09,2,231-->
QRO :: Dois-je augmenter la puissance d'émission ?
<!--SR:!2025-02-09,2,231-->
QRP :: Dois-je diminuer la puissance d'emission ?
<!--SR:!2025-02-09,2,231-->
QRT :: Dois-je cesser la transmission ?
<!--SR:!2025-02-10,3,251-->
QRU :: Avez vous quelque chose pour moi ?
<!--SR:!2025-02-09,2,231-->
QRV :: Etes vous prêt ?
<!--SR:!2025-02-08,1,211-->
QRX :: A quel moment me rappelez-vous ?
<!--SR:!2025-02-10,3,251-->
QRZ :: Par qui suis-je appelé ?
<!--SR:!2025-02-14,7,251-->
QSA :: Quelle est la force de mes signaux ?
<!--SR:!2025-02-09,2,231-->
QSB :: La force de mes signaux varie-t-elle ?
<!--SR:!2025-02-08,1,211-->
QSL :: Pouvez-vous me donner un accusé réception ?
<!--SR:!2025-02-08,1,211-->
QSO :: Pouvez-vous communiquer avec ... ?
<!--SR:!2025-02-15,8,251-->
QSP :: Voulez-vous retransmettre gratuitement à ... ?
<!--SR:!2025-02-08,1,211-->
QSY :: Dois-je passer à une autre fréquence ?
<!--SR:!2025-02-08,1,211-->
QTH :: Quelle est votre position ?
<!--SR:!2025-02-09,2,231-->
QTR :: Quelle est l'heure exacte ?
<!--SR:!2025-02-09,2,231-->

### Déroulement d'un contact

On doit transmettre son indicatif en début d'emmission et au moins une fois toutes les 15 minutes. On doit veiller à ne pas brouiller une émission déjà en cours (écouter avant d'émettre). On ne doit pas utiliser la même fréquence en permanence ni brouiller volontairement des emissions déjà en cours.

Les communications doivent être en rapport avec l'objet du service radioamateur. Ne doivent pas être codées, ne pas être en provenance ou à destination d'une tièrce personne non radioamateur (sauf situation d'urgence ou catastrophe naturelle).

Journal de bord doit comporter la date, l'heure, l'indicatif du correspondant, la fréquence et la classe d'emmission (et le lieu d'emission en portable ou mobile). Il doit être conservé 1 an après la dernière emission.

L'adresse d'une station fixe doit être déclarée à l'ANFR dans les 2 mois (après un changement).

L'indicatif peut entre suffixé de /P pour portable, /M pour mobile, /MM pour maritime mobile en CW ou en plein terme en audio.

# Technique
## Rapports de puissance
#flashcards/gains
En puissance :

| Gain puissance | -30dB  | -20dB | -10dB | -6db | -3dB | 0dB | 3dB | 6dB | 10dB | 20db | 30dB |
| -------------- | ------ | ----- | ----- | ---- | ---- | --- | --- | --- | ---- | ---- | ---- |
| Rapport        | 1/1000 | 1/100 | 1/10  | 1/4  | 1/2  | 1   | 2   | 4   | 10   | 100  | 1000 |

Gain de -20dB en puissance ::: Rapport de 1/100 en puissance
Gain de -6dB en puissance ::: Rapport de 1/4 en puissance
Gain de 3dB en puissance ::: Rapport de 3 en puissance
Gain de 10dB en puissance ::: Rapport de 10 en puissance

*dBW = dBm +30 = dBµ +60. Ainsi –43 dBW = –13 dBm = +17 dBµ*

Pour calculer un puissance émise, on transforme la puissance d'entrée (W) en dbW, on applique le gain en dB et retransforme en W.

| Gain tension | -60dB  | -40dB | -20dB | -12db | -6dB | 0dB | 6dB | 12dB | 20dB | 40db | 60dB |
| ------------ | ------ | ----- | ----- | ----- | ---- | --- | --- | ---- | ---- | ---- | ---- |
| Rapport      | 1/1000 | 1/100 | 1/10  | 1/4   | 1/2  | 1   | 2   | 4    | 10   | 100  | 1000 |

Gain de -20dB en puissance ::: Rapport de 1/100 en tension
Gain de -6dB en tension ::: Rapport de 1/4 en tension
Gain de 3dB en tension ::: Rapport de 3 en tension
Gain de 10dB en tension ::: Rapport de 10 en tension

**En modulation d’amplitude (AM) comme en BLU**, la puissance d’émission varie au cours du temps. Dans ce cas, la mesure de la puissance se fera sur les pointes d’amplitude ce qui amène à définir la **puissance crête** appelée aussi **puissance de pointe de l’enveloppe** (ou **PEP**, Peak Envelope Power en anglais)


Le rendement détermine la qualité du transfert de puissance. Le rendement, exprimé en % et toujours inférieur à 100%, est le rapport obtenu en divisant la puissance utile (puissance émise) par la puissance consommée totale.

$$
Rendement (\%) = \frac{Puissance\ utile \times 100}{Puissance\ consomm\acute{e}e }
$$


## Ondes et fréquences

Dans le vide (ou dans l’air), les ondes radio se déplacent à la vitesse de la lumière (300.000 km/s). **La longueur d’onde** (mesurée en mètres et notée λ, lettre grecque minuscule lambda) est la distance parcourue dans le vide par l’onde au cours d’une durée égale à la période du signal. **La fréquence** (notée F et mesurée en hertz, Hz) est le nombre de période du signal par seconde.

$F(MHz) = \frac{300}{λ(m)}$ et $\lambda(m)=\frac{300}{F(MHz)}$ 

#flashcards/gammes_fréquences
VLF ::: Myriamétrique > 10km / < 30kHz
LF ::: Kilométrique - de 1km à 10km / de 30kHz à 300 kHz
MF ::: Hectométriques - de  100m à 1km / de 300kHz à 3MHz
HF ::: Décamétrique - de 10m à 100m - de 3MHz à 30MHz
VHF ::: Métriques - 1m à 10m - de 30MHz à 300MHz
UHF ::: Décimétrique - de 10cm à 1m / de 300MHz à 3GHz
SHF ::: Centimétrique - de 1cm à 10cm / de 3GHz à 30GHz
EHF ::: Millimétrique - de 1mm à 1cm / de 30GHz à 300GHz
