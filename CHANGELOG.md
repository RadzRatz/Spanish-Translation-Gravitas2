# Changelog

# 📦 0.2.6-a

## 📰 General changes and notes

Summary of changes here!

<details open>
<summary>Github Commits :octocat:</summary>
<blockquote>

- Removed Rubber Cast
- Re-added Rubber Cast
- Rubber cast fix
- experimental changelog
- removed false positives of changes
- add collapse degrade for greg ores
- using replaceAll
- fix chalk recipe
- seed oil fix
- reduce fire dragon spawn locations
- add saltpeter conversion
- fixing computers
- adds missing igneous alloy de-molding
- update(reduce) alloy smelter processing time for iron
- add feature to replace stones of structures
- update EBF recipes to output slag</blockquote>

</details>

---

## 🛠️ Mods

<details open>
<summary>Added (1)</summary>

- Create: Vintage Improvements (1.20.1-0.1.2.0)

</details>

<details>
<summary>Updated (27)</summary>

- AE2WTLib (15.2.1-forge) -> (15.2.2-forge)
- AlmostUnified (1.20.1-0.7.2) -> (1.20.1-0.8.1)
- Apotheosis (7.3.0) -> (7.3.1)
- Architectury (9.1.13) -> (9.2.14)
- Apothic Attributes (1.2.1) -> (1.3.0)
- Balm (7.2.1) -> (7.2.2)
- Building Gadgets 2 (1.0.6) -> (1.0.7)
- Citadel (2.4.9) -> (2.5.4)
- Cupboard utilities (1.20.1-2.3) -> (1.20.1-2.5)
- EnchantmentDescriptions (17.0.13) -> (17.0.14)
- Every Compat (1.20-2.6.29) -> (1.20-2.6.35)
- ExtendedAE (1.20-1.0.12-forge) -> (1.20-1.0.13-forge)
- FramedBlocks (9.1.6) -> (9.2.0)
- Fusion (1.1.0c) -> (1.1.1)
- Gravitas² Core Mod (1.0.32) -> (1.0.33)
- Ice and Fire (2.1.13-1.20.1+build.beta-2) -> (2.1.13-1.20.1-beta-4)
- ModernFix (5.13.0+mc1.20.1) -> (5.14.0+mc1.20.1)
- Moonlight Library (1.20-2.9.17) -> (1.20-2.10.10)
- Railcraft Reborn (1.0.10) -> (1.1.0)
- Repurposed Structures (7.1.11+1.20.1-forge) -> (7.1.13+1.20.1-forge)
- Stargate Journey (0.6.20) -> (0.6.21)
- Small Ships (2.0.0-b1.0) -> (2.0.0-b1.1)
- Stellar View (0.2.1) -> (0.2.2)
- Storage Drawers (12.0.2) -> (12.0.3)
- TFC Thermal Deposits (1.3.7) -> (1.3.8)
- ThoriumReactors (0.1.5b) -> (0.1.6b)
- Titanium (3.8.25) -> (3.8.27)

</details>

## 🍳 Recipes

<details>
<summary>Added (212)</summary>
<blockquote>

<details>
<summary>ae2/matter_cannon/nuggets/sulfur</summary>

```diff
+{
+  type: "ae2:matter_cannon"
+  ammo: {
+    tag: "forge:nuggets/sulfur"
+  }
+  conditions: [
+    {
+      type: "forge:not"
+      value: {
+        type: "forge:tag_empty"
+        tag: "forge:nuggets/sulfur"
+      }
+    }
+  ]
+  weight: 32.065
+}

```


</details>

<details>
<summary>almostunified/vintageimprovements</summary>

```diff
+{
+  type: "almostunified:client_recipe_tracker"
+  namespace: "vintageimprovements"
+  recipes: [
+    "1$craft/steel_rod"
+    "3$rolling/steel_ingot"
+  ]
+}

```


</details>

<details>
<summary>create/kjs/15gutmetunqvpcr90u4szfg46</summary>

```diff
+{
+  type: "create:deploying"
+  results: [
+    {
+      item: "gtceu:rubber_ingot"
+      count: 1
+    }
+    {
+      item: "tfc:ceramic/ingot_mold"
+      count: 1
+      chance: 0.8999999985098839
+    }
+  ]
+  ingredients: [
+    {
+      type: "tfc:heatable"
+      ingredient: {
+        type: "forge:partial_nbt"
+        item: "tfc:ceramic/ingot_mold"
+        nbt: "{tank:{Amount:144,FluidName:\"gtceu:rubber\"}}"
+      }
+    }
+    {
+      tag: "tfc:chisels"
+    }
+  ]
+}

```


</details>

<details>
<summary>create/kjs/2p90hjdycyzdrzqt04gncrfa4</summary>

```diff
+{
+  type: "create:deploying"
+  results: [
+    {
+      item: "create:andesite_alloy"
+      count: 1
+    }
+    {
+      item: "tfc:ceramic/fire_ingot_mold"
+      count: 1
+      chance: 0.99
+    }
+  ]
+  ingredients: [
+    {
+      type: "tfc:heatable"
+      ingredient: {
+        type: "forge:partial_nbt"
+        item: "tfc:ceramic/fire_ingot_mold"
+        nbt: "{tank:{Amount:144,FluidName:\"gregitas_core:igneous_alloy\"}}"
+      }
+    }
+    {
+      tag: "tfc:chisels"
+    }
+  ]
+}

```


</details>

<details>
<summary>create/kjs/3ihxkenat7q47xq89ceku38p</summary>

```diff
+{
+  type: "create:deploying"
+  results: [
+    {
+      item: "create:andesite_alloy"
+      count: 1
+    }
+    {
+      item: "tfc:ceramic/ingot_mold"
+      count: 1
+      chance: 0.9
+    }
+  ]
+  ingredients: [
+    {
+      type: "tfc:heatable"
+      ingredient: {
+        type: "forge:partial_nbt"
+        item: "tfc:ceramic/ingot_mold"
+        nbt: "{tank:{Amount:144,FluidName:\"gregitas_core:igneous_alloy\"}}"
+      }
+    }
+    {
+      tag: "tfc:chisels"
+    }
+  ]
+}

```


</details>

<details>
<summary>create/kjs/atky7u3681ayp9im8dncwrhh4</summary>

```diff
+{
+  type: "create:deploying"
+  results: [
+    {
+      item: "gtceu:rubber_ingot"
+      count: 1
+    }
+    {
+      item: "tfc:ceramic/fire_ingot_mold"
+      count: 1
+      chance: 0.9900000002235174
+    }
+  ]
+  ingredients: [
+    {
+      type: "tfc:heatable"
+      ingredient: {
+        type: "forge:partial_nbt"
+        item: "tfc:ceramic/fire_ingot_mold"
+        nbt: "{tank:{Amount:144,FluidName:\"gtceu:rubber\"}}"
+      }
+    }
+    {
+      tag: "tfc:chisels"
+    }
+  ]
+}

```


</details>

<details>
<summary>framedblocks/framed_checkered_cube</summary>

```diff
+{
+  type: "minecraft:crafting_shaped"
+  category: "building"
+  key: {
+    C: {
+      item: "framedblocks:framed_slab_corner"
+    }
+  }
+  pattern: [
+    "CCC"
+    "C C"
+    "CCC"
+  ]
+  result: {
+    item: "framedblocks:framed_checkered_cube"
+  }
+  show_notification: true
+}

```


</details>

<details>
<summary>framedblocks/framed_checkered_panel</summary>

```diff
+{
+  type: "minecraft:crafting_shaped"
+  category: "building"
+  key: {
+    C: {
+      item: "framedblocks:framed_checkered_cube"
+    }
+  }
+  pattern: [
+    "C"
+    "C"
+    "C"
+  ]
+  result: {
+    count: 6
+    item: "framedblocks:framed_checkered_panel"
+  }
+  show_notification: true
+}

```


</details>

<details>
<summary>framedblocks/framed_checkered_slab</summary>

```diff
+{
+  type: "minecraft:crafting_shaped"
+  category: "building"
+  key: {
+    C: {
+      item: "framedblocks:framed_checkered_cube"
+    }
+  }
+  pattern: [
+    "CCC"
+  ]
+  result: {
+    count: 6
+    item: "framedblocks:framed_checkered_slab"
+  }
+  show_notification: true
+}

```


</details>

<details>
<summary>framedblocks/framed_collapsible_copycat_block</summary>

```diff
+{
+  type: "minecraft:crafting_shaped"
+  category: "building"
+  key: {
+    C: {
+      tag: "forge:ingots/copper"
+    }
+    F: {
+      item: "framedblocks:framed_cube"
+    }
+  }
+  pattern: [
+    "FCF"
+    "C C"
+    "FCF"
+  ]
+  result: {
+    count: 4
+    item: "framedblocks:framed_collapsible_copycat_block"
+  }
+  show_notification: true
+}

```


</details>

<details>
<summary>framedblocks/framed_compound_slope_panel</summary>

```diff
+{
+  type: "minecraft:crafting_shaped"
+  category: "building"
+  key: {
+    H: {
+      item: "framedblocks:framed_hammer"
+    }
+    P: {
+      item: "framedblocks:framed_slope_panel"
+    }
+  }
+  pattern: [
+    "PPH"
+  ]
+  result: {
+    item: "framedblocks:framed_compound_slope_panel"
+  }
+  show_notification: true
+}

```


</details>

<details>
<summary>framedblocks/framed_compound_slope_slab</summary>

```diff
+{
+  type: "minecraft:crafting_shaped"
+  category: "building"
+  key: {
+    H: {
+      item: "framedblocks:framed_hammer"
+    }
+    S: {
+      item: "framedblocks:framed_slope_slab"
+    }
+  }
+  pattern: [
+    "SSH"
+  ]
+  result: {
+    item: "framedblocks:framed_compound_slope_slab"
+  }
+  show_notification: true
+}

```


</details>

<details>
<summary>framedblocks/framed_corner_strip_from_framed_floor_board</summary>

```diff
+{
+  type: "minecraft:crafting_shapeless"
+  category: "building"
+  ingredients: [
+    {
+      item: "framedblocks:framed_floor_board"
+    }
+    {
+      item: "framedblocks:framed_hammer"
+    }
+  ]
+  result: {
+    count: 16
+    item: "framedblocks:framed_corner_strip"
+  }
+}

```


</details>

<details>
<summary>framedblocks/framed_corner_strip_from_framed_wall_board</summary>

```diff
+{
+  type: "minecraft:crafting_shapeless"
+  category: "building"
+  ingredients: [
+    {
+      item: "framedblocks:framed_wall_board"
+    }
+    {
+      item: "framedblocks:framed_hammer"
+    }
+  ]
+  result: {
+    count: 16
+    item: "framedblocks:framed_corner_strip"
+  }
+}

```


</details>

<details>
<summary>framedblocks/framed_double_half_stairs</summary>

```diff
+{
+  type: "minecraft:crafting_shaped"
+  category: "building"
+  key: {
+    C: {
+      item: "framedblocks:framed_slab_corner"
+    }
+    S: {
+      item: "framedblocks:framed_half_stairs"
+    }
+  }
+  pattern: [
+    "SC"
+  ]
+  result: {
+    item: "framedblocks:framed_double_half_stairs"
+  }
+  show_notification: true
+}

```


</details>

<details>
<summary>framedblocks/framed_double_threeway_corner_pillar</summary>

```diff
+{
+  type: "minecraft:crafting_shaped"
+  category: "building"
+  key: {
+    F: {
+      item: "framedblocks:framed_threeway_corner_pillar"
+    }
+  }
+  pattern: [
+    "F"
+    "F"
+  ]
+  result: {
+    item: "framedblocks:framed_double_threeway_corner_pillar"
+  }
+  show_notification: true
+}

```


</details>

<details>
<summary>framedblocks/framed_elevated_double_slope_edge</summary>

```diff
+{
+  type: "minecraft:crafting_shaped"
+  category: "building"
+  key: {
+    E: {
+      item: "framedblocks:framed_elevated_slope_edge"
+    }
+    S: {
+      item: "framedblocks:framed_slope_edge"
+    }
+  }
+  pattern: [
+    "S"
+    "E"
+  ]
+  result: {
+    item: "framedblocks:framed_elevated_double_slope_edge"
+  }
+  show_notification: true
+}

```


</details>

<details>
<summary>framedblocks/framed_elevated_slope_edge</summary>

```diff
+{
+  type: "minecraft:crafting_shaped"
+  category: "building"
+  key: {
+    E: {
+      item: "framedblocks:framed_slope_edge"
+    }
+    S: {
+      item: "framedblocks:framed_stairs"
+    }
+  }
+  pattern: [
+    "E"
+    "S"
+  ]
+  result: {
+    item: "framedblocks:framed_elevated_slope_edge"
+  }
+  show_notification: true
+}

```


</details>

<details>
<summary>framedblocks/framed_masonry_corner</summary>

```diff
+{
+  type: "minecraft:crafting_shaped"
+  category: "building"
+  key: {
+    E: {
+      item: "framedblocks:framed_slab_edge"
+    }
+  }
+  pattern: [
+    "EE"
+    "EE"
+  ]
+  result: {
+    item: "framedblocks:framed_masonry_corner"
+  }
+  show_notification: true
+}

```


</details>

<details>
<summary>framedblocks/framed_sliced_stairs_panel</summary>

```diff
+{
+  type: "minecraft:crafting_shaped"
+  category: "building"
+  key: {
+    E: {
+      item: "framedblocks:framed_slab_edge"
+    }
+    P: {
+      item: "framedblocks:framed_panel"
+    }
+  }
+  pattern: [
+    "PE"
+  ]
+  result: {
+    item: "framedblocks:framed_sliced_stairs_panel"
+  }
+  show_notification: true
+}

```


</details>

<details>
<summary>framedblocks/framed_sliced_stairs_slab</summary>

```diff
+{
+  type: "minecraft:crafting_shaped"
+  category: "building"
+  key: {
+    E: {
+      item: "framedblocks:framed_slab_edge"
+    }
+    S: {
+      item: "framedblocks:framed_slab"
+    }
+  }
+  pattern: [
+    "E"
+    "S"
+  ]
+  result: {
+    item: "framedblocks:framed_sliced_stairs_slab"
+  }
+  show_notification: true
+}

```


</details>

<details>
<summary>framedblocks/framed_slope_edge</summary>

```diff
+{
+  type: "minecraft:crafting_shaped"
+  category: "building"
+  key: {
+    F: {
+      item: "framedblocks:framed_slope"
+    }
+    H: {
+      item: "framedblocks:framed_hammer"
+    }
+  }
+  pattern: [
+    "FFF"
+    " H "
+  ]
+  result: {
+    count: 6
+    item: "framedblocks:framed_slope_edge"
+  }
+  show_notification: true
+}

```


</details>

<details>
<summary>framedblocks/framed_stacked_slope_edge</summary>

```diff
+{
+  type: "minecraft:crafting_shaped"
+  category: "building"
+  key: {
+    E: {
+      item: "framedblocks:framed_slope_edge"
+    }
+    H: {
+      item: "framedblocks:framed_hammer"
+    }
+    S: {
+      item: "framedblocks:framed_stairs"
+    }
+  }
+  pattern: [
+    "H"
+    "E"
+    "S"
+  ]
+  result: {
+    item: "framedblocks:framed_stacked_slope_edge"
+  }
+  show_notification: true
+}

```


</details>

<details>
<summary>framedblocks/framed_threeway_corner_pillar</summary>

```diff
+{
+  type: "minecraft:crafting_shaped"
+  category: "building"
+  key: {
+    E: {
+      item: "framedblocks:framed_slab_edge"
+    }
+    P: {
+      item: "framedblocks:framed_corner_pillar"
+    }
+  }
+  pattern: [
+    "P"
+    "E"
+  ]
+  result: {
+    item: "framedblocks:framed_threeway_corner_pillar"
+  }
+  show_notification: true
+}

```


</details>

<details>
<summary>framedblocks/framed_vertical_double_half_stairs</summary>

```diff
+{
+  type: "minecraft:crafting_shaped"
+  category: "building"
+  key: {
+    C: {
+      item: "framedblocks:framed_slab_corner"
+    }
+    S: {
+      item: "framedblocks:framed_vertical_half_stairs"
+    }
+  }
+  pattern: [
+    "SC"
+  ]
+  result: {
+    item: "framedblocks:framed_vertical_double_half_stairs"
+  }
+  show_notification: true
+}

```


</details>

<details>
<summary>framedblocks/framed_vertical_sliced_stairs</summary>

```diff
+{
+  type: "minecraft:crafting_shaped"
+  category: "building"
+  key: {
+    E: {
+      item: "framedblocks:framed_slab_edge"
+    }
+    P: {
+      item: "framedblocks:framed_panel"
+    }
+    W: {
+      item: "framedblocks:framed_wrench"
+    }
+  }
+  pattern: [
+    "PEW"
+  ]
+  result: {
+    item: "framedblocks:framed_vertical_sliced_stairs"
+  }
+  show_notification: true
+}

```


</details>

<details>
<summary>framedblocks/framing_saw/framed_checkered_cube</summary>

```diff
+{
+  type: "framedblocks:frame"
+  material: 6144
+  result: {
+    item: "framedblocks:framed_checkered_cube"
+  }
+}

```


</details>

<details>
<summary>framedblocks/framing_saw/framed_checkered_panel</summary>

```diff
+{
+  type: "framedblocks:frame"
+  material: 3072
+  result: {
+    item: "framedblocks:framed_checkered_panel"
+  }
+}

```


</details>

<details>
<summary>framedblocks/framing_saw/framed_checkered_slab</summary>

```diff
+{
+  type: "framedblocks:frame"
+  material: 3072
+  result: {
+    item: "framedblocks:framed_checkered_slab"
+  }
+}

```


</details>

<details>
<summary>framedblocks/framing_saw/framed_collapsible_copycat_block</summary>

```diff
+{
+  type: "framedblocks:frame"
+  additives: [
+    {
+      count: 1
+      ingredient: {
+        tag: "forge:ingots/copper"
+      }
+    }
+  ]
+  material: 6144
+  result: {
+    item: "framedblocks:framed_collapsible_copycat_block"
+  }
+}

```


</details>

<details>
<summary>framedblocks/framing_saw/framed_compound_slope_panel</summary>

```diff
+{
+  type: "framedblocks:frame"
+  material: 3072
+  result: {
+    item: "framedblocks:framed_compound_slope_panel"
+  }
+}

```


</details>

<details>
<summary>framedblocks/framing_saw/framed_compound_slope_slab</summary>

```diff
+{
+  type: "framedblocks:frame"
+  material: 3072
+  result: {
+    item: "framedblocks:framed_compound_slope_slab"
+  }
+}

```


</details>

<details>
<summary>framedblocks/framing_saw/framed_corner_strip</summary>

```diff
+{
+  type: "framedblocks:frame"
+  material: 24
+  result: {
+    item: "framedblocks:framed_corner_strip"
+  }
+}

```


</details>

<details>
<summary>framedblocks/framing_saw/framed_double_half_stairs</summary>

```diff
+{
+  type: "framedblocks:frame"
+  material: 3072
+  result: {
+    item: "framedblocks:framed_double_half_stairs"
+  }
+}

```


</details>

<details>
<summary>framedblocks/framing_saw/framed_double_threeway_corner_pillar</summary>

```diff
+{
+  type: "framedblocks:frame"
+  material: 6144
+  result: {
+    item: "framedblocks:framed_double_threeway_corner_pillar"
+  }
+}

```


</details>

<details>
<summary>framedblocks/framing_saw/framed_elevated_double_slope_edge</summary>

```diff
+{
+  type: "framedblocks:frame"
+  material: 6144
+  result: {
+    item: "framedblocks:framed_elevated_double_slope_edge"
+  }
+}

```


</details>

<details>
<summary>framedblocks/framing_saw/framed_elevated_slope_edge</summary>

```diff
+{
+  type: "framedblocks:frame"
+  material: 5376
+  result: {
+    item: "framedblocks:framed_elevated_slope_edge"
+  }
+}

```


</details>

<details>
<summary>framedblocks/framing_saw/framed_masonry_corner</summary>

```diff
+{
+  type: "framedblocks:frame"
+  material: 6144
+  result: {
+    item: "framedblocks:framed_masonry_corner"
+  }
+}

```


</details>

<details>
<summary>framedblocks/framing_saw/framed_sliced_stairs_panel</summary>

```diff
+{
+  type: "framedblocks:frame"
+  material: 4608
+  result: {
+    item: "framedblocks:framed_sliced_stairs_panel"
+  }
+}

```


</details>

<details>
<summary>framedblocks/framing_saw/framed_sliced_stairs_slab</summary>

```diff
+{
+  type: "framedblocks:frame"
+  material: 4608
+  result: {
+    item: "framedblocks:framed_sliced_stairs_slab"
+  }
+}

```


</details>

<details>
<summary>framedblocks/framing_saw/framed_slope_edge</summary>

```diff
+{
+  type: "framedblocks:frame"
+  material: 768
+  result: {
+    item: "framedblocks:framed_slope_edge"
+  }
+}

```


</details>

<details>
<summary>framedblocks/framing_saw/framed_stacked_slope_edge</summary>

```diff
+{
+  type: "framedblocks:frame"
+  material: 5376
+  result: {
+    item: "framedblocks:framed_stacked_slope_edge"
+  }
+}

```


</details>

<details>
<summary>framedblocks/framing_saw/framed_threeway_corner_pillar</summary>

```diff
+{
+  type: "framedblocks:frame"
+  material: 3072
+  result: {
+    item: "framedblocks:framed_threeway_corner_pillar"
+  }
+}

```


</details>

<details>
<summary>framedblocks/framing_saw/framed_vertical_double_half_stairs</summary>

```diff
+{
+  type: "framedblocks:frame"
+  material: 3072
+  result: {
+    item: "framedblocks:framed_vertical_double_half_stairs"
+  }
+}

```


</details>

<details>
<summary>framedblocks/framing_saw/framed_vertical_sliced_stairs</summary>

```diff
+{
+  type: "framedblocks:frame"
+  material: 4608
+  result: {
+    item: "framedblocks:framed_vertical_sliced_stairs"
+  }
+}

```


</details>

<details>
<summary>gtceu/electric_blast_furnace/steel</summary>

```diff
+{
+  type: "gtceu:electric_blast_furnace"
+  duration: 300
+  data: {
+    ebf_temp: 1000
+  }
+  inputs: {
+    fluid: [
+      {
+        content: {
+          amount: 200
+          value: [
+            {
+              fluid: "gtceu:oxygen"
+            }
+          ]
+        }
+        chance: 1
+        tierChanceBoost: 0
+      }
+    ]
+    item: [
+      {
+        content: {
+          type: "gtceu:sized"
+          count: 1
+          ingredient: {
+            tag: "forge:ingots/wrought_iron"
+          }
+        }
+        chance: 1
+        tierChanceBoost: 0
+      }
+    ]
+  }
+  tickInputs: {
+    eu: [
+      {
+        content: 120
+        chance: 1
+        tierChanceBoost: 0
+      }
+    ]
+  }
+  outputs: {
+    item: [
+      {
+        content: {
+          type: "gtceu:sized"
+          count: 1
+          ingredient: {
+            item: "gtceu:ash_dust"
+          }
+        }
+        chance: 0.1111
+        tierChanceBoost: 0.0001
+      }
+      {
+        content: {
+          type: "gtceu:sized"
+          count: 1
+          ingredient: {
+            item: "immersiveengineering:slag"
+          }
+        }
+        chance: 0.2
+        tierChanceBoost: 0.0001
+      }
+      {
+        content: {
+          type: "gtceu:sized"
+          count: 1
+          ingredient: {
+            item: "gtceu:steel_ingot"
+          }
+        }
+        chance: 1
+        tierChanceBoost: 0
+      }
+    ]
+  }
+}

```


</details>

<details>
<summary>gtceu/extractor/seed_oil</summary>

```diff
+{
+  type: "gtceu:extractor"
+  duration: 50
+  inputs: {
+    item: [
+      {
+        content: {
+          type: "gtceu:sized"
+          count: 1
+          ingredient: {
+            tag: "tfc:seeds"
+          }
+        }
+        chance: 1
+        tierChanceBoost: 0
+      }
+    ]
+  }
+  tickInputs: {
+    eu: [
+      {
+        content: 30
+        chance: 1
+        tierChanceBoost: 0
+      }
+    ]
+  }
+  outputs: {
+    fluid: [
+      {
+        content: {
+          amount: 10
+          value: [
+            {
+              fluid: "gtceu:seed_oil"
+            }
+          ]
+        }
+        chance: 1
+        tierChanceBoost: 0
+      }
+    ]
+  }
+}

```


</details>

<details>
<summary>gtceu/macerator/macerate_graphite_block</summary>

```diff
+{
+  type: "gtceu:macerator"
+  duration: 108
+  inputs: {
+    item: [
+      {
+        content: {
+          type: "gtceu:sized"
+          count: 1
+          ingredient: {
+            tag: "forge:storage_blocks/graphite"
+          }
+        }
+        chance: 1
+        tierChanceBoost: 0
+      }
+    ]
+  }
+  outputs: {
+    item: [
+      {
+        content: {
+          type: "gtceu:sized"
+          count: 9
+          ingredient: {
+            item: "gtceu:graphite_dust"
+          }
+        }
+        chance: 1
+        tierChanceBoost: 0
+      }
+    ]
+  }
+  tickInputs: {
+    eu: [
+      {
+        content: 2
+        chance: 1
+        tierChanceBoost: 0
+      }
+    ]
+  }
+  tickOutputs: {
+  }
+}

```


</details>

<details>
<summary>gtceu/macerator/macerate_niob_block</summary>

```diff
+{
+  type: "gtceu:macerator"
+  duration: 306
+  inputs: {
+    item: [
+      {
+        content: {
+          type: "gtceu:sized"
+          count: 1
+          ingredient: {
+            tag: "forge:storage_blocks/pyrochlore"
+          }
+        }
+        chance: 1
+        tierChanceBoost: 0
+      }
+    ]
+  }
+  outputs: {
+    item: [
+      {
+        content: {
+          type: "gtceu:sized"
+          count: 9
+          ingredient: {
+            item: "gtceu:pyrochlore_dust"
+          }
+        }
+        chance: 1
+        tierChanceBoost: 0
+      }
+    ]
+  }
+  tickInputs: {
+    eu: [
+      {
+        content: 2
+        chance: 1
+        tierChanceBoost: 0
+      }
+    ]
+  }
+  tickOutputs: {
+  }
+}

```


</details>

<details>
<summary>gtceu/macerator/macerate_sulfur</summary>

```diff
+{
+  type: "gtceu:macerator"
+  duration: 32
+  inputs: {
+    item: [
+      {
+        content: {
+          type: "gtceu:sized"
+          count: 1
+          ingredient: {
+            tag: "forge:gems/sulfur"
+          }
+        }
+        chance: 1
+        tierChanceBoost: 0
+      }
+    ]
+  }
+  outputs: {
+    item: [
+      {
+        content: {
+          type: "gtceu:sized"
+          count: 1
+          ingredient: {
+            item: "gtceu:sulfur_dust"
+          }
+        }
+        chance: 1
+        tierChanceBoost: 0
+      }
+    ]
+  }
+  tickInputs: {
+    eu: [
+      {
+        content: 2
+        chance: 1
+        tierChanceBoost: 0
+      }
+    ]
+  }
+  tickOutputs: {
+  }
+}

```


</details>

<details>
<summary>gtceu/macerator/macerate_sulfur_block</summary>

```diff
+{
+  type: "gtceu:macerator"
+  duration: 288
+  inputs: {
+    item: [
+      {
+        content: {
+          type: "gtceu:sized"
+          count: 1
+          ingredient: {
+            tag: "forge:storage_blocks/sulfur"
+          }
+        }
+        chance: 1
+        tierChanceBoost: 0
+      }
+    ]
+  }
+  outputs: {
+    item: [
+      {
+        content: {
+          type: "gtceu:sized"
+          count: 9
+          ingredient: {
+            item: "gtceu:sulfur_dust"
+          }
+        }
+        chance: 1
+        tierChanceBoost: 0
+      }
+    ]
+  }
+  tickInputs: {
+    eu: [
+      {
+        content: 2
+        chance: 1
+        tierChanceBoost: 0
+      }
+    ]
+  }
+  tickOutputs: {
+  }
+}

```


</details>

<details>
<summary>gtceu/macerator/macerate_sulfur_chunk</summary>

```diff
+{
+  type: "gtceu:macerator"
+  duration: 3
+  inputs: {
+    item: [
+      {
+        content: {
+          type: "gtceu:sized"
+          count: 1
+          ingredient: {
+            tag: "forge:nuggets/sulfur"
+          }
+        }
+        chance: 1
+        tierChanceBoost: 0
+      }
+    ]
+  }
+  outputs: {
+    item: [
+      {
+        content: {
+          type: "gtceu:sized"
+          count: 1
+          ingredient: {
+            item: "gtceu:tiny_sulfur_dust"
+          }
+        }
+        chance: 1
+        tierChanceBoost: 0
+      }
+    ]
+  }
+  tickInputs: {
+    eu: [
+      {
+        content: 2
+        chance: 1
+        tierChanceBoost: 0
+      }
+    ]
+  }
+  tickOutputs: {
+  }
+}

```


</details>

<details>
<summary>immersiveengineering/metalpress/wire_brass</summary>

```diff
+{
+  type: "immersiveengineering:metal_press"
+  conditions: [
+    {
+      type: "forge:not"
+      value: {
+        type: "forge:tag_empty"
+        tag: "forge:ingots/brass"
+      }
+    }
+    {
+      type: "forge:not"
+      value: {
+        type: "forge:tag_empty"
+        tag: "forge:wires/brass"
+      }
+    }
+  ]
+  energy: 2400
+  input: {
+    tag: "forge:ingots/brass"
+  }
+  mold: "immersiveengineering:mold_wire"
+  result: {
+    base_ingredient: {
+      tag: "forge:wires/brass"
+    }
+    count: 2
+  }
+}

```


</details>

<details>
<summary>minecraft/kjs/computercraft_computer_normal</summary>

```diff
+{
+  type: "minecraft:crafting_shaped"
+  result: {
+    item: "computercraft:computer_normal"
+    count: 1
+  }
+  pattern: [
+    "sps"
+    "scs"
+    "OPO"
+  ]
+  key: {
+    O: {
+      item: "gtceu:iron_plate"
+    }
+    s: {
+      tag: "forge:plates/copper"
+    }
+    c: {
+      item: "gtceu:basic_electronic_circuit"
+    }
+    p: {
+      item: "gtceu:resin_printed_circuit_board"
+    }
+    P: {
+      tag: "forge:glass_panes"
+    }
+  }
+}

```


</details>

<details>
<summary>minecraft/kjs/computercraft_wireless_modem_normal</summary>

```diff
+{
+  type: "minecraft:crafting_shapeless"
+  result: {
+    item: "computercraft:wireless_modem_normal"
+    count: 1
+  }
+  ingredients: [
+    {
+      item: "computercraft:wired_modem"
+    }
+    {
+      item: "minecraft:ender_pearl"
+    }
+  ]
+}

```


</details>

<details>
<summary>minecraft/kjs/gtceu_saltpeter_dust</summary>

```diff
+{
+  type: "minecraft:crafting_shapeless"
+  result: {
+    item: "gtceu:saltpeter_dust"
+    count: 1
+  }
+  ingredients: [
+    {
+      item: "tfc:powder/saltpeter"
+    }
+    {
+      item: "tfc:powder/saltpeter"
+    }
+    {
+      item: "tfc:powder/saltpeter"
+    }
+    {
+      item: "tfc:powder/saltpeter"
+    }
+  ]
+}

```


</details>

<details>
<summary>railcraft/advanced_detector</summary>

```diff
+{
+  type: "minecraft:crafting_shaped"
+  category: "misc"
+  key: {
+    a: {
+      tag: "forge:ingots/steel"
+    }
+    b: {
+      item: "minecraft:stone_pressure_plate"
+    }
+  }
+  pattern: [
+    "aaa"
+    "aba"
+    "aaa"
+  ]
+  result: {
+    item: "railcraft:advanced_detector"
+  }
+  show_notification: true
+}

```


</details>

<details>
<summary>railcraft/age_detector</summary>

```diff
+{
+  type: "minecraft:crafting_shaped"
+  category: "misc"
+  key: {
+    a: {
+      item: "minecraft:dark_oak_log"
+    }
+    b: {
+      item: "minecraft:stone_pressure_plate"
+    }
+  }
+  pattern: [
+    "aaa"
+    "aba"
+    "aaa"
+  ]
+  result: {
+    item: "railcraft:age_detector"
+  }
+  show_notification: true
+}

```


</details>

<details>
<summary>railcraft/animal_detector</summary>

```diff
+{
+  type: "minecraft:crafting_shaped"
+  category: "misc"
+  key: {
+    a: {
+      item: "minecraft:oak_log"
+    }
+    b: {
+      item: "minecraft:stone_pressure_plate"
+    }
+  }
+  pattern: [
+    "aaa"
+    "aba"
+    "aaa"
+  ]
+  result: {
+    item: "railcraft:animal_detector"
+  }
+  show_notification: true
+}

```


</details>

<details>
<summary>railcraft/any_detector</summary>

```diff
+{
+  type: "minecraft:crafting_shaped"
+  category: "misc"
+  key: {
+    a: {
+      item: "minecraft:stone"
+    }
+    b: {
+      item: "minecraft:stone_pressure_plate"
+    }
+  }
+  pattern: [
+    "aaa"
+    "aba"
+    "aaa"
+  ]
+  result: {
+    item: "railcraft:any_detector"
+  }
+  show_notification: true
+}

```


</details>

<details>
<summary>railcraft/chest_minecart_disassembly</summary>

```diff
+{
+  type: "railcraft:chest_minecart_disassembly"
+  category: "misc"
+}

```


</details>

<details>
<summary>railcraft/crusher/crushing_lapis_lazuli</summary>

```diff
+{
+  type: "railcraft:crusher"
+  conditions: [
+    {
+      type: "forge:not"
+      value: {
+        type: "forge:tag_empty"
+        tag: "forge:dusts/lapis"
+      }
+    }
+  ]
+  ingredient: {
+    tag: "forge:gems/lapis"
+  }
+  outputs: [
+    {
+      probability: 1
+      result: {
+        tag: "forge:dusts/lapis"
+      }
+    }
+  ]
+}

```


</details>

<details>
<summary>railcraft/crusher/crushing_personal_world_spike</summary>

```diff
+{
+  type: "railcraft:crusher"
+  ingredient: [
+    {
+      item: "railcraft:personal_world_spike"
+    }
+    {
+      item: "railcraft:world_spike"
+    }
+  ]
+  outputs: [
+    {
+      probability: 1
+      result: {
+        item: "railcraft:crushed_obsidian"
+      }
+    }
+    {
+      probability: 0.5
+      result: {
+        item: "railcraft:crushed_obsidian"
+      }
+    }
+    {
+      probability: 0.25
+      result: {
+        item: "minecraft:obsidian"
+      }
+    }
+    {
+      probability: 0.25
+      result: {
+        item: "railcraft:obsidian_dust"
+      }
+    }
+    {
+      count: 16
+      probability: 1
+      result: {
+        item: "minecraft:gold_nugget"
+      }
+    }
+    {
+      count: 8
+      probability: 0.5
+      result: {
+        item: "minecraft:gold_nugget"
+      }
+    }
+    {
+      count: 8
+      probability: 0.5
+      result: {
+        item: "minecraft:gold_nugget"
+      }
+    }
+    {
+      count: 4
+      probability: 0.5
+      result: {
+        item: "minecraft:gold_nugget"
+      }
+    }
+    {
+      probability: 0.5
+      result: {
+        item: "minecraft:emerald"
+      }
+    }
+  ]
+}

```


</details>

<details>
<summary>railcraft/crusher/crushing_tags_gems_diamond</summary>

```diff
+{
+  type: "railcraft:crusher"
+  conditions: [
+    {
+      type: "forge:not"
+      value: {
+        type: "forge:tag_empty"
+        tag: "forge:gems/diamond"
+      }
+    }
+    {
+      type: "forge:not"
+      value: {
+        type: "forge:tag_empty"
+        tag: "forge:dusts/diamond"
+      }
+    }
+  ]
+  ingredient: {
+    tag: "forge:gems/diamond"
+  }
+  outputs: [
+    {
+      probability: 1
+      result: {
+        tag: "forge:dusts/diamond"
+      }
+    }
+  ]
+}

```


</details>

<details>
<summary>railcraft/crusher/crushing_tags_gems_emerald</summary>

```diff
+{
+  type: "railcraft:crusher"
+  conditions: [
+    {
+      type: "forge:not"
+      value: {
+        type: "forge:tag_empty"
+        tag: "forge:gems/emerald"
+      }
+    }
+    {
+      type: "forge:not"
+      value: {
+        type: "forge:tag_empty"
+        tag: "forge:dusts/emerald"
+      }
+    }
+  ]
+  ingredient: {
+    tag: "forge:gems/emerald"
+  }
+  outputs: [
+    {
+      probability: 1
+      result: {
+        tag: "forge:dusts/emerald"
+      }
+    }
+  ]
+}

```


</details>

<details>
<summary>railcraft/crusher/crushing_tags_gems_quartz</summary>

```diff
+{
+  type: "railcraft:crusher"
+  conditions: [
+    {
+      type: "forge:not"
+      value: {
+        type: "forge:tag_empty"
+        tag: "forge:gems/quartz"
+      }
+    }
+    {
+      type: "forge:not"
+      value: {
+        type: "forge:tag_empty"
+        tag: "forge:dusts/quartz"
+      }
+    }
+  ]
+  ingredient: {
+    tag: "forge:gems/quartz"
+  }
+  outputs: [
+    {
+      probability: 1
+      result: {
+        tag: "forge:dusts/quartz"
+      }
+    }
+  ]
+}

```


</details>

<details>
<summary>railcraft/crusher/crushing_tags_ingots_bronze</summary>

```diff
+{
+  type: "railcraft:crusher"
+  conditions: [
+    {
+      type: "forge:not"
+      value: {
+        type: "forge:tag_empty"
+        tag: "forge:ingots/bronze"
+      }
+    }
+    {
+      type: "forge:not"
+      value: {
+        type: "forge:tag_empty"
+        tag: "forge:dusts/bronze"
+      }
+    }
+  ]
+  ingredient: {
+    tag: "forge:ingots/bronze"
+  }
+  outputs: [
+    {
+      probability: 1
+      result: {
+        tag: "forge:dusts/bronze"
+      }
+    }
+  ]
+}

```


</details>

<details>
<summary>railcraft/crusher/crushing_tags_ingots_copper</summary>

```diff
+{
+  type: "railcraft:crusher"
+  conditions: [
+    {
+      type: "forge:not"
+      value: {
+        type: "forge:tag_empty"
+        tag: "forge:ingots/copper"
+      }
+    }
+    {
+      type: "forge:not"
+      value: {
+        type: "forge:tag_empty"
+        tag: "forge:dusts/copper"
+      }
+    }
+  ]
+  ingredient: {
+    tag: "forge:ingots/copper"
+  }
+  outputs: [
+    {
+      probability: 1
+      result: {
+        tag: "forge:dusts/copper"
+      }
+    }
+  ]
+}

```


</details>

<details>
<summary>railcraft/crusher/crushing_tags_ingots_gold</summary>

```diff
+{
+  type: "railcraft:crusher"
+  conditions: [
+    {
+      type: "forge:not"
+      value: {
+        type: "forge:tag_empty"
+        tag: "forge:ingots/gold"
+      }
+    }
+    {
+      type: "forge:not"
+      value: {
+        type: "forge:tag_empty"
+        tag: "forge:dusts/gold"
+      }
+    }
+  ]
+  ingredient: {
+    tag: "forge:ingots/gold"
+  }
+  outputs: [
+    {
+      probability: 1
+      result: {
+        tag: "forge:dusts/gold"
+      }
+    }
+  ]
+}

```


</details>

<details>
<summary>railcraft/crusher/crushing_tags_ingots_iron</summary>

```diff
+{
+  type: "railcraft:crusher"
+  conditions: [
+    {
+      type: "forge:not"
+      value: {
+        type: "forge:tag_empty"
+        tag: "forge:ingots/iron"
+      }
+    }
+    {
+      type: "forge:not"
+      value: {
+        type: "forge:tag_empty"
+        tag: "forge:dusts/iron"
+      }
+    }
+  ]
+  ingredient: {
+    tag: "forge:ingots/iron"
+  }
+  outputs: [
+    {
+      probability: 1
+      result: {
+        tag: "forge:dusts/iron"
+      }
+    }
+  ]
+}

```


</details>

<details>
<summary>railcraft/crusher/crushing_tags_ingots_lead</summary>

```diff
+{
+  type: "railcraft:crusher"
+  conditions: [
+    {
+      type: "forge:not"
+      value: {
+        type: "forge:tag_empty"
+        tag: "forge:ingots/lead"
+      }
+    }
+    {
+      type: "forge:not"
+      value: {
+        type: "forge:tag_empty"
+        tag: "forge:dusts/lead"
+      }
+    }
+  ]
+  ingredient: {
+    tag: "forge:ingots/lead"
+  }
+  outputs: [
+    {
+      probability: 1
+      result: {
+        tag: "forge:dusts/lead"
+      }
+    }
+  ]
+}

```


</details>

<details>
<summary>railcraft/crusher/crushing_tags_ingots_nickel</summary>

```diff
+{
+  type: "railcraft:crusher"
+  conditions: [
+    {
+      type: "forge:not"
+      value: {
+        type: "forge:tag_empty"
+        tag: "forge:ingots/nickel"
+      }
+    }
+    {
+      type: "forge:not"
+      value: {
+        type: "forge:tag_empty"
+        tag: "forge:dusts/nickel"
+      }
+    }
+  ]
+  ingredient: {
+    tag: "forge:ingots/nickel"
+  }
+  outputs: [
+    {
+      probability: 1
+      result: {
+        tag: "forge:dusts/nickel"
+      }
+    }
+  ]
+}

```


</details>

<details>
<summary>railcraft/crusher/crushing_tags_ingots_silver</summary>

```diff
+{
+  type: "railcraft:crusher"
+  conditions: [
+    {
+      type: "forge:not"
+      value: {
+        type: "forge:tag_empty"
+        tag: "forge:ingots/silver"
+      }
+    }
+    {
+      type: "forge:not"
+      value: {
+        type: "forge:tag_empty"
+        tag: "forge:dusts/silver"
+      }
+    }
+  ]
+  ingredient: {
+    tag: "forge:ingots/silver"
+  }
+  outputs: [
+    {
+      probability: 1
+      result: {
+        tag: "forge:dusts/silver"
+      }
+    }
+  ]
+}

```


</details>

<details>
<summary>railcraft/crusher/crushing_tags_ingots_steel</summary>

```diff
+{
+  type: "railcraft:crusher"
+  conditions: [
+    {
+      type: "forge:not"
+      value: {
+        type: "forge:tag_empty"
+        tag: "forge:ingots/steel"
+      }
+    }
+    {
+      type: "forge:not"
+      value: {
+        type: "forge:tag_empty"
+        tag: "forge:dusts/steel"
+      }
+    }
+  ]
+  ingredient: {
+    tag: "forge:ingots/steel"
+  }
+  outputs: [
+    {
+      probability: 1
+      result: {
+        tag: "forge:dusts/steel"
+      }
+    }
+  ]
+}

```


</details>

<details>
<summary>railcraft/crusher/crushing_tags_ingots_tin</summary>

```diff
+{
+  type: "railcraft:crusher"
+  conditions: [
+    {
+      type: "forge:not"
+      value: {
+        type: "forge:tag_empty"
+        tag: "forge:ingots/tin"
+      }
+    }
+    {
+      type: "forge:not"
+      value: {
+        type: "forge:tag_empty"
+        tag: "forge:dusts/tin"
+      }
+    }
+  ]
+  ingredient: {
+    tag: "forge:ingots/tin"
+  }
+  outputs: [
+    {
+      probability: 1
+      result: {
+        tag: "forge:dusts/tin"
+      }
+    }
+  ]
+}

```


</details>

<details>
<summary>railcraft/crusher/crushing_tags_ores_copper</summary>

```diff
+{
+  type: "railcraft:crusher"
+  conditions: [
+    {
+      type: "forge:not"
+      value: {
+        type: "forge:tag_empty"
+        tag: "forge:ores/copper"
+      }
+    }
+    {
+      type: "forge:not"
+      value: {
+        type: "forge:tag_empty"
+        tag: "forge:dusts/copper"
+      }
+    }
+    {
+      type: "forge:not"
+      value: {
+        type: "forge:tag_empty"
+        tag: "forge:dusts/gold"
+      }
+    }
+  ]
+  ingredient: {
+    tag: "forge:ores/copper"
+  }
+  outputs: [
+    {
+      count: 2
+      probability: 1
+      result: {
+        tag: "forge:dusts/copper"
+      }
+    }
+    {
+      probability: 0.1
+      result: {
+        tag: "forge:dusts/gold"
+      }
+    }
+  ]
+}

```


</details>

<details>
<summary>railcraft/crusher/crushing_tags_ores_gold</summary>

```diff
+{
+  type: "railcraft:crusher"
+  conditions: [
+    {
+      type: "forge:not"
+      value: {
+        type: "forge:tag_empty"
+        tag: "forge:ores/gold"
+      }
+    }
+    {
+      type: "forge:not"
+      value: {
+        type: "forge:tag_empty"
+        tag: "forge:dusts/gold"
+      }
+    }
+  ]
+  ingredient: {
+    tag: "forge:ores/gold"
+  }
+  outputs: [
+    {
+      count: 2
+      probability: 1
+      result: {
+        tag: "forge:dusts/gold"
+      }
+    }
+  ]
+}

```


</details>

<details>
<summary>railcraft/crusher/crushing_tags_ores_iron</summary>

```diff
+{
+  type: "railcraft:crusher"
+  conditions: [
+    {
+      type: "forge:not"
+      value: {
+        type: "forge:tag_empty"
+        tag: "forge:ores/iron"
+      }
+    }
+    {
+      type: "forge:not"
+      value: {
+        type: "forge:tag_empty"
+        tag: "forge:dusts/iron"
+      }
+    }
+    {
+      type: "forge:not"
+      value: {
+        type: "forge:tag_empty"
+        tag: "forge:dusts/nickel"
+      }
+    }
+  ]
+  ingredient: {
+    tag: "forge:ores/iron"
+  }
+  outputs: [
+    {
+      count: 2
+      probability: 1
+      result: {
+        tag: "forge:dusts/iron"
+      }
+    }
+    {
+      probability: 0.1
+      result: {
+        tag: "forge:dusts/nickel"
+      }
+    }
+  ]
+}

```


</details>

<details>
<summary>railcraft/crusher/crushing_tags_ores_lead</summary>

```diff
+{
+  type: "railcraft:crusher"
+  conditions: [
+    {
+      type: "forge:not"
+      value: {
+        type: "forge:tag_empty"
+        tag: "forge:ores/lead"
+      }
+    }
+    {
+      type: "forge:not"
+      value: {
+        type: "forge:tag_empty"
+        tag: "forge:dusts/lead"
+      }
+    }
+    {
+      type: "forge:not"
+      value: {
+        type: "forge:tag_empty"
+        tag: "forge:dusts/silver"
+      }
+    }
+  ]
+  ingredient: {
+    tag: "forge:ores/lead"
+  }
+  outputs: [
+    {
+      count: 2
+      probability: 1
+      result: {
+        tag: "forge:dusts/lead"
+      }
+    }
+    {
+      probability: 0.1
+      result: {
+        tag: "forge:dusts/silver"
+      }
+    }
+  ]
+}

```


</details>

<details>
<summary>railcraft/crusher/crushing_tags_ores_nickel</summary>

```diff
+{
+  type: "railcraft:crusher"
+  conditions: [
+    {
+      type: "forge:not"
+      value: {
+        type: "forge:tag_empty"
+        tag: "forge:ores/nickel"
+      }
+    }
+    {
+      type: "forge:not"
+      value: {
+        type: "forge:tag_empty"
+        tag: "forge:dusts/nickel"
+      }
+    }
+  ]
+  ingredient: {
+    tag: "forge:ores/nickel"
+  }
+  outputs: [
+    {
+      count: 2
+      probability: 1
+      result: {
+        tag: "forge:dusts/nickel"
+      }
+    }
+  ]
+}

```


</details>

<details>
<summary>railcraft/crusher/crushing_tags_ores_salt</summary>

```diff
+{
+  type: "railcraft:crusher"
+  conditions: [
+    {
+      type: "forge:not"
+      value: {
+        type: "forge:tag_empty"
+        tag: "forge:ores/salt"
+      }
+    }
+  ]
+  ingredient: {
+    tag: "forge:ores/salt"
+  }
+  outputs: [
+    {
+      count: 3
+      probability: 1
+      result: {
+        item: "railcraft:saltpeter_dust"
+      }
+    }
+    {
+      probability: 0.85
+      result: {
+        item: "railcraft:saltpeter_dust"
+      }
+    }
+    {
+      probability: 0.35
+      result: {
+        item: "railcraft:saltpeter_dust"
+      }
+    }
+  ]
+}

```


</details>

<details>
<summary>railcraft/crusher/crushing_tags_ores_silver</summary>

```diff
+{
+  type: "railcraft:crusher"
+  conditions: [
+    {
+      type: "forge:not"
+      value: {
+        type: "forge:tag_empty"
+        tag: "forge:ores/silver"
+      }
+    }
+    {
+      type: "forge:not"
+      value: {
+        type: "forge:tag_empty"
+        tag: "forge:dusts/silver"
+      }
+    }
+    {
+      type: "forge:not"
+      value: {
+        type: "forge:tag_empty"
+        tag: "forge:dusts/lead"
+      }
+    }
+  ]
+  ingredient: {
+    tag: "forge:ores/silver"
+  }
+  outputs: [
+    {
+      count: 2
+      probability: 1
+      result: {
+        tag: "forge:dusts/silver"
+      }
+    }
+    {
+      probability: 0.1
+      result: {
+        tag: "forge:dusts/lead"
+      }
+    }
+  ]
+}

```


</details>

<details>
<summary>railcraft/crusher/crushing_tags_raw_materials_copper</summary>

```diff
+{
+  type: "railcraft:crusher"
+  conditions: [
+    {
+      type: "forge:not"
+      value: {
+        type: "forge:tag_empty"
+        tag: "forge:raw_materials/copper"
+      }
+    }
+    {
+      type: "forge:not"
+      value: {
+        type: "forge:tag_empty"
+        tag: "forge:dusts/copper"
+      }
+    }
+    {
+      type: "forge:not"
+      value: {
+        type: "forge:tag_empty"
+        tag: "forge:dusts/copper"
+      }
+    }
+  ]
+  ingredient: {
+    tag: "forge:raw_materials/copper"
+  }
+  outputs: [
+    {
+      probability: 1
+      result: {
+        tag: "forge:dusts/copper"
+      }
+    }
+    {
+      probability: 0.35
+      result: {
+        tag: "forge:dusts/copper"
+      }
+    }
+  ]
+}

```


</details>

<details>
<summary>railcraft/crusher/crushing_tags_raw_materials_iron</summary>

```diff
+{
+  type: "railcraft:crusher"
+  conditions: [
+    {
+      type: "forge:not"
+      value: {
+        type: "forge:tag_empty"
+        tag: "forge:raw_materials/iron"
+      }
+    }
+    {
+      type: "forge:not"
+      value: {
+        type: "forge:tag_empty"
+        tag: "forge:dusts/iron"
+      }
+    }
+    {
+      type: "forge:not"
+      value: {
+        type: "forge:tag_empty"
+        tag: "forge:dusts/iron"
+      }
+    }
+  ]
+  ingredient: {
+    tag: "forge:raw_materials/iron"
+  }
+  outputs: [
+    {
+      probability: 1
+      result: {
+        tag: "forge:dusts/iron"
+      }
+    }
+    {
+      probability: 0.35
+      result: {
+        tag: "forge:dusts/iron"
+      }
+    }
+  ]
+}

```


</details>

<details>
<summary>railcraft/crusher/crushing_tags_raw_materials_nickel</summary>

```diff
+{
+  type: "railcraft:crusher"
+  conditions: [
+    {
+      type: "forge:not"
+      value: {
+        type: "forge:tag_empty"
+        tag: "forge:raw_materials/nickel"
+      }
+    }
+    {
+      type: "forge:not"
+      value: {
+        type: "forge:tag_empty"
+        tag: "forge:dusts/nickel"
+      }
+    }
+    {
+      type: "forge:not"
+      value: {
+        type: "forge:tag_empty"
+        tag: "forge:dusts/nickel"
+      }
+    }
+  ]
+  ingredient: {
+    tag: "forge:raw_materials/nickel"
+  }
+  outputs: [
+    {
+      probability: 1
+      result: {
+        tag: "forge:dusts/nickel"
+      }
+    }
+    {
+      probability: 0.35
+      result: {
+        tag: "forge:dusts/nickel"
+      }
+    }
+  ]
+}

```


</details>

<details>
<summary>railcraft/crusher/crushing_tags_raw_materials_silver</summary>

```diff
+{
+  type: "railcraft:crusher"
+  conditions: [
+    {
+      type: "forge:not"
+      value: {
+        type: "forge:tag_empty"
+        tag: "forge:raw_materials/silver"
+      }
+    }
+    {
+      type: "forge:not"
+      value: {
+        type: "forge:tag_empty"
+        tag: "forge:dusts/silver"
+      }
+    }
+    {
+      type: "forge:not"
+      value: {
+        type: "forge:tag_empty"
+        tag: "forge:dusts/silver"
+      }
+    }
+  ]
+  ingredient: {
+    tag: "forge:raw_materials/silver"
+  }
+  outputs: [
+    {
+      probability: 1
+      result: {
+        tag: "forge:dusts/silver"
+      }
+    }
+    {
+      probability: 0.35
+      result: {
+        tag: "forge:dusts/silver"
+      }
+    }
+  ]
+}

```


</details>

<details>
<summary>railcraft/crusher/crushing_tags_storage_blocks_quartz</summary>

```diff
+{
+  type: "railcraft:crusher"
+  conditions: [
+    {
+      type: "forge:not"
+      value: {
+        type: "forge:tag_empty"
+        tag: "forge:storage_blocks/quartz"
+      }
+    }
+  ]
+  ingredient: {
+    tag: "forge:storage_blocks/quartz"
+  }
+  outputs: [
+    {
+      count: 4
+      probability: 1
+      result: {
+        item: "minecraft:quartz"
+      }
+    }
+  ]
+}

```


</details>

<details>
<summary>railcraft/crusher/crushing_tags_storage_blocks_raw_copper</summary>

```diff
+{
+  type: "railcraft:crusher"
+  conditions: [
+    {
+      type: "forge:not"
+      value: {
+        type: "forge:tag_empty"
+        tag: "forge:storage_blocks/raw_copper"
+      }
+    }
+  ]
+  ingredient: {
+    tag: "forge:storage_blocks/raw_copper"
+  }
+  outputs: [
+    {
+      count: 9
+      probability: 1
+      result: {
+        item: "minecraft:raw_copper"
+      }
+    }
+  ]
+}

```


</details>

<details>
<summary>railcraft/crusher/crushing_tags_storage_blocks_raw_gold</summary>

```diff
+{
+  type: "railcraft:crusher"
+  conditions: [
+    {
+      type: "forge:not"
+      value: {
+        type: "forge:tag_empty"
+        tag: "forge:storage_blocks/raw_gold"
+      }
+    }
+    {
+      type: "forge:not"
+      value: {
+        type: "forge:tag_empty"
+        tag: "forge:dusts/gold"
+      }
+    }
+  ]
+  ingredient: {
+    tag: "forge:storage_blocks/raw_gold"
+  }
+  outputs: [
+    {
+      count: 12
+      probability: 1
+      result: {
+        tag: "forge:dusts/gold"
+      }
+    }
+  ]
+}

```


</details>

<details>
<summary>railcraft/crusher/crushing_tags_storage_blocks_raw_iron</summary>

```diff
+{
+  type: "railcraft:crusher"
+  conditions: [
+    {
+      type: "forge:not"
+      value: {
+        type: "forge:tag_empty"
+        tag: "forge:storage_blocks/raw_iron"
+      }
+    }
+    {
+      type: "forge:not"
+      value: {
+        type: "forge:tag_empty"
+        tag: "forge:dusts/iron"
+      }
+    }
+  ]
+  ingredient: {
+    tag: "forge:storage_blocks/raw_iron"
+  }
+  outputs: [
+    {
+      count: 12
+      probability: 1
+      result: {
+        tag: "forge:dusts/iron"
+      }
+    }
+  ]
+}

```


</details>

<details>
<summary>railcraft/crusher/crushing_tags_storage_blocks_raw_lead</summary>

```diff
+{
+  type: "railcraft:crusher"
+  conditions: [
+    {
+      type: "forge:not"
+      value: {
+        type: "forge:tag_empty"
+        tag: "forge:storage_blocks/raw_lead"
+      }
+    }
+    {
+      type: "forge:not"
+      value: {
+        type: "forge:tag_empty"
+        tag: "forge:dusts/lead"
+      }
+    }
+  ]
+  ingredient: {
+    tag: "forge:storage_blocks/raw_lead"
+  }
+  outputs: [
+    {
+      count: 12
+      probability: 1
+      result: {
+        tag: "forge:dusts/lead"
+      }
+    }
+  ]
+}

```


</details>

<details>
<summary>railcraft/crusher/crushing_tags_storage_blocks_raw_nickel</summary>

```diff
+{
+  type: "railcraft:crusher"
+  conditions: [
+    {
+      type: "forge:not"
+      value: {
+        type: "forge:tag_empty"
+        tag: "forge:storage_blocks/raw_nickel"
+      }
+    }
+    {
+      type: "forge:not"
+      value: {
+        type: "forge:tag_empty"
+        tag: "forge:dusts/nickel"
+      }
+    }
+  ]
+  ingredient: {
+    tag: "forge:storage_blocks/raw_nickel"
+  }
+  outputs: [
+    {
+      count: 12
+      probability: 1
+      result: {
+        tag: "forge:dusts/nickel"
+      }
+    }
+  ]
+}

```


</details>

<details>
<summary>railcraft/crusher/crushing_tags_storage_blocks_raw_silver</summary>

```diff
+{
+  type: "railcraft:crusher"
+  conditions: [
+    {
+      type: "forge:not"
+      value: {
+        type: "forge:tag_empty"
+        tag: "forge:storage_blocks/raw_silver"
+      }
+    }
+    {
+      type: "forge:not"
+      value: {
+        type: "forge:tag_empty"
+        tag: "forge:dusts/silver"
+      }
+    }
+  ]
+  ingredient: {
+    tag: "forge:storage_blocks/raw_silver"
+  }
+  outputs: [
+    {
+      count: 12
+      probability: 1
+      result: {
+        tag: "forge:dusts/silver"
+      }
+    }
+  ]
+}

```


</details>

<details>
<summary>railcraft/crusher/crushing_zinc_silver_battery_empty</summary>

```diff
+{
+  type: "railcraft:crusher"
+  ingredient: [
+    {
+      item: "railcraft:zinc_silver_battery_empty"
+    }
+    {
+      item: "railcraft:zinc_carbon_battery_empty"
+    }
+  ]
+  outputs: [
+    {
+      count: 2
+      probability: 1
+      result: {
+        item: "railcraft:charge_terminal"
+      }
+    }
+    {
+      probability: 1
+      result: {
+        item: "railcraft:charge_spool_medium"
+      }
+    }
+    {
+      count: 4
+      probability: 1
+      result: {
+        item: "railcraft:slag"
+      }
+    }
+    {
+      count: 2
+      probability: 0.5
+      result: {
+        item: "railcraft:slag"
+      }
+    }
+  ]
+}

```


</details>

<details>
<summary>railcraft/empty_detector</summary>

```diff
+{
+  type: "minecraft:crafting_shaped"
+  category: "misc"
+  key: {
+    a: {
+      item: "minecraft:stone_bricks"
+    }
+    b: {
+      item: "minecraft:stone_pressure_plate"
+    }
+  }
+  pattern: [
+    "aaa"
+    "aba"
+    "aaa"
+  ]
+  result: {
+    item: "railcraft:empty_detector"
+  }
+  show_notification: true
+}

```


</details>

<details>
<summary>railcraft/item_detector</summary>

```diff
+{
+  type: "minecraft:crafting_shaped"
+  category: "misc"
+  key: {
+    a: {
+      item: "minecraft:stripped_acacia_wood"
+    }
+    b: {
+      item: "minecraft:stone_pressure_plate"
+    }
+  }
+  pattern: [
+    "aaa"
+    "aba"
+    "aaa"
+  ]
+  result: {
+    item: "railcraft:item_detector"
+  }
+  show_notification: true
+}

```


</details>

<details>
<summary>railcraft/locomotive_detector</summary>

```diff
+{
+  type: "minecraft:crafting_shaped"
+  category: "misc"
+  key: {
+    a: {
+      item: "railcraft:blast_furnace_bricks"
+    }
+    b: {
+      item: "minecraft:stone_pressure_plate"
+    }
+  }
+  pattern: [
+    "aaa"
+    "aba"
+    "aaa"
+  ]
+  result: {
+    item: "railcraft:locomotive_detector"
+  }
+  show_notification: true
+}

```


</details>

<details>
<summary>railcraft/mob_detector</summary>

```diff
+{
+  type: "minecraft:crafting_shaped"
+  category: "misc"
+  key: {
+    a: {
+      item: "minecraft:mossy_cobblestone"
+    }
+    b: {
+      item: "minecraft:stone_pressure_plate"
+    }
+  }
+  pattern: [
+    "aaa"
+    "aba"
+    "aaa"
+  ]
+  result: {
+    item: "railcraft:mob_detector"
+  }
+  show_notification: true
+}

```


</details>

<details>
<summary>railcraft/personal_world_spike</summary>

```diff
+{
+  type: "minecraft:crafting_shaped"
+  category: "misc"
+  key: {
+    d: {
+      tag: "forge:gems/emerald"
+    }
+    g: {
+      tag: "forge:ingots/gold"
+    }
+    o: {
+      item: "minecraft:obsidian"
+    }
+    p: {
+      item: "minecraft:ender_pearl"
+    }
+  }
+  pattern: [
+    "gog"
+    "dpd"
+    "gog"
+  ]
+  result: {
+    item: "railcraft:personal_world_spike"
+  }
+  show_notification: true
+}

```


</details>

<details>
<summary>railcraft/player_detector</summary>

```diff
+{
+  type: "minecraft:crafting_shaped"
+  category: "misc"
+  key: {
+    a: {
+      item: "minecraft:stone_slab"
+    }
+    b: {
+      item: "minecraft:stone_pressure_plate"
+    }
+  }
+  pattern: [
+    "aaa"
+    "aba"
+    "aaa"
+  ]
+  result: {
+    item: "railcraft:player_detector"
+  }
+  show_notification: true
+}

```


</details>

<details>
<summary>railcraft/routing_detector</summary>

```diff
+{
+  type: "minecraft:crafting_shaped"
+  category: "misc"
+  key: {
+    a: {
+      item: "minecraft:chiseled_quartz_block"
+    }
+    b: {
+      item: "minecraft:stone_pressure_plate"
+    }
+  }
+  pattern: [
+    "aaa"
+    "aba"
+    "aaa"
+  ]
+  result: {
+    item: "railcraft:routing_detector"
+  }
+  show_notification: true
+}

```


</details>

<details>
<summary>railcraft/sheep_detector</summary>

```diff
+{
+  type: "minecraft:crafting_shaped"
+  category: "misc"
+  key: {
+    a: {
+      tag: "minecraft:wool"
+    }
+    b: {
+      item: "minecraft:stone_pressure_plate"
+    }
+  }
+  pattern: [
+    "aaa"
+    "aba"
+    "aaa"
+  ]
+  result: {
+    item: "railcraft:sheep_detector"
+  }
+  show_notification: true
+}

```


</details>

<details>
<summary>railcraft/tank_detector</summary>

```diff
+{
+  type: "minecraft:crafting_shaped"
+  category: "misc"
+  key: {
+    a: {
+      item: "minecraft:brick"
+    }
+    b: {
+      item: "minecraft:stone_pressure_plate"
+    }
+  }
+  pattern: [
+    "aaa"
+    "aba"
+    "aaa"
+  ]
+  result: {
+    item: "railcraft:tank_detector"
+  }
+  show_notification: true
+}

```


</details>

<details>
<summary>railcraft/token_signal_box</summary>

```diff
+{
+  type: "minecraft:crafting_shaped"
+  category: "misc"
+  key: {
+    a: {
+      item: "tfc:metal/ingot/cast_iron"
+    }
+    b: {
+      item: "railcraft:radio_circuit"
+    }
+    c: {
+      item: "minecraft:redstone"
+    }
+  }
+  pattern: [
+    " c "
+    "aba"
+    "aca"
+  ]
+  result: {
+    item: "railcraft:token_signal_box"
+  }
+  show_notification: true
+}

```


</details>

<details>
<summary>railcraft/train_detector</summary>

```diff
+{
+  type: "minecraft:crafting_shaped"
+  category: "misc"
+  key: {
+    a: {
+      item: "minecraft:nether_brick"
+    }
+    b: {
+      item: "minecraft:stone_pressure_plate"
+    }
+  }
+  pattern: [
+    "aaa"
+    "aba"
+    "aaa"
+  ]
+  result: {
+    item: "railcraft:train_detector"
+  }
+  show_notification: true
+}

```


</details>

<details>
<summary>railcraft/villager_detector</summary>

```diff
+{
+  type: "minecraft:crafting_shaped"
+  category: "misc"
+  key: {
+    a: {
+      item: "minecraft:leather"
+    }
+    b: {
+      item: "minecraft:stone_pressure_plate"
+    }
+  }
+  pattern: [
+    "aaa"
+    "aba"
+    "aaa"
+  ]
+  result: {
+    item: "railcraft:villager_detector"
+  }
+  show_notification: true
+}

```


</details>

<details>
<summary>railcraft/world_spike</summary>

```diff
+{
+  type: "minecraft:crafting_shaped"
+  category: "misc"
+  key: {
+    d: {
+      tag: "forge:gems/diamond"
+    }
+    g: {
+      tag: "forge:ingots/gold"
+    }
+    o: {
+      item: "minecraft:obsidian"
+    }
+    p: {
+      item: "minecraft:ender_pearl"
+    }
+  }
+  pattern: [
+    "gog"
+    "dpd"
+    "gog"
+  ]
+  result: {
+    item: "railcraft:world_spike"
+  }
+  show_notification: true
+}

```


</details>

<details>
<summary>railcraft/world_spike_minecart</summary>

```diff
+{
+  type: "minecraft:crafting_shaped"
+  category: "misc"
+  key: {
+    a: {
+      item: "railcraft:world_spike"
+    }
+    b: {
+      item: "minecraft:minecart"
+    }
+  }
+  pattern: [
+    "a"
+    "b"
+  ]
+  result: {
+    item: "railcraft:world_spike_minecart"
+  }
+  show_notification: true
+}

```


</details>

<details>
<summary>railcraft/worldspike_minecart_disassembly</summary>

```diff
+{
+  type: "railcraft:worldspike_minecart_disassembly"
+  category: "misc"
+}

```


</details>

<details>
<summary>sgjourney/universe_stargate_chevron</summary>

```diff
+{
+  type: "minecraft:crafting_shaped"
+  category: "misc"
+  pattern: [
+    "GTG"
+    "GEG"
+    " R "
+  ]
+  key: {
+    G: {
+      item: "minecraft:white_stained_glass_pane"
+    }
+    E: {
+      item: "sgjourney:materialization_crystal"
+    }
+    T: {
+      item: "sgjourney:transfer_crystal"
+    }
+    R: {
+      item: "sgjourney:energy_crystal"
+    }
+  }
+  result: {
+    item: "sgjourney:universe_stargate_chevron"
+  }
+}

```


</details>

<details>
<summary>smallships/bamboo_drakkar</summary>

```diff
+{
+  type: "minecraft:crafting_shaped"
+  group: "drakkar"
+  pattern: [
+    "sys"
+    "xlx"
+    "   "
+  ]
+  key: {
+    y: {
+      item: "smallships:sail"
+    }
+    x: {
+      item: "minecraft:chest"
+    }
+    l: {
+      item: "minecraft:lead"
+    }
+    s: {
+      item: "minecraft:string"
+    }
+  }
+  result: {
+    item: "smallships:bamboo_drakkar"
+  }
+}

```


</details>

<details>
<summary>smallships/cherry_drakkar</summary>

```diff
+{
+  type: "minecraft:crafting_shaped"
+  group: "drakkar"
+  pattern: [
+    "sys"
+    "xlx"
+    "bbb"
+  ]
+  key: {
+    y: {
+      item: "smallships:sail"
+    }
+    x: {
+      item: "minecraft:chest"
+    }
+    l: {
+      item: "minecraft:lead"
+    }
+    s: {
+      item: "minecraft:string"
+    }
+    b: {
+      item: "minecraft:cherry_boat"
+    }
+  }
+  result: {
+    item: "smallships:cherry_drakkar"
+  }
+}

```


</details>

<details>
<summary>tfc/casting/rubber_to_fire_mold</summary>

```diff
+{
+  type: "tfc:casting"
+  mold: {
+    item: "tfc:ceramic/fire_ingot_mold"
+  }
+  fluid: {
+    ingredient: {
+      fluid: "gtceu:rubber"
+      amount: 1000
+    }
+    amount: 144
+  }
+  result: {
+    item: "gtceu:rubber_ingot"
+  }
+  break_chance: 0.01
+}

```


</details>

<details>
<summary>tfc/casting/rubber_to_mold</summary>

```diff
+{
+  type: "tfc:casting"
+  mold: {
+    item: "tfc:ceramic/ingot_mold"
+  }
+  fluid: {
+    ingredient: {
+      fluid: "gtceu:rubber"
+      amount: 1000
+    }
+    amount: 144
+  }
+  result: {
+    item: "gtceu:rubber_ingot"
+  }
+  break_chance: 0.1
+}

```


</details>

<details>
<summary>tfc/collapse/rock_cobble_andesite</summary>

```diff
+{
+  type: "tfc:collapse"
+  ingredient: [
+    "gtceu:andesite_apatite_ore"
+    "gtceu:andesite_tricalcium_phosphate_ore"
+    "gtceu:andesite_pyrochlore_ore"
+    "gtceu:andesite_tin_ore"
+    "gtceu:andesite_cassiterite_ore"
+    "gtceu:andesite_chalcopyrite_ore"
+    "gtceu:andesite_zeolite_ore"
+    "gtceu:andesite_realgar_ore"
+    "gtceu:andesite_galena_ore"
+    "gtceu:andesite_silver_ore"
+    "gtceu:andesite_lead_ore"
+    "gtceu:andesite_cassiterite_sand_ore"
+    "gtceu:andesite_garnet_sand_ore"
+    "gtceu:andesite_asbestos_ore"
+    "gtceu:andesite_diatomite_ore"
+    "gtceu:andesite_red_garnet_ore"
+    "gtceu:andesite_yellow_garnet_ore"
+    "gtceu:andesite_amethyst_ore"
+    "gtceu:andesite_opal_ore"
+    "gtceu:andesite_goethite_ore"
+    "gtceu:andesite_yellow_limonite_ore"
+    "gtceu:andesite_hematite_ore"
+    "gtceu:andesite_malachite_ore"
+    "gtceu:andesite_soapstone_ore"
+    "gtceu:andesite_talc_ore"
+    "gtceu:andesite_glauconite_sand_ore"
+    "gtceu:andesite_pentlandite_ore"
+    "gtceu:andesite_magnetite_ore"
+    "gtceu:andesite_vanadium_magnetite_ore"
+    "gtceu:andesite_basaltic_mineral_sand_ore"
+    "gtceu:andesite_granitic_mineral_sand_ore"
+    "gtceu:andesite_fullers_earth_ore"
+    "gtceu:andesite_gypsum_ore"
+    "gtceu:andesite_garnierite_ore"
+    "gtceu:andesite_nickel_ore"
+    "gtceu:andesite_cobaltite_ore"
+    "gtceu:andesite_rock_salt_ore"
+    "gtceu:andesite_salt_ore"
+    "gtceu:andesite_lepidolite_ore"
+    "gtceu:andesite_spodumene_ore"
+    "gtceu:andesite_oilsands_ore"
+    "gtceu:andesite_pyrite_ore"
+    "gtceu:andesite_lazurite_ore"
+    "gtceu:andesite_sodalite_ore"
+    "gtceu:andesite_lapis_ore"
+    "gtceu:andesite_calcite_ore"
+    "gtceu:andesite_grossular_ore"
+    "gtceu:andesite_spessartine_ore"
+    "gtceu:andesite_pyrolusite_ore"
+    "gtceu:andesite_tantalite_ore"
+    "gtceu:andesite_kyanite_ore"
+    "gtceu:andesite_mica_ore"
+    "gtceu:andesite_bauxite_ore"
+    "gtceu:andesite_pollucite_ore"
+    "gtceu:andesite_bentonite_ore"
+    "gtceu:andesite_olivine_ore"
+    "gtceu:andesite_redstone_ore"
+    "gtceu:andesite_ruby_ore"
+    "gtceu:andesite_cinnabar_ore"
+    "gtceu:andesite_almandine_ore"
+    "gtceu:andesite_pyrope_ore"
+    "gtceu:andesite_sapphire_ore"
+    "gtceu:andesite_green_sapphire_ore"
+    "gtceu:andesite_thorium_ore"
+    "gtceu:andesite_chromite_ore"
+  ]
+  result: "tfc:rock/cobble/andesite"
+}

```


</details>

<details>
<summary>tfc/collapse/rock_cobble_andesite_slab</summary>

```diff
+{
+  type: "tfc:collapse"
+  ingredient: [
+    "tfc:rock/cobble/andesite_slab"
+  ]
+  result: "tfc:rock/cobble/andesite_slab"
+}

```


</details>

<details>
<summary>tfc/collapse/rock_cobble_basalt</summary>

```diff
+{
+  type: "tfc:collapse"
+  ingredient: [
+    "gtceu:basalt_apatite_ore"
+    "gtceu:basalt_tricalcium_phosphate_ore"
+    "gtceu:basalt_pyrochlore_ore"
+    "gtceu:basalt_tin_ore"
+    "gtceu:basalt_cassiterite_ore"
+    "gtceu:basalt_chalcopyrite_ore"
+    "gtceu:basalt_zeolite_ore"
+    "gtceu:basalt_realgar_ore"
+    "gtceu:basalt_galena_ore"
+    "gtceu:basalt_silver_ore"
+    "gtceu:basalt_lead_ore"
+    "gtceu:basalt_cassiterite_sand_ore"
+    "gtceu:basalt_garnet_sand_ore"
+    "gtceu:basalt_asbestos_ore"
+    "gtceu:basalt_diatomite_ore"
+    "gtceu:basalt_red_garnet_ore"
+    "gtceu:basalt_yellow_garnet_ore"
+    "gtceu:basalt_amethyst_ore"
+    "gtceu:basalt_opal_ore"
+    "gtceu:basalt_goethite_ore"
+    "gtceu:basalt_yellow_limonite_ore"
+    "gtceu:basalt_hematite_ore"
+    "gtceu:basalt_malachite_ore"
+    "gtceu:basalt_soapstone_ore"
+    "gtceu:basalt_talc_ore"
+    "gtceu:basalt_glauconite_sand_ore"
+    "gtceu:basalt_pentlandite_ore"
+    "gtceu:basalt_magnetite_ore"
+    "gtceu:basalt_vanadium_magnetite_ore"
+    "gtceu:basalt_basaltic_mineral_sand_ore"
+    "gtceu:basalt_granitic_mineral_sand_ore"
+    "gtceu:basalt_fullers_earth_ore"
+    "gtceu:basalt_gypsum_ore"
+    "gtceu:basalt_garnierite_ore"
+    "gtceu:basalt_nickel_ore"
+    "gtceu:basalt_cobaltite_ore"
+    "gtceu:basalt_rock_salt_ore"
+    "gtceu:basalt_salt_ore"
+    "gtceu:basalt_lepidolite_ore"
+    "gtceu:basalt_spodumene_ore"
+    "gtceu:basalt_oilsands_ore"
+    "gtceu:basalt_pyrite_ore"
+    "gtceu:basalt_lazurite_ore"
+    "gtceu:basalt_sodalite_ore"
+    "gtceu:basalt_lapis_ore"
+    "gtceu:basalt_calcite_ore"
+    "gtceu:basalt_grossular_ore"
+    "gtceu:basalt_spessartine_ore"
+    "gtceu:basalt_pyrolusite_ore"
+    "gtceu:basalt_tantalite_ore"
+    "gtceu:basalt_kyanite_ore"
+    "gtceu:basalt_mica_ore"
+    "gtceu:basalt_bauxite_ore"
+    "gtceu:basalt_pollucite_ore"
+    "gtceu:basalt_bentonite_ore"
+    "gtceu:basalt_olivine_ore"
+    "gtceu:basalt_redstone_ore"
+    "gtceu:basalt_ruby_ore"
+    "gtceu:basalt_cinnabar_ore"
+    "gtceu:basalt_almandine_ore"
+    "gtceu:basalt_pyrope_ore"
+    "gtceu:basalt_sapphire_ore"
+    "gtceu:basalt_green_sapphire_ore"
+    "gtceu:basalt_thorium_ore"
+    "gtceu:basalt_chromite_ore"
+  ]
+  result: "tfc:rock/cobble/basalt"
+}

```


</details>

<details>
<summary>tfc/collapse/rock_cobble_basalt_slab</summary>

```diff
+{
+  type: "tfc:collapse"
+  ingredient: [
+    "tfc:rock/cobble/basalt_slab"
+  ]
+  result: "tfc:rock/cobble/basalt_slab"
+}

```


</details>

<details>
<summary>tfc/collapse/rock_cobble_chalk</summary>

```diff
+{
+  type: "tfc:collapse"
+  ingredient: [
+    "gtceu:chalk_apatite_ore"
+    "gtceu:chalk_tricalcium_phosphate_ore"
+    "gtceu:chalk_pyrochlore_ore"
+    "gtceu:chalk_tin_ore"
+    "gtceu:chalk_cassiterite_ore"
+    "gtceu:chalk_chalcopyrite_ore"
+    "gtceu:chalk_zeolite_ore"
+    "gtceu:chalk_realgar_ore"
+    "gtceu:chalk_galena_ore"
+    "gtceu:chalk_silver_ore"
+    "gtceu:chalk_lead_ore"
+    "gtceu:chalk_cassiterite_sand_ore"
+    "gtceu:chalk_garnet_sand_ore"
+    "gtceu:chalk_asbestos_ore"
+    "gtceu:chalk_diatomite_ore"
+    "gtceu:chalk_red_garnet_ore"
+    "gtceu:chalk_yellow_garnet_ore"
+    "gtceu:chalk_amethyst_ore"
+    "gtceu:chalk_opal_ore"
+    "gtceu:chalk_goethite_ore"
+    "gtceu:chalk_yellow_limonite_ore"
+    "gtceu:chalk_hematite_ore"
+    "gtceu:chalk_malachite_ore"
+    "gtceu:chalk_soapstone_ore"
+    "gtceu:chalk_talc_ore"
+    "gtceu:chalk_glauconite_sand_ore"
+    "gtceu:chalk_pentlandite_ore"
+    "gtceu:chalk_magnetite_ore"
+    "gtceu:chalk_vanadium_magnetite_ore"
+    "gtceu:chalk_basaltic_mineral_sand_ore"
+    "gtceu:chalk_granitic_mineral_sand_ore"
+    "gtceu:chalk_fullers_earth_ore"
+    "gtceu:chalk_gypsum_ore"
+    "gtceu:chalk_garnierite_ore"
+    "gtceu:chalk_nickel_ore"
+    "gtceu:chalk_cobaltite_ore"
+    "gtceu:chalk_rock_salt_ore"
+    "gtceu:chalk_salt_ore"
+    "gtceu:chalk_lepidolite_ore"
+    "gtceu:chalk_spodumene_ore"
+    "gtceu:chalk_oilsands_ore"
+    "gtceu:chalk_pyrite_ore"
+    "gtceu:chalk_lazurite_ore"
+    "gtceu:chalk_sodalite_ore"
+    "gtceu:chalk_lapis_ore"
+    "gtceu:chalk_calcite_ore"
+    "gtceu:chalk_grossular_ore"
+    "gtceu:chalk_spessartine_ore"
+    "gtceu:chalk_pyrolusite_ore"
+    "gtceu:chalk_tantalite_ore"
+    "gtceu:chalk_kyanite_ore"
+    "gtceu:chalk_mica_ore"
+    "gtceu:chalk_bauxite_ore"
+    "gtceu:chalk_pollucite_ore"
+    "gtceu:chalk_bentonite_ore"
+    "gtceu:chalk_olivine_ore"
+    "gtceu:chalk_redstone_ore"
+    "gtceu:chalk_ruby_ore"
+    "gtceu:chalk_cinnabar_ore"
+    "gtceu:chalk_almandine_ore"
+    "gtceu:chalk_pyrope_ore"
+    "gtceu:chalk_sapphire_ore"
+    "gtceu:chalk_green_sapphire_ore"
+    "gtceu:chalk_thorium_ore"
+    "gtceu:chalk_chromite_ore"
+  ]
+  result: "tfc:rock/cobble/chalk"
+}

```


</details>

<details>
<summary>tfc/collapse/rock_cobble_chalk_slab</summary>

```diff
+{
+  type: "tfc:collapse"
+  ingredient: [
+    "tfc:rock/cobble/chalk_slab"
+  ]
+  result: "tfc:rock/cobble/chalk_slab"
+}

```


</details>

<details>
<summary>tfc/collapse/rock_cobble_chert</summary>

```diff
+{
+  type: "tfc:collapse"
+  ingredient: [
+    "gtceu:chert_apatite_ore"
+    "gtceu:chert_tricalcium_phosphate_ore"
+    "gtceu:chert_pyrochlore_ore"
+    "gtceu:chert_tin_ore"
+    "gtceu:chert_cassiterite_ore"
+    "gtceu:chert_chalcopyrite_ore"
+    "gtceu:chert_zeolite_ore"
+    "gtceu:chert_realgar_ore"
+    "gtceu:chert_galena_ore"
+    "gtceu:chert_silver_ore"
+    "gtceu:chert_lead_ore"
+    "gtceu:chert_cassiterite_sand_ore"
+    "gtceu:chert_garnet_sand_ore"
+    "gtceu:chert_asbestos_ore"
+    "gtceu:chert_diatomite_ore"
+    "gtceu:chert_red_garnet_ore"
+    "gtceu:chert_yellow_garnet_ore"
+    "gtceu:chert_amethyst_ore"
+    "gtceu:chert_opal_ore"
+    "gtceu:chert_goethite_ore"
+    "gtceu:chert_yellow_limonite_ore"
+    "gtceu:chert_hematite_ore"
+    "gtceu:chert_malachite_ore"
+    "gtceu:chert_soapstone_ore"
+    "gtceu:chert_talc_ore"
+    "gtceu:chert_glauconite_sand_ore"
+    "gtceu:chert_pentlandite_ore"
+    "gtceu:chert_magnetite_ore"
+    "gtceu:chert_vanadium_magnetite_ore"
+    "gtceu:chert_basaltic_mineral_sand_ore"
+    "gtceu:chert_granitic_mineral_sand_ore"
+    "gtceu:chert_fullers_earth_ore"
+    "gtceu:chert_gypsum_ore"
+    "gtceu:chert_garnierite_ore"
+    "gtceu:chert_nickel_ore"
+    "gtceu:chert_cobaltite_ore"
+    "gtceu:chert_rock_salt_ore"
+    "gtceu:chert_salt_ore"
+    "gtceu:chert_lepidolite_ore"
+    "gtceu:chert_spodumene_ore"
+    "gtceu:chert_oilsands_ore"
+    "gtceu:chert_pyrite_ore"
+    "gtceu:chert_lazurite_ore"
+    "gtceu:chert_sodalite_ore"
+    "gtceu:chert_lapis_ore"
+    "gtceu:chert_calcite_ore"
+    "gtceu:chert_grossular_ore"
+    "gtceu:chert_spessartine_ore"
+    "gtceu:chert_pyrolusite_ore"
+    "gtceu:chert_tantalite_ore"
+    "gtceu:chert_kyanite_ore"
+    "gtceu:chert_mica_ore"
+    "gtceu:chert_bauxite_ore"
+    "gtceu:chert_pollucite_ore"
+    "gtceu:chert_bentonite_ore"
+    "gtceu:chert_olivine_ore"
+    "gtceu:chert_redstone_ore"
+    "gtceu:chert_ruby_ore"
+    "gtceu:chert_cinnabar_ore"
+    "gtceu:chert_almandine_ore"
+    "gtceu:chert_pyrope_ore"
+    "gtceu:chert_sapphire_ore"
+    "gtceu:chert_green_sapphire_ore"
+    "gtceu:chert_thorium_ore"
+    "gtceu:chert_chromite_ore"
+  ]
+  result: "tfc:rock/cobble/chert"
+}

```


</details>

<details>
<summary>tfc/collapse/rock_cobble_chert_slab</summary>

```diff
+{
+  type: "tfc:collapse"
+  ingredient: [
+    "tfc:rock/cobble/chert_slab"
+  ]
+  result: "tfc:rock/cobble/chert_slab"
+}

```


</details>

<details>
<summary>tfc/collapse/rock_cobble_claystone</summary>

```diff
+{
+  type: "tfc:collapse"
+  ingredient: [
+    "gtceu:claystone_apatite_ore"
+    "gtceu:claystone_tricalcium_phosphate_ore"
+    "gtceu:claystone_pyrochlore_ore"
+    "gtceu:claystone_tin_ore"
+    "gtceu:claystone_cassiterite_ore"
+    "gtceu:claystone_chalcopyrite_ore"
+    "gtceu:claystone_zeolite_ore"
+    "gtceu:claystone_realgar_ore"
+    "gtceu:claystone_galena_ore"
+    "gtceu:claystone_silver_ore"
+    "gtceu:claystone_lead_ore"
+    "gtceu:claystone_cassiterite_sand_ore"
+    "gtceu:claystone_garnet_sand_ore"
+    "gtceu:claystone_asbestos_ore"
+    "gtceu:claystone_diatomite_ore"
+    "gtceu:claystone_red_garnet_ore"
+    "gtceu:claystone_yellow_garnet_ore"
+    "gtceu:claystone_amethyst_ore"
+    "gtceu:claystone_opal_ore"
+    "gtceu:claystone_goethite_ore"
+    "gtceu:claystone_yellow_limonite_ore"
+    "gtceu:claystone_hematite_ore"
+    "gtceu:claystone_malachite_ore"
+    "gtceu:claystone_soapstone_ore"
+    "gtceu:claystone_talc_ore"
+    "gtceu:claystone_glauconite_sand_ore"
+    "gtceu:claystone_pentlandite_ore"
+    "gtceu:claystone_magnetite_ore"
+    "gtceu:claystone_vanadium_magnetite_ore"
+    "gtceu:claystone_basaltic_mineral_sand_ore"
+    "gtceu:claystone_granitic_mineral_sand_ore"
+    "gtceu:claystone_fullers_earth_ore"
+    "gtceu:claystone_gypsum_ore"
+    "gtceu:claystone_garnierite_ore"
+    "gtceu:claystone_nickel_ore"
+    "gtceu:claystone_cobaltite_ore"
+    "gtceu:claystone_rock_salt_ore"
+    "gtceu:claystone_salt_ore"
+    "gtceu:claystone_lepidolite_ore"
+    "gtceu:claystone_spodumene_ore"
+    "gtceu:claystone_oilsands_ore"
+    "gtceu:claystone_pyrite_ore"
+    "gtceu:claystone_lazurite_ore"
+    "gtceu:claystone_sodalite_ore"
+    "gtceu:claystone_lapis_ore"
+    "gtceu:claystone_calcite_ore"
+    "gtceu:claystone_grossular_ore"
+    "gtceu:claystone_spessartine_ore"
+    "gtceu:claystone_pyrolusite_ore"
+    "gtceu:claystone_tantalite_ore"
+    "gtceu:claystone_kyanite_ore"
+    "gtceu:claystone_mica_ore"
+    "gtceu:claystone_bauxite_ore"
+    "gtceu:claystone_pollucite_ore"
+    "gtceu:claystone_bentonite_ore"
+    "gtceu:claystone_olivine_ore"
+    "gtceu:claystone_redstone_ore"
+    "gtceu:claystone_ruby_ore"
+    "gtceu:claystone_cinnabar_ore"
+    "gtceu:claystone_almandine_ore"
+    "gtceu:claystone_pyrope_ore"
+    "gtceu:claystone_sapphire_ore"
+    "gtceu:claystone_green_sapphire_ore"
+    "gtceu:claystone_thorium_ore"
+    "gtceu:claystone_chromite_ore"
+  ]
+  result: "tfc:rock/cobble/claystone"
+}

```


</details>

<details>
<summary>tfc/collapse/rock_cobble_claystone_slab</summary>

```diff
+{
+  type: "tfc:collapse"
+  ingredient: [
+    "tfc:rock/cobble/claystone_slab"
+  ]
+  result: "tfc:rock/cobble/claystone_slab"
+}

```


</details>

<details>
<summary>tfc/collapse/rock_cobble_conglomerate</summary>

```diff
+{
+  type: "tfc:collapse"
+  ingredient: [
+    "gtceu:conglomerate_apatite_ore"
+    "gtceu:conglomerate_tricalcium_phosphate_ore"
+    "gtceu:conglomerate_pyrochlore_ore"
+    "gtceu:conglomerate_tin_ore"
+    "gtceu:conglomerate_cassiterite_ore"
+    "gtceu:conglomerate_chalcopyrite_ore"
+    "gtceu:conglomerate_zeolite_ore"
+    "gtceu:conglomerate_realgar_ore"
+    "gtceu:conglomerate_galena_ore"
+    "gtceu:conglomerate_silver_ore"
+    "gtceu:conglomerate_lead_ore"
+    "gtceu:conglomerate_cassiterite_sand_ore"
+    "gtceu:conglomerate_garnet_sand_ore"
+    "gtceu:conglomerate_asbestos_ore"
+    "gtceu:conglomerate_diatomite_ore"
+    "gtceu:conglomerate_red_garnet_ore"
+    "gtceu:conglomerate_yellow_garnet_ore"
+    "gtceu:conglomerate_amethyst_ore"
+    "gtceu:conglomerate_opal_ore"
+    "gtceu:conglomerate_goethite_ore"
+    "gtceu:conglomerate_yellow_limonite_ore"
+    "gtceu:conglomerate_hematite_ore"
+    "gtceu:conglomerate_malachite_ore"
+    "gtceu:conglomerate_soapstone_ore"
+    "gtceu:conglomerate_talc_ore"
+    "gtceu:conglomerate_glauconite_sand_ore"
+    "gtceu:conglomerate_pentlandite_ore"
+    "gtceu:conglomerate_magnetite_ore"
+    "gtceu:conglomerate_vanadium_magnetite_ore"
+    "gtceu:conglomerate_basaltic_mineral_sand_ore"
+    "gtceu:conglomerate_granitic_mineral_sand_ore"
+    "gtceu:conglomerate_fullers_earth_ore"
+    "gtceu:conglomerate_gypsum_ore"
+    "gtceu:conglomerate_garnierite_ore"
+    "gtceu:conglomerate_nickel_ore"
+    "gtceu:conglomerate_cobaltite_ore"
+    "gtceu:conglomerate_rock_salt_ore"
+    "gtceu:conglomerate_salt_ore"
+    "gtceu:conglomerate_lepidolite_ore"
+    "gtceu:conglomerate_spodumene_ore"
+    "gtceu:conglomerate_oilsands_ore"
+    "gtceu:conglomerate_pyrite_ore"
+    "gtceu:conglomerate_lazurite_ore"
+    "gtceu:conglomerate_sodalite_ore"
+    "gtceu:conglomerate_lapis_ore"
+    "gtceu:conglomerate_calcite_ore"
+    "gtceu:conglomerate_grossular_ore"
+    "gtceu:conglomerate_spessartine_ore"
+    "gtceu:conglomerate_pyrolusite_ore"
+    "gtceu:conglomerate_tantalite_ore"
+    "gtceu:conglomerate_kyanite_ore"
+    "gtceu:conglomerate_mica_ore"
+    "gtceu:conglomerate_bauxite_ore"
+    "gtceu:conglomerate_pollucite_ore"
+    "gtceu:conglomerate_bentonite_ore"
+    "gtceu:conglomerate_olivine_ore"
+    "gtceu:conglomerate_redstone_ore"
+    "gtceu:conglomerate_ruby_ore"
+    "gtceu:conglomerate_cinnabar_ore"
+    "gtceu:conglomerate_almandine_ore"
+    "gtceu:conglomerate_pyrope_ore"
+    "gtceu:conglomerate_sapphire_ore"
+    "gtceu:conglomerate_green_sapphire_ore"
+    "gtceu:conglomerate_thorium_ore"
+    "gtceu:conglomerate_chromite_ore"
+  ]
+  result: "tfc:rock/cobble/conglomerate"
+}

```


</details>

<details>
<summary>tfc/collapse/rock_cobble_conglomerate_slab</summary>

```diff
+{
+  type: "tfc:collapse"
+  ingredient: [
+    "tfc:rock/cobble/conglomerate_slab"
+  ]
+  result: "tfc:rock/cobble/conglomerate_slab"
+}

```


</details>

<details>
<summary>tfc/collapse/rock_cobble_dacite</summary>

```diff
+{
+  type: "tfc:collapse"
+  ingredient: [
+    "gtceu:dacite_apatite_ore"
+    "gtceu:dacite_tricalcium_phosphate_ore"
+    "gtceu:dacite_pyrochlore_ore"
+    "gtceu:dacite_tin_ore"
+    "gtceu:dacite_cassiterite_ore"
+    "gtceu:dacite_chalcopyrite_ore"
+    "gtceu:dacite_zeolite_ore"
+    "gtceu:dacite_realgar_ore"
+    "gtceu:dacite_galena_ore"
+    "gtceu:dacite_silver_ore"
+    "gtceu:dacite_lead_ore"
+    "gtceu:dacite_cassiterite_sand_ore"
+    "gtceu:dacite_garnet_sand_ore"
+    "gtceu:dacite_asbestos_ore"
+    "gtceu:dacite_diatomite_ore"
+    "gtceu:dacite_red_garnet_ore"
+    "gtceu:dacite_yellow_garnet_ore"
+    "gtceu:dacite_amethyst_ore"
+    "gtceu:dacite_opal_ore"
+    "gtceu:dacite_goethite_ore"
+    "gtceu:dacite_yellow_limonite_ore"
+    "gtceu:dacite_hematite_ore"
+    "gtceu:dacite_malachite_ore"
+    "gtceu:dacite_soapstone_ore"
+    "gtceu:dacite_talc_ore"
+    "gtceu:dacite_glauconite_sand_ore"
+    "gtceu:dacite_pentlandite_ore"
+    "gtceu:dacite_magnetite_ore"
+    "gtceu:dacite_vanadium_magnetite_ore"
+    "gtceu:dacite_basaltic_mineral_sand_ore"
+    "gtceu:dacite_granitic_mineral_sand_ore"
+    "gtceu:dacite_fullers_earth_ore"
+    "gtceu:dacite_gypsum_ore"
+    "gtceu:dacite_garnierite_ore"
+    "gtceu:dacite_nickel_ore"
+    "gtceu:dacite_cobaltite_ore"
+    "gtceu:dacite_rock_salt_ore"
+    "gtceu:dacite_salt_ore"
+    "gtceu:dacite_lepidolite_ore"
+    "gtceu:dacite_spodumene_ore"
+    "gtceu:dacite_oilsands_ore"
+    "gtceu:dacite_pyrite_ore"
+    "gtceu:dacite_lazurite_ore"
+    "gtceu:dacite_sodalite_ore"
+    "gtceu:dacite_lapis_ore"
+    "gtceu:dacite_calcite_ore"
+    "gtceu:dacite_grossular_ore"
+    "gtceu:dacite_spessartine_ore"
+    "gtceu:dacite_pyrolusite_ore"
+    "gtceu:dacite_tantalite_ore"
+    "gtceu:dacite_kyanite_ore"
+    "gtceu:dacite_mica_ore"
+    "gtceu:dacite_bauxite_ore"
+    "gtceu:dacite_pollucite_ore"
+    "gtceu:dacite_bentonite_ore"
+    "gtceu:dacite_olivine_ore"
+    "gtceu:dacite_redstone_ore"
+    "gtceu:dacite_ruby_ore"
+    "gtceu:dacite_cinnabar_ore"
+    "gtceu:dacite_almandine_ore"
+    "gtceu:dacite_pyrope_ore"
+    "gtceu:dacite_sapphire_ore"
+    "gtceu:dacite_green_sapphire_ore"
+    "gtceu:dacite_thorium_ore"
+    "gtceu:dacite_chromite_ore"
+  ]
+  result: "tfc:rock/cobble/dacite"
+}

```


</details>

<details>
<summary>tfc/collapse/rock_cobble_dacite_slab</summary>

```diff
+{
+  type: "tfc:collapse"
+  ingredient: [
+    "tfc:rock/cobble/dacite_slab"
+  ]
+  result: "tfc:rock/cobble/dacite_slab"
+}

```


</details>

<details>
<summary>tfc/collapse/rock_cobble_diorite</summary>

```diff
+{
+  type: "tfc:collapse"
+  ingredient: [
+    "gtceu:diorite_apatite_ore"
+    "gtceu:diorite_tricalcium_phosphate_ore"
+    "gtceu:diorite_pyrochlore_ore"
+    "gtceu:diorite_tin_ore"
+    "gtceu:diorite_cassiterite_ore"
+    "gtceu:diorite_chalcopyrite_ore"
+    "gtceu:diorite_zeolite_ore"
+    "gtceu:diorite_realgar_ore"
+    "gtceu:diorite_galena_ore"
+    "gtceu:diorite_silver_ore"
+    "gtceu:diorite_lead_ore"
+    "gtceu:diorite_cassiterite_sand_ore"
+    "gtceu:diorite_garnet_sand_ore"
+    "gtceu:diorite_asbestos_ore"
+    "gtceu:diorite_diatomite_ore"
+    "gtceu:diorite_red_garnet_ore"
+    "gtceu:diorite_yellow_garnet_ore"
+    "gtceu:diorite_amethyst_ore"
+    "gtceu:diorite_opal_ore"
+    "gtceu:diorite_goethite_ore"
+    "gtceu:diorite_yellow_limonite_ore"
+    "gtceu:diorite_hematite_ore"
+    "gtceu:diorite_malachite_ore"
+    "gtceu:diorite_soapstone_ore"
+    "gtceu:diorite_talc_ore"
+    "gtceu:diorite_glauconite_sand_ore"
+    "gtceu:diorite_pentlandite_ore"
+    "gtceu:diorite_magnetite_ore"
+    "gtceu:diorite_vanadium_magnetite_ore"
+    "gtceu:diorite_basaltic_mineral_sand_ore"
+    "gtceu:diorite_granitic_mineral_sand_ore"
+    "gtceu:diorite_fullers_earth_ore"
+    "gtceu:diorite_gypsum_ore"
+    "gtceu:diorite_garnierite_ore"
+    "gtceu:diorite_nickel_ore"
+    "gtceu:diorite_cobaltite_ore"
+    "gtceu:diorite_rock_salt_ore"
+    "gtceu:diorite_salt_ore"
+    "gtceu:diorite_lepidolite_ore"
+    "gtceu:diorite_spodumene_ore"
+    "gtceu:diorite_oilsands_ore"
+    "gtceu:diorite_pyrite_ore"
+    "gtceu:diorite_lazurite_ore"
+    "gtceu:diorite_sodalite_ore"
+    "gtceu:diorite_lapis_ore"
+    "gtceu:diorite_calcite_ore"
+    "gtceu:diorite_grossular_ore"
+    "gtceu:diorite_spessartine_ore"
+    "gtceu:diorite_pyrolusite_ore"
+    "gtceu:diorite_tantalite_ore"
+    "gtceu:diorite_kyanite_ore"
+    "gtceu:diorite_mica_ore"
+    "gtceu:diorite_bauxite_ore"
+    "gtceu:diorite_pollucite_ore"
+    "gtceu:diorite_bentonite_ore"
+    "gtceu:diorite_olivine_ore"
+    "gtceu:diorite_redstone_ore"
+    "gtceu:diorite_ruby_ore"
+    "gtceu:diorite_cinnabar_ore"
+    "gtceu:diorite_almandine_ore"
+    "gtceu:diorite_pyrope_ore"
+    "gtceu:diorite_sapphire_ore"
+    "gtceu:diorite_green_sapphire_ore"
+    "gtceu:diorite_thorium_ore"
+    "gtceu:diorite_chromite_ore"
+  ]
+  result: "tfc:rock/cobble/diorite"
+}

```


</details>

<details>
<summary>tfc/collapse/rock_cobble_diorite_slab</summary>

```diff
+{
+  type: "tfc:collapse"
+  ingredient: [
+    "tfc:rock/cobble/diorite_slab"
+  ]
+  result: "tfc:rock/cobble/diorite_slab"
+}

```


</details>

<details>
<summary>tfc/collapse/rock_cobble_dolomite</summary>

```diff
+{
+  type: "tfc:collapse"
+  ingredient: [
+    "gtceu:dolomite_apatite_ore"
+    "gtceu:dolomite_tricalcium_phosphate_ore"
+    "gtceu:dolomite_pyrochlore_ore"
+    "gtceu:dolomite_tin_ore"
+    "gtceu:dolomite_cassiterite_ore"
+    "gtceu:dolomite_chalcopyrite_ore"
+    "gtceu:dolomite_zeolite_ore"
+    "gtceu:dolomite_realgar_ore"
+    "gtceu:dolomite_galena_ore"
+    "gtceu:dolomite_silver_ore"
+    "gtceu:dolomite_lead_ore"
+    "gtceu:dolomite_cassiterite_sand_ore"
+    "gtceu:dolomite_garnet_sand_ore"
+    "gtceu:dolomite_asbestos_ore"
+    "gtceu:dolomite_diatomite_ore"
+    "gtceu:dolomite_red_garnet_ore"
+    "gtceu:dolomite_yellow_garnet_ore"
+    "gtceu:dolomite_amethyst_ore"
+    "gtceu:dolomite_opal_ore"
+    "gtceu:dolomite_goethite_ore"
+    "gtceu:dolomite_yellow_limonite_ore"
+    "gtceu:dolomite_hematite_ore"
+    "gtceu:dolomite_malachite_ore"
+    "gtceu:dolomite_soapstone_ore"
+    "gtceu:dolomite_talc_ore"
+    "gtceu:dolomite_glauconite_sand_ore"
+    "gtceu:dolomite_pentlandite_ore"
+    "gtceu:dolomite_magnetite_ore"
+    "gtceu:dolomite_vanadium_magnetite_ore"
+    "gtceu:dolomite_basaltic_mineral_sand_ore"
+    "gtceu:dolomite_granitic_mineral_sand_ore"
+    "gtceu:dolomite_fullers_earth_ore"
+    "gtceu:dolomite_gypsum_ore"
+    "gtceu:dolomite_garnierite_ore"
+    "gtceu:dolomite_nickel_ore"
+    "gtceu:dolomite_cobaltite_ore"
+    "gtceu:dolomite_rock_salt_ore"
+    "gtceu:dolomite_salt_ore"
+    "gtceu:dolomite_lepidolite_ore"
+    "gtceu:dolomite_spodumene_ore"
+    "gtceu:dolomite_oilsands_ore"
+    "gtceu:dolomite_pyrite_ore"
+    "gtceu:dolomite_lazurite_ore"
+    "gtceu:dolomite_sodalite_ore"
+    "gtceu:dolomite_lapis_ore"
+    "gtceu:dolomite_calcite_ore"
+    "gtceu:dolomite_grossular_ore"
+    "gtceu:dolomite_spessartine_ore"
+    "gtceu:dolomite_pyrolusite_ore"
+    "gtceu:dolomite_tantalite_ore"
+    "gtceu:dolomite_kyanite_ore"
+    "gtceu:dolomite_mica_ore"
+    "gtceu:dolomite_bauxite_ore"
+    "gtceu:dolomite_pollucite_ore"
+    "gtceu:dolomite_bentonite_ore"
+    "gtceu:dolomite_olivine_ore"
+    "gtceu:dolomite_redstone_ore"
+    "gtceu:dolomite_ruby_ore"
+    "gtceu:dolomite_cinnabar_ore"
+    "gtceu:dolomite_almandine_ore"
+    "gtceu:dolomite_pyrope_ore"
+    "gtceu:dolomite_sapphire_ore"
+    "gtceu:dolomite_green_sapphire_ore"
+    "gtceu:dolomite_thorium_ore"
+    "gtceu:dolomite_chromite_ore"
+  ]
+  result: "tfc:rock/cobble/dolomite"
+}

```


</details>

<details>
<summary>tfc/collapse/rock_cobble_dolomite_slab</summary>

```diff
+{
+  type: "tfc:collapse"
+  ingredient: [
+    "tfc:rock/cobble/dolomite_slab"
+  ]
+  result: "tfc:rock/cobble/dolomite_slab"
+}

```


</details>

<details>
<summary>tfc/collapse/rock_cobble_gabbro</summary>

```diff
+{
+  type: "tfc:collapse"
+  ingredient: [
+    "gtceu:gabbro_apatite_ore"
+    "gtceu:gabbro_tricalcium_phosphate_ore"
+    "gtceu:gabbro_pyrochlore_ore"
+    "gtceu:gabbro_tin_ore"
+    "gtceu:gabbro_cassiterite_ore"
+    "gtceu:gabbro_chalcopyrite_ore"
+    "gtceu:gabbro_zeolite_ore"
+    "gtceu:gabbro_realgar_ore"
+    "gtceu:gabbro_galena_ore"
+    "gtceu:gabbro_silver_ore"
+    "gtceu:gabbro_lead_ore"
+    "gtceu:gabbro_cassiterite_sand_ore"
+    "gtceu:gabbro_garnet_sand_ore"
+    "gtceu:gabbro_asbestos_ore"
+    "gtceu:gabbro_diatomite_ore"
+    "gtceu:gabbro_red_garnet_ore"
+    "gtceu:gabbro_yellow_garnet_ore"
+    "gtceu:gabbro_amethyst_ore"
+    "gtceu:gabbro_opal_ore"
+    "gtceu:gabbro_goethite_ore"
+    "gtceu:gabbro_yellow_limonite_ore"
+    "gtceu:gabbro_hematite_ore"
+    "gtceu:gabbro_malachite_ore"
+    "gtceu:gabbro_soapstone_ore"
+    "gtceu:gabbro_talc_ore"
+    "gtceu:gabbro_glauconite_sand_ore"
+    "gtceu:gabbro_pentlandite_ore"
+    "gtceu:gabbro_magnetite_ore"
+    "gtceu:gabbro_vanadium_magnetite_ore"
+    "gtceu:gabbro_basaltic_mineral_sand_ore"
+    "gtceu:gabbro_granitic_mineral_sand_ore"
+    "gtceu:gabbro_fullers_earth_ore"
+    "gtceu:gabbro_gypsum_ore"
+    "gtceu:gabbro_garnierite_ore"
+    "gtceu:gabbro_nickel_ore"
+    "gtceu:gabbro_cobaltite_ore"
+    "gtceu:gabbro_rock_salt_ore"
+    "gtceu:gabbro_salt_ore"
+    "gtceu:gabbro_lepidolite_ore"
+    "gtceu:gabbro_spodumene_ore"
+    "gtceu:gabbro_oilsands_ore"
+    "gtceu:gabbro_pyrite_ore"
+    "gtceu:gabbro_lazurite_ore"
+    "gtceu:gabbro_sodalite_ore"
+    "gtceu:gabbro_lapis_ore"
+    "gtceu:gabbro_calcite_ore"
+    "gtceu:gabbro_grossular_ore"
+    "gtceu:gabbro_spessartine_ore"
+    "gtceu:gabbro_pyrolusite_ore"
+    "gtceu:gabbro_tantalite_ore"
+    "gtceu:gabbro_kyanite_ore"
+    "gtceu:gabbro_mica_ore"
+    "gtceu:gabbro_bauxite_ore"
+    "gtceu:gabbro_pollucite_ore"
+    "gtceu:gabbro_bentonite_ore"
+    "gtceu:gabbro_olivine_ore"
+    "gtceu:gabbro_redstone_ore"
+    "gtceu:gabbro_ruby_ore"
+    "gtceu:gabbro_cinnabar_ore"
+    "gtceu:gabbro_almandine_ore"
+    "gtceu:gabbro_pyrope_ore"
+    "gtceu:gabbro_sapphire_ore"
+    "gtceu:gabbro_green_sapphire_ore"
+    "gtceu:gabbro_thorium_ore"
+    "gtceu:gabbro_chromite_ore"
+  ]
+  result: "tfc:rock/cobble/gabbro"
+}

```


</details>

<details>
<summary>tfc/collapse/rock_cobble_gabbro_slab</summary>

```diff
+{
+  type: "tfc:collapse"
+  ingredient: [
+    "tfc:rock/cobble/gabbro_slab"
+  ]
+  result: "tfc:rock/cobble/gabbro_slab"
+}

```


</details>

<details>
<summary>tfc/collapse/rock_cobble_gneiss</summary>

```diff
+{
+  type: "tfc:collapse"
+  ingredient: [
+    "gtceu:gneiss_apatite_ore"
+    "gtceu:gneiss_tricalcium_phosphate_ore"
+    "gtceu:gneiss_pyrochlore_ore"
+    "gtceu:gneiss_tin_ore"
+    "gtceu:gneiss_cassiterite_ore"
+    "gtceu:gneiss_chalcopyrite_ore"
+    "gtceu:gneiss_zeolite_ore"
+    "gtceu:gneiss_realgar_ore"
+    "gtceu:gneiss_galena_ore"
+    "gtceu:gneiss_silver_ore"
+    "gtceu:gneiss_lead_ore"
+    "gtceu:gneiss_cassiterite_sand_ore"
+    "gtceu:gneiss_garnet_sand_ore"
+    "gtceu:gneiss_asbestos_ore"
+    "gtceu:gneiss_diatomite_ore"
+    "gtceu:gneiss_red_garnet_ore"
+    "gtceu:gneiss_yellow_garnet_ore"
+    "gtceu:gneiss_amethyst_ore"
+    "gtceu:gneiss_opal_ore"
+    "gtceu:gneiss_goethite_ore"
+    "gtceu:gneiss_yellow_limonite_ore"
+    "gtceu:gneiss_hematite_ore"
+    "gtceu:gneiss_malachite_ore"
+    "gtceu:gneiss_soapstone_ore"
+    "gtceu:gneiss_talc_ore"
+    "gtceu:gneiss_glauconite_sand_ore"
+    "gtceu:gneiss_pentlandite_ore"
+    "gtceu:gneiss_magnetite_ore"
+    "gtceu:gneiss_vanadium_magnetite_ore"
+    "gtceu:gneiss_basaltic_mineral_sand_ore"
+    "gtceu:gneiss_granitic_mineral_sand_ore"
+    "gtceu:gneiss_fullers_earth_ore"
+    "gtceu:gneiss_gypsum_ore"
+    "gtceu:gneiss_garnierite_ore"
+    "gtceu:gneiss_nickel_ore"
+    "gtceu:gneiss_cobaltite_ore"
+    "gtceu:gneiss_rock_salt_ore"
+    "gtceu:gneiss_salt_ore"
+    "gtceu:gneiss_lepidolite_ore"
+    "gtceu:gneiss_spodumene_ore"
+    "gtceu:gneiss_oilsands_ore"
+    "gtceu:gneiss_pyrite_ore"
+    "gtceu:gneiss_lazurite_ore"
+    "gtceu:gneiss_sodalite_ore"
+    "gtceu:gneiss_lapis_ore"
+    "gtceu:gneiss_calcite_ore"
+    "gtceu:gneiss_grossular_ore"
+    "gtceu:gneiss_spessartine_ore"
+    "gtceu:gneiss_pyrolusite_ore"
+    "gtceu:gneiss_tantalite_ore"
+    "gtceu:gneiss_kyanite_ore"
+    "gtceu:gneiss_mica_ore"
+    "gtceu:gneiss_bauxite_ore"
+    "gtceu:gneiss_pollucite_ore"
+    "gtceu:gneiss_bentonite_ore"
+    "gtceu:gneiss_olivine_ore"
+    "gtceu:gneiss_redstone_ore"
+    "gtceu:gneiss_ruby_ore"
+    "gtceu:gneiss_cinnabar_ore"
+    "gtceu:gneiss_almandine_ore"
+    "gtceu:gneiss_pyrope_ore"
+    "gtceu:gneiss_sapphire_ore"
+    "gtceu:gneiss_green_sapphire_ore"
+    "gtceu:gneiss_thorium_ore"
+    "gtceu:gneiss_chromite_ore"
+  ]
+  result: "tfc:rock/cobble/gneiss"
+}

```


</details>

<details>
<summary>tfc/collapse/rock_cobble_gneiss_slab</summary>

```diff
+{
+  type: "tfc:collapse"
+  ingredient: [
+    "tfc:rock/cobble/gneiss_slab"
+  ]
+  result: "tfc:rock/cobble/gneiss_slab"
+}

```


</details>

<details>
<summary>tfc/collapse/rock_cobble_granite</summary>

```diff
+{
+  type: "tfc:collapse"
+  ingredient: [
+    "gtceu:granite_apatite_ore"
+    "gtceu:granite_tricalcium_phosphate_ore"
+    "gtceu:granite_pyrochlore_ore"
+    "gtceu:granite_tin_ore"
+    "gtceu:granite_cassiterite_ore"
+    "gtceu:granite_chalcopyrite_ore"
+    "gtceu:granite_zeolite_ore"
+    "gtceu:granite_realgar_ore"
+    "gtceu:granite_galena_ore"
+    "gtceu:granite_silver_ore"
+    "gtceu:granite_lead_ore"
+    "gtceu:granite_cassiterite_sand_ore"
+    "gtceu:granite_garnet_sand_ore"
+    "gtceu:granite_asbestos_ore"
+    "gtceu:granite_diatomite_ore"
+    "gtceu:granite_red_garnet_ore"
+    "gtceu:granite_yellow_garnet_ore"
+    "gtceu:granite_amethyst_ore"
+    "gtceu:granite_opal_ore"
+    "gtceu:granite_goethite_ore"
+    "gtceu:granite_yellow_limonite_ore"
+    "gtceu:granite_hematite_ore"
+    "gtceu:granite_malachite_ore"
+    "gtceu:granite_soapstone_ore"
+    "gtceu:granite_talc_ore"
+    "gtceu:granite_glauconite_sand_ore"
+    "gtceu:granite_pentlandite_ore"
+    "gtceu:granite_magnetite_ore"
+    "gtceu:granite_vanadium_magnetite_ore"
+    "gtceu:granite_basaltic_mineral_sand_ore"
+    "gtceu:granite_granitic_mineral_sand_ore"
+    "gtceu:granite_fullers_earth_ore"
+    "gtceu:granite_gypsum_ore"
+    "gtceu:granite_garnierite_ore"
+    "gtceu:granite_nickel_ore"
+    "gtceu:granite_cobaltite_ore"
+    "gtceu:granite_rock_salt_ore"
+    "gtceu:granite_salt_ore"
+    "gtceu:granite_lepidolite_ore"
+    "gtceu:granite_spodumene_ore"
+    "gtceu:granite_oilsands_ore"
+    "gtceu:granite_pyrite_ore"
+    "gtceu:granite_lazurite_ore"
+    "gtceu:granite_sodalite_ore"
+    "gtceu:granite_lapis_ore"
+    "gtceu:granite_calcite_ore"
+    "gtceu:granite_grossular_ore"
+    "gtceu:granite_spessartine_ore"
+    "gtceu:granite_pyrolusite_ore"
+    "gtceu:granite_tantalite_ore"
+    "gtceu:granite_kyanite_ore"
+    "gtceu:granite_mica_ore"
+    "gtceu:granite_bauxite_ore"
+    "gtceu:granite_pollucite_ore"
+    "gtceu:granite_bentonite_ore"
+    "gtceu:granite_olivine_ore"
+    "gtceu:granite_redstone_ore"
+    "gtceu:granite_ruby_ore"
+    "gtceu:granite_cinnabar_ore"
+    "gtceu:granite_almandine_ore"
+    "gtceu:granite_pyrope_ore"
+    "gtceu:granite_sapphire_ore"
+    "gtceu:granite_green_sapphire_ore"
+    "gtceu:granite_thorium_ore"
+    "gtceu:granite_chromite_ore"
+  ]
+  result: "tfc:rock/cobble/granite"
+}

```


</details>

<details>
<summary>tfc/collapse/rock_cobble_granite_slab</summary>

```diff
+{
+  type: "tfc:collapse"
+  ingredient: [
+    "tfc:rock/cobble/granite_slab"
+  ]
+  result: "tfc:rock/cobble/granite_slab"
+}

```


</details>

<details>
<summary>tfc/collapse/rock_cobble_limestone</summary>

```diff
+{
+  type: "tfc:collapse"
+  ingredient: [
+    "gtceu:limestone_apatite_ore"
+    "gtceu:limestone_tricalcium_phosphate_ore"
+    "gtceu:limestone_pyrochlore_ore"
+    "gtceu:limestone_tin_ore"
+    "gtceu:limestone_cassiterite_ore"
+    "gtceu:limestone_chalcopyrite_ore"
+    "gtceu:limestone_zeolite_ore"
+    "gtceu:limestone_realgar_ore"
+    "gtceu:limestone_galena_ore"
+    "gtceu:limestone_silver_ore"
+    "gtceu:limestone_lead_ore"
+    "gtceu:limestone_cassiterite_sand_ore"
+    "gtceu:limestone_garnet_sand_ore"
+    "gtceu:limestone_asbestos_ore"
+    "gtceu:limestone_diatomite_ore"
+    "gtceu:limestone_red_garnet_ore"
+    "gtceu:limestone_yellow_garnet_ore"
+    "gtceu:limestone_amethyst_ore"
+    "gtceu:limestone_opal_ore"
+    "gtceu:limestone_goethite_ore"
+    "gtceu:limestone_yellow_limonite_ore"
+    "gtceu:limestone_hematite_ore"
+    "gtceu:limestone_malachite_ore"
+    "gtceu:limestone_soapstone_ore"
+    "gtceu:limestone_talc_ore"
+    "gtceu:limestone_glauconite_sand_ore"
+    "gtceu:limestone_pentlandite_ore"
+    "gtceu:limestone_magnetite_ore"
+    "gtceu:limestone_vanadium_magnetite_ore"
+    "gtceu:limestone_basaltic_mineral_sand_ore"
+    "gtceu:limestone_granitic_mineral_sand_ore"
+    "gtceu:limestone_fullers_earth_ore"
+    "gtceu:limestone_gypsum_ore"
+    "gtceu:limestone_garnierite_ore"
+    "gtceu:limestone_nickel_ore"
+    "gtceu:limestone_cobaltite_ore"
+    "gtceu:limestone_rock_salt_ore"
+    "gtceu:limestone_salt_ore"
+    "gtceu:limestone_lepidolite_ore"
+    "gtceu:limestone_spodumene_ore"
+    "gtceu:limestone_oilsands_ore"
+    "gtceu:limestone_pyrite_ore"
+    "gtceu:limestone_lazurite_ore"
+    "gtceu:limestone_sodalite_ore"
+    "gtceu:limestone_lapis_ore"
+    "gtceu:limestone_calcite_ore"
+    "gtceu:limestone_grossular_ore"
+    "gtceu:limestone_spessartine_ore"
+    "gtceu:limestone_pyrolusite_ore"
+    "gtceu:limestone_tantalite_ore"
+    "gtceu:limestone_kyanite_ore"
+    "gtceu:limestone_mica_ore"
+    "gtceu:limestone_bauxite_ore"
+    "gtceu:limestone_pollucite_ore"
+    "gtceu:limestone_bentonite_ore"
+    "gtceu:limestone_olivine_ore"
+    "gtceu:limestone_redstone_ore"
+    "gtceu:limestone_ruby_ore"
+    "gtceu:limestone_cinnabar_ore"
+    "gtceu:limestone_almandine_ore"
+    "gtceu:limestone_pyrope_ore"
+    "gtceu:limestone_sapphire_ore"
+    "gtceu:limestone_green_sapphire_ore"
+    "gtceu:limestone_thorium_ore"
+    "gtceu:limestone_chromite_ore"
+  ]
+  result: "tfc:rock/cobble/limestone"
+}

```


</details>

<details>
<summary>tfc/collapse/rock_cobble_limestone_slab</summary>

```diff
+{
+  type: "tfc:collapse"
+  ingredient: [
+    "tfc:rock/cobble/limestone_slab"
+  ]
+  result: "tfc:rock/cobble/limestone_slab"
+}

```


</details>

<details>
<summary>tfc/collapse/rock_cobble_marble</summary>

```diff
+{
+  type: "tfc:collapse"
+  ingredient: [
+    "gtceu:marble_apatite_ore"
+    "gtceu:marble_tricalcium_phosphate_ore"
+    "gtceu:marble_pyrochlore_ore"
+    "gtceu:marble_tin_ore"
+    "gtceu:marble_cassiterite_ore"
+    "gtceu:marble_chalcopyrite_ore"
+    "gtceu:marble_zeolite_ore"
+    "gtceu:marble_realgar_ore"
+    "gtceu:marble_galena_ore"
+    "gtceu:marble_silver_ore"
+    "gtceu:marble_lead_ore"
+    "gtceu:marble_cassiterite_sand_ore"
+    "gtceu:marble_garnet_sand_ore"
+    "gtceu:marble_asbestos_ore"
+    "gtceu:marble_diatomite_ore"
+    "gtceu:marble_red_garnet_ore"
+    "gtceu:marble_yellow_garnet_ore"
+    "gtceu:marble_amethyst_ore"
+    "gtceu:marble_opal_ore"
+    "gtceu:marble_goethite_ore"
+    "gtceu:marble_yellow_limonite_ore"
+    "gtceu:marble_hematite_ore"
+    "gtceu:marble_malachite_ore"
+    "gtceu:marble_soapstone_ore"
+    "gtceu:marble_talc_ore"
+    "gtceu:marble_glauconite_sand_ore"
+    "gtceu:marble_pentlandite_ore"
+    "gtceu:marble_magnetite_ore"
+    "gtceu:marble_vanadium_magnetite_ore"
+    "gtceu:marble_basaltic_mineral_sand_ore"
+    "gtceu:marble_granitic_mineral_sand_ore"
+    "gtceu:marble_fullers_earth_ore"
+    "gtceu:marble_gypsum_ore"
+    "gtceu:marble_garnierite_ore"
+    "gtceu:marble_nickel_ore"
+    "gtceu:marble_cobaltite_ore"
+    "gtceu:marble_rock_salt_ore"
+    "gtceu:marble_salt_ore"
+    "gtceu:marble_lepidolite_ore"
+    "gtceu:marble_spodumene_ore"
+    "gtceu:marble_oilsands_ore"
+    "gtceu:marble_pyrite_ore"
+    "gtceu:marble_lazurite_ore"
+    "gtceu:marble_sodalite_ore"
+    "gtceu:marble_lapis_ore"
+    "gtceu:marble_calcite_ore"
+    "gtceu:marble_grossular_ore"
+    "gtceu:marble_spessartine_ore"
+    "gtceu:marble_pyrolusite_ore"
+    "gtceu:marble_tantalite_ore"
+    "gtceu:marble_kyanite_ore"
+    "gtceu:marble_mica_ore"
+    "gtceu:marble_bauxite_ore"
+    "gtceu:marble_pollucite_ore"
+    "gtceu:marble_bentonite_ore"
+    "gtceu:marble_olivine_ore"
+    "gtceu:marble_redstone_ore"
+    "gtceu:marble_ruby_ore"
+    "gtceu:marble_cinnabar_ore"
+    "gtceu:marble_almandine_ore"
+    "gtceu:marble_pyrope_ore"
+    "gtceu:marble_sapphire_ore"
+    "gtceu:marble_green_sapphire_ore"
+    "gtceu:marble_thorium_ore"
+    "gtceu:marble_chromite_ore"
+  ]
+  result: "tfc:rock/cobble/marble"
+}

```


</details>

<details>
<summary>tfc/collapse/rock_cobble_marble_slab</summary>

```diff
+{
+  type: "tfc:collapse"
+  ingredient: [
+    "tfc:rock/cobble/marble_slab"
+  ]
+  result: "tfc:rock/cobble/marble_slab"
+}

```


</details>

<details>
<summary>tfc/collapse/rock_cobble_phyllite</summary>

```diff
+{
+  type: "tfc:collapse"
+  ingredient: [
+    "gtceu:phyllite_apatite_ore"
+    "gtceu:phyllite_tricalcium_phosphate_ore"
+    "gtceu:phyllite_pyrochlore_ore"
+    "gtceu:phyllite_tin_ore"
+    "gtceu:phyllite_cassiterite_ore"
+    "gtceu:phyllite_chalcopyrite_ore"
+    "gtceu:phyllite_zeolite_ore"
+    "gtceu:phyllite_realgar_ore"
+    "gtceu:phyllite_galena_ore"
+    "gtceu:phyllite_silver_ore"
+    "gtceu:phyllite_lead_ore"
+    "gtceu:phyllite_cassiterite_sand_ore"
+    "gtceu:phyllite_garnet_sand_ore"
+    "gtceu:phyllite_asbestos_ore"
+    "gtceu:phyllite_diatomite_ore"
+    "gtceu:phyllite_red_garnet_ore"
+    "gtceu:phyllite_yellow_garnet_ore"
+    "gtceu:phyllite_amethyst_ore"
+    "gtceu:phyllite_opal_ore"
+    "gtceu:phyllite_goethite_ore"
+    "gtceu:phyllite_yellow_limonite_ore"
+    "gtceu:phyllite_hematite_ore"
+    "gtceu:phyllite_malachite_ore"
+    "gtceu:phyllite_soapstone_ore"
+    "gtceu:phyllite_talc_ore"
+    "gtceu:phyllite_glauconite_sand_ore"
+    "gtceu:phyllite_pentlandite_ore"
+    "gtceu:phyllite_magnetite_ore"
+    "gtceu:phyllite_vanadium_magnetite_ore"
+    "gtceu:phyllite_basaltic_mineral_sand_ore"
+    "gtceu:phyllite_granitic_mineral_sand_ore"
+    "gtceu:phyllite_fullers_earth_ore"
+    "gtceu:phyllite_gypsum_ore"
+    "gtceu:phyllite_garnierite_ore"
+    "gtceu:phyllite_nickel_ore"
+    "gtceu:phyllite_cobaltite_ore"
+    "gtceu:phyllite_rock_salt_ore"
+    "gtceu:phyllite_salt_ore"
+    "gtceu:phyllite_lepidolite_ore"
+    "gtceu:phyllite_spodumene_ore"
+    "gtceu:phyllite_oilsands_ore"
+    "gtceu:phyllite_pyrite_ore"
+    "gtceu:phyllite_lazurite_ore"
+    "gtceu:phyllite_sodalite_ore"
+    "gtceu:phyllite_lapis_ore"
+    "gtceu:phyllite_calcite_ore"
+    "gtceu:phyllite_grossular_ore"
+    "gtceu:phyllite_spessartine_ore"
+    "gtceu:phyllite_pyrolusite_ore"
+    "gtceu:phyllite_tantalite_ore"
+    "gtceu:phyllite_kyanite_ore"
+    "gtceu:phyllite_mica_ore"
+    "gtceu:phyllite_bauxite_ore"
+    "gtceu:phyllite_pollucite_ore"
+    "gtceu:phyllite_bentonite_ore"
+    "gtceu:phyllite_olivine_ore"
+    "gtceu:phyllite_redstone_ore"
+    "gtceu:phyllite_ruby_ore"
+    "gtceu:phyllite_cinnabar_ore"
+    "gtceu:phyllite_almandine_ore"
+    "gtceu:phyllite_pyrope_ore"
+    "gtceu:phyllite_sapphire_ore"
+    "gtceu:phyllite_green_sapphire_ore"
+    "gtceu:phyllite_thorium_ore"
+    "gtceu:phyllite_chromite_ore"
+  ]
+  result: "tfc:rock/cobble/phyllite"
+}

```


</details>

<details>
<summary>tfc/collapse/rock_cobble_phyllite_slab</summary>

```diff
+{
+  type: "tfc:collapse"
+  ingredient: [
+    "tfc:rock/cobble/phyllite_slab"
+  ]
+  result: "tfc:rock/cobble/phyllite_slab"
+}

```


</details>

<details>
<summary>tfc/collapse/rock_cobble_quartzite</summary>

```diff
+{
+  type: "tfc:collapse"
+  ingredient: [
+    "gtceu:quartzite_apatite_ore"
+    "gtceu:quartzite_tricalcium_phosphate_ore"
+    "gtceu:quartzite_pyrochlore_ore"
+    "gtceu:quartzite_tin_ore"
+    "gtceu:quartzite_cassiterite_ore"
+    "gtceu:quartzite_chalcopyrite_ore"
+    "gtceu:quartzite_zeolite_ore"
+    "gtceu:quartzite_realgar_ore"
+    "gtceu:quartzite_galena_ore"
+    "gtceu:quartzite_silver_ore"
+    "gtceu:quartzite_lead_ore"
+    "gtceu:quartzite_cassiterite_sand_ore"
+    "gtceu:quartzite_garnet_sand_ore"
+    "gtceu:quartzite_asbestos_ore"
+    "gtceu:quartzite_diatomite_ore"
+    "gtceu:quartzite_red_garnet_ore"
+    "gtceu:quartzite_yellow_garnet_ore"
+    "gtceu:quartzite_amethyst_ore"
+    "gtceu:quartzite_opal_ore"
+    "gtceu:quartzite_goethite_ore"
+    "gtceu:quartzite_yellow_limonite_ore"
+    "gtceu:quartzite_hematite_ore"
+    "gtceu:quartzite_malachite_ore"
+    "gtceu:quartzite_soapstone_ore"
+    "gtceu:quartzite_talc_ore"
+    "gtceu:quartzite_glauconite_sand_ore"
+    "gtceu:quartzite_pentlandite_ore"
+    "gtceu:quartzite_magnetite_ore"
+    "gtceu:quartzite_vanadium_magnetite_ore"
+    "gtceu:quartzite_basaltic_mineral_sand_ore"
+    "gtceu:quartzite_granitic_mineral_sand_ore"
+    "gtceu:quartzite_fullers_earth_ore"
+    "gtceu:quartzite_gypsum_ore"
+    "gtceu:quartzite_garnierite_ore"
+    "gtceu:quartzite_nickel_ore"
+    "gtceu:quartzite_cobaltite_ore"
+    "gtceu:quartzite_rock_salt_ore"
+    "gtceu:quartzite_salt_ore"
+    "gtceu:quartzite_lepidolite_ore"
+    "gtceu:quartzite_spodumene_ore"
+    "gtceu:quartzite_oilsands_ore"
+    "gtceu:quartzite_pyrite_ore"
+    "gtceu:quartzite_lazurite_ore"
+    "gtceu:quartzite_sodalite_ore"
+    "gtceu:quartzite_lapis_ore"
+    "gtceu:quartzite_calcite_ore"
+    "gtceu:quartzite_grossular_ore"
+    "gtceu:quartzite_spessartine_ore"
+    "gtceu:quartzite_pyrolusite_ore"
+    "gtceu:quartzite_tantalite_ore"
+    "gtceu:quartzite_kyanite_ore"
+    "gtceu:quartzite_mica_ore"
+    "gtceu:quartzite_bauxite_ore"
+    "gtceu:quartzite_pollucite_ore"
+    "gtceu:quartzite_bentonite_ore"
+    "gtceu:quartzite_olivine_ore"
+    "gtceu:quartzite_redstone_ore"
+    "gtceu:quartzite_ruby_ore"
+    "gtceu:quartzite_cinnabar_ore"
+    "gtceu:quartzite_almandine_ore"
+    "gtceu:quartzite_pyrope_ore"
+    "gtceu:quartzite_sapphire_ore"
+    "gtceu:quartzite_green_sapphire_ore"
+    "gtceu:quartzite_thorium_ore"
+    "gtceu:quartzite_chromite_ore"
+  ]
+  result: "tfc:rock/cobble/quartzite"
+}

```


</details>

<details>
<summary>tfc/collapse/rock_cobble_quartzite_slab</summary>

```diff
+{
+  type: "tfc:collapse"
+  ingredient: [
+    "tfc:rock/cobble/quartzite_slab"
+  ]
+  result: "tfc:rock/cobble/quartzite_slab"
+}

```


</details>

<details>
<summary>tfc/collapse/rock_cobble_rhyolite</summary>

```diff
+{
+  type: "tfc:collapse"
+  ingredient: [
+    "gtceu:rhyolite_apatite_ore"
+    "gtceu:rhyolite_tricalcium_phosphate_ore"
+    "gtceu:rhyolite_pyrochlore_ore"
+    "gtceu:rhyolite_tin_ore"
+    "gtceu:rhyolite_cassiterite_ore"
+    "gtceu:rhyolite_chalcopyrite_ore"
+    "gtceu:rhyolite_zeolite_ore"
+    "gtceu:rhyolite_realgar_ore"
+    "gtceu:rhyolite_galena_ore"
+    "gtceu:rhyolite_silver_ore"
+    "gtceu:rhyolite_lead_ore"
+    "gtceu:rhyolite_cassiterite_sand_ore"
+    "gtceu:rhyolite_garnet_sand_ore"
+    "gtceu:rhyolite_asbestos_ore"
+    "gtceu:rhyolite_diatomite_ore"
+    "gtceu:rhyolite_red_garnet_ore"
+    "gtceu:rhyolite_yellow_garnet_ore"
+    "gtceu:rhyolite_amethyst_ore"
+    "gtceu:rhyolite_opal_ore"
+    "gtceu:rhyolite_goethite_ore"
+    "gtceu:rhyolite_yellow_limonite_ore"
+    "gtceu:rhyolite_hematite_ore"
+    "gtceu:rhyolite_malachite_ore"
+    "gtceu:rhyolite_soapstone_ore"
+    "gtceu:rhyolite_talc_ore"
+    "gtceu:rhyolite_glauconite_sand_ore"
+    "gtceu:rhyolite_pentlandite_ore"
+    "gtceu:rhyolite_magnetite_ore"
+    "gtceu:rhyolite_vanadium_magnetite_ore"
+    "gtceu:rhyolite_basaltic_mineral_sand_ore"
+    "gtceu:rhyolite_granitic_mineral_sand_ore"
+    "gtceu:rhyolite_fullers_earth_ore"
+    "gtceu:rhyolite_gypsum_ore"
+    "gtceu:rhyolite_garnierite_ore"
+    "gtceu:rhyolite_nickel_ore"
+    "gtceu:rhyolite_cobaltite_ore"
+    "gtceu:rhyolite_rock_salt_ore"
+    "gtceu:rhyolite_salt_ore"
+    "gtceu:rhyolite_lepidolite_ore"
+    "gtceu:rhyolite_spodumene_ore"
+    "gtceu:rhyolite_oilsands_ore"
+    "gtceu:rhyolite_pyrite_ore"
+    "gtceu:rhyolite_lazurite_ore"
+    "gtceu:rhyolite_sodalite_ore"
+    "gtceu:rhyolite_lapis_ore"
+    "gtceu:rhyolite_calcite_ore"
+    "gtceu:rhyolite_grossular_ore"
+    "gtceu:rhyolite_spessartine_ore"
+    "gtceu:rhyolite_pyrolusite_ore"
+    "gtceu:rhyolite_tantalite_ore"
+    "gtceu:rhyolite_kyanite_ore"
+    "gtceu:rhyolite_mica_ore"
+    "gtceu:rhyolite_bauxite_ore"
+    "gtceu:rhyolite_pollucite_ore"
+    "gtceu:rhyolite_bentonite_ore"
+    "gtceu:rhyolite_olivine_ore"
+    "gtceu:rhyolite_redstone_ore"
+    "gtceu:rhyolite_ruby_ore"
+    "gtceu:rhyolite_cinnabar_ore"
+    "gtceu:rhyolite_almandine_ore"
+    "gtceu:rhyolite_pyrope_ore"
+    "gtceu:rhyolite_sapphire_ore"
+    "gtceu:rhyolite_green_sapphire_ore"
+    "gtceu:rhyolite_thorium_ore"
+    "gtceu:rhyolite_chromite_ore"
+  ]
+  result: "tfc:rock/cobble/rhyolite"
+}

```


</details>

<details>
<summary>tfc/collapse/rock_cobble_rhyolite_slab</summary>

```diff
+{
+  type: "tfc:collapse"
+  ingredient: [
+    "tfc:rock/cobble/rhyolite_slab"
+  ]
+  result: "tfc:rock/cobble/rhyolite_slab"
+}

```


</details>

<details>
<summary>tfc/collapse/rock_cobble_schist</summary>

```diff
+{
+  type: "tfc:collapse"
+  ingredient: [
+    "gtceu:schist_apatite_ore"
+    "gtceu:schist_tricalcium_phosphate_ore"
+    "gtceu:schist_pyrochlore_ore"
+    "gtceu:schist_tin_ore"
+    "gtceu:schist_cassiterite_ore"
+    "gtceu:schist_chalcopyrite_ore"
+    "gtceu:schist_zeolite_ore"
+    "gtceu:schist_realgar_ore"
+    "gtceu:schist_galena_ore"
+    "gtceu:schist_silver_ore"
+    "gtceu:schist_lead_ore"
+    "gtceu:schist_cassiterite_sand_ore"
+    "gtceu:schist_garnet_sand_ore"
+    "gtceu:schist_asbestos_ore"
+    "gtceu:schist_diatomite_ore"
+    "gtceu:schist_red_garnet_ore"
+    "gtceu:schist_yellow_garnet_ore"
+    "gtceu:schist_amethyst_ore"
+    "gtceu:schist_opal_ore"
+    "gtceu:schist_goethite_ore"
+    "gtceu:schist_yellow_limonite_ore"
+    "gtceu:schist_hematite_ore"
+    "gtceu:schist_malachite_ore"
+    "gtceu:schist_soapstone_ore"
+    "gtceu:schist_talc_ore"
+    "gtceu:schist_glauconite_sand_ore"
+    "gtceu:schist_pentlandite_ore"
+    "gtceu:schist_magnetite_ore"
+    "gtceu:schist_vanadium_magnetite_ore"
+    "gtceu:schist_basaltic_mineral_sand_ore"
+    "gtceu:schist_granitic_mineral_sand_ore"
+    "gtceu:schist_fullers_earth_ore"
+    "gtceu:schist_gypsum_ore"
+    "gtceu:schist_garnierite_ore"
+    "gtceu:schist_nickel_ore"
+    "gtceu:schist_cobaltite_ore"
+    "gtceu:schist_rock_salt_ore"
+    "gtceu:schist_salt_ore"
+    "gtceu:schist_lepidolite_ore"
+    "gtceu:schist_spodumene_ore"
+    "gtceu:schist_oilsands_ore"
+    "gtceu:schist_pyrite_ore"
+    "gtceu:schist_lazurite_ore"
+    "gtceu:schist_sodalite_ore"
+    "gtceu:schist_lapis_ore"
+    "gtceu:schist_calcite_ore"
+    "gtceu:schist_grossular_ore"
+    "gtceu:schist_spessartine_ore"
+    "gtceu:schist_pyrolusite_ore"
+    "gtceu:schist_tantalite_ore"
+    "gtceu:schist_kyanite_ore"
+    "gtceu:schist_mica_ore"
+    "gtceu:schist_bauxite_ore"
+    "gtceu:schist_pollucite_ore"
+    "gtceu:schist_bentonite_ore"
+    "gtceu:schist_olivine_ore"
+    "gtceu:schist_redstone_ore"
+    "gtceu:schist_ruby_ore"
+    "gtceu:schist_cinnabar_ore"
+    "gtceu:schist_almandine_ore"
+    "gtceu:schist_pyrope_ore"
+    "gtceu:schist_sapphire_ore"
+    "gtceu:schist_green_sapphire_ore"
+    "gtceu:schist_thorium_ore"
+    "gtceu:schist_chromite_ore"
+  ]
+  result: "tfc:rock/cobble/schist"
+}

```


</details>

<details>
<summary>tfc/collapse/rock_cobble_schist_slab</summary>

```diff
+{
+  type: "tfc:collapse"
+  ingredient: [
+    "tfc:rock/cobble/schist_slab"
+  ]
+  result: "tfc:rock/cobble/schist_slab"
+}

```


</details>

<details>
<summary>tfc/collapse/rock_cobble_shale</summary>

```diff
+{
+  type: "tfc:collapse"
+  ingredient: [
+    "gtceu:shale_apatite_ore"
+    "gtceu:shale_tricalcium_phosphate_ore"
+    "gtceu:shale_pyrochlore_ore"
+    "gtceu:shale_tin_ore"
+    "gtceu:shale_cassiterite_ore"
+    "gtceu:shale_chalcopyrite_ore"
+    "gtceu:shale_zeolite_ore"
+    "gtceu:shale_realgar_ore"
+    "gtceu:shale_galena_ore"
+    "gtceu:shale_silver_ore"
+    "gtceu:shale_lead_ore"
+    "gtceu:shale_cassiterite_sand_ore"
+    "gtceu:shale_garnet_sand_ore"
+    "gtceu:shale_asbestos_ore"
+    "gtceu:shale_diatomite_ore"
+    "gtceu:shale_red_garnet_ore"
+    "gtceu:shale_yellow_garnet_ore"
+    "gtceu:shale_amethyst_ore"
+    "gtceu:shale_opal_ore"
+    "gtceu:shale_goethite_ore"
+    "gtceu:shale_yellow_limonite_ore"
+    "gtceu:shale_hematite_ore"
+    "gtceu:shale_malachite_ore"
+    "gtceu:shale_soapstone_ore"
+    "gtceu:shale_talc_ore"
+    "gtceu:shale_glauconite_sand_ore"
+    "gtceu:shale_pentlandite_ore"
+    "gtceu:shale_magnetite_ore"
+    "gtceu:shale_vanadium_magnetite_ore"
+    "gtceu:shale_basaltic_mineral_sand_ore"
+    "gtceu:shale_granitic_mineral_sand_ore"
+    "gtceu:shale_fullers_earth_ore"
+    "gtceu:shale_gypsum_ore"
+    "gtceu:shale_garnierite_ore"
+    "gtceu:shale_nickel_ore"
+    "gtceu:shale_cobaltite_ore"
+    "gtceu:shale_rock_salt_ore"
+    "gtceu:shale_salt_ore"
+    "gtceu:shale_lepidolite_ore"
+    "gtceu:shale_spodumene_ore"
+    "gtceu:shale_oilsands_ore"
+    "gtceu:shale_pyrite_ore"
+    "gtceu:shale_lazurite_ore"
+    "gtceu:shale_sodalite_ore"
+    "gtceu:shale_lapis_ore"
+    "gtceu:shale_calcite_ore"
+    "gtceu:shale_grossular_ore"
+    "gtceu:shale_spessartine_ore"
+    "gtceu:shale_pyrolusite_ore"
+    "gtceu:shale_tantalite_ore"
+    "gtceu:shale_kyanite_ore"
+    "gtceu:shale_mica_ore"
+    "gtceu:shale_bauxite_ore"
+    "gtceu:shale_pollucite_ore"
+    "gtceu:shale_bentonite_ore"
+    "gtceu:shale_olivine_ore"
+    "gtceu:shale_redstone_ore"
+    "gtceu:shale_ruby_ore"
+    "gtceu:shale_cinnabar_ore"
+    "gtceu:shale_almandine_ore"
+    "gtceu:shale_pyrope_ore"
+    "gtceu:shale_sapphire_ore"
+    "gtceu:shale_green_sapphire_ore"
+    "gtceu:shale_thorium_ore"
+    "gtceu:shale_chromite_ore"
+  ]
+  result: "tfc:rock/cobble/shale"
+}

```


</details>

<details>
<summary>tfc/collapse/rock_cobble_shale_slab</summary>

```diff
+{
+  type: "tfc:collapse"
+  ingredient: [
+    "tfc:rock/cobble/shale_slab"
+  ]
+  result: "tfc:rock/cobble/shale_slab"
+}

```


</details>

<details>
<summary>tfc/collapse/rock_cobble_slate</summary>

```diff
+{
+  type: "tfc:collapse"
+  ingredient: [
+    "gtceu:slate_apatite_ore"
+    "gtceu:slate_tricalcium_phosphate_ore"
+    "gtceu:slate_pyrochlore_ore"
+    "gtceu:slate_tin_ore"
+    "gtceu:slate_cassiterite_ore"
+    "gtceu:slate_chalcopyrite_ore"
+    "gtceu:slate_zeolite_ore"
+    "gtceu:slate_realgar_ore"
+    "gtceu:slate_galena_ore"
+    "gtceu:slate_silver_ore"
+    "gtceu:slate_lead_ore"
+    "gtceu:slate_cassiterite_sand_ore"
+    "gtceu:slate_garnet_sand_ore"
+    "gtceu:slate_asbestos_ore"
+    "gtceu:slate_diatomite_ore"
+    "gtceu:slate_red_garnet_ore"
+    "gtceu:slate_yellow_garnet_ore"
+    "gtceu:slate_amethyst_ore"
+    "gtceu:slate_opal_ore"
+    "gtceu:slate_goethite_ore"
+    "gtceu:slate_yellow_limonite_ore"
+    "gtceu:slate_hematite_ore"
+    "gtceu:slate_malachite_ore"
+    "gtceu:slate_soapstone_ore"
+    "gtceu:slate_talc_ore"
+    "gtceu:slate_glauconite_sand_ore"
+    "gtceu:slate_pentlandite_ore"
+    "gtceu:slate_magnetite_ore"
+    "gtceu:slate_vanadium_magnetite_ore"
+    "gtceu:slate_basaltic_mineral_sand_ore"
+    "gtceu:slate_granitic_mineral_sand_ore"
+    "gtceu:slate_fullers_earth_ore"
+    "gtceu:slate_gypsum_ore"
+    "gtceu:slate_garnierite_ore"
+    "gtceu:slate_nickel_ore"
+    "gtceu:slate_cobaltite_ore"
+    "gtceu:slate_rock_salt_ore"
+    "gtceu:slate_salt_ore"
+    "gtceu:slate_lepidolite_ore"
+    "gtceu:slate_spodumene_ore"
+    "gtceu:slate_oilsands_ore"
+    "gtceu:slate_pyrite_ore"
+    "gtceu:slate_lazurite_ore"
+    "gtceu:slate_sodalite_ore"
+    "gtceu:slate_lapis_ore"
+    "gtceu:slate_calcite_ore"
+    "gtceu:slate_grossular_ore"
+    "gtceu:slate_spessartine_ore"
+    "gtceu:slate_pyrolusite_ore"
+    "gtceu:slate_tantalite_ore"
+    "gtceu:slate_kyanite_ore"
+    "gtceu:slate_mica_ore"
+    "gtceu:slate_bauxite_ore"
+    "gtceu:slate_pollucite_ore"
+    "gtceu:slate_bentonite_ore"
+    "gtceu:slate_olivine_ore"
+    "gtceu:slate_redstone_ore"
+    "gtceu:slate_ruby_ore"
+    "gtceu:slate_cinnabar_ore"
+    "gtceu:slate_almandine_ore"
+    "gtceu:slate_pyrope_ore"
+    "gtceu:slate_sapphire_ore"
+    "gtceu:slate_green_sapphire_ore"
+    "gtceu:slate_thorium_ore"
+    "gtceu:slate_chromite_ore"
+  ]
+  result: "tfc:rock/cobble/slate"
+}

```


</details>

<details>
<summary>tfc/collapse/rock_cobble_slate_slab</summary>

```diff
+{
+  type: "tfc:collapse"
+  ingredient: [
+    "tfc:rock/cobble/slate_slab"
+  ]
+  result: "tfc:rock/cobble/slate_slab"
+}

```


</details>

<details>
<summary>thoriumreactors/thorium_crafting/grate_wall_block</summary>

```diff
+{
+  type: "thoriumreactors:thorium_crafting"
+  key: {
+    A: {
+      item: "thoriumreactors:blasted_iron_nugget"
+    }
+    B: {
+      item: "thoriumreactors:blasted_iron_ingot"
+    }
+  }
+  pattern: [
+    "     "
+    " BAB "
+    " BAB "
+    " BAB "
+    "     "
+  ]
+  result: {
+    item: "thoriumreactors:grate_wall_block"
+    count: 8
+  }
+}

```


</details>

<details>
<summary>vintageimprovements/centrifugation/cyan_dye</summary>

```diff
+{
+  type: "vintageimprovements:centrifugation"
+  ingredients: [
+    {
+      tag: "forge:dyes/cyan"
+    }
+    {
+      tag: "forge:dyes/cyan"
+    }
+  ]
+  results: [
+    {
+      item: "minecraft:blue_dye"
+      count: 1
+    }
+    {
+      item: "minecraft:green_dye"
+      count: 1
+    }
+  ]
+  processingTime: 1000
+}

```


</details>

<details>
<summary>vintageimprovements/centrifugation/ender_eye</summary>

```diff
+{
+  type: "vintageimprovements:centrifugation"
+  ingredients: [
+    {
+      item: "minecraft:ender_eye"
+    }
+  ]
+  results: [
+    {
+      item: "minecraft:ender_pearl"
+      count: 1
+    }
+    {
+      item: "minecraft:blaze_powder"
+      count: 1
+    }
+  ]
+  processingTime: 1000
+}

```


</details>

<details>
<summary>vintageimprovements/centrifugation/gray_dye</summary>

```diff
+{
+  type: "vintageimprovements:centrifugation"
+  ingredients: [
+    {
+      tag: "forge:dyes/gray"
+    }
+    {
+      tag: "forge:dyes/gray"
+    }
+  ]
+  results: [
+    {
+      item: "minecraft:white_dye"
+      count: 1
+    }
+    {
+      item: "minecraft:black_dye"
+      count: 1
+    }
+  ]
+  processingTime: 1000
+}

```


</details>

<details>
<summary>vintageimprovements/centrifugation/honey_comb</summary>

```diff
+{
+  type: "vintageimprovements:centrifugation"
+  ingredients: [
+    {
+      item: "minecraft:honeycomb"
+    }
+  ]
+  results: [
+    {
+      fluid: "create:honey"
+      amount: 100
+    }
+  ]
+  processingTime: 1000
+}

```


</details>

<details>
<summary>vintageimprovements/centrifugation/light_blue_dye</summary>

```diff
+{
+  type: "vintageimprovements:centrifugation"
+  ingredients: [
+    {
+      tag: "forge:dyes/light_blue"
+    }
+    {
+      tag: "forge:dyes/light_blue"
+    }
+  ]
+  results: [
+    {
+      item: "minecraft:white_dye"
+      count: 1
+    }
+    {
+      item: "minecraft:blue_dye"
+      count: 1
+    }
+  ]
+  processingTime: 1000
+}

```


</details>

<details>
<summary>vintageimprovements/centrifugation/light_gray_dye</summary>

```diff
+{
+  type: "vintageimprovements:centrifugation"
+  ingredients: [
+    {
+      tag: "forge:dyes/light_gray"
+    }
+    {
+      tag: "forge:dyes/light_gray"
+    }
+  ]
+  results: [
+    {
+      item: "minecraft:white_dye"
+      count: 1
+    }
+    {
+      item: "minecraft:gray_dye"
+      count: 1
+    }
+  ]
+  processingTime: 1000
+}

```


</details>

<details>
<summary>vintageimprovements/centrifugation/lime_dye</summary>

```diff
+{
+  type: "vintageimprovements:centrifugation"
+  ingredients: [
+    {
+      tag: "forge:dyes/lime"
+    }
+    {
+      tag: "forge:dyes/lime"
+    }
+  ]
+  results: [
+    {
+      item: "minecraft:white_dye"
+      count: 1
+    }
+    {
+      item: "minecraft:green_dye"
+      count: 1
+    }
+  ]
+  processingTime: 1000
+}

```


</details>

<details>
<summary>vintageimprovements/centrifugation/magenta_dye</summary>

```diff
+{
+  type: "vintageimprovements:centrifugation"
+  ingredients: [
+    {
+      tag: "forge:dyes/magenta"
+    }
+    {
+      tag: "forge:dyes/magenta"
+    }
+  ]
+  results: [
+    {
+      item: "minecraft:pink_dye"
+      count: 1
+    }
+    {
+      item: "minecraft:purple_dye"
+      count: 1
+    }
+  ]
+  processingTime: 1000
+}

```


</details>

<details>
<summary>vintageimprovements/centrifugation/magma_cream</summary>

```diff
+{
+  type: "vintageimprovements:centrifugation"
+  ingredients: [
+    {
+      item: "minecraft:magma_cream"
+    }
+  ]
+  results: [
+    {
+      item: "minecraft:slime_ball"
+      count: 1
+    }
+    {
+      item: "minecraft:blaze_powder"
+      count: 1
+    }
+  ]
+  processingTime: 1000
+}

```


</details>

<details>
<summary>vintageimprovements/centrifugation/mud</summary>

```diff
+{
+  type: "vintageimprovements:centrifugation"
+  ingredients: [
+    {
+      item: "minecraft:mud"
+    }
+  ]
+  results: [
+    {
+      item: "minecraft:dirt"
+      count: 1
+    }
+    {
+      fluid: "minecraft:water"
+      amount: 250
+    }
+  ]
+  processingTime: 1000
+}

```


</details>

<details>
<summary>vintageimprovements/centrifugation/orange_dye</summary>

```diff
+{
+  type: "vintageimprovements:centrifugation"
+  ingredients: [
+    {
+      tag: "forge:dyes/orange"
+    }
+    {
+      tag: "forge:dyes/orange"
+    }
+  ]
+  results: [
+    {
+      item: "minecraft:red_dye"
+      count: 1
+    }
+    {
+      item: "minecraft:yellow_dye"
+      count: 1
+    }
+  ]
+  processingTime: 1000
+}

```


</details>

<details>
<summary>vintageimprovements/centrifugation/pink_dye</summary>

```diff
+{
+  type: "vintageimprovements:centrifugation"
+  ingredients: [
+    {
+      tag: "forge:dyes/pink"
+    }
+    {
+      tag: "forge:dyes/pink"
+    }
+  ]
+  results: [
+    {
+      item: "minecraft:red_dye"
+      count: 1
+    }
+    {
+      item: "minecraft:white_dye"
+      count: 1
+    }
+  ]
+  processingTime: 1000
+}

```


</details>

<details>
<summary>vintageimprovements/centrifugation/purple_dye</summary>

```diff
+{
+  type: "vintageimprovements:centrifugation"
+  ingredients: [
+    {
+      tag: "forge:dyes/purple"
+    }
+    {
+      tag: "forge:dyes/purple"
+    }
+  ]
+  results: [
+    {
+      item: "minecraft:red_dye"
+      count: 1
+    }
+    {
+      item: "minecraft:blue_dye"
+      count: 1
+    }
+  ]
+  processingTime: 1000
+}

```


</details>

<details>
<summary>vintageimprovements/coiling/brass_rod</summary>

```diff
+{
+  type: "vintageimprovements:coiling"
+  ingredients: [
+    {
+      tag: "forge:rods/brass"
+    }
+  ]
+  results: [
+    {
+      item: "vintageimprovements:brass_spring"
+      count: 1
+    }
+  ]
+  processingTime: 120
+  conditions: [
+    {
+      type: "forge:mod_loaded"
+      modid: "createaddition"
+    }
+  ]
+}

```


</details>

<details>
<summary>vintageimprovements/coiling/brass_wire</summary>

```diff
+{
+  type: "vintageimprovements:coiling"
+  ingredients: [
+    {
+      tag: "forge:wires/brass"
+    }
+  ]
+  results: [
+    {
+      item: "vintageimprovements:small_brass_spring"
+      count: 1
+    }
+  ]
+  processingTime: 60
+}

```


</details>

<details>
<summary>vintageimprovements/coiling/copper_rod</summary>

```diff
+{
+  type: "vintageimprovements:coiling"
+  ingredients: [
+    {
+      tag: "forge:rods/copper"
+    }
+  ]
+  results: [
+    {
+      item: "vintageimprovements:copper_spring"
+      count: 1
+    }
+  ]
+  processingTime: 120
+  conditions: [
+    {
+      type: "forge:mod_loaded"
+      modid: "createaddition"
+    }
+  ]
+}

```


</details>

<details>
<summary>vintageimprovements/coiling/copper_wire</summary>

```diff
+{
+  type: "vintageimprovements:coiling"
+  ingredients: [
+    {
+      tag: "forge:wires/copper"
+    }
+  ]
+  results: [
+    {
+      item: "vintageimprovements:small_copper_spring"
+      count: 1
+    }
+  ]
+  processingTime: 60
+  conditions: [
+    {
+      type: "forge:mod_loaded"
+      modid: "createaddition"
+    }
+  ]
+}

```


</details>

<details>
<summary>vintageimprovements/coiling/golden_rod</summary>

```diff
+{
+  type: "vintageimprovements:coiling"
+  ingredients: [
+    {
+      tag: "forge:rods/gold"
+    }
+  ]
+  results: [
+    {
+      item: "vintageimprovements:golden_spring"
+      count: 1
+    }
+  ]
+  processingTime: 120
+  conditions: [
+    {
+      type: "forge:mod_loaded"
+      modid: "createaddition"
+    }
+  ]
+}

```


</details>

<details>
<summary>vintageimprovements/coiling/golden_wire</summary>

```diff
+{
+  type: "vintageimprovements:coiling"
+  ingredients: [
+    {
+      tag: "forge:wires/gold"
+    }
+  ]
+  results: [
+    {
+      item: "vintageimprovements:small_golden_spring"
+      count: 1
+    }
+  ]
+  processingTime: 60
+  conditions: [
+    {
+      type: "forge:mod_loaded"
+      modid: "createaddition"
+    }
+  ]
+}

```


</details>

<details>
<summary>vintageimprovements/coiling/iron_rod</summary>

```diff
+{
+  type: "vintageimprovements:coiling"
+  ingredients: [
+    {
+      tag: "forge:rods/iron"
+    }
+  ]
+  results: [
+    {
+      item: "vintageimprovements:iron_spring"
+      count: 1
+    }
+  ]
+  processingTime: 120
+  conditions: [
+    {
+      type: "forge:mod_loaded"
+      modid: "createaddition"
+    }
+  ]
+}

```


</details>

<details>
<summary>vintageimprovements/coiling/iron_wire</summary>

```diff
+{
+  type: "vintageimprovements:coiling"
+  ingredients: [
+    {
+      tag: "forge:wires/iron"
+    }
+  ]
+  results: [
+    {
+      item: "vintageimprovements:small_iron_spring"
+      count: 1
+    }
+  ]
+  processingTime: 60
+  conditions: [
+    {
+      type: "forge:mod_loaded"
+      modid: "createaddition"
+    }
+  ]
+}

```


</details>

<details>
<summary>vintageimprovements/coiling/steel_rod</summary>

```diff
+{
+  type: "vintageimprovements:coiling"
+  ingredients: [
+    {
+      tag: "forge:rods/steel"
+    }
+  ]
+  results: [
+    {
+      item: "vintageimprovements:steel_spring"
+      count: 1
+    }
+  ]
+  processingTime: 120
+}

```


</details>

<details>
<summary>vintageimprovements/coiling/steel_wire</summary>

```diff
+{
+  type: "vintageimprovements:coiling"
+  ingredients: [
+    {
+      tag: "forge:wires/steel"
+    }
+  ]
+  results: [
+    {
+      item: "vintageimprovements:small_steel_spring"
+      count: 1
+    }
+  ]
+  processingTime: 60
+}

```


</details>

<details>
<summary>vintageimprovements/craft/belt_grinder</summary>

```diff
+{
+  type: "minecraft:crafting_shaped"
+  group: "belt_grinders"
+  key: {
+    B: {
+      item: "vintageimprovements:grinder_belt"
+    }
+    A: {
+      item: "create:andesite_casing"
+    }
+    S: {
+      item: "create:shaft"
+    }
+  }
+  pattern: [
+    "B"
+    "A"
+    "S"
+  ]
+  result: {
+    count: 1
+    item: "vintageimprovements:belt_grinder"
+  }
+}

```


</details>

<details>
<summary>vintageimprovements/craft/centrifuge</summary>

```diff
+{
+  type: "minecraft:crafting_shaped"
+  group: "centrifuges"
+  key: {
+    S: {
+      tag: "vintageimprovements:springs/iron"
+    }
+    s: {
+      item: "create:shaft"
+    }
+    L: {
+      tag: "minecraft:logs"
+    }
+    C: {
+      item: "create:andesite_casing"
+    }
+  }
+  pattern: [
+    "S S"
+    "LsL"
+    "SCS"
+  ]
+  result: {
+    count: 1
+    item: "vintageimprovements:centrifuge"
+  }
+}

```


</details>

<details>
<summary>vintageimprovements/craft/curving_press</summary>

```diff
+{
+  type: "minecraft:crafting_shaped"
+  group: "curving_presses"
+  key: {
+    I: {
+      tag: "forge:ingots/iron"
+    }
+    P: {
+      item: "create:mechanical_press"
+    }
+  }
+  pattern: [
+    "IPI"
+    " I "
+  ]
+  result: {
+    count: 1
+    item: "vintageimprovements:curving_press"
+  }
+}

```


</details>

<details>
<summary>vintageimprovements/craft/grinder_belt</summary>

```diff
+{
+  type: "minecraft:crafting_shaped"
+  group: "grinder_belts"
+  key: {
+    #: {
+      tag: "create:sandpaper"
+    }
+  }
+  pattern: [
+    "###"
+    "# #"
+    "###"
+  ]
+  result: {
+    count: 1
+    item: "vintageimprovements:grinder_belt"
+  }
+}

```


</details>

<details>
<summary>vintageimprovements/craft/spring_coiling_machine</summary>

```diff
+{
+  type: "minecraft:crafting_shaped"
+  group: "belt_grinders"
+  key: {
+    W: {
+      item: "vintageimprovements:spring_coiling_machine_wheel"
+    }
+    I: {
+      tag: "forge:ingots/iron"
+    }
+    A: {
+      item: "create:andesite_casing"
+    }
+    S: {
+      item: "create:shaft"
+    }
+  }
+  pattern: [
+    "I  "
+    "WAS"
+    "I  "
+  ]
+  result: {
+    count: 1
+    item: "vintageimprovements:spring_coiling_machine"
+  }
+}

```


</details>

<details>
<summary>vintageimprovements/craft/spring_coiling_machine_wheel</summary>

```diff
+{
+  type: "minecraft:crafting_shaped"
+  group: "coiling_wheels"
+  key: {
+    B: {
+      tag: "forge:storage_blocks/iron"
+    }
+    A: {
+      item: "create:andesite_alloy"
+    }
+  }
+  pattern: [
+    " A "
+    "ABA"
+    " A "
+  ]
+  result: {
+    count: 1
+    item: "vintageimprovements:spring_coiling_machine_wheel"
+  }
+}

```


</details>

<details>
<summary>vintageimprovements/craft/sulfur_block_to_items</summary>

```diff
+{
+  type: "minecraft:crafting_shaped"
+  key: {
+    B: {
+      tag: "forge:storage_blocks/sulfur"
+    }
+  }
+  pattern: [
+    "B"
+  ]
+  result: {
+    count: 9
+    item: "vintageimprovements:sulfur"
+  }
+}

```


</details>

<details>
<summary>vintageimprovements/craft/sulfur_item_to_nuggets</summary>

```diff
+{
+  type: "minecraft:crafting_shaped"
+  key: {
+    G: {
+      tag: "forge:gems/sulfur"
+    }
+  }
+  pattern: [
+    "G"
+  ]
+  result: {
+    count: 9
+    item: "vintageimprovements:sulfur_chunk"
+  }
+}

```


</details>

<details>
<summary>vintageimprovements/craft/sulfur_items_to_block</summary>

```diff
+{
+  type: "minecraft:crafting_shaped"
+  key: {
+    G: {
+      tag: "forge:gems/sulfur"
+    }
+  }
+  pattern: [
+    "GGG"
+    "GGG"
+    "GGG"
+  ]
+  result: {
+    count: 1
+    item: "vintageimprovements:sulfur_block"
+  }
+}

```


</details>

<details>
<summary>vintageimprovements/craft/sulfur_nuggets_to_item</summary>

```diff
+{
+  type: "minecraft:crafting_shaped"
+  key: {
+    N: {
+      tag: "forge:nuggets/sulfur"
+    }
+  }
+  pattern: [
+    "NNN"
+    "NNN"
+    "NNN"
+  ]
+  result: {
+    count: 1
+    item: "vintageimprovements:sulfur"
+  }
+}

```


</details>

<details>
<summary>vintageimprovements/craft/vacuum_chamber</summary>

```diff
+{
+  type: "minecraft:crafting_shaped"
+  group: "vacuum_chambers"
+  key: {
+    P: {
+      item: "create:mechanical_pump"
+    }
+    S: {
+      tag: "vintageimprovements:springs/iron"
+    }
+    C: {
+      item: "create:andesite_casing"
+    }
+    A: {
+      item: "create:andesite_alloy"
+    }
+  }
+  pattern: [
+    "SCS"
+    "APA"
+  ]
+  result: {
+    count: 1
+    item: "vintageimprovements:vacuum_chamber"
+  }
+}

```


</details>

<details>
<summary>vintageimprovements/craft/vanadium_block_to_ingots</summary>

```diff
+{
+  type: "minecraft:crafting_shaped"
+  key: {
+    B: {
+      tag: "forge:storage_blocks/vanadium"
+    }
+  }
+  pattern: [
+    "B"
+  ]
+  result: {
+    count: 9
+    item: "vintageimprovements:vanadium_ingot"
+  }
+}

```


</details>

<details>
<summary>vintageimprovements/craft/vanadium_ingot_to_nuggets</summary>

```diff
+{
+  type: "minecraft:crafting_shaped"
+  key: {
+    I: {
+      tag: "forge:ingots/vanadium"
+    }
+  }
+  pattern: [
+    "I"
+  ]
+  result: {
+    count: 9
+    item: "vintageimprovements:vanadium_nugget"
+  }
+}

```


</details>

<details>
<summary>vintageimprovements/craft/vanadium_ingots_to_block</summary>

```diff
+{
+  type: "minecraft:crafting_shaped"
+  key: {
+    I: {
+      tag: "forge:ingots/vanadium"
+    }
+  }
+  pattern: [
+    "III"
+    "III"
+    "III"
+  ]
+  result: {
+    count: 1
+    item: "vintageimprovements:vanadium_block"
+  }
+}

```


</details>

<details>
<summary>vintageimprovements/craft/vanadium_nuggets_to_ingot</summary>

```diff
+{
+  type: "minecraft:crafting_shaped"
+  key: {
+    N: {
+      tag: "forge:nuggets/vanadium"
+    }
+  }
+  pattern: [
+    "NNN"
+    "NNN"
+    "NNN"
+  ]
+  result: {
+    count: 1
+    item: "vintageimprovements:vanadium_ingot"
+  }
+}

```


</details>

<details>
<summary>vintageimprovements/craft/vibrating_table</summary>

```diff
+{
+  type: "minecraft:crafting_shaped"
+  group: "vacuum_chambers"
+  key: {
+    S: {
+      tag: "vintageimprovements:springs/iron"
+    }
+    P: {
+      item: "create:mechanical_piston"
+    }
+    T: {
+      tag: "minecraft:wooden_slabs"
+    }
+  }
+  pattern: [
+    "STS"
+    "SPS"
+  ]
+  result: {
+    count: 1
+    item: "vintageimprovements:vibrating_table"
+  }
+}

```


</details>

<details>
<summary>vintageimprovements/crushing/basalt</summary>

```diff
+{
+  type: "create:crushing"
+  ingredients: [
+    {
+      item: "minecraft:basalt"
+    }
+  ]
+  processingTime: 250
+  results: [
+    {
+      chance: 0.3
+      item: "vintageimprovements:vanadium_nugget"
+    }
+    {
+      chance: 0.1
+      item: "vintageimprovements:vanadium_nugget"
+    }
+  ]
+}

```


</details>

<details>
<summary>vintageimprovements/crushing/basalt_recycling</summary>

```diff
+{
+  type: "create:crushing"
+  ingredients: [
+    {
+      tag: "vintageimprovements:stone_types/basalt"
+    }
+  ]
+  processingTime: 250
+  results: [
+    {
+      chance: 0.3
+      item: "vintageimprovements:vanadium_nugget"
+    }
+    {
+      chance: 0.1
+      item: "vintageimprovements:vanadium_nugget"
+    }
+  ]
+}

```


</details>

<details>
<summary>vintageimprovements/crushing/scoria</summary>

```diff
+{
+  type: "create:crushing"
+  ingredients: [
+    [
+      {
+        item: "create:scoria"
+      }
+      {
+        item: "create:scorchia"
+      }
+    ]
+  ]
+  processingTime: 250
+  results: [
+    {
+      chance: 0.3
+      item: "vintageimprovements:sulfur_chunk"
+    }
+    {
+      chance: 0.1
+      item: "vintageimprovements:sulfur_chunk"
+    }
+    {
+      chance: 0.05
+      item: "vintageimprovements:sulfur_chunk"
+    }
+  ]
+}

```


</details>

<details>
<summary>vintageimprovements/crushing/scoria_recycling</summary>

```diff
+{
+  type: "create:crushing"
+  ingredients: [
+    [
+      {
+        tag: "create:stone_types/scoria"
+      }
+      {
+        tag: "create:stone_types/scorchia"
+      }
+    ]
+  ]
+  processingTime: 250
+  results: [
+    {
+      chance: 0.3
+      item: "vintageimprovements:sulfur_chunk"
+    }
+    {
+      chance: 0.1
+      item: "vintageimprovements:sulfur_chunk"
+    }
+    {
+      chance: 0.05
+      item: "vintageimprovements:sulfur_chunk"
+    }
+  ]
+}

```


</details>

<details>
<summary>vintageimprovements/curving/iron_sheet</summary>

```diff
+{
+  type: "vintageimprovements:curving"
+  ingredients: [
+    {
+      tag: "forge:plates/iron"
+    }
+  ]
+  results: [
+    {
+      item: "minecraft:bucket"
+    }
+  ]
+}

```


</details>

<details>
<summary>vintageimprovements/grinder_polishing/rose_quartz</summary>

```diff
+{
+  type: "vintageimprovements:polishing"
+  speed_limits: 1
+  ingredients: [
+    {
+      item: "create:rose_quartz"
+    }
+  ]
+  results: [
+    {
+      item: "create:polished_rose_quartz"
+      count: 1
+    }
+  ]
+  processingTime: 20
+}

```


</details>

<details>
<summary>vintageimprovements/pressurizing/copper_sulfate</summary>

```diff
+{
+  type: "vintageimprovements:pressurizing"
+  ingredients: [
+    {
+      fluid: "vintageimprovements:sulfuric_acid"
+      amount: 200
+    }
+    {
+      fluid: "minecraft:water"
+      amount: 200
+    }
+    {
+      tag: "forge:ingots/copper"
+    }
+  ]
+  results: [
+    {
+      item: "vintageimprovements:copper_sulfate"
+    }
+  ]
+  processingTime: 800
+}

```


</details>

<details>
<summary>vintageimprovements/pressurizing/sulfur_dioxide</summary>

```diff
+{
+  type: "vintageimprovements:pressurizing"
+  secondaryFluidResults: 0
+  heatRequirement: "heated"
+  ingredients: [
+    {
+      tag: "forge:gems/sulfur"
+    }
+  ]
+  results: [
+    {
+      fluid: "vintageimprovements:sulfur_dioxide"
+      amount: 1000
+    }
+  ]
+  processingTime: 600
+}

```


</details>

<details>
<summary>vintageimprovements/pressurizing/sulfur_trioxide</summary>

```diff
+{
+  type: "vintageimprovements:pressurizing"
+  secondaryFluidResults: 0
+  heatRequirement: "heated"
+  ingredients: [
+    {
+      fluid: "vintageimprovements:sulfur_dioxide"
+      amount: 250
+    }
+    {
+      tag: "forge:nuggets/vanadium"
+    }
+  ]
+  results: [
+    {
+      fluid: "vintageimprovements:sulfur_trioxide"
+      amount: 250
+    }
+  ]
+  processingTime: 400
+}

```


</details>

<details>
<summary>vintageimprovements/pressurizing/sulfur_trioxide_alt</summary>

```diff
+{
+  type: "vintageimprovements:pressurizing"
+  secondaryFluidResults: 0
+  heatRequirement: "superheated"
+  ingredients: [
+    {
+      fluid: "vintageimprovements:sulfur_dioxide"
+      amount: 250
+    }
+    {
+      tag: "forge:nuggets/iron"
+    }
+  ]
+  results: [
+    {
+      fluid: "vintageimprovements:sulfur_trioxide"
+      amount: 250
+    }
+  ]
+  processingTime: 400
+}

```


</details>

<details>
<summary>vintageimprovements/pressurizing/sulfuric_acid</summary>

```diff
+{
+  type: "vintageimprovements:pressurizing"
+  secondaryFluidInputs: 1
+  ingredients: [
+    {
+      fluid: "vintageimprovements:sulfur_trioxide"
+      amount: 1000
+    }
+    {
+      fluid: "minecraft:water"
+      amount: 1000
+    }
+  ]
+  results: [
+    {
+      fluid: "vintageimprovements:sulfuric_acid"
+      amount: 1000
+    }
+  ]
+  processingTime: 600
+}

```


</details>

<details>
<summary>vintageimprovements/rolling/brass_plate</summary>

```diff
+{
+  type: "createaddition:rolling"
+  input: {
+    tag: "forge:plates/brass"
+  }
+  result: {
+    item: "vintageimprovements:brass_wire"
+    count: 2
+  }
+  conditions: [
+    {
+      type: "forge:mod_loaded"
+      modid: "createaddition"
+    }
+  ]
+}

```


</details>

<details>
<summary>vintageimprovements/rolling/steel_plate</summary>

```diff
+{
+  type: "createaddition:rolling"
+  input: {
+    tag: "forge:plates/steel"
+  }
+  result: {
+    item: "vintageimprovements:steel_wire"
+    count: 2
+  }
+  conditions: [
+    {
+      type: "forge:mod_loaded"
+      modid: "createaddition"
+    }
+  ]
+}

```


</details>

<details>
<summary>vintageimprovements/sequenced_assembly/redstone_module</summary>

```diff
+{
+  type: "create:sequenced_assembly"
+  ingredient: {
+    tag: "forge:plates/gold"
+  }
+  loops: 3
+  results: [
+    {
+      item: "vintageimprovements:redstone_module"
+    }
+  ]
+  sequence: [
+    {
+      type: "create:deploying"
+      ingredients: [
+        {
+          item: "vintageimprovements:incomplete_redstone_module"
+        }
+        {
+          item: "minecraft:redstone"
+        }
+      ]
+      results: [
+        {
+          item: "vintageimprovements:incomplete_redstone_module"
+        }
+      ]
+    }
+    {
+      type: "vintageimprovements:vibrating"
+      ingredients: [
+        {
+          item: "vintageimprovements:incomplete_redstone_module"
+        }
+      ]
+      results: [
+        {
+          item: "vintageimprovements:incomplete_redstone_module"
+        }
+      ]
+    }
+    {
+      type: "create:deploying"
+      ingredients: [
+        {
+          item: "vintageimprovements:incomplete_redstone_module"
+        }
+        {
+          tag: "forge:gems/quartz"
+        }
+      ]
+      results: [
+        {
+          item: "vintageimprovements:incomplete_redstone_module"
+        }
+      ]
+    }
+    {
+      type: "create:pressing"
+      ingredients: [
+        {
+          item: "vintageimprovements:incomplete_redstone_module"
+        }
+      ]
+      results: [
+        {
+          item: "vintageimprovements:incomplete_redstone_module"
+        }
+      ]
+    }
+    {
+      type: "create:deploying"
+      ingredients: [
+        {
+          item: "vintageimprovements:incomplete_redstone_module"
+        }
+        {
+          tag: "forge:nuggets/iron"
+        }
+      ]
+      results: [
+        {
+          item: "vintageimprovements:incomplete_redstone_module"
+        }
+      ]
+    }
+  ]
+  transitionalItem: {
+    item: "vintageimprovements:incomplete_redstone_module"
+  }
+}

```


</details>

<details>
<summary>vintageimprovements/vacuumizing/powder_snow</summary>

```diff
+{
+  type: "vintageimprovements:vacuumizing"
+  ingredients: [
+    {
+      item: "minecraft:bucket"
+    }
+    {
+      item: "minecraft:snow_block"
+    }
+  ]
+  results: [
+    {
+      item: "minecraft:powder_snow_bucket"
+      count: 1
+    }
+  ]
+  processingTime: 600
+}

```


</details>

<details>
<summary>vintageimprovements/vibrating/leaves_vibrating</summary>

```diff
+{
+  type: "vintageimprovements:leaves_vibrating"
+  ingredients: [
+    {
+      tag: "minecraft:leaves"
+    }
+  ]
+  results: [
+  ]
+  processingTime: 300
+}

```


</details>

<details>
<summary>vintageimprovements/vibrating/snow</summary>

```diff
+{
+  type: "vintageimprovements:vibrating"
+  ingredients: [
+    {
+      item: "minecraft:snow"
+    }
+  ]
+  results: [
+    {
+      item: "minecraft:snowball"
+      count: 2
+    }
+  ]
+  processingTime: 300
+}

```


</details>

<details>
<summary>vintageimprovements/vibrating/snow_block</summary>

```diff
+{
+  type: "vintageimprovements:vibrating"
+  ingredients: [
+    {
+      item: "minecraft:snow_block"
+    }
+  ]
+  results: [
+    {
+      item: "minecraft:snowball"
+      count: 4
+    }
+  ]
+  processingTime: 300
+}

```


</details>

</blockquote>

</details>

<details>
<summary>Changed (323)</summary>
<blockquote>

<details>
<summary>almostunified/createaddition</summary>

```diff
 {
   type: "almostunified:client_recipe_tracker"
   namespace: "createaddition"
   recipes: [
     "1$compat/immersiveengineering/crushing/steel_ingot"
     "1$crafting/electrum_ingot"
     "1$crushing/diamond"
     "1$mixing/electrum"
     "1$pressing/aluminum_ingot"
     "1$pressing/electrum_ingot"
     "1$pressing/lead_ingot"
     "1$pressing/nickel_ingot"
     "1$pressing/silver_ingot"
     "1$pressing/steel_ingot"
     "1$pressing/uranium_ingot"
     "1$pressing/zinc_ingot"
     "1$rolling/brass_ingot"
     "1$rolling/copper_ingot"
     "1$rolling/electrum_ingot"
     "1$rolling/gold_ingot"
     "1$rolling/iron_ingot"
-    "1$rolling/steel_ingot"
     "3$crafting/electrum_nugget"
+    "3$rolling/steel_ingot"
   ]
 }

```


</details>

<details>
<summary>almostunified/firmalife</summary>

```diff
 {
   type: "almostunified:client_recipe_tracker"
   namespace: "firmalife"
   recipes: [
     "1$anvil/chromium_rod"
     "1$anvil/chromium_sheet"
     "1$anvil/stainless_steel_rod"
     "1$anvil/stainless_steel_sheet"
     "1$crafting/greenhouse/copper_greenhouse_door"
     "1$crafting/greenhouse/copper_greenhouse_panel_roof"
     "1$crafting/greenhouse/copper_greenhouse_panel_wall"
     "1$crafting/greenhouse/copper_greenhouse_port"
     "1$crafting/greenhouse/copper_greenhouse_roof"
     "1$crafting/greenhouse/copper_greenhouse_roof_top"
     "1$crafting/greenhouse/copper_greenhouse_trapdoor"
     "1$crafting/greenhouse/copper_greenhouse_wall"
     "1$crafting/greenhouse/iron_greenhouse_door"
     "1$crafting/greenhouse/iron_greenhouse_panel_roof"
     "1$crafting/greenhouse/iron_greenhouse_panel_wall"
     "1$crafting/greenhouse/iron_greenhouse_port"
     "1$crafting/greenhouse/iron_greenhouse_roof"
     "1$crafting/greenhouse/iron_greenhouse_roof_top"
     "1$crafting/greenhouse/iron_greenhouse_trapdoor"
     "1$crafting/greenhouse/iron_greenhouse_wall"
     "1$crafting/greenhouse/stainless_steel_greenhouse_door"
     "1$crafting/greenhouse/stainless_steel_greenhouse_panel_roof"
     "1$crafting/greenhouse/stainless_steel_greenhouse_panel_wall"
     "1$crafting/greenhouse/stainless_steel_greenhouse_port"
     "1$crafting/greenhouse/stainless_steel_greenhouse_roof"
     "1$crafting/greenhouse/stainless_steel_greenhouse_roof_top"
     "1$crafting/greenhouse/stainless_steel_greenhouse_trapdoor"
     "1$crafting/greenhouse/stainless_steel_greenhouse_wall"
     "1$heating/metal/chromium_double_ingot"
     "1$heating/metal/chromium_double_sheet"
     "1$heating/metal/chromium_ingot"
     "1$heating/metal/chromium_rod"
     "1$heating/metal/chromium_sheet"
     "1$heating/metal/stainless_steel_double_ingot"
     "1$heating/metal/stainless_steel_double_sheet"
     "1$heating/metal/stainless_steel_ingot"
     "1$heating/metal/stainless_steel_rod"
     "1$heating/metal/stainless_steel_sheet"
+    "1$welding/chromium_double_ingot"
+    "1$welding/chromium_double_sheet"
+    "1$welding/stainless_steel_double_ingot"
+    "1$welding/stainless_steel_double_sheet"
   ]
 }

```


</details>

<details>
<summary>almostunified/gtceu</summary>

```diff
 {
   type: "almostunified:client_recipe_tracker"
   namespace: "gtceu"
   recipes: [
     "1$alloy_smelter/alloy_smelt_chromium_nugget_to_ingot"
     "1$alloy_smelter/alloy_smelt_chromium_to_ingot"
     "1$alloy_smelter/alloy_smelt_copper_nugget_to_ingot"
     "1$alloy_smelter/alloy_smelt_copper_to_ingot"
     "1$alloy_smelter/alloy_smelt_gold_nugget_to_ingot"
     "1$alloy_smelter/alloy_smelt_gold_to_ingot"
     "1$alloy_smelter/alloy_smelt_stainless_steel_nugget_to_ingot"
     "1$alloy_smelter/alloy_smelt_stainless_steel_to_ingot"
     "1$arc_furnace/arc_auto_maintenance_hatch"
     "1$arc_furnace/arc_brass_gear"
     "1$arc_furnace/arc_chromium_block"
     "1$arc_furnace/arc_chromium_huge_fluid_pipe"
     "1$arc_furnace/arc_chromium_large_fluid_pipe"
     "1$arc_furnace/arc_chromium_normal_fluid_pipe"
     "1$arc_furnace/arc_chromium_plate"
     "1$arc_furnace/arc_chromium_quadruple_fluid_pipe"
     "1$arc_furnace/arc_chromium_rotor"
     "1$arc_furnace/arc_chromium_small_fluid_pipe"
     "1$arc_furnace/arc_chromium_turbine_blade"
     "1$arc_furnace/arc_clean_machine_casing"
     "1$arc_furnace/arc_cleaning_maintenance_hatch"
     "1$arc_furnace/arc_cleanroom"
     "1$arc_furnace/arc_clock"
     "1$arc_furnace/arc_configurable_maintenance_hatch"
     "1$arc_furnace/arc_copper_gear"
     "1$arc_furnace/arc_cracker"
     "1$arc_furnace/arc_distillation_tower"
     "1$arc_furnace/arc_double_chromium_plate"
     "1$arc_furnace/arc_double_gold_plate"
     "1$arc_furnace/arc_double_stainless_steel_plate"
     "1$arc_furnace/arc_electrum_gear"
     "1$arc_furnace/arc_ev_chemical_reactor"
     "1$arc_furnace/arc_ev_fluid_heater"
     "1$arc_furnace/arc_ev_fluid_solidifier"
     "1$arc_furnace/arc_ev_gas_collector"
     "1$arc_furnace/arc_ev_hermetic_casing"
     "1$arc_furnace/arc_ev_mixer"
     "1$arc_furnace/arc_ev_muffler_hatch"
     "1$arc_furnace/arc_ev_ore_washer"
     "1$arc_furnace/arc_ev_pump"
     "1$arc_furnace/arc_ev_stainless_steel_drill"
     "1$arc_furnace/arc_gas_large_turbine"
     "1$arc_furnace/arc_gold_block"
     "1$arc_furnace/arc_gold_double_cable"
     "1$arc_furnace/arc_gold_double_wire"
     "1$arc_furnace/arc_gold_drum"
     "1$arc_furnace/arc_gold_dust"
     "1$arc_furnace/arc_gold_gear"
     "1$arc_furnace/arc_gold_hex_cable"
     "1$arc_furnace/arc_gold_hex_wire"
     "1$arc_furnace/arc_gold_huge_fluid_pipe"
     "1$arc_furnace/arc_gold_large_fluid_pipe"
     "1$arc_furnace/arc_gold_normal_fluid_pipe"
     "1$arc_furnace/arc_gold_octal_cable"
     "1$arc_furnace/arc_gold_octal_wire"
     "1$arc_furnace/arc_gold_plate"
     "1$arc_furnace/arc_gold_quadruple_cable"
     "1$arc_furnace/arc_gold_quadruple_fluid_pipe"
     "1$arc_furnace/arc_gold_quadruple_wire"
     "1$arc_furnace/arc_gold_small_fluid_pipe"
     "1$arc_furnace/arc_gold_spring"
     "1$arc_furnace/arc_golden_apple"
     "1$arc_furnace/arc_golden_axe"
     "1$arc_furnace/arc_golden_boots"
     "1$arc_furnace/arc_golden_chestplate"
     "1$arc_furnace/arc_golden_helmet"
     "1$arc_furnace/arc_golden_hoe"
     "1$arc_furnace/arc_golden_horse_armor"
     "1$arc_furnace/arc_golden_leggings"
     "1$arc_furnace/arc_golden_pickaxe"
     "1$arc_furnace/arc_golden_shovel"
     "1$arc_furnace/arc_golden_sword"
     "1$arc_furnace/arc_hv_16a_energy_converter"
     "1$arc_furnace/arc_hv_1a_energy_converter"
     "1$arc_furnace/arc_hv_4a_energy_converter"
     "1$arc_furnace/arc_hv_8a_energy_converter"
     "1$arc_furnace/arc_hv_alloy_smelter"
     "1$arc_furnace/arc_hv_arc_furnace"
     "1$arc_furnace/arc_hv_assembler"
     "1$arc_furnace/arc_hv_autoclave"
     "1$arc_furnace/arc_hv_battery_buffer_16x"
     "1$arc_furnace/arc_hv_battery_buffer_4x"
     "1$arc_furnace/arc_hv_battery_buffer_8x"
     "1$arc_furnace/arc_hv_bender"
     "1$arc_furnace/arc_hv_block_breaker"
     "1$arc_furnace/arc_hv_brewery"
     "1$arc_furnace/arc_hv_canner"
     "1$arc_furnace/arc_hv_centrifuge"
     "1$arc_furnace/arc_hv_chemical_bath"
     "1$arc_furnace/arc_hv_chemical_reactor"
     "1$arc_furnace/arc_hv_circuit_assembler"
     "1$arc_furnace/arc_hv_combustion"
     "1$arc_furnace/arc_hv_compressor"
     "1$arc_furnace/arc_hv_conveyor_module"
     "1$arc_furnace/arc_hv_cutter"
     "1$arc_furnace/arc_hv_diode"
     "1$arc_furnace/arc_hv_distillery"
     "1$arc_furnace/arc_hv_electric_furnace"
     "1$arc_furnace/arc_hv_electric_motor"
     "1$arc_furnace/arc_hv_electric_piston"
     "1$arc_furnace/arc_hv_electric_pump"
     "1$arc_furnace/arc_hv_electromagnetic_separator"
     "1$arc_furnace/arc_hv_emitter"
     "1$arc_furnace/arc_hv_energy_input_hatch"
     "1$arc_furnace/arc_hv_energy_output_hatch"
     "1$arc_furnace/arc_hv_extractor"
     "1$arc_furnace/arc_hv_fermenter"
     "1$arc_furnace/arc_hv_field_generator"
     "1$arc_furnace/arc_hv_fisher"
     "1$arc_furnace/arc_hv_fluid_heater"
     "1$arc_furnace/arc_hv_fluid_passthrough_hatch"
     "1$arc_furnace/arc_hv_fluid_solidifier"
     "1$arc_furnace/arc_hv_forge_hammer"
     "1$arc_furnace/arc_hv_forming_press"
     "1$arc_furnace/arc_hv_gas_collector"
     "1$arc_furnace/arc_hv_hermetic_casing"
     "1$arc_furnace/arc_hv_item_magnet"
     "1$arc_furnace/arc_hv_item_passthrough_hatch"
     "1$arc_furnace/arc_hv_laser_engraver"
     "1$arc_furnace/arc_hv_lathe"
     "1$arc_furnace/arc_hv_macerator"
     "1$arc_furnace/arc_hv_machine_casing"
     "1$arc_furnace/arc_hv_machine_hull"
     "1$arc_furnace/arc_hv_miner"
     "1$arc_furnace/arc_hv_mixer"
     "1$arc_furnace/arc_hv_muffler_hatch"
     "1$arc_furnace/arc_hv_ore_washer"
     "1$arc_furnace/arc_hv_packer"
     "1$arc_furnace/arc_hv_polarizer"
     "1$arc_furnace/arc_hv_pump"
     "1$arc_furnace/arc_hv_rock_crusher"
     "1$arc_furnace/arc_hv_rotor_holder"
     "1$arc_furnace/arc_hv_sensor"
     "1$arc_furnace/arc_hv_sifter"
     "1$arc_furnace/arc_hv_stainless_steel_drill"
     "1$arc_furnace/arc_hv_stainless_steel_wrench"
     "1$arc_furnace/arc_hv_steam_turbine"
     "1$arc_furnace/arc_hv_super_chest"
     "1$arc_furnace/arc_hv_super_tank"
     "1$arc_furnace/arc_hv_thermal_centrifuge"
     "1$arc_furnace/arc_hv_transformer_16a"
     "1$arc_furnace/arc_hv_transformer_1a"
     "1$arc_furnace/arc_hv_transformer_2a"
     "1$arc_furnace/arc_hv_transformer_4a"
     "1$arc_furnace/arc_hv_wiremill"
     "1$arc_furnace/arc_hv_world_accelerator"
     "1$arc_furnace/arc_implosion_compressor"
     "1$arc_furnace/arc_iv_processing_array"
     "1$arc_furnace/arc_iv_quantum_chest"
     "1$arc_furnace/arc_iv_stainless_steel_drill"
     "1$arc_furnace/arc_iv_stainless_steel_wrench"
     "1$arc_furnace/arc_large_centrifuge"
     "1$arc_furnace/arc_large_chemical_reactor"
     "1$arc_furnace/arc_large_distillery"
     "1$arc_furnace/arc_large_packer"
     "1$arc_furnace/arc_lead_gear"
     "1$arc_furnace/arc_light_weighted_pressure_plate"
     "1$arc_furnace/arc_long_gold_rod"
     "1$arc_furnace/arc_long_stainless_steel_rod"
     "1$arc_furnace/arc_lv_electrolyzer"
     "1$arc_furnace/arc_lv_stainless_steel_chainsaw"
     "1$arc_furnace/arc_lv_stainless_steel_drill"
     "1$arc_furnace/arc_lv_stainless_steel_screwdriver"
     "1$arc_furnace/arc_lv_stainless_steel_wrench"
     "1$arc_furnace/arc_mv_stainless_steel_drill"
     "1$arc_furnace/arc_mv_transformer_16a"
     "1$arc_furnace/arc_mv_transformer_2a"
     "1$arc_furnace/arc_mv_transformer_4a"
     "1$arc_furnace/arc_nichrome_coil_block"
     "1$arc_furnace/arc_nickel_gear"
     "1$arc_furnace/arc_osmium_gear"
     "1$arc_furnace/arc_platinum_gear"
     "1$arc_furnace/arc_prospector.hv"
     "1$arc_furnace/arc_silver_gear"
     "1$arc_furnace/arc_small_stainless_steel_gear"
     "1$arc_furnace/arc_stainless_steel_block"
     "1$arc_furnace/arc_stainless_steel_buzzsaw"
     "1$arc_furnace/arc_stainless_steel_crate"
     "1$arc_furnace/arc_stainless_steel_drum"
     "1$arc_furnace/arc_stainless_steel_fluid_cell"
     "1$arc_furnace/arc_stainless_steel_frame"
     "1$arc_furnace/arc_stainless_steel_gear"
     "1$arc_furnace/arc_stainless_steel_gearbox"
     "1$arc_furnace/arc_stainless_steel_huge_fluid_pipe"
     "1$arc_furnace/arc_stainless_steel_large_fluid_pipe"
     "1$arc_furnace/arc_stainless_steel_normal_fluid_pipe"
     "1$arc_furnace/arc_stainless_steel_plate"
     "1$arc_furnace/arc_stainless_steel_quadruple_fluid_pipe"
     "1$arc_furnace/arc_stainless_steel_rotor"
     "1$arc_furnace/arc_stainless_steel_small_fluid_pipe"
     "1$arc_furnace/arc_stainless_steel_turbine_blade"
     "1$arc_furnace/arc_stainless_steel_turbine_casing"
     "1$arc_furnace/arc_tin_gear"
     "1$arc_furnace/arc_titanium_large_boiler"
     "1$arc_furnace/arc_uranium_gear"
     "1$arc_furnace/arc_vacuum_freezer"
     "1$arc_furnace/arc_zinc_gear"
     "1$autoclave/autoclave_dust_apatite__distilled"
     "1$autoclave/autoclave_dust_apatite__water"
     "1$autoclave/autoclave_dust_cinnabar__distilled"
     "1$autoclave/autoclave_dust_cinnabar__water"
     "1$autoclave/autoclave_dust_lapis__distilled"
     "1$autoclave/autoclave_dust_lapis__water"
     "1$blasting/smelt_bornite_ore_to_ingot"
     "1$blasting/smelt_chalcocite_ore_to_ingot"
     "1$blasting/smelt_chalcopyrite_ore_to_ingot"
     "1$blasting/smelt_copper_ore_to_ingot"
     "1$blasting/smelt_deepslate_bornite_ore_to_ingot"
     "1$blasting/smelt_deepslate_chalcocite_ore_to_ingot"
     "1$blasting/smelt_deepslate_chalcopyrite_ore_to_ingot"
     "1$blasting/smelt_deepslate_copper_ore_to_ingot"
     "1$blasting/smelt_deepslate_diamond_ore_to_ingot"
     "1$blasting/smelt_deepslate_emerald_ore_to_ingot"
     "1$blasting/smelt_deepslate_gold_ore_to_ingot"
     "1$blasting/smelt_deepslate_lapis_ore_to_ingot"
     "1$blasting/smelt_deepslate_malachite_ore_to_ingot"
     "1$blasting/smelt_deepslate_tetrahedrite_ore_to_ingot"
     "1$blasting/smelt_diamond_ore_to_ingot"
     "1$blasting/smelt_emerald_ore_to_ingot"
     "1$blasting/smelt_endstone_bornite_ore_to_ingot"
     "1$blasting/smelt_endstone_chalcocite_ore_to_ingot"
     "1$blasting/smelt_endstone_chalcopyrite_ore_to_ingot"
     "1$blasting/smelt_endstone_copper_ore_to_ingot"
     "1$blasting/smelt_endstone_diamond_ore_to_ingot"
     "1$blasting/smelt_endstone_emerald_ore_to_ingot"
     "1$blasting/smelt_endstone_gold_ore_to_ingot"
     "1$blasting/smelt_endstone_lapis_ore_to_ingot"
     "1$blasting/smelt_endstone_malachite_ore_to_ingot"
     "1$blasting/smelt_endstone_tetrahedrite_ore_to_ingot"
     "1$blasting/smelt_gold_ore_to_ingot"
     "1$blasting/smelt_lapis_ore_to_ingot"
     "1$blasting/smelt_malachite_ore_to_ingot"
     "1$blasting/smelt_netherrack_bornite_ore_to_ingot"
     "1$blasting/smelt_netherrack_chalcocite_ore_to_ingot"
     "1$blasting/smelt_netherrack_chalcopyrite_ore_to_ingot"
     "1$blasting/smelt_netherrack_copper_ore_to_ingot"
     "1$blasting/smelt_netherrack_diamond_ore_to_ingot"
     "1$blasting/smelt_netherrack_emerald_ore_to_ingot"
     "1$blasting/smelt_netherrack_gold_ore_to_ingot"
     "1$blasting/smelt_netherrack_lapis_ore_to_ingot"
     "1$blasting/smelt_netherrack_malachite_ore_to_ingot"
     "1$blasting/smelt_netherrack_tetrahedrite_ore_to_ingot"
     "1$blasting/smelt_raw_bornite_ore_to_ingot"
     "1$blasting/smelt_raw_chalcocite_ore_to_ingot"
     "1$blasting/smelt_raw_chalcopyrite_ore_to_ingot"
     "1$blasting/smelt_raw_diamond_ore_to_ingot"
     "1$blasting/smelt_raw_emerald_ore_to_ingot"
     "1$blasting/smelt_raw_lapis_ore_to_ingot"
     "1$blasting/smelt_raw_malachite_ore_to_ingot"
     "1$blasting/smelt_raw_tetrahedrite_ore_to_ingot"
     "1$blasting/smelt_tetrahedrite_ore_to_ingot"
     "1$compressor/compress_chromium_nugget_to_ingot"
     "1$compressor/compress_copper_nugget_to_ingot"
     "1$compressor/compress_gold_nugget_to_ingot"
     "1$compressor/compress_plate_dust_obsidian_"
     "1$compressor/compress_stainless_steel_nugget_to_ingot"
     "1$cutter/cut_diamond_flawless_gem_to_gem"
     "1$cutter/cut_diamond_flawless_gem_to_gem_distilled_water"
     "1$cutter/cut_diamond_flawless_gem_to_gem_water"
     "1$cutter/cut_emerald_flawless_gem_to_gem"
     "1$cutter/cut_emerald_flawless_gem_to_gem_distilled_water"
     "1$cutter/cut_emerald_flawless_gem_to_gem_water"
     "1$cutter/cut_lapis_flawless_gem_to_gem"
     "1$cutter/cut_lapis_flawless_gem_to_gem_distilled_water"
     "1$cutter/cut_lapis_flawless_gem_to_gem_water"
     "1$cutter/cut_stainless_steel_long_rod_to_rod"
     "1$cutter/cut_stainless_steel_long_rod_to_rod_distilled_water"
     "1$cutter/cut_stainless_steel_long_rod_to_rod_water"
     "1$electric_blast_furnace/blast_chromium"
     "1$electric_blast_furnace/blast_chromium_gas"
     "1$electric_blast_furnace/blast_stainless_steel"
     "1$electric_blast_furnace/blast_stainless_steel_gas"
     "1$extractor/charcoal_extraction"
     "1$extruder/extrude_chromium_to_rod"
     "1$extruder/extrude_stainless_steel_to_rod"
     "1$fluid_solidifier/solidify_chromium_to_ingot"
     "1$fluid_solidifier/solidify_copper_to_ingot"
     "1$fluid_solidifier/solidify_gold_to_ingot"
     "1$fluid_solidifier/solidify_stainless_steel_to_ingot"
     "1$forge_hammer/hammer_diamond_block_to_gem"
     "1$forge_hammer/hammer_emerald_block_to_gem"
     "1$forge_hammer/hammer_lapis_block_to_gem"
     "1$implosion_compressor/implode_dust_apatite__tnt"
     "1$implosion_compressor/implode_dust_cinnabar__tnt"
     "1$implosion_compressor/implode_dust_diamond__tnt"
     "1$implosion_compressor/implode_dust_emerald__tnt"
     "1$implosion_compressor/implode_dust_fluorite__tnt"
     "1$implosion_compressor/implode_dust_lapis__tnt"
     "1$implosion_compressor/implode_dust_ruby__tnt"
     "1$implosion_compressor/implode_dust_sapphire__tnt"
     "1$large_boiler/charcoal_block"
     "1$large_boiler/charcoal_dust"
     "1$large_boiler/coal_dust"
     "1$laser_engraver/engrave_apatite_flawless_gem_to_gem"
     "1$laser_engraver/engrave_cinnabar_flawless_gem_to_gem"
     "1$laser_engraver/engrave_coal_flawless_gem_to_gem"
     "1$laser_engraver/engrave_diamond_flawless_gem_to_gem"
     "1$laser_engraver/engrave_diamond_gem_to_flawed_gem"
     "1$laser_engraver/engrave_emerald_flawless_gem_to_gem"
     "1$laser_engraver/engrave_emerald_gem_to_flawed_gem"
     "1$laser_engraver/engrave_fluorite_flawless_gem_to_gem"
     "1$laser_engraver/engrave_lapis_flawless_gem_to_gem"
     "1$laser_engraver/engrave_lapis_gem_to_flawed_gem"
     "1$laser_engraver/engrave_ruby_flawless_gem_to_gem"
     "1$laser_engraver/engrave_sapphire_flawless_gem_to_gem"
     "1$lathe/lathe_chromium_to_rod"
     "1$lathe/lathe_stainless_steel_to_rod"
     "1$macerator/macerate_beryllium_ore_to_raw_ore"
     "1$macerator/macerate_brass_gear"
     "1$macerator/macerate_copper_gear"
     "1$macerator/macerate_deepslate_beryllium_ore_to_raw_ore"
     "1$macerator/macerate_electrum_gear"
     "1$macerator/macerate_endstone_beryllium_ore_to_raw_ore"
     "1$macerator/macerate_fluorite_ingot"
     "1$macerator/macerate_fluorite_nugget"
     "1$macerator/macerate_gold_gear"
+    "1$macerator/macerate_graphite_block"
     "1$macerator/macerate_graphite_ingot"
     "1$macerator/macerate_graphite_nugget"
     "1$macerator/macerate_lead_gear"
     "1$macerator/macerate_netherrack_beryllium_ore_to_raw_ore"
     "1$macerator/macerate_nickel_gear"
+    "1$macerator/macerate_niob_block"
     "1$macerator/macerate_osmium_gear"
     "1$macerator/macerate_platinum_gear"
     "1$macerator/macerate_silver_gear"
+    "1$macerator/macerate_sulfur"
+    "1$macerator/macerate_sulfur_block"
+    "1$macerator/macerate_sulfur_chunk"
     "1$macerator/macerate_tin_gear"
     "1$macerator/macerate_uranium_gear"
     "1$macerator/macerate_zinc_gear"
     "1$pyrolyse_oven/charcoal_to_coal_tar"
     "1$pyrolyse_oven/coal_to_coal_tar"
     "1$shaped/stick_chromium"
     "1$shaped/stick_long_stainless_steel"
     "1$shaped/stick_stainless_steel"
     "1$shapeless/gem_to_gem_gem_diamond"
     "1$shapeless/gem_to_gem_gem_emerald"
     "1$shapeless/gem_to_gem_gem_lapis"
     "1$sifter/sift_diamond_purified_ore_to_gems"
     "1$sifter/sift_emerald_purified_ore_to_gems"
     "1$sifter/sift_lapis_purified_ore_to_gems"
     "1$smelting/dust_bornite__dust_to_ingot"
     "1$smelting/dust_chalcocite__dust_to_ingot"
     "1$smelting/dust_chalcopyrite__dust_to_ingot"
     "1$smelting/dust_copper__demagnetize_from_dust"
     "1$smelting/dust_gold__demagnetize_from_dust"
     "1$smelting/dust_malachite__ingot"
     "1$smelting/dust_tetrahedrite__dust_to_ingot"
     "1$smelting/smelt_bornite_ore_to_ingot"
     "1$smelting/smelt_chalcocite_ore_to_ingot"
     "1$smelting/smelt_chalcopyrite_ore_to_ingot"
     "1$smelting/smelt_copper_ore_to_ingot"
     "1$smelting/smelt_crushed_ore_bornite_to_ingot"
     "1$smelting/smelt_crushed_ore_chalcocite_to_ingot"
     "1$smelting/smelt_crushed_ore_chalcopyrite_to_ingot"
     "1$smelting/smelt_crushed_ore_copper_to_ingot"
     "1$smelting/smelt_crushed_ore_gold_to_ingot"
     "1$smelting/smelt_crushed_ore_malachite_to_ingot"
     "1$smelting/smelt_crushed_ore_tetrahedrite_to_ingot"
     "1$smelting/smelt_deepslate_bornite_ore_to_ingot"
     "1$smelting/smelt_deepslate_chalcocite_ore_to_ingot"
     "1$smelting/smelt_deepslate_chalcopyrite_ore_to_ingot"
     "1$smelting/smelt_deepslate_copper_ore_to_ingot"
     "1$smelting/smelt_deepslate_diamond_ore_to_ingot"
     "1$smelting/smelt_deepslate_emerald_ore_to_ingot"
     "1$smelting/smelt_deepslate_gold_ore_to_ingot"
     "1$smelting/smelt_deepslate_lapis_ore_to_ingot"
     "1$smelting/smelt_deepslate_malachite_ore_to_ingot"
     "1$smelting/smelt_deepslate_tetrahedrite_ore_to_ingot"
     "1$smelting/smelt_diamond_ore_to_ingot"
     "1$smelting/smelt_emerald_ore_to_ingot"
     "1$smelting/smelt_endstone_bornite_ore_to_ingot"
     "1$smelting/smelt_endstone_chalcocite_ore_to_ingot"
     "1$smelting/smelt_endstone_chalcopyrite_ore_to_ingot"
     "1$smelting/smelt_endstone_copper_ore_to_ingot"
     "1$smelting/smelt_endstone_diamond_ore_to_ingot"
     "1$smelting/smelt_endstone_emerald_ore_to_ingot"
     "1$smelting/smelt_endstone_gold_ore_to_ingot"
     "1$smelting/smelt_endstone_lapis_ore_to_ingot"
     "1$smelting/smelt_endstone_malachite_ore_to_ingot"
     "1$smelting/smelt_endstone_tetrahedrite_ore_to_ingot"
     "1$smelting/smelt_gold_ore_to_ingot"
     "1$smelting/smelt_impure_dust_bornite_to_ingot"
     "1$smelting/smelt_impure_dust_chalcocite_to_ingot"
     "1$smelting/smelt_impure_dust_chalcopyrite_to_ingot"
     "1$smelting/smelt_impure_dust_copper_to_ingot"
     "1$smelting/smelt_impure_dust_gold_to_ingot"
     "1$smelting/smelt_impure_dust_malachite_to_ingot"
     "1$smelting/smelt_impure_dust_tetrahedrite_to_ingot"
     "1$smelting/smelt_lapis_ore_to_ingot"
     "1$smelting/smelt_malachite_ore_to_ingot"
     "1$smelting/smelt_netherrack_bornite_ore_to_ingot"
     "1$smelting/smelt_netherrack_chalcocite_ore_to_ingot"
     "1$smelting/smelt_netherrack_chalcopyrite_ore_to_ingot"
     "1$smelting/smelt_netherrack_copper_ore_to_ingot"
     "1$smelting/smelt_netherrack_diamond_ore_to_ingot"
     "1$smelting/smelt_netherrack_emerald_ore_to_ingot"
     "1$smelting/smelt_netherrack_gold_ore_to_ingot"
     "1$smelting/smelt_netherrack_lapis_ore_to_ingot"
     "1$smelting/smelt_netherrack_malachite_ore_to_ingot"
     "1$smelting/smelt_netherrack_tetrahedrite_ore_to_ingot"
     "1$smelting/smelt_pure_dust_bornite_to_ingot"
     "1$smelting/smelt_pure_dust_chalcocite_to_ingot"
     "1$smelting/smelt_pure_dust_chalcopyrite_to_ingot"
     "1$smelting/smelt_pure_dust_copper_to_ingot"
     "1$smelting/smelt_pure_dust_gold_to_ingot"
     "1$smelting/smelt_pure_dust_malachite_to_ingot"
     "1$smelting/smelt_pure_dust_tetrahedrite_to_ingot"
     "1$smelting/smelt_purified_ore_bornite_to_ingot"
     "1$smelting/smelt_purified_ore_chalcocite_to_ingot"
     "1$smelting/smelt_purified_ore_chalcopyrite_to_ingot"
     "1$smelting/smelt_purified_ore_copper_to_ingot"
     "1$smelting/smelt_purified_ore_gold_to_ingot"
     "1$smelting/smelt_purified_ore_malachite_to_ingot"
     "1$smelting/smelt_purified_ore_tetrahedrite_to_ingot"
     "1$smelting/smelt_raw_bornite_ore_to_ingot"
     "1$smelting/smelt_raw_chalcocite_ore_to_ingot"
     "1$smelting/smelt_raw_chalcopyrite_ore_to_ingot"
     "1$smelting/smelt_raw_diamond_ore_to_ingot"
     "1$smelting/smelt_raw_emerald_ore_to_ingot"
     "1$smelting/smelt_raw_lapis_ore_to_ingot"
     "1$smelting/smelt_raw_malachite_ore_to_ingot"
     "1$smelting/smelt_raw_tetrahedrite_ore_to_ingot"
     "1$smelting/smelt_refined_ore_bornite_to_ingot"
     "1$smelting/smelt_refined_ore_chalcocite_to_ingot"
     "1$smelting/smelt_refined_ore_chalcopyrite_to_ingot"
     "1$smelting/smelt_refined_ore_copper_to_ingot"
     "1$smelting/smelt_refined_ore_gold_to_ingot"
     "1$smelting/smelt_refined_ore_malachite_to_ingot"
     "1$smelting/smelt_refined_ore_tetrahedrite_to_ingot"
     "1$smelting/smelt_tetrahedrite_ore_to_ingot"
     "1$steam_boiler/charcoal_block"
     "1$steam_boiler/charcoal_dust"
     "1$steam_boiler/coal_dust"
   ]
 }

```


</details>

<details>
<summary>almostunified/iceandfire</summary>

```diff
 {
   type: "almostunified:client_recipe_tracker"
   namespace: "iceandfire"
   recipes: [
     "1$copper_nuggets_to_ingot"
     "1$furnace/copper_nugget"
     "1$furnace/copper_nugget_blasting"
     "1$furnace/sapphire"
     "1$furnace/sapphire_blasting"
     "1$furnace/silver_nugget"
     "1$furnace/silver_nugget_blasting"
+    "1$raw_silver_to_raw_silver_block"
     "1$sapphire_gem_to_sapphire_block"
     "1$silver_ingot_to_silver_block"
     "1$silver_nugget_to_silver_ingot"
     "3$copper_ingot_to_nuggets"
     "3$furnace/deepslate_silver_ingot"
     "3$furnace/deepslate_silver_ingot_blasting"
     "3$furnace/silver_ingot"
     "3$furnace/silver_ingot_blasting"
+    "3$raw_silver_block_to_raw_silver"
     "3$sapphire_block_to_sapphire_gem"
     "3$silver_block_to_silver_ingot"
+    "3$silver_ingot_from_blasting_raw_silver"
+    "3$silver_ingot_from_smelting_raw_silver"
     "3$silver_ingot_to_silver_nugget"
   ]
 }

```


</details>

<details>
<summary>almostunified/integrateddynamics</summary>

```diff
 {
   type: "almostunified:client_recipe_tracker"
   namespace: "integrateddynamics"
   recipes: [
     "1$mechanical_squeezer/ore/dust_coal"
+    "1$mechanical_squeezer/ore/dust_obsidian"
+    "1$mechanical_squeezer/ore/gem_diamond"
+    "1$mechanical_squeezer/ore/gem_emerald"
+    "1$mechanical_squeezer/ore/gem_lapis"
+    "1$mechanical_squeezer/ore/gold_nugget_blackstone"
+    "1$mechanical_squeezer/ore/raw_cobalt"
+    "1$mechanical_squeezer/ore/raw_copper"
+    "1$mechanical_squeezer/ore/raw_gold"
+    "1$mechanical_squeezer/ore/raw_iron"
+    "1$mechanical_squeezer/ore/raw_lead"
+    "1$mechanical_squeezer/ore/raw_nickel"
+    "1$mechanical_squeezer/ore/raw_platinum"
+    "1$mechanical_squeezer/ore/raw_silver"
+    "1$mechanical_squeezer/ore/raw_tin"
+    "1$mechanical_squeezer/ore/raw_zinc"
     "1$squeezer/ore/dust_coal"
+    "1$squeezer/ore/dust_obsidian"
+    "1$squeezer/ore/gem_diamond"
+    "1$squeezer/ore/gem_emerald"
+    "1$squeezer/ore/gem_lapis"
+    "1$squeezer/ore/gold_nugget_blackstone"
+    "1$squeezer/ore/raw_cobalt"
+    "1$squeezer/ore/raw_copper"
+    "1$squeezer/ore/raw_gold"
+    "1$squeezer/ore/raw_iron"
+    "1$squeezer/ore/raw_lead"
+    "1$squeezer/ore/raw_nickel"
+    "1$squeezer/ore/raw_platinum"
+    "1$squeezer/ore/raw_silver"
+    "1$squeezer/ore/raw_tin"
+    "1$squeezer/ore/raw_zinc"
   ]
 }

```


</details>

<details>
<summary>almostunified/minecraft</summary>

```diff
 {
   type: "almostunified:client_recipe_tracker"
   namespace: "minecraft"
   recipes: [
     "1$aluminum_ingot_from_smelting"
     "1$aluminum_ingot_from_smelting_deepslate"
     "1$blue_dye"
     "1$chain"
     "1$chromium_ingot_from_smelting"
     "1$chromium_ingot_from_smelting_deeplate"
     "1$copper_block"
     "1$copper_ingot_from_blasting_raw_copper"
     "1$copper_ingot_from_smelting_raw_copper"
     "1$copper_ingot_from_waxed_copper_block"
     "1$cut_copper"
     "1$cut_copper_from_copper_block_stonecutting"
     "1$cut_copper_slab_from_copper_block_stonecutting"
     "1$cut_copper_stairs_from_copper_block_stonecutting"
     "1$fire_charge"
+    "1$fluorite_ingot_from_smelting"
     "1$glistering_melon_slice"
     "1$gold_ingot_from_blasting_raw_gold"
     "1$gold_ingot_from_smelting_raw_gold"
     "1$golden_carrot"
+    "1$graphite_ingot_from_smelting"
     "1$iron_ingot_from_blasting_raw_iron"
     "1$iron_ingot_from_smelting_raw_iron"
     "1$large_boiler/charcoal"
     "1$large_boiler/coal"
     "1$large_boiler/coal_block"
     "1$manganese_ingot_from_smelting"
     "1$manganese_ingot_from_smelting_deepslate"
     "1$molybdenum_ingot_from_smelting"
     "1$molybdenum_ingot_from_smelting_deepslate"
     "1$netherite_axe_smithing"
     "1$netherite_block"
     "1$netherite_boots_smithing"
     "1$netherite_chestplate_smithing"
     "1$netherite_helmet_smithing"
     "1$netherite_hoe_smithing"
     "1$netherite_ingot_from_netherite_block"
     "1$netherite_leggings_smithing"
     "1$netherite_pickaxe_smithing"
     "1$netherite_shovel_smithing"
     "1$netherite_sword_smithing"
     "1$nickel_ingot_from_smelting"
     "1$nickel_ingot_from_smelting_deepslate"
     "1$niob_ingot_from_smelting"
     "1$niob_ingot_from_smelting_deepslate"
     "1$raw_copper"
     "1$raw_copper_block"
     "1$raw_gold"
     "1$raw_gold_block"
     "1$raw_iron"
     "1$raw_iron_block"
     "1$soul_lantern"
     "1$steam_boiler/charcoal"
     "1$steam_boiler/coal"
     "1$steam_boiler/coal_block"
     "1$titanium_ingot_from_smelting"
     "1$titanium_ingot_from_smelting_deepslate"
     "1$uranium_ingot_from_smelting"
     "1$uranium_ingot_from_smelting_deepslate"
     "1$waxed_copper_block_from_honeycomb"
     "3$coal_from_blasting_coal_ore"
     "3$coal_from_blasting_deepslate_coal_ore"
     "3$coal_from_smelting_coal_ore"
     "3$coal_from_smelting_deepslate_coal_ore"
     "3$copper_ingot"
     "3$copper_ingot_from_blasting_copper_ore"
     "3$copper_ingot_from_blasting_deepslate_copper_ore"
     "3$copper_ingot_from_smelting_copper_ore"
     "3$copper_ingot_from_smelting_deepslate_copper_ore"
     "3$diamond_from_blasting_deepslate_diamond_ore"
     "3$diamond_from_blasting_diamond_ore"
     "3$diamond_from_smelting_deepslate_diamond_ore"
     "3$diamond_from_smelting_diamond_ore"
     "3$emerald_from_blasting_deepslate_emerald_ore"
     "3$emerald_from_blasting_emerald_ore"
     "3$emerald_from_smelting_deepslate_emerald_ore"
     "3$emerald_from_smelting_emerald_ore"
     "3$gold_ingot_from_blasting_deepslate_gold_ore"
     "3$gold_ingot_from_blasting_gold_ore"
     "3$gold_ingot_from_blasting_nether_gold_ore"
     "3$gold_ingot_from_smelting_deepslate_gold_ore"
     "3$gold_ingot_from_smelting_gold_ore"
     "3$gold_ingot_from_smelting_nether_gold_ore"
     "3$iron_ingot_from_blasting_deepslate_iron_ore"
     "3$iron_ingot_from_blasting_iron_ore"
     "3$iron_ingot_from_smelting_deepslate_iron_ore"
     "3$iron_ingot_from_smelting_iron_ore"
     "3$lapis_lazuli_from_blasting_deepslate_lapis_ore"
     "3$lapis_lazuli_from_blasting_lapis_ore"
     "3$lapis_lazuli_from_smelting_deepslate_lapis_ore"
     "3$lapis_lazuli_from_smelting_lapis_ore"
     "3$lead_ingot_from_blasting_deepslate_lead_ore"
     "3$lead_ingot_from_blasting_lead_ore"
     "3$lead_ingot_from_blasting_lead_raw"
     "3$lead_ingot_from_smelting_deepslate_lead_ore"
     "3$lead_ingot_from_smelting_lead_ore"
     "3$lead_ingot_from_smelting_lead_raw"
     "3$nickel_ingot_from_blasting_deepslate_nickel_ore"
     "3$nickel_ingot_from_blasting_nickel_ore"
     "3$nickel_ingot_from_blasting_nickel_raw"
     "3$nickel_ingot_from_smelting_deepslate_nickel_ore"
     "3$nickel_ingot_from_smelting_nickel_ore"
     "3$nickel_ingot_from_smelting_nickel_raw"
     "3$silver_ingot_from_blasting_deepslate_silver_ore"
     "3$silver_ingot_from_blasting_silver_ore"
     "3$silver_ingot_from_blasting_silver_raw"
     "3$silver_ingot_from_smelting_deepslate_silver_ore"
     "3$silver_ingot_from_smelting_silver_ore"
     "3$silver_ingot_from_smelting_silver_raw"
     "3$tin_ingot_from_blasting_deepslate_tin_ore"
     "3$tin_ingot_from_blasting_tin_ore"
     "3$tin_ingot_from_blasting_tin_raw"
     "3$tin_ingot_from_smelting_deepslate_tin_ore"
     "3$tin_ingot_from_smelting_tin_ore"
     "3$tin_ingot_from_smelting_tin_raw"
     "3$zinc_ingot_from_blasting_deepslate_zinc_ore"
     "3$zinc_ingot_from_blasting_zinc_ore"
     "3$zinc_ingot_from_blasting_zinc_raw"
     "3$zinc_ingot_from_smelting_deepslate_zinc_ore"
     "3$zinc_ingot_from_smelting_zinc_ore"
     "3$zinc_ingot_from_smelting_zinc_raw"
   ]
 }

```


</details>

<details>
<summary>almostunified/railcraft</summary>

```diff
 {
   type: "almostunified:client_recipe_tracker"
   namespace: "railcraft"
   recipes: [
     "1$analog_signal_controller_box"
     "1$blast_furnace/blasting_bucket"
     "1$blast_furnace/blasting_iron_axe"
     "1$blast_furnace/blasting_iron_boots"
     "1$blast_furnace/blasting_iron_chestplate"
     "1$blast_furnace/blasting_iron_crowbar"
     "1$blast_furnace/blasting_iron_door"
     "1$blast_furnace/blasting_iron_helmet"
     "1$blast_furnace/blasting_iron_hoe"
     "1$blast_furnace/blasting_iron_horse_armor"
     "1$blast_furnace/blasting_iron_ingot"
     "1$blast_furnace/blasting_iron_leggings"
     "1$blast_furnace/blasting_iron_pickaxe"
     "1$blast_furnace/blasting_iron_shovel"
     "1$blast_furnace/blasting_iron_sword"
     "1$blast_furnace/blasting_iron_trapdoor"
     "1$blast_furnace/blasting_shears"
     "1$blast_furnace/blasting_steel_axe"
     "1$blast_furnace/blasting_steel_block"
     "1$blast_furnace/blasting_steel_boots"
     "1$blast_furnace/blasting_steel_chestplate"
     "1$blast_furnace/blasting_steel_helmet"
     "1$blast_furnace/blasting_steel_hoe"
     "1$blast_furnace/blasting_steel_leggings"
     "1$blast_furnace/blasting_steel_pickaxe"
     "1$blast_furnace/blasting_steel_shears"
     "1$blast_furnace/blasting_steel_sword"
     "1$block_signal"
     "1$brass_ingot_crafted_with_ingots"
     "1$bronze_gear"
     "1$bronze_ingot_crafted_with_ingots"
     "1$coke_oven/coal_coke"
     "1$coke_oven/coal_coke_block"
     "1$crusher"
     "1$crusher/crushing_charcoal"
     "1$crusher/crushing_coal"
     "1$crusher/crushing_coal_block"
-    "1$crusher/crushing_raw_copper_block"
+    "1$crusher/crushing_lapis_lazuli"
+    "1$crusher/crushing_netherite_ingot"
     "1$crusher/crushing_raw_gold_block"
     "1$crusher/crushing_raw_iron_block"
     "1$distant_signal"
     "1$dual_block_signal"
     "1$dual_distant_signal"
     "1$dual_token_signal"
     "1$invar_gear"
     "1$invar_ingot_crafted_with_ingots"
     "1$iron_gear"
     "1$logbook"
     "1$rolling/brass_plate"
     "1$rolling/bronze_plate"
     "1$rolling/carbon_electrode"
     "1$rolling/copper_plate"
     "1$rolling/gold_plate"
     "1$rolling/invar_plate"
     "1$rolling/iron_plate"
     "1$rolling/lead_plate"
     "1$rolling/nickel_plate"
     "1$rolling/silver_plate"
     "1$rolling/steel_plate"
     "1$rolling/tin_plate"
     "1$rolling/zinc_plate"
     "1$signal_block_relay_box"
     "1$signal_capacitor_box"
     "1$signal_controller_box"
     "1$signal_interlock_box"
     "1$signal_receiver_box"
     "1$signal_sequencer_box"
     "1$steel_gear"
     "1$switch_track_lever"
     "1$switch_track_motor"
     "1$token_signal"
+    "1$token_signal_box"
     "3$brass_block_from_brass_ingot"
     "3$brass_ingot"
     "3$brass_ingot_from_brass_nugget"
     "3$brass_nugget"
     "3$bronze_block_from_bronze_ingot"
     "3$bronze_ingot"
     "3$bronze_ingot_from_bronze_nugget"
     "3$bronze_nugget"
     "3$invar_block_from_invar_ingot"
     "3$invar_ingot"
     "3$invar_ingot_from_invar_nugget"
     "3$invar_nugget"
     "3$lead_block_from_lead_ingot"
     "3$lead_ingot"
     "3$lead_ingot_from_lead_nugget"
     "3$lead_nugget"
     "3$nickel_block_from_nickel_ingot"
     "3$nickel_ingot"
     "3$nickel_ingot_from_nickel_nugget"
     "3$nickel_nugget"
     "3$silver_block_from_silver_ingot"
     "3$silver_ingot"
     "3$silver_ingot_from_silver_nugget"
     "3$silver_nugget"
     "3$steel_block_from_steel_ingot"
     "3$steel_ingot"
     "3$steel_ingot_from_steel_nugget"
     "3$steel_nugget"
     "3$tin_block_from_tin_ingot"
     "3$tin_ingot"
     "3$tin_ingot_from_tin_nugget"
     "3$tin_nugget"
     "3$zinc_block_from_zinc_ingot"
     "3$zinc_ingot"
     "3$zinc_ingot_from_zinc_nugget"
     "3$zinc_nugget"
   ]
 }

```


</details>

<details>
<summary>almostunified/tfc</summary>

```diff
 {
   type: "almostunified:client_recipe_tracker"
   namespace: "tfc"
   recipes: [
     "1$anvil/bismuth_bronze_rod"
     "1$anvil/bismuth_bronze_sheet"
     "1$anvil/bismuth_rod"
     "1$anvil/bismuth_sheet"
     "1$anvil/black_bronze_rod"
     "1$anvil/black_bronze_sheet"
     "1$anvil/black_steel_ingot"
     "1$anvil/black_steel_rod"
     "1$anvil/black_steel_sheet"
     "1$anvil/blue_steel_ingot"
     "1$anvil/blue_steel_rod"
     "1$anvil/blue_steel_sheet"
     "1$anvil/brass_rod"
     "1$anvil/brass_sheet"
     "1$anvil/bronze_rod"
     "1$anvil/bronze_sheet"
     "1$anvil/copper_rod"
     "1$anvil/copper_sheet"
     "1$anvil/gold_rod"
     "1$anvil/gold_sheet"
     "1$anvil/invar_plate"
     "1$anvil/nickel_rod"
     "1$anvil/nickel_sheet"
     "1$anvil/red_steel_ingot"
     "1$anvil/red_steel_rod"
     "1$anvil/red_steel_sheet"
     "1$anvil/rose_gold_rod"
     "1$anvil/rose_gold_sheet"
     "1$anvil/silver_rod"
     "1$anvil/silver_sheet"
     "1$anvil/steel_ingot"
     "1$anvil/steel_rod"
     "1$anvil/steel_sheet"
     "1$anvil/sterling_silver_rod"
     "1$anvil/sterling_silver_sheet"
     "1$anvil/tin_rod"
     "1$anvil/tin_sheet"
     "1$anvil/wrought_iron_from_bloom"
     "1$anvil/wrought_iron_rod"
     "1$anvil/wrought_iron_sheet"
     "1$anvil/zinc_rod"
     "1$anvil/zinc_sheet"
+    "1$bloomery/raw_iron_bloom"
     "1$casting/bismuth_bronze_fire_ingot"
     "1$casting/bismuth_bronze_ingot"
     "1$casting/bismuth_fire_ingot"
     "1$casting/bismuth_ingot"
     "1$casting/black_bronze_fire_ingot"
     "1$casting/black_bronze_ingot"
     "1$casting/black_steel_fire_ingot"
     "1$casting/black_steel_ingot"
     "1$casting/blue_steel_fire_ingot"
     "1$casting/blue_steel_ingot"
     "1$casting/brass_fire_ingot"
     "1$casting/brass_ingot"
     "1$casting/bronze_fire_ingot"
     "1$casting/bronze_ingot"
     "1$casting/nickel_fire_ingot"
     "1$casting/nickel_ingot"
     "1$casting/red_steel_fire_ingot"
     "1$casting/red_steel_ingot"
     "1$casting/rose_gold_fire_ingot"
     "1$casting/rose_gold_ingot"
     "1$casting/silver_fire_ingot"
     "1$casting/silver_ingot"
     "1$casting/steel_fire_ingot"
     "1$casting/steel_ingot"
     "1$casting/sterling_silver_fire_ingot"
     "1$casting/sterling_silver_ingot"
     "1$casting/tin_fire_ingot"
     "1$casting/tin_ingot"
     "1$casting/wrought_iron_fire_ingot"
     "1$casting/wrought_iron_ingot"
     "1$casting/zinc_fire_ingot"
     "1$casting/zinc_ingot"
     "1$crafting/blast_furnace"
     "1$crafting/gunpowder"
     "1$crafting/gunpowder_graphite"
     "1$crafting/vanilla/lapis_block"
     "1$heating/metal/aluminium_ingot"
     "1$heating/metal/bismuth_bronze_double_ingot"
     "1$heating/metal/bismuth_bronze_double_sheet"
     "1$heating/metal/bismuth_bronze_ingot"
     "1$heating/metal/bismuth_bronze_rod"
     "1$heating/metal/bismuth_bronze_sheet"
     "1$heating/metal/bismuth_double_ingot"
     "1$heating/metal/bismuth_double_sheet"
     "1$heating/metal/bismuth_ingot"
     "1$heating/metal/bismuth_rod"
     "1$heating/metal/bismuth_sheet"
     "1$heating/metal/black_bronze_double_ingot"
     "1$heating/metal/black_bronze_double_sheet"
     "1$heating/metal/black_bronze_ingot"
     "1$heating/metal/black_bronze_rod"
     "1$heating/metal/black_bronze_sheet"
     "1$heating/metal/black_steel_double_ingot"
     "1$heating/metal/black_steel_double_sheet"
     "1$heating/metal/black_steel_ingot"
     "1$heating/metal/black_steel_rod"
     "1$heating/metal/black_steel_sheet"
     "1$heating/metal/blue_steel_double_ingot"
     "1$heating/metal/blue_steel_double_sheet"
     "1$heating/metal/blue_steel_ingot"
     "1$heating/metal/blue_steel_rod"
     "1$heating/metal/blue_steel_sheet"
     "1$heating/metal/brass_double_ingot"
     "1$heating/metal/brass_double_sheet"
     "1$heating/metal/brass_ingot"
     "1$heating/metal/brass_rod"
     "1$heating/metal/brass_sheet"
     "1$heating/metal/bronze_double_ingot"
     "1$heating/metal/bronze_double_sheet"
     "1$heating/metal/bronze_ingot"
     "1$heating/metal/bronze_rod"
     "1$heating/metal/bronze_sheet"
     "1$heating/metal/cobalt_ingot"
     "1$heating/metal/copper_double_ingot"
     "1$heating/metal/copper_double_sheet"
     "1$heating/metal/copper_ingot"
     "1$heating/metal/copper_rod"
     "1$heating/metal/copper_sheet"
     "1$heating/metal/electrum_ingot"
     "1$heating/metal/gold_double_ingot"
     "1$heating/metal/gold_double_sheet"
     "1$heating/metal/gold_ingot"
     "1$heating/metal/gold_rod"
     "1$heating/metal/gold_sheet"
     "1$heating/metal/invar_double_ingot"
     "1$heating/metal/invar_ingot"
     "1$heating/metal/lead_ingot"
     "1$heating/metal/manganese_ingot"
     "1$heating/metal/nickel_double_ingot"
     "1$heating/metal/nickel_double_sheet"
     "1$heating/metal/nickel_ingot"
     "1$heating/metal/nickel_rod"
     "1$heating/metal/nickel_sheet"
     "1$heating/metal/raw_lead"
     "1$heating/metal/raw_silver"
     "1$heating/metal/raw_thorium"
     "1$heating/metal/raw_tin"
     "1$heating/metal/red_steel_double_ingot"
     "1$heating/metal/red_steel_double_sheet"
     "1$heating/metal/red_steel_ingot"
     "1$heating/metal/red_steel_rod"
     "1$heating/metal/red_steel_sheet"
     "1$heating/metal/rose_gold_double_ingot"
     "1$heating/metal/rose_gold_double_sheet"
     "1$heating/metal/rose_gold_ingot"
     "1$heating/metal/rose_gold_rod"
     "1$heating/metal/rose_gold_sheet"
     "1$heating/metal/silver_double_ingot"
     "1$heating/metal/silver_double_sheet"
     "1$heating/metal/silver_ingot"
     "1$heating/metal/silver_rod"
     "1$heating/metal/silver_sheet"
     "1$heating/metal/steel_double_ingot"
     "1$heating/metal/steel_double_sheet"
     "1$heating/metal/steel_ingot"
     "1$heating/metal/steel_rod"
     "1$heating/metal/steel_sheet"
     "1$heating/metal/sterling_silver_double_ingot"
     "1$heating/metal/sterling_silver_double_sheet"
     "1$heating/metal/sterling_silver_ingot"
     "1$heating/metal/sterling_silver_rod"
     "1$heating/metal/sterling_silver_sheet"
     "1$heating/metal/tin_double_ingot"
     "1$heating/metal/tin_double_sheet"
     "1$heating/metal/tin_ingot"
     "1$heating/metal/tin_rod"
     "1$heating/metal/tin_sheet"
     "1$heating/metal/uranium_ingot"
     "1$heating/metal/wrought_iron_double_ingot"
     "1$heating/metal/wrought_iron_double_sheet"
     "1$heating/metal/wrought_iron_ingot"
     "1$heating/metal/wrought_iron_rod"
     "1$heating/metal/wrought_iron_sheet"
     "1$heating/metal/zinc_double_ingot"
     "1$heating/metal/zinc_double_sheet"
     "1$heating/metal/zinc_ingot"
     "1$heating/metal/zinc_rod"
     "1$heating/metal/zinc_sheet"
     "1$quern/charcoal"
     "1$quern/diamond"
     "1$quern/sulfur"
+    "1$welding/bismuth_bronze_boots"
+    "1$welding/bismuth_bronze_chestplate"
     "1$welding/bismuth_bronze_double_sheet"
+    "1$welding/bismuth_bronze_greaves"
+    "1$welding/bismuth_bronze_helmet"
     "1$welding/bismuth_double_sheet"
+    "1$welding/black_bronze_boots"
+    "1$welding/black_bronze_chestplate"
     "1$welding/black_bronze_double_sheet"
+    "1$welding/black_bronze_greaves"
+    "1$welding/black_bronze_helmet"
+    "1$welding/black_steel_boots"
+    "1$welding/black_steel_chestplate"
     "1$welding/black_steel_double_sheet"
+    "1$welding/black_steel_greaves"
+    "1$welding/black_steel_helmet"
+    "1$welding/blue_steel_boots"
+    "1$welding/blue_steel_chestplate"
     "1$welding/blue_steel_double_sheet"
+    "1$welding/blue_steel_greaves"
+    "1$welding/blue_steel_helmet"
     "1$welding/brass_double_sheet"
+    "1$welding/bronze_boots"
+    "1$welding/bronze_chestplate"
     "1$welding/bronze_double_sheet"
+    "1$welding/bronze_greaves"
+    "1$welding/bronze_helmet"
+    "1$welding/copper_boots"
+    "1$welding/copper_chestplate"
     "1$welding/copper_double_sheet"
+    "1$welding/copper_greaves"
+    "1$welding/copper_helmet"
     "1$welding/gold_double_sheet"
+    "1$welding/invar_double_ingot"
+    "1$welding/invar_double_plate"
     "1$welding/nickel_double_sheet"
+    "1$welding/red_steel_boots"
+    "1$welding/red_steel_chestplate"
     "1$welding/red_steel_double_sheet"
+    "1$welding/red_steel_greaves"
+    "1$welding/red_steel_helmet"
     "1$welding/rose_gold_double_sheet"
     "1$welding/silver_double_sheet"
+    "1$welding/steel_boots"
+    "1$welding/steel_chestplate"
     "1$welding/steel_double_sheet"
+    "1$welding/steel_greaves"
+    "1$welding/steel_helmet"
     "1$welding/sterling_silver_double_sheet"
     "1$welding/tin_double_sheet"
+    "1$welding/wrought_iron_boots"
+    "1$welding/wrought_iron_chestplate"
     "1$welding/wrought_iron_double_sheet"
+    "1$welding/wrought_iron_greaves"
+    "1$welding/wrought_iron_helmet"
     "1$welding/zinc_double_sheet"
     "3$quern/diamond_cut"
     "3$quern/emerald_cut"
     "3$quern/graphite"
     "3$quern/graphite_from_gt"
     "3$quern/lapis_lazuli_cut"
   ]
 }

```


</details>

<details>
<summary>almostunified/thoriumreactors</summary>

```diff
 {
   type: "almostunified:client_recipe_tracker"
   namespace: "thoriumreactors"
   recipes: [
     "1$aluminum_block_craft_from_ingot"
-    "1$aluminum_ingot_craft_from_block"
     "1$aluminum_ingot_craft_from_nugget"
     "1$chromium_block_craft_from_ingot"
     "1$chromium_ingot_craft_from_block"
     "1$chromium_ingot_craft_from_nugget"
     "1$chromium_nugget_craft_from_ingot"
     "1$cobalt_block_craft_from_ingot"
     "1$cobalt_ingot_craft_from_block"
     "1$cobalt_ingot_craft_from_nugget"
     "1$cobalt_nugget_craft_from_ingot"
     "1$factory_block"
     "1$fluorite_block_craft_from_ingot"
+    "1$fluorite_ingot_craft_from_block"
     "1$fluorite_ingot_craft_from_nugget"
     "1$fluorite_nugget_craft_from_ingot"
     "1$graphite_block_craft_from_ingot"
     "1$graphite_ingot_craft_from_nugget"
     "1$graphite_nugget_craft_from_ingot"
     "1$manganese_block_craft_from_ingot"
     "1$manganese_ingot_craft_from_block"
     "1$manganese_ingot_craft_from_nugget"
     "1$manganese_nugget_craft_from_ingot"
     "1$molybdenum_block_craft_from_ingot"
     "1$molybdenum_ingot_craft_from_block"
     "1$molybdenum_ingot_craft_from_nugget"
     "1$molybdenum_nugget_craft_from_ingot"
     "1$nickel_block_craft_from_ingot"
-    "1$nickel_ingot_craft_from_block"
     "1$nickel_ingot_craft_from_nugget"
     "1$niob_block_craft_from_ingot"
     "1$niob_ingot_craft_from_block"
     "1$niob_ingot_craft_from_nugget"
     "1$niob_nugget_craft_from_ingot"
     "1$steel_block_craft_from_ingot"
-    "1$steel_ingot_craft_from_block"
     "1$steel_ingot_craft_from_nugget"
     "1$thorium"
     "1$thorium_block"
-    "1$thorium_crafting/blast_furnace"
-    "1$thorium_crafting/blasted_iron_chest"
-    "1$thorium_crafting/concentrator_block"
-    "1$thorium_crafting/configurator"
-    "1$thorium_crafting/crystallizer"
-    "1$thorium_crafting/decomposer_block"
-    "1$thorium_crafting/electrolytic_salt_separator"
-    "1$thorium_crafting/electromagnetic_coil"
-    "1$thorium_crafting/factory_block"
-    "1$thorium_crafting/fluid_centrifuge"
-    "1$thorium_crafting/fluid_enricher"
-    "1$thorium_crafting/fluid_evaporation"
     "1$thorium_crafting/generator"
-    "1$thorium_crafting/generic_energy_tank"
-    "1$thorium_crafting/generic_fluid_tank"
-    "1$thorium_crafting/graphite_tube"
-    "1$thorium_crafting/machine_casing"
-    "1$thorium_crafting/module_empty"
-    "1$thorium_crafting/module_energy"
-    "1$thorium_crafting/module_io"
-    "1$thorium_crafting/module_processing"
-    "1$thorium_crafting/module_sensor"
-    "1$thorium_crafting/module_storage"
-    "1$thorium_crafting/module_tank"
-    "1$thorium_crafting/progressive_energy_tank"
-    "1$thorium_crafting/progressive_fluid_tank"
-    "1$thorium_crafting/reactor_casing"
-    "1$thorium_crafting/reactor_control_rod"
-    "1$thorium_crafting/reactor_controller"
-    "1$thorium_crafting/reactor_core"
-    "1$thorium_crafting/reactor_glass"
-    "1$thorium_crafting/reactor_valve"
-    "1$thorium_crafting/redstone_processor"
-    "1$thorium_crafting/salt_melter"
-    "1$thorium_crafting/simple_energy_tank"
-    "1$thorium_crafting/simple_fluid_tank"
-    "1$thorium_crafting/steel_chest"
-    "1$thorium_crafting/thermal_conductor"
-    "1$thorium_crafting/thermal_heat_controller"
-    "1$thorium_crafting/thermal_heat_valve"
-    "1$thorium_crafting/thermal_heatsink"
     "1$thorium_crafting/thorium_chest"
-    "1$thorium_crafting/turbine_blade"
-    "1$thorium_crafting/turbine_casing"
-    "1$thorium_crafting/turbine_constroller"
-    "1$thorium_crafting/turbine_glass"
-    "1$thorium_crafting/turbine_power_port"
-    "1$thorium_crafting/turbine_rotation_mount"
-    "1$thorium_crafting/turbine_rotor"
-    "1$thorium_crafting/turbine_valve"
-    "1$thorium_crafting/turbine_vent"
-    "1$thorium_crafting/uranium_oxidizer_block"
-    "1$thorium_crafting/water_source_block"
     "1$thorium_crafting_table"
     "1$titanium_block_craft_from_ingot"
     "1$titanium_ingot_craft_from_block"
     "1$titanium_ingot_craft_from_nugget"
     "1$titanium_nugget_craft_from_ingot"
     "1$uranium_block_craft_from_ingot"
-    "1$uranium_ingot_craft_from_block"
     "1$uranium_ingot_craft_from_nugget"
+    "3$aluminum_ingot_craft_from_block"
     "3$aluminum_nugget_craft_from_ingot"
+    "3$nickel_ingot_craft_from_block"
     "3$nickel_nugget_craft_from_ingot"
+    "3$steel_ingot_craft_from_block"
     "3$steel_nugget_craft_from_ingot"
+    "3$uranium_ingot_craft_from_block"
     "3$uranium_nugget_craft_from_ingot"
   ]
 }

```


</details>

<details>
<summary>computercraft/cable</summary>

```diff
 {
   type: "minecraft:crafting_shaped"
   category: "redstone"
   key: {
     #: {
       tag: "forge:stone"
     }
     R: {
-      tag: "forge:dusts/redstone"
+      item: "gtceu:basic_electronic_circuit"
     }
   }
   pattern: [
     " # "
     "#R#"
     " # "
   ]
   result: {
     count: 6
     item: "computercraft:cable"
   }
   show_notification: true
 }

```


</details>

<details>
<summary>computercraft/disk_drive</summary>

```diff
 {
   type: "minecraft:crafting_shaped"
   category: "redstone"
   key: {
     #: {
       tag: "forge:stone"
     }
     R: {
-      tag: "forge:dusts/redstone"
+      item: "gtceu:basic_electronic_circuit"
     }
   }
   pattern: [
     "###"
     "#R#"
     "#R#"
   ]
   result: {
     item: "computercraft:disk_drive"
   }
   show_notification: true
 }

```


</details>

<details>
<summary>computercraft/printer</summary>

```diff
 {
   type: "minecraft:crafting_shaped"
   category: "redstone"
   key: {
     #: {
       tag: "forge:stone"
     }
     D: {
       tag: "forge:dyes"
     }
     R: {
-      tag: "forge:dusts/redstone"
+      item: "gtceu:basic_electronic_circuit"
     }
   }
   pattern: [
     "###"
     "#R#"
     "#D#"
   ]
   result: {
     item: "computercraft:printer"
   }
   show_notification: true
 }

```


</details>

<details>
<summary>computercraft/speaker</summary>

```diff
 {
   type: "minecraft:crafting_shaped"
   category: "redstone"
   key: {
     #: {
       tag: "forge:stone"
     }
     N: {
       item: "minecraft:note_block"
     }
     R: {
-      tag: "forge:dusts/redstone"
+      item: "gtceu:basic_electronic_circuit"
     }
   }
   pattern: [
     "###"
     "#N#"
     "#R#"
   ]
   result: {
     item: "computercraft:speaker"
   }
   show_notification: true
 }

```


</details>

<details>
<summary>computercraft/wired_modem</summary>

```diff
 {
   type: "minecraft:crafting_shaped"
   category: "redstone"
   key: {
     #: {
       tag: "forge:stone"
     }
     R: {
-      tag: "forge:dusts/redstone"
+      item: "gtceu:basic_electronic_circuit"
     }
   }
   pattern: [
     "###"
     "#R#"
     "###"
   ]
   result: {
     item: "computercraft:wired_modem"
   }
   show_notification: true
 }

```


</details>

<details>
<summary>firmalife/welding/chromium_double_ingot</summary>

```diff
 {
   __comment__: "This file was automatically created by mcresources"
   type: "tfc:welding"
   first_input: {
-    item: "firmalife:metal/ingot/chromium"
+    tag: "forge:ingots/chromium"
   }
   second_input: {
-    item: "firmalife:metal/ingot/chromium"
+    tag: "forge:ingots/chromium"
   }
   tier: 3
   result: {
     item: "firmalife:metal/double_ingot/chromium"
   }
 }

```


</details>

<details>
<summary>firmalife/welding/chromium_double_sheet</summary>

```diff
 {
   __comment__: "This file was automatically created by mcresources"
   type: "tfc:welding"
   first_input: {
-    item: "firmalife:metal/sheet/chromium"
+    tag: "forge:sheets/chromium"
   }
   second_input: {
-    item: "firmalife:metal/sheet/chromium"
+    tag: "forge:sheets/chromium"
   }
   tier: 3
   result: {
     item: "firmalife:metal/double_sheet/chromium"
   }
 }

```


</details>

<details>
<summary>firmalife/welding/stainless_steel_double_ingot</summary>

```diff
 {
   __comment__: "This file was automatically created by mcresources"
   type: "tfc:welding"
   first_input: {
-    item: "firmalife:metal/ingot/stainless_steel"
+    tag: "forge:ingots/stainless_steel"
   }
   second_input: {
-    item: "firmalife:metal/ingot/stainless_steel"
+    tag: "forge:ingots/stainless_steel"
   }
   tier: 3
   result: {
     item: "firmalife:metal/double_ingot/stainless_steel"
   }
 }

```


</details>

<details>
<summary>firmalife/welding/stainless_steel_double_sheet</summary>

```diff
 {
   __comment__: "This file was automatically created by mcresources"
   type: "tfc:welding"
   first_input: {
-    item: "firmalife:metal/sheet/stainless_steel"
+    tag: "forge:sheets/stainless_steel"
   }
   second_input: {
-    item: "firmalife:metal/sheet/stainless_steel"
+    tag: "forge:sheets/stainless_steel"
   }
   tier: 3
   result: {
     item: "firmalife:metal/double_sheet/stainless_steel"
   }
 }

```


</details>

<details>
<summary>gtceu/alloy_smelter/vanilla_iron</summary>

```diff
 {
   type: "gtceu:alloy_smelter"
-  duration: 750
+  duration: 250
   inputs: {
     item: [
       {
         content: {
           type: "gtceu:sized"
           count: 1
           ingredient: {
             tag: "forge:ingots/cast_iron"
           }
         }
         chance: 1
         tierChanceBoost: 0
       }
       {
         content: {
           type: "gtceu:sized"
           count: 1
           ingredient: {
             item: "tfc:powder/lime"
           }
         }
         chance: 1
         tierChanceBoost: 0
       }
     ]
   }
   tickInputs: {
     eu: [
       {
         content: 30
         chance: 1
         tierChanceBoost: 0
       }
     ]
   }
   outputs: {
     item: [
       {
         content: {
           type: "gtceu:sized"
           count: 1
           ingredient: {
             item: "minecraft:iron_ingot"
           }
         }
         chance: 1
         tierChanceBoost: 0
       }
     ]
   }
 }

```


</details>

<details>
<summary>gtceu/arc_furnace/arc_hv_chemical_reactor</summary>

```diff
 {
   type: "gtceu:arc_furnace"
-  duration: 1262
+  duration: 1121
   inputs: {
     item: [
       {
         content: {
           type: "gtceu:sized"
           count: 1
           ingredient: {
             item: "gtceu:hv_chemical_reactor"
           }
         }
         chance: 1
         tierChanceBoost: 0
       }
     ]
     fluid: [
       {
         content: {
-          amount: 1262
+          amount: 1121
           value: [
             {
               tag: "forge:oxygen"
             }
           ]
         }
         chance: 1
         tierChanceBoost: 0
       }
     ]
   }
   outputs: {
     item: [
       {
         content: {
           type: "gtceu:sized"
           count: 40
           ingredient: {
             item: "gtceu:steel_nugget"
           }
         }
         chance: 1
         tierChanceBoost: 0
       }
       {
         content: {
           type: "gtceu:sized"
           count: 4
           ingredient: {
             item: "gtceu:electrum_ingot"
           }
         }
         chance: 1
         tierChanceBoost: 0
       }
       {
         content: {
           type: "gtceu:sized"
           count: 2
           ingredient: {
             item: "gtceu:silver_ingot"
           }
         }
         chance: 1
         tierChanceBoost: 0
       }
       {
         content: {
           type: "gtceu:sized"
           count: 1
           ingredient: {
-            item: "tfc:metal/ingot/gold"
+            item: "firmalife:metal/ingot/stainless_steel"
           }
         }
         chance: 1
         tierChanceBoost: 0
       }
     ]
   }
   tickInputs: {
     eu: [
       {
         content: 30
         chance: 1
         tierChanceBoost: 0
       }
     ]
   }
   tickOutputs: {
   }
 }

```


</details>

<details>
<summary>gtceu/arc_furnace/arc_hv_ore_washer</summary>

```diff
 {
   type: "gtceu:arc_furnace"
-  duration: 1462
+  duration: 1321
   inputs: {
     item: [
       {
         content: {
           type: "gtceu:sized"
           count: 1
           ingredient: {
             item: "gtceu:hv_ore_washer"
           }
         }
         chance: 1
         tierChanceBoost: 0
       }
     ]
     fluid: [
       {
         content: {
-          amount: 1462
+          amount: 1321
           value: [
             {
               tag: "forge:oxygen"
             }
           ]
         }
         chance: 1
         tierChanceBoost: 0
       }
     ]
   }
   outputs: {
     item: [
       {
         content: {
           type: "gtceu:sized"
           count: 8
           ingredient: {
             item: "gtceu:steel_ingot"
           }
         }
         chance: 1
         tierChanceBoost: 0
       }
       {
         content: {
           type: "gtceu:sized"
           count: 4
           ingredient: {
             item: "gtceu:electrum_ingot"
           }
         }
         chance: 1
         tierChanceBoost: 0
       }
       {
         content: {
           type: "gtceu:sized"
           count: 2
           ingredient: {
             item: "gtceu:silver_ingot"
           }
         }
         chance: 1
         tierChanceBoost: 0
       }
       {
         content: {
           type: "gtceu:sized"
           count: 1
           ingredient: {
-            item: "tfc:metal/ingot/gold"
+            item: "firmalife:metal/ingot/stainless_steel"
           }
         }
         chance: 1
         tierChanceBoost: 0
       }
     ]
   }
   tickInputs: {
     eu: [
       {
         content: 30
         chance: 1
         tierChanceBoost: 0
       }
     ]
   }
   tickOutputs: {
   }
 }

```


</details>

<details>
<summary>gtceu/arc_furnace/arc_iv_centrifuge</summary>

```diff
 {
   type: "gtceu:arc_furnace"
-  duration: 1261
+  duration: 1210
   inputs: {
     item: [
       {
         content: {
           type: "gtceu:sized"
           count: 1
           ingredient: {
             item: "gtceu:iv_centrifuge"
           }
         }
         chance: 1
         tierChanceBoost: 0
       }
     ]
     fluid: [
       {
         content: {
-          amount: 1261
+          amount: 1210
           value: [
             {
               tag: "forge:oxygen"
             }
           ]
         }
         chance: 1
         tierChanceBoost: 0
       }
     ]
   }
   outputs: {
     item: [
       {
         content: {
           type: "gtceu:sized"
           count: 8
           ingredient: {
             item: "gtceu:graphene_ingot"
           }
         }
         chance: 1
         tierChanceBoost: 0
       }
       {
         content: {
           type: "gtceu:sized"
           count: 4
           ingredient: {
             item: "gtceu:tungsten_ingot"
           }
         }
         chance: 1
         tierChanceBoost: 0
       }
       {
         content: {
           type: "gtceu:sized"
           count: 2
           ingredient: {
             item: "gtceu:tungsten_steel_ingot"
           }
         }
         chance: 1
         tierChanceBoost: 0
       }
       {
         content: {
           type: "gtceu:sized"
           count: 1
           ingredient: {
-            item: "gtceu:platinum_ingot"
+            item: "gtceu:neodymium_ingot"
           }
         }
         chance: 1
         tierChanceBoost: 0
       }
     ]
   }
   tickInputs: {
     eu: [
       {
         content: 30
         chance: 1
         tierChanceBoost: 0
       }
     ]
   }
   tickOutputs: {
   }
 }

```


</details>

<details>
<summary>gtceu/arc_furnace/arc_iv_compressor</summary>

```diff
 {
   type: "gtceu:arc_furnace"
-  duration: 2817
+  duration: 2766
   inputs: {
     item: [
       {
         content: {
           type: "gtceu:sized"
           count: 1
           ingredient: {
             item: "gtceu:iv_compressor"
           }
         }
         chance: 1
         tierChanceBoost: 0
       }
     ]
     fluid: [
       {
         content: {
-          amount: 2817
+          amount: 2766
           value: [
             {
               tag: "forge:oxygen"
             }
           ]
         }
         chance: 1
         tierChanceBoost: 0
       }
     ]
   }
   outputs: {
     item: [
       {
         content: {
           type: "gtceu:sized"
           count: 12
           ingredient: {
             item: "gtceu:tungsten_steel_ingot"
           }
         }
         chance: 1
         tierChanceBoost: 0
       }
       {
         content: {
           type: "gtceu:sized"
           count: 8
           ingredient: {
             item: "gtceu:graphene_ingot"
           }
         }
         chance: 1
         tierChanceBoost: 0
       }
       {
         content: {
           type: "gtceu:sized"
           count: 6
           ingredient: {
             item: "gtceu:tungsten_ingot"
           }
         }
         chance: 1
         tierChanceBoost: 0
       }
       {
         content: {
           type: "gtceu:sized"
           count: 1
           ingredient: {
-            item: "gtceu:platinum_ingot"
+            item: "gtceu:neodymium_ingot"
           }
         }
         chance: 1
         tierChanceBoost: 0
       }
     ]
   }
   tickInputs: {
     eu: [
       {
         content: 30
         chance: 1
         tierChanceBoost: 0
       }
     ]
   }
   tickOutputs: {
   }
 }

```


</details>

<details>
<summary>gtceu/arc_furnace/arc_iv_fluid_heater</summary>

```diff
 {
   type: "gtceu:arc_furnace"
-  duration: 3586
+  duration: 3535
   inputs: {
     item: [
       {
         content: {
           type: "gtceu:sized"
           count: 1
           ingredient: {
             item: "gtceu:iv_fluid_heater"
           }
         }
         chance: 1
         tierChanceBoost: 0
       }
     ]
     fluid: [
       {
         content: {
-          amount: 3586
+          amount: 3535
           value: [
             {
               tag: "forge:oxygen"
             }
           ]
         }
         chance: 1
         tierChanceBoost: 0
       }
     ]
   }
   outputs: {
     item: [
       {
         content: {
           type: "gtceu:sized"
           count: 20
           ingredient: {
             item: "gtceu:tungsten_steel_ingot"
           }
         }
         chance: 1
         tierChanceBoost: 0
       }
       {
         content: {
           type: "gtceu:sized"
           count: 8
           ingredient: {
             item: "gtceu:graphene_ingot"
           }
         }
         chance: 1
         tierChanceBoost: 0
       }
       {
         content: {
           type: "gtceu:sized"
           count: 5
           ingredient: {
             item: "gtceu:tungsten_ingot"
           }
         }
         chance: 1
         tierChanceBoost: 0
       }
       {
         content: {
           type: "gtceu:sized"
           count: 1
           ingredient: {
-            item: "gtceu:platinum_ingot"
+            item: "gtceu:neodymium_ingot"
           }
         }
         chance: 1
         tierChanceBoost: 0
       }
     ]
   }
   tickInputs: {
     eu: [
       {
         content: 30
         chance: 1
         tierChanceBoost: 0
       }
     ]
   }
   tickOutputs: {
   }
 }

```


</details>

<details>
<summary>gtceu/arc_furnace/arc_iv_fluid_solidifier</summary>

```diff
 {
   type: "gtceu:arc_furnace"
-  duration: 3110
+  duration: 3059
   inputs: {
     item: [
       {
         content: {
           type: "gtceu:sized"
           count: 1
           ingredient: {
             item: "gtceu:iv_fluid_solidifier"
           }
         }
         chance: 1
         tierChanceBoost: 0
       }
     ]
     fluid: [
       {
         content: {
-          amount: 3110
+          amount: 3059
           value: [
             {
               tag: "forge:oxygen"
             }
           ]
         }
         chance: 1
         tierChanceBoost: 0
       }
     ]
   }
   outputs: {
     item: [
       {
         content: {
           type: "gtceu:sized"
           count: 16
           ingredient: {
             item: "gtceu:tungsten_steel_ingot"
           }
         }
         chance: 1
         tierChanceBoost: 0
       }
       {
         content: {
           type: "gtceu:sized"
           count: 8
           ingredient: {
             item: "gtceu:graphene_ingot"
           }
         }
         chance: 1
         tierChanceBoost: 0
       }
       {
         content: {
           type: "gtceu:sized"
           count: 5
           ingredient: {
             item: "gtceu:tungsten_ingot"
           }
         }
         chance: 1
         tierChanceBoost: 0
       }
       {
         content: {
           type: "gtceu:sized"
           count: 1
           ingredient: {
-            item: "gtceu:platinum_ingot"
+            item: "gtceu:neodymium_ingot"
           }
         }
         chance: 1
         tierChanceBoost: 0
       }
     ]
   }
   tickInputs: {
     eu: [
       {
         content: 30
         chance: 1
         tierChanceBoost: 0
       }
     ]
   }
   tickOutputs: {
   }
 }

```


</details>

<details>
<summary>gtceu/arc_furnace/arc_iv_thermal_centrifuge</summary>

```diff
 {
   type: "gtceu:arc_furnace"
-  duration: 1737
+  duration: 1686
   inputs: {
     item: [
       {
         content: {
           type: "gtceu:sized"
           count: 1
           ingredient: {
             item: "gtceu:iv_thermal_centrifuge"
           }
         }
         chance: 1
         tierChanceBoost: 0
       }
     ]
     fluid: [
       {
         content: {
-          amount: 1737
+          amount: 1686
           value: [
             {
               tag: "forge:oxygen"
             }
           ]
         }
         chance: 1
         tierChanceBoost: 0
       }
     ]
   }
   outputs: {
     item: [
       {
         content: {
           type: "gtceu:sized"
           count: 8
           ingredient: {
             item: "gtceu:graphene_ingot"
           }
         }
         chance: 1
         tierChanceBoost: 0
       }
       {
         content: {
           type: "gtceu:sized"
           count: 6
           ingredient: {
             item: "gtceu:tungsten_steel_ingot"
           }
         }
         chance: 1
         tierChanceBoost: 0
       }
       {
         content: {
           type: "gtceu:sized"
           count: 4
           ingredient: {
             item: "gtceu:tungsten_ingot"
           }
         }
         chance: 1
         tierChanceBoost: 0
       }
       {
         content: {
           type: "gtceu:sized"
           count: 1
           ingredient: {
-            item: "gtceu:platinum_ingot"
+            item: "gtceu:neodymium_ingot"
           }
         }
         chance: 1
         tierChanceBoost: 0
       }
     ]
   }
   tickInputs: {
     eu: [
       {
         content: 30
         chance: 1
         tierChanceBoost: 0
       }
     ]
   }
   tickOutputs: {
   }
 }

```


</details>

<details>
<summary>gtceu/arc_furnace/arc_lv_extractor</summary>

```diff
 {
   type: "gtceu:arc_furnace"
-  duration: 1644
+  duration: 1704
   inputs: {
     item: [
       {
         content: {
           type: "gtceu:sized"
           count: 1
           ingredient: {
             item: "gtceu:lv_extractor"
           }
         }
         chance: 1
         tierChanceBoost: 0
       }
     ]
     fluid: [
       {
         content: {
-          amount: 1644
+          amount: 1704
           value: [
             {
               tag: "forge:oxygen"
             }
           ]
         }
         chance: 1
         tierChanceBoost: 0
       }
     ]
   }
   outputs: {
     item: [
       {
         content: {
           type: "gtceu:sized"
           count: 8
           ingredient: {
             item: "gtceu:tin_ingot"
           }
         }
         chance: 1
         tierChanceBoost: 0
       }
       {
         content: {
           type: "gtceu:sized"
           count: 5
           ingredient: {
             item: "gtceu:steel_ingot"
           }
         }
         chance: 1
         tierChanceBoost: 0
       }
       {
         content: {
           type: "gtceu:sized"
           count: 4
           ingredient: {
             item: "gtceu:annealed_copper_ingot"
           }
         }
         chance: 1
         tierChanceBoost: 0
       }
       {
         content: {
           type: "gtceu:sized"
           count: 3
           ingredient: {
-            item: "gtceu:wrought_iron_ingot"
+            item: "gtceu:bronze_ingot"
           }
         }
         chance: 1
         tierChanceBoost: 0
       }
     ]
   }
   tickInputs: {
     eu: [
       {
         content: 30
         chance: 1
         tierChanceBoost: 0
       }
     ]
   }
   tickOutputs: {
   }
 }

```


</details>

<details>
<summary>gtceu/electric_blast_furnace/steel_from_iron</summary>

```diff
 {
-  tickOutputs: {
-  }
   type: "gtceu:electric_blast_furnace"
-  duration: 500
+  duration: 300
   data: {
     ebf_temp: 1000
   }
   inputs: {
     item: [
       {
         content: {
           type: "gtceu:sized"
           count: 1
           ingredient: {
             tag: "forge:ingots/iron"
           }
         }
         chance: 1
         tierChanceBoost: 0
       }
     ]
     fluid: [
       {
         content: {
           amount: 200
           value: [
             {
-              tag: "forge:oxygen"
+              fluid: "gtceu:oxygen"
             }
           ]
         }
         chance: 1
         tierChanceBoost: 0
       }
     ]
   }
   outputs: {
     item: [
       {
         content: {
           type: "gtceu:sized"
           count: 1
           ingredient: {
             item: "gtceu:steel_ingot"
           }
         }
         chance: 1
         tierChanceBoost: 0
       }
       {
         content: {
           type: "gtceu:sized"
           count: 1
           ingredient: {
             item: "gtceu:ash_dust"
           }
         }
         chance: 0.1111
-        tierChanceBoost: 0
+        tierChanceBoost: 0.0001
       }
+      {
+        content: {
+          type: "gtceu:sized"
+          count: 1
+          ingredient: {
+            item: "immersiveengineering:slag"
+          }
+        }
+        chance: 0.2
+        tierChanceBoost: 0.0001
+      }
     ]
   }
   tickInputs: {
     eu: [
       {
         content: 120
         chance: 1
         tierChanceBoost: 0
       }
     ]
   }
 }

```


</details>

<details>
<summary>gtceu/macerator/macerate_chalcocite_ore_to_raw_ore</summary>

```diff
 {
   type: "gtceu:macerator"
   duration: 400
   inputs: {
     item: [
       {
         content: {
           type: "forge:intersection"
           children: [
             {
               tag: "forge:ores/chalcocite"
             }
             {
               tag: "forge:ores_in_ground/stone"
             }
           ]
         }
         chance: 1
         tierChanceBoost: 0
       }
     ]
   }
   outputs: {
     item: [
       {
         content: {
           type: "gtceu:sized"
           count: 2
           ingredient: {
             item: "gtceu:crushed_chalcocite_ore"
           }
         }
         chance: 1
         tierChanceBoost: 0
       }
       {
         content: {
           type: "gtceu:sized"
           count: 1
           ingredient: {
-            item: "gtceu:sulfur_dust"
+            item: "vintageimprovements:sulfur"
           }
         }
         chance: 0.14
         tierChanceBoost: 0.085
       }
       {
         content: {
           type: "gtceu:sized"
           count: 1
           ingredient: {
             item: "gtceu:stone_dust"
           }
         }
         chance: 0.67
         tierChanceBoost: 0.08
       }
     ]
   }
   tickInputs: {
     eu: [
       {
         content: 2
         chance: 1
         tierChanceBoost: 0
       }
     ]
   }
   tickOutputs: {
   }
 }

```


</details>

<details>
<summary>gtceu/macerator/macerate_cleanroom</summary>

```diff
 {
   type: "gtceu:macerator"
-  duration: 2576
+  duration: 2168
   inputs: {
     item: [
       {
         content: {
           type: "gtceu:sized"
           count: 1
           ingredient: {
             item: "gtceu:cleanroom"
           }
         }
         chance: 1
         tierChanceBoost: 0
       }
     ]
   }
   outputs: {
     item: [
       {
         content: {
           type: "gtceu:sized"
           count: 10
           ingredient: {
             item: "gtceu:stainless_steel_dust"
           }
         }
         chance: 1
         tierChanceBoost: 0
       }
       {
         content: {
           type: "gtceu:sized"
           count: 8
           ingredient: {
             item: "gtceu:electrum_dust"
           }
         }
         chance: 1
         tierChanceBoost: 0
       }
       {
         content: {
           type: "gtceu:sized"
           count: 6
           ingredient: {
             item: "gtceu:zinc_dust"
           }
         }
         chance: 1
         tierChanceBoost: 0
       }
       {
         content: {
           type: "gtceu:sized"
           count: 4
           ingredient: {
-            item: "gtceu:silver_dust"
+            item: "gtceu:rubber_dust"
           }
         }
         chance: 1
         tierChanceBoost: 0
       }
     ]
   }
   tickInputs: {
     eu: [
       {
         content: 8
         chance: 1
         tierChanceBoost: 0
       }
     ]
   }
   tickOutputs: {
   }
 }

```


</details>

<details>
<summary>gtceu/macerator/macerate_cobaltite_ore_to_raw_ore</summary>

```diff
 {
   type: "gtceu:macerator"
   duration: 400
   inputs: {
     item: [
       {
         content: {
           type: "forge:intersection"
           children: [
             {
               tag: "forge:ores/cobaltite"
             }
             {
               tag: "forge:ores_in_ground/stone"
             }
           ]
         }
         chance: 1
         tierChanceBoost: 0
       }
     ]
   }
   outputs: {
     item: [
       {
         content: {
           type: "gtceu:sized"
           count: 2
           ingredient: {
             item: "gtceu:crushed_cobaltite_ore"
           }
         }
         chance: 1
         tierChanceBoost: 0
       }
       {
         content: {
           type: "gtceu:sized"
           count: 1
           ingredient: {
-            item: "gtceu:sulfur_dust"
+            item: "vintageimprovements:sulfur"
           }
         }
         chance: 0.14
         tierChanceBoost: 0.085
       }
       {
         content: {
           type: "gtceu:sized"
           count: 1
           ingredient: {
             item: "gtceu:stone_dust"
           }
         }
         chance: 0.67
         tierChanceBoost: 0.08
       }
     ]
   }
   tickInputs: {
     eu: [
       {
         content: 2
         chance: 1
         tierChanceBoost: 0
       }
     ]
   }
   tickOutputs: {
   }
 }

```


</details>

<details>
<summary>gtceu/macerator/macerate_deepslate_chalcocite_ore_to_raw_ore</summary>

```diff
 {
   type: "gtceu:macerator"
   duration: 400
   inputs: {
     item: [
       {
         content: {
           type: "forge:intersection"
           children: [
             {
               tag: "forge:ores/chalcocite"
             }
             {
               tag: "forge:ores_in_ground/deepslate"
             }
           ]
         }
         chance: 1
         tierChanceBoost: 0
       }
     ]
   }
   outputs: {
     item: [
       {
         content: {
           type: "gtceu:sized"
           count: 2
           ingredient: {
             item: "gtceu:crushed_chalcocite_ore"
           }
         }
         chance: 1
         tierChanceBoost: 0
       }
       {
         content: {
           type: "gtceu:sized"
           count: 1
           ingredient: {
-            item: "gtceu:sulfur_dust"
+            item: "vintageimprovements:sulfur"
           }
         }
         chance: 0.14
         tierChanceBoost: 0.085
       }
       {
         content: {
           type: "gtceu:sized"
           count: 1
           ingredient: {
             item: "gtceu:deepslate_dust"
           }
         }
         chance: 0.67
         tierChanceBoost: 0.08
       }
     ]
   }
   tickInputs: {
     eu: [
       {
         content: 2
         chance: 1
         tierChanceBoost: 0
       }
     ]
   }
   tickOutputs: {
   }
 }

```


</details>

<details>
<summary>gtceu/macerator/macerate_deepslate_cobaltite_ore_to_raw_ore</summary>

```diff
 {
   type: "gtceu:macerator"
   duration: 400
   inputs: {
     item: [
       {
         content: {
           type: "forge:intersection"
           children: [
             {
               tag: "forge:ores/cobaltite"
             }
             {
               tag: "forge:ores_in_ground/deepslate"
             }
           ]
         }
         chance: 1
         tierChanceBoost: 0
       }
     ]
   }
   outputs: {
     item: [
       {
         content: {
           type: "gtceu:sized"
           count: 2
           ingredient: {
             item: "gtceu:crushed_cobaltite_ore"
           }
         }
         chance: 1
         tierChanceBoost: 0
       }
       {
         content: {
           type: "gtceu:sized"
           count: 1
           ingredient: {
-            item: "gtceu:sulfur_dust"
+            item: "vintageimprovements:sulfur"
           }
         }
         chance: 0.14
         tierChanceBoost: 0.085
       }
       {
         content: {
           type: "gtceu:sized"
           count: 1
           ingredient: {
             item: "gtceu:deepslate_dust"
           }
         }
         chance: 0.67
         tierChanceBoost: 0.08
       }
     ]
   }
   tickInputs: {
     eu: [
       {
         content: 2
         chance: 1
         tierChanceBoost: 0
       }
     ]
   }
   tickOutputs: {
   }
 }

```


</details>

<details>
<summary>gtceu/macerator/macerate_deepslate_galena_ore_to_raw_ore</summary>

```diff
 {
   type: "gtceu:macerator"
   duration: 400
   inputs: {
     item: [
       {
         content: {
           type: "forge:intersection"
           children: [
             {
               tag: "forge:ores/galena"
             }
             {
               tag: "forge:ores_in_ground/deepslate"
             }
           ]
         }
         chance: 1
         tierChanceBoost: 0
       }
     ]
   }
   outputs: {
     item: [
       {
         content: {
           type: "gtceu:sized"
           count: 2
           ingredient: {
             item: "gtceu:crushed_galena_ore"
           }
         }
         chance: 1
         tierChanceBoost: 0
       }
       {
         content: {
           type: "gtceu:sized"
           count: 1
           ingredient: {
-            item: "gtceu:sulfur_dust"
+            item: "vintageimprovements:sulfur"
           }
         }
         chance: 0.14
         tierChanceBoost: 0.085
       }
       {
         content: {
           type: "gtceu:sized"
           count: 1
           ingredient: {
             item: "gtceu:deepslate_dust"
           }
         }
         chance: 0.67
         tierChanceBoost: 0.08
       }
     ]
   }
   tickInputs: {
     eu: [
       {
         content: 2
         chance: 1
         tierChanceBoost: 0
       }
     ]
   }
   tickOutputs: {
   }
 }

```


</details>

<details>
<summary>gtceu/macerator/macerate_deepslate_gypsum_ore_to_raw_ore</summary>

```diff
 {
   type: "gtceu:macerator"
   duration: 400
   inputs: {
     item: [
       {
         content: {
           type: "forge:intersection"
           children: [
             {
               tag: "forge:ores/gypsum"
             }
             {
               tag: "forge:ores_in_ground/deepslate"
             }
           ]
         }
         chance: 1
         tierChanceBoost: 0
       }
     ]
   }
   outputs: {
     item: [
       {
         content: {
           type: "gtceu:sized"
           count: 2
           ingredient: {
             item: "gtceu:crushed_gypsum_ore"
           }
         }
         chance: 1
         tierChanceBoost: 0
       }
       {
         content: {
           type: "gtceu:sized"
           count: 1
           ingredient: {
-            item: "gtceu:sulfur_dust"
+            item: "vintageimprovements:sulfur"
           }
         }
         chance: 0.14
         tierChanceBoost: 0.085
       }
       {
         content: {
           type: "gtceu:sized"
           count: 1
           ingredient: {
             item: "gtceu:deepslate_dust"
           }
         }
         chance: 0.67
         tierChanceBoost: 0.08
       }
     ]
   }
   tickInputs: {
     eu: [
       {
         content: 2
         chance: 1
         tierChanceBoost: 0
       }
     ]
   }
   tickOutputs: {
   }
 }

```


</details>

<details>
<summary>gtceu/macerator/macerate_deepslate_naquadah_ore_to_raw_ore</summary>

```diff
 {
   type: "gtceu:macerator"
   duration: 400
   inputs: {
     item: [
       {
         content: {
           type: "forge:intersection"
           children: [
             {
               tag: "forge:ores/naquadah"
             }
             {
               tag: "forge:ores_in_ground/deepslate"
             }
           ]
         }
         chance: 1
         tierChanceBoost: 0
       }
     ]
   }
   outputs: {
     item: [
       {
         content: {
           type: "gtceu:sized"
           count: 2
           ingredient: {
             item: "gtceu:crushed_naquadah_ore"
           }
         }
         chance: 1
         tierChanceBoost: 0
       }
       {
         content: {
           type: "gtceu:sized"
           count: 1
           ingredient: {
-            item: "gtceu:sulfur_dust"
+            item: "vintageimprovements:sulfur"
           }
         }
         chance: 0.14
         tierChanceBoost: 0.085
       }
       {
         content: {
           type: "gtceu:sized"
           count: 1
           ingredient: {
             item: "gtceu:deepslate_dust"
           }
         }
         chance: 0.67
         tierChanceBoost: 0.08
       }
     ]
   }
   tickInputs: {
     eu: [
       {
         content: 2
         chance: 1
         tierChanceBoost: 0
       }
     ]
   }
   tickOutputs: {
   }
 }

```


</details>

<details>
<summary>gtceu/macerator/macerate_deepslate_pyrite_ore_to_raw_ore</summary>

```diff
 {
   type: "gtceu:macerator"
   duration: 400
   inputs: {
     item: [
       {
         content: {
           type: "forge:intersection"
           children: [
             {
               tag: "forge:ores/pyrite"
             }
             {
               tag: "forge:ores_in_ground/deepslate"
             }
           ]
         }
         chance: 1
         tierChanceBoost: 0
       }
     ]
   }
   outputs: {
     item: [
       {
         content: {
           type: "gtceu:sized"
           count: 2
           ingredient: {
             item: "gtceu:crushed_pyrite_ore"
           }
         }
         chance: 1
         tierChanceBoost: 0
       }
       {
         content: {
           type: "gtceu:sized"
           count: 1
           ingredient: {
-            item: "gtceu:sulfur_dust"
+            item: "vintageimprovements:sulfur"
           }
         }
         chance: 0.14
         tierChanceBoost: 0.085
       }
       {
         content: {
           type: "gtceu:sized"
           count: 1
           ingredient: {
             item: "gtceu:deepslate_dust"
           }
         }
         chance: 0.67
         tierChanceBoost: 0.08
       }
     ]
   }
   tickInputs: {
     eu: [
       {
         content: 2
         chance: 1
         tierChanceBoost: 0
       }
     ]
   }
   tickOutputs: {
   }
 }

```


</details>

<details>
<summary>gtceu/macerator/macerate_deepslate_realgar_ore_to_raw_ore</summary>

```diff
 {
   type: "gtceu:macerator"
   duration: 400
   inputs: {
     item: [
       {
         content: {
           type: "forge:intersection"
           children: [
             {
               tag: "forge:ores/realgar"
             }
             {
               tag: "forge:ores_in_ground/deepslate"
             }
           ]
         }
         chance: 1
         tierChanceBoost: 0
       }
     ]
   }
   outputs: {
     item: [
       {
         content: {
           type: "gtceu:sized"
           count: 2
           ingredient: {
             item: "gtceu:crushed_realgar_ore"
           }
         }
         chance: 1
         tierChanceBoost: 0
       }
       {
         content: {
           type: "gtceu:sized"
           count: 1
           ingredient: {
-            item: "gtceu:sulfur_dust"
+            item: "vintageimprovements:sulfur"
           }
         }
         chance: 0.14
         tierChanceBoost: 0.085
       }
       {
         content: {
           type: "gtceu:sized"
           count: 1
           ingredient: {
             item: "gtceu:deepslate_dust"
           }
         }
         chance: 0.67
         tierChanceBoost: 0.08
       }
     ]
   }
   tickInputs: {
     eu: [
       {
         content: 2
         chance: 1
         tierChanceBoost: 0
       }
     ]
   }
   tickOutputs: {
   }
 }

```


</details>

<details>
<summary>gtceu/macerator/macerate_deepslate_sulfur_ore_to_raw_ore</summary>

```diff
 {
   type: "gtceu:macerator"
   duration: 400
   inputs: {
     item: [
       {
         content: {
           type: "forge:intersection"
           children: [
             {
               tag: "forge:ores/sulfur"
             }
             {
               tag: "forge:ores_in_ground/deepslate"
             }
           ]
         }
         chance: 1
         tierChanceBoost: 0
       }
     ]
   }
   outputs: {
     item: [
       {
         content: {
           type: "gtceu:sized"
           count: 2
           ingredient: {
             item: "gtceu:crushed_sulfur_ore"
           }
         }
         chance: 1
         tierChanceBoost: 0
       }
       {
         content: {
           type: "gtceu:sized"
           count: 1
           ingredient: {
-            item: "gtceu:sulfur_dust"
+            item: "vintageimprovements:sulfur"
           }
         }
         chance: 0.14
         tierChanceBoost: 0.085
       }
       {
         content: {
           type: "gtceu:sized"
           count: 1
           ingredient: {
             item: "gtceu:deepslate_dust"
           }
         }
         chance: 0.67
         tierChanceBoost: 0.08
       }
     ]
   }
   tickInputs: {
     eu: [
       {
         content: 2
         chance: 1
         tierChanceBoost: 0
       }
     ]
   }
   tickOutputs: {
   }
 }

```


</details>

<details>
<summary>gtceu/macerator/macerate_endstone_chalcocite_ore_to_raw_ore</summary>

```diff
 {
   type: "gtceu:macerator"
   duration: 400
   inputs: {
     item: [
       {
         content: {
           type: "forge:intersection"
           children: [
             {
               tag: "forge:ores/chalcocite"
             }
             {
               tag: "forge:ores_in_ground/endstone"
             }
           ]
         }
         chance: 1
         tierChanceBoost: 0
       }
     ]
   }
   outputs: {
     item: [
       {
         content: {
           type: "gtceu:sized"
           count: 4
           ingredient: {
             item: "gtceu:crushed_chalcocite_ore"
           }
         }
         chance: 1
         tierChanceBoost: 0
       }
       {
         content: {
           type: "gtceu:sized"
           count: 1
           ingredient: {
-            item: "gtceu:sulfur_dust"
+            item: "vintageimprovements:sulfur"
           }
         }
         chance: 0.14
         tierChanceBoost: 0.085
       }
       {
         content: {
           type: "gtceu:sized"
           count: 1
           ingredient: {
             item: "gtceu:endstone_dust"
           }
         }
         chance: 0.67
         tierChanceBoost: 0.08
       }
     ]
   }
   tickInputs: {
     eu: [
       {
         content: 2
         chance: 1
         tierChanceBoost: 0
       }
     ]
   }
   tickOutputs: {
   }
 }

```


</details>

<details>
<summary>gtceu/macerator/macerate_endstone_cobaltite_ore_to_raw_ore</summary>

```diff
 {
   type: "gtceu:macerator"
   duration: 400
   inputs: {
     item: [
       {
         content: {
           type: "forge:intersection"
           children: [
             {
               tag: "forge:ores/cobaltite"
             }
             {
               tag: "forge:ores_in_ground/endstone"
             }
           ]
         }
         chance: 1
         tierChanceBoost: 0
       }
     ]
   }
   outputs: {
     item: [
       {
         content: {
           type: "gtceu:sized"
           count: 4
           ingredient: {
             item: "gtceu:crushed_cobaltite_ore"
           }
         }
         chance: 1
         tierChanceBoost: 0
       }
       {
         content: {
           type: "gtceu:sized"
           count: 1
           ingredient: {
-            item: "gtceu:sulfur_dust"
+            item: "vintageimprovements:sulfur"
           }
         }
         chance: 0.14
         tierChanceBoost: 0.085
       }
       {
         content: {
           type: "gtceu:sized"
           count: 1
           ingredient: {
             item: "gtceu:endstone_dust"
           }
         }
         chance: 0.67
         tierChanceBoost: 0.08
       }
     ]
   }
   tickInputs: {
     eu: [
       {
         content: 2
         chance: 1
         tierChanceBoost: 0
       }
     ]
   }
   tickOutputs: {
   }
 }

```


</details>

<details>
<summary>gtceu/macerator/macerate_endstone_galena_ore_to_raw_ore</summary>

```diff
 {
   type: "gtceu:macerator"
   duration: 400
   inputs: {
     item: [
       {
         content: {
           type: "forge:intersection"
           children: [
             {
               tag: "forge:ores/galena"
             }
             {
               tag: "forge:ores_in_ground/endstone"
             }
           ]
         }
         chance: 1
         tierChanceBoost: 0
       }
     ]
   }
   outputs: {
     item: [
       {
         content: {
           type: "gtceu:sized"
           count: 4
           ingredient: {
             item: "gtceu:crushed_galena_ore"
           }
         }
         chance: 1
         tierChanceBoost: 0
       }
       {
         content: {
           type: "gtceu:sized"
           count: 1
           ingredient: {
-            item: "gtceu:sulfur_dust"
+            item: "vintageimprovements:sulfur"
           }
         }
         chance: 0.14
         tierChanceBoost: 0.085
       }
       {
         content: {
           type: "gtceu:sized"
           count: 1
           ingredient: {
             item: "gtceu:endstone_dust"
           }
         }
         chance: 0.67
         tierChanceBoost: 0.08
       }
     ]
   }
   tickInputs: {
     eu: [
       {
         content: 2
         chance: 1
         tierChanceBoost: 0
       }
     ]
   }
   tickOutputs: {
   }
 }

```


</details>

<details>
<summary>gtceu/macerator/macerate_endstone_gypsum_ore_to_raw_ore</summary>

```diff
 {
   type: "gtceu:macerator"
   duration: 400
   inputs: {
     item: [
       {
         content: {
           type: "forge:intersection"
           children: [
             {
               tag: "forge:ores/gypsum"
             }
             {
               tag: "forge:ores_in_ground/endstone"
             }
           ]
         }
         chance: 1
         tierChanceBoost: 0
       }
     ]
   }
   outputs: {
     item: [
       {
         content: {
           type: "gtceu:sized"
           count: 4
           ingredient: {
             item: "gtceu:crushed_gypsum_ore"
           }
         }
         chance: 1
         tierChanceBoost: 0
       }
       {
         content: {
           type: "gtceu:sized"
           count: 1
           ingredient: {
-            item: "gtceu:sulfur_dust"
+            item: "vintageimprovements:sulfur"
           }
         }
         chance: 0.14
         tierChanceBoost: 0.085
       }
       {
         content: {
           type: "gtceu:sized"
           count: 1
           ingredient: {
             item: "gtceu:endstone_dust"
           }
         }
         chance: 0.67
         tierChanceBoost: 0.08
       }
     ]
   }
   tickInputs: {
     eu: [
       {
         content: 2
         chance: 1
         tierChanceBoost: 0
       }
     ]
   }
   tickOutputs: {
   }
 }

```


</details>

<details>
<summary>gtceu/macerator/macerate_endstone_naquadah_ore_to_raw_ore</summary>

```diff
 {
   type: "gtceu:macerator"
   duration: 400
   inputs: {
     item: [
       {
         content: {
           type: "forge:intersection"
           children: [
             {
               tag: "forge:ores/naquadah"
             }
             {
               tag: "forge:ores_in_ground/endstone"
             }
           ]
         }
         chance: 1
         tierChanceBoost: 0
       }
     ]
   }
   outputs: {
     item: [
       {
         content: {
           type: "gtceu:sized"
           count: 4
           ingredient: {
             item: "gtceu:crushed_naquadah_ore"
           }
         }
         chance: 1
         tierChanceBoost: 0
       }
       {
         content: {
           type: "gtceu:sized"
           count: 1
           ingredient: {
-            item: "gtceu:sulfur_dust"
+            item: "vintageimprovements:sulfur"
           }
         }
         chance: 0.14
         tierChanceBoost: 0.085
       }
       {
         content: {
           type: "gtceu:sized"
           count: 1
           ingredient: {
             item: "gtceu:endstone_dust"
           }
         }
         chance: 0.67
         tierChanceBoost: 0.08
       }
     ]
   }
   tickInputs: {
     eu: [
       {
         content: 2
         chance: 1
         tierChanceBoost: 0
       }
     ]
   }
   tickOutputs: {
   }
 }

```


</details>

<details>
<summary>gtceu/macerator/macerate_endstone_pyrite_ore_to_raw_ore</summary>

```diff
 {
   type: "gtceu:macerator"
   duration: 400
   inputs: {
     item: [
       {
         content: {
           type: "forge:intersection"
           children: [
             {
               tag: "forge:ores/pyrite"
             }
             {
               tag: "forge:ores_in_ground/endstone"
             }
           ]
         }
         chance: 1
         tierChanceBoost: 0
       }
     ]
   }
   outputs: {
     item: [
       {
         content: {
           type: "gtceu:sized"
           count: 4
           ingredient: {
             item: "gtceu:crushed_pyrite_ore"
           }
         }
         chance: 1
         tierChanceBoost: 0
       }
       {
         content: {
           type: "gtceu:sized"
           count: 1
           ingredient: {
-            item: "gtceu:sulfur_dust"
+            item: "vintageimprovements:sulfur"
           }
         }
         chance: 0.14
         tierChanceBoost: 0.085
       }
       {
         content: {
           type: "gtceu:sized"
           count: 1
           ingredient: {
             item: "gtceu:endstone_dust"
           }
         }
         chance: 0.67
         tierChanceBoost: 0.08
       }
     ]
   }
   tickInputs: {
     eu: [
       {
         content: 2
         chance: 1
         tierChanceBoost: 0
       }
     ]
   }
   tickOutputs: {
   }
 }

```


</details>

<details>
<summary>gtceu/macerator/macerate_endstone_realgar_ore_to_raw_ore</summary>

```diff
 {
   type: "gtceu:macerator"
   duration: 400
   inputs: {
     item: [
       {
         content: {
           type: "forge:intersection"
           children: [
             {
               tag: "forge:ores/realgar"
             }
             {
               tag: "forge:ores_in_ground/endstone"
             }
           ]
         }
         chance: 1
         tierChanceBoost: 0
       }
     ]
   }
   outputs: {
     item: [
       {
         content: {
           type: "gtceu:sized"
           count: 4
           ingredient: {
             item: "gtceu:crushed_realgar_ore"
           }
         }
         chance: 1
         tierChanceBoost: 0
       }
       {
         content: {
           type: "gtceu:sized"
           count: 1
           ingredient: {
-            item: "gtceu:sulfur_dust"
+            item: "vintageimprovements:sulfur"
           }
         }
         chance: 0.14
         tierChanceBoost: 0.085
       }
       {
         content: {
           type: "gtceu:sized"
           count: 1
           ingredient: {
             item: "gtceu:endstone_dust"
           }
         }
         chance: 0.67
         tierChanceBoost: 0.08
       }
     ]
   }
   tickInputs: {
     eu: [
       {
         content: 2
         chance: 1
         tierChanceBoost: 0
       }
     ]
   }
   tickOutputs: {
   }
 }

```


</details>

<details>
<summary>gtceu/macerator/macerate_endstone_sulfur_ore_to_raw_ore</summary>

```diff
 {
   type: "gtceu:macerator"
   duration: 400
   inputs: {
     item: [
       {
         content: {
           type: "forge:intersection"
           children: [
             {
               tag: "forge:ores/sulfur"
             }
             {
               tag: "forge:ores_in_ground/endstone"
             }
           ]
         }
         chance: 1
         tierChanceBoost: 0
       }
     ]
   }
   outputs: {
     item: [
       {
         content: {
           type: "gtceu:sized"
           count: 4
           ingredient: {
             item: "gtceu:crushed_sulfur_ore"
           }
         }
         chance: 1
         tierChanceBoost: 0
       }
       {
         content: {
           type: "gtceu:sized"
           count: 1
           ingredient: {
-            item: "gtceu:sulfur_dust"
+            item: "vintageimprovements:sulfur"
           }
         }
         chance: 0.14
         tierChanceBoost: 0.085
       }
       {
         content: {
           type: "gtceu:sized"
           count: 1
           ingredient: {
             item: "gtceu:endstone_dust"
           }
         }
         chance: 0.67
         tierChanceBoost: 0.08
       }
     ]
   }
   tickInputs: {
     eu: [
       {
         content: 2
         chance: 1
         tierChanceBoost: 0
       }
     ]
   }
   tickOutputs: {
   }
 }

```


</details>

<details>
<summary>gtceu/macerator/macerate_ev_fermenter</summary>

```diff
 {
   type: "gtceu:macerator"
-  duration: 556
+  duration: 572
   inputs: {
     item: [
       {
         content: {
           type: "gtceu:sized"
           count: 1
           ingredient: {
             item: "gtceu:ev_fermenter"
           }
         }
         chance: 1
         tierChanceBoost: 0
       }
     ]
   }
   outputs: {
     item: [
       {
         content: {
           type: "gtceu:sized"
           count: 30
           ingredient: {
             item: "gtceu:small_rubber_dust"
           }
         }
         chance: 1
         tierChanceBoost: 0
       }
       {
         content: {
           type: "gtceu:sized"
           count: 18
           ingredient: {
             item: "gtceu:small_aluminium_dust"
           }
         }
         chance: 1
         tierChanceBoost: 0
       }
       {
         content: {
           type: "gtceu:sized"
           count: 37
           ingredient: {
             item: "gtceu:tiny_stainless_steel_dust"
           }
         }
         chance: 1
         tierChanceBoost: 0
       }
       {
         content: {
           type: "gtceu:sized"
           count: 4
           ingredient: {
-            item: "gtceu:kanthal_dust"
+            item: "gtceu:titanium_dust"
           }
         }
         chance: 1
         tierChanceBoost: 0
       }
     ]
   }
   tickInputs: {
     eu: [
       {
         content: 8
         chance: 1
         tierChanceBoost: 0
       }
     ]
   }
   tickOutputs: {
   }
 }

```


</details>

<details>
<summary>gtceu/macerator/macerate_ev_muffler_hatch</summary>

```diff
 {
   type: "gtceu:macerator"
-  duration: 598
+  duration: 640
   inputs: {
     item: [
       {
         content: {
           type: "gtceu:sized"
           count: 1
           ingredient: {
             item: "gtceu:ev_muffler_hatch"
           }
         }
         chance: 1
         tierChanceBoost: 0
       }
     ]
   }
   outputs: {
     item: [
       {
         content: {
           type: "gtceu:sized"
           count: 4
           ingredient: {
             item: "gtceu:stainless_steel_dust"
           }
         }
         chance: 1
         tierChanceBoost: 0
       }
       {
         content: {
           type: "gtceu:sized"
           count: 4
           ingredient: {
             item: "gtceu:kanthal_dust"
           }
         }
         chance: 1
         tierChanceBoost: 0
       }
       {
         content: {
           type: "gtceu:sized"
           count: 4
           ingredient: {
             item: "gtceu:titanium_dust"
           }
         }
         chance: 1
         tierChanceBoost: 0
       }
       {
         content: {
           type: "gtceu:sized"
           count: 2
           ingredient: {
-            item: "gtceu:rubber_dust"
+            item: "gtceu:aluminium_dust"
           }
         }
         chance: 1
         tierChanceBoost: 0
       }
     ]
   }
   tickInputs: {
     eu: [
       {
         content: 8
         chance: 1
         tierChanceBoost: 0
       }
     ]
   }
   tickOutputs: {
   }
 }

```


</details>

<details>
<summary>gtceu/macerator/macerate_ev_world_accelerator</summary>

```diff
 {
   type: "gtceu:macerator"
-  duration: 9079
+  duration: 8707
   inputs: {
     item: [
       {
         content: {
           type: "gtceu:sized"
           count: 1
           ingredient: {
             item: "gtceu:ev_world_accelerator"
           }
         }
         chance: 1
         tierChanceBoost: 0
       }
     ]
   }
   outputs: {
     item: [
       {
         content: {
           type: "gtceu:sized"
           count: 32
           ingredient: {
             item: "gtceu:uranium_triplatinum_dust"
           }
         }
         chance: 1
         tierChanceBoost: 0
       }
       {
         content: {
           type: "gtceu:sized"
           count: 24
           ingredient: {
             item: "gtceu:titanium_dust"
           }
         }
         chance: 1
         tierChanceBoost: 0
       }
       {
         content: {
           type: "gtceu:sized"
           count: 5
           ingredient: {
             item: "gtceu:platinum_dust"
           }
         }
         chance: 1
         tierChanceBoost: 0
       }
       {
         content: {
           type: "gtceu:sized"
           count: 4
           ingredient: {
-            item: "gtceu:nether_star_dust"
+            item: "gtceu:rubber_dust"
           }
         }
         chance: 1
         tierChanceBoost: 0
       }
     ]
   }
   tickInputs: {
     eu: [
       {
         content: 32
         chance: 1
         tierChanceBoost: 0
       }
     ]
   }
   tickOutputs: {
   }
 }

```


</details>

<details>
<summary>gtceu/macerator/macerate_galena_ore_to_raw_ore</summary>

```diff
 {
   type: "gtceu:macerator"
   duration: 400
   inputs: {
     item: [
       {
         content: {
           type: "forge:intersection"
           children: [
             {
               tag: "forge:ores/galena"
             }
             {
               tag: "forge:ores_in_ground/stone"
             }
           ]
         }
         chance: 1
         tierChanceBoost: 0
       }
     ]
   }
   outputs: {
     item: [
       {
         content: {
           type: "gtceu:sized"
           count: 2
           ingredient: {
             item: "gtceu:crushed_galena_ore"
           }
         }
         chance: 1
         tierChanceBoost: 0
       }
       {
         content: {
           type: "gtceu:sized"
           count: 1
           ingredient: {
-            item: "gtceu:sulfur_dust"
+            item: "vintageimprovements:sulfur"
           }
         }
         chance: 0.14
         tierChanceBoost: 0.085
       }
       {
         content: {
           type: "gtceu:sized"
           count: 1
           ingredient: {
             item: "gtceu:stone_dust"
           }
         }
         chance: 0.67
         tierChanceBoost: 0.08
       }
     ]
   }
   tickInputs: {
     eu: [
       {
         content: 2
         chance: 1
         tierChanceBoost: 0
       }
     ]
   }
   tickOutputs: {
   }
 }

```


</details>

<details>
<summary>gtceu/macerator/macerate_gypsum_ore_to_raw_ore</summary>

```diff
 {
   type: "gtceu:macerator"
   duration: 400
   inputs: {
     item: [
       {
         content: {
           type: "forge:intersection"
           children: [
             {
               tag: "forge:ores/gypsum"
             }
             {
               tag: "forge:ores_in_ground/stone"
             }
           ]
         }
         chance: 1
         tierChanceBoost: 0
       }
     ]
   }
   outputs: {
     item: [
       {
         content: {
           type: "gtceu:sized"
           count: 2
           ingredient: {
             item: "gtceu:crushed_gypsum_ore"
           }
         }
         chance: 1
         tierChanceBoost: 0
       }
       {
         content: {
           type: "gtceu:sized"
           count: 1
           ingredient: {
-            item: "gtceu:sulfur_dust"
+            item: "vintageimprovements:sulfur"
           }
         }
         chance: 0.14
         tierChanceBoost: 0.085
       }
       {
         content: {
           type: "gtceu:sized"
           count: 1
           ingredient: {
             item: "gtceu:stone_dust"
           }
         }
         chance: 0.67
         tierChanceBoost: 0.08
       }
     ]
   }
   tickInputs: {
     eu: [
       {
         content: 2
         chance: 1
         tierChanceBoost: 0
       }
     ]
   }
   tickOutputs: {
   }
 }

```


</details>

<details>
<summary>gtceu/macerator/macerate_hp_steam_extractor</summary>

```diff
 {
   type: "gtceu:macerator"
-  duration: 1667
+  duration: 1631
   inputs: {
     item: [
       {
         content: {
           type: "gtceu:sized"
           count: 1
           ingredient: {
             item: "gtceu:hp_steam_extractor"
           }
         }
         chance: 1
         tierChanceBoost: 0
       }
     ]
   }
   outputs: {
     item: [
       {
         content: {
           type: "gtceu:sized"
           count: 14
           ingredient: {
             item: "gtceu:bronze_dust"
           }
         }
         chance: 1
         tierChanceBoost: 0
       }
       {
         content: {
           type: "gtceu:sized"
           count: 5
           ingredient: {
             item: "gtceu:tin_alloy_dust"
           }
         }
         chance: 1
         tierChanceBoost: 0
       }
       {
         content: {
           type: "gtceu:sized"
           count: 2
           ingredient: {
             item: "gtceu:wrought_iron_dust"
           }
         }
         chance: 1
         tierChanceBoost: 0
       }
       {
         content: {
           type: "gtceu:sized"
           count: 1
           ingredient: {
-            item: "gtceu:steel_dust"
+            item: "gtceu:glass_dust"
           }
         }
         chance: 1
         tierChanceBoost: 0
       }
     ]
   }
   tickInputs: {
     eu: [
       {
         content: 8
         chance: 1
         tierChanceBoost: 0
       }
     ]
   }
   tickOutputs: {
   }
 }

```


</details>

<details>
<summary>gtceu/macerator/macerate_hv_electromagnetic_separator</summary>

```diff
 {
   type: "gtceu:macerator"
-  duration: 2030
+  duration: 2312
   inputs: {
     item: [
       {
         content: {
           type: "gtceu:sized"
           count: 1
           ingredient: {
             item: "gtceu:hv_electromagnetic_separator"
           }
         }
         chance: 1
         tierChanceBoost: 0
       }
     ]
   }
   outputs: {
     item: [
       {
         content: {
           type: "gtceu:sized"
           count: 14
           ingredient: {
             item: "gtceu:rubber_dust"
           }
         }
         chance: 1
         tierChanceBoost: 0
       }
       {
         content: {
           type: "gtceu:sized"
           count: 8
           ingredient: {
             item: "gtceu:electrum_dust"
           }
         }
         chance: 1
         tierChanceBoost: 0
       }
       {
         content: {
           type: "gtceu:sized"
           count: 6
           ingredient: {
             item: "gtceu:silver_dust"
           }
         }
         chance: 1
         tierChanceBoost: 0
       }
       {
         content: {
           type: "gtceu:sized"
           count: 2
           ingredient: {
-            item: "gtceu:stainless_steel_dust"
+            item: "gtceu:gold_dust"
           }
         }
         chance: 1
         tierChanceBoost: 0
       }
     ]
   }
   tickInputs: {
     eu: [
       {
         content: 8
         chance: 1
         tierChanceBoost: 0
       }
     ]
   }
   tickOutputs: {
   }
 }

```


</details>

<details>
<summary>gtceu/macerator/macerate_hv_forming_press</summary>

```diff
 {
   type: "gtceu:macerator"
-  duration: 2712
+  duration: 2356
   inputs: {
     item: [
       {
         content: {
           type: "gtceu:sized"
           count: 1
           ingredient: {
             item: "gtceu:hv_forming_press"
           }
         }
         chance: 1
         tierChanceBoost: 0
       }
     ]
   }
   outputs: {
     item: [
       {
         content: {
           type: "gtceu:sized"
           count: 12
           ingredient: {
             item: "gtceu:rubber_dust"
           }
         }
         chance: 1
         tierChanceBoost: 0
       }
       {
         content: {
           type: "gtceu:sized"
           count: 12
           ingredient: {
             item: "gtceu:stainless_steel_dust"
           }
         }
         chance: 1
         tierChanceBoost: 0
       }
       {
         content: {
           type: "gtceu:sized"
           count: 8
           ingredient: {
             item: "gtceu:electrum_dust"
           }
         }
         chance: 1
         tierChanceBoost: 0
       }
       {
         content: {
           type: "gtceu:sized"
           count: 4
           ingredient: {
-            item: "gtceu:gold_dust"
+            item: "gtceu:silver_dust"
           }
         }
         chance: 1
         tierChanceBoost: 0
       }
     ]
   }
   tickInputs: {
     eu: [
       {
         content: 8
         chance: 1
         tierChanceBoost: 0
       }
     ]
   }
   tickOutputs: {
   }
 }

```


</details>

<details>
<summary>gtceu/macerator/macerate_hv_laser_engraver</summary>

```diff
 {
   type: "gtceu:macerator"
-  duration: 2712
+  duration: 2356
   inputs: {
     item: [
       {
         content: {
           type: "gtceu:sized"
           count: 1
           ingredient: {
             item: "gtceu:hv_laser_engraver"
           }
         }
         chance: 1
         tierChanceBoost: 0
       }
     ]
   }
   outputs: {
     item: [
       {
         content: {
           type: "gtceu:sized"
           count: 12
           ingredient: {
             item: "gtceu:rubber_dust"
           }
         }
         chance: 1
         tierChanceBoost: 0
       }
       {
         content: {
           type: "gtceu:sized"
           count: 12
           ingredient: {
             item: "gtceu:stainless_steel_dust"
           }
         }
         chance: 1
         tierChanceBoost: 0
       }
       {
         content: {
           type: "gtceu:sized"
           count: 8
           ingredient: {
             item: "gtceu:electrum_dust"
           }
         }
         chance: 1
         tierChanceBoost: 0
       }
       {
         content: {
           type: "gtceu:sized"
           count: 4
           ingredient: {
-            item: "gtceu:gold_dust"
+            item: "gtceu:silver_dust"
           }
         }
         chance: 1
         tierChanceBoost: 0
       }
     ]
   }
   tickInputs: {
     eu: [
       {
         content: 8
         chance: 1
         tierChanceBoost: 0
       }
     ]
   }
   tickOutputs: {
   }
 }

```


</details>

<details>
<summary>gtceu/macerator/macerate_hv_muffler_hatch</summary>

```diff
 {
   type: "gtceu:macerator"
-  duration: 1058
+  duration: 1262
   inputs: {
     item: [
       {
         content: {
           type: "gtceu:sized"
           count: 1
           ingredient: {
             item: "gtceu:hv_muffler_hatch"
           }
         }
         chance: 1
         tierChanceBoost: 0
       }
     ]
   }
   outputs: {
     item: [
       {
         content: {
           type: "gtceu:sized"
           count: 4
           ingredient: {
             item: "gtceu:stainless_steel_dust"
           }
         }
         chance: 1
         tierChanceBoost: 0
       }
       {
         content: {
           type: "gtceu:sized"
           count: 4
           ingredient: {
             item: "gtceu:steel_dust"
           }
         }
         chance: 1
         tierChanceBoost: 0
       }
       {
         content: {
           type: "gtceu:sized"
           count: 4
           ingredient: {
             item: "gtceu:electrum_dust"
           }
         }
         chance: 1
         tierChanceBoost: 0
       }
       {
         content: {
           type: "gtceu:sized"
           count: 2
           ingredient: {
-            item: "gtceu:rubber_dust"
+            item: "gtceu:silver_dust"
           }
         }
         chance: 1
         tierChanceBoost: 0
       }
     ]
   }
   tickInputs: {
     eu: [
       {
         content: 8
         chance: 1
         tierChanceBoost: 0
       }
     ]
   }
   tickOutputs: {
   }
 }

```


</details>

<details>
<summary>gtceu/macerator/macerate_hv_world_accelerator</summary>

```diff
 {
   type: "gtceu:macerator"
-  duration: 3260
+  duration: 2888
   inputs: {
     item: [
       {
         content: {
           type: "gtceu:sized"
           count: 1
           ingredient: {
             item: "gtceu:hv_world_accelerator"
           }
         }
         chance: 1
         tierChanceBoost: 0
       }
     ]
   }
   outputs: {
     item: [
       {
         content: {
           type: "gtceu:sized"
           count: 32
           ingredient: {
             item: "gtceu:mercury_barium_calcium_cuprate_dust"
           }
         }
         chance: 1
         tierChanceBoost: 0
       }
       {
         content: {
           type: "gtceu:sized"
           count: 16
           ingredient: {
             item: "gtceu:stainless_steel_dust"
           }
         }
         chance: 1
         tierChanceBoost: 0
       }
       {
         content: {
           type: "gtceu:sized"
           count: 5
           ingredient: {
             item: "gtceu:chromium_dust"
           }
         }
         chance: 1
         tierChanceBoost: 0
       }
       {
         content: {
           type: "gtceu:sized"
           count: 4
           ingredient: {
-            item: "gtceu:ender_eye_dust"
+            item: "gtceu:rubber_dust"
           }
         }
         chance: 1
         tierChanceBoost: 0
       }
     ]
   }
   tickInputs: {
     eu: [
       {
         content: 32
         chance: 1
         tierChanceBoost: 0
       }
     ]
   }
   tickOutputs: {
   }
 }

```


</details>

<details>
<summary>gtceu/macerator/macerate_large_chemical_reactor</summary>

```diff
 {
   type: "gtceu:macerator"
-  duration: 1081
+  duration: 1285
   inputs: {
     item: [
       {
         content: {
           type: "gtceu:sized"
           count: 1
           ingredient: {
             item: "gtceu:large_chemical_reactor"
           }
         }
         chance: 1
         tierChanceBoost: 0
       }
     ]
   }
   outputs: {
     item: [
       {
         content: {
           type: "gtceu:sized"
           count: 12
           ingredient: {
             item: "gtceu:polytetrafluoroethylene_dust"
           }
         }
         chance: 1
         tierChanceBoost: 0
       }
       {
         content: {
           type: "gtceu:sized"
           count: 5
           ingredient: {
             item: "gtceu:stainless_steel_dust"
           }
         }
         chance: 1
         tierChanceBoost: 0
       }
       {
         content: {
           type: "gtceu:sized"
           count: 4
           ingredient: {
             item: "gtceu:electrum_dust"
           }
         }
         chance: 1
         tierChanceBoost: 0
       }
       {
         content: {
           type: "gtceu:sized"
           count: 2
           ingredient: {
-            item: "gtceu:rubber_dust"
+            item: "gtceu:silver_dust"
           }
         }
         chance: 1
         tierChanceBoost: 0
       }
     ]
   }
   tickInputs: {
     eu: [
       {
         content: 8
         chance: 1
         tierChanceBoost: 0
       }
     ]
   }
   tickOutputs: {
   }
 }

```


</details>

<details>
<summary>gtceu/macerator/macerate_lv_power_unit</summary>

```diff
 {
   type: "gtceu:macerator"
-  duration: 422
+  duration: 484
   inputs: {
     item: [
       {
         content: {
           type: "gtceu:sized"
           count: 1
           ingredient: {
             item: "gtceu:lv_power_unit"
           }
         }
         chance: 1
         tierChanceBoost: 0
       }
     ]
   }
   outputs: {
     item: [
       {
         content: {
           type: "gtceu:sized"
           count: 37
           ingredient: {
             item: "gtceu:tiny_steel_dust"
           }
         }
         chance: 1
         tierChanceBoost: 0
       }
       {
         content: {
           type: "gtceu:sized"
           count: 2
           ingredient: {
             item: "gtceu:rubber_dust"
           }
         }
         chance: 1
         tierChanceBoost: 0
       }
       {
         content: {
           type: "gtceu:sized"
           count: 2
           ingredient: {
             item: "gtceu:copper_dust"
           }
         }
         chance: 1
         tierChanceBoost: 0
       }
       {
         content: {
           type: "gtceu:sized"
           count: 1
           ingredient: {
-            item: "gtceu:iron_dust"
+            item: "gtceu:tin_dust"
           }
         }
         chance: 1
         tierChanceBoost: 0
       }
     ]
   }
   tickInputs: {
     eu: [
       {
         content: 8
         chance: 1
         tierChanceBoost: 0
       }
     ]
   }
   tickOutputs: {
   }
 }

```


</details>

<details>
<summary>gtceu/macerator/macerate_lv_sifter</summary>

```diff
 {
   type: "gtceu:macerator"
-  duration: 1564
+  duration: 1572
   inputs: {
     item: [
       {
         content: {
           type: "gtceu:sized"
           count: 1
           ingredient: {
             item: "gtceu:lv_sifter"
           }
         }
         chance: 1
         tierChanceBoost: 0
       }
     ]
   }
   outputs: {
     item: [
       {
         content: {
           type: "gtceu:sized"
           count: 12
           ingredient: {
             item: "gtceu:steel_dust"
           }
         }
         chance: 1
         tierChanceBoost: 0
       }
       {
         content: {
           type: "gtceu:sized"
           count: 10
           ingredient: {
             item: "gtceu:rubber_dust"
           }
         }
         chance: 1
         tierChanceBoost: 0
       }
       {
         content: {
           type: "gtceu:sized"
           count: 5
           ingredient: {
             item: "gtceu:tin_dust"
           }
         }
         chance: 1
         tierChanceBoost: 0
       }
       {
         content: {
           type: "gtceu:sized"
           count: 4
           ingredient: {
-            item: "gtceu:copper_dust"
+            item: "gtceu:zinc_dust"
           }
         }
         chance: 1
         tierChanceBoost: 0
       }
     ]
   }
   tickInputs: {
     eu: [
       {
         content: 8
         chance: 1
         tierChanceBoost: 0
       }
     ]
   }
   tickOutputs: {
   }
 }

```


</details>

<details>
<summary>gtceu/macerator/macerate_lv_world_accelerator</summary>

```diff
 {
   type: "gtceu:macerator"
-  duration: 2635
+  duration: 2575
   inputs: {
     item: [
       {
         content: {
           type: "gtceu:sized"
           count: 1
           ingredient: {
             item: "gtceu:lv_world_accelerator"
           }
         }
         chance: 1
         tierChanceBoost: 0
       }
     ]
   }
   outputs: {
     item: [
       {
         content: {
           type: "gtceu:sized"
           count: 32
           ingredient: {
             item: "gtceu:manganese_phosphide_dust"
           }
         }
         chance: 1
         tierChanceBoost: 0
       }
       {
         content: {
           type: "gtceu:sized"
           count: 16
           ingredient: {
             item: "gtceu:steel_dust"
           }
         }
         chance: 1
         tierChanceBoost: 0
       }
       {
         content: {
           type: "gtceu:sized"
           count: 5
           ingredient: {
             item: "gtceu:brass_dust"
           }
         }
         chance: 1
         tierChanceBoost: 0
       }
       {
         content: {
           type: "gtceu:sized"
           count: 4
           ingredient: {
-            item: "gtceu:quartzite_dust"
+            item: "gtceu:rubber_dust"
           }
         }
         chance: 1
         tierChanceBoost: 0
       }
     ]
   }
   tickInputs: {
     eu: [
       {
         content: 8
         chance: 1
         tierChanceBoost: 0
       }
     ]
   }
   tickOutputs: {
   }
 }

```


</details>

<details>
<summary>gtceu/macerator/macerate_mv_chemical_reactor</summary>

```diff
 {
   type: "gtceu:macerator"
-  duration: 604
+  duration: 690
   inputs: {
     item: [
       {
         content: {
           type: "gtceu:sized"
           count: 1
           ingredient: {
             item: "gtceu:mv_chemical_reactor"
           }
         }
         chance: 1
         tierChanceBoost: 0
       }
     ]
   }
   outputs: {
     item: [
       {
         content: {
           type: "gtceu:sized"
           count: 4
           ingredient: {
             item: "gtceu:cupronickel_dust"
           }
         }
         chance: 1
         tierChanceBoost: 0
       }
       {
         content: {
           type: "gtceu:sized"
           count: 4
           ingredient: {
             item: "gtceu:bronze_dust"
           }
         }
         chance: 1
         tierChanceBoost: 0
       }
       {
         content: {
           type: "gtceu:sized"
           count: 4
           ingredient: {
             item: "gtceu:rubber_dust"
           }
         }
         chance: 1
         tierChanceBoost: 0
       }
       {
         content: {
           type: "gtceu:sized"
           count: 2
           ingredient: {
-            item: "gtceu:glass_dust"
+            item: "gtceu:copper_dust"
           }
         }
         chance: 1
         tierChanceBoost: 0
       }
     ]
   }
   tickInputs: {
     eu: [
       {
         content: 8
         chance: 1
         tierChanceBoost: 0
       }
     ]
   }
   tickOutputs: {
   }
 }

```


</details>

<details>
<summary>gtceu/macerator/macerate_mv_mixer</summary>

```diff
 {
   type: "gtceu:macerator"
-  duration: 617
+  duration: 580
   inputs: {
     item: [
       {
         content: {
           type: "gtceu:sized"
           count: 1
           ingredient: {
             item: "gtceu:mv_mixer"
           }
         }
         chance: 1
         tierChanceBoost: 0
       }
     ]
   }
   outputs: {
     item: [
       {
         content: {
           type: "gtceu:sized"
           count: 4
           ingredient: {
             item: "gtceu:cupronickel_dust"
           }
         }
         chance: 1
         tierChanceBoost: 0
       }
       {
         content: {
           type: "gtceu:sized"
           count: 4
           ingredient: {
             item: "gtceu:bronze_dust"
           }
         }
         chance: 1
         tierChanceBoost: 0
       }
       {
         content: {
           type: "gtceu:sized"
           count: 2
           ingredient: {
             item: "gtceu:rubber_dust"
           }
         }
         chance: 1
         tierChanceBoost: 0
       }
       {
         content: {
           type: "gtceu:sized"
           count: 1
           ingredient: {
-            item: "gtceu:copper_dust"
+            item: "gtceu:aluminium_dust"
           }
         }
         chance: 1
         tierChanceBoost: 0
       }
     ]
   }
   tickInputs: {
     eu: [
       {
         content: 8
         chance: 1
         tierChanceBoost: 0
       }
     ]
   }
   tickOutputs: {
   }
 }

```


</details>

<details>
<summary>gtceu/macerator/macerate_naquadah_ore_to_raw_ore</summary>

```diff
 {
   type: "gtceu:macerator"
   duration: 400
   inputs: {
     item: [
       {
         content: {
           type: "forge:intersection"
           children: [
             {
               tag: "forge:ores/naquadah"
             }
             {
               tag: "forge:ores_in_ground/stone"
             }
           ]
         }
         chance: 1
         tierChanceBoost: 0
       }
     ]
   }
   outputs: {
     item: [
       {
         content: {
           type: "gtceu:sized"
           count: 2
           ingredient: {
             item: "gtceu:crushed_naquadah_ore"
           }
         }
         chance: 1
         tierChanceBoost: 0
       }
       {
         content: {
           type: "gtceu:sized"
           count: 1
           ingredient: {
-            item: "gtceu:sulfur_dust"
+            item: "vintageimprovements:sulfur"
           }
         }
         chance: 0.14
         tierChanceBoost: 0.085
       }
       {
         content: {
           type: "gtceu:sized"
           count: 1
           ingredient: {
             item: "gtceu:stone_dust"
           }
         }
         chance: 0.67
         tierChanceBoost: 0.08
       }
     ]
   }
   tickInputs: {
     eu: [
       {
         content: 2
         chance: 1
         tierChanceBoost: 0
       }
     ]
   }
   tickOutputs: {
   }
 }

```


</details>

<details>
<summary>gtceu/macerator/macerate_netherrack_chalcocite_ore_to_raw_ore</summary>

```diff
 {
   type: "gtceu:macerator"
   duration: 400
   inputs: {
     item: [
       {
         content: {
           type: "forge:intersection"
           children: [
             {
               tag: "forge:ores/chalcocite"
             }
             {
               tag: "forge:ores_in_ground/netherrack"
             }
           ]
         }
         chance: 1
         tierChanceBoost: 0
       }
     ]
   }
   outputs: {
     item: [
       {
         content: {
           type: "gtceu:sized"
           count: 4
           ingredient: {
             item: "gtceu:crushed_chalcocite_ore"
           }
         }
         chance: 1
         tierChanceBoost: 0
       }
       {
         content: {
           type: "gtceu:sized"
           count: 1
           ingredient: {
-            item: "gtceu:sulfur_dust"
+            item: "vintageimprovements:sulfur"
           }
         }
         chance: 0.14
         tierChanceBoost: 0.085
       }
       {
         content: {
           type: "gtceu:sized"
           count: 1
           ingredient: {
             item: "gtceu:netherrack_dust"
           }
         }
         chance: 0.67
         tierChanceBoost: 0.08
       }
     ]
   }
   tickInputs: {
     eu: [
       {
         content: 2
         chance: 1
         tierChanceBoost: 0
       }
     ]
   }
   tickOutputs: {
   }
 }

```


</details>

<details>
<summary>gtceu/macerator/macerate_netherrack_cobaltite_ore_to_raw_ore</summary>

```diff
 {
   type: "gtceu:macerator"
   duration: 400
   inputs: {
     item: [
       {
         content: {
           type: "forge:intersection"
           children: [
             {
               tag: "forge:ores/cobaltite"
             }
             {
               tag: "forge:ores_in_ground/netherrack"
             }
           ]
         }
         chance: 1
         tierChanceBoost: 0
       }
     ]
   }
   outputs: {
     item: [
       {
         content: {
           type: "gtceu:sized"
           count: 4
           ingredient: {
             item: "gtceu:crushed_cobaltite_ore"
           }
         }
         chance: 1
         tierChanceBoost: 0
       }
       {
         content: {
           type: "gtceu:sized"
           count: 1
           ingredient: {
-            item: "gtceu:sulfur_dust"
+            item: "vintageimprovements:sulfur"
           }
         }
         chance: 0.14
         tierChanceBoost: 0.085
       }
       {
         content: {
           type: "gtceu:sized"
           count: 1
           ingredient: {
             item: "gtceu:netherrack_dust"
           }
         }
         chance: 0.67
         tierChanceBoost: 0.08
       }
     ]
   }
   tickInputs: {
     eu: [
       {
         content: 2
         chance: 1
         tierChanceBoost: 0
       }
     ]
   }
   tickOutputs: {
   }
 }

```


</details>

<details>
<summary>gtceu/macerator/macerate_netherrack_galena_ore_to_raw_ore</summary>

```diff
 {
   type: "gtceu:macerator"
   duration: 400
   inputs: {
     item: [
       {
         content: {
           type: "forge:intersection"
           children: [
             {
               tag: "forge:ores/galena"
             }
             {
               tag: "forge:ores_in_ground/netherrack"
             }
           ]
         }
         chance: 1
         tierChanceBoost: 0
       }
     ]
   }
   outputs: {
     item: [
       {
         content: {
           type: "gtceu:sized"
           count: 4
           ingredient: {
             item: "gtceu:crushed_galena_ore"
           }
         }
         chance: 1
         tierChanceBoost: 0
       }
       {
         content: {
           type: "gtceu:sized"
           count: 1
           ingredient: {
-            item: "gtceu:sulfur_dust"
+            item: "vintageimprovements:sulfur"
           }
         }
         chance: 0.14
         tierChanceBoost: 0.085
       }
       {
         content: {
           type: "gtceu:sized"
           count: 1
           ingredient: {
             item: "gtceu:netherrack_dust"
           }
         }
         chance: 0.67
         tierChanceBoost: 0.08
       }
     ]
   }
   tickInputs: {
     eu: [
       {
         content: 2
         chance: 1
         tierChanceBoost: 0
       }
     ]
   }
   tickOutputs: {
   }
 }

```


</details>

<details>
<summary>gtceu/macerator/macerate_netherrack_gypsum_ore_to_raw_ore</summary>

```diff
 {
   type: "gtceu:macerator"
   duration: 400
   inputs: {
     item: [
       {
         content: {
           type: "forge:intersection"
           children: [
             {
               tag: "forge:ores/gypsum"
             }
             {
               tag: "forge:ores_in_ground/netherrack"
             }
           ]
         }
         chance: 1
         tierChanceBoost: 0
       }
     ]
   }
   outputs: {
     item: [
       {
         content: {
           type: "gtceu:sized"
           count: 4
           ingredient: {
             item: "gtceu:crushed_gypsum_ore"
           }
         }
         chance: 1
         tierChanceBoost: 0
       }
       {
         content: {
           type: "gtceu:sized"
           count: 1
           ingredient: {
-            item: "gtceu:sulfur_dust"
+            item: "vintageimprovements:sulfur"
           }
         }
         chance: 0.14
         tierChanceBoost: 0.085
       }
       {
         content: {
           type: "gtceu:sized"
           count: 1
           ingredient: {
             item: "gtceu:netherrack_dust"
           }
         }
         chance: 0.67
         tierChanceBoost: 0.08
       }
     ]
   }
   tickInputs: {
     eu: [
       {
         content: 2
         chance: 1
         tierChanceBoost: 0
       }
     ]
   }
   tickOutputs: {
   }
 }

```


</details>

<details>
<summary>gtceu/macerator/macerate_netherrack_naquadah_ore_to_raw_ore</summary>

```diff
 {
   type: "gtceu:macerator"
   duration: 400
   inputs: {
     item: [
       {
         content: {
           type: "forge:intersection"
           children: [
             {
               tag: "forge:ores/naquadah"
             }
             {
               tag: "forge:ores_in_ground/netherrack"
             }
           ]
         }
         chance: 1
         tierChanceBoost: 0
       }
     ]
   }
   outputs: {
     item: [
       {
         content: {
           type: "gtceu:sized"
           count: 4
           ingredient: {
             item: "gtceu:crushed_naquadah_ore"
           }
         }
         chance: 1
         tierChanceBoost: 0
       }
       {
         content: {
           type: "gtceu:sized"
           count: 1
           ingredient: {
-            item: "gtceu:sulfur_dust"
+            item: "vintageimprovements:sulfur"
           }
         }
         chance: 0.14
         tierChanceBoost: 0.085
       }
       {
         content: {
           type: "gtceu:sized"
           count: 1
           ingredient: {
             item: "gtceu:netherrack_dust"
           }
         }
         chance: 0.67
         tierChanceBoost: 0.08
       }
     ]
   }
   tickInputs: {
     eu: [
       {
         content: 2
         chance: 1
         tierChanceBoost: 0
       }
     ]
   }
   tickOutputs: {
   }
 }

```


</details>

<details>
<summary>gtceu/macerator/macerate_netherrack_pyrite_ore_to_raw_ore</summary>

```diff
 {
   type: "gtceu:macerator"
   duration: 400
   inputs: {
     item: [
       {
         content: {
           type: "forge:intersection"
           children: [
             {
               tag: "forge:ores/pyrite"
             }
             {
               tag: "forge:ores_in_ground/netherrack"
             }
           ]
         }
         chance: 1
         tierChanceBoost: 0
       }
     ]
   }
   outputs: {
     item: [
       {
         content: {
           type: "gtceu:sized"
           count: 4
           ingredient: {
             item: "gtceu:crushed_pyrite_ore"
           }
         }
         chance: 1
         tierChanceBoost: 0
       }
       {
         content: {
           type: "gtceu:sized"
           count: 1
           ingredient: {
-            item: "gtceu:sulfur_dust"
+            item: "vintageimprovements:sulfur"
           }
         }
         chance: 0.14
         tierChanceBoost: 0.085
       }
       {
         content: {
           type: "gtceu:sized"
           count: 1
           ingredient: {
             item: "gtceu:netherrack_dust"
           }
         }
         chance: 0.67
         tierChanceBoost: 0.08
       }
     ]
   }
   tickInputs: {
     eu: [
       {
         content: 2
         chance: 1
         tierChanceBoost: 0
       }
     ]
   }
   tickOutputs: {
   }
 }

```


</details>

<details>
<summary>gtceu/macerator/macerate_netherrack_realgar_ore_to_raw_ore</summary>

```diff
 {
   type: "gtceu:macerator"
   duration: 400
   inputs: {
     item: [
       {
         content: {
           type: "forge:intersection"
           children: [
             {
               tag: "forge:ores/realgar"
             }
             {
               tag: "forge:ores_in_ground/netherrack"
             }
           ]
         }
         chance: 1
         tierChanceBoost: 0
       }
     ]
   }
   outputs: {
     item: [
       {
         content: {
           type: "gtceu:sized"
           count: 4
           ingredient: {
             item: "gtceu:crushed_realgar_ore"
           }
         }
         chance: 1
         tierChanceBoost: 0
       }
       {
         content: {
           type: "gtceu:sized"
           count: 1
           ingredient: {
-            item: "gtceu:sulfur_dust"
+            item: "vintageimprovements:sulfur"
           }
         }
         chance: 0.14
         tierChanceBoost: 0.085
       }
       {
         content: {
           type: "gtceu:sized"
           count: 1
           ingredient: {
             item: "gtceu:netherrack_dust"
           }
         }
         chance: 0.67
         tierChanceBoost: 0.08
       }
     ]
   }
   tickInputs: {
     eu: [
       {
         content: 2
         chance: 1
         tierChanceBoost: 0
       }
     ]
   }
   tickOutputs: {
   }
 }

```


</details>

<details>
<summary>gtceu/macerator/macerate_netherrack_sulfur_ore_to_raw_ore</summary>

```diff
 {
   type: "gtceu:macerator"
   duration: 400
   inputs: {
     item: [
       {
         content: {
           type: "forge:intersection"
           children: [
             {
               tag: "forge:ores/sulfur"
             }
             {
               tag: "forge:ores_in_ground/netherrack"
             }
           ]
         }
         chance: 1
         tierChanceBoost: 0
       }
     ]
   }
   outputs: {
     item: [
       {
         content: {
           type: "gtceu:sized"
           count: 4
           ingredient: {
             item: "gtceu:crushed_sulfur_ore"
           }
         }
         chance: 1
         tierChanceBoost: 0
       }
       {
         content: {
           type: "gtceu:sized"
           count: 1
           ingredient: {
-            item: "gtceu:sulfur_dust"
+            item: "vintageimprovements:sulfur"
           }
         }
         chance: 0.14
         tierChanceBoost: 0.085
       }
       {
         content: {
           type: "gtceu:sized"
           count: 1
           ingredient: {
             item: "gtceu:netherrack_dust"
           }
         }
         chance: 0.67
         tierChanceBoost: 0.08
       }
     ]
   }
   tickInputs: {
     eu: [
       {
         content: 2
         chance: 1
         tierChanceBoost: 0
       }
     ]
   }
   tickOutputs: {
   }
 }

```


</details>

<details>
<summary>gtceu/macerator/macerate_pyrite_ore_to_raw_ore</summary>

```diff
 {
   type: "gtceu:macerator"
   duration: 400
   inputs: {
     item: [
       {
         content: {
           type: "forge:intersection"
           children: [
             {
               tag: "forge:ores/pyrite"
             }
             {
               tag: "forge:ores_in_ground/stone"
             }
           ]
         }
         chance: 1
         tierChanceBoost: 0
       }
     ]
   }
   outputs: {
     item: [
       {
         content: {
           type: "gtceu:sized"
           count: 2
           ingredient: {
             item: "gtceu:crushed_pyrite_ore"
           }
         }
         chance: 1
         tierChanceBoost: 0
       }
       {
         content: {
           type: "gtceu:sized"
           count: 1
           ingredient: {
-            item: "gtceu:sulfur_dust"
+            item: "vintageimprovements:sulfur"
           }
         }
         chance: 0.14
         tierChanceBoost: 0.085
       }
       {
         content: {
           type: "gtceu:sized"
           count: 1
           ingredient: {
             item: "gtceu:stone_dust"
           }
         }
         chance: 0.67
         tierChanceBoost: 0.08
       }
     ]
   }
   tickInputs: {
     eu: [
       {
         content: 2
         chance: 1
         tierChanceBoost: 0
       }
     ]
   }
   tickOutputs: {
   }
 }

```


</details>

<details>
<summary>gtceu/macerator/macerate_realgar_ore_to_raw_ore</summary>

```diff
 {
   type: "gtceu:macerator"
   duration: 400
   inputs: {
     item: [
       {
         content: {
           type: "forge:intersection"
           children: [
             {
               tag: "forge:ores/realgar"
             }
             {
               tag: "forge:ores_in_ground/stone"
             }
           ]
         }
         chance: 1
         tierChanceBoost: 0
       }
     ]
   }
   outputs: {
     item: [
       {
         content: {
           type: "gtceu:sized"
           count: 2
           ingredient: {
             item: "gtceu:crushed_realgar_ore"
           }
         }
         chance: 1
         tierChanceBoost: 0
       }
       {
         content: {
           type: "gtceu:sized"
           count: 1
           ingredient: {
-            item: "gtceu:sulfur_dust"
+            item: "vintageimprovements:sulfur"
           }
         }
         chance: 0.14
         tierChanceBoost: 0.085
       }
       {
         content: {
           type: "gtceu:sized"
           count: 1
           ingredient: {
             item: "gtceu:stone_dust"
           }
         }
         chance: 0.67
         tierChanceBoost: 0.08
       }
     ]
   }
   tickInputs: {
     eu: [
       {
         content: 2
         chance: 1
         tierChanceBoost: 0
       }
     ]
   }
   tickOutputs: {
   }
 }

```


</details>

<details>
<summary>gtceu/macerator/macerate_sapphire_lens</summary>

```diff
 {
   type: "gtceu:macerator"
   duration: 15
   inputs: {
     item: [
       {
         content: {
           type: "gtceu:sized"
           count: 1
           ingredient: {
-            tag: "forge:lenses/sapphire"
+            tag: "forge:lenses/blue"
           }
         }
         chance: 1
         tierChanceBoost: 0
       }
     ]
   }
   outputs: {
     item: [
       {
         content: {
           type: "gtceu:sized"
           count: 3
           ingredient: {
             item: "gtceu:small_sapphire_dust"
           }
         }
         chance: 1
         tierChanceBoost: 0
       }
     ]
   }
   tickInputs: {
     eu: [
       {
         content: 2
         chance: 1
         tierChanceBoost: 0
       }
     ]
   }
   tickOutputs: {
   }
 }

```


</details>

<details>
<summary>gtceu/macerator/macerate_sulfur_ore_to_raw_ore</summary>

```diff
 {
   type: "gtceu:macerator"
   duration: 400
   inputs: {
     item: [
       {
         content: {
           type: "forge:intersection"
           children: [
             {
               tag: "forge:ores/sulfur"
             }
             {
               tag: "forge:ores_in_ground/stone"
             }
           ]
         }
         chance: 1
         tierChanceBoost: 0
       }
     ]
   }
   outputs: {
     item: [
       {
         content: {
           type: "gtceu:sized"
           count: 2
           ingredient: {
             item: "gtceu:crushed_sulfur_ore"
           }
         }
         chance: 1
         tierChanceBoost: 0
       }
       {
         content: {
           type: "gtceu:sized"
           count: 1
           ingredient: {
-            item: "gtceu:sulfur_dust"
+            item: "vintageimprovements:sulfur"
           }
         }
         chance: 0.14
         tierChanceBoost: 0.085
       }
       {
         content: {
           type: "gtceu:sized"
           count: 1
           ingredient: {
             item: "gtceu:stone_dust"
           }
         }
         chance: 0.67
         tierChanceBoost: 0.08
       }
     ]
   }
   tickInputs: {
     eu: [
       {
         content: 2
         chance: 1
         tierChanceBoost: 0
       }
     ]
   }
   tickOutputs: {
   }
 }

```


</details>

<details>
<summary>gtceu/macerator/macerate_uv_rock_crusher</summary>

```diff
 {
   type: "gtceu:macerator"
-  duration: 1194
+  duration: 1233
   inputs: {
     item: [
       {
         content: {
           type: "gtceu:sized"
           count: 1
           ingredient: {
             item: "gtceu:uv_rock_crusher"
           }
         }
         chance: 1
         tierChanceBoost: 0
       }
     ]
   }
   outputs: {
     item: [
       {
         content: {
           type: "gtceu:sized"
           count: 8
           ingredient: {
             item: "gtceu:vanadium_steel_dust"
           }
         }
         chance: 1
         tierChanceBoost: 0
       }
       {
         content: {
           type: "gtceu:sized"
           count: 4
           ingredient: {
             item: "gtceu:tungsten_dust"
           }
         }
         chance: 1
         tierChanceBoost: 0
       }
       {
         content: {
           type: "gtceu:sized"
           count: 2
           ingredient: {
             item: "gtceu:rubber_dust"
           }
         }
         chance: 1
         tierChanceBoost: 0
       }
       {
         content: {
           type: "gtceu:sized"
           count: 1
           ingredient: {
-            item: "gtceu:diamond_dust"
+            item: "gtceu:yttrium_barium_cuprate_dust"
           }
         }
         chance: 1
         tierChanceBoost: 0
       }
     ]
   }
   tickInputs: {
     eu: [
       {
         content: 32
         chance: 1
         tierChanceBoost: 0
       }
     ]
   }
   tickOutputs: {
   }
 }

```


</details>

<details>
<summary>minecraft/fluorite_ingot_from_smelting</summary>

```diff
 {
   type: "minecraft:smelting"
   cookingtime: 150
   experience: 0.7
   ingredient: {
-    item: "thoriumreactors:fluorite"
+    tag: "forge:gems/fluorite"
   }
   result: "thoriumreactors:fluorite_ingot"
 }

```


</details>

<details>
<summary>minecraft/graphite_ingot_from_smelting</summary>

```diff
 {
   type: "minecraft:smelting"
   cookingtime: 150
   experience: 0.2
   ingredient: {
-    item: "thoriumreactors:graphite_crystal"
+    tag: "forge:raw_materials/graphite"
   }
   result: "thoriumreactors:graphite_ingot"
 }

```


</details>

<details>
<summary>minecraft/kjs/gtceu_brass_ingot</summary>

```diff
 {
   type: "minecraft:crafting_shapeless"
   result: {
     item: "gtceu:brass_ingot"
     count: 1
   }
   ingredients: [
     {
-      item: "alltheores:brass_ingot"
+      item: "tfc:metal/ingot/brass"
     }
   ]
 }

```


</details>

<details>
<summary>minecraft/kjs/gtceu_brass_ingot_2</summary>

```diff
 {
   type: "minecraft:crafting_shapeless"
   result: {
     item: "gtceu:brass_ingot"
     count: 1
   }
   ingredients: [
     {
-      item: "tfc:metal/ingot/brass"
+      item: "alltheores:brass_ingot"
     }
   ]
 }

```


</details>

<details>
<summary>minecraft/kjs/gtceu_bronze_ingot</summary>

```diff
 {
   type: "minecraft:crafting_shapeless"
   result: {
     item: "gtceu:bronze_ingot"
     count: 1
   }
   ingredients: [
     {
-      item: "alltheores:bronze_ingot"
+      item: "railcraft:bronze_ingot"
     }
   ]
 }

```


</details>

<details>
<summary>minecraft/kjs/gtceu_bronze_ingot_3</summary>

```diff
 {
   type: "minecraft:crafting_shapeless"
   result: {
     item: "gtceu:bronze_ingot"
     count: 1
   }
   ingredients: [
     {
-      item: "railcraft:bronze_ingot"
+      item: "alltheores:bronze_ingot"
     }
   ]
 }

```


</details>

<details>
<summary>minecraft/kjs/gtceu_gold_plate</summary>

```diff
 {
   type: "minecraft:crafting_shapeless"
   result: {
     item: "gtceu:gold_plate"
     count: 1
   }
   ingredients: [
     {
-      item: "create:golden_sheet"
+      item: "railcraft:gold_plate"
     }
   ]
 }

```


</details>

<details>
<summary>minecraft/kjs/gtceu_gold_plate_2</summary>

```diff
 {
   type: "minecraft:crafting_shapeless"
   result: {
     item: "gtceu:gold_plate"
     count: 1
   }
   ingredients: [
     {
-      item: "railcraft:gold_plate"
+      item: "create:golden_sheet"
     }
   ]
 }

```


</details>

<details>
<summary>minecraft/kjs/gtceu_lead_ingot</summary>

```diff
 {
   type: "minecraft:crafting_shapeless"
   result: {
     item: "gtceu:lead_ingot"
     count: 1
   }
   ingredients: [
     {
-      item: "alltheores:lead_ingot"
+      item: "railcraft:lead_ingot"
     }
   ]
 }

```


</details>

<details>
<summary>minecraft/kjs/gtceu_lead_ingot_2</summary>

```diff
 {
   type: "minecraft:crafting_shapeless"
   result: {
     item: "gtceu:lead_ingot"
     count: 1
   }
   ingredients: [
     {
-      item: "immersiveengineering:ingot_lead"
+      item: "alltheores:lead_ingot"
     }
   ]
 }

```


</details>

<details>
<summary>minecraft/kjs/gtceu_lead_ingot_3</summary>

```diff
 {
   type: "minecraft:crafting_shapeless"
   result: {
     item: "gtceu:lead_ingot"
     count: 1
   }
   ingredients: [
     {
-      item: "railcraft:lead_ingot"
+      item: "immersiveengineering:ingot_lead"
     }
   ]
 }

```


</details>

<details>
<summary>minecraft/kjs/gtceu_silver_ingot</summary>

```diff
 {
   type: "minecraft:crafting_shapeless"
   result: {
     item: "gtceu:silver_ingot"
     count: 1
   }
   ingredients: [
     {
-      item: "tfc:metal/ingot/silver"
+      item: "railcraft:silver_ingot"
     }
   ]
 }

```


</details>

<details>
<summary>minecraft/kjs/gtceu_silver_ingot_2</summary>

```diff
 {
   type: "minecraft:crafting_shapeless"
   result: {
     item: "gtceu:silver_ingot"
     count: 1
   }
   ingredients: [
     {
-      item: "alltheores:silver_ingot"
+      item: "tfc:metal/ingot/silver"
     }
   ]
 }

```


</details>

<details>
<summary>minecraft/kjs/gtceu_silver_ingot_3</summary>

```diff
 {
   type: "minecraft:crafting_shapeless"
   result: {
     item: "gtceu:silver_ingot"
     count: 1
   }
   ingredients: [
     {
-      item: "railcraft:silver_ingot"
+      item: "alltheores:silver_ingot"
     }
   ]
 }

```


</details>

<details>
<summary>minecraft/kjs/gtceu_silver_plate</summary>

```diff
 {
   type: "minecraft:crafting_shapeless"
   result: {
     item: "gtceu:silver_plate"
     count: 1
   }
   ingredients: [
     {
-      item: "tfc:metal/sheet/silver"
+      item: "railcraft:silver_plate"
     }
   ]
 }

```


</details>

<details>
<summary>minecraft/kjs/gtceu_silver_plate_2</summary>

```diff
 {
   type: "minecraft:crafting_shapeless"
   result: {
     item: "gtceu:silver_plate"
     count: 1
   }
   ingredients: [
     {
-      item: "alltheores:silver_plate"
+      item: "tfc:metal/sheet/silver"
     }
   ]
 }

```


</details>

<details>
<summary>minecraft/kjs/gtceu_silver_plate_3</summary>

```diff
 {
   type: "minecraft:crafting_shapeless"
   result: {
     item: "gtceu:silver_plate"
     count: 1
   }
   ingredients: [
     {
-      item: "railcraft:silver_plate"
+      item: "alltheores:silver_plate"
     }
   ]
 }

```


</details>

<details>
<summary>railcraft/block_signal</summary>

```diff
 {
   type: "minecraft:crafting_shaped"
   category: "misc"
   key: {
     a: {
       item: "railcraft:signal_lamp"
     }
     b: {
       item: "railcraft:signal_circuit"
     }
     c: {
       item: "tfc:metal/ingot/cast_iron"
     }
     d: {
-      item: "minecraft:ink_sac"
+      tag: "forge:dyes/black"
     }
   }
   pattern: [
     "abc"
     " dc"
   ]
   result: {
     item: "railcraft:block_signal"
   }
   show_notification: true
 }

```


</details>

<details>
<summary>railcraft/crusher/crushing_abyssal_brick_slab</summary>

```diff
 {
-  output: [
-    {
-      probability: 0.5
-      result: {
-        count: 1
-        item: "railcraft:abyssal_cobblestone"
-      }
-    }
-  ]
-  processTime: 200
+  outputs: [
+    {
+      probability: 0.5
+      result: {
+        item: "railcraft:abyssal_cobblestone"
+      }
+    }
+  ]
   type: "railcraft:crusher"
   ingredient: [
     {
       item: "railcraft:abyssal_brick_slab"
     }
     {
       item: "railcraft:abyssal_paver_slab"
     }
   ]
 }

```


</details>

<details>
<summary>railcraft/crusher/crushing_abyssal_brick_stairs</summary>

```diff
 {
-  output: [
-    {
-      probability: 0.75
-      result: {
-        count: 1
-        item: "railcraft:abyssal_cobblestone"
-      }
-    }
-  ]
-  processTime: 200
+  outputs: [
+    {
+      probability: 0.75
+      result: {
+        item: "railcraft:abyssal_cobblestone"
+      }
+    }
+  ]
   type: "railcraft:crusher"
   ingredient: [
     {
       item: "railcraft:abyssal_brick_stairs"
     }
     {
       item: "railcraft:abyssal_paver_stairs"
     }
   ]
 }

```


</details>

<details>
<summary>railcraft/crusher/crushing_amethyst_block</summary>

```diff
 {
-  output: [
-    {
-      probability: 1
-      result: {
-        count: 4
-        item: "minecraft:amethyst_shard"
-      }
-    }
-  ]
-  processTime: 200
+  outputs: [
+    {
+      count: 4
+      probability: 1
+      result: {
+        item: "minecraft:amethyst_shard"
+      }
+    }
+  ]
   type: "railcraft:crusher"
   ingredient: {
     item: "minecraft:amethyst_block"
   }
 }

```


</details>

<details>
<summary>railcraft/crusher/crushing_blast_furnace_bricks</summary>

```diff
 {
-  output: [
-    {
-      probability: 0.75
-      result: {
-        count: 1
-        item: "minecraft:nether_brick"
-      }
-    }
-    {
-      probability: 0.75
-      result: {
-        count: 1
-        item: "minecraft:soul_sand"
-      }
-    }
-    {
-      probability: 0.05
-      result: {
-        count: 1
-        item: "minecraft:blaze_powder"
-      }
-    }
-  ]
-  processTime: 200
+  outputs: [
+    {
+      probability: 0.75
+      result: {
+        item: "minecraft:nether_brick"
+      }
+    }
+    {
+      probability: 0.75
+      result: {
+        item: "minecraft:soul_sand"
+      }
+    }
+    {
+      probability: 0.05
+      result: {
+        item: "minecraft:blaze_powder"
+      }
+    }
+  ]
   type: "railcraft:crusher"
   ingredient: {
     item: "railcraft:blast_furnace_bricks"
   }
 }

```


</details>

<details>
<summary>railcraft/crusher/crushing_blaze_rod</summary>

```diff
 {
-  output: [
-    {
-      probability: 1
-      result: {
-        count: 2
-        item: "minecraft:blaze_powder"
-      }
-    }
-    {
-      probability: 0.65
-      result: {
-        count: 1
-        item: "minecraft:blaze_powder"
-      }
-    }
-    {
-      probability: 0.5
-      result: {
-        count: 1
-        item: "railcraft:sulfur_dust"
-      }
-    }
-    {
-      probability: 0.25
-      result: {
-        count: 1
-        item: "minecraft:blaze_powder"
-      }
-    }
-    {
-      probability: 0.25
-      result: {
-        count: 1
-        item: "minecraft:blaze_powder"
-      }
-    }
-  ]
-  processTime: 200
+  outputs: [
+    {
+      count: 2
+      probability: 1
+      result: {
+        item: "minecraft:blaze_powder"
+      }
+    }
+    {
+      probability: 0.65
+      result: {
+        item: "minecraft:blaze_powder"
+      }
+    }
+    {
+      probability: 0.5
+      result: {
+        item: "railcraft:sulfur_dust"
+      }
+    }
+    {
+      probability: 0.25
+      result: {
+        item: "minecraft:blaze_powder"
+      }
+    }
+    {
+      probability: 0.25
+      result: {
+        item: "minecraft:blaze_powder"
+      }
+    }
+  ]
   type: "railcraft:crusher"
   ingredient: {
     item: "minecraft:blaze_rod"
   }
 }

```


</details>

<details>
<summary>railcraft/crusher/crushing_bone</summary>

```diff
 {
-  output: [
-    {
-      probability: 1
-      result: {
-        count: 4
-        item: "minecraft:bone_meal"
-      }
-    }
-  ]
-  processTime: 200
+  outputs: [
+    {
+      count: 4
+      probability: 1
+      result: {
+        item: "minecraft:bone_meal"
+      }
+    }
+  ]
   type: "railcraft:crusher"
   ingredient: {
     item: "minecraft:bone"
   }
 }

```


</details>

<details>
<summary>railcraft/crusher/crushing_brick_slab</summary>

```diff
 {
-  output: [
-    {
-      probability: 1
-      result: {
-        count: 1
-        item: "minecraft:brick"
-      }
-    }
-    {
-      probability: 0.75
-      result: {
-        count: 1
-        item: "minecraft:brick"
-      }
-    }
-  ]
-  processTime: 200
+  outputs: [
+    {
+      probability: 1
+      result: {
+        item: "minecraft:brick"
+      }
+    }
+    {
+      probability: 0.75
+      result: {
+        item: "minecraft:brick"
+      }
+    }
+  ]
   type: "railcraft:crusher"
   ingredient: {
     item: "minecraft:brick_slab"
   }
 }

```


</details>

<details>
<summary>railcraft/crusher/crushing_brick_stairs</summary>

```diff
 {
-  output: [
-    {
-      probability: 1
-      result: {
-        count: 4
-        item: "minecraft:brick"
-      }
-    }
-    {
-      probability: 0.5
-      result: {
-        count: 1
-        item: "minecraft:brick"
-      }
-    }
-    {
-      probability: 0.5
-      result: {
-        count: 1
-        item: "minecraft:brick"
-      }
-    }
-  ]
-  processTime: 200
+  outputs: [
+    {
+      count: 4
+      probability: 1
+      result: {
+        item: "minecraft:brick"
+      }
+    }
+    {
+      probability: 0.5
+      result: {
+        item: "minecraft:brick"
+      }
+    }
+    {
+      probability: 0.5
+      result: {
+        item: "minecraft:brick"
+      }
+    }
+  ]
   type: "railcraft:crusher"
   ingredient: {
     item: "minecraft:brick_stairs"
   }
 }

```


</details>

<details>
<summary>railcraft/crusher/crushing_bricks</summary>

```diff
 {
-  output: [
-    {
-      probability: 1
-      result: {
-        count: 3
-        item: "minecraft:brick"
-      }
-    }
-    {
-      probability: 0.5
-      result: {
-        count: 1
-        item: "minecraft:brick"
-      }
-    }
-  ]
-  processTime: 200
+  outputs: [
+    {
+      count: 3
+      probability: 1
+      result: {
+        item: "minecraft:brick"
+      }
+    }
+    {
+      probability: 0.5
+      result: {
+        item: "minecraft:brick"
+      }
+    }
+  ]
   type: "railcraft:crusher"
   ingredient: {
     item: "minecraft:bricks"
   }
 }

```


</details>

<details>
<summary>railcraft/crusher/crushing_charcoal</summary>

```diff
 {
-  output: [
-    {
-      probability: 1
-      result: {
-        count: 1
-        item: "railcraft:charcoal_dust"
-      }
-    }
-  ]
-  processTime: 200
+  outputs: [
+    {
+      probability: 1
+      result: {
+        item: "railcraft:charcoal_dust"
+      }
+    }
+  ]
   type: "railcraft:crusher"
   ingredient: {
     tag: "forge:gems/charcoal"
   }
 }

```


</details>

<details>
<summary>railcraft/crusher/crushing_clay</summary>

```diff
 {
-  output: [
-    {
-      probability: 1
-      result: {
-        count: 4
-        item: "minecraft:clay_ball"
-      }
-    }
-  ]
-  processTime: 200
+  outputs: [
+    {
+      count: 4
+      probability: 1
+      result: {
+        item: "minecraft:clay_ball"
+      }
+    }
+  ]
   type: "railcraft:crusher"
   ingredient: {
     item: "minecraft:clay"
   }
 }

```


</details>

<details>
<summary>railcraft/crusher/crushing_coal</summary>

```diff
 {
-  output: [
-    {
-      probability: 1
-      result: {
-        count: 1
-        item: "railcraft:coal_dust"
-      }
-    }
-  ]
-  processTime: 200
+  outputs: [
+    {
+      probability: 1
+      result: {
+        item: "railcraft:coal_dust"
+      }
+    }
+  ]
   type: "railcraft:crusher"
   ingredient: {
     tag: "forge:gems/coal"
   }
 }

```


</details>

<details>
<summary>railcraft/crusher/crushing_coal_block</summary>

```diff
 {
-  output: [
-    {
-      probability: 1
-      result: {
-        count: 9
-        item: "railcraft:coal_dust"
-      }
-    }
-  ]
-  processTime: 200
+  outputs: [
+    {
+      count: 9
+      probability: 1
+      result: {
+        item: "railcraft:coal_dust"
+      }
+    }
+  ]
   type: "railcraft:crusher"
   ingredient: {
     tag: "forge:storage_blocks/coal"
   }
 }

```


</details>

<details>
<summary>railcraft/crusher/crushing_crushed_obsidian</summary>

```diff
 {
-  output: [
-    {
-      probability: 1
-      result: {
-        count: 1
-        item: "railcraft:obsidian_dust"
-      }
-    }
-    {
-      probability: 0.25
-      result: {
-        count: 1
-        item: "railcraft:obsidian_dust"
-      }
-    }
-  ]
-  processTime: 200
+  outputs: [
+    {
+      probability: 1
+      result: {
+        item: "railcraft:obsidian_dust"
+      }
+    }
+    {
+      probability: 0.25
+      result: {
+        item: "railcraft:obsidian_dust"
+      }
+    }
+  ]
   type: "railcraft:crusher"
   ingredient: {
     item: "railcraft:crushed_obsidian"
   }
 }

```


</details>

<details>
<summary>railcraft/crusher/crushing_dark_prismarine</summary>

```diff
 {
-  output: [
-    {
-      probability: 1
-      result: {
-        count: 8
-        item: "minecraft:prismarine_shard"
-      }
-    }
-  ]
-  processTime: 200
+  outputs: [
+    {
+      count: 8
+      probability: 1
+      result: {
+        item: "minecraft:prismarine_shard"
+      }
+    }
+  ]
   type: "railcraft:crusher"
   ingredient: {
     item: "minecraft:dark_prismarine"
   }
 }

```


</details>

<details>
<summary>railcraft/crusher/crushing_ender_pearl</summary>

```diff
 {
-  output: [
-    {
-      probability: 1
-      result: {
-        count: 1
-        item: "railcraft:ender_dust"
-      }
-    }
-  ]
-  processTime: 200
+  outputs: [
+    {
+      probability: 1
+      result: {
+        item: "railcraft:ender_dust"
+      }
+    }
+  ]
   type: "railcraft:crusher"
   ingredient: {
     item: "minecraft:ender_pearl"
   }
 }

```


</details>

<details>
<summary>railcraft/crusher/crushing_firestone_ore</summary>

```diff
 {
-  output: [
-    {
-      probability: 1
-      result: {
-        count: 1
-        item: "railcraft:raw_firestone"
-      }
-    }
-  ]
-  processTime: 200
+  outputs: [
+    {
+      probability: 1
+      result: {
+        item: "railcraft:raw_firestone"
+      }
+    }
+  ]
   type: "railcraft:crusher"
   ingredient: {
     item: "railcraft:firestone_ore"
   }
 }

```


</details>

<details>
<summary>railcraft/crusher/crushing_glowstone</summary>

```diff
 {
-  output: [
-    {
-      probability: 1
-      result: {
-        count: 3
-        item: "minecraft:glowstone_dust"
-      }
-    }
-    {
-      probability: 0.75
-      result: {
-        count: 1
-        item: "minecraft:glowstone_dust"
-      }
-    }
-  ]
-  processTime: 200
+  outputs: [
+    {
+      count: 3
+      probability: 1
+      result: {
+        item: "minecraft:glowstone_dust"
+      }
+    }
+    {
+      probability: 0.75
+      result: {
+        item: "minecraft:glowstone_dust"
+      }
+    }
+  ]
   type: "railcraft:crusher"
   ingredient: {
     item: "minecraft:glowstone"
   }
 }

```


</details>

<details>
<summary>railcraft/crusher/crushing_gravel</summary>

```diff
 {
-  output: [
-    {
-      probability: 1
-      result: {
-        count: 1
-        item: "minecraft:sand"
-      }
-    }
-    {
-      probability: 0.001
-      result: {
-        count: 1
-        item: "minecraft:gold_nugget"
-      }
-    }
-    {
-      probability: 0.00005
-      result: {
-        count: 1
-        item: "minecraft:diamond"
-      }
-    }
-  ]
-  processTime: 200
+  outputs: [
+    {
+      probability: 1
+      result: {
+        item: "minecraft:sand"
+      }
+    }
+    {
+      probability: 0.001
+      result: {
+        item: "minecraft:gold_nugget"
+      }
+    }
+    {
+      probability: 0.00005
+      result: {
+        item: "minecraft:diamond"
+      }
+    }
+  ]
   type: "railcraft:crusher"
   ingredient: {
     item: "minecraft:gravel"
   }
 }

```


</details>

<details>
<summary>railcraft/crusher/crushing_ice</summary>

```diff
 {
-  output: [
-    {
-      probability: 0.85
-      result: {
-        count: 1
-        item: "minecraft:snow_block"
-      }
-    }
-    {
-      probability: 0.25
-      result: {
-        count: 1
-        item: "minecraft:snowball"
-      }
-    }
-  ]
-  processTime: 200
+  outputs: [
+    {
+      probability: 0.85
+      result: {
+        item: "minecraft:snow_block"
+      }
+    }
+    {
+      probability: 0.25
+      result: {
+        item: "minecraft:snowball"
+      }
+    }
+  ]
   type: "railcraft:crusher"
   ingredient: {
     item: "minecraft:ice"
   }
 }

```


</details>

<details>
<summary>railcraft/crusher/crushing_nether_brick_fence</summary>

```diff
 {
-  output: [
-    {
-      probability: 1
-      result: {
-        count: 1
-        item: "minecraft:nether_brick"
-      }
-    }
-  ]
-  processTime: 200
+  outputs: [
+    {
+      probability: 1
+      result: {
+        item: "minecraft:nether_brick"
+      }
+    }
+  ]
   type: "railcraft:crusher"
   ingredient: {
     item: "minecraft:nether_brick_fence"
   }
 }

```


</details>

<details>
<summary>railcraft/crusher/crushing_nether_brick_stairs</summary>

```diff
 {
-  output: [
-    {
-      probability: 1
-      result: {
-        count: 1
-        item: "minecraft:nether_brick"
-      }
-    }
-  ]
-  processTime: 200
+  outputs: [
+    {
+      probability: 1
+      result: {
+        item: "minecraft:nether_brick"
+      }
+    }
+  ]
   type: "railcraft:crusher"
   ingredient: {
     item: "minecraft:nether_brick_stairs"
   }
 }

```


</details>

<details>
<summary>railcraft/crusher/crushing_nether_wart_block</summary>

```diff
 {
-  output: [
-    {
-      probability: 1
-      result: {
-        count: 9
-        item: "minecraft:nether_wart"
-      }
-    }
-  ]
-  processTime: 200
+  outputs: [
+    {
+      count: 9
+      probability: 1
+      result: {
+        item: "minecraft:nether_wart"
+      }
+    }
+  ]
   type: "railcraft:crusher"
   ingredient: {
     item: "minecraft:nether_wart_block"
   }
 }

```


</details>

<details>
<summary>railcraft/crusher/crushing_obsidian</summary>

```diff
 {
-  output: [
-    {
-      probability: 1
-      result: {
-        count: 1
-        item: "railcraft:crushed_obsidian"
-      }
-    }
-    {
-      probability: 0.25
-      result: {
-        count: 1
-        item: "railcraft:obsidian_dust"
-      }
-    }
-  ]
-  processTime: 200
+  outputs: [
+    {
+      probability: 1
+      result: {
+        item: "railcraft:crushed_obsidian"
+      }
+    }
+    {
+      probability: 0.25
+      result: {
+        item: "railcraft:obsidian_dust"
+      }
+    }
+  ]
   type: "railcraft:crusher"
   ingredient: {
     item: "minecraft:obsidian"
   }
 }

```


</details>

<details>
<summary>railcraft/crusher/crushing_prismarine</summary>

```diff
 {
-  output: [
-    {
-      probability: 1
-      result: {
-        count: 4
-        item: "minecraft:prismarine_shard"
-      }
-    }
-  ]
-  processTime: 200
+  outputs: [
+    {
+      count: 4
+      probability: 1
+      result: {
+        item: "minecraft:prismarine_shard"
+      }
+    }
+  ]
   type: "railcraft:crusher"
   ingredient: {
     item: "minecraft:prismarine"
   }
 }

```


</details>

<details>
<summary>railcraft/crusher/crushing_prismarine_bricks</summary>

```diff
 {
-  output: [
-    {
-      probability: 1
-      result: {
-        count: 9
-        item: "minecraft:prismarine_shard"
-      }
-    }
-  ]
-  processTime: 200
+  outputs: [
+    {
+      count: 9
+      probability: 1
+      result: {
+        item: "minecraft:prismarine_shard"
+      }
+    }
+  ]
   type: "railcraft:crusher"
   ingredient: {
     item: "minecraft:prismarine_bricks"
   }
 }

```


</details>

<details>
<summary>railcraft/crusher/crushing_quarried_brick_slab</summary>

```diff
 {
-  output: [
-    {
-      probability: 0.5
-      result: {
-        count: 1
-        item: "railcraft:quarried_cobblestone"
-      }
-    }
-  ]
-  processTime: 200
+  outputs: [
+    {
+      probability: 0.5
+      result: {
+        item: "railcraft:quarried_cobblestone"
+      }
+    }
+  ]
   type: "railcraft:crusher"
   ingredient: [
     {
       item: "railcraft:quarried_brick_slab"
     }
     {
       item: "railcraft:quarried_paver_slab"
     }
   ]
 }

```


</details>

<details>
<summary>railcraft/crusher/crushing_quarried_brick_stairs</summary>

```diff
 {
-  output: [
-    {
-      probability: 0.75
-      result: {
-        count: 1
-        item: "railcraft:quarried_cobblestone"
-      }
-    }
-  ]
-  processTime: 200
+  outputs: [
+    {
+      probability: 0.75
+      result: {
+        item: "railcraft:quarried_cobblestone"
+      }
+    }
+  ]
   type: "railcraft:crusher"
   ingredient: [
     {
       item: "railcraft:quarried_brick_stairs"
     }
     {
       item: "railcraft:quarried_paver_stairs"
     }
   ]
 }

```


</details>

<details>
<summary>railcraft/crusher/crushing_raw_gold_block</summary>

```diff
 {
-  output: [
-    {
-      probability: 1
-      result: {
-        count: 9
-        item: "minecraft:raw_gold"
-      }
-    }
-  ]
-  processTime: 200
+  outputs: [
+    {
+      count: 9
+      probability: 1
+      result: {
+        item: "minecraft:raw_gold"
+      }
+    }
+  ]
   type: "railcraft:crusher"
   ingredient: {
     tag: "forge:storage_blocks/raw_gold"
   }
 }

```


</details>

<details>
<summary>railcraft/crusher/crushing_raw_iron_block</summary>

```diff
 {
-  output: [
-    {
-      probability: 1
-      result: {
-        count: 9
-        item: "minecraft:raw_iron"
-      }
-    }
-  ]
-  processTime: 200
+  outputs: [
+    {
+      count: 9
+      probability: 1
+      result: {
+        item: "minecraft:raw_iron"
+      }
+    }
+  ]
   type: "railcraft:crusher"
   ingredient: {
     tag: "forge:storage_blocks/raw_iron"
   }
 }

```


</details>

<details>
<summary>railcraft/crusher/crushing_redstone_lamp</summary>

```diff
 {
-  output: [
-    {
-      probability: 1
-      result: {
-        count: 3
-        item: "minecraft:glowstone_dust"
-      }
-    }
-    {
-      probability: 0.75
-      result: {
-        count: 1
-        item: "minecraft:glowstone_dust"
-      }
-    }
-    {
-      probability: 1
-      result: {
-        count: 3
-        item: "minecraft:redstone"
-      }
-    }
-    {
-      probability: 0.75
-      result: {
-        count: 1
-        item: "minecraft:redstone"
-      }
-    }
-  ]
-  processTime: 200
+  outputs: [
+    {
+      count: 3
+      probability: 1
+      result: {
+        item: "minecraft:glowstone_dust"
+      }
+    }
+    {
+      probability: 0.75
+      result: {
+        item: "minecraft:glowstone_dust"
+      }
+    }
+    {
+      count: 3
+      probability: 1
+      result: {
+        item: "minecraft:redstone"
+      }
+    }
+    {
+      probability: 0.75
+      result: {
+        item: "minecraft:redstone"
+      }
+    }
+  ]
   type: "railcraft:crusher"
   ingredient: {
     item: "minecraft:redstone_lamp"
   }
 }

```


</details>

<details>
<summary>railcraft/crusher/crushing_sandstone_slab</summary>

```diff
 {
-  output: [
-    {
-      probability: 0.45
-      result: {
-        count: 1
-        item: "minecraft:sand"
-      }
-    }
-  ]
-  processTime: 200
+  outputs: [
+    {
+      probability: 0.45
+      result: {
+        item: "minecraft:sand"
+      }
+    }
+  ]
   type: "railcraft:crusher"
   ingredient: {
     item: "minecraft:sandstone_slab"
   }
 }

```


</details>

<details>
<summary>railcraft/crusher/crushing_stone_brick_stairs</summary>

```diff
 {
-  output: [
-    {
-      probability: 1
-      result: {
-        count: 1
-        item: "minecraft:cobblestone"
-      }
-    }
-  ]
-  processTime: 200
+  outputs: [
+    {
+      probability: 1
+      result: {
+        item: "minecraft:cobblestone"
+      }
+    }
+  ]
   type: "railcraft:crusher"
   ingredient: {
     item: "minecraft:stone_brick_stairs"
   }
 }

```


</details>

<details>
<summary>railcraft/crusher/crushing_stone_slab</summary>

```diff
 {
-  output: [
-    {
-      probability: 0.45
-      result: {
-        count: 1
-        item: "minecraft:cobblestone"
-      }
-    }
-  ]
-  processTime: 200
+  outputs: [
+    {
+      probability: 0.45
+      result: {
+        item: "minecraft:cobblestone"
+      }
+    }
+  ]
   type: "railcraft:crusher"
   ingredient: [
     {
       item: "minecraft:stone_slab"
     }
     {
       item: "minecraft:stone_brick_slab"
     }
   ]
 }

```


</details>

<details>
<summary>railcraft/crusher/crushing_tags_abyssal</summary>

```diff
 {
-  output: [
-    {
-      probability: 1
-      result: {
-        count: 1
-        item: "railcraft:abyssal_cobblestone"
-      }
-    }
-  ]
-  processTime: 200
+  conditions: [
+    {
+      type: "forge:not"
+      value: {
+        type: "forge:tag_empty"
+        tag: "railcraft:abyssal"
+      }
+    }
+  ]
+  outputs: [
+    {
+      probability: 1
+      result: {
+        item: "railcraft:abyssal_cobblestone"
+      }
+    }
+  ]
   type: "railcraft:crusher"
   ingredient: {
     tag: "railcraft:abyssal"
   }
 }

```


</details>

<details>
<summary>railcraft/crusher/crushing_tags_ores_coal</summary>

```diff
 {
-  output: [
-    {
-      probability: 1
-      result: {
-        count: 2
-        item: "railcraft:coal_dust"
-      }
-    }
-    {
-      probability: 0.65
-      result: {
-        count: 1
-        item: "railcraft:coal_dust"
-      }
-    }
-    {
-      probability: 0.15
-      result: {
-        count: 1
-        item: "minecraft:coal"
-      }
-    }
-    {
-      probability: 0.001
-      result: {
-        count: 1
-        item: "minecraft:diamond"
-      }
-    }
-  ]
-  processTime: 200
+  conditions: [
+    {
+      type: "forge:not"
+      value: {
+        type: "forge:tag_empty"
+        tag: "forge:ores/coal"
+      }
+    }
+  ]
+  outputs: [
+    {
+      count: 2
+      probability: 1
+      result: {
+        item: "railcraft:coal_dust"
+      }
+    }
+    {
+      probability: 0.65
+      result: {
+        item: "railcraft:coal_dust"
+      }
+    }
+    {
+      probability: 0.15
+      result: {
+        item: "railcraft:sulfur_dust"
+      }
+    }
+    {
+      probability: 0.15
+      result: {
+        item: "minecraft:coal"
+      }
+    }
+    {
+      probability: 0.001
+      result: {
+        item: "minecraft:diamond"
+      }
+    }
+  ]
   type: "railcraft:crusher"
   ingredient: {
     tag: "forge:ores/coal"
   }
 }

```


</details>

<details>
<summary>railcraft/crusher/crushing_tags_ores_diamond</summary>

```diff
 {
-  output: [
-    {
-      probability: 1
-      result: {
-        count: 1
-        item: "minecraft:diamond"
-      }
-    }
-    {
-      probability: 0.85
-      result: {
-        count: 1
-        item: "minecraft:diamond"
-      }
-    }
-    {
-      probability: 0.25
-      result: {
-        count: 1
-        item: "minecraft:diamond"
-      }
-    }
-    {
-      probability: 0.1
-      result: {
-        count: 1
-        item: "minecraft:coal"
-      }
-    }
-  ]
-  processTime: 200
+  conditions: [
+    {
+      type: "forge:not"
+      value: {
+        type: "forge:tag_empty"
+        tag: "forge:ores/diamond"
+      }
+    }
+  ]
+  outputs: [
+    {
+      probability: 1
+      result: {
+        item: "minecraft:diamond"
+      }
+    }
+    {
+      probability: 0.85
+      result: {
+        item: "minecraft:diamond"
+      }
+    }
+    {
+      probability: 0.25
+      result: {
+        item: "minecraft:diamond"
+      }
+    }
+    {
+      probability: 0.1
+      result: {
+        item: "minecraft:coal"
+      }
+    }
+  ]
   type: "railcraft:crusher"
   ingredient: {
     tag: "forge:ores/diamond"
   }
 }

```


</details>

<details>
<summary>railcraft/crusher/crushing_tags_ores_emerald</summary>

```diff
 {
-  output: [
-    {
-      probability: 1
-      result: {
-        count: 1
-        item: "minecraft:emerald"
-      }
-    }
-    {
-      probability: 0.85
-      result: {
-        count: 1
-        item: "minecraft:emerald"
-      }
-    }
-    {
-      probability: 0.25
-      result: {
-        count: 1
-        item: "minecraft:emerald"
-      }
-    }
-  ]
-  processTime: 200
+  conditions: [
+    {
+      type: "forge:not"
+      value: {
+        type: "forge:tag_empty"
+        tag: "forge:ores/emerald"
+      }
+    }
+  ]
+  outputs: [
+    {
+      probability: 1
+      result: {
+        item: "minecraft:emerald"
+      }
+    }
+    {
+      probability: 0.85
+      result: {
+        item: "minecraft:emerald"
+      }
+    }
+    {
+      probability: 0.25
+      result: {
+        item: "minecraft:emerald"
+      }
+    }
+  ]
   type: "railcraft:crusher"
   ingredient: {
     tag: "forge:ores/emerald"
   }
 }

```


</details>

<details>
<summary>railcraft/crusher/crushing_tags_ores_lapis</summary>

```diff
 {
-  output: [
-    {
-      probability: 1
-      result: {
-        count: 8
-        item: "minecraft:lapis_lazuli"
-      }
-    }
-    {
-      probability: 0.85
-      result: {
-        count: 1
-        item: "minecraft:lapis_lazuli"
-      }
-    }
-    {
-      probability: 0.35
-      result: {
-        count: 1
-        item: "minecraft:lapis_lazuli"
-      }
-    }
-  ]
-  processTime: 200
+  conditions: [
+    {
+      type: "forge:not"
+      value: {
+        type: "forge:tag_empty"
+        tag: "forge:ores/lapis"
+      }
+    }
+  ]
+  outputs: [
+    {
+      count: 8
+      probability: 1
+      result: {
+        item: "minecraft:lapis_lazuli"
+      }
+    }
+    {
+      probability: 0.85
+      result: {
+        item: "minecraft:lapis_lazuli"
+      }
+    }
+    {
+      probability: 0.35
+      result: {
+        item: "minecraft:lapis_lazuli"
+      }
+    }
+    {
+      probability: 0.2
+      result: {
+        item: "railcraft:sulfur_dust"
+      }
+    }
+  ]
   type: "railcraft:crusher"
   ingredient: {
     tag: "forge:ores/lapis"
   }
 }

```


</details>

<details>
<summary>railcraft/crusher/crushing_tags_ores_quartz</summary>

```diff
 {
-  output: [
-    {
-      probability: 1
-      result: {
-        count: 3
-        item: "minecraft:quartz"
-      }
-    }
-    {
-      probability: 0.25
-      result: {
-        count: 1
-        item: "railcraft:sulfur_dust"
-      }
-    }
-  ]
-  processTime: 200
+  conditions: [
+    {
+      type: "forge:not"
+      value: {
+        type: "forge:tag_empty"
+        tag: "forge:ores/quartz"
+      }
+    }
+  ]
+  outputs: [
+    {
+      count: 3
+      probability: 1
+      result: {
+        item: "minecraft:quartz"
+      }
+    }
+    {
+      probability: 0.25
+      result: {
+        item: "railcraft:sulfur_dust"
+      }
+    }
+  ]
   type: "railcraft:crusher"
   ingredient: {
     tag: "forge:ores/quartz"
   }
 }

```


</details>

<details>
<summary>railcraft/crusher/crushing_tags_ores_redstone</summary>

```diff
 {
-  output: [
-    {
-      probability: 1
-      result: {
-        count: 6
-        item: "minecraft:redstone"
-      }
-    }
-    {
-      probability: 0.85
-      result: {
-        count: 2
-        item: "minecraft:redstone"
-      }
-    }
-    {
-      probability: 0.25
-      result: {
-        count: 1
-        item: "minecraft:redstone"
-      }
-    }
-    {
-      probability: 0.1
-      result: {
-        count: 1
-        item: "minecraft:glowstone_dust"
-      }
-    }
-  ]
-  processTime: 200
+  conditions: [
+    {
+      type: "forge:not"
+      value: {
+        type: "forge:tag_empty"
+        tag: "forge:ores/redstone"
+      }
+    }
+  ]
+  outputs: [
+    {
+      count: 6
+      probability: 1
+      result: {
+        item: "minecraft:redstone"
+      }
+    }
+    {
+      count: 2
+      probability: 0.85
+      result: {
+        item: "minecraft:redstone"
+      }
+    }
+    {
+      probability: 0.25
+      result: {
+        item: "minecraft:redstone"
+      }
+    }
+    {
+      probability: 0.1
+      result: {
+        item: "minecraft:glowstone_dust"
+      }
+    }
+  ]
   type: "railcraft:crusher"
   ingredient: {
     tag: "forge:ores/redstone"
   }
 }

```


</details>

<details>
<summary>railcraft/crusher/crushing_tags_ores_sulfur</summary>

```diff
 {
-  output: [
-    {
-      probability: 1
-      result: {
-        count: 5
-        item: "railcraft:sulfur_dust"
-      }
-    }
-    {
-      probability: 0.85
-      result: {
-        count: 1
-        item: "railcraft:sulfur_dust"
-      }
-    }
-    {
-      probability: 0.35
-      result: {
-        count: 1
-        item: "railcraft:sulfur_dust"
-      }
-    }
-  ]
-  processTime: 200
+  conditions: [
+    {
+      type: "forge:not"
+      value: {
+        type: "forge:tag_empty"
+        tag: "forge:ores/sulfur"
+      }
+    }
+  ]
+  outputs: [
+    {
+      count: 5
+      probability: 1
+      result: {
+        item: "railcraft:sulfur_dust"
+      }
+    }
+    {
+      probability: 0.85
+      result: {
+        item: "railcraft:sulfur_dust"
+      }
+    }
+    {
+      probability: 0.35
+      result: {
+        item: "railcraft:sulfur_dust"
+      }
+    }
+  ]
   type: "railcraft:crusher"
   ingredient: {
     tag: "forge:ores/sulfur"
   }
 }

```


</details>

<details>
<summary>railcraft/crusher/crushing_tags_quarried</summary>

```diff
 {
-  output: [
-    {
-      probability: 1
-      result: {
-        count: 1
-        item: "railcraft:quarried_cobblestone"
-      }
-    }
-  ]
-  processTime: 200
+  conditions: [
+    {
+      type: "forge:not"
+      value: {
+        type: "forge:tag_empty"
+        tag: "railcraft:quarried"
+      }
+    }
+  ]
+  outputs: [
+    {
+      probability: 1
+      result: {
+        item: "railcraft:quarried_cobblestone"
+      }
+    }
+  ]
   type: "railcraft:crusher"
   ingredient: {
     tag: "railcraft:quarried"
   }
 }

```


</details>

<details>
<summary>railcraft/crusher/crushing_tags_sandstone</summary>

```diff
 {
-  output: [
-    {
-      probability: 1
-      result: {
-        count: 4
-        item: "minecraft:sand"
-      }
-    }
-  ]
-  processTime: 200
+  conditions: [
+    {
+      type: "forge:not"
+      value: {
+        type: "forge:tag_empty"
+        tag: "forge:sandstone"
+      }
+    }
+  ]
+  outputs: [
+    {
+      count: 4
+      probability: 1
+      result: {
+        item: "minecraft:sand"
+      }
+    }
+  ]
   type: "railcraft:crusher"
   ingredient: {
     tag: "forge:sandstone"
   }
 }

```


</details>

<details>
<summary>railcraft/crusher/crushing_tags_stone</summary>

```diff
 {
-  output: [
-    {
-      probability: 1
-      result: {
-        count: 1
-        item: "minecraft:cobblestone"
-      }
-    }
-  ]
-  processTime: 200
+  conditions: [
+    {
+      type: "forge:not"
+      value: {
+        type: "forge:tag_empty"
+        tag: "forge:stone"
+      }
+    }
+  ]
+  outputs: [
+    {
+      probability: 1
+      result: {
+        item: "minecraft:cobblestone"
+      }
+    }
+  ]
   type: "railcraft:crusher"
   ingredient: {
     tag: "forge:stone"
   }
 }

```


</details>

<details>
<summary>railcraft/crusher/crushing_tags_stone_bricks</summary>

```diff
 {
-  output: [
-    {
-      probability: 1
-      result: {
-        count: 1
-        item: "minecraft:cobblestone"
-      }
-    }
-  ]
-  processTime: 200
+  conditions: [
+    {
+      type: "forge:not"
+      value: {
+        type: "forge:tag_empty"
+        tag: "minecraft:stone_bricks"
+      }
+    }
+  ]
+  outputs: [
+    {
+      probability: 1
+      result: {
+        item: "minecraft:cobblestone"
+      }
+    }
+  ]
   type: "railcraft:crusher"
   ingredient: {
     tag: "minecraft:stone_bricks"
   }
 }

```


</details>

<details>
<summary>railcraft/crusher/crushing_tags_wool</summary>

```diff
 {
-  output: [
-    {
-      probability: 1
-      result: {
-        count: 4
-        item: "minecraft:string"
-      }
-    }
-  ]
-  processTime: 200
+  conditions: [
+    {
+      type: "forge:not"
+      value: {
+        type: "forge:tag_empty"
+        tag: "minecraft:wool"
+      }
+    }
+  ]
+  outputs: [
+    {
+      count: 4
+      probability: 1
+      result: {
+        item: "minecraft:string"
+      }
+    }
+  ]
   type: "railcraft:crusher"
   ingredient: {
     tag: "minecraft:wool"
   }
 }

```


</details>

<details>
<summary>railcraft/distant_signal</summary>

```diff
 {
   type: "minecraft:crafting_shaped"
   category: "misc"
   key: {
     a: {
       item: "railcraft:signal_lamp"
     }
     b: {
       item: "railcraft:receiver_circuit"
     }
     c: {
       item: "tfc:metal/ingot/cast_iron"
     }
     d: {
-      item: "minecraft:ink_sac"
+      tag: "forge:dyes/black"
     }
   }
   pattern: [
     "abc"
     " dc"
   ]
   result: {
     item: "railcraft:distant_signal"
   }
   show_notification: true
 }

```


</details>

<details>
<summary>railcraft/dual_block_signal</summary>

```diff
 {
   type: "minecraft:crafting_shaped"
   category: "misc"
   key: {
     a: {
       item: "railcraft:signal_lamp"
     }
     b: {
       item: "railcraft:signal_circuit"
     }
     c: {
       item: "tfc:metal/ingot/cast_iron"
     }
     d: {
-      item: "minecraft:ink_sac"
+      tag: "forge:dyes/black"
     }
     e: {
       item: "railcraft:receiver_circuit"
     }
   }
   pattern: [
     "abc"
     " dc"
     "aec"
   ]
   result: {
     item: "railcraft:dual_block_signal"
   }
   show_notification: true
 }

```


</details>

<details>
<summary>railcraft/dual_distant_signal</summary>

```diff
 {
   type: "minecraft:crafting_shaped"
   category: "misc"
   key: {
     a: {
       item: "railcraft:signal_lamp"
     }
     b: {
       item: "railcraft:receiver_circuit"
     }
     c: {
       item: "tfc:metal/ingot/cast_iron"
     }
     d: {
-      item: "minecraft:ink_sac"
+      tag: "forge:dyes/black"
     }
     e: {
       item: "railcraft:receiver_circuit"
     }
   }
   pattern: [
     "abc"
     " dc"
     "aec"
   ]
   result: {
     item: "railcraft:dual_distant_signal"
   }
   show_notification: true
 }

```


</details>

<details>
<summary>railcraft/dual_token_signal</summary>

```diff
 {
   type: "minecraft:crafting_shaped"
   category: "misc"
   key: {
     a: {
       item: "railcraft:signal_lamp"
     }
     b: {
       item: "railcraft:radio_circuit"
     }
     c: {
       item: "tfc:metal/ingot/cast_iron"
     }
     d: {
-      item: "minecraft:ink_sac"
+      tag: "forge:dyes/black"
     }
     e: {
       item: "railcraft:receiver_circuit"
     }
   }
   pattern: [
     "abc"
     " dc"
     "aec"
   ]
   result: {
     item: "railcraft:dual_token_signal"
   }
   show_notification: true
 }

```


</details>

<details>
<summary>railcraft/high_speed_electric_junction_track</summary>

```diff
 {
   type: "minecraft:crafting_shaped"
   category: "misc"
   key: {
     a: {
       item: "railcraft:high_speed_rail"
     }
     b: {
       item: "railcraft:electric_rail"
     }
     c: {
       item: "railcraft:stone_railbed"
     }
   }
   pattern: [
     "aba"
     "aba"
-    "aca"
+    "bcb"
   ]
   result: {
     count: 16
     item: "railcraft:high_speed_electric_junction_track"
   }
   show_notification: true
 }

```


</details>

<details>
<summary>railcraft/item_loader</summary>

```diff
 {
   type: "minecraft:crafting_shaped"
   category: "misc"
   key: {
     a: {
       item: "minecraft:cobblestone"
     }
     b: {
       item: "minecraft:hopper"
     }
     c: {
-      item: "railcraft:detector_track_kit"
+      item: "railcraft:item_detector"
     }
   }
   pattern: [
     "aaa"
     "aba"
     "aca"
   ]
   result: {
     item: "railcraft:item_loader"
   }
   show_notification: true
 }

```


</details>

<details>
<summary>railcraft/item_unloader</summary>

```diff
 {
   type: "minecraft:crafting_shaped"
   category: "misc"
   key: {
     a: {
       item: "minecraft:cobblestone"
     }
     b: {
-      item: "railcraft:detector_track_kit"
+      item: "railcraft:item_detector"
     }
     c: {
       item: "minecraft:hopper"
     }
   }
   pattern: [
     "aaa"
     "aba"
     "aca"
   ]
   result: {
     item: "railcraft:item_unloader"
   }
   show_notification: true
 }

```


</details>

<details>
<summary>railcraft/rolling/advanced_rail</summary>

```diff
 {
-  processTime: 100
   type: "railcraft:rolling"
   key: {
     a: {
       tag: "forge:dusts/redstone"
     }
     b: {
       tag: "forge:ingots/gold"
     }
   }
   pattern: [
     "a b"
     "a b"
     "a b"
   ]
   result: {
     count: 8
     item: "railcraft:advanced_rail"
   }
 }

```


</details>

<details>
<summary>railcraft/rolling/black_post</summary>

```diff
 {
-  processTime: 100
   type: "railcraft:rolling"
   key: {
     a: {
       tag: "forge:ingots/iron"
     }
   }
   pattern: [
     "a a"
     "aaa"
     "a a"
   ]
   result: {
     count: 16
     item: "railcraft:black_post"
   }
 }

```


</details>

<details>
<summary>railcraft/rolling/brass_electrode</summary>

```diff
 {
-  processTime: 100
   type: "railcraft:rolling"
   key: {
     a: {
       tag: "forge:plates/brass"
     }
   }
   pattern: [
     " a "
     " a "
     " a "
   ]
   result: {
     item: "railcraft:brass_electrode"
   }
 }

```


</details>

<details>
<summary>railcraft/rolling/bronze_electrode</summary>

```diff
 {
-  processTime: 100
   type: "railcraft:rolling"
   key: {
     a: {
       tag: "forge:plates/bronze"
     }
   }
   pattern: [
     " a "
     " a "
     " a "
   ]
   result: {
     item: "railcraft:bronze_electrode"
   }
 }

```


</details>

<details>
<summary>railcraft/rolling/bronze_rail</summary>

```diff
 {
-  processTime: 100
   type: "railcraft:rolling"
   key: {
     a: {
       tag: "forge:ingots/bronze"
     }
     b: {
       tag: "forge:ingots/bronze"
     }
   }
   pattern: [
     "a b"
     "a b"
     "a b"
   ]
   result: {
     count: 8
     item: "railcraft:standard_rail"
   }
 }

```


</details>

<details>
<summary>railcraft/rolling/carbon_electrode</summary>

```diff
 {
-  processTime: 100
   type: "railcraft:rolling"
   key: {
     a: [
       {
         tag: "forge:gems/coal"
       }
       {
         tag: "forge:gems/charcoal"
       }
     ]
   }
   pattern: [
     " a "
     " a "
     " a "
   ]
   result: {
     item: "railcraft:carbon_electrode"
   }
 }

```


</details>

<details>
<summary>railcraft/rolling/charge_spool_large</summary>

```diff
 {
-  processTime: 100
   type: "railcraft:rolling"
   key: {
     a: {
       tag: "forge:storage_blocks/copper"
     }
   }
   pattern: [
     "a"
   ]
   result: {
     item: "railcraft:charge_spool_large"
   }
 }

```


</details>

<details>
<summary>railcraft/rolling/charge_spool_small</summary>

```diff
 {
-  processTime: 100
   type: "railcraft:rolling"
   key: {
     a: {
       tag: "forge:ingots/copper"
     }
   }
   pattern: [
     "a"
   ]
   result: {
     item: "railcraft:charge_spool_small"
   }
 }

```


</details>

<details>
<summary>railcraft/rolling/copper_electric_rail</summary>

```diff
 {
-  processTime: 100
   type: "railcraft:rolling"
   key: {
     a: {
       tag: "forge:ingots/copper"
     }
     b: {
       tag: "forge:ingots/copper"
     }
   }
   pattern: [
     "a b"
     "a b"
     "a b"
   ]
   result: {
     count: 6
     item: "railcraft:electric_rail"
   }
 }

```


</details>

<details>
<summary>railcraft/rolling/copper_electrode</summary>

```diff
 {
-  processTime: 100
   type: "railcraft:rolling"
   key: {
     a: {
       tag: "forge:plates/copper"
     }
   }
   pattern: [
     " a "
     " a "
     " a "
   ]
   result: {
     item: "railcraft:copper_electrode"
   }
 }

```


</details>

<details>
<summary>railcraft/rolling/electric_rail</summary>

```diff
 {
-  processTime: 100
   type: "railcraft:rolling"
   key: {
     a: {
       tag: "forge:ingots/steel"
     }
     b: {
       tag: "forge:ingots/copper"
     }
     c: {
       tag: "forge:ingots/steel"
     }
   }
   pattern: [
     "abc"
     "abc"
     "abc"
   ]
   result: {
     count: 12
     item: "railcraft:electric_rail"
   }
 }

```


</details>

<details>
<summary>railcraft/rolling/gold_electrode</summary>

```diff
 {
-  processTime: 100
   type: "railcraft:rolling"
   key: {
     a: {
       tag: "forge:plates/gold"
     }
   }
   pattern: [
     " a "
     " a "
     " a "
   ]
   result: {
     item: "railcraft:gold_electrode"
   }
 }

```


</details>

<details>
<summary>railcraft/rolling/invar_electrode</summary>

```diff
 {
-  processTime: 100
   type: "railcraft:rolling"
   key: {
     a: {
       tag: "forge:plates/invar"
     }
   }
   pattern: [
     " a "
     " a "
     " a "
   ]
   result: {
     item: "railcraft:invar_electrode"
   }
 }

```


</details>

<details>
<summary>railcraft/rolling/invar_rail</summary>

```diff
 {
-  processTime: 100
   type: "railcraft:rolling"
   key: {
     a: {
       tag: "forge:ingots/invar"
     }
     b: {
       tag: "forge:ingots/invar"
     }
   }
   pattern: [
     "a b"
     "a b"
     "a b"
   ]
   result: {
     count: 12
     item: "railcraft:standard_rail"
   }
 }

```


</details>

<details>
<summary>railcraft/rolling/invar_reinforced_rail</summary>

```diff
 {
-  processTime: 100
   type: "railcraft:rolling"
   key: {
     a: {
       tag: "forge:ingots/invar"
     }
     b: {
       tag: "forge:dusts/obsidian"
     }
     c: {
       tag: "forge:ingots/invar"
     }
   }
   pattern: [
     "abc"
     "abc"
     "abc"
   ]
   result: {
     count: 4
     item: "railcraft:reinforced_rail"
   }
 }

```


</details>

<details>
<summary>railcraft/rolling/iron_electrode</summary>

```diff
 {
-  processTime: 100
   type: "railcraft:rolling"
   key: {
     a: {
       tag: "forge:plates/iron"
     }
   }
   pattern: [
     " a "
     " a "
     " a "
   ]
   result: {
     item: "railcraft:iron_electrode"
   }
 }

```


</details>

<details>
<summary>railcraft/rolling/lead_electrode</summary>

```diff
 {
-  processTime: 100
   type: "railcraft:rolling"
   key: {
     a: {
       tag: "forge:plates/lead"
     }
   }
   pattern: [
     " a "
     " a "
     " a "
   ]
   result: {
     item: "railcraft:lead_electrode"
   }
 }

```


</details>

<details>
<summary>railcraft/rolling/nickel_electrode</summary>

```diff
 {
-  processTime: 100
   type: "railcraft:rolling"
   key: {
     a: {
       tag: "forge:plates/nickel"
     }
   }
   pattern: [
     " a "
     " a "
     " a "
   ]
   result: {
     item: "railcraft:nickel_electrode"
   }
 }

```


</details>

<details>
<summary>railcraft/rolling/nickel_turbine_blade</summary>

```diff
 {
-  processTime: 100
   type: "railcraft:rolling"
   key: {
     a: {
       tag: "forge:plates/nickel"
     }
   }
   pattern: [
     "  a"
     " a "
     "a  "
   ]
   result: {
     item: "railcraft:turbine_blade"
   }
 }

```


</details>

<details>
<summary>railcraft/rolling/rebar_bronze</summary>

```diff
 {
-  processTime: 100
   type: "railcraft:rolling"
   key: {
     a: {
       tag: "forge:ingots/bronze"
     }
   }
   pattern: [
     "  a"
     " a "
     "a  "
   ]
   result: {
     count: 4
     item: "railcraft:rebar"
   }
 }

```


</details>

<details>
<summary>railcraft/rolling/rebar_invar</summary>

```diff
 {
-  processTime: 100
   type: "railcraft:rolling"
   key: {
     a: {
       tag: "forge:ingots/invar"
     }
   }
   pattern: [
     "  a"
     " a "
     "a  "
   ]
   result: {
     count: 6
     item: "railcraft:rebar"
   }
 }

```


</details>

<details>
<summary>railcraft/rolling/rebar_iron</summary>

```diff
 {
-  processTime: 100
   type: "railcraft:rolling"
   key: {
     a: {
       tag: "forge:ingots/iron"
     }
   }
   pattern: [
     "  a"
     " a "
     "a  "
   ]
   result: {
     count: 4
     item: "railcraft:rebar"
   }
 }

```


</details>

<details>
<summary>railcraft/rolling/rebar_steel</summary>

```diff
 {
-  processTime: 100
   type: "railcraft:rolling"
   key: {
     a: {
       tag: "forge:ingots/steel"
     }
   }
   pattern: [
     "  a"
     " a "
     "a  "
   ]
   result: {
     count: 8
     item: "railcraft:rebar"
   }
 }

```


</details>

<details>
<summary>railcraft/rolling/silver_electrode</summary>

```diff
 {
-  processTime: 100
   type: "railcraft:rolling"
   key: {
     a: {
       tag: "forge:plates/silver"
     }
   }
   pattern: [
     " a "
     " a "
     " a "
   ]
   result: {
     item: "railcraft:silver_electrode"
   }
 }

```


</details>

<details>
<summary>railcraft/rolling/standard_high_speed_rail</summary>

```diff
 {
-  processTime: 100
   type: "railcraft:rolling"
   key: {
     a: {
       tag: "forge:ingots/steel"
     }
     b: {
       item: "minecraft:blaze_powder"
     }
     c: {
       tag: "forge:ingots/gold"
     }
   }
   pattern: [
     "abc"
     "abc"
     "abc"
   ]
   result: {
     count: 8
     item: "railcraft:high_speed_rail"
   }
 }

```


</details>

<details>
<summary>railcraft/rolling/standard_rail</summary>

```diff
 {
-  processTime: 100
   type: "railcraft:rolling"
   key: {
     a: {
       tag: "forge:ingots/iron"
     }
     b: {
       tag: "forge:ingots/iron"
     }
   }
   pattern: [
     "a b"
     "a b"
     "a b"
   ]
   result: {
     count: 8
     item: "railcraft:standard_rail"
   }
 }

```


</details>

<details>
<summary>railcraft/rolling/steel_electrode</summary>

```diff
 {
-  processTime: 100
   type: "railcraft:rolling"
   key: {
     a: {
       tag: "forge:plates/steel"
     }
   }
   pattern: [
     " a "
     " a "
     " a "
   ]
   result: {
     item: "railcraft:steel_electrode"
   }
 }

```


</details>

<details>
<summary>railcraft/rolling/steel_rail</summary>

```diff
 {
-  processTime: 100
   type: "railcraft:rolling"
   key: {
     a: {
       tag: "forge:ingots/steel"
     }
     b: {
       tag: "forge:ingots/steel"
     }
   }
   pattern: [
     "a b"
     "a b"
     "a b"
   ]
   result: {
     count: 16
     item: "railcraft:standard_rail"
   }
 }

```


</details>

<details>
<summary>railcraft/rolling/steel_reinforced_rail</summary>

```diff
 {
-  processTime: 100
   type: "railcraft:rolling"
   key: {
     a: {
       tag: "forge:ingots/steel"
     }
     b: {
       tag: "forge:dusts/obsidian"
     }
     c: {
       tag: "forge:ingots/steel"
     }
   }
   pattern: [
     "abc"
     "abc"
     "abc"
   ]
   result: {
     count: 8
     item: "railcraft:reinforced_rail"
   }
 }

```


</details>

<details>
<summary>railcraft/rolling/steel_turbine_blade</summary>

```diff
 {
-  processTime: 100
   type: "railcraft:rolling"
   key: {
     a: {
       tag: "forge:plates/steel"
     }
   }
   pattern: [
     "  a"
     " a "
     "a  "
   ]
   result: {
     item: "railcraft:turbine_blade"
   }
 }

```


</details>

<details>
<summary>railcraft/rolling/tin_electrode</summary>

```diff
 {
-  processTime: 100
   type: "railcraft:rolling"
   key: {
     a: {
       tag: "forge:plates/tin"
     }
   }
   pattern: [
     " a "
     " a "
     " a "
   ]
   result: {
     item: "railcraft:tin_electrode"
   }
 }

```


</details>

<details>
<summary>railcraft/rolling/track_parts_bronze_nugget</summary>

```diff
 {
-  processTime: 100
   type: "railcraft:rolling"
   key: {
     a: {
       tag: "forge:nuggets/bronze"
     }
   }
   pattern: [
     "aa "
     "a  "
   ]
   result: {
     item: "railcraft:track_parts"
   }
 }

```


</details>

<details>
<summary>railcraft/rolling/track_parts_iron_nugget</summary>

```diff
 {
-  processTime: 100
   type: "railcraft:rolling"
   key: {
     a: {
       tag: "forge:nuggets/iron"
     }
   }
   pattern: [
     "aa"
   ]
   result: {
     item: "railcraft:track_parts"
   }
 }

```


</details>

<details>
<summary>railcraft/rolling/track_parts_steel_nugget</summary>

```diff
 {
-  processTime: 100
   type: "railcraft:rolling"
   key: {
     a: {
       tag: "forge:nuggets/steel"
     }
   }
   pattern: [
     "a"
   ]
   result: {
     item: "railcraft:track_parts"
   }
 }

```


</details>

<details>
<summary>railcraft/rolling/zinc_electrode</summary>

```diff
 {
-  processTime: 100
   type: "railcraft:rolling"
   key: {
     a: {
       tag: "forge:plates/zinc"
     }
   }
   pattern: [
     " a "
     " a "
     " a "
   ]
   result: {
     item: "railcraft:zinc_electrode"
   }
 }

```


</details>

<details>
<summary>railcraft/signal_lamp</summary>

```diff
 {
   type: "minecraft:crafting_shaped"
   category: "misc"
   key: {
     a: {
       item: "minecraft:glass_pane"
     }
     b: {
-      item: "minecraft:lime_dye"
+      tag: "forge:dyes/lime"
     }
     c: {
-      item: "minecraft:yellow_dye"
+      tag: "forge:dyes/yellow"
     }
     d: {
-      item: "minecraft:red_dye"
+      tag: "forge:dyes/red"
     }
     e: {
       item: "minecraft:glowstone_dust"
     }
     f: {
       item: "minecraft:redstone"
     }
   }
   pattern: [
     "ab "
     "ace"
     "adf"
   ]
   result: {
     item: "railcraft:signal_lamp"
   }
   show_notification: true
 }

```


</details>

<details>
<summary>railcraft/switch_track_lever</summary>

```diff
 {
   type: "minecraft:crafting_shaped"
   category: "misc"
   key: {
     a: {
-      item: "minecraft:red_dye"
+      tag: "forge:dyes/red"
     }
     b: {
-      item: "minecraft:ink_sac"
+      tag: "forge:dyes/black"
     }
     c: {
       item: "minecraft:bone_meal"
     }
     d: {
       item: "minecraft:piston"
     }
     e: {
       item: "minecraft:lever"
     }
     f: {
       item: "tfc:metal/ingot/cast_iron"
     }
   }
   pattern: [
     "abc"
     "def"
   ]
   result: {
     item: "railcraft:switch_track_lever"
   }
   show_notification: true
 }

```


</details>

<details>
<summary>railcraft/switch_track_motor</summary>

```diff
 {
   type: "minecraft:crafting_shaped"
   category: "misc"
   key: {
     a: {
-      item: "minecraft:red_dye"
+      tag: "forge:dyes/red"
     }
     b: {
-      item: "minecraft:ink_sac"
+      tag: "forge:dyes/black"
     }
     c: {
       item: "minecraft:bone_meal"
     }
     d: {
       item: "minecraft:piston"
     }
     e: {
       item: "railcraft:receiver_circuit"
     }
     f: {
       item: "tfc:metal/ingot/cast_iron"
     }
   }
   pattern: [
     "abc"
     "def"
   ]
   result: {
     item: "railcraft:switch_track_motor"
   }
   show_notification: true
 }

```


</details>

<details>
<summary>railcraft/switch_track_router</summary>

```diff
 {
   type: "minecraft:crafting_shapeless"
   category: "misc"
   ingredients: [
     {
       item: "railcraft:switch_track_motor"
     }
     {
-      item: "minecraft:comparator"
+      item: "railcraft:routing_detector"
     }
   ]
   result: {
     item: "railcraft:switch_track_router"
   }
 }

```


</details>

<details>
<summary>railcraft/throttle_track_kit</summary>

```diff
 {
   type: "minecraft:crafting_shapeless"
   category: "misc"
   ingredients: [
     {
       tag: "minecraft:planks"
     }
     {
       item: "railcraft:track_parts"
     }
     {
       tag: "forge:dyes/yellow"
     }
-    {
-      item: "minecraft:ink_sac"
-    }
     {
       tag: "forge:dusts/redstone"
     }
+    {
+      tag: "forge:dyes/black"
+    }
   ]
   result: {
     count: 4
     item: "railcraft:throttle_track_kit"
   }
 }

```


</details>

<details>
<summary>railcraft/token_signal</summary>

```diff
 {
   type: "minecraft:crafting_shaped"
   category: "misc"
   key: {
     a: {
       item: "railcraft:signal_lamp"
     }
     b: {
       item: "railcraft:radio_circuit"
     }
     c: {
       item: "tfc:metal/ingot/cast_iron"
     }
     d: {
-      item: "minecraft:ink_sac"
+      tag: "forge:dyes/black"
     }
   }
   pattern: [
     "abc"
     " dc"
   ]
   result: {
     item: "railcraft:token_signal"
   }
   show_notification: true
 }

```


</details>

<details>
<summary>railcraft/track_layer</summary>

```diff
 {
   type: "minecraft:crafting_shaped"
   category: "misc"
   key: {
     a: {
-      item: "minecraft:yellow_dye"
+      tag: "forge:dyes/yellow"
     }
     b: {
       item: "minecraft:redstone_lamp"
     }
     c: {
       item: "tfc:metal/anvil/wrought_iron"
     }
     d: {
       tag: "forge:storage_blocks/steel"
     }
     e: {
       item: "minecraft:dispenser"
     }
     f: {
       item: "minecraft:minecart"
     }
   }
   pattern: [
     "aba"
     "cdc"
     "efe"
   ]
   result: {
     item: "railcraft:track_layer"
   }
   show_notification: true
 }

```


</details>

<details>
<summary>railcraft/track_relayer</summary>

```diff
 {
   type: "minecraft:crafting_shaped"
   category: "misc"
   key: {
     a: {
-      item: "minecraft:yellow_dye"
+      tag: "forge:dyes/yellow"
     }
     b: {
       item: "minecraft:redstone_lamp"
     }
     c: {
       item: "minecraft:blaze_rod"
     }
     d: {
       tag: "forge:storage_blocks/steel"
     }
     e: {
       item: "minecraft:diamond_pickaxe"
     }
     f: {
       item: "minecraft:minecart"
     }
   }
   pattern: [
     "aba"
     "cdc"
     "efe"
   ]
   result: {
     item: "railcraft:track_relayer"
   }
   show_notification: true
 }

```


</details>

<details>
<summary>railcraft/track_remover</summary>

```diff
 {
   type: "minecraft:crafting_shaped"
   category: "misc"
   key: {
     a: {
-      item: "minecraft:yellow_dye"
+      tag: "forge:dyes/yellow"
     }
     b: {
       item: "minecraft:redstone_lamp"
     }
     c: {
       item: "minecraft:sticky_piston"
     }
     d: {
       tag: "forge:storage_blocks/steel"
     }
     e: {
       tag: "railcraft:crowbar"
     }
     f: {
       item: "minecraft:minecart"
     }
   }
   pattern: [
     "aba"
     "cdc"
     "efe"
   ]
   result: {
     item: "railcraft:track_remover"
   }
   show_notification: true
 }

```


</details>

<details>
<summary>railcraft/track_undercutter</summary>

```diff
 {
   type: "minecraft:crafting_shaped"
   category: "misc"
   key: {
     a: {
-      item: "minecraft:yellow_dye"
+      tag: "forge:dyes/yellow"
     }
     b: {
       item: "minecraft:redstone_lamp"
     }
     c: {
       item: "minecraft:piston"
     }
     d: {
       tag: "forge:storage_blocks/steel"
     }
     e: {
       item: "minecraft:diamond_shovel"
     }
     f: {
       item: "minecraft:minecart"
     }
   }
   pattern: [
     "aba"
     "cdc"
     "efe"
   ]
   result: {
     item: "railcraft:track_undercutter"
   }
   show_notification: true
 }

```


</details>

<details>
<summary>railcraft/whistle_track_kit</summary>

```diff
 {
   type: "minecraft:crafting_shapeless"
   category: "misc"
   ingredients: [
     {
       tag: "minecraft:planks"
     }
     {
       item: "railcraft:track_parts"
     }
     {
       tag: "forge:dyes/yellow"
     }
-    {
-      item: "minecraft:ink_sac"
-    }
     {
       item: "minecraft:note_block"
     }
     {
       tag: "forge:dusts/redstone"
     }
+    {
+      tag: "forge:dyes/black"
+    }
   ]
   result: {
     count: 8
     item: "railcraft:whistle_track_kit"
   }
 }

```


</details>

<details>
<summary>tfc/bloomery/raw_iron_bloom</summary>

```diff
 {
   __comment__: "This file was automatically created by mcresources"
   type: "tfc:bloomery"
   result: {
     item: "tfc:raw_iron_bloom"
   }
   fluid: {
     ingredient: "tfc:metal/cast_iron"
     amount: 144
   }
   catalyst: {
-    item: "minecraft:charcoal"
+    tag: "forge:gems/charcoal"
   }
   duration: 15000
 }

```


</details>

<details>
<summary>tfc/heating/metal/bismuth_bronze_sheet</summary>

```diff
 {
   __comment__: "This file was automatically created by mcresources"
   type: "tfc:heating"
   ingredient: {
-    tag: "forge:sheets/bismuth_bronze"
+    tag: "forge:plates/bismuth_bronze"
   }
   temperature: 985
   result_fluid: {
     fluid: "tfc:metal/bismuth_bronze"
     amount: 144
   }
 }

```


</details>

<details>
<summary>tfc/heating/metal/bismuth_sheet</summary>

```diff
 {
   __comment__: "This file was automatically created by mcresources"
   type: "tfc:heating"
   ingredient: {
-    tag: "forge:plates/bismuth"
+    tag: "forge:sheets/bismuth"
   }
   temperature: 270
   result_fluid: {
     fluid: "tfc:metal/bismuth"
     amount: 144
   }
 }

```


</details>

<details>
<summary>tfc/heating/metal/black_bronze_sheet</summary>

```diff
 {
   __comment__: "This file was automatically created by mcresources"
   type: "tfc:heating"
   ingredient: {
-    tag: "forge:sheets/black_bronze"
+    tag: "forge:plates/black_bronze"
   }
   temperature: 1070
   result_fluid: {
     fluid: "tfc:metal/black_bronze"
     amount: 144
   }
 }

```


</details>

<details>
<summary>tfc/heating/metal/black_steel_sheet</summary>

```diff
 {
   __comment__: "This file was automatically created by mcresources"
   type: "tfc:heating"
   ingredient: {
-    tag: "forge:plates/black_steel"
+    tag: "forge:sheets/black_steel"
   }
   temperature: 1485
   result_fluid: {
     fluid: "tfc:metal/black_steel"
     amount: 144
   }
 }

```


</details>

<details>
<summary>tfc/heating/metal/blue_steel_sheet</summary>

```diff
 {
   __comment__: "This file was automatically created by mcresources"
   type: "tfc:heating"
   ingredient: {
-    tag: "forge:sheets/blue_steel"
+    tag: "forge:plates/blue_steel"
   }
   temperature: 1540
   result_fluid: {
     fluid: "tfc:metal/blue_steel"
     amount: 144
   }
 }

```


</details>

<details>
<summary>tfc/heating/metal/gold_sheet</summary>

```diff
 {
   __comment__: "This file was automatically created by mcresources"
   type: "tfc:heating"
   ingredient: {
-    tag: "forge:plates/gold"
+    tag: "forge:sheets/gold"
   }
   temperature: 1060
   result_fluid: {
     fluid: "tfc:metal/gold"
     amount: 144
   }
 }

```


</details>

<details>
<summary>tfc/heating/metal/nickel_sheet</summary>

```diff
 {
   __comment__: "This file was automatically created by mcresources"
   type: "tfc:heating"
   ingredient: {
-    tag: "forge:sheets/nickel"
+    tag: "forge:plates/nickel"
   }
   temperature: 1453
   result_fluid: {
     fluid: "tfc:metal/nickel"
     amount: 144
   }
 }

```


</details>

<details>
<summary>tfc/heating/metal/red_steel_sheet</summary>

```diff
 {
   __comment__: "This file was automatically created by mcresources"
   type: "tfc:heating"
   ingredient: {
-    tag: "forge:sheets/red_steel"
+    tag: "forge:plates/red_steel"
   }
   temperature: 1540
   result_fluid: {
     fluid: "tfc:metal/red_steel"
     amount: 144
   }
 }

```


</details>

<details>
<summary>tfc/heating/metal/rose_gold_sheet</summary>

```diff
 {
   __comment__: "This file was automatically created by mcresources"
   type: "tfc:heating"
   ingredient: {
-    tag: "forge:plates/rose_gold"
+    tag: "forge:sheets/rose_gold"
   }
   temperature: 960
   result_fluid: {
     fluid: "tfc:metal/rose_gold"
     amount: 144
   }
 }

```


</details>

<details>
<summary>tfc/heating/metal/silver_sheet</summary>

```diff
 {
   __comment__: "This file was automatically created by mcresources"
   type: "tfc:heating"
   ingredient: {
-    tag: "forge:sheets/silver"
+    tag: "forge:plates/silver"
   }
   temperature: 961
   result_fluid: {
     fluid: "tfc:metal/silver"
     amount: 144
   }
 }

```


</details>

<details>
<summary>tfc/heating/metal/sterling_silver_sheet</summary>

```diff
 {
   __comment__: "This file was automatically created by mcresources"
   type: "tfc:heating"
   ingredient: {
-    tag: "forge:plates/sterling_silver"
+    tag: "forge:sheets/sterling_silver"
   }
   temperature: 950
   result_fluid: {
     fluid: "tfc:metal/sterling_silver"
     amount: 144
   }
 }

```


</details>

<details>
<summary>tfc/heating/metal/tin_sheet</summary>

```diff
 {
   __comment__: "This file was automatically created by mcresources"
   type: "tfc:heating"
   ingredient: {
-    tag: "forge:plates/tin"
+    tag: "forge:sheets/tin"
   }
   temperature: 230
   result_fluid: {
     fluid: "tfc:metal/tin"
     amount: 144
   }
 }

```


</details>

<details>
<summary>tfc/heating/metal/wrought_iron_sheet</summary>

```diff
 {
   __comment__: "This file was automatically created by mcresources"
   type: "tfc:heating"
   ingredient: {
-    tag: "forge:plates/wrought_iron"
+    tag: "forge:sheets/wrought_iron"
   }
   temperature: 1535
   result_fluid: {
     fluid: "tfc:metal/cast_iron"
     amount: 144
   }
 }

```


</details>

<details>
<summary>tfc/heating/metal/zinc_sheet</summary>

```diff
 {
   __comment__: "This file was automatically created by mcresources"
   type: "tfc:heating"
   ingredient: {
-    tag: "forge:plates/zinc"
+    tag: "forge:sheets/zinc"
   }
   temperature: 420
   result_fluid: {
     fluid: "tfc:metal/zinc"
     amount: 144
   }
 }

```


</details>

<details>
<summary>tfc/welding/bismuth_bronze_boots</summary>

```diff
 {
   type: "tfc:welding"
   first_input: {
     item: "tfc:metal/unfinished_boots/bismuth_bronze"
   }
   second_input: {
-    item: "gtceu:bismuth_bronze_plate"
+    tag: "forge:plates/bismuth_bronze"
   }
   tier: 1
   result: {
     item: "tfc:metal/boots/bismuth_bronze"
   }
 }

```


</details>

<details>
<summary>tfc/welding/bismuth_bronze_chestplate</summary>

```diff
 {
   type: "tfc:welding"
   first_input: {
     item: "tfc:metal/unfinished_chestplate/bismuth_bronze"
   }
   second_input: {
-    item: "gtceu:bismuth_bronze_plate"
+    tag: "forge:plates/bismuth_bronze"
   }
   tier: 1
   result: {
     item: "tfc:metal/chestplate/bismuth_bronze"
   }
 }

```


</details>

<details>
<summary>tfc/welding/bismuth_bronze_greaves</summary>

```diff
 {
   type: "tfc:welding"
   first_input: {
     item: "tfc:metal/unfinished_greaves/bismuth_bronze"
   }
   second_input: {
-    item: "gtceu:bismuth_bronze_plate"
+    tag: "forge:plates/bismuth_bronze"
   }
   tier: 1
   result: {
     item: "tfc:metal/greaves/bismuth_bronze"
   }
 }

```


</details>

<details>
<summary>tfc/welding/bismuth_bronze_helmet</summary>

```diff
 {
   type: "tfc:welding"
   first_input: {
     item: "tfc:metal/unfinished_helmet/bismuth_bronze"
   }
   second_input: {
-    item: "gtceu:bismuth_bronze_plate"
+    tag: "forge:plates/bismuth_bronze"
   }
   tier: 1
   result: {
     item: "tfc:metal/helmet/bismuth_bronze"
   }
 }

```


</details>

<details>
<summary>tfc/welding/black_bronze_boots</summary>

```diff
 {
   type: "tfc:welding"
   first_input: {
     item: "tfc:metal/unfinished_boots/black_bronze"
   }
   second_input: {
-    item: "gtceu:black_bronze_plate"
+    tag: "forge:plates/black_bronze"
   }
   tier: 1
   result: {
     item: "tfc:metal/boots/black_bronze"
   }
 }

```


</details>

<details>
<summary>tfc/welding/black_bronze_chestplate</summary>

```diff
 {
   type: "tfc:welding"
   first_input: {
     item: "tfc:metal/unfinished_chestplate/black_bronze"
   }
   second_input: {
-    item: "gtceu:black_bronze_plate"
+    tag: "forge:plates/black_bronze"
   }
   tier: 1
   result: {
     item: "tfc:metal/chestplate/black_bronze"
   }
 }

```


</details>

<details>
<summary>tfc/welding/black_bronze_greaves</summary>

```diff
 {
   type: "tfc:welding"
   first_input: {
     item: "tfc:metal/unfinished_greaves/black_bronze"
   }
   second_input: {
-    item: "gtceu:black_bronze_plate"
+    tag: "forge:plates/black_bronze"
   }
   tier: 1
   result: {
     item: "tfc:metal/greaves/black_bronze"
   }
 }

```


</details>

<details>
<summary>tfc/welding/black_bronze_helmet</summary>

```diff
 {
   type: "tfc:welding"
   first_input: {
     item: "tfc:metal/unfinished_helmet/black_bronze"
   }
   second_input: {
-    item: "gtceu:black_bronze_plate"
+    tag: "forge:plates/black_bronze"
   }
   tier: 1
   result: {
     item: "tfc:metal/helmet/black_bronze"
   }
 }

```


</details>

<details>
<summary>tfc/welding/black_steel_boots</summary>

```diff
 {
   type: "tfc:welding"
   first_input: {
     item: "tfc:metal/unfinished_boots/black_steel"
   }
   second_input: {
-    item: "gtceu:black_steel_plate"
+    tag: "forge:sheets/black_steel"
   }
   tier: 4
   result: {
     item: "tfc:metal/boots/black_steel"
   }
 }

```


</details>

<details>
<summary>tfc/welding/black_steel_chestplate</summary>

```diff
 {
   type: "tfc:welding"
   first_input: {
     item: "tfc:metal/unfinished_chestplate/black_steel"
   }
   second_input: {
-    item: "gtceu:black_steel_plate"
+    tag: "forge:sheets/black_steel"
   }
   tier: 4
   result: {
     item: "tfc:metal/chestplate/black_steel"
   }
 }

```


</details>

<details>
<summary>tfc/welding/black_steel_greaves</summary>

```diff
 {
   type: "tfc:welding"
   first_input: {
     item: "tfc:metal/unfinished_greaves/black_steel"
   }
   second_input: {
-    item: "gtceu:black_steel_plate"
+    tag: "forge:sheets/black_steel"
   }
   tier: 4
   result: {
     item: "tfc:metal/greaves/black_steel"
   }
 }

```


</details>

<details>
<summary>tfc/welding/black_steel_helmet</summary>

```diff
 {
   type: "tfc:welding"
   first_input: {
     item: "tfc:metal/unfinished_helmet/black_steel"
   }
   second_input: {
-    item: "gtceu:black_steel_plate"
+    tag: "forge:sheets/black_steel"
   }
   tier: 4
   result: {
     item: "tfc:metal/helmet/black_steel"
   }
 }

```


</details>

<details>
<summary>tfc/welding/blue_steel_boots</summary>

```diff
 {
   type: "tfc:welding"
   first_input: {
     item: "tfc:metal/unfinished_boots/blue_steel"
   }
   second_input: {
-    item: "gtceu:blue_steel_plate"
+    tag: "forge:plates/blue_steel"
   }
   tier: 5
   result: {
     item: "tfc:metal/boots/blue_steel"
   }
 }

```


</details>

<details>
<summary>tfc/welding/blue_steel_chestplate</summary>

```diff
 {
   type: "tfc:welding"
   first_input: {
     item: "tfc:metal/unfinished_chestplate/blue_steel"
   }
   second_input: {
-    item: "gtceu:blue_steel_plate"
+    tag: "forge:plates/blue_steel"
   }
   tier: 5
   result: {
     item: "tfc:metal/chestplate/blue_steel"
   }
 }

```


</details>

<details>
<summary>tfc/welding/blue_steel_greaves</summary>

```diff
 {
   type: "tfc:welding"
   first_input: {
     item: "tfc:metal/unfinished_greaves/blue_steel"
   }
   second_input: {
-    item: "gtceu:blue_steel_plate"
+    tag: "forge:plates/blue_steel"
   }
   tier: 5
   result: {
     item: "tfc:metal/greaves/blue_steel"
   }
 }

```


</details>

<details>
<summary>tfc/welding/blue_steel_helmet</summary>

```diff
 {
   type: "tfc:welding"
   first_input: {
     item: "tfc:metal/unfinished_helmet/blue_steel"
   }
   second_input: {
-    item: "gtceu:blue_steel_plate"
+    tag: "forge:plates/blue_steel"
   }
   tier: 5
   result: {
     item: "tfc:metal/helmet/blue_steel"
   }
 }

```


</details>

<details>
<summary>tfc/welding/bronze_boots</summary>

```diff
 {
   type: "tfc:welding"
   first_input: {
     item: "tfc:metal/unfinished_boots/bronze"
   }
   second_input: {
-    item: "gtceu:bronze_plate"
+    tag: "forge:plates/bronze"
   }
   tier: 1
   result: {
     item: "tfc:metal/boots/bronze"
   }
 }

```


</details>

<details>
<summary>tfc/welding/bronze_chestplate</summary>

```diff
 {
   type: "tfc:welding"
   first_input: {
     item: "tfc:metal/unfinished_chestplate/bronze"
   }
   second_input: {
-    item: "gtceu:bronze_plate"
+    tag: "forge:plates/bronze"
   }
   tier: 1
   result: {
     item: "tfc:metal/chestplate/bronze"
   }
 }

```


</details>

<details>
<summary>tfc/welding/bronze_greaves</summary>

```diff
 {
   type: "tfc:welding"
   first_input: {
     item: "tfc:metal/unfinished_greaves/bronze"
   }
   second_input: {
-    item: "gtceu:bronze_plate"
+    tag: "forge:plates/bronze"
   }
   tier: 1
   result: {
     item: "tfc:metal/greaves/bronze"
   }
 }

```


</details>

<details>
<summary>tfc/welding/bronze_helmet</summary>

```diff
 {
   type: "tfc:welding"
   first_input: {
     item: "tfc:metal/unfinished_helmet/bronze"
   }
   second_input: {
-    item: "gtceu:bronze_plate"
+    tag: "forge:plates/bronze"
   }
   tier: 1
   result: {
     item: "tfc:metal/helmet/bronze"
   }
 }

```


</details>

<details>
<summary>tfc/welding/copper_boots</summary>

```diff
 {
   type: "tfc:welding"
   first_input: {
     item: "tfc:metal/unfinished_boots/copper"
   }
   second_input: {
-    item: "gtceu:copper_plate"
+    tag: "forge:sheets/copper"
   }
   tier: 0
   result: {
     item: "tfc:metal/boots/copper"
   }
 }

```


</details>

<details>
<summary>tfc/welding/copper_chestplate</summary>

```diff
 {
   type: "tfc:welding"
   first_input: {
     item: "tfc:metal/unfinished_chestplate/copper"
   }
   second_input: {
-    item: "gtceu:copper_plate"
+    tag: "forge:sheets/copper"
   }
   tier: 0
   result: {
     item: "tfc:metal/chestplate/copper"
   }
 }

```


</details>

<details>
<summary>tfc/welding/copper_greaves</summary>

```diff
 {
   type: "tfc:welding"
   first_input: {
     item: "tfc:metal/unfinished_greaves/copper"
   }
   second_input: {
-    item: "gtceu:copper_plate"
+    tag: "forge:sheets/copper"
   }
   tier: 0
   result: {
     item: "tfc:metal/greaves/copper"
   }
 }

```


</details>

<details>
<summary>tfc/welding/copper_helmet</summary>

```diff
 {
   type: "tfc:welding"
   first_input: {
     item: "tfc:metal/unfinished_helmet/copper"
   }
   second_input: {
-    item: "gtceu:copper_plate"
+    tag: "forge:sheets/copper"
   }
   tier: 0
   result: {
     item: "tfc:metal/helmet/copper"
   }
 }

```


</details>

<details>
<summary>tfc/welding/invar_double_ingot</summary>

```diff
 {
   type: "tfc:welding"
   first_input: {
-    item: "gtceu:invar_ingot"
+    tag: "forge:ingots/invar"
   }
   second_input: {
-    item: "gtceu:invar_ingot"
+    tag: "forge:ingots/invar"
   }
   tier: 2
   result: {
     item: "gregitas:double_invar_ingot"
   }
 }

```


</details>

<details>
<summary>tfc/welding/invar_double_plate</summary>

```diff
 {
   type: "tfc:welding"
   first_input: {
-    item: "gtceu:invar_plate"
+    tag: "forge:sheets/invar"
   }
   second_input: {
-    item: "gtceu:invar_plate"
+    tag: "forge:sheets/invar"
   }
   tier: 2
   result: {
     item: "gtceu:invar_double_plate"
   }
 }

```


</details>

<details>
<summary>tfc/welding/red_steel_boots</summary>

```diff
 {
   type: "tfc:welding"
   first_input: {
     item: "tfc:metal/unfinished_boots/red_steel"
   }
   second_input: {
-    item: "gtceu:red_steel_plate"
+    tag: "forge:plates/red_steel"
   }
   tier: 5
   result: {
     item: "tfc:metal/boots/red_steel"
   }
 }

```


</details>

<details>
<summary>tfc/welding/red_steel_chestplate</summary>

```diff
 {
   type: "tfc:welding"
   first_input: {
     item: "tfc:metal/unfinished_chestplate/red_steel"
   }
   second_input: {
-    item: "gtceu:red_steel_plate"
+    tag: "forge:plates/red_steel"
   }
   tier: 5
   result: {
     item: "tfc:metal/chestplate/red_steel"
   }
 }

```


</details>

<details>
<summary>tfc/welding/red_steel_greaves</summary>

```diff
 {
   type: "tfc:welding"
   first_input: {
     item: "tfc:metal/unfinished_greaves/red_steel"
   }
   second_input: {
-    item: "gtceu:red_steel_plate"
+    tag: "forge:plates/red_steel"
   }
   tier: 5
   result: {
     item: "tfc:metal/greaves/red_steel"
   }
 }

```


</details>

<details>
<summary>tfc/welding/red_steel_helmet</summary>

```diff
 {
   type: "tfc:welding"
   first_input: {
     item: "tfc:metal/unfinished_helmet/red_steel"
   }
   second_input: {
-    item: "gtceu:red_steel_plate"
+    tag: "forge:plates/red_steel"
   }
   tier: 5
   result: {
     item: "tfc:metal/helmet/red_steel"
   }
 }

```


</details>

<details>
<summary>tfc/welding/steel_boots</summary>

```diff
 {
   type: "tfc:welding"
   first_input: {
     item: "tfc:metal/unfinished_boots/steel"
   }
   second_input: {
-    item: "gtceu:steel_plate"
+    tag: "forge:sheets/steel"
   }
   tier: 3
   result: {
     item: "tfc:metal/boots/steel"
   }
 }

```


</details>

<details>
<summary>tfc/welding/steel_chestplate</summary>

```diff
 {
   type: "tfc:welding"
   first_input: {
     item: "tfc:metal/unfinished_chestplate/steel"
   }
   second_input: {
-    item: "gtceu:steel_plate"
+    tag: "forge:sheets/steel"
   }
   tier: 3
   result: {
     item: "tfc:metal/chestplate/steel"
   }
 }

```


</details>

<details>
<summary>tfc/welding/steel_greaves</summary>

```diff
 {
   type: "tfc:welding"
   first_input: {
     item: "tfc:metal/unfinished_greaves/steel"
   }
   second_input: {
-    item: "gtceu:steel_plate"
+    tag: "forge:sheets/steel"
   }
   tier: 3
   result: {
     item: "tfc:metal/greaves/steel"
   }
 }

```


</details>

<details>
<summary>tfc/welding/steel_helmet</summary>

```diff
 {
   type: "tfc:welding"
   first_input: {
     item: "tfc:metal/unfinished_helmet/steel"
   }
   second_input: {
-    item: "gtceu:steel_plate"
+    tag: "forge:sheets/steel"
   }
   tier: 3
   result: {
     item: "tfc:metal/helmet/steel"
   }
 }

```


</details>

<details>
<summary>tfc/welding/wrought_iron_boots</summary>

```diff
 {
   type: "tfc:welding"
   first_input: {
     item: "tfc:metal/unfinished_boots/wrought_iron"
   }
   second_input: {
-    item: "gtceu:wrought_iron_plate"
+    tag: "forge:sheets/wrought_iron"
   }
   tier: 2
   result: {
     item: "tfc:metal/boots/wrought_iron"
   }
 }

```


</details>

<details>
<summary>tfc/welding/wrought_iron_chestplate</summary>

```diff
 {
   type: "tfc:welding"
   first_input: {
     item: "tfc:metal/unfinished_chestplate/wrought_iron"
   }
   second_input: {
-    item: "gtceu:wrought_iron_plate"
+    tag: "forge:sheets/wrought_iron"
   }
   tier: 2
   result: {
     item: "tfc:metal/chestplate/wrought_iron"
   }
 }

```


</details>

<details>
<summary>tfc/welding/wrought_iron_greaves</summary>

```diff
 {
   type: "tfc:welding"
   first_input: {
     item: "tfc:metal/unfinished_greaves/wrought_iron"
   }
   second_input: {
-    item: "gtceu:wrought_iron_plate"
+    tag: "forge:sheets/wrought_iron"
   }
   tier: 2
   result: {
     item: "tfc:metal/greaves/wrought_iron"
   }
 }

```


</details>

<details>
<summary>tfc/welding/wrought_iron_helmet</summary>

```diff
 {
   type: "tfc:welding"
   first_input: {
     item: "tfc:metal/unfinished_helmet/wrought_iron"
   }
   second_input: {
-    item: "gtceu:wrought_iron_plate"
+    tag: "forge:sheets/wrought_iron"
   }
   tier: 2
   result: {
     item: "tfc:metal/helmet/wrought_iron"
   }
 }

```


</details>

<details>
<summary>thoriumreactors/black_industrial_block_smooth</summary>

```diff
 {
   type: "minecraft:crafting_shaped"
   category: "misc"
   key: {
     A: {
       item: "thoriumreactors:industrial_block_smooth"
     }
     B: {
       item: "minecraft:black_dye"
     }
   }
   pattern: [
-    " A "
-    " A "
+    "AAA"
+    "AAA"
     "ABA"
   ]
   result: {
     count: 8
     item: "thoriumreactors:black_industrial_block_smooth"
   }
   show_notification: true
 }

```


</details>

<details>
<summary>thoriumreactors/blasting/blasted_iron_ingot</summary>

```diff
 {
   type: "thoriumreactors:blasting"
   ticks: 900
   temperature: 1150
   input: {
     slot-0: {
       item: "minecraft:coal"
     }
     slot-1: {
-      item: "minecraft:iron_ingot"
+      tag: "forge:ingots/iron"
     }
   }
   output: {
     slot-0: {
       item: "thoriumreactors:blasted_iron_ingot"
     }
   }
 }

```


</details>

<details>
<summary>thoriumreactors/chromium_block_craft_from_ingot</summary>

```diff
 {
   type: "minecraft:crafting_shapeless"
   category: "misc"
   ingredients: [
     {
       tag: "forge:ingots/chromium"
     }
     {
       tag: "forge:ingots/chromium"
     }
     {
       tag: "forge:ingots/chromium"
     }
     {
       tag: "forge:ingots/chromium"
     }
     {
       tag: "forge:ingots/chromium"
     }
     {
       tag: "forge:ingots/chromium"
     }
     {
       tag: "forge:ingots/chromium"
     }
     {
       tag: "forge:ingots/chromium"
     }
     {
       tag: "forge:ingots/chromium"
     }
   ]
   result: {
-    item: "thoriumreactors:chromium_block"
+    item: "gtceu:chromium_block"
   }
 }

```


</details>

<details>
<summary>thoriumreactors/chromium_ingot_craft_from_block</summary>

```diff
 {
   type: "minecraft:crafting_shapeless"
   category: "misc"
   ingredients: [
     {
-      item: "thoriumreactors:chromium_block"
+      tag: "forge:storage_blocks/chromium"
     }
   ]
   result: {
     count: 9
     item: "firmalife:metal/ingot/chromium"
   }
 }

```


</details>

<details>
<summary>thoriumreactors/chromium_ingot_craft_from_nugget</summary>

```diff
 {
   type: "minecraft:crafting_shapeless"
   category: "misc"
   ingredients: [
     {
-      tag: "forge:nuggets/chromium"
+      tag: "forge:nuggets/chrome"
     }
     {
-      tag: "forge:nuggets/chromium"
+      tag: "forge:nuggets/chrome"
     }
     {
-      tag: "forge:nuggets/chromium"
+      tag: "forge:nuggets/chrome"
     }
     {
-      tag: "forge:nuggets/chromium"
+      tag: "forge:nuggets/chrome"
     }
     {
-      tag: "forge:nuggets/chromium"
+      tag: "forge:nuggets/chrome"
     }
     {
-      tag: "forge:nuggets/chromium"
+      tag: "forge:nuggets/chrome"
     }
     {
-      tag: "forge:nuggets/chromium"
+      tag: "forge:nuggets/chrome"
     }
     {
-      tag: "forge:nuggets/chromium"
+      tag: "forge:nuggets/chrome"
     }
     {
-      tag: "forge:nuggets/chromium"
+      tag: "forge:nuggets/chrome"
     }
   ]
   result: {
     item: "firmalife:metal/ingot/chromium"
   }
 }

```


</details>

<details>
<summary>thoriumreactors/chromium_nugget_craft_from_ingot</summary>

```diff
 {
   type: "minecraft:crafting_shapeless"
   category: "misc"
   ingredients: [
     {
       tag: "forge:ingots/chromium"
     }
   ]
   result: {
     count: 9
-    item: "gtceu:chromium_nugget"
+    item: "thoriumreactors:chromium_nugget"
   }
 }

```


</details>

<details>
<summary>thoriumreactors/cobalt_block_craft_from_ingot</summary>

```diff
 {
   type: "minecraft:crafting_shapeless"
   category: "misc"
   ingredients: [
     {
       tag: "forge:ingots/cobalt"
     }
     {
       tag: "forge:ingots/cobalt"
     }
     {
       tag: "forge:ingots/cobalt"
     }
     {
       tag: "forge:ingots/cobalt"
     }
     {
       tag: "forge:ingots/cobalt"
     }
     {
       tag: "forge:ingots/cobalt"
     }
     {
       tag: "forge:ingots/cobalt"
     }
     {
       tag: "forge:ingots/cobalt"
     }
     {
       tag: "forge:ingots/cobalt"
     }
   ]
   result: {
-    item: "thoriumreactors:cobalt_block"
+    item: "gtceu:cobalt_block"
   }
 }

```


</details>

<details>
<summary>thoriumreactors/cobalt_ingot_craft_from_block</summary>

```diff
 {
   type: "minecraft:crafting_shapeless"
   category: "misc"
   ingredients: [
     {
-      item: "thoriumreactors:cobalt_block"
+      tag: "forge:storage_blocks/cobalt"
     }
   ]
   result: {
     count: 9
     item: "gtceu:cobalt_ingot"
   }
 }

```


</details>

<details>
<summary>thoriumreactors/concentrating/yellow_cake</summary>

```diff
 {
   type: "thoriumreactors:concentrating"
   ticks: 500
   input: {
     slot-0: {
-      item: "thoriumreactors:raw_uranium"
+      tag: "forge:raw_materials/uranium"
     }
   }
   output: {
     slot-0: {
       item: "thoriumreactors:yellow_cake"
     }
   }
 }

```


</details>

<details>
<summary>thoriumreactors/decomposing/hydrofluorite</summary>

```diff
 {
   type: "thoriumreactors:decomposing"
   ticks: 100
   operationAfterTicks: 1
   input: {
     slot-0: {
-      item: "thoriumreactors:fluorite"
+      tag: "forge:gems/fluorite"
     }
     tank-0: {
       FluidName: "minecraft:water"
       Amount: 2
     }
   }
   output: {
     tank-0: {
       FluidName: "thoriumreactors:hydrofluorite"
       Amount: 2
     }
   }
 }

```


</details>

<details>
<summary>thoriumreactors/fluorite_ingot_craft_from_block</summary>

```diff
 {
   type: "minecraft:crafting_shapeless"
   category: "misc"
   ingredients: [
     {
-      item: "thoriumreactors:fluorite_block"
+      tag: "forge:storage_blocks/fluorite"
     }
   ]
   result: {
     count: 9
     item: "thoriumreactors:fluorite_ingot"
   }
 }

```


</details>

<details>
<summary>thoriumreactors/manganese_block_craft_from_ingot</summary>

```diff
 {
   type: "minecraft:crafting_shapeless"
   category: "misc"
   ingredients: [
     {
       tag: "forge:ingots/manganese"
     }
     {
       tag: "forge:ingots/manganese"
     }
     {
       tag: "forge:ingots/manganese"
     }
     {
       tag: "forge:ingots/manganese"
     }
     {
       tag: "forge:ingots/manganese"
     }
     {
       tag: "forge:ingots/manganese"
     }
     {
       tag: "forge:ingots/manganese"
     }
     {
       tag: "forge:ingots/manganese"
     }
     {
       tag: "forge:ingots/manganese"
     }
   ]
   result: {
-    item: "thoriumreactors:manganese_block"
+    item: "gtceu:manganese_block"
   }
 }

```


</details>

<details>
<summary>thoriumreactors/manganese_ingot_craft_from_block</summary>

```diff
 {
   type: "minecraft:crafting_shapeless"
   category: "misc"
   ingredients: [
     {
-      item: "thoriumreactors:manganese_block"
+      tag: "forge:storage_blocks/manganese"
     }
   ]
   result: {
     count: 9
     item: "gtceu:manganese_ingot"
   }
 }

```


</details>

<details>
<summary>thoriumreactors/molybdenum_block_craft_from_ingot</summary>

```diff
 {
   type: "minecraft:crafting_shapeless"
   category: "misc"
   ingredients: [
     {
       tag: "forge:ingots/molybdenum"
     }
     {
       tag: "forge:ingots/molybdenum"
     }
     {
       tag: "forge:ingots/molybdenum"
     }
     {
       tag: "forge:ingots/molybdenum"
     }
     {
       tag: "forge:ingots/molybdenum"
     }
     {
       tag: "forge:ingots/molybdenum"
     }
     {
       tag: "forge:ingots/molybdenum"
     }
     {
       tag: "forge:ingots/molybdenum"
     }
     {
       tag: "forge:ingots/molybdenum"
     }
   ]
   result: {
-    item: "thoriumreactors:molybdenum_block"
+    item: "gtceu:molybdenum_block"
   }
 }

```


</details>

<details>
<summary>thoriumreactors/molybdenum_ingot_craft_from_block</summary>

```diff
 {
   type: "minecraft:crafting_shapeless"
   category: "misc"
   ingredients: [
     {
-      item: "thoriumreactors:molybdenum_block"
+      tag: "forge:storage_blocks/molybdenum"
     }
   ]
   result: {
     count: 9
     item: "gtceu:molybdenum_ingot"
   }
 }

```


</details>

<details>
<summary>thoriumreactors/nickel_block_craft_from_ingot</summary>

```diff
 {
   type: "minecraft:crafting_shapeless"
   category: "misc"
   ingredients: [
     {
       tag: "forge:ingots/nickel"
     }
     {
       tag: "forge:ingots/nickel"
     }
     {
       tag: "forge:ingots/nickel"
     }
     {
       tag: "forge:ingots/nickel"
     }
     {
       tag: "forge:ingots/nickel"
     }
     {
       tag: "forge:ingots/nickel"
     }
     {
       tag: "forge:ingots/nickel"
     }
     {
       tag: "forge:ingots/nickel"
     }
     {
       tag: "forge:ingots/nickel"
     }
   ]
   result: {
-    item: "thoriumreactors:nickel_block"
+    item: "gtceu:nickel_block"
   }
 }

```


</details>

<details>
<summary>thoriumreactors/niob_ingot_craft_from_block</summary>

```diff
 {
   type: "minecraft:crafting_shapeless"
   category: "misc"
   ingredients: [
     {
-      item: "thoriumreactors:niob_block"
+      tag: "forge:storage_blocks/pyrochlore"
     }
   ]
   result: {
     count: 9
     item: "gtceu:niobium_ingot"
   }
 }

```


</details>

<details>
<summary>thoriumreactors/steel_block_craft_from_ingot</summary>

```diff
 {
   type: "minecraft:crafting_shapeless"
   category: "misc"
   ingredients: [
     {
       tag: "forge:ingots/steel"
     }
     {
       tag: "forge:ingots/steel"
     }
     {
       tag: "forge:ingots/steel"
     }
     {
       tag: "forge:ingots/steel"
     }
     {
       tag: "forge:ingots/steel"
     }
     {
       tag: "forge:ingots/steel"
     }
     {
       tag: "forge:ingots/steel"
     }
     {
       tag: "forge:ingots/steel"
     }
     {
       tag: "forge:ingots/steel"
     }
   ]
   result: {
-    item: "thoriumreactors:steel_block"
+    item: "gtceu:steel_block"
   }
 }

```


</details>

<details>
<summary>thoriumreactors/thorium_crafting/black_factory_block</summary>

```diff
 {
   type: "thoriumreactors:thorium_crafting"
   key: {
     A: {
       item: "thoriumreactors:factory_block"
     }
     B: {
-      item: "minecraft:black_dye"
+      tag: "forge:dyes/black"
     }
   }
   pattern: [
     "     "
     " AAA "
     " ABA "
     " AAA "
     "     "
   ]
   result: {
     item: "thoriumreactors:black_factory_block"
     count: 8
   }
 }

```


</details>

<details>
<summary>thoriumreactors/thorium_crafting/black_industrial_block</summary>

```diff
 {
   type: "thoriumreactors:thorium_crafting"
   key: {
     A: {
       item: "thoriumreactors:industrial_block"
     }
     B: {
-      item: "minecraft:black_dye"
+      tag: "forge:dyes/black"
     }
   }
   pattern: [
     "     "
     " AAA "
     " ABA "
     " AAA "
     "     "
   ]
   result: {
     item: "thoriumreactors:black_industrial_block"
     count: 8
   }
 }

```


</details>

<details>
<summary>thoriumreactors/thorium_crafting/black_industrial_block_smooth</summary>

```diff
 {
   type: "thoriumreactors:thorium_crafting"
   key: {
     A: {
       item: "thoriumreactors:industrial_block_smooth"
     }
     B: {
-      item: "minecraft:black_dye"
+      tag: "forge:dyes/black"
     }
   }
   pattern: [
     "     "
     " AAA "
     " ABA "
     " AAA "
     "     "
   ]
   result: {
     item: "thoriumreactors:black_industrial_block_smooth"
     count: 8
   }
 }

```


</details>

<details>
<summary>thoriumreactors/thorium_crafting/black_industrial_floor_block</summary>

```diff
 {
   type: "thoriumreactors:thorium_crafting"
   key: {
     A: {
-      item: "minecraft:black_dye"
+      tag: "forge:dyes/black"
     }
     B: {
       item: "thoriumreactors:industrial_block_floor"
     }
   }
   pattern: [
     "     "
     " BBB "
     " BAB "
     " BBB "
     "     "
   ]
   result: {
     item: "thoriumreactors:black_industrial_block_floor"
     count: 8
   }
 }

```


</details>

<details>
<summary>thoriumreactors/thorium_crafting/black_inverted_factory_block</summary>

```diff
 {
   type: "thoriumreactors:thorium_crafting"
   key: {
     A: {
       item: "thoriumreactors:black_factory_block"
     }
     B: {
-      item: "minecraft:gray_dye"
+      tag: "forge:dyes/gray"
     }
   }
   pattern: [
     "     "
     " AAA "
     " ABA "
     " AAA "
     "     "
   ]
   result: {
     item: "thoriumreactors:black_inverted_factory_block"
     count: 8
   }
 }

```


</details>

<details>
<summary>thoriumreactors/thorium_crafting/blast_furnace</summary>

```diff
 {
   type: "thoriumreactors:thorium_crafting"
   key: {
     A: {
       tag: "forge:ingots/gold"
     }
     B: {
       tag: "forge:nuggets/gold"
     }
     C: {
       tag: "forge:ingots/iron"
     }
     D: {
       tag: "forge:nuggets/iron"
     }
     E: {
       item: "minecraft:redstone"
     }
     F: {
       item: "thoriumreactors:machine_casing"
     }
     G: {
       item: "thoriumreactors:module_sensor"
     }
     H: {
-      tag: "forge:nuggets/aluminum"
+      tag: "forge:nuggets/aluminium"
     }
     I: {
       tag: "forge:nuggets/molybdenum"
     }
     J: {
       tag: "forge:nuggets/fluorite"
     }
     K: {
       tag: "forge:nuggets/nickel"
     }
   }
   pattern: [
     " BAB "
     "DEHED"
     "CKFIC"
     "DEJGD"
     " BAB "
   ]
   result: {
     item: "thoriumreactors:blast_furnace_block"
   }
 }

```


</details>

<details>
<summary>thoriumreactors/thorium_crafting/blasted_iron_chest</summary>

```diff
 {
   type: "thoriumreactors:thorium_crafting"
   key: {
     A: {
-      item: "thoriumreactors:blasted_iron_ingot"
+      tag: "forge:ingots/blasted_iron"
     }
     B: {
-      item: "thoriumreactors:blasted_iron_nugget"
+      tag: "forge:nuggets/blasted_iron"
     }
     C: {
-      item: "minecraft:chest"
+      tag: "forge:chests/wooden"
     }
     D: {
       tag: "forge:nuggets/iron"
     }
     E: {
       tag: "forge:ingots/iron"
     }
   }
   pattern: [
     " EDE "
     "EBABE"
     "DACAD"
     "EBABE"
     " EDE "
   ]
   result: {
     item: "thoriumreactors:blasted_iron_chest_block"
   }
 }

```


</details>

<details>
<summary>thoriumreactors/thorium_crafting/concentrator_block</summary>

```diff
 {
   type: "thoriumreactors:thorium_crafting"
   key: {
     A: {
-      item: "thoriumreactors:blasted_iron_ingot"
+      tag: "forge:ingots/blasted_iron"
     }
     B: {
-      item: "thoriumreactors:blasted_iron_nugget"
+      tag: "forge:nuggets/blasted_iron"
     }
     C: {
       tag: "forge:ingots/steel"
     }
     D: {
       tag: "forge:nuggets/steel"
     }
     E: {
       item: "minecraft:redstone"
     }
     F: {
       item: "thoriumreactors:machine_casing"
     }
     G: {
       tag: "forge:nuggets/manganese"
     }
     H: {
       tag: "forge:nuggets/cobalt"
     }
   }
   pattern: [
     " BAB "
     "DEGED"
     "CHFHC"
     "DEGED"
     " BAB "
   ]
   result: {
     item: "thoriumreactors:concentrator_block"
   }
 }

```


</details>

<details>
<summary>thoriumreactors/thorium_crafting/configurator</summary>

```diff
 {
   type: "thoriumreactors:thorium_crafting"
   key: {
     A: {
       tag: "forge:ingots/iron"
     }
     B: {
       tag: "forge:ingots/gold"
     }
     C: {
-      tag: "forge:ingots/aluminum"
+      tag: "forge:ingots/aluminium"
     }
     D: {
       tag: "forge:ingots/steel"
     }
     E: {
-      item: "thoriumreactors:blasted_iron_ingot"
+      tag: "forge:ingots/blasted_iron"
     }
     F: {
       item: "thoriumreactors:redstone_processor"
     }
     G: {
       tag: "forge:nuggets/cobalt"
     }
     H: {
       tag: "forge:nuggets/fluorite"
     }
     I: {
-      item: "thoriumreactors:niob_nugget"
+      tag: "forge:nuggets/niob"
     }
     J: {
       tag: "forge:nuggets/manganese"
     }
     K: {
       item: "minecraft:redstone"
     }
   }
   pattern: [
     " AAA "
     "ACDKA"
     "AEFGB"
     "AHIJB"
     " ABB "
   ]
   result: {
     item: "thoriumreactors:configurator"
   }
 }

```


</details>

<details>
<summary>thoriumreactors/thorium_crafting/crystallizer</summary>

```diff
 {
   type: "thoriumreactors:thorium_crafting"
   key: {
     A: {
-      item: "thoriumreactors:blasted_iron_ingot"
+      tag: "forge:ingots/blasted_iron"
     }
     B: {
-      item: "thoriumreactors:blasted_iron_nugget"
+      tag: "forge:nuggets/blasted_iron"
     }
     C: {
       tag: "forge:ingots/steel"
     }
     D: {
       tag: "forge:nuggets/steel"
     }
     E: {
       item: "minecraft:redstone"
     }
     F: {
       item: "thoriumreactors:machine_casing"
     }
     G: {
       item: "thoriumreactors:module_tank"
     }
     H: {
       tag: "forge:nuggets/cobalt"
     }
     I: {
       tag: "forge:nuggets/molybdenum"
     }
     J: {
       tag: "forge:nuggets/nickel"
     }
   }
   pattern: [
     " BAB "
     "DEJED"
     "CIFHC"
     "DGJED"
     " BAB "
   ]
   result: {
     item: "thoriumreactors:crystallizer_block"
   }
 }

```


</details>

<details>
<summary>thoriumreactors/thorium_crafting/decomposer_block</summary>

```diff
 {
   type: "thoriumreactors:thorium_crafting"
   key: {
     A: {
-      item: "thoriumreactors:blasted_iron_ingot"
+      tag: "forge:ingots/blasted_iron"
     }
     B: {
-      item: "thoriumreactors:blasted_iron_nugget"
+      tag: "forge:nuggets/blasted_iron"
     }
     C: {
       tag: "forge:ingots/steel"
     }
     D: {
       tag: "forge:nuggets/steel"
     }
     E: {
       item: "minecraft:redstone"
     }
     F: {
       item: "thoriumreactors:machine_casing"
     }
     G: {
       item: "thoriumreactors:module_tank"
     }
     H: {
       tag: "forge:nuggets/manganese"
     }
     I: {
       tag: "forge:nuggets/molybdenum"
     }
     J: {
-      item: "thoriumreactors:niob_nugget"
+      tag: "forge:nuggets/niob"
     }
     K: {
       tag: "forge:nuggets/cobalt"
     }
   }
   pattern: [
     " BAB "
     "DEHGD"
     "CIFKC"
     "DGJED"
     " BAB "
   ]
   result: {
     item: "thoriumreactors:decomposer_block"
   }
 }

```


</details>

<details>
<summary>thoriumreactors/thorium_crafting/electrolytic_salt_separator</summary>

```diff
 {
   type: "thoriumreactors:thorium_crafting"
   key: {
     A: {
-      item: "thoriumreactors:blasted_iron_ingot"
+      tag: "forge:ingots/blasted_iron"
     }
     B: {
-      item: "thoriumreactors:blasted_iron_nugget"
+      tag: "forge:nuggets/blasted_iron"
     }
     C: {
       tag: "forge:ingots/steel"
     }
     D: {
       tag: "forge:nuggets/steel"
     }
     E: {
       item: "minecraft:bucket"
     }
     F: {
       item: "thoriumreactors:machine_casing"
     }
     G: {
       tag: "forge:nuggets/manganese"
     }
     H: {
       item: "thoriumreactors:module_tank"
     }
   }
   pattern: [
     " BAB "
     "DEGHD"
     "CGFGC"
     "DEGED"
     " BAB "
   ]
   result: {
     item: "thoriumreactors:electrolytic_salt_separator"
   }
 }

```


</details>

<details>
<summary>thoriumreactors/thorium_crafting/electromagnetic_coil</summary>

```diff
 {
   type: "thoriumreactors:thorium_crafting"
   key: {
     A: {
       tag: "forge:ingots/steel"
     }
     B: {
       tag: "forge:nuggets/steel"
     }
     C: {
       tag: "forge:ingots/copper"
     }
     D: {
-      item: "thoriumreactors:steel_block"
+      tag: "forge:storage_blocks/steel"
     }
   }
   pattern: [
     " BAB "
     "BCCCB"
     "ACDCA"
     "BCCCB"
     " BAB "
   ]
   result: {
     item: "thoriumreactors:electromagnetic_coil"
     count: 2
   }
 }

```


</details>

<details>
<summary>thoriumreactors/thorium_crafting/fluid_centrifuge</summary>

```diff
 {
   type: "thoriumreactors:thorium_crafting"
   key: {
     A: {
-      item: "thoriumreactors:blasted_iron_ingot"
+      tag: "forge:ingots/blasted_iron"
     }
     B: {
-      item: "thoriumreactors:blasted_iron_nugget"
+      tag: "forge:nuggets/blasted_iron"
     }
     C: {
       tag: "forge:ingots/steel"
     }
     D: {
       tag: "forge:nuggets/steel"
     }
     E: {
       item: "minecraft:redstone"
     }
     F: {
       item: "thoriumreactors:machine_casing"
     }
     G: {
       item: "thoriumreactors:module_tank"
     }
     H: {
       tag: "forge:nuggets/cobalt"
     }
     I: {
       tag: "forge:nuggets/molybdenum"
     }
   }
   pattern: [
     " BAB "
     "DGIED"
     "CHFIC"
     "DEHGD"
     " BAB "
   ]
   result: {
     item: "thoriumreactors:fluid_centrifuge_block"
   }
 }

```


</details>

<details>
<summary>thoriumreactors/thorium_crafting/fluid_enricher</summary>

```diff
 {
   type: "thoriumreactors:thorium_crafting"
   key: {
     A: {
-      item: "thoriumreactors:blasted_iron_ingot"
+      tag: "forge:ingots/blasted_iron"
     }
     B: {
-      item: "thoriumreactors:blasted_iron_nugget"
+      tag: "forge:nuggets/blasted_iron"
     }
     C: {
       tag: "forge:ingots/steel"
     }
     D: {
       tag: "forge:nuggets/steel"
     }
     E: {
       item: "minecraft:redstone"
     }
     F: {
       item: "thoriumreactors:machine_casing"
     }
     G: {
       item: "thoriumreactors:module_tank"
     }
     H: {
       tag: "forge:nuggets/cobalt"
     }
     I: {
       tag: "forge:nuggets/molybdenum"
     }
     J: {
-      item: "thoriumreactors:niob_nugget"
+      tag: "forge:nuggets/niob"
     }
   }
   pattern: [
     " BAB "
     "DEJGD"
     "CIFHC"
     "DGJED"
     " BAB "
   ]
   result: {
     item: "thoriumreactors:fluid_enricher_block"
   }
 }

```


</details>

<details>
<summary>thoriumreactors/thorium_crafting/fluid_evaporation</summary>

```diff
 {
   type: "thoriumreactors:thorium_crafting"
   key: {
     A: {
-      item: "thoriumreactors:blasted_iron_ingot"
+      tag: "forge:ingots/blasted_iron"
     }
     B: {
-      item: "thoriumreactors:blasted_iron_nugget"
+      tag: "forge:nuggets/blasted_iron"
     }
     C: {
       tag: "forge:ingots/steel"
     }
     D: {
       tag: "forge:nuggets/steel"
     }
     E: {
       item: "minecraft:water_bucket"
     }
     F: {
       item: "thoriumreactors:machine_casing"
     }
     G: {
       tag: "forge:nuggets/manganese"
     }
     H: {
       item: "thoriumreactors:module_tank"
     }
   }
   pattern: [
     " BAB "
     "DEGED"
     "CGFGC"
     "DHGED"
     " BAB "
   ]
   result: {
     item: "thoriumreactors:fluid_evaporation_block"
   }
 }

```


</details>

<details>
<summary>thoriumreactors/thorium_crafting/generator</summary>

```diff
 {
   type: "thoriumreactors:thorium_crafting"
   key: {
     A: {
       tag: "forge:ingots/iron"
     }
     B: {
       tag: "forge:nuggets/iron"
     }
     C: {
       tag: "forge:gems/coal"
     }
     D: {
       item: "thoriumreactors:machine_casing"
     }
     E: {
-      tag: "forge:nuggets/aluminum"
+      tag: "forge:nuggets/aluminium"
     }
   }
   pattern: [
     " BAB "
     "BCECB"
     "AEDEA"
     "BCECB"
     " BAB "
   ]
   result: {
     item: "thoriumreactors:generator_block"
   }
 }

```


</details>

<details>
<summary>thoriumreactors/thorium_crafting/generic_energy_tank</summary>

```diff
 {
   type: "thoriumreactors:thorium_crafting"
   key: {
     A: {
-      tag: "forge:nuggets/aluminum"
+      tag: "forge:nuggets/aluminium"
     }
     B: {
       tag: "forge:ingots/steel"
     }
     C: {
       item: "minecraft:redstone"
     }
     D: {
       tag: "forge:ingots/iron"
     }
     E: {
       item: "thoriumreactors:simple_energy_tank"
     }
     F: {
       tag: "forge:nuggets/molybdenum"
     }
   }
   pattern: [
     " DDD "
     " BAB "
     " CEC "
     " BFB "
     " DDD "
   ]
   result: {
     item: "thoriumreactors:generic_energy_tank"
   }
 }

```


</details>

<details>
<summary>thoriumreactors/thorium_crafting/generic_fluid_tank</summary>

```diff
 {
   type: "thoriumreactors:thorium_crafting"
   key: {
     A: {
       tag: "forge:nuggets/nickel"
     }
     B: {
       tag: "forge:ingots/steel"
     }
     C: {
       item: "minecraft:redstone"
     }
     D: {
       tag: "forge:ingots/iron"
     }
     E: {
       item: "thoriumreactors:simple_fluid_tank"
     }
     F: {
-      item: "thoriumreactors:niob_nugget"
+      tag: "forge:nuggets/niob"
     }
   }
   pattern: [
     " DDD "
     " BAB "
     " CEC "
     " BFB "
     " DDD "
   ]
   result: {
     item: "thoriumreactors:generic_fluid_tank"
   }
 }

```


</details>

<details>
<summary>thoriumreactors/thorium_crafting/grate_floor_block</summary>

```diff
 {
   type: "thoriumreactors:thorium_crafting"
   key: {
     A: {
-      item: "thoriumreactors:blasted_iron_nugget"
+      tag: "forge:nuggets/blasted_iron"
     }
     B: {
-      item: "thoriumreactors:blasted_iron_ingot"
+      tag: "forge:ingots/blasted_iron"
     }
   }
   pattern: [
     "     "
     " BBB "
     " AAA "
     " BBB "
     "     "
   ]
   result: {
     item: "thoriumreactors:grate_floor_block"
-    count: 2
+    count: 8
   }
 }

```


</details>

<details>
<summary>thoriumreactors/thorium_crafting/industrial_block</summary>

```diff
 {
   type: "thoriumreactors:thorium_crafting"
   key: {
     A: {
       item: "minecraft:smooth_stone"
     }
     B: {
-      item: "thoriumreactors:blasted_iron_nugget"
+      tag: "forge:nuggets/blasted_iron"
     }
   }
   pattern: [
     "     "
     "  B  "
     " BAB "
     "  B  "
     "     "
   ]
   result: {
     item: "thoriumreactors:industrial_block"
     count: 16
   }
 }

```


</details>

<details>
<summary>thoriumreactors/thorium_crafting/industrial_block_smooth</summary>

```diff
 {
   type: "thoriumreactors:thorium_crafting"
   key: {
     A: {
       item: "minecraft:stone"
     }
     B: {
-      item: "thoriumreactors:blasted_iron_nugget"
+      tag: "forge:nuggets/blasted_iron"
     }
   }
   pattern: [
     "     "
     "  B  "
     " BAB "
     "  B  "
     "     "
   ]
   result: {
     item: "thoriumreactors:industrial_block_smooth"
     count: 16
   }
 }

```


</details>

<details>
<summary>thoriumreactors/thorium_crafting/industrial_floor_block</summary>

```diff
 {
   type: "thoriumreactors:thorium_crafting"
   key: {
     A: {
-      item: "thoriumreactors:blasted_iron_nugget"
+      tag: "forge:nuggets/blasted_iron"
     }
     B: {
       item: "minecraft:obsidian"
     }
   }
   pattern: [
     "     "
     "  A  "
     " ABA "
     "  A  "
     "     "
   ]
   result: {
     item: "thoriumreactors:industrial_block_floor"
     count: 16
   }
 }

```


</details>

<details>
<summary>thoriumreactors/thorium_crafting/inverted_factory_block</summary>

```diff
 {
   type: "thoriumreactors:thorium_crafting"
   key: {
     A: {
       item: "thoriumreactors:factory_block"
     }
     B: {
-      item: "minecraft:gray_dye"
+      tag: "forge:dyes/gray"
     }
   }
   pattern: [
     "     "
     " AAA "
     " ABA "
     " AAA "
     "     "
   ]
   result: {
     item: "thoriumreactors:inverted_factory_block"
     count: 8
   }
 }

```


</details>

<details>
<summary>thoriumreactors/thorium_crafting/module_storage</summary>

```diff
 {
   type: "thoriumreactors:thorium_crafting"
   key: {
     A: {
       tag: "forge:nuggets/nickel"
     }
     B: {
-      item: "minecraft:barrel"
+      tag: "forge:barrels"
     }
     C: {
       item: "minecraft:redstone"
     }
     D: {
       tag: "forge:ingots/gold"
     }
     E: {
       tag: "forge:ingots/iron"
     }
     F: {
       tag: "forge:ingots/aluminum"
     }
     G: {
       item: "thoriumreactors:module_empty"
     }
   }
   pattern: [
     " EEE "
     "ECFCE"
     "EABAE"
     "ECGCE"
     " EDE "
   ]
   result: {
     item: "thoriumreactors:module_storage"
   }
 }

```


</details>

<details>
<summary>thoriumreactors/thorium_crafting/progressive_energy_tank</summary>

```diff
 {
   type: "thoriumreactors:thorium_crafting"
   key: {
     A: {
-      item: "thoriumreactors:niob_nugget"
+      tag: "forge:nuggets/niob"
     }
     B: {
       tag: "forge:ingots/steel"
     }
     C: {
       item: "minecraft:redstone"
     }
     D: {
       tag: "forge:ingots/iron"
     }
     E: {
       item: "thoriumreactors:generic_energy_tank"
     }
     F: {
       tag: "forge:nuggets/fluorite"
     }
   }
   pattern: [
     " DDD "
     " BAB "
     " CEC "
     " BFB "
     " DDD "
   ]
   result: {
     item: "thoriumreactors:progressive_energy_tank"
   }
 }

```


</details>

<details>
<summary>thoriumreactors/thorium_crafting/reactor_control_rod</summary>

```diff
 {
   type: "thoriumreactors:thorium_crafting"
   key: {
     A: {
-      item: "thoriumreactors:blasted_iron_ingot"
+      tag: "forge:ingots/blasted_iron"
     }
     B: {
-      item: "thoriumreactors:blasted_iron_nugget"
+      tag: "forge:nuggets/blasted_iron"
     }
     C: {
       tag: "forge:ingots/graphite"
     }
     D: {
       tag: "forge:nuggets/graphite"
     }
     E: {
       item: "thoriumreactors:reactor_graphite_moderator"
     }
     F: {
       item: "thoriumreactors:reactor_casing"
     }
   }
   pattern: [
     "  B  "
     " ADA "
     " CEC "
     " AFA "
     "  B  "
   ]
   result: {
     item: "thoriumreactors:reactor_rod_controller"
   }
 }

```


</details>

<details>
<summary>thoriumreactors/thorium_crafting/reactor_core</summary>

```diff
 {
   type: "thoriumreactors:thorium_crafting"
   key: {
     A: {
       tag: "forge:nuggets/steel"
     }
     B: {
       tag: "forge:ingots/graphite"
     }
     C: {
       item: "thoriumreactors:reactor_casing"
     }
     D: {
-      tag: "forge:ingots/niobium"
+      tag: "forge:ingots/niob"
     }
     E: {
       tag: "forge:ingots/manganese"
     }
     F: {
       tag: "forge:ingots/nickel"
     }
     G: {
       tag: "forge:nuggets/graphite"
     }
   }
   pattern: [
     "  A  "
     " BDB "
     "GCECG"
     " BFB "
     "  A  "
   ]
   result: {
     item: "thoriumreactors:reactor_core"
   }
 }

```


</details>

<details>
<summary>thoriumreactors/thorium_crafting/reactor_valve</summary>

```diff
 {
   type: "thoriumreactors:thorium_crafting"
   key: {
     A: {
       tag: "forge:ingots/aluminum"
     }
     B: {
-      item: "thoriumreactors:blasted_iron_nugget"
+      tag: "forge:nuggets/blasted_iron"
     }
     C: {
       item: "thoriumreactors:reactor_casing"
     }
     D: {
       item: "minecraft:bucket"
     }
     E: {
       tag: "forge:nuggets/gold"
     }
     F: {
       tag: "forge:ingots/graphite"
     }
     G: {
       item: "minecraft:redstone"
     }
   }
   pattern: [
     "  B  "
     " GAG "
     " FDF "
     " GCG "
     "  E  "
   ]
   result: {
     item: "thoriumreactors:reactor_valve"
   }
 }

```


</details>

<details>
<summary>thoriumreactors/thorium_crafting/salt_melter</summary>

```diff
 {
   type: "thoriumreactors:thorium_crafting"
   key: {
     A: {
-      item: "thoriumreactors:blasted_iron_ingot"
+      tag: "forge:ingots/blasted_iron"
     }
     B: {
-      item: "thoriumreactors:blasted_iron_nugget"
+      tag: "forge:nuggets/blasted_iron"
     }
     C: {
       tag: "forge:ingots/steel"
     }
     D: {
       tag: "forge:nuggets/steel"
     }
     E: {
       item: "minecraft:bucket"
     }
     F: {
       item: "thoriumreactors:machine_casing"
     }
     G: {
       tag: "forge:nuggets/manganese"
     }
     H: {
-      item: "thoriumreactors:niob_nugget"
+      tag: "forge:nuggets/niob"
     }
     I: {
       item: "thoriumreactors:module_sensor"
     }
     J: {
       item: "thoriumreactors:module_tank"
     }
   }
   pattern: [
     " BAB "
     "DEGJD"
     "CHFHC"
     "DIGED"
     " BAB "
   ]
   result: {
     item: "thoriumreactors:salt_melter_block"
   }
 }

```


</details>

<details>
<summary>thoriumreactors/thorium_crafting/steel_chest</summary>

```diff
 {
   type: "thoriumreactors:thorium_crafting"
   key: {
     A: {
-      item: "thoriumreactors:blasted_iron_ingot"
+      tag: "forge:ingots/blasted_iron"
     }
     B: {
-      item: "thoriumreactors:blasted_iron_nugget"
+      tag: "forge:nuggets/blasted_iron"
     }
     C: {
       item: "thoriumreactors:blasted_iron_chest_block"
     }
     D: {
       tag: "forge:nuggets/steel"
     }
     E: {
       tag: "forge:ingots/steel"
     }
     F: {
-      item: "thoriumreactors:steel_block"
+      tag: "forge:storage_blocks/steel"
     }
     G: {
       tag: "forge:nuggets/molybdenum"
     }
     H: {
       tag: "forge:nuggets/cobalt"
     }
   }
   pattern: [
     " BAB "
     "BEDEB"
     "AGFHA"
     "BECEB"
     " BAB "
   ]
   result: {
     item: "thoriumreactors:steel_chest_block"
   }
 }

```


</details>

<details>
<summary>thoriumreactors/thorium_crafting/thermal_heat_controller</summary>

```diff
 {
   type: "thoriumreactors:thorium_crafting"
   key: {
     A: {
-      item: "thoriumreactors:blasted_iron_ingot"
+      tag: "forge:ingots/blasted_iron"
     }
     B: {
       tag: "forge:ingots/titanium"
     }
     C: {
       tag: "forge:ingots/aluminum"
     }
     D: {
       item: "thoriumreactors:thermal_conductor"
     }
     E: {
       item: "thoriumreactors:redstone_processor"
     }
     F: {
       tag: "forge:nuggets/nickel"
     }
     G: {
       item: "minecraft:redstone"
     }
   }
   pattern: [
     "     "
     " GCG "
     "FADBF"
     " GEG "
     "     "
   ]
   result: {
     item: "thoriumreactors:thermal_controller"
     count: 1
   }
 }

```


</details>

<details>
<summary>thoriumreactors/thorium_crafting/thermal_heat_valve</summary>

```diff
 {
   type: "thoriumreactors:thorium_crafting"
   key: {
     A: {
-      item: "thoriumreactors:blasted_iron_ingot"
+      tag: "forge:ingots/blasted_iron"
     }
     B: {
       tag: "forge:ingots/titanium"
     }
     C: {
       tag: "forge:nuggets/titanium"
     }
     D: {
       tag: "forge:ingots/aluminum"
     }
     E: {
       item: "thoriumreactors:thermal_conductor"
     }
     F: {
       item: "minecraft:redstone"
     }
     G: {
       item: "minecraft:bucket"
     }
     H: {
       tag: "forge:nuggets/gold"
     }
   }
   pattern: [
     "  C  "
     " FDF "
     " AGB "
     " FEF "
     "  H  "
   ]
   result: {
     item: "thoriumreactors:thermal_valve"
     count: 1
   }
 }

```


</details>

<details>
<summary>thoriumreactors/thorium_crafting/thorium_chest</summary>

```diff
 {
   type: "thoriumreactors:thorium_crafting"
   key: {
     A: {
       tag: "forge:nuggets/steel"
     }
     B: {
-      item: "thoriumreactors:blasted_iron_nugget"
+      tag: "forge:nuggets/blasted_iron"
     }
     C: {
       item: "thoriumreactors:steel_chest_block"
     }
     D: {
       tag: "forge:thorium"
     }
     E: {
       item: "thoriumreactors:thorium_block"
     }
     F: {
-      tag: "forge:ingots/chromium"
+      tag: "forge:ingots/chrome"
     }
     G: {
-      tag: "forge:ingots/niobium"
+      tag: "forge:ingots/niob"
     }
     H: {
       tag: "forge:ingots/manganese"
     }
   }
   pattern: [
     " ABA "
     "ADFDA"
     "BGEHB"
     "ADCDA"
     " ABA "
   ]
   result: {
     item: "thoriumreactors:thorium_chest_block"
   }
 }

```


</details>

<details>
<summary>thoriumreactors/thorium_crafting/turbine_blade</summary>

```diff
 {
   type: "thoriumreactors:thorium_crafting"
   key: {
     A: {
-      item: "thoriumreactors:blasted_iron_ingot"
+      tag: "forge:ingots/blasted_iron"
     }
     B: {
       tag: "forge:ingots/steel"
     }
     C: {
       tag: "forge:nuggets/steel"
     }
   }
   pattern: [
     "   A "
     "  AAA"
     " AAA "
     "BAA  "
     "CB   "
   ]
   result: {
     item: "thoriumreactors:turbine_blade"
     count: 2
   }
 }

```


</details>

<details>
<summary>thoriumreactors/thorium_crafting/turbine_casing</summary>

```diff
 {
   type: "thoriumreactors:thorium_crafting"
   key: {
     A: {
-      item: "thoriumreactors:blasted_iron_nugget"
+      tag: "forge:nuggets/blasted_iron"
     }
     B: {
       tag: "forge:ingots/titanium"
     }
     C: {
       tag: "forge:nuggets/titanium"
     }
     D: {
       tag: "forge:ingots/iron"
     }
     E: {
       tag: "forge:ingots/aluminum"
     }
     F: {
       item: "thoriumreactors:blasted_stone"
     }
   }
   pattern: [
     " CDA "
     "AEBEC"
     "DBFBD"
     "CEBEA"
     " ADC "
   ]
   result: {
     item: "thoriumreactors:turbine_casing"
     count: 2
   }
 }

```


</details>

<details>
<summary>thoriumreactors/thorium_crafting/turbine_power_port</summary>

```diff
 {
   type: "thoriumreactors:thorium_crafting"
   key: {
     A: {
       tag: "forge:ingots/steel"
     }
     B: {
       tag: "forge:ingots/titanium"
     }
     C: {
       tag: "forge:ingots/aluminum"
     }
     D: {
       item: "minecraft:redstone"
     }
     E: {
       item: "thoriumreactors:turbine_casing"
     }
     F: {
       tag: "forge:nuggets/nickel"
     }
     G: {
       tag: "forge:nuggets/steel"
     }
     H: {
-      item: "thoriumreactors:blasted_iron_nugget"
+      tag: "forge:nuggets/blasted_iron"
     }
   }
   pattern: [
     "  G  "
     " DCD "
     " BFA "
     " DED "
     "  H  "
   ]
   result: {
     item: "thoriumreactors:turbine_power_port"
   }
 }

```


</details>

<details>
<summary>thoriumreactors/thorium_crafting/turbine_rotation_mount</summary>

```diff
 {
   type: "thoriumreactors:thorium_crafting"
   key: {
     A: {
       tag: "forge:nuggets/titanium"
     }
     B: {
       tag: "forge:ingots/titanium"
     }
     C: {
-      item: "thoriumreactors:blasted_iron_ingot"
+      tag: "forge:ingots/blasted_iron"
     }
     D: {
       item: "thoriumreactors:turbine_casing"
     }
     E: {
       item: "thoriumreactors:turbine_rotor"
     }
     F: {
       tag: "forge:nuggets/steel"
     }
   }
   pattern: [
     "  A  "
     " CFB "
     "AFEFA"
     " BFC "
     "  D  "
   ]
   result: {
     item: "thoriumreactors:turbine_rotation_mount"
   }
 }

```


</details>

<details>
<summary>thoriumreactors/thorium_crafting/turbine_rotor</summary>

```diff
 {
   type: "thoriumreactors:thorium_crafting"
   key: {
     A: {
       tag: "forge:ingots/steel"
     }
     B: {
       tag: "forge:nuggets/steel"
     }
     C: {
-      item: "thoriumreactors:blasted_iron_ingot"
+      tag: "forge:ingots/blasted_iron"
     }
   }
   pattern: [
     "  B  "
     " CAC "
     " CAC "
     " CAC "
     "  B  "
   ]
   result: {
     item: "thoriumreactors:turbine_rotor"
     count: 2
   }
 }

```


</details>

<details>
<summary>thoriumreactors/thorium_crafting/uranium_oxidizer_block</summary>

```diff
 {
   type: "thoriumreactors:thorium_crafting"
   key: {
     A: {
-      item: "thoriumreactors:blasted_iron_ingot"
+      tag: "forge:ingots/blasted_iron"
     }
     B: {
-      item: "thoriumreactors:blasted_iron_nugget"
+      tag: "forge:nuggets/blasted_iron"
     }
     C: {
       tag: "forge:ingots/steel"
     }
     D: {
       tag: "forge:nuggets/steel"
     }
     E: {
       item: "minecraft:redstone"
     }
     F: {
       item: "thoriumreactors:machine_casing"
     }
     G: {
       item: "thoriumreactors:module_tank"
     }
     H: {
       tag: "forge:nuggets/manganese"
     }
     I: {
       tag: "forge:nuggets/molybdenum"
     }
     J: {
-      item: "thoriumreactors:niob_nugget"
+      tag: "forge:nuggets/niob"
     }
   }
   pattern: [
     " BAB "
     "DEIED"
     "CJFJC"
     "DGHGD"
     " BAB "
   ]
   result: {
     item: "thoriumreactors:uranium_oxidizer_block"
   }
 }

```


</details>

<details>
<summary>thoriumreactors/thorium_crafting/warning_block_lined_black_yellow_left</summary>

```diff
 {
   type: "thoriumreactors:thorium_crafting"
   key: {
     B: {
       item: "minecraft:stone"
     }
     C: {
-      item: "minecraft:black_dye"
+      tag: "forge:dyes/black"
     }
     D: {
-      item: "minecraft:yellow_dye"
+      tag: "forge:dyes/yellow"
     }
   }
   pattern: [
     "     "
     " BCB "
     " DBC "
     " BDB "
     "     "
   ]
   result: {
     item: "thoriumreactors:warning_block_lined_black_yellow_left"
     count: 5
   }
 }

```


</details>

<details>
<summary>thoriumreactors/thorium_crafting/warning_block_lined_black_yellow_right</summary>

```diff
 {
   type: "thoriumreactors:thorium_crafting"
   key: {
     B: {
       item: "minecraft:stone"
     }
     C: {
-      item: "minecraft:black_dye"
+      tag: "forge:dyes/black"
     }
     D: {
-      item: "minecraft:yellow_dye"
+      tag: "forge:dyes/yellow"
     }
   }
   pattern: [
     "     "
     " BCB "
     " CBD "
     " BDB "
     "     "
   ]
   result: {
     item: "thoriumreactors:warning_block_lined_black_yellow_right"
     count: 5
   }
 }

```


</details>

<details>
<summary>thoriumreactors/thorium_crafting/warning_block_lined_white_black_left</summary>

```diff
 {
   type: "thoriumreactors:thorium_crafting"
   key: {
     B: {
       item: "minecraft:stone"
     }
     C: {
-      item: "minecraft:white_dye"
+      tag: "forge:dyes/white"
     }
     D: {
-      item: "minecraft:black_dye"
+      tag: "forge:dyes/black"
     }
   }
   pattern: [
     "     "
     " BCB "
     " DBC "
     " BDB "
     "     "
   ]
   result: {
     item: "thoriumreactors:warning_block_lined_white_black_left"
     count: 5
   }
 }

```


</details>

<details>
<summary>thoriumreactors/thorium_crafting/warning_block_lined_white_black_right</summary>

```diff
 {
   type: "thoriumreactors:thorium_crafting"
   key: {
     B: {
       item: "minecraft:stone"
     }
     C: {
-      item: "minecraft:white_dye"
+      tag: "forge:dyes/white"
     }
     D: {
-      item: "minecraft:black_dye"
+      tag: "forge:dyes/black"
     }
   }
   pattern: [
     "     "
     " BCB "
     " CBD "
     " BDB "
     "     "
   ]
   result: {
     item: "thoriumreactors:warning_block_lined_white_black_right"
     count: 5
   }
 }

```


</details>

<details>
<summary>thoriumreactors/thorium_crafting/warning_block_lined_white_orange_left</summary>

```diff
 {
   type: "thoriumreactors:thorium_crafting"
   key: {
     B: {
       item: "minecraft:stone"
     }
     C: {
-      item: "minecraft:white_dye"
+      tag: "forge:dyes/white"
     }
     D: {
-      item: "minecraft:orange_dye"
+      tag: "forge:dyes/orange"
     }
   }
   pattern: [
     "     "
     " BCB "
     " DBC "
     " BDB "
     "     "
   ]
   result: {
     item: "thoriumreactors:warning_block_lined_white_orange_left"
     count: 5
   }
 }

```


</details>

<details>
<summary>thoriumreactors/thorium_crafting/warning_block_lined_white_orange_right</summary>

```diff
 {
   type: "thoriumreactors:thorium_crafting"
   key: {
     B: {
       item: "minecraft:stone"
     }
     C: {
-      item: "minecraft:white_dye"
+      tag: "forge:dyes/white"
     }
     D: {
-      item: "minecraft:orange_dye"
+      tag: "forge:dyes/orange"
     }
   }
   pattern: [
     "     "
     " BCB "
     " CBD "
     " BDB "
     "     "
   ]
   result: {
     item: "thoriumreactors:warning_block_lined_white_orange_right"
     count: 5
   }
 }

```


</details>

<details>
<summary>thoriumreactors/thorium_crafting/water_source_block</summary>

```diff
 {
   type: "thoriumreactors:thorium_crafting"
   key: {
     A: {
-      item: "thoriumreactors:tank_module"
+      item: "thoriumreactors:module_tank"
     }
     B: {
       tag: "forge:nuggets/manganese"
     }
     C: {
       tag: "forge:nuggets/cobalt"
     }
     D: {
-      item: "thoriumreactors:niob_nugget"
+      tag: "forge:nuggets/niob"
     }
     E: {
       tag: "forge:nuggets/molybdenum"
     }
     F: {
       tag: "forge:ingots/iron"
     }
     G: {
       item: "minecraft:water_bucket"
     }
   }
   pattern: [
     " FFF "
     "FBGCF"
     "FGAGF"
     "FDGEF"
     " FFF "
   ]
   result: {
     item: "thoriumreactors:water_source_block"
   }
 }

```


</details>

<details>
<summary>thoriumreactors/thorium_crafting/white_industrial_block</summary>

```diff
 {
   type: "thoriumreactors:thorium_crafting"
   key: {
     A: {
       item: "thoriumreactors:industrial_block"
     }
     B: {
-      item: "minecraft:white_dye"
+      tag: "forge:dyes/white"
     }
   }
   pattern: [
     "     "
     " AAA "
     " ABA "
     " AAA "
     "     "
   ]
   result: {
     item: "thoriumreactors:white_industrial_block"
     count: 8
   }
 }

```


</details>

<details>
<summary>thoriumreactors/thorium_crafting/white_industrial_block_smooth</summary>

```diff
 {
   type: "thoriumreactors:thorium_crafting"
   key: {
     A: {
       item: "thoriumreactors:industrial_block_smooth"
     }
     B: {
-      item: "minecraft:white_dye"
+      tag: "forge:dyes/white"
     }
   }
   pattern: [
     "     "
     " AAA "
     " ABA "
     " AAA "
     "     "
   ]
   result: {
     item: "thoriumreactors:white_industrial_block_smooth"
     count: 8
   }
 }

```


</details>

<details>
<summary>thoriumreactors/titanium_block_craft_from_ingot</summary>

```diff
 {
   type: "minecraft:crafting_shapeless"
   category: "misc"
   ingredients: [
     {
       tag: "forge:ingots/titanium"
     }
     {
       tag: "forge:ingots/titanium"
     }
     {
       tag: "forge:ingots/titanium"
     }
     {
       tag: "forge:ingots/titanium"
     }
     {
       tag: "forge:ingots/titanium"
     }
     {
       tag: "forge:ingots/titanium"
     }
     {
       tag: "forge:ingots/titanium"
     }
     {
       tag: "forge:ingots/titanium"
     }
     {
       tag: "forge:ingots/titanium"
     }
   ]
   result: {
-    item: "thoriumreactors:titanium_block"
+    item: "gtceu:titanium_block"
   }
 }

```


</details>

<details>
<summary>thoriumreactors/titanium_ingot_craft_from_block</summary>

```diff
 {
   type: "minecraft:crafting_shapeless"
   category: "misc"
   ingredients: [
     {
-      item: "thoriumreactors:titanium_block"
+      tag: "forge:storage_blocks/titanium"
     }
   ]
   result: {
     count: 9
     item: "gtceu:titanium_ingot"
   }
 }

```


</details>

<details>
<summary>thoriumreactors/uranium_block_craft_from_ingot</summary>

```diff
 {
   type: "minecraft:crafting_shapeless"
   category: "misc"
   ingredients: [
     {
       tag: "forge:ingots/uranium"
     }
     {
       tag: "forge:ingots/uranium"
     }
     {
       tag: "forge:ingots/uranium"
     }
     {
       tag: "forge:ingots/uranium"
     }
     {
       tag: "forge:ingots/uranium"
     }
     {
       tag: "forge:ingots/uranium"
     }
     {
       tag: "forge:ingots/uranium"
     }
     {
       tag: "forge:ingots/uranium"
     }
     {
       tag: "forge:ingots/uranium"
     }
   ]
   result: {
-    item: "thoriumreactors:uranium_block"
+    item: "gtceu:uranium_block"
   }
 }

```


</details>

<details>
<summary>thoriumreactors/white_industrial_block_big_tile</summary>

```diff
 {
   type: "minecraft:crafting_shaped"
   category: "misc"
   key: {
     A: {
-      item: "thoriumreactors:black_industrial_block"
+      item: "thoriumreactors:white_industrial_block"
     }
   }
   pattern: [
     "A A"
     "AAA"
     "A A"
   ]
   result: {
     count: 7
     item: "thoriumreactors:white_industrial_block_big_tile"
   }
   show_notification: true
 }

```


</details>

<details>
<summary>thoriumreactors/white_industrial_block_brick</summary>

```diff
 {
   type: "minecraft:crafting_shaped"
   category: "misc"
   key: {
     A: {
-      item: "thoriumreactors:black_industrial_block"
+      item: "thoriumreactors:white_industrial_block"
     }
   }
   pattern: [
     "AAA"
     " A "
     "AAA"
   ]
   result: {
     count: 7
     item: "thoriumreactors:white_industrial_block_brick"
   }
   show_notification: true
 }

```


</details>

<details>
<summary>thoriumreactors/white_industrial_block_paving</summary>

```diff
 {
   type: "minecraft:crafting_shaped"
   category: "misc"
   key: {
     A: {
-      item: "thoriumreactors:black_industrial_block"
+      item: "thoriumreactors:white_industrial_block"
     }
   }
   pattern: [
     "AAA"
     "A A"
     "AAA"
   ]
   result: {
     count: 8
     item: "thoriumreactors:white_industrial_block_paving"
   }
   show_notification: true
 }

```


</details>

<details>
<summary>thoriumreactors/white_industrial_block_smooth</summary>

```diff
 {
   type: "minecraft:crafting_shaped"
   category: "misc"
   key: {
     A: {
       item: "thoriumreactors:industrial_block_smooth"
     }
     B: {
       item: "minecraft:white_dye"
     }
   }
   pattern: [
-    " A "
-    " A "
+    "AAA"
+    "AAA"
     "ABA"
   ]
   result: {
     count: 8
     item: "thoriumreactors:white_industrial_block_smooth"
   }
   show_notification: true
 }

```


</details>

</blockquote>

</details>

<details>
<summary>Removed (3202)</summary>
<blockquote>

<details>
<summary>computercraft/computer_advanced</summary>

```diff
-{
-  type: "minecraft:crafting_shaped"
-  category: "redstone"
-  key: {
-    #: {
-      tag: "forge:ingots/gold"
-    }
-    G: {
-      tag: "forge:glass_panes"
-    }
-    R: {
-      tag: "forge:dusts/redstone"
-    }
-  }
-  pattern: [
-    "###"
-    "#R#"
-    "#G#"
-  ]
-  result: {
-    item: "computercraft:computer_advanced"
-  }
-  show_notification: true
-}

```


</details>

<details>
<summary>computercraft/computer_advanced_upgrade</summary>

```diff
-{
-  type: "computercraft:computer_upgrade"
-  category: "redstone"
-  key: {
-    #: {
-      tag: "forge:ingots/gold"
-    }
-    C: {
-      item: "computercraft:computer_normal"
-    }
-  }
-  pattern: [
-    "###"
-    "#C#"
-    "# #"
-  ]
-  result: {
-    item: "computercraft:computer_advanced"
-  }
-  show_notification: true
-}

```


</details>

<details>
<summary>computercraft/computer_normal</summary>

```diff
-{
-  type: "minecraft:crafting_shaped"
-  category: "redstone"
-  key: {
-    #: {
-      tag: "forge:stone"
-    }
-    G: {
-      tag: "forge:glass_panes"
-    }
-    R: {
-      tag: "forge:dusts/redstone"
-    }
-  }
-  pattern: [
-    "###"
-    "#R#"
-    "#G#"
-  ]
-  result: {
-    item: "computercraft:computer_normal"
-  }
-  show_notification: true
-}

```


</details>

<details>
<summary>computercraft/pocket_computer_advanced</summary>

```diff
-{
-  type: "minecraft:crafting_shaped"
-  category: "redstone"
-  key: {
-    #: {
-      tag: "forge:ingots/gold"
-    }
-    A: {
-      item: "minecraft:golden_apple"
-    }
-    G: {
-      tag: "forge:glass_panes"
-    }
-  }
-  pattern: [
-    "###"
-    "#A#"
-    "#G#"
-  ]
-  result: {
-    item: "computercraft:pocket_computer_advanced"
-  }
-  show_notification: true
-}

```


</details>

<details>
<summary>computercraft/pocket_computer_advanced_upgrade</summary>

```diff
-{
-  type: "computercraft:computer_upgrade"
-  category: "redstone"
-  key: {
-    #: {
-      tag: "forge:ingots/gold"
-    }
-    C: {
-      item: "computercraft:pocket_computer_normal"
-    }
-  }
-  pattern: [
-    "###"
-    "#C#"
-    "# #"
-  ]
-  result: {
-    item: "computercraft:pocket_computer_advanced"
-  }
-  show_notification: true
-}

```


</details>

<details>
<summary>computercraft/pocket_computer_normal</summary>

```diff
-{
-  type: "minecraft:crafting_shaped"
-  category: "redstone"
-  key: {
-    #: {
-      tag: "forge:stone"
-    }
-    A: {
-      item: "minecraft:golden_apple"
-    }
-    G: {
-      tag: "forge:glass_panes"
-    }
-  }
-  pattern: [
-    "###"
-    "#A#"
-    "#G#"
-  ]
-  result: {
-    item: "computercraft:pocket_computer_normal"
-  }
-  show_notification: true
-}

```


</details>

<details>
<summary>computercraft/wireless_modem_advanced</summary>

```diff
-{
-  type: "minecraft:crafting_shaped"
-  category: "redstone"
-  key: {
-    #: {
-      tag: "forge:ingots/gold"
-    }
-    E: {
-      item: "minecraft:ender_eye"
-    }
-  }
-  pattern: [
-    "###"
-    "#E#"
-    "###"
-  ]
-  result: {
-    item: "computercraft:wireless_modem_advanced"
-  }
-  show_notification: true
-}

```


</details>

<details>
<summary>computercraft/wireless_modem_normal</summary>

```diff
-{
-  type: "minecraft:crafting_shaped"
-  category: "redstone"
-  key: {
-    #: {
-      tag: "forge:stone"
-    }
-    E: {
-      tag: "forge:ender_pearls"
-    }
-  }
-  pattern: [
-    "###"
-    "#E#"
-    "###"
-  ]
-  result: {
-    item: "computercraft:wireless_modem_normal"
-  }
-  show_notification: true
-}

```


</details>

<details>
<summary>gcyr/collapse/andesite_fluorite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gcyr:andesite_fluorite_ore"
-  result: "gcyr:andesite_fluorite_ore"
-}

```


</details>

<details>
<summary>gcyr/collapse/basalt_fluorite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gcyr:basalt_fluorite_ore"
-  result: "gcyr:basalt_fluorite_ore"
-}

```


</details>

<details>
<summary>gcyr/collapse/chalk_fluorite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gcyr:chalk_fluorite_ore"
-  result: "gcyr:chalk_fluorite_ore"
-}

```


</details>

<details>
<summary>gcyr/collapse/chert_fluorite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gcyr:chert_fluorite_ore"
-  result: "gcyr:chert_fluorite_ore"
-}

```


</details>

<details>
<summary>gcyr/collapse/claystone_fluorite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gcyr:claystone_fluorite_ore"
-  result: "gcyr:claystone_fluorite_ore"
-}

```


</details>

<details>
<summary>gcyr/collapse/conglomerate_fluorite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gcyr:conglomerate_fluorite_ore"
-  result: "gcyr:conglomerate_fluorite_ore"
-}

```


</details>

<details>
<summary>gcyr/collapse/dacite_fluorite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gcyr:dacite_fluorite_ore"
-  result: "gcyr:dacite_fluorite_ore"
-}

```


</details>

<details>
<summary>gcyr/collapse/deepslate_fluorite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gcyr:deepslate_fluorite_ore"
-  result: "gcyr:deepslate_fluorite_ore"
-}

```


</details>

<details>
<summary>gcyr/collapse/diorite_fluorite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gcyr:diorite_fluorite_ore"
-  result: "gcyr:diorite_fluorite_ore"
-}

```


</details>

<details>
<summary>gcyr/collapse/dolomite_fluorite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gcyr:dolomite_fluorite_ore"
-  result: "gcyr:dolomite_fluorite_ore"
-}

```


</details>

<details>
<summary>gcyr/collapse/endstone_fluorite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gcyr:endstone_fluorite_ore"
-  result: "gcyr:endstone_fluorite_ore"
-}

```


</details>

<details>
<summary>gcyr/collapse/fluorite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gcyr:fluorite_ore"
-  result: "gcyr:fluorite_ore"
-}

```


</details>

<details>
<summary>gcyr/collapse/gabbro_fluorite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gcyr:gabbro_fluorite_ore"
-  result: "gcyr:gabbro_fluorite_ore"
-}

```


</details>

<details>
<summary>gcyr/collapse/gneiss_fluorite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gcyr:gneiss_fluorite_ore"
-  result: "gcyr:gneiss_fluorite_ore"
-}

```


</details>

<details>
<summary>gcyr/collapse/granite_fluorite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gcyr:granite_fluorite_ore"
-  result: "gcyr:granite_fluorite_ore"
-}

```


</details>

<details>
<summary>gcyr/collapse/limestone_fluorite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gcyr:limestone_fluorite_ore"
-  result: "gcyr:limestone_fluorite_ore"
-}

```


</details>

<details>
<summary>gcyr/collapse/marble_fluorite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gcyr:marble_fluorite_ore"
-  result: "gcyr:marble_fluorite_ore"
-}

```


</details>

<details>
<summary>gcyr/collapse/mars_fluorite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gcyr:mars_fluorite_ore"
-  result: "gcyr:mars_fluorite_ore"
-}

```


</details>

<details>
<summary>gcyr/collapse/mercury_fluorite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gcyr:mercury_fluorite_ore"
-  result: "gcyr:mercury_fluorite_ore"
-}

```


</details>

<details>
<summary>gcyr/collapse/moon_fluorite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gcyr:moon_fluorite_ore"
-  result: "gcyr:moon_fluorite_ore"
-}

```


</details>

<details>
<summary>gcyr/collapse/netherrack_fluorite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gcyr:netherrack_fluorite_ore"
-  result: "gcyr:netherrack_fluorite_ore"
-}

```


</details>

<details>
<summary>gcyr/collapse/phyllite_fluorite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gcyr:phyllite_fluorite_ore"
-  result: "gcyr:phyllite_fluorite_ore"
-}

```


</details>

<details>
<summary>gcyr/collapse/quartzite_fluorite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gcyr:quartzite_fluorite_ore"
-  result: "gcyr:quartzite_fluorite_ore"
-}

```


</details>

<details>
<summary>gcyr/collapse/rhyolite_fluorite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gcyr:rhyolite_fluorite_ore"
-  result: "gcyr:rhyolite_fluorite_ore"
-}

```


</details>

<details>
<summary>gcyr/collapse/schist_fluorite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gcyr:schist_fluorite_ore"
-  result: "gcyr:schist_fluorite_ore"
-}

```


</details>

<details>
<summary>gcyr/collapse/shale_fluorite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gcyr:shale_fluorite_ore"
-  result: "gcyr:shale_fluorite_ore"
-}

```


</details>

<details>
<summary>gcyr/collapse/slate_fluorite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gcyr:slate_fluorite_ore"
-  result: "gcyr:slate_fluorite_ore"
-}

```


</details>

<details>
<summary>gcyr/collapse/venus_fluorite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gcyr:venus_fluorite_ore"
-  result: "gcyr:venus_fluorite_ore"
-}

```


</details>

<details>
<summary>gregitas/casting/rubber_ingot</summary>

```diff
-{
-  type: "tfc:casting"
-  mold: {
-    item: "tfc:ceramic/ingot_mold"
-  }
-  fluid: {
-    ingredient: {
-      fluid: "gtceu:rubber"
-      amount: 1000
-    }
-    amount: 144
-  }
-  result: {
-    item: "gtceu:rubber_ingot"
-    count: 1
-  }
-  break_chance: 0.1
-}

```


</details>

<details>
<summary>gtceu/alloy_smelter/anvil</summary>

```diff
-{
-  type: "gtceu:alloy_smelter"
-  duration: 1680
-  inputs: {
-    item: [
-      {
-        content: {
-          type: "gtceu:sized"
-          count: 31
-          ingredient: {
-            tag: "forge:ingots/iron"
-          }
-        }
-        chance: 1
-        tierChanceBoost: 0
-      }
-      {
-        content: {
-          type: "gtceu:sized"
-          count: 1
-          ingredient: {
-            item: "gtceu:anvil_casting_mold"
-          }
-        }
-        chance: 0
-        tierChanceBoost: 0
-      }
-    ]
-  }
-  outputs: {
-    item: [
-      {
-        content: {
-          type: "gtceu:sized"
-          count: 1
-          ingredient: {
-            item: "minecraft:anvil"
-          }
-        }
-        chance: 1
-        tierChanceBoost: 0
-      }
-    ]
-  }
-  tickInputs: {
-    eu: [
-      {
-        content: 16
-        chance: 1
-        tierChanceBoost: 0
-      }
-    ]
-  }
-  tickOutputs: {
-  }
-}

```


</details>

<details>
<summary>gtceu/collapse/almandine_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:almandine_ore"
-  result: "gtceu:almandine_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/aluminium_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:aluminium_ore"
-  result: "gtceu:aluminium_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/alunite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:alunite_ore"
-  result: "gtceu:alunite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/amethyst_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:amethyst_ore"
-  result: "gtceu:amethyst_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/andesite_almandine_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:andesite_almandine_ore"
-  result: "gtceu:andesite_almandine_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/andesite_aluminium_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:andesite_aluminium_ore"
-  result: "gtceu:andesite_aluminium_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/andesite_alunite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:andesite_alunite_ore"
-  result: "gtceu:andesite_alunite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/andesite_amethyst_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:andesite_amethyst_ore"
-  result: "gtceu:andesite_amethyst_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/andesite_apatite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:andesite_apatite_ore"
-  result: "gtceu:andesite_apatite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/andesite_asbestos_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:andesite_asbestos_ore"
-  result: "gtceu:andesite_asbestos_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/andesite_barite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:andesite_barite_ore"
-  result: "gtceu:andesite_barite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/andesite_basaltic_mineral_sand_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:andesite_basaltic_mineral_sand_ore"
-  result: "gtceu:andesite_basaltic_mineral_sand_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/andesite_bastnasite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:andesite_bastnasite_ore"
-  result: "gtceu:andesite_bastnasite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/andesite_bauxite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:andesite_bauxite_ore"
-  result: "gtceu:andesite_bauxite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/andesite_bentonite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:andesite_bentonite_ore"
-  result: "gtceu:andesite_bentonite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/andesite_beryllium_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:andesite_beryllium_ore"
-  result: "gtceu:andesite_beryllium_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/andesite_blue_topaz_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:andesite_blue_topaz_ore"
-  result: "gtceu:andesite_blue_topaz_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/andesite_bornite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:andesite_bornite_ore"
-  result: "gtceu:andesite_bornite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/andesite_calcite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:andesite_calcite_ore"
-  result: "gtceu:andesite_calcite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/andesite_cassiterite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:andesite_cassiterite_ore"
-  result: "gtceu:andesite_cassiterite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/andesite_cassiterite_sand_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:andesite_cassiterite_sand_ore"
-  result: "gtceu:andesite_cassiterite_sand_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/andesite_certus_quartz_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:andesite_certus_quartz_ore"
-  result: "gtceu:andesite_certus_quartz_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/andesite_chalcocite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:andesite_chalcocite_ore"
-  result: "gtceu:andesite_chalcocite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/andesite_chalcopyrite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:andesite_chalcopyrite_ore"
-  result: "gtceu:andesite_chalcopyrite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/andesite_chromite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:andesite_chromite_ore"
-  result: "gtceu:andesite_chromite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/andesite_cinnabar_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:andesite_cinnabar_ore"
-  result: "gtceu:andesite_cinnabar_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/andesite_coal_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:andesite_coal_ore"
-  result: "gtceu:andesite_coal_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/andesite_cobalt_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:andesite_cobalt_ore"
-  result: "gtceu:andesite_cobalt_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/andesite_cobaltite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:andesite_cobaltite_ore"
-  result: "gtceu:andesite_cobaltite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/andesite_cooperite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:andesite_cooperite_ore"
-  result: "gtceu:andesite_cooperite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/andesite_copper_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:andesite_copper_ore"
-  result: "gtceu:andesite_copper_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/andesite_diamond_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:andesite_diamond_ore"
-  result: "gtceu:andesite_diamond_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/andesite_diatomite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:andesite_diatomite_ore"
-  result: "gtceu:andesite_diatomite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/andesite_electrotine_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:andesite_electrotine_ore"
-  result: "gtceu:andesite_electrotine_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/andesite_emerald_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:andesite_emerald_ore"
-  result: "gtceu:andesite_emerald_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/andesite_fullers_earth_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:andesite_fullers_earth_ore"
-  result: "gtceu:andesite_fullers_earth_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/andesite_galena_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:andesite_galena_ore"
-  result: "gtceu:andesite_galena_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/andesite_garnet_sand_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:andesite_garnet_sand_ore"
-  result: "gtceu:andesite_garnet_sand_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/andesite_garnierite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:andesite_garnierite_ore"
-  result: "gtceu:andesite_garnierite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/andesite_glauconite_sand_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:andesite_glauconite_sand_ore"
-  result: "gtceu:andesite_glauconite_sand_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/andesite_goethite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:andesite_goethite_ore"
-  result: "gtceu:andesite_goethite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/andesite_gold_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:andesite_gold_ore"
-  result: "gtceu:andesite_gold_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/andesite_granitic_mineral_sand_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:andesite_granitic_mineral_sand_ore"
-  result: "gtceu:andesite_granitic_mineral_sand_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/andesite_graphite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:andesite_graphite_ore"
-  result: "gtceu:andesite_graphite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/andesite_green_sapphire_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:andesite_green_sapphire_ore"
-  result: "gtceu:andesite_green_sapphire_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/andesite_grossular_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:andesite_grossular_ore"
-  result: "gtceu:andesite_grossular_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/andesite_gypsum_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:andesite_gypsum_ore"
-  result: "gtceu:andesite_gypsum_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/andesite_hematite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:andesite_hematite_ore"
-  result: "gtceu:andesite_hematite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/andesite_ilmenite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:andesite_ilmenite_ore"
-  result: "gtceu:andesite_ilmenite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/andesite_iron_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:andesite_iron_ore"
-  result: "gtceu:andesite_iron_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/andesite_kyanite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:andesite_kyanite_ore"
-  result: "gtceu:andesite_kyanite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/andesite_lapis_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:andesite_lapis_ore"
-  result: "gtceu:andesite_lapis_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/andesite_lazurite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:andesite_lazurite_ore"
-  result: "gtceu:andesite_lazurite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/andesite_lead_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:andesite_lead_ore"
-  result: "gtceu:andesite_lead_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/andesite_lepidolite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:andesite_lepidolite_ore"
-  result: "gtceu:andesite_lepidolite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/andesite_lithium_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:andesite_lithium_ore"
-  result: "gtceu:andesite_lithium_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/andesite_magnesite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:andesite_magnesite_ore"
-  result: "gtceu:andesite_magnesite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/andesite_magnetite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:andesite_magnetite_ore"
-  result: "gtceu:andesite_magnetite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/andesite_malachite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:andesite_malachite_ore"
-  result: "gtceu:andesite_malachite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/andesite_mica_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:andesite_mica_ore"
-  result: "gtceu:andesite_mica_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/andesite_molybdenite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:andesite_molybdenite_ore"
-  result: "gtceu:andesite_molybdenite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/andesite_molybdenum_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:andesite_molybdenum_ore"
-  result: "gtceu:andesite_molybdenum_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/andesite_monazite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:andesite_monazite_ore"
-  result: "gtceu:andesite_monazite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/andesite_naquadah_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:andesite_naquadah_ore"
-  result: "gtceu:andesite_naquadah_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/andesite_neodymium_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:andesite_neodymium_ore"
-  result: "gtceu:andesite_neodymium_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/andesite_nether_quartz_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:andesite_nether_quartz_ore"
-  result: "gtceu:andesite_nether_quartz_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/andesite_nickel_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:andesite_nickel_ore"
-  result: "gtceu:andesite_nickel_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/andesite_oilsands_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:andesite_oilsands_ore"
-  result: "gtceu:andesite_oilsands_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/andesite_olivine_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:andesite_olivine_ore"
-  result: "gtceu:andesite_olivine_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/andesite_opal_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:andesite_opal_ore"
-  result: "gtceu:andesite_opal_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/andesite_palladium_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:andesite_palladium_ore"
-  result: "gtceu:andesite_palladium_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/andesite_pentlandite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:andesite_pentlandite_ore"
-  result: "gtceu:andesite_pentlandite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/andesite_pitchblende_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:andesite_pitchblende_ore"
-  result: "gtceu:andesite_pitchblende_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/andesite_platinum_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:andesite_platinum_ore"
-  result: "gtceu:andesite_platinum_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/andesite_plutonium_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:andesite_plutonium_ore"
-  result: "gtceu:andesite_plutonium_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/andesite_pollucite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:andesite_pollucite_ore"
-  result: "gtceu:andesite_pollucite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/andesite_powellite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:andesite_powellite_ore"
-  result: "gtceu:andesite_powellite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/andesite_pyrite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:andesite_pyrite_ore"
-  result: "gtceu:andesite_pyrite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/andesite_pyrochlore_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:andesite_pyrochlore_ore"
-  result: "gtceu:andesite_pyrochlore_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/andesite_pyrolusite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:andesite_pyrolusite_ore"
-  result: "gtceu:andesite_pyrolusite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/andesite_pyrope_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:andesite_pyrope_ore"
-  result: "gtceu:andesite_pyrope_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/andesite_quartzite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:andesite_quartzite_ore"
-  result: "gtceu:andesite_quartzite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/andesite_realgar_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:andesite_realgar_ore"
-  result: "gtceu:andesite_realgar_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/andesite_red_garnet_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:andesite_red_garnet_ore"
-  result: "gtceu:andesite_red_garnet_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/andesite_redstone_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:andesite_redstone_ore"
-  result: "gtceu:andesite_redstone_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/andesite_rock_salt_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:andesite_rock_salt_ore"
-  result: "gtceu:andesite_rock_salt_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/andesite_ruby_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:andesite_ruby_ore"
-  result: "gtceu:andesite_ruby_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/andesite_salt_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:andesite_salt_ore"
-  result: "gtceu:andesite_salt_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/andesite_saltpeter_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:andesite_saltpeter_ore"
-  result: "gtceu:andesite_saltpeter_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/andesite_sapphire_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:andesite_sapphire_ore"
-  result: "gtceu:andesite_sapphire_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/andesite_scheelite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:andesite_scheelite_ore"
-  result: "gtceu:andesite_scheelite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/andesite_silver_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:andesite_silver_ore"
-  result: "gtceu:andesite_silver_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/andesite_soapstone_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:andesite_soapstone_ore"
-  result: "gtceu:andesite_soapstone_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/andesite_sodalite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:andesite_sodalite_ore"
-  result: "gtceu:andesite_sodalite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/andesite_spessartine_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:andesite_spessartine_ore"
-  result: "gtceu:andesite_spessartine_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/andesite_sphalerite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:andesite_sphalerite_ore"
-  result: "gtceu:andesite_sphalerite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/andesite_spodumene_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:andesite_spodumene_ore"
-  result: "gtceu:andesite_spodumene_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/andesite_stibnite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:andesite_stibnite_ore"
-  result: "gtceu:andesite_stibnite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/andesite_sulfur_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:andesite_sulfur_ore"
-  result: "gtceu:andesite_sulfur_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/andesite_talc_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:andesite_talc_ore"
-  result: "gtceu:andesite_talc_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/andesite_tantalite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:andesite_tantalite_ore"
-  result: "gtceu:andesite_tantalite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/andesite_tetrahedrite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:andesite_tetrahedrite_ore"
-  result: "gtceu:andesite_tetrahedrite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/andesite_thorium_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:andesite_thorium_ore"
-  result: "gtceu:andesite_thorium_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/andesite_tin_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:andesite_tin_ore"
-  result: "gtceu:andesite_tin_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/andesite_titanium_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:andesite_titanium_ore"
-  result: "gtceu:andesite_titanium_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/andesite_topaz_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:andesite_topaz_ore"
-  result: "gtceu:andesite_topaz_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/andesite_tricalcium_phosphate_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:andesite_tricalcium_phosphate_ore"
-  result: "gtceu:andesite_tricalcium_phosphate_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/andesite_trona_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:andesite_trona_ore"
-  result: "gtceu:andesite_trona_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/andesite_tungstate_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:andesite_tungstate_ore"
-  result: "gtceu:andesite_tungstate_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/andesite_uraninite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:andesite_uraninite_ore"
-  result: "gtceu:andesite_uraninite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/andesite_vanadium_magnetite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:andesite_vanadium_magnetite_ore"
-  result: "gtceu:andesite_vanadium_magnetite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/andesite_wulfenite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:andesite_wulfenite_ore"
-  result: "gtceu:andesite_wulfenite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/andesite_yellow_garnet_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:andesite_yellow_garnet_ore"
-  result: "gtceu:andesite_yellow_garnet_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/andesite_yellow_limonite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:andesite_yellow_limonite_ore"
-  result: "gtceu:andesite_yellow_limonite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/andesite_zeolite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:andesite_zeolite_ore"
-  result: "gtceu:andesite_zeolite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/apatite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:apatite_ore"
-  result: "gtceu:apatite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/asbestos_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:asbestos_ore"
-  result: "gtceu:asbestos_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/barite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:barite_ore"
-  result: "gtceu:barite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/basalt_almandine_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:basalt_almandine_ore"
-  result: "gtceu:basalt_almandine_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/basalt_aluminium_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:basalt_aluminium_ore"
-  result: "gtceu:basalt_aluminium_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/basalt_alunite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:basalt_alunite_ore"
-  result: "gtceu:basalt_alunite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/basalt_amethyst_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:basalt_amethyst_ore"
-  result: "gtceu:basalt_amethyst_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/basalt_apatite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:basalt_apatite_ore"
-  result: "gtceu:basalt_apatite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/basalt_asbestos_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:basalt_asbestos_ore"
-  result: "gtceu:basalt_asbestos_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/basalt_barite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:basalt_barite_ore"
-  result: "gtceu:basalt_barite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/basalt_basaltic_mineral_sand_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:basalt_basaltic_mineral_sand_ore"
-  result: "gtceu:basalt_basaltic_mineral_sand_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/basalt_bastnasite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:basalt_bastnasite_ore"
-  result: "gtceu:basalt_bastnasite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/basalt_bauxite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:basalt_bauxite_ore"
-  result: "gtceu:basalt_bauxite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/basalt_bentonite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:basalt_bentonite_ore"
-  result: "gtceu:basalt_bentonite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/basalt_beryllium_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:basalt_beryllium_ore"
-  result: "gtceu:basalt_beryllium_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/basalt_blue_topaz_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:basalt_blue_topaz_ore"
-  result: "gtceu:basalt_blue_topaz_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/basalt_bornite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:basalt_bornite_ore"
-  result: "gtceu:basalt_bornite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/basalt_calcite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:basalt_calcite_ore"
-  result: "gtceu:basalt_calcite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/basalt_cassiterite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:basalt_cassiterite_ore"
-  result: "gtceu:basalt_cassiterite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/basalt_cassiterite_sand_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:basalt_cassiterite_sand_ore"
-  result: "gtceu:basalt_cassiterite_sand_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/basalt_certus_quartz_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:basalt_certus_quartz_ore"
-  result: "gtceu:basalt_certus_quartz_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/basalt_chalcocite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:basalt_chalcocite_ore"
-  result: "gtceu:basalt_chalcocite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/basalt_chalcopyrite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:basalt_chalcopyrite_ore"
-  result: "gtceu:basalt_chalcopyrite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/basalt_chromite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:basalt_chromite_ore"
-  result: "gtceu:basalt_chromite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/basalt_cinnabar_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:basalt_cinnabar_ore"
-  result: "gtceu:basalt_cinnabar_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/basalt_coal_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:basalt_coal_ore"
-  result: "gtceu:basalt_coal_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/basalt_cobalt_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:basalt_cobalt_ore"
-  result: "gtceu:basalt_cobalt_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/basalt_cobaltite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:basalt_cobaltite_ore"
-  result: "gtceu:basalt_cobaltite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/basalt_cooperite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:basalt_cooperite_ore"
-  result: "gtceu:basalt_cooperite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/basalt_copper_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:basalt_copper_ore"
-  result: "gtceu:basalt_copper_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/basalt_diamond_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:basalt_diamond_ore"
-  result: "gtceu:basalt_diamond_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/basalt_diatomite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:basalt_diatomite_ore"
-  result: "gtceu:basalt_diatomite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/basalt_electrotine_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:basalt_electrotine_ore"
-  result: "gtceu:basalt_electrotine_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/basalt_emerald_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:basalt_emerald_ore"
-  result: "gtceu:basalt_emerald_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/basalt_fullers_earth_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:basalt_fullers_earth_ore"
-  result: "gtceu:basalt_fullers_earth_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/basalt_galena_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:basalt_galena_ore"
-  result: "gtceu:basalt_galena_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/basalt_garnet_sand_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:basalt_garnet_sand_ore"
-  result: "gtceu:basalt_garnet_sand_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/basalt_garnierite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:basalt_garnierite_ore"
-  result: "gtceu:basalt_garnierite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/basalt_glauconite_sand_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:basalt_glauconite_sand_ore"
-  result: "gtceu:basalt_glauconite_sand_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/basalt_goethite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:basalt_goethite_ore"
-  result: "gtceu:basalt_goethite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/basalt_gold_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:basalt_gold_ore"
-  result: "gtceu:basalt_gold_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/basalt_granitic_mineral_sand_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:basalt_granitic_mineral_sand_ore"
-  result: "gtceu:basalt_granitic_mineral_sand_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/basalt_graphite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:basalt_graphite_ore"
-  result: "gtceu:basalt_graphite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/basalt_green_sapphire_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:basalt_green_sapphire_ore"
-  result: "gtceu:basalt_green_sapphire_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/basalt_grossular_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:basalt_grossular_ore"
-  result: "gtceu:basalt_grossular_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/basalt_gypsum_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:basalt_gypsum_ore"
-  result: "gtceu:basalt_gypsum_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/basalt_hematite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:basalt_hematite_ore"
-  result: "gtceu:basalt_hematite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/basalt_ilmenite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:basalt_ilmenite_ore"
-  result: "gtceu:basalt_ilmenite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/basalt_iron_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:basalt_iron_ore"
-  result: "gtceu:basalt_iron_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/basalt_kyanite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:basalt_kyanite_ore"
-  result: "gtceu:basalt_kyanite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/basalt_lapis_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:basalt_lapis_ore"
-  result: "gtceu:basalt_lapis_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/basalt_lazurite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:basalt_lazurite_ore"
-  result: "gtceu:basalt_lazurite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/basalt_lead_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:basalt_lead_ore"
-  result: "gtceu:basalt_lead_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/basalt_lepidolite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:basalt_lepidolite_ore"
-  result: "gtceu:basalt_lepidolite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/basalt_lithium_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:basalt_lithium_ore"
-  result: "gtceu:basalt_lithium_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/basalt_magnesite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:basalt_magnesite_ore"
-  result: "gtceu:basalt_magnesite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/basalt_magnetite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:basalt_magnetite_ore"
-  result: "gtceu:basalt_magnetite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/basalt_malachite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:basalt_malachite_ore"
-  result: "gtceu:basalt_malachite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/basalt_mica_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:basalt_mica_ore"
-  result: "gtceu:basalt_mica_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/basalt_molybdenite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:basalt_molybdenite_ore"
-  result: "gtceu:basalt_molybdenite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/basalt_molybdenum_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:basalt_molybdenum_ore"
-  result: "gtceu:basalt_molybdenum_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/basalt_monazite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:basalt_monazite_ore"
-  result: "gtceu:basalt_monazite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/basalt_naquadah_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:basalt_naquadah_ore"
-  result: "gtceu:basalt_naquadah_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/basalt_neodymium_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:basalt_neodymium_ore"
-  result: "gtceu:basalt_neodymium_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/basalt_nether_quartz_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:basalt_nether_quartz_ore"
-  result: "gtceu:basalt_nether_quartz_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/basalt_nickel_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:basalt_nickel_ore"
-  result: "gtceu:basalt_nickel_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/basalt_oilsands_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:basalt_oilsands_ore"
-  result: "gtceu:basalt_oilsands_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/basalt_olivine_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:basalt_olivine_ore"
-  result: "gtceu:basalt_olivine_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/basalt_opal_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:basalt_opal_ore"
-  result: "gtceu:basalt_opal_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/basalt_palladium_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:basalt_palladium_ore"
-  result: "gtceu:basalt_palladium_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/basalt_pentlandite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:basalt_pentlandite_ore"
-  result: "gtceu:basalt_pentlandite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/basalt_pitchblende_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:basalt_pitchblende_ore"
-  result: "gtceu:basalt_pitchblende_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/basalt_platinum_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:basalt_platinum_ore"
-  result: "gtceu:basalt_platinum_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/basalt_plutonium_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:basalt_plutonium_ore"
-  result: "gtceu:basalt_plutonium_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/basalt_pollucite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:basalt_pollucite_ore"
-  result: "gtceu:basalt_pollucite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/basalt_powellite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:basalt_powellite_ore"
-  result: "gtceu:basalt_powellite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/basalt_pyrite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:basalt_pyrite_ore"
-  result: "gtceu:basalt_pyrite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/basalt_pyrochlore_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:basalt_pyrochlore_ore"
-  result: "gtceu:basalt_pyrochlore_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/basalt_pyrolusite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:basalt_pyrolusite_ore"
-  result: "gtceu:basalt_pyrolusite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/basalt_pyrope_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:basalt_pyrope_ore"
-  result: "gtceu:basalt_pyrope_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/basalt_quartzite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:basalt_quartzite_ore"
-  result: "gtceu:basalt_quartzite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/basalt_realgar_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:basalt_realgar_ore"
-  result: "gtceu:basalt_realgar_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/basalt_red_garnet_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:basalt_red_garnet_ore"
-  result: "gtceu:basalt_red_garnet_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/basalt_redstone_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:basalt_redstone_ore"
-  result: "gtceu:basalt_redstone_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/basalt_rock_salt_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:basalt_rock_salt_ore"
-  result: "gtceu:basalt_rock_salt_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/basalt_ruby_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:basalt_ruby_ore"
-  result: "gtceu:basalt_ruby_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/basalt_salt_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:basalt_salt_ore"
-  result: "gtceu:basalt_salt_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/basalt_saltpeter_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:basalt_saltpeter_ore"
-  result: "gtceu:basalt_saltpeter_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/basalt_sapphire_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:basalt_sapphire_ore"
-  result: "gtceu:basalt_sapphire_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/basalt_scheelite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:basalt_scheelite_ore"
-  result: "gtceu:basalt_scheelite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/basalt_silver_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:basalt_silver_ore"
-  result: "gtceu:basalt_silver_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/basalt_soapstone_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:basalt_soapstone_ore"
-  result: "gtceu:basalt_soapstone_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/basalt_sodalite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:basalt_sodalite_ore"
-  result: "gtceu:basalt_sodalite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/basalt_spessartine_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:basalt_spessartine_ore"
-  result: "gtceu:basalt_spessartine_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/basalt_sphalerite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:basalt_sphalerite_ore"
-  result: "gtceu:basalt_sphalerite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/basalt_spodumene_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:basalt_spodumene_ore"
-  result: "gtceu:basalt_spodumene_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/basalt_stibnite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:basalt_stibnite_ore"
-  result: "gtceu:basalt_stibnite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/basalt_sulfur_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:basalt_sulfur_ore"
-  result: "gtceu:basalt_sulfur_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/basalt_talc_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:basalt_talc_ore"
-  result: "gtceu:basalt_talc_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/basalt_tantalite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:basalt_tantalite_ore"
-  result: "gtceu:basalt_tantalite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/basalt_tetrahedrite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:basalt_tetrahedrite_ore"
-  result: "gtceu:basalt_tetrahedrite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/basalt_thorium_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:basalt_thorium_ore"
-  result: "gtceu:basalt_thorium_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/basalt_tin_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:basalt_tin_ore"
-  result: "gtceu:basalt_tin_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/basalt_titanium_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:basalt_titanium_ore"
-  result: "gtceu:basalt_titanium_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/basalt_topaz_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:basalt_topaz_ore"
-  result: "gtceu:basalt_topaz_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/basalt_tricalcium_phosphate_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:basalt_tricalcium_phosphate_ore"
-  result: "gtceu:basalt_tricalcium_phosphate_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/basalt_trona_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:basalt_trona_ore"
-  result: "gtceu:basalt_trona_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/basalt_tungstate_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:basalt_tungstate_ore"
-  result: "gtceu:basalt_tungstate_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/basalt_uraninite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:basalt_uraninite_ore"
-  result: "gtceu:basalt_uraninite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/basalt_vanadium_magnetite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:basalt_vanadium_magnetite_ore"
-  result: "gtceu:basalt_vanadium_magnetite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/basalt_wulfenite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:basalt_wulfenite_ore"
-  result: "gtceu:basalt_wulfenite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/basalt_yellow_garnet_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:basalt_yellow_garnet_ore"
-  result: "gtceu:basalt_yellow_garnet_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/basalt_yellow_limonite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:basalt_yellow_limonite_ore"
-  result: "gtceu:basalt_yellow_limonite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/basalt_zeolite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:basalt_zeolite_ore"
-  result: "gtceu:basalt_zeolite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/basaltic_mineral_sand_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:basaltic_mineral_sand_ore"
-  result: "gtceu:basaltic_mineral_sand_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/bastnasite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:bastnasite_ore"
-  result: "gtceu:bastnasite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/bauxite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:bauxite_ore"
-  result: "gtceu:bauxite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/bentonite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:bentonite_ore"
-  result: "gtceu:bentonite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/beryllium_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:beryllium_ore"
-  result: "gtceu:beryllium_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/blue_topaz_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:blue_topaz_ore"
-  result: "gtceu:blue_topaz_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/bornite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:bornite_ore"
-  result: "gtceu:bornite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/calcite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:calcite_ore"
-  result: "gtceu:calcite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/cassiterite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:cassiterite_ore"
-  result: "gtceu:cassiterite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/cassiterite_sand_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:cassiterite_sand_ore"
-  result: "gtceu:cassiterite_sand_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/certus_quartz_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:certus_quartz_ore"
-  result: "gtceu:certus_quartz_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/chalcocite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:chalcocite_ore"
-  result: "gtceu:chalcocite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/chalcopyrite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:chalcopyrite_ore"
-  result: "gtceu:chalcopyrite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/chalk_almandine_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:chalk_almandine_ore"
-  result: "gtceu:chalk_almandine_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/chalk_aluminium_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:chalk_aluminium_ore"
-  result: "gtceu:chalk_aluminium_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/chalk_alunite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:chalk_alunite_ore"
-  result: "gtceu:chalk_alunite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/chalk_amethyst_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:chalk_amethyst_ore"
-  result: "gtceu:chalk_amethyst_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/chalk_apatite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:chalk_apatite_ore"
-  result: "gtceu:chalk_apatite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/chalk_asbestos_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:chalk_asbestos_ore"
-  result: "gtceu:chalk_asbestos_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/chalk_barite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:chalk_barite_ore"
-  result: "gtceu:chalk_barite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/chalk_basaltic_mineral_sand_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:chalk_basaltic_mineral_sand_ore"
-  result: "gtceu:chalk_basaltic_mineral_sand_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/chalk_bastnasite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:chalk_bastnasite_ore"
-  result: "gtceu:chalk_bastnasite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/chalk_bauxite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:chalk_bauxite_ore"
-  result: "gtceu:chalk_bauxite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/chalk_bentonite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:chalk_bentonite_ore"
-  result: "gtceu:chalk_bentonite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/chalk_beryllium_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:chalk_beryllium_ore"
-  result: "gtceu:chalk_beryllium_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/chalk_blue_topaz_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:chalk_blue_topaz_ore"
-  result: "gtceu:chalk_blue_topaz_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/chalk_bornite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:chalk_bornite_ore"
-  result: "gtceu:chalk_bornite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/chalk_calcite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:chalk_calcite_ore"
-  result: "gtceu:chalk_calcite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/chalk_cassiterite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:chalk_cassiterite_ore"
-  result: "gtceu:chalk_cassiterite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/chalk_cassiterite_sand_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:chalk_cassiterite_sand_ore"
-  result: "gtceu:chalk_cassiterite_sand_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/chalk_certus_quartz_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:chalk_certus_quartz_ore"
-  result: "gtceu:chalk_certus_quartz_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/chalk_chalcocite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:chalk_chalcocite_ore"
-  result: "gtceu:chalk_chalcocite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/chalk_chalcopyrite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:chalk_chalcopyrite_ore"
-  result: "gtceu:chalk_chalcopyrite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/chalk_chromite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:chalk_chromite_ore"
-  result: "gtceu:chalk_chromite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/chalk_cinnabar_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:chalk_cinnabar_ore"
-  result: "gtceu:chalk_cinnabar_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/chalk_coal_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:chalk_coal_ore"
-  result: "gtceu:chalk_coal_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/chalk_cobalt_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:chalk_cobalt_ore"
-  result: "gtceu:chalk_cobalt_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/chalk_cobaltite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:chalk_cobaltite_ore"
-  result: "gtceu:chalk_cobaltite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/chalk_cooperite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:chalk_cooperite_ore"
-  result: "gtceu:chalk_cooperite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/chalk_copper_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:chalk_copper_ore"
-  result: "gtceu:chalk_copper_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/chalk_diamond_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:chalk_diamond_ore"
-  result: "gtceu:chalk_diamond_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/chalk_diatomite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:chalk_diatomite_ore"
-  result: "gtceu:chalk_diatomite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/chalk_electrotine_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:chalk_electrotine_ore"
-  result: "gtceu:chalk_electrotine_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/chalk_emerald_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:chalk_emerald_ore"
-  result: "gtceu:chalk_emerald_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/chalk_fullers_earth_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:chalk_fullers_earth_ore"
-  result: "gtceu:chalk_fullers_earth_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/chalk_galena_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:chalk_galena_ore"
-  result: "gtceu:chalk_galena_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/chalk_garnet_sand_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:chalk_garnet_sand_ore"
-  result: "gtceu:chalk_garnet_sand_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/chalk_garnierite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:chalk_garnierite_ore"
-  result: "gtceu:chalk_garnierite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/chalk_glauconite_sand_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:chalk_glauconite_sand_ore"
-  result: "gtceu:chalk_glauconite_sand_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/chalk_goethite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:chalk_goethite_ore"
-  result: "gtceu:chalk_goethite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/chalk_gold_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:chalk_gold_ore"
-  result: "gtceu:chalk_gold_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/chalk_granitic_mineral_sand_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:chalk_granitic_mineral_sand_ore"
-  result: "gtceu:chalk_granitic_mineral_sand_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/chalk_graphite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:chalk_graphite_ore"
-  result: "gtceu:chalk_graphite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/chalk_green_sapphire_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:chalk_green_sapphire_ore"
-  result: "gtceu:chalk_green_sapphire_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/chalk_grossular_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:chalk_grossular_ore"
-  result: "gtceu:chalk_grossular_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/chalk_gypsum_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:chalk_gypsum_ore"
-  result: "gtceu:chalk_gypsum_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/chalk_hematite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:chalk_hematite_ore"
-  result: "gtceu:chalk_hematite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/chalk_ilmenite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:chalk_ilmenite_ore"
-  result: "gtceu:chalk_ilmenite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/chalk_iron_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:chalk_iron_ore"
-  result: "gtceu:chalk_iron_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/chalk_kyanite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:chalk_kyanite_ore"
-  result: "gtceu:chalk_kyanite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/chalk_lapis_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:chalk_lapis_ore"
-  result: "gtceu:chalk_lapis_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/chalk_lazurite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:chalk_lazurite_ore"
-  result: "gtceu:chalk_lazurite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/chalk_lead_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:chalk_lead_ore"
-  result: "gtceu:chalk_lead_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/chalk_lepidolite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:chalk_lepidolite_ore"
-  result: "gtceu:chalk_lepidolite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/chalk_lithium_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:chalk_lithium_ore"
-  result: "gtceu:chalk_lithium_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/chalk_magnesite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:chalk_magnesite_ore"
-  result: "gtceu:chalk_magnesite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/chalk_magnetite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:chalk_magnetite_ore"
-  result: "gtceu:chalk_magnetite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/chalk_malachite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:chalk_malachite_ore"
-  result: "gtceu:chalk_malachite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/chalk_mica_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:chalk_mica_ore"
-  result: "gtceu:chalk_mica_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/chalk_molybdenite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:chalk_molybdenite_ore"
-  result: "gtceu:chalk_molybdenite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/chalk_molybdenum_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:chalk_molybdenum_ore"
-  result: "gtceu:chalk_molybdenum_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/chalk_monazite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:chalk_monazite_ore"
-  result: "gtceu:chalk_monazite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/chalk_naquadah_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:chalk_naquadah_ore"
-  result: "gtceu:chalk_naquadah_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/chalk_neodymium_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:chalk_neodymium_ore"
-  result: "gtceu:chalk_neodymium_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/chalk_nether_quartz_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:chalk_nether_quartz_ore"
-  result: "gtceu:chalk_nether_quartz_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/chalk_nickel_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:chalk_nickel_ore"
-  result: "gtceu:chalk_nickel_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/chalk_oilsands_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:chalk_oilsands_ore"
-  result: "gtceu:chalk_oilsands_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/chalk_olivine_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:chalk_olivine_ore"
-  result: "gtceu:chalk_olivine_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/chalk_opal_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:chalk_opal_ore"
-  result: "gtceu:chalk_opal_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/chalk_palladium_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:chalk_palladium_ore"
-  result: "gtceu:chalk_palladium_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/chalk_pentlandite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:chalk_pentlandite_ore"
-  result: "gtceu:chalk_pentlandite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/chalk_pitchblende_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:chalk_pitchblende_ore"
-  result: "gtceu:chalk_pitchblende_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/chalk_platinum_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:chalk_platinum_ore"
-  result: "gtceu:chalk_platinum_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/chalk_plutonium_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:chalk_plutonium_ore"
-  result: "gtceu:chalk_plutonium_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/chalk_pollucite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:chalk_pollucite_ore"
-  result: "gtceu:chalk_pollucite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/chalk_powellite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:chalk_powellite_ore"
-  result: "gtceu:chalk_powellite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/chalk_pyrite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:chalk_pyrite_ore"
-  result: "gtceu:chalk_pyrite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/chalk_pyrochlore_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:chalk_pyrochlore_ore"
-  result: "gtceu:chalk_pyrochlore_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/chalk_pyrolusite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:chalk_pyrolusite_ore"
-  result: "gtceu:chalk_pyrolusite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/chalk_pyrope_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:chalk_pyrope_ore"
-  result: "gtceu:chalk_pyrope_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/chalk_quartzite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:chalk_quartzite_ore"
-  result: "gtceu:chalk_quartzite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/chalk_realgar_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:chalk_realgar_ore"
-  result: "gtceu:chalk_realgar_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/chalk_red_garnet_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:chalk_red_garnet_ore"
-  result: "gtceu:chalk_red_garnet_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/chalk_redstone_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:chalk_redstone_ore"
-  result: "gtceu:chalk_redstone_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/chalk_rock_salt_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:chalk_rock_salt_ore"
-  result: "gtceu:chalk_rock_salt_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/chalk_ruby_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:chalk_ruby_ore"
-  result: "gtceu:chalk_ruby_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/chalk_salt_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:chalk_salt_ore"
-  result: "gtceu:chalk_salt_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/chalk_saltpeter_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:chalk_saltpeter_ore"
-  result: "gtceu:chalk_saltpeter_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/chalk_sapphire_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:chalk_sapphire_ore"
-  result: "gtceu:chalk_sapphire_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/chalk_scheelite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:chalk_scheelite_ore"
-  result: "gtceu:chalk_scheelite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/chalk_silver_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:chalk_silver_ore"
-  result: "gtceu:chalk_silver_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/chalk_soapstone_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:chalk_soapstone_ore"
-  result: "gtceu:chalk_soapstone_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/chalk_sodalite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:chalk_sodalite_ore"
-  result: "gtceu:chalk_sodalite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/chalk_spessartine_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:chalk_spessartine_ore"
-  result: "gtceu:chalk_spessartine_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/chalk_sphalerite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:chalk_sphalerite_ore"
-  result: "gtceu:chalk_sphalerite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/chalk_spodumene_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:chalk_spodumene_ore"
-  result: "gtceu:chalk_spodumene_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/chalk_stibnite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:chalk_stibnite_ore"
-  result: "gtceu:chalk_stibnite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/chalk_sulfur_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:chalk_sulfur_ore"
-  result: "gtceu:chalk_sulfur_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/chalk_talc_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:chalk_talc_ore"
-  result: "gtceu:chalk_talc_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/chalk_tantalite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:chalk_tantalite_ore"
-  result: "gtceu:chalk_tantalite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/chalk_tetrahedrite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:chalk_tetrahedrite_ore"
-  result: "gtceu:chalk_tetrahedrite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/chalk_thorium_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:chalk_thorium_ore"
-  result: "gtceu:chalk_thorium_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/chalk_tin_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:chalk_tin_ore"
-  result: "gtceu:chalk_tin_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/chalk_titanium_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:chalk_titanium_ore"
-  result: "gtceu:chalk_titanium_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/chalk_topaz_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:chalk_topaz_ore"
-  result: "gtceu:chalk_topaz_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/chalk_tricalcium_phosphate_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:chalk_tricalcium_phosphate_ore"
-  result: "gtceu:chalk_tricalcium_phosphate_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/chalk_trona_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:chalk_trona_ore"
-  result: "gtceu:chalk_trona_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/chalk_tungstate_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:chalk_tungstate_ore"
-  result: "gtceu:chalk_tungstate_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/chalk_uraninite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:chalk_uraninite_ore"
-  result: "gtceu:chalk_uraninite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/chalk_vanadium_magnetite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:chalk_vanadium_magnetite_ore"
-  result: "gtceu:chalk_vanadium_magnetite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/chalk_wulfenite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:chalk_wulfenite_ore"
-  result: "gtceu:chalk_wulfenite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/chalk_yellow_garnet_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:chalk_yellow_garnet_ore"
-  result: "gtceu:chalk_yellow_garnet_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/chalk_yellow_limonite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:chalk_yellow_limonite_ore"
-  result: "gtceu:chalk_yellow_limonite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/chalk_zeolite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:chalk_zeolite_ore"
-  result: "gtceu:chalk_zeolite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/chert_almandine_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:chert_almandine_ore"
-  result: "gtceu:chert_almandine_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/chert_aluminium_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:chert_aluminium_ore"
-  result: "gtceu:chert_aluminium_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/chert_alunite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:chert_alunite_ore"
-  result: "gtceu:chert_alunite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/chert_amethyst_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:chert_amethyst_ore"
-  result: "gtceu:chert_amethyst_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/chert_apatite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:chert_apatite_ore"
-  result: "gtceu:chert_apatite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/chert_asbestos_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:chert_asbestos_ore"
-  result: "gtceu:chert_asbestos_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/chert_barite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:chert_barite_ore"
-  result: "gtceu:chert_barite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/chert_basaltic_mineral_sand_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:chert_basaltic_mineral_sand_ore"
-  result: "gtceu:chert_basaltic_mineral_sand_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/chert_bastnasite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:chert_bastnasite_ore"
-  result: "gtceu:chert_bastnasite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/chert_bauxite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:chert_bauxite_ore"
-  result: "gtceu:chert_bauxite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/chert_bentonite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:chert_bentonite_ore"
-  result: "gtceu:chert_bentonite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/chert_beryllium_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:chert_beryllium_ore"
-  result: "gtceu:chert_beryllium_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/chert_blue_topaz_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:chert_blue_topaz_ore"
-  result: "gtceu:chert_blue_topaz_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/chert_bornite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:chert_bornite_ore"
-  result: "gtceu:chert_bornite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/chert_calcite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:chert_calcite_ore"
-  result: "gtceu:chert_calcite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/chert_cassiterite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:chert_cassiterite_ore"
-  result: "gtceu:chert_cassiterite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/chert_cassiterite_sand_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:chert_cassiterite_sand_ore"
-  result: "gtceu:chert_cassiterite_sand_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/chert_certus_quartz_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:chert_certus_quartz_ore"
-  result: "gtceu:chert_certus_quartz_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/chert_chalcocite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:chert_chalcocite_ore"
-  result: "gtceu:chert_chalcocite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/chert_chalcopyrite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:chert_chalcopyrite_ore"
-  result: "gtceu:chert_chalcopyrite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/chert_chromite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:chert_chromite_ore"
-  result: "gtceu:chert_chromite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/chert_cinnabar_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:chert_cinnabar_ore"
-  result: "gtceu:chert_cinnabar_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/chert_coal_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:chert_coal_ore"
-  result: "gtceu:chert_coal_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/chert_cobalt_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:chert_cobalt_ore"
-  result: "gtceu:chert_cobalt_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/chert_cobaltite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:chert_cobaltite_ore"
-  result: "gtceu:chert_cobaltite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/chert_cooperite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:chert_cooperite_ore"
-  result: "gtceu:chert_cooperite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/chert_copper_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:chert_copper_ore"
-  result: "gtceu:chert_copper_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/chert_diamond_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:chert_diamond_ore"
-  result: "gtceu:chert_diamond_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/chert_diatomite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:chert_diatomite_ore"
-  result: "gtceu:chert_diatomite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/chert_electrotine_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:chert_electrotine_ore"
-  result: "gtceu:chert_electrotine_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/chert_emerald_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:chert_emerald_ore"
-  result: "gtceu:chert_emerald_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/chert_fullers_earth_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:chert_fullers_earth_ore"
-  result: "gtceu:chert_fullers_earth_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/chert_galena_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:chert_galena_ore"
-  result: "gtceu:chert_galena_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/chert_garnet_sand_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:chert_garnet_sand_ore"
-  result: "gtceu:chert_garnet_sand_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/chert_garnierite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:chert_garnierite_ore"
-  result: "gtceu:chert_garnierite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/chert_glauconite_sand_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:chert_glauconite_sand_ore"
-  result: "gtceu:chert_glauconite_sand_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/chert_goethite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:chert_goethite_ore"
-  result: "gtceu:chert_goethite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/chert_gold_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:chert_gold_ore"
-  result: "gtceu:chert_gold_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/chert_granitic_mineral_sand_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:chert_granitic_mineral_sand_ore"
-  result: "gtceu:chert_granitic_mineral_sand_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/chert_graphite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:chert_graphite_ore"
-  result: "gtceu:chert_graphite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/chert_green_sapphire_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:chert_green_sapphire_ore"
-  result: "gtceu:chert_green_sapphire_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/chert_grossular_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:chert_grossular_ore"
-  result: "gtceu:chert_grossular_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/chert_gypsum_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:chert_gypsum_ore"
-  result: "gtceu:chert_gypsum_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/chert_hematite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:chert_hematite_ore"
-  result: "gtceu:chert_hematite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/chert_ilmenite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:chert_ilmenite_ore"
-  result: "gtceu:chert_ilmenite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/chert_iron_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:chert_iron_ore"
-  result: "gtceu:chert_iron_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/chert_kyanite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:chert_kyanite_ore"
-  result: "gtceu:chert_kyanite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/chert_lapis_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:chert_lapis_ore"
-  result: "gtceu:chert_lapis_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/chert_lazurite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:chert_lazurite_ore"
-  result: "gtceu:chert_lazurite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/chert_lead_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:chert_lead_ore"
-  result: "gtceu:chert_lead_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/chert_lepidolite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:chert_lepidolite_ore"
-  result: "gtceu:chert_lepidolite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/chert_lithium_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:chert_lithium_ore"
-  result: "gtceu:chert_lithium_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/chert_magnesite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:chert_magnesite_ore"
-  result: "gtceu:chert_magnesite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/chert_magnetite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:chert_magnetite_ore"
-  result: "gtceu:chert_magnetite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/chert_malachite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:chert_malachite_ore"
-  result: "gtceu:chert_malachite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/chert_mica_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:chert_mica_ore"
-  result: "gtceu:chert_mica_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/chert_molybdenite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:chert_molybdenite_ore"
-  result: "gtceu:chert_molybdenite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/chert_molybdenum_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:chert_molybdenum_ore"
-  result: "gtceu:chert_molybdenum_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/chert_monazite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:chert_monazite_ore"
-  result: "gtceu:chert_monazite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/chert_naquadah_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:chert_naquadah_ore"
-  result: "gtceu:chert_naquadah_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/chert_neodymium_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:chert_neodymium_ore"
-  result: "gtceu:chert_neodymium_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/chert_nether_quartz_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:chert_nether_quartz_ore"
-  result: "gtceu:chert_nether_quartz_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/chert_nickel_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:chert_nickel_ore"
-  result: "gtceu:chert_nickel_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/chert_oilsands_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:chert_oilsands_ore"
-  result: "gtceu:chert_oilsands_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/chert_olivine_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:chert_olivine_ore"
-  result: "gtceu:chert_olivine_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/chert_opal_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:chert_opal_ore"
-  result: "gtceu:chert_opal_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/chert_palladium_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:chert_palladium_ore"
-  result: "gtceu:chert_palladium_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/chert_pentlandite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:chert_pentlandite_ore"
-  result: "gtceu:chert_pentlandite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/chert_pitchblende_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:chert_pitchblende_ore"
-  result: "gtceu:chert_pitchblende_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/chert_platinum_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:chert_platinum_ore"
-  result: "gtceu:chert_platinum_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/chert_plutonium_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:chert_plutonium_ore"
-  result: "gtceu:chert_plutonium_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/chert_pollucite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:chert_pollucite_ore"
-  result: "gtceu:chert_pollucite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/chert_powellite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:chert_powellite_ore"
-  result: "gtceu:chert_powellite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/chert_pyrite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:chert_pyrite_ore"
-  result: "gtceu:chert_pyrite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/chert_pyrochlore_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:chert_pyrochlore_ore"
-  result: "gtceu:chert_pyrochlore_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/chert_pyrolusite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:chert_pyrolusite_ore"
-  result: "gtceu:chert_pyrolusite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/chert_pyrope_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:chert_pyrope_ore"
-  result: "gtceu:chert_pyrope_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/chert_quartzite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:chert_quartzite_ore"
-  result: "gtceu:chert_quartzite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/chert_realgar_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:chert_realgar_ore"
-  result: "gtceu:chert_realgar_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/chert_red_garnet_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:chert_red_garnet_ore"
-  result: "gtceu:chert_red_garnet_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/chert_redstone_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:chert_redstone_ore"
-  result: "gtceu:chert_redstone_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/chert_rock_salt_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:chert_rock_salt_ore"
-  result: "gtceu:chert_rock_salt_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/chert_ruby_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:chert_ruby_ore"
-  result: "gtceu:chert_ruby_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/chert_salt_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:chert_salt_ore"
-  result: "gtceu:chert_salt_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/chert_saltpeter_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:chert_saltpeter_ore"
-  result: "gtceu:chert_saltpeter_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/chert_sapphire_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:chert_sapphire_ore"
-  result: "gtceu:chert_sapphire_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/chert_scheelite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:chert_scheelite_ore"
-  result: "gtceu:chert_scheelite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/chert_silver_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:chert_silver_ore"
-  result: "gtceu:chert_silver_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/chert_soapstone_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:chert_soapstone_ore"
-  result: "gtceu:chert_soapstone_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/chert_sodalite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:chert_sodalite_ore"
-  result: "gtceu:chert_sodalite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/chert_spessartine_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:chert_spessartine_ore"
-  result: "gtceu:chert_spessartine_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/chert_sphalerite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:chert_sphalerite_ore"
-  result: "gtceu:chert_sphalerite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/chert_spodumene_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:chert_spodumene_ore"
-  result: "gtceu:chert_spodumene_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/chert_stibnite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:chert_stibnite_ore"
-  result: "gtceu:chert_stibnite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/chert_sulfur_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:chert_sulfur_ore"
-  result: "gtceu:chert_sulfur_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/chert_talc_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:chert_talc_ore"
-  result: "gtceu:chert_talc_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/chert_tantalite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:chert_tantalite_ore"
-  result: "gtceu:chert_tantalite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/chert_tetrahedrite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:chert_tetrahedrite_ore"
-  result: "gtceu:chert_tetrahedrite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/chert_thorium_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:chert_thorium_ore"
-  result: "gtceu:chert_thorium_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/chert_tin_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:chert_tin_ore"
-  result: "gtceu:chert_tin_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/chert_titanium_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:chert_titanium_ore"
-  result: "gtceu:chert_titanium_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/chert_topaz_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:chert_topaz_ore"
-  result: "gtceu:chert_topaz_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/chert_tricalcium_phosphate_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:chert_tricalcium_phosphate_ore"
-  result: "gtceu:chert_tricalcium_phosphate_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/chert_trona_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:chert_trona_ore"
-  result: "gtceu:chert_trona_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/chert_tungstate_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:chert_tungstate_ore"
-  result: "gtceu:chert_tungstate_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/chert_uraninite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:chert_uraninite_ore"
-  result: "gtceu:chert_uraninite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/chert_vanadium_magnetite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:chert_vanadium_magnetite_ore"
-  result: "gtceu:chert_vanadium_magnetite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/chert_wulfenite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:chert_wulfenite_ore"
-  result: "gtceu:chert_wulfenite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/chert_yellow_garnet_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:chert_yellow_garnet_ore"
-  result: "gtceu:chert_yellow_garnet_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/chert_yellow_limonite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:chert_yellow_limonite_ore"
-  result: "gtceu:chert_yellow_limonite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/chert_zeolite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:chert_zeolite_ore"
-  result: "gtceu:chert_zeolite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/chromite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:chromite_ore"
-  result: "gtceu:chromite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/cinnabar_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:cinnabar_ore"
-  result: "gtceu:cinnabar_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/claystone_almandine_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:claystone_almandine_ore"
-  result: "gtceu:claystone_almandine_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/claystone_aluminium_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:claystone_aluminium_ore"
-  result: "gtceu:claystone_aluminium_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/claystone_alunite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:claystone_alunite_ore"
-  result: "gtceu:claystone_alunite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/claystone_amethyst_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:claystone_amethyst_ore"
-  result: "gtceu:claystone_amethyst_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/claystone_apatite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:claystone_apatite_ore"
-  result: "gtceu:claystone_apatite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/claystone_asbestos_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:claystone_asbestos_ore"
-  result: "gtceu:claystone_asbestos_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/claystone_barite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:claystone_barite_ore"
-  result: "gtceu:claystone_barite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/claystone_basaltic_mineral_sand_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:claystone_basaltic_mineral_sand_ore"
-  result: "gtceu:claystone_basaltic_mineral_sand_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/claystone_bastnasite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:claystone_bastnasite_ore"
-  result: "gtceu:claystone_bastnasite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/claystone_bauxite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:claystone_bauxite_ore"
-  result: "gtceu:claystone_bauxite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/claystone_bentonite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:claystone_bentonite_ore"
-  result: "gtceu:claystone_bentonite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/claystone_beryllium_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:claystone_beryllium_ore"
-  result: "gtceu:claystone_beryllium_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/claystone_blue_topaz_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:claystone_blue_topaz_ore"
-  result: "gtceu:claystone_blue_topaz_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/claystone_bornite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:claystone_bornite_ore"
-  result: "gtceu:claystone_bornite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/claystone_calcite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:claystone_calcite_ore"
-  result: "gtceu:claystone_calcite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/claystone_cassiterite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:claystone_cassiterite_ore"
-  result: "gtceu:claystone_cassiterite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/claystone_cassiterite_sand_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:claystone_cassiterite_sand_ore"
-  result: "gtceu:claystone_cassiterite_sand_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/claystone_certus_quartz_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:claystone_certus_quartz_ore"
-  result: "gtceu:claystone_certus_quartz_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/claystone_chalcocite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:claystone_chalcocite_ore"
-  result: "gtceu:claystone_chalcocite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/claystone_chalcopyrite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:claystone_chalcopyrite_ore"
-  result: "gtceu:claystone_chalcopyrite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/claystone_chromite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:claystone_chromite_ore"
-  result: "gtceu:claystone_chromite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/claystone_cinnabar_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:claystone_cinnabar_ore"
-  result: "gtceu:claystone_cinnabar_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/claystone_coal_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:claystone_coal_ore"
-  result: "gtceu:claystone_coal_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/claystone_cobalt_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:claystone_cobalt_ore"
-  result: "gtceu:claystone_cobalt_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/claystone_cobaltite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:claystone_cobaltite_ore"
-  result: "gtceu:claystone_cobaltite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/claystone_cooperite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:claystone_cooperite_ore"
-  result: "gtceu:claystone_cooperite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/claystone_copper_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:claystone_copper_ore"
-  result: "gtceu:claystone_copper_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/claystone_diamond_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:claystone_diamond_ore"
-  result: "gtceu:claystone_diamond_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/claystone_diatomite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:claystone_diatomite_ore"
-  result: "gtceu:claystone_diatomite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/claystone_electrotine_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:claystone_electrotine_ore"
-  result: "gtceu:claystone_electrotine_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/claystone_emerald_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:claystone_emerald_ore"
-  result: "gtceu:claystone_emerald_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/claystone_fullers_earth_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:claystone_fullers_earth_ore"
-  result: "gtceu:claystone_fullers_earth_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/claystone_galena_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:claystone_galena_ore"
-  result: "gtceu:claystone_galena_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/claystone_garnet_sand_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:claystone_garnet_sand_ore"
-  result: "gtceu:claystone_garnet_sand_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/claystone_garnierite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:claystone_garnierite_ore"
-  result: "gtceu:claystone_garnierite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/claystone_glauconite_sand_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:claystone_glauconite_sand_ore"
-  result: "gtceu:claystone_glauconite_sand_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/claystone_goethite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:claystone_goethite_ore"
-  result: "gtceu:claystone_goethite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/claystone_gold_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:claystone_gold_ore"
-  result: "gtceu:claystone_gold_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/claystone_granitic_mineral_sand_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:claystone_granitic_mineral_sand_ore"
-  result: "gtceu:claystone_granitic_mineral_sand_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/claystone_graphite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:claystone_graphite_ore"
-  result: "gtceu:claystone_graphite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/claystone_green_sapphire_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:claystone_green_sapphire_ore"
-  result: "gtceu:claystone_green_sapphire_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/claystone_grossular_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:claystone_grossular_ore"
-  result: "gtceu:claystone_grossular_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/claystone_gypsum_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:claystone_gypsum_ore"
-  result: "gtceu:claystone_gypsum_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/claystone_hematite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:claystone_hematite_ore"
-  result: "gtceu:claystone_hematite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/claystone_ilmenite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:claystone_ilmenite_ore"
-  result: "gtceu:claystone_ilmenite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/claystone_iron_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:claystone_iron_ore"
-  result: "gtceu:claystone_iron_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/claystone_kyanite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:claystone_kyanite_ore"
-  result: "gtceu:claystone_kyanite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/claystone_lapis_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:claystone_lapis_ore"
-  result: "gtceu:claystone_lapis_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/claystone_lazurite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:claystone_lazurite_ore"
-  result: "gtceu:claystone_lazurite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/claystone_lead_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:claystone_lead_ore"
-  result: "gtceu:claystone_lead_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/claystone_lepidolite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:claystone_lepidolite_ore"
-  result: "gtceu:claystone_lepidolite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/claystone_lithium_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:claystone_lithium_ore"
-  result: "gtceu:claystone_lithium_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/claystone_magnesite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:claystone_magnesite_ore"
-  result: "gtceu:claystone_magnesite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/claystone_magnetite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:claystone_magnetite_ore"
-  result: "gtceu:claystone_magnetite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/claystone_malachite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:claystone_malachite_ore"
-  result: "gtceu:claystone_malachite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/claystone_mica_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:claystone_mica_ore"
-  result: "gtceu:claystone_mica_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/claystone_molybdenite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:claystone_molybdenite_ore"
-  result: "gtceu:claystone_molybdenite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/claystone_molybdenum_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:claystone_molybdenum_ore"
-  result: "gtceu:claystone_molybdenum_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/claystone_monazite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:claystone_monazite_ore"
-  result: "gtceu:claystone_monazite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/claystone_naquadah_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:claystone_naquadah_ore"
-  result: "gtceu:claystone_naquadah_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/claystone_neodymium_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:claystone_neodymium_ore"
-  result: "gtceu:claystone_neodymium_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/claystone_nether_quartz_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:claystone_nether_quartz_ore"
-  result: "gtceu:claystone_nether_quartz_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/claystone_nickel_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:claystone_nickel_ore"
-  result: "gtceu:claystone_nickel_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/claystone_oilsands_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:claystone_oilsands_ore"
-  result: "gtceu:claystone_oilsands_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/claystone_olivine_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:claystone_olivine_ore"
-  result: "gtceu:claystone_olivine_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/claystone_opal_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:claystone_opal_ore"
-  result: "gtceu:claystone_opal_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/claystone_palladium_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:claystone_palladium_ore"
-  result: "gtceu:claystone_palladium_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/claystone_pentlandite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:claystone_pentlandite_ore"
-  result: "gtceu:claystone_pentlandite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/claystone_pitchblende_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:claystone_pitchblende_ore"
-  result: "gtceu:claystone_pitchblende_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/claystone_platinum_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:claystone_platinum_ore"
-  result: "gtceu:claystone_platinum_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/claystone_plutonium_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:claystone_plutonium_ore"
-  result: "gtceu:claystone_plutonium_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/claystone_pollucite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:claystone_pollucite_ore"
-  result: "gtceu:claystone_pollucite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/claystone_powellite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:claystone_powellite_ore"
-  result: "gtceu:claystone_powellite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/claystone_pyrite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:claystone_pyrite_ore"
-  result: "gtceu:claystone_pyrite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/claystone_pyrochlore_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:claystone_pyrochlore_ore"
-  result: "gtceu:claystone_pyrochlore_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/claystone_pyrolusite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:claystone_pyrolusite_ore"
-  result: "gtceu:claystone_pyrolusite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/claystone_pyrope_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:claystone_pyrope_ore"
-  result: "gtceu:claystone_pyrope_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/claystone_quartzite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:claystone_quartzite_ore"
-  result: "gtceu:claystone_quartzite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/claystone_realgar_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:claystone_realgar_ore"
-  result: "gtceu:claystone_realgar_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/claystone_red_garnet_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:claystone_red_garnet_ore"
-  result: "gtceu:claystone_red_garnet_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/claystone_redstone_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:claystone_redstone_ore"
-  result: "gtceu:claystone_redstone_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/claystone_rock_salt_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:claystone_rock_salt_ore"
-  result: "gtceu:claystone_rock_salt_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/claystone_ruby_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:claystone_ruby_ore"
-  result: "gtceu:claystone_ruby_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/claystone_salt_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:claystone_salt_ore"
-  result: "gtceu:claystone_salt_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/claystone_saltpeter_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:claystone_saltpeter_ore"
-  result: "gtceu:claystone_saltpeter_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/claystone_sapphire_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:claystone_sapphire_ore"
-  result: "gtceu:claystone_sapphire_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/claystone_scheelite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:claystone_scheelite_ore"
-  result: "gtceu:claystone_scheelite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/claystone_silver_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:claystone_silver_ore"
-  result: "gtceu:claystone_silver_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/claystone_soapstone_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:claystone_soapstone_ore"
-  result: "gtceu:claystone_soapstone_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/claystone_sodalite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:claystone_sodalite_ore"
-  result: "gtceu:claystone_sodalite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/claystone_spessartine_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:claystone_spessartine_ore"
-  result: "gtceu:claystone_spessartine_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/claystone_sphalerite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:claystone_sphalerite_ore"
-  result: "gtceu:claystone_sphalerite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/claystone_spodumene_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:claystone_spodumene_ore"
-  result: "gtceu:claystone_spodumene_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/claystone_stibnite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:claystone_stibnite_ore"
-  result: "gtceu:claystone_stibnite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/claystone_sulfur_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:claystone_sulfur_ore"
-  result: "gtceu:claystone_sulfur_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/claystone_talc_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:claystone_talc_ore"
-  result: "gtceu:claystone_talc_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/claystone_tantalite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:claystone_tantalite_ore"
-  result: "gtceu:claystone_tantalite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/claystone_tetrahedrite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:claystone_tetrahedrite_ore"
-  result: "gtceu:claystone_tetrahedrite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/claystone_thorium_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:claystone_thorium_ore"
-  result: "gtceu:claystone_thorium_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/claystone_tin_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:claystone_tin_ore"
-  result: "gtceu:claystone_tin_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/claystone_titanium_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:claystone_titanium_ore"
-  result: "gtceu:claystone_titanium_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/claystone_topaz_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:claystone_topaz_ore"
-  result: "gtceu:claystone_topaz_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/claystone_tricalcium_phosphate_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:claystone_tricalcium_phosphate_ore"
-  result: "gtceu:claystone_tricalcium_phosphate_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/claystone_trona_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:claystone_trona_ore"
-  result: "gtceu:claystone_trona_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/claystone_tungstate_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:claystone_tungstate_ore"
-  result: "gtceu:claystone_tungstate_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/claystone_uraninite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:claystone_uraninite_ore"
-  result: "gtceu:claystone_uraninite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/claystone_vanadium_magnetite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:claystone_vanadium_magnetite_ore"
-  result: "gtceu:claystone_vanadium_magnetite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/claystone_wulfenite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:claystone_wulfenite_ore"
-  result: "gtceu:claystone_wulfenite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/claystone_yellow_garnet_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:claystone_yellow_garnet_ore"
-  result: "gtceu:claystone_yellow_garnet_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/claystone_yellow_limonite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:claystone_yellow_limonite_ore"
-  result: "gtceu:claystone_yellow_limonite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/claystone_zeolite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:claystone_zeolite_ore"
-  result: "gtceu:claystone_zeolite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/coal_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:coal_ore"
-  result: "gtceu:coal_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/cobalt_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:cobalt_ore"
-  result: "gtceu:cobalt_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/cobaltite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:cobaltite_ore"
-  result: "gtceu:cobaltite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/conglomerate_almandine_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:conglomerate_almandine_ore"
-  result: "gtceu:conglomerate_almandine_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/conglomerate_aluminium_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:conglomerate_aluminium_ore"
-  result: "gtceu:conglomerate_aluminium_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/conglomerate_alunite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:conglomerate_alunite_ore"
-  result: "gtceu:conglomerate_alunite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/conglomerate_amethyst_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:conglomerate_amethyst_ore"
-  result: "gtceu:conglomerate_amethyst_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/conglomerate_apatite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:conglomerate_apatite_ore"
-  result: "gtceu:conglomerate_apatite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/conglomerate_asbestos_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:conglomerate_asbestos_ore"
-  result: "gtceu:conglomerate_asbestos_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/conglomerate_barite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:conglomerate_barite_ore"
-  result: "gtceu:conglomerate_barite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/conglomerate_basaltic_mineral_sand_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:conglomerate_basaltic_mineral_sand_ore"
-  result: "gtceu:conglomerate_basaltic_mineral_sand_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/conglomerate_bastnasite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:conglomerate_bastnasite_ore"
-  result: "gtceu:conglomerate_bastnasite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/conglomerate_bauxite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:conglomerate_bauxite_ore"
-  result: "gtceu:conglomerate_bauxite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/conglomerate_bentonite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:conglomerate_bentonite_ore"
-  result: "gtceu:conglomerate_bentonite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/conglomerate_beryllium_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:conglomerate_beryllium_ore"
-  result: "gtceu:conglomerate_beryllium_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/conglomerate_blue_topaz_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:conglomerate_blue_topaz_ore"
-  result: "gtceu:conglomerate_blue_topaz_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/conglomerate_bornite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:conglomerate_bornite_ore"
-  result: "gtceu:conglomerate_bornite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/conglomerate_calcite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:conglomerate_calcite_ore"
-  result: "gtceu:conglomerate_calcite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/conglomerate_cassiterite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:conglomerate_cassiterite_ore"
-  result: "gtceu:conglomerate_cassiterite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/conglomerate_cassiterite_sand_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:conglomerate_cassiterite_sand_ore"
-  result: "gtceu:conglomerate_cassiterite_sand_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/conglomerate_certus_quartz_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:conglomerate_certus_quartz_ore"
-  result: "gtceu:conglomerate_certus_quartz_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/conglomerate_chalcocite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:conglomerate_chalcocite_ore"
-  result: "gtceu:conglomerate_chalcocite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/conglomerate_chalcopyrite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:conglomerate_chalcopyrite_ore"
-  result: "gtceu:conglomerate_chalcopyrite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/conglomerate_chromite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:conglomerate_chromite_ore"
-  result: "gtceu:conglomerate_chromite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/conglomerate_cinnabar_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:conglomerate_cinnabar_ore"
-  result: "gtceu:conglomerate_cinnabar_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/conglomerate_coal_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:conglomerate_coal_ore"
-  result: "gtceu:conglomerate_coal_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/conglomerate_cobalt_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:conglomerate_cobalt_ore"
-  result: "gtceu:conglomerate_cobalt_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/conglomerate_cobaltite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:conglomerate_cobaltite_ore"
-  result: "gtceu:conglomerate_cobaltite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/conglomerate_cooperite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:conglomerate_cooperite_ore"
-  result: "gtceu:conglomerate_cooperite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/conglomerate_copper_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:conglomerate_copper_ore"
-  result: "gtceu:conglomerate_copper_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/conglomerate_diamond_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:conglomerate_diamond_ore"
-  result: "gtceu:conglomerate_diamond_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/conglomerate_diatomite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:conglomerate_diatomite_ore"
-  result: "gtceu:conglomerate_diatomite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/conglomerate_electrotine_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:conglomerate_electrotine_ore"
-  result: "gtceu:conglomerate_electrotine_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/conglomerate_emerald_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:conglomerate_emerald_ore"
-  result: "gtceu:conglomerate_emerald_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/conglomerate_fullers_earth_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:conglomerate_fullers_earth_ore"
-  result: "gtceu:conglomerate_fullers_earth_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/conglomerate_galena_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:conglomerate_galena_ore"
-  result: "gtceu:conglomerate_galena_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/conglomerate_garnet_sand_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:conglomerate_garnet_sand_ore"
-  result: "gtceu:conglomerate_garnet_sand_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/conglomerate_garnierite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:conglomerate_garnierite_ore"
-  result: "gtceu:conglomerate_garnierite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/conglomerate_glauconite_sand_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:conglomerate_glauconite_sand_ore"
-  result: "gtceu:conglomerate_glauconite_sand_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/conglomerate_goethite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:conglomerate_goethite_ore"
-  result: "gtceu:conglomerate_goethite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/conglomerate_gold_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:conglomerate_gold_ore"
-  result: "gtceu:conglomerate_gold_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/conglomerate_granitic_mineral_sand_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:conglomerate_granitic_mineral_sand_ore"
-  result: "gtceu:conglomerate_granitic_mineral_sand_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/conglomerate_graphite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:conglomerate_graphite_ore"
-  result: "gtceu:conglomerate_graphite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/conglomerate_green_sapphire_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:conglomerate_green_sapphire_ore"
-  result: "gtceu:conglomerate_green_sapphire_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/conglomerate_grossular_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:conglomerate_grossular_ore"
-  result: "gtceu:conglomerate_grossular_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/conglomerate_gypsum_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:conglomerate_gypsum_ore"
-  result: "gtceu:conglomerate_gypsum_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/conglomerate_hematite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:conglomerate_hematite_ore"
-  result: "gtceu:conglomerate_hematite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/conglomerate_ilmenite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:conglomerate_ilmenite_ore"
-  result: "gtceu:conglomerate_ilmenite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/conglomerate_iron_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:conglomerate_iron_ore"
-  result: "gtceu:conglomerate_iron_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/conglomerate_kyanite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:conglomerate_kyanite_ore"
-  result: "gtceu:conglomerate_kyanite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/conglomerate_lapis_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:conglomerate_lapis_ore"
-  result: "gtceu:conglomerate_lapis_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/conglomerate_lazurite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:conglomerate_lazurite_ore"
-  result: "gtceu:conglomerate_lazurite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/conglomerate_lead_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:conglomerate_lead_ore"
-  result: "gtceu:conglomerate_lead_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/conglomerate_lepidolite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:conglomerate_lepidolite_ore"
-  result: "gtceu:conglomerate_lepidolite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/conglomerate_lithium_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:conglomerate_lithium_ore"
-  result: "gtceu:conglomerate_lithium_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/conglomerate_magnesite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:conglomerate_magnesite_ore"
-  result: "gtceu:conglomerate_magnesite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/conglomerate_magnetite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:conglomerate_magnetite_ore"
-  result: "gtceu:conglomerate_magnetite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/conglomerate_malachite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:conglomerate_malachite_ore"
-  result: "gtceu:conglomerate_malachite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/conglomerate_mica_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:conglomerate_mica_ore"
-  result: "gtceu:conglomerate_mica_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/conglomerate_molybdenite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:conglomerate_molybdenite_ore"
-  result: "gtceu:conglomerate_molybdenite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/conglomerate_molybdenum_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:conglomerate_molybdenum_ore"
-  result: "gtceu:conglomerate_molybdenum_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/conglomerate_monazite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:conglomerate_monazite_ore"
-  result: "gtceu:conglomerate_monazite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/conglomerate_naquadah_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:conglomerate_naquadah_ore"
-  result: "gtceu:conglomerate_naquadah_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/conglomerate_neodymium_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:conglomerate_neodymium_ore"
-  result: "gtceu:conglomerate_neodymium_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/conglomerate_nether_quartz_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:conglomerate_nether_quartz_ore"
-  result: "gtceu:conglomerate_nether_quartz_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/conglomerate_nickel_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:conglomerate_nickel_ore"
-  result: "gtceu:conglomerate_nickel_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/conglomerate_oilsands_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:conglomerate_oilsands_ore"
-  result: "gtceu:conglomerate_oilsands_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/conglomerate_olivine_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:conglomerate_olivine_ore"
-  result: "gtceu:conglomerate_olivine_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/conglomerate_opal_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:conglomerate_opal_ore"
-  result: "gtceu:conglomerate_opal_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/conglomerate_palladium_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:conglomerate_palladium_ore"
-  result: "gtceu:conglomerate_palladium_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/conglomerate_pentlandite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:conglomerate_pentlandite_ore"
-  result: "gtceu:conglomerate_pentlandite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/conglomerate_pitchblende_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:conglomerate_pitchblende_ore"
-  result: "gtceu:conglomerate_pitchblende_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/conglomerate_platinum_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:conglomerate_platinum_ore"
-  result: "gtceu:conglomerate_platinum_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/conglomerate_plutonium_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:conglomerate_plutonium_ore"
-  result: "gtceu:conglomerate_plutonium_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/conglomerate_pollucite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:conglomerate_pollucite_ore"
-  result: "gtceu:conglomerate_pollucite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/conglomerate_powellite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:conglomerate_powellite_ore"
-  result: "gtceu:conglomerate_powellite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/conglomerate_pyrite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:conglomerate_pyrite_ore"
-  result: "gtceu:conglomerate_pyrite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/conglomerate_pyrochlore_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:conglomerate_pyrochlore_ore"
-  result: "gtceu:conglomerate_pyrochlore_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/conglomerate_pyrolusite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:conglomerate_pyrolusite_ore"
-  result: "gtceu:conglomerate_pyrolusite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/conglomerate_pyrope_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:conglomerate_pyrope_ore"
-  result: "gtceu:conglomerate_pyrope_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/conglomerate_quartzite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:conglomerate_quartzite_ore"
-  result: "gtceu:conglomerate_quartzite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/conglomerate_realgar_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:conglomerate_realgar_ore"
-  result: "gtceu:conglomerate_realgar_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/conglomerate_red_garnet_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:conglomerate_red_garnet_ore"
-  result: "gtceu:conglomerate_red_garnet_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/conglomerate_redstone_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:conglomerate_redstone_ore"
-  result: "gtceu:conglomerate_redstone_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/conglomerate_rock_salt_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:conglomerate_rock_salt_ore"
-  result: "gtceu:conglomerate_rock_salt_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/conglomerate_ruby_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:conglomerate_ruby_ore"
-  result: "gtceu:conglomerate_ruby_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/conglomerate_salt_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:conglomerate_salt_ore"
-  result: "gtceu:conglomerate_salt_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/conglomerate_saltpeter_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:conglomerate_saltpeter_ore"
-  result: "gtceu:conglomerate_saltpeter_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/conglomerate_sapphire_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:conglomerate_sapphire_ore"
-  result: "gtceu:conglomerate_sapphire_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/conglomerate_scheelite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:conglomerate_scheelite_ore"
-  result: "gtceu:conglomerate_scheelite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/conglomerate_silver_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:conglomerate_silver_ore"
-  result: "gtceu:conglomerate_silver_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/conglomerate_soapstone_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:conglomerate_soapstone_ore"
-  result: "gtceu:conglomerate_soapstone_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/conglomerate_sodalite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:conglomerate_sodalite_ore"
-  result: "gtceu:conglomerate_sodalite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/conglomerate_spessartine_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:conglomerate_spessartine_ore"
-  result: "gtceu:conglomerate_spessartine_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/conglomerate_sphalerite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:conglomerate_sphalerite_ore"
-  result: "gtceu:conglomerate_sphalerite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/conglomerate_spodumene_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:conglomerate_spodumene_ore"
-  result: "gtceu:conglomerate_spodumene_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/conglomerate_stibnite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:conglomerate_stibnite_ore"
-  result: "gtceu:conglomerate_stibnite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/conglomerate_sulfur_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:conglomerate_sulfur_ore"
-  result: "gtceu:conglomerate_sulfur_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/conglomerate_talc_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:conglomerate_talc_ore"
-  result: "gtceu:conglomerate_talc_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/conglomerate_tantalite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:conglomerate_tantalite_ore"
-  result: "gtceu:conglomerate_tantalite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/conglomerate_tetrahedrite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:conglomerate_tetrahedrite_ore"
-  result: "gtceu:conglomerate_tetrahedrite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/conglomerate_thorium_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:conglomerate_thorium_ore"
-  result: "gtceu:conglomerate_thorium_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/conglomerate_tin_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:conglomerate_tin_ore"
-  result: "gtceu:conglomerate_tin_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/conglomerate_titanium_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:conglomerate_titanium_ore"
-  result: "gtceu:conglomerate_titanium_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/conglomerate_topaz_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:conglomerate_topaz_ore"
-  result: "gtceu:conglomerate_topaz_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/conglomerate_tricalcium_phosphate_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:conglomerate_tricalcium_phosphate_ore"
-  result: "gtceu:conglomerate_tricalcium_phosphate_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/conglomerate_trona_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:conglomerate_trona_ore"
-  result: "gtceu:conglomerate_trona_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/conglomerate_tungstate_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:conglomerate_tungstate_ore"
-  result: "gtceu:conglomerate_tungstate_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/conglomerate_uraninite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:conglomerate_uraninite_ore"
-  result: "gtceu:conglomerate_uraninite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/conglomerate_vanadium_magnetite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:conglomerate_vanadium_magnetite_ore"
-  result: "gtceu:conglomerate_vanadium_magnetite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/conglomerate_wulfenite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:conglomerate_wulfenite_ore"
-  result: "gtceu:conglomerate_wulfenite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/conglomerate_yellow_garnet_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:conglomerate_yellow_garnet_ore"
-  result: "gtceu:conglomerate_yellow_garnet_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/conglomerate_yellow_limonite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:conglomerate_yellow_limonite_ore"
-  result: "gtceu:conglomerate_yellow_limonite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/conglomerate_zeolite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:conglomerate_zeolite_ore"
-  result: "gtceu:conglomerate_zeolite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/cooperite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:cooperite_ore"
-  result: "gtceu:cooperite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/copper_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:copper_ore"
-  result: "gtceu:copper_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/dacite_almandine_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:dacite_almandine_ore"
-  result: "gtceu:dacite_almandine_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/dacite_aluminium_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:dacite_aluminium_ore"
-  result: "gtceu:dacite_aluminium_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/dacite_alunite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:dacite_alunite_ore"
-  result: "gtceu:dacite_alunite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/dacite_amethyst_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:dacite_amethyst_ore"
-  result: "gtceu:dacite_amethyst_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/dacite_apatite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:dacite_apatite_ore"
-  result: "gtceu:dacite_apatite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/dacite_asbestos_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:dacite_asbestos_ore"
-  result: "gtceu:dacite_asbestos_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/dacite_barite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:dacite_barite_ore"
-  result: "gtceu:dacite_barite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/dacite_basaltic_mineral_sand_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:dacite_basaltic_mineral_sand_ore"
-  result: "gtceu:dacite_basaltic_mineral_sand_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/dacite_bastnasite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:dacite_bastnasite_ore"
-  result: "gtceu:dacite_bastnasite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/dacite_bauxite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:dacite_bauxite_ore"
-  result: "gtceu:dacite_bauxite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/dacite_bentonite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:dacite_bentonite_ore"
-  result: "gtceu:dacite_bentonite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/dacite_beryllium_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:dacite_beryllium_ore"
-  result: "gtceu:dacite_beryllium_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/dacite_blue_topaz_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:dacite_blue_topaz_ore"
-  result: "gtceu:dacite_blue_topaz_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/dacite_bornite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:dacite_bornite_ore"
-  result: "gtceu:dacite_bornite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/dacite_calcite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:dacite_calcite_ore"
-  result: "gtceu:dacite_calcite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/dacite_cassiterite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:dacite_cassiterite_ore"
-  result: "gtceu:dacite_cassiterite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/dacite_cassiterite_sand_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:dacite_cassiterite_sand_ore"
-  result: "gtceu:dacite_cassiterite_sand_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/dacite_certus_quartz_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:dacite_certus_quartz_ore"
-  result: "gtceu:dacite_certus_quartz_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/dacite_chalcocite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:dacite_chalcocite_ore"
-  result: "gtceu:dacite_chalcocite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/dacite_chalcopyrite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:dacite_chalcopyrite_ore"
-  result: "gtceu:dacite_chalcopyrite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/dacite_chromite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:dacite_chromite_ore"
-  result: "gtceu:dacite_chromite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/dacite_cinnabar_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:dacite_cinnabar_ore"
-  result: "gtceu:dacite_cinnabar_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/dacite_coal_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:dacite_coal_ore"
-  result: "gtceu:dacite_coal_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/dacite_cobalt_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:dacite_cobalt_ore"
-  result: "gtceu:dacite_cobalt_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/dacite_cobaltite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:dacite_cobaltite_ore"
-  result: "gtceu:dacite_cobaltite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/dacite_cooperite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:dacite_cooperite_ore"
-  result: "gtceu:dacite_cooperite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/dacite_copper_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:dacite_copper_ore"
-  result: "gtceu:dacite_copper_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/dacite_diamond_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:dacite_diamond_ore"
-  result: "gtceu:dacite_diamond_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/dacite_diatomite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:dacite_diatomite_ore"
-  result: "gtceu:dacite_diatomite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/dacite_electrotine_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:dacite_electrotine_ore"
-  result: "gtceu:dacite_electrotine_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/dacite_emerald_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:dacite_emerald_ore"
-  result: "gtceu:dacite_emerald_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/dacite_fullers_earth_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:dacite_fullers_earth_ore"
-  result: "gtceu:dacite_fullers_earth_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/dacite_galena_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:dacite_galena_ore"
-  result: "gtceu:dacite_galena_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/dacite_garnet_sand_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:dacite_garnet_sand_ore"
-  result: "gtceu:dacite_garnet_sand_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/dacite_garnierite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:dacite_garnierite_ore"
-  result: "gtceu:dacite_garnierite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/dacite_glauconite_sand_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:dacite_glauconite_sand_ore"
-  result: "gtceu:dacite_glauconite_sand_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/dacite_goethite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:dacite_goethite_ore"
-  result: "gtceu:dacite_goethite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/dacite_gold_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:dacite_gold_ore"
-  result: "gtceu:dacite_gold_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/dacite_granitic_mineral_sand_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:dacite_granitic_mineral_sand_ore"
-  result: "gtceu:dacite_granitic_mineral_sand_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/dacite_graphite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:dacite_graphite_ore"
-  result: "gtceu:dacite_graphite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/dacite_green_sapphire_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:dacite_green_sapphire_ore"
-  result: "gtceu:dacite_green_sapphire_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/dacite_grossular_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:dacite_grossular_ore"
-  result: "gtceu:dacite_grossular_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/dacite_gypsum_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:dacite_gypsum_ore"
-  result: "gtceu:dacite_gypsum_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/dacite_hematite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:dacite_hematite_ore"
-  result: "gtceu:dacite_hematite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/dacite_ilmenite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:dacite_ilmenite_ore"
-  result: "gtceu:dacite_ilmenite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/dacite_iron_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:dacite_iron_ore"
-  result: "gtceu:dacite_iron_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/dacite_kyanite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:dacite_kyanite_ore"
-  result: "gtceu:dacite_kyanite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/dacite_lapis_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:dacite_lapis_ore"
-  result: "gtceu:dacite_lapis_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/dacite_lazurite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:dacite_lazurite_ore"
-  result: "gtceu:dacite_lazurite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/dacite_lead_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:dacite_lead_ore"
-  result: "gtceu:dacite_lead_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/dacite_lepidolite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:dacite_lepidolite_ore"
-  result: "gtceu:dacite_lepidolite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/dacite_lithium_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:dacite_lithium_ore"
-  result: "gtceu:dacite_lithium_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/dacite_magnesite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:dacite_magnesite_ore"
-  result: "gtceu:dacite_magnesite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/dacite_magnetite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:dacite_magnetite_ore"
-  result: "gtceu:dacite_magnetite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/dacite_malachite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:dacite_malachite_ore"
-  result: "gtceu:dacite_malachite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/dacite_mica_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:dacite_mica_ore"
-  result: "gtceu:dacite_mica_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/dacite_molybdenite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:dacite_molybdenite_ore"
-  result: "gtceu:dacite_molybdenite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/dacite_molybdenum_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:dacite_molybdenum_ore"
-  result: "gtceu:dacite_molybdenum_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/dacite_monazite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:dacite_monazite_ore"
-  result: "gtceu:dacite_monazite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/dacite_naquadah_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:dacite_naquadah_ore"
-  result: "gtceu:dacite_naquadah_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/dacite_neodymium_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:dacite_neodymium_ore"
-  result: "gtceu:dacite_neodymium_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/dacite_nether_quartz_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:dacite_nether_quartz_ore"
-  result: "gtceu:dacite_nether_quartz_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/dacite_nickel_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:dacite_nickel_ore"
-  result: "gtceu:dacite_nickel_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/dacite_oilsands_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:dacite_oilsands_ore"
-  result: "gtceu:dacite_oilsands_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/dacite_olivine_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:dacite_olivine_ore"
-  result: "gtceu:dacite_olivine_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/dacite_opal_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:dacite_opal_ore"
-  result: "gtceu:dacite_opal_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/dacite_palladium_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:dacite_palladium_ore"
-  result: "gtceu:dacite_palladium_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/dacite_pentlandite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:dacite_pentlandite_ore"
-  result: "gtceu:dacite_pentlandite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/dacite_pitchblende_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:dacite_pitchblende_ore"
-  result: "gtceu:dacite_pitchblende_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/dacite_platinum_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:dacite_platinum_ore"
-  result: "gtceu:dacite_platinum_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/dacite_plutonium_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:dacite_plutonium_ore"
-  result: "gtceu:dacite_plutonium_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/dacite_pollucite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:dacite_pollucite_ore"
-  result: "gtceu:dacite_pollucite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/dacite_powellite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:dacite_powellite_ore"
-  result: "gtceu:dacite_powellite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/dacite_pyrite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:dacite_pyrite_ore"
-  result: "gtceu:dacite_pyrite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/dacite_pyrochlore_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:dacite_pyrochlore_ore"
-  result: "gtceu:dacite_pyrochlore_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/dacite_pyrolusite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:dacite_pyrolusite_ore"
-  result: "gtceu:dacite_pyrolusite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/dacite_pyrope_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:dacite_pyrope_ore"
-  result: "gtceu:dacite_pyrope_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/dacite_quartzite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:dacite_quartzite_ore"
-  result: "gtceu:dacite_quartzite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/dacite_realgar_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:dacite_realgar_ore"
-  result: "gtceu:dacite_realgar_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/dacite_red_garnet_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:dacite_red_garnet_ore"
-  result: "gtceu:dacite_red_garnet_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/dacite_redstone_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:dacite_redstone_ore"
-  result: "gtceu:dacite_redstone_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/dacite_rock_salt_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:dacite_rock_salt_ore"
-  result: "gtceu:dacite_rock_salt_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/dacite_ruby_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:dacite_ruby_ore"
-  result: "gtceu:dacite_ruby_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/dacite_salt_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:dacite_salt_ore"
-  result: "gtceu:dacite_salt_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/dacite_saltpeter_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:dacite_saltpeter_ore"
-  result: "gtceu:dacite_saltpeter_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/dacite_sapphire_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:dacite_sapphire_ore"
-  result: "gtceu:dacite_sapphire_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/dacite_scheelite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:dacite_scheelite_ore"
-  result: "gtceu:dacite_scheelite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/dacite_silver_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:dacite_silver_ore"
-  result: "gtceu:dacite_silver_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/dacite_soapstone_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:dacite_soapstone_ore"
-  result: "gtceu:dacite_soapstone_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/dacite_sodalite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:dacite_sodalite_ore"
-  result: "gtceu:dacite_sodalite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/dacite_spessartine_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:dacite_spessartine_ore"
-  result: "gtceu:dacite_spessartine_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/dacite_sphalerite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:dacite_sphalerite_ore"
-  result: "gtceu:dacite_sphalerite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/dacite_spodumene_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:dacite_spodumene_ore"
-  result: "gtceu:dacite_spodumene_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/dacite_stibnite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:dacite_stibnite_ore"
-  result: "gtceu:dacite_stibnite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/dacite_sulfur_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:dacite_sulfur_ore"
-  result: "gtceu:dacite_sulfur_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/dacite_talc_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:dacite_talc_ore"
-  result: "gtceu:dacite_talc_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/dacite_tantalite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:dacite_tantalite_ore"
-  result: "gtceu:dacite_tantalite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/dacite_tetrahedrite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:dacite_tetrahedrite_ore"
-  result: "gtceu:dacite_tetrahedrite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/dacite_thorium_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:dacite_thorium_ore"
-  result: "gtceu:dacite_thorium_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/dacite_tin_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:dacite_tin_ore"
-  result: "gtceu:dacite_tin_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/dacite_titanium_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:dacite_titanium_ore"
-  result: "gtceu:dacite_titanium_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/dacite_topaz_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:dacite_topaz_ore"
-  result: "gtceu:dacite_topaz_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/dacite_tricalcium_phosphate_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:dacite_tricalcium_phosphate_ore"
-  result: "gtceu:dacite_tricalcium_phosphate_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/dacite_trona_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:dacite_trona_ore"
-  result: "gtceu:dacite_trona_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/dacite_tungstate_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:dacite_tungstate_ore"
-  result: "gtceu:dacite_tungstate_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/dacite_uraninite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:dacite_uraninite_ore"
-  result: "gtceu:dacite_uraninite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/dacite_vanadium_magnetite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:dacite_vanadium_magnetite_ore"
-  result: "gtceu:dacite_vanadium_magnetite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/dacite_wulfenite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:dacite_wulfenite_ore"
-  result: "gtceu:dacite_wulfenite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/dacite_yellow_garnet_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:dacite_yellow_garnet_ore"
-  result: "gtceu:dacite_yellow_garnet_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/dacite_yellow_limonite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:dacite_yellow_limonite_ore"
-  result: "gtceu:dacite_yellow_limonite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/dacite_zeolite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:dacite_zeolite_ore"
-  result: "gtceu:dacite_zeolite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/deepslate_almandine_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:deepslate_almandine_ore"
-  result: "gtceu:deepslate_almandine_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/deepslate_aluminium_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:deepslate_aluminium_ore"
-  result: "gtceu:deepslate_aluminium_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/deepslate_alunite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:deepslate_alunite_ore"
-  result: "gtceu:deepslate_alunite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/deepslate_amethyst_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:deepslate_amethyst_ore"
-  result: "gtceu:deepslate_amethyst_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/deepslate_apatite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:deepslate_apatite_ore"
-  result: "gtceu:deepslate_apatite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/deepslate_asbestos_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:deepslate_asbestos_ore"
-  result: "gtceu:deepslate_asbestos_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/deepslate_barite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:deepslate_barite_ore"
-  result: "gtceu:deepslate_barite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/deepslate_basaltic_mineral_sand_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:deepslate_basaltic_mineral_sand_ore"
-  result: "gtceu:deepslate_basaltic_mineral_sand_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/deepslate_bastnasite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:deepslate_bastnasite_ore"
-  result: "gtceu:deepslate_bastnasite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/deepslate_bauxite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:deepslate_bauxite_ore"
-  result: "gtceu:deepslate_bauxite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/deepslate_bentonite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:deepslate_bentonite_ore"
-  result: "gtceu:deepslate_bentonite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/deepslate_beryllium_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:deepslate_beryllium_ore"
-  result: "gtceu:deepslate_beryllium_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/deepslate_blue_topaz_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:deepslate_blue_topaz_ore"
-  result: "gtceu:deepslate_blue_topaz_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/deepslate_bornite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:deepslate_bornite_ore"
-  result: "gtceu:deepslate_bornite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/deepslate_calcite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:deepslate_calcite_ore"
-  result: "gtceu:deepslate_calcite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/deepslate_cassiterite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:deepslate_cassiterite_ore"
-  result: "gtceu:deepslate_cassiterite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/deepslate_cassiterite_sand_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:deepslate_cassiterite_sand_ore"
-  result: "gtceu:deepslate_cassiterite_sand_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/deepslate_certus_quartz_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:deepslate_certus_quartz_ore"
-  result: "gtceu:deepslate_certus_quartz_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/deepslate_chalcocite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:deepslate_chalcocite_ore"
-  result: "gtceu:deepslate_chalcocite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/deepslate_chalcopyrite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:deepslate_chalcopyrite_ore"
-  result: "gtceu:deepslate_chalcopyrite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/deepslate_chromite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:deepslate_chromite_ore"
-  result: "gtceu:deepslate_chromite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/deepslate_cinnabar_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:deepslate_cinnabar_ore"
-  result: "gtceu:deepslate_cinnabar_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/deepslate_coal_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:deepslate_coal_ore"
-  result: "gtceu:deepslate_coal_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/deepslate_cobalt_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:deepslate_cobalt_ore"
-  result: "gtceu:deepslate_cobalt_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/deepslate_cobaltite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:deepslate_cobaltite_ore"
-  result: "gtceu:deepslate_cobaltite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/deepslate_cooperite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:deepslate_cooperite_ore"
-  result: "gtceu:deepslate_cooperite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/deepslate_copper_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:deepslate_copper_ore"
-  result: "gtceu:deepslate_copper_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/deepslate_diamond_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:deepslate_diamond_ore"
-  result: "gtceu:deepslate_diamond_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/deepslate_diatomite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:deepslate_diatomite_ore"
-  result: "gtceu:deepslate_diatomite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/deepslate_electrotine_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:deepslate_electrotine_ore"
-  result: "gtceu:deepslate_electrotine_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/deepslate_emerald_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:deepslate_emerald_ore"
-  result: "gtceu:deepslate_emerald_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/deepslate_fullers_earth_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:deepslate_fullers_earth_ore"
-  result: "gtceu:deepslate_fullers_earth_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/deepslate_galena_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:deepslate_galena_ore"
-  result: "gtceu:deepslate_galena_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/deepslate_garnet_sand_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:deepslate_garnet_sand_ore"
-  result: "gtceu:deepslate_garnet_sand_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/deepslate_garnierite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:deepslate_garnierite_ore"
-  result: "gtceu:deepslate_garnierite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/deepslate_glauconite_sand_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:deepslate_glauconite_sand_ore"
-  result: "gtceu:deepslate_glauconite_sand_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/deepslate_goethite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:deepslate_goethite_ore"
-  result: "gtceu:deepslate_goethite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/deepslate_gold_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:deepslate_gold_ore"
-  result: "gtceu:deepslate_gold_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/deepslate_granitic_mineral_sand_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:deepslate_granitic_mineral_sand_ore"
-  result: "gtceu:deepslate_granitic_mineral_sand_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/deepslate_graphite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:deepslate_graphite_ore"
-  result: "gtceu:deepslate_graphite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/deepslate_green_sapphire_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:deepslate_green_sapphire_ore"
-  result: "gtceu:deepslate_green_sapphire_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/deepslate_grossular_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:deepslate_grossular_ore"
-  result: "gtceu:deepslate_grossular_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/deepslate_gypsum_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:deepslate_gypsum_ore"
-  result: "gtceu:deepslate_gypsum_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/deepslate_hematite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:deepslate_hematite_ore"
-  result: "gtceu:deepslate_hematite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/deepslate_ilmenite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:deepslate_ilmenite_ore"
-  result: "gtceu:deepslate_ilmenite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/deepslate_iron_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:deepslate_iron_ore"
-  result: "gtceu:deepslate_iron_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/deepslate_kyanite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:deepslate_kyanite_ore"
-  result: "gtceu:deepslate_kyanite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/deepslate_lapis_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:deepslate_lapis_ore"
-  result: "gtceu:deepslate_lapis_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/deepslate_lazurite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:deepslate_lazurite_ore"
-  result: "gtceu:deepslate_lazurite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/deepslate_lead_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:deepslate_lead_ore"
-  result: "gtceu:deepslate_lead_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/deepslate_lepidolite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:deepslate_lepidolite_ore"
-  result: "gtceu:deepslate_lepidolite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/deepslate_lithium_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:deepslate_lithium_ore"
-  result: "gtceu:deepslate_lithium_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/deepslate_magnesite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:deepslate_magnesite_ore"
-  result: "gtceu:deepslate_magnesite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/deepslate_magnetite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:deepslate_magnetite_ore"
-  result: "gtceu:deepslate_magnetite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/deepslate_malachite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:deepslate_malachite_ore"
-  result: "gtceu:deepslate_malachite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/deepslate_mica_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:deepslate_mica_ore"
-  result: "gtceu:deepslate_mica_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/deepslate_molybdenite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:deepslate_molybdenite_ore"
-  result: "gtceu:deepslate_molybdenite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/deepslate_molybdenum_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:deepslate_molybdenum_ore"
-  result: "gtceu:deepslate_molybdenum_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/deepslate_monazite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:deepslate_monazite_ore"
-  result: "gtceu:deepslate_monazite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/deepslate_naquadah_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:deepslate_naquadah_ore"
-  result: "gtceu:deepslate_naquadah_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/deepslate_neodymium_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:deepslate_neodymium_ore"
-  result: "gtceu:deepslate_neodymium_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/deepslate_nether_quartz_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:deepslate_nether_quartz_ore"
-  result: "gtceu:deepslate_nether_quartz_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/deepslate_nickel_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:deepslate_nickel_ore"
-  result: "gtceu:deepslate_nickel_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/deepslate_oilsands_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:deepslate_oilsands_ore"
-  result: "gtceu:deepslate_oilsands_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/deepslate_olivine_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:deepslate_olivine_ore"
-  result: "gtceu:deepslate_olivine_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/deepslate_opal_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:deepslate_opal_ore"
-  result: "gtceu:deepslate_opal_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/deepslate_palladium_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:deepslate_palladium_ore"
-  result: "gtceu:deepslate_palladium_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/deepslate_pentlandite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:deepslate_pentlandite_ore"
-  result: "gtceu:deepslate_pentlandite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/deepslate_pitchblende_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:deepslate_pitchblende_ore"
-  result: "gtceu:deepslate_pitchblende_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/deepslate_platinum_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:deepslate_platinum_ore"
-  result: "gtceu:deepslate_platinum_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/deepslate_plutonium_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:deepslate_plutonium_ore"
-  result: "gtceu:deepslate_plutonium_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/deepslate_pollucite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:deepslate_pollucite_ore"
-  result: "gtceu:deepslate_pollucite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/deepslate_powellite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:deepslate_powellite_ore"
-  result: "gtceu:deepslate_powellite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/deepslate_pyrite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:deepslate_pyrite_ore"
-  result: "gtceu:deepslate_pyrite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/deepslate_pyrochlore_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:deepslate_pyrochlore_ore"
-  result: "gtceu:deepslate_pyrochlore_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/deepslate_pyrolusite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:deepslate_pyrolusite_ore"
-  result: "gtceu:deepslate_pyrolusite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/deepslate_pyrope_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:deepslate_pyrope_ore"
-  result: "gtceu:deepslate_pyrope_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/deepslate_quartzite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:deepslate_quartzite_ore"
-  result: "gtceu:deepslate_quartzite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/deepslate_realgar_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:deepslate_realgar_ore"
-  result: "gtceu:deepslate_realgar_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/deepslate_red_garnet_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:deepslate_red_garnet_ore"
-  result: "gtceu:deepslate_red_garnet_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/deepslate_redstone_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:deepslate_redstone_ore"
-  result: "gtceu:deepslate_redstone_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/deepslate_rock_salt_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:deepslate_rock_salt_ore"
-  result: "gtceu:deepslate_rock_salt_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/deepslate_ruby_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:deepslate_ruby_ore"
-  result: "gtceu:deepslate_ruby_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/deepslate_salt_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:deepslate_salt_ore"
-  result: "gtceu:deepslate_salt_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/deepslate_saltpeter_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:deepslate_saltpeter_ore"
-  result: "gtceu:deepslate_saltpeter_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/deepslate_sapphire_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:deepslate_sapphire_ore"
-  result: "gtceu:deepslate_sapphire_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/deepslate_scheelite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:deepslate_scheelite_ore"
-  result: "gtceu:deepslate_scheelite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/deepslate_silver_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:deepslate_silver_ore"
-  result: "gtceu:deepslate_silver_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/deepslate_soapstone_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:deepslate_soapstone_ore"
-  result: "gtceu:deepslate_soapstone_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/deepslate_sodalite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:deepslate_sodalite_ore"
-  result: "gtceu:deepslate_sodalite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/deepslate_spessartine_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:deepslate_spessartine_ore"
-  result: "gtceu:deepslate_spessartine_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/deepslate_sphalerite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:deepslate_sphalerite_ore"
-  result: "gtceu:deepslate_sphalerite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/deepslate_spodumene_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:deepslate_spodumene_ore"
-  result: "gtceu:deepslate_spodumene_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/deepslate_stibnite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:deepslate_stibnite_ore"
-  result: "gtceu:deepslate_stibnite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/deepslate_sulfur_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:deepslate_sulfur_ore"
-  result: "gtceu:deepslate_sulfur_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/deepslate_talc_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:deepslate_talc_ore"
-  result: "gtceu:deepslate_talc_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/deepslate_tantalite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:deepslate_tantalite_ore"
-  result: "gtceu:deepslate_tantalite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/deepslate_tetrahedrite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:deepslate_tetrahedrite_ore"
-  result: "gtceu:deepslate_tetrahedrite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/deepslate_thorium_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:deepslate_thorium_ore"
-  result: "gtceu:deepslate_thorium_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/deepslate_tin_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:deepslate_tin_ore"
-  result: "gtceu:deepslate_tin_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/deepslate_titanium_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:deepslate_titanium_ore"
-  result: "gtceu:deepslate_titanium_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/deepslate_topaz_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:deepslate_topaz_ore"
-  result: "gtceu:deepslate_topaz_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/deepslate_tricalcium_phosphate_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:deepslate_tricalcium_phosphate_ore"
-  result: "gtceu:deepslate_tricalcium_phosphate_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/deepslate_trona_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:deepslate_trona_ore"
-  result: "gtceu:deepslate_trona_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/deepslate_tungstate_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:deepslate_tungstate_ore"
-  result: "gtceu:deepslate_tungstate_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/deepslate_uraninite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:deepslate_uraninite_ore"
-  result: "gtceu:deepslate_uraninite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/deepslate_vanadium_magnetite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:deepslate_vanadium_magnetite_ore"
-  result: "gtceu:deepslate_vanadium_magnetite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/deepslate_wulfenite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:deepslate_wulfenite_ore"
-  result: "gtceu:deepslate_wulfenite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/deepslate_yellow_garnet_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:deepslate_yellow_garnet_ore"
-  result: "gtceu:deepslate_yellow_garnet_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/deepslate_yellow_limonite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:deepslate_yellow_limonite_ore"
-  result: "gtceu:deepslate_yellow_limonite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/deepslate_zeolite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:deepslate_zeolite_ore"
-  result: "gtceu:deepslate_zeolite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/diamond_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:diamond_ore"
-  result: "gtceu:diamond_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/diatomite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:diatomite_ore"
-  result: "gtceu:diatomite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/diorite_almandine_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:diorite_almandine_ore"
-  result: "gtceu:diorite_almandine_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/diorite_aluminium_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:diorite_aluminium_ore"
-  result: "gtceu:diorite_aluminium_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/diorite_alunite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:diorite_alunite_ore"
-  result: "gtceu:diorite_alunite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/diorite_amethyst_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:diorite_amethyst_ore"
-  result: "gtceu:diorite_amethyst_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/diorite_apatite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:diorite_apatite_ore"
-  result: "gtceu:diorite_apatite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/diorite_asbestos_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:diorite_asbestos_ore"
-  result: "gtceu:diorite_asbestos_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/diorite_barite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:diorite_barite_ore"
-  result: "gtceu:diorite_barite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/diorite_basaltic_mineral_sand_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:diorite_basaltic_mineral_sand_ore"
-  result: "gtceu:diorite_basaltic_mineral_sand_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/diorite_bastnasite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:diorite_bastnasite_ore"
-  result: "gtceu:diorite_bastnasite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/diorite_bauxite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:diorite_bauxite_ore"
-  result: "gtceu:diorite_bauxite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/diorite_bentonite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:diorite_bentonite_ore"
-  result: "gtceu:diorite_bentonite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/diorite_beryllium_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:diorite_beryllium_ore"
-  result: "gtceu:diorite_beryllium_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/diorite_blue_topaz_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:diorite_blue_topaz_ore"
-  result: "gtceu:diorite_blue_topaz_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/diorite_bornite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:diorite_bornite_ore"
-  result: "gtceu:diorite_bornite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/diorite_calcite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:diorite_calcite_ore"
-  result: "gtceu:diorite_calcite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/diorite_cassiterite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:diorite_cassiterite_ore"
-  result: "gtceu:diorite_cassiterite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/diorite_cassiterite_sand_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:diorite_cassiterite_sand_ore"
-  result: "gtceu:diorite_cassiterite_sand_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/diorite_certus_quartz_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:diorite_certus_quartz_ore"
-  result: "gtceu:diorite_certus_quartz_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/diorite_chalcocite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:diorite_chalcocite_ore"
-  result: "gtceu:diorite_chalcocite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/diorite_chalcopyrite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:diorite_chalcopyrite_ore"
-  result: "gtceu:diorite_chalcopyrite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/diorite_chromite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:diorite_chromite_ore"
-  result: "gtceu:diorite_chromite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/diorite_cinnabar_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:diorite_cinnabar_ore"
-  result: "gtceu:diorite_cinnabar_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/diorite_coal_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:diorite_coal_ore"
-  result: "gtceu:diorite_coal_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/diorite_cobalt_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:diorite_cobalt_ore"
-  result: "gtceu:diorite_cobalt_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/diorite_cobaltite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:diorite_cobaltite_ore"
-  result: "gtceu:diorite_cobaltite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/diorite_cooperite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:diorite_cooperite_ore"
-  result: "gtceu:diorite_cooperite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/diorite_copper_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:diorite_copper_ore"
-  result: "gtceu:diorite_copper_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/diorite_diamond_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:diorite_diamond_ore"
-  result: "gtceu:diorite_diamond_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/diorite_diatomite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:diorite_diatomite_ore"
-  result: "gtceu:diorite_diatomite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/diorite_electrotine_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:diorite_electrotine_ore"
-  result: "gtceu:diorite_electrotine_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/diorite_emerald_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:diorite_emerald_ore"
-  result: "gtceu:diorite_emerald_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/diorite_fullers_earth_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:diorite_fullers_earth_ore"
-  result: "gtceu:diorite_fullers_earth_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/diorite_galena_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:diorite_galena_ore"
-  result: "gtceu:diorite_galena_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/diorite_garnet_sand_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:diorite_garnet_sand_ore"
-  result: "gtceu:diorite_garnet_sand_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/diorite_garnierite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:diorite_garnierite_ore"
-  result: "gtceu:diorite_garnierite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/diorite_glauconite_sand_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:diorite_glauconite_sand_ore"
-  result: "gtceu:diorite_glauconite_sand_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/diorite_goethite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:diorite_goethite_ore"
-  result: "gtceu:diorite_goethite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/diorite_gold_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:diorite_gold_ore"
-  result: "gtceu:diorite_gold_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/diorite_granitic_mineral_sand_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:diorite_granitic_mineral_sand_ore"
-  result: "gtceu:diorite_granitic_mineral_sand_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/diorite_graphite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:diorite_graphite_ore"
-  result: "gtceu:diorite_graphite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/diorite_green_sapphire_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:diorite_green_sapphire_ore"
-  result: "gtceu:diorite_green_sapphire_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/diorite_grossular_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:diorite_grossular_ore"
-  result: "gtceu:diorite_grossular_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/diorite_gypsum_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:diorite_gypsum_ore"
-  result: "gtceu:diorite_gypsum_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/diorite_hematite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:diorite_hematite_ore"
-  result: "gtceu:diorite_hematite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/diorite_ilmenite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:diorite_ilmenite_ore"
-  result: "gtceu:diorite_ilmenite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/diorite_iron_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:diorite_iron_ore"
-  result: "gtceu:diorite_iron_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/diorite_kyanite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:diorite_kyanite_ore"
-  result: "gtceu:diorite_kyanite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/diorite_lapis_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:diorite_lapis_ore"
-  result: "gtceu:diorite_lapis_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/diorite_lazurite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:diorite_lazurite_ore"
-  result: "gtceu:diorite_lazurite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/diorite_lead_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:diorite_lead_ore"
-  result: "gtceu:diorite_lead_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/diorite_lepidolite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:diorite_lepidolite_ore"
-  result: "gtceu:diorite_lepidolite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/diorite_lithium_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:diorite_lithium_ore"
-  result: "gtceu:diorite_lithium_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/diorite_magnesite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:diorite_magnesite_ore"
-  result: "gtceu:diorite_magnesite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/diorite_magnetite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:diorite_magnetite_ore"
-  result: "gtceu:diorite_magnetite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/diorite_malachite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:diorite_malachite_ore"
-  result: "gtceu:diorite_malachite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/diorite_mica_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:diorite_mica_ore"
-  result: "gtceu:diorite_mica_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/diorite_molybdenite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:diorite_molybdenite_ore"
-  result: "gtceu:diorite_molybdenite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/diorite_molybdenum_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:diorite_molybdenum_ore"
-  result: "gtceu:diorite_molybdenum_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/diorite_monazite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:diorite_monazite_ore"
-  result: "gtceu:diorite_monazite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/diorite_naquadah_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:diorite_naquadah_ore"
-  result: "gtceu:diorite_naquadah_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/diorite_neodymium_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:diorite_neodymium_ore"
-  result: "gtceu:diorite_neodymium_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/diorite_nether_quartz_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:diorite_nether_quartz_ore"
-  result: "gtceu:diorite_nether_quartz_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/diorite_nickel_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:diorite_nickel_ore"
-  result: "gtceu:diorite_nickel_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/diorite_oilsands_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:diorite_oilsands_ore"
-  result: "gtceu:diorite_oilsands_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/diorite_olivine_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:diorite_olivine_ore"
-  result: "gtceu:diorite_olivine_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/diorite_opal_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:diorite_opal_ore"
-  result: "gtceu:diorite_opal_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/diorite_palladium_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:diorite_palladium_ore"
-  result: "gtceu:diorite_palladium_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/diorite_pentlandite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:diorite_pentlandite_ore"
-  result: "gtceu:diorite_pentlandite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/diorite_pitchblende_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:diorite_pitchblende_ore"
-  result: "gtceu:diorite_pitchblende_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/diorite_platinum_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:diorite_platinum_ore"
-  result: "gtceu:diorite_platinum_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/diorite_plutonium_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:diorite_plutonium_ore"
-  result: "gtceu:diorite_plutonium_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/diorite_pollucite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:diorite_pollucite_ore"
-  result: "gtceu:diorite_pollucite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/diorite_powellite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:diorite_powellite_ore"
-  result: "gtceu:diorite_powellite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/diorite_pyrite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:diorite_pyrite_ore"
-  result: "gtceu:diorite_pyrite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/diorite_pyrochlore_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:diorite_pyrochlore_ore"
-  result: "gtceu:diorite_pyrochlore_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/diorite_pyrolusite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:diorite_pyrolusite_ore"
-  result: "gtceu:diorite_pyrolusite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/diorite_pyrope_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:diorite_pyrope_ore"
-  result: "gtceu:diorite_pyrope_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/diorite_quartzite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:diorite_quartzite_ore"
-  result: "gtceu:diorite_quartzite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/diorite_realgar_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:diorite_realgar_ore"
-  result: "gtceu:diorite_realgar_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/diorite_red_garnet_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:diorite_red_garnet_ore"
-  result: "gtceu:diorite_red_garnet_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/diorite_redstone_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:diorite_redstone_ore"
-  result: "gtceu:diorite_redstone_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/diorite_rock_salt_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:diorite_rock_salt_ore"
-  result: "gtceu:diorite_rock_salt_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/diorite_ruby_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:diorite_ruby_ore"
-  result: "gtceu:diorite_ruby_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/diorite_salt_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:diorite_salt_ore"
-  result: "gtceu:diorite_salt_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/diorite_saltpeter_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:diorite_saltpeter_ore"
-  result: "gtceu:diorite_saltpeter_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/diorite_sapphire_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:diorite_sapphire_ore"
-  result: "gtceu:diorite_sapphire_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/diorite_scheelite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:diorite_scheelite_ore"
-  result: "gtceu:diorite_scheelite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/diorite_silver_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:diorite_silver_ore"
-  result: "gtceu:diorite_silver_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/diorite_soapstone_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:diorite_soapstone_ore"
-  result: "gtceu:diorite_soapstone_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/diorite_sodalite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:diorite_sodalite_ore"
-  result: "gtceu:diorite_sodalite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/diorite_spessartine_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:diorite_spessartine_ore"
-  result: "gtceu:diorite_spessartine_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/diorite_sphalerite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:diorite_sphalerite_ore"
-  result: "gtceu:diorite_sphalerite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/diorite_spodumene_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:diorite_spodumene_ore"
-  result: "gtceu:diorite_spodumene_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/diorite_stibnite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:diorite_stibnite_ore"
-  result: "gtceu:diorite_stibnite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/diorite_sulfur_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:diorite_sulfur_ore"
-  result: "gtceu:diorite_sulfur_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/diorite_talc_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:diorite_talc_ore"
-  result: "gtceu:diorite_talc_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/diorite_tantalite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:diorite_tantalite_ore"
-  result: "gtceu:diorite_tantalite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/diorite_tetrahedrite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:diorite_tetrahedrite_ore"
-  result: "gtceu:diorite_tetrahedrite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/diorite_thorium_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:diorite_thorium_ore"
-  result: "gtceu:diorite_thorium_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/diorite_tin_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:diorite_tin_ore"
-  result: "gtceu:diorite_tin_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/diorite_titanium_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:diorite_titanium_ore"
-  result: "gtceu:diorite_titanium_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/diorite_topaz_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:diorite_topaz_ore"
-  result: "gtceu:diorite_topaz_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/diorite_tricalcium_phosphate_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:diorite_tricalcium_phosphate_ore"
-  result: "gtceu:diorite_tricalcium_phosphate_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/diorite_trona_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:diorite_trona_ore"
-  result: "gtceu:diorite_trona_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/diorite_tungstate_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:diorite_tungstate_ore"
-  result: "gtceu:diorite_tungstate_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/diorite_uraninite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:diorite_uraninite_ore"
-  result: "gtceu:diorite_uraninite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/diorite_vanadium_magnetite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:diorite_vanadium_magnetite_ore"
-  result: "gtceu:diorite_vanadium_magnetite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/diorite_wulfenite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:diorite_wulfenite_ore"
-  result: "gtceu:diorite_wulfenite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/diorite_yellow_garnet_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:diorite_yellow_garnet_ore"
-  result: "gtceu:diorite_yellow_garnet_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/diorite_yellow_limonite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:diorite_yellow_limonite_ore"
-  result: "gtceu:diorite_yellow_limonite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/diorite_zeolite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:diorite_zeolite_ore"
-  result: "gtceu:diorite_zeolite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/dolomite_almandine_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:dolomite_almandine_ore"
-  result: "gtceu:dolomite_almandine_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/dolomite_aluminium_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:dolomite_aluminium_ore"
-  result: "gtceu:dolomite_aluminium_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/dolomite_alunite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:dolomite_alunite_ore"
-  result: "gtceu:dolomite_alunite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/dolomite_amethyst_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:dolomite_amethyst_ore"
-  result: "gtceu:dolomite_amethyst_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/dolomite_apatite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:dolomite_apatite_ore"
-  result: "gtceu:dolomite_apatite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/dolomite_asbestos_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:dolomite_asbestos_ore"
-  result: "gtceu:dolomite_asbestos_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/dolomite_barite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:dolomite_barite_ore"
-  result: "gtceu:dolomite_barite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/dolomite_basaltic_mineral_sand_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:dolomite_basaltic_mineral_sand_ore"
-  result: "gtceu:dolomite_basaltic_mineral_sand_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/dolomite_bastnasite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:dolomite_bastnasite_ore"
-  result: "gtceu:dolomite_bastnasite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/dolomite_bauxite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:dolomite_bauxite_ore"
-  result: "gtceu:dolomite_bauxite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/dolomite_bentonite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:dolomite_bentonite_ore"
-  result: "gtceu:dolomite_bentonite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/dolomite_beryllium_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:dolomite_beryllium_ore"
-  result: "gtceu:dolomite_beryllium_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/dolomite_blue_topaz_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:dolomite_blue_topaz_ore"
-  result: "gtceu:dolomite_blue_topaz_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/dolomite_bornite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:dolomite_bornite_ore"
-  result: "gtceu:dolomite_bornite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/dolomite_calcite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:dolomite_calcite_ore"
-  result: "gtceu:dolomite_calcite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/dolomite_cassiterite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:dolomite_cassiterite_ore"
-  result: "gtceu:dolomite_cassiterite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/dolomite_cassiterite_sand_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:dolomite_cassiterite_sand_ore"
-  result: "gtceu:dolomite_cassiterite_sand_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/dolomite_certus_quartz_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:dolomite_certus_quartz_ore"
-  result: "gtceu:dolomite_certus_quartz_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/dolomite_chalcocite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:dolomite_chalcocite_ore"
-  result: "gtceu:dolomite_chalcocite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/dolomite_chalcopyrite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:dolomite_chalcopyrite_ore"
-  result: "gtceu:dolomite_chalcopyrite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/dolomite_chromite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:dolomite_chromite_ore"
-  result: "gtceu:dolomite_chromite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/dolomite_cinnabar_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:dolomite_cinnabar_ore"
-  result: "gtceu:dolomite_cinnabar_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/dolomite_coal_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:dolomite_coal_ore"
-  result: "gtceu:dolomite_coal_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/dolomite_cobalt_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:dolomite_cobalt_ore"
-  result: "gtceu:dolomite_cobalt_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/dolomite_cobaltite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:dolomite_cobaltite_ore"
-  result: "gtceu:dolomite_cobaltite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/dolomite_cooperite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:dolomite_cooperite_ore"
-  result: "gtceu:dolomite_cooperite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/dolomite_copper_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:dolomite_copper_ore"
-  result: "gtceu:dolomite_copper_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/dolomite_diamond_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:dolomite_diamond_ore"
-  result: "gtceu:dolomite_diamond_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/dolomite_diatomite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:dolomite_diatomite_ore"
-  result: "gtceu:dolomite_diatomite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/dolomite_electrotine_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:dolomite_electrotine_ore"
-  result: "gtceu:dolomite_electrotine_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/dolomite_emerald_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:dolomite_emerald_ore"
-  result: "gtceu:dolomite_emerald_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/dolomite_fullers_earth_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:dolomite_fullers_earth_ore"
-  result: "gtceu:dolomite_fullers_earth_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/dolomite_galena_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:dolomite_galena_ore"
-  result: "gtceu:dolomite_galena_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/dolomite_garnet_sand_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:dolomite_garnet_sand_ore"
-  result: "gtceu:dolomite_garnet_sand_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/dolomite_garnierite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:dolomite_garnierite_ore"
-  result: "gtceu:dolomite_garnierite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/dolomite_glauconite_sand_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:dolomite_glauconite_sand_ore"
-  result: "gtceu:dolomite_glauconite_sand_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/dolomite_goethite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:dolomite_goethite_ore"
-  result: "gtceu:dolomite_goethite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/dolomite_gold_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:dolomite_gold_ore"
-  result: "gtceu:dolomite_gold_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/dolomite_granitic_mineral_sand_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:dolomite_granitic_mineral_sand_ore"
-  result: "gtceu:dolomite_granitic_mineral_sand_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/dolomite_graphite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:dolomite_graphite_ore"
-  result: "gtceu:dolomite_graphite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/dolomite_green_sapphire_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:dolomite_green_sapphire_ore"
-  result: "gtceu:dolomite_green_sapphire_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/dolomite_grossular_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:dolomite_grossular_ore"
-  result: "gtceu:dolomite_grossular_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/dolomite_gypsum_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:dolomite_gypsum_ore"
-  result: "gtceu:dolomite_gypsum_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/dolomite_hematite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:dolomite_hematite_ore"
-  result: "gtceu:dolomite_hematite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/dolomite_ilmenite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:dolomite_ilmenite_ore"
-  result: "gtceu:dolomite_ilmenite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/dolomite_iron_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:dolomite_iron_ore"
-  result: "gtceu:dolomite_iron_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/dolomite_kyanite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:dolomite_kyanite_ore"
-  result: "gtceu:dolomite_kyanite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/dolomite_lapis_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:dolomite_lapis_ore"
-  result: "gtceu:dolomite_lapis_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/dolomite_lazurite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:dolomite_lazurite_ore"
-  result: "gtceu:dolomite_lazurite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/dolomite_lead_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:dolomite_lead_ore"
-  result: "gtceu:dolomite_lead_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/dolomite_lepidolite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:dolomite_lepidolite_ore"
-  result: "gtceu:dolomite_lepidolite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/dolomite_lithium_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:dolomite_lithium_ore"
-  result: "gtceu:dolomite_lithium_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/dolomite_magnesite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:dolomite_magnesite_ore"
-  result: "gtceu:dolomite_magnesite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/dolomite_magnetite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:dolomite_magnetite_ore"
-  result: "gtceu:dolomite_magnetite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/dolomite_malachite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:dolomite_malachite_ore"
-  result: "gtceu:dolomite_malachite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/dolomite_mica_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:dolomite_mica_ore"
-  result: "gtceu:dolomite_mica_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/dolomite_molybdenite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:dolomite_molybdenite_ore"
-  result: "gtceu:dolomite_molybdenite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/dolomite_molybdenum_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:dolomite_molybdenum_ore"
-  result: "gtceu:dolomite_molybdenum_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/dolomite_monazite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:dolomite_monazite_ore"
-  result: "gtceu:dolomite_monazite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/dolomite_naquadah_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:dolomite_naquadah_ore"
-  result: "gtceu:dolomite_naquadah_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/dolomite_neodymium_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:dolomite_neodymium_ore"
-  result: "gtceu:dolomite_neodymium_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/dolomite_nether_quartz_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:dolomite_nether_quartz_ore"
-  result: "gtceu:dolomite_nether_quartz_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/dolomite_nickel_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:dolomite_nickel_ore"
-  result: "gtceu:dolomite_nickel_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/dolomite_oilsands_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:dolomite_oilsands_ore"
-  result: "gtceu:dolomite_oilsands_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/dolomite_olivine_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:dolomite_olivine_ore"
-  result: "gtceu:dolomite_olivine_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/dolomite_opal_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:dolomite_opal_ore"
-  result: "gtceu:dolomite_opal_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/dolomite_palladium_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:dolomite_palladium_ore"
-  result: "gtceu:dolomite_palladium_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/dolomite_pentlandite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:dolomite_pentlandite_ore"
-  result: "gtceu:dolomite_pentlandite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/dolomite_pitchblende_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:dolomite_pitchblende_ore"
-  result: "gtceu:dolomite_pitchblende_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/dolomite_platinum_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:dolomite_platinum_ore"
-  result: "gtceu:dolomite_platinum_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/dolomite_plutonium_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:dolomite_plutonium_ore"
-  result: "gtceu:dolomite_plutonium_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/dolomite_pollucite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:dolomite_pollucite_ore"
-  result: "gtceu:dolomite_pollucite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/dolomite_powellite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:dolomite_powellite_ore"
-  result: "gtceu:dolomite_powellite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/dolomite_pyrite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:dolomite_pyrite_ore"
-  result: "gtceu:dolomite_pyrite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/dolomite_pyrochlore_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:dolomite_pyrochlore_ore"
-  result: "gtceu:dolomite_pyrochlore_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/dolomite_pyrolusite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:dolomite_pyrolusite_ore"
-  result: "gtceu:dolomite_pyrolusite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/dolomite_pyrope_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:dolomite_pyrope_ore"
-  result: "gtceu:dolomite_pyrope_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/dolomite_quartzite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:dolomite_quartzite_ore"
-  result: "gtceu:dolomite_quartzite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/dolomite_realgar_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:dolomite_realgar_ore"
-  result: "gtceu:dolomite_realgar_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/dolomite_red_garnet_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:dolomite_red_garnet_ore"
-  result: "gtceu:dolomite_red_garnet_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/dolomite_redstone_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:dolomite_redstone_ore"
-  result: "gtceu:dolomite_redstone_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/dolomite_rock_salt_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:dolomite_rock_salt_ore"
-  result: "gtceu:dolomite_rock_salt_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/dolomite_ruby_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:dolomite_ruby_ore"
-  result: "gtceu:dolomite_ruby_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/dolomite_salt_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:dolomite_salt_ore"
-  result: "gtceu:dolomite_salt_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/dolomite_saltpeter_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:dolomite_saltpeter_ore"
-  result: "gtceu:dolomite_saltpeter_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/dolomite_sapphire_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:dolomite_sapphire_ore"
-  result: "gtceu:dolomite_sapphire_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/dolomite_scheelite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:dolomite_scheelite_ore"
-  result: "gtceu:dolomite_scheelite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/dolomite_silver_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:dolomite_silver_ore"
-  result: "gtceu:dolomite_silver_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/dolomite_soapstone_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:dolomite_soapstone_ore"
-  result: "gtceu:dolomite_soapstone_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/dolomite_sodalite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:dolomite_sodalite_ore"
-  result: "gtceu:dolomite_sodalite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/dolomite_spessartine_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:dolomite_spessartine_ore"
-  result: "gtceu:dolomite_spessartine_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/dolomite_sphalerite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:dolomite_sphalerite_ore"
-  result: "gtceu:dolomite_sphalerite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/dolomite_spodumene_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:dolomite_spodumene_ore"
-  result: "gtceu:dolomite_spodumene_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/dolomite_stibnite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:dolomite_stibnite_ore"
-  result: "gtceu:dolomite_stibnite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/dolomite_sulfur_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:dolomite_sulfur_ore"
-  result: "gtceu:dolomite_sulfur_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/dolomite_talc_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:dolomite_talc_ore"
-  result: "gtceu:dolomite_talc_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/dolomite_tantalite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:dolomite_tantalite_ore"
-  result: "gtceu:dolomite_tantalite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/dolomite_tetrahedrite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:dolomite_tetrahedrite_ore"
-  result: "gtceu:dolomite_tetrahedrite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/dolomite_thorium_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:dolomite_thorium_ore"
-  result: "gtceu:dolomite_thorium_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/dolomite_tin_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:dolomite_tin_ore"
-  result: "gtceu:dolomite_tin_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/dolomite_titanium_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:dolomite_titanium_ore"
-  result: "gtceu:dolomite_titanium_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/dolomite_topaz_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:dolomite_topaz_ore"
-  result: "gtceu:dolomite_topaz_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/dolomite_tricalcium_phosphate_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:dolomite_tricalcium_phosphate_ore"
-  result: "gtceu:dolomite_tricalcium_phosphate_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/dolomite_trona_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:dolomite_trona_ore"
-  result: "gtceu:dolomite_trona_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/dolomite_tungstate_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:dolomite_tungstate_ore"
-  result: "gtceu:dolomite_tungstate_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/dolomite_uraninite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:dolomite_uraninite_ore"
-  result: "gtceu:dolomite_uraninite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/dolomite_vanadium_magnetite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:dolomite_vanadium_magnetite_ore"
-  result: "gtceu:dolomite_vanadium_magnetite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/dolomite_wulfenite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:dolomite_wulfenite_ore"
-  result: "gtceu:dolomite_wulfenite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/dolomite_yellow_garnet_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:dolomite_yellow_garnet_ore"
-  result: "gtceu:dolomite_yellow_garnet_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/dolomite_yellow_limonite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:dolomite_yellow_limonite_ore"
-  result: "gtceu:dolomite_yellow_limonite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/dolomite_zeolite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:dolomite_zeolite_ore"
-  result: "gtceu:dolomite_zeolite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/electrotine_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:electrotine_ore"
-  result: "gtceu:electrotine_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/emerald_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:emerald_ore"
-  result: "gtceu:emerald_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/endstone_almandine_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:endstone_almandine_ore"
-  result: "gtceu:endstone_almandine_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/endstone_aluminium_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:endstone_aluminium_ore"
-  result: "gtceu:endstone_aluminium_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/endstone_alunite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:endstone_alunite_ore"
-  result: "gtceu:endstone_alunite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/endstone_amethyst_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:endstone_amethyst_ore"
-  result: "gtceu:endstone_amethyst_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/endstone_apatite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:endstone_apatite_ore"
-  result: "gtceu:endstone_apatite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/endstone_asbestos_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:endstone_asbestos_ore"
-  result: "gtceu:endstone_asbestos_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/endstone_barite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:endstone_barite_ore"
-  result: "gtceu:endstone_barite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/endstone_basaltic_mineral_sand_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:endstone_basaltic_mineral_sand_ore"
-  result: "gtceu:endstone_basaltic_mineral_sand_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/endstone_bastnasite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:endstone_bastnasite_ore"
-  result: "gtceu:endstone_bastnasite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/endstone_bauxite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:endstone_bauxite_ore"
-  result: "gtceu:endstone_bauxite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/endstone_bentonite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:endstone_bentonite_ore"
-  result: "gtceu:endstone_bentonite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/endstone_beryllium_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:endstone_beryllium_ore"
-  result: "gtceu:endstone_beryllium_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/endstone_blue_topaz_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:endstone_blue_topaz_ore"
-  result: "gtceu:endstone_blue_topaz_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/endstone_bornite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:endstone_bornite_ore"
-  result: "gtceu:endstone_bornite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/endstone_calcite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:endstone_calcite_ore"
-  result: "gtceu:endstone_calcite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/endstone_cassiterite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:endstone_cassiterite_ore"
-  result: "gtceu:endstone_cassiterite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/endstone_cassiterite_sand_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:endstone_cassiterite_sand_ore"
-  result: "gtceu:endstone_cassiterite_sand_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/endstone_certus_quartz_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:endstone_certus_quartz_ore"
-  result: "gtceu:endstone_certus_quartz_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/endstone_chalcocite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:endstone_chalcocite_ore"
-  result: "gtceu:endstone_chalcocite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/endstone_chalcopyrite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:endstone_chalcopyrite_ore"
-  result: "gtceu:endstone_chalcopyrite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/endstone_chromite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:endstone_chromite_ore"
-  result: "gtceu:endstone_chromite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/endstone_cinnabar_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:endstone_cinnabar_ore"
-  result: "gtceu:endstone_cinnabar_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/endstone_coal_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:endstone_coal_ore"
-  result: "gtceu:endstone_coal_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/endstone_cobalt_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:endstone_cobalt_ore"
-  result: "gtceu:endstone_cobalt_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/endstone_cobaltite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:endstone_cobaltite_ore"
-  result: "gtceu:endstone_cobaltite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/endstone_cooperite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:endstone_cooperite_ore"
-  result: "gtceu:endstone_cooperite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/endstone_copper_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:endstone_copper_ore"
-  result: "gtceu:endstone_copper_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/endstone_diamond_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:endstone_diamond_ore"
-  result: "gtceu:endstone_diamond_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/endstone_diatomite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:endstone_diatomite_ore"
-  result: "gtceu:endstone_diatomite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/endstone_electrotine_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:endstone_electrotine_ore"
-  result: "gtceu:endstone_electrotine_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/endstone_emerald_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:endstone_emerald_ore"
-  result: "gtceu:endstone_emerald_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/endstone_fullers_earth_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:endstone_fullers_earth_ore"
-  result: "gtceu:endstone_fullers_earth_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/endstone_galena_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:endstone_galena_ore"
-  result: "gtceu:endstone_galena_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/endstone_garnet_sand_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:endstone_garnet_sand_ore"
-  result: "gtceu:endstone_garnet_sand_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/endstone_garnierite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:endstone_garnierite_ore"
-  result: "gtceu:endstone_garnierite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/endstone_glauconite_sand_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:endstone_glauconite_sand_ore"
-  result: "gtceu:endstone_glauconite_sand_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/endstone_goethite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:endstone_goethite_ore"
-  result: "gtceu:endstone_goethite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/endstone_gold_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:endstone_gold_ore"
-  result: "gtceu:endstone_gold_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/endstone_granitic_mineral_sand_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:endstone_granitic_mineral_sand_ore"
-  result: "gtceu:endstone_granitic_mineral_sand_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/endstone_graphite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:endstone_graphite_ore"
-  result: "gtceu:endstone_graphite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/endstone_green_sapphire_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:endstone_green_sapphire_ore"
-  result: "gtceu:endstone_green_sapphire_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/endstone_grossular_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:endstone_grossular_ore"
-  result: "gtceu:endstone_grossular_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/endstone_gypsum_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:endstone_gypsum_ore"
-  result: "gtceu:endstone_gypsum_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/endstone_hematite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:endstone_hematite_ore"
-  result: "gtceu:endstone_hematite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/endstone_ilmenite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:endstone_ilmenite_ore"
-  result: "gtceu:endstone_ilmenite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/endstone_iron_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:endstone_iron_ore"
-  result: "gtceu:endstone_iron_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/endstone_kyanite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:endstone_kyanite_ore"
-  result: "gtceu:endstone_kyanite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/endstone_lapis_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:endstone_lapis_ore"
-  result: "gtceu:endstone_lapis_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/endstone_lazurite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:endstone_lazurite_ore"
-  result: "gtceu:endstone_lazurite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/endstone_lead_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:endstone_lead_ore"
-  result: "gtceu:endstone_lead_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/endstone_lepidolite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:endstone_lepidolite_ore"
-  result: "gtceu:endstone_lepidolite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/endstone_lithium_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:endstone_lithium_ore"
-  result: "gtceu:endstone_lithium_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/endstone_magnesite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:endstone_magnesite_ore"
-  result: "gtceu:endstone_magnesite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/endstone_magnetite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:endstone_magnetite_ore"
-  result: "gtceu:endstone_magnetite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/endstone_malachite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:endstone_malachite_ore"
-  result: "gtceu:endstone_malachite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/endstone_mica_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:endstone_mica_ore"
-  result: "gtceu:endstone_mica_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/endstone_molybdenite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:endstone_molybdenite_ore"
-  result: "gtceu:endstone_molybdenite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/endstone_molybdenum_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:endstone_molybdenum_ore"
-  result: "gtceu:endstone_molybdenum_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/endstone_monazite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:endstone_monazite_ore"
-  result: "gtceu:endstone_monazite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/endstone_naquadah_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:endstone_naquadah_ore"
-  result: "gtceu:endstone_naquadah_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/endstone_neodymium_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:endstone_neodymium_ore"
-  result: "gtceu:endstone_neodymium_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/endstone_nether_quartz_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:endstone_nether_quartz_ore"
-  result: "gtceu:endstone_nether_quartz_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/endstone_nickel_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:endstone_nickel_ore"
-  result: "gtceu:endstone_nickel_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/endstone_oilsands_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:endstone_oilsands_ore"
-  result: "gtceu:endstone_oilsands_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/endstone_olivine_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:endstone_olivine_ore"
-  result: "gtceu:endstone_olivine_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/endstone_opal_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:endstone_opal_ore"
-  result: "gtceu:endstone_opal_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/endstone_palladium_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:endstone_palladium_ore"
-  result: "gtceu:endstone_palladium_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/endstone_pentlandite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:endstone_pentlandite_ore"
-  result: "gtceu:endstone_pentlandite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/endstone_pitchblende_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:endstone_pitchblende_ore"
-  result: "gtceu:endstone_pitchblende_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/endstone_platinum_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:endstone_platinum_ore"
-  result: "gtceu:endstone_platinum_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/endstone_plutonium_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:endstone_plutonium_ore"
-  result: "gtceu:endstone_plutonium_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/endstone_pollucite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:endstone_pollucite_ore"
-  result: "gtceu:endstone_pollucite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/endstone_powellite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:endstone_powellite_ore"
-  result: "gtceu:endstone_powellite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/endstone_pyrite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:endstone_pyrite_ore"
-  result: "gtceu:endstone_pyrite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/endstone_pyrochlore_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:endstone_pyrochlore_ore"
-  result: "gtceu:endstone_pyrochlore_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/endstone_pyrolusite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:endstone_pyrolusite_ore"
-  result: "gtceu:endstone_pyrolusite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/endstone_pyrope_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:endstone_pyrope_ore"
-  result: "gtceu:endstone_pyrope_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/endstone_quartzite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:endstone_quartzite_ore"
-  result: "gtceu:endstone_quartzite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/endstone_realgar_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:endstone_realgar_ore"
-  result: "gtceu:endstone_realgar_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/endstone_red_garnet_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:endstone_red_garnet_ore"
-  result: "gtceu:endstone_red_garnet_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/endstone_redstone_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:endstone_redstone_ore"
-  result: "gtceu:endstone_redstone_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/endstone_rock_salt_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:endstone_rock_salt_ore"
-  result: "gtceu:endstone_rock_salt_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/endstone_ruby_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:endstone_ruby_ore"
-  result: "gtceu:endstone_ruby_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/endstone_salt_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:endstone_salt_ore"
-  result: "gtceu:endstone_salt_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/endstone_saltpeter_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:endstone_saltpeter_ore"
-  result: "gtceu:endstone_saltpeter_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/endstone_sapphire_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:endstone_sapphire_ore"
-  result: "gtceu:endstone_sapphire_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/endstone_scheelite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:endstone_scheelite_ore"
-  result: "gtceu:endstone_scheelite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/endstone_silver_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:endstone_silver_ore"
-  result: "gtceu:endstone_silver_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/endstone_soapstone_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:endstone_soapstone_ore"
-  result: "gtceu:endstone_soapstone_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/endstone_sodalite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:endstone_sodalite_ore"
-  result: "gtceu:endstone_sodalite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/endstone_spessartine_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:endstone_spessartine_ore"
-  result: "gtceu:endstone_spessartine_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/endstone_sphalerite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:endstone_sphalerite_ore"
-  result: "gtceu:endstone_sphalerite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/endstone_spodumene_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:endstone_spodumene_ore"
-  result: "gtceu:endstone_spodumene_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/endstone_stibnite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:endstone_stibnite_ore"
-  result: "gtceu:endstone_stibnite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/endstone_sulfur_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:endstone_sulfur_ore"
-  result: "gtceu:endstone_sulfur_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/endstone_talc_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:endstone_talc_ore"
-  result: "gtceu:endstone_talc_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/endstone_tantalite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:endstone_tantalite_ore"
-  result: "gtceu:endstone_tantalite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/endstone_tetrahedrite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:endstone_tetrahedrite_ore"
-  result: "gtceu:endstone_tetrahedrite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/endstone_thorium_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:endstone_thorium_ore"
-  result: "gtceu:endstone_thorium_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/endstone_tin_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:endstone_tin_ore"
-  result: "gtceu:endstone_tin_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/endstone_titanium_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:endstone_titanium_ore"
-  result: "gtceu:endstone_titanium_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/endstone_topaz_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:endstone_topaz_ore"
-  result: "gtceu:endstone_topaz_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/endstone_tricalcium_phosphate_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:endstone_tricalcium_phosphate_ore"
-  result: "gtceu:endstone_tricalcium_phosphate_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/endstone_trona_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:endstone_trona_ore"
-  result: "gtceu:endstone_trona_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/endstone_tungstate_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:endstone_tungstate_ore"
-  result: "gtceu:endstone_tungstate_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/endstone_uraninite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:endstone_uraninite_ore"
-  result: "gtceu:endstone_uraninite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/endstone_vanadium_magnetite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:endstone_vanadium_magnetite_ore"
-  result: "gtceu:endstone_vanadium_magnetite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/endstone_wulfenite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:endstone_wulfenite_ore"
-  result: "gtceu:endstone_wulfenite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/endstone_yellow_garnet_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:endstone_yellow_garnet_ore"
-  result: "gtceu:endstone_yellow_garnet_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/endstone_yellow_limonite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:endstone_yellow_limonite_ore"
-  result: "gtceu:endstone_yellow_limonite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/endstone_zeolite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:endstone_zeolite_ore"
-  result: "gtceu:endstone_zeolite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/fullers_earth_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:fullers_earth_ore"
-  result: "gtceu:fullers_earth_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/gabbro_almandine_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:gabbro_almandine_ore"
-  result: "gtceu:gabbro_almandine_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/gabbro_aluminium_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:gabbro_aluminium_ore"
-  result: "gtceu:gabbro_aluminium_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/gabbro_alunite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:gabbro_alunite_ore"
-  result: "gtceu:gabbro_alunite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/gabbro_amethyst_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:gabbro_amethyst_ore"
-  result: "gtceu:gabbro_amethyst_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/gabbro_apatite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:gabbro_apatite_ore"
-  result: "gtceu:gabbro_apatite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/gabbro_asbestos_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:gabbro_asbestos_ore"
-  result: "gtceu:gabbro_asbestos_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/gabbro_barite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:gabbro_barite_ore"
-  result: "gtceu:gabbro_barite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/gabbro_basaltic_mineral_sand_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:gabbro_basaltic_mineral_sand_ore"
-  result: "gtceu:gabbro_basaltic_mineral_sand_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/gabbro_bastnasite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:gabbro_bastnasite_ore"
-  result: "gtceu:gabbro_bastnasite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/gabbro_bauxite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:gabbro_bauxite_ore"
-  result: "gtceu:gabbro_bauxite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/gabbro_bentonite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:gabbro_bentonite_ore"
-  result: "gtceu:gabbro_bentonite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/gabbro_beryllium_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:gabbro_beryllium_ore"
-  result: "gtceu:gabbro_beryllium_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/gabbro_blue_topaz_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:gabbro_blue_topaz_ore"
-  result: "gtceu:gabbro_blue_topaz_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/gabbro_bornite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:gabbro_bornite_ore"
-  result: "gtceu:gabbro_bornite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/gabbro_calcite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:gabbro_calcite_ore"
-  result: "gtceu:gabbro_calcite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/gabbro_cassiterite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:gabbro_cassiterite_ore"
-  result: "gtceu:gabbro_cassiterite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/gabbro_cassiterite_sand_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:gabbro_cassiterite_sand_ore"
-  result: "gtceu:gabbro_cassiterite_sand_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/gabbro_certus_quartz_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:gabbro_certus_quartz_ore"
-  result: "gtceu:gabbro_certus_quartz_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/gabbro_chalcocite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:gabbro_chalcocite_ore"
-  result: "gtceu:gabbro_chalcocite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/gabbro_chalcopyrite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:gabbro_chalcopyrite_ore"
-  result: "gtceu:gabbro_chalcopyrite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/gabbro_chromite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:gabbro_chromite_ore"
-  result: "gtceu:gabbro_chromite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/gabbro_cinnabar_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:gabbro_cinnabar_ore"
-  result: "gtceu:gabbro_cinnabar_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/gabbro_coal_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:gabbro_coal_ore"
-  result: "gtceu:gabbro_coal_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/gabbro_cobalt_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:gabbro_cobalt_ore"
-  result: "gtceu:gabbro_cobalt_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/gabbro_cobaltite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:gabbro_cobaltite_ore"
-  result: "gtceu:gabbro_cobaltite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/gabbro_cooperite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:gabbro_cooperite_ore"
-  result: "gtceu:gabbro_cooperite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/gabbro_copper_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:gabbro_copper_ore"
-  result: "gtceu:gabbro_copper_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/gabbro_diamond_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:gabbro_diamond_ore"
-  result: "gtceu:gabbro_diamond_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/gabbro_diatomite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:gabbro_diatomite_ore"
-  result: "gtceu:gabbro_diatomite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/gabbro_electrotine_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:gabbro_electrotine_ore"
-  result: "gtceu:gabbro_electrotine_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/gabbro_emerald_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:gabbro_emerald_ore"
-  result: "gtceu:gabbro_emerald_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/gabbro_fullers_earth_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:gabbro_fullers_earth_ore"
-  result: "gtceu:gabbro_fullers_earth_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/gabbro_galena_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:gabbro_galena_ore"
-  result: "gtceu:gabbro_galena_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/gabbro_garnet_sand_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:gabbro_garnet_sand_ore"
-  result: "gtceu:gabbro_garnet_sand_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/gabbro_garnierite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:gabbro_garnierite_ore"
-  result: "gtceu:gabbro_garnierite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/gabbro_glauconite_sand_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:gabbro_glauconite_sand_ore"
-  result: "gtceu:gabbro_glauconite_sand_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/gabbro_goethite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:gabbro_goethite_ore"
-  result: "gtceu:gabbro_goethite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/gabbro_gold_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:gabbro_gold_ore"
-  result: "gtceu:gabbro_gold_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/gabbro_granitic_mineral_sand_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:gabbro_granitic_mineral_sand_ore"
-  result: "gtceu:gabbro_granitic_mineral_sand_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/gabbro_graphite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:gabbro_graphite_ore"
-  result: "gtceu:gabbro_graphite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/gabbro_green_sapphire_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:gabbro_green_sapphire_ore"
-  result: "gtceu:gabbro_green_sapphire_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/gabbro_grossular_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:gabbro_grossular_ore"
-  result: "gtceu:gabbro_grossular_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/gabbro_gypsum_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:gabbro_gypsum_ore"
-  result: "gtceu:gabbro_gypsum_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/gabbro_hematite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:gabbro_hematite_ore"
-  result: "gtceu:gabbro_hematite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/gabbro_ilmenite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:gabbro_ilmenite_ore"
-  result: "gtceu:gabbro_ilmenite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/gabbro_iron_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:gabbro_iron_ore"
-  result: "gtceu:gabbro_iron_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/gabbro_kyanite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:gabbro_kyanite_ore"
-  result: "gtceu:gabbro_kyanite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/gabbro_lapis_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:gabbro_lapis_ore"
-  result: "gtceu:gabbro_lapis_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/gabbro_lazurite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:gabbro_lazurite_ore"
-  result: "gtceu:gabbro_lazurite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/gabbro_lead_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:gabbro_lead_ore"
-  result: "gtceu:gabbro_lead_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/gabbro_lepidolite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:gabbro_lepidolite_ore"
-  result: "gtceu:gabbro_lepidolite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/gabbro_lithium_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:gabbro_lithium_ore"
-  result: "gtceu:gabbro_lithium_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/gabbro_magnesite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:gabbro_magnesite_ore"
-  result: "gtceu:gabbro_magnesite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/gabbro_magnetite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:gabbro_magnetite_ore"
-  result: "gtceu:gabbro_magnetite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/gabbro_malachite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:gabbro_malachite_ore"
-  result: "gtceu:gabbro_malachite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/gabbro_mica_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:gabbro_mica_ore"
-  result: "gtceu:gabbro_mica_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/gabbro_molybdenite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:gabbro_molybdenite_ore"
-  result: "gtceu:gabbro_molybdenite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/gabbro_molybdenum_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:gabbro_molybdenum_ore"
-  result: "gtceu:gabbro_molybdenum_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/gabbro_monazite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:gabbro_monazite_ore"
-  result: "gtceu:gabbro_monazite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/gabbro_naquadah_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:gabbro_naquadah_ore"
-  result: "gtceu:gabbro_naquadah_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/gabbro_neodymium_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:gabbro_neodymium_ore"
-  result: "gtceu:gabbro_neodymium_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/gabbro_nether_quartz_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:gabbro_nether_quartz_ore"
-  result: "gtceu:gabbro_nether_quartz_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/gabbro_nickel_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:gabbro_nickel_ore"
-  result: "gtceu:gabbro_nickel_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/gabbro_oilsands_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:gabbro_oilsands_ore"
-  result: "gtceu:gabbro_oilsands_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/gabbro_olivine_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:gabbro_olivine_ore"
-  result: "gtceu:gabbro_olivine_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/gabbro_opal_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:gabbro_opal_ore"
-  result: "gtceu:gabbro_opal_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/gabbro_palladium_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:gabbro_palladium_ore"
-  result: "gtceu:gabbro_palladium_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/gabbro_pentlandite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:gabbro_pentlandite_ore"
-  result: "gtceu:gabbro_pentlandite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/gabbro_pitchblende_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:gabbro_pitchblende_ore"
-  result: "gtceu:gabbro_pitchblende_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/gabbro_platinum_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:gabbro_platinum_ore"
-  result: "gtceu:gabbro_platinum_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/gabbro_plutonium_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:gabbro_plutonium_ore"
-  result: "gtceu:gabbro_plutonium_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/gabbro_pollucite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:gabbro_pollucite_ore"
-  result: "gtceu:gabbro_pollucite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/gabbro_powellite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:gabbro_powellite_ore"
-  result: "gtceu:gabbro_powellite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/gabbro_pyrite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:gabbro_pyrite_ore"
-  result: "gtceu:gabbro_pyrite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/gabbro_pyrochlore_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:gabbro_pyrochlore_ore"
-  result: "gtceu:gabbro_pyrochlore_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/gabbro_pyrolusite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:gabbro_pyrolusite_ore"
-  result: "gtceu:gabbro_pyrolusite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/gabbro_pyrope_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:gabbro_pyrope_ore"
-  result: "gtceu:gabbro_pyrope_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/gabbro_quartzite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:gabbro_quartzite_ore"
-  result: "gtceu:gabbro_quartzite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/gabbro_realgar_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:gabbro_realgar_ore"
-  result: "gtceu:gabbro_realgar_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/gabbro_red_garnet_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:gabbro_red_garnet_ore"
-  result: "gtceu:gabbro_red_garnet_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/gabbro_redstone_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:gabbro_redstone_ore"
-  result: "gtceu:gabbro_redstone_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/gabbro_rock_salt_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:gabbro_rock_salt_ore"
-  result: "gtceu:gabbro_rock_salt_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/gabbro_ruby_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:gabbro_ruby_ore"
-  result: "gtceu:gabbro_ruby_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/gabbro_salt_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:gabbro_salt_ore"
-  result: "gtceu:gabbro_salt_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/gabbro_saltpeter_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:gabbro_saltpeter_ore"
-  result: "gtceu:gabbro_saltpeter_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/gabbro_sapphire_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:gabbro_sapphire_ore"
-  result: "gtceu:gabbro_sapphire_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/gabbro_scheelite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:gabbro_scheelite_ore"
-  result: "gtceu:gabbro_scheelite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/gabbro_silver_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:gabbro_silver_ore"
-  result: "gtceu:gabbro_silver_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/gabbro_soapstone_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:gabbro_soapstone_ore"
-  result: "gtceu:gabbro_soapstone_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/gabbro_sodalite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:gabbro_sodalite_ore"
-  result: "gtceu:gabbro_sodalite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/gabbro_spessartine_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:gabbro_spessartine_ore"
-  result: "gtceu:gabbro_spessartine_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/gabbro_sphalerite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:gabbro_sphalerite_ore"
-  result: "gtceu:gabbro_sphalerite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/gabbro_spodumene_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:gabbro_spodumene_ore"
-  result: "gtceu:gabbro_spodumene_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/gabbro_stibnite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:gabbro_stibnite_ore"
-  result: "gtceu:gabbro_stibnite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/gabbro_sulfur_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:gabbro_sulfur_ore"
-  result: "gtceu:gabbro_sulfur_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/gabbro_talc_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:gabbro_talc_ore"
-  result: "gtceu:gabbro_talc_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/gabbro_tantalite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:gabbro_tantalite_ore"
-  result: "gtceu:gabbro_tantalite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/gabbro_tetrahedrite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:gabbro_tetrahedrite_ore"
-  result: "gtceu:gabbro_tetrahedrite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/gabbro_thorium_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:gabbro_thorium_ore"
-  result: "gtceu:gabbro_thorium_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/gabbro_tin_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:gabbro_tin_ore"
-  result: "gtceu:gabbro_tin_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/gabbro_titanium_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:gabbro_titanium_ore"
-  result: "gtceu:gabbro_titanium_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/gabbro_topaz_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:gabbro_topaz_ore"
-  result: "gtceu:gabbro_topaz_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/gabbro_tricalcium_phosphate_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:gabbro_tricalcium_phosphate_ore"
-  result: "gtceu:gabbro_tricalcium_phosphate_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/gabbro_trona_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:gabbro_trona_ore"
-  result: "gtceu:gabbro_trona_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/gabbro_tungstate_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:gabbro_tungstate_ore"
-  result: "gtceu:gabbro_tungstate_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/gabbro_uraninite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:gabbro_uraninite_ore"
-  result: "gtceu:gabbro_uraninite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/gabbro_vanadium_magnetite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:gabbro_vanadium_magnetite_ore"
-  result: "gtceu:gabbro_vanadium_magnetite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/gabbro_wulfenite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:gabbro_wulfenite_ore"
-  result: "gtceu:gabbro_wulfenite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/gabbro_yellow_garnet_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:gabbro_yellow_garnet_ore"
-  result: "gtceu:gabbro_yellow_garnet_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/gabbro_yellow_limonite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:gabbro_yellow_limonite_ore"
-  result: "gtceu:gabbro_yellow_limonite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/gabbro_zeolite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:gabbro_zeolite_ore"
-  result: "gtceu:gabbro_zeolite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/galena_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:galena_ore"
-  result: "gtceu:galena_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/garnet_sand_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:garnet_sand_ore"
-  result: "gtceu:garnet_sand_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/garnierite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:garnierite_ore"
-  result: "gtceu:garnierite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/glauconite_sand_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:glauconite_sand_ore"
-  result: "gtceu:glauconite_sand_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/gneiss_almandine_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:gneiss_almandine_ore"
-  result: "gtceu:gneiss_almandine_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/gneiss_aluminium_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:gneiss_aluminium_ore"
-  result: "gtceu:gneiss_aluminium_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/gneiss_alunite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:gneiss_alunite_ore"
-  result: "gtceu:gneiss_alunite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/gneiss_amethyst_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:gneiss_amethyst_ore"
-  result: "gtceu:gneiss_amethyst_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/gneiss_apatite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:gneiss_apatite_ore"
-  result: "gtceu:gneiss_apatite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/gneiss_asbestos_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:gneiss_asbestos_ore"
-  result: "gtceu:gneiss_asbestos_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/gneiss_barite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:gneiss_barite_ore"
-  result: "gtceu:gneiss_barite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/gneiss_basaltic_mineral_sand_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:gneiss_basaltic_mineral_sand_ore"
-  result: "gtceu:gneiss_basaltic_mineral_sand_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/gneiss_bastnasite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:gneiss_bastnasite_ore"
-  result: "gtceu:gneiss_bastnasite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/gneiss_bauxite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:gneiss_bauxite_ore"
-  result: "gtceu:gneiss_bauxite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/gneiss_bentonite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:gneiss_bentonite_ore"
-  result: "gtceu:gneiss_bentonite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/gneiss_beryllium_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:gneiss_beryllium_ore"
-  result: "gtceu:gneiss_beryllium_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/gneiss_blue_topaz_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:gneiss_blue_topaz_ore"
-  result: "gtceu:gneiss_blue_topaz_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/gneiss_bornite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:gneiss_bornite_ore"
-  result: "gtceu:gneiss_bornite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/gneiss_calcite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:gneiss_calcite_ore"
-  result: "gtceu:gneiss_calcite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/gneiss_cassiterite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:gneiss_cassiterite_ore"
-  result: "gtceu:gneiss_cassiterite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/gneiss_cassiterite_sand_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:gneiss_cassiterite_sand_ore"
-  result: "gtceu:gneiss_cassiterite_sand_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/gneiss_certus_quartz_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:gneiss_certus_quartz_ore"
-  result: "gtceu:gneiss_certus_quartz_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/gneiss_chalcocite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:gneiss_chalcocite_ore"
-  result: "gtceu:gneiss_chalcocite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/gneiss_chalcopyrite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:gneiss_chalcopyrite_ore"
-  result: "gtceu:gneiss_chalcopyrite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/gneiss_chromite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:gneiss_chromite_ore"
-  result: "gtceu:gneiss_chromite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/gneiss_cinnabar_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:gneiss_cinnabar_ore"
-  result: "gtceu:gneiss_cinnabar_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/gneiss_coal_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:gneiss_coal_ore"
-  result: "gtceu:gneiss_coal_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/gneiss_cobalt_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:gneiss_cobalt_ore"
-  result: "gtceu:gneiss_cobalt_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/gneiss_cobaltite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:gneiss_cobaltite_ore"
-  result: "gtceu:gneiss_cobaltite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/gneiss_cooperite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:gneiss_cooperite_ore"
-  result: "gtceu:gneiss_cooperite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/gneiss_copper_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:gneiss_copper_ore"
-  result: "gtceu:gneiss_copper_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/gneiss_diamond_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:gneiss_diamond_ore"
-  result: "gtceu:gneiss_diamond_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/gneiss_diatomite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:gneiss_diatomite_ore"
-  result: "gtceu:gneiss_diatomite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/gneiss_electrotine_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:gneiss_electrotine_ore"
-  result: "gtceu:gneiss_electrotine_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/gneiss_emerald_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:gneiss_emerald_ore"
-  result: "gtceu:gneiss_emerald_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/gneiss_fullers_earth_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:gneiss_fullers_earth_ore"
-  result: "gtceu:gneiss_fullers_earth_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/gneiss_galena_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:gneiss_galena_ore"
-  result: "gtceu:gneiss_galena_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/gneiss_garnet_sand_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:gneiss_garnet_sand_ore"
-  result: "gtceu:gneiss_garnet_sand_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/gneiss_garnierite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:gneiss_garnierite_ore"
-  result: "gtceu:gneiss_garnierite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/gneiss_glauconite_sand_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:gneiss_glauconite_sand_ore"
-  result: "gtceu:gneiss_glauconite_sand_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/gneiss_goethite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:gneiss_goethite_ore"
-  result: "gtceu:gneiss_goethite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/gneiss_gold_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:gneiss_gold_ore"
-  result: "gtceu:gneiss_gold_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/gneiss_granitic_mineral_sand_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:gneiss_granitic_mineral_sand_ore"
-  result: "gtceu:gneiss_granitic_mineral_sand_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/gneiss_graphite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:gneiss_graphite_ore"
-  result: "gtceu:gneiss_graphite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/gneiss_green_sapphire_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:gneiss_green_sapphire_ore"
-  result: "gtceu:gneiss_green_sapphire_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/gneiss_grossular_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:gneiss_grossular_ore"
-  result: "gtceu:gneiss_grossular_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/gneiss_gypsum_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:gneiss_gypsum_ore"
-  result: "gtceu:gneiss_gypsum_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/gneiss_hematite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:gneiss_hematite_ore"
-  result: "gtceu:gneiss_hematite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/gneiss_ilmenite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:gneiss_ilmenite_ore"
-  result: "gtceu:gneiss_ilmenite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/gneiss_iron_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:gneiss_iron_ore"
-  result: "gtceu:gneiss_iron_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/gneiss_kyanite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:gneiss_kyanite_ore"
-  result: "gtceu:gneiss_kyanite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/gneiss_lapis_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:gneiss_lapis_ore"
-  result: "gtceu:gneiss_lapis_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/gneiss_lazurite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:gneiss_lazurite_ore"
-  result: "gtceu:gneiss_lazurite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/gneiss_lead_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:gneiss_lead_ore"
-  result: "gtceu:gneiss_lead_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/gneiss_lepidolite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:gneiss_lepidolite_ore"
-  result: "gtceu:gneiss_lepidolite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/gneiss_lithium_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:gneiss_lithium_ore"
-  result: "gtceu:gneiss_lithium_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/gneiss_magnesite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:gneiss_magnesite_ore"
-  result: "gtceu:gneiss_magnesite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/gneiss_magnetite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:gneiss_magnetite_ore"
-  result: "gtceu:gneiss_magnetite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/gneiss_malachite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:gneiss_malachite_ore"
-  result: "gtceu:gneiss_malachite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/gneiss_mica_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:gneiss_mica_ore"
-  result: "gtceu:gneiss_mica_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/gneiss_molybdenite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:gneiss_molybdenite_ore"
-  result: "gtceu:gneiss_molybdenite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/gneiss_molybdenum_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:gneiss_molybdenum_ore"
-  result: "gtceu:gneiss_molybdenum_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/gneiss_monazite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:gneiss_monazite_ore"
-  result: "gtceu:gneiss_monazite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/gneiss_naquadah_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:gneiss_naquadah_ore"
-  result: "gtceu:gneiss_naquadah_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/gneiss_neodymium_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:gneiss_neodymium_ore"
-  result: "gtceu:gneiss_neodymium_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/gneiss_nether_quartz_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:gneiss_nether_quartz_ore"
-  result: "gtceu:gneiss_nether_quartz_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/gneiss_nickel_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:gneiss_nickel_ore"
-  result: "gtceu:gneiss_nickel_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/gneiss_oilsands_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:gneiss_oilsands_ore"
-  result: "gtceu:gneiss_oilsands_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/gneiss_olivine_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:gneiss_olivine_ore"
-  result: "gtceu:gneiss_olivine_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/gneiss_opal_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:gneiss_opal_ore"
-  result: "gtceu:gneiss_opal_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/gneiss_palladium_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:gneiss_palladium_ore"
-  result: "gtceu:gneiss_palladium_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/gneiss_pentlandite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:gneiss_pentlandite_ore"
-  result: "gtceu:gneiss_pentlandite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/gneiss_pitchblende_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:gneiss_pitchblende_ore"
-  result: "gtceu:gneiss_pitchblende_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/gneiss_platinum_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:gneiss_platinum_ore"
-  result: "gtceu:gneiss_platinum_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/gneiss_plutonium_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:gneiss_plutonium_ore"
-  result: "gtceu:gneiss_plutonium_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/gneiss_pollucite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:gneiss_pollucite_ore"
-  result: "gtceu:gneiss_pollucite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/gneiss_powellite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:gneiss_powellite_ore"
-  result: "gtceu:gneiss_powellite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/gneiss_pyrite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:gneiss_pyrite_ore"
-  result: "gtceu:gneiss_pyrite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/gneiss_pyrochlore_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:gneiss_pyrochlore_ore"
-  result: "gtceu:gneiss_pyrochlore_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/gneiss_pyrolusite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:gneiss_pyrolusite_ore"
-  result: "gtceu:gneiss_pyrolusite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/gneiss_pyrope_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:gneiss_pyrope_ore"
-  result: "gtceu:gneiss_pyrope_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/gneiss_quartzite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:gneiss_quartzite_ore"
-  result: "gtceu:gneiss_quartzite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/gneiss_realgar_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:gneiss_realgar_ore"
-  result: "gtceu:gneiss_realgar_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/gneiss_red_garnet_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:gneiss_red_garnet_ore"
-  result: "gtceu:gneiss_red_garnet_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/gneiss_redstone_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:gneiss_redstone_ore"
-  result: "gtceu:gneiss_redstone_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/gneiss_rock_salt_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:gneiss_rock_salt_ore"
-  result: "gtceu:gneiss_rock_salt_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/gneiss_ruby_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:gneiss_ruby_ore"
-  result: "gtceu:gneiss_ruby_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/gneiss_salt_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:gneiss_salt_ore"
-  result: "gtceu:gneiss_salt_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/gneiss_saltpeter_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:gneiss_saltpeter_ore"
-  result: "gtceu:gneiss_saltpeter_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/gneiss_sapphire_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:gneiss_sapphire_ore"
-  result: "gtceu:gneiss_sapphire_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/gneiss_scheelite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:gneiss_scheelite_ore"
-  result: "gtceu:gneiss_scheelite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/gneiss_silver_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:gneiss_silver_ore"
-  result: "gtceu:gneiss_silver_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/gneiss_soapstone_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:gneiss_soapstone_ore"
-  result: "gtceu:gneiss_soapstone_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/gneiss_sodalite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:gneiss_sodalite_ore"
-  result: "gtceu:gneiss_sodalite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/gneiss_spessartine_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:gneiss_spessartine_ore"
-  result: "gtceu:gneiss_spessartine_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/gneiss_sphalerite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:gneiss_sphalerite_ore"
-  result: "gtceu:gneiss_sphalerite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/gneiss_spodumene_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:gneiss_spodumene_ore"
-  result: "gtceu:gneiss_spodumene_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/gneiss_stibnite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:gneiss_stibnite_ore"
-  result: "gtceu:gneiss_stibnite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/gneiss_sulfur_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:gneiss_sulfur_ore"
-  result: "gtceu:gneiss_sulfur_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/gneiss_talc_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:gneiss_talc_ore"
-  result: "gtceu:gneiss_talc_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/gneiss_tantalite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:gneiss_tantalite_ore"
-  result: "gtceu:gneiss_tantalite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/gneiss_tetrahedrite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:gneiss_tetrahedrite_ore"
-  result: "gtceu:gneiss_tetrahedrite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/gneiss_thorium_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:gneiss_thorium_ore"
-  result: "gtceu:gneiss_thorium_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/gneiss_tin_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:gneiss_tin_ore"
-  result: "gtceu:gneiss_tin_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/gneiss_titanium_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:gneiss_titanium_ore"
-  result: "gtceu:gneiss_titanium_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/gneiss_topaz_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:gneiss_topaz_ore"
-  result: "gtceu:gneiss_topaz_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/gneiss_tricalcium_phosphate_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:gneiss_tricalcium_phosphate_ore"
-  result: "gtceu:gneiss_tricalcium_phosphate_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/gneiss_trona_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:gneiss_trona_ore"
-  result: "gtceu:gneiss_trona_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/gneiss_tungstate_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:gneiss_tungstate_ore"
-  result: "gtceu:gneiss_tungstate_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/gneiss_uraninite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:gneiss_uraninite_ore"
-  result: "gtceu:gneiss_uraninite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/gneiss_vanadium_magnetite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:gneiss_vanadium_magnetite_ore"
-  result: "gtceu:gneiss_vanadium_magnetite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/gneiss_wulfenite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:gneiss_wulfenite_ore"
-  result: "gtceu:gneiss_wulfenite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/gneiss_yellow_garnet_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:gneiss_yellow_garnet_ore"
-  result: "gtceu:gneiss_yellow_garnet_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/gneiss_yellow_limonite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:gneiss_yellow_limonite_ore"
-  result: "gtceu:gneiss_yellow_limonite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/gneiss_zeolite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:gneiss_zeolite_ore"
-  result: "gtceu:gneiss_zeolite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/goethite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:goethite_ore"
-  result: "gtceu:goethite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/gold_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:gold_ore"
-  result: "gtceu:gold_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/granite_almandine_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:granite_almandine_ore"
-  result: "gtceu:granite_almandine_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/granite_aluminium_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:granite_aluminium_ore"
-  result: "gtceu:granite_aluminium_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/granite_alunite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:granite_alunite_ore"
-  result: "gtceu:granite_alunite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/granite_amethyst_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:granite_amethyst_ore"
-  result: "gtceu:granite_amethyst_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/granite_apatite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:granite_apatite_ore"
-  result: "gtceu:granite_apatite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/granite_asbestos_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:granite_asbestos_ore"
-  result: "gtceu:granite_asbestos_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/granite_barite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:granite_barite_ore"
-  result: "gtceu:granite_barite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/granite_basaltic_mineral_sand_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:granite_basaltic_mineral_sand_ore"
-  result: "gtceu:granite_basaltic_mineral_sand_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/granite_bastnasite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:granite_bastnasite_ore"
-  result: "gtceu:granite_bastnasite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/granite_bauxite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:granite_bauxite_ore"
-  result: "gtceu:granite_bauxite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/granite_bentonite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:granite_bentonite_ore"
-  result: "gtceu:granite_bentonite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/granite_beryllium_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:granite_beryllium_ore"
-  result: "gtceu:granite_beryllium_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/granite_blue_topaz_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:granite_blue_topaz_ore"
-  result: "gtceu:granite_blue_topaz_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/granite_bornite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:granite_bornite_ore"
-  result: "gtceu:granite_bornite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/granite_calcite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:granite_calcite_ore"
-  result: "gtceu:granite_calcite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/granite_cassiterite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:granite_cassiterite_ore"
-  result: "gtceu:granite_cassiterite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/granite_cassiterite_sand_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:granite_cassiterite_sand_ore"
-  result: "gtceu:granite_cassiterite_sand_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/granite_certus_quartz_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:granite_certus_quartz_ore"
-  result: "gtceu:granite_certus_quartz_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/granite_chalcocite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:granite_chalcocite_ore"
-  result: "gtceu:granite_chalcocite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/granite_chalcopyrite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:granite_chalcopyrite_ore"
-  result: "gtceu:granite_chalcopyrite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/granite_chromite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:granite_chromite_ore"
-  result: "gtceu:granite_chromite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/granite_cinnabar_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:granite_cinnabar_ore"
-  result: "gtceu:granite_cinnabar_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/granite_coal_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:granite_coal_ore"
-  result: "gtceu:granite_coal_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/granite_cobalt_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:granite_cobalt_ore"
-  result: "gtceu:granite_cobalt_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/granite_cobaltite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:granite_cobaltite_ore"
-  result: "gtceu:granite_cobaltite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/granite_cooperite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:granite_cooperite_ore"
-  result: "gtceu:granite_cooperite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/granite_copper_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:granite_copper_ore"
-  result: "gtceu:granite_copper_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/granite_diamond_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:granite_diamond_ore"
-  result: "gtceu:granite_diamond_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/granite_diatomite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:granite_diatomite_ore"
-  result: "gtceu:granite_diatomite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/granite_electrotine_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:granite_electrotine_ore"
-  result: "gtceu:granite_electrotine_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/granite_emerald_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:granite_emerald_ore"
-  result: "gtceu:granite_emerald_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/granite_fullers_earth_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:granite_fullers_earth_ore"
-  result: "gtceu:granite_fullers_earth_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/granite_galena_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:granite_galena_ore"
-  result: "gtceu:granite_galena_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/granite_garnet_sand_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:granite_garnet_sand_ore"
-  result: "gtceu:granite_garnet_sand_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/granite_garnierite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:granite_garnierite_ore"
-  result: "gtceu:granite_garnierite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/granite_glauconite_sand_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:granite_glauconite_sand_ore"
-  result: "gtceu:granite_glauconite_sand_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/granite_goethite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:granite_goethite_ore"
-  result: "gtceu:granite_goethite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/granite_gold_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:granite_gold_ore"
-  result: "gtceu:granite_gold_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/granite_granitic_mineral_sand_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:granite_granitic_mineral_sand_ore"
-  result: "gtceu:granite_granitic_mineral_sand_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/granite_graphite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:granite_graphite_ore"
-  result: "gtceu:granite_graphite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/granite_green_sapphire_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:granite_green_sapphire_ore"
-  result: "gtceu:granite_green_sapphire_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/granite_grossular_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:granite_grossular_ore"
-  result: "gtceu:granite_grossular_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/granite_gypsum_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:granite_gypsum_ore"
-  result: "gtceu:granite_gypsum_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/granite_hematite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:granite_hematite_ore"
-  result: "gtceu:granite_hematite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/granite_ilmenite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:granite_ilmenite_ore"
-  result: "gtceu:granite_ilmenite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/granite_iron_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:granite_iron_ore"
-  result: "gtceu:granite_iron_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/granite_kyanite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:granite_kyanite_ore"
-  result: "gtceu:granite_kyanite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/granite_lapis_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:granite_lapis_ore"
-  result: "gtceu:granite_lapis_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/granite_lazurite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:granite_lazurite_ore"
-  result: "gtceu:granite_lazurite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/granite_lead_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:granite_lead_ore"
-  result: "gtceu:granite_lead_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/granite_lepidolite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:granite_lepidolite_ore"
-  result: "gtceu:granite_lepidolite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/granite_lithium_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:granite_lithium_ore"
-  result: "gtceu:granite_lithium_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/granite_magnesite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:granite_magnesite_ore"
-  result: "gtceu:granite_magnesite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/granite_magnetite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:granite_magnetite_ore"
-  result: "gtceu:granite_magnetite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/granite_malachite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:granite_malachite_ore"
-  result: "gtceu:granite_malachite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/granite_mica_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:granite_mica_ore"
-  result: "gtceu:granite_mica_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/granite_molybdenite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:granite_molybdenite_ore"
-  result: "gtceu:granite_molybdenite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/granite_molybdenum_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:granite_molybdenum_ore"
-  result: "gtceu:granite_molybdenum_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/granite_monazite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:granite_monazite_ore"
-  result: "gtceu:granite_monazite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/granite_naquadah_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:granite_naquadah_ore"
-  result: "gtceu:granite_naquadah_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/granite_neodymium_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:granite_neodymium_ore"
-  result: "gtceu:granite_neodymium_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/granite_nether_quartz_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:granite_nether_quartz_ore"
-  result: "gtceu:granite_nether_quartz_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/granite_nickel_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:granite_nickel_ore"
-  result: "gtceu:granite_nickel_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/granite_oilsands_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:granite_oilsands_ore"
-  result: "gtceu:granite_oilsands_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/granite_olivine_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:granite_olivine_ore"
-  result: "gtceu:granite_olivine_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/granite_opal_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:granite_opal_ore"
-  result: "gtceu:granite_opal_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/granite_palladium_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:granite_palladium_ore"
-  result: "gtceu:granite_palladium_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/granite_pentlandite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:granite_pentlandite_ore"
-  result: "gtceu:granite_pentlandite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/granite_pitchblende_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:granite_pitchblende_ore"
-  result: "gtceu:granite_pitchblende_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/granite_platinum_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:granite_platinum_ore"
-  result: "gtceu:granite_platinum_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/granite_plutonium_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:granite_plutonium_ore"
-  result: "gtceu:granite_plutonium_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/granite_pollucite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:granite_pollucite_ore"
-  result: "gtceu:granite_pollucite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/granite_powellite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:granite_powellite_ore"
-  result: "gtceu:granite_powellite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/granite_pyrite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:granite_pyrite_ore"
-  result: "gtceu:granite_pyrite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/granite_pyrochlore_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:granite_pyrochlore_ore"
-  result: "gtceu:granite_pyrochlore_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/granite_pyrolusite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:granite_pyrolusite_ore"
-  result: "gtceu:granite_pyrolusite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/granite_pyrope_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:granite_pyrope_ore"
-  result: "gtceu:granite_pyrope_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/granite_quartzite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:granite_quartzite_ore"
-  result: "gtceu:granite_quartzite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/granite_realgar_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:granite_realgar_ore"
-  result: "gtceu:granite_realgar_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/granite_red_garnet_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:granite_red_garnet_ore"
-  result: "gtceu:granite_red_garnet_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/granite_redstone_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:granite_redstone_ore"
-  result: "gtceu:granite_redstone_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/granite_rock_salt_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:granite_rock_salt_ore"
-  result: "gtceu:granite_rock_salt_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/granite_ruby_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:granite_ruby_ore"
-  result: "gtceu:granite_ruby_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/granite_salt_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:granite_salt_ore"
-  result: "gtceu:granite_salt_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/granite_saltpeter_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:granite_saltpeter_ore"
-  result: "gtceu:granite_saltpeter_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/granite_sapphire_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:granite_sapphire_ore"
-  result: "gtceu:granite_sapphire_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/granite_scheelite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:granite_scheelite_ore"
-  result: "gtceu:granite_scheelite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/granite_silver_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:granite_silver_ore"
-  result: "gtceu:granite_silver_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/granite_soapstone_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:granite_soapstone_ore"
-  result: "gtceu:granite_soapstone_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/granite_sodalite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:granite_sodalite_ore"
-  result: "gtceu:granite_sodalite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/granite_spessartine_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:granite_spessartine_ore"
-  result: "gtceu:granite_spessartine_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/granite_sphalerite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:granite_sphalerite_ore"
-  result: "gtceu:granite_sphalerite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/granite_spodumene_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:granite_spodumene_ore"
-  result: "gtceu:granite_spodumene_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/granite_stibnite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:granite_stibnite_ore"
-  result: "gtceu:granite_stibnite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/granite_sulfur_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:granite_sulfur_ore"
-  result: "gtceu:granite_sulfur_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/granite_talc_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:granite_talc_ore"
-  result: "gtceu:granite_talc_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/granite_tantalite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:granite_tantalite_ore"
-  result: "gtceu:granite_tantalite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/granite_tetrahedrite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:granite_tetrahedrite_ore"
-  result: "gtceu:granite_tetrahedrite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/granite_thorium_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:granite_thorium_ore"
-  result: "gtceu:granite_thorium_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/granite_tin_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:granite_tin_ore"
-  result: "gtceu:granite_tin_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/granite_titanium_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:granite_titanium_ore"
-  result: "gtceu:granite_titanium_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/granite_topaz_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:granite_topaz_ore"
-  result: "gtceu:granite_topaz_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/granite_tricalcium_phosphate_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:granite_tricalcium_phosphate_ore"
-  result: "gtceu:granite_tricalcium_phosphate_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/granite_trona_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:granite_trona_ore"
-  result: "gtceu:granite_trona_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/granite_tungstate_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:granite_tungstate_ore"
-  result: "gtceu:granite_tungstate_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/granite_uraninite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:granite_uraninite_ore"
-  result: "gtceu:granite_uraninite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/granite_vanadium_magnetite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:granite_vanadium_magnetite_ore"
-  result: "gtceu:granite_vanadium_magnetite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/granite_wulfenite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:granite_wulfenite_ore"
-  result: "gtceu:granite_wulfenite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/granite_yellow_garnet_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:granite_yellow_garnet_ore"
-  result: "gtceu:granite_yellow_garnet_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/granite_yellow_limonite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:granite_yellow_limonite_ore"
-  result: "gtceu:granite_yellow_limonite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/granite_zeolite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:granite_zeolite_ore"
-  result: "gtceu:granite_zeolite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/granitic_mineral_sand_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:granitic_mineral_sand_ore"
-  result: "gtceu:granitic_mineral_sand_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/graphite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:graphite_ore"
-  result: "gtceu:graphite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/green_sapphire_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:green_sapphire_ore"
-  result: "gtceu:green_sapphire_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/grossular_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:grossular_ore"
-  result: "gtceu:grossular_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/gypsum_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:gypsum_ore"
-  result: "gtceu:gypsum_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/hematite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:hematite_ore"
-  result: "gtceu:hematite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/ilmenite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:ilmenite_ore"
-  result: "gtceu:ilmenite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/iron_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:iron_ore"
-  result: "gtceu:iron_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/kyanite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:kyanite_ore"
-  result: "gtceu:kyanite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/lapis_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:lapis_ore"
-  result: "gtceu:lapis_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/lazurite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:lazurite_ore"
-  result: "gtceu:lazurite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/lead_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:lead_ore"
-  result: "gtceu:lead_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/lepidolite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:lepidolite_ore"
-  result: "gtceu:lepidolite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/limestone_almandine_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:limestone_almandine_ore"
-  result: "gtceu:limestone_almandine_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/limestone_aluminium_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:limestone_aluminium_ore"
-  result: "gtceu:limestone_aluminium_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/limestone_alunite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:limestone_alunite_ore"
-  result: "gtceu:limestone_alunite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/limestone_amethyst_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:limestone_amethyst_ore"
-  result: "gtceu:limestone_amethyst_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/limestone_apatite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:limestone_apatite_ore"
-  result: "gtceu:limestone_apatite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/limestone_asbestos_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:limestone_asbestos_ore"
-  result: "gtceu:limestone_asbestos_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/limestone_barite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:limestone_barite_ore"
-  result: "gtceu:limestone_barite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/limestone_basaltic_mineral_sand_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:limestone_basaltic_mineral_sand_ore"
-  result: "gtceu:limestone_basaltic_mineral_sand_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/limestone_bastnasite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:limestone_bastnasite_ore"
-  result: "gtceu:limestone_bastnasite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/limestone_bauxite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:limestone_bauxite_ore"
-  result: "gtceu:limestone_bauxite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/limestone_bentonite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:limestone_bentonite_ore"
-  result: "gtceu:limestone_bentonite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/limestone_beryllium_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:limestone_beryllium_ore"
-  result: "gtceu:limestone_beryllium_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/limestone_blue_topaz_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:limestone_blue_topaz_ore"
-  result: "gtceu:limestone_blue_topaz_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/limestone_bornite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:limestone_bornite_ore"
-  result: "gtceu:limestone_bornite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/limestone_calcite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:limestone_calcite_ore"
-  result: "gtceu:limestone_calcite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/limestone_cassiterite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:limestone_cassiterite_ore"
-  result: "gtceu:limestone_cassiterite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/limestone_cassiterite_sand_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:limestone_cassiterite_sand_ore"
-  result: "gtceu:limestone_cassiterite_sand_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/limestone_certus_quartz_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:limestone_certus_quartz_ore"
-  result: "gtceu:limestone_certus_quartz_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/limestone_chalcocite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:limestone_chalcocite_ore"
-  result: "gtceu:limestone_chalcocite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/limestone_chalcopyrite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:limestone_chalcopyrite_ore"
-  result: "gtceu:limestone_chalcopyrite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/limestone_chromite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:limestone_chromite_ore"
-  result: "gtceu:limestone_chromite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/limestone_cinnabar_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:limestone_cinnabar_ore"
-  result: "gtceu:limestone_cinnabar_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/limestone_coal_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:limestone_coal_ore"
-  result: "gtceu:limestone_coal_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/limestone_cobalt_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:limestone_cobalt_ore"
-  result: "gtceu:limestone_cobalt_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/limestone_cobaltite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:limestone_cobaltite_ore"
-  result: "gtceu:limestone_cobaltite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/limestone_cooperite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:limestone_cooperite_ore"
-  result: "gtceu:limestone_cooperite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/limestone_copper_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:limestone_copper_ore"
-  result: "gtceu:limestone_copper_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/limestone_diamond_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:limestone_diamond_ore"
-  result: "gtceu:limestone_diamond_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/limestone_diatomite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:limestone_diatomite_ore"
-  result: "gtceu:limestone_diatomite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/limestone_electrotine_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:limestone_electrotine_ore"
-  result: "gtceu:limestone_electrotine_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/limestone_emerald_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:limestone_emerald_ore"
-  result: "gtceu:limestone_emerald_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/limestone_fullers_earth_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:limestone_fullers_earth_ore"
-  result: "gtceu:limestone_fullers_earth_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/limestone_galena_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:limestone_galena_ore"
-  result: "gtceu:limestone_galena_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/limestone_garnet_sand_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:limestone_garnet_sand_ore"
-  result: "gtceu:limestone_garnet_sand_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/limestone_garnierite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:limestone_garnierite_ore"
-  result: "gtceu:limestone_garnierite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/limestone_glauconite_sand_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:limestone_glauconite_sand_ore"
-  result: "gtceu:limestone_glauconite_sand_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/limestone_goethite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:limestone_goethite_ore"
-  result: "gtceu:limestone_goethite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/limestone_gold_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:limestone_gold_ore"
-  result: "gtceu:limestone_gold_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/limestone_granitic_mineral_sand_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:limestone_granitic_mineral_sand_ore"
-  result: "gtceu:limestone_granitic_mineral_sand_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/limestone_graphite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:limestone_graphite_ore"
-  result: "gtceu:limestone_graphite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/limestone_green_sapphire_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:limestone_green_sapphire_ore"
-  result: "gtceu:limestone_green_sapphire_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/limestone_grossular_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:limestone_grossular_ore"
-  result: "gtceu:limestone_grossular_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/limestone_gypsum_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:limestone_gypsum_ore"
-  result: "gtceu:limestone_gypsum_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/limestone_hematite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:limestone_hematite_ore"
-  result: "gtceu:limestone_hematite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/limestone_ilmenite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:limestone_ilmenite_ore"
-  result: "gtceu:limestone_ilmenite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/limestone_iron_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:limestone_iron_ore"
-  result: "gtceu:limestone_iron_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/limestone_kyanite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:limestone_kyanite_ore"
-  result: "gtceu:limestone_kyanite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/limestone_lapis_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:limestone_lapis_ore"
-  result: "gtceu:limestone_lapis_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/limestone_lazurite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:limestone_lazurite_ore"
-  result: "gtceu:limestone_lazurite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/limestone_lead_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:limestone_lead_ore"
-  result: "gtceu:limestone_lead_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/limestone_lepidolite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:limestone_lepidolite_ore"
-  result: "gtceu:limestone_lepidolite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/limestone_lithium_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:limestone_lithium_ore"
-  result: "gtceu:limestone_lithium_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/limestone_magnesite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:limestone_magnesite_ore"
-  result: "gtceu:limestone_magnesite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/limestone_magnetite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:limestone_magnetite_ore"
-  result: "gtceu:limestone_magnetite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/limestone_malachite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:limestone_malachite_ore"
-  result: "gtceu:limestone_malachite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/limestone_mica_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:limestone_mica_ore"
-  result: "gtceu:limestone_mica_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/limestone_molybdenite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:limestone_molybdenite_ore"
-  result: "gtceu:limestone_molybdenite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/limestone_molybdenum_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:limestone_molybdenum_ore"
-  result: "gtceu:limestone_molybdenum_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/limestone_monazite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:limestone_monazite_ore"
-  result: "gtceu:limestone_monazite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/limestone_naquadah_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:limestone_naquadah_ore"
-  result: "gtceu:limestone_naquadah_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/limestone_neodymium_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:limestone_neodymium_ore"
-  result: "gtceu:limestone_neodymium_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/limestone_nether_quartz_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:limestone_nether_quartz_ore"
-  result: "gtceu:limestone_nether_quartz_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/limestone_nickel_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:limestone_nickel_ore"
-  result: "gtceu:limestone_nickel_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/limestone_oilsands_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:limestone_oilsands_ore"
-  result: "gtceu:limestone_oilsands_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/limestone_olivine_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:limestone_olivine_ore"
-  result: "gtceu:limestone_olivine_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/limestone_opal_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:limestone_opal_ore"
-  result: "gtceu:limestone_opal_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/limestone_palladium_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:limestone_palladium_ore"
-  result: "gtceu:limestone_palladium_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/limestone_pentlandite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:limestone_pentlandite_ore"
-  result: "gtceu:limestone_pentlandite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/limestone_pitchblende_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:limestone_pitchblende_ore"
-  result: "gtceu:limestone_pitchblende_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/limestone_platinum_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:limestone_platinum_ore"
-  result: "gtceu:limestone_platinum_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/limestone_plutonium_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:limestone_plutonium_ore"
-  result: "gtceu:limestone_plutonium_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/limestone_pollucite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:limestone_pollucite_ore"
-  result: "gtceu:limestone_pollucite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/limestone_powellite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:limestone_powellite_ore"
-  result: "gtceu:limestone_powellite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/limestone_pyrite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:limestone_pyrite_ore"
-  result: "gtceu:limestone_pyrite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/limestone_pyrochlore_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:limestone_pyrochlore_ore"
-  result: "gtceu:limestone_pyrochlore_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/limestone_pyrolusite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:limestone_pyrolusite_ore"
-  result: "gtceu:limestone_pyrolusite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/limestone_pyrope_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:limestone_pyrope_ore"
-  result: "gtceu:limestone_pyrope_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/limestone_quartzite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:limestone_quartzite_ore"
-  result: "gtceu:limestone_quartzite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/limestone_realgar_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:limestone_realgar_ore"
-  result: "gtceu:limestone_realgar_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/limestone_red_garnet_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:limestone_red_garnet_ore"
-  result: "gtceu:limestone_red_garnet_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/limestone_redstone_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:limestone_redstone_ore"
-  result: "gtceu:limestone_redstone_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/limestone_rock_salt_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:limestone_rock_salt_ore"
-  result: "gtceu:limestone_rock_salt_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/limestone_ruby_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:limestone_ruby_ore"
-  result: "gtceu:limestone_ruby_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/limestone_salt_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:limestone_salt_ore"
-  result: "gtceu:limestone_salt_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/limestone_saltpeter_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:limestone_saltpeter_ore"
-  result: "gtceu:limestone_saltpeter_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/limestone_sapphire_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:limestone_sapphire_ore"
-  result: "gtceu:limestone_sapphire_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/limestone_scheelite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:limestone_scheelite_ore"
-  result: "gtceu:limestone_scheelite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/limestone_silver_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:limestone_silver_ore"
-  result: "gtceu:limestone_silver_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/limestone_soapstone_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:limestone_soapstone_ore"
-  result: "gtceu:limestone_soapstone_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/limestone_sodalite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:limestone_sodalite_ore"
-  result: "gtceu:limestone_sodalite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/limestone_spessartine_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:limestone_spessartine_ore"
-  result: "gtceu:limestone_spessartine_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/limestone_sphalerite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:limestone_sphalerite_ore"
-  result: "gtceu:limestone_sphalerite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/limestone_spodumene_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:limestone_spodumene_ore"
-  result: "gtceu:limestone_spodumene_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/limestone_stibnite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:limestone_stibnite_ore"
-  result: "gtceu:limestone_stibnite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/limestone_sulfur_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:limestone_sulfur_ore"
-  result: "gtceu:limestone_sulfur_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/limestone_talc_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:limestone_talc_ore"
-  result: "gtceu:limestone_talc_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/limestone_tantalite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:limestone_tantalite_ore"
-  result: "gtceu:limestone_tantalite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/limestone_tetrahedrite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:limestone_tetrahedrite_ore"
-  result: "gtceu:limestone_tetrahedrite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/limestone_thorium_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:limestone_thorium_ore"
-  result: "gtceu:limestone_thorium_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/limestone_tin_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:limestone_tin_ore"
-  result: "gtceu:limestone_tin_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/limestone_titanium_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:limestone_titanium_ore"
-  result: "gtceu:limestone_titanium_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/limestone_topaz_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:limestone_topaz_ore"
-  result: "gtceu:limestone_topaz_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/limestone_tricalcium_phosphate_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:limestone_tricalcium_phosphate_ore"
-  result: "gtceu:limestone_tricalcium_phosphate_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/limestone_trona_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:limestone_trona_ore"
-  result: "gtceu:limestone_trona_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/limestone_tungstate_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:limestone_tungstate_ore"
-  result: "gtceu:limestone_tungstate_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/limestone_uraninite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:limestone_uraninite_ore"
-  result: "gtceu:limestone_uraninite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/limestone_vanadium_magnetite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:limestone_vanadium_magnetite_ore"
-  result: "gtceu:limestone_vanadium_magnetite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/limestone_wulfenite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:limestone_wulfenite_ore"
-  result: "gtceu:limestone_wulfenite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/limestone_yellow_garnet_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:limestone_yellow_garnet_ore"
-  result: "gtceu:limestone_yellow_garnet_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/limestone_yellow_limonite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:limestone_yellow_limonite_ore"
-  result: "gtceu:limestone_yellow_limonite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/limestone_zeolite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:limestone_zeolite_ore"
-  result: "gtceu:limestone_zeolite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/lithium_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:lithium_ore"
-  result: "gtceu:lithium_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/magnesite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:magnesite_ore"
-  result: "gtceu:magnesite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/magnetite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:magnetite_ore"
-  result: "gtceu:magnetite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/malachite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:malachite_ore"
-  result: "gtceu:malachite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/marble_almandine_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:marble_almandine_ore"
-  result: "gtceu:marble_almandine_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/marble_aluminium_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:marble_aluminium_ore"
-  result: "gtceu:marble_aluminium_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/marble_alunite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:marble_alunite_ore"
-  result: "gtceu:marble_alunite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/marble_amethyst_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:marble_amethyst_ore"
-  result: "gtceu:marble_amethyst_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/marble_apatite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:marble_apatite_ore"
-  result: "gtceu:marble_apatite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/marble_asbestos_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:marble_asbestos_ore"
-  result: "gtceu:marble_asbestos_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/marble_barite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:marble_barite_ore"
-  result: "gtceu:marble_barite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/marble_basaltic_mineral_sand_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:marble_basaltic_mineral_sand_ore"
-  result: "gtceu:marble_basaltic_mineral_sand_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/marble_bastnasite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:marble_bastnasite_ore"
-  result: "gtceu:marble_bastnasite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/marble_bauxite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:marble_bauxite_ore"
-  result: "gtceu:marble_bauxite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/marble_bentonite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:marble_bentonite_ore"
-  result: "gtceu:marble_bentonite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/marble_beryllium_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:marble_beryllium_ore"
-  result: "gtceu:marble_beryllium_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/marble_blue_topaz_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:marble_blue_topaz_ore"
-  result: "gtceu:marble_blue_topaz_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/marble_bornite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:marble_bornite_ore"
-  result: "gtceu:marble_bornite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/marble_calcite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:marble_calcite_ore"
-  result: "gtceu:marble_calcite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/marble_cassiterite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:marble_cassiterite_ore"
-  result: "gtceu:marble_cassiterite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/marble_cassiterite_sand_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:marble_cassiterite_sand_ore"
-  result: "gtceu:marble_cassiterite_sand_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/marble_certus_quartz_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:marble_certus_quartz_ore"
-  result: "gtceu:marble_certus_quartz_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/marble_chalcocite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:marble_chalcocite_ore"
-  result: "gtceu:marble_chalcocite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/marble_chalcopyrite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:marble_chalcopyrite_ore"
-  result: "gtceu:marble_chalcopyrite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/marble_chromite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:marble_chromite_ore"
-  result: "gtceu:marble_chromite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/marble_cinnabar_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:marble_cinnabar_ore"
-  result: "gtceu:marble_cinnabar_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/marble_coal_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:marble_coal_ore"
-  result: "gtceu:marble_coal_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/marble_cobalt_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:marble_cobalt_ore"
-  result: "gtceu:marble_cobalt_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/marble_cobaltite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:marble_cobaltite_ore"
-  result: "gtceu:marble_cobaltite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/marble_cooperite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:marble_cooperite_ore"
-  result: "gtceu:marble_cooperite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/marble_copper_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:marble_copper_ore"
-  result: "gtceu:marble_copper_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/marble_diamond_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:marble_diamond_ore"
-  result: "gtceu:marble_diamond_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/marble_diatomite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:marble_diatomite_ore"
-  result: "gtceu:marble_diatomite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/marble_electrotine_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:marble_electrotine_ore"
-  result: "gtceu:marble_electrotine_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/marble_emerald_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:marble_emerald_ore"
-  result: "gtceu:marble_emerald_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/marble_fullers_earth_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:marble_fullers_earth_ore"
-  result: "gtceu:marble_fullers_earth_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/marble_galena_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:marble_galena_ore"
-  result: "gtceu:marble_galena_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/marble_garnet_sand_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:marble_garnet_sand_ore"
-  result: "gtceu:marble_garnet_sand_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/marble_garnierite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:marble_garnierite_ore"
-  result: "gtceu:marble_garnierite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/marble_glauconite_sand_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:marble_glauconite_sand_ore"
-  result: "gtceu:marble_glauconite_sand_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/marble_goethite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:marble_goethite_ore"
-  result: "gtceu:marble_goethite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/marble_gold_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:marble_gold_ore"
-  result: "gtceu:marble_gold_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/marble_granitic_mineral_sand_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:marble_granitic_mineral_sand_ore"
-  result: "gtceu:marble_granitic_mineral_sand_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/marble_graphite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:marble_graphite_ore"
-  result: "gtceu:marble_graphite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/marble_green_sapphire_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:marble_green_sapphire_ore"
-  result: "gtceu:marble_green_sapphire_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/marble_grossular_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:marble_grossular_ore"
-  result: "gtceu:marble_grossular_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/marble_gypsum_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:marble_gypsum_ore"
-  result: "gtceu:marble_gypsum_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/marble_hematite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:marble_hematite_ore"
-  result: "gtceu:marble_hematite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/marble_ilmenite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:marble_ilmenite_ore"
-  result: "gtceu:marble_ilmenite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/marble_iron_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:marble_iron_ore"
-  result: "gtceu:marble_iron_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/marble_kyanite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:marble_kyanite_ore"
-  result: "gtceu:marble_kyanite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/marble_lapis_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:marble_lapis_ore"
-  result: "gtceu:marble_lapis_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/marble_lazurite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:marble_lazurite_ore"
-  result: "gtceu:marble_lazurite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/marble_lead_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:marble_lead_ore"
-  result: "gtceu:marble_lead_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/marble_lepidolite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:marble_lepidolite_ore"
-  result: "gtceu:marble_lepidolite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/marble_lithium_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:marble_lithium_ore"
-  result: "gtceu:marble_lithium_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/marble_magnesite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:marble_magnesite_ore"
-  result: "gtceu:marble_magnesite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/marble_magnetite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:marble_magnetite_ore"
-  result: "gtceu:marble_magnetite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/marble_malachite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:marble_malachite_ore"
-  result: "gtceu:marble_malachite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/marble_mica_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:marble_mica_ore"
-  result: "gtceu:marble_mica_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/marble_molybdenite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:marble_molybdenite_ore"
-  result: "gtceu:marble_molybdenite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/marble_molybdenum_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:marble_molybdenum_ore"
-  result: "gtceu:marble_molybdenum_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/marble_monazite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:marble_monazite_ore"
-  result: "gtceu:marble_monazite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/marble_naquadah_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:marble_naquadah_ore"
-  result: "gtceu:marble_naquadah_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/marble_neodymium_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:marble_neodymium_ore"
-  result: "gtceu:marble_neodymium_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/marble_nether_quartz_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:marble_nether_quartz_ore"
-  result: "gtceu:marble_nether_quartz_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/marble_nickel_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:marble_nickel_ore"
-  result: "gtceu:marble_nickel_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/marble_oilsands_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:marble_oilsands_ore"
-  result: "gtceu:marble_oilsands_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/marble_olivine_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:marble_olivine_ore"
-  result: "gtceu:marble_olivine_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/marble_opal_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:marble_opal_ore"
-  result: "gtceu:marble_opal_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/marble_palladium_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:marble_palladium_ore"
-  result: "gtceu:marble_palladium_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/marble_pentlandite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:marble_pentlandite_ore"
-  result: "gtceu:marble_pentlandite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/marble_pitchblende_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:marble_pitchblende_ore"
-  result: "gtceu:marble_pitchblende_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/marble_platinum_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:marble_platinum_ore"
-  result: "gtceu:marble_platinum_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/marble_plutonium_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:marble_plutonium_ore"
-  result: "gtceu:marble_plutonium_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/marble_pollucite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:marble_pollucite_ore"
-  result: "gtceu:marble_pollucite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/marble_powellite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:marble_powellite_ore"
-  result: "gtceu:marble_powellite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/marble_pyrite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:marble_pyrite_ore"
-  result: "gtceu:marble_pyrite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/marble_pyrochlore_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:marble_pyrochlore_ore"
-  result: "gtceu:marble_pyrochlore_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/marble_pyrolusite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:marble_pyrolusite_ore"
-  result: "gtceu:marble_pyrolusite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/marble_pyrope_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:marble_pyrope_ore"
-  result: "gtceu:marble_pyrope_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/marble_quartzite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:marble_quartzite_ore"
-  result: "gtceu:marble_quartzite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/marble_realgar_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:marble_realgar_ore"
-  result: "gtceu:marble_realgar_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/marble_red_garnet_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:marble_red_garnet_ore"
-  result: "gtceu:marble_red_garnet_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/marble_redstone_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:marble_redstone_ore"
-  result: "gtceu:marble_redstone_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/marble_rock_salt_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:marble_rock_salt_ore"
-  result: "gtceu:marble_rock_salt_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/marble_ruby_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:marble_ruby_ore"
-  result: "gtceu:marble_ruby_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/marble_salt_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:marble_salt_ore"
-  result: "gtceu:marble_salt_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/marble_saltpeter_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:marble_saltpeter_ore"
-  result: "gtceu:marble_saltpeter_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/marble_sapphire_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:marble_sapphire_ore"
-  result: "gtceu:marble_sapphire_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/marble_scheelite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:marble_scheelite_ore"
-  result: "gtceu:marble_scheelite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/marble_silver_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:marble_silver_ore"
-  result: "gtceu:marble_silver_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/marble_soapstone_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:marble_soapstone_ore"
-  result: "gtceu:marble_soapstone_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/marble_sodalite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:marble_sodalite_ore"
-  result: "gtceu:marble_sodalite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/marble_spessartine_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:marble_spessartine_ore"
-  result: "gtceu:marble_spessartine_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/marble_sphalerite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:marble_sphalerite_ore"
-  result: "gtceu:marble_sphalerite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/marble_spodumene_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:marble_spodumene_ore"
-  result: "gtceu:marble_spodumene_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/marble_stibnite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:marble_stibnite_ore"
-  result: "gtceu:marble_stibnite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/marble_sulfur_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:marble_sulfur_ore"
-  result: "gtceu:marble_sulfur_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/marble_talc_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:marble_talc_ore"
-  result: "gtceu:marble_talc_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/marble_tantalite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:marble_tantalite_ore"
-  result: "gtceu:marble_tantalite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/marble_tetrahedrite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:marble_tetrahedrite_ore"
-  result: "gtceu:marble_tetrahedrite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/marble_thorium_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:marble_thorium_ore"
-  result: "gtceu:marble_thorium_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/marble_tin_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:marble_tin_ore"
-  result: "gtceu:marble_tin_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/marble_titanium_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:marble_titanium_ore"
-  result: "gtceu:marble_titanium_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/marble_topaz_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:marble_topaz_ore"
-  result: "gtceu:marble_topaz_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/marble_tricalcium_phosphate_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:marble_tricalcium_phosphate_ore"
-  result: "gtceu:marble_tricalcium_phosphate_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/marble_trona_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:marble_trona_ore"
-  result: "gtceu:marble_trona_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/marble_tungstate_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:marble_tungstate_ore"
-  result: "gtceu:marble_tungstate_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/marble_uraninite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:marble_uraninite_ore"
-  result: "gtceu:marble_uraninite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/marble_vanadium_magnetite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:marble_vanadium_magnetite_ore"
-  result: "gtceu:marble_vanadium_magnetite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/marble_wulfenite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:marble_wulfenite_ore"
-  result: "gtceu:marble_wulfenite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/marble_yellow_garnet_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:marble_yellow_garnet_ore"
-  result: "gtceu:marble_yellow_garnet_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/marble_yellow_limonite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:marble_yellow_limonite_ore"
-  result: "gtceu:marble_yellow_limonite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/marble_zeolite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:marble_zeolite_ore"
-  result: "gtceu:marble_zeolite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/mars_almandine_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:mars_almandine_ore"
-  result: "gtceu:mars_almandine_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/mars_aluminium_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:mars_aluminium_ore"
-  result: "gtceu:mars_aluminium_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/mars_alunite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:mars_alunite_ore"
-  result: "gtceu:mars_alunite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/mars_amethyst_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:mars_amethyst_ore"
-  result: "gtceu:mars_amethyst_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/mars_apatite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:mars_apatite_ore"
-  result: "gtceu:mars_apatite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/mars_asbestos_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:mars_asbestos_ore"
-  result: "gtceu:mars_asbestos_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/mars_barite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:mars_barite_ore"
-  result: "gtceu:mars_barite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/mars_basaltic_mineral_sand_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:mars_basaltic_mineral_sand_ore"
-  result: "gtceu:mars_basaltic_mineral_sand_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/mars_bastnasite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:mars_bastnasite_ore"
-  result: "gtceu:mars_bastnasite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/mars_bauxite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:mars_bauxite_ore"
-  result: "gtceu:mars_bauxite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/mars_bentonite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:mars_bentonite_ore"
-  result: "gtceu:mars_bentonite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/mars_beryllium_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:mars_beryllium_ore"
-  result: "gtceu:mars_beryllium_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/mars_blue_topaz_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:mars_blue_topaz_ore"
-  result: "gtceu:mars_blue_topaz_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/mars_bornite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:mars_bornite_ore"
-  result: "gtceu:mars_bornite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/mars_calcite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:mars_calcite_ore"
-  result: "gtceu:mars_calcite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/mars_cassiterite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:mars_cassiterite_ore"
-  result: "gtceu:mars_cassiterite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/mars_cassiterite_sand_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:mars_cassiterite_sand_ore"
-  result: "gtceu:mars_cassiterite_sand_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/mars_certus_quartz_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:mars_certus_quartz_ore"
-  result: "gtceu:mars_certus_quartz_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/mars_chalcocite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:mars_chalcocite_ore"
-  result: "gtceu:mars_chalcocite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/mars_chalcopyrite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:mars_chalcopyrite_ore"
-  result: "gtceu:mars_chalcopyrite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/mars_chromite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:mars_chromite_ore"
-  result: "gtceu:mars_chromite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/mars_cinnabar_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:mars_cinnabar_ore"
-  result: "gtceu:mars_cinnabar_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/mars_coal_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:mars_coal_ore"
-  result: "gtceu:mars_coal_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/mars_cobalt_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:mars_cobalt_ore"
-  result: "gtceu:mars_cobalt_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/mars_cobaltite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:mars_cobaltite_ore"
-  result: "gtceu:mars_cobaltite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/mars_cooperite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:mars_cooperite_ore"
-  result: "gtceu:mars_cooperite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/mars_copper_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:mars_copper_ore"
-  result: "gtceu:mars_copper_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/mars_diamond_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:mars_diamond_ore"
-  result: "gtceu:mars_diamond_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/mars_diatomite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:mars_diatomite_ore"
-  result: "gtceu:mars_diatomite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/mars_electrotine_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:mars_electrotine_ore"
-  result: "gtceu:mars_electrotine_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/mars_emerald_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:mars_emerald_ore"
-  result: "gtceu:mars_emerald_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/mars_fullers_earth_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:mars_fullers_earth_ore"
-  result: "gtceu:mars_fullers_earth_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/mars_galena_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:mars_galena_ore"
-  result: "gtceu:mars_galena_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/mars_garnet_sand_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:mars_garnet_sand_ore"
-  result: "gtceu:mars_garnet_sand_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/mars_garnierite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:mars_garnierite_ore"
-  result: "gtceu:mars_garnierite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/mars_glauconite_sand_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:mars_glauconite_sand_ore"
-  result: "gtceu:mars_glauconite_sand_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/mars_goethite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:mars_goethite_ore"
-  result: "gtceu:mars_goethite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/mars_gold_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:mars_gold_ore"
-  result: "gtceu:mars_gold_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/mars_granitic_mineral_sand_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:mars_granitic_mineral_sand_ore"
-  result: "gtceu:mars_granitic_mineral_sand_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/mars_graphite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:mars_graphite_ore"
-  result: "gtceu:mars_graphite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/mars_green_sapphire_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:mars_green_sapphire_ore"
-  result: "gtceu:mars_green_sapphire_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/mars_grossular_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:mars_grossular_ore"
-  result: "gtceu:mars_grossular_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/mars_gypsum_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:mars_gypsum_ore"
-  result: "gtceu:mars_gypsum_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/mars_hematite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:mars_hematite_ore"
-  result: "gtceu:mars_hematite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/mars_ilmenite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:mars_ilmenite_ore"
-  result: "gtceu:mars_ilmenite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/mars_iron_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:mars_iron_ore"
-  result: "gtceu:mars_iron_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/mars_kyanite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:mars_kyanite_ore"
-  result: "gtceu:mars_kyanite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/mars_lapis_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:mars_lapis_ore"
-  result: "gtceu:mars_lapis_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/mars_lazurite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:mars_lazurite_ore"
-  result: "gtceu:mars_lazurite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/mars_lead_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:mars_lead_ore"
-  result: "gtceu:mars_lead_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/mars_lepidolite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:mars_lepidolite_ore"
-  result: "gtceu:mars_lepidolite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/mars_lithium_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:mars_lithium_ore"
-  result: "gtceu:mars_lithium_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/mars_magnesite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:mars_magnesite_ore"
-  result: "gtceu:mars_magnesite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/mars_magnetite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:mars_magnetite_ore"
-  result: "gtceu:mars_magnetite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/mars_malachite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:mars_malachite_ore"
-  result: "gtceu:mars_malachite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/mars_mica_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:mars_mica_ore"
-  result: "gtceu:mars_mica_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/mars_molybdenite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:mars_molybdenite_ore"
-  result: "gtceu:mars_molybdenite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/mars_molybdenum_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:mars_molybdenum_ore"
-  result: "gtceu:mars_molybdenum_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/mars_monazite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:mars_monazite_ore"
-  result: "gtceu:mars_monazite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/mars_naquadah_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:mars_naquadah_ore"
-  result: "gtceu:mars_naquadah_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/mars_neodymium_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:mars_neodymium_ore"
-  result: "gtceu:mars_neodymium_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/mars_nether_quartz_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:mars_nether_quartz_ore"
-  result: "gtceu:mars_nether_quartz_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/mars_nickel_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:mars_nickel_ore"
-  result: "gtceu:mars_nickel_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/mars_oilsands_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:mars_oilsands_ore"
-  result: "gtceu:mars_oilsands_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/mars_olivine_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:mars_olivine_ore"
-  result: "gtceu:mars_olivine_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/mars_opal_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:mars_opal_ore"
-  result: "gtceu:mars_opal_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/mars_palladium_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:mars_palladium_ore"
-  result: "gtceu:mars_palladium_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/mars_pentlandite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:mars_pentlandite_ore"
-  result: "gtceu:mars_pentlandite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/mars_pitchblende_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:mars_pitchblende_ore"
-  result: "gtceu:mars_pitchblende_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/mars_platinum_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:mars_platinum_ore"
-  result: "gtceu:mars_platinum_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/mars_plutonium_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:mars_plutonium_ore"
-  result: "gtceu:mars_plutonium_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/mars_pollucite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:mars_pollucite_ore"
-  result: "gtceu:mars_pollucite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/mars_powellite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:mars_powellite_ore"
-  result: "gtceu:mars_powellite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/mars_pyrite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:mars_pyrite_ore"
-  result: "gtceu:mars_pyrite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/mars_pyrochlore_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:mars_pyrochlore_ore"
-  result: "gtceu:mars_pyrochlore_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/mars_pyrolusite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:mars_pyrolusite_ore"
-  result: "gtceu:mars_pyrolusite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/mars_pyrope_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:mars_pyrope_ore"
-  result: "gtceu:mars_pyrope_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/mars_quartzite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:mars_quartzite_ore"
-  result: "gtceu:mars_quartzite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/mars_realgar_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:mars_realgar_ore"
-  result: "gtceu:mars_realgar_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/mars_red_garnet_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:mars_red_garnet_ore"
-  result: "gtceu:mars_red_garnet_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/mars_redstone_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:mars_redstone_ore"
-  result: "gtceu:mars_redstone_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/mars_rock_salt_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:mars_rock_salt_ore"
-  result: "gtceu:mars_rock_salt_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/mars_ruby_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:mars_ruby_ore"
-  result: "gtceu:mars_ruby_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/mars_salt_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:mars_salt_ore"
-  result: "gtceu:mars_salt_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/mars_saltpeter_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:mars_saltpeter_ore"
-  result: "gtceu:mars_saltpeter_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/mars_sapphire_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:mars_sapphire_ore"
-  result: "gtceu:mars_sapphire_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/mars_scheelite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:mars_scheelite_ore"
-  result: "gtceu:mars_scheelite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/mars_silver_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:mars_silver_ore"
-  result: "gtceu:mars_silver_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/mars_soapstone_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:mars_soapstone_ore"
-  result: "gtceu:mars_soapstone_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/mars_sodalite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:mars_sodalite_ore"
-  result: "gtceu:mars_sodalite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/mars_spessartine_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:mars_spessartine_ore"
-  result: "gtceu:mars_spessartine_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/mars_sphalerite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:mars_sphalerite_ore"
-  result: "gtceu:mars_sphalerite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/mars_spodumene_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:mars_spodumene_ore"
-  result: "gtceu:mars_spodumene_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/mars_stibnite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:mars_stibnite_ore"
-  result: "gtceu:mars_stibnite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/mars_sulfur_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:mars_sulfur_ore"
-  result: "gtceu:mars_sulfur_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/mars_talc_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:mars_talc_ore"
-  result: "gtceu:mars_talc_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/mars_tantalite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:mars_tantalite_ore"
-  result: "gtceu:mars_tantalite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/mars_tetrahedrite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:mars_tetrahedrite_ore"
-  result: "gtceu:mars_tetrahedrite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/mars_thorium_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:mars_thorium_ore"
-  result: "gtceu:mars_thorium_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/mars_tin_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:mars_tin_ore"
-  result: "gtceu:mars_tin_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/mars_titanium_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:mars_titanium_ore"
-  result: "gtceu:mars_titanium_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/mars_topaz_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:mars_topaz_ore"
-  result: "gtceu:mars_topaz_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/mars_tricalcium_phosphate_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:mars_tricalcium_phosphate_ore"
-  result: "gtceu:mars_tricalcium_phosphate_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/mars_trona_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:mars_trona_ore"
-  result: "gtceu:mars_trona_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/mars_tungstate_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:mars_tungstate_ore"
-  result: "gtceu:mars_tungstate_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/mars_uraninite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:mars_uraninite_ore"
-  result: "gtceu:mars_uraninite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/mars_vanadium_magnetite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:mars_vanadium_magnetite_ore"
-  result: "gtceu:mars_vanadium_magnetite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/mars_wulfenite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:mars_wulfenite_ore"
-  result: "gtceu:mars_wulfenite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/mars_yellow_garnet_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:mars_yellow_garnet_ore"
-  result: "gtceu:mars_yellow_garnet_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/mars_yellow_limonite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:mars_yellow_limonite_ore"
-  result: "gtceu:mars_yellow_limonite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/mars_zeolite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:mars_zeolite_ore"
-  result: "gtceu:mars_zeolite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/mercury_almandine_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:mercury_almandine_ore"
-  result: "gtceu:mercury_almandine_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/mercury_aluminium_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:mercury_aluminium_ore"
-  result: "gtceu:mercury_aluminium_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/mercury_alunite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:mercury_alunite_ore"
-  result: "gtceu:mercury_alunite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/mercury_amethyst_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:mercury_amethyst_ore"
-  result: "gtceu:mercury_amethyst_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/mercury_apatite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:mercury_apatite_ore"
-  result: "gtceu:mercury_apatite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/mercury_asbestos_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:mercury_asbestos_ore"
-  result: "gtceu:mercury_asbestos_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/mercury_barite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:mercury_barite_ore"
-  result: "gtceu:mercury_barite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/mercury_basaltic_mineral_sand_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:mercury_basaltic_mineral_sand_ore"
-  result: "gtceu:mercury_basaltic_mineral_sand_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/mercury_bastnasite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:mercury_bastnasite_ore"
-  result: "gtceu:mercury_bastnasite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/mercury_bauxite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:mercury_bauxite_ore"
-  result: "gtceu:mercury_bauxite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/mercury_bentonite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:mercury_bentonite_ore"
-  result: "gtceu:mercury_bentonite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/mercury_beryllium_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:mercury_beryllium_ore"
-  result: "gtceu:mercury_beryllium_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/mercury_blue_topaz_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:mercury_blue_topaz_ore"
-  result: "gtceu:mercury_blue_topaz_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/mercury_bornite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:mercury_bornite_ore"
-  result: "gtceu:mercury_bornite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/mercury_calcite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:mercury_calcite_ore"
-  result: "gtceu:mercury_calcite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/mercury_cassiterite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:mercury_cassiterite_ore"
-  result: "gtceu:mercury_cassiterite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/mercury_cassiterite_sand_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:mercury_cassiterite_sand_ore"
-  result: "gtceu:mercury_cassiterite_sand_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/mercury_certus_quartz_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:mercury_certus_quartz_ore"
-  result: "gtceu:mercury_certus_quartz_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/mercury_chalcocite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:mercury_chalcocite_ore"
-  result: "gtceu:mercury_chalcocite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/mercury_chalcopyrite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:mercury_chalcopyrite_ore"
-  result: "gtceu:mercury_chalcopyrite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/mercury_chromite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:mercury_chromite_ore"
-  result: "gtceu:mercury_chromite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/mercury_cinnabar_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:mercury_cinnabar_ore"
-  result: "gtceu:mercury_cinnabar_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/mercury_coal_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:mercury_coal_ore"
-  result: "gtceu:mercury_coal_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/mercury_cobalt_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:mercury_cobalt_ore"
-  result: "gtceu:mercury_cobalt_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/mercury_cobaltite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:mercury_cobaltite_ore"
-  result: "gtceu:mercury_cobaltite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/mercury_cooperite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:mercury_cooperite_ore"
-  result: "gtceu:mercury_cooperite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/mercury_copper_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:mercury_copper_ore"
-  result: "gtceu:mercury_copper_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/mercury_diamond_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:mercury_diamond_ore"
-  result: "gtceu:mercury_diamond_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/mercury_diatomite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:mercury_diatomite_ore"
-  result: "gtceu:mercury_diatomite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/mercury_electrotine_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:mercury_electrotine_ore"
-  result: "gtceu:mercury_electrotine_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/mercury_emerald_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:mercury_emerald_ore"
-  result: "gtceu:mercury_emerald_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/mercury_fullers_earth_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:mercury_fullers_earth_ore"
-  result: "gtceu:mercury_fullers_earth_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/mercury_galena_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:mercury_galena_ore"
-  result: "gtceu:mercury_galena_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/mercury_garnet_sand_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:mercury_garnet_sand_ore"
-  result: "gtceu:mercury_garnet_sand_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/mercury_garnierite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:mercury_garnierite_ore"
-  result: "gtceu:mercury_garnierite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/mercury_glauconite_sand_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:mercury_glauconite_sand_ore"
-  result: "gtceu:mercury_glauconite_sand_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/mercury_goethite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:mercury_goethite_ore"
-  result: "gtceu:mercury_goethite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/mercury_gold_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:mercury_gold_ore"
-  result: "gtceu:mercury_gold_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/mercury_granitic_mineral_sand_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:mercury_granitic_mineral_sand_ore"
-  result: "gtceu:mercury_granitic_mineral_sand_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/mercury_graphite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:mercury_graphite_ore"
-  result: "gtceu:mercury_graphite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/mercury_green_sapphire_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:mercury_green_sapphire_ore"
-  result: "gtceu:mercury_green_sapphire_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/mercury_grossular_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:mercury_grossular_ore"
-  result: "gtceu:mercury_grossular_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/mercury_gypsum_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:mercury_gypsum_ore"
-  result: "gtceu:mercury_gypsum_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/mercury_hematite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:mercury_hematite_ore"
-  result: "gtceu:mercury_hematite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/mercury_ilmenite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:mercury_ilmenite_ore"
-  result: "gtceu:mercury_ilmenite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/mercury_iron_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:mercury_iron_ore"
-  result: "gtceu:mercury_iron_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/mercury_kyanite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:mercury_kyanite_ore"
-  result: "gtceu:mercury_kyanite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/mercury_lapis_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:mercury_lapis_ore"
-  result: "gtceu:mercury_lapis_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/mercury_lazurite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:mercury_lazurite_ore"
-  result: "gtceu:mercury_lazurite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/mercury_lead_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:mercury_lead_ore"
-  result: "gtceu:mercury_lead_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/mercury_lepidolite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:mercury_lepidolite_ore"
-  result: "gtceu:mercury_lepidolite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/mercury_lithium_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:mercury_lithium_ore"
-  result: "gtceu:mercury_lithium_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/mercury_magnesite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:mercury_magnesite_ore"
-  result: "gtceu:mercury_magnesite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/mercury_magnetite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:mercury_magnetite_ore"
-  result: "gtceu:mercury_magnetite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/mercury_malachite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:mercury_malachite_ore"
-  result: "gtceu:mercury_malachite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/mercury_mica_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:mercury_mica_ore"
-  result: "gtceu:mercury_mica_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/mercury_molybdenite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:mercury_molybdenite_ore"
-  result: "gtceu:mercury_molybdenite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/mercury_molybdenum_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:mercury_molybdenum_ore"
-  result: "gtceu:mercury_molybdenum_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/mercury_monazite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:mercury_monazite_ore"
-  result: "gtceu:mercury_monazite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/mercury_naquadah_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:mercury_naquadah_ore"
-  result: "gtceu:mercury_naquadah_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/mercury_neodymium_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:mercury_neodymium_ore"
-  result: "gtceu:mercury_neodymium_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/mercury_nether_quartz_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:mercury_nether_quartz_ore"
-  result: "gtceu:mercury_nether_quartz_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/mercury_nickel_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:mercury_nickel_ore"
-  result: "gtceu:mercury_nickel_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/mercury_oilsands_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:mercury_oilsands_ore"
-  result: "gtceu:mercury_oilsands_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/mercury_olivine_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:mercury_olivine_ore"
-  result: "gtceu:mercury_olivine_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/mercury_opal_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:mercury_opal_ore"
-  result: "gtceu:mercury_opal_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/mercury_palladium_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:mercury_palladium_ore"
-  result: "gtceu:mercury_palladium_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/mercury_pentlandite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:mercury_pentlandite_ore"
-  result: "gtceu:mercury_pentlandite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/mercury_pitchblende_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:mercury_pitchblende_ore"
-  result: "gtceu:mercury_pitchblende_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/mercury_platinum_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:mercury_platinum_ore"
-  result: "gtceu:mercury_platinum_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/mercury_plutonium_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:mercury_plutonium_ore"
-  result: "gtceu:mercury_plutonium_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/mercury_pollucite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:mercury_pollucite_ore"
-  result: "gtceu:mercury_pollucite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/mercury_powellite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:mercury_powellite_ore"
-  result: "gtceu:mercury_powellite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/mercury_pyrite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:mercury_pyrite_ore"
-  result: "gtceu:mercury_pyrite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/mercury_pyrochlore_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:mercury_pyrochlore_ore"
-  result: "gtceu:mercury_pyrochlore_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/mercury_pyrolusite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:mercury_pyrolusite_ore"
-  result: "gtceu:mercury_pyrolusite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/mercury_pyrope_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:mercury_pyrope_ore"
-  result: "gtceu:mercury_pyrope_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/mercury_quartzite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:mercury_quartzite_ore"
-  result: "gtceu:mercury_quartzite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/mercury_realgar_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:mercury_realgar_ore"
-  result: "gtceu:mercury_realgar_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/mercury_red_garnet_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:mercury_red_garnet_ore"
-  result: "gtceu:mercury_red_garnet_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/mercury_redstone_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:mercury_redstone_ore"
-  result: "gtceu:mercury_redstone_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/mercury_rock_salt_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:mercury_rock_salt_ore"
-  result: "gtceu:mercury_rock_salt_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/mercury_ruby_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:mercury_ruby_ore"
-  result: "gtceu:mercury_ruby_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/mercury_salt_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:mercury_salt_ore"
-  result: "gtceu:mercury_salt_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/mercury_saltpeter_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:mercury_saltpeter_ore"
-  result: "gtceu:mercury_saltpeter_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/mercury_sapphire_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:mercury_sapphire_ore"
-  result: "gtceu:mercury_sapphire_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/mercury_scheelite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:mercury_scheelite_ore"
-  result: "gtceu:mercury_scheelite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/mercury_silver_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:mercury_silver_ore"
-  result: "gtceu:mercury_silver_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/mercury_soapstone_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:mercury_soapstone_ore"
-  result: "gtceu:mercury_soapstone_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/mercury_sodalite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:mercury_sodalite_ore"
-  result: "gtceu:mercury_sodalite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/mercury_spessartine_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:mercury_spessartine_ore"
-  result: "gtceu:mercury_spessartine_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/mercury_sphalerite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:mercury_sphalerite_ore"
-  result: "gtceu:mercury_sphalerite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/mercury_spodumene_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:mercury_spodumene_ore"
-  result: "gtceu:mercury_spodumene_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/mercury_stibnite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:mercury_stibnite_ore"
-  result: "gtceu:mercury_stibnite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/mercury_sulfur_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:mercury_sulfur_ore"
-  result: "gtceu:mercury_sulfur_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/mercury_talc_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:mercury_talc_ore"
-  result: "gtceu:mercury_talc_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/mercury_tantalite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:mercury_tantalite_ore"
-  result: "gtceu:mercury_tantalite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/mercury_tetrahedrite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:mercury_tetrahedrite_ore"
-  result: "gtceu:mercury_tetrahedrite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/mercury_thorium_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:mercury_thorium_ore"
-  result: "gtceu:mercury_thorium_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/mercury_tin_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:mercury_tin_ore"
-  result: "gtceu:mercury_tin_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/mercury_titanium_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:mercury_titanium_ore"
-  result: "gtceu:mercury_titanium_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/mercury_topaz_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:mercury_topaz_ore"
-  result: "gtceu:mercury_topaz_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/mercury_tricalcium_phosphate_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:mercury_tricalcium_phosphate_ore"
-  result: "gtceu:mercury_tricalcium_phosphate_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/mercury_trona_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:mercury_trona_ore"
-  result: "gtceu:mercury_trona_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/mercury_tungstate_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:mercury_tungstate_ore"
-  result: "gtceu:mercury_tungstate_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/mercury_uraninite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:mercury_uraninite_ore"
-  result: "gtceu:mercury_uraninite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/mercury_vanadium_magnetite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:mercury_vanadium_magnetite_ore"
-  result: "gtceu:mercury_vanadium_magnetite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/mercury_wulfenite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:mercury_wulfenite_ore"
-  result: "gtceu:mercury_wulfenite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/mercury_yellow_garnet_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:mercury_yellow_garnet_ore"
-  result: "gtceu:mercury_yellow_garnet_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/mercury_yellow_limonite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:mercury_yellow_limonite_ore"
-  result: "gtceu:mercury_yellow_limonite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/mercury_zeolite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:mercury_zeolite_ore"
-  result: "gtceu:mercury_zeolite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/mica_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:mica_ore"
-  result: "gtceu:mica_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/molybdenite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:molybdenite_ore"
-  result: "gtceu:molybdenite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/molybdenum_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:molybdenum_ore"
-  result: "gtceu:molybdenum_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/monazite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:monazite_ore"
-  result: "gtceu:monazite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/moon_almandine_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:moon_almandine_ore"
-  result: "gtceu:moon_almandine_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/moon_aluminium_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:moon_aluminium_ore"
-  result: "gtceu:moon_aluminium_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/moon_alunite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:moon_alunite_ore"
-  result: "gtceu:moon_alunite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/moon_amethyst_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:moon_amethyst_ore"
-  result: "gtceu:moon_amethyst_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/moon_apatite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:moon_apatite_ore"
-  result: "gtceu:moon_apatite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/moon_asbestos_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:moon_asbestos_ore"
-  result: "gtceu:moon_asbestos_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/moon_barite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:moon_barite_ore"
-  result: "gtceu:moon_barite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/moon_basaltic_mineral_sand_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:moon_basaltic_mineral_sand_ore"
-  result: "gtceu:moon_basaltic_mineral_sand_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/moon_bastnasite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:moon_bastnasite_ore"
-  result: "gtceu:moon_bastnasite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/moon_bauxite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:moon_bauxite_ore"
-  result: "gtceu:moon_bauxite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/moon_bentonite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:moon_bentonite_ore"
-  result: "gtceu:moon_bentonite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/moon_beryllium_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:moon_beryllium_ore"
-  result: "gtceu:moon_beryllium_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/moon_blue_topaz_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:moon_blue_topaz_ore"
-  result: "gtceu:moon_blue_topaz_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/moon_bornite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:moon_bornite_ore"
-  result: "gtceu:moon_bornite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/moon_calcite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:moon_calcite_ore"
-  result: "gtceu:moon_calcite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/moon_cassiterite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:moon_cassiterite_ore"
-  result: "gtceu:moon_cassiterite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/moon_cassiterite_sand_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:moon_cassiterite_sand_ore"
-  result: "gtceu:moon_cassiterite_sand_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/moon_certus_quartz_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:moon_certus_quartz_ore"
-  result: "gtceu:moon_certus_quartz_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/moon_chalcocite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:moon_chalcocite_ore"
-  result: "gtceu:moon_chalcocite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/moon_chalcopyrite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:moon_chalcopyrite_ore"
-  result: "gtceu:moon_chalcopyrite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/moon_chromite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:moon_chromite_ore"
-  result: "gtceu:moon_chromite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/moon_cinnabar_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:moon_cinnabar_ore"
-  result: "gtceu:moon_cinnabar_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/moon_coal_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:moon_coal_ore"
-  result: "gtceu:moon_coal_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/moon_cobalt_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:moon_cobalt_ore"
-  result: "gtceu:moon_cobalt_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/moon_cobaltite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:moon_cobaltite_ore"
-  result: "gtceu:moon_cobaltite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/moon_cooperite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:moon_cooperite_ore"
-  result: "gtceu:moon_cooperite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/moon_copper_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:moon_copper_ore"
-  result: "gtceu:moon_copper_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/moon_diamond_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:moon_diamond_ore"
-  result: "gtceu:moon_diamond_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/moon_diatomite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:moon_diatomite_ore"
-  result: "gtceu:moon_diatomite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/moon_electrotine_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:moon_electrotine_ore"
-  result: "gtceu:moon_electrotine_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/moon_emerald_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:moon_emerald_ore"
-  result: "gtceu:moon_emerald_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/moon_fullers_earth_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:moon_fullers_earth_ore"
-  result: "gtceu:moon_fullers_earth_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/moon_galena_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:moon_galena_ore"
-  result: "gtceu:moon_galena_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/moon_garnet_sand_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:moon_garnet_sand_ore"
-  result: "gtceu:moon_garnet_sand_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/moon_garnierite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:moon_garnierite_ore"
-  result: "gtceu:moon_garnierite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/moon_glauconite_sand_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:moon_glauconite_sand_ore"
-  result: "gtceu:moon_glauconite_sand_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/moon_goethite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:moon_goethite_ore"
-  result: "gtceu:moon_goethite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/moon_gold_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:moon_gold_ore"
-  result: "gtceu:moon_gold_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/moon_granitic_mineral_sand_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:moon_granitic_mineral_sand_ore"
-  result: "gtceu:moon_granitic_mineral_sand_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/moon_graphite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:moon_graphite_ore"
-  result: "gtceu:moon_graphite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/moon_green_sapphire_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:moon_green_sapphire_ore"
-  result: "gtceu:moon_green_sapphire_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/moon_grossular_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:moon_grossular_ore"
-  result: "gtceu:moon_grossular_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/moon_gypsum_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:moon_gypsum_ore"
-  result: "gtceu:moon_gypsum_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/moon_hematite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:moon_hematite_ore"
-  result: "gtceu:moon_hematite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/moon_ilmenite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:moon_ilmenite_ore"
-  result: "gtceu:moon_ilmenite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/moon_iron_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:moon_iron_ore"
-  result: "gtceu:moon_iron_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/moon_kyanite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:moon_kyanite_ore"
-  result: "gtceu:moon_kyanite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/moon_lapis_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:moon_lapis_ore"
-  result: "gtceu:moon_lapis_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/moon_lazurite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:moon_lazurite_ore"
-  result: "gtceu:moon_lazurite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/moon_lead_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:moon_lead_ore"
-  result: "gtceu:moon_lead_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/moon_lepidolite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:moon_lepidolite_ore"
-  result: "gtceu:moon_lepidolite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/moon_lithium_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:moon_lithium_ore"
-  result: "gtceu:moon_lithium_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/moon_magnesite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:moon_magnesite_ore"
-  result: "gtceu:moon_magnesite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/moon_magnetite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:moon_magnetite_ore"
-  result: "gtceu:moon_magnetite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/moon_malachite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:moon_malachite_ore"
-  result: "gtceu:moon_malachite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/moon_mica_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:moon_mica_ore"
-  result: "gtceu:moon_mica_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/moon_molybdenite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:moon_molybdenite_ore"
-  result: "gtceu:moon_molybdenite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/moon_molybdenum_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:moon_molybdenum_ore"
-  result: "gtceu:moon_molybdenum_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/moon_monazite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:moon_monazite_ore"
-  result: "gtceu:moon_monazite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/moon_naquadah_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:moon_naquadah_ore"
-  result: "gtceu:moon_naquadah_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/moon_neodymium_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:moon_neodymium_ore"
-  result: "gtceu:moon_neodymium_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/moon_nether_quartz_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:moon_nether_quartz_ore"
-  result: "gtceu:moon_nether_quartz_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/moon_nickel_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:moon_nickel_ore"
-  result: "gtceu:moon_nickel_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/moon_oilsands_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:moon_oilsands_ore"
-  result: "gtceu:moon_oilsands_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/moon_olivine_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:moon_olivine_ore"
-  result: "gtceu:moon_olivine_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/moon_opal_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:moon_opal_ore"
-  result: "gtceu:moon_opal_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/moon_palladium_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:moon_palladium_ore"
-  result: "gtceu:moon_palladium_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/moon_pentlandite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:moon_pentlandite_ore"
-  result: "gtceu:moon_pentlandite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/moon_pitchblende_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:moon_pitchblende_ore"
-  result: "gtceu:moon_pitchblende_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/moon_platinum_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:moon_platinum_ore"
-  result: "gtceu:moon_platinum_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/moon_plutonium_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:moon_plutonium_ore"
-  result: "gtceu:moon_plutonium_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/moon_pollucite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:moon_pollucite_ore"
-  result: "gtceu:moon_pollucite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/moon_powellite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:moon_powellite_ore"
-  result: "gtceu:moon_powellite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/moon_pyrite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:moon_pyrite_ore"
-  result: "gtceu:moon_pyrite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/moon_pyrochlore_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:moon_pyrochlore_ore"
-  result: "gtceu:moon_pyrochlore_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/moon_pyrolusite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:moon_pyrolusite_ore"
-  result: "gtceu:moon_pyrolusite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/moon_pyrope_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:moon_pyrope_ore"
-  result: "gtceu:moon_pyrope_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/moon_quartzite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:moon_quartzite_ore"
-  result: "gtceu:moon_quartzite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/moon_realgar_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:moon_realgar_ore"
-  result: "gtceu:moon_realgar_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/moon_red_garnet_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:moon_red_garnet_ore"
-  result: "gtceu:moon_red_garnet_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/moon_redstone_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:moon_redstone_ore"
-  result: "gtceu:moon_redstone_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/moon_rock_salt_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:moon_rock_salt_ore"
-  result: "gtceu:moon_rock_salt_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/moon_ruby_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:moon_ruby_ore"
-  result: "gtceu:moon_ruby_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/moon_salt_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:moon_salt_ore"
-  result: "gtceu:moon_salt_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/moon_saltpeter_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:moon_saltpeter_ore"
-  result: "gtceu:moon_saltpeter_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/moon_sapphire_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:moon_sapphire_ore"
-  result: "gtceu:moon_sapphire_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/moon_scheelite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:moon_scheelite_ore"
-  result: "gtceu:moon_scheelite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/moon_silver_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:moon_silver_ore"
-  result: "gtceu:moon_silver_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/moon_soapstone_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:moon_soapstone_ore"
-  result: "gtceu:moon_soapstone_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/moon_sodalite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:moon_sodalite_ore"
-  result: "gtceu:moon_sodalite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/moon_spessartine_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:moon_spessartine_ore"
-  result: "gtceu:moon_spessartine_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/moon_sphalerite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:moon_sphalerite_ore"
-  result: "gtceu:moon_sphalerite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/moon_spodumene_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:moon_spodumene_ore"
-  result: "gtceu:moon_spodumene_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/moon_stibnite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:moon_stibnite_ore"
-  result: "gtceu:moon_stibnite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/moon_sulfur_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:moon_sulfur_ore"
-  result: "gtceu:moon_sulfur_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/moon_talc_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:moon_talc_ore"
-  result: "gtceu:moon_talc_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/moon_tantalite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:moon_tantalite_ore"
-  result: "gtceu:moon_tantalite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/moon_tetrahedrite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:moon_tetrahedrite_ore"
-  result: "gtceu:moon_tetrahedrite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/moon_thorium_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:moon_thorium_ore"
-  result: "gtceu:moon_thorium_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/moon_tin_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:moon_tin_ore"
-  result: "gtceu:moon_tin_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/moon_titanium_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:moon_titanium_ore"
-  result: "gtceu:moon_titanium_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/moon_topaz_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:moon_topaz_ore"
-  result: "gtceu:moon_topaz_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/moon_tricalcium_phosphate_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:moon_tricalcium_phosphate_ore"
-  result: "gtceu:moon_tricalcium_phosphate_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/moon_trona_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:moon_trona_ore"
-  result: "gtceu:moon_trona_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/moon_tungstate_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:moon_tungstate_ore"
-  result: "gtceu:moon_tungstate_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/moon_uraninite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:moon_uraninite_ore"
-  result: "gtceu:moon_uraninite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/moon_vanadium_magnetite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:moon_vanadium_magnetite_ore"
-  result: "gtceu:moon_vanadium_magnetite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/moon_wulfenite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:moon_wulfenite_ore"
-  result: "gtceu:moon_wulfenite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/moon_yellow_garnet_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:moon_yellow_garnet_ore"
-  result: "gtceu:moon_yellow_garnet_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/moon_yellow_limonite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:moon_yellow_limonite_ore"
-  result: "gtceu:moon_yellow_limonite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/moon_zeolite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:moon_zeolite_ore"
-  result: "gtceu:moon_zeolite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/naquadah_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:naquadah_ore"
-  result: "gtceu:naquadah_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/neodymium_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:neodymium_ore"
-  result: "gtceu:neodymium_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/nether_quartz_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:nether_quartz_ore"
-  result: "gtceu:nether_quartz_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/netherrack_almandine_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:netherrack_almandine_ore"
-  result: "gtceu:netherrack_almandine_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/netherrack_aluminium_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:netherrack_aluminium_ore"
-  result: "gtceu:netherrack_aluminium_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/netherrack_alunite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:netherrack_alunite_ore"
-  result: "gtceu:netherrack_alunite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/netherrack_amethyst_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:netherrack_amethyst_ore"
-  result: "gtceu:netherrack_amethyst_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/netherrack_apatite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:netherrack_apatite_ore"
-  result: "gtceu:netherrack_apatite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/netherrack_asbestos_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:netherrack_asbestos_ore"
-  result: "gtceu:netherrack_asbestos_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/netherrack_barite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:netherrack_barite_ore"
-  result: "gtceu:netherrack_barite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/netherrack_basaltic_mineral_sand_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:netherrack_basaltic_mineral_sand_ore"
-  result: "gtceu:netherrack_basaltic_mineral_sand_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/netherrack_bastnasite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:netherrack_bastnasite_ore"
-  result: "gtceu:netherrack_bastnasite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/netherrack_bauxite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:netherrack_bauxite_ore"
-  result: "gtceu:netherrack_bauxite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/netherrack_bentonite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:netherrack_bentonite_ore"
-  result: "gtceu:netherrack_bentonite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/netherrack_beryllium_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:netherrack_beryllium_ore"
-  result: "gtceu:netherrack_beryllium_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/netherrack_blue_topaz_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:netherrack_blue_topaz_ore"
-  result: "gtceu:netherrack_blue_topaz_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/netherrack_bornite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:netherrack_bornite_ore"
-  result: "gtceu:netherrack_bornite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/netherrack_calcite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:netherrack_calcite_ore"
-  result: "gtceu:netherrack_calcite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/netherrack_cassiterite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:netherrack_cassiterite_ore"
-  result: "gtceu:netherrack_cassiterite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/netherrack_cassiterite_sand_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:netherrack_cassiterite_sand_ore"
-  result: "gtceu:netherrack_cassiterite_sand_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/netherrack_certus_quartz_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:netherrack_certus_quartz_ore"
-  result: "gtceu:netherrack_certus_quartz_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/netherrack_chalcocite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:netherrack_chalcocite_ore"
-  result: "gtceu:netherrack_chalcocite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/netherrack_chalcopyrite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:netherrack_chalcopyrite_ore"
-  result: "gtceu:netherrack_chalcopyrite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/netherrack_chromite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:netherrack_chromite_ore"
-  result: "gtceu:netherrack_chromite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/netherrack_cinnabar_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:netherrack_cinnabar_ore"
-  result: "gtceu:netherrack_cinnabar_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/netherrack_coal_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:netherrack_coal_ore"
-  result: "gtceu:netherrack_coal_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/netherrack_cobalt_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:netherrack_cobalt_ore"
-  result: "gtceu:netherrack_cobalt_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/netherrack_cobaltite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:netherrack_cobaltite_ore"
-  result: "gtceu:netherrack_cobaltite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/netherrack_cooperite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:netherrack_cooperite_ore"
-  result: "gtceu:netherrack_cooperite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/netherrack_copper_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:netherrack_copper_ore"
-  result: "gtceu:netherrack_copper_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/netherrack_diamond_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:netherrack_diamond_ore"
-  result: "gtceu:netherrack_diamond_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/netherrack_diatomite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:netherrack_diatomite_ore"
-  result: "gtceu:netherrack_diatomite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/netherrack_electrotine_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:netherrack_electrotine_ore"
-  result: "gtceu:netherrack_electrotine_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/netherrack_emerald_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:netherrack_emerald_ore"
-  result: "gtceu:netherrack_emerald_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/netherrack_fullers_earth_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:netherrack_fullers_earth_ore"
-  result: "gtceu:netherrack_fullers_earth_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/netherrack_galena_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:netherrack_galena_ore"
-  result: "gtceu:netherrack_galena_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/netherrack_garnet_sand_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:netherrack_garnet_sand_ore"
-  result: "gtceu:netherrack_garnet_sand_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/netherrack_garnierite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:netherrack_garnierite_ore"
-  result: "gtceu:netherrack_garnierite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/netherrack_glauconite_sand_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:netherrack_glauconite_sand_ore"
-  result: "gtceu:netherrack_glauconite_sand_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/netherrack_goethite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:netherrack_goethite_ore"
-  result: "gtceu:netherrack_goethite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/netherrack_gold_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:netherrack_gold_ore"
-  result: "gtceu:netherrack_gold_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/netherrack_granitic_mineral_sand_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:netherrack_granitic_mineral_sand_ore"
-  result: "gtceu:netherrack_granitic_mineral_sand_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/netherrack_graphite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:netherrack_graphite_ore"
-  result: "gtceu:netherrack_graphite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/netherrack_green_sapphire_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:netherrack_green_sapphire_ore"
-  result: "gtceu:netherrack_green_sapphire_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/netherrack_grossular_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:netherrack_grossular_ore"
-  result: "gtceu:netherrack_grossular_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/netherrack_gypsum_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:netherrack_gypsum_ore"
-  result: "gtceu:netherrack_gypsum_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/netherrack_hematite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:netherrack_hematite_ore"
-  result: "gtceu:netherrack_hematite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/netherrack_ilmenite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:netherrack_ilmenite_ore"
-  result: "gtceu:netherrack_ilmenite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/netherrack_iron_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:netherrack_iron_ore"
-  result: "gtceu:netherrack_iron_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/netherrack_kyanite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:netherrack_kyanite_ore"
-  result: "gtceu:netherrack_kyanite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/netherrack_lapis_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:netherrack_lapis_ore"
-  result: "gtceu:netherrack_lapis_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/netherrack_lazurite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:netherrack_lazurite_ore"
-  result: "gtceu:netherrack_lazurite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/netherrack_lead_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:netherrack_lead_ore"
-  result: "gtceu:netherrack_lead_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/netherrack_lepidolite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:netherrack_lepidolite_ore"
-  result: "gtceu:netherrack_lepidolite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/netherrack_lithium_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:netherrack_lithium_ore"
-  result: "gtceu:netherrack_lithium_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/netherrack_magnesite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:netherrack_magnesite_ore"
-  result: "gtceu:netherrack_magnesite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/netherrack_magnetite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:netherrack_magnetite_ore"
-  result: "gtceu:netherrack_magnetite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/netherrack_malachite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:netherrack_malachite_ore"
-  result: "gtceu:netherrack_malachite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/netherrack_mica_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:netherrack_mica_ore"
-  result: "gtceu:netherrack_mica_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/netherrack_molybdenite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:netherrack_molybdenite_ore"
-  result: "gtceu:netherrack_molybdenite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/netherrack_molybdenum_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:netherrack_molybdenum_ore"
-  result: "gtceu:netherrack_molybdenum_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/netherrack_monazite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:netherrack_monazite_ore"
-  result: "gtceu:netherrack_monazite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/netherrack_naquadah_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:netherrack_naquadah_ore"
-  result: "gtceu:netherrack_naquadah_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/netherrack_neodymium_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:netherrack_neodymium_ore"
-  result: "gtceu:netherrack_neodymium_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/netherrack_nether_quartz_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:netherrack_nether_quartz_ore"
-  result: "gtceu:netherrack_nether_quartz_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/netherrack_nickel_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:netherrack_nickel_ore"
-  result: "gtceu:netherrack_nickel_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/netherrack_oilsands_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:netherrack_oilsands_ore"
-  result: "gtceu:netherrack_oilsands_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/netherrack_olivine_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:netherrack_olivine_ore"
-  result: "gtceu:netherrack_olivine_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/netherrack_opal_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:netherrack_opal_ore"
-  result: "gtceu:netherrack_opal_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/netherrack_palladium_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:netherrack_palladium_ore"
-  result: "gtceu:netherrack_palladium_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/netherrack_pentlandite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:netherrack_pentlandite_ore"
-  result: "gtceu:netherrack_pentlandite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/netherrack_pitchblende_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:netherrack_pitchblende_ore"
-  result: "gtceu:netherrack_pitchblende_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/netherrack_platinum_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:netherrack_platinum_ore"
-  result: "gtceu:netherrack_platinum_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/netherrack_plutonium_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:netherrack_plutonium_ore"
-  result: "gtceu:netherrack_plutonium_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/netherrack_pollucite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:netherrack_pollucite_ore"
-  result: "gtceu:netherrack_pollucite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/netherrack_powellite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:netherrack_powellite_ore"
-  result: "gtceu:netherrack_powellite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/netherrack_pyrite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:netherrack_pyrite_ore"
-  result: "gtceu:netherrack_pyrite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/netherrack_pyrochlore_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:netherrack_pyrochlore_ore"
-  result: "gtceu:netherrack_pyrochlore_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/netherrack_pyrolusite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:netherrack_pyrolusite_ore"
-  result: "gtceu:netherrack_pyrolusite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/netherrack_pyrope_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:netherrack_pyrope_ore"
-  result: "gtceu:netherrack_pyrope_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/netherrack_quartzite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:netherrack_quartzite_ore"
-  result: "gtceu:netherrack_quartzite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/netherrack_realgar_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:netherrack_realgar_ore"
-  result: "gtceu:netherrack_realgar_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/netherrack_red_garnet_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:netherrack_red_garnet_ore"
-  result: "gtceu:netherrack_red_garnet_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/netherrack_redstone_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:netherrack_redstone_ore"
-  result: "gtceu:netherrack_redstone_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/netherrack_rock_salt_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:netherrack_rock_salt_ore"
-  result: "gtceu:netherrack_rock_salt_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/netherrack_ruby_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:netherrack_ruby_ore"
-  result: "gtceu:netherrack_ruby_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/netherrack_salt_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:netherrack_salt_ore"
-  result: "gtceu:netherrack_salt_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/netherrack_saltpeter_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:netherrack_saltpeter_ore"
-  result: "gtceu:netherrack_saltpeter_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/netherrack_sapphire_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:netherrack_sapphire_ore"
-  result: "gtceu:netherrack_sapphire_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/netherrack_scheelite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:netherrack_scheelite_ore"
-  result: "gtceu:netherrack_scheelite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/netherrack_silver_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:netherrack_silver_ore"
-  result: "gtceu:netherrack_silver_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/netherrack_soapstone_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:netherrack_soapstone_ore"
-  result: "gtceu:netherrack_soapstone_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/netherrack_sodalite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:netherrack_sodalite_ore"
-  result: "gtceu:netherrack_sodalite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/netherrack_spessartine_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:netherrack_spessartine_ore"
-  result: "gtceu:netherrack_spessartine_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/netherrack_sphalerite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:netherrack_sphalerite_ore"
-  result: "gtceu:netherrack_sphalerite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/netherrack_spodumene_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:netherrack_spodumene_ore"
-  result: "gtceu:netherrack_spodumene_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/netherrack_stibnite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:netherrack_stibnite_ore"
-  result: "gtceu:netherrack_stibnite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/netherrack_sulfur_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:netherrack_sulfur_ore"
-  result: "gtceu:netherrack_sulfur_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/netherrack_talc_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:netherrack_talc_ore"
-  result: "gtceu:netherrack_talc_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/netherrack_tantalite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:netherrack_tantalite_ore"
-  result: "gtceu:netherrack_tantalite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/netherrack_tetrahedrite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:netherrack_tetrahedrite_ore"
-  result: "gtceu:netherrack_tetrahedrite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/netherrack_thorium_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:netherrack_thorium_ore"
-  result: "gtceu:netherrack_thorium_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/netherrack_tin_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:netherrack_tin_ore"
-  result: "gtceu:netherrack_tin_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/netherrack_titanium_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:netherrack_titanium_ore"
-  result: "gtceu:netherrack_titanium_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/netherrack_topaz_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:netherrack_topaz_ore"
-  result: "gtceu:netherrack_topaz_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/netherrack_tricalcium_phosphate_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:netherrack_tricalcium_phosphate_ore"
-  result: "gtceu:netherrack_tricalcium_phosphate_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/netherrack_trona_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:netherrack_trona_ore"
-  result: "gtceu:netherrack_trona_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/netherrack_tungstate_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:netherrack_tungstate_ore"
-  result: "gtceu:netherrack_tungstate_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/netherrack_uraninite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:netherrack_uraninite_ore"
-  result: "gtceu:netherrack_uraninite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/netherrack_vanadium_magnetite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:netherrack_vanadium_magnetite_ore"
-  result: "gtceu:netherrack_vanadium_magnetite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/netherrack_wulfenite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:netherrack_wulfenite_ore"
-  result: "gtceu:netherrack_wulfenite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/netherrack_yellow_garnet_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:netherrack_yellow_garnet_ore"
-  result: "gtceu:netherrack_yellow_garnet_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/netherrack_yellow_limonite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:netherrack_yellow_limonite_ore"
-  result: "gtceu:netherrack_yellow_limonite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/netherrack_zeolite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:netherrack_zeolite_ore"
-  result: "gtceu:netherrack_zeolite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/nickel_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:nickel_ore"
-  result: "gtceu:nickel_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/oilsands_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:oilsands_ore"
-  result: "gtceu:oilsands_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/olivine_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:olivine_ore"
-  result: "gtceu:olivine_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/opal_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:opal_ore"
-  result: "gtceu:opal_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/palladium_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:palladium_ore"
-  result: "gtceu:palladium_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/pentlandite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:pentlandite_ore"
-  result: "gtceu:pentlandite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/phyllite_almandine_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:phyllite_almandine_ore"
-  result: "gtceu:phyllite_almandine_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/phyllite_aluminium_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:phyllite_aluminium_ore"
-  result: "gtceu:phyllite_aluminium_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/phyllite_alunite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:phyllite_alunite_ore"
-  result: "gtceu:phyllite_alunite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/phyllite_amethyst_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:phyllite_amethyst_ore"
-  result: "gtceu:phyllite_amethyst_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/phyllite_apatite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:phyllite_apatite_ore"
-  result: "gtceu:phyllite_apatite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/phyllite_asbestos_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:phyllite_asbestos_ore"
-  result: "gtceu:phyllite_asbestos_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/phyllite_barite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:phyllite_barite_ore"
-  result: "gtceu:phyllite_barite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/phyllite_basaltic_mineral_sand_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:phyllite_basaltic_mineral_sand_ore"
-  result: "gtceu:phyllite_basaltic_mineral_sand_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/phyllite_bastnasite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:phyllite_bastnasite_ore"
-  result: "gtceu:phyllite_bastnasite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/phyllite_bauxite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:phyllite_bauxite_ore"
-  result: "gtceu:phyllite_bauxite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/phyllite_bentonite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:phyllite_bentonite_ore"
-  result: "gtceu:phyllite_bentonite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/phyllite_beryllium_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:phyllite_beryllium_ore"
-  result: "gtceu:phyllite_beryllium_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/phyllite_blue_topaz_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:phyllite_blue_topaz_ore"
-  result: "gtceu:phyllite_blue_topaz_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/phyllite_bornite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:phyllite_bornite_ore"
-  result: "gtceu:phyllite_bornite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/phyllite_calcite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:phyllite_calcite_ore"
-  result: "gtceu:phyllite_calcite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/phyllite_cassiterite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:phyllite_cassiterite_ore"
-  result: "gtceu:phyllite_cassiterite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/phyllite_cassiterite_sand_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:phyllite_cassiterite_sand_ore"
-  result: "gtceu:phyllite_cassiterite_sand_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/phyllite_certus_quartz_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:phyllite_certus_quartz_ore"
-  result: "gtceu:phyllite_certus_quartz_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/phyllite_chalcocite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:phyllite_chalcocite_ore"
-  result: "gtceu:phyllite_chalcocite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/phyllite_chalcopyrite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:phyllite_chalcopyrite_ore"
-  result: "gtceu:phyllite_chalcopyrite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/phyllite_chromite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:phyllite_chromite_ore"
-  result: "gtceu:phyllite_chromite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/phyllite_cinnabar_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:phyllite_cinnabar_ore"
-  result: "gtceu:phyllite_cinnabar_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/phyllite_coal_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:phyllite_coal_ore"
-  result: "gtceu:phyllite_coal_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/phyllite_cobalt_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:phyllite_cobalt_ore"
-  result: "gtceu:phyllite_cobalt_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/phyllite_cobaltite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:phyllite_cobaltite_ore"
-  result: "gtceu:phyllite_cobaltite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/phyllite_cooperite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:phyllite_cooperite_ore"
-  result: "gtceu:phyllite_cooperite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/phyllite_copper_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:phyllite_copper_ore"
-  result: "gtceu:phyllite_copper_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/phyllite_diamond_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:phyllite_diamond_ore"
-  result: "gtceu:phyllite_diamond_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/phyllite_diatomite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:phyllite_diatomite_ore"
-  result: "gtceu:phyllite_diatomite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/phyllite_electrotine_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:phyllite_electrotine_ore"
-  result: "gtceu:phyllite_electrotine_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/phyllite_emerald_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:phyllite_emerald_ore"
-  result: "gtceu:phyllite_emerald_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/phyllite_fullers_earth_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:phyllite_fullers_earth_ore"
-  result: "gtceu:phyllite_fullers_earth_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/phyllite_galena_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:phyllite_galena_ore"
-  result: "gtceu:phyllite_galena_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/phyllite_garnet_sand_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:phyllite_garnet_sand_ore"
-  result: "gtceu:phyllite_garnet_sand_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/phyllite_garnierite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:phyllite_garnierite_ore"
-  result: "gtceu:phyllite_garnierite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/phyllite_glauconite_sand_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:phyllite_glauconite_sand_ore"
-  result: "gtceu:phyllite_glauconite_sand_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/phyllite_goethite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:phyllite_goethite_ore"
-  result: "gtceu:phyllite_goethite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/phyllite_gold_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:phyllite_gold_ore"
-  result: "gtceu:phyllite_gold_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/phyllite_granitic_mineral_sand_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:phyllite_granitic_mineral_sand_ore"
-  result: "gtceu:phyllite_granitic_mineral_sand_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/phyllite_graphite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:phyllite_graphite_ore"
-  result: "gtceu:phyllite_graphite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/phyllite_green_sapphire_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:phyllite_green_sapphire_ore"
-  result: "gtceu:phyllite_green_sapphire_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/phyllite_grossular_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:phyllite_grossular_ore"
-  result: "gtceu:phyllite_grossular_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/phyllite_gypsum_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:phyllite_gypsum_ore"
-  result: "gtceu:phyllite_gypsum_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/phyllite_hematite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:phyllite_hematite_ore"
-  result: "gtceu:phyllite_hematite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/phyllite_ilmenite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:phyllite_ilmenite_ore"
-  result: "gtceu:phyllite_ilmenite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/phyllite_iron_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:phyllite_iron_ore"
-  result: "gtceu:phyllite_iron_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/phyllite_kyanite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:phyllite_kyanite_ore"
-  result: "gtceu:phyllite_kyanite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/phyllite_lapis_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:phyllite_lapis_ore"
-  result: "gtceu:phyllite_lapis_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/phyllite_lazurite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:phyllite_lazurite_ore"
-  result: "gtceu:phyllite_lazurite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/phyllite_lead_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:phyllite_lead_ore"
-  result: "gtceu:phyllite_lead_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/phyllite_lepidolite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:phyllite_lepidolite_ore"
-  result: "gtceu:phyllite_lepidolite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/phyllite_lithium_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:phyllite_lithium_ore"
-  result: "gtceu:phyllite_lithium_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/phyllite_magnesite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:phyllite_magnesite_ore"
-  result: "gtceu:phyllite_magnesite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/phyllite_magnetite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:phyllite_magnetite_ore"
-  result: "gtceu:phyllite_magnetite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/phyllite_malachite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:phyllite_malachite_ore"
-  result: "gtceu:phyllite_malachite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/phyllite_mica_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:phyllite_mica_ore"
-  result: "gtceu:phyllite_mica_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/phyllite_molybdenite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:phyllite_molybdenite_ore"
-  result: "gtceu:phyllite_molybdenite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/phyllite_molybdenum_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:phyllite_molybdenum_ore"
-  result: "gtceu:phyllite_molybdenum_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/phyllite_monazite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:phyllite_monazite_ore"
-  result: "gtceu:phyllite_monazite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/phyllite_naquadah_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:phyllite_naquadah_ore"
-  result: "gtceu:phyllite_naquadah_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/phyllite_neodymium_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:phyllite_neodymium_ore"
-  result: "gtceu:phyllite_neodymium_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/phyllite_nether_quartz_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:phyllite_nether_quartz_ore"
-  result: "gtceu:phyllite_nether_quartz_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/phyllite_nickel_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:phyllite_nickel_ore"
-  result: "gtceu:phyllite_nickel_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/phyllite_oilsands_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:phyllite_oilsands_ore"
-  result: "gtceu:phyllite_oilsands_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/phyllite_olivine_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:phyllite_olivine_ore"
-  result: "gtceu:phyllite_olivine_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/phyllite_opal_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:phyllite_opal_ore"
-  result: "gtceu:phyllite_opal_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/phyllite_palladium_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:phyllite_palladium_ore"
-  result: "gtceu:phyllite_palladium_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/phyllite_pentlandite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:phyllite_pentlandite_ore"
-  result: "gtceu:phyllite_pentlandite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/phyllite_pitchblende_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:phyllite_pitchblende_ore"
-  result: "gtceu:phyllite_pitchblende_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/phyllite_platinum_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:phyllite_platinum_ore"
-  result: "gtceu:phyllite_platinum_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/phyllite_plutonium_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:phyllite_plutonium_ore"
-  result: "gtceu:phyllite_plutonium_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/phyllite_pollucite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:phyllite_pollucite_ore"
-  result: "gtceu:phyllite_pollucite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/phyllite_powellite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:phyllite_powellite_ore"
-  result: "gtceu:phyllite_powellite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/phyllite_pyrite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:phyllite_pyrite_ore"
-  result: "gtceu:phyllite_pyrite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/phyllite_pyrochlore_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:phyllite_pyrochlore_ore"
-  result: "gtceu:phyllite_pyrochlore_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/phyllite_pyrolusite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:phyllite_pyrolusite_ore"
-  result: "gtceu:phyllite_pyrolusite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/phyllite_pyrope_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:phyllite_pyrope_ore"
-  result: "gtceu:phyllite_pyrope_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/phyllite_quartzite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:phyllite_quartzite_ore"
-  result: "gtceu:phyllite_quartzite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/phyllite_realgar_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:phyllite_realgar_ore"
-  result: "gtceu:phyllite_realgar_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/phyllite_red_garnet_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:phyllite_red_garnet_ore"
-  result: "gtceu:phyllite_red_garnet_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/phyllite_redstone_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:phyllite_redstone_ore"
-  result: "gtceu:phyllite_redstone_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/phyllite_rock_salt_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:phyllite_rock_salt_ore"
-  result: "gtceu:phyllite_rock_salt_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/phyllite_ruby_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:phyllite_ruby_ore"
-  result: "gtceu:phyllite_ruby_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/phyllite_salt_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:phyllite_salt_ore"
-  result: "gtceu:phyllite_salt_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/phyllite_saltpeter_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:phyllite_saltpeter_ore"
-  result: "gtceu:phyllite_saltpeter_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/phyllite_sapphire_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:phyllite_sapphire_ore"
-  result: "gtceu:phyllite_sapphire_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/phyllite_scheelite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:phyllite_scheelite_ore"
-  result: "gtceu:phyllite_scheelite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/phyllite_silver_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:phyllite_silver_ore"
-  result: "gtceu:phyllite_silver_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/phyllite_soapstone_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:phyllite_soapstone_ore"
-  result: "gtceu:phyllite_soapstone_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/phyllite_sodalite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:phyllite_sodalite_ore"
-  result: "gtceu:phyllite_sodalite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/phyllite_spessartine_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:phyllite_spessartine_ore"
-  result: "gtceu:phyllite_spessartine_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/phyllite_sphalerite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:phyllite_sphalerite_ore"
-  result: "gtceu:phyllite_sphalerite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/phyllite_spodumene_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:phyllite_spodumene_ore"
-  result: "gtceu:phyllite_spodumene_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/phyllite_stibnite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:phyllite_stibnite_ore"
-  result: "gtceu:phyllite_stibnite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/phyllite_sulfur_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:phyllite_sulfur_ore"
-  result: "gtceu:phyllite_sulfur_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/phyllite_talc_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:phyllite_talc_ore"
-  result: "gtceu:phyllite_talc_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/phyllite_tantalite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:phyllite_tantalite_ore"
-  result: "gtceu:phyllite_tantalite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/phyllite_tetrahedrite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:phyllite_tetrahedrite_ore"
-  result: "gtceu:phyllite_tetrahedrite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/phyllite_thorium_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:phyllite_thorium_ore"
-  result: "gtceu:phyllite_thorium_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/phyllite_tin_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:phyllite_tin_ore"
-  result: "gtceu:phyllite_tin_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/phyllite_titanium_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:phyllite_titanium_ore"
-  result: "gtceu:phyllite_titanium_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/phyllite_topaz_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:phyllite_topaz_ore"
-  result: "gtceu:phyllite_topaz_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/phyllite_tricalcium_phosphate_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:phyllite_tricalcium_phosphate_ore"
-  result: "gtceu:phyllite_tricalcium_phosphate_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/phyllite_trona_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:phyllite_trona_ore"
-  result: "gtceu:phyllite_trona_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/phyllite_tungstate_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:phyllite_tungstate_ore"
-  result: "gtceu:phyllite_tungstate_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/phyllite_uraninite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:phyllite_uraninite_ore"
-  result: "gtceu:phyllite_uraninite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/phyllite_vanadium_magnetite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:phyllite_vanadium_magnetite_ore"
-  result: "gtceu:phyllite_vanadium_magnetite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/phyllite_wulfenite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:phyllite_wulfenite_ore"
-  result: "gtceu:phyllite_wulfenite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/phyllite_yellow_garnet_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:phyllite_yellow_garnet_ore"
-  result: "gtceu:phyllite_yellow_garnet_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/phyllite_yellow_limonite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:phyllite_yellow_limonite_ore"
-  result: "gtceu:phyllite_yellow_limonite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/phyllite_zeolite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:phyllite_zeolite_ore"
-  result: "gtceu:phyllite_zeolite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/pitchblende_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:pitchblende_ore"
-  result: "gtceu:pitchblende_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/platinum_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:platinum_ore"
-  result: "gtceu:platinum_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/plutonium_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:plutonium_ore"
-  result: "gtceu:plutonium_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/pollucite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:pollucite_ore"
-  result: "gtceu:pollucite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/powellite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:powellite_ore"
-  result: "gtceu:powellite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/pyrite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:pyrite_ore"
-  result: "gtceu:pyrite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/pyrochlore_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:pyrochlore_ore"
-  result: "gtceu:pyrochlore_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/pyrolusite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:pyrolusite_ore"
-  result: "gtceu:pyrolusite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/pyrope_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:pyrope_ore"
-  result: "gtceu:pyrope_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/quartzite_almandine_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:quartzite_almandine_ore"
-  result: "gtceu:quartzite_almandine_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/quartzite_aluminium_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:quartzite_aluminium_ore"
-  result: "gtceu:quartzite_aluminium_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/quartzite_alunite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:quartzite_alunite_ore"
-  result: "gtceu:quartzite_alunite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/quartzite_amethyst_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:quartzite_amethyst_ore"
-  result: "gtceu:quartzite_amethyst_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/quartzite_apatite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:quartzite_apatite_ore"
-  result: "gtceu:quartzite_apatite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/quartzite_asbestos_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:quartzite_asbestos_ore"
-  result: "gtceu:quartzite_asbestos_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/quartzite_barite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:quartzite_barite_ore"
-  result: "gtceu:quartzite_barite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/quartzite_basaltic_mineral_sand_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:quartzite_basaltic_mineral_sand_ore"
-  result: "gtceu:quartzite_basaltic_mineral_sand_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/quartzite_bastnasite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:quartzite_bastnasite_ore"
-  result: "gtceu:quartzite_bastnasite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/quartzite_bauxite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:quartzite_bauxite_ore"
-  result: "gtceu:quartzite_bauxite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/quartzite_bentonite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:quartzite_bentonite_ore"
-  result: "gtceu:quartzite_bentonite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/quartzite_beryllium_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:quartzite_beryllium_ore"
-  result: "gtceu:quartzite_beryllium_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/quartzite_blue_topaz_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:quartzite_blue_topaz_ore"
-  result: "gtceu:quartzite_blue_topaz_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/quartzite_bornite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:quartzite_bornite_ore"
-  result: "gtceu:quartzite_bornite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/quartzite_calcite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:quartzite_calcite_ore"
-  result: "gtceu:quartzite_calcite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/quartzite_cassiterite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:quartzite_cassiterite_ore"
-  result: "gtceu:quartzite_cassiterite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/quartzite_cassiterite_sand_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:quartzite_cassiterite_sand_ore"
-  result: "gtceu:quartzite_cassiterite_sand_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/quartzite_certus_quartz_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:quartzite_certus_quartz_ore"
-  result: "gtceu:quartzite_certus_quartz_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/quartzite_chalcocite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:quartzite_chalcocite_ore"
-  result: "gtceu:quartzite_chalcocite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/quartzite_chalcopyrite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:quartzite_chalcopyrite_ore"
-  result: "gtceu:quartzite_chalcopyrite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/quartzite_chromite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:quartzite_chromite_ore"
-  result: "gtceu:quartzite_chromite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/quartzite_cinnabar_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:quartzite_cinnabar_ore"
-  result: "gtceu:quartzite_cinnabar_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/quartzite_coal_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:quartzite_coal_ore"
-  result: "gtceu:quartzite_coal_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/quartzite_cobalt_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:quartzite_cobalt_ore"
-  result: "gtceu:quartzite_cobalt_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/quartzite_cobaltite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:quartzite_cobaltite_ore"
-  result: "gtceu:quartzite_cobaltite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/quartzite_cooperite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:quartzite_cooperite_ore"
-  result: "gtceu:quartzite_cooperite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/quartzite_copper_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:quartzite_copper_ore"
-  result: "gtceu:quartzite_copper_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/quartzite_diamond_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:quartzite_diamond_ore"
-  result: "gtceu:quartzite_diamond_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/quartzite_diatomite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:quartzite_diatomite_ore"
-  result: "gtceu:quartzite_diatomite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/quartzite_electrotine_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:quartzite_electrotine_ore"
-  result: "gtceu:quartzite_electrotine_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/quartzite_emerald_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:quartzite_emerald_ore"
-  result: "gtceu:quartzite_emerald_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/quartzite_fullers_earth_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:quartzite_fullers_earth_ore"
-  result: "gtceu:quartzite_fullers_earth_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/quartzite_galena_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:quartzite_galena_ore"
-  result: "gtceu:quartzite_galena_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/quartzite_garnet_sand_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:quartzite_garnet_sand_ore"
-  result: "gtceu:quartzite_garnet_sand_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/quartzite_garnierite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:quartzite_garnierite_ore"
-  result: "gtceu:quartzite_garnierite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/quartzite_glauconite_sand_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:quartzite_glauconite_sand_ore"
-  result: "gtceu:quartzite_glauconite_sand_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/quartzite_goethite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:quartzite_goethite_ore"
-  result: "gtceu:quartzite_goethite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/quartzite_gold_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:quartzite_gold_ore"
-  result: "gtceu:quartzite_gold_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/quartzite_granitic_mineral_sand_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:quartzite_granitic_mineral_sand_ore"
-  result: "gtceu:quartzite_granitic_mineral_sand_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/quartzite_graphite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:quartzite_graphite_ore"
-  result: "gtceu:quartzite_graphite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/quartzite_green_sapphire_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:quartzite_green_sapphire_ore"
-  result: "gtceu:quartzite_green_sapphire_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/quartzite_grossular_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:quartzite_grossular_ore"
-  result: "gtceu:quartzite_grossular_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/quartzite_gypsum_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:quartzite_gypsum_ore"
-  result: "gtceu:quartzite_gypsum_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/quartzite_hematite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:quartzite_hematite_ore"
-  result: "gtceu:quartzite_hematite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/quartzite_ilmenite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:quartzite_ilmenite_ore"
-  result: "gtceu:quartzite_ilmenite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/quartzite_iron_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:quartzite_iron_ore"
-  result: "gtceu:quartzite_iron_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/quartzite_kyanite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:quartzite_kyanite_ore"
-  result: "gtceu:quartzite_kyanite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/quartzite_lapis_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:quartzite_lapis_ore"
-  result: "gtceu:quartzite_lapis_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/quartzite_lazurite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:quartzite_lazurite_ore"
-  result: "gtceu:quartzite_lazurite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/quartzite_lead_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:quartzite_lead_ore"
-  result: "gtceu:quartzite_lead_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/quartzite_lepidolite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:quartzite_lepidolite_ore"
-  result: "gtceu:quartzite_lepidolite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/quartzite_lithium_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:quartzite_lithium_ore"
-  result: "gtceu:quartzite_lithium_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/quartzite_magnesite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:quartzite_magnesite_ore"
-  result: "gtceu:quartzite_magnesite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/quartzite_magnetite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:quartzite_magnetite_ore"
-  result: "gtceu:quartzite_magnetite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/quartzite_malachite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:quartzite_malachite_ore"
-  result: "gtceu:quartzite_malachite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/quartzite_mica_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:quartzite_mica_ore"
-  result: "gtceu:quartzite_mica_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/quartzite_molybdenite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:quartzite_molybdenite_ore"
-  result: "gtceu:quartzite_molybdenite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/quartzite_molybdenum_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:quartzite_molybdenum_ore"
-  result: "gtceu:quartzite_molybdenum_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/quartzite_monazite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:quartzite_monazite_ore"
-  result: "gtceu:quartzite_monazite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/quartzite_naquadah_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:quartzite_naquadah_ore"
-  result: "gtceu:quartzite_naquadah_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/quartzite_neodymium_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:quartzite_neodymium_ore"
-  result: "gtceu:quartzite_neodymium_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/quartzite_nether_quartz_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:quartzite_nether_quartz_ore"
-  result: "gtceu:quartzite_nether_quartz_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/quartzite_nickel_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:quartzite_nickel_ore"
-  result: "gtceu:quartzite_nickel_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/quartzite_oilsands_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:quartzite_oilsands_ore"
-  result: "gtceu:quartzite_oilsands_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/quartzite_olivine_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:quartzite_olivine_ore"
-  result: "gtceu:quartzite_olivine_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/quartzite_opal_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:quartzite_opal_ore"
-  result: "gtceu:quartzite_opal_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/quartzite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:quartzite_ore"
-  result: "gtceu:quartzite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/quartzite_palladium_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:quartzite_palladium_ore"
-  result: "gtceu:quartzite_palladium_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/quartzite_pentlandite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:quartzite_pentlandite_ore"
-  result: "gtceu:quartzite_pentlandite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/quartzite_pitchblende_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:quartzite_pitchblende_ore"
-  result: "gtceu:quartzite_pitchblende_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/quartzite_platinum_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:quartzite_platinum_ore"
-  result: "gtceu:quartzite_platinum_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/quartzite_plutonium_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:quartzite_plutonium_ore"
-  result: "gtceu:quartzite_plutonium_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/quartzite_pollucite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:quartzite_pollucite_ore"
-  result: "gtceu:quartzite_pollucite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/quartzite_powellite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:quartzite_powellite_ore"
-  result: "gtceu:quartzite_powellite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/quartzite_pyrite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:quartzite_pyrite_ore"
-  result: "gtceu:quartzite_pyrite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/quartzite_pyrochlore_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:quartzite_pyrochlore_ore"
-  result: "gtceu:quartzite_pyrochlore_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/quartzite_pyrolusite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:quartzite_pyrolusite_ore"
-  result: "gtceu:quartzite_pyrolusite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/quartzite_pyrope_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:quartzite_pyrope_ore"
-  result: "gtceu:quartzite_pyrope_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/quartzite_quartzite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:quartzite_quartzite_ore"
-  result: "gtceu:quartzite_quartzite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/quartzite_realgar_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:quartzite_realgar_ore"
-  result: "gtceu:quartzite_realgar_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/quartzite_red_garnet_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:quartzite_red_garnet_ore"
-  result: "gtceu:quartzite_red_garnet_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/quartzite_redstone_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:quartzite_redstone_ore"
-  result: "gtceu:quartzite_redstone_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/quartzite_rock_salt_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:quartzite_rock_salt_ore"
-  result: "gtceu:quartzite_rock_salt_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/quartzite_ruby_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:quartzite_ruby_ore"
-  result: "gtceu:quartzite_ruby_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/quartzite_salt_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:quartzite_salt_ore"
-  result: "gtceu:quartzite_salt_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/quartzite_saltpeter_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:quartzite_saltpeter_ore"
-  result: "gtceu:quartzite_saltpeter_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/quartzite_sapphire_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:quartzite_sapphire_ore"
-  result: "gtceu:quartzite_sapphire_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/quartzite_scheelite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:quartzite_scheelite_ore"
-  result: "gtceu:quartzite_scheelite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/quartzite_silver_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:quartzite_silver_ore"
-  result: "gtceu:quartzite_silver_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/quartzite_soapstone_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:quartzite_soapstone_ore"
-  result: "gtceu:quartzite_soapstone_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/quartzite_sodalite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:quartzite_sodalite_ore"
-  result: "gtceu:quartzite_sodalite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/quartzite_spessartine_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:quartzite_spessartine_ore"
-  result: "gtceu:quartzite_spessartine_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/quartzite_sphalerite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:quartzite_sphalerite_ore"
-  result: "gtceu:quartzite_sphalerite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/quartzite_spodumene_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:quartzite_spodumene_ore"
-  result: "gtceu:quartzite_spodumene_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/quartzite_stibnite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:quartzite_stibnite_ore"
-  result: "gtceu:quartzite_stibnite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/quartzite_sulfur_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:quartzite_sulfur_ore"
-  result: "gtceu:quartzite_sulfur_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/quartzite_talc_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:quartzite_talc_ore"
-  result: "gtceu:quartzite_talc_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/quartzite_tantalite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:quartzite_tantalite_ore"
-  result: "gtceu:quartzite_tantalite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/quartzite_tetrahedrite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:quartzite_tetrahedrite_ore"
-  result: "gtceu:quartzite_tetrahedrite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/quartzite_thorium_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:quartzite_thorium_ore"
-  result: "gtceu:quartzite_thorium_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/quartzite_tin_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:quartzite_tin_ore"
-  result: "gtceu:quartzite_tin_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/quartzite_titanium_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:quartzite_titanium_ore"
-  result: "gtceu:quartzite_titanium_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/quartzite_topaz_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:quartzite_topaz_ore"
-  result: "gtceu:quartzite_topaz_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/quartzite_tricalcium_phosphate_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:quartzite_tricalcium_phosphate_ore"
-  result: "gtceu:quartzite_tricalcium_phosphate_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/quartzite_trona_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:quartzite_trona_ore"
-  result: "gtceu:quartzite_trona_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/quartzite_tungstate_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:quartzite_tungstate_ore"
-  result: "gtceu:quartzite_tungstate_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/quartzite_uraninite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:quartzite_uraninite_ore"
-  result: "gtceu:quartzite_uraninite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/quartzite_vanadium_magnetite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:quartzite_vanadium_magnetite_ore"
-  result: "gtceu:quartzite_vanadium_magnetite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/quartzite_wulfenite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:quartzite_wulfenite_ore"
-  result: "gtceu:quartzite_wulfenite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/quartzite_yellow_garnet_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:quartzite_yellow_garnet_ore"
-  result: "gtceu:quartzite_yellow_garnet_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/quartzite_yellow_limonite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:quartzite_yellow_limonite_ore"
-  result: "gtceu:quartzite_yellow_limonite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/quartzite_zeolite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:quartzite_zeolite_ore"
-  result: "gtceu:quartzite_zeolite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/realgar_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:realgar_ore"
-  result: "gtceu:realgar_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/red_garnet_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:red_garnet_ore"
-  result: "gtceu:red_garnet_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/redstone_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:redstone_ore"
-  result: "gtceu:redstone_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/rhyolite_almandine_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:rhyolite_almandine_ore"
-  result: "gtceu:rhyolite_almandine_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/rhyolite_aluminium_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:rhyolite_aluminium_ore"
-  result: "gtceu:rhyolite_aluminium_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/rhyolite_alunite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:rhyolite_alunite_ore"
-  result: "gtceu:rhyolite_alunite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/rhyolite_amethyst_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:rhyolite_amethyst_ore"
-  result: "gtceu:rhyolite_amethyst_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/rhyolite_apatite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:rhyolite_apatite_ore"
-  result: "gtceu:rhyolite_apatite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/rhyolite_asbestos_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:rhyolite_asbestos_ore"
-  result: "gtceu:rhyolite_asbestos_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/rhyolite_barite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:rhyolite_barite_ore"
-  result: "gtceu:rhyolite_barite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/rhyolite_basaltic_mineral_sand_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:rhyolite_basaltic_mineral_sand_ore"
-  result: "gtceu:rhyolite_basaltic_mineral_sand_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/rhyolite_bastnasite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:rhyolite_bastnasite_ore"
-  result: "gtceu:rhyolite_bastnasite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/rhyolite_bauxite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:rhyolite_bauxite_ore"
-  result: "gtceu:rhyolite_bauxite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/rhyolite_bentonite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:rhyolite_bentonite_ore"
-  result: "gtceu:rhyolite_bentonite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/rhyolite_beryllium_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:rhyolite_beryllium_ore"
-  result: "gtceu:rhyolite_beryllium_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/rhyolite_blue_topaz_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:rhyolite_blue_topaz_ore"
-  result: "gtceu:rhyolite_blue_topaz_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/rhyolite_bornite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:rhyolite_bornite_ore"
-  result: "gtceu:rhyolite_bornite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/rhyolite_calcite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:rhyolite_calcite_ore"
-  result: "gtceu:rhyolite_calcite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/rhyolite_cassiterite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:rhyolite_cassiterite_ore"
-  result: "gtceu:rhyolite_cassiterite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/rhyolite_cassiterite_sand_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:rhyolite_cassiterite_sand_ore"
-  result: "gtceu:rhyolite_cassiterite_sand_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/rhyolite_certus_quartz_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:rhyolite_certus_quartz_ore"
-  result: "gtceu:rhyolite_certus_quartz_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/rhyolite_chalcocite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:rhyolite_chalcocite_ore"
-  result: "gtceu:rhyolite_chalcocite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/rhyolite_chalcopyrite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:rhyolite_chalcopyrite_ore"
-  result: "gtceu:rhyolite_chalcopyrite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/rhyolite_chromite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:rhyolite_chromite_ore"
-  result: "gtceu:rhyolite_chromite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/rhyolite_cinnabar_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:rhyolite_cinnabar_ore"
-  result: "gtceu:rhyolite_cinnabar_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/rhyolite_coal_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:rhyolite_coal_ore"
-  result: "gtceu:rhyolite_coal_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/rhyolite_cobalt_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:rhyolite_cobalt_ore"
-  result: "gtceu:rhyolite_cobalt_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/rhyolite_cobaltite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:rhyolite_cobaltite_ore"
-  result: "gtceu:rhyolite_cobaltite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/rhyolite_cooperite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:rhyolite_cooperite_ore"
-  result: "gtceu:rhyolite_cooperite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/rhyolite_copper_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:rhyolite_copper_ore"
-  result: "gtceu:rhyolite_copper_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/rhyolite_diamond_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:rhyolite_diamond_ore"
-  result: "gtceu:rhyolite_diamond_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/rhyolite_diatomite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:rhyolite_diatomite_ore"
-  result: "gtceu:rhyolite_diatomite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/rhyolite_electrotine_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:rhyolite_electrotine_ore"
-  result: "gtceu:rhyolite_electrotine_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/rhyolite_emerald_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:rhyolite_emerald_ore"
-  result: "gtceu:rhyolite_emerald_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/rhyolite_fullers_earth_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:rhyolite_fullers_earth_ore"
-  result: "gtceu:rhyolite_fullers_earth_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/rhyolite_galena_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:rhyolite_galena_ore"
-  result: "gtceu:rhyolite_galena_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/rhyolite_garnet_sand_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:rhyolite_garnet_sand_ore"
-  result: "gtceu:rhyolite_garnet_sand_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/rhyolite_garnierite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:rhyolite_garnierite_ore"
-  result: "gtceu:rhyolite_garnierite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/rhyolite_glauconite_sand_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:rhyolite_glauconite_sand_ore"
-  result: "gtceu:rhyolite_glauconite_sand_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/rhyolite_goethite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:rhyolite_goethite_ore"
-  result: "gtceu:rhyolite_goethite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/rhyolite_gold_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:rhyolite_gold_ore"
-  result: "gtceu:rhyolite_gold_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/rhyolite_granitic_mineral_sand_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:rhyolite_granitic_mineral_sand_ore"
-  result: "gtceu:rhyolite_granitic_mineral_sand_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/rhyolite_graphite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:rhyolite_graphite_ore"
-  result: "gtceu:rhyolite_graphite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/rhyolite_green_sapphire_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:rhyolite_green_sapphire_ore"
-  result: "gtceu:rhyolite_green_sapphire_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/rhyolite_grossular_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:rhyolite_grossular_ore"
-  result: "gtceu:rhyolite_grossular_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/rhyolite_gypsum_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:rhyolite_gypsum_ore"
-  result: "gtceu:rhyolite_gypsum_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/rhyolite_hematite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:rhyolite_hematite_ore"
-  result: "gtceu:rhyolite_hematite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/rhyolite_ilmenite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:rhyolite_ilmenite_ore"
-  result: "gtceu:rhyolite_ilmenite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/rhyolite_iron_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:rhyolite_iron_ore"
-  result: "gtceu:rhyolite_iron_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/rhyolite_kyanite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:rhyolite_kyanite_ore"
-  result: "gtceu:rhyolite_kyanite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/rhyolite_lapis_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:rhyolite_lapis_ore"
-  result: "gtceu:rhyolite_lapis_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/rhyolite_lazurite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:rhyolite_lazurite_ore"
-  result: "gtceu:rhyolite_lazurite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/rhyolite_lead_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:rhyolite_lead_ore"
-  result: "gtceu:rhyolite_lead_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/rhyolite_lepidolite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:rhyolite_lepidolite_ore"
-  result: "gtceu:rhyolite_lepidolite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/rhyolite_lithium_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:rhyolite_lithium_ore"
-  result: "gtceu:rhyolite_lithium_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/rhyolite_magnesite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:rhyolite_magnesite_ore"
-  result: "gtceu:rhyolite_magnesite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/rhyolite_magnetite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:rhyolite_magnetite_ore"
-  result: "gtceu:rhyolite_magnetite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/rhyolite_malachite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:rhyolite_malachite_ore"
-  result: "gtceu:rhyolite_malachite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/rhyolite_mica_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:rhyolite_mica_ore"
-  result: "gtceu:rhyolite_mica_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/rhyolite_molybdenite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:rhyolite_molybdenite_ore"
-  result: "gtceu:rhyolite_molybdenite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/rhyolite_molybdenum_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:rhyolite_molybdenum_ore"
-  result: "gtceu:rhyolite_molybdenum_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/rhyolite_monazite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:rhyolite_monazite_ore"
-  result: "gtceu:rhyolite_monazite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/rhyolite_naquadah_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:rhyolite_naquadah_ore"
-  result: "gtceu:rhyolite_naquadah_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/rhyolite_neodymium_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:rhyolite_neodymium_ore"
-  result: "gtceu:rhyolite_neodymium_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/rhyolite_nether_quartz_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:rhyolite_nether_quartz_ore"
-  result: "gtceu:rhyolite_nether_quartz_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/rhyolite_nickel_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:rhyolite_nickel_ore"
-  result: "gtceu:rhyolite_nickel_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/rhyolite_oilsands_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:rhyolite_oilsands_ore"
-  result: "gtceu:rhyolite_oilsands_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/rhyolite_olivine_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:rhyolite_olivine_ore"
-  result: "gtceu:rhyolite_olivine_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/rhyolite_opal_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:rhyolite_opal_ore"
-  result: "gtceu:rhyolite_opal_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/rhyolite_palladium_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:rhyolite_palladium_ore"
-  result: "gtceu:rhyolite_palladium_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/rhyolite_pentlandite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:rhyolite_pentlandite_ore"
-  result: "gtceu:rhyolite_pentlandite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/rhyolite_pitchblende_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:rhyolite_pitchblende_ore"
-  result: "gtceu:rhyolite_pitchblende_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/rhyolite_platinum_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:rhyolite_platinum_ore"
-  result: "gtceu:rhyolite_platinum_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/rhyolite_plutonium_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:rhyolite_plutonium_ore"
-  result: "gtceu:rhyolite_plutonium_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/rhyolite_pollucite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:rhyolite_pollucite_ore"
-  result: "gtceu:rhyolite_pollucite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/rhyolite_powellite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:rhyolite_powellite_ore"
-  result: "gtceu:rhyolite_powellite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/rhyolite_pyrite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:rhyolite_pyrite_ore"
-  result: "gtceu:rhyolite_pyrite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/rhyolite_pyrochlore_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:rhyolite_pyrochlore_ore"
-  result: "gtceu:rhyolite_pyrochlore_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/rhyolite_pyrolusite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:rhyolite_pyrolusite_ore"
-  result: "gtceu:rhyolite_pyrolusite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/rhyolite_pyrope_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:rhyolite_pyrope_ore"
-  result: "gtceu:rhyolite_pyrope_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/rhyolite_quartzite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:rhyolite_quartzite_ore"
-  result: "gtceu:rhyolite_quartzite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/rhyolite_realgar_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:rhyolite_realgar_ore"
-  result: "gtceu:rhyolite_realgar_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/rhyolite_red_garnet_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:rhyolite_red_garnet_ore"
-  result: "gtceu:rhyolite_red_garnet_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/rhyolite_redstone_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:rhyolite_redstone_ore"
-  result: "gtceu:rhyolite_redstone_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/rhyolite_rock_salt_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:rhyolite_rock_salt_ore"
-  result: "gtceu:rhyolite_rock_salt_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/rhyolite_ruby_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:rhyolite_ruby_ore"
-  result: "gtceu:rhyolite_ruby_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/rhyolite_salt_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:rhyolite_salt_ore"
-  result: "gtceu:rhyolite_salt_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/rhyolite_saltpeter_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:rhyolite_saltpeter_ore"
-  result: "gtceu:rhyolite_saltpeter_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/rhyolite_sapphire_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:rhyolite_sapphire_ore"
-  result: "gtceu:rhyolite_sapphire_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/rhyolite_scheelite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:rhyolite_scheelite_ore"
-  result: "gtceu:rhyolite_scheelite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/rhyolite_silver_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:rhyolite_silver_ore"
-  result: "gtceu:rhyolite_silver_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/rhyolite_soapstone_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:rhyolite_soapstone_ore"
-  result: "gtceu:rhyolite_soapstone_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/rhyolite_sodalite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:rhyolite_sodalite_ore"
-  result: "gtceu:rhyolite_sodalite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/rhyolite_spessartine_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:rhyolite_spessartine_ore"
-  result: "gtceu:rhyolite_spessartine_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/rhyolite_sphalerite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:rhyolite_sphalerite_ore"
-  result: "gtceu:rhyolite_sphalerite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/rhyolite_spodumene_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:rhyolite_spodumene_ore"
-  result: "gtceu:rhyolite_spodumene_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/rhyolite_stibnite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:rhyolite_stibnite_ore"
-  result: "gtceu:rhyolite_stibnite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/rhyolite_sulfur_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:rhyolite_sulfur_ore"
-  result: "gtceu:rhyolite_sulfur_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/rhyolite_talc_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:rhyolite_talc_ore"
-  result: "gtceu:rhyolite_talc_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/rhyolite_tantalite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:rhyolite_tantalite_ore"
-  result: "gtceu:rhyolite_tantalite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/rhyolite_tetrahedrite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:rhyolite_tetrahedrite_ore"
-  result: "gtceu:rhyolite_tetrahedrite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/rhyolite_thorium_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:rhyolite_thorium_ore"
-  result: "gtceu:rhyolite_thorium_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/rhyolite_tin_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:rhyolite_tin_ore"
-  result: "gtceu:rhyolite_tin_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/rhyolite_titanium_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:rhyolite_titanium_ore"
-  result: "gtceu:rhyolite_titanium_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/rhyolite_topaz_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:rhyolite_topaz_ore"
-  result: "gtceu:rhyolite_topaz_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/rhyolite_tricalcium_phosphate_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:rhyolite_tricalcium_phosphate_ore"
-  result: "gtceu:rhyolite_tricalcium_phosphate_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/rhyolite_trona_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:rhyolite_trona_ore"
-  result: "gtceu:rhyolite_trona_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/rhyolite_tungstate_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:rhyolite_tungstate_ore"
-  result: "gtceu:rhyolite_tungstate_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/rhyolite_uraninite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:rhyolite_uraninite_ore"
-  result: "gtceu:rhyolite_uraninite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/rhyolite_vanadium_magnetite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:rhyolite_vanadium_magnetite_ore"
-  result: "gtceu:rhyolite_vanadium_magnetite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/rhyolite_wulfenite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:rhyolite_wulfenite_ore"
-  result: "gtceu:rhyolite_wulfenite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/rhyolite_yellow_garnet_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:rhyolite_yellow_garnet_ore"
-  result: "gtceu:rhyolite_yellow_garnet_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/rhyolite_yellow_limonite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:rhyolite_yellow_limonite_ore"
-  result: "gtceu:rhyolite_yellow_limonite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/rhyolite_zeolite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:rhyolite_zeolite_ore"
-  result: "gtceu:rhyolite_zeolite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/rock_salt_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:rock_salt_ore"
-  result: "gtceu:rock_salt_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/ruby_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:ruby_ore"
-  result: "gtceu:ruby_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/salt_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:salt_ore"
-  result: "gtceu:salt_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/saltpeter_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:saltpeter_ore"
-  result: "gtceu:saltpeter_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/sapphire_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:sapphire_ore"
-  result: "gtceu:sapphire_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/scheelite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:scheelite_ore"
-  result: "gtceu:scheelite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/schist_almandine_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:schist_almandine_ore"
-  result: "gtceu:schist_almandine_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/schist_aluminium_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:schist_aluminium_ore"
-  result: "gtceu:schist_aluminium_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/schist_alunite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:schist_alunite_ore"
-  result: "gtceu:schist_alunite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/schist_amethyst_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:schist_amethyst_ore"
-  result: "gtceu:schist_amethyst_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/schist_apatite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:schist_apatite_ore"
-  result: "gtceu:schist_apatite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/schist_asbestos_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:schist_asbestos_ore"
-  result: "gtceu:schist_asbestos_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/schist_barite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:schist_barite_ore"
-  result: "gtceu:schist_barite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/schist_basaltic_mineral_sand_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:schist_basaltic_mineral_sand_ore"
-  result: "gtceu:schist_basaltic_mineral_sand_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/schist_bastnasite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:schist_bastnasite_ore"
-  result: "gtceu:schist_bastnasite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/schist_bauxite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:schist_bauxite_ore"
-  result: "gtceu:schist_bauxite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/schist_bentonite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:schist_bentonite_ore"
-  result: "gtceu:schist_bentonite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/schist_beryllium_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:schist_beryllium_ore"
-  result: "gtceu:schist_beryllium_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/schist_blue_topaz_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:schist_blue_topaz_ore"
-  result: "gtceu:schist_blue_topaz_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/schist_bornite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:schist_bornite_ore"
-  result: "gtceu:schist_bornite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/schist_calcite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:schist_calcite_ore"
-  result: "gtceu:schist_calcite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/schist_cassiterite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:schist_cassiterite_ore"
-  result: "gtceu:schist_cassiterite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/schist_cassiterite_sand_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:schist_cassiterite_sand_ore"
-  result: "gtceu:schist_cassiterite_sand_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/schist_certus_quartz_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:schist_certus_quartz_ore"
-  result: "gtceu:schist_certus_quartz_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/schist_chalcocite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:schist_chalcocite_ore"
-  result: "gtceu:schist_chalcocite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/schist_chalcopyrite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:schist_chalcopyrite_ore"
-  result: "gtceu:schist_chalcopyrite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/schist_chromite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:schist_chromite_ore"
-  result: "gtceu:schist_chromite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/schist_cinnabar_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:schist_cinnabar_ore"
-  result: "gtceu:schist_cinnabar_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/schist_coal_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:schist_coal_ore"
-  result: "gtceu:schist_coal_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/schist_cobalt_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:schist_cobalt_ore"
-  result: "gtceu:schist_cobalt_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/schist_cobaltite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:schist_cobaltite_ore"
-  result: "gtceu:schist_cobaltite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/schist_cooperite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:schist_cooperite_ore"
-  result: "gtceu:schist_cooperite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/schist_copper_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:schist_copper_ore"
-  result: "gtceu:schist_copper_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/schist_diamond_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:schist_diamond_ore"
-  result: "gtceu:schist_diamond_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/schist_diatomite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:schist_diatomite_ore"
-  result: "gtceu:schist_diatomite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/schist_electrotine_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:schist_electrotine_ore"
-  result: "gtceu:schist_electrotine_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/schist_emerald_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:schist_emerald_ore"
-  result: "gtceu:schist_emerald_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/schist_fullers_earth_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:schist_fullers_earth_ore"
-  result: "gtceu:schist_fullers_earth_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/schist_galena_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:schist_galena_ore"
-  result: "gtceu:schist_galena_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/schist_garnet_sand_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:schist_garnet_sand_ore"
-  result: "gtceu:schist_garnet_sand_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/schist_garnierite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:schist_garnierite_ore"
-  result: "gtceu:schist_garnierite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/schist_glauconite_sand_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:schist_glauconite_sand_ore"
-  result: "gtceu:schist_glauconite_sand_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/schist_goethite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:schist_goethite_ore"
-  result: "gtceu:schist_goethite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/schist_gold_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:schist_gold_ore"
-  result: "gtceu:schist_gold_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/schist_granitic_mineral_sand_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:schist_granitic_mineral_sand_ore"
-  result: "gtceu:schist_granitic_mineral_sand_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/schist_graphite_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:schist_graphite_ore"
-  result: "gtceu:schist_graphite_ore"
-}

```


</details>

<details>
<summary>gtceu/collapse/schist_green_sapphire_ore</summary>

```diff
-{
-  type: "tfc:collapse"
-  ingredient: "gtceu:schist_green_sapphire_ore"
-}
