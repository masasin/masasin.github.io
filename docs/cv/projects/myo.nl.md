# Gebaarbesturing van Robots
2014 &ndash; 2015, [Universiteit van Kyoto](../education/kyoto-u.md)

??? summary "Overzicht"

    - Initieel onderzoeksproject aan de Universiteit van Kyoto gericht op het ontwikkelen van infrastructuur om ergonomische besturing van robots met gebaren mogelijk te maken.
    - Ontworpen en ontwikkelde infrastructuur die de gebruikte interface abstraheerde door middel van een API,
      met een proof of concept met behulp van de Myo-armband van Thalmic Labs om robots te besturen.

Mijn oorspronkelijke onderzoeksonderwerp was het ontwikkelen van infrastructuur die ergonomische besturing van robots met gebaren mogelijk zou maken.

Mijn proof of concept zou het gebruik van de Myo-armband van Thalmic labs zijn om robots te besturen,
ofwel een Kinova robotarm, of een van de andere robots van het lab.
Uiteindelijk bepaalde mijn professor dat het te veel ontwikkeling was en niet genoeg onderzoek,
en ik veranderde mijn scriptie naar [SPIRIT](spirit.md).
De broncode is niet openbaar beschikbaar.

Ik ontwierp en ontwikkelde infrastructuur die gebarenbesturing van robots mogelijk zou maken,
terwijl de gebruikte interface werd geabstraheerd door middel van een API.
Hoewel ik met de armband testte, liet het systeem ook besturing toe met behulp van bijvoorbeeld computer vision van een webcam.

Het moeilijkste deel was het uitzoeken van goede, intuïtieve toewijzingen om te gebruiken.
Ik keek naar ergonomie, evenals het handmatig aanpassen van de configuraties,
maar het project werd geannuleerd voordat een volledig functionele versie kon worden gemaakt.

Het grootste deel van de code was geschreven in Python, inclusief wrappers voor [C++ code](https://github.com/thalmiclabs) die ik schreef om met de armband en de robotarm te communiceren.

![De Myo armband](../../assets/images/myo.png){: style="width:400px"}
