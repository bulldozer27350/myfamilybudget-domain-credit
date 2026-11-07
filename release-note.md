# Release Notes — Silo Crédit (domain-credit)

Toutes les versions publiées de ce dépôt respectent la spécification [SemVer 2.0.0](https://semver.org/lang/fr/).

---

## [0.0.1] - 2026-11-07

### Type de release
**Version initiale** (mise en place et validation de la structure autonome multi-dépôts)

### Résumé
Première version stable du silo Crédit (`domain-credit`), regroupant `credit-api` et `credit-core` avec import du BOM centralisé, cycle de build autonome et configuration de déploiement GitHub Packages.

### Changements par composant
- **`credit-api`** : Contrats d'interfaces de calcul de conseil sur les prêts et modèles de données (aucun changement métier).
- **`credit-core`** : Moteur de conseil (`DefaultLoanAdviceCalculationService`) et persistance JPA des prêts (`credit_loan`, `loan_advice_settings`).

### Rétro-compatibilité & Compatibilité binaire
Non applicable : version initiale, aucune version antérieure publiée.