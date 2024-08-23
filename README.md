# Gemini-Pro Chatbot with Streamlit 

Open in Browser : https://gemini-pro-chatbot-free.streamlit.app/
This project is a web-based chatbot interface built using [Streamlit](https://streamlit.io/) and powered by Google's Gemini-Pro AI model. The application allows users to interact with the Gemini-Pro model in real-time, providing an engaging AI-driven conversation experience.

## Features

- **Real-time Chat Interface**: Engage with Gemini-Pro through a web-based chat interface.
- **Streamlit Integration**: Utilizes Streamlit for quick and easy deployment of web apps.
- **Environment Variables**: Securely manages API keys and sensitive data using `.env` files.

## Installation

### Prerequisites

- Python 3.7 or higher
- [pip](https://pip.pypa.io/en/stable/)
- A Google API key for accessing the Gemini-Pro model

### Setup

1. **Clone the repository**:
    ```bash
    git clone https://github.com/yourusername/gemini-pro-chatbot.git
    cd gemini-pro-chatbot
    ```

2. **Install the required Python packages**:
    ```bash
    pip install -r requirements.txt
    ```

3. **Create a `.env` file** in the project root directory and add your Google API key:
    ```bash
    GOOGLE_API_KEY=your-google-api-key
    ```

4. **Run the Streamlit app**:
    ```bash
    streamlit run app.py
    ```

## Usage

- Open the application in your web browser by navigating to `http://localhost:8501`.
- Enter your queries or prompts in the input field to start a conversation with Gemini-Pro.

## Project Structure

- `app.py`: The main application script that sets up the Streamlit interface and handles communication with the Gemini-Pro AI model.
- `requirements.txt`: Lists the Python packages required to run the application.
- `.env`: Contains environment variables like the Google API key (not included in the repository for security reasons).

## Contributing

Contributions are welcome! Please open an issue or submit a pull request on GitHub.

## License

This project is licensed under the MIT License. See the `LICENSE` file for more details.

## Acknowledgments

- [Streamlit](https://streamlit.io/) for providing a fantastic framework for building web apps.
- [Google Gemini-Pro](https://cloud.google.com/gemini-pro) for the powerful AI capabilities.
