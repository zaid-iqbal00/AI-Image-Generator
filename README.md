# AI-Image-Generator
# AI Image Generator using ComfyUI

This project demonstrates how to use ComfyUI to generate high-quality anime-style images using the `anythingv5nijimix_25BEST.safetensors` checkpoint.

## 🚀 Features

- Prompt-based image generation using ComfyUI
- Integrated LoRA model loading
- Negative prompt guidance
- Uses KSampler with Euler scheduler
- Ready-to-run `anime_girl_workflow.json` workflow

## 🧰 Technologies

- ComfyUI
- Python
- Torch (PyTorch)
- anything-v5-nijimix model
- CUDA (GPU-based inference)

## 📁 Folder Structure

AI-Image-Generator/
│
├── ComfyUI/                  ← Keep only if it contains useful code/assets
│
├── workflows/
│   └── anime_girl_workflow.json  ← Put the exported workflow here
│
├── images/
│   └── sample_output.png     ← (Optional) Include 1–2 output images
│
├── README.md                 ← We’ll create this now
│
└── .gitignore                ← Optional but recommended


## 💡 How to Use

1. Clone this repo.
2. Open ComfyUI and import the workflow from `workflows/anime_girl_workflow.json`.
3. Make sure the checkpoint `anythingv5nijimix_25BEST.safetensors` is in your `models/checkpoints/` directory.
4. Run the workflow to generate anime-style art.

## 🖼 Output Sample

![sample_output](images/sample_output.png)

## 🔗 Model Used

- [anythingv5nijimix_25BEST.safetensors](https://civitai.com/models/9409/anything-v5)

## 📜 License

MIT License. Feel free to use and modify.

---

Made with ❤️ using ComfyUI.
