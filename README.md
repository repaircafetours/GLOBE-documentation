# GLOBE-documentation

Ce site web est créé avec [Docusaurus](https://docusaurus.io/), un générateur de sites web statiques moderne.

## Installation

```bash
bun
```

## Développement local

```bash
bun start
```

Cette commande lance un serveur de développement local et ouvre une fenêtre de navigateur. La plupart des modifications sont visibles instantanément sans avoir à redémarrer le serveur.

## Compilation

```bash
bun run build
```

Cette commande génère le contenu statique dans le répertoire `build` et peut être servie par n'importe quel service d'hébergement de contenu statique.

## Serveur local

```bash
bun run serve
```

Fonctionne uniquement si vous avez préalablement compilé le site web [build](#build).

## Déploiement

Avec SSH :

```bash
USE_SSH=true bun run deploy
```

Sans SSH :

```bash
GIT_USER=<Votre nom d'utilisateur GitHub> bun run deploy
```

Si vous utilisez GitHub Pages pour l'hébergement, cette commande permet de générer facilement le site web et de le pousser sur la branche `gh-pages`.
