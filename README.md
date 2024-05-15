# Document Genie: Get instant insights from your Documents

This chatbot is built using the Retrieval-Augmented Generation (RAG) framework, leveraging Google's Generative AI model Gemini-PRO. It processes uploaded PDF documents by breaking them down into manageable chunks, creates a searchable vector store, and generates accurate answers to user queries. This advanced approach ensures high-quality, contextually relevant responses for an efficient and effective user experience.

## How It Works

Follow these simple steps to interact with the chatbot:

1. **Enter Your API Key**: You'll need a Google API key for the chatbot to access Google's Generative AI models. Obtain your API key [here](https://makersuite.google.com/app/apikey).

2. **Upload Your Documents**: The system accepts multiple PDF files at once, analyzing the content to provide comprehensive insights.

3. **Ask a Question**: After processing the documents, ask any question related to the content of your uploaded documents for a precise answer.

## Usage

### Prerequisites
- Python 3.6 or later
- Install the required libraries by running `pip install -r requirements.txt`

### Running the Chatbot
1. Clone this repository.
2. Navigate to the project directory.
3. Run `streamlit run your_file_name.py` to launch the chatbot interface.
4. Enter your Google API key when prompted.
5. Upload your PDF documents and click on "Submit & Process".
6. Ask your questions in the provided text input field.

## Contributing
Contributions are welcome! If you have any suggestions, improvements, or issues, please feel free to open an issue or submit a pull request.

## License
This project is licensed under the [MIT License](LICENSE).
