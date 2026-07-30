# Smolov

Tracker web du programme de force **Smolov** (squat) — cycle complet de 13 semaines,
navigable semaine par semaine, avec suivi des séances complétées.

Site **100 % statique** : un seul fichier `index.html` (HTML/CSS/JS vanilla, aucune dépendance, aucun build).

## Fonctionnalités

- Cycle Smolov complet : introduction, mésocycle de base, transition/test, switching, mésocycle intense, affûtage + test final.
- Charges calculées depuis **deux 1RM** : le 1RM de départ (phases 1–5) et le 1RM post-base (phases 6–13, éditable).
- Charges arrondies au 2,5 kg, séries lourdes (≥ 90 %) mises en évidence.
- Suivi des séances (cases à cocher) + barres de progression, sauvegardés dans le navigateur (localStorage).
- Programme calé pour que le test final tombe le 31 décembre 2026 (dates de début modifiables).

## Utilisation locale

Ouvre simplement `index.html` dans un navigateur.

## Déploiement (Vercel)

Site statique sans build : sur Vercel, framework **Other**, aucune commande de build, dossier racine.
Chaque push sur `main` redéploie automatiquement.

---

Barème Smolov d'après liftosaur.com & liftvault.com.
