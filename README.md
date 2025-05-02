📝 LangChain-Powered Summarizer for YouTube & Web Pages
This project is a powerful and user-friendly Streamlit application designed to summarize content from YouTube videos and web pages using Groq-hosted large language models (LLMs) via the LangChain framework. It enables users to extract concise, high-quality summaries from long-form content by simply pasting a URL—no manual reading or time-consuming transcription required.

Whether you're researching a topic, skimming through lengthy video lectures, reading articles, or just trying to keep up with information overload, this app serves as a time-saving assistant by automatically pulling content, processing it, and generating a clean ~300-word summary. It’s especially useful for:

->Students trying to review YouTube lectures or educational websites

->Professionals who need to skim news, whitepapers, or tutorials quickly

->Content creators or researchers looking to understand key points before deep dives

Under the hood, the app uses LangChain document loaders to fetch and parse the raw text content. It identifies the source (YouTube or generic website) and routes it through the appropriate pipeline. It then utilizes Groq’s fast LLMs (like LLaMA3) to generate intelligent summaries, all structured through a custom prompt template. The app also uses a Groq API key input field to ensure personalized access to the backend model.

This tool showcases the integration of modern LLM infrastructure, clean UI with Streamlit, and modular document processing logic with LangChain—all wrapped in a fast, easy-to-use package for non-technical and technical users alike.
