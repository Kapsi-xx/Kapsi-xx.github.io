# Kapsi-xx.github.io

A propos de HKapsi

## Objectifs

Le premier objectif de ce blog est, pour moi, de mémoriser et de pratiquer ce que je suis en train d'apprendre sur la réalisation de la basse chiffrée sur le théorbe, la guitare baroque et le luth au XVIIème et XVIIIème siècles.

Un deuxième objectif est de partager avec d'autres étudiants en basse chiffrée sur le théorbe le parcours que je fais. Si ce blog vous intéresse, n'hésitez pas à me faire part de vos remarques et commentaires.

Il n'aura échappé à personne que le nom de ce blog rend hommage au premier (en tout cas, c'est ce qu'il disait) des joueurs de théorbe (ou de chitarone, en italien), le compositeur italien Hieronymus Kapsberger (1580-1651), dit HK.

## Références

 Je me suis appuyé sur la théorie "moderne" héritée" de Rameau telle que présentée par [Martial Morand, Basse Chiffrée, Volume 1 - Première Approche](http://www.martial-morand-clavecin.fr/basse-chiffree.html).

Les exemples et les enchainements types, notamment pour le suivi des voix, suivent les [Principes de l'accompagnement du clavecin de Jean-François Dandrieu (1719)](https://gallica.bnf.fr/ark:/12148/btv1b10074961j?rk=321890;0).

L'application au théorbe et à la guitare s'inspire librement de l'[Addition au traité d'accompagnement et de composition par la règle de l'octave de François Campion (Ed 1730)](https://gallica.bnf.fr/ark:/12148/bpt6k1175542z.image#), par l'étude des positions sur la touche suivant que la basse des accords est sur les cordes de Sol, Ré ou La.

## Méthode

Nous allons commencer par construire les accords principaux dans les tonalités les plus courantes en mineur (La, Ré, Mi), et en majeur (Do, Fa, Sol).

Pour chaque accord, on cherchera les positions avec tous les dessus possibles. Par exemple, en La mineur, sur le théorbe, l'accord de tonique a trois positions du dessus : à la tierce (Do4), à la quinte (Mi4) ou à l'octave (La4).

On imposera que la basse soit toujours touchée par le pouce, sur l'une des trois cordes, Sol, Ré ou La (ou pour le théorbe, sur le registre grave, à vide de Sol1 à Mi2, à vide ou sur la première touche pour Sol2 - ⑦ et Fa2 - ⑧).

On mettra en évidence des positions glissantes, ce qui permettra de déduire facilement les accords et enchainements dans d'autres tonalités à partir des tonalités courantes, en identifiant les diagrammes d'accord, quand la basse est sur une de ces trois cordes.

En suivant Dandrieu, les réalisations seront faites en général à quatre voix. Toutefois, quand il est possible d'utiliser le plus grand nombre possible de cordes (pour les battues par exemple), nous indiquerons les positions les plus complètes possibles (jusqu'à six voix). A l'inverse, nous verrons que certains accords ne sont possibles sur le théorbe qu'à trois voix.

Enfin, les réalisations privilégieront la réalité de l'accord, comme dit Campion, à la hauteur réelle des notes. On pourra, dans certains cas, avoir la voix de ténor qui passe sous la basse. C'est souvent le cas des accords dont la basse est sur la corde de Sol sur le théorbe ou la guitare ou sur la corde de La sur la guitare. A l'époque, ce n'était pas entendu comme un renversement de l'accord, pour peu que la basse soit touchée avant les autres cordes. C'est l'art de toucher les accords que décrit Campion dans son traité.

## Notation musicale

Les exemples musicaux sont transcrits sur trois portées, du bas en haut :

![La mineur Parfait](/assets/laMineur/LaMineur-01.svg)

+ la basse chiffrée (en clef de Fa),
+ la réalisation (en clef de Sol 8va bassa) avec, en-dessous, la disposition des notes de l'accord comptée en intervalles à partir de la basse (à la Dandrieu),
+ la tablature en notation française. Au dessus de la tablature, les diagrammes d'accord sont ajoutés quand l'accord peut être glissé sur d'autres positions de la touche du théorbe.

## Remerciements

Je voudrais remercier tous les magnifiques professeurs que j'ai cotoyé ces dernières années.

En commençant par Wanda Kozyra avec qui j'ai commencé la basse chiffrée en 2019, sur mon archiluth, lors des stages de musique ancienne de Valence. Elle m'a fait découvrir les méthodes pour clavecin, dont le recueil de Martial Morand, que j'ai utilisé abondamment ici.

J'ai ensuite découvert le théorbe en février 2020, grâce à Benjamin Narvey qui m'a donné l'opportunité d'acquérir un de ses instruments signé du maître luthier Lars Jönsson. Juste à temps pour tenter de maîtriser cet instrument lors du premier confinement qui a débuté en mars 2020 !

Puis, grâce à Carola Grinberg, en septembre 2020, j'ai découvert les méthodes pour théorbe du XVIIème siècle mais aussi, j'ai pratiqué la méthode de Dandrieu qui est une de mes références ici.

Enfin, avec Laurence Postigo, depuis septembre 2021, j'ai pu mettre en pratique ces connaissances, tant sur le théorbe que sur la guitare : *l'art de toucher l'instrument* comme le dirait Campion.

## Outils du blog

Ce blog est un site web statique.

Le site est écrit en swift, en utilisant les frameworks de [Point-Free](https://www.pointfree.co) :
* [swift-html](https://github.com/pointfreeco/swift-html.git),
* le module CSS de [swift-web](https://github.com/pointfreeco/swift-web.git),
* [swift-url-routing](https://github.com/pointfreeco/swift-url-routing.git).

Pour convertir les pages markdown en html :
* [cmark](https://github.com/commonmark/cmark.git)

Pour écrire les exemples musicaux au format svg :
* [MuseScore 3](https://musescore.org/fr).

## Pour me contacter

Thierry Darrigrand

email : kapsi at me.com
