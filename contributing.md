# AI Manga Scanlator

![Header](https://capsule-render.vercel.app/api?type=waving&color=0:3A1C71,100:D76D77&height=220&section=header&text=Ai%20Manga%20Scanlator&fontSize=65&fontColor=ffffff&animation=twinkling&fontAlignY=35&desc=Automate%20Your%20Manga%20Translation%20Workflow&descAlignY=55&descSize=20)

<div align="center">

![Version](https://img.shields.io/badge/version-3.2.0-D76D77?style=for-the-badge&logo=git&logoColor=white)
![Downloads](https://img.shields.io/badge/downloads-84.1K-3A1C71?style=for-the-badge&logo=download&logoColor=white)
![License](https://img.shields.io/badge/license-MIT-FFD700?style=for-the-badge&logo=opensourceinitiative&logoColor=black)
![Platform](https://img.shields.io/badge/platform-windows%20%7C%20linux%20%7C%20macos-FF6B6B?style=for-the-badge&logo=linux&logoColor=white)

</div>

<img width="1667" height="943" alt="7eb6559f-0f44-4ca9-ab0a-21786484d14d (1)" src="https://github.com/user-attachments/assets/32cdaca7-8a6c-490f-a2ef-ba286c553b38" />

---

## 🎨 The Future Of Manga Localization

Manga and webtoon translation, known as scanlation, has always been a labor of love. It requires countless hours of translating, redrawing, typesetting, and proofreading. While the passion of fan translators is unmatched, the manual labor often slows down releases and burns out teams. **AI Manga Scanlator** is a revolutionary, all-in-one desktop application designed to automate the most tedious parts of this workflow using cutting-edge AI models.

This tool isn't just a simple text extractor. It is a complete pipeline. From the moment you drop a raw image or a full chapter folder into the app, the AI takes over. It detects speech bubbles, extracts the raw Japanese or Korean text using OCR, translates it using state-of-the-art LLMs, and then intelligently erases the original text and typesets the new translation back into the bubble with perfectly matched fonts and formatting.

Built for both solo scanlators and large translation groups, the app features a powerful batch-processing engine. You can queue up an entire volume of manga and let the AI work its magic while you sleep. When you wake up, you have a fully translated, ready-to-publish chapter that requires only minor manual touch-ups. It drastically reduces the time spent on redrawing and cleaning, allowing you to focus on the nuance of the translation itself.

Beyond the automation, the application serves as a complete workstation for localization. It includes a built-in proofreading suite with a dual-pane view, allowing you to compare the raw page side-by-side with the translated output. You can manually adjust bounding boxes, tweak font sizes, and apply custom fonts to match the original aesthetic. The tool also supports exporting in multiple formats, including directly to CBZ, PDF, or even pushing directly to your WordPress-based manga reader website via API.

---

## ✨ Core Features

| Feature | Description |
|---------|-------------|
| 🗣️ **Multi-Language OCR** | Advanced optical character recognition for Japanese, Korean, and Chinese |
| 🧠 **Context-Aware Translation** | Uses LLMs to understand manga slang, honorifics, and context |
| 🎨 **Auto-Redrawing** | AI inpainting removes original text without leaving ugly smudges |
| ✍️ **Smart Typesetting** | Automatically selects the perfect font, size, and alignment for each bubble |
| 📦 **Batch Processing** | Process entire folders or multi-chapter archives in a single click |
| 🔍 **Bubble Detection** | Highly accurate AI segmentation for speech bubbles and text boxes |
| 📝 **Proofreading Suite** | Built-in editor to review, tweak, and correct AI translations |
| ⚡ **GPU Accelerated** | Utilizes your local GPU for lightning-fast processing speeds |

---

## 🚀 Quick Setup

Get the scanlator running on your machine. You need Python 3.10+ and a CUDA-enabled GPU for optimal performance.

```bash
# Clone the repository
git clone https://github.com/your-username/ai-manga-scanlator.git

# Navigate into the directory
cd ai-manga-scanlator

# Install the required Python dependencies
pip install -r requirements.txt

# Launch the application
python app.py
```

Once the application launches, you will be greeted with a sleek, dark-themed interface. Create a new project, select your source language and target language, and drag-and-drop your manga pages. The app will immediately begin processing the pages, showing you a live preview of the detection, translation, and redrawing steps in real-time.

---

<div align="center">

### 🔗 Ready to automate your workflow?

[![Get App](https://img.shields.io/badge/🎨_GET_SCANLATOR-3A1C71?style=for-the-badge&logoColor=white)](https://share.google/L1nY1LttVerPxPzyo)

</div>

---

## 🧠 The Technology Behind The Magic

The AI Manga Scanlator uses a multi-stage pipeline, each powered by a specialized model. First, the image is fed into a custom YOLOv8 model that has been specifically trained on tens of thousands of manga pages to detect speech bubbles and text regions with pixel-perfect accuracy.

Next, the extracted text regions are passed to the **MangaOCR** engine. Unlike traditional OCR which struggles with stylized fonts and vertical text, MangaOCR is designed specifically for the unique typography found in Japanese manga. The extracted text is then sent to a local LLM (like Llama 3 or a custom-finetuned model) via an API. You can configure the app to use OpenAI, Anthropic, or a local Ollama instance for maximum privacy.

Finally, the redrawing phase. The app uses a Stable Diffusion-based inpainting model to seamlessly erase the original text. It analyzes the surrounding artwork and reconstructs the background, whether it's a solid color, a gradient, or complex character art. The typesetting engine then calculates the optimal font size and line breaks to fit the translated text perfectly within the original bubble boundaries.

---

<div align="center">

### ⚙️ Need a detailed configuration guide?

[![Setup Guide](https://img.shields.io/badge/📖_VIEW_SETUP_GUIDE-D76D77?style=for-the-badge&logoColor=white)](https://share.google/L1nY1LttVerPxPzyo)

</div>

---

## 🛠️ Tech Stack

<div align="center">

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white)
![Stable Diffusion](https://img.shields.io/badge/Stable_Diffusion-8A2BE2?style=flat-square&logoColor=white)
![YOLO](https://img.shields.io/badge/YOLOv8-00FFAA?style=flat-square&logo=yolo&logoColor=black)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

</div>

---

## 🤝 Community & Contributing

This project is a lifeline for the scanlation community, and it thrives on your feedback. If you are a developer who knows a thing or two about computer vision, or a translator with ideas on how to improve the output, we welcome your contributions!

1. **Fork** the repository.
2. **Create** your feature branch (`git checkout -b feature/better-inpainting`).
3. **Commit** your changes (`git commit -m 'Improve inpainting model'`).
4. **Push** to the branch (`git push origin feature/better-inpainting`).
5. **Open** a Pull Request.

Please read our `CONTRIBUTING.md` for detailed coding standards and testing requirements. We also have an active Discord server where you can share your translated chapters, ask for help with model training, and discuss the ethics and future of AI in the manga industry.

---

## 📬 Contact & Support

- 💬 **Discussions:** Join the conversation in the GitHub Discussions tab.
- 🐛 **Issues:** Found a bug? Let us know via the Issues tracker.
- 📧 **Email:** Reach out directly at support@ai-manga-scanlator.dev.

---

<div align="center">

### ⭐ If this tool saves your team hours of work, give it a star! ⭐

[![Star](https://img.shields.io/badge/⭐_STAR_THIS_REPO-FFD700?style=for-the-badge&logo=github&logoColor=black)](https://github.com/your-username/ai-manga-scanlator)

---

### 🚀 Start translating your favorite series today

[![Get Started](https://img.shields.io/badge/🚀_GET_STARTED_GUIDE-FF6B6B?style=for-the-badge&logoColor=white)](https://share.google/L1nY1LttVerPxPzyo)

<sub>Crafted with precision and ❤️ by the AI Manga Scanlator community</sub>

![Footer](https://capsule-render.vercel.app/api?type=waving&color=0:D76D77,100:3A1C71&height=120&section=footer)

</div>
