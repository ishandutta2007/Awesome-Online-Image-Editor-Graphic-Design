# Awesome-Online-Image-Editor-Graphic-Design

# Awesome Online Image Editor & Graphic Design

> A curated list of top Online Image Editor and Graphic Design platforms — both SaaS/Hosted commercial solutions and open-source alternatives for editing photos, creating social graphics, and designing visual content in the browser.
> 🌟 Star this repo if you find it useful! 🌟

---

## 📋 Table of Contents

- [SaaS / Hosted Platforms](#-saas--hosted-platforms)
  - [Canva](#canva)
  - [Adobe Express](#adobe-express)
  - [Pixlr](#pixlr)
  - [Fotor](#fotor)
  - [Photopea](#photopea)
  - [PicMonkey](#picmonkey)
  - [BeFunky](#befunky)
  - [Polarr](#polarr)
  - [Snappa](#snappa)
  - [VistaCreate](#vistacreate)
- [Open-Source Software](#-open-source-software)
  - [Doory](#doory)
  - [miniPaint](#minipaint)
  - [Pentrado](#pentrado)
  - [OpenShop](#openshop)
  - [Pixra](#pixra)
  - [Penpot](#penpot)
  - [Krita](#krita)
  - [Inkscape](#inkscape)
  - [GIMP](#gimp)

---

## 🟦 SaaS / Hosted Platforms

Commercial, cloud-hosted image editing and graphic design platforms. These are not open-source but are included as reference points for feature comparison.

### Canva
**Type:** Template-driven graphic design platform
Canva is the dominant commercial design platform, offering thousands of templates for social media, presentations, posters, and more, with drag-and-drop editing and brand kits. It is positioned for non-designers wanting professional-looking graphics quickly.

### Adobe Express
**Type:** All-in-one creative app with Adobe ecosystem integration
Adobe Express provides template-based design, photo editing, and video creation with access to Adobe Fonts and Stock. It is positioned for users wanting Adobe-grade assets in a simplified interface.

### Pixlr
**Type:** Browser-based photo editor with AI tools
Pixlr offers a suite of editing tools including Pixlr X (quick edits) and Pixlr E (advanced editing), with AI-powered features like background removal and generative fill. It is positioned for quick browser-based photo manipulation.

### Fotor
**Type:** Photo editing and design platform
Fotor combines photo editing, collage creation, and design templates with AI features. It is positioned for users wanting an accessible all-in-one editing and design tool.

### Photopea
**Type:** Advanced browser-based image editor with PSD support
Photopea is a free online editor supporting **PSD, AI, Sketch, XD, and CDR** files, along with raster formats including PNG, JPG, WebP, and HEIC [citation:1]. Despite its free availability, it is **not fully open-source**—its GitHub repository serves only as a bug tracker and discussion forum [citation:1]. It is the closest browser-based equivalent to Photoshop, with layers, masks, filters, and vector tools.  
**Best for:** Users needing advanced PSD-compatible editing without installing desktop software, accepting that the underlying code is proprietary.

### PicMonkey
**Type:** Photo editing and design tool
PicMonkey provides photo editing, collage making, and design templates with a focus on ease of use. It is positioned for small businesses and creatives wanting straightforward editing and design.

### BeFunky
**Type:** Photo editing and graphic design
BeFunky offers photo editing, collage creation, and design templates, with a focus on creative effects and easy-to-use tools. It is positioned for casual users and small teams.

### Polarr
**Type:** AI-powered photo editing
Polarr specializes in photo editing with AI features, including auto-enhancement, portrait retouching, and filters. It is positioned for photographers wanting browser-based editing with advanced adjustment controls.

### Snappa
**Type:** Quick graphic design for social media
Snappa focuses on creating social media graphics, headers, and ads with templates and a simple editor. It is positioned for marketers and small businesses needing fast visual content.

### VistaCreate
**Type:** Template-based design platform
VistaCreate (formerly Crello) provides templates for social media, marketing, and print designs with an easy-to-use editor. It is positioned for non-designers wanting quick, attractive visuals.

---

## 🟩 Open-Source Software

Self-hosted, community-driven image editing and graphic design tools. The open-source ecosystem spans **Canva alternatives with template libraries**, **browser-based Photoshop alternatives**, **professional-grade desktop editors**, and **UI/UX design platforms**.

### Doory
**Stack:** React / TypeScript / Fabric.js / Django / PostgreSQL | **License:** Attribution Assurance License (AAL) 
Doory is an open-source **Canva alternative** that runs in the browser and can be self-hosted via Docker or without it [citation:2][citation:7]. Key capabilities include:
- **Design types**: Posters, social posts, stories, slides, invitations, resumes, thumbnails, and business cards 
- **Editing**: Layers, groups, masks, filters, text with curved text and effects, 27,500+ icons, shapes, QR codes, background removal, and 2×–4× upscaling 
- **Motion**: 27 enter/exit animations, 12 emphasis animations, 16 page transitions, music loops, sound effects, and voiceover recording 
- **Collaboration**: Real-time co-editing, comments, version history, brand kits, and share links with view/comment/edit permissions 
- **Export**: PNG, JPG, SVG, PDF, MP4, WebM, and GIF 
- **MCP support**: AI assistants can create and edit designs via Model Context Protocol 

**Important:** The **Attribution Assurance License** permits commercial use but requires a visible credit to the author in the running app [citation:7]. The template library is small (ten starter templates), but everything is editable and admins can add more [citation:2].  
**Best for:** Teams wanting a self-hosted Canva alternative with real-time collaboration and motion design, accepting the attribution requirement and smaller template library.

### miniPaint
**Stack:** JavaScript / HTML5 | **License:** MIT 
miniPaint is a free, open-source **browser-based image editor** that operates entirely client-side—nothing is sent to a server, and it works offline via service workers after initial load [citation:14][citation:15]. Key capabilities include:
- **Layers**: Multi-layer system with transparency, merging, flattening, and JSON layer export 
- **Tools**: Pencil, brush, magic wand, eraser, fill, color picker, text, crop, blur, clone, borders, and more 
- **Effects**: Blur variants, denoise, oil painting, solarize, tilt-shift, vignette, and Instagram-style filters 
- **Formats**: Open/save PNG, JPG, BMP, WEBP, animated GIF, TIFF, and JSON 
- **Self-hostable**: Can be embedded or deployed independently 

**Trade-off:** Selection tools are limited to a rectangle (no lasso), masking requires menu navigation, and it lacks smart objects and advanced typography [citation:15].  
**Best for:** Users wanting a lightweight, privacy-respecting Photoshop alternative for quick edits, mockups, and social graphics that works offline.

### Pentrado
**Stack:** Vue 3 / TypeScript / WebGL | **License:** Open Source (per repository) 
Pentrado is an open-source **layered raster/vector image editor for the web**, built as an embeddable library and positioned in the class of GIMP, Photoshop, and Photopea [citation:5]. Key characteristics:
- **Pure TypeScript engine**: Scene-graph document model (raster, text, vector, adjustment, fill, group nodes, masks), command-based undo history, WebGL compositor with full blend modes, and non-destructive layer effects 
- **PSD import/export**: Via `ag-psd` 
- **Embeddable**: Host contract (`PentradoHost`) lets you integrate it into your own app, with built-in fallbacks for standalone use 
- **Standalone editor**: Available at pentrado.com with IndexedDB persistence 

**Trade-off:** It is a library/engine rather than a finished consumer product—integration requires Vue 3 and development effort.  
**Best for:** Developers wanting to embed a capable, Photoshop-class editor into their own web application, accepting the integration effort.

### OpenShop
**Stack:** JavaScript / Browser | **License:** Open Source (per repository) 
OpenShop is an open-source **private browser image editor** with layers, PSD interchange, and local export—no account, no telemetry, and no editing server [citation:9]. Key capabilities:
- **Layered editing**: Nested groups, raster masks, adjustment layers, editable vectors, per-range text styling, and Smart Objects 
- **Precise selection**: Marquee, lasso, magnetic lasso, Quick Selection, Magic Wand, Color Range, and Refine Edge 
- **Format support**: Import/export PNG, JPEG, WebP, AVIF, SVG, PDF, PSD, OpenRaster, and GIF; import HEIC, JPEG XL, and camera RAW 
- **Offline**: Installable PWA or portable single HTML file 
- **Automation**: Record and replay actions, process folders to ZIP 
- **Local AI**: Background removal, depth maps, object detection, and upscaling run in the browser 

**Trade-off:** The portable HTML file requires an initial connection to fetch core libraries from a CDN.  
**Best for:** Users wanting a privacy-first, offline-capable editor with PSD support and no cloud dependency.

### Pixra
**Stack:** TypeScript / Web | **License:** AGPL-3.0 (core) / MIT (plugin SDK) 
Pixra is an open-source, extensible **web-based image editor** with basic editing (crop, resize, brush, marquee selection), multi-tab support, undo/redo, and export to PNG/JPEG/WEBP [citation:4]. Its distinguishing feature is a **plugin system** for custom tools, with the plugin SDK and CLI licensed under MIT to encourage ecosystem development.  
**Best for:** Developers wanting an extensible editor foundation they can build custom tools into, accepting a basic core feature set.

### Penpot
**Stack:** Clojure / ClojureScript | **License:** MPL-2.0 
Penpot is a fully open-source **design and prototyping platform** positioned as a Figma alternative, built by Kaleidos [citation:3]. Key capabilities include UI design, interactive prototyping, component libraries, CSS Grid layout generation, native design tokens (W3C specification), and a free Inspect tab for developer handoff [citation:3]. It runs in the browser or can be self-hosted.  
**Best for:** UI/UX designers and product teams wanting a self-hostable Figma alternative with strong developer handoff and design tokens.

### Krita
**Stack:** C++ / Qt | **License:** GPL-3.0 
Krita is a professional-grade open-source **digital painting** application, available for Windows, macOS, Linux, Android, and ChromeOS [citation:3]. It features an OpenGL-accelerated canvas, non-destructive layers and masks, and a brush engine with **nine different engines and over 100 presets** covering watercolor, oil, charcoal, and more [citation:3]. It is positioned for digital artists and illustrators rather than general graphic design.  
**Best for:** Digital painters and illustrators needing a powerful, free alternative to Photoshop's painting tools.

### Inkscape
**Stack:** C++ / GTK | **License:** GPL-3.0 
Inkscape is the leading open-source **vector graphics editor**, positioned as an Illustrator alternative [citation:3][citation:13]. It uses **SVG as its native format**, with precise path editing, node manipulation, boolean operations, text-on-path, and a robust object management system [citation:13]. It is available cross-platform and supports extensions and plugins for automation.  
**Best for:** Designers creating logos, icons, illustrations, and any vector-based work without Adobe licensing costs.

### GIMP
**Stack:** C / GTK | **License:** GPL-3.0 
GIMP (GNU Image Manipulation Program) is the long-standing open-source **raster image editor**, positioned as a Photoshop alternative [citation:13]. It offers advanced layer and mask management, a full suite of selection tools, healing and clone tools, blend modes, filters, and extensive plugin support (including GMIC). It supports high-resolution files and multiple color spaces. **Trade-off:** It lacks smart objects and adjustment layers, and the interface is less polished than commercial alternatives [citation:13].  
**Best for:** Photographers and designers needing a comprehensive, free raster editor with strong plugin extensibility.

---

## 📊 Comparison at a Glance

| Software | License | Stack | Browser-Based | PSD Support | Self-Hosted | Best For |
|----------|---------|-------|---------------|-------------|-------------|----------|
| **Canva** | Proprietary | Cloud | ✅ | ❌ | ❌ | Template-driven design |
| **Photopea** | Proprietary | Browser | ✅ | ✅ | ❌ | Advanced PSD editing |
| **Doory** | AAL | React/Django | ✅ | ❌ | ✅ | Canva alternative + motion |
| **miniPaint** | MIT | JavaScript | ✅ | ❌ | ✅ | Lightweight offline editor |
| **Pentrado** | Open Source | Vue/WebGL | ✅ | ✅ | ✅ (Library) | Embeddable editor engine |
| **OpenShop** | Open Source | Browser | ✅ | ✅ | ✅ (PWA) | Privacy-first offline editing |
| **Pixra** | AGPL/MIT | TypeScript | ✅ | ❌ | ✅ | Extensible plugin editor |
| **Penpot** | MPL-2.0 | Clojure | ✅ | ❌ | ✅ | UI/UX design + handoff |
| **Krita** | GPL-3.0 | C++/Qt | ❌ (Desktop) | (Check) | ✅ (Desktop) | Digital painting |
| **Inkscape** | GPL-3.0 | C++/GTK | ❌ (Desktop) | ❌ (SVG native) | ✅ (Desktop) | Vector graphics |
| **GIMP** | GPL-3.0 | C/GTK | ❌ (Desktop) | (Check) | ✅ (Desktop) | Full raster editing |

---

## 🤝 Contributing

Contributions are welcome! If you know of an open-source online image editor or graphic design tool that should be listed here, please open a pull request with:

- Project name and URL
- Brief description (1–2 sentences)
- Stack and license
- Why it stands out

Please ensure the project is actively maintained (releases within the last 12 months) and genuinely open-source.

**Note on the open-source ecosystem:** The open-source landscape for **online image editing and graphic design** splits between **Canva-style template editors** (Doory, with real-time collaboration and motion design), **browser-based Photoshop alternatives** (miniPaint, OpenShop, Pentrado), and **professional desktop tools** (Krita for painting, Inkscape for vectors, GIMP for raster) [citation:2][citation:9][citation:13]. **Doory** is the most complete open-source Canva alternative, though its Attribution Assurance License requires visible credit [citation:7]. **miniPaint** is the best choice for a lightweight, offline-capable editor [citation:15], while **OpenShop** offers stronger PSD support and privacy guarantees [citation:9]. **Pentrado** provides an embeddable engine for developers [citation:5]. For professional work, **Krita**, **Inkscape**, and **GIMP** remain the open-source standards, though they are desktop applications rather than browser-based [citation:13]. **Photopea** is a popular free browser editor but is **not open-source**—its GitHub repo is only for issue tracking [citation:1].

---

## 📄 License

This list is released under CC0 1.0 Universal (Public Domain). The software projects listed retain their respective licenses.

---

⭐ **If this list helped you discover a useful tool, please star the repo!** ⭐
