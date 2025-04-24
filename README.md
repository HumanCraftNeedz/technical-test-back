# 🧪 Test technique – Développeur·se Backend chez HumanCraft

Bonjour et bienvenue ! 👋

Si vous êtes ici, c’est que nous avons souhaité poursuivre ensemble le processus de recrutement — et nous en sommes ravis !

Ces 2 tests ont pour objectif d’évaluer vos compétences techniques ainsi que votre manière d’aborder le développement de nouvelles fonctionnalités dans le cadre d’une application. Il couvre plusieurs aspects clés du métier de développeur·se backend.

---

## 🗂️ Modalités générales

- Il n’y a **pas de limite de temps imposée**, mais nous vous demandons de nous transmettre vos propositions avant votre prochain entretien à :  
  📩 `vthomas@humancraft.eu` et `lelkasm@humancraft.eu` 

- Nous discuterons ensemble de vos propositions lors de l’entretien

- Le fichier `needs.openapi.yaml` fourni contient les **spécifications OpenAPI** définissant les routes à implémenter.

👉 En cas de question ou de doute, n’hésitez pas à nous écrire aux adresses ci-dessus — nous serons ravis de vous répondre !

---

## 1️⃣ Test #1 – Développement d’une fonctionnalité

Ce test est le plus complet. Nous attendons de vous la **production de code** sur la base des spécifications fournies.

### 🎯 Consignes

- Certaines routes nécessitent une authentification. **Le système d’authentification ne fait pas partie du périmètre** de ce test.
- Le développement devra être réalisé avec le **framework Symfony (PHP)**.
- Le choix du moteur de base de données est **libre** (MySQL, PostgreSQL, SQLite, etc.).
- Le rendu doit être effectué sous la forme d’un **repository GitHub**.

🔎 Si vous avez l’habitude de travailler en TDD ou avec des tests automatisés, n’hésitez pas à les inclure dans votre développement : cela nous donnera un aperçu de votre rigueur et de vos pratiques de qualité logicielle.

L’objectif est d’évaluer **votre manière de structurer, prioriser, modéliser et implémenter une solution**.

---

## 2️⃣ Test #2 – Conception fonctionnelle (pas de code à produire)

Ce second test est plus rapide et ne nécessite pas d’écrire du code mais plutôt de nous expliquer comment vous concevriez et mettriez en œuvre cette nouvelle fonctionnalité.

### 🎯 Contexte

Nos partenaires ESN déposent les CV de leurs candidat·es sur notre plateforme pour répondre à des appels d’offres.  
Nous avons déjà mis en place un outil de **parsing IA** permettant de préremplir les champs du profil (contact, expériences, diplômes, etc.).

Actuellement, seul un **CV à la fois** peut être traité, et cette tâche **bloque l’accès** aux autres fonctionnalités de la plateforme.

Nous souhaitons :

- Permettre la **dépose et le traitement de CV en masse** ;
- Garantir un **fonctionnement asynchrone** pour ne pas perturber la navigation.

### 📌 Votre mission

- Décrire les grandes étapes de votre approche : par quoi commenceriez-vous ? quelles décisions techniques prendriez-vous ?
- Présenter les éléments clés à mettre en place, en expliquant leur rôle (ex. : gestion de l’envoi des fichiers, traitement en arrière-plan, retour à l’utilisateur, suivi du traitement, etc.).
- Vous pouvez utiliser le format de votre choix : texte, schéma, présentation, document structuré…
- Mettez-vous dans la peau d’un·e développeur·se qui doit expliquer sa solution à un membre de l’équipe Produit : soyez clair, synthétique, et montrez votre capacité à structurer une réponse sans entrer dans les détails de l’implémentation technique.
- N’hésitez pas à faire vos propres hypothèses sur le contexte technique ou fonctionnel (par exemple sur le volume de CV à traiter, les technologies utilisées, etc.), à condition de bien les expliciter dans votre livrable.

---

## 🧠 Ce que nous évaluons à travers ces tests

Nous porterons une attention particulière à :

- Votre **vision de la structuration du travail technique** ;
- Votre **autonomie dans la mise en œuvre** ;
- Votre capacité à **modéliser, vulgariser et proposer une solution cohérente** ;
- Votre **esprit de synthèse et vos qualités de communication**.

---

Bonne chance et à très vite ! 💪  
— L’équipe HumanCraft
