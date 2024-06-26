# Simple Dictionary Application

This is a simple web-based dictionary application that allows users to look up definitions of English words. The application fetches data from the Dictionary API and displays the word's part of speech, phonetic transcription, definition, and an example sentence if available.

## Table of Contents

1. [Features](#features)
2. [Installation](#installation)
3. [Usage](#usage)
4. [Files](#files)


## Features

- Search for English word definitions
- Display part of speech and phonetic transcription
- Show definitions and example sentences
- User-friendly interface with a responsive design

## Installation

To set up the dictionary application, follow these steps:

1. **Clone the repository:**

   ```bash
   git clone https://github.com/yourusername/simple-dictionary.git
   ```

2. **Navigate to the project directory:**

   ```bash
   cd simple-dictionary
   ```

3. **Open `index.html` in your web browser:**

   You can open the file directly or use a local server.

## Usage

1. Open `index.html` in a web browser.
2. Type a word in the input box.
3. Click the "Search" button.
4. The definition, part of speech, phonetic transcription, and an example sentence (if available) will be displayed below the search box.

## Files

### `index.html`

This file contains the structure of the web page, including:

- Input field for word search
- Search button
- Area to display results

### `style.css`

This file contains the styles for the application, including:

- Container styling
- Input field and button styling
- Result display styling

### `script.js`

This file contains the JavaScript code to handle:

- Fetching data from the Dictionary API
- Displaying the results in the defined HTML structure
- Handling errors if the word is not found

## Code Explanation

### HTML (`index.html`)

- The main container includes a search box with an input field and a search button.
- The `result` div is where the fetched data will be displayed.

### JavaScript (`script.js`)

- The script listens for a click event on the search button.
- It fetches data from the Dictionary API using the input word.
- If the word is found, it displays the word's part of speech, phonetic transcription, definition, and an example.
- If the word is not found, it displays an error message.

### CSS (`style.css`)

- Styles the container for a clean and centered layout.
- Styles the input and button for better usability.
- Styles the result section for clear and readable output.

---

Feel free to contribute to this project by creating pull requests or reporting issues. Enjoy using the simple dictionary application!