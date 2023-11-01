# Todo2Notion

**Todo2Notion** is a Node.js script that fetches tasks from the Todoist API and creates corresponding pages in a Notion database, helping you keep your tasks organized in Notion.

## Table of Contents
- [Prerequisites](#Prerequisites)
- [Installation](#Installation)
- [Usage](#Usage)
- [Configuration](#Configuration)
- [Contributing](#Contributing)
- [License](#License)

## Prerequisites
Before using **Todo2Notion**, make sure you have the following prerequisites:

- [Node.js](https://nodejs.org/en) installed
- A Todoist API key
- A Notion API key
- A Notion database ID


## Installation
1. Clone the repository or download the code.
2. Navigate to the project directory using the terminal.
3. Install the project's dependencies by running:
```
npm install
```

## Usage
To use **Todo2Notion**, follow these steps:

1. Set your Todoist API key, Notion API key, and Notion database ID as environment variables:
```
export NOTION_KEY=your-notion-api-key
export NOTION_DATABASE_ID=your-notion-database-id
export TODOIST_API_KEY=your-todoist-api-key
```
2. Run the script:
```
node index.js
```
The script will fetch tasks from Todoist and create corresponding pages in a Notion database based on the configuration provided.

## Configuration
The project uses environment variables for configuration. Here are the variables you need to set:

- **NOTION_KEY**: Your Notion API key.
- **NOTION_DATABASE_ID**: The ID of the Notion database where you want to create pages.
- **TODOIST_API_KEY**: Your Todoist API key.

You can set these environment variables in a .env file or through your system's environment variable settings as shown above.

## Contributing
Contributions to this project are welcome. If you'd like to contribute, please follow these guidelines:

1. Fork the repository.
2. Create a new branch for your feature or fix.
3. Make your changes.
4. Test your changes.
5. Submit a pull request.

## License
This project is licensed under the MIT License.
