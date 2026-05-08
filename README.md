# 🌌 Compte Rendu Interactif : TP3 - Filtres Actifs (Sallen-Key)

[![Thème](https://img.shields.io/badge/Thème-Astronomic_Violet_Blue-7b2cbf?style=flat-square)](#)
[![Technologies](https://img.shields.io/badge/Stack-HTML5_%7C_MathJax_%7C_Chart.js-4cc9f0?style=flat-square)](#)
[![Déploiement](https://img.shields.io/badge/Deploy-GitHub_Pages-success?style=flat-square)](#)

Ce dépôt héberge un **véritable mémoire interactif** sous la forme d'une application web monolithique. Il est dédié à l'étude théorique, analytique et à la simulation de **filtres actifs du second ordre utilisant la topologie de Sallen-Key** (Passe-Bas et Passe-Haut).

L'interface est conçue avec un design moderne "Dark Space" pour une immersion totale et une lisibilité optimale des données scientifiques.

## 📑 Sommaire
- [Aperçu du Projet](#aperçu-du-projet)
- [Fonctionnalités Principales](#fonctionnalités-principales)
- [Contexte Académique](#contexte-académique)
- [Instructions de Déploiement](#-instructions-de-déploiement-important)
- [Auteur](#auteur)

## 🚀 Aperçu du Projet

Ce projet va bien au-delà d'un simple compte rendu. Il intègre la démonstration rigoureuse des fonctions de transfert à partir des équations nodales, corrige les approximations typographiques du fascicule, et propose des simulations interactives (domaine fréquentiel et temporel) pour valider la théorie par la pratique.

## ✨ Fonctionnalités Principales

* 🧮 **Démonstrations Mathématiques (MathJax)** : Calculs pas-à-pas avec un rendu typographique LaTeX de qualité universitaire :
    * Remplacement des impédances ($Z_1, Z_2, Z_3, Z_4$).
    * Simplification et identification avec les formes canoniques.
    * Applications numériques exactes.
* 📐 **Schémas Vectoriels Précis (SVG)** : Représentations graphiques des circuits Sallen-Key (Passe-Bas et Passe-Haut) incluant les alimentations symétriques et les nœuds, dessinées à 100% en pur code.
* 📈 **Tableaux de Mesures Pratiques** : Tableaux exhaustifs générés avec les valeurs théoriques exactes (Amplitude, Gain, Déphasage, $\Delta T$) pour confronter la simulation aux relevés d'oscilloscope.
* 📊 **Simulations Interactives (Chart.js)** :
    * **Oscilloscope Virtuel** : Visualisation temporelle des signaux d'entrée ($V_e$) et de sortie ($V_s$) aux fréquences clés (100 Hz et 1 kHz).
    * **Diagrammes de Bode** : Tracés dynamiques séparant le Gain (dB) et la Phase (°) pour observer clairement les résonances, les fréquences de cassure et les pentes d'atténuation ($\pm40$ dB/décade).

## 🎓 Contexte Académique

Projet réalisé dans le cadre du module d'**Électronique Appliquée** (Master 1 Automatique et Informatique Industrielle - USTHB).

* **Présenté à :** Dr. Laib

## ⚡ Instructions de Déploiement (Important)

Ce projet est contenu dans un unique fichier HTML (Zéro dépendance locale). Pour un déploiement instantané sur GitHub Pages :

1. Déposez le fichier `index.html` à la racine de votre dépôt.
2. **Crucial :** Créez un fichier vide nommé exactement **`.nojekyll`** (n'oubliez pas le point) à la racine du dépôt. Cela force GitHub à contourner son moteur de build Jekyll, évitant ainsi les erreurs de déploiement et garantissant une mise en ligne en quelques secondes.
3. Dans les paramètres de votre dépôt (**Settings** > **Pages**), sélectionnez la branche `main` (ou `master`) et le dossier `/ (root)`, puis sauvegardez.

## 👨‍💻 Auteur

**Créé et développé par :** Dahane Ahmed Lamine
