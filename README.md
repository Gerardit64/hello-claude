# Hello Claude

Hello World Next.js application

## Description

Application Next.js simple utilisant l'App Router et TypeScript, conçue comme point de départ pour développer des applications web modernes.

## Technologies

- **Next.js** 16.1.6 - Framework React avec rendu serveur
- **React** 19.2.4 - Bibliothèque UI
- **TypeScript** 5.9.3 - Typage statique

## Installation

```bash
npm install
```

## Développement

```bash
npm run dev
```

Le serveur de développement démarrera sur [http://localhost:3001](http://localhost:3001)

## Construction

```bash
npm run build
```

## Production

```bash
npm start
```

## Linting

```bash
npm run lint
```

## Structure du projet

```
hello-claude/
├── app/
│   ├── layout.tsx    # Layout racine
│   ├── page.tsx      # Page d'accueil
│   └── globals.css   # Styles globaux
├── public/           # Assets statiques
├── next.config.js    # Configuration Next.js
├── tsconfig.json     # Configuration TypeScript
└── package.json      # Dépendances du projet
```

## Configuration

- **Port de développement** : 3001
- **Path alias** : `@/*` mappe vers la racine du projet
- **TypeScript strict mode** : activé