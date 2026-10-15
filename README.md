# Y-Turnover Management

Application de suivi du chiffre d'affaires et des bénéfices.

## Fonctionnalités principales

- **Logo officiel** de Y-Turnover
- **Plusieurs activités** organisées en **dossiers** (et sous-dossiers)
- **Déplacer** une activité ou un dossier (bouton ↔️)
- **Corbeille** avec restauration
- **Colonnes & formules** personnalisables
- **Saisie multi-lignes** : dans une case tu peux écrire plusieurs montants (Entrée) et le total est calculé automatiquement
- **Copier / Coller**
- **Undo / Redo / Sauvegarde** (↩️ ↪️ 💾)
- Confirmation avant toute suppression
- Export CSV + hors-ligne

## Saisie multi-lignes (nouveau)

Dans n’importe quelle case de saisie :

```
1525
1626
1727
```

→ La valeur de la colonne devient **4878** (somme automatique).  
Un petit total `Σ 4 878` s’affiche sous la case quand il y a plusieurs lignes.

Tu peux aussi séparer par des points-virgules : `1525;1626;1727`

## Formules supportées

- `C1 + C2 - C4`
- `C6 * 7%`
- `C6_prev` (ligne précédente)
- `round100(C6)` / `round(C6)`

## Installation

1. Ouvre `index.html` avec Chrome
2. Menu ⋮ → **Ajouter à l’écran d’accueil**
