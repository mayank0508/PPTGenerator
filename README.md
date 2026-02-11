# PPTGenerator
An automated tool that transforms a simple topic into a professional, visually engaging PowerPoint presentation in seconds. By leveraging Google Gemini 3 Flash for intelligent content structuring and the Pexels API for high-quality visual context, this project eliminates the "blank slide" problem for students, educators, and professionals.

✨ Key Features
Intelligent Content Generation: Uses Gemini 3 Flash to research and draft slide outlines, speaker notes, and concise bullet points.

Automated Image Sourcing: Dynamically generates search queries based on slide context to fetch relevant, royalty-free high-resolution images via the Pexels API.

Ready-to-Use Export: Outputs a fully formatted .pptx file compatible with Microsoft PowerPoint, Google Slides, and LibreOffice.

Optimized Performance: Built with the Flash model to ensure low-latency generation without sacrificing the quality of the narrative.

🛠️ Tech Stack
LLM: Google Gemini 3 Flash (Content & Logic)

Media: Pexels API (Stock Images)

Language: Python 3.10+

Libraries: python-pptx (PPT construction), google-generativeai (AI integration), requests (API handling)

📦 Installation & Setup
Clone the repository:

Bash
git clone https://github.com/yourusername/your-repo-name.git
cd your-repo-name
Install dependencies:

Bash
pip install -r requirements.txt
Configure API Keys: Create a .env file in the root directory and add your credentials:

Code snippet
GEMINI_API_KEY=your_gemini_api_key
PEXELS_API_KEY=your_pexels_api_key
🖥️ Usage
Run the main script and enter your topic when prompted:

Bash
python main.py --topic "The Future of Quantum Computing" --slides 7
🤝 Contributing
Contributions are welcome! Whether it's adding new slide templates, improving the prompt engineering, or supporting more image providers, feel free to open an issue or submit a PR.
