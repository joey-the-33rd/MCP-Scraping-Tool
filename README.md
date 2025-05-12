# MCP Scraping Tool

## Project Background

The MCP Scraping Tool is an advanced scraping utility that integrates AI language models to enhance data extraction and processing capabilities. Leveraging the MCP (Multi-Channel Processing) framework and Langchain adapters, it enables complex question answering by orchestrating multiple tools in sequence. The project features a command-line chat interface powered by the Claude 3.5 model from Anthropic, allowing users to interactively query and receive intelligent responses based on the scraped data and tool outputs. This combination of AI and scraping technologies makes it a powerful tool for sophisticated data retrieval and analysis tasks.

## Installation

1. Ensure you have Python 3.13 or higher installed.
2. Clone the repository:
   ```
   git clone <repository-url>
   cd MCP-Scraping-Tool
   ```
3. Install dependencies:
   ```
   pip install -r requirements.txt
   ```
   or if using poetry or pipenv, use the appropriate command to install from `pyproject.toml`.
   Alternatively, you can install the dependencies using `uv`:
   ```
   uv install
   ```

4. Set up environment variables by creating a `.env` file in the project root with the following keys:
   ```
   API_TOKEN=your_api_token_here
   BROWSER_AUTH=your_browser_auth_here
   WEB_UNLOCKER_ZONE=your_web_unlocker_zone_here
   ```

## Usage

Run the main chat interface script:

```
python main.py
```

You will be prompted to enter your queries. Type your questions and receive intelligent responses powered by the AI agent. To exit, type `exit` or `quit`.

## Dependencies

- Python 3.13+
- anthropic
- langchain
- python-dotenv
- langgraph
- langchain-mcp-adapters
- langchain-anthropic

## Contributing

Contributions are welcome! Please open issues or submit pull requests for improvements or bug fixes.

## License

[Add your license here]
