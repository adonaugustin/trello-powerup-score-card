Card Score Power-Up for Trello



This Trello Power-Up provides a simple, visual way to assign and track scores (e.g., Priority, Effort, Risk) directly on Trello cards using custom badges and a dedicated section on the card back.

✨ Features
Card Badges: Displays the assigned score (Low, Medium, or High) directly on the card face for quick identification.

Color-Coded Status: Scores are automatically color-coded for visual prioritization:

🟢 Low (Green)

🟡 Medium (Yellow)

🔴 High (Red/Orange)

Card Button: A dedicated "Set Score" button on the card back opens a simple selection pop-up.

Card Back Section: A persistent section on the card details view displays the current score.

Data Persistence: Scores are stored using the Power-Up's shared data storage, meaning the score is available to all users on the board.

🛠️ Installation and Setup
This Power-Up requires hosting and registration with Trello's Power-Up administration panel.

Prerequisites
A server or simple static hosting (e.g., GitHub Pages, Netlify) for your Power-Up files.

A Trello account.

Steps
Host the Files: Ensure the following files are hosted and publicly accessible:

index.html (The main entry point)

popup.html (The interface for setting the score)

section.html (The content for the card back section)

Register the Power-Up:

Go to the Trello Power-Up Administration.

Click "Create New Power-Up."

Set the IFrame Connector URL (https://majestic-gaufre-d33697.netlify.app/) to the URL where your index.html is hosted.

Enable Capabilities: The index.html file automatically registers the necessary capabilities (card-buttons, card-badges, card-detail-badges, card-back-section).

⚙️ Power-Up Capabilities Explained
The core logic is contained within the index.html file.
