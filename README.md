# Markdown to HTML Converter

This Python script allows you to convert Markdown files into HTML format effortlessly. It's a handy tool for quickly transforming your Markdown documents into HTML, saving you time and manual effort.

## Usage

1. Clone this repository or download the `markdown2html.py` script.
2. Open a terminal window and navigate to the directory containing the script.
3. Run the script using the command:

   ```
   python3 markdown2html.py input_file.md output_file.html
   ```

   Replace `input_file.md` with the path to your Markdown file and `output_file.html` with the desired name for the generated HTML file.

## Features

- Converts Markdown headings to HTML heading tags (`<h1>`, `<h2>`, etc.).
- Handles unordered lists (`- item`) and ordered lists (`* item`).
- Converts bold and italic text using `**` and `__` symbols.
- Replaces content enclosed in `[[...]]` with MD5 hashes.
- Removes the letter 'c' (uppercase and lowercase) from content enclosed in `((...))`.

## Dependencies

This script does not require any external libraries or dependencies. It is written in Python and utilizes regular expressions for pattern matching and replacement.

## Example

For instance, if you have a Markdown file named `document.md`, you can convert it to HTML by running:

```
python3 markdown2html.py document.md output.html
```

The resulting HTML file, `output.html`, will contain the formatted content from the Markdown file.

## Contribution

Feel free to contribute to this project by suggesting improvements, reporting issues, or submitting pull requests. Your input is highly appreciated!
