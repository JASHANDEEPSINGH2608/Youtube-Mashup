# Audio Mashup
This Python script allows users to download the audio from a set of YouTube videos based on a given keyword and compile trimmed sections of the audio into a single MP3 file.

# Features
Keyword-based search: Enter a keyword, and the script will fetch a specified number of YouTube videos related to that keyword.
Audio Download: The script extracts the audio from each video and stores it in a temporary location.
Trimming: The user can specify the duration to trim from each video’s audio file (from the beginning).
Compilation: All the trimmed audio files are merged into a single MP3 file.
Custom Output: The user can choose the name and location for the output file.

## Usage

```sh
python audio.py  "keyword" no.of videos trim_duration outputfile "output file location"
```

