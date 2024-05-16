# Telegram Automated Bot

Welcome to the Telegram Automated Bot, a versatile tool designed to automate various tasks on Telegram. This bot leverages the power of ChatGPT to answer questions, schedule tasks, calculate BMI, and download YouTube videos via links.

## Table of Contents

- [Features](#features)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Technologies Used](#technologies-used)
- [Contributing](#contributing)
- [Contact](#contact)

## Features

- **ChatGPT Integration**: Answer any question using the power of OpenAI's ChatGPT.
- **Task Scheduling**: Schedule tasks and reminders.
- **BMI Calculation**: Calculate Body Mass Index (BMI) quickly and easily.
- **YouTube Video Download**: Download any YouTube video by providing its link.

## Getting Started

### Prerequisites

- A Telegram account
- Python 3.8 or higher
- A Telegram Bot API token (You can get this by creating a bot via the [BotFather](https://core.telegram.org/bots#botfather))

### Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/your-username/telegram-automated-bot.git
    cd telegram-automated-bot
    ```

2. Install the required dependencies:


3. Set up your environment variables (e.g., in a `.env` file):

    ```env
    TELEGRAM_API_TOKEN=your-telegram-api-token
    OPENAI_API_KEY=your-openai-api-key
    ```

4. Run the bot:

    ```bash
    python bot.py
    ```

## Usage

1. **Start the Bot**: Add the bot to your Telegram and start a chat with it.
2. **Ask Questions**: Use natural language to ask any question and get answers from ChatGPT.
3. **Schedule Tasks**: Use commands to schedule tasks (e.g., `/schedule Meeting at 3 PM`).
4. **Calculate BMI**: Use the command `/bmi height weight` to calculate your BMI.
5. **Download YouTube Videos**: Send a YouTube link to download the video.

## Technologies Used

- **Programming Language**: Python
- **APIs**: Telegram Bot API, OpenAI API, YouTube Data API
- **Libraries**: python-telegram-bot, requests, schedule, pytube

## Contributing

Contributions are welcome! To contribute to this project, please follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/your-feature-name`).
3. Make your changes.
4. Commit your changes (`git commit -m 'Add some feature'`).
5. Push to the branch (`git push origin feature/your-feature-name`).
6. Open a Pull Request.


## Contact

If you have any questions or feedback, please contact:

- **Email**: [arankallesahil@outlook.com]
- **GitHub**: [https://github.com/SahilArankalle]

Thank you for using the Telegram Automated Bot!
