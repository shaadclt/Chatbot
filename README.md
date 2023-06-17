# Chatbot

This is a simple chatbot implemented using Python and Streamlit. The chatbot uses a logistic regression classifier with TF-IDF vectorization to classify user input and generate appropriate responses. It can handle various intents such as greetings, goodbyes, thanks, and provides information on topics like budgets and credit scores.

## Installation

1. Clone the repository:
   ```shell
   git clone https://github.com/shaadclt/Chatbot.git
   ```

2. Change to the project directory:
   ```shell
   cd chatbot
   ```

3. Install the required dependencies:
   ```shell
   pip install -r requirements.txt
   ```

4. Run the chatbot:
   ```shell
   streamlit run app.py
   ```

## Usage

Once the chatbot is running, a web interface will open in your browser. Type a message in the input box and press Enter to start the conversation. The chatbot will respond based on the input and display the response in the chat area.

You can have a conversation with the chatbot by typing messages and pressing Enter. 
## Customization

If you want to customize the chatbot's behavior or add new intents, you can modify the `intents` list in the `app.py` file. Each intent consists of a tag, patterns (user input variations), and corresponding responses.

You can also modify the training data, add more features, or use more sophisticated models to enhance the chatbot's capabilities.

## Contributing

Contributions to this project are welcome. If you encounter any issues or have suggestions for improvement, please open an issue or submit a pull request on the GitHub repository.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more information.

## Acknowledgments

- The chatbot code is based on the [Streamlit](https://www.streamlit.io/) library and the scikit-learn machine learning library.
- The project uses the [Natural Language Toolkit (NLTK)](https://www.nltk.org/) for text processing and tokenization.

Feel free to customize and improve the README file based on your specific needs and additional information about the project.
