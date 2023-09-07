# vector-space-search-using-ChatGPT-embedding-
## README for Streamlit Chat Application

---

### Description

This repository contains a Streamlit-based web application for a chat interface, integrated with language processing capabilities from the `langchain` package. The application allows for processing of PDF documents, splitting text, and engaging in conversational contexts using the embedded models.

### Requirements

- Python 3.x
- Streamlit
- dotenv
- PyPDF2
- langchain (and its dependencies)
- An internet connection (for loading avatar images)

### How to Run

1. Ensure you have all the required libraries installed.
2. Clone the repository and navigate to the project directory.
3. Run the Streamlit app using:

```bash
streamlit run app.py
```

This will launch the web application in your default browser.

### File Structure

- `app.py`: The main Streamlit application script. Contains the logic for PDF processing, text splitting, and chat interface.
- `htmlTemplates.py`: Contains CSS styles and HTML templates for the chat interface, including templates for bot and user messages.

### Features

- **PDF Processing**: Upload and extract text from PDF documents.
- **Chat Interface**: Engage in a chat with the bot, powered by the `langchain` package. The chat interface is styled with custom CSS and showcases avatars for both the user and the bot.
- **Text Splitting**: The application can split large chunks of text for efficient processing.

### Contributions

Feel free to fork this repository and contribute. Pull requests, enhancements, and bug reports are welcome.

---

