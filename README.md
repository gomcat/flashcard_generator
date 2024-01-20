# AnkiConnect OpenAI Flashcard Generator

## Description
This project is a Python notebook that automates the creation of flashcards by leveraging OpenAI's GPT-3.5 model. It generates English-German flashcards, each containing a word or phrase, its translation, and an example sentence in both languages. These flashcards are then automatically inserted into a specified deck in Anki, a popular flashcard application, using AnkiConnect API.

## Features
- **Automatic Flashcard Creation**: Generates flashcards for a given list of English words/phrases.
- **Bilingual Support**: Each flashcard includes English and German translations along with example sentences.
- **Anki Integration**: Seamlessly adds generated flashcards to your Anki decks via AnkiConnect.

## Installation

### Prerequisites
- Python 3.x
- OpenAI API Key: You need to have an OpenAI account and access to the API key.
- Anki Application with AnkiConnect installed: This script assumes you have the Anki desktop application with the AnkiConnect add-on installed and running.

### Setup
1. **Clone the Repository**
   ```bash
   git clone [your-repository-link]
   cd ankiconnect_openai
2. **Install the required packages**:
   pip install openai requests
3. **Set up your OpenAI API Key**:
- Store your OpenAI API key in an environment variable named `OPENAI_API_KEY`.
- You can also modify the script to directly include your API key, but this is not recommended for security reasons.

4. **Ensure Anki & AnkiConnect are running**:
- Open your Anki desktop application.
- Confirm that the AnkiConnect add-on is properly installed and configured.

## Usage
1. **Start the Notebook**: Open the `ankiconnect_openai.ipynb` notebook in a Jupyter environment.
2. **Running the cells**: Execute the cells sequentially.
- The first cells will import necessary libraries and set up regular expressions and functions for flashcard creation.
- Ensure the constants for the Anki API URL and version are correct as per your AnkiConnect setup.

3. **Create Flashcards**:
- Use the `create_english_german_flashcard(word)` function to create a flashcard for a given word or phrase. The function communicates with the OpenAI API to generate a flashcard with an English word, its German translation, and example sentences in both languages.

## Contributing
Contributions to enhance the functionality or efficiency of this script are welcome. Please ensure to follow best practices for code contributions.

## License
Include a license here, if applicable.

