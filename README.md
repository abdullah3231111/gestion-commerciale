# 🛠️ Gestion Commerciale — TechShop

Application privée de gestion commerciale pour boutique de réparation et vente de matériel.

## 🔐 Connexion
Mot de passe par défaut : `admin2024`  
*(modifiable dans `src/App.jsx`, ligne : `const PASSWORD = "admin2024"`)*

## ✨ Fonctionnalités
- Tableau de bord temps réel
- Gestion du stock avec marges
- Vente rapide (clic → vendu)
- Gestion des réparations
- Statistiques financières + rentabilité mensuelle
- Historique filtrable (jour / semaine / mois / année)
- Charges fixes intégrées (loyer 1 580 € + électricité 30 €)
- Paiements espèces / CB séparés
- Données sauvegardées automatiquement (localStorage)

## 🚀 Déploiement rapide

### Option A — StackBlitz (aucune installation)
1. Aller sur [stackblitz.com](https://stackblitz.com)
2. Cliquer **"Import from GitHub"**
3. Coller l'URL de ce repo → l'app démarre automatiquement

### Option B — Vercel (recommandé pour accès permanent)
1. Aller sur [vercel.com](https://vercel.com)
2. **"Add New Project"** → importer ce repo GitHub
3. Framework : **Vite** (détecté auto)
4. Cliquer **Deploy** → URL publique en 1 minute

### Option C — En local
```bash
npm install
npm run dev
```
Ouvrir [http://localhost:5173](http://localhost:5173)

## 📁 Structure
```
src/
  App.jsx      ← Application complète
  main.jsx     ← Point d'entrée React
index.html
vite.config.js
package.json
```
