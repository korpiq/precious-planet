Precious Planet
---------------

[![Sponsored](https://img.shields.io/badge/chilicorn-sponsored-brightgreen.svg)](http://spiceprogram.org/oss-sponsorship/)

Here we maintain tools for processing materials for the board game Precious Planet.

See http://kato.iki.fi/precious-planet/ for the game.

Setup
=====

    source setup-development

Usage
=====

Produce printable cards for the game:

    source planet-dev-env/bin/activate
    python -m datafaser --default-format=text datafaser.yaml

