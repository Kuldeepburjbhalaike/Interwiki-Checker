# Interwiki Checker (En ↔ Pa)

A lightweight, browser-based tool designed to help Wikimedians check for interlanguage links between English and Punjabi Wikipedia. It supports bidirectional checking for both articles and categories.

[**Tool Link**](https://kuldeepburjbhalaike.github.io/Interwiki-Checker/)

## 🚀 Features

* **Bidirectional Checking:** Toggle easily between **English → Punjabi** and **Punjabi → English**.
* **Unified Input:** Check **Articles** and **Categories** in the same list.
* **Smart Search:**
    * **Auto-Capitalization:** Automatically fixes input case (e.g., `history of india` → `History of India`).
    * **Redirects:** Follows Wikipedia redirects to find the correct title automatically.
* **Bulk Checking:** Accepts a large list of titles (one per line).
* **Visual & Raw Output:**
    * **Table:** Shows side-by-side comparisons with direct links to the target pages.
    * **Copy Box:** Generates a ready-to-paste list of Wikilinks (e.g., `[[ਸ਼੍ਰੇਣੀ:ਇਤਿਹਾਸ]]` or `[[History of Punjab]]`).
* **Dark Mode:** Features a modern "Slate Blue" dark mode that syncs with your system preferences.
* **No Server Required:** Runs entirely in the browser using the MediaWiki API.

## 🛠️ How to Use

1.  Open the tool.
2.  **Select Direction:** Choose "English → Punjabi" or "Punjabi → English".
3.  Paste a list of titles into the input box.
    * **For Articles:** Just type the title (e.g., `History of Punjab`).
    * **For Categories:** Add the prefix (e.g., `Category:Sikhism` or `ਸ਼੍ਰੇਣੀ:ਸਿੱਖ ਧਰਮ`).
4.  Click **"Check Availability"**.
5.  The tool will fetch data from the respective Wikipedia API.
6.  Copy the results from the "Found..." box or use the table to verify links.

## 📦 Installation / Hosting

You can host this tool for free using **GitHub Pages**.

1.  **Fork** this repository or create a new one.
2.  Add the `index.html` file containing the source code.
3.  Go to your repository **Settings** → **Pages**.
4.  Under **"Build and deployment"**, set the **Source** to `Deploy from a branch`.
5.  Select `main` (or `master`) as the branch and click **Save**.
6.  Wait a minute, and GitHub will provide your live URL.

## 💻 Tech Stack

* **HTML5 & CSS3** (Responsive, Dark Mode variables)
* **JavaScript** (Fetch API, Async/Await)
* **API:** [MediaWiki Action API](https://www.mediawiki.org/wiki/API:Main_page) (Dynamic endpoint switching between `en` and `pa`)

## 🤝 Contributing

Contributions are welcome! If you find a bug or want to add support for another language, feel free to open an issue or submit a pull request.

1.  Fork the Project
2.  Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3.  Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4.  Push to the Branch (`git push origin feature/AmazingFeature`)
5.  Open a Pull Request

## 📄 License

Distributed under the MIT License. See `LICENSE` for more information.

---
Made with ❤️ by [Kuldeep](https://meta.wikimedia.org/wiki/User:Kuldeepburjbhalaike)
