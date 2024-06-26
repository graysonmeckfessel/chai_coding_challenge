# Chatbot Interaction System

This project provides a command-line interface (CLI) for interacting with a chatbot, featuring persistent memory, a custom quit function, and selectable bot personalities. You can chat with a bot by yourself or have two bots talk to each other in the chatroom.

## Features

-   **Persistent Bot Memory**: Enhances conversation continuity by remembering previous interactions.
-   **Custom Quit Function** (not included in chatroom.py): Offers flexible entries to quit program and prevents accidental chat termination by requiring explicit user confirmation.
-   **Selectable Bot Personalities**: Allows users to choose the bot's personality for a customized chat experience.
-   **Chatroom**: Users can select two bots to engage in a conversation with each other about the subject of their choosing. (Bot exchanges will not exceed 70).

## Instructions

1.  Clone this project to your local machine: https://github.com/graysonmeckfessel/chai_coding_challenge
2.  Navigate to the project directory.
3.  Ensure you have Python installed on your system. This project requires only the `requests` library as an external dependency. Install it using `pip install requests`.
4.  To start a chat session, run one of the following commands from the appropriate project directory:
    -   `python classic_chatbot.py` for interacting with "Bot" (your friendly AI companion).
    -   `python choose_your_own_chatbot.py` to converse with a character of your choice (e.g., Oprah Winfrey, Nostradamus, the Moon).
    -   `python chatroom.py` to let two characters of your choice engage in discourse about whatever you desire. 
5.  Follow the on-screen prompts to interact with the chatbot.

# Acknowledgements

I would like to thank the wonderful people at Chai for allowing me to use their API, as well as for giving me the opportunity to demonstrate my curiosity and interest in AI. Thank you so much!