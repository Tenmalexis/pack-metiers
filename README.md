# 🎒 Tenmalexis — Pack Métiers Tool

**Outil de calcul de rentabilité des Packs Métiers pour Dofus 3 (Unity)**

> Créé par [@Tenmalexis](https://www.youtube.com/@Tenmalexis) — YouTubeur Dofus

---

## 🔗 Accès direct

[👉 [Ouvrir le Pack Métiers Tool](Tenmalexis%20%E2%80%94%20Pack%20M%C3%A9tiers%20Tool.html)](https://tenmalexis.github.io/pack-metiers/%F0%9F%8E%92%20Tenmalexis%20%E2%80%94%20Pack%20M%C3%A9tiers%20Tool.html)

---

## 📌 C'est quoi ?

Cet outil permet de **calculer le coût total en ressources HDV** pour monter un Pack Métier Dofus de 0 à 200, et de le comparer au **prix de vente sur le marché** pour savoir instantanément si l'investissement est rentable. Tu renseignes les prix des ressources une fois, et l'outil calcule tout le reste automatiquement.

---

## ✅ Fonctionnalités

- 💰 **Table des prix HDV** — saisie centralisée des prix de toutes les ressources, regroupées par catégorie (Bois, Céréale, Divers, Minerai, Plante, Poisson, Viande)
- 📋 **Détail du Pack par tranche** — recettes et ressources nécessaires niveau par niveau (0-10, 10-20… jusqu'à 200)
- 🧮 **Décomposition consolidée** — quantité totale de chaque ressource, prix unitaire et coût total calculés automatiquement
- 🪙 **Récap multi-métiers** — vue synthétique de tous les packs avec coût HDV, prix marché, différence et écart %
- ⚡ **Mise à jour en temps réel** — les totaux se recalculent à chaque saisie sans perdre le focus du champ
- 💾 **Sauvegarde automatique** — les prix sont conservés dans le navigateur (localStorage), aucune perte entre les sessions
- 📤 **Export JSON** — exporte tous les prix dans un fichier horodaté pour les conserver ou les transférer
- 📥 **Import JSON** — recharge un fichier exporté précédemment en un clic
- 🖼️ **Images des ressources** — icônes chargées automatiquement depuis l'API Dofus

---

## 🎓 Les 6 métiers couverts

| Métier | Ressource principale | Tranches de niveau |
|--------|----------------------|--------------------|
| 🧪 Alchimiste | Plantes | 20 tranches de 10 niveaux (0 → 200) |
| 🪓 Bûcheron | Bois | 10 tranches de 20 niveaux (0 → 200) |
| 🍖 Chasseur | Viandes | 20 tranches de 10 niveaux (0 → 200) |
| 🌾 Paysan | Céréales | 20 tranches de 10 niveaux (0 → 200) |
| 🎣 Pêcheur | Poissons | 20 tranches de 10 niveaux (0 → 200) |
| ⛏️ Mineur | Minerais | 10 tranches (0 → 200) |

---

## 🗺️ Navigation

L'outil est organisé en **8 onglets** :

- `💰 Prix HDV` — point de départ : saisir les cours actuels de chaque ressource en K (milliers de kamas)
- `Alchimiste / Bûcheron / Chasseur / Paysan / Pêcheur / Mineur` — détail du pack + décomposition pour chaque métier
- `🪙 Récap` — tableau de bord comparant le coût HDV au prix de vente marché pour tous les métiers simultanément

---

## 💾 Gestion des prix

| Action | Description |
|--------|-------------|
| Auto-save | Les prix sont sauvegardés automatiquement dans le navigateur à chaque saisie |
| `📤 Export` | Télécharge les prix au format `pack_metiers_prix_YYYY-MM-DD.json` |
| `📥 Import` | Recharge un fichier JSON exporté précédemment |
| `🗑️ Reset` | Remet tous les prix à zéro (confirmation demandée) |

---

## ⚙️ Utilisation

Le fichier est un **HTML standalone** — il s'ouvre directement dans le navigateur, aucune installation requise.

- Les images des ressources sont chargées depuis `api.dofusdb.fr` — une connexion internet est nécessaire pour les afficher
- Les données sont basées sur **Dofus 3.5 (mars 2026)**
- Compatible avec tous les navigateurs modernes (Chrome, Firefox, Edge, Safari)

---

*Outil créé par **Tenmalexis** — [YouTube](https://www.youtube.com/@Tenmalexis) · [Twitch](https://www.twitch.tv/tenmalexis)*
