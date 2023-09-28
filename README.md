# Lanparty

Pour déployer une lan party

Sur ubuntu / debian :

    jeux.md:
    sudo apt install \
    wesnoth teeworlds teeworlds-server \
    hedgewars 0ad supertuxkart \
    minetest gcompris fretsonfire \
    openarena openarena-server armagetronad \
    kobodeluxe

    jeux-2023.md (ubuntu 22.04):
    sudo apt install \
      wesnoth teeworlds teeworlds-server \
      hedgewars 0ad supertuxkart \
      minetest gcompris-qt \
      openarena openarena-server armagetronad \
      kobodeluxe redeclipse freeciv
    sudo snap install frets-on-fire

Texte du dépliant pour les visiteurs dans [jeux.md](jeux.md) et [jeux-2023.md](jeux-2023.md)

Pour le générer en odt :

    pandoc jeux.md -o jeux.odt
    pandoc jeux-2023.md -o jeux-2023.odt
