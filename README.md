# Mbot

This is a Discord bot built using Python, `discord.py`, `youtube-dl`, and `ffmpeg`. It allows users to play music in a voice channel, with commands to join, play, pause, resume, and disconnect from the voice channel.

## Prerequisites

Before you begin, ensure you have met the following requirements:

- You have a Discord account.
- You have created a Discord bot and obtained its token.
- You have Python installed on your machine.
- You have installed `ffmpeg` on your machine. You can download it from [here](https://ffmpeg.org/download.html).

## Installation

1. Clone the repository:
    ```sh
    git clone <repository_url>
    cd <repository_directory>
    ```

2. Install the required Python packages:
    ```sh
    pip install -r requirements.txt
    ```

3. Create a `.env` file in the root directory and add your Discord bot token:
    ```env
    TOKEN=YOUR_DISCORD_BOT_TOKEN
    ```

## Usage

1. Run the bot:
    ```sh
    python bot.py
    ```

2. Invite the bot to your server using the OAuth2 URL with the necessary permissions.

3. Use the following commands in your Discord server:

    - `?join`: Make the bot join your current voice channel.
    - `?disconnect`: Disconnect the bot from the voice channel.
    - `?play <YouTube URL>`: Play the audio from the provided YouTube URL.
    - `?pause`: Pause the currently playing audio.
    - `?resume`: Resume the paused audio.

## File Structure

- `bot.py`: The main script to run the bot.
- `music.py`: Contains the music-related commands and functionality.
- `responses.py`: Contains the response handling logic (not detailed in this README).
- `requirements.txt`: Lists the dependencies required for the bot.
- `.env`: File to store your Discord bot token (not included in the repository).

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request.

## Acknowledgements

- [discord.py](https://github.com/Rapptz/discord.py)
- [youtube-dl](https://github.com/ytdl-org/youtube-dl)
- [ffmpeg](https://ffmpeg.org/)

For any issues or questions, please open an issue on the GitHub repository.
