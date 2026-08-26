# DESIGN.md — Ma charte visuelle CandyPop

> Ma direction artistique, à charger avant toute production visuelle : visuel de post, carrousel, miniature, bannière, page web, PDF, e-mail.
>
> **Source de vérité :** le design system `CandyPop Design System` sur claude.ai/design (projet `d954261a-8784-4c20-9739-1fd0d2aa6e06`). Ce fichier en est la copie locale, pour que MAÏA connaisse ma charte quand je travaille dans Claude Code.
>
> **Document d'origine :** `context/import/univers-visuel.pdf`
>
> Si je change une couleur ou une police, il faut la changer aux deux endroits.

---

## La règle qui prime sur toutes les autres

> **Un visuel doit être compris en deux secondes.**
> Un visage reconnaissable, une phrase forte, un contraste très élevé.

Si un choix esthétique nuit à la lisibilité en deux secondes sur un écran de téléphone, il dégage. C'est le seul arbitrage qui compte.

---

## L'ambiance en une phrase

Univers **CandyPop business premium** : pastel et fluo mélangés, féminin, énergique, digital, légèrement futuriste. Professionnel mais jamais froid. Inspiré des publicités sociales premium. Fait pour être très visible dans un fil d'actualité.

---

## Palette

**Couleurs de base** (les noms entre parenthèses sont les tokens, c'est-à-dire les variables réutilisables du design system) :

| Couleur | Code | Token |
|---|---|---|
| Rose fuchsia | `#FF2E9A` | `--cp-fuchsia` |
| Fuchsia profond | `#D80B77` | `--cp-fuchsia-deep` |
| Rose bonbon | `#FF7DC3` | `--cp-bonbon` |
| Rose bonbon pastel | `#FFC2E2` | `--cp-bonbon-soft` |
| Violet électrique | `#7C1FFF` | `--cp-violet` |
| Violet profond | `#5A00D6` | `--cp-violet-deep` |
| Lavande | `#C3A6FF` | `--cp-lavender` |
| Lavande pastel | `#E7DBFF` | `--cp-lavender-soft` |
| Bleu électrique | `#2B5BFF` | `--cp-blue` |
| Cyan | `#00D5FF` | `--cp-cyan` |
| Cyan pastel | `#B7F1FF` | `--cp-cyan-soft` |
| Turquoise | `#14E3C8` | `--cp-turquoise` |
| Vert lime fluo | `#C6FF3D` | `--cp-lime` |
| Lime pastel | `#EBFFC0` | `--cp-lime-soft` |
| Jaune néon | `#FFF23D` | `--cp-neon-yellow` |
| Orange | `#FF7A3D` | `--cp-orange` |
| Blanc lumineux | `#FFFDFF` | `--cp-white` |

**Encres et gris** (jamais de gris neutre, ils sont tous teintés violet) :

| Rôle | Code | Token |
|---|---|---|
| Texte fort | `#1A0B2E` | `--cp-ink` |
| Texte courant | `#3A2A55` | `--cp-ink-2` |
| Texte secondaire | `#6E5C8C` | `--cp-ink-3` |
| Fond pastel | `#F6F2FB` | `--cp-grey-1` |
| Bordure douce | `#EAE3F4` | `--cp-grey-2` |
| Bordure marquée | `#D6CCE6` | `--cp-grey-3` |

**Les cinq dégradés signature :**

| Nom | Composition | Token |
|---|---|---|
| Pop | fuchsia vers violet | `--cp-grad-pop` |
| Aqua | bleu vers turquoise | `--cp-grad-aqua` |
| Sunset | fuchsia vers orange | `--cp-grad-sunset` |
| Fluo | lime vers cyan | `--cp-grad-fluo` |
| Electric | violet vers bleu | `--cp-grad-electric` |

Tous à 120 degrés. Un fond pastel diffus existe aussi : `--cp-grad-pastel-bg`, un dégradé radial rose bonbon vers lavande vers cyan.

### La règle du mot en couleur

Sur un visuel, un mot ou deux au maximum changent de couleur pour attirer l'œil :

- **un mot en rose fuchsia**
- **un élément en cyan**
- **un chiffre en lime**
- **une phrase clé posée sur un rectangle violet ou bleu**

C'est un accent, pas une décoration. Trois mots colorés dans la même phrase annulent l'effet.

---

## Typographie

**Titres :** Anton, en repli Impact ou Haettenschweiler. Toujours en **capitales**, très grands, très gras, condensés, interlignage serré (0.92).

**Corps de texte :** Manrope, en repli Helvetica Neue. Interlignage 1.55.

Échelle des tailles :

| Usage | Taille |
|---|---|
| Hook (l'accroche principale) | de 44 à 104 px, adaptatif |
| Titre 1 | 72 px |
| Titre 2 | 56 px |
| Titre 3 | 40 px |
| Sous-titre | 28 px |
| Chapeau | 20 px |
| Corps | 16 px |
| Petit | 14 px |
| Micro | 12 px |

Graisses disponibles : 400 régulier, 500 medium, 600 semi-gras, 700 gras, 800 très gras.

---

## Composition d'un visuel

Structure type, dans cet ordre :

1. **Un hook très visible en haut.** C'est l'accroche, la phrase qui arrête le scroll
2. **Mon avatar**, au centre ou sur un côté
3. **Une expression** sérieuse, confiante ou réfléchie
4. **Des blocs secondaires** qui portent l'information
5. **Un élément de contraste** : cercle, badge, flèche, encadré ou bandeau
6. **Un fond** clair, pastel, flouté ou digital

---

## Mon avatar

C'est le point central de mon identité visuelle. À décrire ainsi dans tout prompt de génération d'image :

- cheveux longs, nombreuses tresses fines
- nuances blondes, pastel, rose, bleu, lavande et menthe
- yeux noisette-verts
- peau naturelle, rendu réaliste
- expression assurée, posture professionnelle
- vêtements colorés et structurés

Tenues déjà utilisées : blazer rose vif, blazer lavande, tailleur pastel, top vert fluo, top violet. Toujours féminin, moderne, professionnel.

---

## Éléments graphiques récurrents

Cadres arrondis, néons, halos lumineux, contours blancs, ombres douces, flèches, badges circulaires, lignes cyan ou rose, dégradés fluo, blocs de texte superposés, arrière-plans floutés liés au sujet, tableaux ou captures intégrés en second plan.

**Arrondis :** 8, 12, 20, 28, 40 px, ou complètement arrondi pour les pastilles.
**Épaisseur de bordure :** 2 px en standard, 3 px pour appuyer.

**Ombres :** toujours teintées violet (`rgba(26,11,46,...)`), jamais du gris neutre.

**Halos néon**, la signature de la charte : un anneau flou de 4 px plus une diffusion large, en rose, violet, cyan ou lime.

**Contour blanc :** sert à détacher un texte ou un badge d'un fond chargé.

**Effet verre dépoli :** réservé aux panneaux posés sur une photo ou un fond pastel.

---

## Espacement

Échelle : 4, 8, 12, 16, 24, 32, 48, 64, 96, 128 px.
Gouttière 24 px. Largeur de page maximale 1200 px. Espacement vertical entre sections 96 px.

---

## Animation

Trois durées : 120 ms rapide, 200 ms standard, 420 ms lent.
Deux courbes : `ease-pop` avec un léger rebond pour les apparitions, `ease-out` pour tout le reste.

---

## Décisions déjà prises, à ne pas rouvrir

- **Fond clair forcé partout**, y compris pour les visiteurs en mode sombre. Décision du 21 août 2026. Motif : cohérence avec le "blanc lumineux" de la charte et avec les visuels Facebook. Une version sombre avait été construite puis retirée
- **Anton pour les titres, Manrope pour le corps.** Validé et appliqué sur `machine.promptik.fr`
- **Aucun faux élément de preuve** : pas de témoignage inventé, pas de chiffre de résultat non obtenu, pas de logo de média, pas de compte à rebours factice. Cette règle vient de `context/VOIX.md` et prime sur toute considération esthétique

---

## Où vit quoi

| Besoin | Où aller |
|---|---|
| Générer un visuel ou une page sur claude.ai | Sélectionner le projet `CandyPop Design System` dans Claude Design |
| Travailler ici, dans Claude Code | Ce fichier, chargé avant toute production visuelle |
| Le document d'origine | `context/import/univers-visuel.pdf` |
| Le site déjà en ligne | dossier `site/`, en production sur `machine.promptik.fr` |

Le design system en ligne contient en plus des composants prêts à l'emploi (boutons, badges, cartes, `HookTitle` pour les accroches, `Highlight` pour les mots surlignés), des fiches de guidelines visuelles et deux gabarits : `templates/social-post` et `templates/landing`.
