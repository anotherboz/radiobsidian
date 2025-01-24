Exam1 : https://exam1.r-e-f.org/accueil

[[COURS radioamateur 2024.pdf]]

#flashcards/généralité
## Examen, Classes d'émission, Conditions techniques
Deux épreuves (techniques et réglementaires), 10/20 minimum pour chaque. Pas d'age réglementaire. 1 point par bonne réponse. Organisé par les SRR.

ANFR :: Agence Nationale des Fréquences
SRR :: Service Régionaux de Radiocommunication de l'ANFR

### Réglementation internationale 
Le Réglement des Radiocommunications définit le service radioamateur (S1-56) et service d'amateurs par satellite (S1-57).

UIT :: Union Internationale des Télécommunications
RR :: Radio Regulation, Réglement des Radiocommunications

### Réglementation européenne
CEPT :: Conférence Européenne des administration des Postes et Télécommunications

### Réglementation nationale
Le CPCE définit 5 catégories d'installations. Les installations radioamateurs constituent la 3ème catégorie (L33-3). "L'utilisation des fréquences radioélectrique constitue un mode privatif du domaine publicde l'Etat."

ARCEP est consulté pour les projets de loi. Elle prend des décisions qui sont homologuées par le ministre et publiées au journal officiel. Elle attribue les fréquences et veille à leur bonne utilisation.

L'ANFR a pour but d'assurer la planification, la gestion et le contrôle d'utilisation des fréquences radioélectriques. Elle organise les examens, délivre les certificats et les indicatifs. Les SRR organisent les examens en région.

CPCE :: Code des Postes et Communications électroniques
ARCEP :: Autorité de Régulation des Communications Electronique, des Postes et de la distribution de la Presse (autres usagers dont services amateurs)
ARCOM :: Autorité de Régulation des Communication, anciennement CSA, gère les fréquences de la TV, la FM et les services de l'état
TNRBF :: Tableau National de Répartition des Bandes de Fréquences
ANFR :: Agence Nationale des Fréquences
SRR :: Services Régionaux de Radiocommunication


### Classe d'émission

| 1er lettre - Modulation de porteuse            | Chiffre - Signal modulant                          | 2eme lettre - Information transmises |
| ---------------------------------------------- | -------------------------------------------------- | ------------------------------------ |
| **A** Amplitude (double bande latérale)        | **1** Une seule voies sans sous porteuse           | **A** Télégraphie auditive           |
| **B** Amplitude (bande latérale indépendantes) | **2** Une seule voies avec sous porteuse modulante | **B** Télégraphie automatique        |
| **C** Amplitude (bande latérale résiduelle)    | **3** Analogique                                   | **C** Fac-similé (image fixe)        |
| **D** Amplitude et angulaire                   | **7** Numérique (plusieurs voies)                  | **D** Transmission de données        |
| **F** Angulaire - Fréquence                    | **8** Analogique (plusieurs voies)                 | **E** Téléphonie                     |
| **G** Angulaire - Phase                        | **9** Analogique et numérique                      | **F** Télévision                     |
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
A1B :: Télégraphie automatique, modulation d'amplitude par tout ou rien sans sous porteuse
F2A :: Télégraphie auditive en FM avec une seule voie avec sous porteuse modulante
F3E :: Téléphonie en modulation de fréquence
G2B :: Télégraphie automatique avec modulation de phase; une seule voie avec sous porteuse modulante (PSK31)
J3C :: Fac-simile, BLU porteuse supprimée
F7W :: Combinaison de différent type d'information, modulation de fréquence avec plusieur voies numériques (comme le protocole D-Start)

### Conditions techniques

#flashcards/conditions-techniques

Le seul **matériel obligatoire** est ==l'indicateur de puissance==.
Les **largeurs de bandes occupées** sont ==6kHz== pour les fréquences inférieues à 28MHz, ==12kHz== entre 28 et 144MHz, ==20kHz== entre 144 et 225MHz, ==pas de limite== au dessus de 225MHz.

Puissance maximale des **rayonnements non essentiels** est ==43dB + 10 log[P]==.
Emission hors bande = ==5 x bande passante==. Rayonnement non essentiel : hors de la zone hors bande.

## Fréquences et Puissances autorisées

Il y a 27 bandes attribuées aux radio-amateurs. Certaines à **titre primaire** sont attribuées exclusivement aux OM. Celles à titre **primaire partagées** avec égalitée de droits avec d'autres services. Celles à **titre secondaire**, les OM ne sont pas prioritaires et ne doivent pas causer de brouillage.

|     | Bande | Fréquences MHz | Statut     | Puissance |
| --- | ----- | -------------- | ---------- | --------- |
| LF  | 2222m | 0,1357-0,1378  | Secondaire | 1 W       |
| MF  | 630m  | 0,472-0,479    | Secondaire | 15 W      |
|     | 160m  | 1,810-1,850    | Primaire   |           |
| HF  | 80m   | 3,5-3,8        | Secondaire | < 500W    |
|     | 60m   | 5,3515-5,5665  | Partagé    |           |
|     | 40m   | 7-7,2          | Primaire   |           |
|     | 30m   | 10,1-10,15     | Secondaire |           |
|     | 20m   | 14-14,35       | Primaire   |           |
|     | 17m   | 18,068-18,168  | Primaire   |           |
|     | 15m   | 21-21,45       | Primaire   |           |
|     | 12m   | 24,89-24,99    | Primaire   |           |
|     | 10m   | 28-29,7        | Primaire   | < 250W    |
| VHF | 6m    | 50-52          | Secondaire | < 120W    |
|     | 2m    | **144-146**    | Primaire   |           |
| UHF | 70cm  | 430-434        | Secondaire |           |
|     | 70cm  | 434-440        | Primaire   |           |
|     | 23cm  | 1240-1300      | Secondaire |           |
|     | 13cm  | 2300-2450      | Secondaire |           |
| SHF | 6cm   | 5650-5850      | Secondaire |           |
|     | 3cm   | 10 000-10 450  | Secondaire |           |
|     | 3cm   | 10 450-10 500  | Primaire   |           |
|     | 1,2cm | 24 000-24 050  | Primaire   |           |
|     | 1,2cm | 24 050-24 250  | Secondaire |           |
| EHF | 6mm   | 47 000-47 200  |            |           |
|     | 4mm   | 76 000-77 500  |            |           |
|     | 4mm   | 77 500-78 000  |            |           |
|     | 2,4mm |                |            |           |
|     | 2,2mm |                |            |           |
|     | 2,2mm |                |            |           |
|     | 1,2mm |                |            |           |

PIRE :: Puissance Isotrope Rayonnée Equivalente

## Alphabet & Code Q

### Alphabete
#flashcards/alphabet
A :: Alpha
B :: Bravo
C :: Charlie
D :: Delta
E :: Echo
F :: Foxtrot
G :: Golf
H :: Hotel
I :: India
J :: Juliett
K :: Kilo
L :: Lima
M :: Mike
N :: November
O :: Oscar
P :: Papa
Q :: Quebec
R :: Romeo
S :: Sierra
T :: Tango
U :: Uniform
V :: Victor
W :: Whiskey
X :: X-Ray
Y :: Yankee
Z :: Zoulou

### Code Q

#flashcards/code-q
QRA :: Quel est le nom de votre station ?
QRG :: Quelle est *ma* fréquence exacte ?
QRH :: Ma fréquence varie-t-elle ?
QRK :: Quelle est l'intelligibilité de mes signaux ? de 1 à 5
QRL :: Etes vos occupé ?
QRM :: Etes vous brouillé ?
QRN :: Etes vous troublé par des parasites ?
QRO :: Dois-je augmenter la puissance d'émission ?
QRP :: Dois-je diminuer la puissance d'emission ?
QRT :: Dois-je cesser la transmission ?
QRU :: Avez vous quelque chose pour moi ?
QRV :: Etes vous prêt ?
QRX :: A quel moment me rappelez-vous ?
QRZ :: Par qui suis-je appelé ?
QSA :: Quelle est la force de mes signaux ?
QSB :: La force de mes signaux varie-t-elle ?
QSL :: Pouvez-vous me donner un accusé réception ?
QSO :: Pouvez-vous communiquer avec ... ?
QSP :: Voulez-vous retransmettre gratuitement à ... ?
QSY :: Dois-je passer à une autre fréquence ?
QTH :: Quelle est votre position ?
QTR :: Quelle est l'heure exacte ?

### Déroulement d'un contact



