# Almanack PlaZma — Project Brain
> Encyclopédie LoL de la PlaZma · VinX Labs · v0.1

---

## 🌟 North Star

**Ce qu'on construit** : Un vault Obsidian de connaissance collective sur LoL — stratégie, psychologie, draft, macro — propre à notre façon de jouer.

**Pour qui** : Les membres de la PlaZma. Pas pour les casuals.

**Pourquoi maintenant** : La connaissance est dispersée dans des heads et des chats Discord. Il faut un seul endroit, toujours à jour, consultable avant une session.

**Succès à 6 mois** : Chaque joueur peut ouvrir le vault avant une game et calibrer son mindset / draft en 5 minutes.

---

## 📍 Où j'en suis

> ⬆️ **Mis à jour à chaque fin de session. C'est la première chose à lire au retour.**

```
[27/08/2026 — init]
✅ Fait :     Structure complète du vault créée, tous les fichiers v0.1 rédigés
🔜 Next :     Réviser chaque fichier avec l'équipe · Ajouter 03_Maths_&_Stats · Peupler 06_Champions
🤖 AI :       Demandé → Créer le vault · Codé → Tous les .md · ⚠️ Divergence → —
🚧 Bloqué :   06_Champions — structure à définir par rôle ou par champion ?
```

---

## ⚡ Focus maintenant

> **3 items maximum.** Tout le reste attend dans le Backlog.

- [ ] Review collective des profils (01) — chaque joueur valide son archétype
- [ ] Peupler 03_Maths_&_Stats — gold leads, breakpoints, timing math
- [ ] Définir la structure de 06_Champions

---

## 📋 Backlog vivant

### Up next
- Ajouter des notes de session post-scrim dans chaque section concernée
- Créer des templates de scrim review
- Lier les profils aux compos de draft (qui joue quoi selon son archétype)
- Ajouter des exemples de pro play annotés
- Section 07_Scrim_Review à créer

### Someday / Maybe
- Intégration avec un tracker de stats d'équipe
- Flashcard system pour les concepts macro

---

## 🧠 Décisions techniques (ADR)

> Format : `Contexte → Options → Choix → Pourquoi → Implémenté dans → Note`

---

### ADR-001 : Format des fichiers
Date : 27/08/2026 | Statut : Actif

**Contexte** : Quel format pour que le vault soit lisible en dehors d'Obsidian (GitHub, éditeur simple) ?
**Options** : Markdown pur / Markdown + syntaxe Obsidian / Notion
**Choix** : Markdown avec `[[wikilinks]]` Obsidian
**Pourquoi** : On reste dans Git, consultable partout, Obsidian les résout proprement
**Implémenté dans** : Tous les fichiers .md
**Note** : Les `[[liens]]` apparaissent en texte brut sur GitHub — acceptable

---

### ADR-002 : Langue
Date : 27/08/2026 | Statut : Actif

**Contexte** : FR ou EN ?
**Options** : Français / Anglais / Mixte (termes LoL EN, prose FR)
**Choix** : Français avec terminologie LoL en anglais
**Pourquoi** : L'équipe pense en français, les termes LoL sont universellement en anglais
**Implémenté dans** : Tous les fichiers
**Note** : —

---

## ⚠️ Risques actifs

| # | Risque | P | I | Score | Action |
|---|--------|---|---|-------|--------|
| R01 | Vault pas maintenu → connaissances qui pourrissent | H | H | HH | Assigner un "vault keeper" par saison |
| R02 | Profils psychologiques pas acceptés par les joueurs | M | H | MH | Review collective obligatoire |
| R03 | Structure trop rigide → freins à l'ajout de contenu | M | M | MM | Garder les templates légers |

### Risques archivés
*(vide)*

---

## 📅 Jalons

| Jalon | Date cible | Statut |
|-------|-----------|--------|
| J0 — Kick-off vault | 27/08/2026 | ✅ |
| J1 — Review collective des profils | TBD | ⏳ |
| J2 — Maths & Stats + Champions | TBD | ⏳ |
| JN — Vault "production ready" | TBD | ⏳ |

---

*VinX Method v1.0 · haitodann@gmail.com*
