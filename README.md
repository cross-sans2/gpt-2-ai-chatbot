# GPT-2 Chatbot

This is a simple chatbot that uses a pre-trained GPT-2 language model from Hugging Face to generate responses to user prompts. The chatbot is implemented as a Flask web application and can be run locally on your machine.

## Installation

To install the necessary dependencies, run the following command:

```
pip install -r requirements.txt
```

This will install Flask and the Hugging Face Transformers library, which are required to run the chatbot.

## Usage

To start the chatbot, run the following command:

```
python app.py
```

This will start the Flask web server and make the chatbot available at `http://localhost:5000/chat`. 

On the chat page, you can enter a prompt and click "Send" to generate a response from the GPT-2 model. The response will be displayed on the screen, and you can continue the conversation by entering additional prompts.

## Customization

To customize the behavior of the chatbot, you can modify the `characters.json` file in the `data` directory. This file contains JSON-like structures for each character, which include personality traits, conversation topics, and response templates.

To add a new character, simply create a new JSON-like structure in the `characters.json` file and update the `SELECTED_CHARACTER` variable in the `app.py` file to point to the new character.

## Resources

- [Flask documentation](https://flask.palletsprojects.com/)
- [Hugging Face Transformers documentation](https://huggingface.co/transformers/)
- [GPT-2 model page on Hugging Face](https://huggingface.co/gpt2)

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.
