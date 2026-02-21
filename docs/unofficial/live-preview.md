# Unofficial Live Preview Behavior

This fork enables per-step preview updates during regular generation.

Environment override:
- `KRITA_AI_DIFFUSION_PREVIEW_METHOD=auto` (default)
- `KRITA_AI_DIFFUSION_PREVIEW_METHOD=taesd`
- `KRITA_AI_DIFFUSION_PREVIEW_METHOD=latent2rgb`

Notes:
- Live previews depend on ComfyUI-side preview image emission.
- Final image insertion remains full-resolution at completion.
