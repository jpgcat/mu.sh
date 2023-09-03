# mu.sh
**Music Shell (mu.sh) - Simplified Music Managing Bash Script (for Linux)**

A simple but functional bash script designed to manage your music properly using youtube-dl. mu.sh effectively acts as a youtube-dl config, handling how your music is downloaded, applying an easy to use naming convention, correct metadata tags, and art covers in one simple command.

## Installation

#### 1. Set your current working directory to ~/Music
`$ cd ~/Music`

#### 2. Clone the project
`$ git clone https://github.com/MetallyChallenged/mu.sh.git`

#### 3. Install the required packages
`$ pacman -S - < mu.sh/requirements`
or install using your respective package manager by checking what mu.sh requires in the requirements file.

## Usage

`$ mu.sh/download`
  + `url (URL)` - download music from a specified URL.
  + `list (FILE)` - download music from a list of predefined links in a file seperated by newlines.

`$ mu.sh/play`
  + `all (STRING (OPTIONAL))` - play all music or all music which includes your specified string in the name.
  + `shuffle (STRING (OPTIONAL))` - shuffle and play all music or all music which includes your specified string in the name.
  + `(STRING)` - play a single song specified by string.

## Files

A default mu.sh has 4 files upon installing, these files are;
+ download - the main script, this is where your music is downloaded and managed.
+ play - a play script, this is not needed by mu.sh and is simply an example cli for playing what you have downloaded using mpv.
+ playlist - the default playlist file, these are just songs from my own playlist, feel free to download an use this on your own computer if you somehow like the same music as i do.
+ requirements - the required packages mu.sh needs to run.
