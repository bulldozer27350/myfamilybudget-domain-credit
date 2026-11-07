# Release Notes — Silo Crédit (domain-credit)

Toutes les versions publiées de ce dépôt respectent la spécification [SemVer 2.0.0](https://semver.org/lang/fr/).

---

## [0.0.2-SNAPSHOT] - En cours

### Type de release
**Documentation** (aucun changement de comportement métier)

### Résumé
Ajout de la Software Requirements Specification (`doc/srs.adoc`) et de l'Interface
Requirements Specification (`doc/irs.adoc`) du silo Crédit, formalisant les exigences
fonctionnelles, non fonctionnelles et d'interface déjà implémentées par `credit-api` et
`credit-core`. Bump de version de développement continu vers `0.0.2-SNAPSHOT`.

### Changements par composant
- **`credit-api`** : aucun changement de code (uniquement le bump de version).
- **`credit-core`** : aucun changement de code (uniquement le bump de version).
- **Documentation** : `doc/srs.adoc` (29 exigences fonctionnelles, 12 exigences non
  fonctionnelles) et `doc/irs.adoc` (13 exigences d'interface silo ↔ application
  MyFamilyBudget).

### Rétro-compatibilité & Compatibilité binaire
Totale : aucune modification de code, uniquement de la documentation et un bump de version de
développement continu.

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