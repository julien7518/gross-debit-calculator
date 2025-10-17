# 🧾 Gross Debit Calculator

Cette application web permet de calculer automatiquement le **Total Gross Debit (GC)** à partir d’un fichier CSV exporté depuis **Adyen** (logiciel hôtelier).

👉 [Accéder à l'application en ligne](https://gross-debit-calculator.vercel.app)

## 📂 Fonctionnement
1. Glissez ou importez votre fichier CSV (délimité par `;`).
2. L’application lit le fichier directement **dans votre navigateur**.
3. Le **total du champ “Gross Debit (GC)”** est calculé et affiché instantanément.
4. ⚠️ Aucune donnée n’est envoyée sur un serveur — tout est traité en local.

## 📊 Prérequis du fichier
- Format : `.csv`  
- Délimiteur : `;`  
- Doit contenir une colonne nommée **`Gross Debit (GC)`**

## 🚀 Utilisation
Ouvrez simplement le fichier `index.html` dans votre navigateur ou rendez-vous sur le lien hébergé ci-dessus pour utiliser l’outil.

---

🛡️ *Le traitement s'effectue entièrement côté client — aucune donnée n’est transmise ou stockée sur un serveur.*