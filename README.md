# Flambot — Fakemon Cobblemon

Addon combinant **resource pack + data pack** pour ajouter Flambot, un fakemon
robot Feu/Acier inspiré du dessin original.

## Installation

1. Copie le dossier `flambot-addon` (ou le zip décompressé) dans le dossier
   `resourcepacks` de ton Minecraft, et active-le dans les options.
2. Copie le même dossier dans le dossier `datapacks` de ta sauvegarde
   (monde avec le mod Cobblemon installé).
3. Relance le monde (le `/reload` ne fonctionne pas avec les datapacks Cobblemon).
4. Teste avec : `/pokespawn flambot`

## Identité

- **Nom** : Flambot
- **Types** : Feu / Acier
- **Taille** : 0,9 m — 240 kg
- **Talent** : Corps Ardent (caché : Ignifugé)
- **Spawn** : montagnes (`#cobblemon:is_mountain`), niveaux 5-25, peu commun

## Contenu

| Fichier | Rôle |
|---|---|
| `assets/cobblemon/bedrock/pokemon/models/flambot/flambot.geo.json` | Modèle 3D (Bedrock entity) |
| `assets/cobblemon/bedrock/pokemon/animations/flambot/flambot.animation.json` | Animations idle / marche / K.O. |
| `assets/cobblemon/bedrock/pokemon/posers/flambot.json` | Poses + cadrage portrait/profil |
| `assets/cobblemon/bedrock/pokemon/resolvers/flambot/0_flambot_base.json` | Liaison modèle/texture (normal + shiny) |
| `assets/cobblemon/textures/pokemon/flambot/flambot.png` | Texture (64x64) |
| `assets/cobblemon/textures/pokemon/flambot/flambot_shiny.png` | Texture chromatisée |
| `data/cobblemon/species/custom/flambot.json` | Stats, types, talents, moves |
| `data/cobblemon/spawn_pool_world/0_flambot.json` | Apparitions dans le monde |

## Fidélité au dessin

Couleurs échantillonnées directement sur l'image d'origine :
corps jaune pâle `#FFD276`, accents orange `#F49501`, lentilles bleues
`#68C3E2`, détails sombres `#4A4426`. Crête en flamme inclinée vers
l'arrière, grands yeux ronds avec pupilles et reflet, bouche grille,
épaulettes / avant-bras / genoux / pieds orange, longs bras à trois segments.
