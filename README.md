# OpenLeads - Lead Scraper Open Source Project

## Overview

Welcome to the Lead Scraper Open Source Project! This project aims to develop a robust lead scraping tool that integrates a Chrome Extension with a server-side crawler to find and aggregate lead data from websites. By leveraging the power of OpenAI's API, our tool will summarize and present the data in a user-friendly dashboard, similar to platforms like [Ocean.io](https://ocean.io), [Apollo.io](https://apollo.io), and [StoreLeads](https://storeleads.com).

## Features

- **Chrome Extension**: Easily scrape lead data while browsing websites.
- **Server-Side Crawler**: Efficiently crawl websites to gather comprehensive lead data.
- **OpenAI API Integration**: Utilize OpenAI to process and summarize lead data.
- **Dashboard**: View and manage your leads in an intuitive dashboard built with NuxtJs.

## Tech Stack

- **Frontend**: NuxtJs
- **Browser Extension**: Chrome Extension
- **Backend**: Node.js with Express (or similar framework)
- **AI Integration**: OpenAI API

## Getting Started

### Prerequisites

- Node.js and npm installed
- Google Chrome browser
- OpenAI API key

## Installation

### Install dependencies for the server and frontend

```bash
npm install
```

### Set up the Chrome Extension

- Navigate to `chrome-extension` directory.
- Open Chrome and go to `chrome://extensions/`.
- Enable "Developer mode" and click on "Load unpacked".
- Select the `chrome-extension` directory.

### Configure the environment variables

Create a `.env` file in the `server` directory and add your OpenAI API key:

```env
OPENAI_API_KEY=your_openai_api_key
```

### Run the NuxtJs frontend

```bash
npm run dev
```

## Usage

- **Using the Chrome Extension**: While browsing, click on the extension icon to scrape lead data from the current website.
- **Viewing Leads**: Access the dashboard via the NuxtJs frontend to view and manage your leads.

## Contributing

We welcome contributions from the community! Here’s how you can help:

- **Report bugs and suggest features**: Use the [issue tracker](https://github.com/codextde/openleads/issues).
- **Contribute code**: Fork the repository and submit a pull request.
- **Improve documentation**: Help us improve and expand our documentation.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact

For any questions or feedback, please reach out via the [GitHub Issues](https://github.com/codextde/openleads/issues).

We hope you find this tool useful and look forward to your contributions!
