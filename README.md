# Justice Walcott | Developer Portfolio

**Live site: [jwalcott02.github.io](https://jwalcott02.github.io)**

My personal portfolio: software engineering and applied AI projects, experience, and live GitHub activity. Built as a single, dependency-free page and hosted free on GitHub Pages.

## About me

Computer science student at Florida Atlantic University (B.A. expected December 2026, minors in Cybersecurity and Artificial Intelligence), starting an M.S. in Artificial Intelligence in January 2027. I build practical AI tools: retrieval-augmented chatbots, fine-tuned models, and LLM apps with real safeguards.

## What's on the site

- **About and principles:** how I approach building AI tools
- **Projects:** selected work with the stack and a result for each
- **Live GitHub activity:** repo count, stars, top repos, and language mix, pulled from the GitHub API each time the page loads
- **Experience and education:** Amazon, CodePath, FAU, and Broward College
- **Skills, currently learning, and FAQ**
- **Contact links**

## Featured projects

| Project | What it does | Stack |
| --- | --- | --- |
| [FAU CS Unofficial Guide](https://github.com/Jwalcott02/FAU-RAG) | Question-answering assistant for CS students, built on retrieval | Python, Gradio, ChromaDB |
| Conversational RAG Chatbot | Chatbot with session memory and source citations, deployed on a Google Cloud VM | LangChain, ChromaDB, Gemini, Chainlit |
| [FitFindr](https://github.com/Jwalcott02/ai201-project2-fitfindr-starter) | Multi-tool LLM agent with a planning loop that branches on tool output | Python, Groq, Gradio |
| [Provenance Guard](https://github.com/Jwalcott02/Provenance-Guard) | Content-safety API: classification, confidence scoring, transparency labels, rate limiting, and appeals | Flask, Groq, Flask-Limiter |
| [TakeMeter](https://github.com/Jwalcott02/ai201-project3-takemeter) | Fine-tuned DistilBERT classifier benchmarked against a zero-shot LLM (72.7% vs. 90.9% accuracy) | DistilBERT, Groq, Google Colab |

## How it's built

- One `index.html` file with inline HTML, CSS, and vanilla JavaScript. No framework, no build step.
- A canvas-based flowing-particle background that turns off for visitors who prefer reduced motion.
- Responsive layout that works on phones, tablets, and desktops.
- Live data from the public [GitHub REST API](https://docs.github.com/rest), with a graceful fallback if the API is unavailable.

## Run it locally

```bash
git clone https://github.com/Jwalcott02/Jwalcott02.github.io.git
cd Jwalcott02.github.io
# open index.html in your browser
```

No install needed. To serve it locally instead, run `python3 -m http.server` in the folder and visit `http://localhost:8000`.

## Updating the site

1. Edit `index.html`.
2. Commit and push to `main`.
3. GitHub Pages redeploys automatically within a minute or two.

## Contact

- Email: [justicewalcott@outlook.com](mailto:justicewalcott@outlook.com)
- LinkedIn: [justice-w-a673451b5](https://www.linkedin.com/in/justice-w-a673451b5/)
- GitHub: [@Jwalcott02](https://github.com/Jwalcott02)
