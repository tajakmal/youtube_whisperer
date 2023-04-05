YouTube Transcription Script
============================

This is a Python script that uses the OpenAI API and the PyTube library to transcribe the audio of a YouTube video.

Usage
-----

1. Install the required packages:

2. Set up environment variables:

- Create a new file called `.env` in the root directory of your project.
- Add the following line to the file to set the value of your API key:

  ```
  OPENAI_API_KEY=YOUR_API_KEY_HERE
  ```

  Replace `YOUR_API_KEY_HERE` with your actual API key.

3. Update the `youtube_url` variable in the script with the URL of the YouTube video you want to transcribe.

4. Run the script:

The script will download the audio of the YouTube video, transcribe it using the OpenAI API, and save the transcription as a text file in the current directory with the same name as the YouTube video title.

Limitations
-----------

- This script only works with YouTube videos that have clear and distinct audio.
- The quality of the transcription may vary depending on the quality of the audio and the accuracy of the OpenAI model.
- There are size limitations that still need to be worked out in order to handle larger file sizes.

License
-------

This script is released under the MIT License. See `LICENSE` for details.
