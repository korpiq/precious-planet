Precious Planet
---------------

Here we maintain tools for processing materials for the board game Precious Planet.

See http://kato.iki.fi/precious-planet/ for the game.

Setup
=====

    source setup-development

Usage
=====

Produce printable cards for the game:

    source planet-dev-env/bin/activate
    python datafaser --default-format=text datafaser.yml

