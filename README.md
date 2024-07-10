# Interactive DOM Visualizer

A dynamic DOM Visualizer application that provides a visual representation of the DOM tree structure from HTML input. Paste your HTML into the input area and see an interactive tree representation of your DOM structure.

## Features

- **Interactive Visualization**: Visualize the DOM tree structure from HTML input.
- **Zoom and Pan**: Easily navigate through the DOM tree with zoom and pan functionality.
- **Error Handling**: Displays error messages for invalid HTML input.
- **Responsive Design**: Adjusts the visualization based on the window size.

## Technologies Used

- **HTML**: Structure of the application.
- **CSS**: Styling for the application.
- **JavaScript**: Interactivity and DOM manipulation.
- **D3.js**: Visualization library used for rendering the DOM tree.

## Getting Started

### Prerequisites

To run this application, you need a modern web browser with JavaScript enabled.

### Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/yourusername/dom-visualizer.git
    ```
2. Navigate to the project directory:
    ```sh
    cd dom-visualizer
    ```
3. Open the `index.html` file in your web browser.

### Usage

1. Open the application in your web browser.
2. Paste your HTML code into the input area provided.
3. The DOM tree structure will be visualized in the SVG canvas below the input area.

### Example

```html
<div class="container">
    <p>Hello</p>
    <p class="highlight">World</p>
</div>
```

## Development

### File Structure

- `index.html`: The main HTML file containing the structure of the application.
- `style.css`: The CSS file for styling the application.
- `script.js`: The JavaScript file containing the logic for rendering the DOM tree.

### Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository.
2. Create a new branch:
    ```sh
    git checkout -b feature/your-feature
    ```
3. Make your changes.
4. Commit your changes:
    ```sh
    git commit -m 'Add your feature'
    ```
5. Push to the branch:
    ```sh
    git push origin feature/your-feature
    ```
6. Open a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgements

- [D3.js](https://d3js.org/) for the powerful visualization library.
- [Fathom Analytics](https://usefathom.com/) for the simple website analytics.

## Contact

For any questions or suggestions, please open an issue.
