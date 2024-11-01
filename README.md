Voici un README pour le projet `ffcam-aura` :

---

# FFCAM-aura

> Ce dépôt contient le code source du site [FFCAM-aura.fr](https://ffcam-aura.fr), développé avec [Astro](https://astro.build/).

## Installation et Utilisation

### Prérequis
Le projet utilise [pnpm](https://pnpm.io/) pour la gestion des paquets. Assurez-vous d’avoir pnpm installé sur votre machine avant de continuer.

### Commandes

Pour installer les dépendances :
```sh
pnpm install
```

Pour démarrer le site en local :
```sh
pnpm dev
```

Pour vérifier le code et le compiler pour la production :
```sh
pnpm run build
```

Pour prévisualiser la version build du site :
```sh
pnpm run preview
```

### Déploiement sur Cloudflare Pages

Le site peut être déployé sur Cloudflare Pages avec la commande suivante :
```sh
pnpm run deploy
```

## Configuration

Les principales configurations se trouvent dans le fichier `package.json`. Pour les types de Cloudflare Workers, vous pouvez générer les types avec :
```sh
pnpm run cf-typegen
```

## Structure du projet

Le projet suit l'architecture recommandée par Astro, avec les fichiers et dossiers principaux :

- **src/** : Contient le code source du site.
- **public/** : Contient les ressources publiques (images, icônes, etc.).
- **astro.config.mjs** : Fichier de configuration pour Astro.
- **wrangler.toml** : Configuration pour le déploiement sur Cloudflare.

## Dépendances principales

- **Astro** : Framework de base du site.
- **Cloudflare** : Utilisé pour héberger et gérer le déploiement du site.
- **TypeScript** : Utilisé pour le typage et la robustesse du code.

## Licence

Le code de ce projet est distribué sous licence MIT. Voir le fichier `LICENSE` pour plus de détails.

---

Ce README devrait vous aider à démarrer et à contribuer au développement du site.