Openverse
Openverse is a platform that enables users to search for openly licensed media. The project is built with accessibility, extensibility, and community contributions in mind.

Features
Search: Explore a vast collection of openly licensed content.
Filter: Refine search results based on license type, content category, and more.
Preview: View details of content before downloading.
Localization: Support for multiple languages, making Openverse accessible to a global audience.
Recent Contributions
Localization Support (Added by Contributor)
We have added Spanish language support to make Openverse accessible to Spanish-speaking users.
Localization now allows users to switch between supported languages through a dropdown menu in the application header.

What’s New?
Language Files: Added src/locales/es.json for Spanish translations.
Locale Integration: Updated src/config/localization.js to include Spanish as a supported language.
Language Selector: Introduced a dropdown menu in the application header for language selection.
Getting Started
Prerequisites
Ensure you have the following installed:

Node.js (>= 14.x)
Yarn (preferred) or npm
Installation
Clone the repository:

bash
Copy
Edit
git clone https://github.com/WordPress/openverse.git
cd openverse
Install dependencies:

bash
Copy
Edit
yarn install
Start the development server:

bash
Copy
Edit
yarn start
Adding Localization
If you want to add support for more languages:

Add a language file in the src/locales directory (e.g., fr.json for French).
Update the supportedLocales in src/config/localization.js.
Test your changes by running the development server.
Contributing
We welcome contributions from the community! Here’s how you can get involved:

Fork the repository.
Create a new branch for your changes:
bash
Copy
Edit
git checkout -b feature/localization-support
Make your changes and commit them:
bash
Copy
Edit
git commit -m "Add support for [language]"
Push your branch:
bash
Copy
Edit
git push origin feature/localization-support
Open a pull request on the main repository.
Acknowledgments
This project is maintained by the WordPress Openverse team and supported by contributions from the global community.

Would you like me to refine or expand any part of this file further?
