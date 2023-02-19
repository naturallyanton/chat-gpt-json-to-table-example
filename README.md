# Using ChatGPT to generate a table of design tokens from a JSON file

This example shows how ChatGPT was used to generate a table from JSON data, using natural language to adjust the formatting and the presentation.

The example JSON file contains design tokens (key/value pairs representing colors) and was exported with [Tokens Studio for Figma](https://tokens.studio).

Three prompts were used:
- `Group colours, like gray.100, gray.200... using the parent "gray" in bold as a heading`
- `Remove the type column`
- `Add an "Example" column with 30px squares, with the color as background and in a format compatible with a GitHub README file`

The examples were generated with the prompt "[...] using a format compatible with a README file for GitHub". The `placeholder.com` service wasn't specified.

## Result

| Key       | Value     | Example      |
| --------- | --------- | ------------ |
| black     | #000000   | ![#000000](https://via.placeholder.com/30x30/000000/000000?text=+) |
| white     | #ffffff   | ![#ffffff](https://via.placeholder.com/30x30/ffffff/000000?text=+) |
| **gray**  |           |              |
| gray.100  | #f7fafc   | ![#f7fafc](https://via.placeholder.com/30x30/f7fafc/000000?text=+) |
| gray.200  | #edf2f7   | ![#edf2f7](https://via.placeholder.com/30x30/edf2f7/000000?text=+) |
| gray.300  | #e2e8f0   | ![#e2e8f0](https://via.placeholder.com/30x30/e2e8f0/000000?text=+) |
| gray.400  | #cbd5e0   | ![#cbd5e0](https://via.placeholder.com/30x30/cbd5e0/000000?text=+) |
| gray.500  | #a0aec0   | ![#a0aec0](https://via.placeholder.com/30x30/a0aec0/000000?text=+) |
| gray.600  | #718096   | ![#718096](https://via.placeholder.com/30x30/718096/000000?text=+) |
| gray.700  | #4a5568   | ![#4a5568](https://via.placeholder.com/30x30/4a5568/000000?text=+) |
| gray.800  | #2d3748   | ![#2d3748](https://via.placeholder.com/30x30/2d3748/000000?text=+) |
| gray.900  | #1a202c   | ![#1a202c](https://via.placeholder.com/30x30/1a202c/ffffff?text=+) |
| **pink**  |           |              |
| pink.100  | #fff5f7   | ![#fff5f7](https://via.placeholder.com/30x30/fff5f7/000000?text=+) |
| pink.200  | #fed7e2   | ![#fed7e2](https://via.placeholder.com/30x30/fed7e2/000000?text=+) |
| pink.300  | #fbb6ce   | ![#fbb6ce](https://via.placeholder.com/30x30/fbb6ce/000000?text=+) |
| pink.400  | #f687b3   | ![#f687b3](https://via.placeholder.com/30x30/f687b3/000000?text=+) |
| pink.500  | #ed64a6   | ![#ed64a6](https://via.placeholder.com/30x30/ed64a6/000000?text=+) |
| pink.600  | #d53f8c   | ![#d53f8c](https://via.placeholder.com/30x30/d53f8c/000000?text=+) |
| pink.700  | #b83280   | ![#b83280](https://via.placeholder.com/30x30/b83280/000000?text=+) |
| pink.800  | #97266d   | ![#97266d](https://via.placeholder.com/30x30/97266d/000000?text=+) |
| pink.900  | #702459   | ![#702459](https://via.placeholder.com/30x30/702459/000000?text=+) |
