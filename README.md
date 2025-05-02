## 📍 Regions and Cities Explorer
A simple React project to explore regions, their cities, and city-specific details.

## ✨ Features
🗺️ Browse a list of Regions on the Home page.
🏙️ View a list of Cities within a selected Region.
📄 Access a City Detail Page with information about a selected City.
🔎 Search for cities within a region.
🌟 Highlight the active region on city pages.
📱 Responsive design for desktop and mobile screens.

## 🚀 Project Structure
src/
├── components/
│   ├── DraggableScrollContainer.css
│   ├── DraggableScrollContainer.jsx
│   ├── FetchData.jsx
│   ├── Footer.jsx
│   ├── Layout.css
│   ├── Layout.jsx
├── pages/
│   ├── CityDetailPage.css
│   ├── CityDetailPage.jsx
│   ├── CityPage.css
│   ├── CityPage.jsx
│   ├── HomePage.css
│   ├── HomePage.jsx
│   ├── Regions.css
│   ├── Regions.jsx
├── data/
│   ├── regionsData.json
├── App.jsx
├── index.css
├── index.jsx

Regions: Displays all regions.
CityPage: Displays cities under a selected region + searchable list.
CityDetailPage: Shows details for a specific city.

## 🛠️ Technologies Used
React
React Router (react-router-dom)
Plain CSS

## ⚡ How it Works
1. Home Page
→ Lists all regions.
→ Clicking a region navigates to its cities.

2. City Page
→ Displays all cities in the selected region.
→ Includes a search bar.
→ Highlights the active region in the UI.

3. City Detail Page
→ Shows specific information about the clicked city.

4. Footer
→ Always visible, and shows the regions list on Home Page.