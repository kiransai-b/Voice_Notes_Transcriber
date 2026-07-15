# Voice Notes Transcriber

Welcome to the Voice Notes Transcriber This plugin integrates seamlessly with your Obsidian, offering an advanced, interactive way to transcribe and generate notes from your audio files. My goal is to enhance your ability to capture and understand information from audio sources, transforming the way you interact with and understand your information.

## Features
- **Enhanced Audio Recorder**: Record audio files directly into an Obsidian note with added functionality to pause, resume, and restart recordings. 
- **Audio Transcription**: Transcribe audio files that are either spoken directly into Obsidian or imported into a note using advanced AI models.
- **Note Generation**: Generate detailed notes in markdown language from the transcribed audio.
- **Customizable Prompts**: Customize the prompt that will be sent to the AI model before adding your transcribed audio so you can get any kind of analysis, note structure format, or enhancements you want!
- **Built in Obsidian Support**: Use the customized prompt to request formats that are supported by obsidian, such as markdown and mermaid charts as you can see in the video.
- **Support for Multiple Audio Formats**: Supports mp3, mp4, mpeg, mpga, wav, webm audio formats.

## Installation
Getting started with the Smart Memos Plugin is easy. Follow these steps to install:

1. Download and install the Smart Memos Plugin from the Obsidian Community Plugins.
2. Configure the plugin settings with your OpenAI API Key and preferred AI model.

**Note** This plugin currently uses online openAI models to recieve and transcribe your voice memos.  Looking to add Local AI Models in the near future. OpenAI's retention policy retains text up to 30 days, but does not retain any audio data. 

**Another Note:** If you have the native record feature in Obsidian turned on, it must be turned off for audio to record using Smart Memos.

## Platforms

- Desktop
- Mobile

## Usage
Once installed, the Smart Memos Plugin provides an intuitive interface to transcribe your audio files and generate notes.  

- **Adding Audio**: To speak your memo directly into Obsidian, tap the microphone icon that displays "Record smart memo" or select `Record smart memo` from the command palette (`Ctrl + p` for Windows and `Cmd + p` for Mac) to open the smart memos popup that'll automatically start recording.  To import audio into a note, simply drag and drop an audio file into it.
- **Transcribing Audio**: To transcribe an audio file after it's been imported into a note, move your cursor right underneath the audio file and use the command `Smart transcribe` from the command palette. The plugin will transcribe the audio file and generate detailed notes. If you're speaking directly to Obsidian, you can select the "Smart Transcribe" button to transcribe what you've recorded.
- **Customizing the Prompt**: You can customize the prompt that will be sent to the AI model before adding your transcribed audio in the plugin settings.
- **Include Raw Transcript**: If you just want clean notes returned, you can remove the addition of the raw transcript at the end by toggling it off in the settings
- **Specify where audio files are recorded in your vault**: By default, audio recordings will be saved to your root vault folder.  If you want to store audio recordings in a specific folder, you can change it in the settings of this plugin. I.e if you want them to be saved in a 'Recordings' folder within your 'Resources' folder, you can set the settings value to Resources/Recordings.

