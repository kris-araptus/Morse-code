# Morse Code Converter

This Python script converts a given paragraph of text into Morse code. It uses a predefined dictionary to map each character to its corresponding Morse code representation.

## Features

- Converts letters, digits, and a selection of special characters to Morse code.
- Handles both uppercase and lowercase input by converting all text to uppercase.
- Represents spaces in the original text with a slash (`/`) in Morse code.

## Usage

1. Clone or download this repository.
2. Ensure you have Python installed on your system.
3. Run the script and enter a paragraph of text when prompted.

## Example

### Input

Hello, World!


### Output

.... . .-.. .-.. --- --..-- / .-- --- .-. .-.. -.. -.-.--


## Morse Code Dictionary

The script uses the following Morse code mappings:

| Character | Morse Code | Character | Morse Code |
|-----------|------------|-----------|------------|
| A         | .-         | N         | -.         |
| B         | -...       | O         | ---        |
| C         | -.-.       | P         | .--.       |
| D         | -..        | Q         | --.-       |
| E         | .          | R         | .-.        |
| F         | ..-.       | S         | ...        |
| G         | --.        | T         | -          |
| H         | ....       | U         | ..-        |
| I         | ..         | V         | ...-       |
| J         | .---       | W         | .--        |
| K         | -.-        | X         | -..-       |
| L         | .-..       | Y         | -.--       |
| M         | --         | Z         | --..       |
| 0         | -----      | 5         | .....      |
| 1         | .----      | 6         | -....      |
| 2         | ..---      | 7         | --...      |
| 3         | ...--      | 8         | ---..      |
| 4         | ....-      | 9         | ----.      |
| ,         | --..--     | :         | ---...     |
| .         | .-.-.-     | ;         | -.-.-.     |
| ?         | ..--..     | =         | -...-      |
| /         | -..-.      | +         | .-.-.      |
| -         | -....-     | _         | ..--.-     |
| (         | -.--.      | "         | .-..-.     |
| )         | -.--.-     | $         | ...-..-    |
| &         | .-...      | !         | -.-.--     |
| @         | .--.-.     | Space     | /          |

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/morse-code-converter.git
    ```
2. Navigate to the project directory:
    ```bash
    cd morse-code-converter
    ```

## Running the Script

1. Ensure you have Python installed on your system.
2. Run the script:
    ```bash
    python morse_code_converter.py
    ```
3. Enter a paragraph of text when prompted.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- The Morse code dictionary was sourced from various online references.
