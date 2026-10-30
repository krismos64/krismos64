<picture>
  <source media="(prefers-color-scheme: dark)" srcset="banner-dark.svg">
  <img src="banner-light.svg" width="100%" alt="Christophe Mostefaoui, développeur fullstack Next.js et TypeScript. Du besoin métier à la mise en production. Pau, Tarbes, Orthez.">
</picture>

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/christophemostefaoui/)
[![Portfolio](https://img.shields.io/badge/Portfolio-FF5722?style=for-the-badge&logo=googlechrome&logoColor=white)](https://krismos.fr/)
[![Site freelance](https://img.shields.io/badge/Site_freelance-24292F?style=for-the-badge&logo=googlechrome&logoColor=white)](https://christophe-dev-freelance.fr/)

</div>

## À propos

Développeur fullstack **Next.js · TypeScript · Node.js**, titulaire du titre **CDA spécialité IA** (Concepteur Développeur d'Applications, bac+3) obtenu à La Fabrique Numérique Paloise.

Avant le développement, j'ai passé 12 ans en grande distribution et, en parallèle, 10 ans dans la gestion administrative de l'entreprise familiale, où j'ai automatisé la facturation sous Excel. Je sais ce qu'un logiciel change au quotidien pour ceux qui l'utilisent.

Je conçois, développe et exploite mes applications seul, du recueil du besoin à la mise en production.

## Projets

### SmartPlanning

<a href="https://smartplanning.fr">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="smartplanning-dark.svg">
    <img src="smartplanning-light.svg" width="100%" alt="Aperçu animé de SmartPlanning : planning de semaine par équipe, demande de congé validée, notifications en temps réel.">
  </picture>
</a>

[smartplanning.fr](https://smartplanning.fr) · [Code source](https://github.com/krismos64/SmartplanningAI-V2)

SaaS multi-entreprise de gestion des plannings et des congés d'équipe, en production.

- **Stack** : Next.js · React · TypeScript · PostgreSQL · Prisma · Redis · Stripe
- **Fonctionnel** : rôles direction, manager et employé, planning en glisser-déposer, workflow de congés, messagerie et notifications temps réel (SSE), abonnement Stripe par employé
- **Sécurité** : contrôle d'accès par rôle, isolation stricte entre entreprises, validation Zod, limitation de débit sur Redis
- **Production** : CI/CD GitHub Actions vers Docker sur VPS OVH, retour arrière automatique si le contrôle de santé échoue, sauvegardes chiffrées copiées hors site

### Lune-soleil

<a href="https://lune-soleil.fr">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="lune-soleil-dark.svg">
    <img src="lune-soleil-light.svg" width="100%" alt="Aperçu animé du parcours d'achat de Lune-soleil : fiche produit, panier, paiement, facture, expédition.">
  </picture>
</a>

[lune-soleil.fr](https://lune-soleil.fr) · [Code source](https://github.com/krismos64/lune-soleil)

Boutique e-commerce sur mesure pour une créatrice de bijoux artisanaux du Béarn : catalogue, paiement, stock partagé entre le site et les marchés, facturation, expédition.

- **Stack** : Next.js · TypeScript strict · PostgreSQL · Prisma · Better Auth (passkeys) · Stripe
- **Paiement fiable** : réservation atomique des pièces uniques, webhooks signés et idempotents, montants en centimes, factures immuables
- **Usage réel** : back-office conçu pour le smartphone, utilisable sur les marchés
- **Conformité** : droit de rétractation, médiation de la consommation, RGPD

## Ma façon de travailler

- **Tests bloquants en CI** (Vitest, Playwright, axe-core) et mutation testing pour vérifier que les tests détectent vraiment les défauts
- **Décisions d'architecture documentées** (ADR) et journal de développement
- **Déploiement continu** avec retour arrière, sauvegardes dont la restauration est testée
- **Incidents analysés** jusqu'à leur cause, corrigés et documentés
- **Agile / Scrum** avec Jira et Confluence
- **Développement assisté par IA encadré** : règles de projet, hooks de vérification, revue systématique

## Stack

<div align="center">

![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=next.js&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)
![Framer Motion](https://img.shields.io/badge/Framer_Motion-0055FF?style=flat-square&logo=framer&logoColor=white)

![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=node.js&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=flat-square&logo=prisma&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![Stripe](https://img.shields.io/badge/Stripe-635BFF?style=flat-square&logo=stripe&logoColor=white)
![Zod](https://img.shields.io/badge/Zod-3E67B1?style=flat-square&logo=zod&logoColor=white)

![Vitest](https://img.shields.io/badge/Vitest-6E9F18?style=flat-square&logo=vitest&logoColor=white)
![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=flat-square&logo=playwright&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

</div>

## Parcours

- **CDA spécialité IA** (Concepteur Développeur d'Applications, bac+3) · La Fabrique Numérique Paloise · 2024 – 2026
- **DWWM** (Développeur Web et Web Mobile, bac+2) · Studi · 2022 – 2023
- **Avant le développement** : 12 ans en grande distribution et, en parallèle, 10 ans de gestion administrative dans l'entreprise familiale

