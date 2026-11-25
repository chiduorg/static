# Texture attribution

Planetary maps by Solar System Scope / INOVE.

Source: https://www.solarsystemscope.com/textures/
License: Creative Commons Attribution 4.0 International (CC BY 4.0)
https://creativecommons.org/licenses/by/4.0/

Files: earth-day.jpg, earth-night.jpg, earth-clouds.jpg, earth-normal.jpg,
earth-specular.jpg, moon.jpg, sun.jpg, jupiter.jpg, saturn.jpg, saturn-ring.png,
and the planets/ folder (Mercury, Venus, Mars, Uranus, Neptune).
Thumbnails under thumbs/ are 96 px wide derivatives of the same maps, used only for 18 px list glyphs.
Hero images hero-earth.jpg (900 px), hero-moon.jpg (640 px) and hero-sun.jpg (640 px) are
JPEG quality 82 derivatives of earth-day.jpg, moon.jpg and sun.jpg, used only as portal
background decoration; the 3D scenes keep the full-resolution maps.
Original download names are 2k_earth_daymap.jpg, 2k_earth_nightmap.jpg,
2k_earth_clouds.jpg, 2k_moon.jpg, 2k_sun.jpg, 2k_jupiter.jpg, 2k_saturn.jpg,
2k_saturn_ring_alpha.png, 2k_mercury.jpg, 2k_venus_surface.jpg, 2k_mars.jpg,
2k_uranus.jpg, 2k_neptune.jpg under /textures/download/ on the source website.
Earth's normal and specular maps are the 2048 px Public Domain/NASA-derived maps
from the three.js example asset set (MIT-licensed repository).

Changes: Maps are
composited in custom materials with simulated lighting, clouds, atmosphere,
night-side lights and color management. Renderings are illustrative.
For web delivery the maps were re-encoded at JPEG quality 82–84. The principal
planets now use the full 2048 px maps; Earth additionally uses normal, specular,
cloud and night-light maps. Downsampling is limited to list thumbnails and portal
hero decorations.

Saturn's ring alpha strip is stored as a locally warmed derivative (R×1.32, G×1.22,
B×1.05, opacity set in-material) so the unlit ring reads as tan rather than near-black;
the untouched download is kept at planets/saturn_ring_alpha_original.png.

# 3D model attribution

Animal models in `models/` are external free assets, used as illustrative 3D models.
They are not scientific specimens and several entries use a visually close species
where an exact species asset was unavailable; these are documented in the animal
quality report.

## Grab3D human base mesh (CC0 1.0)

Source: https://grab3d.com/models/characters/man-base-character/
License: CC0 1.0 Universal (public domain dedication).
https://creativecommons.org/publicdomain/zero/1.0/

File: `human-real.glb` (Grab3D “Man Base Mesh”, full-quality download).
1.80 m A-pose, 262,348 triangles. The source uses 4K PBR base-colour / normal /
metallic-roughness textures; for web delivery the embedded images are resized to
2048 px. The model is scaled to 1.70 m in the scene as the chosen human reference
height; it is a static mesh with no armature or animation. A soft contact shadow is
added by the renderer for grounding.

## Grab3D (CC0 1.0)

Source: https://grab3d.com/low-poly-3d-models/
License: CC0 1.0 Universal (public domain dedication).
https://creativecommons.org/publicdomain/zero/1.0/

Files include the `low-poly-*.glb` animals (lion, bear, wolf, fox, rabbit, horse,
cow, bull, sheep, pig, elephant, rhino, hippo, penguin, octopus, shark, humpback,
snake, dolphin) and the simplified `tiger.glb`, `giraffe.glb`, `cheetah.glb`,
`crocodile.glb`, `eagle.glb`, `axolotl.glb`, `moose.glb`, `squirrel.glb`,
`kitten.glb`, `puppy.glb`, `orca.glb`, `reindeer.glb` derivatives. High-detail
originals were remeshed with `gltf-transform weld + simplify` for web delivery.

## Poly Pizza (per-model license)

Source: https://poly.pizza/
License: each model page states its license; the assets used here are CC0 1.0 or
CC BY 3.0 (Poly by Google / Quaternius). Attribution is retained here and in the
model filenames (`poly-*.glb`).

Representative model pages:
- https://poly.pizza/m/cwyNyIba6WE (tree frog)
- https://poly.pizza/m/5-MuhNMDmY_ (bat, wings spread)
- https://poly.pizza/m/5T7nIjx9ekP (walrus)
- https://poly.pizza/m/eau2X1phgjJ (hippopotamus)
- https://poly.pizza/m/25ijpkQ3YAb (lobster)
- https://poly.pizza/m/9xOaiLvBLF- (earthworm)
- https://poly.pizza/m/7XeLogrxLad (camel)
- https://poly.pizza/m/7BiPR-oOGgX (kangaroo)
- https://poly.pizza/m/UYtneO5FpF (Tyrannosaurus)
- https://poly.pizza/m/IGvrUqGrRM (Triceratops)
- https://poly.pizza/m/7hMOlBjln0 (swordfish)
- https://poly.pizza/m/1tycAcvSVW (tuna)

Poly Pizza model pages and the original authors retain copyright where a CC BY
license applies; no endorsement is implied.

## Quaternius (CC0 1.0)

Some Poly Pizza assets originate from Quaternius packs, released under CC0 1.0.
https://quaternius.com/

## 3DAssets.dev (CC0 1.0)

High-detail animals added in the 2026-11 7.0–7.9 band upgrade (gorilla, chimpanzee,
Komodo dragon, hippopotamus, green iguana, cane toad, brachiosaurus, salmon,
harbour seal, bluespotted stingray, sperm whale, blue whale). Source CDN pattern
`https://cdn.3dassets.dev/assets/<id>/v1/model.glb`; the asset pages state CC0 1.0.
The cod entry reuses the salmon mesh with an olive material as a documented
stand-in until an exact cod asset is available.

## HMS Queen Elizabeth R08 (CC BY 4.0)

Title: “HMS Queen Elizabeth R08 Aircraft Carrier”
Author: Muhamad Mirza Arrafi
Source: https://sketchfab.com/3d-models/hms-queen-elizabeth-r08-aircraft-carrier-b7394547685749ae9e1c48afe29586ab
License: Creative Commons Attribution 4.0 International (CC BY 4.0)
https://creativecommons.org/licenses/by/4.0/

File: `models/hms-queen-elizabeth.glb` (17,140 triangles, 3.69 MB).
Changes: the source glTF's empty material slots and mismatched texture atlas were
discarded; the hull is rendered with a clean PBR material, and the site adds its
own flight-deck texture, twin islands, F-35B-style aircraft, Merlin-style
helicopter, deck crew, markings and wake. The site does not imply endorsement by
the author, the Royal Navy or Sketchfab.

## USGS / NASA planetary maps

Triton: “Triton Voyager 2 Global Color Mosaic 600m”, USGS Astrogeology Science
Center, https://astrogeology.usgs.gov/search/map/triton_voyager_2_global_color_mosaic_600m.
Public domain USGS product; the web derivative is cropped, colour-graded and
desaturated for display.

Kilauea lava lake: USGS / Hawaiian Volcano Observatory aerial photograph
(public domain), source image `work/kilauea-lava-lake.jpg`; cropped, contrast-
enhanced and used as the crater-floor albedo in the lava-temperature scene.

# 1.4.0 asset audit

On 2026-11-25 the asset tree was re-audited: 186 files were hashed and mapped to entries, features, 3D scenes and shared OG/favicon slots. 90 unreferenced or duplicate files were removed; 96 files (about 81.7 MB) remain. The lists above describe the retained textures, models, thumbnails and hero derivatives; no removed file is still referenced by the build.
