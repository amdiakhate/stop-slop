---
name: stop-slop-fr
description: Élimine les tics d'écriture de l'IA dans les textes en français. À utiliser lors de la rédaction, l'édition ou la relecture d'un texte français pour supprimer les marqueurs prévisibles de l'IA (amorces creuses, connecteurs scolaires, mots fétiches, jargon, anglicismes, gérondifs finaux, faux contrastes, voix passive, « on » impersonnel, énumérations ternaires, mise en forme et typographie).
metadata:
  trigger: Rédaction de prose, édition de brouillons, relecture pour repérer les marqueurs IA en français
  author: Adapté en français à partir de stop-slop de Hardik Pandya (https://hvpandya.com) — licence MIT
---

# Stop Slop (français)

Supprimer les marqueurs prévisibles de l'écriture IA dans un texte français.

Cette adaptation cible les tics propres au français, pas une traduction des règles anglaises. Le français a ses propres amorces, son jargon, ses anglicismes et ses structures (gérondif final, clivées « c'est… que », « on » impersonnel, énumérations ternaires, typographie).

## Règles de base

1. **Couper le remplissage.** Supprimer les amorces creuses (« il est important de noter que »), les béquilles d'emphase, les connecteurs scolaires en série et tous les adverbes en -ment. Voir [references/expressions.md](references/expressions.md).

2. **Casser les structures formulaïques.** Éviter les faux contrastes (« ce n'est pas X, c'est Y »), les énumérations par la négation, la fragmentation dramatique, les questions rhétoriques de relance, le gérondif final qui commente l'action, l'agentivité factice. Voir [references/structures.md](references/structures.md).

3. **Voix active, acteur nommé.** Chaque phrase a un sujet humain qui agit. Pas de voix passive (« la décision a été prise »). Pas de « on » qui masque l'acteur (« on observe que »). Pas d'objet inanimé qui agit (« la donnée nous dit »).

4. **Bannir les anglicismes et les calques.** « impacter », « adresser un problème », « faire du sens », « au final », « basé sur », « en charge de ». Voir [references/anglicismes.md](references/anglicismes.md).

5. **Être précis.** Pas de déclaration vague (« les enjeux sont considérables »). Nommer la chose précise, donner un chiffre, un nom, une date. Pas d'extrêmes faciles (« tous », « toujours », « jamais ») qui font un travail vague.

6. **Tuer les mots fétiches.** « crucial », « essentiel », « incontournable », « riche », « robuste », « fascinant », et surtout « véritable ». Voir [references/expressions.md](references/expressions.md).

7. **Mettre le lecteur dans la scène.** Pas de voix de narrateur surplombant. « Vous » vaut mieux que « les gens ». Le concret bat l'abstrait.

8. **Varier le rythme.** Mélanger les longueurs de phrases. Deux éléments valent mieux que trois (méfiance des énumérations ternaires). Varier les fins de paragraphe. Pas de tiret cadratin.

9. **Dégonfler la mise en forme.** Pas d'emoji décoratifs, pas de gras systématique « **Titre :** » devant chaque puce, pas de liste à puces par réflexe quand une phrase suffit, pas de paragraphes tous de même longueur. Voir la section « Mise en forme » dans [references/structures.md](references/structures.md).

10. **Faire confiance au lecteur.** Énoncer les faits directement. Pas d'atténuation, pas de justification, pas de prise par la main. Pas de conclusion qui se contente de résumer.

Le ton se règle selon le type de texte (article, e-mail, post, doc technique) : voir [references/registres.md](references/registres.md).

## Comment l'appliquer (méthode)

1. **Lire en entier d'abord.** Comprendre l'intention et la voix de l'auteur avant de couper quoi que ce soit.
2. **Diagnostiquer par passes ciblées.** Remplissage et adverbes → structures (faux contrastes, gérondif, passif, « on ») → anglicismes → mise en forme.
3. **Réécrire phrase par phrase.** Couper le superflu, nommer l'acteur, remplacer le vague par le fait précis déjà présent dans le texte.
4. **Vérifier le sens.** La version réécrite dit-elle exactement la même chose ? Aucun fait, chiffre ou nuance ajouté ni perdu.
5. **Vérifier le rythme et la forme.** Longueurs de phrases variées (pas de staccato), mise en forme sobre, typographie française.
6. **Noter.** Utiliser la grille ci-dessous. Sous le seuil, refaire une passe.

## Garde-fous (ne pas sur-corriger)

- **Préserver le sens et les faits.** Ne jamais inventer un chiffre, un nom ou une nuance pour « rendre concret ». Si le texte source est vague, le resserrer sans fabriquer de détail.
- **Préserver la voix de l'auteur.** Le but est un texte qui sonne humain, pas un texte aseptisé identique pour tous.
- **Ne pas remplacer un tic par un autre.** Supprimer le remplissage ne veut pas dire empiler des phrases de trois mots : le staccato est lui aussi un marqueur IA.
- **Garder les précautions et le passif quand ils portent un sens** (textes juridiques, scientifiques, médicaux) : voir [references/registres.md](references/registres.md).
- **Garder les termes techniques exacts.** Ne pas franciser un nom d'API, de produit ou un terme consacré.
- **Ne jamais réécrire une citation** entre guillemets : la signaler, pas la corriger.
- En cas de doute entre fidélité au sens et élégance, **choisir la fidélité**.

## Vérifications rapides

Avant de livrer un texte :

- Des adverbes en -ment ? Les supprimer. « véritable / véritablement » ? Couper.
- De la voix passive, ou un « on » qui cache l'acteur ? Trouver la personne, en faire le sujet.
- Un objet inanimé qui fait un verbe humain (« la technologie transforme ») ? Nommer la personne.
- Un connecteur scolaire en tête (« En outre », « Par ailleurs », « En effet », « Ainsi », « Force est de constater ») ? Couper ou fondre.
- Une amorce creuse (« il est important de noter que », « il convient de souligner ») ? Aller droit au but.
- Un anglicisme/calque (« impacter », « adresser », « faire du sens », « au final ») ? Remplacer.
- Un mot fétiche (« crucial », « riche », « robuste », « incontournable ») ? Le remplacer par le fait précis.
- Un faux contraste (« ce n'est pas X, c'est Y », « il ne s'agit pas de X mais de Y ») ? Énoncer Y directement.
- Un gérondif final qui commente (« …, ouvrant la voie à de nouvelles possibilités ») ? Le couper.
- Une clivée de remplissage (« Ce qu'il faut retenir, c'est… ») ? Énoncer le fait.
- Une question rhétorique d'ouverture (« Et si… ? », « Vous aussi… ? ») ? La supprimer, affirmer.
- Trois phrases d'affilée de même longueur ? En casser une. Une énumération ternaire (« X, Y et Z ») par réflexe ? Réduire à deux ou un.
- Un tiret cadratin (—) ? Le remplacer par une virgule, un point ou des parenthèses.
- Des emoji décoratifs, un gras systématique, des puces par réflexe, des paragraphes calibrés ? Dégonfler.
- Une formule de conclusion automatique (« En somme », « En définitive », « Au final », « Vous l'aurez compris ») ? Couper.
- Une déclaration vague (« les implications sont majeures ») ? Nommer l'implication précise.
- Typographie : guillemets français « » (pas `"`), espace insécable avant `: ; ! ?`, pas de virgule d'Oxford avant « et ».

## Notation

Noter de 1 à 10 chaque dimension :

| Dimension | Question |
|-----------|----------|
| Franchise | Affirmations ou annonces ? |
| Rythme | Varié ou métronomique ? |
| Confiance | Respecte l'intelligence du lecteur ? |
| Authenticité | Sonne humain et français (pas traduit) ? |
| Densité | Reste-t-il quelque chose à couper ? |
| Forme | Mise en forme sobre, ou sapin de Noël (emoji, gras, puces) ? |

En dessous de 42/60 : réviser.

## Références

- [references/expressions.md](references/expressions.md) — expressions à supprimer (amorces, connecteurs, mots fétiches, verbes passe-partout, adverbes, conclusions).
- [references/structures.md](references/structures.md) — motifs structurels et de mise en forme à éviter.
- [references/anglicismes.md](references/anglicismes.md) — anglicismes et calques de l'anglais, avec corrections.
- [references/registres.md](references/registres.md) — adapter le ton par type de texte.
- [references/exemples.md](references/exemples.md) — transformations avant/après.

## Licence

MIT. Adapté de [stop-slop](https://github.com/hardikpandya/stop-slop) de Hardik Pandya.
