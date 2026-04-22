# Graph Report - .  (2026-04-21)

## Corpus Check
- 24 files · ~257,301 words
- Verdict: corpus is large enough that graph structure adds value.

## Summary
- 47 nodes · 37 edges · 16 communities detected
- Extraction: 100% EXTRACTED · 0% INFERRED · 0% AMBIGUOUS
- Token cost: 0 input · 0 output

## Community Hubs (Navigation)
- [[_COMMUNITY_Forum Walk Branding|Forum Walk Branding]]
- [[_COMMUNITY_DesignOne Form Flow|DesignOne Form Flow]]
- [[_COMMUNITY_Prestige Group Branding|Prestige Group Branding]]
- [[_COMMUNITY_API Submit Handler|API Submit Handler]]
- [[_COMMUNITY_Forum Logo & Enterprise|Forum Logo & Enterprise]]
- [[_COMMUNITY_DesignTwo Form Flow|DesignTwo Form Flow]]
- [[_COMMUNITY_Dev Server (JS)|Dev Server (JS)]]
- [[_COMMUNITY_Dev Server (TS)|Dev Server (TS)]]
- [[_COMMUNITY_App Entry Point|App Entry Point]]
- [[_COMMUNITY_Header Component|Header Component]]
- [[_COMMUNITY_Vite Config|Vite Config]]
- [[_COMMUNITY_Vite Env Types|Vite Env Types]]
- [[_COMMUNITY_Survey Data|Survey Data]]
- [[_COMMUNITY_Prestige Logo (Asset)|Prestige Logo (Asset)]]
- [[_COMMUNITY_Mall Exterior Render|Mall Exterior Render]]
- [[_COMMUNITY_Prestige Logo (srcassets)|Prestige Logo (src/assets)]]

## God Nodes (most connected - your core abstractions)
1. `Forum Walk Mulund Banner Image` - 6 edges
2. `handler()` - 4 edges
3. `Prestige Group Logo` - 4 edges
4. `Prestige Group (Brand)` - 3 edges
5. `Forum Logo (Prestige Group Enterprise)` - 3 edges
6. `mapIds()` - 2 edges
7. `formatBrands()` - 2 edges
8. `getCredentials()` - 2 edges
9. `submitToGoogleSheet()` - 2 edges
10. `nextStep()` - 2 edges

## Surprising Connections (you probably didn't know these)
- None detected - all connections are within the same source files.

## Communities

### Community 0 - "Forum Walk Branding"
Cohesion: 0.33
Nodes (7): Forum Walk Logo (English and Devanagari), Visible Retail Storefront Signage, Forum Walk Mulund Banner Image, Hero/Header Image for Survey Form, Forum Walk Mall (Mulund), Text: 'forum walk' / 'फोरम वॉक', Architectural Render of Glass-Facade Mall with Adjacent High-Rise

### Community 1 - "DesignOne Form Flow"
Cohesion: 0.4
Nodes (2): nextStep(), submitToGoogleSheet()

### Community 2 - "Prestige Group Branding"
Cohesion: 0.4
Nodes (6): Prestige Group (Brand), Black and Gold Color Scheme, Golden Eagle Emblem, Real Estate / Property Development, Prestige Group Logo, Add Prestige to your life

### Community 3 - "API Submit Handler"
Cohesion: 0.7
Nodes (4): formatBrands(), getCredentials(), handler(), mapIds()

### Community 4 - "Forum Logo & Enterprise"
Cohesion: 0.4
Nodes (5): Forum Brand, Colorful Butterfly Logo Mark, Forum Logo (Prestige Group Enterprise), Prestige Group, A Prestige Group Enterprise Tagline

### Community 5 - "DesignTwo Form Flow"
Cohesion: 0.5
Nodes (0): 

### Community 6 - "Dev Server (JS)"
Cohesion: 1.0
Nodes (0): 

### Community 7 - "Dev Server (TS)"
Cohesion: 1.0
Nodes (0): 

### Community 8 - "App Entry Point"
Cohesion: 1.0
Nodes (0): 

### Community 9 - "Header Component"
Cohesion: 1.0
Nodes (0): 

### Community 10 - "Vite Config"
Cohesion: 1.0
Nodes (0): 

### Community 11 - "Vite Env Types"
Cohesion: 1.0
Nodes (0): 

### Community 12 - "Survey Data"
Cohesion: 1.0
Nodes (0): 

### Community 13 - "Prestige Logo (Asset)"
Cohesion: 1.0
Nodes (1): Prestige Group Logo

### Community 14 - "Mall Exterior Render"
Cohesion: 1.0
Nodes (1): Forum Walk Mulund Mall Exterior Rendering

### Community 15 - "Prestige Logo (src/assets)"
Cohesion: 1.0
Nodes (1): Prestige Group Logo (src/assets)

## Knowledge Gaps
- **13 isolated node(s):** `Add Prestige to your life`, `Black and Gold Color Scheme`, `Real Estate / Property Development`, `Prestige Group Logo`, `Forum Walk Mulund Mall Exterior Rendering` (+8 more)
  These have ≤1 connection - possible missing edges or undocumented components.
- **Thin community `Dev Server (JS)`** (2 nodes): `server.js`, `formatEntries()`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Dev Server (TS)`** (2 nodes): `server.ts`, `parseBrands()`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `App Entry Point`** (2 nodes): `App.tsx`, `main.tsx`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Header Component`** (2 nodes): `Header.tsx`, `Header()`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Vite Config`** (1 nodes): `vite.config.ts`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Vite Env Types`** (1 nodes): `vite-env.d.ts`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Survey Data`** (1 nodes): `survey.ts`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Prestige Logo (Asset)`** (1 nodes): `Prestige Group Logo`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Mall Exterior Render`** (1 nodes): `Forum Walk Mulund Mall Exterior Rendering`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Prestige Logo (src/assets)`** (1 nodes): `Prestige Group Logo (src/assets)`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.

## Suggested Questions
_Questions this graph is uniquely positioned to answer:_

- **What connects `Add Prestige to your life`, `Black and Gold Color Scheme`, `Real Estate / Property Development` to the rest of the system?**
  _13 weakly-connected nodes found - possible documentation gaps or missing edges._