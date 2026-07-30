# Smolov

Tracker web du programme de force **Smolov** (squat) — cycle complet de 13 semaines,
navigable semaine par semaine, avec suivi des séances complétées.

Site **100 % statique** : un seul fichier `index.html` (HTML/CSS/JS vanilla, aucune dépendance, aucun build).

## Fonctionnalités

- Cycle Smolov complet : introduction, mésocycle de base, transition/test, switching, mésocycle intense, affûtage + test final.
- Charges calculées depuis **deux 1RM** : le 1RM de départ (phases 1–5) et le 1RM post-base (phases 6–13, éditable).
- Charges arrondies au 5 kg inférieur, séries lourdes (≥ 90 %) mises en évidence.
- Suivi des séances (cases à cocher) + barres de progression, sauvegardés dans le navigateur (localStorage).
- Thème clair / sombre (bascule + respect de la préférence système, mémorisé).
- Calculateur de disques par côté (poids de barre réglable), codes couleur IPF.
- Application installable (PWA) + fonctionnement hors-ligne (service worker).
- Export calendrier (.ics) : les 40 séances avec rappels, importables dans l'app calendrier native.
- Icônes Lucide inline (aucune dépendance réseau).
- Timer de repos flottant (presets, ±15 s, bip + vibration en fin).
- Journal par séance : poids réellement soulevé + RPE + note, avec écart au poids prévu (vert/orange). Sauvegardé.
- Programme calé pour que le test final tombe le 31 décembre 2026 (dates de début modifiables).

## Utilisation locale

Ouvre simplement `index.html` dans un navigateur.

## Déploiement (Vercel)

Site statique sans build : sur Vercel, framework **Other**, aucune commande de build, dossier racine.
Chaque push sur `main` redéploie automatiquement.

---

Barème Smolov d'après liftosaur.com & liftvault.com.
