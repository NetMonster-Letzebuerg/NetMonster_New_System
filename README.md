# NetMonster Luxembourg Coeur du systéme

Status du développement: alpha

NetMonster Luxembourg - Système Frontend et explication

**Description simplifiée:**

NetMonster Luxembourg gère la collecte et le traitement des données de localisation et les transmet aux bases de données des opérateurs nationaux. Ce qui comprends:

**Fonctionnalité:**

1. **Mise à jour de la base de donnée NTM:**
   - Maintient en ligne de la base de donnée en format NTM pour chaque opérateur, mises à jour réguliérement

2. **Envoi de données de localisation:**
   - Les utilisateurs somettent des informations en JSON au endpoint

3. **Intégration des bases de données**
   - Facilite l'intégration des donées soumises par les utilisateurs au sein de la base de données de chaques opérateurs

4. **Traitement flexible:**
   - Permet de prendres des décisions présonnalisées lors du traitement des données soumis pas l'utilisateur

**Information d'utilsation quotidienne:**

   - Fournit des données sur les utilisateurs actifs quotidiennement
   - Enregistre les smartphones les plus utilisés par marque

**Enregistrement du modèle par opérateur:**

   - Capture et enregistre les modèles de smartphones les plus utilisés par les usagers de chaques opérateurs
   - Comprends les statistique pour POST,Tango,LOL et Orange LU

**Frontend NetMonster Luxembourg:**
   - Affichage des statistique nationales et informations pour chaques opérateurs luxembourgeois
   - Accées à la base de données de chaques opérateurs national

# Project Setup and Start Guide

## Prerequisites

Before you begin, ensure you have met the following requirements:

- You have installed the latest LTS version of [Node.js and npm](https://nodejs.org/en/download/).
- You have a Windows/Linux/Mac machine.

## Setup

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/NetMonster_Portugal_system.git
   ```

2. Navigate to the project directory:

   ```bash
   cd NetMonster_Portugal_system
   ```

3. Install the project dependencies:

   ```bash
   npm install
   ```

## Start

To start the project, run the following command: `npm start`


## Environment Variables

The following environment variables can be configured in the project:

- `PORT`: The port number on which the server will listen. Default is `8080`.

Make sure to set these variables according to your environment before starting the project.

## Linting and formatting

This projects uses [Biome](https://biomejs.dev/guides/getting-started/) to lint and format all JavaScript files. Make sure to install the [VSCode extension](https://biomejs.dev/guides/integrate-in-editor/#vs-code) to have support for Biome while developing.

## Original Projet
This projects is base in [The NetMonster_Portugal_system](https://github.com/luisbaker/NetMonster_Portugal_system) From Luis Baker 