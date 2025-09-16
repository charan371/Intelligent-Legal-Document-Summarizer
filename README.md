# Intelligent-Legal-Document-Summarizer

Description:
This project is a legal case summarization and recommender agent. It's built as a Jupyter notebook that leverages a pre-trained T5-base model to generate concise summaries of legal case texts. The application also includes a feature that allows users to categorize the legal text by selecting a specific domain and subdomain, such as "Criminal Law & Procedure" or "Intellectual Property & Technology Law".

Features:
Text Summarization: Uses a transformer-based model to create summaries from long legal texts.

Legal Domain Categorization: Organizes legal subdomains within broader categories like "Corporate & Commercial Law" and "Environmental & Energy Law".

Interactive Interface: The tool is accessible via a user-friendly Gradio web interface, which can be shared via a public URL.

Requirements:
The following Python libraries are necessary to run the notebook:

transformers
gradio
tqdm

How to Use:
Open and run the Jupyter notebook in a compatible environment like Google Colab.

Wait for the models to load and for the Gradio interface to launch.

Once the public URL is generated, navigate to the link provided.

Paste your legal case text into the "Input Legal Case Text" box.

Optionally, select a "Domain" and "Subdomain" to categorize the text.

Click the submit button to generate the summary.
