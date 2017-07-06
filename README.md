# hello-world
place for ideas

test
errrr
BYE!
UGHHHHH

## audio_cutter

`usage: audio_cutter.py [-h] [-i IN_DIR] [-o OUT_DIR] timestamps_file`

Cuts .wav files at specified start and stop times. Requires a .txt file to
detail this information.

positional arguments:
- `timestamps_file`  Name of the text file with timestamps, e.g.
  "timestamps_sample.txt". Each line of the file lists an audio file
  name followed by start and stop times seperated by tabs,
  e.g. `audio_sample.wav HH:MM:SS HH:MM:SS`

optional arguments:
- `-h`, `--help`     show this help message and exit
- `-i IN_DIR`        Directory containing audio and timestamp files. Default is
  current working directory.
- `-o OUT_DIR`       Directory where cut .wav files will be exported. Default is
  current working directory.
