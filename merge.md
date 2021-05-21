# Git-merge

Git est merge est une commande qui permet de fusionner deux branches d'un projet GIT. Cette fusion peut être simple ou compliquée.

 Voyons tout d'abord le cas le plus simple. Dans ce cas, par exemple, notre page index.html et notre page style.css ont été modifiés dans deux branches différentes. GIT peut alors faire une fusion linéaire car il n'y a pas de conflit. Tout se fait automatiquement.

 Intéressons nous maintenant au cas plus compliqué. Dans ce cas, il y a un conflit entre les différentes branches. Si nous reprenons notre exemple précédent nos pages index.html et style css ont été modifiées dans chacunes des branches que l'on souhaite fusionner. GIT ne sait donc pas quelle version de ces pages est la bonne. Dans notre éditeur de texte apparaissent alors les modifications  des deux versions. C'est à nous de résoudre manuellement le conflit en supprimant ce que l'on ne souhaite pas garder et en réorganisant nos pages pour qu'elles correspondent à ce que l'on souhaite.
Il ne nous reste plus qu'a réaliser un nouveau commit et à push notre nouvelle versions sur GIT.