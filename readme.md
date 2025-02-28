# RAG Application with Langchain

This project is a Retrieval-Augmented Generation (RAG) application built using Langchain. It features the ability to store conversation history and improve responses based on that history. Additionally, it allows users to upload PDFs and get responses in accordance with the content of the uploaded PDFs. The application uses Huggingface vector embeddings and is deployed using Streamlit.

## Features

- **Conversation History**: Stores conversation history to improve response accuracy.
- **PDF Upload**: Users can upload PDFs and get responses based on the content of the PDFs.
- **Huggingface Vector Embeddings**: Utilizes Huggingface vector embeddings for better response generation.
- **Streamlit Deployment**: The application is deployed using Streamlit for an interactive user interface.

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/your-repo-name.git
    ```
2. Navigate to the project directory:
    ```bash
    cd pdf_chatbot
    ```
3. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

## Usage

1. Run the application:
    ```bash
    streamlit run app.py
    ```
2. Open your web browser and go to `http://localhost:8501` to interact with the application.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any changes or improvements.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgements

- [Langchain](https://github.com/langchain/langchain)
- [Huggingface](https://huggingface.co/)
- [Streamlit](https://streamlit.io/)
