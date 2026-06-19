# Deep Technical Guide: Lekhai Image Generation System

## How It Works

Lekhai image generation uses a **text-to-image diffusion pipeline**:

1. Prompt Input
2. Tokenization
3. Diffusion Model Processing
4. Latent Space Generation
5. Image Decoding
6. Output Rendering

---

## Prompt-to-Image Pipeline

Prompt → Encoder → Latent Diffusion → Decoder → Image Output

---

## Model Behavior

- Understands structured prompts
- Prioritizes subject clarity
- Uses attention weighting for style keywords
- Responds strongly to lighting and composition terms

---

## 🎯 Optimization Rules

- Use 8–25 word prompts
- Always include lighting
- Always include style
- Avoid conflicting keywords
