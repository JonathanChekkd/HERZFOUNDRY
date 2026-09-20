# Graph Report - https-herzfoundry-github-io-herzfoundry-contact  (2026-09-20)

## Corpus Check
- Large corpus: 30 files · ~689,763 words. Semantic extraction will be expensive (many Claude tokens). Consider running on a subfolder.

## Summary
- 75 nodes · 70 edges · 17 communities (10 shown, 7 thin omitted)
- Extraction: 64% EXTRACTED · 34% INFERRED · 1% AMBIGUOUS · INFERRED: 24 edges (avg confidence: 0.85)
- Token cost: 0 input · 0 output

## Community Hubs (Navigation)
- Portfolio Experience
- Client Mark Variants
- Beverage Production Study
- Production Workflow
- Camera Production Study
- Interactive 3D System
- GitHub Pages Delivery
- Beverage Visuals
- Vapor Product Visuals
- Gaming Product Visuals
- Client Graphic Placeholders
- Skincare Product Visual
- Creator Portrait
- Headphone Product Visual
- Camera Product Visual
- HERZ Brand Mark
- Audio Transcript Fragment

## God Nodes (most connected - your core abstractions)
1. `Green V Client Banner` - 8 edges
2. `HERZ FOUNDRY` - 6 edges
3. `Production Workflow` - 6 edges
4. `3D Visualization` - 4 edges
5. `Motion Systems` - 4 edges
6. `Completed Beverage Product Shot` - 4 edges
7. `Beverage Scene Clay Preview` - 4 edges
8. `Deploy Static Content to Pages` - 3 edges
9. `Concept Development` - 3 edges
10. `Production and Development` - 3 edges

## Surprising Connections (you probably didn't know these)
- `3D Visualization and Paragraph Breaks` --semantically_similar_to--> `3D Visualization`  [INFERRED] [semantically similar]
  graphify-out/transcripts/video2.txt → index.html
- `3D Visualization` --semantically_similar_to--> `3D Visualization`  [INFERRED] [semantically similar]
  graphify-out/transcripts/video4.txt → index.html
- `Viewer Thanks` --conceptually_related_to--> `Motion Systems`  [AMBIGUOUS]
  graphify-out/transcripts/video3.txt → index.html
- `Blank White Client Banner` --semantically_similar_to--> `Green V Client Banner`  [INFERRED] [semantically similar]
  assets/client1.png → assets/client2.png
- `Empty Transparent Client Banner` --semantically_similar_to--> `Green V Client Banner`  [INFERRED] [semantically similar]
  assets/client10.png → assets/client2.png

## Import Cycles
- None detected.

## Hyperedges (group relationships)
- **Six-Stage Production Workflow** — index_discovery_and_direction, index_concept_development, index_production_and_development, index_post_production_and_editing, index_asset_delivery, index_refinement_and_revision [EXTRACTED 1.00]
- **Core Creative Services** — index_product_animation, index_cgi_ad_creative, index_3d_visualization [EXTRACTED 1.00]
- **Beverage Scene Before and After Workflow** — assets_before1_beverage_scene_clay_preview, assets_before1_untextured_can_geometry, assets_after1_completed_beverage_product_shot, assets_after1_branded_beverage_can [INFERRED 0.95]
- **Action Camera Scene Before and After Workflow** — assets_before2_action_camera_clay_preview, assets_before2_untextured_camera_model, assets_after2_completed_action_camera_product_shot, assets_after2_insta360_x5_camera [INFERRED 0.95]
- **Client Banner Asset Set** — assets_client1_blank_white_client_banner, assets_client10_empty_transparent_client_banner, assets_client2_green_v_client_banner, assets_client3_empty_transparent_client_banner, assets_client4_empty_transparent_client_banner, assets_client5_empty_transparent_client_banner, assets_client6_empty_transparent_client_banner, assets_client7_empty_transparent_client_banner [INFERRED 0.75]
- **JOIWAY product campaign** — assets_image4_joiway_vaporizer, assets_image4_designed_to_flow, assets_thumbnail_video3_joiway_vaporizer [INFERRED 0.85]
- **DI MENZO fruit product campaign** — assets_image2_di_menzo_energy_drink, assets_image2_fruit_still_life_staging, assets_thumbnail_video4_di_menzo_energy_drink, assets_thumbnail_video4_fruit_still_life_staging [INFERRED 0.95]
- **Product visualization portfolio** — assets_image1_arrancare_nocturnal_repair_serum, assets_image2_di_menzo_energy_drink, assets_image3_gaming_mouse, assets_image4_joiway_vaporizer, assets_thumbnail_video1_over_ear_headphones, assets_thumbnail_video2_insta360_x5_camera [INFERRED 0.75]

## Communities (17 total, 7 thin omitted)

### Community 0 - "Portfolio Experience"
Cohesion: 0.20
Nodes (10): Viewer Thanks, Bayu Hermawan, CGI Ad Creative, Contact Channels, Google Analytics, HERZ FOUNDRY, Interactive Media Controls, Motion Systems (+2 more)

### Community 1 - "Client Mark Variants"
Cohesion: 0.22
Nodes (9): Empty Transparent Client Banner, Blank White Client Banner, Green V Client Banner, Green V Mark, Empty Transparent Client Banner, Empty Transparent Client Banner, Empty Transparent Client Banner, Empty Transparent Client Banner (+1 more)

### Community 2 - "Beverage Production Study"
Cohesion: 0.36
Nodes (8): Branded Beverage Can, Citrus and Strawberry Props, Completed Beverage Product Shot, Dark Foliage Environment, Beverage Scene Clay Preview, Foliage Geometry, Untextured Can Geometry, Untextured Fruit Props

### Community 3 - "Production Workflow"
Cohesion: 0.52
Nodes (7): Asset Delivery, Concept Development, Discovery and Direction, Post-Production and Editing, Production and Development, Production Workflow, Refinement and Revision

### Community 4 - "Camera Production Study"
Cohesion: 0.47
Nodes (6): Completed Action Camera Product Shot, Insta360 X5 Camera, Rain and Water Droplets, Action Camera Clay Preview, Untextured Camera Model, Water Droplet Simulation

### Community 5 - "Interactive 3D System"
Cohesion: 0.33
Nodes (6): 3D Visualization and Paragraph Breaks, 3D Visualization, 3D Visualization, Logo GLTF Model, Three.js Auto-Rotating Viewport, Visibility-Optimized Rendering

### Community 6 - "GitHub Pages Delivery"
Cohesion: 0.40
Nodes (5): Deploy Static Content to Pages, GitHub Pages Environment, Main Branch Push Trigger, GitHub Pages Deployment Actions, Pages Token Permissions

### Community 7 - "Beverage Visuals"
Cohesion: 0.67
Nodes (4): DI MENZO energy drink can, Fruit still-life product staging, DI MENZO energy drink can, Fruit still-life product staging

### Community 8 - "Vapor Product Visuals"
Cohesion: 0.50
Nodes (4): Designed to Flow, JOIWAY vaporizer device, JOIWAY vaporizer device, Vapor product render

### Community 9 - "Gaming Product Visuals"
Cohesion: 0.67
Nodes (3): Gaming mouse, High-speed gaming visual, Wireless mouse status receiver

## Ambiguous Edges - Review These
- `Motion Systems` → `Viewer Thanks`  [AMBIGUOUS]
  graphify-out/transcripts/video3.txt · relation: conceptually_related_to

## Knowledge Gaps
- **38 isolated node(s):** `Main Branch Push Trigger`, `GitHub Pages Environment`, `Pages Token Permissions`, `Bayu Hermawan`, `CGI Ad Creative` (+33 more)
  These have ≤1 connection - possible missing edges or undocumented components. (Counts symbols only; 39 node(s) total have ≤1 connection when file, concept and rationale nodes are included.)
- **7 thin communities (<3 nodes) omitted from report** — run `graphify query` to explore isolated nodes.

## Suggested Questions
_Questions this graph is uniquely positioned to answer:_

- **What is the exact relationship between `Motion Systems` and `Viewer Thanks`?**
  _Edge tagged AMBIGUOUS (relation: conceptually_related_to) - confidence is low._
- **Why does `HERZ FOUNDRY` connect `Portfolio Experience` to `Interactive 3D System`?**
  _High betweenness centrality (0.030) - this node is a cross-community bridge._
- **Why does `3D Visualization` connect `Interactive 3D System` to `Portfolio Experience`?**
  _High betweenness centrality (0.021) - this node is a cross-community bridge._
- **Are the 7 inferred relationships involving `Green V Client Banner` (e.g. with `Empty Transparent Client Banner` and `Blank White Client Banner`) actually correct?**
  _`Green V Client Banner` has 7 INFERRED edges - model-reasoned connections that need verification._
- **Are the 3 inferred relationships involving `3D Visualization` (e.g. with `3D Visualization and Paragraph Breaks` and `3D Visualization`) actually correct?**
  _`3D Visualization` has 3 INFERRED edges - model-reasoned connections that need verification._
- **What connects `Main Branch Push Trigger`, `GitHub Pages Environment`, `Pages Token Permissions` to the rest of the system?**
  _38 weakly-connected nodes found - possible documentation gaps or missing edges._