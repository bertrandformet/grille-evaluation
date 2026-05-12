# Grille d'évaluation d'un outil numérique éducatif

Outil d'évaluation interactif basé sur le cadre **Utilité / Utilisabilité / Acceptabilité** de Tricot et al. (2003).

🔗 **[Accéder à la grille en ligne →](https://bertrandformet.github.io/grille-evaluation/)**

---

## Présentation

Cette grille permet d'évaluer de façon structurée un outil numérique utilisé en contexte éducatif, selon trois dimensions issues de la recherche en EIAH (Environnements Informatiques pour l'Apprentissage Humain) :

| Dimension | Critères | Score max |
|---|---|---|
| 🎯 **Utilité** | L'outil fait-il vraiment apprendre ? | 20 pts |
| 🖱️ **Utilisabilité** | L'outil est-il facile à utiliser ? | 24 pts |
| ✅ **Acceptabilité** | L'outil s'intègre-t-il bien dans le contexte scolaire ? | 20 pts |
| | **Total** | **64 pts** |

Chaque critère est noté de 1 (insuffisant) à 4 (très bien). La grille calcule les scores en temps réel et permet d'exporter la trace d'évaluation.

---

## Fonctionnalités

- **Interface interactive** : clic sur les scores, calcul automatique, barres de progression
- **Champs libres** : observations par section, verdict final
- **Export .txt** : téléchargement direct de la grille renseignée
- **Export .pdf** : génération PDF côté navigateur, sans serveur
- **Grille vierge** : version PDF imprimable disponible dans `/docs`
- **Autonome** : un seul fichier HTML, aucune dépendance externe, fonctionne hors ligne

---

## Utilisation

### En ligne
Rendez-vous sur la page GitHub Pages du projet et utilisez la grille directement dans votre navigateur.

### En local
```bash
git clone https://github.com/[votre-compte]/[nom-du-repo].git
cd [nom-du-repo]
# Ouvrir index.html dans un navigateur
open index.html
```

Aucune installation requise.

---

## Structure du dépôt

```
.
├── index.html                         # Grille interactive (page principale)
├── grille_evaluation_EIAH_vierge.pdf  # Version vierge imprimable
└── README.md
```

---

## Fondement théorique

> Tricot, A., Plégat-Soutjis, F., Camps, J.-F., Amiel, A., Lutz, G. & Morcillo, A. (2003).  
> « Utilité, utilisabilité, acceptabilité : interpréter les relations entre trois dimensions de l'évaluation des EIAH ».  
> *Environnements Informatiques pour l'Apprentissage Humain*, Strasbourg, pp. 391-402.  
> [https://edutice.hal.science/edutice-00000154](https://edutice.hal.science/edutice-00000154)

Le modèle distingue trois niveaux d'évaluation complémentaires :
- **Utilité** : l'outil permet-il d'atteindre les objectifs d'apprentissage visés ?
- **Utilisabilité** : l'outil est-il ergonomique et accessible pour les utilisateurs cibles ?
- **Acceptabilité** : l'outil s'inscrit-il dans les contraintes réelles du contexte d'usage (institution, matériel, temps) ?

---

## Publication sur GitHub Pages

1. Renommer `grille_evaluation_EIAH.html` en `index.html`
2. Pousser sur GitHub
3. Dans *Settings → Pages*, sélectionner la branche `main` et le dossier `/ (root)`
4. La grille est accessible à `https://[votre-compte].github.io/[nom-du-repo]/`

---

## Licence

[MIT](LICENSE) — libre d'utilisation, de modification et de redistribution, y compris en contexte professionnel et institutionnel.
