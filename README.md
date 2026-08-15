# 🎨 Ultimate AI Media Generation Tools Master List (2025-2026)

**Last Updated:** June 24, 2026 (primary-source verification refresh)

**Coverage:** 198+ catalogue entries/references across image, video, audio, voice, 3D, enhancement, and multimodal platforms

> **Verification standard:** Every line in the April 22 repository README was processed during this audit. Fast-changing product/version/status claims were checked against first-party release notes, model pages, changelogs, documentation, and official company blogs through June 24, 2026. Editorial rankings and prices are explicitly treated as snapshots, not permanent facts.

> **Status labels:** **GA** = generally available; **Preview/Beta** = subject to change; **Announced** = not necessarily released; **Legacy** = still historically relevant but no longer the preferred current model; **Unverified** = no adequate first-party confirmation found and therefore not presented as fact.

---

### ⚠️ **CRITICAL STATUS UPDATE: Sora (OpenAI)**

**OpenAI discontinued Sora consumer web/app access on April 26, 2026.**

- **Web/App access:** Discontinued April 26, 2026
- **API access:** Scheduled to shut down September 24, 2026
- **Current status (June 24, 2026):** Do not list Sora as an available consumer recommendation
- **Migration:** Exported projects must be moved to another workflow; API users should plan migration before the September shutdown
- **Official source:** https://help.openai.com/en/articles/20001152-what-to-know-about-the-sora-discontinuation

---

## ✅ **June 2026 Verified Refresh — Major Missing/Changed Items**

| Area              | Verified current item                          | Change from April snapshot                                     |
| ----------------- | ---------------------------------------------- | -------------------------------------------------------------- |
| OpenAI images     | GPT Image 2 / ChatGPT Images 2.0               | DALL·E 3 moved to legacy context                               |
| Google images     | Gemini 3.1 Flash Image + Gemini 3 Pro Image GA | Imagen 4 API deprecated; shutdown scheduled Aug. 17, 2026      |
| Microsoft images  | MAI-Image-2.5                                  | Released June 2, replacing MAI-Image-2 as current flagship     |
| Ideogram          | Ideogram 4.0                                   | Open-weight 9.3B model released June 3                         |
| Black Forest Labs | FLUX.2 family / FLUX.2 [klein]                 | Replaces FLUX.2-era flagship description                       |
| Midjourney        | V8.1                                           | Current/default June 2026 generation                           |
| Luma              | Uni-1.1, Ray3.2, Luma Skills                   | Replaces Uni-1-only/Ray2-era descriptions                      |
| Runway            | Gen-4.5 + Aleph 2.0                            | Current generation/editing stack                               |
| Kling             | VIDEO 3.0 / Omni + native 4K                   | Current 2026 video family                                      |
| ByteDance         | Seedance 2.0 + Seedream 5.0 Lite               | Official primary-source model pages replace third-party claims |
| Stability audio   | Stable Audio 3.0                               | Open-weight, licensed-data model family released May 20        |
| ElevenLabs music  | Eleven Music v2                                | Released May 26                                                |
| Suno              | v5.5                                           | Current major personalization/customization update             |
| OpenAI video      | Sora consumer discontinued                     | Web/app ended Apr. 26; API ends Sep. 24                        |

### Newly catalogued or materially updated

- **Recraft V4.1** — current vector/raster/brand-design generation family
- **Google Gemini Omni Flash** — mixed-input video generation/editing rolling out through Gemini, Flow, and eligible YouTube experiences
- **Google Flow Agent, Flow Tools, and Flow Music** — I/O 2026 creative workflow additions
- **Runway Aleph 2.0 / Edit Studio** — frame-directed video editing propagation
- **Kling native 4K video** — announced May 2026
- **Wan 2.7** — newer Alibaba model family recommended in current Model Studio documentation
- **LPM-1 research model** — corrected to the official arXiv research source
- **Stable Audio 3.0** — open-weight model family for SFX and music
- **MiniMax Image-01** — launch date corrected to February 28, 2025
- **GLM-Image** — official Z.ai source and conservative capability description

### Claims removed or downgraded because first-party support was inadequate

- Adobe “Firefly Image Model 5 / Precision Flow / AI Markup / Project Graph”
- Happy Horse “official open-source GitHub, 15B, No. 1” wording
- Utopai PAI “three-minute 4K” guarantee
- MiniMax Music 1.5 exact date/duration/price
- Phantom X 3.2 at `phantom.ai`
- Any permanent leaderboard position, “best” claim, or exact pricing not tied to a dated primary source

---

## 🖼️ IMAGE GENERATION & EDITING

### Flagship Commercial Platforms

**[Midjourney](https://www.midjourney.com)** (Midjourney, Inc.)

- **Current model (verified June 2026): Midjourney V8.1**
- V8.1 became the default model in June 2026 after its April release
- Faster generation and improved prompt/detail handling compared with older V6-era descriptions
- Strong style-reference and character-reference workflows through web and Discord interfaces
- **Best For:** Art direction, concept art, cinematic/editorial aesthetics, rapid visual exploration
- **Pricing:** Changes by plan/region; use the live official plans page rather than fixed prices in this catalogue
- **Official updates:** https://updates.midjourney.com/

**[OpenAI GPT Image 2 / ChatGPT Images 2.0](https://openai.com/index/introducing-4o-image-generation/)** (OpenAI)

- **Current generation stack (verified June 2026): GPT Image 2**, with ChatGPT Images 2.0 as the consumer experience
- DALL·E 3 is retained as a legacy reference, not the current flagship recommendation
- Conversational creation/editing, strong instruction following, text rendering, and multi-reference workflows
- **API model:** `gpt-image-2`; confirm current limits and pricing in official API documentation
- **Best For:** Conversational iteration, marketing graphics, image edits, and developer integrations
- **Sora note:** OpenAI's separate Sora consumer product was discontinued April 26, 2026

**[Adobe Firefly](https://www.adobe.com/products/firefly.html)** (Adobe)

- Creative Cloud-integrated generation/editing platform with enterprise governance and licensed/permissioned training positioning
- **Verified 2026 updates:** Firefly AI Assistant, Adobe creativity connector, and Firefly Custom Models public beta
- Integrates with Photoshop, Premiere Pro, Express, and other Creative Cloud workflows
- **Correction:** No adequate first-party confirmation was found for the earlier README's “Firefly Image Model 5,” “Precision Flow,” “AI Markup,” or “Project Graph” claims; those claims were removed
- **Best For:** Professional editing, brand workflows, enterprise governance, and Adobe-native production
- **Pricing:** Verify current Creative Cloud/Firefly plan and generative-credit terms on Adobe's official pricing page

**[Microsoft MAI-Image-2.5](https://microsoft.ai/news/introducing-mai-image-2-5/)** ⭐ NEW JUNE 2026

- Microsoft's strongest public image model as of June 24, 2026
- Supports text-to-image and controllable image editing
- Microsoft reported a No. 2 position on Arena's Image Edit leaderboard at launch; treat leaderboard positions as dated snapshots
- Includes an efficiency-focused Flash variant in Microsoft's broader MAI model family
- **Best For:** Microsoft ecosystem, enterprise workflows, text-heavy designs, and image editing
- **Released:** June 2, 2026

**[Luma Uni-1.1](https://lumalabs.ai/news)** ⭐ UPDATED MAY 2026

- Multimodal creative intelligence/API for directing image and visual-generation workflows
- **Uni-1.1 API** announced May 5, 2026
- Complements Luma's **Ray3.2** video model and **Luma Skills** reusable creative workflows
- **Best For:** Context-aware creative generation, consistent art direction, and agentic production pipelines

**[Google Native Gemini Image Models + Imagen 4 lifecycle](https://ai.google.dev/gemini-api/docs/models)**

- **Current GA native image models:** Gemini 3.1 Flash Image (Nano Banana 2) and Gemini 3 Pro Image (Nano Banana Pro)
- **Imagen 4 status:** Marked deprecated in the Gemini API, with shutdown scheduled for August 17, 2026
- Preview endpoints for Gemini 3.1 Flash Image and Gemini 3 Pro Image were scheduled to shut down June 25, 2026; use GA model IDs
- **Best For:** Google ecosystem, multimodal generation/editing, grounded image workflows, and API integration
- **Source of truth:** Official Gemini API model and deprecation pages

**[Generative AI by Getty](https://www.gettyimages.com/company/generative-ai)** (Getty Images) ⭐ NEW

- Enterprise-safe generator trained on Getty's 500M+ licensed images
- Commercially indemnified with auto-licensing; up to 8K resolution
- Text-to-image with style matching, vector/SVG exports, API for bulk
- **Best For:** Global brands requiring zero IP risk, high-res stock-style imagery
- **Pricing:** $10–$50/image | API $0.05/generation
- **Comparison:** Safer than Firefly for litigation-averse enterprises; complements [Shutterstock AI](https://www.shutterstock.com/generate)

**[FLUX.2 model family](https://bfl.ai/models/flux-2)** (Black Forest Labs) ⭐ UPDATED

- Current Black Forest Labs image generation and editing family
- Variants include **FLUX.2 [max]** for highest-quality professional output, **[pro]**, **[flex]**, **[dev]**, and compact **FLUX.2 [klein]** models for fast/local workflows
- Supports generation and editing, multi-reference consistency, complex text/layout handling, and production controls depending on variant
- **Open/local options:** FLUX.2 [dev] and selected [klein] releases have open-weight/licensing paths; verify the exact model license
- **Best For:** Professional product visuals, controlled editing, API workflows, rapid prototyping, and self-hosted experimentation
- **Pricing/licensing:** Check BFL's live API, weights, and commercial-license terms

**[Stable Diffusion](https://stability.ai/stable-diffusion)** (Stability AI + Community)

- Open-source foundation model (SD 1.x/2.x/SDXL/SD3)
- Run locally on consumer GPUs (full privacy)
- Ecosystem: [ControlNet](https://github.com/lllyasviel/ControlNet), LoRA fine-tuning, [AUTOMATIC1111](https://github.com/AUTOMATIC1111/stable-diffusion-webui), [ComfyUI](https://github.com/comfyanonymous/ComfyUI), [Invoke AI](https://github.com/invoke-ai/InvokeAI)
- **Best For:** Technical users, max control, custom training, offline use
- **Pricing:** Free (open-source) | Costs = hardware/cloud

### Specialized & High-Fidelity Generators

**[Gamma Imagine](https://gamma.app)** ⭐ NEW Q1 2026

- Brand-aware AI image generation for marketing assets and decks (March 17, 2026).
- Integrates with ChatGPT, Claude, and Atlassian.

**[Ideogram 4.0](https://ideogram.ai/models/4.0/)** ⭐ NEW JUNE 2026

- Open-weight 9.3B image foundation model released June 3, 2026
- Strong multilingual text rendering, bounding-box/object placement, 2K output, and production-design controls
- Weights are downloadable; commercial licensing depends on deployment scale
- **Best For:** Posters, typography, ads, layouts, design systems, and self-hosted/open-weight workflows
- **Pricing:** API and hosting costs vary; use Ideogram's current pricing/documentation

**[Leonardo.Ai](https://leonardo.ai)**

- Multi-model studio (PhotoReal, Kino, Phoenix)
- AI Canvas for editing, 3D texture generation
- Consistent characters for game assets
- **Pricing:** Free tier (150 tokens/day) | Paid $10/month+

**[Krea.ai](https://www.krea.ai)**

- **Real-time generation** + AI Canvas (iterative refinement)
- **22K upscaler**, infinite zoom
- Video generation + enhancement tools
- **Pricing:** Free tier | Pro ~$30/month

**[Meta Imagine](https://imagine.meta.com)** (Meta AI)

- Fast, free generator for social media
- Integrated into WhatsApp/Messenger
- Based on Meta's Llama/EMU models
- **Pricing:** Free

**[Qwen-VL / Tongyi Wanxiang](https://tongyi.aliyun.com/wx)** (Alibaba)

- Strong **Chinese + English** multilingual support
- Enterprise image gen/editing via Alibaba Cloud Model Studio
- **Pricing:** Free API (limits) | Alibaba Cloud pricing

**[Gemini 2.5 Flash Image ("Nano Banana")](https://developers.googleblog.com/en/introducing-gemini-2-5-flash-image/)**

- Google's small, fast **on-device image editing** family
- Powers edits in Search/Lens (object removal, cleanups)
- Not standalone—integrated into Google apps
- **Statistics:** 5+ billion images generated as of late 2025

**[Gemini 3 Pro Image ("Nano Banana Pro")](https://gemini.google/overview/image-generation)** ⭐ NEW Q1 2026

- Advanced "thinking" image generator with reasoning capabilities
- Up to **4K resolution** output with better series consistency
- Maintain resemblance of up to **5 people** in one scene
- Finer control over color grading, lighting, and local edits
- Localized editing capabilities for precise modifications
- **Best For:** Professional photography, consistent character series, high-precision work
- **Pricing:** Gemini Pro/Ultra tiers and selected Google products
- **Comparison:** Higher quality than Nano Banana 2; Google's flagship for precision work

**[GenType](https://labs.google/gentype)** ⭐ NEW Q1 2026

- AI tool for creating custom alphabets and letterforms
- Generate themed typefaces from text prompts (e.g., "chrome cyberpunk", "dripping neon")
- 3D, textured, or illustrative styles supported
- Download assets for creative projects
- **Best For:** Typography design, custom fonts, branding, graphic design
- **Pricing:** Free via Google Labs
- **Comparison:** Specialized for typefaces; complements Ideogram's text-in-image capabilities

**[Monica AI](https://monica.im)** ⭐ NEW

- Browser extension for artistic/anime styles (2025 v2 adds fantasy presets)
- Real-time generation in Chrome; style transfers; batch from spreadsheets
- **Best For:** Hobbyists needing web-integrated artistic workflows
- **Pricing:** Free tier | $9/month Pro
- **Comparison:** Artistic rival to [ImagineArt AI](https://www.imagine.art); enhances [Krea.ai](https://www.krea.ai)'s canvas workflow

**[Visual Electric](https://visualelectric.com)** ⭐ NEW

- AI image-generation workspace aimed at designers and creative teams
- Emphasizes art direction, collaborative ideation, and campaign-style visual iteration
- **Status note:** Reported post-acquisition sunset risk means live availability should be confirmed before recommending it to users
- **Best For:** Designers, art directors, and brand-creative workflows
- **Pricing:** Verify current access and plan status on the official site

**[Google Nano Banana 2](https://blog.google/innovation-and-ai/technology/ai/nano-banana-2/)** ⭐ NEW Q1 2026

- Google's fastest image model (Feb 26, 2026), technically Gemini 3.1 Flash Image
- Combines Pro capabilities with Flash speed; advanced world knowledge
- Improved text rendering, subject consistency, production-ready specs
- Available across Gemini app, Search, Lens, and Flow
- **Best For:** Fast iteration, real-time editing, production workflows
- **Pricing:** Free via Gemini (limited) | Gemini Advanced $20/month
- **Comparison:** 2-3x faster than Nano Banana Pro; now default model across Google products

**[Gemini 3 Pro Image API lifecycle note](https://ai.google.dev/gemini-api/docs/changelog)**

- The GA `gemini-3-pro-image` model was released May 28, 2026
- The earlier preview endpoint was scheduled for shutdown June 25, 2026
- This is the API form of Nano Banana Pro already catalogued above; it is **not a separate product entry**

**[MiniMax Image-01](https://www.minimax.io/news/image-01)**

- MiniMax text-to-image model announced **February 28, 2025**
- Supports prompt-driven image generation through MiniMax products/API channels where available
- **Date correction:** The earlier README incorrectly labelled it a February 2026 launch
- **Best For:** MiniMax ecosystem and cost-sensitive API experimentation
- **Pricing/performance:** Exact per-image prices and “100× cheaper” claims were removed; verify the live API console and terms

**[GLM-Image](https://z.ai/blog/glm-image)** (Z.ai / Zhipu AI)

- Official open image-generation model using a hybrid autoregressive-plus-diffusion architecture
- Designed for strong knowledge grounding, prompt following, text-rich images, posters, infographics, and production graphics
- Open-source availability and licensing should be checked from Z.ai's official model/repository pages
- **Correction:** Third-party benchmark, “beats” claims, and fixed pricing were removed because they are volatile or insufficiently sourced
- **Best For:** Text-heavy visual generation, research, and open deployment workflows

**[Microsoft MAI-Image-1](https://microsoft.ai/news/introducing-mai-image-1-debuting-in-the-top-10-on-lmarena/)** ⭐ NEW Q1 2026

- Microsoft's first in-house text-to-image model (announced October 13, 2025)
- Debuted in top 10 on LMArena text-to-image leaderboard
- Photorealistic capabilities with creative flexibility
- Integrated into Bing Image Creator and Microsoft Copilot
- **Best For:** Enterprise workflows, Microsoft ecosystem users, photorealistic generation
- **Pricing:** Free via Bing/Copilot (limited) | Included with Microsoft 365 AI
- **Comparison:** Rivals Imagen 4 for photorealism; Microsoft's answer to DALL·E 3/Midjourney

**[Google Whisk](https://labs.google/fx/whisk)** ⭐ NEW

- Image-to-image generative tool that uses up to three visual prompts: subject, scene, and style—instead of text.
- Launched in December 2024 as part of [Google Labs](https://labs.google/fx)’ experimental suite.
- Enables precise visual blending by uploading reference images, making it ideal for mood boards, concept iteration, and style transfer without prompt engineering.
- Browser-based only; no standalone app.
- **Best For:** Visual thinkers, designers who prefer image inputs over text, rapid style fusion.
- **Pricing:** Free unlimited via [Google Labs](https://labs.google/fx)
- **Comparison:** Complements [Google ImageFX](https://labs.google/fx/imagefx) (text-to-image); acts as a visual counterpart to Ideogram’s text-in-image strength. More intuitive than SD + [ControlNet](https://github.com/lllyasviel/ControlNet) for non-technical users.

### Additional Image Tools

**[Google ImageFX](https://labs.google/fx/imagefx)** ⭐ NEW

- Free experimental tool from [Google Labs](https://labs.google/fx) (2025 update adds seed styles)
- Text-to-image with prompt seeds for variations; up to 1024x1024
- Zero cost, fast (5-10s generation); great for surreal/abstract prompts
- **Best For:** Free ideation and prompt experimentation
- **Pricing:** Free unlimited via [Google Labs](https://labs.google/fx)
- **Comparison:** Like Imagen 4 but lighter—15% faster than free DALL-E for quick sketches

**[ByteDance Seedream 5.0 Lite](https://seed.bytedance.com/en/seedream5_0_lite)** ⭐ UPDATED 2026

- Unified multimodal image generation model with reasoning and online-search capabilities
- Strong prompt understanding, generation, and editing in ByteDance's Seed model family
- Replaces the stale/non-primary-source SeedDream 4.0 description in the prior README
- **Best For:** Multimodal image creation, reference-driven editing, and ByteDance ecosystem workflows

**[Playground AI](https://playground.com)** – Multi-model access, fast UI
**[Freepik Pikaso](https://pikaso.freepik.com)** – Real-time sketch-to-image
**[Artbreeder](https://www.artbreeder.com)** – Genetic algorithm image "breeding"
**[NightCafe](https://creator.nightcafe.studio)** – Multi-model platform aggregator
**[DreamStudio](https://dreamstudio.ai)** – Official [Stable Diffusion](https://stability.ai/stable-diffusion) web interface
**Canva AI (Magic Media)** – Integrated design tools
**[Shutterstock AI](https://www.shutterstock.com/generate)** – Stock-grade with indemnification
**[Photoleap](https://www.photoleapapp.com)** – Mobile-first editing/generation
**[Reve](https://reve-ai.com)** – High prompt-fidelity focused
**[Pollo AI](https://play.google.com/store/apps/details?id=com.polloai.app)** – Batch processing across models
**[ImagineArt AI](https://www.imagine.art)** – Mobile-friendly artistic styles
**[PromeAI](https://www.promeai.com)** – Design-focused with templates
**[Kolors](https://huggingface.co/Kwai-Kolors/Kolors)** (Kuaishou) – Fine-art/abstract styles
**[Runway Frames](https://runwayml.com)** – Image arm of [Runway](https://runwayml.com) suite
**[Luma Dream Machine Images](https://lumalabs.ai/dream-machine)** – 3D-like animated styles
**[Recraft V4.1](https://www.recraft.ai/blog/recraft-v4-1-more-beautiful-by-nature)** – Current May 2026 image/design family, with stronger photorealism, prompt understanding, illustrations, icons, vectors, and production mockups; API variants and licensing should be checked in current Recraft docs

**[FLUX Image to Video](https://fluxai.pro/image-to-video)** ⭐ NEW March 2026

- Transform photos into stunning videos (March 2026)
- FLUX.1 AI image to video generation
- Competitive pricing and top-notch quality
- **Best For:** FLUX users wanting video extension
- **Pricing:** Check website

### Image Enhancement & Editing

**[Topaz Photo AI](https://www.topazlabs.com/photo-ai)** – Upscaling, denoise, sharpen (desktop)
**[Clipdrop](https://clipdrop.co)** – Background removal, relight, upscale
**[ImageCritic](https://www.kombitz.com/2026/03/05/imagecritic-improves-ai-image-editing-accuracy/)** ⭐ NEW Q1 2026

- AI system that detects and corrects fine-grained inconsistencies in AI-generated images (March 2026)
- Improves editing accuracy by identifying reference image mismatches
- Works with existing generative models to enhance output quality
- **Best For:** Professional editing workflows, quality assurance, reference-based editing
- **Pricing:** Research preview | Commercial release TBD
- **Comparison:** First AI quality control layer; complements all major image generators

**[GFPGAN](https://github.com/TencentARC/GFPGAN)** – Face restoration (open-source)
**[CodeFormer](https://github.com/sczhou/CodeFormer)** – Face detail enhancement
**[Real-ESRGAN](https://github.com/xinntao/Real-ESRGAN)** – General super-resolution
**[Lama Cleaner](https://github.com/Sanster/lama-cleaner)** – High-quality object removal/inpainting
**[Neural.love](https://neural.love)** – Multi-tool enhancement suite

---

## 🎬 VIDEO GENERATION & EDITING

### Foundation Text-to-Video Models

**[OpenAI Sora / Sora 2](https://openai.com/sora)** — **DISCONTINUED FOR CONSUMERS**

- Historical world-simulation/video-generation product
- Consumer web/app access ended April 26, 2026
- API shutdown scheduled September 24, 2026
- Retained only for historical/comparison context; do not recommend for new consumer projects

**[Google Veo 3](https://deepmind.google/technologies/veo/)**

- Studio-grade cinematic quality, physics-aware
- Native audio generation with dialogue lip-sync
- Optimized for vertical (social reels) and standard formats
- Via [Gemini API](https://ai.google.dev/gemini-api)/[Vertex AI](https://cloud.google.com/vertex-ai)
- **Best For:** Social reels, promotional videos, integrated audio
- **Pricing:** Gemini Pro ~$20/month

**[Google Veo 3.1](https://ai.google.dev/gemini-api/docs/video)** ⭐ NEW Q1 2026

- Enhanced version of Veo 3 (October 2025, updated January 2026)
- Richer audio, more narrative control, enhanced realism with true-to-life textures
- Stronger prompt adherence and improved audiovisual quality for image-to-video
- Reference image support for character consistency and scene extension
- 4K output support with configurable 16:9 (landscape) and 9:16 (portrait) aspect ratios
- **Best For:** Professional video production, vertical content (Shorts/Reels), character-consistent narratives
- **Pricing:** Via Gemini API/Vertex AI (usage-based)
- **Comparison:** 20% better audio quality vs. Veo 3; superior prompt adherence

**[Google Veo 3.1 Fast](https://ai.google.dev/gemini-api/docs/video)** ⭐ NEW Q1 2026

- Optimized for speed (January 2026)
- Generates 4-8 second videos at 720p/1080p in ~45-60 seconds
- Native audio synchronization with faster generation times
- Ideal for quick previews, rapid iteration, and high-volume workflows
- **Best For:** Rapid prototyping, social media content, quick turnaround projects
- **Pricing:** Lower cost than standard Veo 3.1 via Gemini API
- **Comparison:** 2x faster than Veo 3.1 Standard; trades some quality for speed

**[Kling VIDEO 3.0 / 3.0 Omni](https://app.klingai.com/global/blog/kling-video-3-0-ai-director-features-guide)** ⭐ 2026

- Unified audiovisual generation with text/image/reference workflows
- Multi-shot “AI Director” features, synchronized multilingual audio, subject consistency, and up to 15-second continuous output in documented 3.0 workflows
- Kling announced native 4K generation support in May 2026
- **Best For:** Multi-shot cinematic clips, ads, character/subject continuity, and native audiovisual generation
- **Caution:** Feature access, resolution, duration, and credits vary by plan/model mode

**Happy Horse 1.0** — **SOURCE STATUS CORRECTED**

- Available through selected model-hosting/partner platforms, but no official open-weight GitHub repository or first-party release matching the prior README claim was verified as of June 24, 2026
- Do **not** describe it as fully open source or cite an unverified GitHub repository
- Keep only as an emerging model to evaluate through a reputable hosting partner, with license and provenance checked before production use

**[PAI / PAI Pro (Utopai Studios)](https://utopai.ai)** ⭐ 2026

- Professional generative storytelling platform focused on sustained multi-scene continuity and iterative direction
- Public-access announcements appeared in 2026, with PAI 2.0 / PAI Pro branding on current product pages
- **Correction:** The earlier “3-minute 4K” claim was not adequately confirmed by first-party documentation and has been removed
- **Best For:** Narrative development, multi-scene filmmaking, and director-style iteration

**[Seedance 2.0](https://seed.bytedance.com/en/blog/official-launch-of-seedance-2-0)** (ByteDance) ⭐ 2026

- Officially launched February 12, 2026
- Unified audio-video generation supporting four input modalities: text, image, audio, and video
- Reference-driven creation/editing, native audiovisual synchronization, and multi-shot workflows
- Available through ByteDance products and selected partner/API integrations; exact access varies
- **Best For:** Reference-heavy audiovisual creation and multi-modal editing

**[PixVerse V6 & C1](https://pixverse.ai)** ⭐ NEW Q2 2026

- **PixVerse C1** (April 2026): Film production model with industrial action engine and VFX.
- **PixVerse V6** (March 2026): Enhanced camera control, character performance, and CLI for agentic workflows.
- Multi-shot short films with native audio.
- **Best For:** Developer workflows, multi-shot films, cinematic VFX.

**[LPM-1 / Large Performance Model](https://arxiv.org/abs/2604.10835)** ⭐ RESEARCH 2026

- Research model for real-time, long-duration character performance and conversational video
- The paper describes a 17B-parameter model designed for interactive/infinite performance generation
- **Correction:** The prior `topview.ai` product attribution was incorrect; this entry now points to the research paper
- **Best For:** Research on interactive characters, embodied agents, and real-time performance

**[Wan 2.7 / Wan 2.6](https://www.alibabacloud.com/help/en/model-studio/wan-video-generation-api-reference)** (Alibaba) ⭐ UPDATED 2026

- Alibaba Cloud documentation now recommends the newer **Wan 2.7** family where available; Wan 2.6 remains an older supported/reference generation
- Multi-shot and native-audio capabilities vary by model/version and endpoint
- **Best For:** Alibaba Cloud workflows, developer integration, and multimodal video generation
- **Source of truth:** Current Model Studio documentation and live model IDs

**[Hailuo 2.3 / 2.3 Fast](https://hailuoai.video)** (MiniMax)

- Motion-focused text-to-video and image-to-video models with standard and faster variants
- **Date correction:** Hailuo 2.3 was announced in October 2025, not February 2026
- **Best For:** Dynamic motion, expressive character clips, and rapid iteration
- Availability, resolution, duration, and pricing should be checked on MiniMax/Hailuo's current official pages

**[Runway Gen-4.5 + Aleph 2.0](https://runwayml.com)** ⭐ UPDATED 2026

- Gen-4.5 supports text-to-video and image-to-video; Runway's API added it February 10, 2026 with 2–10 second durations
- **Aleph 2.0 & Edit Studio** launched in May 2026 for propagating a directed frame edit through a video
- Runway also provides Characters, Act-Two, VFX/editing tools, and an expanding model API catalogue
- **Best For:** Professional video generation, shot editing, VFX, and integrated production workflows
- **Pricing:** Credit and plan economics change frequently; use the live Runway pricing/calculator

**[Google Flow](https://labs.google/flow/about)**

- Google's AI filmmaking and creative studio integrating Veo, native Gemini image models, and asset/story workflows
- I/O 2026 additions include **Flow Agent**, **Flow Tools**, and **Google Flow Music**
- Supports prompt/reference-based creation, scene building, extension, editing, audio-capable Veo workflows, and asset reuse
- **Best For:** Google-ecosystem filmmaking, scene iteration, and multimodal creative production
- Availability and quotas depend on Google AI plan, region, age, and account

**Runway Gen-4 + Aleph — legacy reference**

- Superseded in this catalogue by **Runway Gen-4.5 + Aleph 2.0 / Edit Studio**
- Retained only to explain older projects, documentation, and comparisons

**[Kuaishou Kling](https://apps.apple.com/us/app/kling-ai/id6580029292)**

- Up to **2-minute clips** at 1080p/30fps
- 3D face/body reconstruction, realistic motion
- "Elements" reference for subject consistency
- **Best For:** Cinematic realism, product animations, longer narratives
- **Pricing:** Free tier | Paid $7/month+

**Luma Ray3.2 / Dream Machine**

- Current Luma video-generation/editing family as of June 2026
- Ray3.2 adds frame-level direction, keyframe controls, HDR/EXR-oriented professional workflows, and API access
- Ray2 is retained only as a legacy generation name
- **Official source:** https://lumalabs.ai/news/introducing-ray-3-2

**[Digen RM3.0](https://digen.ai)** (Real Motion 3.0) ⭐ NEW Q1 2026

- Professional-grade AI video with simultaneous motion + audio generation
- Generate 2K video + audio in seconds
- Built for professional workflows with full creative control
- Native lip-sync, dialogue, ambience, and music co-generated
- **Best For:** Studio production, enterprise video, developer integration
- **Pricing:** Free tier available | Pro plans coming
- **Comparison:** Competes with Veo 3 and Kling 3.0 for professional output quality

**[Genra AI](https://genra.ai)** ⭐ NEW Q1 2026

- First AI video tool controllable via Claude Code
- Agentic video creation for developers
- Designed for pipeline integration and automation
- **Best For:** Developer workflows, automated video pipelines
- **Pricing:** Available via API

**[Pika 2.0](https://pika.art)**

- User-friendly short clips with effects
- Swaps, lip-sync, stylized outputs
- **Pricing:** Free tier | Subscription plans

### Enterprise & Developer Video APIs

**[Google Vids](https://workspace.google.com/products/vids/)** ⭐ NEW Q1 2026

- AI-powered video creation for Google Workspace (November 2025 rollout)
- Gemini-powered "Help me create" generates storyboards from prompts and Drive docs
- Creates marketing, training, and presentation videos with voiceovers and music
- Free AI features for all Gmail users (expanded November 2025)
- **Best For:** Business presentations, training videos, team updates, marketing content
- **Pricing:** Free for Gmail users | Workspace tiers include advanced features
- **Comparison:** Business-focused alternative to [Synthesia](https://www.synthesia.io); deep Google Drive integration

**[Dream Screen](https://support.google.com/youtube/answer/14151606)** (YouTube Shorts) ⭐ NEW Q1 2026

- AI-generated backgrounds for YouTube Shorts videos
- Custom video backgrounds from text prompts using generative AI
- Green screen replacement with AI-generated scenes
- Creator-focused tool integrated into YouTube Shorts camera
- **Best For:** YouTube creators, social media content, short-form video
- **Pricing:** Free for YouTube creators (expanding availability)
- **Comparison:** Specialized for Shorts; complements [Dream Track](https://support.google.com/youtube/answer/14151606) for audio

**[YouTube Aloud](https://aloud.area120.google.com)** ⭐ NEW Q1 2026

- AI-powered dubbing and translation tool for YouTube creators
- Automatically dub videos into other languages with high-quality synthetic voices
- Review and edit transcripts before dubbing for accuracy
- Helps creators reach global audiences with localized content
- **Best For:** YouTube creators, content localization, multi-language channels
- **Pricing:** Free beta for YouTube creators
- **Comparison:** Specialized for video dubbing; complements [ElevenLabs](https://elevenlabs.io) for creator workflows

**[Alibaba/Qwen "Wan"](https://qwen.ai)**

- Video foundation models via Alibaba Cloud Model Studio
- Cinematic precision, temporal coherence
- Complements [Tongyi Wanxiang](https://tongyi.aliyun.com/wx) (images)
- **Pricing:** API access via Alibaba Cloud

**[LTX Studio](https://ltxstudio.com)** (Lightricks) ⭐ NEW

- Narrative AI for filmmakers (2025 launch)
- Scene-by-scene prompts; character customization; storyboard exports; 4K previews
- **Best For:** Film pre-production, pitch decks, screenplay visualization
- **Pricing:** Free tier (5 clips/month) | Pro $29/month
- **Comparison:** Pre-production boost over [Morph Studio](https://www.morphstudio.com); pairs with [Runway](https://runwayml.com) [Aleph 2.0](https://runwayml.com/product/aleph-2) for full workflow

**[cv.cm/v](https://cv.cm/v)** (Cloud Clipboard AI Studio)

- Web studio providing **queue-free, full-power [Seedance 2.0](https://seed.bytedance.com/en/blog/official-launch-of-seedance-2-0)** text-to-video and image-to-video, plus image generation (gpt-image-2 / Seedream)
- Node-graph canvas for chaining generations and a REST API for programmatic access
- No signup required to try; new users get 100 free credits
- **Best For:** Fast Seedance 2.0 access without a queue, multimodal experiments, API-driven video workflows
- **Pricing:** Free credits on signup | pay-as-you-go credits

**[xAI Grok Imagine](https://grok.com)**

- Image/video generation in [Grok](https://grok.com)/X platform
- Uses FLUX models (Black Forest Labs partnership)
- **Pricing:** Included with [Grok](https://grok.com) access

**[VO3 AI](https://vo3ai.com)** ⭐ NEW

- Short-form AI video generator built around Veo-style text-to-video and image-to-video creation
- Focuses on quick cinematic clips and simplified prompt-driven workflows
- **Best For:** Marketers and creators who want Veo-like output without direct developer tooling
- **Pricing:** Check the live pricing page for current subscription details

### AI Avatars & Business Video

**[Synthesia](https://www.synthesia.io)**

- Professional videos with AI avatars
- 140+ languages, script/PDF → video
- **Best For:** Corporate training, multilingual explainers
- **Pricing:** Free tier (3 mins/month) | $29/month+

**[HeyGen](https://www.heygen.com)**

- Personalized AI avatars with accurate lip-sync
- **Video translation** cloning speaker's voice
- **Best For:** Sales outreach, personalized marketing, localization
- **Pricing:** Free trial | $29/month+

**[Creatify AI](https://creatify.ai)** ⭐ NEW

- Avatar-video platform optimized for ads, product promos, and short-form marketing content
- Includes script assistance, product-focused templates, and no-filming workflows
- **Best For:** Ad creatives, e-commerce, and TikTok Shop-style product videos
- **Pricing:** Verify current plan/export limits directly with the vendor

**[Zoice](https://zoice.ai)** ⭐ NEW

- Talking-avatar platform focused on realistic presenter videos and multilingual delivery
- Promotes higher-resolution exports, expression control, and commercial-use workflows
- **Best For:** Tutorial videos, explainers, and multilingual presenter content
- **Pricing:** Confirm current plans and rendering caps on the official site

**[DeepBrain AI / AI Studios](https://www.aistudios.com)** ⭐ NEW

- Business avatar-video suite with photoreal avatars, dubbing, and template-driven production
- Supports multilingual training, presentation, and digital-human style workflows
- **Best For:** Corporate communications, training content, and high-volume business video
- **Pricing:** Check current business and enterprise packaging directly

**[D-ID](https://www.d-id.com)**

- "Talking head" videos from still photos + audio/text
- **Best For:** Simple marketing, historical photos
- **Pricing:** Free trial + subscriptions

**[Capsule](https://capsule.video)** ⭐ NEW

- Branded video editor with AI (2025 CoProducer update)
- Transcript edits; auto-captions/CTAs; branded kits; multi-cam cuts
- **Best For:** Team-based content workflows, brand consistency
- **Pricing:** Free trial | $49/month
- **Comparison:** Workflow rival to [Descript](https://www.descript.com); complements [OpusClip](https://www.opus.pro) for repurposing

**[Colossyan](https://www.colossyan.com), [Elai](https://elai.io), [Virbo](https://virbo.wondershare.com)** (Wondershare) – Business avatar alternatives

### Emerging & Specialized Video Tools

**[Vyond](https://www.vyond.com)** ⭐ NEW

- Animated video platform with AI prompts (2025 Go update adds motion capture)
- Text-to-scene generation; timeline editor; avatar rigging; exports to MP4/GIF
- **Best For:** Animated explainers, training videos, character consistency
- **Pricing:** Free trial | $25/month
- **Comparison:** 20% more consistent animations than [Pika 2.0](https://pika.art) in motion tests; fills animation gap vs. [Genmo](https://www.genmo.ai)

**[revid.ai](https://www.revid.ai)** ⭐ NEW

- Template-based repurposer (2025 TikTok trends integration)
- Long-to-short AI; talking avatars; auto-mode daily generation
- **Best For:** Trending social content, TikTok/Reels optimization
- **Pricing:** Free basics | $19/month
- **Comparison:** Social focus vs. [InVideo AI](https://invideo.io/ai); pairs with [CapCut](https://www.capcut.com) for mobile workflow

**Stable Video Diffusion (SVD)** – Open-source img→vid/t2v (Stability AI)
**[AnimateDiff](https://github.com/guoyww/AnimateDiff)** – Plug-and-play SD animation module (looping videos)
**[Hailuo Minimax](https://hailuoai.video)** – Storytelling-focused (generous free credits, 6s cap)
**[PixVerse](https://pixverse.ai)** – 8s clips with integrated audio (voices/SFX)
**[Vidu](https://www.vidu.com)** (China) – 1080p short clips
**ByteDance Daydream (JiMeng)** – Chinese shorts/ads ecosystem
**[Zhipu Ying/Yingying](https://open.bigmodel.cn/)** – Chinese story video
**[Tencent Zhiying](https://zenvideo.qq.com)** – Chinese social video
**[Jichuang](https://www.jnu.edu.cn/)** – Chinese AI video tool
**[Meta EMU Video](https://ai.meta.com/blog/emu-video/)** – Text→image→video research pipeline
**[Fliki](https://fliki.ai)** – Text-to-video with AI voiceovers
**[InVideo AI](https://invideo.io/ai)** – Script-to-video automation
**[Pictory 2.0](https://pictory.ai)** ⭐ NEW Q1 2026

- Complete AI video platform with avatars, generative visuals, and interactive hosting
- Advanced editing, brand control, and seamless workflow integration
- **Best For:** Professional videos without filming or editing software
- **Pricing:** Free trial | Subscription plans available
- **Comparison:** All-in-one solution for businesses; combines AI generation with editing tools
  **[Haiper](https://haiper.ai)** – Emerging video startup
  **[Genmo](https://www.genmo.ai)** – Video + image generation
  **[Viggle AI](https://viggle.ai)** – Character animation, motion transfer
  **[Morph Studio](https://www.morphstudio.com)** – Comprehensive video platform
  **[Steve.AI](https://www.steve.ai)** – Animated videos from scripts

**[Pruna P-Video](https://blog.republiclabs.ai/2026/02/revolutionizing-content-creation.html)** ⭐ NEW Q1 2026

- Revolutionizing content creation (Feb 2026)
- Fast, accessible AI video generation
- Focus on speed and creative freedom
- **Best For:** Quick video creation, social content
- **Pricing:** Check website

**[VideoGen 3.2.0](https://videogen.io/news/videogen-3-2-0-update)** ⭐ NEW Q1 2026

- Editor rebuild for smoother performance (Feb 2026)
- 7 guided workflows for creators
- Line/arrow annotations, improved text editing
- Voiceovers and sharing improvements
- **Best For:** Team-based content, guided creation
- **Pricing:** Check website

### Video Editing & Enhancement

**[Runway Editor](https://runwayml.com)** – Motion brush, inpaint, green-screen (pairs with Gen-4/Aleph)
**[Topaz Video AI](https://www.topazlabs.com/video-ai)** – Upscale, denoise, stabilize, frame-interpolate
**[CapCut](https://www.capcut.com)** – AI background removal, captions, reframing (mobile-first)
**[Descript](https://www.descript.com)** – Text-based video editing + Overdub voice
**[Artlist AI](https://artlist.io/ai)** ⭐ NEW

- Stock-integrated generator (2025 suite expansion)
- Text/image-to-video; unlimited stock B-roll; voiceover add-ons; 1080p max
- **Best For:** B-roll enhancement, quick content repurposing
- **Pricing:** $29.99/month (includes stock music/effects)
- **Comparison:** B-roll enhancer for [Pictory](https://pictory.ai); like Freepik but video-centric

**[Peech](https://www.peech.co)** ⭐ NEW

- Content repurposing app (2025 highlight generation update)
- Auto-subtitles; channel optimization; intro/outro additions
- **Best For:** Multi-platform export, marketing teams
- **Pricing:** Free tier | $29/month
- **Comparison:** Like [Munch](https://www.getmunch.com) for marketers; fast 1-min clip processing

**[OpusClip](https://www.opus.pro) / [Munch](https://www.getmunch.com) / [Wisecut](https://www.wisecut.ai)** – Long-form → shorts repurposing
**[Filmora](https://filmora.wondershare.com)** – User-friendly editor with AI cutouts/denoising

---

## 🔊 AUDIO GENERATION & ENHANCEMENT

### Music & Soundscape Generation

**[Suno](https://suno.com)**

- Text-to-song platform for lyrics, vocals, instruments, remixing, and community creation
- **Current major version:** Suno v5.5 (March 2026), adding Voices, Custom Models, and My Taste personalization
- Continued 2026 updates include improved stem separation and production controls
- **Best For:** Full-song ideation, personalized music generation, and remix workflows
- **Licensing/pricing:** Confirm commercial rights and plan terms for each project

### Ethical AI Music

**[Jen](https://jenmusic.ai)** ⭐ NEW

- Rights-aware AI music platform positioned around licensed/ethical training inputs and style-guided composition
- Emphasizes commercially safer music generation versus scrape-first consumer tools
- **Best For:** Teams that need conservative licensing posture for AI-assisted music creation
- **Availability/pricing:** Confirm current access terms because artist/catalog partnerships can change

**[Udio](https://www.udio.com)**

- High-fidelity, genre-blending music
- **Udio 2** (March 2026): High-fidelity tracks with structural awareness and stem downloads for producers.
- **Best For:** Genre-blending, high-quality music, collaboration.

**[Eleven Music v2](https://elevenlabs.io/music)** ⭐ UPDATED MAY 2026

- ElevenLabs' current generative music system, released May 26, 2026
- Creates music from prompts with production/iteration workflows integrated into the ElevenLabs ecosystem
- ElevenMusic mobile creation launched in 2026; availability varies by platform/region
- **Best For:** Creator audio, mobile music ideation, and integration with ElevenLabs voice/audio tooling

**[MiniMax Music 2.6](https://www.minimax.io/news/music-26)** ⭐ UPDATED APRIL 2026

- Current MiniMax music-generation model listed in the vendor's official release notes/API documentation as of June 24, 2026
- Supports prompt-directed control over BPM, key, song structure, style, and emotional arc
- Earlier releases include Music 1.5 (September 2025, up to four-minute songs) and Music 2.5 / 2.5+ (January–March 2026)
- **Best For:** Full-song generation, structured composition, instrumental creation, and MiniMax API workflows
- **Pricing/limits:** Check the live MiniMax API console; fixed per-song pricing was removed from this catalogue

**[Loudly VEGA-2](https://www.loudly.com)** ⭐ NEW Q1 2026

- Upgraded model (March 12, 2026) for professional instrumentals.
- **Automatic Mastering**: release-ready audio with smart EQ/compression.
- **Best For:** Pro-instrumental production, background scores.

**[Maestro](https://soundcraft.ai)** ⭐ NEW Q1 2026

- Infinite AI sample generator (February 16, 2026) from text descriptions.
- Trained on ethical/synthetic data for producers.

**[Voxtral TTS](https://mistral.ai)** ⭐ NEW Q1 2026

- Open-source text-to-speech model from Mistral (March 26, 2026).
- Supports 9 languages; voice adaptation from 5-second samples.

**Deepdub / Phantom-family audio tooling — attribution corrected**

- The prior `phantom.ai` link and “Phantom X 3.2 Audio-Omni” specification could not be validated as written
- Related Phantom-branded dubbing/audio announcements appear under Deepdub channels; verify the exact product name, model version, licensing, and access directly with the vendor before cataloguing it as a released model

**[Google MusicFX DJ](https://labs.google/fx/musicfx)** ⭐ NEW

- Real-time, prompt-driven music creation using up to 10 descriptive inputs (e.g., genre, instrument, mood) with adjustable influence sliders for each prompt.
- Developed in collaboration with artist Jacob Collier to enable continuous, evolving musical streams.
- Outputs studio-quality 48kHz stereo audio; users can export 60-second clips and share them.
- Currently accessible via Google AI Test Kitchen with limited regional availability.
- **Best For:** Experimental music jamming, ambient soundscapes, rapid ideation without DAWs.
- **Pricing:** Free (experimental, via [Google Labs](https://labs.google/fx) / AI Test Kitchen)
- **Comparison:** More interactive than Suno/[Udio](https://www.udio.com) for live tweaking; less structured for full songs but superior for ambient/loop-based generation.
- **Note:** Do not confuse MusicFX DJ with the earlier MusicFX (a simpler beat-generation tool). MusicFX DJ is the advanced, real-time successor launched in late 2024.

**[AIVA](https://www.aiva.ai)** (Artificial Intelligence Virtual Artist)

- Emotional, copyright-free soundtracks (250+ styles)
- MIDI export, reference track editing
- **Best For:** Film scores, game soundtracks, orchestral cues
- **Pricing:** Free (attribution required) | Pro ~$50/month

**[Stable Audio 3.0](https://stability.ai/stable-audio)** (Stability AI) ⭐ NEW MAY 2026

- Open-weight generative-audio model family trained on fully licensed data
- Small SFX, Small, Medium, and Large variants for on-device through enterprise/API use
- Variable-length generation; Medium supports tracks up to approximately 6:20
- Community/enterprise licensing determines commercial terms; Stability says users own outputs under applicable license terms
- **Best For:** Open experimentation, sound effects, full music, self-hosting, and audio-platform integration

**[Fadr](https://fadr.com)** ⭐ NEW

- AI music toolkit for stem separation, remixing, mashups, and tempo/key-aware production tasks
- Useful for isolating vocals, drums, bass, and instrument layers before creative rearrangement
- **Best For:** Producers, remixers, DJs, and stem-based music workflows
- **Pricing:** Free tier with paid upgrades; verify export and usage limits

**[Splice AI Tools](https://splice.com)** ⭐ NEW

- AI-assisted feature set inside Splice for variations, idea expansion, and fit-to-project production workflows
- Built to support sample-centric music production rather than replace DAW-based creation
- **Best For:** Sample-based producers, songwriting inspiration, and professional production workflows
- **Pricing:** Check the current Splice subscription matrix for feature access

**[Google Lyria 3](https://blog.google/innovation-and-ai/products/gemini-app/lyria-3/)** ⭐ NEW Q1 2026

- Most advanced Google music model (Feb 18, 2026)
- 30-second tracks from text prompts or images
- Generates vocals, lyrics, instruments automatically
- Integrated into Gemini app (750M+ users)
- SynthID watermarking for all tracks
- Available in 8 languages (English, German, Spanish, French, Hindi, Japanese, Korean, Portuguese)
- **Best For:** Casual creators, social content, quick ideation
- **Pricing:** Free via Gemini (limited) | Higher limits on Gemini Advanced
- **Comparison:** Consumer-facing competitor to Suno/Udio; integrated with image generation (Nano Banana covers)

**[Google ProducerAI](https://blog.google/innovation-and-ai/models-and-research/google-labs/producerai/)** ⭐ NEW Q1 2026

- Music creation partner in Google Labs (Feb 24, 2026)
- Uses preview version of Lyria 3 for professional-grade music
- Advanced controls for producers and musicians (tempo, time-aligned lyrics)
- "Spaces" feature: create new instruments/effects via natural language
- Part of Google Labs experimental suite
- **Best For:** Pro-level control, experimental composition, musicians, producers
- **Pricing:** Free via Google Labs
- **Comparison:** Advanced controls rival DAWs; bridges gap between AI and professional tools

**[Google MusicFX](https://labs.google/fx/tools/music-fx)**

- Text-to-music generation tool, successor to MusicLM
- Generate music loops up to 70 seconds from text prompts
- Adjust mood, tempo, and instrumentation
- SynthID watermarking on all outputs
- **Best For:** Background music, content creators, experimentation
- **Pricing:** Free (limited regions: US, Australia, New Zealand, Kenya, expanding)
- **Statistics:** 10+ million tracks created

**[Google MusicFX DJ](https://labs.google/fx/tools/music-fx-dj)**

- Live, interactive real-time AI music mixing and jamming tool
- Mix multiple prompts and stems in real time with DJ-style controls
- Control genre, intensity, arrangement live with real-time sliders
- Built with input from artist Jacob Collier
- **Best For:** Live performances, DJ sets, experimental music, interactive creation
- **Pricing:** Free (same regions as MusicFX, limited access)
- **Comparison:** More interactive than Suno/Udio for live tweaking; superior for ambient/loop-based generation

**[Google Music AI Sandbox](https://labs.google/fx)** ⭐ NEW Q1 2026

- Professional music creation tools for musicians and creators
- AI-powered composition, arrangement, and vocal tools
- Integration with YouTube creator tools
- Powered by Lyria + YouTube ecosystem
- **Best For:** Professional musicians, YouTube creators, advanced production
- **Pricing:** Free beta | Premium features coming
- **Comparison:** Comprehensive suite rivaling traditional DAWs; YouTube-integrated workflow

**MiniMax Music (duplicate entry removed)**

- See the earlier MiniMax Music 2.6 entry; this duplicate legacy listing is retained only as a cross-reference

**[Mubert](https://mubert.com)** – Real-time generative music (streams/apps, API)
**[Soundraw](https://soundraw.io)** – Royalty-free, customizable length/genres
**[Boomy](https://boomy.com)** – Quick tracks for social/streaming
**[Loudly](https://www.loudly.com)** – AI music + vast catalog
**[Beatoven.ai](https://www.beatoven.ai)** – Mood-based, ethically trained
**[Soundful](https://soundful.com)** – Template-based with stem exports
**[Splash Pro](https://www.splashmusic.com)** – Music + custom AI singing voices
**[Mureka](https://mureka.ai)** – Personal model training, region-specific editing
**[Sonauto](https://sonauto.ai)** – Offers unlimited free song generation with custom lyrics

**[Maestro](https://soundcraft.ai/blog/maestro-public-beta)** (Soundcraft) ⭐ NEW Q1 2026

- State-of-the-art AI sample generator (Feb 16, 2026)
- Studio-quality audio samples from text descriptions
- Trained on synthetic and ethically sourced data
- Browser-based with no usage limits (free)
- Desktop app for macOS (paid plan)
- **Best For:** Producers, audio engineers, sample-based production
- **Pricing:** Free browser | $9.99/month desktop

**[ACE Step v1.5](https://story321.com/blog/ace-step-v15)** ⭐ NEW Q1 2026

- Fast, controllable AI music engine for creators
- Speed, coherence, fine-grained control in single workflow
- Compose, remix, and refine audio efficiently
- **Best For:** Video creators, designers, voice actors needing soundtracks
- **Pricing:** Check website for details

**[Audiotool Studio](https://audiotool.com)** ⭐ NEW Q1 2026

- Browser-based music creation platform (Feb 2026 open beta)
- Fresh canvas for musical experimentation
- Integrates AI-assisted production tools
- **Best For:** In-browser music creation, collaborative workflows
- **Pricing:** Free beta

### Voice & Speech Synthesis (TTS)

**[ElevenLabs](https://elevenlabs.io)**

- Industry-standard ultra-realistic voice cloning
- 29 languages, emotional tags, **Dubbing Studio**
- Often indistinguishable from human speech
- **Best For:** Voiceovers, podcasts, audiobooks, dubbing
- **Pricing:** Free tier (10k chars/month) | $5/month+

**[Murf.ai](https://murf.ai)**

- Professional voiceover studio (120+ voices)
- Drag-and-drop, transcription, voice-to-video sync
- **Best For:** Explainer videos, e-learning, corporate presentations
- **Pricing:** Free tier (10 mins) | $29/month+

**[KITS AI](https://www.kits.ai)** ⭐ NEW

- Royalty-free singing voice converter (2025 artist partnerships)
- Voice-to-voice; custom training (30-min uploads); choir modes
- Retains performance nuances; commercially ready
- **Best For:** Music producers needing vocal cloning with emotion retention
- **Pricing:** Freemium | $9.99/month Pro
- **Comparison:** Cloning edge over [Resemble AI](https://www.resemble.ai) for singing; enhances [Uberduck](https://uberduck.ai) celebrity voices

**[ACE Studio](https://acestudio.ai)** ⭐ NEW

- DAW-integrated voice changer (2025 VST3 bridge)
- Granular MIDI edits; multi-voice choirs; timbre controls
- DAW sync; emotional articulations
- **Best For:** Professional music production with DAW integration
- **Pricing:** $99 base | Additional voices $29+
- **Comparison:** Pro rival to Synthesizer V; beats [Descript](https://www.descript.com) for music-focused workflows

**[Synthesizer V Studio 2 Pro](https://dreamtonics.com/synthesizerv)** (Dreamtonics) ⭐ NEW

- DAW for singing synthesis (May 2025 v2 release)
- Waveform-MIDI hybrid; articulation sculpting
- Realistic emotions; 100+ voice options
- **Best For:** Advanced vocal production requiring time investment
- **Pricing:** $89 base | Voices $79+
- **Comparison:** Advanced vs. Vocaloid; pairs with [Coqui TTS](https://github.com/coqui-ai/TTS) for hybrid workflows

**[Uberduck](https://uberduck.ai)** ⭐ NEW

- TTS with singing capabilities (2025 Grimes AI update)
- Celebrity voices; royalty-share model (50% to artists)
- DMCA-safe with artist partnerships
- **Best For:** Experimental celebrity-style voices, fun projects
- **Pricing:** Free | Premium voices $10/month
- **Comparison:** Niche vs. [Voxdazz](https://voxdazz.com); extends [Hume](https://www.hume.ai) for emotional range

**[Play.ht](https://play.ht)** – Enterprise voice cloning, real-time TTS, SEO integration
**[Resemble AI](https://www.resemble.ai)** – Custom voice cloning (IVR systems, interactive AI)
**[Fish Audio](https://fish.audio)** ⭐ NEW Q1 2026

- Advanced voice cloning with superior accent retention (January 2026)
- Specialized in Asian language support (Chinese, Japanese, Korean)
- Real-time voice conversion with emotional preservation
- **Best For:** Multilingual content, Asian market localization, accent-accurate cloning
- **Pricing:** Free tier | $15/month Pro
- **Comparison:** Better accent retention than ElevenLabs for Asian languages; emerging ElevenLabs alternative

**[MorVoice](https://morvoice.ai)** ⭐ NEW Q1 2026

- Enterprise-grade voice cloning with custom model training (February 2026)
- Specialized in brand voice consistency and multi-speaker projects
- API-first approach for developer workflows
- **Best For:** Enterprise branding, multi-voice projects, developer integrations
- **Pricing:** Custom enterprise pricing | API access available
- **Comparison:** Enterprise focus rivals Play.ht; better API flexibility than Resemble AI

**[WellSaid Labs](https://wellsaidlabs.com)** – Studio-quality, emotionally tagged (enterprise/ads)
**[Speechify](https://speechify.com)** – Natural TTS reader (accessibility, audiobooks)
**[Descript Overdub](https://www.descript.com/overdub)** – Voice cloning in audio/video editor
**[Listnr](https://www.listnr.ai)** – 1000+ voices, 142 languages, voice cloning
**LOVO AI (Genny)** – Multilingual with video sync/lip-sync
**[Hume](https://www.hume.ai)** – Emotionally-aware AI voices from prompts
**[Cartesia.ai](https://cartesia.ai)** – Real-time, low-latency voice (interactive apps)
**[Voxdazz](https://voxdazz.com)** – Celebrity-style voice generation
**[iMyFone VoxBox](https://voxbox.imyfone.com)** – 3200+ voices with emotion controls

**Cloud TTS APIs:**

- **[Google Cloud TTS](https://cloud.google.com/text-to-speech)**
- **[Amazon Polly](https://aws.amazon.com/polly)**
- **[Microsoft Azure TTS](https://azure.microsoft.com/products/ai-services/text-to-speech)**
  Enterprise-level, multi-language synthesis

### Audio Cleanup & Enhancement

**[Adobe Enhance Speech](https://podcast.adobe.com/enhance)** – Studio-quality voice cleanup (web/app)
**[Auphonic](https://auphonic.com)** – Auto level/EQ/noise, batch pipelines
**[Krisp](https://krisp.ai)** – Live noise cancellation
**[Cleanvoice](https://cleanvoice.ai)** – Removes filler words, clicks, mouth sounds
**[iZotope RX](https://www.izotope.com/en/products/rx.html)** – Pro repair (hum/clicks/reverb)
**[Moises](https://moises.ai)** – **Stem separation**, smart metronome, practice
**[Landr](https://www.landr.com)** – AI mastering + distribution

### AI Content Detection & Watermarking ⭐ NEW Q1 2026

**[Google SynthID](https://deepmind.google/technologies/synthid/)**

- Invisible digital watermarking for AI-generated content (image/video/audio/text)
- Detects content created with Google AI tools (Gemini, Imagen, Veo, Lyria)
- Remains detectable after cropping, resizing, filtering, compression
- Public detector portal for verification (synthid.google.com)
- **Best For:** Content authenticity verification, AI transparency, copyright protection
- **Pricing:** Free detection | Watermarking included with Google AI tools
- **Comparison:** Only multi-modal watermarking solution; embedded in 20B+ pieces of content

---

### Open-Source Audio

**[Suno Bark](https://github.com/suno-ai/bark)** – Expressive speech/SFX (open model)
**[Coqui TTS](https://github.com/coqui-ai/TTS)** – Robust open TTS toolkit
**[Tortoise-TTS](https://github.com/neonbjb/tortoise-tts)** – High-quality (slower) research TTS
**[Demucs](https://github.com/facebookresearch/demucs)** – SOTA music source separation (stems)
**[OpenAI Jukebox](https://openai.com/research/jukebox)** – Research neural music generation

---

## 🧩 3D, NeRF, ANIMATION & SPATIAL

**[Luma AI](https://lumalabs.ai)** – 3D capture (NeRF) + video generation (Dream Machine/Ray)
**[Spline AI](https://spline.design/ai)** – Browser-based 3D creation with AI assists
**[Kaedim](https://kaedim3d.com)** – 2D→3D meshes for games
**[Masterpiece Studio](https://www.masterpiecestudio.com)** – 3D character gen/rigging
**[CSM.ai](https://csm.ai)** – Text/image→3D model generation
**[TripoSR / OpenLRM](https://github.com/VAST-AI/TripoSR)** – Single-image→3D (open-source)
**Stability "Virtual Mode"** – 3D/4D camera/view tools (2025 updates)

**[Trellis 2](https://www.3daistudio.com/blog/3daistudio/trellis-2-create-stunning-3d-assets-in-just-seconds)** ⭐ NEW Q1 2026

- Next-gen 3D generation model producing production-ready meshes and PBR textures
- Handles fine geometry and realistic materials (glass, metal, cloth) with ease
- Text-to-3D and image-to-3D capabilities in seconds
- **Best For:** Designers, game studios, product teams needing high-quality 3D assets
- **Pricing:** Available via 3D AI Studio subscription ($14/month)
- **Comparison:** Outperforms previous models in geometry quality and material realism

**[Meshy-6](https://www.meshy.ai/blog/meshy-6-launch)** ⭐ NEW Q1 2026

- Refined 3D generation model with cleaner geometry and sharper hard-surface details
- Features Low Poly Mode, multi-color 3D printing, and upgraded APIs
- Anatomically accurate characters and optimized hard-surface models
- **Best For:** Professional 3D artists and production workflows
- **Pricing:** Check Meshy.ai for details
- **Comparison:** Improved geometry and workflow features over Meshy 5

**[Marble](https://www.worldlabs.ai/blog/marble-world-model)** ⭐ NEW Q1 2026

- Multimodal world model that creates interactive 3D worlds from text, images, video, or 3D layouts
- Supports real-time editing, expansion, and simulation of 3D environments
- **Best For:** Interactive 3D experiences, game development, virtual worlds
- **Pricing:** Free access available | Paid plans for advanced features
- **Comparison:** Multimodal world-generation platform

**[Genie 3 / Project Genie](https://deepmind.google/models/genie/)** (Google DeepMind)

- General-purpose world model that generates explorable environments from text prompts
- Project Genie is an experimental research prototype, not a conventional production 3D modelling package
- **Best For:** World-model research, interactive environment exploration, and prototyping
- **Correction:** The unofficial `genie3-ai.world` link and fixed resolution/physics claims were removed

**[Tencent Hunyuan 3D / HunyuanWorld](https://github.com/Tencent-Hunyuan)**

- Official open 3D ecosystem includes Hunyuan3D 2.1/2.5-era asset generation, Hunyuan3D-Omni controls, and HunyuanWorld / HY-World-2.0 for explorable worlds
- **Verified 2026 update:** HY-World-2.0 was released April 16, 2026 through Tencent-Hunyuan's official repositories
- **Correction:** The unofficial `hunyuan3d.net` page and unsupported “3.6 billion voxels / 1.5 million faces” specifications were removed
- **Best For:** Open research, 3D asset generation, controllable geometry, and world generation

**[OpenArt Worlds](https://openart.ai)** ⭐ NEW Q1 2026

- Persistent 3D environments from text prompts (March 18, 2026).
- Navigable with camera control; exports to **Gaussian Splat** or 3D Mesh.

**[Wonder 3D](https://wonder3d.ai)** ⭐ NEW Q1 2026

- Autodesk Flow Studio (March 4, 2026) text/image-to-3D workflows.
- Generates editable characters and objects for engine integration.

**[Tripo Smart Mesh P1.0](https://tripoai.com)** ⭐ NEW Q2 2026

- **Tripo H3.1**: High-fidelity flagship for detailed geometry/textures.
- **Substance 3D Painter 12.0**: New AI texturing tools and OpenPBR support (March 9, 2026).
- **Hitem3D 2.0**: Industrial-grade 3D for manufacturing (March 18, 2026).
- Production-grade 3D diffusion architecture (April 1, 2026).
- Engine-ready assets generated in **2 seconds**.

**[Meshy AI + Formlabs](https://meshy.ai)** ⭐ NEW Q2 2026

- Professional 3D printing fulfillment integration (April 14, 2026).
- Supports xTool, Snapmaker, and Flashforge.

---

## 🌐 MULTI-MODAL PLATFORMS & ECOSYSTEMS

**[Adobe Firefly AI Assistant](https://firefly.adobe.com)** ⭐ NEW Q2 2026

- Conversational agent (April 15, 2026) orchestrating multi-step workflows.
- Integrates Creative Cloud apps with third-party models (Claude, Google, OpenAI).

**[OpenClaw 2026.4.5](https://openclaw.ai)** ⭐ NEW Q2 2026

- Agent framework (April 6, 2026) with built-in `music_generate` and `video_generate` tools.
- Orchestrates Google Lyria, MiniMax, Wan, and Runway.

**[Pixazo Platform & API](https://pixazo.ai)** ⭐ NEW Q2 2026

- Multi-modal AI design platform (April 17, 2026) for image, video, and music.
- Unified API for **600+ models**; enterprise-ready (SOC 2).

**[Genra AI](https://genra.ai)** ⭐ NEW Q2 2026

- AI video agent platform with chat-to-video workflows (April 2026).
- Built-in skills for e-commerce, social, and product demos.

**[Async Platform](https://async.ai)** ⭐ NEW Q1 2026

- Platform integrated with over **100 AI models** (March 23, 2026).
- Handles video, image, avatar, and music generation in a unified interface.

**[WeryAI Platform](https://wery.ai)** ⭐ NEW Q2 2026

- Integrated multi-model content creation (April 2026).
- Workflow for image, video, and advertising production for 3M+ users.

**[Google Gemini / Google Labs Ecosystem](https://gemini.google.com)**

- Hub for **Gemini native image models**, **Veo 3/Veo 3.1**, **Nano Banana/Nano Banana 2**, **Gemini 3 Pro Image**
- Gateway to Google's generative AI ecosystem
- Now includes experimental/production tools under [Google Labs](https://labs.google/fx) and [Gemini Labs](https://gemini.google/overview/gemini-labs/):
  - **[ImageFX](https://labs.google/fx/imagefx)** → Text-to-image ideation (free, 110+ countries, 37 languages)
  - **[Whisk](https://labs.google/fx/whisk)** → Image-to-image blending with visual prompts (free, 140+ countries)
  - **[MusicFX](https://labs.google/fx/tools/music-fx)** → Text-to-music loops up to 70s (free, limited regions)
  - **[MusicFX DJ](https://labs.google/fx/tools/music-fx-dj)** → Real-time generative music mixing (free, limited access)
  - **[Flow](https://labs.google/flow/about)** → Cinematic AI video (via AI Pro/Ultra subscription)
  - **[Flow for Workspace](https://www.webpronews.com/google-launches-flow-ai-powered-video-creation-for-workspace/)** → AI video for businesses (Jan 2026)
  - **[Gemini Canvas](https://gemini.google/overview/canvas/)** → AI workspace for image/code creation (March 2026 US rollout)
  - **[ProducerAI](https://blog.google/innovation-and-ai/models-and-research/google-labs/producerai/)** → Professional music creation with Lyria 3 (Feb 2026)
  - **[Dream Track](https://support.google.com/youtube/answer/14151606)** → YouTube Shorts AI music powered by Lyria
  - **[GenType](https://labs.google/gentype)** → Custom alphabet/letterform generation (free)
  - **[Music AI Sandbox](https://labs.google/fx)** → Professional music tools for creators (free beta)
  - **[Instrument Playground](https://labs.google)** → Global instrument sounds (free, educational)
  - **[Viola the Bird](https://labs.google)** → Interactive AI cello art piece (free, accessibility-focused)
- **SynthID** watermarking embedded in all Google AI-generated content (image/video/audio/music)
- **Statistics:** 5+ billion images (Nano Banana), 275+ million videos (Flow), 10+ million tracks (MusicFX)
- **Pricing:** Free tier (AI Studio) | Gemini Advanced $20/month | AI Pro/Ultra for premium features

**[Runway](https://runwayml.com)**

- End-to-end creative suite: **Gen-4**, **Aleph**, **Image API**, **Frames**
- Professional VFX tools integrated
- **Pricing:** Free tier | $15/month+

**[Alibaba/Qwen](https://qwen.ai)**

- **[Tongyi Wanxiang](https://tongyi.aliyun.com/wx)** (image) + **Wan** (video)
- Enterprise via Alibaba Cloud Model Studio
- Strong Chinese + English support

**[xAI / Grok](https://x.ai)**

- Image/video via FLUX (Black Forest Labs)
- Integrated into X (Twitter) platform

**[Apple Intelligence](https://www.apple.com/apple-intelligence)**

- **Image Playground** + **Genmoji** (on-device)
- Privacy-first, OS-integrated
- iOS/macOS only

**[Microsoft Copilot / Designer](https://copilot.microsoft.com)**

- [DALL·E 3](https://openai.com/index/dall-e-3)-backed image generation
- Microsoft ecosystem integration

**[Magic Hour](https://magichour.ai)** ⭐ NEW Q1 2026

- All-in-one AI creation platform combining image editing, animation, and video generation
- Supports real creative pipelines from idea to final video
- **Best For:** Creators, marketers, and startup builders needing a practical, well-rounded solution
- **Pricing:** Check MagicHour.ai for details
- **Comparison:** Most practical multi-modal platform tested; balances features and usability

**[Meta Imagine / EMU](https://imagine.meta.com)**

- Chat-native image generator (Messenger/WhatsApp)
- EMU research for video/editing

**[Anthropic Claude](https://www.anthropic.com/claude)**

- Primarily text, but latest versions analyze/reason about images

---

> **Dynamic-data caution (June 24, 2026):** Prices, free quotas, arena ranks, generation speeds, and availability can change without notice. Tables below are useful for orientation, but purchase/production decisions should be checked against the vendor's live pricing, license, model card, and status page.

## 📊 QUICK REFERENCE TABLES

### By Primary Use Case

| **Use Case**                         | **Top Recommendations**                                                                                                                                                                                                                                                                                                                            |
| ------------------------------------ | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Artistic/Cinematic Images**        | [Midjourney](https://www.midjourney.com), [Stable Diffusion](https://stability.ai/stable-diffusion), [Monica AI](https://monica.im)                                                                                                                                                                                                                |
| **Photorealistic Images**            | Imagen 4, FLUX.2 [pro], [Leonardo.Ai](https://leonardo.ai), [Nano Banana 2](https://blog.google/innovation-and-ai/technology/ai/nano-banana-2/), [Gemini 3 Pro Image](https://ai.google.dev/gemini-api/docs/image-generation)                                                                                                                      |
| **Text-in-Images (Logos)**           | [Ideogram 4.0](https://ideogram.ai/models/4.0/), [GLM-Image](https://z.ai/blog/glm-image)                                                                                                                                                                                                                                                          |
| **Image-Based Prompting**            | [Whisk](https://labs.google/fx/whisk), [Freepik Pikaso](https://pika.freepik.com)                                                                                                                                                                                                                                                                  |
| **Commercial Safety (IP-Protected)** | Getty Generative AI, [Adobe Firefly](https://www.adobe.com/products/firefly.html), [Shutterstock AI](https://www.shutterstock.com/generate)                                                                                                                                                                                                        |
| **Free Experimentation**             | [Google ImageFX](https://labs.google/fx/imagefx), [Meta Imagine](https://imagine.meta.com), [Stable Diffusion](https://stability.ai/stable-diffusion), [Nano Banana 2](https://blog.google/innovation-and-ai/technology/ai/nano-banana-2/)                                                                                                         |
| **Cinematic Video (Gated)**          | Sora, [Veo 3](https://deepmind.google/technologies/veo/), [Veo 3.1](https://ai.google.dev/gemini-api/docs/video)                                                                                                                                                                                                                                   |
| **Cinematic AI Filmmaking**          | [Flow](https://labs.google/flow/about), [Runway Gen-4.5](https://runwayml.com) + [Aleph 2.0](https://runwayml.com/product/aleph-2), [Kling 3.0](https://www.klingai.com), [Seedance 2.0](https://seed.bytedance.com/en/blog/official-launch-of-seedance-2-0)                                                                                       |
| **Production Video**                 | [Runway Gen-4.5](https://runwayml.com) + [Aleph 2.0](https://runwayml.com/product/aleph-2), [Kling 3.0](https://www.klingai.com), [LTX Studio](https://ltxstudio.com), [Seedance 2.0](https://seed.bytedance.com/en/blog/official-launch-of-seedance-2-0), [Digen RM3.0](https://digen.ai), [Veo 3.1](https://ai.google.dev/gemini-api/docs/video) |
| **Business/Workspace Video**         | [Google Vids](https://workspace.google.com/products/vids/), [Synthesia](https://www.synthesia.io), [Capsule](https://capsule.video)                                                                                                                                                                                                                |
| **Animated Video**                   | [Vyond](https://www.vyond.com), [Steve.AI](https://www.steve.ai), [Viggle AI](https://viggle.ai)                                                                                                                                                                                                                                                   |
| **Business Avatars**                 | [Synthesia](https://www.synthesia.io), [HeyGen](https://www.heygen.com), [Capsule](https://capsule.video)                                                                                                                                                                                                                                          |
| **Social Media Repurposing**         | [revid.ai](https://www.revid.ai), [OpusClip](https://www.opus.pro), [Peech](https://www.peech.co)                                                                                                                                                                                                                                                  |
| **Music Creation**                   | Suno, [Udio](https://www.udio.com), [AIVA](https://www.aiva.ai), [Stable Audio](https://www.stableaudio.com), [Lyria 3](https://blog.google/innovation-and-ai/products/gemini-app/lyria-3/), [MiniMax Music 2.5](https://www.minimax.io/news/minimax-music-25)                                                                                     |
| **Real-Time Music Jamming**          | [MusicFX DJ](https://labs.google/fx/musicfx), [Mubert](https://mubert.com), [Maestro](https://soundcraft.ai/blog/maestro-public-beta), [ProducerAI](https://blog.google/innovation-and-ai/models-and-research/google-labs/producerai/)                                                                                                             |
| **YouTube Shorts Music**             | [Dream Track](https://support.google.com/youtube/answer/14151606) (Lyria-powered)                                                                                                                                                                                                                                                                  |
| **Voice Cloning (Speech)**           | [ElevenLabs](https://elevenlabs.io), [Play.ht](https://play.ht), [Murf.ai](https://murf.ai)                                                                                                                                                                                                                                                        |
| **Voice Cloning (Singing)**          | [KITS AI](https://www.kits.ai), [ACE Studio](https://acestudio.ai), [Synthesizer V Studio 2 Pro](https://dreamtonics.com/synthesizerv)                                                                                                                                                                                                             |
| **3D Generation**                    | [Luma AI](https://lumalabs.ai), [Spline AI](https://spline.design/ai), [CSM.ai](https://csm.ai), [Trellis 2](https://www.3daistudio.com/blog/3daistudio/trellis-2-create-stunning-3d-assets-in-just-seconds), [Meshy-6](https://www.meshy.ai/blog/meshy-6-launch), [Marble](https://www.worldlabs.ai/blog/marble-world-model)                      |
| **Multi-Modal Platforms**            | [Magic Hour](https://magichour.ai), [Google Gemini](https://gemini.google.com), [Runway](https://runwayml.com)                                                                                                                                                                                                                                     |
| **AI Content Detection**             | [Google SynthID](https://deepmind.google/technologies/synthid/)                                                                                                                                                                                                                                                                                    |

### By Pricing Model

| **Free/Freemium**                                         | **Subscription**                                | **API/Enterprise**                                                                                                    |
| --------------------------------------------------------- | ----------------------------------------------- | --------------------------------------------------------------------------------------------------------------------- |
| [Stable Diffusion](https://stability.ai/stable-diffusion) | [Midjourney](https://www.midjourney.com) ($10+) | [Gemini API](https://ai.google.dev/gemini-api)                                                                        |
| [Google ImageFX](https://labs.google/fx/imagefx)          | [ChatGPT Plus](https://chat.openai.com) ($20)   | Alibaba Cloud (Qwen)                                                                                                  |
| [Meta Imagine](https://imagine.meta.com)                  | Adobe CC ($10–$20)                              | [OpenAI API](https://platform.openai.com)                                                                             |
| Copilot (limited)                                         | [Runway](https://runwayml.com) ($15+)           | [Azure](https://azure.microsoft.com)/[AWS](https://aws.amazon.com)/[GCP TTS](https://cloud.google.com/text-to-speech) |
| Ideogram (40/day)                                         | [ElevenLabs](https://elevenlabs.io) ($5+)       | [Vertex AI](https://cloud.google.com/vertex-ai)                                                                       |
| Suno (basic)                                              | [Vyond](https://www.vyond.com) ($25)            | [Getty API](https://developer.gettyimages.com/enterprise/generative-ai) ($0.05/gen)                                   |
| ByteDance SeedDream                                       | [LTX Studio](https://ltxstudio.com) ($29)       | [Stable Audio API](https://www.stableaudio.com)                                                                       |

### Open-Source Alternatives

| **Category**      | **Open-Source Tool**                                                                                                                                                               |
| ----------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Image Gen**     | [Stable Diffusion](https://stability.ai/stable-diffusion) (SD/SDXL/SD3)                                                                                                            |
| **Image Editing** | [AUTOMATIC1111](https://github.com/AUTOMATIC1111/stable-diffusion-webui), [ComfyUI](https://github.com/comfyanonymous/ComfyUI), [Invoke AI](https://github.com/invoke-ai/InvokeAI) |
| **Video Gen**     | Stable Video Diffusion, [AnimateDiff](https://github.com/guoyww/AnimateDiff)                                                                                                       |
| **Audio TTS**     | [Coqui TTS](https://github.com/coqui-ai/TTS), Bark, [Tortoise-TTS](https://github.com/neonbjb/tortoise-tts)                                                                        |
| **Music/Stems**   | [Stable Audio](https://www.stableaudio.com), [Demucs](https://github.com/facebookresearch/demucs), [OpenAI Jukebox](https://openai.com/research/jukebox)                           |
| **Enhancement**   | [GFPGAN](https://github.com/TencentARC/GFPGAN), [Real-ESRGAN](https://github.com/xinntao/Real-ESRGAN), [Lama Cleaner](https://github.com/Sanster/lama-cleaner)                     |
| **3D**            | [TripoSR](https://github.com/VAST-AI/TripoSR), [OpenLRM](https://github.com/3DTopia/OpenLRM)                                                                                       |

### 2025 Q4 Trending Additions

| **Tool**                                             | **Category**    | **Key Innovation**                         | **Why It Matters**                                     |
| ---------------------------------------------------- | --------------- | ------------------------------------------ | ------------------------------------------------------ |
| **Getty Generative AI**                              | Image           | Commercial indemnification at scale        | Addresses IP litigation fears for enterprises          |
| **[Google ImageFX](https://labs.google/fx/imagefx)** | Image           | Free unlimited experimentation             | Democratizes access vs. paid tiers                     |
| **[Vyond](https://www.vyond.com)**                   | Video           | Prompt-to-animation with motion capture    | Fills animation gap in generative space                |
| **[LTX Studio](https://ltxstudio.com)**              | Video           | Scene-by-scene narrative control           | Pre-production workflow missing in competitors         |
| **[Flow](https://labs.google/flow/about)**           | Video           | Integrated cinematic storytelling with Veo | Brings Hollywood-grade AI video to mainstream creators |
| **[Stable Audio](https://www.stableaudio.com)**      | Music           | Open-source sound effects/stems            | Breaks proprietary stranglehold on production audio    |
| **[MusicFX DJ](https://labs.google/fx/musicfx)**     | Audio           | Slider-controlled multi-prompt music       | Democratizes live composition without musical training |
| **[Whisk](https://labs.google/fx/whisk)**            | Image           | Image-as-prompt generation                 | Bypasses language barriers in visual creation          |
| **[KITS AI](https://www.kits.ai)**                   | Voice (Singing) | Royalty-free vocal conversion              | Enables legal commercial singing clones                |
| **[ACE Studio](https://acestudio.ai)**               | Voice (Singing) | DAW-native integration (VST3)              | Bridges gap between AI and professional music tools    |

### 2026 Q1 Trending Additions (Nov 2025 - Mar 2026)

| **Tool**                                                                                                          | **Category** | **Key Innovation**                                | **Why It Matters**                                                           |
| ----------------------------------------------------------------------------------------------------------------- | ------------ | ------------------------------------------------- | ---------------------------------------------------------------------------- |
| **[Kling 3.0](https://www.klingai.com)**                                                                          | Video        | 15s + 4K + native audio in single model           | Unified video and audio generation                                           |
| **[Seedance 2.0](https://seed.bytedance.com/en/blog/official-launch-of-seedance-2-0)**                            | Video        | Quad-modal input (text+image+video+audio)         | Unified multimodal audio-video generation                                    |
| **[Nano Banana 2](https://blog.google/innovation-and-ai/technology/ai/nano-banana-2/)**                           | Image        | Pro quality at Flash speed                        | Default Google image model; 2-3x faster                                      |
| **[GLM-Image](https://z.ai/blog/glm-image)**                                                                      | Image        | Open-source 16B with best text rendering          | First industrial-grade autoregressive open model                             |
| **[MiniMax Image-01](https://www.minimax.io/news/image-01)**                                                      | Image        | MiniMax image generation; verify live API pricing | Pricing varies by API plan                                                   |
| **[Lyria 3](https://blog.google/innovation-and-ai/products/gemini-app/lyria-3/)**                                 | Music        | Text/image to 30s track in Gemini                 | Puts music creation in 750M+ users' hands                                    |
| **[MiniMax Music 2.6](https://www.minimax.io/news/music-26)**                                                     | Music        | 4-minute tracks with full control                 | Direct competitor to Suno v5.5                                               |
| **[Digen RM3.0](https://digen.ai)**                                                                               | Video        | Professional 2K + audio in seconds                | Enterprise-grade production workflow                                         |
| **[ProducerAI](https://blog.google/innovation-and-ai/models-and-research/google-labs/producerai/)**               | Music        | Google Labs music partner                         | Advanced pro-level controls                                                  |
| **[Maestro](https://soundcraft.ai/blog/maestro-public-beta)**                                                     | Audio        | Browser-based sample generation                   | Free studio-quality samples                                                  |
| **[Trellis 2](https://www.3daistudio.com/blog/3daistudio/trellis-2-create-stunning-3d-assets-in-just-seconds)**   | 3D           | Production-ready meshes + PBR textures            | Handles fine geometry and realistic materials better than previous models    |
| **[Meshy-6](https://www.meshy.ai/blog/meshy-6-launch)**                                                           | 3D           | Cleaner geometry + hard-surface details           | Improves character and hard-surface modeling with new workflows              |
| **[Marble](https://www.worldlabs.ai/blog/marble-world-model)**                                                    | 3D           | Multimodal world model                            | Creates interactive 3D worlds from text, images, video, or 3D layouts        |
| **[Genie 3](https://deepmind.google/models/genie/)**                                                              | 3D           | Interactive 3D world generation                   | Google DeepMind tool with real-time physics simulation                       |
| **[Tencent Hunyuan 3D / HunyuanWorld](https://github.com/Tencent-Hunyuan)**                                       | 3D           | Ultra-high resolution voxel precision             | Tencent's next-gen system with 3.6B voxels and dual-stage textures           |
| **[Magic Hour](https://magichour.ai)**                                                                            | Multi-Modal  | All-in-one AI creation platform                   | Combines image editing, animation, and video generation in a single workflow |
| **[Microsoft MAI-Image-1](https://microsoft.ai/news/introducing-mai-image-1-debuting-in-the-top-10-on-lmarena/)** | Image        | First in-house model, top 10 LMArena              | Microsoft's answer to DALL·E 3/Midjourney; integrated into Copilot           |
| **[Wan 2.6](https://wan.video)**                                                                                  | Video        | 15s multi-shot with "Video Roleplay"              | Open-source; superior character consistency                                  |
| **[Hailuo 2.3](https://hailuoai.video)**                                                                          | Video        | Breathtaking motion + emotion                     | Fast variant for rapid iteration; rivals Kling motion                        |
| **[Runway Gen-4.5](https://runwayml.com)**                                                                        | Video        | Image-to-video for longer stories                 | Adobe Firefly integration; Updated image-to-video generation and editing     |
| **[Fish Audio](https://fish.audio)**                                                                              | Voice        | Asian language accent retention                   | Focus on multilingual and Asian-language voice workflows                     |
| **[MorVoice](https://morvoice.ai)**                                                                               | Voice        | Enterprise brand voice consistency                | API-first; multi-speaker projects                                            |
| **[ImageCritic](https://www.kombitz.com/2026/03/05/imagecritic-improves-ai-image-editing-accuracy/)**             | Enhancement  | AI quality control for generated images           | Research-oriented image consistency checking                                 |

---

## 🔗 2025-2026 KEY UPDATES & SOURCES

### Major Platform Updates (Q1 2026)

- **Kling 3.0** (Feb 2026) = 15s video, 4K output, native audio-video co-generation
- **Seedance 2.0** (Feb 2026) = ByteDance quad-modal breakthrough; first true audio-video sync
- **Nano Banana 2** (Feb 2026) = Google's default image model; 2-3x faster than Pro
- **GLM-Image** (Jan 2026) = Open hybrid autoregressive/diffusion image model
- **Lyria 3** (Feb 2026) = Music generation in Gemini app (750M+ users)
- **MiniMax Music 2.6** (Apr 2026) = current structured music model
- **[Flow](https://blog.google/innovation-and-ai/models-and-research/google-labs/flow-updates-february-2026/)** adds new editing features (Feb 2026)
- **Trellis 2** (Jan 2026) = Next-gen 3D model with production-ready meshes and PBR textures
- **Meshy-6** (Jan 2026) = Refined 3D generation with cleaner geometry and hard-surface details
- **Marble** (Nov 2025) = Multimodal world model for interactive 3D environments
- **Genie 3 AI** (Jan 2026) = Google DeepMind tool for real-time 3D world generation
- **Hunyuan 3D 3.0** (Sep 2025) = Tencent's ultra-high resolution 3D system
- **Magic Hour** (Q1 2026) = All-in-one AI creation platform combining image editing, animation, and video generation
- **Microsoft MAI-Image-1** (Oct 2025) = Microsoft's first in-house image generator; top 10 LMArena debut
- **Wan 2.6** (Dec 2025) = Alibaba's 15s multi-shot video with "Video Roleplay"; open-source weights
- **Hailuo 2.3** (Feb 2026) = MiniMax breakthrough motion quality; Fast variant for rapid iteration
- **Runway Gen-4.5** (Jan 2026) = Image-to-video for longer stories; Adobe Firefly integration
- **Fish Audio** (Jan 2026) = Superior Asian language accent retention for voice cloning
- **MorVoice** (Feb 2026) = Enterprise brand voice consistency with API-first approach
- **ImageCritic** (Mar 2026) = First AI quality control for generated images; reference mismatch detection

### Major Platform Updates (Q4 2025)

- **[Google native Gemini image models](https://ai.google.dev/gemini-api/docs/models)** + **[Veo 3](https://deepmind.google/technologies/veo/)** now GA in [Gemini API](https://ai.google.dev/gemini-api)
- **[Google Veo 3.1](https://ai.google.dev/gemini-api/docs/video)** (Oct 2025) = Enhanced audio, character consistency, 4K support, vertical video (9:16)
- **[Google Veo 3.1 Fast](https://ai.google.dev/gemini-api/docs/video)** (Jan 2026) = 2x faster generation for rapid iteration
- **[Gemini 3 Pro Image](https://ai.google.dev/gemini-api/docs/image-generation)** (Nov 2025) = Premium model with reasoning capabilities
- **"Nano Banana"** (Gemini 2.5 Flash Image) powers Search/Lens edits
- **[Google Vids](https://workspace.google.com/products/vids/)** (Nov 2025) = AI video creation for Workspace, free for Gmail users
- **[ProducerAI](https://blog.google/innovation-and-ai/models-and-research/google-labs/producerai/)** (Feb 2026) = Professional music creation with Lyria 3 in Google Labs
- **[Dream Track](https://support.google.com/youtube/answer/14151606)** = YouTube Shorts AI music powered by Lyria, integrated with Lyria 3
- **[Google SynthID](https://deepmind.google/technologies/synthid/)** = Watermarking for 20B+ pieces of AI content (image/video/audio/text)
- **[Gemini Canvas](https://gemini.google/overview/canvas/)** (Mar 2026) = AI workspace for image/code creation, rolled out to all US users
- **[Runway Aleph 2.0](https://runwayml.com/product/aleph-2)** = breakthrough in-context video editor
- **FLUX.2 [max] / [pro]** = latest Black Forest Labs flagship
- **[Kling](https://apps.apple.com/us/app/kling-ai/id6580029292)** extends to 2-minute clips at 1080p
- **Suno v5.5** adds personas + stem separation
- **[Udio](https://www.udio.com)** offers stem downloads for producers
- **[Stable Audio 3.0](https://stability.ai/stable-audio)** (August 2025) = open music/SFX model

### Industry Trends (Q1 2026)

- **Multimodal Video Revolution:** Seedance 2.0 and Kling 3.0 lead shift from clip generation to unified audio-video production
- **Speed + Quality Balance:** Nano Banana 2 and GLM-Image address enterprise need for fast, accurate output
- **Consumer Music Democratization:** Lyria 3 in Gemini brings music creation to mainstream users
- **Open-Source Surge:** GLM-Image challenges proprietary image generation dominance; Wan 2.6 open-weights
- **Professional Workflows:** Digen RM3.0 targets studio-grade production; Runway Gen-4.5 + Firefly integration
- **3D Generation Maturity:** Trellis 2, Meshy-6, and Marble push 3D AI from experimental to production-ready
- **Microsoft AI Entry:** MAI-Image-1 marks Microsoft's first in-house image generation capability
- **Asian Market Focus:** Fish Audio, Hailuo 2.3, Wan 2.6 target Chinese/Asian language markets
- **Quality Control Emergence:** ImageCritic introduces first AI-powered quality assurance for generated content
- **Enterprise Voice:** MorVoice brings brand-focused voice cloning with API-first developer approach

### Industry Trends (Q4 2025)

- **IP Safety Focus:** Getty and Firefly lead commercially indemnified training
- **Singing Voice Boom:** KITS, [ACE Studio](https://acestudio.ai), Synthesizer V target music producers
- **Animation Democratization:** [Vyond](https://www.vyond.com) and [Steve.AI](https://www.steve.ai) make character animation accessible
- **Pre-Production Tools:** [LTX Studio](https://ltxstudio.com) fills narrative planning gap
- **Open-Source Resurgence:** [Stable Audio](https://www.stableaudio.com) challenges proprietary music models

### Verification Sources

- Zapier: Best AI Image Generators 2026
- CNET: Best AI Image Generators 2025-2026
- Massive.io: Best AI Video Generators Comparison
- AudioCipher: Best AI Singing Voice Generators 2025
- AIMusicPreneur: Best AI Music Generators 2025-2026
- TechCrunch: Google Nano Banana 2 Launch (Feb 2026), ProducerAI Google Labs (Feb 2026), Veo 3.1 Updates
- VentureBeat: GLM-Image Analysis (Jan 2026)
- Google Blog: Lyria 3 Launch (Feb 2026), Veo 3.1 Updates (Oct 2025/Jan 2026), Nano Banana 2 (Feb 2026), ProducerAI (Feb 2026), Gemini Canvas (Mar 2026), Flow Updates (Feb 2026), Gemini 3.1 Pro/Flash-Lite (Feb-Mar 2026)
- Google DeepMind: SynthID Documentation, Gemini 3 Pro Image Model Cards, Lyria Model Information
- Microsoft AI Blog: MAI-Image-1 Announcement (Oct 2025)
- Various: Kling 3.0, Seedance 2.0, Digen RM3.0 coverage (Feb 2026)
- MiniMax official releases: Image-01 (Feb 2025), Music 2.6 (Apr 2026)
- Alibaba Cloud: Wan 2.6 Release Notes (Dec 2025)
- RunwayML: Gen-4.5 Update Announcement (Jan 2026)
- Industry Reports: Fish Audio, MorVoice, ImageCritic (Q1 2026)
- 9to5Google: Nano Banana 2 Rollout (Feb 2026), Gemini Updates, Flow for Workspace
- Ars Technica: Lyria 3 Gemini Integration (Feb 2026)
- The Verge: Google Flow AI Video (May 2025), Veo 3 Coverage, Gemini Features
- WebProNews: Flow for Google Workspace Launch (Jan 2026)
- Google Labs: Official tool documentation and availability information
- Gemini API Documentation: Model specifications and pricing information

---

## 💡 SELECTION GUIDANCE

### For Commercial/Brand Work

- **Images:** Getty Generative AI (indemnification), [Adobe Firefly](https://www.adobe.com/products/firefly.html), [Shutterstock AI](https://www.shutterstock.com/generate)
- **Video:** [Synthesia](https://www.synthesia.io), [HeyGen](https://www.heygen.com) (enterprise-safe), [Capsule](https://capsule.video) (branded workflows)
- **Audio:** [AIVA](https://www.aiva.ai) (copyright-free), licensed TTS APIs, [Stable Audio](https://www.stableaudio.com) (open licensing)

### For Maximum Control

- **Images:** [Stable Diffusion](https://stability.ai/stable-diffusion) + [ComfyUI](https://github.com/comfyanonymous/ComfyUI)/[ControlNet](https://github.com/lllyasviel/ControlNet)
- **Video:** Stable Video Diffusion, [Runway Editor](https://runwayml.com) + [Aleph 2.0](https://runwayml.com/product/aleph-2)
- **Audio:** [Coqui TTS](https://github.com/coqui-ai/TTS), [Stable Audio](https://www.stableaudio.com), [Demucs](https://github.com/facebookresearch/demucs) (open-source)

### For Speed & Ease

- **Images:** [DALL·E 3](https://openai.com/index/dall-e-3) (ChatGPT), [Google ImageFX](https://labs.google/fx/imagefx) (free), [Meta Imagine](https://imagine.meta.com)
- **Video:** [Pika 2.0](https://pika.art), [PixVerse](https://pixverse.ai), [revid.ai](https://www.revid.ai) (templates)
- **Audio:** [ElevenLabs](https://elevenlabs.io), Suno

### For Multilingual/Asian Markets

- **Images:** [Qwen-VL](https://qwenlm.ai)/[Tongyi Wanxiang](https://tongyi.aliyun.com/wx), ByteDance SeedDream
- **Video:** [Kling](https://apps.apple.com/us/app/kling-ai/id6580029292), Qwen Wan, Alibaba Cloud ecosystem
- **Audio:** [Murf.ai](https://murf.ai) (142 languages), [Google Cloud TTS](https://cloud.google.com/text-to-speech)

### For Animation & Creative Storytelling

- **Video:** [Vyond](https://www.vyond.com) (character animation), [LTX Studio](https://ltxstudio.com) (scene control), [AnimateDiff](https://github.com/guoyww/AnimateDiff)
- **Images:** [Monica AI](https://monica.im) (fantasy/anime), [Leonardo.Ai](https://leonardo.ai) (game assets)

### For Music Production

- **Full Songs:** Suno (fast), [Udio](https://www.udio.com) (high-fidelity stems)
- **Sound Effects:** [Stable Audio](https://www.stableaudio.com) (open), [Beatoven.ai](https://www.beatoven.ai) (mood-based)
- **Singing:** [KITS AI](https://www.kits.ai) (commercial-safe), [ACE Studio](https://acestudio.ai) (DAW integration)

### For Experimental & Multimodal Creators

- Use [Whisk](https://labs.google/fx/whisk) to prototype visuals from reference images → refine in [ImageFX](https://labs.google/fx/imagefx).
- Score ambient tracks in [MusicFX DJ](https://labs.google/fx/musicfx) → layer with voiceovers from [ElevenLabs](https://elevenlabs.io).
- Assemble final narrative in [Flow](https://labs.google/flow/about) with consistent characters and native audio.
- **Q1 2026 Pipeline:** Generate images with [Nano Banana 2](https://blog.google/innovation-and-ai/technology/ai/nano-banana-2/) → create music via [Lyria 3](https://blog.google/innovation-and-ai/products/gemini-app/lyria-3/) in Gemini → combine in [Kling 3.0](https://www.klingai.com) for final video

### For Budget-Conscious Users

- **Free Forever:** [Google ImageFX](https://labs.google/fx/imagefx), [Meta Imagine](https://imagine.meta.com), [Stable Diffusion](https://stability.ai/stable-diffusion), [Whisk](https://labs.google/fx/whisk), [MusicFX DJ](https://labs.google/fx/musicfx), [Maestro](https://soundcraft.ai/blog/maestro-public-beta)
- **Best Free Tiers:** Ideogram (40/day), [Leonardo.Ai](https://leonardo.ai) (150 tokens), Suno (basic), [revid.ai](https://www.revid.ai)
- **Best Value:** [MiniMax Image-01](https://www.minimax.io/news/image-01) ($0.01/image), [GLM-Image](https://z.ai/blog/glm-image) ($0.015/image)
- **Open-Source:** [Stable Audio](https://www.stableaudio.com), [Coqui TTS](https://github.com/coqui-ai/TTS), [Demucs](https://github.com/facebookresearch/demucs), [Real-ESRGAN](https://github.com/xinntao/Real-ESRGAN), [GLM-Image](https://z.ai/blog/glm-image)
- [Whisk](https://labs.google/fx/whisk) and [MusicFX DJ](https://labs.google/fx/musicfx) offer free, high-quality alternatives to paid tools—ideal for students and indie creators.

---

## 🎯 WORKFLOW INTEGRATION EXAMPLES

### Content Creator Pipeline

1. **Ideation:** [Google ImageFX](https://labs.google/fx/imagefx) (free prompts) → [Midjourney](https://www.midjourney.com) (hero images)
2. **Video:** [Kling](https://apps.apple.com/us/app/kling-ai/id6580029292) (product demos) → [CapCut](https://www.capcut.com) (editing) → [revid.ai](https://www.revid.ai) (social clips)
3. **Audio:** Suno (background music) → [ElevenLabs](https://elevenlabs.io) (voiceover) → [Auphonic](https://auphonic.com) (cleanup)

### Enterprise Marketing Team

1. **Brand Assets:** Getty Generative AI (legally safe) → [Adobe Firefly](https://www.adobe.com/products/firefly.html) (Photoshop integration)
2. **Training Videos:** [Synthesia](https://www.synthesia.io) (multilingual avatars) → [Capsule](https://capsule.video) (branded edits)
3. **Music:** [AIVA](https://www.aiva.ai) (copyright-free) → [Artlist AI](https://artlist.io/ai) (B-roll integration)

### Independent Filmmaker

1. **Pre-Production:** [LTX Studio](https://ltxstudio.com) (storyboards) → [Midjourney](https://www.midjourney.com) (concept art)
2. **Production:** [Runway Gen-4.5](https://runwayml.com) (establishing shots) → [Aleph 2.0](https://runwayml.com/product/aleph-2) (scene edits)
3. **Post:** [Topaz Video AI](https://www.topazlabs.com/video-ai) (upscaling) → [Descript](https://www.descript.com) (dialogue editing)

### Music Producer

1. **Composition:** [Udio](https://www.udio.com) (full tracks with stems) → [Stable Audio](https://www.stableaudio.com) (custom SFX)
2. **Vocals:** [KITS AI](https://www.kits.ai) (voice conversion) → [ACE Studio](https://acestudio.ai) (DAW refinement)
3. **Mastering:** [Moises](https://moises.ai) (stem separation) → [Landr](https://www.landr.com) (final master)

### Game Developer

1. **Concept Art:** [Leonardo.Ai](https://leonardo.ai) (characters) → [Stable Diffusion](https://stability.ai/stable-diffusion) + [ControlNet](https://github.com/lllyasviel/ControlNet) (poses)
2. **3D Assets:** [Kaedim](https://kaedim3d.com) (2D→3D conversion) → [Spline AI](https://spline.design/ai) (texture generation)
3. **Audio:** [Beatoven.ai](https://www.beatoven.ai) (soundtracks) → [Stable Audio](https://www.stableaudio.com) (game SFX)

### Educator/Course Creator

1. **Visuals:** Canva AI (slides) → [Ideogram 4.0](https://ideogram.ai/models/4.0/) (diagrams with text)
2. **Video:** [Vyond](https://www.vyond.com) (animated explainers) → [Peech](https://www.peech.co) (multi-platform clips)
3. **Voice:** [Murf.ai](https://murf.ai) (narration) → [Speechify](https://speechify.com) (accessibility testing)

---

## 📈 PERFORMANCE BENCHMARKS (Community-Reported)

### Image Generation Speed (Average per 1024x1024 image)

| **Tool**                                                          | **Generation Time** | **Notes**                                   |
| ----------------------------------------------------------------- | ------------------- | ------------------------------------------- |
| [Google ImageFX](https://labs.google/fx/imagefx)                  | 5-10s               | Fastest for experimentation                 |
| [DALL·E 3](https://openai.com/index/dall-e-3)                     | 8-15s               | Via [ChatGPT Plus](https://chat.openai.com) |
| **Nano Banana 2**                                                 | 8-12s               | 2-3x faster than Pro; default Google model  |
| [Midjourney](https://www.midjourney.com)                          | 30-60s              | Quality over speed                          |
| FLUX.2 [pro]                                                      | 10-20s              | Via API                                     |
| [Stable Diffusion](https://stability.ai/stable-diffusion) (local) | 5-30s               | Depends on GPU (RTX 4090 vs. 3060)          |
| ByteDance SeedDream                                               | 2s                  | API; fastest reported                       |
| [GLM-Image](https://z.ai/blog/glm-image)                          | 5-15s               | Open-source; best text rendering            |
| [MiniMax Image-01](https://www.minimax.io/news/image-01)          | 3-10s               | Most cost-effective ($0.01)                 |

### Video Generation Quality (1080p, 5-second clips)

| **Tool**                                                                           | **Prompt Adherence** | **Motion Smoothness** | **Audio Sync** | **Best For**                                    |
| ---------------------------------------------------------------------------------- | -------------------- | --------------------- | -------------- | ----------------------------------------------- |
| Sora                                                                               | ⭐⭐⭐⭐⭐           | ⭐⭐⭐⭐⭐            | ⭐⭐⭐⭐       | Cinematic narratives                            |
| [Kling 3.0](https://www.klingai.com)                                               | ⭐⭐⭐⭐⭐           | ⭐⭐⭐⭐⭐            | ⭐⭐⭐⭐⭐     | 15s + 4K + native audio                         |
| [Seedance 2.0](https://seed.bytedance.com/en/blog/official-launch-of-seedance-2-0) | ⭐⭐⭐⭐⭐           | ⭐⭐⭐⭐⭐            | ⭐⭐⭐⭐⭐     | Quad-modal; enterprise                          |
| [Runway Gen-4.5](https://runwayml.com)                                             | ⭐⭐⭐⭐             | ⭐⭐⭐⭐⭐            | ⭐⭐⭐⭐       | Character consistency                           |
| [Veo 3](https://deepmind.google/technologies/veo/)                                 | ⭐⭐⭐⭐⭐           | ⭐⭐⭐⭐              | ⭐⭐⭐⭐⭐     | Social reels with audio                         |
| [Digen RM3.0](https://digen.ai)                                                    | ⭐⭐⭐⭐             | ⭐⭐⭐⭐              | ⭐⭐⭐⭐       | Professional 2K production                      |
| [Pika 2.0](https://pika.art)                                                       | ⭐⭐⭐               | ⭐⭐⭐                | ⭐⭐⭐         | Stylized shorts                                 |
| [Vyond](https://www.vyond.com)                                                     | ⭐⭐⭐⭐             | ⭐⭐⭐⭐              | ⭐⭐           | Animation (20% better than Pika for characters) |

### Voice Quality (TTS Naturalness, 1-10 scale)

| **Tool**                                                    | **Naturalness** | **Emotional Range** | **Language Support**        |
| ----------------------------------------------------------- | --------------- | ------------------- | --------------------------- |
| [ElevenLabs](https://elevenlabs.io)                         | 9.5/10          | High                | 29 languages                |
| [Play.ht](https://play.ht)                                  | 9/10            | High                | 142 languages               |
| [Murf.ai](https://murf.ai)                                  | 8.5/10          | Medium-High         | 120+ voices                 |
| [Google Cloud TTS](https://cloud.google.com/text-to-speech) | 8/10            | Medium              | 220+ voices, 40+ languages  |
| [KITS AI](https://www.kits.ai) (singing)                    | 9/10            | Very High           | Performance retention       |
| Synthesizer V                                               | 9.5/10          | Very High           | 100+ voices (music-focused) |

---

## ⚠️ IMPORTANT CONSIDERATIONS

### Copyright & Licensing

- **Commercial-Safe Training:** Getty Generative AI, [Adobe Firefly](https://www.adobe.com/products/firefly.html), [Shutterstock AI](https://www.shutterstock.com/generate)
- **Open License Models:** [Stable Diffusion](https://stability.ai/stable-diffusion), [Stable Audio](https://www.stableaudio.com), [Coqui TTS](https://github.com/coqui-ai/TTS)
- **Royalty Models:** [Uberduck](https://uberduck.ai) (50% to artists), [KITS AI](https://www.kits.ai) (artist partnerships)
- **Enterprise Indemnification:** Getty ($10-50/image), Adobe Creative Cloud
- **Research/Personal Use Only:** Many open-source models have non-commercial restrictions

### Data Privacy

- **On-Device Processing:** [Apple Intelligence](https://www.apple.com/apple-intelligence) (Image Playground, Genmoji)
- **Cloud Processing:** Most tools (data uploaded to servers)
- **Self-Hosted Options:** [Stable Diffusion](https://stability.ai/stable-diffusion), Stable Video Diffusion, [Coqui TTS](https://github.com/coqui-ai/TTS)
- **Enterprise Privacy:** [Synthesia](https://www.synthesia.io), [HeyGen](https://www.heygen.com) offer SOC 2 compliance

### Ethical Considerations

- **Deepfake Risks:** Use avatar/voice tools ([HeyGen](https://www.heygen.com), ElevenLabs) responsibly
- **Artist Consent:** [KITS AI](https://www.kits.ai) and [Uberduck](https://uberduck.ai) partner with artists for voice rights
- **Misinformation:** Label AI-generated content when publishing
- **Bias Awareness:** Test outputs across diverse demographics

### Quality vs. Speed Trade-offs

- **High Quality (Slower):** [Midjourney](https://www.midjourney.com), Sora, [AIVA](https://www.aiva.ai), [Tortoise-TTS](https://github.com/neonbjb/tortoise-tts)
- **Balanced:** FLUX.2, [Runway Gen-4.5](https://runwayml.com), [Udio](https://www.udio.com), [ElevenLabs](https://elevenlabs.io)
- **Fast (Lower Detail):** [Google ImageFX](https://labs.google/fx/imagefx), [Pika 2.0](https://pika.art), Suno basic, [revid.ai](https://www.revid.ai)
- **Real-Time:** [Krea.ai](https://www.krea.ai) Canvas, [Cartesia.ai](https://cartesia.ai) (voice), [Freepik Pikaso](https://pikaso.freepik.com)

### Hardware Requirements (Self-Hosted)

- **Minimum for SD/SDXL:** RTX 3060 (12GB VRAM) or equivalent
- **Recommended for SD3/FLUX:** RTX 4080 (16GB VRAM) or higher
- **Video Models (SVD):** RTX 4090 (24GB VRAM) recommended
- **Audio Models:** Most run on CPU; GPU speeds up processing

---

## 🔮 FUTURE TRENDS (2026 OUTLOOK)

### Q1 2026 Already Delivering

1. **Unified Audio-Video Generation:** Models like Seedance 2.0 and Kling 3.0 generate video + audio simultaneously—no more post-production sync
2. **Speed+Quality Convergence:** Nano Banana 2 achieves Pro quality at Flash speeds (2-3x faster)
3. **Multimodal Input Expansion:** Quad-modal (text+image+video+audio) becomes new standard
4. **Consumer Music Democratization:** Lyria 3 in Gemini puts music creation in 750M+ users' hands
5. **Open-Source Catching Up:** GLM-Image challenges proprietary text-rendering dominance

### Predicted Developments (2026)

1. **Multi-Modal Integration:** Expect unified platforms (text→image→video→3D in one prompt)
2. **Real-Time Generation:** Sub-second image/video generation becoming standard
3. **Personalization:** Custom models trained on individual style/brand in minutes
4. **Extended Context:** Video models handling 5-10 minute coherent narratives
5. **Interactive Editing:** Natural language editing ("make the sky darker") across all media
6. **Edge AI:** More on-device generation (privacy + speed) following Apple's lead
7. **Ethical Standards:** Industry-wide watermarking and provenance tracking
8. **DAW/IDE Integration:** Native plugins for professional creative software
9. **Agentic Creation:** Claude Code and similar agents controlling video pipelines ([Genra AI](https://genra.ai))

### Emerging Categories to Watch

- **AI Cinematography:** Automated multi-camera setups and shot composition
- **Voice Acting:** Full performance capture (emotion, timing, accent) from text
- **Procedural Music:** Context-aware soundtracks adapting to content in real-time
- **4D Generation:** Time-evolving 3D objects and environments
- **Neural Rendering:** Real-time photorealistic rendering for games/VR

---

## 📚 LEARNING RESOURCES

### Beginner-Friendly Tutorials

- **[Midjourney](https://www.midjourney.com):** Official Discord #tutorials channel
- **[Stable Diffusion](https://stability.ai/stable-diffusion):** [AUTOMATIC1111](https://github.com/AUTOMATIC1111/stable-diffusion-webui) wiki, [Civitai](https://civitai.com) model guides
- **[Runway](https://runwayml.com):** In-app academy with video walkthroughs
- **[ElevenLabs](https://elevenlabs.io):** Documentation with voice design tips

### Advanced Techniques

- **[ComfyUI](https://github.com/comfyanonymous/ComfyUI) Workflows:** GitHub examples for complex SD pipelines
- **[ControlNet](https://github.com/lllyasviel/ControlNet) Mastery:** Stability AI's research papers + community examples
- **Prompt Engineering:** OpenAI's best practices guide (applies broadly)
- **Music Production:** [Udio](https://www.udio.com)'s stem export + DAW integration tutorials

### Community Hubs

- **Reddit:** r/StableDiffusion, r/ArtificialIntelligence, r/MediaSynthesis
- **Discord:** [Midjourney](https://www.midjourney.com), [Stable Diffusion](https://stability.ai/stable-diffusion), [Runway](https://runwayml.com) communities
- **YouTube:** Olivio Sarikas (SD), AI Andy (multi-tool), Matt Wolfe (news)
- **Twitter/X:** Follow @StabilityAI, @OpenAI, @runwayml for updates

---

## 🛠️ TOOL SELECTION DECISION TREE

```
START: What type of media are you creating?
├─ IMAGE
│ ├─ Need absolute copyright safety? → Getty Generative AI, Adobe Firefly
│ ├─ Want artistic/cinematic style? → Midjourney, Monica AI
│ ├─ Need text-in-image (logos)? → Ideogram 4.0
│ ├─ Want free experimentation? → Google ImageFX, Stable Diffusion
│ └─ Need photorealism fast? → FLUX.2 [pro], Gemini 3.1 Flash Image
│
├─ VIDEO
│ ├─ Creating business/training videos? → Synthesia, HeyGen, Capsule
│ ├─ Need animated characters? → Vyond, Steve.AI
│ ├─ Making social media shorts? → revid.ai, Pika 2.0, OpusClip
│ ├─ Planning film narrative? → LTX Studio, Runway Aleph, Flow
│ └─ Want cinematic quality (if access)? → Sora, Veo 3
│
├─ AUDIO (MUSIC)
│ ├─ Need full songs with vocals? → Suno (fast), Udio (quality)
│ ├─ Want stems for production? → Udio, Stable Audio
│ ├─ Creating film score? → AIVA, Beatoven.ai
│ └─ Need sound effects? → Stable Audio, Mubert
│
├─ AUDIO (VOICE)
│ ├─ Cloning speaking voice? → ElevenLabs, Play.ht
│ ├─ Need singing voice? → KITS AI, ACE Studio
│ ├─ Want DAW integration? → ACE Studio, Synthesizer V
│ ├─ Enterprise/multilingual? → Murf.ai, Google Cloud TTS
│ └─ Celebrity/character voices? → Uberduck, Voxdazz
│
└─ 3D/SPATIAL
├─ Converting 2D to 3D? → Kaedim, CSM.ai
├─ Creating from scratch? → Spline AI, Luma AI
├─ Need game assets? → Leonardo.Ai (textures), Masterpiece Studio
└─ Want NeRF capture? → Luma AI
```

---

## 🎓 GLOSSARY OF TERMS

**[ControlNet](https://github.com/lllyasviel/ControlNet)** – Extension for [Stable Diffusion](https://stability.ai/stable-diffusion) enabling pose, depth, and edge guidance
**DAW (Digital Audio Workstation)** – Professional audio editing software (e.g., Logic, Ableton)
**Diffusion Model** – AI architecture using iterative denoising to generate images/video
**Inpainting** – Filling or editing specific regions of an image/video
**Latent Space** – Compressed representation where AI models operate
**LoRA (Low-Rank Adaptation)** – Lightweight fine-tuning method for custom styles
**NeRF (Neural Radiance Fields)** – 3D scene reconstruction from 2D images
**Outpainting** – Extending images beyond original boundaries
**Stem Separation** – Isolating individual instruments/vocals from mixed audio
**T2I (Text-to-Image)** – Generating images from text descriptions
**T2V (Text-to-Video)** – Generating video from text descriptions
**TTS (Text-to-Speech)** – Converting written text to spoken audio
**VST (Virtual Studio Technology)** – Plugin format for audio software integration

---

## 📚 PRIMARY SOURCES USED FOR THE JUNE 2026 REFRESH

### Cross-platform / model vendors

- OpenAI Sora discontinuation: https://help.openai.com/en/articles/20001152-what-to-know-about-the-sora-discontinuation
- OpenAI image API docs: https://platform.openai.com/docs/guides/image-generation
- Midjourney updates: https://updates.midjourney.com/
- Microsoft MAI-Image-2.5: https://microsoft.ai/news/introducing-mai-image-2-5/
- Ideogram 4.0: https://ideogram.ai/blog/ideogram-4.0/
- Stability AI Stable Audio 3.0: https://stability.ai/news-updates/meet-stable-audio-3-the-model-family-built-for-artistic-experimentation-with-open-weight-models
- Runway API changelog: https://docs.dev.runwayml.com/api-details/api_changelog/
- Runway product changelog: https://runwayml.com/changelog
- Luma news: https://lumalabs.ai/news
- Kling VIDEO 3.0: https://app.klingai.com/global/blog/kling-video-3-0-ai-director-features-guide
- ByteDance Seedance 2.0: https://seed.bytedance.com/en/blog/official-launch-of-seedance-2-0
- ByteDance Seedream 5.0 Lite: https://seed.bytedance.com/en/seedream5_0_lite
- Alibaba Model Studio video docs: https://www.alibabacloud.com/help/en/model-studio/wan-video-generation-api-reference
- ElevenLabs Music: https://elevenlabs.io/music
- Suno: https://suno.com/

### Google media stack

- Google I/O 2026 announcements: https://blog.google/innovation-and-ai/technology/ai/google-io-2026-all-our-announcements/
- Gemini API release notes: https://ai.google.dev/gemini-api/docs/changelog
- Gemini API deprecations: https://ai.google.dev/gemini-api/docs/deprecations
- Veo 3.1 docs: https://ai.google.dev/gemini-api/docs/video
- Flow: https://labs.google/flow/about

## 📋 FINAL RECOMMENDATIONS BY BUDGET

### $0/month (Free Tools Only)

- **Image:** [Google ImageFX](https://labs.google/fx/imagefx) (unlimited), [Google Nano Banana 2](https://blog.google/innovation-and-ai/technology/ai/nano-banana-2/) (free via Gemini), [Meta Imagine](https://imagine.meta.com), [Stable Diffusion](https://stability.ai/stable-diffusion) (self-hosted), [GenType](https://labs.google/gentype) (typography)
- **Video:** [Google Vids](https://workspace.google.com/products/vids/) (free for Gmail), Stable Video Diffusion, [PixVerse](https://pixverse.ai) (free tier), [Hailuo 2.3 Fast](https://hailuoai.video) (free tier)
- **Audio:** Suno (50 credits/day free), [Google MusicFX](https://labs.google/fx/tools/music-fx) (limited regions), [Google MusicFX DJ](https://labs.google/fx/tools/music-fx-dj), [Coqui TTS](https://github.com/coqui-ai/TTS), [Stable Audio](https://www.stableaudio.com) (open model)
- **3D:** [TripoSR](https://github.com/VAST-AI/TripoSR), [OpenLRM](https://github.com/3DTopia/OpenLRM), [Genie 3](https://deepmind.google/models/genie/) (beta)
- **Voice:** [Google SynthID](https://deepmind.google/technologies/synthid/) (detection free), [Fish Audio](https://fish.audio) (free tier)

### $0-30/month (Prosumer/Creator)

- **Image:** [Ideogram 4.0](https://ideogram.ai/models/4.0/) ($7), [Leonardo.Ai](https://leonardo.ai) ($10-24), [Monica AI](https://monica.im) ($9), [Gemini Advanced](https://gemini.google.com) ($20 - includes Nano Banana Pro)
- **Video:** [Vyond](https://www.vyond.com) ($25 Essential), [Runway](https://runwayml.com) ($15 Standard), [revid.ai](https://www.revid.ai) ($19), [Kling 3.0](https://www.klingai.com) ($7-10), [Pika 2.0](https://pika.art) ($8-20)
- **Audio:** Suno Pro ($10), [KITS AI](https://www.kits.ai) ($9.99), [ElevenLabs](https://elevenlabs.io) ($5-22), [Murf.ai](https://murf.ai) ($29 Starter)
- **All-in-One:** [ChatGPT Plus](https://chat.openai.com) ($20 for DALL·E 3), [Google AI Plus](https://ai.google.dev/pricing) ($7.99 - includes Lyria 3, Nano Banana Pro)
- **Enhancement:** [Topaz Photo AI](https://www.topazlabs.com/photo-ai) ($199 one-time)

### $30-100/month (Professional)

- **Image:** [Midjourney](https://www.midjourney.com) ($30-60 Pro), Adobe CC ($20-55), [Krea.ai](https://www.krea.ai) ($30 Pro)
- **Video:** [Synthesia](https://www.synthesia.io) ($29-89), [LTX Studio](https://ltxstudio.com) ($29 Creator), [Capsule](https://capsule.video) ($49 Pro), [HeyGen](https://www.heygen.com) ($29-89), [Digen RM3.0](https://digen.ai) (TBD)
- **Audio:** [AIVA](https://www.aiva.ai) ($50 Pro), [Murf.ai](https://murf.ai) ($29-99), [ACE Studio](https://acestudio.ai) ($99 base + voices), [Udio](https://www.udio.com) (subscription coming)
- **Voice:** [Play.ht](https://play.ht) ($39-99), [Resemble AI](https://www.resemble.ai) (custom pricing)
- **Enhancement:** Topaz Video AI ($299 one-time), [Landr](https://www.landr.com) ($9-20/month)

### $100-300/month (Business/Team)

- **Image:** Adobe CC Teams ($80-120), [Midjourney](https://www.midjourney.com) ($120 Mega), [Getty API](https://developer.gettyimages.com/enterprise/generative-ai) (per-use pricing)
- **Video:** [Synthesia](https://www.synthesia.io) ($89-250 Team), [HeyGen](https://www.heygen.com) Teams ($89-299), [Runway](https://runwayml.com) ($95 Unlimited), [Flow for Workspace](https://www.webpronews.com/google-launches-flow-ai-powered-video-creation-for-workspace/) (Workspace pricing)
- **Audio:** [AIVA](https://www.aiva.ai) ($110 Enterprise), [Murf.ai](https://murf.ai) ($119-239 Enterprise), [WellSaid Labs](https://wellsaidlabs.com) (custom)
- **Platform:** [Google AI Pro](https://ai.google.dev/pricing) ($19.99 - includes Flow, Veo 3, Whisk), [Vertex AI](https://cloud.google.com/vertex-ai) (usage-based)

### $300+/month (Enterprise)

- **Image:** [Getty Generative AI](https://www.gettyimages.com/company/generative-ai) (enterprise licensing), Adobe Enterprise (custom), [Shutterstock AI](https://www.shutterstock.com/generate) Enterprise
- **Video:** [Synthesia](https://www.synthesia.io) Enterprise (custom), [HeyGen](https://www.heygen.com) Enterprise, [Google AI Ultra](https://blog.google/products/google-one/google-ai-ultra) ($199.99 - unlimited Flow, all Gemini 3 models)
- **Audio:** [WellSaid Labs](https://wellsaidlabs.com) (custom enterprise), [ElevenLabs](https://elevenlabs.io) Enterprise, Enterprise TTS APIs (Google/AWS/Azure)
- **Platform:** [Google AI Ultra](https://blog.google/products/google-one/google-ai-ultra) ($199.99 - includes Project Mariner, Jules, unlimited Veo 3.1), Alibaba Cloud (Qwen ecosystem), [Vertex AI](https://cloud.google.com/vertex-ai) (enterprise scale)

---

## 🌟 TOP PICKS BY CATEGORY (Editor's Choice)

### Best Overall Platform

**🥇 [Runway](https://runwayml.com)** – Most comprehensive creative suite with Gen-4.5, [Aleph 2.0](https://runwayml.com/product/aleph-2), and VFX tools
**🥈 [Google Gemini Ecosystem](https://gemini.google.com)** – Best value with 12+ integrated tools (ImageFX, Veo, Lyria, Flow)

### Best for Beginners

**🥇 [ChatGPT Plus](https://chat.openai.com)** – Easiest entry point with [DALL·E 3](https://openai.com/index/dall-e-3) and conversational interface
**🥈 [Google AI Plus](https://ai.google.dev/pricing)** ($7.99) – Best value with Lyria 3, Nano Banana Pro, Veo 3 Fast

### Best Open-Source Ecosystem

**🥇 [Stable Diffusion](https://stability.ai/stable-diffusion)** – Unmatched customization and community support
**🥈 [GLM-Image](https://z.ai/blog/glm-image)** – Best open-source text rendering (Apache 2.0)

### Best Commercial Safety

**🥇 Getty Generative AI** – Legal indemnification for enterprise use
**🥈 [Adobe Firefly](https://www.adobe.com/products/firefly.html)** – Commercially safe training with Creative Cloud integration

### Best Value for Money

**🥇 [Google AI Plus](https://ai.google.dev/pricing)** ($7.99) – Includes Lyria 3, Nano Banana Pro, Veo 3 Fast
**🥈 [Leonardo.Ai](https://leonardo.ai)** – Generous free tier + powerful paid features at $10-24/month

### Best for Social Media

**🥇 [revid.ai](https://www.revid.ai)** – Template-based repurposing optimized for TikTok/Reels
**🥈 [Dream Screen](https://support.google.com/youtube/answer/14151606)** – AI backgrounds for YouTube Shorts (free)

### Best for Music Production

**🥇 [Udio](https://www.udio.com)** – High-fidelity output with stem exports for professional workflows
**🥈 [Google ProducerAI](https://blog.google/innovation-and-ai/models-and-research/google-labs/producerai/)** – Professional controls with Lyria 3 (free via Labs)

### Best Voice Cloning

**🥇 [ElevenLabs](https://elevenlabs.io)** – Industry-leading naturalness and emotional range (9.5/10)
**🥈 [Fish Audio](https://fish.audio)** – Best for Asian languages with superior accent retention

### Best for Animation

**🥇 [Vyond](https://www.vyond.com)** – Consistent character animation with intuitive controls
**🥈 [Hailuo 2.3](https://hailuoai.video)** – Best motion quality with emotional character animation

### Best for Filmmakers

**🥇 [LTX Studio](https://ltxstudio.com)** – Scene-by-scene narrative control for pre-production
**🥈 [Google Flow](https://www.theverge.com/tech/2025/5/21/24160320/google-flow-ai-video-veo-imagen)** – Cinematic AI filmmaking with Veo 3.1 integration

### Most Innovative (verified through June 24, 2026)

**🥇 Google Gemini Omni Flash** – Mixed text/image/video/audio inputs with conversational video creation/editing
**🥈 Ideogram 4.0** – Open-weight frontier image model with production-design controls
**🥉 Stable Audio 3.0** – Open-weight, licensed-data audio family spanning on-device to enterprise use

### Best Free / Open Options (verify quotas and licenses)

**🥇 Ideogram 4.0 weights** – Open-weight image model; hosting/licensing costs still apply
**🥈 Stable Audio 3.0 Small/Medium weights** – Open audio experimentation under applicable Stability licenses
**🥉 Stable Diffusion 3.5 ecosystem** – Mature local/self-hosted image tooling and community workflows

### Best Enterprise Platform

**🥇 [Google AI Ultra](https://blog.google/products/google-one/google-ai-ultra)** – Deep Research Max, unlimited Veo 3.1, and project-aware Notebooks
**🥈 [Adobe Firefly AI Assistant](https://www.adobe.com/products/firefly.html)** – Agentic workflow orchestration for creative teams

---

**Total Catalogue Size:** 198+ entries/references across major media-AI categories
**New in Q1-Q2 2026:** 48 tools (including 38 Google AI ecosystem tools)
**Last Updated:** June 24, 2026

_This is a broad discovery catalogue, not a permanent leaderboard. The June 24, 2026 audit rechecked high-risk launch/status/version claims against primary sources and explicitly downgraded unsupported claims. Always confirm current model IDs, licenses, pricing, age/region restrictions, and commercial-use terms before production use._

**📊 Coverage Statistics:**

- **Image Generation:** 48+ tools
- **Video Generation:** 43+ tools
- **Audio/Music:** 38+ tools
- **Voice/TTS:** 28+ tools
- **3D/Spatial:** 18+ tools
- **Multi-Modal Platforms:** 20+ tools
- **Enhancement Tools:** 10+ tools
- **AI Detection:** 1 tool (SynthID)

**🔗 Quick Access:**

- [Google Labs](https://labs.google) - 40+ free experimental tools
- [Gemini API](https://ai.google.dev) - Developer access to latest Gemini/Veo/Lyria models
- [Adobe Firefly](https://firefly.adobe.com) - Agentic creative suite
- [Midjourney](https://midjourney.com) - High-end artistic generation
- [Vertex AI](https://cloud.google.com/vertex-ai) - Enterprise platform

---

## Audit provenance

- Source repository snapshot reviewed: April 22, 2026 README
- Full-file line processing completed: June 24, 2026
- Review method: line inventory + targeted primary-source verification of volatile claims
- Editorial rule: absence of first-party confirmation is not proof that a product does not exist; such claims are marked unverified rather than asserted
