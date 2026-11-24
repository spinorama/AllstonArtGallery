# 🏛️ Allston Art Gallery Pavilion — Architectural Editorial Hybrid WebXR Gallery

An interactive **Architectural Editorial Hybrid Multi-Model WebXR Gallery** combining a two-wing **Allston Art Gallery Pavilion** (`14.0m × 15.0m × 3.85m`) with full-screen **Editorial Soft-PBR + Whisper Ink**, **glTF `extras` Interactive Rigs**, **Live Horizontal Z-Cut**, and **4-Mode WebXR** inspection across 6 live architectural & motorsport exhibits (plus drag-and-drop local `.glb`/`.gltf` support).

**Live Gallery:** https://spinorama.github.io/AllstonArtGallery/

---

## ✨ Two-Wing Allston Pavilion Architecture
- **Front Storefront Wing (Inspired by Allston Night Storefront):**
  - 7-bay floor-to-ceiling black anodized glass curtain wall, interactive sliding glass entry door (`[O]`), circular steel `"ALLSTON"` bike rack, low walnut street benches, framing trees, stepped weathered-bronze feature wall, center glass pass-through window, and 7 illuminated terracotta ceramic plates.
  - **6 Museum Pedestals with Live Miniature GitHub Displays:** Asynchronously streams live miniature `.glb` displays (`9-Tsubo House`, `Massaro House`, `F1 COTA Austin`, `F1 Tabletop Track`) straight onto the storefront vitrine plinths. Click any plinth (or its 3D pin, or laser+Trigger in Quest VR) to open that model in full-scale Editorial Hybrid WebXR.
- **Darker Rear Gallery Behind the Wall (Media, Photography & Sculpture Vault):**
  - Walk through the West or East passage behind the dividing wall into an atmospheric obsidian-and-slate gallery featuring:
    - **3 Live Animated Placeholder Video Projection Screens (`V-01`–`V-03`):** Large North Wall cinema projection (`4.8m × 2.65m`), West Wall vertical media display, and rear partition horizontal archive loop monitor.
    - **6 Curated Framed Placeholder Pictures (`P-01`–`P-06`)** with brushed brass picture lights.
    - **4 Pin-Spotlit Placeholder Statues (`S-01`–`S-04`):** Alabaster Modernist Bust, Twisted Patinated Bronze Knot, Obsidian & Brass Totem, and Luminous Amber Glass Prism.
  - All placeholder works are centralized in `DARK_GALLERY_PLACEHOLDERS` in [index.html](./index.html) so they can be swapped for your own videos, photographs, and 3D sculptures at any time.

---

## 🎨 Architectural Editorial Hybrid System (Three.js `0.170.0`)
- **Studio IBL & Whisper Ink:** `PMREMGenerator` + `RoomEnvironment`, `ACESFilmicToneMapping`, `PCFSoftShadowMap`, and cached `EdgesGeometry` (`28°`/`32°`) linework.
- **4 Switchable Visual Styles (`[V]`):** `✨ Editorial`, `☀️ Soft-PBR`, `✏️ Paper CAD`, and `📐 Blueprint`.
- **4 Lighting Moods (`[F]`):** `☀️ Day`, `🌅 Golden`, `🌙 Evening` *(Pavilion default)*, and `🏛️ Studio`.
- **Verified Same-Origin Live Exhibits (`gallery_models.json`):**
  1. **9-Tsubo House (Koizumi Studio, 1999 — Pass 2 Pocket Doors)** — 16 glTF `extras` interactive rigs + curated interior shots.
  2. **Massaro House (Petra Island, Mahopac NY)**
  3. **American Midwestern Modern House**
  4. **Victorian House (Murder House & Coven Edition)**
  5. **F1 COTA Austin** *(animated track)*
  6. **F1 Tabletop Track**
  7. **Universal Drag & Drop + `+ GLB` Picker** for any local `.glb`/`.gltf`.
- **Spatial & WebXR Suite:** Live Horizontal `✂️ Z-Cut` (`5%–100%`), Exploded Axonometric, `🏠 Roof` / `🌳 Site` layer toggles, `3D Studio`, `Quest VR` (world-space 3D Command HUD, parabolic floor teleport, thumbsticks, laser+Trigger door & plinth interaction), `1:1 AR Walk`, and `Tabletop AR`.
