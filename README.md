# SpellCheck

## Spelling Checker Using Tkinter and TextBlob

This project is a simple spelling checker application built using Python's Tkinter for the GUI and TextBlob for spell-checking.

## Features
- Takes user input for spell-checking.
- Uses the TextBlob library to correct spelling mistakes.
- Displays the corrected text.
- User-friendly GUI with a simple and intuitive interface.

## Requirements
This project requires Python and the following libraries:

- **tkinter**: Built-in GUI library in Python.
- **textblob**: For natural language processing and spell checking. Install using:
  ```bash
  pip install textblob
  ```
- **nltk** (required for TextBlob): Install necessary corpora using:
  ```bash
  python -m textblob.download_corpora
  ```

## Installation
1. Clone this repository or download the script.
2. Install the required dependencies by running:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the script using:
   ```bash
   python spelling_checker.py
   ```

## Usage
1. Enter a word with potential spelling mistakes.
2. Click the **Check** button.
3. The corrected text will be displayed below the button.

## File Structure
- `spelling_checker.py`: Main script for the application.
- `requirements.txt`: List of required dependencies.
- `.gitignore`: Ensures unnecessary files are not pushed to the repository.

## Example Output
```bash
Input: "recieve"
Output: "Correct text is: receive"
```

## References
- [TextBlob Documentation](https://textblob.readthedocs.io/)
- [Tkinter Documentation](https://docs.python.org/3/library/tkinter.html)

## License
This project is licensed under the MIT License. See the LICENSE file for details.

