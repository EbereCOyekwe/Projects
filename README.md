# AI PDF Project

## Overview
The **AI PDF Project** is a powerful AI-driven tool designed to extract, analyze, and summarize information from PDF documents. Built using cutting-edge libraries like **LangChain**, **LlamaIndex**, and **OpenAI**, this project is ideal for automating document analysis, generating summaries, extracting structured data, and performing complex queries.

---

## Features
- **PDF Parsing**: Extract text and metadata from PDF documents.
- **Natural Language Queries**: Use AI to query PDFs as though you’re asking a person.
- **Summarization**: Generate concise summaries of long documents.
- **Data Extraction**: Extract structured information from tables, forms, or unstructured text.
- **Interactive Interface**: Serve the tool via a web-based interface for easy interaction.

---

## Technologies
- **Python**: Programming language for the core implementation.
- **LangChain**: Framework for building language model-driven applications.
- **LlamaIndex**: For building and querying document indices.
- **PyPDF2**: For reading and parsing PDF documents.
- **OpenAI GPT**: AI language model for processing and analyzing text.
- **Flask** (or Streamlit): To create an interactive web interface.

---

## Installation

### Prerequisites
- Python 3.8 or higher
- OpenAI API key

### Steps
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/ai-pdf-project.git
   cd ai-pdf-project
   ```

2. Create a virtual environment:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
   ```

3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

4. Set up your `.env` file with the following content:
   ```
   OPENAI_API_KEY=your-api-key-here
   ```

---

## Usage

### Running Locally
1. Process a PDF file:
   ```bash
   python main.py --file example.pdf
   ```

2. Launch the web interface:
   ```bash
   streamlit run app.py
   ```

3. Access the web app at `http://localhost:8501`.

---

## Example Queries
1. **Summarize the document**: "Can you summarize the attached PDF in 100 words?"
2. **Search for specific information**: "What are the key findings in the report?"
3. **Extract data**: "Can you extract the names and dates from this document?"

---

## Contributing
Contributions are welcome! Please follow these steps:
1. Fork the repository.
2. Create a feature branch (`git checkout -b feature-name`).
3. Commit your changes (`git commit -m "Add feature"`).
4. Push to the branch (`git push origin feature-name`).
5. Open a pull request.

---

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

## Acknowledgements
- [OpenAI](https://openai.com/) for their powerful language models.
- [LangChain](https://docs.langchain.com/) for enabling complex language model workflows.
- [LlamaIndex](https://gpt-index.readthedocs.io/) for document indexing and querying.

---
