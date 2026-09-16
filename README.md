# Lucas Guilhot

**Développeur full-stack** — produits web, APIs, données et automatisation
Toulouse / Remote · [lucasguilhot.fr](https://lucasguilhot.fr)

Je construis des produits web complets : interface, API, base de données et mise
en production. Une préférence pour ceux qui traitent de la donnée ou automatisent
quelque chose — là où la règle métier est plus difficile que l'écran.

Les cinq projets ci-dessous sont en ligne. Les chiffres sont mesurés, pas estimés :
comptes de tests exécutés, mesures de backtest, calculs exacts.

## Projets

### [RushPlay](https://github.com/lucas04022002/Saas) — analyse du marché des paris sportifs
[rushplay.fr](https://rushplay.fr) · Next.js · TypeScript · FastAPI · Python · PostgreSQL · Docker

Six sources de cotes collectées plusieurs fois par jour, dédupliquées, avec reprise
après panne. Le produit ne prédit rien : il montre ce que le marché dit, et où il se
contredit.

J'avais construit un modèle de prédiction. Testé hors échantillon sur 1 752 matchs
jamais vus, il faisait moins bien que le bookmaker — log-loss 1,004 contre 0,978,
rendement −5,6 %. Je l'ai retiré du produit. **267 tests automatisés**, accessibilité
100/100.

### [ApplyBot](https://github.com/lucas04022002/CandidatureIA) — SaaS B2B pour organismes de formation
[applybot.lucasguilhot.fr](https://applybot.lucasguilhot.fr) · Next.js · TypeScript · Node · PostgreSQL · Docker

Suivi de candidatures vendu à des organismes : trois rôles, sessions signées, places
et quotas, export et suppression des données sur demande. Sept sources d'offres
collectées et dédupliquées.

Le fournisseur d'IA a été retiré après mesure — il coûtait un abonnement par
utilisateur pour un résultat obtenu gratuitement ailleurs. Coût par candidature :
0 €. **202 tests automatisés.**

### [Le Local](https://github.com/lucas04022002/wildwalker) — réservation d'un tiers-lieu
[lelocal.lucasguilhot.fr](https://lelocal.lucasguilhot.fr) · React · TypeScript · Express · MySQL · Stripe · Docker

Projet d'équipe de ma formation, repris seul pour le rendre déployable : sécurité des
routes, migrations versionnées, concurrence sur les réservations, image Docker ramenée
de 113 Mo à 8,7 Mo. **213 tests ajoutés** là où il n'y en avait aucun.

### selv. — e-commerce cosmétique et moteur de recommandation
[selv.shop](https://selv.shop) · Shopify · Python · FastAPI · JavaScript · Docker

Marque créée et mise en ligne, 29 références. **SkinMatch**, le moteur intégré à la
boutique, construit une routine à partir d'un diagnostic. Le modèle de langage rédige
l'explication ; c'est le moteur qui choisit les produits — aucun produit n'est choisi
par le modèle, et un test le vérifie. **61 tests automatisés.**

### [Vault Rush](https://github.com/lucas04022002/vault-rush) — arcade en monnaie fictive
[vault-rush.lucasguilhot.fr](https://vault-rush.lucasguilhot.fr) · React · TypeScript · Express · SQLite · Docker

Sept jeux sur un moteur commun : ajouter un jeu demande trois fichiers neufs, pas une
refonte. Montants en centimes entiers, transactions en base. Le jeu de code est
calibré par énumération exacte de ses 5 040 combinaisons, le blackjack mesuré sur
40 000 mains simulées. **391 tests automatisés.**

## Stack

**Langages** — TypeScript, JavaScript, Python, Java, SQL
**Frontend** — React, Next.js, Angular, React Native, Tailwind
**Backend** — Node, Express, FastAPI, API REST, authentification et rôles
**Données** — PostgreSQL, MySQL, SQLite, migrations versionnées, pandas
**Livraison** — Docker, GitHub Actions, VPS et Coolify, tests automatisés

Les cinq produits tournent sur un seul VPS, déployés par webhook à chaque push.

## Contact

À la recherche d'un CDI ou d'un CDD, à Toulouse ou en remote.

[lucasguilhot.fr](https://lucasguilhot.fr) · [CV](https://lucasguilhot.fr/cv.pdf) ·
[LinkedIn](https://www.linkedin.com/in/guilhot-lucas) · lucasguilhot7@gmail.com
