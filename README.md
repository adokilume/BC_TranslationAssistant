# Bondage College Translation Assistant

Unofficial translation tool for the game [Bondage College by Ben987](https://github.com/Ben987/Bondage-College).

## Usage

1. Fork [Ben987/Bondage-College](https://github.com/Ben987/Bondage-College), then clone or download it to your local machine.
2. In the folder you downloaded the game in, create a copy of any `_EN.csv` file(s) you wish to translate and rename them to change `EN` to your language's two-letter code.
3. [Follow this link to use the Tool online.](https://adokilume.github.io/BC_TranslationAssistant/BC_TranslationAssistant.html) As an alternative, you can download the `BC_TranslationAssistant.html` file and open it in any modern web browser.
4. Click the "Open File" dialog in the upper left corner and navigate to one of the CSV copies you've created to open it.
5. To save your changes, hit "Save". The edited version of your file will be saved to your Browser's default download location (unless you configured your browser to ask you where to download files to). You will need to overwrite the old file with the new version.

### Things to keep in mind

* **Do not edit the file with another program while it's still open in this tool.** The Translation Assistant does not keep track of changes to your file from other sources, so any changes you made externally will be overwritten when saving.
* **Make frequent backups.** While I haven't personally encountered any major issues while testing, I can't guarantee that this tool won't mess anything up when you edit and save a file. Always make sure the newly generated file works properly before overwriting the previous one, and please don't make me responsible if you lose part of your work.

## Features

* View the game's CSV files in a table specifically designed for the purpose of translating / editing the game
  * Syntax higlighting for line breaks, other special characters and variables
  * Prevents accidental editing of non-text content
* Live text preview that updates as you type, to show you exactly what your text is going to look like in the game (useful for finding the right place for line breaks and keeping the length limits)
  * Option to set custom variable values (such as the player's name) for testing in the preview
* Lines get highlighted if they're too long for the game's text boxes
* Takes care of proper formatting and character encoding, allowing you to just focus on the text

### Missing features (might be added eventually)

* Support for Bondage Club files (only Bondage College is supported at the moment)
* "Developer Mode", allowing for changes in all columns as well as adding/removing lines
* A few more things to improve usability and usefulness

----------

Bug reports, suggestions, and general feedback welcome!

Tested in Firefox 65.0.2
