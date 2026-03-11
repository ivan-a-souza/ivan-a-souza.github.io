# Portfolio — Ivan Augusto Xavier Souza

A minimalist, premium portfolio website built with vanilla web technologies. It dynamically fetches data from the GitHub API and supports multiple languages.

## ✨ Features

- 🌓 **Dark/Light Mode**: Elegant theme switching with local storage persistence.
- 🌍 **Multi-language Support**: Full support for English and Portuguese, including browser language detection.
- 📊 **Dynamic GitHub Sync**: Fetches profile data, repository lists, and star counts directly from GitHub.
- 📱 **Fully Responsive**: Optimized for all devices with a premium minimalist aesthetic.
- ⚡ **Performance Optimized**: Zero dependencies, vanilla JS/CSS for lightning-fast loads.

## 🛠️ Stack

- **Core**: HTML5, Vanilla CSS3, Vanilla JavaScript (ES6+)
- **Integration**: GitHub REST API
- **Fonts**: Inter (via Google Fonts)

## 🚀 Local Development

Since the site uses `fetch` for GitHub data and `localStorage`, it's best to run it through a local server.

1. Clone the repository:

   ```bash
   git clone https://github.com/ivan-a-souza/ivan-a-souza.github.io.git
   cd ivan-a-souza.github.io
   ```

2. Run a local server (e.g., using `http-server` or VS Code Live Server):

   ```bash
   npx http-server .
   ```

3. Open your browser at `http://localhost:8080`.

## ⚙️ Configuration

The main logic is contained within `index.html`. To adapt this for another user:

1. Change the `USER` constant in the script section (line ~499).
2. Update the static labels and text in the `trans` object.
3. Update specific social links (LinkedIn, Twitter, etc.) in the HTML structure.

## 📄 License

© 2025 Ivan Augusto Xavier Souza. All rights reserved.
