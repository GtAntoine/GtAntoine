![Banner](banner.jpg)


## 🚀 Portfolio de projets

<table>
<tr>
<td colspan="2" valign="top">

### <img src="https://github.com/GtAntoine/petcheri-public/raw/main/public/images/icon.png" alt="Pet Cheri" width="30" style="vertical-align: middle;"/> [Pet Cheri](https://github.com/GtAntoine/petcheri-public)
**CPTO · Marketplace de services pour animaux · Vitrine, web et mobile**

> Refonte complète d'une conciergerie animalière premium en quatre mois : **site vitrine, application web à trois portails (clients, prestataires, équipe) et application mobile**

**Innovation :** assistant IA **PACO** qui prépare les demandes, répond sur les données et rédige les tickets, sans jamais écrire seul (chaque action est confirmée d'un clic par l'humain) + facturation refondue avec la comptabilité (note mensuelle, avoirs, facture de commission figée, journal des ventes).

**Tech :** Next.js 16, React 19, TypeScript, Sequelize / MariaDB, Expo, Stripe, Brevo, OpenAI, Playwright, Sentry

**Compétences :**
- Design system « lux » commun aux trois portails, mode sombre par tokens
- Product Ownership : règles métier écrites avec la comptabilité, 98 pages spécifiées, 12 audits
- IA en production avec garde-fous (écriture confirmée, plafonds de coût)
- Qualité : 465 tests, près de 500 commits en quatre mois

[➡️ Voir le portfolio complet](https://github.com/GtAntoine/petcheri-public#-pet-cheri---case-study) · [🎨 Design system](https://app.petcheri.com/design) · [🌐 petcheri.com](https://petcheri.com)

</td>
</tr>
<tr>
<td colspan="2" valign="top">

### <img src="https://github.com/GtAntoine/ciel-cobalt-public/raw/main/public/images/icon.png" alt="Ciel Cobalt" width="30" style="vertical-align: middle;"/> [Ciel Cobalt](https://github.com/GtAntoine/ciel-cobalt-public)
**Jeu vidéo · Product Owner d'une équipe d'agents IA · Jouable dans le navigateur**

<p align="center"><a href="https://github.com/GtAntoine/ciel-cobalt-public"><img src="https://github.com/GtAntoine/ciel-cobalt-public/raw/main/public/images/01-boss-barrage.jpg" alt="Ciel Cobalt : un boss mécanique agrippé à un barrage de 108 mètres, en voxels" width="560"></a></p>

> Shoot'em up roguelite en voxels où **tout se casse** : barrage de 108 m, pont sous un convoi, volcan, porte-avions. **Une semaine, 144 commits, ~77 000 lignes de C#** : spécifié, arbitré et testé par moi, codé par des agents IA (Claude Code, Codex)

**Innovation :** le rôle de Product Owner appliqué à des agents IA : règles du projet chiffrées pour eux (« une vedette occupe plus de 15 % de l'écran »), planche de référence obligatoire avant chaque décor, revue par comparaison avant / après, plusieurs agents en parallèle sur le même dépôt avec une discipline de commit ligne à ligne.

**Tech :** Unity 6, URP, C#, moteur voxel maison (destruction par morceaux), génération procédurale seedée, eau en compute shader, Python (chaîne de voxélisation), WebGL · Tripo3D, Suno, synthèse vocale

**Compétences :**
- Product Ownership : GDD à cinq piliers, jalons à critère de fin, 39 décisions tracées avec alternatives et raisons
- Arbitrage par la donnée : durée d'une sortie mesurée par un pilote automatique, lisibilité raisonnée en % d'écran
- Qualité : 150 tests joués dans le moteur, Unity piloté en ligne de commande, preuve par capture
- Go-to-market : étude de 15 pages Steam d'indés, prix, calendrier, déclaration d'IA

[➡️ Voir le portfolio complet](https://github.com/GtAntoine/ciel-cobalt-public) · [🎮 Jouer](https://goethals.fr/ciel-cobalt/)

</td>
</tr>
<tr>
<td colspan="2" valign="top">

### <img src="https://github.com/GtAntoine/triolet/raw/main/site/public/favicon.svg" alt="Triolet" width="30" style="vertical-align: middle;"/> [Triolet](https://github.com/GtAntoine/triolet)
**Open source · npm · Icônes animées pour le web, React et React Native**

<p align="center"><a href="https://gtantoine.github.io/triolet/"><img src="https://github.com/GtAntoine/triolet/raw/main/docs/assets/icons.svg" alt="Seize icônes Triolet qui jouent leur geste : la cloche sonne, le calendrier se coche, le bulletin tombe dans l'urne..." width="560"></a></p>

> **435 icônes animées en trois couleurs**, publiées en trois paquets npm : `triolet` (JavaScript et CSS), `triolet-react` et `triolet-react-native`

**Innovation :** chaque icône se dessine dans trois couleurs au choix (base, principale, accent, en 60 / 30 / 10) avec un léger relief, et joue un petit geste qui dit à quoi elle sert : la cloche sonne, le bulletin tombe dans l'urne, les lignes s'écrivent. Une seule source par icône (dessin, parties mobiles, geste, mots-clés), tout le reste est généré.

**Tech :** TypeScript, CSS pur pour les gestes sur le web (aucune librairie d'animation), React 18 et 19, React Native Skia + Reanimated (gestes sur le thread UI), Astro pour le site, pnpm workspaces

**Compétences :**
- Design system : trois couleurs dont se déduisent teintes et relief, relief adapté à la taille (complet dès 40 px, simplifié dès 24 px, à plat en dessous)
- Motion design : un geste par icône, à l'arrêt quand l'utilisateur demande moins d'animation
- Chaîne de génération : une source par icône vers le SVG et les trois paquets
- Publication open source : paquets versionnés ensemble, changelog

[➡️ Voir les icônes](https://gtantoine.github.io/triolet/icons/) · [📦 npm](https://www.npmjs.com/package/triolet) · [💻 Code source](https://github.com/GtAntoine/triolet)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### <img src="https://github.com/GtAntoine/artnalyse-public/raw/main/public/images/icon.png" alt="Artnalyse" width="30" style="vertical-align: middle;"/> [Artnalyse](https://github.com/GtAntoine/artnalyse-public)
**App Store · Google Play · IA Vision & Culture**

> Pipeline IA : **GPT-5 Vision + reverse image search Google Lens + TTS streaming** pour analyser n'importe quelle oeuvre d'art

**Innovation :** Streaming NDJSON 5 sections en temps réel (identification → narration → points clés → anecdote → oeuvres similaires) + narration audio générée à la volée.

**Tech :** React Native, Expo, TypeScript, Supabase Edge Functions, OpenAI GPT-5 Vision, SerpAPI, OpenAI TTS

**Compétences :**
- Vision produit culturelle (musée dans la poche)
- Architecture IA streaming temps réel (NDJSON + XMLHttpRequest)
- Design "Le Vernissage" (noir profond + or champagne)
- Publication App Store + Google Play

[➡️ Voir le portfolio complet](https://github.com/GtAntoine/artnalyse-public#-artnalyse---case-study) · [📱 App Store](https://apps.apple.com/fr/app/artnalyse/id6762506288) · [🤖 Google Play](https://play.google.com/store/apps/details?id=fr.goethals.artnalyse)

</td>
<td width="50%" valign="top">

### <img src="https://github.com/GtAntoine/sapior-public/raw/main/public/images/icon.png" alt="Sapior" width="30" style="vertical-align: middle;"/> [Sapior](https://github.com/GtAntoine/sapior-public)
**App Store · Google Play · Philosophie & Audio**

> Application audio gamifiée : **catalogue de 170+ livres audio** avec quiz, progression et citations partageables

**Innovation :** Liquid Glass sur iOS 26, MiniPlayer natif intégré à la navigation, couleur de l'interface tirée de chaque couverture + téléchargement offline Cloudflare R2 + QCM auto-générés + partage visuel de citations.

**Tech :** React Native, Expo, TypeScript, Zustand, Cloudflare R2, expo-audio, Liquid Glass, BlurView

**Compétences :**
- Curation de contenu culturel (32 catégories)
- Architecture audio offline/streaming (R2 + expo-audio)
- Gamification de l'apprentissage (quiz, progression)
- Publication App Store + Google Play

[➡️ Voir le portfolio complet](https://github.com/GtAntoine/sapior-public#-sapior---case-study) · [📱 App Store](https://apps.apple.com/fr/app/sapior/id6761835272) · [🤖 Google Play](https://play.google.com/store/apps/details?id=fr.goethals.sapior)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### <img src="https://github.com/GtAntoine/tuteur-prive-public/raw/main/public/images/logo.png" alt="TuteurPrivé" width="30" style="vertical-align: middle;"/> [TuteurPrivé](https://github.com/GtAntoine/tuteur-prive-public)
**App Store iOS · IA Éducative**

> Pipeline IA : **GPT-5 Vision pour créer des exercices personnalisés à partir des leçons photographiés**

**Innovation :** Combine OCR manuscrit, vision par IA, et feedback pédagogique personnalisé en un seul flux utilisateur, avec une analyse en streaming dans l'app iOS (iPhone et iPad).

**Tech :** React, React Native, Expo, TypeScript, Supabase Edge Functions, OpenAI GPT-5 Vision, Lottie

**Compétences :**
- Vision produit disruptive
- Analyse concurrentielle vs Louxor.ai
- Roadmap en 4 phases (MVP → V2 → V3 → V4)
- Refonte UX/UI « Le Cahier Vivant »

[➡️ Voir le portfolio complet](https://github.com/GtAntoine/tuteur-prive-public?tab=readme-ov-file#-tuteurpriv%C3%A9---case-study) · [📱 App Store](https://apps.apple.com/fr/app/tuteurpriv%C3%A9/id6761138454)

</td>
<td width="50%" valign="top">

### 🌙 [NeuraDream](https://github.com/GtAntoine/neuradream-public?tab=readme-ov-file#-neuradream---case-study)
**Analyse de Rêves par IA**

> Application utilisant **GPT-4 et DALL-E 3** avec système unique de **multi-interprétations**

**Innovation :** 3-5 explications par aspect que l'utilisateur valide pour affiner l'IA progressivement. L'utilisateur devient acteur de son analyse.

**Tech :** React Native, Expo, TypeScript, IndexedDB, GPT-4, DALL-E

**Compétences :**
- Différenciation "IA qui apprend de vous"
- Système de validation utilisateur
- Architecture 3 niveaux (individuel, thématique, global)

[➡️ Voir le portfolio complet](https://github.com/GtAntoine/neuradream-public?tab=readme-ov-file#-neuradream---case-study)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### <img src="https://github.com/GtAntoine/invitemoi-public/raw/main/public/logo.png" alt="InviteMoi" width="30" style="vertical-align: middle;"/> [InviteMoi](https://github.com/GtAntoine/invitemoi-public)
**Learnings d'un Échec Instructif**

> Plateforme sociale de partage d'expériences culturelles

**Innovation :** Double système host/guest unique + swipe Tinder-like pour événements culturels + design glassmorphism.

**Tech :** React 18, TypeScript, Vite, Supabase, Framer Motion

**Learnings actionnables :**
- Marketplace = seuil critique (500+ users/ville)
- Sans budget marketing, pas de masse critique
- Seeding essentiel + focus géographique

[➡️ Voir le portfolio complet](https://github.com/GtAntoine/invitemoi-public?tab=readme-ov-file#-invitemoi---case-study)

</td>
<td width="50%" valign="top">

### ⛳ [AGSE Golf](https://github.com/GtAntoine/golf-agse-public?tab=readme-ov-file#-agse-golf---case-study)
**ROI & Pragmatisme Produit**

> Application de gestion d'adhésions pour association — **Approche Make vs Buy pragmatique**

**Contexte :** Remplace Google Forms + 3 Google Sheets pour gérer 100 membres.

**ROI :** **300€/an économisés** + contrôle total des données

**Adoption anticipée :** Lancement **6 mois en avance**

**Compétences :**
- Analyse comparative rigoureuse
- Force de proposition UX (validation client, multi-étape, admin dashboard)
- Évolutions 2026 : statistiques, journal d'audit, audit de sécurité

[➡️ Voir le portfolio complet](https://github.com/GtAntoine/golf-agse-public?tab=readme-ov-file#-agse-golf---case-study)

</td>
</tr>
</table>

