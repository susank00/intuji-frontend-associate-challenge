# Intuji Frontend Associate Challenge - Finance Dashboard

This repository contains my solution for the **Intuji Frontend Associate Challenge**. The task was to create an interactive **Finance Dashboard** based on a Figma design, using HTML, CSS, and optionally JavaScript. The project focuses on replicating the "Home" screen design, ensuring proper HTML/CSS structure, semantic tags, clear naming conventions, and responsiveness.

## Features

- **Sidebar Navigation**: A responsive sidebar with icons and navigation links (Dashboard, Schedule, Message, Analytics, Team, Profile, Settings, Help, Logout).
- **Header**: Includes a search bar, user profile, and notification/message icons.
- **Overview Section**: Displays cards for Balance, Saving, Expenses, and Incomes with icons, percentages, and links to details.
- **Saving Plan Section**: Shows saving goals (e.g., Bali Vacation, New Gadget, Charity) with progress bars.
- **Analytics Section**: Placeholder for a chart with a dropdown for time filtering (Weekly, Last Week, Today).
- **Recent Transactions Section**: Lists recent transactions (e.g., Figma, YouTube, Spotify, Freepik) with amounts and status.

## 🛠️ Tech Stack

- **HTML**: Structured with semantic tags for accessibility and clarity.
- **CSS**: Styled to match the Figma design, with a focus on proper class naming and shorthand properties.
- **JavaScript**: Includes Chart.js for potential chart integration (not fully implemented in this version).
- **Font**: Uses "Plus Jakarta Sans" as specified in the design.

## 🏗️ Project Structure

```
├── index.html         # Main HTML file for the Finance Dashboard
├── css/
│   └── style.css # CSS styles for the dashboard
│   └── mobilesidebar.css.css # CSS styles for the dashboard

├── js/
│   └── mobilesidebar.js      # JavaScript to toggles the sidebar and overlay visibility when the hamburger icon is clicked, and closes them when the overlay is clicked.
└── assets/            # Images and icons used in the design (assumed placeholder paths)
│   └── fonts          # Uses "Plus Jakarta Sans" as specified in the design.
```
## 🚀 Getting Started
Clone the Repository:
```bash
git clone https://github.com/susank00/intuji-frontend-associate-challenge.git
Navigate to the Project Directory:
cd intuji-frontend-associate-challenge
```
**Open the Project:**
Open index.html in a web browser to view the dashboard locally.
Alternatively, use a local server (e.g., via VS Code Live Server) for better testing.
