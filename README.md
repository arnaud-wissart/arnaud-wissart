# Arnaud Wissart

### Développeur .NET senior — applications métier, modernisation & CI/CD

Je conçois, modernise et industrialise des applications professionnelles en **C# / .NET**, de l’API au front-end, avec une attention particulière portée à la **maintenabilité**, aux **tests**, à la **sécurité** et à la **livraison reproductible**.

Mon parcours couvre aussi bien la création de nouveaux produits que la reprise de systèmes existants, la migration de patrimoines .NET Framework vers des stacks modernes et l’intégration progressive de pratiques CI/CD.

**Portfolio :** https://arnaudwissart.fr  
**LinkedIn :** https://www.linkedin.com/in/arnaud-wissart-67a2a065/  
**Organisation de projets publics :** https://github.com/arnaud-wissart-lab

---

## Projets principaux

### BikeVoyager
**Application full-stack .NET 10 / React de planification d’itinéraires vélo.**

BikeVoyager est aujourd’hui mon projet public le plus complet pour illustrer une architecture full-stack moderne : API ASP.NET Core versionnée, React/TypeScript, moteur de routage Valhalla, POI via Overpass, synchronisation Google Drive / OneDrive, sécurité applicative, tests et déploiement automatisé.

Points clés :
- ASP.NET Core `.NET 10`, Minimal APIs et architecture Domain / Application / Infrastructure ;
- React, TypeScript, Vite, Mantine et Cesium ;
- Valhalla, Overpass, Google Drive et Microsoft Graph ;
- CORS contrôlé, origin guard, cookies HttpOnly, rate limiting et headers de sécurité ;
- xUnit, Vitest et Playwright E2E ;
- .NET Aspire, Docker Compose et GitHub Actions ;
- déploiement reproductible sur runner Linux self-hosted.

**Démo :** https://bike.arnaudwissart.fr  
**Code :** https://github.com/arnaud-wissart-lab/BikeVoyager

---

### BlazorEnterpriseStarter
**Socle applicatif métier Blazor / ASP.NET Core prêt à être repris.**

Starter .NET structuré autour d’une Blazor Web App, d’une API ASP.NET Core séparée, de contrats partagés et d’un module backlog complet avec recherche, filtres, pagination et CRUD.

Points clés :
- Blazor Web App + API ASP.NET Core séparée ;
- EF Core / SQLite ;
- design system et composants réutilisables ;
- .NET Aspire et Docker ;
- tests unitaires, composants et E2E Playwright ;
- GitHub Actions pour compilation, tests et validation Docker.

**Démo :** https://blazor.arnaudwissart.fr/  
**Code :** https://github.com/arnaud-wissart-lab/blazor-enterprise-starter

---

### Orymessa
**Produit logiciel commercial privé en préparation pour Steam.**

Orymessa est une application desktop multiplateforme développée en **.NET / Avalonia**, destinée à Windows, Linux et SteamOS. Le projet est volontairement privé car il est conçu pour être commercialisé.

Il me permet de travailler sur un cycle produit beaucoup plus large que le seul développement fonctionnel : architecture, UX souris/clavier/tactile/manette, lecture multimédia, persistance sécurisée, enregistrement et planification, localisation, packaging autonome, CI/CD et préparation Steamworks.

**Code source privé en vue de la commercialisation.**

---

## Desktop / industrie

### LayupPulse
Démonstrateur Windows `.NET 10 / WPF` consacré à l’architecture d’une supervision autour d’une **cellule fictive** de drapage composite.

Le projet sépare simulateur et interface via gRPC, traite une télémétrie simulée, persiste l’historique dans SQLite, produit des rapports de cycle et dispose d’un packaging Windows autonome.

LayupPulse utilise uniquement des données simulées et **ne commande aucun équipement réel**.

**Version Windows :** https://github.com/arnaud-wissart-lab/layup-pulse/releases/tag/v0.4.0  
**Code :** https://github.com/arnaud-wissart-lab/layup-pulse

---

## Outillage / automatisation

### RepoOps
Socle d’automatisation pour la maintenance de dépôts GitHub : worker .NET, GitHub API, Renovate, Dependabot, Docker Compose, n8n, Aspire, reporting et supervision.

Le projet expérimente également une chaîne de décisions structurées et de génération de prompts pour Codex, avec **validation humaine conservée avant toute action**.

**Code :** https://github.com/arnaud-wissart-lab/repo-ops

---

## Autres réalisations

| Projet | Type | Accès |
|---|---|---|
| OnigiriShop | Application e-commerce .NET 8 / Blazor Server / Dapper / SQLite | [Démo](https://onigirishop.onrender.com/) · [Code](https://github.com/arnaud-wissart-lab/OnigiriShop) |
| WattPilot (`NVConso`) | Utilitaire Windows .NET 10 / WPF pour suivre et limiter la puissance d’un GPU NVIDIA | [Télécharger / Code](https://github.com/arnaud-wissart-lab/NVConso) |
| Tetrigular | Jeu Angular / TypeScript avec moteur découplé et rendu Canvas 2D | [Démo](https://tetris.arnaudwissart.fr) · [Code](https://github.com/arnaud-wissart-lab/Tetrigular) |
| Probabilités Loto / EuroMillions | Plateforme .NET 10 / Blazor / PostgreSQL d’ingestion et de statistiques | [Démo](https://loto.arnaudwissart.fr) · [Code](https://github.com/arnaud-wissart-lab/Proba-loto-euromillions) |

---

## Expertise

- **Back-end :** C#, .NET Framework, .NET 6–10, ASP.NET Core, Web API REST, gRPC
- **Données :** SQL Server, PostgreSQL, SQLite, Entity Framework Core, Dapper
- **Front-end :** React, TypeScript, JavaScript, Angular, Blazor, WPF
- **Architecture :** séparation des couches, SOLID, clean architecture, design patterns, modernisation de legacy
- **Qualité :** tests unitaires, intégration, E2E, Playwright, non-régression, documentation
- **DevOps :** GitHub Actions, CI/CD, Docker, Docker Compose, runners self-hosted, packaging et déploiements reproductibles
- **Orchestration / tooling :** .NET Aspire, Renovate, Dependabot, n8n

---

## Ma manière de travailler

- comprendre d’abord le besoin métier et les contraintes réelles ;
- préférer une architecture proportionnée à la complexité effective ;
- moderniser progressivement plutôt que réécrire sans nécessité ;
- garder le code lisible, testable et exploitable ;
- automatiser build, tests, audits et déploiements lorsque cela apporte un gain réel ;
- documenter les décisions importantes et les limites connues ;
- conserver une vision utilisateur du produit jusqu’à la livraison.

---

## Contact

**Portfolio :** https://arnaudwissart.fr  
**LinkedIn :** https://www.linkedin.com/in/arnaud-wissart-67a2a065/  
**Projets publics :** https://github.com/arnaud-wissart-lab
