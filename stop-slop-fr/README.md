# Stop Slop (français)

Un skill pour supprimer les marqueurs de l'IA dans les textes en français.

## Ce que c'est

L'écriture IA a des motifs : expressions prévisibles, structures, rythmes. En français, ces motifs sont propres à la langue — ce n'est pas une traduction des tics anglais. Ce skill apprend à Claude (ou tout LLM) à les repérer et les supprimer dans un texte français.

## Ce qui change par rapport à la version anglaise

Adaptation, pas traduction. Couvre les marqueurs spécifiques au français :

- **Connecteurs scolaires** sur-utilisés (« En outre », « Par ailleurs », « Force est de constater »).
- **Mots fétiches** de l'IA française (« crucial », « essentiel », « incontournable », « véritable »).
- **Anglicismes** et calques (« impacter », « adresser un problème », « faire du sens », « au final »).
- **Gérondif final** qui commente l'action (« …, ouvrant la voie à de nouvelles possibilités »).
- **Le « on » impersonnel** qui masque l'acteur, au même titre que la voix passive.
- **Phrases clivées** de remplissage (« Ce qu'il faut retenir, c'est… »).
- **Énumérations ternaires** par réflexe et fragmentation dramatique.
- **Typographie française** : guillemets « », espaces insécables avant `: ; ! ?`, tiret cadratin, virgule d'Oxford.
- **Formules de conclusion** automatiques (« En somme », « En définitive », « Vous l'aurez compris »).

## Structure

```
stop-slop-fr/
├── SKILL.md                  # Instructions de base
├── references/
│   ├── expressions.md        # Expressions à supprimer
│   ├── structures.md         # Motifs structurels à éviter
│   └── exemples.md           # Transformations avant/après
├── README.md
└── LICENSE
```

## Utilisation

- **Claude Code :** placer ce dossier dans `~/.claude/skills/`. Le skill se déclenche à la rédaction, l'édition ou la relecture d'un texte français.
- **Projets Claude :** téléverser `SKILL.md` et les fichiers de référence dans la base de connaissances.
- **Instructions personnalisées :** copier les règles de base de `SKILL.md`.
- **Appels API :** inclure `SKILL.md` dans le prompt système. Les fichiers de référence se chargent à la demande.

## Notation

Noter de 1 à 10 chaque dimension : franchise, rythme, confiance, authenticité, densité. En dessous de 35/50 : réviser.

## Crédits et licence

Adapté en français à partir de [stop-slop](https://github.com/hardikpandya/stop-slop) de [Hardik Pandya](https://hvpandya.com). Licence MIT — utilisez et partagez librement.
