# 📊 AI PowerPoint Generator 

An automated presentation engine that uses **Google Gemini 3 Flash** to write content and the **Pexels API** to source high-quality visuals. Turn a single prompt into a ready-to-present `.pptx` file in seconds.

---

## 🌟 Overview

Creating presentations is often a tedious balance of writing content and hunting for relevant imagery. This tool automates the entire workflow:
1.  **Content Synthesis:** Gemini 3 Flash generates a logical slide-by-slide outline, bullet points, and speaker notes.
2.  **Visual Matching:** The system extracts keywords from the content to query the Pexels API for contextually relevant background images.
3.  **File Assembly:** Everything is packaged into a clean, professional `.pptx` format.

## 🛠️ Built With

* **[Google Gemini 3 Flash](https://aistudio.google.com/)** - High-speed, multimodal LLM for content generation.
* **[Pexels API](https://www.pexels.com/api/)** - Sourcing royalty-free, high-definition photography.
* **[python-pptx](https://python-pptx.readthedocs.io/)** - The engine used to programmatically create and style slides.
* **Python 3.10+**

## 🚀 Getting Started

### Prerequisites
* A Google AI Studio API Key.
* A Pexels Developer API Key.

### Installation
1. Clone the repo:
   ```bash
   git clone [https://github.com/yourusername/repo-name.git](https://github.com/yourusername/repo-name.git)
   cd repo-name

   pip install -r requirements.txt

   GEMINI_API_KEY=your_key_here
   PEXELS_API_KEY=your_key_here

   python generator.py
