# Cripping-LLM
documentation of the chatbot development
# LM Studio + Qwen3 4B Instruct (2507) — Quick Start

Follow these steps to install **LM Studio**, download the **Qwen3 4B Instruct (2507)** model, and enable **Developer Mode**.

---

## Prerequisites
- A computer running **Windows/macOS/Linux** with an internet connection
- ~6–8 GB free disk space (installer + model)

---

## 1) Download and Install LM Studio
1. Go to **[lmstudio.ai](http://lmstudio.ai)**.
2. Download the **LM Studio Installer** for your operating system.
3. Run the installer and follow on-screen prompts to complete installation.

> Tip: After installation, launch **LM Studio** from your Applications/Programs menu.

---

## 2) Download the Qwen3 4B Instruct (2507) Model
1. Open this model page in your browser:  
   **<https://lmstudio.ai/models/qwen/qwen3-4b-2507>**
2. In **LM Studio**, use the **Models** or **Explore** tab and search for:  
   `Qwen3 4B Instruct 2507`
3. Click **Download** (or **Add** → **Download**) and wait for the model to finish downloading.

> Note: Model names are case-sensitive; confirm the exact variant **“Qwen3 4B Instruct (2507)”**.

---

## 3) Enable Developer Mode
1. Open **LM Studio**.
2. Go to **Settings** (gear icon ⚙️ in the sidebar or top-right menu).
3. Find **Developer Mode** and toggle it **On**.

> Why enable Developer Mode? It exposes advanced options useful for local API usage, debugging, and fine-grained configuration.
>![LM Studio Settings panel: Server Port 1234; CORS enabled; Permitir Conexiones de Red enabled; Just-in-Time Model Loading disabled.](assets/screenshot.png "LM Studio Settings with CORS enabled")



---

## 4) Verify the Setup (Optional)
- In LM Studio, open the **Chat** tab.
- Select the **Qwen3 4B Instruct (2507)** model from the model picker.
- Send a quick prompt like: `Hello!`  
  If you get a response, the model is correctly installed.

---

## Troubleshooting
- **Can’t find the model?** Double-check the exact name and version: *Qwen3 4B Instruct (2507)*.
- **Download stalls?** Pause/resume the download or restart LM Studio.
- **Low VRAM/Memory?** Try lowering context length or system settings in **Settings → Performance**.

---

## Attributions
- LM Studio: <http://lmstudio.ai>
- Qwen3 4B Instruct (2507) model page: <https://lmstudio.ai/models/qwen/qwen3-4b-2507>

---

*Keep this README in your repository root as `README.md` so teammates can follow the same setup.*
