# AI Proxy GitHub Page

This project is a simple GitHub Page that acts as a proxy for an AI API. It allows users to interact with an AI using their own API key.

## Features

- Input and local storage of the API key
- Chat interface for interaction with the AI
- Uses the OpenAI GPT-3.5 Turbo API (can be easily adapted to other APIs)

## Usage

1. Visit the GitHub Page: `https://[YourUsername].github.io/[RepositoryName]`
2. Enter your API key and save it.
3. Start chatting with the AI by entering messages in the input field.

## Installation

To set up this project locally or create your own version:

1. Clone this repository:
   ```
   git clone https://github.com/[YourUsername]/[RepositoryName].git
   ```
2. Navigate to the project directory:
   ```
   cd [RepositoryName]
   ```
3. Open `index.html` in a web browser to test the page locally.

## Customization

You can customize the page by editing the `index.html` file:

- Change the design by modifying the CSS in the `<style>` section.
- Modify the JavaScript functions to change the behavior of the page.
- Adjust the API request to use a different AI API.

## Security Note

This implementation is intended for demonstration purposes only and is not suitable for production use. The API key is stored in the browser's storage, which is not secure. For a secure application, you should manage the API key server-side.

## Contributing

Contributions to this project are welcome! Please fork the repository and submit a pull request with your changes.

## License

This project is licensed under the MIT License. See the `LICENSE` file for more information.
