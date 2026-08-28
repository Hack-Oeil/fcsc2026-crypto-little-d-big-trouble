# FCSC 2025 Little d - Big trouble

Le standard FIPS 186-5 impose dans la génération d’une clef RSA que l’exposant privé `d` soit plus grand que `2**(size//2)`. Le standard précise d’ailleurs que dans le cas extrêment rare où `d` serait plus petit il faut générer de nouveaux nombres premiers `p` et `q`.

Testez votre chance en soumettant un de ces cas extrêment rares.

![presentation/assets/images/little-d-big-trouble.jpg](presentation/assets/images/little-d-big-trouble.jpg)

Auteur : Neige

Origine : [Little d - Big trouble](https://hackropole.fr/fr/challenges/crypto/fcsc2026-crypto-little-d-big-trouble-1/)


## Challenge
[files/little-d-big-trouble.py](files/little-d-big-trouble.py)

-----------

## Installation manuel
Vous n'utilisez pas l'application **les CTFs de Cyrhades** ? C'est dommage !
Mais voici comment installer ce CTF manuellement :

> git clone https://github.com/Hack-Oeil/fcsc2026-crypto-little-d-big-trouble.git

> cd fcsc2026-crypto-little-d-big-trouble

> docker compose -f docker-compose-default.yml up

-----------

## Sur le site officiel hackropole.fr
> https://hackropole.fr/fr/challenges/crypto/fcsc2026-crypto-little-d-big-trouble/
