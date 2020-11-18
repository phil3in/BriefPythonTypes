# BriefPythonTypes
Brief Python / 1-On_commence_par_exploiter_les_types_de_base

#### Utiliser un template pour générer du texte
Corrigé Environnement => Environment pour que le code fonctionne.

#### Lire des données au clavier
Rien à signaler.

#### Enregistrer et charger des matrices
Problème d'importation de scipy. Réglé en installant d'abord numpy.

#### Utiliser des nombres aléatoires
RAS.

#### Vérifier la validité d'une date
RAS.

#### Accéder à un endroit précis d'un fichier
J'ai rajouté une ligne de caractères pour vérifier le fonctionnement.

#### Lire un fichier texte ligne par ligne
RAS.

#### Créer un fichier xml

Corrigé une ligne de code : rajouté des parenthèses autour de ```(etree.tostring(root, pretty_print=True)).decode("utf-8")``` pour que ça fonctionne.

#### Lire un fichier xml

RAS.

#### Créer un fichier json

RAS.

#### Lire un fichier json

RAS.

#### Parcourir une liste

RAS.

#### Trier une liste d'entiers lus sous forme d'une chaîne de caractères

Pas bien compris les \n et \r.

#### Trier une liste avec une fonction de tri personnalisée

Erreur dans le code : trois arguments au lieu de deux. En supprimant ```ma_liste```, ça fonctionne.

#### Supprimer les doublons dans une liste

RAS.

#### Trier les valeurs d'un dictionnaire

RAS.

#### Conserver l'ordre des éléments dans un dictionnaire

Si j'ai bien compris, il faut importer "collections" et utiliser ```collections.OrderedDict``` pour que le dictionnaire reste dans l'ordre dans lequel il a été écrit. Mais apparemment c'est déjà son ordre par défaut, la même commande sans ```collections.OrderedDict``` renvoie le même résultat.

#### Créer un dictionnaire qui soit la fusion de deux dictionnaires

RAS.

#### Créer une liste en utilisant la compréhension de liste

RAS. Je crois bien avoir compris le fonctionnement.

#### Créer un dictionnaire en utilisant la compréhension de dictionnaire

Pas bien compris pourquoi ```in zip(ma_liste[::2], ma_liste[1::2])``` plutôt que ```in ma_liste```.